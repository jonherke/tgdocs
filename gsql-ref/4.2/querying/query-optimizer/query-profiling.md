![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling)[Next](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling)
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
[Resources](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling)
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
  * Profile and Optimize
  * [Query Profiling](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/4.2/modules/querying/pages/query-optimizer/query-profiling.adoc)
### Contents
  * [Introduction](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_introduction)
  * [Supported Scope and Limitations](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_supported_scope_and_limitations)
  * [Supported Query Types](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_supported_query_types)
  * [Limitations](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_limitations)
  * [Prerequisite](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_prerequisite)
  * [How to Activate Profiling](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_how_to_activate_profiling)
  * [RESTPP Request](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_restpp_request)
  * [GSQL](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_gsql)
  * [Profiling Data Explanation](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_profiling_data_explanation)
  * [Profile Query Stages Breakdown](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_profile_query_stages_breakdown)
  * [General Metrics](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_general_metrics)
  * [Profiling Data Hierarchy](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_profiling_data_hierarchy)
  * [Disable Query Profiling](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_disable_query_profiling)
  * [Profiling Data Example](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_profiling_data_example)
  * [Example of Profiling Data for Finished Request](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_example_of_profiling_data_for_finished_request)
  * [Example of Realtime Profiling Data for Running Request](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_example_of_realtime_profiling_data_for_running_request)


# Query Profiling
Table of Contents
  * [Introduction](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_introduction)
  * [Supported Scope and Limitations](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_supported_scope_and_limitations)
  * [Prerequisite](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_prerequisite)
  * [How to Activate Profiling](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_how_to_activate_profiling)
  * [Profiling Data Explanation](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_profiling_data_explanation)
  * [Disable Query Profiling](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_disable_query_profiling)
  * [Profiling Data Example](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_profiling_data_example)


This page provides an overview of query profiling in TigerGraph, a feature introduced in version 4.2. Query profiling allows users to view detailed metrics and data about a query’s execution, whether it is running or completed. By analyzing query profiling data, users can identify performance bottlenecks, troubleshoot issues, and optimize queries for better performance.
## [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_introduction)Introduction
Query profiling is designed to provide insights into query execution, allowing users to examine the performance of a query in real-time or after completion. This data helps identify potential areas for optimization and diagnose performance issues. You can use query profiling to gain visibility into execution times, memory usage, and the number of vertices and edges accessed during query processing.
## [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_supported_scope_and_limitations)Supported Scope and Limitations
This feature applies only to GSQL syntax and is not supported for OpenCypher syntax at this time.
### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_supported_query_types)Supported Query Types
Query profiling is supported for the following types of queries:
  * Installed **DISTRIBUTED** user-defined queries
  * Installed **NON-DISTRIBUTED** user-defined queries, if installed with the `-SINGLE` flag (e.g., `INSTALL QUERY -SINGLE q1`)
  * Three built-in endpoints:
    * `/kstep_expansion`
    * `/allpaths`
    * `/searchvertex`


For these queries, profiling data will include more detailed information about memory usage and the overall query execution, as explained in the [Profiling Data Explanation](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_profiling_data_explanation) section below.
### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_limitations)Limitations
While query profiling is a powerful tool for diagnosing and optimizing query performance, there are some limitations:
  * It does not support OpenCypher syntax.
  * It does not support `INTERPRET` queries.
  * It is not available for non-distributed queries unless installed with the `-SINGLE` flag.
  * Profiling does not include data for subqueries.
  * Memory metrics do not account for edge and global accumulators.
  * Topology metrics do not include attribute data.
  * Profiling does not track create/update/delete operations in the topology metric.


