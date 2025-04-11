![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations)[Next](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations)
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
[Resources](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations)
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
  * [Queries](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/3.6/modules/querying/pages/query-operations.adoc)
### Contents
  * [CREATE QUERY](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_create_query)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_parameters)
  * [Examples](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_examples)
  * [Default query parameter values](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_default_query_parameter_values)
  * [Dynamic querying](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_dynamic_querying)
  * [Statement types](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_statement_types)
  * [INTERPRET QUERY](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_interpret_query)
  * [Interpret an anonymous query](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#interpret-an-anonymous-query)
  * [Interpret a created query](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#interpret-a-created-query)
  * [INSTALL QUERY](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_install_query)
  * [Options for INSTALL QUERY](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_options_for_install_query)
  * [Optimize installed queries](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_optimize_installed_queries)
  * [RUN QUERY](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_run_query)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_syntax)
  * [Query parameters](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_query_parameters)
  * [Complex type parameter passing](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_complex_type_parameter_passing)
  * [Options](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_options)
  * [GSQL Query output format](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_gsql_query_output_format)
  * [Changing the default output API](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_changing_the_default_output_api)
  * [SHOW QUERY](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_show_query)
  * [DROP QUERY](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_drop_query)


# Queries
### Contents
  * [CREATE QUERY](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_create_query)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_parameters)
  * [Examples](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_examples)
  * [Default query parameter values](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_default_query_parameter_values)
  * [Dynamic querying](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_dynamic_querying)
  * [Statement types](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_statement_types)
  * [INTERPRET QUERY](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_interpret_query)
  * [Interpret an anonymous query](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#interpret-an-anonymous-query)
  * [Interpret a created query](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#interpret-a-created-query)
  * [INSTALL QUERY](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_install_query)
  * [Options for INSTALL QUERY](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_options_for_install_query)
  * [Optimize installed queries](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_optimize_installed_queries)
  * [RUN QUERY](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_run_query)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_syntax)
  * [Query parameters](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_query_parameters)
  * [Complex type parameter passing](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_complex_type_parameter_passing)
  * [Options](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_options)
  * [GSQL Query output format](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_gsql_query_output_format)
  * [Changing the default output API](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_changing_the_default_output_api)
  * [SHOW QUERY](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_show_query)
  * [DROP QUERY](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_drop_query)


A GSQL query is a sequence of data retrieval-and-computation statements executed as a single operation. Users can write queries to explore a data graph however they like, to read and make computations on the graph data along the way, to update the graph, and to deliver resulting data. A query is analogous to a user-defined procedure or function: it can have one or more input parameters, and it can produce output in two ways: by returning a value or by printing.
EBNF for `CREATE QUERY`
```
createQuery := CREATE [OR REPLACE] [DISTRIBUTED] QUERY queryName
        "(" [parameterList] ")"
        [FOR GRAPH graphName]
        [RETURNS "(" baseType | accumType ")"]
        [API "(" stringLiteral ")"]
        [SYNTAX syntaxName]
        "{" queryBody "}"
interpretQuery := INTERPRET QUERY "(" ")"
        [FOR GRAPH graphName]
        [SYNTAX syntaxName]
        "{" queryBody "}"
parameterValueList := parameterValue ["," parameterValue]*
parameterValue := parameterConstant
        | "[" parameterValue ["," parameterValue]* "]" // BAG or SET
        | "(" stringLiteral "," stringLiteral ")"    // generic VERTEX value
parameterConstant := numeric | stringLiteral | TRUE | FALSE
parameterList := parameterType paramName ["=" constant]
         ["," parameterType paramName ["=" constant]]*
syntaxName := name
queryBody := [typedefs] [declStmts] [declExceptStmts] queryBodyStmts
typedefs := (typedef ";")+
declStmts := (declStmt ";")+
declStmt := baseDeclStmt | accumDeclStmt | fileDeclStmt
declExceptStmts := (declExceptStmt ";")+
queryBodyStmts := (queryBodyStmt ";")+
installQuery := INSTALL QUERY [installOptions] ( "*" | ALL |queryName ["," queryName]* )
runQuery := RUN QUERY [runOptions] queryName "(" parameterValueList ")"
showQuery := SHOW QUERY queryName
dropQuery := DROP QUERY ( "*" | ALL | queryName ["," queryName]* )
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

A query can be run in one of three ways:
  1. Define and run an unnamed query immediately:
    1. `INTERPRET QUERY`: execute the query’s statements
Alternately, there is also a built-in REST++ endpoint to interpret a query string: `POST /gsqlserver/interpreted_query` See the [RESTPP API User Guide](https://docs.tigergraph.com/tigergraph-server/4.2/API/) for details.
  2. Define a named query and then run it.
    1. `CREATE QUERY`: define the functionality of the query
    2. `INTERPRET QUERY`: execute the query with input values
  3. Define a named query, compile it to optimize performance, and then run it.
    1. `CREATE QUERY`: define the functionality of the query
    2. `INSTALL QUERY`: compile the query
    3. `RUN QUERY`: execute the query with input values


There are some limitations to Interpreted Mode. See the section on [Interpret a created query](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#interpret-a-created-query) and the appendix section [Interpreted GSQL Limitations](https://docs.tigergraph.com/gsql-ref/3.6/appendix/interpreted-gsql-limitations).
## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_create_query)`CREATE QUERY`
```
createQuery := CREATE [OR REPLACE] [DISTRIBUTED] QUERY queryName
        "(" [parameterList] ")"
        [FOR GRAPH graphName]
        [RETURNS "(" baseType | accumType ")"]
        [API ( v2 )]
        [SYNTAX syntaxName]
        "{" queryBody "}"
queryBody := [typedefs] [declExceptStmts] queryBodyStmts
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

`CREATE QUERY` defines the functionality of a query on a given graph schema.
A query has a name, a parameter list, the name of the graph being queried, an optional `RETURNS` type (see Section "[`RETURN` Statement](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_return_statement)" for more details), optional specifiers for the output API and the language syntax version, and a body. The body consists of an optional sequence of `typedefs`, followed by an optional sequence of declarations, then followed by one or more statements. The body defines the behavior of the query.
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_parameters)Parameters 

