![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes)[Next](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes)
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
[Resources](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes)
[Developer Site](https://dev.tigergraph.com/) [Community Forum](https://community.tigergraph.com/) [Knowledge Base](https://tigergraph.freshdesk.com/support/solutions)
[Download](https://dl.tigergraph.com)
[ TG Savanna](https://savanna.tgcloud.io)
### [GSQL Language Reference](https://docs.tigergraph.com/gsql-ref/4.2/intro/)
  *     * [Query Language Tutorials](https://docs.tigergraph.com/gsql-ref/4.2/tutorials/)
      * [What sets GSQL apart](https://docs.tigergraph.com/gsql-ref/4.2/intro/set-gsql-apart)
      * [GSQL V3 Tutorial](https://github.com/tigergraph/ecosys/blob/master/tutorials/GSQL.md)
      * [Accumulators Tutorial](https://docs.tigergraph.com/gsql-ref/4.2/tutorials/accumulators-tutorial)
      * [TigerGraph OpenCypher](https://github.com/tigergraph/ecosys/blob/master/tutorials/Cypher.md)
      * [Hybrid Vector Search](https://github.com/tigergraph/ecosys/tree/master/tutorials/vector)
  *     * [Running GSQL](https://docs.tigergraph.com/gsql-ref/4.2/basics/running-gsql)
  *     * [Defining a Schema](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/)
      * [Data Types](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/attribute-data-types)
      * [Define a Graph Schema](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/defining-a-graph-schema)
      * [Modify a Graph Schema](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/modifying-a-graph-schema)
    * [Loading Data](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/loading-jobs)
      * [Create a Loading Job](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/creating-a-loading-job)
        * [Functions](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/)
          * [Token Functions](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/)
            * [flatten()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/flatten)
            * [flatten_json_array()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/flatten_json_array)
            * [gsql_concat()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_concat)
            * [gsql_current_time_epoch()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_current_time_epoch)
            * [gsql_day()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_day)
            * [gsql_day_epoch()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_day_epoch)
            * [gsql_find()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_find)
            * [gsql_length()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_length)
            * [gsql_lower()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_lower)
            * [gsql_ltrim()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_ltrim)
            * [gsql_month()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_month)
            * [gsql_month_epoch()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_month_epoch)
            * [gsql_regex_match()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_regex_match)
            * [gsql_regex_replace()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_regex_replace)
            * [gsql_reverse()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_reverse)
            * [gsql_rtrim()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_rtrim)
            * [gsql_substring()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_substring)
            * [gsql_to_bool()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_to_bool)
            * [gsql_to_int()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_to_int)
            * [gsql_to_uint()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_to_uint)
            * [gsql_trim()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_trim)
            * [gsql_ts_to_epoch_seconds()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_ts_to_epoch)
            * [gsql_upper()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_upper)
            * [gsql_uuid_v4()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_uuid_v4)
            * [gsql_year()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_year)
            * [gsql_year_epoch()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_year_epoch)
            * [split()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/split)
          * [Token Functions in WHERE Clause](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token_where/)
            * [concat()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token_where/concat)
            * [gsql_is_false()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token_where/gsql_is_false)
            * [gsql_is_not_empty()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token_where/gsql_is_not_empty)
            * [gsql_is_true()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token_where/gsql_is_true)
            * [gsql_token_equal()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token_where/gsql_token_equal)
            * [gsql_token_ignore_case_equal()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token_where/gsql_token_ignore_case_equal)
            * [to_float()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token_where/to_float)
            * [to_int()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token_where/to_int)
            * [token_len()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token_where/token_len)
          * [Reducer functions](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/reducer/)
            * [add()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/reducer/add)
            * [and()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/reducer/and)
            * [ignore_if_exists()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/reducer/ignore_if_exists)
            * [max()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/reducer/max)
            * [min()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/reducer/min)
            * [or()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/reducer/or)
        * [Add a User-defined Token Function](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/add-token-function)
      * [Run a Loading Job](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/running-a-loading-job)
      * [Manage Loading Jobs](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/managing-loading-job)
  *     * [Querying Choices](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes)
    * [Create and Run Queries](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-operations)
      * [Distributed Query Mode](https://docs.tigergraph.com/gsql-ref/4.2/querying/distributed-query-mode)
    * [GSQL Language](https://docs.tigergraph.com/gsql-ref/4.2/querying/)
      * [GSQL Syntax Versions](https://docs.tigergraph.com/gsql-ref/4.2/querying/syntax-versions)
      * [Data Types](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types)
      * [Accumulators](https://docs.tigergraph.com/gsql-ref/4.2/querying/accumulators)
      * [SELECT Statement](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/)
        * [SELECT Statement (Syntax V1)](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/select-statement-v1)
        * [SQL-like SELECT statement](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/sql-like-select-statement)
      * [Operators and Expressions](https://docs.tigergraph.com/gsql-ref/4.2/querying/operators-and-expressions)
      * [Functions](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/)
        * [Aggregation Functions](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/aggregation-functions)
        * [Context Functions](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/context-functions)
        * [Datetime Functions](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/datetime-functions)
        * [Edge Methods](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/edge-methods)
        * [JSON Object Methods](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/json-object-methods)
        * [JSON Array Methods](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/jsonarray-methods)
        * [List Functions](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/list-functions)
        * [Mathematical Functions](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/mathematical-functions)
        * [Miscellaneous Functions](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/miscellaneous-functions)
        * [Query User-Defined Functions](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/query-user-defined-functions)
        * [String Functions](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/string-functions)
        * [Type Conversion Functions](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/type-conversion-functions)
        * [Vector Functions](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/vector-functions)
        * [Vertex Functions](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/vertex-methods)
      * [Declaration and Assignment Statements](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements)
      * [Control Flow](https://docs.tigergraph.com/gsql-ref/4.2/querying/control-flow-statements)
      * [Updating Data](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-modification-statements)
      * [Writing Output](https://docs.tigergraph.com/gsql-ref/4.2/querying/output-statements-and-file-objects)
        * [Write Output to Cloud](https://docs.tigergraph.com/gsql-ref/4.2/querying/write-output-to-cloud)
      * [Exception Statements](https://docs.tigergraph.com/gsql-ref/4.2/querying/exception-statements)
      * [Comments](https://docs.tigergraph.com/gsql-ref/4.2/querying/comments)
    * Profile and Optimize
      * [Query Plan Cache](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-plan-cache)
      * [Query Profiling](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling)
      * [Query Optimizer (Preview)](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/)
        * [Enable Query Optimizer](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/enable-cost-optimizer)
        * [Statistics REST APIs](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/stats-api)
  *     * [openCypher in GSQL](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/)
      * [Writing and Running openCypher in GSQL Shell](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/openCypher-in-gsql-web-shell)
      * [openCypher Pattern Support in GSQL](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/openCypher-gsql-from-clause-extension)
  *     * [Vector Searches](https://docs.tigergraph.com/gsql-ref/4.2/vector/)
  *     * Appendix
      * [Common Errors and Problems](https://docs.tigergraph.com/gsql-ref/4.2/appendix/common-errors-and-problems)
      * [DLL Keywords & Reserved Words](https://docs.tigergraph.com/gsql-ref/4.2/appendix/keywords-and-reserved-words)
      * [Documentation Notation](https://docs.tigergraph.com/gsql-ref/4.2/appendix/notations)
      * [Example Graphs](https://docs.tigergraph.com/gsql-ref/4.2/appendix/example-graphs)
      * [GSQL Cheat Sheets](https://docs.tigergraph.com/gsql-ref/4.2/appendix/cheat-sheets)
      * [GSQL Start-to-End Process and Data Flow](https://docs.tigergraph.com/gsql-ref/4.2/appendix/gsql-start-to-end-process)
      * [GSQL Style Guide](https://docs.tigergraph.com/gsql-ref/4.2/appendix/gsql-style-guide)
      * [Interpreted GSQL Limitations](https://docs.tigergraph.com/gsql-ref/4.2/appendix/interpreted-gsql-limitations)
      * [Legacy Version Documentation](https://docs.tigergraph.com/gsql-ref/4.2/appendix/legacy-tg-versions)
      * [Query Language Keywords & Reserved Words](https://docs.tigergraph.com/gsql-ref/4.2/appendix/query-language-reserved-words)


GSQL Language Reference 4.2 Pre
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
  * [GSQL Language Reference 4.2 Pre](https://docs.tigergraph.com/gsql-ref/4.2/intro/)
  * [Querying Choices](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/4.2/modules/querying/pages/query-modes.adoc)
### Contents
  * [Query Languages](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_query_languages)
  * [GSQL](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_gsql)
  * [OpenCypher](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_opencypher)
  * [GQL](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_gql)
  * [Query Structure](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_query_structure)
  * [Stored Procedure Queries](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_stored_procedure_queries)
  * [Anonymous Queries](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_anonymous_queries)
  * [Non-Procedural Queries](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_non_procedural_queries)
  * [Query APIs](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_query_apis)
  * [Query Execution Modes](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_query_execution_modes)
  * [Install and run a stored procedure query](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_install_and_run_a_stored_procedure_query)
  * [Interpret a stored procedure query](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_interpret_a_stored_procedure_query)
  * [Interpret an ad hoc anonymous query](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_interpret_an_ad_hoc_anonymous_query)
  * [Interpret a non procedural query](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_interpret_a_non_procedural_query)
  * [Distributed Mode](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_distributed_mode)


# Querying Choices
### Contents
  * [Query Languages](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_query_languages)
  * [GSQL](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_gsql)
  * [OpenCypher](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_opencypher)
  * [GQL](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_gql)
  * [Query Structure](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_query_structure)
  * [Stored Procedure Queries](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_stored_procedure_queries)
  * [Anonymous Queries](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_anonymous_queries)
  * [Non-Procedural Queries](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_non_procedural_queries)
  * [Query APIs](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_query_apis)
  * [Query Execution Modes](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_query_execution_modes)
  * [Install and run a stored procedure query](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_install_and_run_a_stored_procedure_query)
  * [Interpret a stored procedure query](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_interpret_a_stored_procedure_query)
  * [Interpret an ad hoc anonymous query](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_interpret_an_ad_hoc_anonymous_query)
  * [Interpret a non procedural query](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_interpret_a_non_procedural_query)
  * [Distributed Mode](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_distributed_mode)


The TigerGraph database provides users with a wide range of choices for how to write and run queries, letting you choose what is the best fit for your needs and preferences.
This page presents the options in a simple outline, pointing out the advantages and typical use cases for each mode or option. It then directs you to where you can learn in more detail about each option.
The following sections will summarize the options in four areas:
  * [Query Languages](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_query_languages)
  * [Query Structure](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_query_structure)
  * [Query APIs](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_query_apis)
  * [Query Execution Modes](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_query_execution_modes)


## [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_query_languages)Query Languages
Query Language Options:
  * [GSQL](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_gsql) | [OpenCypher](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_opencypher) | [GQL](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_gql)


### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_gsql)GSQL
GSQL is [TigerGraph’s original native language](https://docs.tigergraph.com/gsql-ref/4.2/querying/). it offers graph traversal and pattern matching queries using declarative syntax similar to SQL, extends it for procedural programming to enable more complex algorithmic querying, adds _[accumulators](https://docs.tigergraph.com/gsql-ref/4.2/querying/accumulators)_ for efficient analytics, and installs (pre-compiles) queries to optimize the execution performance.
GSQL is more than just for [querying](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-operations) and [schema definition](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/defining-a-graph-schema). It also includes a [data loading language](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/) to define stored procedures (jobs) that map and transform data from tabular sources to a graph.
### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_opencypher)OpenCypher
openCypher is a popular open-source declarative query language for property graphs. It is well suited for basic graph traversal queries and pattern matching queries. More about openCypher can be found at [openCypher.org](http://opencypher.org).
GSQL V3 Syatax [supports the majority of openCypher features](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/), embedded within its native GSQL framework. To learn to how to run OpenCypher on TigerGraph, see the [OpenCypher in GSQL tutorial](https://github.com/tigergraph/ecosys/blob/master/tutorials/Cypher.md).
### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_gql)GQL
GQL is a new ISO standard for a property graph query language. Its initial version was published in 2024, focusing on pattern matching queries. TigerGraph was and is a contributing member of the ISO GQL committee.
GQL borrows from and extends both OpenCypher and GSQL, enabling a graceful transition for users. [GSQL’s V3 Syntax for path patterns](https://github.com/tigergraph/ecosys/blob/master/tutorials/GSQL.md) aligns with GQL’s syntax. GQL can work with both schema-first and schema-optional graph databases.
TigerGraph currently supports the path pattern matching syntax (the `MATCH` or `FROM` clause) of GQL.
  * Use GSQL for analytical and algorithmic queries.
  * Use OpenCypher for graph traversal queries if you are already familar with it.
  * Become familiar with V3 syntax to learn GQL.

  
---  
## [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_query_structure)Query Structure
Query Structure Options:
  * Stored Procedure (Procedural and Saved)
  * Anonymous (Procedural and Ad Hoc)
  * Non-Procedural (Ad Hoc)


### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_stored_procedure_queries)Stored Procedure Queries
Originally, all GSQL queries were **stored procedures**. A stored procedure is a named sequence of executable statements that is **saved** , and then executing by calling it by name. Key characteristics:
  * Looping and conditional flow, to implement algorithms and analytics
  * Input parameters
  * A header and body. The body is bounded by curly braces.
  * Output must be explicitly requested with PRINT statements.


Since this was the only query structure format for some time, we will often simply refer to this choice as a **GSQL query**.   
---  
Example of a Stored Procedure Query
```
CREATE QUERY topMovies(INT year, INT k) {
topK = SELECT m FROM (m:Movie) WHERE m.year == year
    ORDER BY m.boxoffice DESC
    LIMIT k;
PRINT topK;
}
```

### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_anonymous_queries)Anonymous Queries
There are times when you will run a only query one or a few times. You may not want to bother to first save it by name and then call it; you just want to run it. You may be exploring the data as you go, without a full plan in advance. You are building an application that will construct and run custom queries based on the interests of the end user’s real time behavior and requests. Similar to a stored procedura query, except
  * no name
  * no parameters
  * Still has a header, delimited body, and explicit output.


Example of an Anonymous Query
```
INTERPRET QUERY () {
topK = SELECT m FROM (m:Movie) WHERE m.year == 1939
    ORDER BY m.boxoffice DESC
    LIMIT 10;
PRINT topK;
}
```

### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_non_procedural_queries)Non-Procedural Queries
Starting with version 4.2, TigerGraph can run non-procedural queries. This is very much like how the composition of SQL queries:
  * No header.
  * Output selection is implicit.
  * Queries consisting of a single query statement/block do not need to define the body’s start and end.
  * Optionally, can use `BEGIN` and `END` to delimit a multi-line query.


Example of an Non-Procedural Query
```
SELECT m FROM (m:Movie) WHERE m.year == 1939 ORDER BY m.boxoffice DESC LIMIT 10
```

Stored procedural queries with are installed (see Execution Modes) before running will always run faster and more effiiently, sometimes much faster.  
---  
## [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_query_apis)Query APIs
There are four major APIs for running queries and performing other database operations:
  * [GSQL command line interface](https://docs.tigergraph.com/gsql-ref/4.2/basics/running-gsql) (aka GSQL Shell)
  * [REST endpoints](https://docs.tigergraph.com/tigergraph-server/4.2/API/)
  * Graphical user interface, in [GraphStudio](https://docs.tigergraph.com/gui/4.2/graphstudio/overview) or [Savanna](https://docs.tigergraph.com/savanna/main/graph-development/gsql-editor/)
  * [pyTigerGraph](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#pytigergraph:core-functions:) Python language driver


Table 1. Query APIs API (link to documentation) | Description | Use Cases  
---|---|---  
[GSQL CLI](https://docs.tigergraph.com/gsql-ref/4.2/basics/running-gsql) | Classic SQL-like commands | text-based, interactive user  
[REST endpoints](https://docs.tigergraph.com/tigergraph-server/4.2/API/) | HTTP requests, JSON responses | General application development  
[GraphStudio](https://docs.tigergraph.com/gui/4.2/graphstudio/overview), [Savanna](https://docs.tigergraph.com/savanna/main/graph-development/gsql-editor/) | Browser GUI-based interaces for building graphs, developing queries, and running queries | Cloud users, those who prefer a graphical interface  
[pyTigerGraph](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#pytigergraph:core-functions:) | Open-source Python library | Data science applications based on Python  
## [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_query_execution_modes)Query Execution Modes
Excecution Mode Options:
  * Install and run a stored procedure query
  * Interpret a stored procedure query
  * interpret an ad hoc anonymous query
  * Interpret a non procedural query
  * BONUS: Distributed Mode


### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_install_and_run_a_stored_procedure_query)Install and run a stored procedure query
The classic—​and still most performant—​way to run a GSQL query is to create, install it, and run it. The `INSTALL` step provides a level of optimization that is not available when running in interpreted mode.
```
CREATE QUERY topMovies(INT year, INT k) {
topK = SELECT m FROM (m:Movie) WHERE m.year == year
    ORDER BY m.boxoffice DESC
    LIMIT k;
PRINT topK;
}
INSTALL QUERY topMovies
RUN QUERY topMovies(1939, 10)
```

### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_interpret_a_stored_procedure_query)Interpret a stored procedure query
When a developer is writing and refining a stored procedure query, they may be rapidly iterating through different versions of the query. In this case, they may not want to take the time to install the query. And if they are experimenting with a small database, they may not be concerned with the slower run time.
In this case, they can simply skip the `INSTALL` step, and use `INTERPRET` instead of `RUN`:
```
CREATE QUERY topMovies(INT year, INT k) {
topK = SELECT m FROM (m:Movie) WHERE m.year == year
    ORDER BY m.boxoffice DESC
    LIMIT k;
PRINT topK;
}
INTERPRET QUERY topMovies(1939, 10)
```

### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_interpret_an_ad_hoc_anonymous_query)Interpret an ad hoc anonymous query
If we plan to run a query just once, we can skip the step of saving the query. The query is not named, and there is no need to have parameters.
```
INTERPRET QUERY () {
topK = SELECT m FROM (m:Movie) WHERE m.year == 1939
ORDER BY m.boxoffice DESC
LIMIT 10;
PRINT topK;
}
```

When this approach is used by an application that is building the query, users often find the REST API or pyTigerGraph library to be the best fit.  
---  
### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_interpret_a_non_procedural_query)Interpret a non procedural query
This method, introduced in 4.2, is well-suited both for applications and for interactive users, due to its simplicity. If you are running the GSQL shell, you simply type in the query with minimal overhead. There is no `RUN` or `INTERPRET` command; you just submit the query itself.
```
SELECT m FROM (m:Movie) WHERE m.year == 1939 ORDER BY m.boxoffice DESC LIMIT 10
```

For more examples, see the [1-Block Query Examples](https://github.com/tigergraph/ecosys/blob/master/tutorials/GSQL.md#1-block-query-examples) in the GSQL V3 Tutorial.
### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes#_distributed_mode)Distributed Mode
We cannot end without mentioning Distributed Mode. Any procedural query can be run in distributed mode. It is the more performant mode when the query will traverse a large percentage of your graph, especially if it begins the query not at a single vertex but at a large set of vertices.
For more information, see the [Distributed Query Mode](https://docs.tigergraph.com/gsql-ref/4.2/querying/distributed-query-mode) page.
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