## [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_prerequisite)Prerequisite
To enable query profiling, users must have the READ QUERY or OWNERSHIP privileges for the query being executed. If RESTPP authentication is enabled, users will need to ensure they have the appropriate privileges. Otherwise, they may encounter an error message like this:
```
{
 "version": {
  "edition": "enterprise",
  "api": "v2",
  "schema": 1
 },
 "error": true,
 "message": "Insufficient permissions to enable profiling on this request.",
 "required_privileges": {
  "Query Privileges": {
   "GRAPHS": {
    "SocialNet": {
     "QUERIES": {
      "qTest": {
       "QUERY-LEVEL Privileges": [
        "READ [MISSING]"
       ]
      }
     }
    }
   }
  }
 },
 "code": "REST-15001"
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_how_to_activate_profiling)How to Activate Profiling
Activate profiling by setting a profiling mode. Currently, only one profiling mode, `BASIC`, is available. You can choose the appropriate method from the options below based on whether you need real-time profiling or asynchronous query execution.
### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_restpp_request)RESTPP Request
**Option 1: Run the query in the foreground** :
To run a query and view the profile information in real-time, add the `PROFILE: BASIC` header to your RESTPP request:
```
curl -H "PROFILE: BASIC" -X POST 'http://localhost:14240/restpp/query/testGraph/{query_name}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**Option 2: Run the query asynchronously** :
To run a query asynchronously with profiling enabled, add both the `GSQL-ASYNC: true` and `PROFILE: BASIC` headers to your request:
```
curl -H "GSQL-ASYNC: true" -H "PROFILE: BASIC" -X GET 'http://localhost:14240/restpp/query/testGraph/{query_name}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

To fetch real-time profiling data for a query running in asynchronous mode, use the `/query_status` endpoint:
```
curl -X GET "http://localhost:14240/restpp/query_status?requestid=$reqid"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_gsql)GSQL
**Option 1: Run the query in the foreground** :
To run a query and view the profile information in real-time, using the `-PROFILE` flag followed by a profiling mode (e.g. `BASIC`):
```
RUN QUERY -PROFILE BASIC <queryName>
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**Option 2: Run the query asynchronously** :
To run a query asynchronously with profiling enabled, also include the `-async` flag:
```
RUN QUERY -async -PROFILE BASIC <queryName>
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