`OR REPLACE`
    
If the optional keywords `OR REPLACE` are included, then this query definition, if error-free, replaces a previous definition with the same query name. If the original query was installed, you’ll need to reinstall the new query.
However, if there are any errors in this query definition, then the previous query definition is maintained. If the `OR REPLACE` option is not used, GSQL rejects a `CREATE QUERY` command that uses an existing name.
Only the [query owner](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_query_owner) is allowed to run `CREATE OR REPLACE` on a query. However, if you have the `WRITE_QUERY` RBAC privilege on the corresponding graph, you can execute `DROP QUERY` to drop the query and create a new one with the same name.
The difference between `CREATE OR REPLACE` and dropped the query and recreating a query are the following:
  * Only the query owner is allowed to run `CREATE OR REPLACE` on a query directly, while anyone with the `WRITE_QUERY` privilege on the corresponding graph and drop and recreate the query.
  * The ACLs on the original query are dropped when you drop the query. `CREATE OR REPLACE` keeps the original ACLs intact.

  
--- 

`DISTRIBUTED`
      
The `DISTRIBUTED` option applies only to installations where the graph has been distributed across a cluster. If specified, the query will run with a different execution model which may give better performance for queries that traverse a large portion of the cluster.For details, see [Distributed Query Mode.](https://docs.tigergraph.com/gsql-ref/3.6/querying/distributed-query-mode) 

`queryName`
    
Name of the query. 

`parameterList`
    
A list of parameters for the query. The parameter list for a query follows the following form:
```
parameterType paramName ["=" constant] ["," parameterType paramName ["=" constant]]*
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

For a list of allowed data types for query parameters, see [Query parameter types](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_query_parameter_types). 

`FOR GRAPH graphName`
    
Specifies the graph that the query is created on. This clause is optional if you have already specified a working graph either when entering GSQL or through the `USE GRAPH` command. 

`RETURNS` clause
    
The optional `RETURNS` clause makes the query a subquery and specifies the data type to be returned in the `RETRUN` statement of the subquery. For more information, see [Subqueries](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_subqueries). 

`API v2`
    
Specifies the JSON output format. The only option is v2. 

`SYNTAX syntaxName`
    
Specifies the GSQL syntax version to be used by the query. See the [Query Language Syntax Versions](https://docs.tigergraph.com/gsql-ref/3.6/querying/syntax-versions) for an outline of the differences. See [Pattern Matching tutorial](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/) for details on v2. 

`queryBody`
    
The query body contains a sequence of data retrieval-and-computation statements.
Typedefs allow the definition of custom types for use within the body. The declarations support the definition of _accumulators_ (see Chapter "[Accumulators](https://docs.tigergraph.com/gsql-ref/3.6/querying/accumulators)" for more details) and global/local variables. All accumulators and global variables must be declared before any statements.There are various types of statements that can be used within the body.
Typically, the core statement(s) in the body of a query is one or more `SELECT`, `UPDATE`, `INSERT`, `DELETE` statements. The language supports conditional statements such as an `IF` statement as well as looping constructs such as `WHILE` and `FOREACH`. It also supports calling functions, assigning variables, printing, and modifying the graph data.
The query body may include calls to other queries. That is, the other queries are treated as subquery functions. See the subsection on "[subqueries](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_subqueries)".
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_examples)Examples
Example of a `CREATE QUERY` statement
```
CREATE QUERY create_query_ex (STRING uid) FOR GRAPH Social_Net RETURNS (int) SYNTAX v2 {
  // declaration statements
  users = {Person.*};
  // body statements
  posts = SELECT p
    FROM users:u-(Posted>)-:p
    WHERE u.id == uid;
  PRINT posts;
  RETURN posts.size();
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_default_query_parameter_values)Default query parameter values
You can specify default values for parameters of primitive types when creating a query. Primitive types include:
  * `INT`
  * `UINT`
  * `FLOAT`
  * `DOUBLE`
  * `STRING`
  * `BOOL`
  * `STRING`
  * `DATETIME`


To specify the default value for a parameter, use the assignment operator (`=`) after the parameter name and specify the default value:
Example of a `CREATE QUERY` command with a default parameter value
```
CREATE QUERY create_query_ex (STRING uid = "Tom") FOR GRAPH Social_Net RETURNS (int) SYNTAX v2 {
  // declaration statements
  users = {Person.*};
  // body statements
  posts = SELECT p
    FROM users:u-(Posted>)-:p
    WHERE u.id == uid;
  PRINT posts;
  RETURN posts.size();
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_dynamic_querying)Dynamic querying
TigerGraph 3.0+ supports Dynamic Querying. This means the query can be written and installed as a saved procedure without referencing a particular graph.Schema details — the name of the graph, vertex types, edge types, and attributes — can all be parameterized and only need to be specified at run time.
Here are the ingredients for a dynamic query:
  * **Graph name:** When [creating a query](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_create_query), **`FOR GRAPH graphName`**is optional, as long as the graph has been specified already, either when entering gsql:**`GSQL -g graphName [<gsql_command>]`**or once inside the GSQL shell, by using the**`USE GRAPH graphName`**command.
  * **Vertex type and edge type in`SELECT` statements**. Typically, the [`FROM` clause](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/#_from_clause) mentions the name of specific vertex types and edge types. String or string set parameters can be used for edge and target types instead.
  * **Attribute names**. The [`getAttr` and `setAttr` functions](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods), which take attribute name and data type as string parameters, can be used to parameterize attribute access.
  * `INSERT` **statements** : If you are using [`INSERT`](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-modification-statements#_insert_into_statement) to add data to your graph, you need to specify what type of vertex or edge you want to add.This can also be parameterized.


The following example demonstrates Dynamic GSQL Query techniques using the [PageRank algorithm](https://docs.tigergraph.com/graph-ml/3.10/centrality-algorithms/pagerank) from our Graph Data Science library. The query is written with schema information embedded statically in it:
  * graph name = social
  * vertex type = Page
  * edge type = Link
  * vertex attribute = Score


  * Embedded schema
  * Dynamic querying


```
CREATE QUERY page_rank (FLOAT max_change=0.00, INT max_iter=25,
  FLOAT damping=0.85) // parameters
  FOR GRAPH Gsql_Demo
  {
  MaxAccum<float> @@max_diff = 9999;
  SumAccum<float> @rcvd_score = 0;
  SumAccum<float> @score = 1;
  Start = {Page.*};
  WHILE @@maxDiff > max_change LIMIT max_iter DO
    @@maxDiff = 0;
    V = SELECT s
      FROM Start:s -(Linkto:e)- Page:t    // hardcoded types
      ACCUM t.@rcvd_score += s.@score/(s.outdegree("Linkto")) // Param
      POST-ACCUM s.@score = (1.0-damping) + damping * s.@rcvd_score, s.@rcvd_score = 0, @@max_diff += abs(s.@score - s.@score');
  END;
  V = SELECT s FROM Start:s
   POST-ACCUM s.Score = s.@score;  // hardcoded attribute
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
CREATE QUERY pagerank_dyn (FLOAT max_change=0.00, INT max_iter=25,
 FLOAT damping=0.85, STRING v_type, STRING e_type, STRING attr)
{
  MaxAccum<FLOAT> @@max_diff = 9999;
  SumAccum<FLOAT> @rcvd_score = 0;
  SumAccum<FLOAT> @score = 1;
  Start = {v_type};
  WHILE @@max_diff > max_change LIMIT max_iter DO
    @@max_diff = 0;
    V = SELECT s
      FROM Start:s -(e_type:e)- v_type:t // Parameterized
      ACCUM t.@rcvd_score += s.@score/(s.outdegree(e_type)) //param
      POST-ACCUM s.@score = (1.0-damping) + damping * s.@rcvd_score,
        s.@rcvd_score = 0,
        @@max_diff += abs(s.@score - s.@score');
  END;
  V = SELECT s FROM Start:s
    POST-ACCUM s.setAttr(attr, s.@score); // Parameterized
}
RUN QUERY pagerank_dyn(_,_,_,"Page", "Link", "Score")
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_statement_types)Statement types
A _statement_ is a standalone instruction that expresses an action to be carried out.The most common statements are _data manipulation language (DML) statements_. DML statements include the `SELECT`, `UPDATE`, `INSERT INTO`, `DELETE FROM`, and `DELETE` statements.
A GSQL query has two levels of statements. The upper-level statement type is called _query-body-level statement_ , or _*query-body statement*_ for short. This statement type is part of either the top-level block or a query-body control flow block.For example, each of the statements at the top level directly under `CREATE QUERY` is a query-body statement. If one of the statements is a `CASE` statement with several `THEN` blocks, each of the statements in the `THEN` blocks is also a query-body statement.Each query-body statement ends with a semicolon.
The lower-level statement type is called _DML-sub-level statement_ or _DML-sub statement_ for short. This statement type is used inside certain query-body DML statements, to define particular data manipulation actions.DML-sub-statements are comma-separated. There is no comma or semicolon after the last DML-sub-statement in a block. For example, one of the top-level statements is a `SELECT` statement, each of the statements in its `ACCUM` clause is a DML-sub-statement. If one of those DML-sub-statements is a `CASE` statement, each of the statement in the `THEN` blocks is a DML-sub-statement.
There is some overlap in the types. For example, an assignment statement can be used either at the query-body level or the DML-sub-level.
```
queryBodyStmts := (queryBodyStmt ";")+
queryBodyStmt := assignStmt      // Assignment
        | vSetVarDeclStmt   // Declaration
        | gAccumAssignStmt   // Assignment
        | gAccumAccumStmt   // Assignment
        | lAccumAccumStmt   // Assignment
        | funcCallStmt     // Function Call
        | selectStmt      // Select
        | queryBodyCaseStmt  // Control Flow
        | queryBodyIfStmt   // Control Flow
        | queryBodyWhileStmt  // Control Flow
        | queryBodyForEachStmt // Control Flow
        | BREAK        // Control Flow
        | CONTINUE       // Control Flow
        | updateStmt      // Data Modification
        | insertStmt      // Data Modification
        | queryBodyDeleteStmt // Data Modification
        | printStmt      // Output
        | printlnStmt     // Output
        | logStmt       // Output
        | returnStmt      // Output
        | raiseStmt      // Exception
        | tryStmt       // Exception
DMLSubStmtList := DMLSubStmt ["," DMLSubStmt]*
DMLSubStmt := assignStmt      // Assignment
      | funcCallStmt     // Function Call
      | gAccumAccumStmt   // Assignment
      | lAccumAccumStmt   // Assignment
      | attrAccumStmt    // Assignment
      | vAccumFuncCall    // Function Call
      | localVarDeclStmt   // Declaration
      | DMLSubCaseStmt    // Control Flow
      | DMLSubIfStmt     // Control Flow
      | DMLSubWhileStmt   // Control Flow
      | DMLSubForEachStmt  // Control Flow
      | BREAK        // Control Flow
      | CONTINUE       // Control Flow
      | insertStmt      // Data Modification
      | DMLSubDeleteStmt   // Data Modification
      | printlnStmt     // Output
      | logStmt       // Output
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Guidelines for understanding statement type hierarchy:
  * Top-level statements are Query-Body type (each statement ending with a semicolon).
  * The statements within a DML statement are DML-sub statements (comma-separated list).
  * The blocks within a Control Flow statement have the same type as the entire Control Flow statement itself.


Schematic illustration of relationship between queryBodyStmt and DMLSubStmt
```
CREATE QUERY stmt_types (parameterList) FOR GRAPH g [
	other queryBodyStmt1;
	ControlFlow queryBodyStmt2  // ControlFlow inside top level.
		other queryBodyStmt2.1;   // subStmts in ControlFlow are queryBody unless inside DML.
		ControlFlow queryBodyStmt2.2 // ControlFlow inside ControlFlow inside top level
			other queryBodyStmt2.2.1;
			other queryBodyStmt2.2.2;
		END;
		DML queryBodyStmt2.3   // DML inside ControlFlow inside top-level
			other DMLSubStmt2.3.1,  // switch to DMLSubStmt
			other DMLSubStmt2.3.2
		;
	END;
	DML queryBodyStmt3      // DML inside top level.
		other DMLSubStmt3.1,   // All subStmts in DML must be DMLSubStmt type
		ControlFlow DMLSubStmt3.2 // ControlFlow inside DML inside top level
			other DMLSubStmt3.2.1,
			other DMLSubStmt3.2.2
		,
		DML DMLsubStmt3.3
			other DMLSubStmt3.3.1,
			other DMLSubStmt3.3.2
	;
	other queryBodyStmt4;
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Here is a descriptive list of query-body statements:
EBNF term | Common Name | Description  
---|---|---  
assignStmt | Assignment Statement | See "Declaration and Assignment Statements"  
vSetVarDeclStmt | Vertex Set Variable Declaration Statement | See "Declaration and Assignment Statements"  
gAccumAssignStmt | Global Accumulator Assignment Statement | See "Declaration and Assignment Statements"  
gAccumAccumStmt | Global Accumulator Accumulation Statement | See "Declaration and Assignment Statements"  
lAccumAccumStmt | Local Accumulator Accumulation Statement | See "Declaration and Assignment Statements"  
funcCallStmt | Functional Call or Query Call Statement | See "Declaration and Assignment Statements"  
selectStmt | SELECT Statement | See "SELECT Statement"  
queryBodyCaseStmt | query-body CASE statement | See "Control Flow Statements"  
queryBodyIfStmt | query-body IF statement | See "Control Flow Statements"  
queryBodyWhileStmt | query-body WHILE statement | See "Control Flow Statements"  
queryBodyForEachStmt | query-body FOREACH statement | See "Control Flow Statements"  
updateStmt | UPDATE Statement | See "Data Modification Statements"  
insertStmt | INSERT INTO statement | See "Data Modification Statements"  
queryBodyDeleteStmt | Query-body DELETE Statement | See "Data Modification Statements"  
printStmt | PRINT Statement | See "Output Statements"  
logStmt | LOG Statement | See Output Statements"  
returnStmt | RETURN Statement | See "Output Statements"  
raiseStmt | PRINT Statement | See "Exception Statements"  
tryStmt | TRY Statement | See "Exception Statements"  
Here is a descriptive list of DML-sub-statements:
EBNF term | Common Name | Description  
---|---|---  
assignStmt | Assignment Statement | See "Declaration and Assignment Statements"  
funcCallStmt | Functional Call Statement | See "Declaration and Assignment Statements"  
gAccumAccumStmt | Global Accumulator Accumulation Statement | See "Declaration and Assignment Statements"  
lAccumAccumStmt | Local Accumulator Accumulation Statement | See "Declaration and Assignment Statements"/  
attrAccumStmt | Attribute Accumulation Statement | See "Declaration and Assignment Statements"  
vAccumFuncCall | Vertex-attached Accumulator Function Call Statement | See "Declaration and Assignment Statements"  
localVarDeclStmt | Local Variable Declaration Statement | See "SELECT Statement"  
insertStmt | INSERT INTO Statement | See "Control Flow Statements"  
DMLSubDeleteStmt | DML-sub DELETE Statement | See "Data Modification Statements"  
DMLSubcaseStmt | DML-sub CASE statement | See "Data Modification Statements"  
DMLSubIfStmt | DML-sub IF statement | See "Data Modification Statements"  
DMLSubForEachStmt | DML-sub FOREACH statement | See "Data Modification Statements"  
DMLSubWhileStmt | DML-sub WHILE statement | See "Data Modification Statements"  
logStmt | LOG Statement | See "Output Statements"  
## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_interpret_query)`INTERPRET QUERY`
`INTERPRET QUERY` runs a query by translating it line-by-line. This is in contrast to the 2-step flow to [install a query](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_install_query) first and then [run the query](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_run_query).
`INTERPRET QUERY` runs a query immediately but may take longer to finish than running an installed query. `INTERPRET QUERY` also has [limitations](https://docs.tigergraph.com/gsql-ref/3.6/appendix/interpreted-gsql-limitations) and does not support all GSQL query language features.
There are two GSQL syntax options for Interpreted GSQL:
  * [Interpret an anonymous query](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#interpret-an-anonymous-query)
  * [Interpret a created query](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#interpret-a-created-query).


### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#interpret-an-anonymous-query)Interpret an anonymous query
Syntax for interpreting an anonymous query
```
interpretQuery := INTERPRET QUERY "(" ")"
        [FOR GRAPH graph_name]
        [SYNTAX syntax_name]
        "{" queryBody "}"
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This syntax is similar in concept to SQL queries. Queries are not named, do not accept parameters, and are not saved after being run.
Compare the example below to the example in the `Create Query` section:
  * No query name, no parameters, no `RETURN` statement.
  * Because no parameter is allowed, the parameter `uid` is set within the query.


Example of Immediate Mode for INTERPRET QUERY
```
INTERPRET QUERY () FOR GRAPH Social_Net {
  // declaration statements
  STRING uid = "Jane.Doe";
  users = {Person.*};
  // body statements
  posts = SELECT p
    FROM users:u-(Posted>)-:p
    WHERE u.id == uid;
  PRINT posts, posts.size();
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#interpret-a-created-query)Interpret a created query
Syntax for interpreting a created query
```
runQuery := (RUN | INTERPRET) QUERY [runOptions] queryName "(" parameterValueList ")"
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This syntax is like `RUN` query, except
  * The keyword `RUN` is replaced with `INTERPRET`.
  * Some options may not be supported.


Example of Interpret-Only Mode for INTERPRET QUERY
```
INTERPRET QUERY createQueryEx ("Jane.Doe")
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_install_query)`INSTALL QUERY`
```
installQuery := INSTALL QUERY [installOptions] ( "*" | ALL | queryName ["," queryMame]* )
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

`INSTALL QUERY` installs a query or multiple queries on a graph.Installing a query compiles the procedures described by the query as well as generates a [REST endpoint](https://docs.tigergraph.com/tigergraph-server/4.2/API/built-in-endpoints#_run_an_installed_query_get) for running the query.
Installing a query allows the query to be run through the `RUN QUERY` command as well as through its REST endpoint, both offering stronger performance as compared to running the query through the `INTERPRET QUERY` command.The `INSTALL QUERY` command will install the queries specified, with query names separated by a comma.
If a query calls a [subquery](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_subqueries), the query can only be installed after one of the following conditions is met:
  * The subquery has already been installed
  * The subquery is being installed in the same `INSTALL QUERY` command as the query itself


If a subquery that was previously installed is dropped from the graph, all installed queries that call the subquery will be disabled. To re-enable a disabled query, all its subqueries need to be installed with the same parameters and return type.
When a single `INSTALL QUERY` command installs multiple queries, each query is installed independently. If one query fails to be installed, it will not affect the installation of other queries.
To install a query, the user needs to have the `WRITE_QUERY` privilege on the graph where the query is to be installed or on the global scope.
Users can also install all uninstalled queries on a graph with `INSTALL QUERY`, using either of the following commands:
  * `INSTALL QUERY *`
  * `INSTALL QUERY ALL`


Installing takes several seconds for each query. The current version does not support concurrent installation and running of queries. Other concurrent graph operations will be delayed until the installation finishes. Concurrent `INSTALL QUERY` commands are allowed as long as only one `INSTALL QUERY` command is running on a single graph. Concurrent `INSTALL QUERY` commands are _not_ allowed on a single graph.  
---  
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_options_for_install_query)Options for `INSTALL QUERY`
The following options are available:
Option | Effect  
---|---  
`-FORCE` | Reinstall the query even if the system indicates the query is already installed. This is useful for overwriting an installation that is corrupted or otherwise outdated, without having to drop and then recreate the query. If this option is not used, the GSQL shell will refuse to re-install a query that is already installed.  
`-SINGLE` | Enables a new internal framework for compiling non-distributed queries. Equivalent to the `single_gpr` session parameter described on the [Session Parameters page.](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/system-and-language-basics#_session_parameters) The loop variable in a `FOREACH[](https://docs.tigergraph.com/gsql-ref/3.6/querying/control-flow-statements#_foreach_statement)`[ loop](https://docs.tigergraph.com/gsql-ref/3.6/querying/control-flow-statements#_foreach_statement) with this option enabled is treated as a copy, while normally, changes to the loop variable will change the value in the set or bag expression.  
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_optimize_installed_queries)Optimize installed queries
`INSTALL QUERY -OPTIMIZE`
This feature is deprecated and support for it will be dropped in a future version.   
---  
Users can run `INSTALL QUERY -OPTIMIZE` to optimize all installed queries. The names of the individual queries are not needed. This operation optimizes all previously installed queries, reducing their run times by about 20%. Optimize a query if query run time is more important to you than query installation time.
## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_run_query)RUN QUERY
The `RUN QUERY` command runs an installed query. To run a query with the `RUN QUERY` command, specify the query name, followed by the query parameters enclosed in parentheses. Running a query executes all statements in the query body and produces output as specified by the output statements in the query.
You can also run an installed query through REST requests - see [Run an installed query](https://docs.tigergraph.com/tigergraph-server/3.6/API/built-in-endpoints#_run_an_installed_query_get).
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_syntax)Syntax
RUN QUERY syntax
```
runQuery := (RUN | INTERPRET) QUERY [runOptions] queryName
  "(" parameterValueList | parameterValueJSON ")"
runOptions := ( "-av" | "-d" )*
parameterValueList := parameterValue ["," parameterValue]*
parmeterValueJSON ::= '{"'parameterName'":' parameterValue(', "'parameterName'":' parameterValue)* '}'
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_query_parameters)Query parameters
There are two ways of passing parameters to a query in a `RUN QUERY` command:
  * [Pass parameters as an ordered list separated by commas](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_parameter_list)
  * [Pass parameters by name in JSON](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_parameter_json_object)


#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_parameter_list)Parameter list
To pass parameters to a query with a list, the parameters must be put in the same order as they were in the query definition. Each value passed in will correspond to the parameter at the same index when the query was created.
To use the default value for a parameter, use the `_` character for the value of the parameter. You can also omit parameters to use their default value. However, if you omit one parameter, you also have to omit all parameters that come after that parameter.
For example, if we have the following query definition:
```
CREATE QUERY greet_person(INT age = 3, STRING name = "John",
 DATETIME birthday = to_datetime("2019-02-19 19:19:19"))
{
 PRINT age, name, birthday;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

To run the query with default values for the parameter `name,` use `_` in the place of the second parameter value:
```
GSQL > RUN QUERY greet_person (21, _, "2020-02-02 20:02:20")
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{
  "birthday": "2020-02-02 20:02:20",
  "name": "John",
  "age": 21
 }]
}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

To use the default values for both the second and the third parameters, you can omit both parameters and only provide a value for the first parameter.
```
GSQL > RUN QUERY greet_person(21)
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{
  "birthday": "2019-02-19 19:19:19",
  "name": "John",
  "age": 21
 }]
}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_parameter_json_object)Parameter JSON object
To pass query parameters by name with a JSON object, map the parameter names to their values in a JSON object enclosed in parentheses. Parameters that are not named in the JSON object will keep their default values for the execution of the query.
For example, if we have the following query:
```
CREATE QUERY greet_person(INT age = 3, STRING name = "John",
 DATETIME birthday = to_datetime("2019-02-19 19:19:19"))
{
 PRINT age, name, birthday;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Supplying the parameters with a JSON object will look like the following. The parameter `birthday` is not named in the parameter JSON object and therefore takes the default value:
```
RUN QUERY greet_person( {"name": "Emma", "age": 21} )
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_complex_type_parameter_passing)Complex type parameter passing
This subsection describes how to format the complex type parameter values when executing a query by `RUN QUERY`. More details about all parameter types are described in Section "[Query Parameter Types](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_query_parameter_types)".
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_parameter_list_2)Parameter list
Parameter type | Syntax | Example  
---|---|---  
`DATETIME` | Use a string formatted as `"YYYY-MM-DD HH-MM-SS"` | `"2019-02-19 19:19:19"`  
Set or bag of primitives | Use square brackets to enclose the collection of values. | A set of integers: `[1,5,10]`  
`VERTEX<type>` | If the vertex type is specified in the query definition, then the vertex argument is `**vertex_id**`|  The vertex type is `person` and the desired ID is `person2`. `"person2"`  
`VERTEX`(type not pre-specified) | If the type is not defined in the query definition, then the argument must provide both the id and type in parentheses:*(vertex_id, vertex_type)* | A vertex with ID `"person1"` and `type="person`: `("person1","person")`  
Set or bag of `VERTEX<type>` | Same as a SET or BAG of primitives, where the primitive type is vertex_id. | `[ "person3", "person4" ]`  
Set or bag of `VERTEX`(type not pre-specified) | Same as a SET or BAG of vertices, with vertex type not pre-specified. Square brackets enclose a comma-separated list of vertex (id, type) pairs. Mixed types are permitted. | `[ ("person1","person"),("11","post") ]`  
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_parameter_json_object_2)Parameter JSON object
Parameter type | Syntax | Example  
---|---|---  
`DATETIME` | Use a string formatted as `"YYYY-MM-DD HH-MM-SS"` | `"2019-02-19 19:19:19"`  
Set or bag of primitives | Use a JSON array containing the primitive values | `["a", "list", "of", "args"]`  
`VERTEX<type>` | Since the type is already specified in the query, you only need to use a JSON object containing the field `"id"` for the vertex ID | `{"id": "person1"}`  
`VERTEX` (type not specified) | Use a JSON object containing a field `"id"` for the vertex ID and a field `"type"` for the type of the vertex. | `{"id": "person1","type": "person"}`  
Set or bag of `VERTEX<type>` | Use a JSON array containing a list of JSON `VERTEX<type>` object | `[{"id": "person1"}, {"id": "person2"}]`  
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_options)Options
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_all_vertex_mode_av_option)All-vertex mode -av option
Some queries run with all or almost all vertices in a SELECT statement s, e.g. PageRank algorithm. In this case, the graph processing engine can run much more efficiently in all-vertex mode. In the all-vertex mode, all vertices are always selected, and the following actions become ineffective:
  * Filtering with selected vertices or vertex types. The source vertex set must be all vertices.
  * Filtering with the WHERE clause.
  * Filtering with the HAVING clause.
  * Assigning designated vertex or designated type of vertexes. E.g. X = { _vertex_type_ .*}


