![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects)[Next](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects)
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
[Resources](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects)
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
  * [Output Statements and FILE Objects](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/3.6/modules/querying/pages/output-statements-and-file-objects.adoc)
### Contents
  * [PRINT Statement (API v2)](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_print_statement_api_v2)
  * [PRINT Expressions](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_print_expressions)
  * [JSON Format: Keys](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_json_format_keys)
  * [JSON Format: Values](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_json_format_values)
  * [Vertex Expression Set](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_vertex_expression_set)
  * [Printing CSV to a FILE Object](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_printing_csv_to_a_file_object)
  * [FILE println statement](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_file_println_statement)
  * [Example](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_example)
  * [Passing a FILE Object as a Parameter](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_passing_a_file_object_as_a_parameter)
  * [LOG Statement](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_log_statement)
  * [RETURN Statement](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_return_statement)


# Output Statements and FILE Objects
### Contents
  * [PRINT Statement (API v2)](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_print_statement_api_v2)
  * [PRINT Expressions](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_print_expressions)
  * [JSON Format: Keys](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_json_format_keys)
  * [JSON Format: Values](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_json_format_values)
  * [Vertex Expression Set](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_vertex_expression_set)
  * [Printing CSV to a FILE Object](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_printing_csv_to_a_file_object)
  * [FILE println statement](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_file_println_statement)
  * [Example](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_example)
  * [Passing a FILE Object as a Parameter](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_passing_a_file_object_as_a_parameter)
  * [LOG Statement](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_log_statement)
  * [RETURN Statement](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_return_statement)


## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_print_statement_api_v2)`PRINT` Statement (API v2)
The `PRINT` statement specifies output data. Each execution of a `PRINT` statement adds a JSON object to the results array which will be part of the query output. A `PRINT` statement can appear wherever query-body statements are permitted.
A `PRINT` statement does not trigger immediate output. The full set of data from all PRINT statements is delivered at one time, when the query concludes. A query can print a maximum of 2GB of data. If the output is to a `FILE` object, then the size limit does not apply.  
---  
EBNF
```
printStmt := PRINT printExpr ("," printExpr)* [WHERE condition] [TO_CSV (filePath | fileVar)]
printExpr := (expr | vExprSet) [ AS jsonKey]
      | tableName
vExprSet := expr "[" vSetProj ("," vSetProj)* "]"
vSetProj := expr [ AS jsonKey]
jsonKey := name
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Each `PRINT` statement contains a list of expressions for output data. The optional `WHERE` clause filters the output to exclude any items for which the condition is false.
Each `printExpr` contributes one key-value pair to the `PRINT` statement’s JSON object result. The optional `AS` clause sets the JSON key for the expression, overriding the default key (explained below).
If the query includes one more tabular `SELECT` statements, the `PRINT` statement can include table names. Both tabular and non-tabular `printExpr` expressions can be included in one `PRINT` statement.  
---  
Simple Example Showing JSON Output Format
```
STRING str = "first statement";
INT number = 5;
PRINT str, number;
str = "second statement";
number = number + 1;
PRINT str, number;
// The statements above produce the following output
{
 "version": {"edition": "developer","api": "v2","schema": 0},
 "error": false,
 "message": "",
 "results": [
  {
   "str": "first statement",
   "number": 5
  },
  {
   "str": "second statement",
   "number": 6
  }
 ]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_print_expressions)`PRINT` Expressions
Each `printExpr` may be one of the following:
  * A literal value
  * A global or local variable (including `VERTEX` and `EDGE` variables)
  * An attribute of a vertex variable, e.g., `Person.name`
  * A global accumulator
  * An expression whose terms are among the types above. The following operators may be used:


Data type | Operators  
---|---  
String | concatenation: `+`  
Set | `UNION INTERSECT MINUS`  
Numeric | Arithmetic: `+ - * / . %` Bit: `<< >> & |`  
Parentheses can be used for controlling order of precedence.
  1. A vertex set variable
  2. A vertex expression set `vExprSet` (only available if the output API is set to `"v2"`. Vertex expression sets are explained below in the [Vertex Expression Set](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_vertex_expression_set) section.


### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_json_format_keys)JSON Format: Keys
If a `printExpr` includes the optional `AS _*name*_`clause, then the _name_ sets the key for that expression in the JSON output. Otherwise, the following rules determine the key:
  * If the expression is simply a single variable (local variable, global variable, global accumulator, or vertex set variable), then the key is the variable name.
  * The key for a vertex expression set is the vertex set variable name.
  * Otherwise, the key is the entire expression, represented as a string.


### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_json_format_values)**JSON Format: Values**
Each data type has a distinct output format.
  * Simple numeric, string, and boolean data types follow JSON standards.
  * Lists, sets, bags, and arrays are printed as JSON **arrays** (i.e., a list enclosed in square brackets).
  * Maps and tuples are printed as JSON **objects** (i.e., a list of key:value pairs enclosed in curly braces).
  * Vertices and edges have a custom JSON object, shown below.
  * A vertex set variable is treated as a list of vertices.
  * Accumulator output format is determined by the accumulator’s return type. For example, an `AvgAccum` outputs a `DOUBLE` value, and a `BitwiseAndAccum` outputs an `INT` value. For container accumulators, simply consider whether the output is a list, set, bag, or map.
    * `ListAccum`, `SetAccum`, `BagAccum`, `ArrayAccum`: list
    * `MapAccum`: map
    * `HeapAccum`, `GroupByAccum`: list of tuples


Full details of vertices are printed only when part of a vertex set variable or vertex expression set. When a single vertex is printed (from a variable or accumulator whose data type happens to be `VERTEX`), only the vertex id is printed. Cases where only the vertex id will be printed ```
ListAccum<VERTEX> @@vList; // not a vertex set variable
VERTEX v;          // not a vertex set variable
...
PRINT @@vList, v;      // output will contain only vertex idsgsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!
```
  
---  
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_examples_of_printing_various_data_types)Examples of printing various data types
##### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_vertex_when_not_part_of_a_vertex_set_variable)Vertex (when not part of a vertex set variable)
The output is just the vertex id as a string:
```
"<vertex_id>"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

##### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_vertex_as_part_of_a_vertex_set_variable)Vertex (as part of a vertex set variable)
```
{
 "v_id":  "<vertex_id>",
 "v_type": "<vertex_type>",
 "attributes": {
  <list of key:value pairs,
   one for each attribute
   or vertex-attached accumulator>
 }
}
yaml![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

##### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_edge)Edge
```
{
 "e_type":  "<edge_type>",
 "directed": <boolean_value>,
 "from_id":  "<source_vertex_id>",
 "from_type": "<source_vertex_type>",
 "to_id":   "<target_vertex_id>",
 "to_type":  "<target_vertex_type>",
 "attributes": {
  <list of key:value pairs,
   one for each attribute>
 }
}
yaml![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

##### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_list_set_or_bag)List, Set or Bag
```
[
 <value1>,
 <value2>,
 ...,
 <valueN>
]
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

##### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_map)Map
```
{
 <key1>: <value1>,
 <key2>: <value2>,
 ...,
 <keyN>: <valueN>
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

##### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_tuple)Tuple
```
{
 <fieldName1>: <value1>,
 <fieldName2>: <value2>,
 ...,
 <fieldNameN>: <valueN>
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

##### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_vertex_set_variable)Vertex Set Variable
```
[
 <vertex1>,
 <vertex2>,
 ...,
 <vertexN>
]
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_vertex_expression_set)Vertex Expression Set
A vertex expression set is a list of expressions applied to each vertex in a vertex set variable. The expression list is used to compute an alternative set of values to display in the "attributes" field of each vertex.
The easiest way to understand this is to consider examples containing only one term and then consider combinations.
Example Query for Vertex Expression Set
In this example, C is a vertex set variable containing the set of all company vertices. Furthermore, each vertex has a vertex-attached accumulator @count.
```
// CREATE VERTEX company(PRIMARY_ID clientId STRING, id STRING, country STRING)
CREATE QUERY v_expr_set () FOR GRAPH Work_Net {
  SumAccum<INT> @count;
  C = {Company.*};
  // include some print statements here
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

If we print the full vertex set, the "attributes" field of each vertex will contain 3 fields: "id", "country", and "@count". Now consider some simple vertex expression sets:
  * `PRINT C[C.country]` prints the vertex set variable C, except that the "attributes" field will contain only "country", instead of 3 fields.
  * `PRINT C[C.@count]` prints the vertex set variable C, except that the "attributes" field will contain only "@count", instead of 3 fields.
  * `PRINT C[C.@count AS company_count]` prints the same as above, except that the "@count" accumulator is aliased as "company_count".
  * `PRINT C[C.id, C.@count]` prints the vertex set variable C, except that the "attributes" field will contain only "id" and "@count".
  * `PRINT C[C.id+"_ex", C.@count+1]` prints the vertex set variable C, except that the "attributes" field contains the following:
    * One field consists of each vertex’s id value, with the string "_ex" appended to it.
    * Another field consists of the @count value incremented by 1. Note: the value of @count itself has not changed, only the displayed value is incremented.


The last example illustrates the general format for a vertex expression set:
Syntax for Vertex Expression Set
```
vExprSet := expr "[" vSetProj {, vSetProj} "]"
vSetProj := expr [ AS name]
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The vertex expression set begins with the name of a vertex set variable, followed by a list of attribute expressions enclosed in square brackets. Each attribute expression follows the same rules described earlier in the [`PRINT` Expressions](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_print_expressions) section.
That is, each attribute expression may refer to one or more attributes or vertex-attached accumulators of the current vertices, as well as literals, local or global variables, and global accumulators. The allowed operators (for numeric, string, or set operations) are the same ones mentioned above.
The _key_ for the vertex expression set is the vertex set variable name.
The _value_ for the vertex expression set is a modified vertex set variable, where the regular "attributes" value for each vertex is replaced with a set of key:value pairs corresponding to the set of attribute expressions given in the print expression.
An example which shows all of the cases described above in combination is shown below.
Print Basic Example
```
CREATE QUERY print_example_v2(VERTEX<Person> v) FOR GRAPH Social_Net {
  SetAccum<VERTEX> @@set_of_vertices;
  SetAccum<EDGE> @posted_set;
  MapAccum<VERTEX,ListAccum<VERTEX>> @@test_map;
  FLOAT paper_width = 8.5;
  INT paper_height = 11;
  STRING Alpha = "ABC";
  Seed = Person.*;
  A = SELECT s
     FROM Seed:s
     WHERE s.gender == "Female"
     ACCUM @@set_of_vertices += s;
  B = SELECT t
    FROM Seed:s - (Posted>:e) - Post:t
    ACCUM s.@posted_set += e,
      @@test_map += (s -> t);
  // Numeric, String, and Boolean expressions, with renamed keys:
  PRINT paper_height*paper_width AS paper_size, Alpha+"XYZ" AS Letters,
  A.size() > 10 AS a_size_more_than_10;
  // Note how an expression is named if "AS" is not used:
  PRINT A.size() > 10;
  // Vertex variables. Only the vertex id is included (no attributes):
  PRINT v, @@set_of_vertices;
  // Map of Person -> Posts posted by that person:
  PRINT @@test_map;
  // Vertex Set Variable. Each vertex has a vertex-attached accumulator, which happens to be a set of edges (SetAccum<EDGE>), so edge format is shown also:
  PRINT A AS v_set_var_women;
  // Vertex Set Expression. The same set of vertices as above, but with only one attribute plus one computed attribute:
  PRINT A[A.gender, A.@posted_set.size()] AS v_set_expr;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Note how the results of the six `PRINT` statements are grouped in the JSON `results` field below:
  1. Each of the six `PRINT` statements is represented as one JSON object with the `results` array.
  2. When a `PRINT` statement has more than one expression (like the first one), the expressions may appear in the output in a different order than on the `PRINT` statement.
  3. The 2nd `PRINT` statement shows a key that is generated from the expression itself.
  4. The 3rd and 4th `PRINT` statements show a set of vertices (different from a vertex set variable) and a map, respectively.
  5. The 5th `PRINT` statement shows the vertex set variable A, including its vertex-attached accumulators (PRINT A).
  6. The 6th `PRINT` statement shows a vertex set expression for A, customized to include only one static attribute plus a newly computed attribute.

  
---  
Results from Query printExampleV2 (WITH COMMENTS ADDED)
```
GSQL > RUN QUERY print_example_v2("person1")
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [
  {
   "AsizeMoreThan10": false,
   "Letters": "ABCXYZ",
   "PaperSize": 93.5
  },
  {"A.size()>10": false},
  {
   "v": "person1",
   "@@setOfVertices": [ "person4", "person5", "person2" ]
  },
  {"@@testMap": {
   "person4": ["3"],
   "person3": ["2"],
   "person2": ["1"],
   "person1": ["0"],
   "person8": [ "7", "8" ],
   "person7": [ "9", "6" ],
   "person6": [ "10", "5" ],
   "person5": [ "4", "11" ]
  }},
  {"VSetVarWomen": [
   {
    "v_id": "person4",
    "attributes": {
     "gender": "Female",
     "id": "person4",
     "@postedSet": [{
      "from_type": "person",
      "to_type": "post",
      "directed": true,
      "from_id": "person4",
      "to_id": "3",
      "attributes": {},
      "e_type": "posted"
     }]
    },
    "v_type": "person"
   },
   {
    "v_id": "person5",
    "attributes": {
     "gender": "Female",
     "id": "person5",
     "@postedSet": [
      {
       "from_type": "person",
       "to_type": "post",
       "directed": true,
       "from_id": "person5",
       "to_id": "11",
       "attributes": {},
       "e_type": "posted"
      },
      {
       "from_type": "person",
       "to_type": "post",
       "directed": true,
       "from_id": "person5",
       "to_id": "4",
       "attributes": {},
       "e_type": "posted"
      }
     ]
    },
    "v_type": "person"
   },
   {
    "v_id": "person2",
    "attributes": {
     "gender": "Female",
     "id": "person2",
     "@postedSet": [{
      "from_type": "person",
      "to_type": "post",
      "directed": true,
      "from_id": "person2",
      "to_id": "1",
      "attributes": {},
      "e_type": "posted"
     }]
    },
    "v_type": "person"
   }
  ]},
  {"VSetExpr": [
   {
    "v_id": "person4",
    "attributes": {
     "A.@postedSet.size()": 1,
     "A.gender": "Female"
    },
    "v_type": "person"
   },
   {
    "v_id": "person5",
    "attributes": {
     "A.@postedSet.size()": 2,
     "A.gender": "Female"
    },
    "v_type": "person"
   },
   {
    "v_id": "person2",
    "attributes": {
     "A.@postedSet.size()": 1,
     "A.gender": "Female"
    },
    "v_type": "person"
   }
  ]}
 ]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_printing_csv_to_a_file_object)Printing CSV to a FILE Object
Instead of printing output in JSON format, output can be written to a `FILE` object in comma-separated values (CSV) format by appending the keyword `TO_CSV` followed by the `FILE` object name to the `PRINT` statement:
```
PRINT @@set_of_vertices TO_CSV file1;
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Each execution of the `PRINT` statement appends one line to the `FILE`. If the `PRINT` statement includes multiple expressions, then each printed value is separated from its neighbor by a comma. If an expression evaluates to a set or list, then the collection’s values are delimited by single spaces. Due to the simpler format of CSV vs. JSON, the `TO_CSV` feature only supports data with a simple one- or two-dimension structure.
Limitations of `PRINT` > File
  * Printing a full Vertex set variable is not supported.
  * If a vertex is printed, only its ID value is printed.
  * If printing a vertex set’s vertex-attached accumulator or a vertex set’s variable, the result is a list of values, one for each vertex, separated by newlines.
  * The syntax for printing a vertex set expression is different when printing to a file than when printing to standard output. Compare:
    * `PRINT A[A.gender];` # with brackets
    * `PRINT A.gender TO_CSV file1;` # without brackets

  
---  
Writing to `FILE` objects is optimized for parallel processing. Consequently, the order in which data is written to the `FILE` is not guaranteed. Therefore, it is strongly recommended that the user design their queries such that one of these conditions is satisfied:
  1. The query prints only one set of data, and the order of the set is not important.
  2. Each line of data to print to a file includes a label which can be used to identify the data.

  
---  
PRINT WHERE and PRINT TO_CSV FILE Object Example
```
CREATE QUERY print_example_file() FOR GRAPH Social_Net {
  SetAccum<VERTEX> @@test_set, @@test_set2;
  ListAccum<STRING> @@str_list;
  int x = 3;
  FILE file1 ("/home/tigergraph/print_example_file.txt");
  Seed = Person.*;
  A = SELECT s
    FROM Seed:s
    WHERE s.gender == "Female"
    ACCUM @@test_set += s, @@str_list += s.gender;
  A = SELECT s
    FROM Seed:s
    WHERE s.gender == "Male"
    ACCUM @@test_set2 += s;
  PRINT @@test_set, @@test_set2 TO_CSV file1; // 1st line: 2 4 5, 1 3 6 7 8 (order not guaranteed)
  PRINT x WHERE x < 0 TO_CSV file1;  // 2nd line: <skipped because no content>
  PRINT x WHERE x > 0 TO_CSV file1;  // 3rd line: 3
  PRINT @@str_list TO_CSV file1;    // 4th line: Female Female Female
  PRINT A.gender TO_CSV file1;   // 5th line: Male\n Male\n Male\n Male\n Male
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_file_println_statement)`FILE println` statement
The `FILE println` statement writes data to a `FILE` object. Unlike the `PRINT` statement, which is a query-body level statement, the `FILE println` statement can be either a query-body level statement or a DML-sub-statement:
```
printlnStmt := fileVar".println" "(" expr ("," expr)* ")"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

`println` is a method of a FILE object variable. The `println` statement can be used either at the query-body or DML-sub-statement level, e.g., within the `ACCUM` clause of a `SELECT` block. Each time `println` is called, it adds one new line of values to the `FILE` object, and then to the corresponding file.
The `println` function can print any expression that can be printed by a `PRINT` statement with the exception of vertex set variables. Vertex expression sets are also not applicable to the `println` function.
If the `println` statement has a list of expressions to print, it will produce a comma-separated list of values. If an expression refers to a list or set, then the output will be a list of values separated by spaces.
The data from query-body level `FILE` print statements (either `TO_CSV` or `println`) will appear in their original order. However, due to the parallel processing of statements in an `ACCUM` block, the order in which `println` statements at the DML-sub-statement level are processed cannot be guaranteed.  
---  
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_example)Example
File object query example
```
CREATE QUERY file_ex (STRING file_location) FOR GRAPH Work_Net {
  FILE f1 (file_location);
  P = {Person.*};
  PRINT "header" TO_CSV f1;
  USWorkers = SELECT v FROM P:v
    WHERE v.location_id == "us"
    ACCUM f1.println(v.id, v.interest_list);
  PRINT "footer" TO_CSV f1;
}
INSTALL QUERY file_ex
RUN QUERY file_ex("/home/tigergraph/files")
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

All of the `PRINT` statements in this example use the `TO_CSV` option, so there is no JSON output to the console.
Results from Query fileEx
```
GSQL > RUN QUERY file_ex("/home/tigergraph/file_ex.txt")
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": []
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

All the output in this case goes to the `FILE` object. In the query definition, the line `"header"` is printed first, followed by the `println` statements in the `ACCUM` clause, and `"footer"` is printed last. The output in the file follows this order because the order of query-body level statements is maintained in the output.
File contents produced by file_ex example
```
[tigergraph@localhost]$ more /home/tigergraph/file_ex.txt
header
person7,art sport
person10,football sport
person4,football
person9,financial teaching
person1,management financial
footer
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

However, within the `ACCUM` clause itself, the order of the `println` statements is not guaranteed.
## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_passing_a_file_object_as_a_parameter)Passing a FILE Object as a Parameter
A `FILE` Object can be passed from one query to a subquery. The subquery can then also write to the `FILE` object.
Example: query passing a FILE object to another query
```
CREATE QUERY file_param_sub(FILE f, STRING label, INT num) FOR GRAPH Social_Net {
  f.println(label, "header");
  FOREACH i IN RANGE [1,2] DO
    f.println(label, num+i);
  END;
  f.println(label, "footer");
}
CREATE QUERY file_param_main(STRING main_label) FOR GRAPH Social_Net {
  FILE f ("/home/tigergraph/file_param.txt");
  f.println(main_label, "header");
  FOREACH i IN RANGE [1,2] DO
    f.println(main_label, i);
    file_param_sub(f, "sub", 10*i);
  END;
  f.println(main_label, "footer");
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
GSQL > RUN QUERY file_param_main("main")
GSQL > EXIT
a
$ cat /home/tigergraph/file_param.txt
main,header
main,1
 sub,header
 sub,11
 sub,12
 sub,footer
main,2
 sub,header
 sub,21
 sub,22
 sub,footer
main,footer
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_log_statement)`LOG` Statement
The `LOG` statement is another means to output data. It works as a function that outputs information to a log file:
```
logStmt := LOG "(" condition "," argList ")"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The first argument of the LOG statement is a boolean condition that enables or disables logging. This allows logging to be easily turned on/off for debugging. After the condition, `LOG` takes one or more expressions (separated by commas). These expressions are evaluated and output to the log file.
Unlike the `PRINT` statement, which can only be used as a query-body statement, the `LOG` statement can be used as both a query-body statement and a DML-sub-statement.
The values will be recorded in the GPE log. To find the log file after the query has completed, open a Linux shell and use the command `gadmin log gpe`. It may return more than one log file name; use the one ending in `"INFO"`. Search this file for `"UDF_"`.
Examples
```
BOOLEAN debug = TRUE;
INT x = 10;
LOG(debug, 20);
LOG(debug, 10, x);
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects#_return_statement)`RETURN` Statement
EBNF for RETURN statement
```
returnStmt := RETURN expr
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The `RETURN` statement specifies data that a [subquery](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions#_subqueries) passes back to an outer query that called the subquery. The return type for a `RETURN` statement can be any base type or accumulator type, but **must be the same type** as indicated by the `RETURNS` clause of the subquery.
For subqueries to return a [`HeapAccum`](https://docs.tigergraph.com/gsql-ref/3.6/querying/accumulators#_heapaccum) or [`GroupByAccum`](https://docs.tigergraph.com/gsql-ref/3.6/querying/accumulators#_groupbyaccum), the accumulators must be [defined at the catalog level](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/defining-a-graph-schema#_typedef). See the example below:
Subquery Returning HeapAccum Example
```
CREATE QUERY file_param_sub(FILE f, STRING label, INT num) FOR GRAPH Social_Net {
  f.println(label, "header");
  FOREACH i IN RANGE [1,2] DO
    f.println(label, num+i);
  END;
  f.println(label, "footer");
}
CREATE QUERY file_param_main(STRING main_label) FOR GRAPH Social_Net {
  FILE f ("/home/tigergraph/file_param.txt");
  f.println(main_label, "header");
  FOREACH i IN RANGE [1,2] DO
    f.println(main_label, i);
    file_param_sub(f, "sub", 10*i);
  END;
  f.println(main_label, "footer");
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


