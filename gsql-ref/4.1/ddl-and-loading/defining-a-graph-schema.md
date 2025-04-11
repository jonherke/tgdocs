![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema)[Next](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema)
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
[Resources](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema)
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
  * [Schema Definition](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/)
  * [Define a Graph Schema](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/4.1/modules/ddl-and-loading/pages/defining-a-graph-schema.adoc)
### Contents
  * [CREATE VERTEX](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_create_vertex)
  * [Primary ID/key options](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_primary_idkey_options)
  * [PRIMARY_ID](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_primary_id)
  * [WITH primary_id_as_attribute](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_with_primary_id_as_attribute)
  * [PRIMARY KEY](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_primary_key)
  * [Composite Key using PRIMARY KEY](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_composite_key_using_primary_key)
  * [Vertex Attribute List](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_vertex_attribute_list)
  * [Vertex Options](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_vertex_options)
  * [CREATE EDGE](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_create_edge)
  * [DISCRIMINATOR](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_discriminator)
  * [Create an edge from or to any vertex type](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_create_an_edge_from_or_to_any_vertex_type)
  * [WITH REVERSE_EDGE](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_with_reverse_edge)
  * [TYPEDEF](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_typedef)
  * [ALTER INDEX](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_alter_index)
  * [CREATE GRAPH](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_create_graph)
  * [Required privilege](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_required_privilege)
  * [Examples](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_examples)
  * [CREATE GRAPH …​ AS (Beta)](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_create_graph_as_beta)
  * [USE GRAPH](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_use_graph)
  * [DROP GRAPH](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_drop_graph)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_syntax)
  * [Required privilege](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_required_privilege_2)
  * [DROP ALL](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_drop_all)
  * [Required privilege](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_required_privilege_3)
  * [SHOW - View Parts of the Catalog](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_show_view_parts_of_the_catalog)


# Defining a Graph Schema
### Contents
  * [CREATE VERTEX](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_create_vertex)
  * [Primary ID/key options](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_primary_idkey_options)
  * [PRIMARY_ID](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_primary_id)
  * [WITH primary_id_as_attribute](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_with_primary_id_as_attribute)
  * [PRIMARY KEY](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_primary_key)
  * [Composite Key using PRIMARY KEY](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_composite_key_using_primary_key)
  * [Vertex Attribute List](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_vertex_attribute_list)
  * [Vertex Options](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_vertex_options)
  * [CREATE EDGE](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_create_edge)
  * [DISCRIMINATOR](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_discriminator)
  * [Create an edge from or to any vertex type](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_create_an_edge_from_or_to_any_vertex_type)
  * [WITH REVERSE_EDGE](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_with_reverse_edge)
  * [TYPEDEF](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_typedef)
  * [ALTER INDEX](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_alter_index)
  * [CREATE GRAPH](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_create_graph)
  * [Required privilege](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_required_privilege)
  * [Examples](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_examples)
  * [CREATE GRAPH …​ AS (Beta)](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_create_graph_as_beta)
  * [USE GRAPH](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_use_graph)
  * [DROP GRAPH](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_drop_graph)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_syntax)
  * [Required privilege](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_required_privilege_2)
  * [DROP ALL](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_drop_all)
  * [Required privilege](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_required_privilege_3)
  * [SHOW - View Parts of the Catalog](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_show_view_parts_of_the_catalog)