To run the query in all-vertex mode, use the -av option in shell mode or include `__GQUERY__USING_ALL_ACTIVE_MODE=true` in the query string of an HTTP request.
```
GSQL > RUN QUERY -av test()

## In a curl URL call. Note the use of both single and double underscores.
curl -X GET 'http://localhost:9000/query/graphname/queryname?__GQUERY__USING_ALL_ACTIVE_MODE=true'
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_detached_mode_async_option)Detached mode -async option
Typically, the GSQL `RUN QUERY` command runs in the foreground and does not produce output until the query completes, which is inconvenient in the case of long-running queries. Starting with TigerGraph 3.1, you can run queries in Detached Mode to enable background execution of long-running queries.
Queries executed in Detached mode are still subject to the system timeout limit. The default timeout limit is 16 seconds and can be set using the [`GSQL-TIMEOUT`](https://docs.tigergraph.com/tigergraph-server/4.2/API/#_gsql_query_timeout) header.
To run a query in Detached Mode from the command line, use the`-async`option for the`RUN QUERY`command:
```
GSQL > RUN QUERY -async <queryName>
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

You will receive a JSON response immediately containing a query ID (`request_id`):
```
{
 "error": false,
 "message": "The query is successfully submitted. Please check query status using the request id.",
 "request_id": "<RequestID>"
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

To run queries in Detached Mode via RESTPP endpoint call, use the `GSQL-ASYNC` header and set its value to true. If the query takes parameters, put them in the query string:
```
$ curl -s -H "GSQL-ASYNC:true" GET "http://localhost:9000/query/<graphName>/<queryName>?parameter1=<parameter1>
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

