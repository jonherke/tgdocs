![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods)[Next](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods)
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
[Resources](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods)
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
  * [Functions](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/)
  * [Vertex Functions](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/4.1/modules/querying/pages/func/vertex-methods.adoc)
### Contents
  * [Dot-syntax methods](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_dot_syntax_methods)
  * [edgeAttribute()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_edgeattribute)
  * [filter()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_filter)
  * [getAttr()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_getattr)
  * [neighborAttribute()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_neighborattribute)
  * [neighbors()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_neighbors)
  * [outdegree()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_outdegree)
  * [setAttr()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_setattr)
  * [Vertex functions](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_vertex_functions)
  * [getvid()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_getvid)
  * [selectVertex()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_selectvertex)
  * [to_vertex()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_to_vertex)
  * [to_vertex_set()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_to_vertex_set)
  * [elementId()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_elementid)


# Vertex Functions
### Contents
  * [Dot-syntax methods](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_dot_syntax_methods)
  * [edgeAttribute()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_edgeattribute)
  * [filter()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_filter)
  * [getAttr()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_getattr)
  * [neighborAttribute()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_neighborattribute)
  * [neighbors()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_neighbors)
  * [outdegree()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_outdegree)
  * [setAttr()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_setattr)
  * [Vertex functions](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_vertex_functions)
  * [getvid()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_getvid)
  * [selectVertex()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_selectvertex)
  * [to_vertex()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_to_vertex)
  * [to_vertex_set()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_to_vertex_set)
  * [elementId()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_elementid)


This page lists the vertex functions that are available in the GSQL query language. The functions are divided into three categories.
  * Dot-syntax methods
    * Object-oriented methods that are invoked on a vertex or vertex alias.
  * Other vertex functions
    * Functions that return a vertex or vertex set, or functions that are closely related to certain attributes of `VERTEX` type variables.