Before data can be loaded into the graph store, the user must define a _graph schema._
A graph schema is a "dictionary" that defines the types of entities, _vertices_ and _edges_ , in the graph and how those types of entities are related to one another. Each vertex or edge type has a name and a set of attributes (properties) associated with it. For example, a Book vertex could have title, author, publication year, genre, and language attributes.
In the figure below, circles represent vertex types, and lines represent edge types. The labeling text shows the name of each type. This example has four types of vertices: _User, Occupation, Book,_ and _Genre_. Also, the example has 3 types of edges: _user_occupation, user_book_rating,_ and _book_genre_. Note that this diagram does not say anything about how many users or books are in the graph database. It also does not indicate the cardinality of the relationship. For example, it does not specify whether a User may connect to multiple occupations.
![A schema for a User-Book-Rating graph. The vertex User is connected to Occupation with the user_occupation edge and to Book with the user_book_rating edge. Book is connected to Genre with the book_genre edge.](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/_images/user-book-rating-schema.png)
Figure 1. A schema for a User-Book-Rating graph
An edge connects two vertices: a _source vertex_ and a _target vertex_ . An edge type can be either _directed_ or _undirected_. A directed edge has a clear semantic direction, from the source vertex to the target vertex. For example, if there is an edge type that represents a plane flight segment, each segment needs to distinguish which airport is the origin (source vertex) and which airport is the destination (target vertex). In the example schema below, all edges are undirected.
A useful test to decide whether an edge should be directed or undirected is the following: "An edge type is directed if knowing there is a relationship from A to B does not tell me whether there is a relationship from B to A." Having nonstop service from Chicago to Shanghai does not automatically imply there is nonstop service from Shanghai to Chicago.
An expanded schema is shown below, containing all the original vertex and edge types plus three additional edge types: _friend_of, sequel_of, and user_book_read_. Note that _friend_of_ joins a User to a User. The friendship is assumed to be bidirectional, so the edge type is undirected. _Sequel_of_ joins a Book to a Book but it is directed, as evidenced by the arrowhead. _The Two Towers_ is the sequel of _The Fellowship of the Ring_ , but the reverse is not true. User_book_read is added to illustrate that there may be more than one edge type between a pair of vertex types.
![User-Book-Rating schema with addtional edges.](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/_images/user-book-rating-schema-expanded.png)
Figure 2. Expanded-User-Book-Rating schema with additional edges
The TigerGraph system user designs a graph schema to fit the source data and the user’s needs and interests. The TigerGraph system user should consider what type of relationships are of interest and what type of analysis is needed. The TigerGraph system lets the user modify an existing schema, so the user is not locked into the initial design decision.
In the first schema diagram above, there are seven entities: four vertex types and three edge types. You may wonder why it was decided to make Occupation a separate vertex type instead of an attribute of User. Likewise, why is Genre a vertex type instead of an attribute of Book? These are examples of design choices. Occupation and Genre were separated out as vertex types because in graph analysis, if an attribute will be used as a query variable, it is often easier to work with as a vertex type.
Once the graph designer has chosen a graph schema, the schema is ready to be formalized into a series of GSQL statements.
Graph Creation and Modification Privileges You need the `WRITE_SCHEMA` privilege in the scope you are operating on to run commands that alter the graph schema. To learn more about permission and privileges, see [Access Control Model in TigerGraph](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model).  
---  
## [](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_create_vertex)`CREATE VERTEX`
**Required privilege** : `WRITE_SCHEMA`
The `CREATE VERTEX` statement defines a new global vertex type with a name, primary key, and an attribute list.
Data loaded to a global vertex type in one graph will be shared across all graphs that use that vertex type. See [Global vs. local schema changes](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/modifying-a-graph-schema#_global_vs_local_schema_changes) for instructions on creating local vertices. At a high level, the `CREATE VERTEX` syntax is as follows:
```
CREATE VERTEX vertex_type_name "("id_and_attribute_list")" [vertex_options]
```

### [](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_primary_idkey_options)Primary ID/key options
There are three variations of `id_and_attribute_list`, based on whether the key is to be treated as an attribute and whether the key is a composite key:
  1. [Using `PRIMARY_ID`](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_primary_id) to define the ID. By default, the ID is not considered an attribute, so it cannot be read and used in expressions with the same flexible as regular attributes. The advantage of this mode is that vertices are stored more compactly.
  2. [Using `PRIMARY KEY`](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_primary_key) to designate one attribute as the primary key.
  3. [Using `PRIMARY KEY` to create a composite key](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_composite_key_using_primary_key).


If you have a single attribute which serves as your primary key, use the `PRIMARY_ID` syntax, along with the WITH `primary_id_as_attribute="true"` vertex option. This gives you the flexibility of option 2 with the GraphStudio compatibility of option 1.  
---  
Regardless of which option is selected, GSQL automatically creates a hash index of the key for fast O(1) searches.
The syntax for the three options are summarized below.
CREATE VERTEX Syntax
```
id_and_attribute_list :=
 PRIMARY_ID id_name id_type ["," attribute_list] **(1)**
 | id_name id_type PRIMARY KEY ["," attribute_list] **(2)**
 | attribute list "," PRIMARY KEY "("key_list")" **(3)**
attribute_list :=
 attribute_name type [DEFAULT default_value]
 ["," attribute_name type [DEFAULT default_value] ]*
enbf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

`id_type` may be `STRING`, `INT`, `UINT`, or `DATETIME`. Once a vertex is inserted, its ID value cannot be modified. Every vertex must have a unique ID value, of course.
An empty string is not a valid value for a vertex primary ID. Beginning with v3.9, GSQL will reject attempts to insert or load a vertex whose ID is an empty string.   
---  
**Maximum Size**
A vertex primary key has a length limit of 16384 bytes. The size of a vertex, including all of its attributes, cannot exceed 10 megabytes.
The following sections go into detail for each of the primary id/key options, attribute lists, and the vertex options.
### [](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_primary_id)PRIMARY_ID
This is GSQL’s original syntax and semantics. Its data type may be `STRING`, `INT`, `UINT`, or `DATETIME`. Its syntax for the `id_and_attribute_list` term is as follows:
```
PRIMARY_ID id_name id_type "," attribute_list
```

Example:
```
CREATE VERTEX Movie (id UINT PRIMARY KEY, name STRING, year UINT)
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

By default, a vertex type which is defined with `PRIMARY_ID` cannot treat the ID as a regular attribute. For example, if the ID’s field name is `serial_num`, neither of the following syntaxes are valid:
```
 v.serial_num // error: not supported
 v.id // error: id is not a built-in function or field name
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

If you want to retreive a vertex having a specific ID, you can use the `to_vertex(id, type)` function.
See the next section to see how to override the default behavior and treat the primary ID as attribute.
### [](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_with_primary_id_as_attribute)`WITH primary_id_as_attribute`
If the `WITH …​ primary_id_as_attribute="true"` option is declared, then the ID can be treated as a readable attribute. Internally, the ID is being stored a second time, once as an ID and once as a write-once attribute. This is exactly the same way that PRIMARY KEY allows the ID to be treated as a vertex. Using this option eliminates the storage advantage of `PRIMARY_ID` in exchange for greater flexible in query operations.
Example:
```
CREATE VERTEX Movie (PRIMARY_ID id UINT, name STRING, year UINT) WITH primary_id_as_attribute="true"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_primary_key)PRIMARY KEY
Instead of the legacy `PRIMARY_ID` syntax, GSQL offers another option for specifying the primary key. Append the keyword phrase `PRIMARY KEY` to any one of the attributes in the attribute list to make the attribute the primary key. It is conventional for the primary key to be the first attribute. The primary key data type must be `STRING`, `INT`, or `UINT`.
Its syntax for the `id_and_attribute_list` term is as follows:
```
[attribute_list ", "] id_attribute_name key_type PRIMARY KEY ["," attribute_list]
```

