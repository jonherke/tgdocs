![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions)[Next](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions)
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
[Resources](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions)
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
  * [Functions](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/)
  * [Miscellaneous Functions](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/3.6/modules/querying/pages/func/miscellaneous-functions.adoc)
### Contents
  * [coalesce()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions#_coalesce)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions#_syntax)
  * [Description](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions#_description)
  * [Return type](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions#_return_type)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions#_parameters)
  * [Example](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions#_example)
  * [evaluate()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions#_evaluate)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions#_syntax_2)
  * [Description](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions#_description_2)
  * [Return type](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions#_return_type_2)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions#_parameters_2)
  * [Example](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions#_example_2)


# Miscellaneous Functions
### Contents
  * [coalesce()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions#_coalesce)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions#_syntax)
  * [Description](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions#_description)
  * [Return type](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions#_return_type)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions#_parameters)
  * [Example](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions#_example)
  * [evaluate()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions#_evaluate)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions#_syntax_2)
  * [Description](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions#_description_2)
  * [Return type](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions#_return_type_2)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions#_parameters_2)
  * [Example](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions#_example_2)


This page lists the functions in the GSQL query language that are not tied to any single data type.
## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions#_coalesce)`coalesce()`
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions#_syntax)Syntax
`coalesce( exp [, exp ...] )`
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions#_description)Description
Returns the first expression that isn’t `NULL`.
This function requires all its arguments have the same data type (`BOOL`, `INT`, `FLOAT,` `DOUBLE`, `STRING`, or `VERTEX`). The only exception is that different numeric types can be used together. In this case, all values are converted into the first argument type.
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions#_return_type)Return type
`BOOL`, `INT`, `FLOAT,` `DOUBLE`, `STRING`, or `VERTEX`
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions#_parameters)Parameters
The function takes a number of parameters and returns the first one that does not evaluate to `NULL`
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions#_example)Example
```
CREATE QUERY coalesceFuncEx (INT p1, DOUBLE p2) FOR GRAPH social {
 PRINT COALESCE(p1, p2, 999.5); # p2 and the last value will be converted into first argument type, which is INT.
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results
```
GSQL > RUN QUERY coalesceFuncEx(_,_)
{
 "error": false,
 "message": "",
 "version": {
  "schema": 1,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"coalesce(p1,p2,999.5)": 999}]
}
GSQL > RUN QUERY coalesceFuncEx(1,2)
{
 "error": false,
 "message": "",
 "version": {
  "schema": 1,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"coalesce(p1,p2,999.5)": 1}]
}
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions#_evaluate)`evaluate()`
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions#_syntax_2)Syntax
`evaluate( expressionStr, typeStr )`
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions#_description_2)Description
Takes a string argument and interprets it as an expression which is evaluated during run-time. This enables users to create a general purpose query instead of separate queries for each specific computation.
This function cannot be nested.
The following situations generate a run-time error:
  * The expression string expressionStr cannot be compiled (unless the error is due to a non-existent vertex or edge attribute).
  * The result type of the expression does not match the parameter typeStr.


Silent failure conditions If any of the following conditions occur, the query may continue running, but the entire clause or statement in which the evaluate() function resides will fail, without producing a run-time error message. For conditional clauses (WHERE, HAVING), a failing evaluate() clause is treated as if the condition is false. An assignment statement with a failing evaluate() will not execute, and an ORDER BY clause with a failing evaluate() will not sort.
  1. The expression references a non-existent attribute of a vertex or edge alias.
  2. The expression uses an operator for non-compatible operation. For example, 123 == "xyz".

  
---  
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions#_return_type_2)Return type
Type indicated by `typeStr`
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions#_parameters_2)Parameters
Parameter | Description | Data type  
---|---|---  
`expressionStr` |  The expression to evaluate typed as a string.
  * Identifiers used in the expression can refer only to a vertex or edge aliases, vertex-attached accumulators, global accumulators, parameters, or scalar function calls involving the above variables.
  * The expression may not refer to local variables, global variables, or to FROM clause vertices or edges by type.
  * Any accumulators in the expression must be scalar accumulators (e.g., MaxAccum) for primitive-type data. Container accumulators (e.g., SetAccum) or scalar accumulators with non-primitive type (e.g. VERTEX, EDGE, DATETIME) are not supported. Container type attributes are not supported.

| `STRING`  
`typeStr` | The return type for the function call. It must be a string literal for a primitive data type, e.g., one of `"int"`, `"float"`, `"double"`, `"bool"`, `"string"` (case insensitive). The default value is `"bool"`. | `STRING`  
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions#_example_2)Example
Example query
```
CREATE QUERY evaluateEx (STRING whereCond = "TRUE", STRING postAccumIntExpr = "1") FOR GRAPH socialNet {
 SetAccum<INT> @@timeSet;
 MaxAccum<INT> @latestLikeTime, @latestLikePostTime;
 S = {person.*};
 S2 = SELECT s
    FROM S:s - (liked>:e) - post:t
    WHERE evaluate(whereCond)
    ACCUM s.@latestLikeTime += datetime_to_epoch( e.actionTime ),
       s.@latestLikePostTime += datetime_to_epoch( t.postTime )
    POST-ACCUM @@timeSet += evaluate(postAccumIntExpr, "int")
    ;
 PRINT @@timeSet;
}
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results
```
GSQL > RUN QUERY evaluateEx("s.gender==\"Male\"", "s.@latestLikePostTime")
{
 "error": false,
 "message": "",
 "results": [
  {
   "@@timeSet": [1263295325,1296752752,1297054971,1296788551]
  }
 ]
}
GSQL > RUN QUERY evaluateEx("s.gender==\"Female\"", "s.@latestLikeTime + 1")
{
 "error": false,
 "message": "",
 "results": [
  {
   "@@timeSet": [1263293536,1263352566,1263330726]
  }
 ]
}
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

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