## [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_dot_syntax_methods)Dot-syntax methods
This section lists the built-in methods of vertex aliases. Methods can be accessed by the dot (`.`) operator. When noted, a method may also be available to statement-level vertex variables, not just SELECT-body aliases.
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_edgeattribute)`edgeAttribute()`
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_syntax)Syntax
`v.edgeAttribute( edgeType, attrName )`
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_description)Description
From a vertex, traverse edges of a specified type and return the bag of values for a specified edge attribute.
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_return_type)Return type
`BagAccum<attrType>`
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_parameters)Parameters
Parameter | Description | Data type  
---|---|---  
`edgeType` | The edge type to traverse | `STRING`  
`attrName` | The attribute whose value to retrieve | `STRING`  
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_filter)`filter()`
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_syntax_2)Syntax
```
v.neighbors().filter( condition )
v.neighborAttribute().filter( condition )
v.edgeAttribute().filter( condition )
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_description_2)Description
This function is appended to [`neighbors()`](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_neighbors), [`neighborAttribute()`](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_neighborattribute), or [`edgeAttribute()`](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_edgeattribute) to filter the output set according to a filter condition. Only elements that satisfy the condition will be returned.
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_return_type_2)Return type
`BagAccum`
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_parameters_2)Parameters
Parameter | Description | Data type  
---|---|---  
`condition` | An expression that evaluates to a boolean value | `BOOL`  
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_example)Example
Example query
```
CREATE QUERY filterEx (SET<STRING> pIds, INT yr) FOR GRAPH workNet api("v2") {
 SetAccum<vertex<company>> @recentEmplr, @allEmplr;
 BagAccum<string> @diffCountry, @allCountry;
 Start = {person.*};
 L0 = SELECT v
    FROM Start:v
    WHERE v.id IN pIds
    ACCUM
     # filter using edge attribute
     v.@recentEmplr += v.neighbors("worksFor").filter(worksFor.startYear >= yr),
     v.@allEmplr += v.neighbors("worksFor").filter(true),
    # vertex alias attribute and neighbor type attribute
    v.@diffCountry += v.neighborAttribute("worksFor", "company", "id")
             .filter(v.locationId != company.country),
    v.@allCountry += v.neighborAttribute("worksFor", "company", "id")
    ;
 PRINT yr, L0[L0.@recentEmplr, L0.@allEmplr, L0.@diffCountry, L0.@allCountry]; // api v2
}
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results
```
GSQL > RUN QUERY filterEx(["person1","person2"],2016)
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{
  "L0": [
   {
    "v_id": "person1",
    "attributes": {
     "L0.@diffCountry": ["company2"],
     "L0.@recentEmplr": ["company1"],
     "L0.@allCountry": [ "company1", "company2" ],
     "L0.@allEmplr": [ "company2", "company1" ]
    },
    "v_type": "person"
   },
   {
    "v_id": "person2",
    "attributes": {
     "L0.@diffCountry": ["company1"],
     "L0.@recentEmplr": [],
     "L0.@allCountry": [ "company1", "company2" ],
     "L0.@allEmplr": [ "company2", "company1" ]
    },
    "v_type": "person"
   }
  ],
  "yr": 2016
 }]
}
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_getattr)`getAttr()`
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_syntax_3)Syntax
`v.getAttr(attrName, attrType)`
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_description_3)Description
Returns the value of a vertex attribute on the vertex.
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_return_type_3)Return type
`attrType`
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_parameters_3)Parameters
Parameter | Description | Data type  
---|---|---  
`attrName` | The name of an attribute. This can be a query parameter, constant string, or global string variable. | Base types: `STRING`, `INT`, `UINT,` `DATETIME`, `DOUBLE`, `FLOAT`, `BOOL` Container types follow the format `CONTAINER<TYPE>`, where `CONTAINER` can be `LIST` or `SET` and `TYPE` can be `INT`, `DATETIME`, `DOUBLE`, or `STRING`. Type conversion is supported between numerical values and between `LIST` and `SET` types. For example, a vertex with an attribute of type `LIST<INT>` can be retrieved as `SET<DOUBLE>`.  
`attrType` | The type of the attribute value | `STRING`  
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_neighborattribute)`neighborAttribute()`
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_syntax_4)Syntax
`v.neighborAttribute( edgeType, targetVertexType, attrName )`
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_description_4)Description
From a vertex, traverses edges of a specified type to its neighbors of a specified type, and returns the set of values for a specified attribute.
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_return_type_4)Return type
`BagAccum<attrType>`
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_parameters_4)Parameters
Parameter | Description | Data type  
---|---|---  
`edgeType` | The edge type to traverse | `STRING`  
`targetVertexType` | The target vertex type to visit | `STRING`  
`attrName` | An attribute of the target vertex type | `STRING`  
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_example_2)Example
For the following graph:
![Diagram of a graph of Person vertices connected to each other with friendship edges. Each vertex is connected to one or two other vertices except for 'Dan', who is connected to three.](https://docs.tigergraph.com/gsql-ref/4.1/querying/_images/image%20\(79\).png)
```
# If v is Jenny
v.neighborAttribute("friendship", "person", "state") -> ["ca", "ny", "ca"]
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_neighbors)`neighbors()`
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_syntax_5)Syntax
`v.neighbors([edgeType])`
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_description_5)Description
Returns the out-neighbors or undirected neighbors of the vertex. If edge types are provided, it will only return the neighbors connected by the specified edge types.
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_return_type_5)Return type
`BagAccum<VERTEX>`
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_parameters_5)Parameters
Parameter | Description | Data type  
---|---|---  
`edgeType` | Optional. An edge type or a collections of edge types. | `STRING`, `SET<STRING>`, `SetAccum<STRING>`, `BagAccum<STRING>`, `ListAccum<STRING>`  
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_example_3)Example
For the following graph:
![Diagram of a graph of Person vertices connected to each other with friendship edges. Each vertex is connected to one or two other vertices except for 'Dan', who is connected to three.](https://docs.tigergraph.com/gsql-ref/4.1/querying/_images/image%20\(79\)%20\(1\).png)
```
# If v is Jenny
v.neighbors() -> ["Dan", "Amily", "Tom"]
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_outdegree)`outdegree()`
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_syntax_6)Syntax
`v.outdegree([edgeType])`
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_description_6)Description
Returns the number of outgoing or undirected edges connected to the vertex. If edge types are provided, it will only return the number of edges of the specified types.
[For 3.9.2+] `outdegree()` is also available for vertex input parameters. In this case, outdegree() can be used in a [query-body statement](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-operations#_statement_types).  
---  
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_return_type_6)Return type
`INT`
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_parameters_6)Parameters
Parameter | Description | Data type  
---|---|---  
`edgeType` | Optional. An edge type or a collection of edge types. | `STRING`, `SET<STRING>`, `SetAccum<STRING>`, `BagAccum<STRING>`, `ListAccum<STRING>`  
**Note on outdegree()** : This function reads a metadata value stored with each vertex, to avoid traversing the graph and thus have a fast response. The snapshot transaction semantics means that outdegree() may sometimes read an old value if there are concurrent write transactions. To guarantee an accurate count, traverse the neighboring edges and count them with a SumAccum, or use a function like neighbors() and then use size() on the set.  
---  
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_examples)Examples
Vertex alias:
```
result = SELECT v FROM Members.v
  ACCUM @@num_friends += v.outdegree("is_friend");
wrap![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Query-body level:
```
CREATE QUERY outdegree_statement(VERTEX v1) {
 PRINT v1.outdegree();
}
wrap![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_setattr)`setAttr()`
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_syntax_7)Syntax
`v.setAttr( attrName, newValue )`
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_description_7)Description
Sets the specified attribute of a vertex to a new value.
Type conversion is not allowed for `setAttr()`. The input variable types must match the types in the attribute or the accumulator equivalent.
For example, suppose you run `v.setAttr("emails", @@emails)`. If `v.emails` is type `SET<STRING>`, `@@emails` must be type `SET<STRING>` or `SetAccum<STRING>`.
`SetAccum<STRING>` does not support declaring a set or list inside `setAttr()`.
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_return_type_7)Return type
No return value.
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_parameters_7)Parameters
Parameter | Description | Data type  
---|---|---  
`attrName` | The name of an attribute. This can be a query parameter, constant string, or global string variable. | `STRING`  
`newValue` | The new value for the attribute | The type of the attribute.  
## [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_vertex_functions)Vertex functions
The functions in this section either have return values of vertex or vertex set type or are closely related to vertex attributes.
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_getvid)`getvid()`
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_syntax_8)Syntax
`getvid( v )`
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_description_8)Description
Returns the _internal_ ID number of a vertex.
The internal ID is not the primary ID which the user assigned when creating the vertex. However, there is a 1-to-1 mapping between the external ID (`primary_id`) and internal ID.
The engine can access the internal ID faster than accessing the external ID, so if a query needs unique values for a large number of vertices, but doesn’t care about particular values, `getvid()` can be a useful option. For example, in many community detection algorithms, we start by assigning every vertex a unique community ID. Then, as the algorithm progresses, some vertices will join the community of one of their neighbors, giving up their current community ID and copying the IDs of their neighbors.
We also support `id()` function that works as an alias for `getvid()`  
---  
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_return_type_8)Return type
`UINT`
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_parameters_8)Parameters
Parameter | Description | Data type  
---|---|---  
`v` | A vertex alias. | Vertex alias  
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_example_4)Example
  * Query
  * Result


```
CREATE QUERY getvid_ex () FOR GRAPH socialNet {
MinAccum<int> @cc_id;    //each vertex's tentative component id
 Start = {person.*};
 # Initialize: Label each vertex with its own internal ID
 S = SELECT x FROM Start:x
   POST-ACCUM
     x.@cc_id = getvid(x);
 # Community detection steps omitted
 PRINT Start.@cc_id;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
{
  "error": false,
  "message": "",
  "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
  },
  "results": [{"Start": [
  {
  "v_id": "person7",
  "attributes": {"Start.@cc_id": 0},
  "v_type": "person"
  },
  {
  "v_id": "person5",
  "attributes": {"Start.@cc_id": 4194304},
  "v_type": "person"
  },
  {
  "v_id": "person1",
  "attributes": {"Start.@cc_id": 4194305},
  "v_type": "person"
  },
  {
  "v_id": "person4",
  "attributes": {"Start.@cc_id": 11534336},
  "v_type": "person"
  },
  {
  "v_id": "person2",
  "attributes": {"Start.@cc_id": 13631488},
  "v_type": "person"
  },
  {
  "v_id": "person3",
  "attributes": {"Start.@cc_id": 20971520},
  "v_type": "person"
  },
  {
  "v_id": "person8",
  "attributes": {"Start.@cc_id": 22020096},
  "v_type": "person"
  },
  {
  "v_id": "person6",
  "attributes": {"Start.@cc_id": 24117248},
  "v_type": "person"
  }
]}]
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_selectvertex)`selectVertex()`
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_syntax_9)Syntax
`selectVertex( filepath, vertexIdColumn, vertexTypeColumn, seperator, header)`
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_description_9)Description
Reads a data file that lists particular vertices of the graph and returns the corresponding vertex set.This function can only be used in a vertex set variable declaration statement as a seed set and the vertices in the data file **must already be in the graph**.The data file must be organized as a table with one or more columns.One column must be for vertex ID.Optionally, another column is for vertex type.
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_return_type_9)Return type
`SET<VERTEX>`
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_parameters_9)Parameters
Parameter | Description | Data type  
---|---|---  
`filePath` | The absolute file path of the input file to be read. A relative path is not supported. | `STRING`  
`vertexIdColumn` |  The vertex ID column position. The index for column positions starts at 0. Therefore, to designate the first column as the ID column, set this parameter to `$0`. |  `$ num` If `header` is set to true, `$ "column_name"` is also acceptable.  
`vertexTypeColumn` | The vertex type column position or a specific vertex type. |  `$ num` If `header` is set to true,`$ "column_name"` is also acceptable. Alternatively, a vertex type without double quotes.  
`separator` | The column separator character. | `STRING`  
`header` | Whether this file has a header. | `BOO  
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_example_5)Example
selectVertex.csv
```
ID,type
Dan,person
Jenny,person
Amily,person
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Example query
```
CREATE QUERY selectVertexEx(STRING filename) FOR GRAPH socialNet {
 S1 = {SelectVertex(filename, $"c1", $1, ",", true)};
 S2 = {SelectVertex(filename, $0, person, ",", true)};
 PRINT S1, S2; # Both sets of inputs product the same result
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results
```
RUN QUERY selectVertex("/home/tigergraph/mydata/selectVertex.csv")
{
  "S1": [
   {
    "attributes": {
     "age": 0,
     "gender": "female",
     "name": "Amily",
     "state": "ca"
    },
    "v_id": "Amily",
    "v_type": "person"
   },
   {
    "attributes": {
     "age": 1,
     "gender": "male",
     "name": "Dan",
     "state": "ny"
    },
    "v_id": "Dan",
    "v_type": "person"
   },
   {
    "attributes": {
     "age": 1,
     "gender": "female",
     "name": "Jenny",
     "state": "tx"
    },
    "v_id": "Jenny",
    "v_type": "person"
   }
  ],
  "S2": [
   {
    "attributes": {
     "age": 0,
     "gender": "female",
     "name": "Amily",
     "state": "ca"
    },
    "v_id": "Amily",
    "v_type": "person"
   },
   {
    "attributes": {
     "age": 1,
     "gender": "male",
     "name": "Dan",
     "state": "ny"
    },
    "v_id": "Dan",
    "v_type": "person"
   },
   {
    "attributes": {
     "age": 1,
     "gender": "female",
     "name": "Jenny",
     "state": "tx"
    },
    "v_id": "Jenny",
    "v_type": "person"
   }
  ]
 }
]
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_to_vertex)`to_vertex()`
Running `to_vertex() and to_vertex_set()` requires real-time conversion of an external ID to a GSQL internal ID, which is a relatively slow process. Therefore,
  * If the user can always know the id before running the query, define the query with `VERTEX` or `SET<VERTEX>` parameters instead of `STRING` or `SET<STRING>` parameters, and avoid calling `to_vertex()` or `to_vertex_set()`.
  * Calling `to_vertex_set()` one time is much faster than calling `to_vertex()` multiple times. Use `to_vertex_set()` instead of `to_vertex()` as much as possible.