Example:
```
CREATE VERTEX Movie (id UINT PRIMARY KEY, name STRING, year UINT)
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

PRIMARY KEY is not supported in GraphStudio. If you define a vertex type using the PRIMARY KEY syntax, you will not be able to use that vertex type or the global schema in GraphStudio.  
---  
### [](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_composite_key_using_primary_key)Composite Key using `PRIMARY KEY`
GSQL supports composite keys - grouping multiple attributes to create a primary key for a specific vertex. To specify a composite key, first definite all the vertex type’s attributes. Follow that with the keyword PRIMARY KEY and then the parenthesized list of attributes that form the composite key.
Its syntax for the `id_and_attribute_list` term is as follows:
```
attribute_list "," PRIMARY KEY "(" attribute_name ("," attribute_name)* ")"
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Example:
```
CREATE VERTEX Movie (id UINT, title STRING, year UINT, PRIMARY KEY (title,year,id))
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Composite keys are not supported in GraphStudio. If you define a vertex type with composite keys, you will not be able to use that vertex type or the global schema in GraphStudio.  
---  
### [](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_vertex_attribute_list)Vertex Attribute List
The attribute list is a list of one or more _id definitions_ and _attribute descriptions_ separated by commas:
```
attribute_list :=
 attribute_name type [DEFAULT default_value]
 ["," attribute_name type [DEFAULT default_value] ]*
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The available attribute types, including user-defined types, are listed in the section [Attribute Data Types](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/attribute-data-types).
  1. Every attribute data type has a built-in default value (e.g., the default value for INT type is 0). The `DEFAULT default_value` option overrides the built-in value.
  2. There is no maximum number of attributes, but there is a maximum storage size for a [vertex](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_create_vertex).


