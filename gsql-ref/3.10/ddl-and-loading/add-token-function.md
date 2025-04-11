![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/add-token-function)[Next](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/add-token-function)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/add-token-function)
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
[Resources](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/add-token-function)
[Developer Site](https://dev.tigergraph.com/) [Community Forum](https://community.tigergraph.com/) [Knowledge Base](https://tigergraph.freshdesk.com/support/solutions)
[Download](https://dl.tigergraph.com)
[ TG Savanna](https://savanna.tgcloud.io)
### [GSQL Language Reference](https://docs.tigergraph.com/gsql-ref/3.10/intro/)
  *     * [Overview](https://docs.tigergraph.com/gsql-ref/3.10/intro/)
    * [What sets GSQL apart](https://docs.tigergraph.com/gsql-ref/3.10/intro/set-gsql-apart)
  *     * Tutorials
      * [GSQL 101](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/)
        * [Define a Schema](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/define-a-schema)
        * [Load Data](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/load-data-gsql-101)
        * [Run Built-in Queries](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/built-in-select-queries)
        * [Parameterized Queries](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query)
        * [Review](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/review)
      * [Pattern Matching Tutorial](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/pattern-matching/)
        * [Prepare your Environment](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/pattern-matching/prepare-environment)
        * [One-hop patterns](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/pattern-matching/one-hop-patterns)
        * [Repeating a 1-Hop Pattern](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/pattern-matching/repeating-a-pattern)
        * [Multiple Hop Patterns and Accumulation](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/pattern-matching/multiple-hop-and-accumulation)
        * [Example - A Recommender](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/pattern-matching/example)
        * [Advanced Features](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/pattern-matching/adv/)
          * [Per Clause (Beta)](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/pattern-matching/adv/per-clause)
          * [Conjunctive Pattern Matching (Beta)](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/pattern-matching/adv/conjunctive-pattern-matching)
          * [Data Modification](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/pattern-matching/adv/dml)
        * [Summary](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/pattern-matching/summary)
      * [Accumulators Tutorial](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/accumulators-tutorial)
  *     * [System & Language Basics](https://docs.tigergraph.com/gsql-ref/3.10/basics/system-and-language-basics)
  *     * [Attribute Data Types](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/attribute-data-types)
    * [Schema Definition](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/)
      * [Define a Graph Schema](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/defining-a-graph-schema)
      * [Modify a Graph Schema](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/modifying-a-graph-schema)
    * [Loading Jobs](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/loading-jobs)
      * [Create a Loading Job](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/creating-a-loading-job)
        * [Functions](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/)
          * [Token Functions](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/)
            * [flatten()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/flatten)
            * [flatten_json_array()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/flatten_json_array)
            * [gsql_concat()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_concat)
            * [gsql_current_time_epoch()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_current_time_epoch)
            * [gsql_day()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_day)
            * [gsql_day_epoch()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_day_epoch)
            * [gsql_find()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_find)
            * [gsql_length()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_length)
            * [gsql_lower()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_lower)
            * [gsql_ltrim()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_ltrim)
            * [gsql_month()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_month)
            * [gsql_month_epoch()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_month_epoch)
            * [gsql_regex_match()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_regex_match)
            * [gsql_regex_replace()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_regex_replace)
            * [gsql_reverse()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_reverse)
            * [gsql_rtrim()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_rtrim)
            * [gsql_substring()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_substring)
            * [gsql_to_bool()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_to_bool)
            * [gsql_to_int()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_to_int)
            * [gsql_to_uint()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_to_uint)
            * [gsql_trim()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_trim)
            * [gsql_ts_to_epoch_seconds()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_ts_to_epoch)
            * [gsql_upper()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_upper)
            * [gsql_uuid_v4()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_uuid_v4)
            * [gsql_year()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_year)
            * [gsql_year_epoch()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_year_epoch)
            * [split()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/split)
          * [Token Functions in WHERE Clause](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token_where/)
            * [concat()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token_where/concat)
            * [gsql_is_false()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token_where/gsql_is_false)
            * [gsql_is_not_empty()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token_where/gsql_is_not_empty)
            * [gsql_is_true()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token_where/gsql_is_true)
            * [gsql_token_equal()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token_where/gsql_token_equal)
            * [gsql_token_ignore_case_equal()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token_where/gsql_token_ignore_case_equal)
            * [to_float()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token_where/to_float)
            * [to_int()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token_where/to_int)
            * [token_len()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token_where/token_len)
          * [Reducer functions](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/reducer/)
            * [add()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/reducer/add)
            * [and()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/reducer/and)
            * [ignore_if_exists()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/reducer/ignore_if_exists)
            * [max()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/reducer/max)
            * [min()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/reducer/min)
            * [or()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/reducer/or)
        * [Add a User-defined Token Function](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/add-token-function)
      * [Run a Loading Job](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/running-a-loading-job)
      * [Manage Loading Jobs](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/managing-loading-job)
  *     * [Querying](https://docs.tigergraph.com/gsql-ref/3.10/querying/)
      * [Query Language Syntax Versions](https://docs.tigergraph.com/gsql-ref/3.10/querying/syntax-versions)
      * [Queries](https://docs.tigergraph.com/gsql-ref/3.10/querying/query-operations)
      * [Query Optimizer (Preview Feature)](https://docs.tigergraph.com/gsql-ref/3.10/querying/query-optimizer/)
        * [Enabling Cost-Based Optimization (Preview Feature)](https://docs.tigergraph.com/gsql-ref/3.10/querying/query-optimizer/enable-cost-optimizer)
        * [Statistics REST APIs (Preview Feature)](https://docs.tigergraph.com/gsql-ref/3.10/querying/query-optimizer/stats-api)
      * [Distributed Query Mode](https://docs.tigergraph.com/gsql-ref/3.10/querying/distributed-query-mode)
      * [Data Types](https://docs.tigergraph.com/gsql-ref/3.10/querying/data-types)
      * [Accumulators](https://docs.tigergraph.com/gsql-ref/3.10/querying/accumulators)
      * [Operators and Expressions](https://docs.tigergraph.com/gsql-ref/3.10/querying/operators-and-expressions)
      * [Functions](https://docs.tigergraph.com/gsql-ref/3.10/querying/func/)
        * [Aggregation Functions](https://docs.tigergraph.com/gsql-ref/3.10/querying/func/aggregation-functions)
        * [Datetime Functions](https://docs.tigergraph.com/gsql-ref/3.10/querying/func/datetime-functions)
        * [Edge Methods](https://docs.tigergraph.com/gsql-ref/3.10/querying/func/edge-methods)
        * [JSON Object Methods](https://docs.tigergraph.com/gsql-ref/3.10/querying/func/json-object-methods)
        * [JSON Array Methods](https://docs.tigergraph.com/gsql-ref/3.10/querying/func/jsonarray-methods)
        * [Mathematical Functions](https://docs.tigergraph.com/gsql-ref/3.10/querying/func/mathematical-functions)
        * [Miscellaneous Functions](https://docs.tigergraph.com/gsql-ref/3.10/querying/func/miscellaneous-functions)
        * [Query User-Defined Functions](https://docs.tigergraph.com/gsql-ref/3.10/querying/func/query-user-defined-functions)
        * [String Functions](https://docs.tigergraph.com/gsql-ref/3.10/querying/func/string-functions)
        * [Type Conversion Functions](https://docs.tigergraph.com/gsql-ref/3.10/querying/func/type-conversion-functions)
        * [Vertex Functions](https://docs.tigergraph.com/gsql-ref/3.10/querying/func/vertex-methods)
        * [Context Functions](https://docs.tigergraph.com/gsql-ref/3.10/querying/func/context-functions)
      * [Declaration and Assignment Statements](https://docs.tigergraph.com/gsql-ref/3.10/querying/declaration-and-assignment-statements)
      * [SELECT Statement](https://docs.tigergraph.com/gsql-ref/3.10/querying/select-statement/)
        * [SELECT Statement (Syntax V1)](https://docs.tigergraph.com/gsql-ref/3.10/querying/select-statement/select-statement-v1)
        * [SQL-like SELECT statement](https://docs.tigergraph.com/gsql-ref/3.10/querying/select-statement/sql-like-select-statement)
      * [Control Flow Statements](https://docs.tigergraph.com/gsql-ref/3.10/querying/control-flow-statements)
      * [Data Modification Statements](https://docs.tigergraph.com/gsql-ref/3.10/querying/data-modification-statements)
      * [Output Statements and FILE Objects](https://docs.tigergraph.com/gsql-ref/3.10/querying/output-statements-and-file-objects)
      * [Exception Statements](https://docs.tigergraph.com/gsql-ref/3.10/querying/exception-statements)
      * [Comments](https://docs.tigergraph.com/gsql-ref/3.10/querying/comments)
  *     * openCypher
      * [openCypher in GSQL](https://docs.tigergraph.com/gsql-ref/3.10/openCypher-in-gsql/openCypher-in-gsql)
      * [Writing and Running openCypher in GSQL Shell](https://docs.tigergraph.com/gsql-ref/3.10/openCypher-in-gsql/openCypher-in-gsql-web-shell)
      * [openCypher Pattern Support in GSQL](https://docs.tigergraph.com/gsql-ref/3.10/openCypher-in-gsql/openCypher-gsql-from-clause-extension)
  *     * Appendix
      * [GSQL Style Guide](https://docs.tigergraph.com/gsql-ref/3.10/appendix/gsql-style-guide)
      * [DDL Keywords & Reserved Words](https://docs.tigergraph.com/gsql-ref/3.10/appendix/keywords-and-reserved-words)
      * [Query Language Keywords & Reserved Words](https://docs.tigergraph.com/gsql-ref/3.10/appendix/query-language-reserved-words)
      * [Interpreted GSQL Limitations](https://docs.tigergraph.com/gsql-ref/3.10/appendix/interpreted-gsql-limitations)
      * [GSQL Start-to-End Process and Data Flow](https://docs.tigergraph.com/gsql-ref/3.10/appendix/gsql-start-to-end-process)
      * [Example Graphs](https://docs.tigergraph.com/gsql-ref/3.10/appendix/example-graphs)
      * [Common Errors and Problems](https://docs.tigergraph.com/gsql-ref/3.10/appendix/common-errors-and-problems)
      * [GSQL Cheat Sheets](https://docs.tigergraph.com/gsql-ref/3.10/appendix/cheat-sheets)
      * [Documentation Notations](https://docs.tigergraph.com/gsql-ref/3.10/appendix/notations)
    * [Legacy Version Documentation](https://docs.tigergraph.com/gsql-ref/3.10/appendix/legacy-tg-versions)


GSQL Language Reference 3.10
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
  * [GSQL Language Reference 3.10](https://docs.tigergraph.com/gsql-ref/3.10/intro/)
  * [Loading Jobs](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/loading-jobs)
  * [Create a Loading Job](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/creating-a-loading-job)
  * [Add a User-defined Token Function](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/add-token-function)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/3.10/modules/ddl-and-loading/pages/add-token-function.adoc)
### Contents
  * [Define a token function in C++](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/add-token-function#_define_a_token_function_in_c)
  * [Example](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/add-token-function#_example)
  * [User-defined Token Functions for WHERE Clause](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/add-token-function#_user_defined_token_functions_for_where_clause)
  * [Use GitHub to store token functions](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/add-token-function#_use_github_to_store_token_functions)
  * [Store token functions locally](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/add-token-function#_store_token_functions_locally)
  * [Step 1: Enable adding a TokenBank with PUT](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/add-token-function#_step_1_enable_adding_a_tokenbank_with_put)
  * [Step 2: Modify the current TokenBank file](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/add-token-function#_step_2_modify_the_current_tokenbank_file)
  * [Step 3: Define your token function](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/add-token-function#_step_3_define_your_token_function)
  * [Step 4: Store the modified TokenBank.cpp file](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/add-token-function#_step_4_store_the_modified_tokenbank_cpp_file)
  * [Step 5: Disable adding a TokenBank with PUT](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/add-token-function#_step_5_disable_adding_a_tokenbank_with_put)


# Add a User-defined Token Function
### Contents
  * [Define a token function in C++](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/add-token-function#_define_a_token_function_in_c)
  * [Example](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/add-token-function#_example)
  * [User-defined Token Functions for WHERE Clause](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/add-token-function#_user_defined_token_functions_for_where_clause)
  * [Use GitHub to store token functions](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/add-token-function#_use_github_to_store_token_functions)
  * [Store token functions locally](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/add-token-function#_store_token_functions_locally)
  * [Step 1: Enable adding a TokenBank with PUT](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/add-token-function#_step_1_enable_adding_a_tokenbank_with_put)
  * [Step 2: Modify the current TokenBank file](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/add-token-function#_step_2_modify_the_current_tokenbank_file)
  * [Step 3: Define your token function](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/add-token-function#_step_3_define_your_token_function)
  * [Step 4: Store the modified TokenBank.cpp file](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/add-token-function#_step_4_store_the_modified_tokenbank_cpp_file)
  * [Step 5: Disable adding a TokenBank with PUT](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/add-token-function#_step_5_disable_adding_a_tokenbank_with_put)


In GSQL’s Data Definition and Loading (DDL) language, users can define their own token functions if the built-in token functions do not meet their needs.
Token functions are written in C++ and stored in a file named `tokenbank.cpp`.
There are two ways to modify this file to add token functions to GSQL:
  * Store the file in a GitHub repository, and configure GSQL to read from the repository.
  * Use `GET` and `PUT` commands to download, modify, and store the file locally.


This section first explains how to define a token function, then how to integrate token functions into GSQL.
## [](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/add-token-function#_define_a_token_function_in_c)Define a token function in C++
Token functions can either return a value that is used for an attribute expression or used in a `WHERE` clause as a condition expression. Depending on the return type of the function, the signature of the function must match the allowed format.
If your token function is used to return an attribute expression, the signature of the function must follow the format specified in the table below depending on the attribute type.
Attribute type | Function signature | Function return type  
---|---|---  
`STRING` | `extern "C" void funcName (const char* const iToken[], uint32_t iTokenLen[], uint32_t iTokenNum, char* const oToken, uint32_t& oTokenLen)` | `void`. The value of `oToken` will be returned in GSQL  
`BOOL` | `extern "C" bool funcName (const char* const iToken[], uint32_t iTokenLen[], uint32_t iTokenNum)` | `bool`  
`UINT` | `extern "C" uint64_t funcName (const char* const iToken[], uint32_t iTokenLen[], uint32_t iTokenNum)` | `uint64_t`  
`INT` | `extern "C" int64_t funcName (const char* const iToken[], uint32_t iTokenLen[], uint32_t iTokenNum)` | `int64_t`  
`FLOAT` | `extern "C" float funcName (const char* const iToken[], uint32_t iTokenLen[], uint32_t iTokenNum)` | `float`  
`DOUBLE` | `extern "C" double funcName (const char* const iToken[], uint32_t iTokenLen[], uint32_t iTokenNum)` | `double`  
The parameters `iToken`, `iTokenLen`, and `iTokenNum` must be named exactly as such, and are used to describe the input tokens:
  * `iToken` is an array of the string tokens
  * `iTokenLen` is an array of the lengths of the string tokens
  * `iTokenNum` is the number of tokens


Token functions for attribute types `STRING` have a C++ function return type of `void`. Use the parameter `oToken` to store the string you want returned, and in GSQL the token function will return the string stored in `oToken`:
  * `oToken` is the returned string value
  * `oTokenLen` is the length of the return string


Note that the input tokens are always in string (`char*`) format. If necessary, convert them to other types inside the function.
### [](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/add-token-function#_example)Example
The built-in token function `gsql_concat` is used in the following example. It takes multiple token parameters and returns a string.
```
extern "C" void gsql_concat(const char* const iToken[], uint32_t iTokenLen[], uint32_t iTokenNum, char* const oToken, uint32_t& oTokenLen) {
 int k = 0;
 for (int i=0; i < iTokenNum; i++) {
  for (int j =0; j < iTokenLen[i]; j++) {
      oToken[k++] = iToken[i][j];
  }
 }
 oTokenLen = k;
}
c++![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/add-token-function#_user_defined_token_functions_for_where_clause)User-defined Token Functions for `WHERE` Clause
User-defined token functions (described above) can also be used to construct the boolean conditional expression in the `WHERE` clause. However, there are some restrictions in the `WHERE` clause:
In the clause `WHERE <conditions>`,
  * The only user-defined token functions allowed are those that return a boolean value.
  * If a user-defined token function is used in a `WHERE` clause, then it must constitute the entire condition; it cannot be combined with another function or operator to produce a subsequent value. However, the arguments of the token function can include other functions.


The source code for the built-in token function `gsql_token_equal` is used as an example for how to write a user-defined token function.
```
extern "C" bool gsql_token_equal(const char* const iToken[], uint32_t iTokenLen[], uint32_t iTokenNum) {
 if (iTokenNum != 2) {
  return false;
 }
 if (iTokenLen[0] != iTokenLen[1]) {
  return false;
 }
 for (int i =0; i < iTokenLen[0]; i++) {
  if (iToken[0][i] != iToken[1][i]) {
   return false;
  }
 }
 return true;
}
```

## [](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/add-token-function#_use_github_to_store_token_functions)Use GitHub to store token functions
You can configure GSQL to read from a GitHub repository for `tokenbank.cpp`.
If GitHub access is configured, GSQL will retrieve user source code files from GitHub before files added via `PUT`, so long as the files exist.
TigerGraph only allows one TokenBank file at a time. Files on GitHub take priority. If GitHub is connected but files are missing, TigerGraph will look for a TokenBank file added via `PUT`.   
---  
New additions to the files in the GitHub repository are instantly available in GSQL.
You can retrieve the TokenBank from `AppRoot/dev/gdk/gsql/src/TokenBank/TokenBank.cpp` and copy it to a Git repository of your choice.
The file name must remain `TokenBank.cpp` on GitHub. This is in contrast to the `PUT` method, where the file could have any file name.
The `gadmin` configuration parameters for setting up the connection to GitHub are as follows:
Table 1. Parameters for GitHub Parameter | Description | Example  
---|---|---  
`GSQL.GithubUserAcessToken` | The credential used to access the repository | `anonymous`  
`GSQL.GithubRepository` | The user and repository where the files are held | `sample_user/repository`  
`GSQL.GithubBranch` | The branch to access | `main`  
`GSQL.GithubPath` | Path to the directory in the repository that has `TokenBank.cpp` | `src/`  
`GSQL.GithubUrl` | Optional parameter used for GitHub Enterprise | `https://api.github.com[](https://api.github.com)`  
Use the [`gadmin config set`](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/management-with-gadmin#_gadmin_config_set) command to configure the aforementioned parameters to connect GSQL to the GitHub repository hosting your files.
Below is an example configuration. Remember to run `gadmin config apply` after changing the parameters. If GSQL is already running, you will need to run `gadmin restart all` to restart GSQL before the token functions become available.
```
gadmin config set GSQL.GithubUserAcessToken anonymous
gadmin config set GSQL.GithubRepository tigergraph/ecosys
gadmin config set GSQL.GithubBranch demo_github
gadmin config set GSQL.GithubPath sample_code/src
gadmin config apply
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

After the parameters are successfully configured, you can access your user-defined token functions right away.
## [](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/add-token-function#_store_token_functions_locally)Store token functions locally
All UDF files are scanned by the system to ensure that they comply with the UDF file policy as set by configuration commands in TigerGraph Server. For more details, see [TigerGraph Server - Security](https://docs.tigergraph.com/tigergraph-server/4.2/security/).
### [](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/add-token-function#_step_1_enable_adding_a_tokenbank_with_put)Step 1: Enable adding a TokenBank with PUT
Run the following commands to enable uploading a TokenBank through the GSQL `PUT` command:
```
$ gadmin config set GSQL.UDF.EnablePutTokenBank true
$ gadmin config apply
$ gadmin restart gsql
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/add-token-function#_step_2_modify_the_current_tokenbank_file)Step 2: Modify the current TokenBank file
Use the `GET TokenBank` command in GSQL to download the current file to any location on your machine. The path after the keyword `TO` specifies the path where the `file` will be output to.
The file must end with the file extension `.cpp`. The file and the directories will be created if they do not exist.
```
GSQL > GET TokenBank TO "/home/tigergraph/TokenBank.cpp"
GET TokenBank successfully.
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

If you only supply a directory but not a filename, the file will be created with the default filename `TokenBank.cpp`.
### [](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/add-token-function#_step_3_define_your_token_function)Step 3: Define your token function
Write your function in `TokenBank.cpp`.
If any code in `TokenBank.cpp` causes a compilation error, GSQL will be unable to run _any_ loading jobs, whether containing user-defined token functions or not.  
---  
### [](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/add-token-function#_step_4_store_the_modified_tokenbank_cpp_file)Step 4: Store the modified TokenBank.cpp file
After defining the token function, use the `PUT TokenBank` command to store the file so that GSQL can read it. The path after the keyword `FROM` is the absolute path to the `TokenBank.cpp` file.
```
GSQL > PUT TokenBank FROM "/home/tigergraph/TokenBank.cpp"
PUT TokenBank successfully.
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The `PUT` command will automatically store the files in all nodes in a cluster, overwriting any existing files that contain token functions. Once the file is stored, you will be able to call the user-defined token function the next time GSQL is executed. This includes the next time you start the GSQL shell or execute GSQL scripts from a bash shell.
### [](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/add-token-function#_step_5_disable_adding_a_tokenbank_with_put)Step 5: Disable adding a TokenBank with PUT
For best security practices, run the following commands to once more disable uploading a TokenBank through the GSQL `PUT` command:
```
$ gadmin config set GSQL.UDF.EnablePutTokenBank false
$ gadmin config apply
$ gadmin restart gsql
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

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