To fetch real-time profiling data for a query running in asynchronous mode, use the `/query_status` endpoint:
```
curl -X GET "http://localhost:14240/restpp/query_status?requestid=$reqid"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**Option 3: Set profiling for the session** :
You can set the profiling mode for a session in GSQL. Use the `SET PROFILE` command to enable profiling in your session:
```
SET PROFILE = "BASIC"
RUN QUERY <query_name>
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_profiling_data_explanation)Profiling Data Explanation
When profiling is activated, the query result JSON and the `/query_status` output for real-time profiling will include a field called `profile`, which contains the profiling data.
### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_profile_query_stages_breakdown)Profile Query Stages Breakdown
To understand the query profiling stages, consider the following simple example:
```
CREATE DISTRIBUTED QUERY qTest(INT temp) {
	INT threshold = 90;           // statementKey 1 (1 action)
	IF temp > threshold THEN        // statementKey 2 (2 child statements)
	 STRING new_state = "sweat";      // statementKey 2.1 (1 action)
	 vSet = SELECT s from person:s     // statementKey 2.2 (3 actions: create_vset, vertex, reduce)
	     POST-ACCUM s.state = new_state;
	END;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The execution of this query `qTest` can be broken down into the following stages:
  * **Scheduling** : The stage between when TigerGraph receives the request and assigns a thread to process it.
  * **Execution** : This stage includes several sub-stages:
    * **Initialization** : Initializes global variables and starts workers on all nodes for distributed queries.
    * **Processing** : The main logic of the query, including control flow, graph traversal, and data processing.
    * **Finalization** : Constructs and sends the query result.


Within the **Processing** stage, there are two types of fine-grained stages:
  * **Statement** : Represents a complete statement in the original query (e.g., graph traversal, control-flow).
  * **Action** : Represents the smallest unit of execution in the final query plan. A statement without child statements will have child actions, while a statement with child statements will not have child actions.


### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_general_metrics)General Metrics
Query profiling includes several general metrics at different levels (Query, Statement, and Action). Some of the key metrics are:
#### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_executioncount)ExecutionCount
This metric indicates how many times a particular stage has been executed and completed. It does not count stages that are currently in progress.
#### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_time)Time
The time metric provides the following data:
  * **startTime** : The start time of the stage.
  * **endTime** : The end time of the stage.


If the execution count is greater than 1, the **startTime** and **endTime** fields will not be provided.  
---  
#### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_memory)Memory
The memory metric tracks memory usage across different GPE nodes. It includes data for `vertexAccumulator` memory, which represents memory used by vertex-attached accumulators.
Notice the vertexAccumulator include internal variables not explicitly declared in original query, so it can be non-zero even there’s no VERTEX-attached accumulators declared.
Key memory fields:
  * **totalPeakMB** : Peak memory usage during the stage execution.
  * **totalFinalMB** : Memory usage at the end of the stage.


#### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_topology)Topology
Data for this metric is separated to different GPE nodes, with name in format `GPE_<partId>_<replicaId>`.
For each GPE node, this metric contains non-zeros values for following fields:
  * `vertex`
    * `readCount`: The number of accesses to vertices.
  * `edge`
    * `readCount`: The number of accesses to edges.
  * `table`
    * `rowCount`: The number of accesses to table rows.
  * `join`
    * `totalCount`: The total number of join operations.


### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_profiling_data_hierarchy)Profiling Data Hierarchy
Profiling data is organized in three hierarchical levels: Query, Statement, and Action. Each level provides additional details about the query execution.
#### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_query_level)Query Level
This is for field `profile.overall`. It may contain the following extra fields.
  * `runningActionKey`: current on-going action. It only appears before query completes.
  * `time`
    * `scheduling`
      * `schedulingTimeMs`: time spent on “Scheduling”
      * `schedulingTimePercentage`: percentage of `schedulingTimeMs` to the `totalTimeMs`.
    * `execution`
      * `initialization`
        * `initializationTimeMs`: time spent on “Initialization”
        * `initializationTimePercentage`: percentage of `initializationTimeMs` to the `totalTimeMs`.
      * `processing`
        * `processingTimeMs`: time spent on “Processing”
        * `processingTimePercentage`: percentage of `processingTimeMs` to the `totalTimeMs`.
      * `finalization`
        * `finalizationTimeMs`: time spent on “Finalization”
        * `finalizationTimePercentage`: percentage of `finalizationTimeMs` to the `totalTimeMs`.
    * `totalTimeMs`: total time of query run, including “Scheduling” and “Execution”.


#### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_statement_level)Statement Level
Element in `profile.statements` are statement-level entries. A statement-level entry can also contain child statements. Each statement-level entry represents a statement in the original query. It may contain the following extra fields:
  * `statementKey`: this is unique key for this statement in the original query.
  * `statementType`: type of this statement in the original query.
  * `statementText`: text of this statement in the original query.
  * `statementOverall`
    * `time`
      * `processingTimeMs`: time spent on this statement, including all executions.
      * `processingTimePercentage`: percentage of `processingTimeMs` to query-level `totalTimeMs`.
      * `averageProcessingTimeMs`: average process time of each execution. It only appears when `executionCount > 1`.
  * `statements`: child statement entries of this statement.
  * `actions`: child action entries of this statement.


#### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_action_level)Action Level
Elements in `actions` of statement-level entry are action-level entries. Each action-level entry represents a minimum execution unit in execution plan, from final transformed and optimized query. It may contain the following extra fields:
  * `actionKey`: this is unique key for this action.
  * `actionType`: type of this action in the final transformed query.
  * `actionText`: text of this action in the final transformed query.
  * `actionOverall`
    * `time`
      * `processingTimeMs`: time spent on this action, including all executions.
      * `processingTimePercentage`: percentage of `processingTimeMs` to query-level `totalTimeMs`.
      * `averageProcessingTimeMs`: average process time of each execution. It only appears when `executionCount > 1`.


## [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_disable_query_profiling)Disable Query Profiling
If the Query Profiling feature is causing issues, it can be disabled for all installed queries by following this procedure:
  1. Add `DISABLE_PROFILE=true;` to the `GSQL.BasicConfig.Env` [configuration parameter](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters).
  2. Apply the change: `gadmin config apply`
  3. Re-installing all queries.


## [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_profiling_data_example)Profiling Data Example
### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_example_of_profiling_data_for_finished_request)Example of Profiling Data for Finished Request
Below is an example final result for a request of query `qTest`, with profiling enabled. It’s running on a 2x1 cluster.
```
{
 "version": {
  "edition": "enterprise",
  "api": "v2",
  "schema": 0
 },
 "error": false,
 "message": "",
 "results": [],
 "profile": {
  "queryName": "qTest",
  "requestId": "16973826.RESTPP_1_1.1742242555505.N",
  "serverId": "GPE_1_1",
  "overall": {
   "executionCount": 1,
   "time": {
    "startTime": "2025-03-17 20:15:55.505 UTC",
    "endTime": "2025-03-17 20:16:02.420 UTC",
    "totalTimeMs": 6915,
    "scheduling": {
     "schedulingTimeMs": 1,
     "schedulingTimePercentage": 0.0145
    },
    "execution": {
     "executionTimeMs": 6914,
     "executionTimePercentage": 100,
     "initialization": {
      "initializationTimeMs": 4,
      "initializationTimePercentage": 0.0578
     },
     "processing": {
      "processingTimeMs": 6910,
      "processingTimePercentage": 99.9
     },
     "finalization": {
      "finalizationTimeMs": 0,
      "finalizationTimePercentage": 0
     }
    }
   },
   "memory": {
    "GPE_2_1": {
     "vertexAccumulator": {
      "totalPeakMB": 23,
      "totalFinalMB": 21
     }
    },
    "GPE_1_1": {
     "vertexAccumulator": {
      "totalPeakMB": 23,
      "totalFinalMB": 21
     }
    }
   },
   "topology": {
    "GPE_2_1": {
     "vertex": {
      "readCount": 12360296
     }
    },
    "GPE_1_1": {
     "vertex": {
      "readCount": 12368774
     }
    }
   }
  },
  "statements": [....] // Nested statement, details not showm
   }
  ]
 }
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling#_example_of_realtime_profiling_data_for_running_request)Example of Realtime Profiling Data for Running Request
Below is an example output of `/query_status` for an async request of query `qTest`, with profiling enabled, running on a 2x1 cluster. You can notice this field `"runningActionKey": "2.2.3"`, which indicates the current running action. And there’s not much profiling data in `"actionOverall"` for `"actionKey": "2.2.3"`, except for the `"startTime"`.
```
{
 "version": {
  "edition": "enterprise",
  "api": "v2",
  "schema": 0
 },
 "error": false,
 "message": "",
 "results": [
  {
   "requestid": "16973827.RESTPP_1_1.1742242692587.N",
   "startTime": "2025-03-17 20:18:12.587",
   "expirationTime": "2025-03-17 20:18:28.587",
   "url": "/query/SocialNet/qTest?temp=93",
   "elapsedTime": 1137,
   "status": "running",
   "user": "",
   "profile": {
    "queryName": "qTest",
    "requestId": "16973827.RESTPP_1_1.1742242692587.N",
    "serverId": "GPE_2_1",
    "overall": {
     "executionCount": 0,
     "runningActionKey": "2.2.3",
     "time": {
      "startTime": "2025-03-17 20:18:12.583 UTC",
      "scheduling": {
       "schedulingTimeMs": 0
      },
      "execution": {
       "initialization": {
        "initializationTimeMs": 4
       },
       "processing": {}
      }
     },
     "memory": {
      "GPE_1_1": {
       "vertexAccumulator": {
        "totalPeakMB": 24,
        "totalFinalMB": 21
       }
      },
      "GPE_2_1": {
       "vertexAccumulator": {
        "totalPeakMB": 23,
        "totalFinalMB": 21
       }
      }
     },
     "topology": {
      "GPE_1_1": {
       "vertex": {
        "readCount": 6184387
       }
      },
      "GPE_2_1": {
       "vertex": {
        "readCount": 6180148
       }
      }
     }
    },
    "statements": [....] // Nested statement, details not showm
   }
  }
 ],
 "code": "REST-0000"
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

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