Example:
  * Create vertex types for the graph schema of Figure 1.


Vertex definitions for User-Book-Rating graph
```
CREATE VERTEX User (PRIMARY_ID user_id UINT, name STRING, age UINT, gender STRING, postalCode STRING)
CREATE VERTEX Occupation (PRIMARY_ID occ_id UINT, occ_name STRING)
  WITH STATS="outdegree_by_edgetype"
CREATE VERTEX Book (PRIMARY_ID bookcode UINT, title STRING, pub_year UINT)
  WITH STATS="none"
CREATE VERTEX Genre (PRIMARY_ID genre_id STRING, genre_name STRING)
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Unlike the tables in a relational database, vertex types do not need to have a foreign key attribute for one vertex type to have a relationship to another vertex type. Such relationships are handled by edge types.
### [](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_vertex_options)Vertex Options
```
vertex_option :=
WITH [STATS="none"|"outdegree_by_edgetype"]
[primary_id_as_attribute="false"]
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The [primary_id_as_attribute](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_primary_id_and_with_primary_id_as_attribute) option was described with PRIMARY ID.
#### [](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_with_stats)`WITH STATS`
By default, when the loader stores a vertex and its attributes in the graph store, it also stores some statistics about the vertex’s outdegree — how many connections it has to other vertices. The optional `WITH STATS` clause lets the user control how much information is recorded. Recording the information in the graph store will speed up queries which need degree information, but it increases the memory usage. There are two* options.
  * If `outdegree_by_edgetype` is chosen, then each vertex records a list of degree count values, one value for each type of edge in the schema.
  * If "none" is chosen, then no degree statistics are recorded with each vertex. If the `WITH STATS` clause is not used, the loader acts as if `outdegree_by_edgetype` were selected.


