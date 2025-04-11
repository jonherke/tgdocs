![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/query-user-defined-functions)[Next](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/query-user-defined-functions)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/query-user-defined-functions)
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
[Resources](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/query-user-defined-functions)
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
  * [Query User-Defined Functions](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/query-user-defined-functions)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/3.6/modules/querying/pages/func/query-user-defined-functions.adoc)
### Contents
  * [Define a query UDF in C++](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/query-user-defined-functions#_define_a_query_udf_in_c)
  * [Use GitHub to store UDFs](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/query-user-defined-functions#_use_github_to_store_udfs)
  * [Store a UDF file locally](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/query-user-defined-functions#_store_a_udf_file_locally)
  * [Step 1: Modify current query UDF file](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/query-user-defined-functions#_step_1_modify_current_query_udf_file)
  * [Step 2: Define your function](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/query-user-defined-functions#_step_2_define_your_function)
  * [Step 3: Store the updated query UDF file](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/query-user-defined-functions#_step_3_store_the_updated_query_udf_file)
  * [Example](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/query-user-defined-functions#_example)


# Query User-Defined Functions
### Contents
  * [Define a query UDF in C++](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/query-user-defined-functions#_define_a_query_udf_in_c)
  * [Use GitHub to store UDFs](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/query-user-defined-functions#_use_github_to_store_udfs)
  * [Store a UDF file locally](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/query-user-defined-functions#_store_a_udf_file_locally)
  * [Step 1: Modify current query UDF file](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/query-user-defined-functions#_step_1_modify_current_query_udf_file)
  * [Step 2: Define your function](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/query-user-defined-functions#_step_2_define_your_function)
  * [Step 3: Store the updated query UDF file](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/query-user-defined-functions#_step_3_store_the_updated_query_udf_file)
  * [Example](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/query-user-defined-functions#_example)


In GSQL, users can supplement the language by defining their own query user-defined functions (query UDFs) in C++. Query UDFs can be called in queries and subqueries to perform a set of defined actions and return a value like the built-in functions.
This page introduces the process to define a query UDF. Once defined, the new functions are added into GSQL automatically the next time GSQL is executed.
UDFs are written in C++ in two files, `ExprFunctions.hpp` and `ExprUtil.hpp`. ExprFunctions is used for functions that are called directly in GSQL queries, while ExprUtil contains structs or helper functions that used called by the functions in ExprFunctions.
These files are stored as `.hpp` files in `AppRoot/dev/gdk/gsql/src/QueryUdf/` in a TigerGraph Server installation.
There are two ways to modify these files to add user-defined functions to GSQL:
  * Store the files in a GitHub repository, and configure GSQL to read from the repository.
  * Use `GET` and `PUT` commands to download, modify, and store the files locally.
    * The `GET` command requires the [`READ_FILE` privilege](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_privileges).
    * The `PUT` command requires the `WRITE_FILE` privilege.


It is strongly recommended that you enable GSQL user authentication by changing the password of the default user `tigergraph` to protect your UDF files. If you don’t enable user authentication, anyone with GSQL shell access can log in as the default user with `superuser` privileges and modify your files.   
---  
This section first explains how to define a query UDF, then how to integrate query UDFs into GSQL.
## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/query-user-defined-functions#_define_a_query_udf_in_c)Define a query UDF in C++
User-defined functions are C++ functions with a certain set of allowed data types. The function definition must include the keyword `inline`.
Example 1. Sample user-defined function
This is a sample function that returns `true` if the value passed to the function is greater than 3.
```
inline bool greater_than_three (double x) {
 return x > 3;
}
c++![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Table 1. Allowed Data Types in User-Defined Functions Data Type | Argument | Return | Function Body  
---|---|---|---  
`bool` | Yes | Yes | Yes  
`int` | Yes | Yes | Yes  
`uint` | Yes | Yes | Yes  
`float` | Yes | Yes | Yes  
`double` | Yes | Yes | Yes  
`string` | Yes | Yes | Yes  
`std::string` | **No** | **No** | Yes  
[Accumulators](https://docs.tigergraph.com/gsql-ref/3.6/querying/accumulators) | Yes | Yes | Yes  
All other C++ data types | **No** | **No** | Yes  
You can write your functions in the `ExprFunctions` file provided as a sample in TigerGraph Server installations, or create your own `.hpp` files from scratch.
If your function requires a user-defined struct or helper function, that struct or helper function must be defined in a separate `ExprUtil` file.
Below is an example of a short `ExprFunctions` file containing a single UDF that reverses a string. Note the `include` statement on the first line.
New code in ExprFunctions.hpp
```
#include <algorithm> // for std::reverse
inline string reverse(string str){
 std::reverse(str.begin(), str.end());
 return str;
}
c++![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/query-user-defined-functions#_use_github_to_store_udfs)Use GitHub to store UDFs
You can configure GSQL to read from a GitHub repository for ExprFunctions and ExprUtil.
If GitHub access is configured, GSQL will retrieve user source code files from GitHub before files added via `PUT`, so long as the files exist.
TigerGraph only allows one UDF file at a time. Files on GitHub take priority. If GitHub is connected but files are missing, TigerGraph will look for an UDF file added via `PUT`.   
---  
New additions to the files in the GitHub repository are instantly available in GSQL.
You can retrieve ExprFunctions.hpp and ExprUtil.hpp from `AppRoot/dev/gdk/gsql/src/QueryUdf/ExprFunctions.hpp` and copy them to a Git repository of your choice.
When the files are hosted on GitHub, the `typedef` statements and `include` directives must be part of the `.hpp` files. These are included by default in the files located in the `/QueryUDF/` folder.  
---  
The file names must be `ExprFunctions.hpp` and `ExprUtil.hpp`. This is in contrast to the `PUT` method, where the files could have any file name.
The `gadmin` configuration parameters for setting up the connection to GitHub are as follows:
Table 2. Parameters for GitHub Parameter | Description | Example  
---|---|---  
`GSQL.GithubUserAcessToken` | The credential used to access the repository | `anonymous`  
`GSQL.GithubRepository` | The user and repository where the files are held | `sample_user/repository`  
`GSQL.GithubBranch` | The branch to access | `main`  
`GSQL.GithubPath` | Path to the directory in the repository that has ExprFunctions.hpp and ExprUtil.hpp | `src/`  
`GSQL.GithubUrl` | Optional parameter used for GitHub Enterprise | `https://api.github.com[](https://api.github.com)`  
Use the [`gadmin config set`](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/management-with-gadmin#_gadmin_config_set) command to configure the aforementioned parameters to connect GSQL to the GitHub repository hosting your files.
Below is an example configuration. Remember to run `gadmin config apply` after changing the parameters. If GSQL is already running, you will need to run `gadmin restart all` to restart GSQL before the UDFs become available.
```
gadmin config set GSQL.GithubUserAcessToken anonymous
gadmin config set GSQL.GithubRepository tigergraph/ecosys
gadmin config set GSQL.GithubBranch demo_github
gadmin config set GSQL.GithubPath sample_code/src
gadmin config apply
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

After the parameters are successfully configured, you can access your UDFs in new queries right away.
## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/query-user-defined-functions#_store_a_udf_file_locally)Store a UDF file locally
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/query-user-defined-functions#_step_1_modify_current_query_udf_file)Step 1: Modify current query UDF file
Use the `GET ExprFunctions` command in GSQL to copy the current set of functions into a local file. The path can be absolute or relative to your current directory, but the file extension must be `.hpp`:
```
GSQL > GET ExprFunctions TO "/example/path/to/ExprFunctions.hpp"
GSQL > GET ExprFunctions TO "./ExprFunctions.hpp"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

If your query UDF requires a user-defined struct or helper function, also use the `GET ExprUtil` command to download the current `ExprUtil` file:
```
GSQL > GET ExprUtil TO "/example/path/ExprUtil.hpp"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/query-user-defined-functions#_step_2_define_your_function)Step 2: Define your function
Write your function in ExprFunctions and any helper functions in ExprUtil.
If any code in `ExprFunctions.hpp` or `ExprUtil.hpp` causes a compilation error, GSQL will be unable to install _any_ new queries, whether containing user-defined functions or not.  
---  
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/query-user-defined-functions#_step_3_store_the_updated_query_udf_file)Step 3: Store the updated query UDF file
After you have defined the function, use the `PUT` command to store the files you modified.
```
GSQL > PUT ExprFunctions FROM "/path/to/udf_file.hpp"
PUT ExprFunctions successfully.
GSQL > PUT ExprUtil FROM "/path/to/utils_file.hpp"
PUT ExprUtil successfully.
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The `PUT` command will automatically store the files in all nodes in a cluster, overwriting any existing files that contain UDFs.
Once the files are stored, you will be able to call the Query UDF the next time GSQL is executed. This includes the next time you start the GSQL shell or execute GSQL scripts from a bash shell. If you are using GraphStudio, however, you will be able to use the queries without needing to refresh the page.
Example of a GSQL query that uses the UDF
```
CREATE QUERY udfExample() FOR GRAPH minimalNet {
 DOUBLE x;
 BOOL y;
 x = 3.5;
 PRINT greater_than_three(x);
 y = greater_than_three(2.5);
 PRINT y;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/query-user-defined-functions#_example)Example
Suppose you are working in a distributed environment and want to add a function `rng()` that that returns a random double between 0 and 1. In this example, suppose you want to modify the ExprFunctions file locally rather than using GitHub.
Start by downloading the current UDF file with the `GET` command. In this example, we will place our download in the working directory and use the name `udf.hpp` in contrast to above, where it was named `ExprFunctions.hpp`, to illustrate the flexibility of the naming scheme.
```
GSQL > GET ExprFunctions TO "./udf.hpp"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

In the downloaded file, add the function definition for the `rng()` function.
udf.hpp
```
inline double rng() {
  std::random_device rd;
  std::mt19937 gen(rd());
  std::uniform_real_distribution < double > distribution(0.0, 1.0);
  return distribution(gen);
  }
c++![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

After adding your query, use the `PUT` command to store the file in all nodes in a cluster:
```
GSQL > PUT ExprFunctions FROM "./udf.hpp"
PUT ExprFunctions successfully.
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The file has been stored and the UDF has now been added to GSQL. You can add it to a query, then run the commands `INSTALL QUERY` and `RUN QUERY` to test the `rng()` function.
The following commands demonstrate the process with a one-line query called `rngExample` that simply prints the output of the new function `rng()`.
```
GSQL > CREATE QUERY rngExample() FOR GRAPH example_graph {PRINT rng();}
Successfully created queries: [rngExample].
GSQL > INSTALL QUERY rngExample
Start installing queries, about 1 minute ...
rngExample query: curl -X GET 'http://127.0.0.1:9000/query/example_graph/rngExample'. Add -H "Authorization: Bearer TOKEN" if authentication is enabled.
Select 'm1' as compile server, now connecting ...
Node 'm1' is prepared as compile server.
[=========================================================================================] 100% (1/1)
Query installation finished.
GSQL > RUN QUERY rngExample()
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"rng()": 0.51352}]
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


