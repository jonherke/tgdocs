![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types)[Next](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types)
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
[Resources](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types)
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
  * [GSQL Language](https://docs.tigergraph.com/gsql-ref/4.2/querying/)
  * [Data Types](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/4.2/modules/querying/pages/data-types.adoc)
### Contents
  * [Identifiers](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_identifiers)
  * [Overview](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_overview)
  * [Base types](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_base_types)
  * [Vertex](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_vertex)
  * [Edge](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_edge)
  * [Vertex and Edge Attribute Types](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_vertex_and_edge_attribute_types)
  * [JSONOBJECT](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_jsonobject)
  * [JSONARRAY](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_jsonarray)
  * [Container types](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_container_types)
  * [Tuple](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_tuple)
  * [Virtual Edge](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_virtual_edge)
  * [Definition scope](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_definition_scope)
  * [Access, Manipulation and Traversal](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_access_manipulation_and_traversal)
  * [Limitation](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_limitation)
  * [FILE Object](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_file_object)
  * [Local disk file](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_local_disk_file)
  * [S3 object](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_s3_object)
  * [Query parameter types](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_query_parameter_types)


# Data Types
### Contents
  * [Identifiers](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_identifiers)
  * [Overview](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_overview)
  * [Base types](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_base_types)
  * [Vertex](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_vertex)
  * [Edge](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_edge)
  * [Vertex and Edge Attribute Types](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_vertex_and_edge_attribute_types)
  * [JSONOBJECT](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_jsonobject)
  * [JSONARRAY](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_jsonarray)
  * [Container types](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_container_types)
  * [Tuple](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_tuple)
  * [Virtual Edge](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_virtual_edge)
  * [Definition scope](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_definition_scope)
  * [Access, Manipulation and Traversal](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_access_manipulation_and_traversal)
  * [Limitation](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_limitation)
  * [FILE Object](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_file_object)
  * [Local disk file](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_local_disk_file)
  * [S3 object](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_s3_object)
  * [Query parameter types](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_query_parameter_types)


This section describes the data types that are native to and are supported by the GSQL Query Language. Most of the data objects used in queries come from one of three sources:
  * The query’s input parameters
  * The vertices, edges, and their attributes which are encountered when traversing the graph
  * The variables defined within the query to assist in the computational work of the query


This section covers the following subset of the EBNF language definitions:
EBNF for Data Types
```
lowercase     := [a-z]
uppercase     := [A-Z]
letter       := lowercase | uppercase
digit       := [0-9]
integer      := ["-"]digit+
real        := ["-"]("."digit+) | ["-"](digit+"."digit*)
numeric      := integer | real
stringLiteral   := '"' [~["] | '\\' ('"' | '\\')]* '"'
name := (letter | "_") [letter | digit | "_"]*  // Can be a single "_" or start with "_"
graphName := name
queryName := name
paramName := name
vertexType := name
edgeType := name
accumName := name
vertexSetName := name
attrName := name
varName := name
tupleType := name
fieldName :=name
funcName := name
type := baseType | tupleType | accumType
baseType := INT
     | UINT
     | FLOAT
     | DOUBLE
     | STRING
     | BOOL
     | VERTEX ["<" vertexType ">"]
     | EDGE
     | JSONOBJECT
     | JSONARRAY
     | DATETIME
filePath := paramName | stringLiteral
typedef := TYPEDEF TUPLE "<" tupleFields ">" tupleType
tupleFields := (baseType fieldName) | (fieldName baseType)
      ["," (baseType fieldName) | (fieldName baseType)]*
createVirtualEdge := CREATE DIRECTED|UNDIRECTED VIRTUAL EDGE Virtual_Edge_Type_Name "("
  FROM Vertex_Type_Name ("|" Vertex_Type_Name)* ","
  TO Vertex_Type_Name ("|" Vertex_Type_Name)*
  ["," attribute_name type [DEFAULT default_value]]* ")"
parameterType := baseType
        | [ SET | BAG ] "<" baseType ">"
        | FILE
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The legacy data type `STRING COMPRESS` has been deprecated since TigerGraph Server 3.0. You can no longer create new schema with the type `STRING COMPRESS`. As such, we have removed `STRING COMPRESS` from the documentation. Existing schemas that are using `STRING COMPRESS` can continue to function normally. If you need reference for `STRING COMPRESS`, please refer to GSQL Language Reference version 3.5 or older.  
---  
## [](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_identifiers)Identifiers
An identifier is the name for an instance of a language element. In the GSQL query language, identifiers are used to name elements such as a query, a variable, or a user-defined function. In the EBNF syntax, an identifier is referred as `name`. It can be a sequence of letters, digits, or underscores (`"_"`). Other punctuation characters are not supported. The initial character can only be a letter or an underscore.
name (identifier)
```
name := (letter | "_") [letter | digit | "_"]*
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_overview)Overview
Different types of data can be used in different contexts. The EBNF syntax defines several classes of data types. The most basic is called base type (`baseType`). The other independent type is `FILE`. The remaining types are either compound data types built from the independent data types, or supersets of other types. The table below gives an overview of their definitions and their uses.
EBNF term | Description | Use Case  
---|---|---  
`baseType` | `INT`, `UINT`, `FLOAT`, `DOUBLE`, `STRING`, `BOOL`, `DATETIME,` `VERTEX`, `EDGE`, + `JSONOBJECT`, or `JSONARRAY` | 
  * Base type variable
  * Query return value

  
