![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/)[Next](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/)
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
[Resources](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/)
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
  * [SELECT Statement](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/3.6/modules/querying/pages/select-statement/index.adoc)
### Contents
  * [Overview](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_overview)
  * [FROM](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_from_clause)
  * [Path pattern](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_path_pattern)
  * [Vertex and Edge Aliases](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_vertex_and_edge_aliases)
  * [SAMPLE](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_sample)
  * [WHERE](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_where)
  * [ACCUM](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_accum)
  * [Iteration model](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_iteration_model)
  * [Edge/Vertex Type Inference and Conflict](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_edgevertex_type_inference_and_conflict)
  * [Examples](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_examples)
  * [POST-ACCUM](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_post_accum_clause)
  * [Iteration model](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_iteration_model_2)
  * [Multiple POST-ACCUM clauses](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_multiple_post_accum_clauses)
  * [Examples](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_examples_2)
  * [Updating vertex-attached accumulators](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_updating_vertex_attached_accumulators)
  * [PER](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_per)
  * [HAVING](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_having)
  * [ORDER BY](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_order_by)
  * [LIMIT](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_limit)


# SELECT Statement
### Contents
  * [Overview](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_overview)
  * [FROM](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_from_clause)
  * [Path pattern](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_path_pattern)
  * [Vertex and Edge Aliases](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_vertex_and_edge_aliases)
  * [SAMPLE](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_sample)
  * [WHERE](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_where)
  * [ACCUM](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_accum)
  * [Iteration model](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_iteration_model)
  * [Edge/Vertex Type Inference and Conflict](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_edgevertex_type_inference_and_conflict)
  * [Examples](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_examples)
  * [POST-ACCUM](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_post_accum_clause)
  * [Iteration model](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_iteration_model_2)
  * [Multiple POST-ACCUM clauses](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_multiple_post_accum_clauses)
  * [Examples](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_examples_2)
  * [Updating vertex-attached accumulators](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_updating_vertex_attached_accumulators)
  * [PER](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_per)
  * [HAVING](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_having)
  * [ORDER BY](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_order_by)
  * [LIMIT](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_limit)


This page discusses the `SELECT` statement in GSQL Syntax V2, which is the default syntax for TigerGraph version 3.5 and above. To learn about the `SELECT` statement in the legacy V1 syntax, see [SELECT Statement (Syntax V1)](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/select-statement-v1)  
---  
## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_overview)Overview
The `SELECT` statement is an assignment statement with a `SELECT` block on the right-hand side.
The `SELECT` block uses a _path pattern_ to select some of the graph’s vertices and edges. There are a number of optional clauses that define and/or refine the selection by constraining the vertex or edge set or the result set. The final output of a query is either a vertex set known as the _result set_ or a table.
There is a maximum size limit of 2 GB for the result set of a `SELECT` block. If the result of the `SELECT` block is larger than 2 GB, the system will return no data. No error message is produced.
EBNF for GSQL Select Statement
```
gsqlSelectBlock := gsqlSelectClause
        fromClause
        [sampleClause]
        [whereClause]
        [accumClause]
        [postAccumClause]*
        [havingClause]
        [orderClause]
        [limitClause]
gsqlSelectClause := vertexSetName "=" SELECT vertexAlias
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The initial clause is the `SELECT` clause: `SELECT vertexAlias`. Its purpose is to specify which set of vertices from the `FROM` clause is to become the output.
The `SELECT` clause may contain only one item: a vertex alias defined in the `FROM` clause. The vertex alias may be from anywhere in a multi-hop pattern, not only an endpoint.
The [`FROM` clause](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_from_clause) defines a path pattern to traverse in the graph, and each vertex in the path pattern can be given a vertex alias. Thus, the `SELECT` clause picks the set of vertices at one of these points in the pattern — the source vertices, the target vertices, or those from an interior point in a multi-hop path — to be the output vertices.
The `SELECT` block has many optional clauses, which fit together in a logical flow. Overall, the `SELECT` block starts from a source set of vertices and returns a result set that is either a subset of the source vertices or a subset of their neighboring vertices. Along the way, computations can be performed on the selected vertices and edges.
## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_from_clause)`FROM`
The `FROM` clause describes either a single _hop_ or a multi-hop _path pattern_. Path patterns also have many other options for finer control and greater flexibility.
`FROM` clause
```
fromClause := FROM ( pathPattern ["," pathPattern]*)
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

A _hop_ or _step_ consists of going from a starting set of vertices, crossing over a set of their edges, to an ending set of vertices.
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_path_pattern)Path pattern
A path pattern specifies sets of vertex types and how they are connected by edge types.
A path pattern starts with a source vertex set, traverses through specified path edge patterns to another step vertex set. This is called a _hop_. From the other step vertex set, it can perform multiple hops and traverse to other step vertex sets.
Notice that a path pattern can be just a single source vertex set; the subsequent path edge pattern and step vertex sets are optional.
EBNF for path pattern
```
pathPattern := sourceVertexSet ["-" "(" pathEdgePattern ")" "-" stepVertexSet]*
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_source_vertex_set)Source vertex set
The source vertex set is the vertex set from which a path pattern starts. A source vertex set can be denoted by one of the following:
  * `_` or `ANY`, or omitted. If the source vertex type is omitted, you must give the source vertex set an [alias](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_vertex_and_edge_aliases).
  * Vertex type
  * A vertex set variable


Optionally, you can give a source vertex set an alias by appending the alias after a colon`:`. Although declaring an alias is optional, it is strongly recommended that you declare them. In the later clauses of the `SELECT` block , you can only refer to vertex sets in the `FROM` clause by their aliases.
EBNF for source vertex set
```
sourceVertexSet := [sourceVertexTypes] [":" vertexAlias]
sourceVertexTypes := "_" | ANY | "(" sourceVertexSetType ["|" sourceVertexSetType]* ")"
sourceVertexSetType := vertexType | vertexSetVariableName
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Belows are a few examples of valid source vertex sets in `SELECT` statements:
  * Vertex type
  * Any type
  * Vertex set


```
Result = SELECT src
  FROM Person:src -(<Likes_REVERSE)- (Comment|Post):tgt **(1)**
  WHERE src.first_name == "Viktor" AND src.last_name == "Akhiezer"
  ACCUM CASE
    WHEN tgt.type == "Comment" THEN
      src.@comment_cnt += 1
    WHEN tgt.type == "Post" THEN
      src.@post_cnt += 1
    END;
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | `Person` is a vertex type. `(Comment | POST)` combines two vertex types.  
---|---  
You can use `_` or `ANY` to represent any vertex types. You can also choose to omit the step vertex type altogether to represent any vertex type. If you choose to omit the type, you must give the step vertex set an alias.
```
Result = SELECT tgt
  FROM :s -(<Likes)- Person:tgt
  WHERE tgt.first_name == "Viktor" AND tgt.last_name == "Akhiezer"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

A source vertex set can also be represented by a vertex set variable.
```
CREATE QUERY count_friends_of_2 (VERTEX<Person> seed) FOR GRAPH Friend_Net {
  SumAccum<INT> @@num_friends = 0;
  seed_set = { seed };
  friends = SELECT v FROM seed_set:s -((Friend | Coworker):e)- :v
    ACCUM @@num_friends +=1;
  PRINT @@num_friends;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_step_vertex_set)Step vertex set
A vertex set that represents a step in a path pattern. Compared with [source vertex set](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_source_vertex_set), step vertex sets have more flexibility in how they are denoted. A step vertex set can be denoted by one of the following:
  * `_` or `ANY`, or omitted. If the step vertex type is omitted, you must give the step vertex set an alias.
  * Vertex type
  * A vertex set variable
  * A global accumulator


Optionally, you can give a source vertex set an alias by appending the alias after a colon`:`. Although declaring an alias is optional, TigerGraph strongly suggests that you declare them. In the later clauses of the `SELECT` block , you can only refer to vertex sets in the `FROM` clause by their aliases.
EBNF for step vertex set
```
stepVertexSet := [stepVertexTypes] [":" vertexAlias]
stepVertexTypes := atomicVertexType | "(" vertexSetType ["|" vertexSetType]* ")"
atomicVertexType := "_" | ANY | vertexSetType
vertexSetType := vertexType | vertexSetVariableName | globalAccumName
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Belows are a few examples of valid step vertex sets in `SELECT` statements:
  * Vertex type
  * Any type
  * Vertex set
  * Global accumulator


```
Result = SELECT tgt
  FROM Person:tgt -(<Likes_REVERSE)- (Comment|Post):src **(1)**
  WHERE tgt.firstName == "Viktor" AND tgt.lastName == "Akhiezer"
  ACCUM CASE
    WHEN src.type == "Comment" THEN
      tgt.@commentCnt += 1
    WHEN src.type == "Post" THEN
      tgt.@postCnt += 1
    END;
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | `Person` is a vertex type. `(Comment | POST)` combines two vertex types.  
---|---  
You can use `_` or `ANY` to represent any vertex types. You can also choose to omit the step vertex type altogether to represent any vertex type. If you choose to omit the type, you must give the step vertex set an alias.
```
Result = SELECT s
  FROM Person:s -(Likes>)- :tgt
  WHERE s.first_name == "Viktor" AND s.last_name == "Akhiezer"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

A step vertex set can also be represented by a vertex set variable.
```
CREATE QUERY count_friends_of_2 (VERTEX<Person> seed) FOR GRAPH Friend_Net
{
  SumAccum<INT> @@num_friends = 0;
  seed_set = { seed };
  friends = SELECT v FROM :s -((Friend | Coworker):e)- seed_set:v
   ACCUM @@num_friends +=1;
  PRINT @@num_friends;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

A step vertex set can be represented by a global accumulator of strings (the strings are vertex types). The accumulator must be of type `SetAccum`, `BagAccum` or `ListAccum`.
```
CREATE QUERY count_friends_of_2(STRING target_type) FOR GRAPH Friend_Net {
  SumAccum<INT> @@num_friends = 0;
  SetAccum<STRING> @@target_set;
  @@target_set += target_type;
  friends = SELECT s FROM :s -((Friend | Coworker):e)- @@target_set:v
   ACCUM @@num_friends +=1;
  PRINT @@num_friends;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_path_edge_pattern)Path edge pattern
The path edge pattern represents the relationship between a source vertex set to a step vertex set or from a step vertex set to the next step vertex set.
EBNF for path edge pattern
```
pathEdgePattern := atomicEdgePattern
         | "(" pathEdgePattern ")"
         | pathEdgePattern "." pathEdgePattern
         | disjPattern
         | starPattern
atomicEdgePattern := atomicEdgeType
    	    | atomicEdgeType ">"
    	    | "<" atomicEdgeType
atomicEdgeType := "_" | ANY | edgeSetType
disjPattern := atomicEdgePattern ("|" atomicEdgePattern)*
starPattern := ([atomicEdgePattern] | "(" disjPattern ")") "*" [starBounds]
starBounds := CONST_INT ".." CONST_INT
      | CONST_INT ".."
      | ".." CONST_INT
      | CONST_INT
```