Since v4.1.0, `to_vertex()` may not be used in ACCUM or POST-ACCUM clauses. ==== Example Example query using to_vertex() in Accum should propmt an error message ```
CREATE QUERY myTest() {
  ListAccum<VERTEX> @@myVertices;
  vSet = SELECT src from Person:src
   Accum
    @@myVertices += to_vertex("m1","Person")  # such use case should not be allowed anymore
  ;
}gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!
```
You should receive a similar error message. ```
Using a vertex function 'to_vertex' or 'to_vertex_set' in ACCUM/POST-ACCUM,
this has been deprecated. Please rewrite your query.text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!
```
  
---  
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_syntax_10)Syntax
`to_vertex( id, vertex_type )`
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_description_10)Description
Returns a vertex from a string ID and vertex type. If a vertex with the provided ID and type does not exist, the function will throw a run-time error.
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_return_type_10)Return type
`VERTEX`
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_parameters_10)Parameters
Parameter | Description | Data type  
---|---|---  
`id` | The ID of a vertex | `STRING`  
`vertex_type` | The type of the vertex | `STRING`  
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_example_6)Example
Example query using to_vertex()
```
CREATE QUERY to_vertex_test (STRING uid, STRING vtype) FOR GRAPH social {
 VERTEX v;
 v = to_vertex (uid, vtype);			# to_vertex assigned to a vertex variable
 PRINT v;								# vertex variable -> only vertex id is printed
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Query result
```
GSQL > RUN QUERY to_vertex_test("Dan", "person")
{
 "error": false,
 "message": "",
 "version": {
  "schema": 1,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"v": "Dan"}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_to_vertex_set)`to_vertex_set()`
