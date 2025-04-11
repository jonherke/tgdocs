![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions)[Next](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions)
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
[Resources](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions)
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
  * [Mathematical Functions](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/3.6/modules/querying/pages/func/mathematical-functions.adoc)
### Contents
  * [General](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_general)
  * [abs()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_abs)
  * [ceil()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_ceil)
  * [exp()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_exp)
  * [float_to_int()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_float_to_int)
  * [floor()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_floor)
  * [fmod()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_fmod)
  * [ldexp()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_ldexp)
  * [PI()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_pi)
  * [pow()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_pow)
  * [rand()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_rand)
  * [round()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_round)
  * [sign()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_sign)
  * [square()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_square)
  * [sqrt()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_sqrt)
  * [trunc()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_trunc)
  * [Logarithmic](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_logarithmic)
  * [log()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_log)
  * [log2()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_log2)
  * [log10()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_log10)
  * [Trigonometric](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_trigonometric)
  * [acos()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_acos)
  * [asin()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_asin)
  * [atan()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_atan)
  * [atan2()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_atan2)
  * [cos()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_cos)
  * [cosh()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_cosh)
  * [cot()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_cot)
  * [degrees()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_degrees)
  * [radians()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_radians)
  * [sin()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_sin)
  * [sinh()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_sinh)
  * [tan()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_tan)
  * [tanh()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_tanh)


# Mathematical Functions
### Contents
  * [General](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_general)
  * [abs()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_abs)
  * [ceil()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_ceil)
  * [exp()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_exp)
  * [float_to_int()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_float_to_int)
  * [floor()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_floor)
  * [fmod()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_fmod)
  * [ldexp()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_ldexp)
  * [PI()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_pi)
  * [pow()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_pow)
  * [rand()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_rand)
  * [round()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_round)
  * [sign()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_sign)
  * [square()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_square)
  * [sqrt()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_sqrt)
  * [trunc()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_trunc)
  * [Logarithmic](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_logarithmic)
  * [log()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_log)
  * [log2()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_log2)
  * [log10()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_log10)
  * [Trigonometric](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_trigonometric)
  * [acos()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_acos)
  * [asin()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_asin)
  * [atan()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_atan)
  * [atan2()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_atan2)
  * [cos()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_cos)
  * [cosh()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_cosh)
  * [cot()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_cot)
  * [degrees()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_degrees)
  * [radians()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_radians)
  * [sin()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_sin)
  * [sinh()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_sinh)
  * [tan()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_tan)
  * [tanh()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_tanh)


This page lists the mathematical functions that are available in the GSQL query language. They are divided into three categories:
  * General
  * Logarithmic
  * Trigonometric


## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_general)General
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_abs)abs()
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_syntax)Syntax
`abs( num )`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_description)Description
Returns the absolute value of a number.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_return_type)Return type
Number
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_parameters)Parameters
Parameter | Description | Data type  
---|---|---  
`num` | The number to return the absolute value for | Number  
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_ceil)ceil()
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_syntax_2)Syntax
`ceil(num)`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_description_2)Description
Rounds a number up to the smallest integer that’s greater than or equal to the number.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_return_type_2)Return type
`INT`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_parameters_2)Parameters
Parameter | Description | Data type  
---|---|---  
`num` | The number to round up from | num  
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_exp)**exp()**
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_syntax_3)Syntax
`exp(num)`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_description_3)Description
Returns the base-e exponential of a number.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_return_type_3)Return type
`FLOAT`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_parameters_3)Parameters
Parameter | Description | Data type  
---|---|---  
`num` | The exponent | Number  
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_float_to_int)float_to_int()
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_syntax_4)Syntax
`float_to_int (num)`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_description_4)**Description**
Converts a floating-point number to an integer by truncating the floating part.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_return_type_4)Return type
`INT`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_parameters_4)Parameters
Parameter | Description | Data type  
---|---|---  
`num` | The floating-point number to convert to integer | `FLOAT`  
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_floor)floor()
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_syntax_5)Syntax
`floor(num)`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_description_5)Description
Rounds a number down to the biggest integer that is smaller than or equal to the number.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_return_type_5)Return type
`INT`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_parameter)Parameter
Parameter | Description | Data type  
---|---|---  
`num` | The number to round down from | Number  
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_fmod)fmod()
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_syntax_6)Syntax
`fmod(numer, denom)`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_description_6)Description
Returns the floating-point remainder of `numer` divided by `denom`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_return_type_6)Return type
`FLOAT`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_parameters_5)Parameters
Parameter | Description | Data type  
---|---|---  
`numer` | The dividend | Number  
`denom` | The divisor | Number  
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_ldexp)ldexp()
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_syntax_7)Syntax
`ldexp(x, exp)`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_description_7)Description
Returns `x` multiplied by 2 raised to the power of `exp`
x∗2exp
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_return_type_7)Return type
`FLOAT`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_parameters_6)Parameters
Parameter | Description | Data type  
---|---|---  
`x` | The base | Number  
`exp` | The exponent of 2 | Number  
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_pi)PI()
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_syntax_8)Syntax
`PI()`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_description_8)Description
Returns the value of π.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_return_type_8)Return type
`DOUBLE`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_parameters_7)Parameters
None.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_example)Example
```
 PI() * 1000000000 -> 3.141592653589793E9
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_pow)pow()
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_syntax_9)Syntax
`pow(base, exp)`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_description_9)Description
Returns the power of a number.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_return_type_9)Return type
`FLOAT`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_parameters_8)Parameters
Parameter | Description | Data type  
---|---|---  
`base` | The base | Number  
`exp` | The exponent | Number  
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_rand)rand()
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_syntax_10)Syntax
`rand( [seed] )`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_description_10)Description
Returns a completely random number >= 0 and <1. If `seed` is specified, it returns a repeatable sequence of random numbers. If no seed is specified, it returns a completely random number.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_return_type_10)Return type
`DOUBLE`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_parameters_9)Parameters
Parameter | Description | Data type  
---|---|---  
`seed` | Optional. If `seed` is specified, it returns a repeatable sequence of random numbers. If no seed is specified, it returns a completely random number | `UINT`  
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_example_2)Example
```
rand(5) -> 0.05518
rand(5) -> 0.83133
rand(5) -> 0.36374
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_round)round()
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_syntax_11)Syntax
`round ( num[, integer] )`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_description_11)Description
Rounds a number to a specified place relative to the decimal point and returns the result.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_return_type_11)Return type
A numeric type.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_parameters_10)Parameters
Parameter | Description | Data type  
---|---|---  
`num` | The number to be rounded | `NUM`  
`integer` |  Optional. An integer value indicating the place to round the first argument to. + If `integer` is positive, the function returns `num` rounded to `integer` places to the right of the decimal point. If you omit `integer`, then `num` is rounded to zero places. If `integer` is negative, then `num` is rounded off to the left of the decimal point. | `INT`  
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_examples)Examples
```
round(15.213) => 15
round(15.213, -1) => 20
round(2.15, 1) => 2.2
round(2.25, 1) => 2.3
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_sign)sign()
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_syntax_12)Syntax
`sign( num )`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_description_12)Description
Returns the sign of a number. If the number is positive, return `1`; if the number is negative, return `-1`; if the number is `0`, return `0`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_return_type_12)Return type
`INT`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_parameters_11)Parameters
Parameter | Description | Data type  
---|---|---  
`num` | A numeric value | `INT`, `DOUBLE`  
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_examples_2)Examples
```
sign(100) => 1
sign(0) => 0
sign(-1.23) => -1
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_square)square()
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_syntax_13)Syntax
`square( num )`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_description_13)Description
Returns the square of a number.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_return_type_13)Return type
A numeric type.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_parameters_12)Parameters
Parameter | Description | Data type  
---|---|---  
`num` | A numeric value. | `INT`, `FLOAT`, or `DOUBLE`  
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_examples_3)Examples
```
square(0) => 0
square(50) => 2500
square(-50) => 2500
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_sqrt)sqrt()
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_syntax_14)Syntax
`sqrt(num)`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_description_14)Description
Returns the square root of a number
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_return_type_14)Return type
`FLOAT`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_parameters_13)Parameters
Parameter | Description | Data type  
---|---|---  
`num` | The number to get square root for. | Number  
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_trunc)trunc()
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_syntax_15)Syntax
`trunc( num, [decimal_place] )`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_description_15)Description
Returns a number truncated to a specified decimal place.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_return_type_15)Return type
A numeric type.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_parameters_14)Parameters
Parameter | Description | Data type  
---|---|---  
`num` | The number to be truncated | `INT`, `FLOAT` or `DOUBLE`  
`decimal_place` | Optional. The integer indicating the decimal place to truncate the number to. If `decimal_plac` is positive, the function returns the number truncated to `decimal_place` decimal places. If `decimal_place` is omitted, then the number is truncated to 0 places. `decimal_place` can be negative to truncate (make zero) `decimal_place` digits left of the decimal point. | `INT`  
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_examples_4)Examples
```
trunc(9.99) => 9
trunc(-9.99) => 9
trunc(99.999. -1) => 90
trunc(9.99, 1) => 9.9
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_logarithmic)Logarithmic
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_log)**log**()
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_syntax_16)Syntax
`log(num)`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_description_16)Description
Returns the natural logarithm of a number (base e).
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_return_type_16)Return type
`DOUBLE`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_parameters_15)Parameters
Parameter | Description | Data type  
---|---|---  
`num` | The number to compute natural logarithm for | Number  
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_log2)log2()
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_syntax_17)Syntax
`log2( num )`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_description_17)Description
Returns the base-2 logarithm of a number.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_return_type_17)Return type
`DOUBLE`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_parameters_16)Parameters
Parameter | Description | Data type  
---|---|---  
`num` | A numeric value | `INT`, `FLOAT`, `DOUBLE`  
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_examples_5)Examples
```
log2(0.5) => -1
log2(1) => 0
log2(3) => 1.58
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_log10)log10()
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_syntax_18)Syntax
`log10(num)`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_description_18)Description
Return the common logarithm of a number (base 10).
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_return_type_18)Return type
`FLOAT`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_parameters_17)Parameters
Parameter | Description | Data type  
---|---|---  
`num` | The number to compute common logarithm for | Number  
## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_trigonometric)Trigonometric
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_acos)acos()
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_syntax_19)Syntax
`acos(num)`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_description_19)Description
Returns the arc cosine of a number.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_return_type_19)Return type
`FLOAT`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_parameters_18)Parameters
Parameter | Description | Data type  
---|---|---  
`num` | The number to compute arccosine for | Number  
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_asin)**asin()**
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_syntax_20)Syntax
`asin(num)`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_description_20)Description
Returns the arc sine of a number.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_return_type_20)Return type
`FLOAT`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_parameters_19)Parameters
Parameter | Description | Data type  
---|---|---  
`num` | The number to compute arcsine for | Number  
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_atan)**atan()**
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_syntax_21)Syntax
`atan(num)`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_description_21)Description
Returns the arctangent of a number.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_return_type_21)Return type
`FLOAT`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_parameters_20)Parameters
Parameter | Description | Data type  
---|---|---  
`num` | The number to compute arctangent for | Number  
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_atan2)**atan2()**
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_syntax_22)Syntax
`atan2(y, x)`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_description_22)Description
Returns the arctangent of a fraction.
atan(yx)
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_return_type_22)Return type
`FLOAT`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_parameters_21)Parameters
Parameter | Description | Data type  
---|---|---  
`y` | The dividend of the fraction to compute arctangent for | Number  
`x` | The divisor of the fraction to compute arctangent for | Number  
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_cos)**cos**()
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_syntax_23)Syntax
`cos(num)`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_description_23)Description
Returns the cosine of a number.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_return_type_23)Return type
`FLOAT`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_parameters_22)Parameters
Parameter | Description | Data type  
---|---|---  
`num` | The number to return cosine for | Number  
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_cosh)**cosh()**
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_syntax_24)Syntax
`cosh(num)`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_description_24)Description
Returns the hyperbolic cosine of a number.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_return_type_24)Return type
`FLOAT`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_parameters_23)Parameters
Parameter | Description | Data type  
---|---|---  
`num` | The number to compute hyperbolic cosine for | Number  
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_cot)cot()
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_syntax_25)Syntax
`cot( num )`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_description_25)Description
Returns the cotangent of a number.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_return_type_25)Return type
`DOUBLE`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_parameters_24)Parameters
Parameter | Description | Data type  
---|---|---  
`num` | A numeric value | `INT`, `FLOAT`, or `DOUBLE`  
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_examples_6)Examples
```
cot(6) => -3.4363530041801278
cot(-1) => -0.64209261593433065
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_degrees)degrees()
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_syntax_26)Syntax
`degrees( num )`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_description_26)Description
Converts a value in radians to degrees.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_return_type_26)Return type
`DOUBLE`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_parameters_25)Parameters
Parameter | Description | Data type  
---|---|---  
`num` | A numeric value | `INT`, `FLOAT`, or `DOUBLE`  
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_examples_7)Examples
```
degrees(2) => 114.59155902616465
degrees(1) => -57.29577951308232
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_radians)radians()
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_syntax_27)Syntax
`radians( num )`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_description_27)Description
Converts a value in degrees to radians.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_return_type_27)Return type
`DOUBLE`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_parameters_26)Parameters
Parameter | Description | Data type  
---|---|---  
`num` | A numeric value | `INT`, `FLOAT`, or `DOUBLE`  
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_examples_8)Examples
```
radians( 45 ) => -0.7853981633974483
radians( 30 ) => 0.5235987755982988
radians( 50 ) => 0.8726646259971648
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_sin)sin()
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_syntax_28)Syntax
`sin(num)`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_description_28)Description
Returns the sine of a number.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_return_type_28)Return type
`FLOAT`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_parameters_27)Parameters
Parameter | Description | Data type  
---|---|---  
`num` | The number to compute sine for | Number  
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_sinh)**sinh()**
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_syntax_29)Syntax
`sinh(num)`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_description_29)Description
Returns the hyperbolic sine of a number.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_return_type_29)Return type
`FLOAT`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_parameters_28)Parameters
Parameter | Description | Data type  
---|---|---  
`num` | The number to compute hyperbolic sine for | Number  
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_tan)**tan()**
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_syntax_30)Syntax
`tan(num)`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_description_30)Description
Returns the tangent of a number.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_return_type_30)Return type
`FLOAT`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_parameters_29)Parameters
Parameter | Description | Data type  
---|---|---  
`num` | The number to compute tangent for | Number  
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_tanh)tanh()
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_syntax_31)Syntax
`tanh(num)`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_description_31)Description
Returns the hyperbolic tangent of a number.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_return_type_31)Return type
`FLOAT`
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions#_parameters_30)Parameters
Parameter | Description | Data type  
---|---|---  
`num` | The number to compute hyperbolic tangent for | Number  
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