A path edge pattern can represent one hop or repeated hops. A path edge pattern is denoted by `-()-`, where the relationship between vertex sets is specified between the parentheses.
#### Atomic edge pattern
The most basic form for a path edge pattern is an atomic edge pattern. An atomic edge pattern can be one of the following:
  * `_` or `ANY`.
  * An edge type.
  * A string parameter. The value of the parameter must be an edge type and can be provided at runtime. You do not need to specify a direction when using a string parameter to specify the edge type.
  * A global `SetAccum` accumulator of strings. Each string is the name of an edge type.


If the edge is directed, an atomic edge pattern has either a left pointer `<` on the left or a right pointer `>` on the right to indicate edge direction. If the edge is undirected, the atomic edge pattern does not have a pointer. Suppose we have 3 edge types or parameters called A, B, C.
  * `A>` is a rightward facing A edge
  * `<B` is a leftward facing B edge
  * C is an undirected C edge. If C is actually a directed edge type, then there is no match.


For example:
  * `-(STUDY_AT>)-` refers to forward traversal of the directed edge type `STUDY_AT`.
  * `-(<STUDY_AT)-` refers to backward traversal of the directed edge type `STUDY_AT`.
    * This means that the right side of `-(<STUDY_AT)-` is expected to have the same type as the left side of `-(STUDY_AT>)-`.
  * `-(KNOWS)-` refers to forward traversal of the undirected `KNOWS`.
  * `-(_>)-` refers to forward traversal of any directed edge types.
  * `-(_)-` refers to forward traversal of any undirected edge types.
  * `-(<_)-` refers to backward traversal of any directed edge types.


#### Disjunction pattern
Pattern disjunction allows a path edge pattern to indicate an `OR` relationship between two or more atomic patterns. If an edge matches any of the atomic patterns, the edge matches the path edge pattern.
EBNF for disjunction pattern
```
disjPattern := atomicEdgePattern ("|" atomicEdgePattern)*
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

For example:
  * `-(KNOWS|STUDY_AT>)-` refers to traversing an undirected `KNOWS` edge or a directed `STUDY_AT` edge.
  * `-(KNOWS|_>)-` refers to traversing an undirected `KNOWS` edge or any directed edge from left to right.


#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_pattern_repetition)Pattern repetition
The Kleene star`*` and `min..max` range specifiers repeat an edge pattern for a specified number of times. The range specifiers must be integers and must be constants. See [Repeating a 1-Hop Pattern](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/repeating-a-pattern) for a tutorial on how to use pattern repetition in a path edge pattern.
EBNF for star pattern
```
starPattern := ([atomicEdgePattern] | "(" disjPattern ")") "*" [starBounds]
starBounds := CONST_INT ".." CONST_INT
      | CONST_INT ".."
      | ".." CONST_INT
      | CONST_INT
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * Add `*` to the end of a pattern to have the star pattern match all paths where the edge pattern occurs one or more times.
    * For example, `Person:s - (Friendship*) - Person` matches all paths between two `Person` vertices connected by any number of `Friendship` edges.
    * The vertices in the middle do not need to be `Person` vertices. For example, a path like `person1 -(Friendship)- dog1 - (Friendship) - person2` matches the star pattern.
  * Add `*` to the end of a pattern, and then a number after the star to have the star pattern match paths where the edge pattern occurs for the specified number of times.
    * For example, `Person:s - (Friendship*2) - Person` matches all paths between two `Person` vertices connected by exactly two `Friendship` edges. The vertices in the middle do not need to be `Person` vertices.
  * Add `*` to the end of a pattern, and then a range after the star (`*x..y`) to have the star pattern match all paths where the edge pattern occurs as many times as within the specified range.
    * For example, `Employee:s - (Works_For>*2..4) - Employee` matches all paths between two `Employee` vertices with 2 - 4 right-directed `Works_For` edges. The vertices in the middle do not need to be `Person` vertices.


#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_pattern_concatenation)Pattern concatenation
The dot operator`.` means concatenate the two edge patterns into one. The vertex joining the two edges is omitted from the syntax. The dot operator is a shorthand, when you don’t care about the type of that intermediate vertex. `(A>.<B.C)` means a series of 3 edges, having the specified types and directions.
For example, the following `FROM` clauses produce the same source and target vertex sets. While the second `FROM` clause is more concise, it does not give you access to the intermediate vertex and edge sets.
```
SELECT x
FROM X:x -(E2>:e2)- Y:y -(<E3:e3)- Z:z -(E4:e4)- U:u; **(1)**

SELECT u
FROM X:x -(E2>.<E3.E4)- U:u; **(2)**
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | This `FROM` clauses uses a longer pattern, but gives you access to `y`, `e2`, `z` and `e4`.  
---|---  
**2** | This `FROM` clauses is more concise than the first `FROM` clause, but does not give you access to the intermediate vertex and edge sets.  
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_conjunctive_pattern_matching)Conjunctive Pattern Matching
The optional repeating phrase `["," pathPattern]*` allows you to have multiple path patterns. They form a conjunction, meaning all of them must be satisfied in order to have a valid match result. See [Conjunctive Pattern Matching (Beta)](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/adv/conjunctive-pattern-matching) for more details.
```
fromClause := FROM (step | stepV2 | pathPattern ["," pathPattern]*)
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Each step pattern or path pattern forms a match table, one row per matching path in the graph. Each vertex alias or edge alias is one column in the table. When we have a conjunctive path, each path must share at least one vertex alias with another path. This enables the two path sets (and match tables) to be joined. Formally, we make the natural join of the two tables.
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_vertex_and_edge_aliases)Vertex and Edge Aliases
Vertex and edge _aliases_ are declared within the `FROM` clause of a `SELECT` block, by using the colon `:`, followed by the alias name. Aliases can be accessed anywhere within the same `SELECT` block. They are used to reference a single selected vertex or edge of a set. It is through the vertex or edge aliases that the attributes of these vertices or edges can be accessed.
For example, the following code snippets show two different `SELECT` statements. The first `SELECT` statement starts from a vertex set called `allVertices`, and the vertex alias name `v` can access each individual vertex from `allVertices`. The second `SELECT` statement selects a set of edges.It can use the vertex alias `s` to reference the source vertices, or the alias `t` to reference the target vertices.
Vertex variables
```
results = SELECT v FROM all_vertices:v;
results = SELECT t FROM all_vertices:s -()- :t;
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The following example shows an edge-based `SELECT` statement, declaring aliases for all three parts of the edge. In the `ACCUM` clause, the `e` and `t` aliases are assigned to local vertex and edge variables.
Edge variables
```
results = SELECT v
  FROM all_vertices:s -(:e)- :t
  ACCUM VERTEX v = t, EDGE eg = e;
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

