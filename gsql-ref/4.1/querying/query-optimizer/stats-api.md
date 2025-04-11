![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api)[Next](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api)
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
[Resources](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api)
[Developer Site](https://dev.tigergraph.com/) [Community Forum](https://community.tigergraph.com/) [Knowledge Base](https://tigergraph.freshdesk.com/support/solutions)
[Download](https://dl.tigergraph.com)
[ TG Savanna](https://savanna.tgcloud.io)
### [GSQL Language Reference](https://docs.tigergraph.com/gsql-ref/4.1/intro/)
  *     * [Overview](https://docs.tigergraph.com/gsql-ref/4.1/intro/)
    * [What sets GSQL apart](https://docs.tigergraph.com/gsql-ref/4.1/intro/set-gsql-apart)
  *     * [GSQL Tutorials](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/)
      * [GSQL V3 Tutorial](https://github.com/tigergraph/ecosys/blob/master/demos/guru_scripts/docker/tutorial/4.x/README.md)
      * [Accumulators Tutorial](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/accumulators-tutorial)
  *     * [System & Language Basics](https://docs.tigergraph.com/gsql-ref/4.1/basics/system-and-language-basics)
  *     * [Attribute Data Types](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/attribute-data-types)
    * [Schema Definition](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/)
      * [Define a Graph Schema](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema)
      * [Modify a Graph Schema](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/modifying-a-graph-schema)
    * [Loading Jobs](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/loading-jobs)
      * [Create a Loading Job](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/creating-a-loading-job)
        * [Functions](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/)
          * [Token Functions](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/)
            * [flatten()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/flatten)
            * [flatten_json_array()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/flatten_json_array)
            * [gsql_concat()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_concat)
            * [gsql_current_time_epoch()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_current_time_epoch)
            * [gsql_day()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_day)
            * [gsql_day_epoch()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_day_epoch)
            * [gsql_find()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_find)
            * [gsql_length()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_length)
            * [gsql_lower()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_lower)
            * [gsql_ltrim()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_ltrim)
            * [gsql_month()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_month)
            * [gsql_month_epoch()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_month_epoch)
            * [gsql_regex_match()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_regex_match)
            * [gsql_regex_replace()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_regex_replace)
            * [gsql_reverse()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_reverse)
            * [gsql_rtrim()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_rtrim)
            * [gsql_substring()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_substring)
            * [gsql_to_bool()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_to_bool)
            * [gsql_to_int()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_to_int)
            * [gsql_to_uint()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_to_uint)
            * [gsql_trim()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_trim)
            * [gsql_ts_to_epoch_seconds()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_ts_to_epoch)
            * [gsql_upper()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_upper)
            * [gsql_uuid_v4()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_uuid_v4)
            * [gsql_year()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_year)
            * [gsql_year_epoch()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_year_epoch)
            * [split()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/split)
          * [Token Functions in WHERE Clause](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token_where/)
            * [concat()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token_where/concat)
            * [gsql_is_false()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token_where/gsql_is_false)
            * [gsql_is_not_empty()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token_where/gsql_is_not_empty)
            * [gsql_is_true()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token_where/gsql_is_true)
            * [gsql_token_equal()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token_where/gsql_token_equal)
            * [gsql_token_ignore_case_equal()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token_where/gsql_token_ignore_case_equal)
            * [to_float()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token_where/to_float)
            * [to_int()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token_where/to_int)
            * [token_len()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token_where/token_len)
          * [Reducer functions](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/reducer/)
            * [add()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/reducer/add)
            * [and()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/reducer/and)
            * [ignore_if_exists()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/reducer/ignore_if_exists)
            * [max()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/reducer/max)
            * [min()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/reducer/min)
            * [or()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/reducer/or)
        * [Add a User-defined Token Function](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/add-token-function)
      * [Run a Loading Job](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/running-a-loading-job)
      * [Manage Loading Jobs](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/managing-loading-job)
  *     * [Querying](https://docs.tigergraph.com/gsql-ref/4.1/querying/)
      * [Query Language Syntax Versions](https://docs.tigergraph.com/gsql-ref/4.1/querying/syntax-versions)
      * [Queries](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-operations)
      * [Query Optimizer (Preview Feature)](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/)
        * [Enabling Cost-Based Optimization (Preview Feature)](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/enable-cost-optimizer)
        * [Statistics REST APIs (Preview Feature)](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api)
      * [Distributed Query Mode](https://docs.tigergraph.com/gsql-ref/4.1/querying/distributed-query-mode)
      * [Data Types](https://docs.tigergraph.com/gsql-ref/4.1/querying/data-types)
      * [Accumulators](https://docs.tigergraph.com/gsql-ref/4.1/querying/accumulators)
      * [Operators and Expressions](https://docs.tigergraph.com/gsql-ref/4.1/querying/operators-and-expressions)
      * [Functions](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/)
        * [Aggregation Functions](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/aggregation-functions)
        * [Context Functions](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions)
        * [Datetime Functions](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/datetime-functions)
        * [Edge Methods](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/edge-methods)
        * [JSON Object Methods](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/json-object-methods)
        * [JSON Array Methods](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/jsonarray-methods)
        * [List Functions](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/list-functions)
        * [Mathematical Functions](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/mathematical-functions)
        * [Miscellaneous Functions](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/miscellaneous-functions)
        * [Query User-Defined Functions](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/query-user-defined-functions)
        * [String Functions](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions)
        * [Type Conversion Functions](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/type-conversion-functions)
        * [Vector Functions](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vector-functions)
        * [Vertex Functions](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods)
      * [Declaration and Assignment Statements](https://docs.tigergraph.com/gsql-ref/4.1/querying/declaration-and-assignment-statements)
      * [SELECT Statement](https://docs.tigergraph.com/gsql-ref/4.1/querying/select-statement/)
        * [SELECT Statement (Syntax V1)](https://docs.tigergraph.com/gsql-ref/4.1/querying/select-statement/select-statement-v1)
        * [SQL-like SELECT statement](https://docs.tigergraph.com/gsql-ref/4.1/querying/select-statement/sql-like-select-statement)
      * [Control Flow Statements](https://docs.tigergraph.com/gsql-ref/4.1/querying/control-flow-statements)
      * [Data Modification Statements](https://docs.tigergraph.com/gsql-ref/4.1/querying/data-modification-statements)
      * [Output Statements and FILE Objects](https://docs.tigergraph.com/gsql-ref/4.1/querying/output-statements-and-file-objects)
      * [Exception Statements](https://docs.tigergraph.com/gsql-ref/4.1/querying/exception-statements)
      * [Comments](https://docs.tigergraph.com/gsql-ref/4.1/querying/comments)
      * [Write Query Output to Cloud](https://docs.tigergraph.com/gsql-ref/4.1/querying/write-query-data-to-cloud)
  *     * openCypher
      * [OpenCypher Tutorial (on GitHub)](https://github.com/tigergraph/ecosys/blob/master/demos/guru_scripts/docker/tutorial/4.x/Cypher.md)
      * [openCypher in GSQL](https://docs.tigergraph.com/gsql-ref/4.1/openCypher-in-gsql/openCypher-in-gsql)
      * [Writing and Running openCypher in GSQL Shell](https://docs.tigergraph.com/gsql-ref/4.1/openCypher-in-gsql/openCypher-in-gsql-web-shell)
      * [openCypher Pattern Support in GSQL](https://docs.tigergraph.com/gsql-ref/4.1/openCypher-in-gsql/openCypher-gsql-from-clause-extension)
  *     * Appendix
      * [GSQL Style Guide](https://docs.tigergraph.com/gsql-ref/4.1/appendix/gsql-style-guide)
      * [DDL Keywords & Reserved Words](https://docs.tigergraph.com/gsql-ref/4.1/appendix/keywords-and-reserved-words)
      * [Query Language Keywords & Reserved Words](https://docs.tigergraph.com/gsql-ref/4.1/appendix/query-language-reserved-words)
      * [Interpreted GSQL Limitations](https://docs.tigergraph.com/gsql-ref/4.1/appendix/interpreted-gsql-limitations)
      * [GSQL Start-to-End Process and Data Flow](https://docs.tigergraph.com/gsql-ref/4.1/appendix/gsql-start-to-end-process)
      * [Example Graphs](https://docs.tigergraph.com/gsql-ref/4.1/appendix/example-graphs)
      * [Common Errors and Problems](https://docs.tigergraph.com/gsql-ref/4.1/appendix/common-errors-and-problems)
      * [GSQL Cheat Sheets](https://docs.tigergraph.com/gsql-ref/4.1/appendix/cheat-sheets)
      * [Documentation Notations](https://docs.tigergraph.com/gsql-ref/4.1/appendix/notations)
    * [Legacy Version Documentation](https://docs.tigergraph.com/gsql-ref/4.1/appendix/legacy-tg-versions)


GSQL Language Reference 4.1
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
  * [GSQL Language Reference 4.1](https://docs.tigergraph.com/gsql-ref/4.1/intro/)
  * [Querying](https://docs.tigergraph.com/gsql-ref/4.1/querying/)
  * [Query Optimizer (Preview Feature)](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/)
  * [Statistics REST APIs (Preview Feature)](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/4.1/modules/querying/pages/query-optimizer/stats-api.adoc)
### Contents
  * [Cardinality](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_cardinality)
  * [Compute cardinality statistics](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_compute_cardinality_statistics)
  * [Retrieve cardinality statistics](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_retrieve_cardinality_statistics)
  * [Delete cardinality statistics](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_delete_cardinality_statistics)
  * [Histogram](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_histogram)
  * [Compute histogram statistics](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_compute_histogram_statistics)
  * [Retrieve histogram statistics](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_retrieve_histogram_statistics)
  * [Delete histogram statistics](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_delete_histogram_statistics)


# Statistics REST APIs (Preview Feature)
### Contents
  * [Cardinality](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_cardinality)
  * [Compute cardinality statistics](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_compute_cardinality_statistics)
  * [Retrieve cardinality statistics](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_retrieve_cardinality_statistics)
  * [Delete cardinality statistics](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_delete_cardinality_statistics)
  * [Histogram](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_histogram)
  * [Compute histogram statistics](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_compute_histogram_statistics)
  * [Retrieve histogram statistics](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_retrieve_histogram_statistics)
  * [Delete histogram statistics](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_delete_histogram_statistics)


The endpoints on this page calculate cardinality and histogram statistics of vertex and edge types and attributes. The statistics are required for effective optimization.
Query Optimizer is currently a Preview Feature. Preview Features give users an early look at future production-level features. Preview Features should not be used for production deployments.  
---  
## [](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_cardinality)Cardinality
The following endpoints compute, fetch and delete vertex and edge counts (cardinality) of a graph.
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_compute_cardinality_statistics)Compute cardinality statistics
`POST :14240/gsql/v1/stats/cardinality`
This endpoint computes the cardinality statistics for the vertex and edge types specified in the request. The cardinality statistics describe the number of vertices of a specified type, and the number of edges of a specified type between a specified pair of vertex types.
The following header is also required: `-H 'Content-Type: application/json'`
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_parameters)Parameters
Parameter | Description | Type  
---|---|---  
`graph` | Name of the graph. Required. | `STRING`  
`vertex` | Vertex type to compute statistics for. You must provide either the `vertex` or `edge` parameter. | `STRING`  
`edge` | Edge type to compute statistics for. You must provide either the `vertex` or `edge` parameter, but not both. If you provided it an edge type, you also need to provide the `from` and `to` parameters. | `STRING`  
`from` | The source vertex type of an edge. Required if `edge` is provided. | `STRING`  
`to` | The target vertex type of an edge. Required if `edge` is provided. | `STRING`  
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_examples)Examples
The following request computes cardinality for vertex type `Person` in the graph `ldbc_snb`:
```
curl -s --user tigergraph:tigergraph \
-H 'Content-Type: application/json' \
-X POST "http://localhost:14240/gsql/v1/stats/cardinality?graph=ldbc_snb&vertex=Person"
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The following request computes cardinality for edge type `LIKES` from `Person` to `Post` in the graph `ldbc_snb`:
```
curl -s --user tigergraph:tigergraph \
-H 'Content-Type: application/json' \
-X POST "http://localhost:14240/gsql/v1/stats/cardinality?graph=ldbc_snb&edge=LIKES&from=Person&to=Post"
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_retrieve_cardinality_statistics)Retrieve cardinality statistics
`GET :14240/gsql/v1/stats/cardinality`
This endpoint retrieves the cardinality statistics of a graph.
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_parameters_2)Parameters
Parameter | Description | Data type  
---|---|---  
`graph` | Name of the graph. Required. | `STRING`  
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_examples_2)Examples
The following request retrieves the cardinality data for graph `ldbc_snb`:
```
curl -s --user tigergraph:tigergraph \
-H 'Content-Type: application/json' \
-X GET "http://localhost:14240/gsql/v1/stats/cardinality?graph=ldbc_snb"
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_delete_cardinality_statistics)Delete cardinality statistics
`DELETE :14240/gsql/v1/stats/cardinality`
This endpoint deletes the cardinality statistics of a graph.
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_parameters_3)Parameters
Parameter | Description | Data type  
---|---|---  
`graph` | Name of the graph. Required. | `STRING`  
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_examples_3)Examples
The following request deletes the cardinality data for graph `ldbc_snb`:
```
curl -s --user tigergraph:tigergraph \
-H 'Content-Type: application/json' \
-X DELETE "http://localhost:14240/gsql/v1/stats/cardinality?graph=ldbc_snb"
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_histogram)Histogram
Histograms store information about the distribution of attribute values. They are computed using an Equi-Width computation method. This means, given a target bucket count, a histogram will be computed with up to that many buckets (see bucket parameter for more details).
**Bucket Count** : Increasing the number of buckets will increase the granularity of the computed histogram, while decreasing the number of buckets will increase compaction. Choosing the right bucket count should be done based on the use case first, then adjusted afterwards if necessary. Please see recommendations below for best practices.
**NDV** (Number of Distinct Values): This value is approximated for each bucket.
  * Integral datatypes (UINT, INT, DATETIME): the NDV value represents an upper bound (the actual NDV may be lower).
  * Floating point numeric values (FLOAT, DOUBLE): the NDV is approximated by assuming all values are distinct.
  * Primary id’s: the NDV represents the actual NDV and no approximation is used.


**Supported Data Types** : UINT, INT, DATETIME, FLOAT, DOUBLE
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_compute_histogram_statistics)Compute histogram statistics
`POST :14240/gsql/v1/stats/histogram`
This endpoint computes histograms for a specified attribute of a vertex or edge type.
READ_SCHEMA privilege is required for the graph that the histogram attribute belongs to. When gathering for multiple graphs at once (see Compute Multiple Histograms in one request), READ_SCHEMA is required on ALL of those graphs.
The following header is also required: `-H 'Content-Type: application/json'`
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_parameters_4)Parameters
Additional options can be specified in the header using -H: `GSQL-Timeout` indicates timeout for the request. In the case of multiple computations, this timeout covers the overall timeout, including all the histogram computations. `GSQL-Thread-Limit` indicates the thread limit per histogram computation. In the case of multiple computations this thread limit will apply to each histogram computation individually.
Note that multiple headers can be included, for example: `-H 'Content-Type: application/json' -H 'GSQL-Timeout: 1000000' …​`
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_request_body)Request body
The request body expects a JSON object with the following schema:
  * Vertex attribute
  * Edge attribute


```
{
  "graph": <graph_name>,
  "vertex": <vertex_type_name>
  "attribute": <attribute_name>
  "bucket" <bucket_number>
}
```

```
{
  "graph": <graph_name>,
  "edge": <edge_type_name>,
  "attribute": <attribute_name>,
  "bucket" <bucket_number>,
  "from`: <source_vertex_type>,
  "to": <target_vertex_type>
}
```

Parameter | Description | Data type  
---|---|---  
`graph` | Name of the graph. | `STRING`  
`vertex` | Name of the vertex type. | `STRING`  
`edge` | Name of the refined edge type. | `STRING`  
`attribute` | Name of the attribute. | `STRING`  
`bucket` | The number of intervals ([buckets](https://en.wikipedia.org/wiki/Data_binning)) to divide the range of attribute values by. The default value is 256. With integral datatypes, it may be possible that the provided bucket count is too high for the range of values. In such cases, the highest number of buckets that can be used for that range of values will be used instead. | `INT`  
`from` | Source vertex type of a refined edge type. | `STRING`  
`to` | Target edge type of a refined edge type. | `STRING`  
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_examples_4)Examples
The following request computes the histogram data for attribute `length` of vertex type `Comment` on graph `test_graph`:
  * Histogram Computation Request
  * Results


Vertex Attribute Histogram Computation
```
$ curl --user tigergraph:tigergraph \
-H 'Content-Type: application/json' \
-X POST "http://localhost:14240/gsql/v1/stats/histogram" \
-d '{"graph":"test_graph","vertex":"Comment","attribute":"length","bucket":10}'
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
{
 "error": false,
 "message": "Histogram stats gathering completed",
 "results": [
  {
   "success": "[1/1]",
   "failure": []
  }
 ]
}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The following request computes the histogram data for attribute `joinDate` from edge type `COMP_MEMBER` between from vertex `compForum` and to vertex `compPerson` on graph `test_graph`:
  * Histogram Computation Request
  * Results


Edge Attribute Histogram Computation
```
$ curl --user tigergraph:tigergraph \
-H 'Content-Type: application/json' \
-X POST "http://localhost:14240/gsql/v1/stats/histogram" \
-d '{"graph":"test_graph","edge":"COMP_MEMBER","from":"compForum","to":"compPerson","attribute":"joinDate","bucket":10}'
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
{
 "error": false,
 "message": "Histogram stats gathering completed",
 "results": [
  {
   "success": "[1/1]",
   "failure": []
  }
 ]
}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_compute_multiple_histograms_together)Compute Multiple Histograms together
In addition to requesting individual histograms through the POST endpoint, it is also possible to request all valid histograms on a per schema object basis. The`bucket` parameter can still be specified and will be applied to every histogram being computed in the request.
Respecting the dependency of lower level schema objects, this can be done as follows:
```
// Compute Histograms for ALL valid attributes (default bucket value)
-d '{}'
// Compute Histograms for ALL valid attributes (bucket specified)
-d '{"bucket":"10"}'
// Compute Histograms for ALL valid attributes under:
// graph test_graph
// (default bucket value)
-d '{"graph":"test_graph"}'
// Compute Histograms for ALL valid attributes under:
// graph test_graph
// vertex Comment
// (default bucket value)
-d '{"graph":"test_graph", "vertex":"Comment"}'
// Compute Histograms for ALL valid attributes under:
// graph test_graph
// vertex Comment
// (default bucket value)
-d '{"graph":"test_graph", "vertex":"Comment"}'
// Compute Histograms for ALL valid attributes and from/to vertices under:
// graph test_graph
// edge COMP_MEMBER
// (default bucket value)
-d '{"graph":"test_graph", "edge":"COMP_MEMBER"}'
// Compute Histograms for ALL from/to vertices for attribute joinDate:
// graph test_graph
// edge COMP_MEMBER
// attribute joinDate
// (default bucket value)
-d '{"graph":"test_graph", "edge":"COMP_MEMBER", "attribute":"joinDate"}'
// Compute Histograms for ALL valid attributes under:
// graph test_graph
// edge COMP_MEMBER, from vertex compForum, to vertex compPerson
// (default bucket value)
-d '{"graph":"test_graph", "edge":"COMP_MEMBER", "from":"compForum", "to":"compPerson"}'
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The output generated is in the same format as individual computation, with the `success` field tracking the total number of successful computations and `failure` tracking all of the failures encountered:
  * Histogram Computation Request
  * Results


Gather ALL Histogram Computation
```
$ curl --user tigergraph:tigergraph \
-H 'Content-Type: application/json' \
-X POST "http://localhost:14240/gsql/v1/stats/histogram" \
-d '{}'
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
{
 "error": false,
 "message": "Histogram stats gathering completed",
 "results": [
  {
   "failure": [],
   "success": "[94/94]"
  }
 ]
}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

A more condensed error message will be provided under `failure` if any of the histogram computations encounter an error. This allows the request to log the error and continue with the next computation. For more information on the specific error refer to the logs or run the particular histogram computation individually for more verbose feedback.
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_retrieve_histogram_statistics)Retrieve histogram statistics
`READ_DATA` privilege is required to retrieve a histogram for a particular attribute. This can be at the attribute level or a higher level. Note that for edge-based histograms, the 'from' and 'to' vertex are not read and therefore only the edge requires the privilege.
`GET :14240/gsql/v1/stats/histogram`
This endpoint retrieves histogram data for a specified attribute of a vertex or edge type. Empty buckets in the histogram are denoted by a totalCount, upperCount, and ndv of zero. The upperBound will have the max theoretical value for an empty bucket.
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_request_body_2)Request Body
Parameter | Description | Data type  
---|---|---  
`graph` | Name of the graph. | `STRING`  
`vertex` | Name of the vertex type. | `STRING`  
`edge` | Name of the refined edge type. | `STRING`  
`from` | Source vertex type of a refined edge type. | `STRING`  
`to` | Target edge type of a refined edge type. | `STRING`  
`attribute` | Name of the attribute. | `STRING`  
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_examples_5)Examples
  * Histogram Retrieval Request
  * Results Histogram Exists
  * Results Histogram Does Not Exist


Retrieve Vertex Attribute Histogram
```
$ curl --user tigergraph:tigergraph \
-H 'Content-Type: application/json' \
-X GET "http://localhost:14240/gsql/v1/stats/histogram" \
-d '{"graph":"test_graph","vertex":"Comment","attribute":"length","bucket":10}'
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
{
 "error": false,
 "message": "",
 "results": [
  {
   "histogram": [
    {
     "ndv": 1,
     "upperBound": 1988,
     "rowsUpper": 1,
     "rowsTotal": 1
    },
    {
     "ndv": 0,
     "upperBound": 1789,
     "rowsUpper": 0,
     "rowsTotal": 0
    },
    {
     "ndv": 1,
     "upperBound": 1402,
     "rowsUpper": 1,
     "rowsTotal": 1
    },
    {
     "ndv": 1,
     "upperBound": 1211,
     "rowsUpper": 1,
     "rowsTotal": 1
    },
    {
     "ndv": 1,
     "upperBound": 1119,
     "rowsUpper": 1,
     "rowsTotal": 1
    },
    {
     "ndv": 1,
     "upperBound": 908,
     "rowsUpper": 1,
     "rowsTotal": 1
    },
    {
     "ndv": 116,
     "upperBound": 183,
     "rowsUpper": 90,
     "rowsTotal": 151037
    },
    {
     "ndv": 0,
     "upperBound": 399,
     "rowsUpper": 0,
     "rowsTotal": 0
    },
    {
     "ndv": 0,
     "upperBound": 598,
     "rowsUpper": 0,
     "rowsTotal": 0
    },
    {
     "ndv": 1,
     "upperBound": 710,
     "rowsUpper": 1,
     "rowsTotal": 1
    }
   ],
   "gatherEnd": "2024-05-07 19:09:03",
   "gatherStart": "2024-05-07 19:09:03"
  }
 ]
}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
{
 "error": true,
 "message": "Histogram does not exist for test_graph.Comment.length",
 "results": ""
}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * Histogram Retrieval Request
  * Results Histogram Exists
  * Results Histogram Does Not Exist


Retrieve Edge Attribute Histogram
```
$ curl --user tigergraph:tigergraph \
-H 'Content-Type: application/json' \
-X GET "http://localhost:14240/gsql/v1/stats/histogram" \
-d '{"graph":"test_graph","edge":"COMP_MEMBER","from":"compForum","to":"compPerson","attribute":"joinDate","bucket":10}'
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
{
 "error": false,
 "message": "",
 "results": [
  {
   "histogram": [
    {
     "ndv": 1,
     "upperBound": "2012-09-03 16:44:14",
     "rowsUpper": 1,
     "rowsTotal": 1
    },
    {
     "ndv": 2,
     "upperBound": "2012-04-15 18:07:22",
     "rowsUpper": 1,
     "rowsTotal": 2
    },
    {
     "ndv": 0,
     "upperBound": "2012-03-14 15:53:37",
     "rowsUpper": 0,
     "rowsTotal": 0
    },
    {
     "ndv": 3,
     "upperBound": "2011-12-15 02:34:53",
     "rowsUpper": 1,
     "rowsTotal": 3
    },
    {
     "ndv": 1,
     "upperBound": "2011-09-11 17:20:51",
     "rowsUpper": 1,
     "rowsTotal": 1
    },
    {
     "ndv": 0,
     "upperBound": "2011-06-29 02:37:41",
     "rowsUpper": 0,
     "rowsTotal": 0
    },
    {
     "ndv": 1,
     "upperBound": "2010-04-22 12:31:07",
     "rowsUpper": 1,
     "rowsTotal": 1
    },
    {
     "ndv": 0,
     "upperBound": "2010-10-12 13:21:44",
     "rowsUpper": 0,
     "rowsTotal": 0
    },
    {
     "ndv": 1,
     "upperBound": "2010-11-15 07:23:59",
     "rowsUpper": 1,
     "rowsTotal": 1
    },
    {
     "ndv": 0,
     "upperBound": "2011-04-03 14:12:22",
     "rowsUpper": 0,
     "rowsTotal": 0
    }
   ],
   "gatherEnd": "2024-05-07 20:44:34",
   "gatherStart": "2024-05-07 20:44:34"
  }
 ]
}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
{
 "error": true,
 "message": "Histogram does not exist for test_graph.COMP_MEMBER.compForum.compPerson.joinDate",
 "results": ""
}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_delete_histogram_statistics)Delete histogram statistics
`DELETE :14240/gsql/v1/stats/histogram`
This endpoint deletes histogram data for a graph. This includes histogram data on all vertex attributes in that graph.
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_request_body_3)Request Body
Parameter | Description | Data type  
---|---|---  
`graph` | Name of the graph. | `STRING`  
`vertex` | Name of the vertex type. | `STRING`  
`edge` | Name of the refined edge type. | `STRING`  
`from` | Source vertex type of a refined edge type. | `STRING`  
`to` | Target edge type of a refined edge type. | `STRING`  
`attribute` | Name of the attribute. | `STRING`  
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_examples_6)Examples
  * Histogram Deletion Request
  * Results


Delete Vertex Attribute Histogram
```
$ curl --user tigergraph:tigergraph \
-H 'Content-Type: application/json' \
-X DELETE "http://localhost:14240/gsql/v1/stats/histogram" \
-d '{"graph":"test_graph","vertex":"Comment","attribute":"length"}'
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
{
 "error": false,
 "message": "",
 "results": "Deleting any histogram(s) for test_graph.Comment.length"
}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * Histogram Deletion Request
  * Results


Delete Edge Attribute Histogram
```
$ curl --user tigergraph:tigergraph \
-H 'Content-Type: application/json' \
-X DELETE "http://localhost:14240/gsql/v1/stats/histogram" \
-d '{"graph":"test_graph","edge":"COMP_MEMBER","from":"compForum","to":"compPerson","attribute":"joinDate"}'
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
{
 "error": false,
 "message": "",
 "results": "Deleting any histogram(s) for test_graph.compForum.COMP_MEMBER.compPerson.joinDate"
}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_deleting_multiple_histograms_together)Deleting Multiple Histograms together
It is possible to request multiple histograms be deleted in the same request. The graph name is always required, but it is possible to delete all histograms under a given type as follows:
```
// Delete Histograms for ALL attributes under:
// graph test_graph
-d '{"graph":"test_graph"}'
// Delete Histograms for ALL attributes under:
// graph test_graph
// vertex Comment
-d '{"graph":"test_graph", "vertex":"Comment"}'
// Delete Histograms for ALL attributes under:
// graph test_graph
// edge COMP_MEMBER, from vertex compForum, to vertex compPerson
-d '{"graph":"test_graph", "edge":"COMP_MEMBER", "from":"compForum", "to":"compPerson"}'
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_current_limitations)Current Limitations
If leader switch or some other interruption takes place in GSQL the histogram operation will not be able to resume. Statistics are stored as they are computed along with their start and end timestamps so there is no progress lost. See recommendations for some suggestions on how to handle such situations.
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api#_recommendations)Recommendations
  1. If timeout or some other event interrupts the collection of all the desired statistics, specifying a smaller subset of histograms based on what still has yet to be gathered will reduce the amount of regathering. For example, if executing a histogram computation request for attributes under all graphs, and after 2/4 graphs are fully gathered a timeout occurs, you can issue two requests at the graph level for graphs 3 and 4.
  2. When possible, it is best to schedule histogram computations after schema change jobs and data loading, not before. This is to ensure the statistics best reflect the current state of the database.
  3. When choosing the right bucket value, the first step is to determine the requirements of the use case. Then, choose the fewer number of buckets that provides enough granularity.


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