`containerType` | `SET`, `BAG`, `LIST`, `MAP` | 
  * Local container variable

  
`tupleType` | Sequence of base types | 
  * User-defined tuple

  
`accumType` | Family of specialized data objects which support accumulation operations | 
  * Accumulate and aggregate data, when traversing a set of vertices or edges (Details are in the [Query Lang Spec - Accumulators](https://docs.tigergraph.com/gsql-ref/4.2/querying/accumulators) chapter.)

  
`FILE` | `FILE` object | 
  * Global sequential data object, linked to a text file

  
`parameterType` | `baseType` (except `EDGE` or `JSONOBJECT`), a set or bag of `baseType`, or `FILE` object | 
  * Query parameter

  
`elementType` | `baseType`, or identifier | 
  * Element for most types of container accumulators: `SetAccum`, `BagAccum`, `GroupByAccum`, key of a `MapAccum` element

  
`type` | `baseType`, identifier, or `accumType` | 
  * Element of a `ListAccum`, value of a `MapAccum` element
  * Local variable

  
## [](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_base_types)Base types
The query language supports the following _base types_ , which can be declared and assigned anywhere within their scope. Any of these base types may be used when defining a global variable, a local variable, a query return value, a parameter, part of a tuple, or an element of a container accumulator. Accumulators are described in detail in a later section.
EBNF
```
baseType := INT
     | UINT
     | FLOAT
     | DOUBLE
     | STRING
     | BOOL
     | VERTEX ["<" vertexType ">"]
     | EDGE
     | JSONOBJECT
     | JSONARRAY
     | DATETIME
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The default value of each base type is shown in the table below. The default value is the initial value of a base type variable (see Section "Variable Types" for more details), or the default return value for some functions.
The first seven types (`INT`, `UINT`, `FLOAT`, `DOUBLE`, `BOOL`, `STRING`, and `DATETIME`) are the same ones mentioned in the "[Attribute Data Types](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/attribute-data-types#_primitive_types)" section of [GSQL Language Reference, Part 1](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/attribute-data-types).
Type | Default value | Literal  
---|---|---  
`INT` | `0` | A signed integer: `-3`  
`UINT` | `0` | An unsigned integer: `5`  
`FLOAT` | `0` | A decimal precise up to about 7 digits: `3.14159`  
`DOUBLE` | `0` | A decimal precise up to about 16 digits.  
`BOOL` | `false` | `TRUE` or `FALSE`  
`STRING` | `""` | Characters enclosed by double quotes: `"Hello"`  
`DATETIME` | `1970-01-01 00:00:00` | No literal. Can be converted from a correctly formatted string with [`to_datetime()`](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/type-conversion-functions#_to_datetime).  
`VERTEX` | `"Unknown"` | No literal.  
`EDGE` | No edge: `{}` | No literal.  
`JSONOBJECT` | An empty object: `{}` | No literal. Can be converted from a correctly formatted string with [`parse_json_object()`](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/type-conversion-functions#_parse_json_object).  
`JSONARRAY` | An empty array: `[]` | No literal. Can be converted from a correctly formatted string with [`parse_json_array()`](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/type-conversion-functions#_parse_json_array).  
The `FLOAT` and `DOUBLE` data types have the same precision limits as in C++. See [Common Errors and Problems](https://docs.tigergraph.com/gsql-ref/4.2/appendix/common-errors-and-problems) for more details.
`FLOAT` and `DOUBLE` input values must be in fixed point `d.dddd` _**_ format, where `d` is a digit. Output values will be printed in either fixed point for exponential notation, whichever is more compact. The GSQL Loader can read FLOAT and DOUBLE values with exponential notation (e.g., 1.25 E-7).  
---  
### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_vertex)Vertex
`VERTEX` is considered a base type in the GSQL query language. Both query parameters and variables in a query body can be of type `VERTEX`.
#### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_vertex_types)Vertex types
A graph schema defines specific vertex types. Each vertex type has its own set of attributes. The parameter or variable type can be restricted by giving the vertex type in angle brackets `<>` after the keyword `VERTEX`. A vertex variable declared without a specifier is called a _generic_ vertex variable.
Generic and typed vertex variables
```
VERTEX anyVertex;
VERTEX<person> owner;
```

All vertices have a built-in attribute `type`. The built-in attribute is of type string. You can access it with the dot (`.`) operator.
For example, if you declare a vertex variable `VERTEX<person> personVertex`, then `personVertex.type` returns `"person"`.
When you run a query with a vertex type, the syntax is different for typed vertex parameters and generic vertex parameters. See the [RUN QUERY parameter list](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-operations#_parameter_list) for details.
### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_edge)Edge
`EDGE` is considered a base type in the GSQL query language. Both query parameters and variables in a query body can be of type `EDGE`.
#### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_edge_types)Edge types
A graph schema defines specific edge types. Each edge type has its own set of attributes. The parameter or variable type can be restricted by giving the edge type in angle brackets `<>` after the keyword `EDGE`. An edge variable declared without a specifier is called a _generic_ edge variable.
Generic and typed edge variables
```
EDGE anyEdge;
EDGE<friendship> friendEdge;
```

All edges have a built-in attribute `type`. The built-in attribute is of type string. You can access it with the dot (`.`) operator.
For example, if you define an edge variable `EDGE<friendship> friendEdge`, then `friendEdge.type` returns `"Friendship"`.
### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_vertex_and_edge_attribute_types)Vertex and Edge Attribute Types
The following table maps vertex or edge attribute types in the Data Definition Language (DDL) to GSQL query language types. If an attribute of a vertex or edge is referenced in a GSQL query, they will be automatically converted to their corresponding data type in the GSQL query language.
DDL | GSQL Query  
---|---  
`INT` | `INT`  
`UINT` | `UINT`  
`FLOAT` | `FLOAT`  
`DOUBLE` | `DOUBLE`  
`BOOL` | `BOOL`  
`STRING` | `STRING`  
`SET< type >` | `SetAccum< type >`  
`LIST< type >` | `ListAccum< type >`  
`MAP <key_type, value_type>` | `MapAccum <key_type, value_type>`  
`DATETIME` | `DATETIME`  
### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_jsonobject)`JSONOBJECT`
A `JSONOBJECT` instance’s external representation (as input and output) is a string, starting and ending with curly braces (`{}`) which enclose an unordered list of key-value pairs. `JSONOBJECT` is immutable. No operator is allowed to alter its value.
#### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_assign_a_jsonobject_value_to_a_base_type_variable)Assign a `JSONOBJECT` value to a base type variable
There is no `JSONOBJECT` literal in the GSQL query language. Therefore, to assign value to a `JSONOBJECT` base type variable in GSQL, you need to use the `parse_json_object()` function to convert a string representation of s JSON object to a `JSONOBJECT` value.
For example, the following line declares a variable `han` with a `JSONOBJECT` value:
```
JSONOBJECT han = parse_json_object("{\"f_name\": \"Han\", \"l_name\": \"Solo\"}");
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_jsonarray)`JSONARRAY`
A `JSONARRAY` is represented as a string, starting and ending with square brackets (`[]`)which enclose an ordered list of _values_. `JSONARRAY` is immutable. No operator is allowed to alter its value.
#### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_assign_a_jsonarray_value_to_a_base_type_variable)Assign a `JSONARRAY` value to a base type variable
There is no `JSONARRAY` literal in the GSQL query language. Therefore, to assign value to a `JSONARRAY` base type variable in GSQL, you need to use the `parse_json_array()` function to convert a string representation of s JSON object to a `JSONARRAY` value.
For example, the following line declares a variable `fruits` with a `JSONARRAY` value:
```
JSONARRAY fruits = parse_json_array("[\"apple\", \"banana\", \"citrus\"]");
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_container_types)Container types
Container types include the following data types:
  * `SET`
  * `BAG`
  * `LIST`
  * `MAP`


Table 1. Container types Type | Literal | Example | Default value  
---|---|---|---  
`SET` | Elements enclosed by parentheses, separated by commas. | `(1, 2, 3)` | Empty set.  
`BAG` | Elements enclosed by parentheses, separated by commas. | `(1, 1, 2)` | Empty bag.  
`LIST` | Elements enclosed by square brackets, separated by commas. | `[1, 2, 3]` | Empty list.  
`MAP` | No literal. | N/A | Empty map.  
To see how container type variables are declared in a GSQL query, see [Local container variables](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_local_container_variable).
## [](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_tuple)Tuple
A tuple is a user-defined data structure consisting of a fixed sequence of base type variables. Tuple types can be created and named using a `TYPEDEF` statement. Tuples must be defined first, before any other statements in a query.
EBNF for tuples
```
typedef := TYPEDEF TUPLE "<" tupleFields ">" tupleType
tupleFields := (baseType fieldName) | (fieldName baseType)
      ["," (baseType fieldName) | (fieldName baseType)]*
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

A tuple can also be defined in a graph schema and then can be used as a vertex or edge attribute type. A tuple type that has been defined in the graph schema does not need to be re-defined in a query.
The vertex type `person` contains two complex attributes:
  * `secretInfo` of type `SECRET_INFO`, which a user-defined tuple
  * `portfolio` of type `MAP<STRING, DOUBLE>`


`Investment_Net` Schema
```
TYPEDEF TUPLE <age UINT (4), mothers_name STRING(20) > SECRET_INFO
CREATE VERTEX Person(PRIMARY_ID person_id STRING, portfolio MAP<STRING, DOUBLE>, secret_info SECRET_INFO)
CREATE VERTEX Stock_Order(PRIMARY_ID order_id STRING, ticker STRING, order_size UINT, price FLOAT)
CREATE UNDIRECTED EDGE make_order(FROM Person, TO Stock_Order, order_time DATETIME)
CREATE GRAPH Investment_Net (*)
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The query below reads both the `SECRET_INFO` tuple and the portfolio MAP. The tuple type does not need to be redefined in the query. To read and save the map, we define a [`MapAccum`](https://docs.tigergraph.com/gsql-ref/4.2/querying/accumulators#_mapaccum) with the same types for key and value as the `portfolio` attribute. In addition, the query creates a new tuple type, `ORDER_RECORD`.
  * Query
  * Result


```
CREATE QUERY tuple_ex(VERTEX<Person> p) FOR GRAPH Investment_Net{
  TYPEDEF TUPLE <STRING ticker, FLOAT price, DATETIME order_time> Order_Record; **(1)**
  SetAccum<Secret_Info> @@info; **(2)**
  ListAccum<Order_Record> @@order_records;
  MapAccum<STRING, DOUBLE> @@portf;
  INIT = {p};
  // Get person p's secret_info and portfolio
  X = SELECT v FROM INIT:v
    ACCUM @@portf += v.portfolio, @@info += v.secret_info;
  // Search person p's orders to record ticker, price, and order time.
  // Note that the tuple gathers info from both edges and vertices.
  orders = SELECT t
    FROM INIT:s -(Make_Order:e)-Stock_Order:t
    ACCUM @@order_records += Order_Record(t.ticker, t.price, e.order_time);
  PRINT @@portf, @@info;
  PRINT @@order_records;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | This statement defines a new tuple `Order_Record` at the top of the query.  
---|---  
**2** | `Secret_Info` has already been defined in [`Investment_Net` Schema](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#Investment_Net-schema).  
```
GSQL > RUN QUERY tuple_ex("person1")
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [
  {
   "@@info": [{
    "mothers_name": "JAMES",
    "age": 25
   }],
   "@@portf": {
    "AAPL": 3142.24,
    "MS": 5000,
    "G": 6112.23
   }
  },
  {"@@order_records": [
   {
    "ticker": "B",
    "price": 202.32001,
    "order_time": "2017-03-03 18:42:30"
   },
   {
    "ticker": "AAPL",
    "price": 34.42,
    "order_time": "2017-03-03 18:42:28"
   },
   {
    "ticker": "A",
    "price": 50.55,
    "order_time": "2017-03-03 18:42:29"
   }
  ]}
 ]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_virtual_edge)Virtual Edge
In the graph schema, while regular edges facilitate CRUD operations, traversing multiple steps between vertices can be cumbersome.
To streamline this process, we are introducing the Virtual Edge feature, which are in memory edges that can be created during query runtime, simplifying traversal and enabling predicate application across non-adjacent vertices.
EBNF for creating virtual edge
```
createVirtualEdge := CREATE DIRECTED|UNDIRECTED VIRTUAL EDGE Virtual_Edge_Type_Name "("
  FROM Vertex_Type_Name ("|" Vertex_Type_Name)* ","
  TO Vertex_Type_Name ("|" Vertex_Type_Name)*
  ["," attribute_name type [DEFAULT default_value]]* ")"
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Example
```
CREATE OR REPLACE DISTRIBUTED QUERY exampleQuery(){
 CREATE DIRECTED VIRTUAL EDGE virtualE1(from v1, to v2, attr1 int);
 CREATE DIRECTED VIRTUAL EDGE virtualE2(from v1|v3|v5, to v2|v4|v6, attr1 int, attr2 float);
 ...
}
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_definition_scope)Definition scope
Virtual edges can only be defined in the global scope of a query, meaning they must be declared at the top level of the query body. They cannot be nested within local statement such as IF, ELSE, FOREACH, select-block etc. The definition of a virtual edge is visible and valid throughout the entire query.
### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_access_manipulation_and_traversal)Access, Manipulation and Traversal
In general, virtual edge is very similar to regular edge, meaning we can update, upsert, access, delete virtual edge just like regular edge.
  * Query
  * Result


```
CREATE OR REPLACE DISTRIBUTED QUERY virtualEdgeExample(){
 // First we create a virtual edge type
 CREATE DIRECTED VIRTUAL EDGE VirtualE1(FROM v1, TO v2, creationDate DATETIME);
 P = SELECT s FROM v1:s -(e1>:e)- :t
     ACCUM
	   // here we insert virtual edges
      INSERT INTO VirtualE1 VALUES(s, t, to_datetime("2024-01-01"));
 SumAccum<INT> @@cntVE1;
 MinAccum<DATETIME> @@minDatetime;
 P = SELECT s FROM v1:s -(VirtualE1>:e)- :t
     ACCUM
		// here we traverse virtual edges just like regular edge
      @@cntVE1 += 1,
      @@minDatetime += e.creationDate;
 PRINT @@cntVE1;
 PRINT @@minDatetime;
 P = SELECT s FROM v1:s -(VirtualE1>:e)- :t
     ACCUM
		// here we delete the virtual edges
      DELETE(e);
 SumAccum<INT> @@cntVE2;
 P = SELECT s FROM v1:s -(VirtualE1>)- :t
     ACCUM
		// here we sum up the number of virtual edges, it should be 0
      @@cntVE2 += 1;
 PRINT @@cntVE2;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This query creates a virtual edge type VirtualE1, insert edge, access, and delete just like regular edge
```
GSQL > RUN QUERY virtualEdgeExample()
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
   "@@cntVE1": 3
  },
  {
   "@@minDatetime": "2024-01-01 00:00:00"
  },
  {
   "@@cntVE2": 0
  }
 ]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_limitation)Limitation
  * It is only supported to create virtual edge type in the global scope of query, creating virtual edge type inside statements are not allowed, for example below is an incorrect usage


```
CREATE OR REPLACE DISTRIBUTED QUERY exampleQuery(Bool condition){
 IF Condition THEN
	// we are creating virtual edge inside if statement, which is not allowed
	CREATE DIRECTED VIRTUAL EDGE VirtualE1(FROM Person, TO Post|Comment, creationDate DATETIME);
	...
 END;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * Only GPR v2 syntax support virtual edge, while UDF does not.
  * Virtual Edge does not support multi edge, i.e. no DISCRIMINATOR attribute can be added in virtual edge
  * Virtual Edge types cannot be used together with other virtual edge or regular edges in edge traversal, for example below is an incorrect usage


```
R = select s from Person:s -((VirtualE1>|VirtualE2>):e)- :t
  accum
   case e.type
    when "VirtualE1" then @@results1 += Results01(e._a, e._b, e._c, e._d)
    when "VirtualE2" then @@results2 += Results02(e._a, e._b)
   end
  ;
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * Does not support virtual edge with getAttr(), setAttr() functions
  * Cannot aggregate virtual edge into edge containers, for example below is an incorrect usage


```
ListAccum<edge> @@res;
R = SELECT p1 FROM person:p1 -(FOF:e)- person:p2
   ACCUM
    @@res += e;
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * Does not support user defined tuple as attribute type
  * Does not support update and access attributes of same Virtual Edge type in the same ACCUM clause.
    * Correct example


```
// we are reading the attribute of virtual edge in ACCUM clause, and
// insert(update) virtual edge in POST-ACCUM caluse, which is allowed
W = select s from Src:s - (VE:e) - Tgt:t
    ACCUM @@cnt +=e.attr1;
	 POST-ACCUM INSERT INTO VE values(s, t);
```

  * Incorrect example


```
// we are reading the attribute of virtual edge and also updating it in
// the same ACCUM clause, which is not allowed
W = select s from Src:s - (VE:e) - Tgt:t
    ACCUM @@cnt +=e.attr1,
 e.attr1 += 1;
```

## [](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_file_object)`FILE` Object
A `FILE` object is a sequential data storage object, associated with a text file on the local machine or with an S3 bucket.
When referring to a `FILE` object, we always capitalize the word `FILE` to distinguish it from ordinary files.  
---  
### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_local_disk_file)Local disk file
When a `FILE` object is declared, associated with a particular text file, any existing content in the text file will be erased. During the execution of the query, content written to the `FILE` will be appended to the `FILE`. When the query where the `FILE` was declared finishes running, the `FILE` contents are saved to the text file.
### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_s3_object)S3 object
#### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_define_s3_file_object)Define s3 file object
The path should start with `s3://`, followed by the bucket name and the S3 path, e.g., `s3://bucket-name/queryoutput/output.csv`. During the execution of the query, content will be uploaded to the S3 bucket. Note that the S3 object cannot be modified or appended, if an S3 object with the same path already exists, it will be overwritten.
#### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_set_s3_connection_credentials)Set S3 connection credentials
The S3 credentials can be set as GSQL session parameters, so they persist for a user for a full session.
```
set s3_aws_access_key_id = <AWS_KEY_ID>;
set s3_aws_secret_access_key = <AWS_ACCESS_KEY>;
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

These session parameters should be set within the GSQL Editor to enable read/write access to the specified S3 bucket for query results. Replace `<AWS_KEY_ID>` and `<AWS_ACCESS_KEY>` with your actual AWS credentials.
#### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_output)Output
Since S3 is a shared storage system, multiple nodes in a cluster can upload to the same S3 bucket. To handle potential conflicts and ensure unique output files, the S3 path can include a suffix based on the instance name, such as `_GPE_{PartitionId}_{ReplicaId}`. For distributed queries, additional suffixes will be used to differentiate between the manager and worker roles on the same GPE. Specifically, suffixes like `_coordinator` and `_worker` will be added, where `_coordinator` refers to the worker manager and `_worker` refers to the worker node.
#### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_error_code)Error code
For S3 bucket connection errors, refer to error code `GSQL-5301`.
A `FILE` object can be passed as a parameter to another query. When a query receives a `FILE` object as a parameter, for a file on the local machine, it can append data to that `FILE`, as can every other query which receives this FILE object as a parameter. However, an S3 bucket `FILE` object cannot be appended to. When you write to an S3 path, any existing object will be overwritten.  
---  
## [](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_query_parameter_types)Query parameter types
A query can have one or more input parameters having any of the following types:
  * [Base types](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_base_types) (except `EDGE` , `JSONARRAY`, or `JSONOBJECT`).
  * [FILE object](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_file_object)
  * A `SET` or `BAG` of base type elements (except `EDGE` , `JSONARRAY`, or `JSONOBJECT`).
  * As of 4.2, `LIST` and `MAP` of base type elements are also supported. The key and value of a `MAP` may be [primitiveType](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/attribute-data-types#_primitive_types) (numerical, string, or Boolean).


Within the query, `SET`, `BAG`, `LIST`, and `MAP` parameters are converted to [`SetAccum`](https://docs.tigergraph.com/gsql-ref/4.2/querying/accumulators#<em>setaccum), [`BagAccum`](https://docs.tigergraph.com/gsql-ref/4.2/querying/accumulators#_bagaccum), [`ListAccum`](https://docs.tigergraph.com/gsql-ref/4.2/querying/accumulators#_listaccum), and [`MapAccum`](https://docs.tigergraph.com/gsql-ref/4.2/querying/accumulators#_mapaccum</em>), respectively.
A query parameter is immutable. It cannot be assigned a new value within the query. The `FILE` object is a special case. It is passed by reference, meaning that the receiving query gets a link to the original `FILE` object. The receiving query can write to the `FILE` object.  
---  
EBNF
```
parameterType := INT
        | UINT
        | FLOAT
        | DOUBLE
        | STRING
        | BOOL
        | VERTEX ["<" vertexType ">"]
        | DATETIME
        | [ SET | BAG | LIST ] "<" baseType ">"
        | MAP "<" primitiveType "," primitiveType ">"
        | FILE
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Examples of base type and collection type parameter declarations
```
(STRING name, BAG<INT> ids, SET<VERTEX<person>> friends, FILE f1)
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

For how to declare the parameters in a query, see [CREATE QUERY: parameterList](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-operations#_parameters).
For how to run a query, see
  * [Parameters when running a query in the GSQL CLI](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-operations#_query_parameters).
  * [Parameters when running a query as a REST endpoint](https://docs.tigergraph.com/tigergraph-server/4.2/API/gsql-endpoints#_format_for_parameters_of_query_being_run).


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