Since v4.1.0, `to_vertex_set()` may not be used in ACCUM or POST-ACCUM clauses. ==== Example Example query using to_vertex_set() in Accum should propmt an error message ```
CREATE QUERY myTest2(SET<String> myIds) {
  SetAccum<VERTEX> @@myVertices;
  vSet = SELECT src from Person:src
   Accum
    @@myVertices += to_vertex_set(myIds, "Person")  # such use case should not be allowed anymore
  ;
}gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!
```
You should receive a similar error message. ```
Using a vertex function 'to_vertex' or 'to_vertex_set' in ACCUM/POST-ACCUM,
this has been deprecated. Please rewrite your query.text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!
```
  
---  
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_syntax_11)Syntax
`to_vertex_set( id_set, vertex_type)`
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_description_11)Description
Returns a vertex set from a set or bag of string IDs and a vertex type. If there are invalid IDs in the set, those IDs will be skipped and the response will contain a warning message. If the vertex type does not exist, the function will throw a run-time error.
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_return_type_11)Return type
`SET<VERTEX>`
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_parameters_11)Parameters
Parameter | Description | Data type  
---|---|---  
`id_set` | A set of vertex IDs | `SET<STRING>, BAG<STRING>`  
`vertex_type` | The type of the vertices | `STRING`  
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_example_7)Example
```
CREATE QUERY to_vertex_set_test (SET<STRING> uids, STRING vtype) FOR GRAPH social {
 S2 = to_vertex_set (uids, vtype); # to_vertex_set assigned to a vertex set variable
 PRINT S2;								# vertex set variable-> full details printed
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
GSQL > run query to_vertex_set_test(["Dan", "Amily", "Jeff"], "person")
{
 "error": false,
 "message": "Runtime Warning: 1 ids are invalid person vertex ids.",
 "version": {
  "schema": 1,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"S2": [
  {
   "v_id": "Amily",
   "attributes": {
    "gender": "female",
    "name": "Amily",
    "state": "ca",
    "age": 0
   },
   "v_type": "person"
  },
  {
   "v_id": "Dan",
   "attributes": {
    "gender": "male",
    "name": "Dan",
    "state": "ny",
    "age": 1
   },
   "v_type": "person"
  }
 ]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_elementid)`elementId()`
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_syntax_12)Syntax
`elementId(v)`
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_description_12)Description
Returns an internal string id for a vertex or edge.
This internal ID is not the primary ID which the user assigned when creating the vertex. It is guaranteed to remain the same across the same query run, but not across different runs.
See section on edge functions for more information on `elementId(EDGE)`.  
---  
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_return_type_12)Return type
`STRING`
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_parameters_12)Parameters
Parameter | Description | Data type  
---|---|---  
`v` | A vertex | `VERTEX`  
#### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_example_8)Example
```
CREATE QUERY elementId_example () FOR GRAPH socialNet {
 MinAccum<STRING> @@min_id;    //each vertex's tentative string id
 Start = {person.*};
 # Gather a sample element id for demonstration purposes
 S = SELECT x FROM Start:x
   POST-ACCUM
     @@min_id += elementId(x);
 PRINT @@min_id;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
GSQL > run query elementId_example()
{
 "version": {
  "edition": "enterprise",
  "api": "v2",
  "schema": 1
 },
 "error": false,
 "message": "",
 "results": [
  {
   "@@min_id": "160256"
  }
 ]
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