The graph below has two types of edges between persons: phone_call and text. For Bobby, the `outdegree_by_edgetype` option records how many phone calls Bobby made (1) and how many text messages Bobby sent (2). This information can be retrieved using the built-in vertex function outdegree(). To get the outdegree of a specific edge type, provide the edge type name as a string parameter. To get the total outdegree, omit the parameter.
![Diagram of a graph with five person vertices. Andy is connected to Bobby with a phone_call edge. Bobby is connected to three other person vertices, Casey, Dean and Emory with a text, phone_call, and text edges respectively.](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/_images/comms-graph-outdegree.png)
Figure 3. Illustration of outdegree stats
WITH STATS option (case-insensitive) | Bobby.outdegree() | Bobby.outdegree("text") | Bobby.outdegree("phone_call")  
---|---|---|---  
"none" | not available | not available | not available  
"outdegree_by_edgetype" (default) | 3 | 2 | 1  
## [](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_create_edge)`CREATE EDGE`
`CREATE EDGE` defines a new global edge type. Data loaded to a global edge type in one graph will be shared across all graphs that use that edge type. See [Global vs. local schema changes](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/modifying-a-graph-schema#_global_vs_local_schema_changes) for instructions on creating local edges.
A `CREATE EDGE` statement must specify at least one pair of source and target vertex types, that is, the vertex types on both ends of the edge. In GSQL, they are often referred to as `FROM` vertex and `TO` vertex, respectively, to reflect the keywords used to define the edge type.
By default, only one instance of an edge type is allowed between two vertices. You can add a discriminator to the edge type definition to allow for multiple instances of one edge type between two vertices.
  * CREATE UNDIRECTED EDGE
  * CREATE DIRECTED EDGE


```
CREATE UNDIRECTED EDGE Edge_Type_Name "("
    FROM Vertex_Type_Name "," TO Vertex_Type_Name
  [ "|" FROM Vertex_Type_Name "," TO Vertex_Type_Name]*
  [ "," DISCRIMINATOR "(" attribute_name type ("," attribute_name type)* ")"]
  [ "," attribute_name type [DEFAULT default_value]]* ")"
")"
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
CREATE DIRECTED EDGE Edge_Type_Name "("
    FROM Vertex_Type_Name "," TO Vertex_Type_Name
  [ "|" FROM Vertex_Type_Name "," TO Vertex_Type_Name]*
  [ "," DISCRIMINATOR "(" attribute_name type ("," attribute_name type)* ")"]
  [ "," attribute_name type [DEFAULT default_value]]* ")"
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

A single edge type can be defined between multiple pairs of vertex types. For example:
```
CREATE DIRECTED EDGE Member_Of (FROM Person, TO Org | FROM Org, TO Org, joined DATETIME)
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_discriminator)`DISCRIMINATOR`
A discriminator is an attribute or a set of attributes that can be used to uniquely identify an edge. The `DISCRIMINATOR` keyword defines a discriminator in an edge type definition to allow multiple instances of an edge type between two vertices.
By default, edges are uniquely identified by the combination of the edge type, source vertex, and target vertex. Between two vertices, only one instance of a certain edge type is allowed to exist if the edge type definition does not include a discriminator.
The discriminator must be unique between edges of the same type between two vertices. They **do not** have to be unique within the edge type as a whole. For example, an edge type `Study_At` with the `class_month` and `class_year` attributes as discriminators can have multiple edge instances with the same `class_month` and `class_year`, as long as those edge instances are not between the same two vertices.
Define the edge type and specify a discriminator to allow multiple instances of an edge type between two vertices. Only `INT`, `UINT` , `DATETIME` and `STRING` types are allowed to be discriminators for edge types. The specification of the discriminator must come before other attributes.
For example, the following `CREATE EDGE` statement specifies that edges of type `Study_At` can be uniquely identified by the combination of their `class_year` and `class_month` attributes:
```
CREATE DIRECTED EDGE Study_At(From Person, To University, DISCRIMINATOR(class_year INT, class_month INT), major STRING))
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

With the previous edge type definition, there can be multiple `Study_At` edges between two vertices.
### [](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_create_an_edge_from_or_to_any_vertex_type)Create an edge from or to any vertex type
An edge type can be defined whose source and target types can be any vertex type. Use the wildcard symbol `*` to indicate "any vertex type". For example, the following `Any_Edge` type can connect from any vertex to any other vertex:
Wildcard edge type
```
CREATE DIRECTED EDGE Any_Edge (FROM *, TO *, label STRING)
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

