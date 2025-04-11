![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query)[Next](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query)
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
[Resources](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query)
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
  * Tutorials
  * [GSQL 101](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/)
  * [Parameterized Queries](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/3.10/modules/tutorials/pages/gsql-101/parameterized-gsql-query.adoc)
### Contents
  * [A simple 1-hop query](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query#_a_simple_1_hop_query)
  * [Create a query](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query#_create_a_query)
  * [Install a query](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query#_install_a_query)
  * [Run a query in GSQL](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query#_run_a_query_in_gsql)
  * [Run a query as a REST endpoint](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query#_run_a_query_as_a_rest_endpoint)
  * [Running anonymous queries without installing](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query#_running_anonymous_queries_without_installing)
  * [Query with accumulators](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query#_query_with_accumulators)
  * [Method](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query#_method)
  * [Query](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query#_query)
  * [Run query from a GSQL script](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query#_run_query_from_a_gsql_script)
  * [GSQL query summary](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query#_gsql_query_summary)


# Develop Parameterized Queries - GSQL 101
### Contents
  * [A simple 1-hop query](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query#_a_simple_1_hop_query)
  * [Create a query](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query#_create_a_query)
  * [Install a query](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query#_install_a_query)
  * [Run a query in GSQL](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query#_run_a_query_in_gsql)
  * [Run a query as a REST endpoint](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query#_run_a_query_as_a_rest_endpoint)
  * [Running anonymous queries without installing](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query#_running_anonymous_queries_without_installing)
  * [Query with accumulators](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query#_query_with_accumulators)
  * [Method](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query#_method)
  * [Query](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query#_query)
  * [Run query from a GSQL script](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query#_run_query_from_a_gsql_script)
  * [GSQL query summary](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query#_gsql_query_summary)


We just saw how easy and quick it is to run simple built-in queries. However, you’ll undoubtedly want to create more customized or complex queries. GSQL puts maximum power in your hands through parameterized vertex set queries.
Parameterized queries let you traverse the graph from one vertex set to an adjacent set of vertices, again and again, performing computations along the way, with built-in parallel execution and handy aggregation operations. You can even have one query call another query. But we’ll start simple.
A GSQL parameterized query has three steps.
  1. Define your query in GSQL. This query will be added to the GSQL catalog.
  2. Install one or more queries in the catalog, generating a REST endpoint for each query.
  3. Run an installed query, supplying appropriate parameters, either as a GSQL command or by sending an HTTP request to the REST endpoint.


## [](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query#_a_simple_1_hop_query)A simple 1-hop query
Now, let’s write our first GSQL query. We’ll display all the direct (1-hop) neighbors of a person, given as an input parameter.
If you run this query in interactive mode, you’ll need to add `BEGIN` and `END` statements. However, just examine it for now. You will save this query to a file and run it from the GSQL shell.
GSQL command
```
USE GRAPH Social
SET syntax_version="v2"
CREATE QUERY hello (VERTEX<Person> p) {
 start = {p};
 result = SELECT tgt
      FROM start:s -(Friendship:e)- Person:tgt;
 PRINT result;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This query features one `SELECT` statement. The query starts by seeding a vertex set `start` with the person vertex identified by parameter _p_ passed in from the query call. The curly braces tell GSQL to construct a set containing the enclosed items.
Next, the `SELECT` statement describes a 1-hop traversal according to the pattern described in the `FROM` clause:
`start:s -(Friendship:e)- Person:tgt`
The pattern means we select all edges beginning from the given source set (`start`), which have the given undirected edge type (`Friendship`) and which end at the given vertex type (`Person`). The `FROM` clause defines vertex and edge set aliases using `:<alias>`:
  * `s` is the alias for the source vertex,
  * `e` is the edge alias
  * `tgt` is the target vertex alias.


Refer back to the initial clause and the assignment (`result = SELECT tgt`). Here we see the target set’s alias `tgt`. This means that the `SELECT` statement returns the target vertex set (as filtered and processed by the full set of clauses in the `SELECT` query block) and assign that output set to the variable called `result`.
Last, we print out the `result` vertex set, in JSON format.
## [](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query#_create_a_query)Create a query
Rather than defining our query in interactive mode, we can store the query in a file and invoke the file from within the GSQL shell, using the `@filename` syntax. Copy and paste the above query into a file `/home/tigergraph/hello.gsql`. Then, enter the GSQL shell and invoke the file using `@hello.qsql`.
If you are not in the `/home/tigergraph` folder when you start GSQL, you can use the absolute path to invoke a `.gsql` file. e.g., `@/home/tigergraph/hello.gsql`  
---  
Run the `ls` command to see that the query is now in the catalog.
GSQL shell
```
GSQL > @hello.gsql
Using graph 'Social'
Successfully created queries: [hello].
GSQL > ls
---- Graph Social
Vertex Types:
 - VERTEX Person(PRIMARY_ID name STRING, name STRING, age INT, gender STRING, state STRING) WITH STATS="OUTDEGREE_BY_EDGETYPE"
Edge Types:
 - UNDIRECTED EDGE Friendship(from Person, to Person, connect_day DATETIME)
Graphs:
 - Graph Social(Person:v, Friendship:e)
Jobs:
 - CREATE LOADING JOB load_Social FOR GRAPH Social {
   DEFINE FILENAME file2 = "/home/tigergraph/friendship.csv";
   DEFINE FILENAME file1 = "/home/tigergraph/person.csv";
   LOAD file1 TO VERTEX Person VALUES($"name", $"name", $"age", $"gender", $"state") USING SEPARATOR=",", HEADER="true", EOL="\n";
   LOAD file2 TO EDGE Friendship VALUES($0, $1, $2) USING SEPARATOR=",", HEADER="true", EOL="\n";
  }
Queries:
 - hello(vertex<Person> p)
SessionParameters:
 - syntax_version: v2
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query#_install_a_query)Install a query
However, the query is not installed yet. In the GSQL shell, type the following command to install the newly-added query "hello".
GSQL command
```
INSTALL QUERY hello
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

GSQL shell
```
GSQL > INSTALL QUERY hello
Start installing queries, about 1 minute ...
hello query: curl -X GET 'http://127.0.0.1:9000/query/social/hello?p=VALUE'. Add -H "Authorization: Bearer TOKEN" if authentication is enabled.
Select 'm1' as compile server, now connecting ...
Node 'm1' is prepared as compile server.
[========================================================================================================] 100% (1/1)
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

It takes about 1 minute for the database to install this new query. Be patient! For queries on large datasets, this small investment pays off many times over in faster query execution, particularly if you will run the query many times, with different parameters. The installation will generate machine instructions and a REST endpoint. After the progress bar reaches 100%, we are ready to run this query.
## [](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query#_run_a_query_in_gsql)Run a query in GSQL
To run a query in GSQL, use `RUN QUERY` followed by the query name and a set of parameter values.
GSQL command - run query examples
```
RUN QUERY hello("Tom")
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The result is presented in JSON format. Tom has two 1-hop neighbors, namely Dan and Jenny.
GSQL shell
```
GSQL > RUN QUERY hello("Tom")
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{"Result": [
  {
   "v_id": "Dan",
   "attributes": {
    "gender": "male",
    "name": "Dan",
    "state": "ny",
    "age": 34
   },
   "v_type": "Person"
  },
  {
   "v_id": "Jenny",
   "attributes": {
    "gender": "female",
    "name": "Jenny",
    "state": "tx",
    "age": 25
   },
   "v_type": "Person"
  }
 ]}]
}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query#_run_a_query_as_a_rest_endpoint)Run a query as a REST endpoint
Under the hood, installing a query will also generate a REST endpoint, so that the parameterized query can be invoked by an HTTP call. In Linux, the `curl` command is the most popular way to submit an HTTP request.
The JSON result will be returned to the Linux shell’s standard output. Our parameterized query thus becomes an HTTP service.
Linux shell
```
curl -X GET 'http://localhost:9000/query/Social/hello?p=Tom'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Finally, to see the GSQL text of a query in the catalog, you can use `SHOW QUERY <query_name>`.
Congratulations! At this point, you have gone through the whole process of defining, installing, and running a query.
## [](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query#_running_anonymous_queries_without_installing)Running anonymous queries without installing
Installing a query will give the fastest query speed, but the user needs to wait for the installation overhead.
The Interpreted Mode for GSQL lets us skip the `INSTALL` step, and even run a query as soon as we create it, to offer a more interactive experience. These one-step interpreted queries are unnamed (anonymous) and parameterless, just like SQL. Please refer to [Pattern Matching](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/pattern-matching/prepare-environment) for this mode.
## [](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query#_query_with_accumulators)Query with accumulators
Now, let’s write a more advanced query. This time, we are going to learn to use the powerful built-in accumulators, which serve as the runtime attributes (properties) attachable to each vertex visited during our traversal on the graph.
"Runtime" means they exist only while the query is running; they are called accumulators because they are specially designed to gather (accumulate) data during the implicitly parallel processing of the query.
Say we need to write a query to find all the persons which are exactly 2 hops away from the parameterized input Person. Just for fun, let’s also compute the average age of those 2-hop neighbors.
### [](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query#_method)Method
To get all `Person` vertices that are two hops away from the starting vertex, we can use the following logic:
  1. From the starting vertex, visit vertices that are one stop away from the starting vertex, and mark every vertex we visit as visited, including the starting vertex. This gives us the neighbors that are 1 hop away from the starting vertex.
  2. Now that we have the 1-hop neighbors, we can find vertices that are 1-hop away from those neighbors, excluding all vertices that we have already visited in the previous step. This gives us all vertices that are exactly two hops away from the original vertex. As we visit the 2-hop neighbors, we can also calculate their average age.


### [](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query#_query)Query
We will use a `SELECT` statement to perform the first hop from the starting vertex. In order to keep track of vertices that have been visited, we declare a vertex-attached accumulator of the type `OrAccum`, also called a _boolean accumulator_. In addition, we also need to declare an `AvgAccum` to calculate the average age of the final vertex set.
To declare a vertex-attached accumulator, prefix an identifier name with a single `@` symbol. After you declare the accumulator, they are attached to vertices in the query, and you can access its value in an `ACCUM` or `POST-ACCUM` clause of the `SELECT` statement by using the dot`.` operator following a vertex alias as if they are an attribute of the vertices.
After the first hop, we use another `SELECT` statement to perform a second hop, and filter out all vertices that we have visited previously. This gives us the neighbors that are exactly two hops away, and we can use the `AvgAccum` to calculate the average age of the 2-hop neighbors.
```
CREATE QUERY hello2 (VERTEX<Person> p) {
  OrAccum @visited = FALSE;
  AvgAccum @@avg_age;
  start = {p};
  first_neighbors = SELECT tgt
    FROM start:s -(Friendship:e)- Person:tgt
    ACCUM tgt.@visited += TRUE, s.@visited += TRUE; **(1)** **(2)**
  second_neighbors = SELECT tgt **(3)**
    FROM first_neighbors -(:e)- :tgt **(4)**
    WHERE tgt.@visited == FALSE **(5)**
    POST-ACCUM @@avg_age += tgt.age; **(6)**
  PRINT second_neighbors;
  PRINT @@avg_age;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | After defining the Start set, we then have our first one 1-hop traversal. The `SELECT` and `FROM` clauses are the same as in our first example, but there is an additional `ACCUM` clause.  
---|---  
**2** | The statements in the `ACCUM` clause are executed once for each edge matching the `FROM` clause. The `+=` operator within an `ACCUM` clause means that for each edge matching the `FROM` clause pattern, we accumulate the right-hand-side expression (`true`) to the left-hand-accumulator (`tgt.@visited` as well as `s.@visited`).  
**3** | The second `SELECT` block will do one hop further, starting from the `first_neighbors` vertex set variable, and reaching the 2-hop neighbors.  
**4** | Types are omitted in this `FROM` clause, which is interpreted to be all types.  
**5** | The `WHERE` clause filters out the vertices which have been marked as visited before (the 1-hop neighbors and the starting vertex _p_ ).  
**6** | `POST_ACCUM` traverses the vertex sets instead of the edge sets, guaranteeing that we do not double-count any vertices. Here, we accumulate the ages of the 2-hop neighbors to get their average.  
Note that a source vertex or target vertex may be visited multiple times in the first `SELECT` statement. Referring to Figure 1, if we start at vertex Tom, there are two edges incidental to Tom, so the `ACCUM` clause in the first `SELECT` statement will visit Tom twice. Since the accumulator type is `OrAccum`, the cumulative effect of the two traversals is the following:
`Tom.@visited = (initial value: false) OR (true) OR (true)`
We can see it does not matter which of the two edges was processed first. The net effect is that as long as a vertex is visited at least once, it will end up with `@visited = true`.
### [](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query#_run_query_from_a_gsql_script)Run query from a GSQL script
This time, we put all following GSQL commands into one file hello2.gsql:
GSQL command file - hello2.gsql
```
USE GRAPH Social
CREATE QUERY hello2 (VERTEX<Person> p) {
  OrAccum @visited = FALSE;
  AvgAccum @@avg_age;
  start = {p};
  first_neighbors = SELECT tgt
    FROM start:s -(Friendship:e)- Person:tgt
    ACCUM tgt.@visited += TRUE, s.@visited += TRUE; **(1)** **(2)**
  second_neighbors = SELECT tgt **(3)**
    FROM first_neighbors -(:e)- :tgt **(4)**
    WHERE tgt.@visited == FALSE **(5)**
    POST-ACCUM @@avg_age += tgt.age;
  PRINT second_neighbors;
  PRINT @@avg_age;
}
INSTALL QUERY hello2
RUN QUERY hello2("Tom")
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

We can execute this full set of commands _without_ entering the GSQL shell. Please copy and paste the above GSQL commands into a Linux file named `/home/tigergraph/hello2.gsql`.
In a Linux shell, under `/home/tigergraph`, type the following to create, install, and execute the query:
Linux shell
```
gsql hello2.gsql
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query#_gsql_query_summary)GSQL query summary
  * Queries are installed in the catalog and can have one or more input parameters, enabling reuse of queries.
  * A GSQL query consists of a series of SELECT query blocks, each generating a named vertex set.
  * Each SELECT query block can start traversing the graph from any of the previously defined vertex sets (that is, the sequence does not have to form a linear chain).
  * Accumulators are runtime variables with built-in accumulation operations, for efficient multithreaded computation.
  * Query can call another query.
  * Output is in JSON format.


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


