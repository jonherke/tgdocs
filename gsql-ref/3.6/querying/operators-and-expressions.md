![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions)[Next](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions)
TigerGraph Savanna
[TigerGraph Savanna](https://docs.tigergraph.com/savanna/main/overview/) [(_TigerGraph Cloud Classic_)](https://docs.tigergraph.com/cloud/main/start/overview)
TigerGraph Server
[TigerGraph DB](https://docs.tigergraph.com/tigergraph-server/4.2/intro/)
TigerGraph Suite
[GraphStudio and Admin Portal](https://docs.tigergraph.com/gui/4.2/intro/) [Insights](https://docs.tigergraph.com/insights/4.2/intro/) [GSQL Web Shell](https://docs.tigergraph.com/tigergraph-server/current/gsql-shell/web)
Query Languages
[GSQL Language Reference](https://docs.tigergraph.com/gsql-ref/4.2/intro/) [GSQL Web Shell](https://docs.tigergraph.com/tigergraph-server/current/gsql-shell/web) [OpenCypher](https://docs.tigergraph.com/gsql-ref/current/opencypher-in-gsql)
AI & Graph Intelligence
[Graph Data Science Library](https://docs.tigergraph.com/graph-ml/3.10/intro/) [Hybrid Graph+Vector Search](https://docs.tigergraph.com/gsql-ref/current/vector/)
Connectors and APIs
[Data Connectors](https://docs.tigergraph.com/tigergraph-server/current/data-loading) [pyTigerGraph](https://docs.tigergraph.com/pytigergraph/1.8/intro/) [TigerGraph GraphQL Service](https://docs.tigergraph.com/graphql/3.9/) [JDBC Driver](https://github.com/tigergraph/ecosys/tree/master/tools/etl/tg-jdbc-driver)
Legacy Documentation
[ Legacy Documentation ](https://docs-legacy.tigergraph.com)
[Resources](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions)
[Developer Site](https://dev.tigergraph.com/) [Community Forum](https://community.tigergraph.com/) [Knowledge Base](https://tigergraph.freshdesk.com/support/solutions)
[Download](https://dl.tigergraph.com)
[ TG Savanna](https://savanna.tgcloud.io)
### [GSQL Language Reference](https://docs.tigergraph.com/gsql-ref/3.6/intro/intro)
  *     * [Overview](https://docs.tigergraph.com/gsql-ref/3.6/intro/intro)
  *     * Tutorials
      * [GSQL 101](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/gsql-101/)
        * [Define a Schema](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/gsql-101/define-a-schema)
        * [Load Data](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/gsql-101/load-data-gsql-101)
        * [Run Built-in Queries](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/gsql-101/built-in-select-queries)
        * [Parameterized Queries](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/gsql-101/parameterized-gsql-query)
        * [Review](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/gsql-101/review)
      * [Pattern Matching Tutorial](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/)
        * [Prepare your Environment](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/prepare-environment)
        * [One-hop patterns](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns)
        * [Repeating a 1-Hop Pattern](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/repeating-a-pattern)
        * [Multiple Hop Patterns and Accumulation](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/multiple-hop-and-accumulation)
        * [Example - A Recommender](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/example)
        * [Advanced Features](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/adv/)
          * [Per Clause (Beta)](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/adv/per-clause)
          * [Conjunctive Pattern Matching (Beta)](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/adv/conjunctive-pattern-matching)
          * [Data Modification](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/adv/dml)
        * [Summary](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/summary)
      * [Accumulators Tutorial](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/accumulators-tutorial)
  *     * Database definition & Loading
      * [System & Language Basics](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/system-and-language-basics)
      * [Defining a Graph Schema](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/defining-a-graph-schema)
      * [Modifying a Graph Schema](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/modifying-a-graph-schema)
      * [Creating a Loading Job](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/creating-a-loading-job)
        * [Functions](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/)
          * [Token Functions for Attribute Expressions](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/)
            * [flatten()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/flatten)
            * [flatten_json_array()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/flatten_json_array)
            * [gsql_concat()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_concat)
            * [gsql_current_time_epoch()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_current_time_epoch)
            * [gsql_day()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_day)
            * [gsql_day_epoch()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_day_epoch)
            * [gsql_find()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_find)
            * [gsql_length()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_length)
            * [gsql_lower()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_lower)
            * [gsql_ltrim()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_ltrim)
            * [gsql_month()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_month)
            * [gsql_month_epoch()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_month_epoch)
            * [gsql_regex_match()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_regex_match)
            * [gsql_regex_replace()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_regex_replace)
            * [gsql_reverse()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_reverse)
            * [gsql_rtrim()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_rtrim)
            * [gsql_substring()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_substring)
            * [gsql_to_bool()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_to_bool)
            * [gsql_to_int()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_to_int)
            * [gsql_to_uint()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_to_uint)
            * [gsql_trim()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_trim)
            * [gsql_ts_to_epoch_seconds()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_ts_to_epoch)
            * [gsql_upper()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_upper)
            * [gsql_uuid_v4()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_uuid_v4)
            * [gsql_year()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_year)
            * [gsql_year_epoch()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_year_epoch)
            * [split()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/split)
          * [Token Functions in WHERE Clause](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token_where/)
            * [concat()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token_where/concat)
            * [gsql_is_false()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token_where/gsql_is_false)
            * [gsql_is_not_empty()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token_where/gsql_is_not_empty)
            * [gsql_is_true()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token_where/gsql_is_true)
            * [gsql_token_equal()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token_where/gsql_token_equal)
            * [gsql_token_ignore_case_equal()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token_where/gsql_token_ignore_case_equal)
            * [to_float()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token_where/to_float)
            * [to_int()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token_where/to_int)
            * [token_len()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token_where/token_len)
          * [Reducer functions](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/reducer/)
            * [add()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/reducer/add)
            * [and()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/reducer/and)
            * [ignore_if_exists()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/reducer/ignore_if_exists)
            * [max()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/reducer/max)
            * [min()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/reducer/min)
            * [or()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/reducer/or)
        * [Add a User-defined Token Function](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/add-token-function)
      * [Running a Loading Job](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job)
  *     * Querying
      * [Introduction](https://docs.tigergraph.com/gsql-ref/3.6/querying/)
      * [Query Language Syntax Versions](https://docs.tigergraph.com/gsql-ref/3.6/querying/syntax-versions)
      * [Queries](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations)
      * [Distributed Query Mode](https://docs.tigergraph.com/gsql-ref/3.6/querying/distributed-query-mode)
      * [Data Types](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types)
      * [Accumulators](https://docs.tigergraph.com/gsql-ref/3.6/querying/accumulators)
      * [Operators and Expressions](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions)
      * [Functions](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/)
        * [Aggregation Functions](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/aggregation-functions)
        * [Datetime Functions](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/datetime-functions)
        * [Edge Methods](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/edge-methods)
        * [JSON Object Methods](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/json-object-methods)
        * [JSON Array Methods](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/jsonarray-methods)
        * [Mathematical Functions](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions)
        * [Miscellaneous Functions](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions)
        * [Query User-Defined Functions](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/query-user-defined-functions)
        * [String Functions](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/string-functions)
        * [Type Conversion Functions](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/type-conversion-functions)
        * [Vertex Functions](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods)
      * [Declaration and Assignment Statements](https://docs.tigergraph.com/gsql-ref/3.6/querying/declaration-and-assignment-statements)
      * [SELECT Statement](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/)
        * [SELECT Statement (Syntax V1)](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/select-statement-v1)
        * [SQL-like SELECT statement](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/sql-like-select-statement)
      * [Control Flow Statements](https://docs.tigergraph.com/gsql-ref/3.6/querying/control-flow-statements)
      * [Data Modification Statements](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-modification-statements)
      * [Output Statements and FILE Objects](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects)
      * [Exception Statements](https://docs.tigergraph.com/gsql-ref/3.6/querying/exception-statements)
      * [Comments](https://docs.tigergraph.com/gsql-ref/3.6/querying/comments)
  *     * Appendix
      * [GSQL Style Guide](https://docs.tigergraph.com/gsql-ref/3.6/appendix/gsql-style-guide)
      * [DDL Keywords & Reserved Words](https://docs.tigergraph.com/gsql-ref/3.6/appendix/keywords-and-reserved-words)
      * [Query Language Keywords & Reserved Words](https://docs.tigergraph.com/gsql-ref/3.6/appendix/query-language-reserved-words)
      * [Formal Grammar for Query Language](https://docs.tigergraph.com/gsql-ref/3.6/appendix/complete-formal-syntax)
      * [Interpreted GSQL Limitations](https://docs.tigergraph.com/gsql-ref/3.6/appendix/interpreted-gsql-limitations)
      * [GSQL Start-to-End Process and Data Flow](https://docs.tigergraph.com/gsql-ref/3.6/appendix/gsql-start-to-end-process)
      * [Example Graphs](https://docs.tigergraph.com/gsql-ref/3.6/appendix/example-graphs)
      * [Common Errors and Problems](https://docs.tigergraph.com/gsql-ref/3.6/appendix/common-errors-and-problems)


GSQL Language Reference 3.6
[Fully-Managed: Savanna](https://docs.tigergraph.com/savanna/main/overview/)
[Self-Managed: TigerGraph DB](https://docs.tigergraph.com/tigergraph-server/4.2/intro/)
[Install](https://docs.tigergraph.com/tigergraph-server/current/getting-started/) [Manage](https://docs.tigergraph.com/tigergraph-server/current/system-management/)
Tutorials & Guides
[GSQL](https://github.com/tigergraph/ecosys/blob/master/tutorials/GSQL.md) [OpenCypher in GSQL](https://github.com/tigergraph/ecosys/blob/master/tutorials/Cypher.md) [Hybrid Vector Search](https://github.com/tigergraph/ecosys/blob/master/tutorials/VectorSearch.md)
Reference Manuals
[GSQL](https://docs.tigergraph.com/gsql-ref/4.2/intro/) [OpenCypher](https://docs.tigergraph.com/gsql-ref/current/opencypher-in-gsql/) [Vector](https://docs.tigergraph.com/gsql-ref/current/vector/) [REST APIs](https://docs.tigergraph.com/tigergraph-server/current/api/) [Configuration Parameters](https://docs.tigergraph.com/tigergraph-server/current/reference/configuration-parameters)
Visual Tools
[Develop: GraphStudio](https://docs.tigergraph.com/gui/4.2/intro/) [Administer: Admin Portal](https://docs.tigergraph.com/gui/4.2/intro/) [Visualize: Insights](https://docs.tigergraph.com/insights/4.2/intro/)
AI & Data Science
[Graph Algorithms](https://docs.tigergraph.com/graph-ml/3.10/intro/) [pyTigerGraph](https://docs.tigergraph.com/pytigergraph/1.8/intro/) [TigerGraphX](https://github.com/tigergraph/ecosys/blob/master/tutorials/TigerGraphX.md) [ML Workbench](https://docs.tigergraph.com/ml-workbench/1.4/intro/) [CoPilot](https://docs.tigergraph.com/tg-copilot/intro/)
  * [TigerGraph DB](https://docs.tigergraph.com/tigergraph-server/4.2/intro/)
    * [4.2 Pre](https://docs.tigergraph.com/tigergraph-server/4.2/intro/)
    * [4.1](https://docs.tigergraph.com/tigergraph-server/4.1/intro/)
    * [3.11](https://docs.tigergraph.com/tigergraph-server/3.11/intro/)
    * [3.10](https://docs.tigergraph.com/tigergraph-server/3.10/intro/)
    * [3.9](https://docs.tigergraph.com/tigergraph-server/3.9/intro/)
    * [3.6](https://docs.tigergraph.com/tigergraph-server/3.6/intro/)
  * [GSQL Language Reference](https://docs.tigergraph.com/gsql-ref/4.2/intro/)
    * [4.2 Pre](https://docs.tigergraph.com/gsql-ref/4.2/intro/)
    * [4.1](https://docs.tigergraph.com/gsql-ref/4.1/intro/)
    * [3.11](https://docs.tigergraph.com/gsql-ref/3.11/intro/)
    * [3.10](https://docs.tigergraph.com/gsql-ref/3.10/intro/)
    * [3.9](https://docs.tigergraph.com/gsql-ref/3.9/intro/)
    * [3.6](https://docs.tigergraph.com/gsql-ref/3.6/intro/intro)
  * [TigerGraph Savanna](https://docs.tigergraph.com/savanna/main/overview/)
  * [GraphStudio and Admin Portal](https://docs.tigergraph.com/gui/4.2/intro/)
    * [4.2 Pre](https://docs.tigergraph.com/gui/4.2/intro/)
    * [4.1](https://docs.tigergraph.com/gui/4.1/intro/)
    * [3.11](https://docs.tigergraph.com/gui/3.11/intro/)
    * [3.10](https://docs.tigergraph.com/gui/3.10/intro/)
    * [3.9](https://docs.tigergraph.com/gui/3.9/intro/)
    * [3.6](https://docs.tigergraph.com/gui/3.6/graphstudio/overview)
  * [Insights](https://docs.tigergraph.com/insights/4.2/intro/)
    * [4.2 Pre](https://docs.tigergraph.com/insights/4.2/intro/)
    * [4.1](https://docs.tigergraph.com/insights/4.1/intro/)
    * [3.11](https://docs.tigergraph.com/insights/3.11/intro/)
    * [3.10](https://docs.tigergraph.com/insights/3.10/intro/)
    * [3.9](https://docs.tigergraph.com/insights/3.9/intro/)
  * [Graph Data Science Library](https://docs.tigergraph.com/graph-ml/3.10/intro/)
    * [3.10](https://docs.tigergraph.com/graph-ml/3.10/intro/)
  * [pyTigerGraph](https://docs.tigergraph.com/pytigergraph/1.8/intro/)
    * [1.8](https://docs.tigergraph.com/pytigergraph/1.8/intro/)
    * [1.7](https://docs.tigergraph.com/pytigergraph/1.7/intro/)
    * [1.6](https://docs.tigergraph.com/pytigergraph/1.6/intro/)
  * [TigerGraph ML Workbench](https://docs.tigergraph.com/ml-workbench/1.4/intro/)
    * [1.4](https://docs.tigergraph.com/ml-workbench/1.4/intro/)
  * [TigerGraph GraphQL Service](https://docs.tigergraph.com/graphql/3.9/)
    * [3.9](https://docs.tigergraph.com/graphql/3.9/)
  * [TigerGraph CoPilot](https://docs.tigergraph.com/tg-copilot/intro/)
    * [main](https://docs.tigergraph.com/tg-copilot/intro/)
  * [TigerGraph Cloud Classic](https://docs.tigergraph.com/cloud/main/start/overview)


[](https://docs.tigergraph.com/home/)
  * [GSQL Language Reference 3.6](https://docs.tigergraph.com/gsql-ref/3.6/intro/intro)
  * Querying
  * [Operators and Expressions](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/3.6/modules/querying/pages/operators-and-expressions.adoc)
### Contents
  * [Constants](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_constants)
  * [Operators](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_operators)
  * [Mathematical Operators and Expressions](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_mathematical_operators_and_expressions)
  * [Boolean Operators](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_boolean_operators)
  * [Bit Operators](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_bit_operators)
  * [String Operators](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_string_operators)
  * [Tuple Fields](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_tuple_fields)
  * [Comparison Operators and Conditions](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_comparison_operators_and_conditions)
  * [BETWEEN …​ AND …​](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_between_and)
  * [IS NULL, IS NOT NULL](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_is_null_is_not_null)
  * [LIKE](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_like)
  * [Vertex, edge, and accumulator attributes](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_vertex_edge_and_accumulator_attributes)
  * [Accessing attributes](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_accessing_attributes)
  * [Accumulator Functions](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_accumulator_functions)
  * [Set/Bag Expression and Operators](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_setbag_expression_and_operators)
  * [Set/Bag expression operators - UNION, INTERSECT, MINUS](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_setbag_expression_operators_union_intersect_minus)
  * [Set/Bag Expression Membership Operators](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_setbag_expression_membership_operators)
  * [Subqueries](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_subqueries)
  * [Parameter types](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_parameter_types)
  * [Return types](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_return_types)
  * [Recursive subqueries](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_recursive_subqueries)
  * [Examples of Expressions](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_examples_of_expressions)
  * [Examples of Expression Statements](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_examples_of_expression_statements)


# Operators and Expressions
### Contents
  * [Constants](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_constants)
  * [Operators](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_operators)
  * [Mathematical Operators and Expressions](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_mathematical_operators_and_expressions)
  * [Boolean Operators](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_boolean_operators)
  * [Bit Operators](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_bit_operators)
  * [String Operators](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_string_operators)
  * [Tuple Fields](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_tuple_fields)
  * [Comparison Operators and Conditions](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_comparison_operators_and_conditions)
  * [BETWEEN …​ AND …​](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_between_and)
  * [IS NULL, IS NOT NULL](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_is_null_is_not_null)
  * [LIKE](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_like)
  * [Vertex, edge, and accumulator attributes](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_vertex_edge_and_accumulator_attributes)
  * [Accessing attributes](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_accessing_attributes)
  * [Accumulator Functions](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_accumulator_functions)
  * [Set/Bag Expression and Operators](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_setbag_expression_and_operators)
  * [Set/Bag expression operators - UNION, INTERSECT, MINUS](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_setbag_expression_operators_union_intersect_minus)
  * [Set/Bag Expression Membership Operators](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_setbag_expression_membership_operators)
  * [Subqueries](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_subqueries)
  * [Parameter types](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_parameter_types)
  * [Return types](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_return_types)
  * [Recursive subqueries](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_recursive_subqueries)
  * [Examples of Expressions](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_examples_of_expressions)
  * [Examples of Expression Statements](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_examples_of_expression_statements)


An _expression_ is a combination of fixed values, variables, operators, function calls, and groupings that specify a computation, resulting in a data value. This section of the specification describes the literals (fixed values), operators, and functions available in the GSQL query language. It covers the subset of the EBNF definitions shown below.
However, more so than in other sections of the specification, syntax alone is not an adequate description. The semantics (functionality) of the particular operators and functions are an essential complement to the syntax.
EBNF for Operations, Functions, and Expressions
```
constant := numeric | stringLiteral | TRUE | FALSE | GSQL_UINT_MAX
     | GSQL_INT_MAX | GSQL_INT_MIN | TO_DATETIME "(" stringLiteral ")"
mathOperator := "*" | "/" | "%" | "+" | "-" | "<<" | ">>" | "&" | "|"
condition := expr
      | expr comparisonOperator expr
      | expr [ NOT ] IN setBagExpr
      | expr IS [ NOT ] NULL
      | expr BETWEEN expr AND expr
      | "(" condition ")"
      | NOT condition
      | condition (AND | OR) condition
      | (TRUE | FALSE)
      | expr [NOT] LIKE expr [ESCAPE escape_char]
comparisonOperator := "<" | "<=" | ">" | ">=" | "==" | "!="
aggregator := COUNT | MAX | MIN | AVG | SUM
expr := name
  | globalAccumName
		| name ".type"
		| name "." name
		| name "." localAccumName ["\'"]
		| name "." name "." name "(" [argList] ")"
    | name "." name "(" [argList] ")" [ "." FILTER "(" condition ")" ]
		| name ["<" type ["," type]* ">"] "(" argList] ")"
		| name "." localAccumName ("." name "(" [argList] ")")+ ["." name]
		| globalAccumName ("."name "(" [argList] ")")+ ["."name]
		| COALESCE "(" [argList] ")"
		| aggregator "(" [DISTINCT] setBagExpr ")"
		| ISEMPTY "(" setBagExpr ")"
		| expr mathOperator expr
		| "-" expr
		| "(" expr ")"
		| "(" argList "->" argList ")"	// key value pair for MapAccum
		| "[" argList "]"        // a list
		| constant
		| setBagExpr
		| name "(" argList ")"     // function call or a tuple object
setBagExpr := name
    | globalAccumName
  	 | name "." name
		  | name "." localAccumName
		  | name "." localAccumName ("." name "(" [argList] ")")+
		  | name "." name "(" [argList] ")" [ "." FILTER "(" condition ")" ]
		  | globalAccumName ("." name "(" [argList] ")")+
		  | setBagExpr (UNION | INTERSECT | MINUS) setBagExpr
		  | "(" argList ")"
		  | "(" setBagExpr ")"

argList := expr ["," expr]*
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_constants)Constants
```
constant := numeric | stringLiteral | TRUE | FALSE | GSQL_UINT_MAX
     | GSQL_INT_MAX | GSQL_INT_MIN | TO_DATETIME "(" stringLiteral ")"
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Each primitive data type supports constant values:
Data Type | Constant | Examples  
---|---|---  
Numeric types (`INT`, `UINT`, `FLOAT`, `DOUBLE`) | `numeric` | 123 -5 45.67 2.0e-0.5  
`UINT` | `GSQL_UINT_MAX`  
`INT` | `GSQL_INT_MAX` `GSQL_INT_MIN`  
`boolean` | `TRUE` `FALSE`  
`string` | `stringLiteral` | `"atoz@com"` `"0.25"`  
`GSQL_UINT_MAX` = 2 ^ 64 - 1 = 18446744073709551615
`GSQL_INT_MAX` = 2 ^ 63 - 1 = 9223372036854775807
`GSQL_INT_MIN` = -2 ^ 63 = -9223372036854775808
## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_operators)Operators
An operator is a keyword token that performs a specific computational function to return a resulting value, using the adjacent expressions (its operands) as input values. Both operators and functions compute a result from one or more inputs, but syntactically they are different. The most familiar operators are the mathematical operators for addition `+` and subtraction `-` .
The operators listed in this section are designed to behave like the operators in MySQL.  
---  
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_mathematical_operators_and_expressions)Mathematical Operators and Expressions
We support the following standard mathematical operators and meanings. The latter four (`<<` `>>` `&` `|`) are for bitwise operations. See the [[bit-operators]](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#bit-operators) section below.
```
mathOperator := "*" | "/" | "%" | "+" | "-" | "<<" | ">>" | "&" | "|"
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Operator precedences are shown in the following list, from the highest precedence to the lowest. Operators that are shown together on a line have the same precedence:
Operator Precedence, highest to lowest
```
*, /, %
-, +
<<, >>
&
|
==, >=, >, <=, <, !=
test![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_example)Example
  * Query
  * Results


Example 1. Math Operators + - * /
```
CREATE QUERY math_operators() FOR GRAPH Minimal_Net {
  INT x,y;
  INT z1,z2,z3,z4,z5;
  FLOAT f1,f2,f3,f4;
  x = 7;
  y = 3;
  z1 = x * y;  // z = 21
  z2 = x - y;  // z = 4
  z3 = x + y;  // z = 10
  z4 = x / y;  // z = 2
  z5 = x / 4.0; // z = 1
  f1 = x / y;  // v = 2
  f2 = x / 4.0; // v = 1.75
  f3 = x % 3;  // v = 1
  f4 = x % y;  // z = 1
  PRINT x,y;
  PRINT z1 AS x_times_y, z2 AS x_minus_y, z3 AS x_plus_y, z4 AS x_div_y, z5 AS x_div_4f;
  PRINT f1 AS x_div_y,  f2 AS x_div_4f, f3 AS x_mod_3, f4 AS x_mod_y;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

mathOperators.json Results
```
GSQL > RUN QUERY math_operators()
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [
  {
   "x": 7,
   "y": 3
  },
  {
   "x_div_4f": 1,
   "x_times_y": 21,
   "x_div_y": 2,
   "x_minus_y": 4,
   "x_plus_y": 10
  },
  {
   "x_mod_3": 1,
   "x_div_4f": 1.75,
   "x_mod_y": 1,
   "x_div_y": 2
  }
 ]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_boolean_operators)Boolean Operators
We support the standard Boolean operators and standard order of precedence: `AND`, `OR`, `NOT`
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_bit_operators)Bit Operators
Bit operators (`<<` `>>` `&` `|`) operate on integers and return an integer.
Bit Operators
```
CREATE QUERY bit_operation_test() FOR GRAPH Minimal_Net{
  PRINT 80 >> 2;   // 20
  PRINT 80 << 2;   // 320
  PRINT 2 + 80 >> 4; // 5
  PRINT 2 | 3 ;   // 3
  PRINT 2 & 3 ;   // 2
  PRINT 2 | 3 + 2;  // 7
  PRINT 2 & 3 - 2;  // 0
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_string_operators)String Operators
The `+` operator can be used for concatenating strings.
```
CREATE QUERY concat_test() FOR GRAPH Minimal_Net{
  STRING first_string, second_string, third_string;
  first_string = "first string";
  second_string = "second string";
  third_string = first_string + " " + second_string;
  PRINT third_string;  // "first string second string"
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_tuple_fields)Tuple Fields
The fields of the tuple can be accessed using the dot operator.
## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_comparison_operators_and_conditions)Comparison Operators and Conditions
A condition is an expression that evaluates to a boolean value of either true or false. One type of condition uses the familiar comparison operators. A comparison operator compares two numeric or string values.
```
comparisonOperator := "<" | "<=" | ">" | ">=" | "==" | "!="
condition := expr
      | expr comparisonOperator expr
      | expr [ NOT ] IN setBagExpr
      | expr IS [ NOT ] NULL
      | expr BETWEEN expr AND expr
      | "(" condition ")"
      | NOT condition
      | condition (AND | OR) condition
      | (TRUE | FALSE)
      | expr [NOT] LIKE expr [ESCAPE escape_char]
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Strings are compared based on standard lexicographical ordering: (space) < (digit) < (uppercase_letter) < (lowercase_letter).
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_between_and)BETWEEN …​ AND …​
The expression `expr1 BETWEEN expr2 AND expr3` is `true` if the value expr1 is in the range from expr2 to expr3, including the endpoint values. Each expression must be numeric.
`expr1 BETWEEN expr2 AND expr3` is equivalent to `expr1 ⇐ expr3 AND expr1 >= expr2`.
`BETWEEN AND` example
```
CREATE QUERY math_operator_between() FOR GRAPH Minimal_Net {
  INT x;
  BOOL b;
  x = 1;
  b = (x BETWEEN 0 AND 100); PRINT b; // True
  b = (x BETWEEN 1 AND 2); PRINT b;  // True
  b = (x BETWEEN 0 AND 1); PRINT b;  // True
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_is_null_is_not_null)IS NULL, IS NOT NULL
`IS NULL` and `IS NOT NULL` can be used for checking whether an optional parameter is given any value.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_example_2)Example
  * Query
  * Results


IS NULL example
```
CREATE QUERY parameter_is_null (INT p) FOR GRAPH Minimal_Net {
  IF p IS NULL THEN
    PRINT "p is null";
  ELSE
    PRINT "p is not null";
  END;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

parameterIsNULL.json Results
```
GSQL > RUN QUERY parameter_is_null(_)
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"\"p is null\"": "p is null"}]
}
GSQL > RUN QUERY parameter_is_null(3)
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"\"p is not null\"": "p is not null"}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Every attribute value stored in GSQL is a valid value, so IS NULL and IS NOT NULL are only effective for query parameters.  
---  
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_like)LIKE
```
expr [NOT] LIKE expr [ESCAPE escape_char]
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The `LIKE` operator is used for string pattern matching and can only be used in `WHERE` clauses. The expression `string1 LIKE string_pattern` evaluates to boolean true if `string1` matches the pattern in `string_pattern`; otherwise, it is false.
Both operands must be strings. Additionally, while `string1` can be a function call (e.g. `lower(string_variable)`, `string_pattern` must be a string literal or a parameter. `string_pattern` cannot be the result of concatenating other strings, nor can it be a function call.
A `string_pattern` can contain characters as well as the following wildcard and other special symbols, in order to express a pattern (`<char_list>`indicates a placeholder):
Character or syntax | Description | Example  
---|---|---  
`%` | Matches zero or more characters. | `%abc%` matches any string which contains the sequence `"abc"`.  
`_`(underscore) | Matches any single character. | `_abc_e`matches any 6-character string where the 2nd to 4th characters are `"abc"` and the last character is `"e"`.  
`[<char_list>]` | Matches any character in a char list. A char list is a concatenated character set, with no separators. | `[Tiger]`matches either `T`, `i`, `g`, `e`, or `r`.  
`[^<char_list>]` | Matches any character NOT in a char list. | `[^qxz]`matches any character other than `q`, `x`, or `z`.  
`[!<char_list>]` | Matches any character NOT in a char list.  
`α-β` | (Special syntax within a char list) matches a character in the range from α to β. A char list can have multiple ranges. | `[a-mA-M0-3]`matches a letter from a to m, upper or lower case, or a digit from 0 to 3.  
`\\` | (Special syntax within a char list) matches the character `\`  
`\\]` | (Special syntax within a char list) matches the character `]` No special treatment is needed for [ inside a char list. | `%[\\]!]`matches any string which ends with either `]` or `!`  
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_escape_escape_char)`ESCAPE escape_char`
The optional `ESCAPE escape_char` clause is used to define an escape character. When `escape_char` occurs in `string_pattern`, then the next character is interpreted literally, instead of as a pattern matching operator. For example, if we want to specify the pattern "any string ending with the `'%'` character", we could use `"%\%" ESCAPE "\"`
The first `"%"` has its usual pattern-matching meaning "zero or more characters". `"\%"` means a literal percentage character, because it starts with the escape character `"\"`.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_example_3)Example
  * Query Without Parameters
  * Query With Parameters
  * Results


Example query using LIKE operator
```
CREATE QUERY print_a_posts() FOR GRAPH Social_Net {
  posts = {Post.*};
  a_posts = SELECT v FROM posts:v
    // Returns all posts with the character "a" in the subject
    WHERE v.subject LIKE "%a%";
	PRINT a_posts;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Example parameterized query
```
CREATE QUERY print_posts(STRING search_string) FOR GRAPH Social_Net {
  STRING search_param;
  search_param = "%" + search_string + "%";
  posts = {Post.*};
  a_posts = SELECT v FROM posts:v
    // Returns all posts with the search_string in the subject
    WHERE v.subject LIKE search_param;
  PRINT a_posts;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"aPosts": [
  {
   "v_id": "2",
   "attributes": {
    "postTime": "2011-02-03 01:02:42",
    "subject": "query languages"
   },
   "v_type": "post"
  },
  {
   "v_id": "8",
   "attributes": {
    "postTime": "2011-02-03 17:05:52",
    "subject": "cats"
   },
   "v_type": "post"
  },
  {
   "v_id": "0",
   "attributes": {
    "postTime": "2010-01-12 11:22:05",
    "subject": "Graphs"
   },
   "v_type": "post"
  },
  {
   "v_id": "1",
   "attributes": {
    "postTime": "2011-03-03 23:02:00",
    "subject": "tigergraph"
   },
   "v_type": "post"
  }
 ]}]
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_vertex_edge_and_accumulator_attributes)Vertex, edge, and accumulator attributes
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_accessing_attributes)Accessing attributes
Attributes on vertices or edges are defined in the graph schema. Additionally, each vertex and edge has a built-in STRING attribute called **type** which represents the user-defined type of that edge or vertex. These attributes, including **type,** can be accessed for a particular edge or vertex with the dot operator:
Accessing attributes with a known name.
```
name ".type"  // read only. Returns vertexType or edgeType of name
name "." attrName // read/write. Accesses attribute called attrName
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Dynamic query support The name of the attribute can be parameterized using the **getAttr** and **setAttr** [vertex functions](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods), described later in this section. This allows you to write [dynamic query](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_dynamic_querying) procedures where the attribute names are specified when you run the query.  
---  
For example, the following code snippet shows two different `SELECT` statements which produce equivalent results. The first uses the dot operator on the vertex variable `v` to access the `subject` attribute, which is defined in the graph schema. The `FROM` clause in the first `SELECT` statement necessitates that any target vertices will be of type `Post` (also defined in the graph schema). The second `SELECT` schema checks that the vertex variable `v`'s type is a `Post` vertex by using the dot operator to access the built-in `type` attribute.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_example_4)Example
  * Query
  * Results


Accessing vertex variable attributes
```
CREATE QUERY coffee_related_posts() FOR GRAPH Social_Net {
  all_vertices = {ANY};
  results = SELECT v FROM all_vertices:s -(:e)- Post:v
    WHERE v.subject == "coffee";
  PRINT results;
  results = SELECT v FROM all_vertices:s -(:e)- :v
    WHERE v.type == "Post" AND v.subject == "coffee";
  PRINT results;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results for Query `coffeeRelatedPosts`
```
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [
  {"results": [{
   "v_id": "4",
   "attributes": {
    "subject": "coffee",
    "post_time": "2011-02-07 05:02:51"
   },
   "v_type": "Post"
  }]},
  {"results": [{
   "v_id": "4",
   "attributes": {
    "subject": "coffee",
    "post_time": "2011-02-07 05:02:51"
   },
   "v_type": "Post"
  }]}
 ]
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_accumulator_functions)Accumulator Functions
This section describes functions that apply to all or most accumulators. Other accumulator functions for each accumulator type are illustrated in the "Accumulator Type" section.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_previous_value_of_accumulator)Previous value of accumulator
The tick operator `'` can be used to read the value of an accumulator as it was at the start an ACCUM clause, before any changes that took place within the ACCUM clause. It can only be used in the POST-ACCUM clause. A typical use is to compare the value of the accumulator before and after the ACCUM clause. The PageRank algorithm provides a good example:
```
v = SELECT s
  FROM start:s - (e_type:e) -> :t
  ACCUM t.@received_score += s.@score/(s.outdegree(e_type))
  POST-ACCUM
    s.@score = (1.0 - damping) + damping * s.@received_score,
    s.@received_score = 0,
    @@max_diff += abs(s.@score - s.@score');
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

In the last line, we compute `@@max_diff` as the absolute value of the difference between the post-ACCUM score (`s.@score`) and the pre-ACCUM score (`s.@score'`).
## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_setbag_expression_and_operators)Set/Bag Expression and Operators
SELECT blocks take an input vertex set and perform various selection and filtering operations to produce an output set. Therefore, _set/bag expressions_ and their operators are a useful and powerful part of the GSQL query language. A set/bag expression can use either SetAccum or BagAccum.
EBNF
```
setBagExpr := name
    | globalAccumName
  	 | name "." name
		  | name "." localAccumName
		  | name "." localAccumName ("." name "(" [argList] ")")+
		  | name "." name "(" [argList] ")" [ "." FILTER "(" condition ")" ]
		  | globalAccumName ("." name "(" [argList] ")")+
		  | setBagExpr (UNION | INTERSECT | MINUS) setBagExpr
		  | "(" argList ")"
		  | "(" setBagExpr ")"
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_setbag_expression_operators_union_intersect_minus)Set/Bag expression operators - UNION, INTERSECT, MINUS
The operators are straightforward, when two operands are both sets, the result expression is a set. When at least one operand is a bag, the result expression is a bag. If one operand is a bag and the other is a set, the operator treats the set operand as a bag containing one of each value.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_setbag_operator_examples)Set/bag operator examples
  * Query
  * Results


Set/Bag Operator Examples
```
CREATE QUERY set_operators_ex() FOR GRAPH Minimal_Net  {
  SetAccum<INT> @@set_a, @@set_b, @@a_union_b, @@a_intsct_b, @@a_minus_b;
  BagAccum<INT> @@bag_d, @@bag_e, @@d_union_e, @@d_intsct_e, @@d_minus_e;
  BagAccum<INT> @@d_minus_a, @@d_union_a, @@a_union_b_bag;
  BOOL x;
  @@set_a = (1,2,3,4);   PRINT @@set_a;
  @@set_b = (2,4,6,8);   PRINT @@set_b;
  @@a_union_b = @@set_a UNION @@set_b ;   PRINT @@a_union_b;  // (1, 2, 3, 4, 6, 8)
  @@a_intsct_b = @@set_a INTERSECT @@set_b; PRINT @@a_intsct_b;  // (2, 4)
  @@a_minus_b = @@set_a MINUS @@set_b ;   PRINT @@a_minus_b;  // C = (1, 3)
  @@bag_d = (1,2,2,3);   PRINT @@bag_d;
  @@bag_e = (2,3,5,7);   PRINT @@bag_e;
  @@d_union_e = @@bag_d UNION @@bag_e;   PRINT @@d_union_e;  // (1, 2, 2, 2, 3, 3, 5, 7)
  @@d_intsct_e = @@bag_d INTERSECT @@bag_e; PRINT @@d_intsct_e; // (2, 3)
  @@d_minus_e = @@bag_d MINUS @@bag_e;   PRINT @@d_minus_e;  // (1, 2)
  @@d_minus_a = @@bag_d MINUS @@set_a;   PRINT @@d_minus_a;  // (2)
  // bag UNION set is a bag
  @@d_union_a = @@bag_d UNION @@set_a;   PRINT @@d_union_a;  // (1, 1, 2, 2, 2, 3, 3, 4)
  // because set UNION set is a set
  @@a_union_b_bag = @@set_a UNION @@set_b; PRINT @@a_union_b_bag; // (1, 2, 3, 4, 6, 8)
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
CREATE QUERY set_operators_ex() FOR GRAPH Minimal_Net  {
  SetAccum<INT> @@set_a, @@set_b, @@a_union_b, @@a_intsct_b, @@a_minus_b;
  BagAccum<INT> @@bag_d, @@bag_e, @@d_union_e, @@d_intsct_e, @@d_minus_e;
  BagAccum<INT> @@d_minus_a, @@d_union_a, @@a_union_b_bag;
  BOOL x;
  @@set_a = (1,2,3,4);   PRINT @@set_a;
  @@set_b = (2,4,6,8);   PRINT @@set_b;
  @@a_union_b = @@set_a UNION @@set_b ;   PRINT @@a_union_b;  // (1, 2, 3, 4, 6, 8)
  @@a_intsct_b = @@set_a INTERSECT @@set_b; PRINT @@a_intsct_b;  // (2, 4)
  @@a_minus_b = @@set_a MINUS @@set_b ;   PRINT @@a_minus_b;  // C = (1, 3)
  @@bag_d = (1,2,2,3);   PRINT @@bag_d;
  @@bag_e = (2,3,5,7);   PRINT @@bag_e;
  @@d_union_e = @@bag_d UNION @@bag_e;   PRINT @@d_union_e;  // (1, 2, 2, 2, 3, 3, 5, 7)
  @@d_intsct_e = @@bag_d INTERSECT @@bag_e; PRINT @@d_intsct_e; // (2, 3)
  @@d_minus_e = @@bag_d MINUS @@bag_e;   PRINT @@d_minus_e;  // (1, 2)
  @@d_minus_a = @@bag_d MINUS @@set_a;   PRINT @@d_minus_a;  // (2)
  // bag UNION set is a bag
  @@d_union_a = @@bag_d UNION @@set_a;   PRINT @@d_union_a;  // (1, 1, 2, 2, 2, 3, 3, 4)
  // because set UNION set is a set
  @@a_union_b_bag = @@set_a UNION @@set_b; PRINT @@a_union_b_bag; // (1, 2, 3, 4, 6, 8)
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The result of these operators is another set or bag, so these operations can be nested and chained to form more complex expressions, such as
```
(setBagExpr_A INTERSECT (setBagExpr_B UNION setBagExpr_C) ) MINUS setBagExpr_D
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_setbag_expression_membership_operators)Set/Bag Expression Membership Operators
For example , suppose setBagExpr_A is ("a", "b", "c")
```
"a" IN setBagExpr_A      => true
"d" IN setBagExpr_A      => false
"a" NOT IN setBagExpr_A    => false
"d" NOT IN setBagExpr_A    => true
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The `IN` and `NOT IN` operators support all base types on the left-hand side, and any set/bag expression on the right-hand side. The base type must be the same as the accumulator’s element type. `IN` and `NOT IN` return a `BOOL` value.
The following example uses `NOT IN` to exclude neighbors that are on a blocked list.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_example_5)Example
  * Query
  * Result


Set Membership example
```
CREATE QUERY friends_not_in_blocked_list (VERTEX<Person> seed,
  SET<VERTEX<Person>> blocked_list) FOR GRAPH Social_Net {
  start = {seed};
  result = SELECT v
    FROM start:s-(Friend:e)-Person:v
    WHERE v NOT IN blocked_list;
  PRINT result;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results for Query `friends_not_in_blocked_list`
```
GSQL > RUN QUERY friends_not_in_blocked_list("person1", ["person2"])
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{"Result": [{
  "v_id": "person8",
  "attributes": {
   "gender": "Male",
   "id": "person8"
  },
  "v_type": "Person"
 }]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_subqueries)Subqueries
A query defined with a `RETURNS` header following its `CREATE` statement is called a subquery. Subqueries act as callable functions in GSQL: they take parameters, perform a set of actions and return a value.
A subquery must end with a [return statement](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects) to pass its output value to a query. Exactly one type is allowed in the `RETURNS` header, and thus the `RETURN` statement can only return one expression.
A subquery must be created before the query that calls the subquery. A subquery must be installed either before or in the same `INSTALL QUERY` command with the query that calls the subquery.
  * A [distributed query](https://docs.tigergraph.com/gsql-ref/3.6/querying/distributed-query-mode) cannot call another distributed query
  * A non-distributed query cannot call a distributed query in an `ACCUM` or `POST-ACCUM` clause

  
---  
Main Components of a Subquery
```
CREATE QUERY <query_name>() FOR GRAPH <Graph_Name> **(1)**
RETURNS (INT) **(2)**
{
  // ...
  // Query body goes here
  // ...
  RETURN <return_value> **(3)**
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | Parameters are optional.  
---|---  
**2** | A subquery has a `RETURNS` header specifying its return type.  
**3** | The return statement of a subquery. Return value must be the same type as specified in the `RETURNS` header.  
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_parameter_types)Parameter types
A subquery parameter can only be one of the following types:
  * Primitives: `INT`, `UINT`, `FLOAT`, `DOUBLE`, `STRING`, `BOOL`
  * `VERTEX`
  * A set or bag of primitive or `VERTEX` elements


### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_return_types)Return types
A subquery’s return value can be any [base type variable](https://docs.tigergraph.com/gsql-ref/3.6/querying/declaration-and-assignment-statements#_base_type_variables) or accumulator with the following exceptions:
  * If the return type is a `HeapAccum` or `GroupByAccum` that has a user-defined tuple as an element, the user-defined tuple must be [defined at the catalog level](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/defining-a-graph-schema#_typedef).
  * If the return type is a `BagAccum`, `SetAccum`, or `ListAccum` with a tuple as its element, the tuple does not need to be defined at the catalog level and can be anonymous.


#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_example_6)Example
The following query uses a subquery that returns an anonymous tuple:
  * Subquery
  * Query


```
CREATE QUERY sub_query(VERTEX x)
RETURNS (ListAccum<TUPLE<INT, STRING, DOUBLE>>)
{
  TYPEDEF tuple<INT a, STRING b, DOUBLE c> My_Tuple;
  ListAccum<My_Tuple> @@res;
  RETURN @@res;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
CREATE QUERY main_query() {
  TYPEDEF tuple<INT a, STRING b, DOUBLE c> My_Tuple1;
  ListAccum<My_Tuple1> @@acc1;
  V = SELECT src FROM xxxx:src
    // Put the elements returned from the subQuery at the end of the @@Acc1
    ACCUM @@Acc1 += sub_query(src);
  PRINT @@acc1;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_recursive_subqueries)Recursive subqueries
Recursion is supported for subqueries and a subquery can call itself. The following example subquery takes a set of persons as starting points, and returns all the friends within a given distance.
While recursive subqueries may look simpler in writing, they are usually not as efficient as iterative subqueries in GSQL.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_example_7)Example
  * Subquery
  * Query
  * Result


```
CREATE QUERY sub_find_friends_in_distance(SET<VERTEX> seeds, INT distance)
FOR GRAPH Friend_Net RETURNS (SET<VERTEX>)
{
	IF distance <= 0 THEN  // Base case
    // When distance is 0, return the seed vertices themselves
    RETURN seeds;
	ELSE
    seed_vs = seeds; // Initialize starting vertices
    // Select 1-hop neighbors from the starting points
    next_vs = SELECT v FROM seed_vs -(Friend:e)- :v;
    /* Find the (distance-1)-hop neighbors of the 1-hop neighbors
     and return the union of the starting vertices and neighbors */
    RETURN seeds UNION sub_find_friends_in_distance(next_vs, distance - 1);
  END;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
CREATE QUERY find_friends_in_distance(VERTEX<Person> p, INT distance) FOR GRAPH Friend_Net {
	seed = {p};
  //PRINT All Persons;
	PRINT sub_find_friends_in_distance(seed, distance) AS friends;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Test cases: Starting from `person1`, search to a distance of `1` and a distance of `2`.
```
RUN QUERY find_friends_in_distance("person1", 1)
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"friends": [
  "person4",
  "person2",
  "person3",
  "person1"
 ]}]
}
RUN QUERY find_friends_in_distance("person1", 2)
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"friends": [
  "person4",
  "person2",
  "person3",
  "person6",
  "person8",
  "person9",
  "person1"
 ]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_examples_of_expressions)Examples of Expressions
Below is a list of examples of expressions. Note that `( argList )` is a set/bag expression, while `[ argList ]` is a list expression.
  * Query
  * Results


Expression Examples
```
CREATE QUERY expression_ex() FOR GRAPH Work_Net {
  TYPEDEF TUPLE<STRING country_name, STRING company_name> company_info;
  ListAccum<STRING> @company_names;
  SumAccum<INT> @company_count;
  SumAccum<INT> @number_of_relationships;
  ListAccum<company_info> @info;
  MapAccum< STRING,ListAccum<STRING> > @@company_employee_relationships;
  SumAccum<INT> @@total_relationship_count;
  ListAccum<INT> @@value_list;
  SetAccum<INT> @@value_set;
  SumAccum<INT> @@a;
  SumAccum<INT> @@b;
  // expr := constant
  @@a = 10;
  // expr := ["@@"] name
  @@b = @@a;
  // expr := expr mathOperator expr
  @@b = @@a + 5;
  // expr := "(" expr ")"
  @@b = (@@a + 5);
  // expr := "-" expr
  @@b = -(@@a + 5);
  PRINT @@a, @@b;
  // expr := "[" argList "]"  // a list
  @@value_list = [1,2,3,4,5];
  @@value_list += [24,80];
  // expr := "(" argList ")" // setBagExpr
  @@value_set += (1,2,3,4,5);
  // expr := ( COUNT | ISEMPTY | MAX | MIN | AVG | SUM ) "(" setBagExpr ")"
  PRINT MAX(@@value_list);
  PRINT AVG(@@value_list);
  seed = {ANY};
  company1 = SELECT t FROM seed:s -(Works_For)- :t WHERE (s.id == "company1");
  company2 = SELECT t FROM seed:s -(Works_For)- :t WHERE (s.id == "company2");
  // expr := setBagExpr
  works_for_both = company1 INTERSECT company2;
  PRINT works_for_both;
  // expr := name "." "type"
  employees = SELECT s FROM seed:s WHERE (s.type == "Person");
  employees = SELECT s FROM employees:s -(Works_For)- :t
  ACCUM
    // expr := name "." ["@"] name
    s.@company_names += t.id,
    // expr := name "."name "(" [argList] ")" [ "."FILTER "(" condition ")" ]
    s.@number_of_relationships += s.outdegree(),
    // expr := name ["<" type ["," type"]* ">"] "(" [argList] ")"
    s.@info += company_info(t.country, t.id)
  POST-ACCUM
    // expr := name "."localAccum_name ("."name "(" [argList] ")")+ ["."name]
    s.@company_count += s.@company_names.size(),
  // expr := name "."localAccum_name ["\'"]
  @@total_relationship_count += s.@company_count,
  FOREACH comp IN s.@company_names DO
    // expr := "(" argList "->" argList ")"
    @@company_employee_relationships += (s.id -> comp)
  END;
  PRINT employees;
  PRINT @@total_relationship_count;
  PRINT @@company_employee_relationships;
  // expr := globalAccum_name ("."name "(" [argList] ")")+ ["."name]
  PRINT @@company_employee_relationships.size();
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

expressionEx.json Results
```
[
 {
  "@@a": 10,
  "@@b": -15
 },
 {
  "max(@@value_list)": 80
 },
 {
  "avg(@@value_list)": 17
 },
 {
  "works_for_both": [
   {
    "attributes": {
     "@company_count": 0,
     "@company_names": [],
     "@info": [],
     "@number_of_relationships": 0,
     "id": "person1",
     "interest_list": [
      "management",
      "financial"
     ],
     "interest_set": [
      "financial",
      "management"
     ],
     "location_id": "us",
     "skill_list": [
      1,
      2,
      3
     ],
     "skill_set": [
      1,
      2,
      3
     ]
    },
    "v_id": "person1",
    "v_type": "Person"
   },
   {
    "attributes": {
     "@company_count": 0,
     "@company_names": [],
     "@info": [],
     "@number_of_relationships": 0,
     "id": "person2",
     "interest_list": [
      "engineering"
     ],
     "interest_set": [
      "engineering"
     ],
     "location_id": "chn",
     "skill_list": [
      2,
      3,
      5,
      6
     ],
     "skill_set": [
      2,
      3,
      5,
      6
     ]
    },
    "v_id": "person2",
    "v_type": "Person"
   }
  ]
 },
 {
  "employees": [
   {
    "attributes": {
     "@company_count": 2,
     "@company_names": [
      "company2",
      "company3"
     ],
     "@info": [
      {
       "company_name": "company2",
       "country_name": "chn"
      },
      {
       "company_name": "company3",
       "country_name": "jp"
      }
     ],
     "@number_of_relationships": 4,
     "id": "person7",
     "interest_list": [
      "art",
      "sport"
     ],
     "interest_set": [
      "sport",
      "art"
     ],
     "location_id": "us",
     "skill_list": [
      8,
      6
     ],
     "skill_set": [
      6,
      8
     ]
    },
    "v_id": "person7",
    "v_type": "Person"
   },
   {
    "attributes": {
     "@company_count": 2,
     "@company_names": [
      "company2",
      "company1"
     ],
     "@info": [
      {
       "company_name": "company2",
       "country_name": "chn"
      },
      {
       "company_name": "company1",
       "country_name": "us"
      }
     ],
     "@number_of_relationships": 4,
     "id": "person1",
     "interest_list": [
      "management",
      "financial"
     ],
     "interest_set": [
      "financial",
      "management"
     ],
     "location_id": "us",
     "skill_list": [
      1,
      2,
      3
     ],
     "skill_set": [
      1,
      2,
      3
     ]
    },
    "v_id": "person1",
    "v_type": "Person"
   },
   {
    "attributes": {
     "@company_count": 1,
     "@company_names": [
      "company2"
     ],
     "@info": [
      {
       "company_name": "company2",
       "country_name": "chn"
      }
     ],
     "@number_of_relationships": 1,
     "id": "person5",
     "interest_list": [
      "sport",
      "financial",
      "engineering"
     ],
     "interest_set": [
      "engineering",
      "financial",
      "sport"
     ],
     "location_id": "can",
     "skill_list": [
      8,
      2,
      5
     ],
     "skill_set": [
      2,
      5,
      8
     ]
    },
    "v_id": "person5",
    "v_type": "Person"
   },
   {
    "attributes": {
     "@company_count": 2,
     "@company_names": [
      "company2",
      "company1"
     ],
     "@info": [
      {
       "company_name": "company2",
       "country_name": "chn"
      },
      {
       "company_name": "company1",
       "country_name": "us"
      }
     ],
     "@number_of_relationships": 4,
     "id": "person2",
     "interest_list": [
      "engineering"
     ],
     "interest_set": [
      "engineering"
     ],
     "location_id": "chn",
     "skill_list": [
      2,
      3,
      5,
      6
     ],
     "skill_set": [
      2,
      3,
      5,
      6
     ]
    },
    "v_id": "person2",
    "v_type": "Person"
   },
   {
    "attributes": {
     "@company_count": 1,
     "@company_names": [
      "company1"
     ],
     "@info": [
      {
       "company_name": "company1",
       "country_name": "us"
      }
     ],
     "@number_of_relationships": 1,
     "id": "person3",
     "interest_list": [
      "teaching"
     ],
     "interest_set": [
      "teaching"
     ],
     "location_id": "jp",
     "skill_list": [
      4,
      1,
      6
     ],
     "skill_set": [
      1,
      4,
      6
     ]
    },
    "v_id": "person3",
    "v_type": "Person"
   },
   {
    "attributes": {
     "@company_count": 1,
     "@company_names": [
      "company1"
     ],
     "@info": [
      {
       "company_name": "company1",
       "country_name": "us"
      }
     ],
     "@number_of_relationships": 1,
     "id": "person8",
     "interest_list": [
      "management"
     ],
     "interest_set": [
      "management"
     ],
     "location_id": "chn",
     "skill_list": [
      1,
      5,
      2
     ],
     "skill_set": [
      1,
      2,
      5
     ]
    },
    "v_id": "person8",
    "v_type": "Person"
   },
   {
    "attributes": {
     "@company_count": 2,
     "@company_names": [
      "company2",
      "company3"
     ],
     "@info": [
      {
       "company_name": "company2",
       "country_name": "chn"
      },
      {
       "company_name": "company3",
       "country_name": "jp"
      }
     ],
     "@number_of_relationships": 4,
     "id": "person9",
     "interest_list": [
      "financial",
      "teaching"
     ],
     "interest_set": [
      "teaching",
      "financial"
     ],
     "location_id": "us",
     "skill_list": [
      4,
      7,
      2
     ],
     "skill_set": [
      2,
      4,
      7
     ]
    },
    "v_id": "person9",
    "v_type": "Person"
   },
   {
    "attributes": {
     "@company_count": 1,
     "@company_names": [
      "company2"
     ],
     "@info": [
      {
       "company_name": "company2",
       "country_name": "chn"
      }
     ],
     "@number_of_relationships": 1,
     "id": "person4",
     "interest_list": [
      "football"
     ],
     "interest_set": [
      "football"
     ],
     "location_id": "us",
     "skill_list": [
      4,
      1,
      10
     ],
     "skill_set": [
      1,
      4,
      10
     ]
    },
    "v_id": "person4",
    "v_type": "Person"
   },
   {
    "attributes": {
     "@company_count": 2,
     "@company_names": [
      "company3",
      "company1"
     ],
     "@info": [
      {
       "company_name": "company3",
       "country_name": "jp"
      },
      {
       "company_name": "company1",
       "country_name": "us"
      }
     ],
     "@number_of_relationships": 4,
     "id": "person10",
     "interest_list": [
      "football",
      "sport"
     ],
     "interest_set": [
      "sport",
      "football"
     ],
     "location_id": "us",
     "skill_list": [
      3
     ],
     "skill_set": [
      3
     ]
    },
    "v_id": "person10",
    "v_type": "Person"
   },
   {
    "attributes": {
     "@company_count": 1,
     "@company_names": [
      "company1"
     ],
     "@info": [
      {
       "company_name": "company1",
       "country_name": "us"
      }
     ],
     "@number_of_relationships": 1,
     "id": "person6",
     "interest_list": [
      "music",
      "art"
     ],
     "interest_set": [
      "art",
      "music"
     ],
     "location_id": "jp",
     "skill_list": [
      7,
      10
     ],
     "skill_set": [
      7,
      10
     ]
    },
    "v_id": "person6",
    "v_type": "Person"
   },
   {
    "attributes": {
     "@company_count": 1,
     "@company_names": [
      "company4"
     ],
     "@info": [
      {
       "company_name": "company4",
       "country_name": "us"
      }
     ],
     "@number_of_relationships": 1,
     "id": "person12",
     "interest_list": [
      "music",
      "engineering",
      "teaching",
      "teaching",
      "teaching"
     ],
     "interest_set": [
      "teaching",
      "engineering",
      "music"
     ],
     "location_id": "jp",
     "skill_list": [
      1,
      5,
      2,
      2,
      2
     ],
     "skill_set": [
      1,
      2,
      5
     ]
    },
    "v_id": "person12",
    "v_type": "Person"
   },
   {
    "attributes": {
     "@company_count": 1,
     "@company_names": [
      "company5"
     ],
     "@info": [
      {
       "company_name": "company5",
       "country_name": "can"
      }
     ],
     "@number_of_relationships": 1,
     "id": "person11",
     "interest_list": [
      "sport",
      "football"
     ],
     "interest_set": [
      "football",
      "sport"
     ],
     "location_id": "can",
     "skill_list": [
      10
     ],
     "skill_set": [
      10
     ]
    },
    "v_id": "person11",
    "v_type": "Person"
   }
  ]
 },
 {
  "@@total_relationship_count": 17
 },
 {
  "@@company_employee_relationships": {
   "person1": [
    "company2",
    "company1"
   ],
   "person10": [
    "company3",
    "company1"
   ],
   "person11": [
    "company5"
   ],
   "person12": [
    "company4"
   ],
   "person2": [
    "company2",
    "company1"
   ],
   "person3": [
    "company1"
   ],
   "person4": [
    "company2"
   ],
   "person5": [
    "company2"
   ],
   "person6": [
    "company1"
   ],
   "person7": [
    "company2",
    "company3"
   ],
   "person8": [
    "company1"
   ],
   "person9": [
    "company2",
    "company3"
   ]
  }
 },
 {
  "@@company_employee_relationships.size()": 12
 }
]
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_examples_of_expression_statements)Examples of Expression Statements
  * Query
  * Results


Expression Statement Examples
```
CREATE QUERY expression_stmnt_ex() FOR GRAPH Work_Net {
  TYPEDEF TUPLE<STRING country_name, STRING company_name> Company_Info;
  ListAccum<Company_Info> @employer_info;
  SumAccum<INT> @@a;
  ListAccum<STRING> @employers;
  SumAccum<INT> @employer_count;
  SetAccum<STRING> @@country_set;
  INT x;
  // exprStmnt := name "=" expr
  x = 10;
  // gAccumAssignStmt := globalAccumName ("+=" | "=") expr
  @@a = 10;
  PRINT x, @@a;
  start = {Person.*};
  employees = SELECT s FROM start:s -(Works_For)- :t
    ACCUM // exprStmnt := name "."localAccumName ("+="| "=") expr
       s.@employers += t.id,
    		 // exprStmnt := name ["<" type ["," type"]* ">"] "(" [argList] ")"
		   s.@employer_info += Company_Info(t.country, t.id),
       // gAccumAccumStmt := globalAccumName "+=" expr
		   @@country_set += t.country
	     // exprStmnt := name "."localAccumName ["."name "(" [argList] ")"]
	     POST-ACCUM s.@employer_count += s.@employers.size();
  // exprStmnt := globalAccumName ["."name "(" [argList] ")"]+
  PRINT @@country_set.size();
  PRINT employees;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
GSQL > RUN QUERY expression_stmnt_ex()
[
 {
  "@@a": 10,
  "x": 10
 },
 {
  "@@country_set.size()": 4
 },
 {
  "employees": [
   {
    "attributes": {
     "@employer_count": 1,
     "@employer_info": [
      {
       "company_name": "company2",
       "country_name": "chn"
      }
     ],
     "@employers": [
      "company2"
     ],
     "id": "person4",
     "interest_list": [
      "football"
     ],
     "interest_set": [
      "football"
     ],
     "location_id": "us",
     "skill_list": [
      4,
      1,
      10
     ],
     "skill_set": [
      4,
      1,
      10
     ]
    },
    "v_id": "person4",
    "v_type": "Person"
   },
   {
    "attributes": {
     "@employer_count": 2,
     "@employer_info": [
      {
       "company_name": "company2",
       "country_name": "chn"
      },
      {
       "company_name": "company1",
       "country_name": "us"
      }
     ],
     "@employers": [
      "company2",
      "company1"
     ],
     "id": "person1",
     "interest_list": [
      "management",
      "financial"
     ],
     "interest_set": [
      "management",
      "financial"
     ],
     "location_id": "us",
     "skill_list": [
      1,
      2,
      3
     ],
     "skill_set": [
      1,
      2,
      3
     ]
    },
    "v_id": "person1",
    "v_type": "Person"
   },
   {
    "attributes": {
     "@employer_count": 1,
     "@employer_info": [
      {
       "company_name": "company2",
       "country_name": "chn"
      }
     ],
     "@employers": [
      "company2"
     ],
     "id": "person5",
     "interest_list": [
      "sport",
      "financial",
      "engineering"
     ],
     "interest_set": [
      "sport",
      "financial",
      "engineering"
     ],
     "location_id": "can",
     "skill_list": [
      8,
      2,
      5
     ],
     "skill_set": [
      8,
      2,
      5
     ]
    },
    "v_id": "person5",
    "v_type": "Person"
   },
   {
    "attributes": {
     "@employer_count": 2,
     "@employer_info": [
      {
       "company_name": "company3",
       "country_name": "jp"
      },
      {
       "company_name": "company1",
       "country_name": "us"
      }
     ],
     "@employers": [
      "company3",
      "company1"
     ],
     "id": "person10",
     "interest_list": [
      "football",
      "sport"
     ],
     "interest_set": [
      "football",
      "sport"
     ],
     "location_id": "us",
     "skill_list": [
      3
     ],
     "skill_set": [
      3
     ]
    },
    "v_id": "person10",
    "v_type": "Person"
   },
   {
    "attributes": {
     "@employer_count": 2,
     "@employer_info": [
      {
       "company_name": "company2",
       "country_name": "chn"
      },
      {
       "company_name": "company3",
       "country_name": "jp"
      }
     ],
     "@employers": [
      "company2",
      "company3"
     ],
     "id": "person7",
     "interest_list": [
      "art",
      "sport"
     ],
     "interest_set": [
      "art",
      "sport"
     ],
     "location_id": "us",
     "skill_list": [
      8,
      6
     ],
     "skill_set": [
      8,
      6
     ]
    },
    "v_id": "person7",
    "v_type": "Person"
   },
   {
    "attributes": {
     "@employer_count": 1,
     "@employer_info": [
      {
       "company_name": "company1",
       "country_name": "us"
      }
     ],
     "@employers": [
      "company1"
     ],
     "id": "person6",
     "interest_list": [
      "music",
      "art"
     ],
     "interest_set": [
      "music",
      "art"
     ],
     "location_id": "jp",
     "skill_list": [
      7,
      10
     ],
     "skill_set": [
      7,
      10
     ]
    },
    "v_id": "person6",
    "v_type": "Person"
   },
   {
    "attributes": {
     "@employer_count": 2,
     "@employer_info": [
      {
       "company_name": "company2",
       "country_name": "chn"
      },
      {
       "company_name": "company1",
       "country_name": "us"
      }
     ],
     "@employers": [
      "company2",
      "company1"
     ],
     "id": "person2",
     "interest_list": [
      "engineering"
     ],
     "interest_set": [
      "engineering"
     ],
     "location_id": "chn",
     "skill_list": [
      2,
      3,
      5,
      6
     ],
     "skill_set": [
      2,
      3,
      5,
      6
     ]
    },
    "v_id": "person2",
    "v_type": "Person"
   },
   {
    "attributes": {
     "@employer_count": 1,
     "@employer_info": [
      {
       "company_name": "company1",
       "country_name": "us"
      }
     ],
     "@employers": [
      "company1"
     ],
     "id": "person8",
     "interest_list": [
      "management"
     ],
     "interest_set": [
      "management"
     ],
     "location_id": "chn",
     "skill_list": [
      1,
      5,
      2
     ],
     "skill_set": [
      1,
      5,
      2
     ]
    },
    "v_id": "person8",
    "v_type": "Person"
   },
   {
    "attributes": {
     "@employer_count": 2,
     "@employer_info": [
      {
       "company_name": "company2",
       "country_name": "chn"
      },
      {
       "company_name": "company3",
       "country_name": "jp"
      }
     ],
     "@employers": [
      "company2",
      "company3"
     ],
     "id": "person9",
     "interest_list": [
      "financial",
      "teaching"
     ],
     "interest_set": [
      "financial",
      "teaching"
     ],
     "location_id": "us",
     "skill_list": [
      4,
      7,
      2
     ],
     "skill_set": [
      4,
      7,
      2
     ]
    },
    "v_id": "person9",
    "v_type": "Person"
   },
   {
    "attributes": {
     "@employer_count": 1,
     "@employer_info": [
      {
       "company_name": "company1",
       "country_name": "us"
      }
     ],
     "@employers": [
      "company1"
     ],
     "id": "person3",
     "interest_list": [
      "teaching"
     ],
     "interest_set": [
      "teaching"
     ],
     "location_id": "jp",
     "skill_list": [
      4,
      1,
      6
     ],
     "skill_set": [
      4,
      1,
      6
     ]
    },
    "v_id": "person3",
    "v_type": "Person"
   },
   {
    "attributes": {
     "@employer_count": 1,
     "@employer_info": [
      {
       "company_name": "company4",
       "country_name": "us"
      }
     ],
     "@employers": [
      "company4"
     ],
     "id": "person12",
     "interest_list": [
      "music",
      "engineering",
      "teaching",
      "teaching",
      "teaching"
     ],
     "interest_set": [
      "music",
      "engineering",
      "teaching",
      "teaching",
      "teaching"
     ],
     "location_id": "jp",
     "skill_list": [
      1,
      5,
      2,
      2,
      2
     ],
     "skill_set": [
      1,
      5,
      2
     ]
    },
    "v_id": "person12",
    "v_type": "Person"
   },
   {
    "attributes": {
     "@employer_count": 1,
     "@employer_info": [
      {
       "company_name": "company5",
       "country_name": "can"
      }
     ],
     "@employers": [
      "company5"
     ],
     "id": "person11",
     "interest_list": [
      "sport",
      "football"
     ],
     "interest_set": [
      "sport",
      "football"
     ],
     "location_id": "can",
     "skill_list": [
      10
     ],
     "skill_set": [
      10
     ]
    },
    "v_id": "person11",
    "v_type": "Person"
   }
  ]
 }
]
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

3 Twin Dolphin Drive, Ste 225 Redwood City, CA 94065 
Copyright © 2025 TigerGraph
  * ## Resources
    * [Support](https://www.tigergraph.com/support/)
    * [Community](https://community.tigergraph.com/)
    * [Developer Site](https://dev.tigergraph.com/)
    * [Test Drive](https://testdrive.tigergraph.com/)
  * ## Social
    * [Linkedin](https://www.linkedin.com/company/tigergraph/)
    * [Facebook](https://www.facebook.com/TigerGraphDB/)
    * [Twitter](https://twitter.com/tigergraphdb)
  * ## Legal
    * [Privacy Policy](https://www.tigergraph.com/privacy-policy/)
    * [Terms of Use](https://www.tigergraph.com/terms/)
    * [Sitemap](https://docs.tigergraph.com/sitemap.xml)