If new vertex types are added after a wildcard edge type is defined, the new vertex types are NOT included in the wildcard. That is, `*` is an alias for the vertex types that existed at the point in time that the CREATE EDGE statement is executed.  
---  
### [](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_with_reverse_edge)`WITH REVERSE_EDGE`
If a `CREATE DIRECTED EDGE` statement includes the `WITH REVERSE_EDGE=" _rev_name_ "`optional clause, then an additional directed edge type called`rev_name` is automatically created, with the FROM and TO vertices swapped. Moreover, whenever a new edge is created, a reverse edge is also created. The reverse edge will have the same attributes, and whenever the principal edge is updated, the corresponding reverse edge is also updated.
In a TigerGraph system, reverse edges provide the most efficient way to perform graph queries and searches that need to look "backwards". For example, referring to the schema of Figure 2, the query "What is the sequel of Book X, if it has one?" is a forward search, using `Sequel_Of` edges. However, the query "Is Book X a sequel? If so, what Book came before X?" requires examining reverse edges.
**Example:**
Create undirected edges for the three edge types in Figure 1.
Edge definitions for User-Book-Rating graph
```
CREATE UNDIRECTED EDGE User_Occupation (FROM User, TO Occupation)
CREATE UNDIRECTED EDGE Book_Genre (FROM Book, TO Genre)
CREATE UNDIRECTED EDGE User_Book_Rating (FROM User, TO Book, rating UINT, date_time UINT)
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The **`User_Occupation`**and**`Book_Genre`**edges have no attributes. A**`User_Book_Rating`**edge symbolizes that a user has assigned a rating to a book. Therefore it includes an additional attribute**`rating`**. In this case the**`rating`**attribute is defined to be an integer, but it could just as easily have been set to be a float attribute.
**Example:**
Create the additional edges depicted in Figure 2.
Additional Edge definitions for Expanded-User-Book-Rating graph
```
CREATE UNDIRECTED EDGE Friend_Of (FROM User, TO User, on_date UINT)
CREATE UNDIRECTED EDGE User_Book_Read (FROM User, To Book, on_date UINT)
CREATE DIRECTED EDGE Sequel_Of (FROM Book, TO Book) WITH REVERSE_EDGE="Preceded_By"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Every time the GSQL loader creates a **`Sequel_Of`**edge, it will also automatically create a**`Preceded_By`**edge, pointing in the opposite direction.
## [](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_typedef)`TYPEDEF`
User-defined tuple types defined in a query cannot be used outside their queries or across queries. To use a user-defined tuple or an accumulator that uses a user-defined tuple across queries (such as for the return type of a [subquery](https://docs.tigergraph.com/gsql-ref/4.1/querying/operators-and-expressions#_subqueries) ), the tuple and the accumulator type must be defined on the catalog level as part of the schema. User-defined types at the catalog level can only be used for query return value types, and cannot be used as an [attribute data type](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/attribute-data-types).
`TYPEDEF` statements can be used outside a query to define tuple types, GroupBy accumulator types, and heap accumulator types. Once defined, all graphs in the database have access to these user-defined types, and subqueries can be defined to return the user-defined types.
#### Example:
The example below defines a tuple type `My_Tuple` and a heap accumulator type `My_Heap`, so that the subquery `Sub_Query_1` can return a value of `My_Heap` type to its outer query `Query_1`.
```
// Define the heap accumulator at the catalog level
TYPEDEF TUPLE<name string, friends int> My_Tuple
TYPEDEF HeapAccum<My_Tuple>(3, friends DESC) My_Heap
CREATE QUERY subquery1() FOR GRAPH Social_Net RETURNS (My_Heap){
	My_Heap @@heap;
	SumAccum<int> @friends;
	Start = {Person.*};
	Start = SELECT s from Start:s-(Friend:e)-:t
	    ACCUM s.@friends += 1
	    POST-ACCUM @@heap += My_Tuple(s.id,s.@friends);
	RETURN @@heap;
}
CREATE QUERY Query_1() FOR GRAPH Social_Net {
	PRINT Sub_Query_1();
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_alter_index)`ALTER INDEX`
User-defined indexes (or secondary indexes, as they are called commonly called in the database industry) are a valuable feature that enhances the performance of a database system. Indexes allow users to perform fast lookups on non-key columns or attributes without a full-fledged scan.
The TigerGraph database allows users to define on vertex attributes. The user has the flexibility to create indexes in an empty graph initially or to add indexes later when the database is running. If the index is added on an existing vertex, index data is built in the background.
Indexes can be created on vertices on a single attribute of the following data types only: `STRING`, `UINT`, `INT`, and `DATETIME`. Indexes will be used to optimize queries with all predicate types. However, if a predicate uses an in-built function, then index will not be used to optimize the query. Also, built-in queries are not optimized using indexes.
Indexes are very important for data retrieval performance. However, adding indexes will affect write performance. For this reason, users should use caution when adding indexes. Users should review the querying patterns to decide where indexes can help.  
---  
Users can create and drop indexes using `ALTER VERTEX` command as shown below.
```
Syntax:
CREATE GLOBAL SCHEMA_CHANGE job <job-name>
{
 ALTER VERTEX Object_Type_Name ADD INDEX Index_Type_Name ON (Attribute_Name);
 ALTER VERTEX Vertex_Type_Name DROP INDEX Index_Type_Name;
};
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Example:
`ALTER VERTEX User ADD INDEX user_country_index ON (country);`
## [](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_create_graph)`CREATE GRAPH`
`CREATE GRAPH` defines a graph schema, which contains the given vertex types and edge types, and prepares the graph store to accept data. The vertex types and edge types may be listed in any order. Executing `CREATE GRAPH` will set the new graph to be the working graph.
### [](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_required_privilege)Required privilege
`WRITE_SCHEMA`
Syntax for `CREATE GRAPH`
```
CREATE GRAPH Graph_Name (Vertex_Or_Edge_Type, Vertex_Or_Edge_Type...) **(1)****(2)**
        [WITH ADMIN username]
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | Replace graph_name with the name you want to name the graph with  
---|---  
**2** | Replace vertex_or_edge_type with the vertex and edge types you want to include in the graph  
The optional `WITH ADMIN` clause sets the named user to be the admin for the new graph.
Instead of providing a list of specific vertex types and edge types, you can define a graph type that includes all the available vertex types and edge types by replacing the list of vertex and edge types with `*`.
You can also create a graph with no vertex or edge types. A schema change can be used later to add vertex and edge types.
Examples of `CREATE GRAPH` with all vertex & edge types and with an empty domain.
```
CREATE GRAPH Everything_Graph (*)
CREATE GRAPH Empty_Graph ()
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_examples)Examples
Create graph `Book_rating` for the edge and vertex types defined for the below:
![A schema for a User-Book-Rating graph](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/_images/user-book-rating-schema.png)
Figure 4. A schema for a User-Book-Rating graph
Full definition for the Expanded User-Book-Rating graph
```
CREATE VERTEX User (PRIMARY_ID user_id UINT, name STRING, age UINT, gender STRING, postalCode STRING)
CREATE VERTEX Occupation (PRIMARY_ID occ_id UINT, occ_name STRING) WITH STATS="outdegree_by_edgetype"
CREATE VERTEX Book (PRIMARY_ID bookcode UINT, title STRING, pub_year UINT) WITH STATS="none"
CREATE VERTEX Genre (PRIMARY_ID genre_id STRING, genre_name STRING)
CREATE UNDIRECTED EDGE User_Occupation (FROM User, TO Occupation)
CREATE UNDIRECTED EDGE Book_Genre (FROM Book, TO Genre)
CREATE UNDIRECTED EDGE User_Book_Rating (FROM User, TO Book, rating UINT, date_time UINT)
CREATE UNDIRECTED EDGE Friend_Of (FROM User, TO User, on_date UINT)
CREATE UNDIRECTED EDGE User_Book_Read (FROM User, To Book, on_date UINT)
CREATE DIRECTED EDGE Sequel_Of (FROM Book, TO Book) WITH REVERSE_EDGE="Preceded_By"
CREATE GRAPH Book_Rating (*) **(1)**
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | Having created all the necessary vertex and edge types, use the `*` sign to include all vertex and edge types in the graph.  
---|---  
### [](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_create_graph_as_beta)`CREATE GRAPH …​ AS` (Beta)
`CREATE GRAPH …​ AS` creates a tag-based graph of an existing graph. Tag-based graphs include vertices with specific tags from their base graphs, and have their own access control. Users can be granted roles on a tag-based graph and their roles will give them privileges that only apply to the resources in the tag-based graph.
This command can only be run on the base graph and requires the user to have the schema-editing privilege on the base graph.
Synopsis
```
<create_tag_graph> :=
  CREATE GRAPH <tag_graph_name> AS <base_graph_name>
  ( "(" <tagged_element_name> ("," <tagged_element_name>)* ")" | ":" <tag_expr> )
<tagged_element_name> := <tagged_vertex_name> | <edge_name>
<tagged_vertex_name> := <vertex_name> [":" <tag_expr>]
<tag_expr> := <tag> ("&" <tag_expr>)*
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The syntax for creating tag-based graphs is the same as creating a regular graph except that a base graph must be specified with the `AS` clause after the `CREATE GRAPH` command, and the definition of the graph must include at least one tagged vertex type. Edges are not tagged in a tag-based graph, but edges with either a source or a target outside the tag-based graph are not visible to users of the tag-based graph.
#### [](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_include_vertices_with_multiple_tags)Include vertices with multiple tags
Use the ampersand operator (`&`) to express vertices with multiple tags:
```
CREATE GRAPH Mixed_Net AS Social_Net(person:public&vip, post:public&tech&default,
friend, posted, liked)
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_include_everything_in_the_base_graph_with_specified_tags)Include everything in the base graph with specified tags
Use a colon to specify tags directly after the graph name to include everything in the base graph that has the specified tags:
```
CREATE GRAPH Public_Net_2 AS Social_Net:Public
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_use_graph)`USE GRAPH`
New requirement for MultiGraph support. Applies even if only one graph exists.  
---  
Before a user can use a graph, the user must be granted a role on that graph by an admin user of that graph or by a superuser. (Superusers are automatically granted the admin role on every graph). Second, for each GSQL session, the user must set a working graph. The `USE GRAPH` command sets or changes the user’s working graph, for the current session.
For more about roles and privileges, see the document [Managing User Privileges and Authentication](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/).
USE GRAPH syntax
```
USE GRAPH gname
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Instead of the `USE GRAPH` command, gsql can be invoked with the `-g <graph_name>` option.
## [](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_drop_graph)`DROP GRAPH`
### [](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_syntax)Syntax
```
DROP GRAPH Graph_Name
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_required_privilege_2)Required privilege
`WRITE_SCHEMA`
The `DROP GRAPH` command deletes the logical definition of the named graph. It will also delete all local vertex or edge types. Local vertex and edge types are created by an `ADD VERTEX/EDGE[](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/modifying-a-graph-schema#_add_vertex_edge)` statement within a `SCHEMA_CHANGE JOB[](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/modifying-a-graph-schema#_create_schema_change_job)` and so belong only to that graph. Any shared types are unaffected. To delete only selected vertex types or edge types, see `DROP VERTEX | EDGE` in the Section "[Modifying a Graph Schema](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/modifying-a-graph-schema)".
## [](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_drop_all)`DROP ALL`
### [](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_required_privilege_3)Required privilege
`Drop_ALL`
The `DROP ALL` command clears the entire graph store (i.e. deletes all data) and removes all data-related definitions from the catalog: vertex types, edge types, graph types, jobs, and queries. It will also erase graph-specific roles.
Unlike [the `gsql --reset` command](https://docs.tigergraph.com/tigergraph-server/4.1/getting-started/database-definition#_reset_all), `DROP ALL` does not erase user and role information nor system settings.
`DROP ALL`, along with all DROP operations, is non-reversible.  
---  
## [](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_show_view_parts_of_the_catalog)`SHOW` - View Parts of the Catalog
The `SHOW` command can be used to show certain aspects of the graph, instead of manually filtering through the entire graph schema when using the `ls` command. You can either type the exact identifier or use regular expressions / Linux globbing to search.
```
SHOW <VERTEX> | <EDGE> | <JOB> | <QUERY> | <GRAPH> | <PACKAGE> [ <name> | <glob> | -r <regex> ]
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

`SHOW GRAPH` lists vertices and edges without giving their properties, and is also a way to check the JSON API and syntax versions of the graph, as well as any loading jobs. `SHOW VERTEX` and `SHOW EDGE` list the properties of the desired vertex or edge respectively. `SHOW PACKAGE` lists the packages that are available, such as the packaged template queries. See [Using an Algorithm - Packaged template queries](https://docs.tigergraph.com/graph-ml/3.10/using-an-algorithm/#packaged-template-queries) for more information.
This feature supports the `?` and `*` from linux globbing operations, and also regular expression matching. Usage of the feature is limited to the scope of the graph the user is currently in - if you are using a global graph, you will not be able to see vertices that are not included in your current graph.
Regular expression searching will not work with escaping characters.  
---  
To use regular expressions, you will need to use the `-r` flag after the part of the schema you wish to show. If you wish to dive deeper into regular expressions, visit ["Java Patterns"](https://docs.oracle.com/javase/7/docs/api/java/util/regex/Pattern.html). The following are a few examples of what is supported by the `SHOW` command.
```
Linux Globbing examples
SHOW VERTEX us*      //shows all vertices that start with the letters "Us"
SHOW VERTEX co?*y     //shows the vertices that starts with co and ends with y
SHOW VERTEX ?????     //shows all vertices that are 5 letters long
Regular Expression Examples
SHOW VERTEX -r "skil{2}"  //match the pattern "skill"
SHOW EDGE -r "test[1][13579]*"  //match pattern that only contains odd numbers after "test"
SHOW JOB -r "[a-zA-Z]*"   //match all jobs that contain only letters
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

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