We strongly suggest that an alias should be declared with every vertex and edge in the FROM clause, as there are several functions and features only available to vertex and edge aliases.  
---  
## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_sample)`SAMPLE`
The `SAMPLE` clause is an optional clause that selects a uniform random sample from the population of edges or target vertices specified in the `FROM` argument.
Known issue: The `SAMPLE` clause is not supported in syntax V2 in 3.6. To use `SAMPLE` clauses, write your query in [syntax V1](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/select-statement-v1#_sample_clause).   
---  
If you want to sample from a set of vertices directly, not from edges or from neighboring (target) vertices, then the following technique is simpler and faster: Select k random vertices from a vertex set S ```
random = SELECT s
     FROM S:s
     LIMIT k;gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!
```
  
---  
The `SAMPLE` clause draws from the edge population consisting of those edges which satisfy all three parts — source set, edge type, and target type — of the `FROM` clause. The `SAMPLE` clause is intended to provide a representative sample of the distribution of edges (or vertices) connected to _hub_ vertices, instead of dealing with all edges. A _hub_ vertex is a vertex with a relatively high [degree](https://en.wikipedia.org/wiki/Degree_\(graph_theory\)).
EBNF for Sample Clause
```
sampleClause := SAMPLE ( expr | expr "%" ) EDGE WHEN condition **(1)**
       | SAMPLE expr TARGET WHEN condition       **(2)**
       | SAMPLE expr "%" TARGET PINNED WHEN condition  **(3)**
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | Sample an absolute number (or a percentage) of edges for each source vertex.  
---|---  
**2** | Sample an absolute number of edges incident to each target vertex.  
**3** | Sample a percentage of edges incident to each target vertex.  
The expression following `SAMPLE` specifies the sample size, either an absolute number or a percentage of the population. The expression in a `SAMPLE` clause must evaluate to a positive integer. There are two sampling methods:
  * Sampling based on edge ID
  * Sampling based on target vertex ID: if a target vertex ID is sampled, all edges from this source vertex to the sampled target vertex are sampled.


Currently, the `WHEN` condition that can be used with a `SAMPLE` clause is limited strictly to checking if the result of a function call on a vertex is greater than or greater than/equal to some number.  
---  
Given that the sampling is random, some details of each of the example queries may change each time they are run.
The following query displays two modes of sampling: an absolute number of edges from a source vertex and a percentage of edges from a source vertex. We use the Computer_Net graph (see Appendix D). In Computer_Net, there are 31 vertices and 43 edges, but only 7 vertices are source vertices. Moreover, c1, c12, and c23 are hub nodes, with at least 10 outgoing edges each. For the absolute count case, we set the size to 1 edge per source vertex, which is equivalent to a random walk. We expect exactly 7 edges to be selected. For the percentage sampling case, we sample 33% of the edges for vertices which have 3 or more outgoing edges. We expect about 15 edges, but the number may vary.
  * Query
  * Results


SAMPLE based on edges per source vertex
```
CREATE QUERY sample_ex_3() FOR GRAPH Computer_Net {
  // record each selected edge as (src->tgt)
  MapAccum<STRING,ListAccum<STRING>> @@abs_edges;
  SumAccum<INT> @@total_abs;
  // record each selected edge as (src->tgt)
  MapAccum<STRING,ListAccum<STRING>> @@pct_edges;
  SumAccum<INT> @@total_pct;
  start = {Computer.*};
  // Sample one outgoing edge per source vertex = Random Walk
  abs_sample = SELECT v FROM start:s -(:e)- :v
    SAMPLE 1 EDGE WHEN s.outdegree() >= 1  // sample 1 target vertex from each source vertex
    ACCUM
      @@abs_edges += (s.id -> v.id),
      @@total_abs += 1;
  PRINT @@total_abs, @@abs_edges;
  pct_sample = SELECT v FROM start:s -(:e)- :v
    SAMPLE 33% EDGE WHEN s.outdegree() >= 3 # select ~1/3 of edges when outdegree >= 3
    ACCUM
      @@pct_edges += (s.id -> v.id),
      @@total_pct += 1;
  PRINT @@total_pct, @@pct_edges;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

sampleEx3.json
```
RUN QUERY sample_ex_3()
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
   "@@total_abs": 64,
   "@@abs_edges": {
    "c31": ["c23"],
    "c30": ["c23"],
    "c11": [
     "c12",
     "c10"
    ],
    "c10": [
     "c11",
     "c1"
    ],
    "c13": ["c12"],
    "c12": [
     "c13",
     "c14",
     "c21",
     "c16",
     "c19",
     "c17",
     "c18",
     "c22",
     "c20",
     "c15",
     "c11"
    ],
    "c15": ["c12"],
    "c14": [
     "c23",
     "c24",
     "c12"
    ],
    "c17": ["c12"],
    "c16": ["c12"],
    "c19": ["c12"],
    "c18": ["c12"],
    "c20": ["c12"],
    "c22": ["c12"],
    "c21": ["c12"],
    "c24": [
     "c14",
     "c23"
    ],
    "c23": [
     "c29",
     "c31",
     "c27",
     "c26",
     "c25",
     "c24",
     "c28",
     "c30",
     "c14",
     "c4"
    ],
    "c26": ["c23"],
    "c25": ["c23"],
    "c28": ["c23"],
    "c27": ["c23"],
    "c29": ["c23"],
    "c1": [
     "c7",
     "c4",
     "c3",
     "c2",
     "c10",
     "c5",
     "c9",
     "c8",
     "c6"
    ],
    "c2": ["c1"],
    "c3": ["c1"],
    "c4": [
     "c23",
     "c1"
    ],
    "c5": ["c1"],
    "c6": ["c1"],
    "c7": ["c1"],
    "c8": ["c1"],
    "c9": ["c1"]
   }
  },
  {
   "@@total_pct": 64,
   "@@pct_edges": {
    "c31": ["c23"],
    "c30": ["c23"],
    "c11": [
     "c12",
     "c10"
    ],
    "c10": [
     "c11",
     "c1"
    ],
    "c13": ["c12"],
    "c12": [
     "c13",
     "c14",
     "c21",
     "c16",
     "c19",
     "c17",
     "c18",
     "c22",
     "c20",
     "c15",
     "c11"
    ],
    "c15": ["c12"],
    "c14": [
     "c23",
     "c24",
     "c12"
    ],
    "c17": ["c12"],
    "c16": ["c12"],
    "c19": ["c12"],
    "c18": ["c12"],
    "c20": ["c12"],
    "c22": ["c12"],
    "c21": ["c12"],
    "c24": [
     "c14",
     "c23"
    ],
    "c23": [
     "c29",
     "c31",
     "c27",
     "c26",
     "c25",
     "c24",
     "c28",
     "c30",
     "c14",
     "c4"
    ],
    "c26": ["c23"],
    "c25": ["c23"],
    "c28": ["c23"],
    "c27": ["c23"],
    "c29": ["c23"],
    "c1": [
     "c7",
     "c4",
     "c3",
     "c2",
     "c10",
     "c5",
     "c9",
     "c8",
     "c6"
    ],
    "c2": ["c1"],
    "c3": ["c1"],
    "c4": [
     "c23",
     "c1"
    ],
    "c5": ["c1"],
    "c6": ["c1"],
    "c7": ["c1"],
    "c8": ["c1"],
    "c9": ["c1"]
   }
  }
 ]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Below is an example of using `SELECT` to only traverse one edge for each source vertex. The vertex-attached accumulators `@times_traversed_no_sample` and `@times_traversed_with_sample` are used to keep track of the number of times an edge is traversed to reach the target vertex. Without using sampling, this occurs once for each edge; thus `@times_traversed_no_sample` has the same number as the in-degree of the vertex. With sampling edges, the number of edges is restricted. This is reflected in the `@times_traversed_with_sample` accumulator. Notice the difference in the result set. Because only one edge per source vertex is traversed when the `SAMPLE` clause is used, not all target vertices are reached. The vertex `company3` has 3 incident edges, but in one instance of the query execution, it is never reached. Additionally, `company2` has 6 incident edges, but only 4 source vertices sampled an edge incident to `company2`.
  * Query
  * Results


Example of `SAMPLE` using an absolute number of edges
```
CREATE QUERY sample_ex_1() FOR GRAPH Work_Net {
	SumAccum<INT> @times_traversed_no_sample;
	SumAccum<INT> @times_traversed_with_sample;
	workers = {Person.*};
	// the 'before_sample' result set encapsulates the normal functionality of
	// a SELECT statement, where 'times_traversed_no_sample' vertex accumulator is increased for
	// each edge incident to the vertex.
	before_sample = SELECT v FROM workers:t -(:e)- :v
    ACCUM v.@times_traversed_no_sample += 1;
	// The 'after_sample' result set is formed by those vertices which can be
	// reached when for each source vertex, only one edge is used for traversal.
	// This is demonstrated by the values of 'times_traversed_with_sample' vertex accumulator, which
	// is increased for each edge incident to the vertex which is used in the
	// sample.
	after_sample = SELECT v FROM workers:t -(:e)- :v
		   SAMPLE 1 EDGE WHEN t.outdegree() >= 1		// only use 1 edge from the source vertex
		   ACCUM v.@times_traversed_with_sample += 1;
	PRINT before_sample;
	PRINT after_sample;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

sampleEx1.json
```
GSQL > RUN QUERY sample_ex_1()
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [
  {"before_sample": [
   {
    "v_id": "company2",
    "attributes": {
     "country": "chn",
     "@times_traversed_with_sample": 2,
     "@times_traversed_no_sample": 6,
     "id": "company2"
    },
    "v_type": "Company"
   },
   {
    "v_id": "company4",
    "attributes": {
     "country": "us",
     "@times_traversed_with_sample": 1,
     "@times_traversed_no_sample": 1,
     "id": "company4"
    },
    "v_type": "Company"
   },
   {
    "v_id": "company3",
    "attributes": {
     "country": "jp",
     "@times_traversed_with_sample": 2,
     "@times_traversed_no_sample": 3,
     "id": "company3"
    },
    "v_type": "Company"
   },
   {
    "v_id": "company1",
    "attributes": {
     "country": "us",
     "@times_traversed_with_sample": 6,
     "@times_traversed_no_sample": 6,
     "id": "company1"
    },
    "v_type": "Company"
   },
   {
    "v_id": "company5",
    "attributes": {
     "country": "can",
     "@times_traversed_with_sample": 1,
     "@times_traversed_no_sample": 1,
     "id": "company5"
    },
    "v_type": "Company"
   }
  ]},
  {"after_sample": [
   {
    "v_id": "company2",
    "attributes": {
     "country": "chn",
     "@times_traversed_with_sample": 2,
     "@times_traversed_no_sample": 6,
     "id": "company2"
    },
    "v_type": "Company"
   },
   {
    "v_id": "company4",
    "attributes": {
     "country": "us",
     "@times_traversed_with_sample": 1,
     "@times_traversed_no_sample": 1,
     "id": "company4"
    },
    "v_type": "Company"
   },
   {
    "v_id": "company3",
    "attributes": {
     "country": "jp",
     "@times_traversed_with_sample": 2,
     "@times_traversed_no_sample": 3,
     "id": "company3"
    },
    "v_type": "Company"
   },
   {
    "v_id": "company5",
    "attributes": {
     "country": "can",
     "@times_traversed_with_sample": 1,
     "@times_traversed_no_sample": 1,
     "id": "company5"
    },
    "v_type": "Company"
   },
   {
    "v_id": "company1",
    "attributes": {
     "country": "us",
     "@times_traversed_with_sample": 6,
     "@times_traversed_no_sample": 6,
     "id": "company1"
    },
    "v_type": "Company"
   }
  ]}
 ]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Since the `PRINT` statements are placed at the end of query, the two vertex sets _beforeSample_ and _afterSample_ are almost identical, showing the final values of both accumulators `@timesTraversedNoSample` and `@timesTraversedWithSample`. There is one difference: `company3` is not included in after_sample because none of the sample-selected edges reached company3.  
---  
## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_where)`WHERE`
The `WHERE` clause is an optional clause that constrains edges and vertices specified in the `FROM` and `SAMPLE` clauses.
EBNF for `WHERE` Clause
```
whereClause := WHERE condition
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The `WHERE` clause uses a boolean condition to test each vertex or edge in the `FROM` set (or the sampled vertex and edge sets, if the `SAMPLE` clause was used). If the expression evaluates to false for vertex/edge X, then X is excluded from further consideration in the result set.
The expression may use constants or any variables or parameters within the scope of the `SELECT` block. The expression may use arithmetic operators, comparison operators, boolean operators, set operators and parentheses to enforce precedence.
The `WHERE` conditional expression may use any of the variables within its scope (global accumulators, vertex set variables, query input parameters, the `FROM` clause’s vertex and edge sets (or their vertex and edge aliases), or any of the attributes or accumulators of the vertex/edge sets.) For a more formal explanation of condition, see the EBNF definitions of `condition` and `expr`.
Using built-in vertex and edge attributes and functions, such as `.type` and `.neighbors()`, the `WHERE` clause can be used to implement sophisticated selection rules for the edge traversal. In the following example, the selection conditions are completely specified in the `WHERE` clause, with no edge types or vertex types mentioned in the `FROM` clause.
`WHERE` used as a filter
```
result_set1 = SELECT v FROM S:v-((E1|E2|E3):e)-(V1|V2):t;
result_set2 = SELECT v FROM S:v-(:e)-:t
  WHERE t.type IN ("V1", "V2") AND t IN v.neighbors("E1|E2|E3")
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The following examples demonstrate using the `WHERE` clause to limit the resulting vertex set based on a vertex attribute.
  * Query
  * Results


Basic `SELECT WHERE`
```
CREATE QUERY print_cat_posts() FOR GRAPH Social_Net {
	cat_posts = SELECT v FROM Post:v		// select only those post vertices
    WHERE v.subject == "cats"; // which have a subset of 'cats'
	PRINT cat_posts;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results for Query print_cat_posts
```
GSQL > RUN QUERY print_cat_posts()
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"cat_posts": [
  {
   "v_id": "8",
   "attributes": {
    "subject": "cats",
    "post_time": "2011-02-03 17:05:52"
   },
   "v_type": "Post"
  },
  {
   "v_id": "3",
   "attributes": {
    "subject": "cats",
    "post_time": "2011-02-05 01:02:44"
   },
   "v_type": "Post"
  },
  {
   "v_id": "9",
   "attributes": {
    "subject": "cats",
    "post_time": "2011-02-05 23:12:42"
   },
   "v_type": "Post"
  },
  {
   "v_id": "10",
   "attributes": {
    "subject": "cats",
    "post_time": "2011-02-04 03:02:31"
   },
   "v_type": "Post"
  },
  {
   "v_id": "11",
   "attributes": {
    "subject": "cats",
    "post_time": "2011-02-03 01:02:21"
   },
   "v_type": "Post"
  }
 ]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * Query
  * Results


SELECT WHERE using IN operator
```
CREATE QUERY find_graph_focused_posts() FOR GRAPH Social_Net {
	results = SELECT v FROM Post:v					// select only post vertices
		WHERE v.subject IN ("Graph", "tigergraph"); // which have a subject of either 'Graph' or 'tigergraph'
	PRINT results;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results for Query find_graph_focused_posts
```
GSQL > RUN QUERY find_graph_focused_posts()
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"results": [
  {
   "v_id": "1",
   "attributes": {
    "subject": "tigergraph",
    "post_time": "2011-03-03 23:02:00"
   },
   "v_type": "Post"
  },
  {
   "v_id": "6",
   "attributes": {
    "subject": "tigergraph",
    "post_time": "2011-02-05 02:02:05"
   },
   "v_type": "Post"
  },
  {
   "v_id": "5",
   "attributes": {
    "subject": "tigergraph",
    "post_time": "2011-02-06 01:02:02"
   },
   "v_type": "Post"
  }
 ]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

`WHERE NOT` limitations The `NOT` operator may not be used in combination with the `.type` attribute selector. To check if an edge or vertex type is not equal to a given type, use the != operator. See the example below.  
---  
The following example shows the equivalence of using `WHERE` as a type filter as well as its limitations.
  * Query
  * Results


`SELECT` statement with `WHERE` clause using `AND`/`OR`
```
CREATE QUERY find_female_members() FOR GRAPH Social_Net
{
  // Finds female person in the social network. all of the following statements
  // are equivalent (i.e., produce the same results)
	all_vertices = {ANY}; # includes all posts and person
	females = SELECT v FROM all_vertices:v
    WHERE v.type == "Person" AND v.gender != "Male";
	females = SELECT v FROM all_vertices:v
    WHERE v.type == "Person" AND v.gender == "Female";
	females = SELECT v FROM all_vertices:v
    WHERE v.type == "Person" AND
    NOT v.gender == "Male";
	females = SELECT v FROM all_vertices:v
    WHERE v.type != "Post" AND
    NOT v.gender == "Male";
 	/* does not compile. cannot use NOT operator in combination with type attribute
	 females = SELECT v FROM all_vertices:v
		 WHERE NOT v.type  != "Person" AND
		 	  NOT v.gender == "Male";
 	 does not compile. cannot use NOT operator in combination with type attribute
   females = SELECT v FROM all_vertices:v
    WHERE NOT v.type  == "Post" AND
    NOT v.gender == "Male"; */
	person_vertices = {Person.*};
	females = SELECT v FROM person_vertices:v
		  WHERE NOT v.gender == "Male";
	females = SELECT v FROM person_vertices:v
		  WHERE v.gender != "Male";
	females = SELECT v FROM person_vertices:v
		  WHERE v.gender != "Male" AND true;
	females = SELECT v FROM person_vertices:v
		  WHERE v.gender != "Male" OR false;
	PRINT females;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results for Query find_female_members
```
GSQL > RUN QUERY find_female_members()
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"females": [
  {
   "v_id": "person5",
   "attributes": {
    "gender": "Female",
    "id": "person5"
   },
   "v_type": "Person"
  },
  {
   "v_id": "person4",
   "attributes": {
    "gender": "Female",
    "id": "person4"
   },
   "v_type": "Person"
  },
  {
   "v_id": "person2",
   "attributes": {
    "gender": "Female",
    "id": "person2"
   },
   "v_type": "Person"
  }
 ]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The following example uses edge attributes to determine which workers are registered as full time for any company.
  * Query
  * Results


`WHERE` using edge attributes
```
CREATE QUERY full_time_workers() FOR GRAPH Work_Net {
	// find all workers who are full time at some company
  start = {Person.*};
	full_time_workers = SELECT v FROM start:v -(Works_For:e)- Company:t
			WHERE e.full_time;	// full_time is a boolean attribute on the edge
	PRINT full_time_workers;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

`full_time_workers` Results
```
GSQL > RUN QUERY full_time_workers()
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{"full_time_workers": [
  {
   "v_id": "person4",
   "attributes": {
    "interestList": ["football"],
    "skillSet": [ 10, 1, 4 ],
    "skillList": [ 4, 1, 10 ],
    "locationId": "us",
    "interestSet": ["football"],
    "id": "person4"
   },
   "v_type": "Person"
  },
  {
   "v_id": "person11",
   "attributes": {
    "interestList": [ "sport", "football" ],
    "skillSet": [10],
    "skillList": [10],
    "locationId": "can",
    "interestSet": [ "football", "sport" ],
    "id": "person11"
   },
   "v_type": "Person"
  },
  {
   "v_id": "person10",
   "attributes": {
    "interestList": [ "football", "sport" ],
    "skillSet": [3],
    "skillList": [3],
    "locationId": "us",
    "interestSet": [ "sport", "football" ],
    "id": "person10"
   },
   "v_type": "Person"
  },
  {
   "v_id": "person1",
   "attributes": {
    "interestList": [ "management", "financial" ],
    "skillSet": [ 3, 2, 1 ],
    "skillList": [ 1, 2, 3 ],
    "locationId": "us",
    "interestSet": [ "financial", "management" ],
    "id": "person1"
   },
   "v_type": "Person"
  },
  {
   "v_id": "person6",
   "attributes": {
    "interestList": [ "music", "art" ],
    "skillSet": [ 10, 7 ],
    "skillList": [ 7, 10 ],
    "locationId": "jp",
    "interestSet": [ "art", "music" ],
    "id": "person6"
   },
   "v_type": "Person"
  },
  {
   "v_id": "person2",
   "attributes": {
    "interestList": ["engineering"],
    "skillSet": [ 6, 5, 3, 2 ],
    "skillList": [ 2, 3, 5, 6 ],
    "locationId": "chn",
    "interestSet": ["engineering"],
    "id": "person2"
   },
   "v_type": "Person"
  },
  {
   "v_id": "person8",
   "attributes": {
    "interestList": ["management"],
    "skillSet": [ 2, 5, 1 ],
    "skillList": [ 1, 5, 2 ],
    "locationId": "chn",
    "interestSet": ["management"],
    "id": "person8"
   },
   "v_type": "Person"
  },
  {
   "v_id": "person12",
   "attributes": {
    "interestList": [
     "music",
     "engineering",
     "teaching",
     "teaching",
     "teaching"
    ],
    "skillSet": [ 2, 5, 1 ],
    "skillList": [ 1, 5, 2, 2, 2 ],
    "locationId": "jp",
    "interestSet": [ "teaching", "engineering", "music" ],
    "id": "person12"
   },
   "v_type": "Person"
  },
  {
   "v_id": "person3",
   "attributes": {
    "interestList": ["teaching"],
    "skillSet": [ 6, 1, 4 ],
    "skillList": [ 4, 1, 6 ],
    "locationId": "jp",
    "interestSet": ["teaching"],
    "id": "person3"
   },
   "v_type": "Person"
  },
  {
   "v_id": "person9",
   "attributes": {
    "interestList": [ "financial", "teaching" ],
    "skillSet": [ 2, 7, 4 ],
    "skillList": [ 4, 7, 2 ],
    "locationId": "us",
    "interestSet": [ "teaching", "financial" ],
    "id": "person9"
   },
   "v_type": "Person"
  }
 ]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

If multiple edge types are specified in edge-induced selection, the `WHERE` clause should use `OR` to separate each edge type or each target vertex type. For example, Multiple Edge Type `WHERE` clause ```
CREATE QUERY multiple_edge_type_where_ex(VERTEX<Person> m1) FOR GRAPH Social_Net {
  all_user = {m1};
  filtered_user = SELECT s
    FROM all_user:s - ((Posted|Liked|Friend):e) - (Post|Person):t
    // WHERE e.action_time > epoch_to_datetime(1) AND t.gender == "Male";
    WHERE ( e.type == "Liked" AND e.action_time > epoch_to_datetime(1) ) OR
     ( e.type == "Friend" AND t.gender == "Male" );
  PRINT filtered_user;
}gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!
```
The above query is compilable. However, if we use line 5 as the `WHERE` clause instead, the query is not compilable. The edge-type conflict checking detects an error, because it uses attributes from both `Liked` edges and `Friend` edges without separating them out by OR.  
---  
## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_accum)`ACCUM`
The `ACCUM` clause enables sophisticated aggregation and other computations across the set of vertices or edges selected by the preceding `FROM`, `SAMPLE`, and `WHERE` clauses.
### Syntax
The primary purpose of the `ACCUM` clause is to collect information about the graph by updating [accumulators](https://docs.tigergraph.com/gsql-ref/3.6/querying/accumulators) (via `+=` or `=`). However, other kinds of statements (e.g., branching, iteration, local assignments) are permitted to support more complex computations or to log activity.
The EBNF syntax below defines the allowable kinds of statements that can occur within an `ACCUM` clause.
EBNF for `ACCUM` clause
```
accumClause := [perClauseV2] ACCUM dmlSubStmtList **(1)**
dmlSubStmtList := dmlSubStmt ["," dmlSubStmt]*
dmlSubStmt := assignStmt      // Assignment **(2)** **(3)**
      | funcCallStmt     // Function Call
      | gAccumAccumStmt   // Assignment
      | lAccumAccumStmt   // Assignment
      | attrAccumStmt    // Assignment
      | vAccumFuncCall    // Function Call
      | localVarDeclStmt   // Declaration
      | dmlSubCaseStmt    // Control Flow
      | dmlSubIfStmt     // Control Flow
      | dmlSubWhileStmt   // Control Flow
      | dmlSubForEachStmt  // Control Flow
      | BREAK        // Control Flow
      | CONTINUE       // Control Flow
      | insertStmt      // Data Modification
      | dmlSubDeleteStmt   // Data Modification
      | printlnStmt     // Output
      | logStmt       // Output
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | DML-sub-statements do not include global accumulator assignment statement (gAccumAssignStmt) but global accumulator accumulation statement (gAccumAccumStmt). Global accumulators may perform accumulation `+=` but not assignment `=` within an `ACCUM` clause.  
---|---  
**2** | Global variable assignment is permitted in an `ACCUM` clause, but the change in value will not take place until the query completes. Therefore, if there are multiple assignment statements for the same variable, only the final one will take effect.  
**3** | Vertex attribute assignment `=` is not permitted in an `ACCUM` clause. However, edge attribute assignment is permitted. This is because the `ACCUM` clause iterates over an edge set. Vertex attribute assignment is permitted in the `POST-ACCUM` clause. Like all updates, the change in value does not take place until the query completes.  
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_iteration_model)Iteration model
The `ACCUM` clause is executed once for each set of vertices and edges in the graph which match the pattern and constraints given in the `FROM` and `WHERE` clauses. You can think of `FROM-WHERE` as producing a virtual table. The columns of this matching table are the alias variables from the `FROM` clause pattern, and the rows are each possible set of vertex and edge aliases (e.g. a path) which fit the pattern.
For a simple 1-hop pattern below:
```
FROM Person:A -(IS_LOCATED_IN:B)- City:C
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The above `FROM` clause produces a match table with 3 columns: A, B, and C. Each row is a tuple (A,B,C) where there is a `has_lived_in` edge B from a `Person` vertex A to a `City` vertex C. We say that the match table provides a _binding_ between the pattern aliases and graph’s vertices and edges. A multi-hop pattern simply has more columns than a 1-hop pattern.
Since the `ACCUM` clause iterates over edges, and often two edges will connect to the same source vertex or to the same target vertex, the `ACCUM` clause can be repeated multiple times for one vertex. Operations that are to be performed exactly once per vertex should be performed in the [`POST-ACCUM` clause](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_post_accum_clause).
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_parallelism_in_accum_clause)Parallelism in `ACCUM` clause
TigerGraph uses parallelism to improve performance. The statements within the `ACCUM` clause are executed sequentially for a given vertex or edge. However, there is no fixed order in which a vertex set or edge set is processed.
Within an `ACCUM` clause, each edge is handled by a separate process. As such, there is no fixed order in which the edges are processed within the `ACCUM` clause and the edges should not be treated as executing sequentially. The accumulators are mutex variables shared among each of these processes. The results of any accumulation within the `ACCUM` clause is not complete until all edges are traversed. Any inspection of an intermediate result within the `ACCUM` clause is incomplete and may not be that meaningful.
The `ACCUM` clause iterates through **all** matches. If you do not have an alias on every vertex in the pattern, then the number of **distinct** matches may be less than the number of matches. For example, consider the following clauses: ```
FROM Person:A -(Knows.Knows)- Person:C
WHERE C.email = "Andy@www.com"
ACCUM C.@pattern_count += 1gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!
```
This finds the friends of the friends of `Andy@www.com`. Suppose Andy knows 3 persons (Larry, Moe, and Curly) who know Wendy. The accumulator `C.@pattern_count` will be incremented 3 times for C = Wendy. This is similar to a SQL `SELECT C, COUNT(*) …​ GROUP BY C` query. There is no alias for the vertex in the middle of `Knows.Knows` so the identities of Larry, Moe, and Curly cannot be reported.  
---  
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_edgevertex_type_inference_and_conflict)Edge/Vertex Type Inference and Conflict
If multiple edge types are specified in an `ACCUM` clause, each `ACCUM` statement in the `ACCUM` clause checks whether edge types are conflicted. If only a subset of edge types are effective in an `ACCUM` statement, this statement is not executed on other edge types. For example:
Multiple Edge Type `ACCUM` statement check
```
CREATE QUERY multiple_edge_type_check_ex (VERTEX<Person> m1) FOR GRAPH Social_Net {
  ListAccum<STRING> @@test_list_1, @@test_list_2, @@test_list_3;
  all_user = {m1};
  all_user = SELECT s
  FROM all_user:s - ((Posted|Liked|Friend):e) - (Post|Person):t
  ACCUM @@test_list_1 += to_string(datetime_to_epoch(e.action_time)),
   @@test_list_2 += t.gender,
   @@test_list_3 += to_string(datetime_to_epoch(e.action_time)) + t.gender **(1)**
        ;
 PRINT @@test_list_1, @@test_list_2, @@test_list_3;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | This statement causes a compilation error.  
---|---  
In the above example, line 6 is only executed on `Liked` edges, because `action_time` is the attribute of `liked` edge only. Similarly, line 7 is only executed on `Friend` edges, because `gender` is the attribute of `person` only, and only `Friend` edge uses `person` as target vertex. However, line 8 causes a compilation error, because it uses multiple edges where some edges cannot be supported in a part of the statement, i.e., `liked` edges doesn’t have `t.gender`, `Friend` edges doesn’t have `e.action_time`.
We strongly suggest that if multiple edge types are specified in edge-induced selection, `ACCUM` clauses should use [`CASE` statement](https://docs.tigergraph.com/gsql-ref/3.6/querying/control-flow-statements) to separate the operation on each edge type or each target vertex type (or combination of target vertex type and edge type). The edge-type conflict checking then checks the `ACCUM` statement inside each `THEN/ELSE` blocks based on the condition. For example, Multiple Edge Type `ACCUM` statement check 2 ```
CREATE QUERY multiple_edge_type_check_ex_2(VERTEX<Person> m1) FOR GRAPH Social_Net {
  ListAccum<STRING> @@test_list1;
  all_user = {m1};
  all_user = SELECT s
    FROM all_user:s - ((Posted|Liked|Friend):e) - (Post|Person):t
    ACCUM CASE
      WHEN e.type == "Liked" THEN  // for Liked edges
        @@test_list1 += to_string(datetime_to_epoch(e.action_time))
      WHEN e.type == "Friend" THEN  // for Friend edges
        @@test_list1 += t.gender
      ELSE   // For the remaining edge type, which is Posted edges
        @@test_list1 += to_string(datetime_to_epoch(t.post_time))
      END;
  PRINT @@test_list1;
}gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!
```
The above query is compilable. However, if we switch line 8 and line 10, the edge-type conflict checking generates errors because `Liked` edges doesn’t support `t.gender` and `Friend` edges doesn’t support e.action_time.  
---  
### Examples
This example uses `ACCUM` to find all the subjects a user posted about.
  * Query
  * Results


Vertex ACCUM Example
```
CREATE QUERY user_posts() FOR GRAPH Social_Net {
  // For each person, make a list of all their post subjects
  ListAccum<STRING> @person_posts;
  start = {Person.*};
  // Find all user post topics and append them to the vertex list accum
  user_postings = SELECT s FROM start:s -(Posted)- :g
    ACCUM s.@person_posts += g.subject;
 PRINT user_postings;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results for Query user_posts
```
GSQL > RUN QUERY user_posts()
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"user_postings": [
  {
   "v_id": "person7",
   "attributes": {
    "gender": "Male",
    "@person_posts": [
     "tigergraph",
     "cats"
    ],
    "id": "person7"
   },
   "v_type": "Person"
  },
  {
   "v_id": "person5",
   "attributes": {
    "gender": "Female",
    "@person_posts": [
     "coffee",
     "cats"
    ],
    "id": "person5"
   },
   "v_type": "Person"
  },
  {
   "v_id": "person1",
   "attributes": {
    "gender": "Male",
    "@person_posts": ["Graphs"],
    "id": "person1"
   },
   "v_type": "Person"
  },
  {
   "v_id": "person4",
   "attributes": {
    "gender": "Female",
    "@person_posts": ["cats"],
    "id": "person4"
   },
   "v_type": "Person"
  },
  {
   "v_id": "person2",
   "attributes": {
    "gender": "Female",
    "@person_posts": ["tigergraph"],
    "id": "person2"
   },
   "v_type": "Person"
  },
  {
   "v_id": "person8",
   "attributes": {
    "gender": "Male",
    "@person_posts": [
     "cats",
     "Graphs"
    ],
    "id": "person8"
   },
   "v_type": "Person"
  },
  {
   "v_id": "person6",
   "attributes": {
    "gender": "Male",
    "@person_posts": [
     "tigergraph",
     "cats"
    ],
    "id": "person6"
   },
   "v_type": "Person"
  },
  {
   "v_id": "person3",
   "attributes": {
    "gender": "Male",
    "@person_posts": ["query languages"],
    "id": "person3"
   },
   "v_type": "Person"
  }
 ]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This example shows each person’s posted vertices and each person’s like behaviors (liked edges).
  * Query
  * Results


`ACCUM<VERTEX>` and `ACCUM<EDGE>` Example
```
CREATE QUERY user_posts_2() FOR GRAPH Social_Net {
  // Show each user's post and liked post time
  ListAccum<VERTEX> @person_posts;
  ListAccum<EDGE> @person_liked_info;
  start = {Person.*};
  // Find all user post topics and append them to the vertex list accum
  user_postings = SELECT s FROM start:s -(Posted)- :g
    ACCUM s.@person_posts += g;
  user_postings = SELECT s from start:s -(Liked:e)- :g
    ACCUM s.@person_liked_info += e;
  PRINT start;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results from Query user_posts2
```
GSQL > RUN QUERY user_posts2()
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"start": [
  {
   "v_id": "person7",
   "attributes": {
    "gender": "Male",
    "@person_posts": [
     "6",
     "9"
    ],
    "id": "person7",
    "@person_liked_info": [{
     "from_type": "Person",
     "to_type": "Post",
     "directed": true,
     "from_id": "person7",
     "to_id": "10",
     "attributes": {"action_time": "2010-01-12 11:22:05"},
     "e_type": "Liked"
    }]
   },
   "v_type": "Person"
  },
  {
   "v_id": "person5",
   "attributes": {
    "gender": "Female",
    "@person_posts": [
     "4",
     "11"
    ],
    "id": "person5",
    "@person_liked_info": [{
     "from_type": "Person",
     "to_type": "Post",
     "directed": true,
     "from_id": "person5",
     "to_id": "6",
     "attributes": {"action_time": "2010-01-12 21:12:05"},
     "e_type": "Liked"
    }]
   },
   "v_type": "Person"
  },
  {
   "v_id": "person1",
   "attributes": {
    "gender": "Male",
    "@person_posts": ["0"],
    "id": "person1",
    "@person_liked_info": [{
     "from_type": "Person",
     "to_type": "Post",
     "directed": true,
     "from_id": "person1",
     "to_id": "0",
     "attributes": {"action_time": "2010-01-11 11:32:00"},
     "e_type": "Liked"
    }]
   },
   "v_type": "Person"
  },
  {
   "v_id": "person4",
   "attributes": {
    "gender": "Female",
    "@person_posts": ["3"],
    "id": "person4",
    "@person_liked_info": [{
     "from_type": "Person",
     "to_type": "Post",
     "directed": true,
     "from_id": "person4",
     "to_id": "4",
     "attributes": {"action_time": "2010-01-13 03:16:05"},
     "e_type": "Liked"
    }]
   },
   "v_type": "Person"
  },
  {
   "v_id": "person2",
   "attributes": {
    "gender": "Female",
    "@person_posts": ["1"],
    "id": "person2",
    "@person_liked_info": [
     {
      "from_type": "Person",
      "to_type": "Post",
      "directed": true,
      "from_id": "person2",
      "to_id": "0",
      "attributes": {"action_time": "2010-01-12 10:52:15"},
      "e_type": "Liked"
     },
     {
      "from_type": "Person",
      "to_type": "Post",
      "directed": true,
      "from_id": "person2",
      "to_id": "3",
      "attributes": {"action_time": "2010-01-11 16:02:26"},
      "e_type": "Liked"
     }
    ]
   },
   "v_type": "Person"
  },
  {
   "v_id": "person6",
   "attributes": {
    "gender": "Male",
    "@person_posts": [
     "5",
     "10"
    ],
    "id": "person6",
    "@person_liked_info": [{
     "from_type": "Person",
     "to_type": "Post",
     "directed": true,
     "from_id": "person6",
     "to_id": "8",
     "attributes": {"action_time": "2010-01-14 11:23:05"},
     "e_type": "Liked"
    }]
   },
   "v_type": "Person"
  },
  {
   "v_id": "person8",
   "attributes": {
    "gender": "Male",
    "@person_posts": [
     "8",
     "7"
    ],
    "id": "person8",
    "@person_liked_info": [{
     "from_type": "Person",
     "to_type": "Post",
     "directed": true,
     "from_id": "person8",
     "to_id": "4",
     "attributes": {"action_time": "2010-01-11 03:26:05"},
     "e_type": "Liked"
    }]
   },
   "v_type": "Person"
  },
  {
   "v_id": "person3",
   "attributes": {
    "gender": "Male",
    "@person_posts": ["2"],
    "id": "person3",
    "@person_liked_info": [{
     "from_type": "Person",
     "to_type": "Post",
     "directed": true,
     "from_id": "person3",
     "to_id": "0",
     "attributes": {"action_time": "2010-01-16 05:15:53"},
     "e_type": "Liked"
    }]
   },
   "v_type": "Person"
  }
 ]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This example counts the total number of times each topic is used.
  * Query
  * Results


Global ACCUM Example
```
CREATE QUERY user_posts_by_topic() FOR GRAPH Social_Net {
  //Show number of total posts by topic
  MapAccum<STRING, INT> @@post_topic_counts;
  start = {Person.*};
  // Append subject and update the appearance count in the global map accum
  posts = SELECT g FROM start -(Posted)- :g
    ACCUM @@post_topic_counts += (g.subject -> 1);
  PRINT @@post_topic_counts;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results for Query user_posts_by_topic
```
GSQL > RUN QUERY user_posts_by_topic()
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"@@post_topic_counts": {
  "cats": 5,
  "coffee": 1,
  "Graphs": 2,
  "query languages": 1,
  "tigergraph": 3
 }}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_post_accum_clause)`POST-ACCUM`
The optional `POST-ACCUM` clause enables aggregation and other computations across the set of vertices (but not edges) selected by the preceding clauses. `POST-ACCUM` can be used without `ACCUM`. If it is preceded by an `ACCUM` clause, then it can be used for 2-stage accumulative computation: a first stage in `ACCUM` followed by a second stage in `POST-ACCUM`.
When you reference a vertex alias in a DML-sub statement in a `POST-ACCUM` statement, you bind that vertex alias to the `POST-ACCUM` clause implicitly. You can also explicitly bind a vertex alias with a `POST-ACCUM` clause by putting the vertex alias in parentheses immediately after the keyword `POST-ACCUM`. Each `POST-ACCUM` clause must be bound with one and only one vertex alias.
A `SELECT` statement can have multiple `POST-ACCUM` clauses. If you need to run aggregation and other computations by referencing more than one vertex alias, you can use more than one `POST-ACCUM` clause. Each `POST-ACCUM` clauses are processed in parallel; it doesn’t matter in what order you write them.
### Syntax
EBNF for `POST-ACCUM` clause
```
postAccumClause := POST-ACCUM ["(" vertexAlias ")"] dmlSubStmtList
dmlSubStmtList := dmlSubStmt ["," dmlSubStmt]*
dmlSubStmt := assignStmt      // Assignment
      | funcCallStmt     // Function Call
      | gAccumAccumStmt   // Assignment
      | lAccumAccumStmt   // Assignment
      | attrAccumStmt    // Assignment
      | vAccumFuncCall    // Function Call
      | localVarDeclStmt   // Declaration
      | dmlSubCaseStmt    // Control Flow
      | dmlSubIfStmt     // Control Flow
      | dmlSubWhileStmt   // Control Flow
      | dmlSubForEachStmt  // Control Flow
      | BREAK        // Control Flow
      | CONTINUE       // Control Flow
      | insertStmt      // Data Modification
      | dmlSubDeleteStmt   // Data Modification
      | printlnStmt     // Output
      | logStmt       // Output
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_iteration_model_2)Iteration model
The `ACCUM` clause executes **for each full path** that matches the pattern in the `FROM` clause. In contrast, the `POST-ACCUM` clause executes **for each vertex** in one vertex set; its statements can access the aggregated accumulator result computed in the `ACCUM` clause.
You can think of the matching result of the `FROM` clause and the `WHERE` clause as a virtual table. The columns of this matching table are the alias variables from the `FROM` clause pattern, and the rows are each possible set of vertex and edge aliases (e.g. a path) which fit the pattern. A `POST-ACCUM` clause acts like a `FOREACH` loop on the one of the columns of vertex result set specified in the `SELECT` clause and only occurs once for each vertex.
If you want to perform per-vertex updates for more than one vertex alias, you should use a separate `POST-ACCUM` clause for each vertex alias.
For example, below we have three `POST-ACCUM` clauses.
```
INTERPRET QUERY () {
  SumAccum<INT> @cnt1;
  SumAccum<INT> @cnt2;
  SumAccum<INT> @@global_t_count;
  R  = SELECT s
    FROM Person:s-(Likes>) -:msg - (Has_Creator>)-Person:t
    WHERE s.first_name == "Viktor" AND s.last_name == "Akhiezer"
     AND t.last_name LIKE "S%" AND year(msg.creation_date) == 2012
    ACCUM s.@cnt1 +=1 //execute this per match of the FROM pattern.
    POST-ACCUM s.@cnt2 += s.@cnt1 **(1)**
    POST-ACCUM t.@cnt2 +=1 **(2)**
    POST-ACCUM(t) @@global_t_count += 1; **(3)**
    PRINT R [R.first_name, R.last_name, R.@cnt1, R.@cnt2];
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | The first one iterates through `s`, and for each `s`, we do `s.@cnt2 += s.@cnt1`.  
---|---  
**2** | The second `POST-ACCUM` iterates through `t`.  
**3** | The third `POST-ACCUM` also iterates through `t`, but its DML-sub statements do not reference `t`. Rather, the `POST-ACCUM` is bound to `t` explicitly.  
However, the following is not allowed, since it involves two aliases (t and s) in one `POST-ACCUM` clause.
```
 POST-ACCUM t.@cnt1 += 1,
      s.@cnt1 += 1
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Also, you may not use more than one alias in a single assignment. The following is not allowed:
```
 POST-ACCUM t.@cnt1 += s.@cnt + 1
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_multiple_post_accum_clauses)Multiple `POST-ACCUM` clauses
A `SELECT` statement can have multiple `POST-ACCUM` clauses. Each `POST-ACCUM` may refer to only one vertex alias. See the [`POST-ACCUM` section in the Pattern Matching](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/multiple-hop-and-accumulation#_post_accum_clause) tutorial for more details.
### Examples
This is an example of using `ACCUM` and `POST-ACCUM` in conjunction. The `ACCUM` traverses the graph and finds all people who live and work in the same country. After this is determined, `POST-ACCUM` examines each vertex (person) to see if they work where they live.
  * Query
  * Results


Vertex `POST-ACCUM` Example
```
CREATE QUERY resident_employees() FOR GRAPH Work_Net {
  // Show all persons who both work and live in the same country
  ListAccum<STRING> @company;
  OrAccum @works_and_lives;
  start = {Person.*};
  employees = SELECT s FROM start:s -(Works_For)- :c
  // If a person works for a company in the same country where they live, add the company to the list
    ACCUM CASE
      WHEN (s.location_id == c.country) THEN
        s.@company += c.id
      END
  // Check each vertex and see if a person works where they live
    POST-ACCUM CASE
      WHEN (s.@company.size() > 0) THEN
        s.@works_and_lives += TRUE
      ELSE
        s.@works_and_lives += FALSE
      END;
  PRINT employees WHERE (employees.@works_and_lives == TRUE);
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

residentEmployees Result
```
GSQL > RUN QUERY resident_employees()
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"employees": [
  {
   "v_id": "person1",
   "attributes": {
    "skill_set": [
     1,
     2,
     3
    ],
    "skill_list": [
     1,
     2,
     3
    ],
    "@works_and_lives": true,
    "interest_list": [
     "management",
     "financial"
    ],
    "id": "person1",
    "interest_set": [
     "financial",
     "management"
    ],
    "location_id": "us",
    "@company": ["company1"]
   },
   "v_type": "Person"
  },
  {
   "v_id": "person2",
   "attributes": {
    "skill_set": [
     2,
     3,
     5,
     6
    ],
    "skill_list": [
     2,
     3,
     5,
     6
    ],
    "@works_and_lives": true,
    "interest_list": ["engineering"],
    "id": "person2",
    "interest_set": ["engineering"],
    "location_id": "chn",
    "@company": ["company2"]
   },
   "v_type": "Person"
  },
  {
   "v_id": "person11",
   "attributes": {
    "skill_set": [10],
    "skill_list": [10],
    "@works_and_lives": true,
    "interest_list": [
     "sport",
     "football"
    ],
    "id": "person11",
    "interest_set": [
     "football",
     "sport"
    ],
    "location_id": "can",
    "@company": ["company5"]
   },
   "v_type": "Person"
  },
  {
   "v_id": "person10",
   "attributes": {
    "skill_set": [3],
    "skill_list": [3],
    "@works_and_lives": true,
    "interest_list": [
     "football",
     "sport"
    ],
    "id": "person10",
    "interest_set": [
     "sport",
     "football"
    ],
    "location_id": "us",
    "@company": ["company1"]
   },
   "v_type": "Person"
  }
 ]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This is an example of a `POST-ACCUM` only that counts the number of people with a particular gender.
  * Query
  * Results


Global POST-ACCUM Example
```
CREATE QUERY person_gender(STRING gender) FOR GRAPH Social_Net {
  // Count the number of persons of a given gender
  SumAccum<INT> @@gender_count;
  start = {ANY};
  // Select all person vertices and check the gender attribute
  friends = SELECT v FROM start:v
    WHERE v.type == "Person"
    POST-ACCUM (v) CASE
      WHEN (v.gender == gender) THEN
        @@gender_count += 1
    END;
  PRINT @@gender_count;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results for Query person_gender
```
GSQL > RUN QUERY person_gender("Female")
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"@@gender_count": 3}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_updating_vertex_attached_accumulators)Updating vertex-attached accumulators
Vertices _referenced via a vertex-attached accumulator of a selected vertex_ may have their vertex-attached accumulators updated in the `ACCUM` clause (but not in the `POST-ACCUM` clause). That is, a vertex referenced by a selected vertex can be updated, with some limitations explained below. Some examples will help to illustrate this more complex condition.
  * Suppose a query declares a vertex-attached _accumulator which holds vertex information_. We call this a **vertex-holding accumulator**. This could take several forms:
    * A scalar accumulator, e.g., `MaxAccum< VERTEX > @maxV`;
    * A collection accumulator: e.g., `ListAccum< VERTEX > @listV`;
    * An accumulator containing tuple(s), where the tuple type contains a `VERTEX` field.
  * If a vertex `V` is selected, then not only can `V’s accumulators be updated, but the vertices stored in its vertex-holding accumulators can also be updated, in the `ACCUM` clause.
  * Before these indirectly referenced vertices can be used, they need to be **activated**. There are two ways to activate an indirect vertex:
    * A vertex from a vertex-holding accumulator is first assigned to a local vertex variable. The vertex can now be updated through the local vertex variable.


```
ACCUM
 vertex<Person> mx = tgt.@max_v,  # assign to local variable
 mx.@cur_id += src.id   # access via local variable
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * A FOREACH loop can iterate on a vertex-holding collection accumulator. The vertices can now be updated through the loop variable.


```
ACCUM
 FOREACH vtx IN src.@set_ids DO  # iterate on collection accumulator
   vtx.@cur_id += tgt.id    # access via loop variable
 END
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The following uses are NOT supported:
  * Indirectly activated vertices may not be updated in the `POST-ACCUM` clause or outside a `SELECT` statement.
  * Passing a vertex into the query as an input parameter is not a route to activation.
  * Using a global vertex-holding accumulator is not a route to activation.
  * If a vertex is being indirectly activated by assigning it to a local variable (e.g., a variable declaring in ACCUM or POST-ACCUM), note the following rule, which always applies to all local variables:
    * A local variable can be declared and initialized in an ACCUM block once. It cannot be declared again or reassigned later in the ACCUM block.

  
---  
The following query demonstrates updates to indirectly activated vertices.
  * Query
  * Results


Updating an Indirectly-Referenced Vertex
```
CREATE QUERY v_update_indirect_accum() FOR GRAPH Social_Net {
  SetAccum<vertex<Person>> @posters;
  SetAccum<vertex<Person>> @fellows;
  persons = {Person.*};
  // To each post, attach a list of persons who liked the post
  liked_posts = SELECT p
    FROM persons:src -(Liked:e)- Post:p
    ACCUM
    p.@posters += src;
  // To each person who liked a post, attach a list of everyone
  // who also liked one of this person's liked posts.
  liked_posts = SELECT src
    FROM liked_posts:src
    ACCUM
      FOREACH v IN src.@posters DO
        v.@fellows += src.@posters
      END
    ORDER BY src.subject;
  PRINT persons[persons.@fellows];
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results from Query v_update_indirect_accums
```
GSQL > RUN QUERY v_update_indirect_accums()
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"persons": [
  {
   "v_id": "person7",
   "attributes": {"persons.@fellows": ["person7"]},
   "v_type": "Person"
  },
  {
   "v_id": "person5",
   "attributes": {"persons.@fellows": ["person5"]},
   "v_type": "Person"
  },
  {
   "v_id": "person1",
   "attributes": {"persons.@fellows": [
    "person3",
    "person2",
    "person1"
   ]},
   "v_type": "Person"
  },
  {
   "v_id": "person4",
   "attributes": {"persons.@fellows": [
    "person4",
    "person8"
   ]},
   "v_type": "Person"
  },
  {
   "v_id": "person2",
   "attributes": {"persons.@fellows": [
    "person3",
    "person2",
    "person1"
   ]},
   "v_type": "Person"
  },
  {
   "v_id": "person3",
   "attributes": {"persons.@fellows": [
    "person3",
    "person2",
    "person1"
   ]},
   "v_type": "Person"
  },
  {
   "v_id": "person8",
   "attributes": {"persons.@fellows": [
    "person4",
    "person8"
   ]},
   "v_type": "Person"
  },
  {
   "v_id": "person6",
   "attributes": {"persons.@fellows": ["person6"]},
   "v_type": "Person"
  }
 ]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_per)`PER`
The `PER` clause is an optional prefix to an `ACCUM` clause, affecting only that clause.
The `FROM` clause of a `SELECT` statement produces a match table. The `PER` clause allows the user to specify that they wish to aggregate the match table, so that there is one row per alias. For more information see the [`PER` Clause section in the Pattern Matching tutorial](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/adv/per-clause).
## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_having)`HAVING`
The optional `HAVING` clause provides constraints on the result set of the `SELECT` statement. The constraints are applied **after** `ACCUM` and `POST-ACCUM` actions. This differs from the `WHERE` clause, which is applied **before** the `ACCUM` and `POST-ACCUM` actions.
EBNF for `HAVING` Clause
```
havingClause := HAVING condition
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The condition in a `HAVING` clause is applied to each vertex in the `SELECT` set (either source or target vertices) which also fulfilled the `FROM` and `WHERE` conditions. The `HAVING` clause is intended to test one or more of the accumulator variables that were updated in the `ACCUM` or `POST-ACCUM` clause, though the condition may be anything that equates to a boolean value. If the condition is false for a particular vertex, then that vertex is excluded from the result set.
The following example demonstrates using the `HAVING` clause to constrain a result set based on the vertex accumulator variable which was updated during the `ACCUM` clause.
  * Query
  * Results


The following query finds all persons meeting a given activity threshold, based on how many posts or likes a person has made.
```
CREATE QUERY active_members (INT activity_threshold) FOR GRAPH Social_Net {
  SumAccum<INT> @activity_amount;
  start = {Person.*};
  result = SELECT v FROM start:v -(:e)- Post:tgt
    ACCUM v.@activity_amount +=1
    HAVING v.@activity_amount >= activity_threshold;
  PRINT result;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

If the `activity_threshold` parameter is set to 3, the query returns 5 vertices:
Example 1 Results
```
GSQL > RUN QUERY active_members(3)
CREATE QUERY active_members (INT activity_threshold) FOR GRAPH Social_Net {
  SumAccum<INT> @activity_amount;
  start = {Person.*};
  result = SELECT v FROM start:v -(:e)- Post:tgt
    ACCUM v.@activity_amount +=1
    HAVING v.@activity_amount >= activity_threshold;
  PRINT result;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

If the threshold is set to 2, the query would return 8 vertices. If the threshold is set to 4, the query would return no vertices.
The following example demonstrates the equivalence of a `SELECT` statement in which the condition for the `HAVING` clause is always true.
  * Query
  * Results


The following query finds all person meeting a given activity threshold, based on how many posts or likes a person has made
Example 2. HAVING with literal condition
```
CREATE QUERY print_member_activity() FOR GRAPH Social_Net
{
  SumAccum<INT> @activity_amount;
  start = {Person.*};
  /* --- equivalent statements -----
  result = SELECT v FROM start:v -(:e)- Post:tgt
    ACCUM v.@activity_amount +=1
    HAVING true; */
  result = SELECT v FROM start:v -(:e)- Post:tgt
    ACCUM v.@activity_amount +=1;
  PRINT result;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results from Query print_member_activity
```
GSQL > RUN QUERY print_member_activity()
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"result": [
  {
   "v_id": "person7",
   "attributes": {
    "gender": "Male",
    "@activity_amount": 3,
    "id": "person7"
   },
   "v_type": "Person"
  },
  {
   "v_id": "person5",
   "attributes": {
    "gender": "Female",
    "@activity_amount": 3,
    "id": "person5"
   },
   "v_type": "Person"
  },
  {
   "v_id": "person1",
   "attributes": {
    "gender": "Male",
    "@activity_amount": 2,
    "id": "person1"
   },
   "v_type": "Person"
  },
  {
   "v_id": "person4",
   "attributes": {
    "gender": "Female",
    "@activity_amount": 2,
    "id": "person4"
   },
   "v_type": "Person"
  },
  {
   "v_id": "person3",
   "attributes": {
    "gender": "Male",
    "@activity_amount": 2,
    "id": "person3"
   },
   "v_type": "Person"
  },
  {
   "v_id": "person6",
   "attributes": {
    "gender": "Male",
    "@activity_amount": 3,
    "id": "person6"
   },
   "v_type": "Person"
  },
  {
   "v_id": "person2",
   "attributes": {
    "gender": "Female",
    "@activity_amount": 3,
    "id": "person2"
   },
   "v_type": "Person"
  },
  {
   "v_id": "person8",
   "attributes": {
    "gender": "Male",
    "@activity_amount": 3,
    "id": "person8"
   },
   "v_type": "Person"
  }
 ]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The following shows an example of equivalent result sets from using `WHERE` vs. `HAVING`. Recall that the `WHERE` clause is evaluated before the `ACCUM` and that the `HAVING` clause is evaluated after the `ACCUM`. Both constrain the result set based on a condition that vertices must meet.
  * Query


The query below computes the total post activity for each male person. Because the gender of the vertex does not change, evaluating whether the person vertex is male before the `ACCUM` clause with `WHERE` or after the `ACCUM` clause with `HAVING` does not change the result. However, if the condition in the `HAVING` clause could change within the `ACCUM` clause, these statements would produce different results.
Example 3. `HAVING` vs. `WHERE`
```
CREATE QUERY active_male_members() FOR GRAPH Social_Net
{
  SumAccum<INT> @activity_amount;
  start = {Person.*};
  // The two statements produce equivalent results
  result1 = SELECT v FROM start:v -(:e)- Post:tgt
    WHERE v.gender == "Male"
    ACCUM v.@activity_amount +=1;
  result2 = SELECT v FROM start:v -(:e)- Post:tgt
    ACCUM v.@activity_amount +=1
    HAVING v.gender == "Male";
  PRINT result1[result1.@activity_amount];
  PRINT result2[result2.@activity_amount];
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

--qio0 

Results

The following example has a compilation error because the result set is taken from the source vertices, but the `HAVING` condition is checking the target vertices.
  * Query
  * Results


This query does not compile because the having condition is testing the wrong vertex set
Example 4. `HAVING` the wrong vertex set
```
CREATE QUERY print_member_about_cats() FOR GRAPH Social_Net
{
  start = {Person.*};
  result = SELECT v FROM start:v -(:e)- Post:tgt
    HAVING tgt.subject == "cats";
  PRINT result;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Compilation Error for printMemberAboutCats
```
$ gsql printMemberAboutCats.gsql
Semantic Check Error in query printMemberAboutCats (SEM-50): line 8, col 33
The SELECT block selects src, but the HAVING clause uses tgt
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_order_by)`ORDER BY`
The optional `ORDER BY` clause sorts the result set.
EBNF for ORDER BY Clause
```
orderClause := ORDER BY expr [ASC | DESC] ["," expr [ASC | DESC]]*
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

`ASC` specifies ascending order, and `DESC` specifies descending order. If neither is specified, then ascending order is used.
Each expression must refer to the attributes or accumulators of a member of the result set, and the expression must evaluate to a sortable value (e.g., a number or a string).
`ORDER BY` offers hierarchical sorting by allowing a comma-separated list of expressions, sorting first by the leftmost expr. It uses the next expression only to sort items where the current sort expr results in identical values. Any items in the result set which cannot be sorted (because the sort expressions do not pertain to them) will appear at the end of the set, after the sorted items.
The following example demonstrates the use of `ORDER BY` with multiple expressions. The returned vertex set is first ordered by the number of friends of the vertex, and then ordered by the number of coworkers of that vertex.
  * Query
  * Results


This query finds the most popular people, sorting first based on the number of friends and then in case of a tie by the number of coworkers
Sort results in descending order
```
CREATE QUERY top_popular() FOR GRAPH Friend_Net {
	SumAccum<INT> @num_friends;
	SumAccum<INT> @num_coworkers;
	start = {Person.*};
	result = SELECT v FROM start -((Friend|Coworker):e)- Person:v
   ACCUM CASE
     WHEN e.type == "Friend" THEN v.@num_friends += 1
     WHEN e.type == "Coworker" THEN v.@num_coworkers += 1
   END
   ORDER BY v.@num_friends DESC, v.@num_coworkers DESC;
	PRINT result;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
RUN QUERY top_popular()
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"result": [
  {
   "v_id": "person9",
   "attributes": {
    "@num_friends": 5,
    "@num_coworkers": 3,
    "id": "person9"
   },
   "v_type": "Person"
  },
  {
   "v_id": "person12",
   "attributes": {
    "@num_friends": 4,
    "@num_coworkers": 1,
    "id": "person12"
   },
   "v_type": "Person"
  },
  {
   "v_id": "person8",
   "attributes": {
    "@num_friends": 4,
    "@num_coworkers": 1,
    "id": "person8"
   },
   "v_type": "Person"
  },
  {
   "v_id": "person6",
   "attributes": {
    "@num_friends": 3,
    "@num_coworkers": 4,
    "id": "person6"
   },
   "v_type": "Person"
  },
  {
   "v_id": "person1",
   "attributes": {
    "@num_friends": 3,
    "@num_coworkers": 3,
    "id": "person1"
   },
   "v_type": "Person"
  },
  {
   "v_id": "person4",
   "attributes": {
    "@num_friends": 2,
    "@num_coworkers": 5,
    "id": "person4"
   },
   "v_type": "Person"
  },
  {
   "v_id": "person2",
   "attributes": {
    "@num_friends": 2,
    "@num_coworkers": 3,
    "id": "person2"
   },
   "v_type": "Person"
  },
  {
   "v_id": "person3",
   "attributes": {
    "@num_friends": 2,
    "@num_coworkers": 3,
    "id": "person3"
   },
   "v_type": "Person"
  },
  {
   "v_id": "person10",
   "attributes": {
    "@num_friends": 2,
    "@num_coworkers": 1,
    "id": "person10"
   },
   "v_type": "Person"
  },
  {
   "v_id": "person7",
   "attributes": {
    "@num_friends": 1,
    "@num_coworkers": 6,
    "id": "person7"
   },
   "v_type": "Person"
  },
  {
   "v_id": "person5",
   "attributes": {
    "@num_friends": 1,
    "@num_coworkers": 5,
    "id": "person5"
   },
   "v_type": "Person"
  },
  {
   "v_id": "person11",
   "attributes": {
    "@num_friends": 1,
    "@num_coworkers": 1,
    "id": "person11"
   },
   "v_type": "Person"
  }
 ]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_limit)`LIMIT`
The optional `LIMIT` clause sets constraints on the number and ranking of items included in the final result set.
EBNF for `LIMIT` Clause
```
limitClause := LIMIT ( expr | expr "," expr | expr OFFSET expr )
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Each of the expression must evaluate to a non-negative integer. To understand `LIMIT`, note that the tentative result set is held in the computer as a list of vertices. If the query has an `ORDER BY` clause, the order is specified; otherwise the list order is unknown. Assume we number the vertices as `v_1` , `v_2` , …​, `v_n`. The `LIMIT` clause specifies a range of vertices, starting from a lower position in the list to an upper position.
There are three forms:
`LIMIT` scenarios
```
result = SELECT v FROM S -(:e)- :v LIMIT k; **(1)**
result = SELECT v FROM S -(:e)- :v LIMIT j, k; **(2)**
result = SELECT v FROM S -(:e)- :v LIMIT k OFFSET j; **(3)**
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | Case 1: k = Count  
---|---  
**2** | Case 2: j = Offset from the start of the list, k = Count  
**3** | Case 3: k = Count, j = Offset from the start of the list  
Case 1: `LIMIT k`
  * When a single expr is provided, `LIMIT` returns the first k elements from the tentative result set. If there are fewer than **k** elements available, then all elements will be returned in the result set. If k=5 and the tentative result set has at least 5 items, then the final result list will be [ v_1 , v_2 , v_3 , v_4 , v_5 ].


Case 2: `LIMIT j, k`
  * When a comma separates two expressions, `LIMIT` treats the first expression **j** as an offset. That is, it skips the first **j** items in the list. The second expr **k** tells the maximum number of items to include. If the list has at least 7 items, then `LIMIT 2, 5` would return `[ v_3 , v_4 , v_5, v_6 _,_ v_7 ]`.


Case 3: `LIMIT k OFFSET j`
  * The behavior of Case 3 is the same as that of Case 2, except that the syntax is different. The keyword `OFFSET` separates the two expressions, and the count comes before the offset, rather than vice versa. If the list has at least 7 items, then `LIMIT 5 OFFSET 2` would return `[ v_3 , v_4 , v_5, v_6 , v_7 ]`.


If any of the expressions evaluate to a negative integer, the results are undefined.
`OFFSET` is intended for result sets which are in a known order. It is a compile-time error to use OFFSET without the ORDER BY clause.  
---  
The following examples demonstrate the various forms of the LIMIT clause.
The first example shows the `LIMIT` clause when used as an upper limit. It returns a result set with a maximum size of 4 elements in the set.
  * Query
  * Results


limitEx1.gsql: LIMIT by some number
```
CREATE QUERY limit_ex_1 (INT k) FOR GRAPH Friend_Net {
  start = {Person.*};
  result1 = SELECT v FROM start:v
   ORDER BY v.id
   LIMIT k;
  PRINT result1[result1.id]; // api v2
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

limit_ex_1.json Results
```
RUN QUERY limit_ex_1(4)
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"result1": [
  {
   "v_id": "person1",
   "attributes": {"result1.id": "person1"},
   "v_type": "Person"
  },
  {
   "v_id": "person10",
   "attributes": {"result1.id": "person10"},
   "v_type": "Person"
  },
  {
   "v_id": "person11",
   "attributes": {"result1.id": "person11"},
   "v_type": "Person"
  },
  {
   "v_id": "person12",
   "attributes": {"result1.id": "person12"},
   "v_type": "Person"
  }
 ]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The following example shows how to use the `LIMIT` clause with an offset.
  * Query
  * Results


`LIMIT` with lower-bound and size
```
CREATE QUERY limit_ex_2 (INT j, INT k) FOR GRAPH Friend_Net
{
  start = {Person.*};
  result2 = SELECT v FROM start:v
   ORDER BY v.id
   LIMIT j, k;
  PRINT result2[result2.id]; // api v2
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

limit2Ex.json Results
```
RUN QUERY limit_ex_2(2,3)
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"result2": [
  {
   "v_id": "person11",
   "attributes": {"result2.id": "person11"},
   "v_type": "Person"
  },
  {
   "v_id": "person12",
   "attributes": {"result2.id": "person12"},
   "v_type": "Person"
  },
  {
   "v_id": "person2",
   "attributes": {"result2.id": "person2"},
   "v_type": "Person"
  }
 ]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The following example shows the alternative syntax for a result size limit with an offset. This time we try larger values for offset and size. In a large data set, `limitTest(5,20)` might return 20 vertices, but since we don’t have 25 vertices in the original data, the output is fewer than 20 vertices.
  * Query
  * Results


limit_ex_3.gsql: `LIMIT` with `OFFSET`
```
CREATE QUERY limit_ex_3 (INT j, INT k) FOR GRAPH Friend_Net {
  start = {Person.*};
  result3 = SELECT v FROM start:v
   ORDER BY v.id
   LIMIT k OFFSET j;
  PRINT result3[result3.id]; // api v2
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

limit_ex_3.json Results
```
RUN QUERY limit_ex_3(5,20)
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"result3": [
  {
   "v_id": "person3",
   "attributes": {"result3.id": "person3"},
   "v_type": "Person"
  },
  {
   "v_id": "person4",
   "attributes": {"result3.id": "person4"},
   "v_type": "Person"
  },
  {
   "v_id": "person5",
   "attributes": {"result3.id": "person5"},
   "v_type": "Person"
  },
  {
   "v_id": "person6",
   "attributes": {"result3.id": "person6"},
   "v_type": "Person"
  },
  {
   "v_id": "person7",
   "attributes": {"result3.id": "person7"},
   "v_type": "Person"
  },
  {
   "v_id": "person8",
   "attributes": {"result3.id": "person8"},
   "v_type": "Person"
  },
  {
   "v_id": "person9",
   "attributes": {"result3.id": "person9"},
   "v_type": "Person"
  }
 ]}]
}
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