To check the status and results of the queries executed in Detached Mode, use the [**`/query_status`**](https://docs.tigergraph.com/tigergraph-server/4.2/API/built-in-endpoints#_check_query_status_detached_mode)and the[**`/query_result`**](https://docs.tigergraph.com/tigergraph-server/4.2/API/built-in-endpoints#_check_query_results_detached_mode)RESTPP endpoints.
## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_gsql_query_output_format)GSQL Query output format
The standard output of GSQL queries is in industry-standard JSON format. A JSON **object** is an unordered set of **key-value pairs** , enclosed in curly braces. Among the acceptable data types for a JSON **value** are **array** and **object**. A JSON **array** is an ordered list of **values** , enclosed in square brackets. Since values can be objects or arrays, JSON supports hierarchical, nested structures. Strings are enclosed in double quotation marks. We also use the term **field** to refer to a key (or a key-value pair) of a given object.
At the top level of the JSON structure are four required fields ("version", "error", "message", and "results") and one dependent field ("code"). If a query is successful, the value of "error" will be "false", the "message" value will be empty, and the "results" value will be the intended output of the query. If an error or exception occurred during query execution, the "error" value will be "true", the "message" value will be a string message describing the error condition, and the "results" field will be empty. Also, the "code" field will contain an error code.
Beginning with version 2 (v2) of the output specification, an additional top-level field is required: `"version"`. The `"version"` value is an object with the following fields:
Field | Description  
---|---  
`api` | String specifying the output API version. Values are specified as follows:`v1'': Output API used in TigerGraph platform v0.8 through v1.0. **NOTE: **`**v1'' support is no longer available as of TigerGraph v3.0.** ”v2” (default): Output API introduced in TigerGraph platform v1.1 This is the latest API.  
`edition` | String indicating the edition of the product.  
`schema` | Integer representing which version of the user’s graph schema is currently in use. When a `CREATE GRAPH` statement is executed, the version is initialized to 0. Each time a `SCHEMA_CHANGE JOB` is run, the schema value is incremented by 1 (e.g., 1, 2, etc.)  
Other top-level objects, such as "code" may appear in certain circumstances. Note that the top-level objects are enclosed in curly braces, meaning that they form an unordered set. They may appear in any order.
Below is an example of the output of a successful query:
Top Level JSON of a Valid Query - Example
```
{
 "version": {"edition": "developer","api": "v2","schema": "1"},
 "error": false,
 "message": "",
 "results": [
  {results_of_PRINT_statement_1},
  ...,
  {results_of_PRINT_statement_N}
 ]
}
javascript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The value of the "results" key-value pair is a sequential list of the data objects specified by the PRINT statements of the query. The list order follows the order of PRINT execution. The detailed format of the PRINT statement results is described in [Output Statements and FILE Objects](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects).
The following REST response misspells the name of the endpoint
GET echo/ Request and Response
```
curl -X GET "http://localhost:9000/eco"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

and generates the following output:
```
{
 "version": {"edition":"developer","api":"v2","schema":0},
 "error": true,
 "message": "Endpoint is not found from url = /eco, please use GET /endpoints to list all valid endpoints.",
 "code": "REST-1000"
}
javascript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_changing_the_default_output_api)Changing the default output API
The following GSQL statement can be used to set the JSON output API configuration.
```
SET json_api = <version_string>
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The only supported JSON API is "v2".   
---  
This statement sets a persistent system parameter. Each version of the TigerGraph platform is pre-configured to what was the latest output API that at the time of release.
## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_show_query)SHOW QUERY
```
showQuery := SHOW QUERY queryName
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

To show the GSQL text of a query, run `SHOW QUERY query_name` . The `query_name` argument can use `*` or `?` wildcards from Linux globbing, or it can be a regular expression when preceded by `-r`. See [SHOW: View Parts of the Catalog](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/defining-a-graph-schema#_show__view_parts_of_the_catalog)
Additionally, the `ls` GSQL command lists all created queries and identifies which queries have been installed.
## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations#_drop_query)DROP QUERY
```
dropQuery := DROP QUERY ( "*" | ALL | queryName ["," queryName]* )
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

To drop a query, run `DROP QUERY query_name` __. The query will be uninstalled (if it has been installed) and removed from the dictionary. The GSQL language will refuse to drop an installed query if another query is installed which calls query Q. That is, all calling queries must be dropped before or at the same time that their called subqueries are dropped.
To drop all queries, either of the following commands can be used:
  * `DROP QUERY ALL`
  * `DROP QUERY *`


The scope of the command depends on the user’s current scope. If the user has set a working graph, then `DROP ALL` removes all the queries for that graph. If a user has set their scope to be global, then `DROP ALL` removes all queries across all graph spaces.
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


