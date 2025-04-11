![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/4.1/querying/syntax-versions)[Next](https://docs.tigergraph.com/gsql-ref/4.1/querying/syntax-versions)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/4.1/querying/syntax-versions)
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
[Resources](https://docs.tigergraph.com/gsql-ref/4.1/querying/syntax-versions)
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
  * [Query Language Syntax Versions](https://docs.tigergraph.com/gsql-ref/4.1/querying/syntax-versions)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/4.1/modules/querying/pages/syntax-versions.adoc)
### Contents
  * [Differences between V2 and V3](https://docs.tigergraph.com/gsql-ref/4.1/querying/syntax-versions#_differences_between_v2_and_v3)
  * [V2 vs. V3 Syntax: Examples and Explanations](https://docs.tigergraph.com/gsql-ref/4.1/querying/syntax-versions#_v2_vs_v3_syntax_examples_and_explanations)
  * [Comparing V2 and V3 Edge Directions](https://docs.tigergraph.com/gsql-ref/4.1/querying/syntax-versions#_comparing_v2_and_v3_edge_directions)
  * [Differences between V1 and V2](https://docs.tigergraph.com/gsql-ref/4.1/querying/syntax-versions#_differences_between_v1_and_v2)
  * [Changing a query from V1 to V2](https://docs.tigergraph.com/gsql-ref/4.1/querying/syntax-versions#_changing_a_query_from_v1_to_v2)


# Query Language Syntax Versions
### Contents
  * [Differences between V2 and V3](https://docs.tigergraph.com/gsql-ref/4.1/querying/syntax-versions#_differences_between_v2_and_v3)
  * [V2 vs. V3 Syntax: Examples and Explanations](https://docs.tigergraph.com/gsql-ref/4.1/querying/syntax-versions#_v2_vs_v3_syntax_examples_and_explanations)
  * [Comparing V2 and V3 Edge Directions](https://docs.tigergraph.com/gsql-ref/4.1/querying/syntax-versions#_comparing_v2_and_v3_edge_directions)
  * [Differences between V1 and V2](https://docs.tigergraph.com/gsql-ref/4.1/querying/syntax-versions#_differences_between_v1_and_v2)
  * [Changing a query from V1 to V2](https://docs.tigergraph.com/gsql-ref/4.1/querying/syntax-versions#_changing_a_query_from_v1_to_v2)


GSQL has three syntax versions: V3, V2, and V1 (legacy version). In TigerGraph 3.5, the default syntax version was changed to V2. Currently, V2 remains the default syntax version. In a future release, V3 will become the default syntax version. This page provides a summary of the differences between V2 and V3, as well as V1 and V2. It also includes guidance on how to change your V1 query into a V2 query.
## [](https://docs.tigergraph.com/gsql-ref/4.1/querying/syntax-versions#_differences_between_v2_and_v3)Differences between V2 and V3
The table below highlights the differences between V2 and V3, focusing on the `FROM` clause. Note that V3 still supports V2 style syntax, for backward compatibility.
Feature | V2 Style | V3 Style  
---|---|---  
Vertex-Edge-Vertex Markers | Use `source_vset -(edge_set)- target_vset` notation. Vertices and edges are separated without additional symbols for vertices, for example, `Person -(FRIENDS)- Colleague`. | Use `(source_vset) -[edge_set]- (target_vset)` notation, where vertices are enclosed in parentheses () and edges are enclosed in square brackets [] . For example: `(Person) -[FRIENDS]- (Colleague)`.  
Alias Ordering | Object sets precede aliases: `source_vset:Alias -(edge_set:EdgeAlias)- target_set:Alias`. | Aliases precede object sets: `(Alias:source_vset) -[EdgeAlias:edge_set]- (Alias:target_set)`, reversing the order of V2.  
Symbols for Edge Direction | Directionality is applied at the edge-set level. Supports `<` (left), `>` (right), and `_` (undirected). | Directionality applies to the entire edge pattern. Symbols include `<-` (left), `->` (right), `~` (undirected).  
Edge Direction Syntax | Supports granular directionality at the individual edge set level, allowing each edge sets in a pattern to have its own direction. | Directionality is applied globally at the edge pattern level.  
Quantified Multi-Hop Patterns | V2 uses `*j..k` to express a range of j to k repeated edges: `-(FRIENDS*1..3)->` | V3 uses `[j,k]` to express a range of j to k repeated edges: `[FRIENDS]->{1,3}`  
Filters in Edge Patterns | Filters are applied outside the `FROM` clause, e.g., `SELECT Person FROM Person -(FRIENDS)- Colleague WHERE FRIENDS.length > 2` | Filters can also be placed within an edge pattern for more local scope , e.g., `SELECT Person FROM (Person) -[FRIENDS WHERE FRIENDS.length > 2]-> (Colleague)`  
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/syntax-versions#_v2_vs_v3_syntax_examples_and_explanations)V2 vs. V3 Syntax: Examples and Explanations
  1. **Vertex-Edge-Vertex Markers:**
     * **V2 Syntax:** `Person -(FRIENDS)- Colleague`
     * **V3 Syntax:** `(Person) -[FRIENDS]- (Colleague)`
     * In V3, uses more punctuation in order to be more explicit about vertex and edge patterns.
  2. **Alias Ordering:**
     * **V2 Syntax:** `Person:p -(FRIENDS:f)- Colleague:c`
     * **V3 Syntax:** `(p:Person) -[f:FRIENDS]- (c:Colleague)`
  3. **Symbols for Edge Direction:**
     * **V2 Syntax:** `-(FRIENDS>:f)-`
     * **V3 Syntax:** `<-[f:FRIENDS]->`
     * V3 directionality is applied globally to the entire edge pattern. V2 directionality applies to each individual edge type, for greater flexibility.
  4. **Filters in Edge Patterns:**
     * **V2 Syntax:** Filtering is applied outside the `FROM` clause using a `WHERE` condition: `SELECT Person FROM Person -(FRIENDS)- Colleague WHERE FRIENDS.length > 2`
     * **V3 Syntax:** Filters can also be placed within an edge pattern for more local scope: `SELECT Person FROM (Person) -[FRIENDS WHERE FRIENDS.length > 2]-> (Colleague)`
  5. **Quantified Multi-Hop Patterns:**
     * **V2 Syntax:** `-(FRIENDS*1..3)->`
     * **V3 Syntax:** `[FRIENDS]->{1,3}`


## [](https://docs.tigergraph.com/gsql-ref/4.1/querying/syntax-versions#_comparing_v2_and_v3_edge_directions)Comparing V2 and V3 Edge Directions
In the following table,
  1. **E1 and E2:** These represent directed edge types. A directed edge has a defined direction, such as `Person -> Company`.
  2. **U1 and U2:** These represent undirected edge types. An undirected edge does not have a direction and connects vertices symmetrically, such as `Person - Person`.
  3. **Alias (A):** The alias is a short name or label given to an edge or vertex for use in queries.
  4. **Edge Direction:**
     * **Left (`<`):** Represents edges directed towards the starting vertex.
     * **Right (`>`):** Represents edges directed away from the starting vertex.
     * **Undirected (`~`):** Represents edges with no directionality.
     * **Combination (`<~` , `~>`, etc.):** Represents edges with a combination of directionality (e.g., left or undirected, right or undirected).


Orientation | V2 Syntax | V3 Syntax  
---|---|---  
Pointing Left | `-(<E1:A)-` | `<-[A:E1]-`  
Pointing Right | -(E1>:A)- | `-[A:E1]->`  
Undirected | `-(U1:A)-` | `~[A:U1]~`  
Left or Undirected | `-((<E1|U1):A)-` | `<~[A:E1|U1|..]~`  
Right or Undirected | `-((E1>|U1):A)-` | `~[A:E1|U1|..]~>`  
Any direction or undirected | `-(<_|_|_>):A)-` or `-(:A)-` | `-[A:U1|E1|..]-` or `-[A:]-`  
## [](https://docs.tigergraph.com/gsql-ref/4.1/querying/syntax-versions#_differences_between_v1_and_v2)Differences between V1 and V2
The two tables below summarize the differences between V1 and V2.
Most of the syntactical differences between V1 and V2 lie in the `FROM` clause of the `SELECT` statement. Therefore, Table 1 specifically lays out the differences in the `FROM` clause. Other differences are summarized in Table 2.
Table 1. Differences in the `FROM` clause Feature | V1 | V2  
---|---|---  
Step vs path pattern |  The keyword `FROM` is followed by a 1-hop step. Supports 1-hop only. For more information, see [`FROM` clause (V1)](https://docs.tigergraph.com/gsql-ref/4.1/querying/select-statement/select-statement-v1#_from_clause). |  The keyword `FROM` is followed by a [path pattern](https://docs.tigergraph.com/gsql-ref/4.1/querying/select-statement/#_path_pattern). The path pattern may consist of multiple hops and allows for powerful [pattern matching](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/multiple-hop-and-accumulation).  
Edge notation | Edges in a step can optionally have a right arrowhead outside the parentheses. For example: `Start:s -( Edges:e )-> Target:t` or `Start:s -( Edges:e )- Target:t` | No arrowheads are allowed outside the parentheses. If an edge type is directed, the edge notation must have arrowheads inside the parentheses to indicate direction. For example: `Person:s-(STUDY_AT>:e)-University:t`  
Traversal direction | The traversal action is from left to right, and the notation uses either a rightward facing arrowhead or no arrowhead to depict a connection. | The traversal direction is under the control of the query writer, with arrowheads on each edge set to show the direction.  
Source vertex set | The source vertex set in a step in the `FROM` clause must be [a vertex set (seed set)](https://docs.tigergraph.com/gsql-ref/4.1/querying/declaration-and-assignment-statements#_vertex_set_variables) declared earlier in the query. | The [source vertex set path pattern](https://docs.tigergraph.com/gsql-ref/4.1/querying/select-statement/#<em>source_vertex_set) in `FROM` clause can be a vertex set, a vertex type, or use or `ANY` to indicate any vertex.  
Table 2. Other differences Feature | V1 | V2  
---|---|---  
[`POST-ACCUM` clause](https://docs.tigergraph.com/gsql-ref/4.1/querying/select-statement/#_post_accum_clause) | 
  * Each `SELECT` statement can only have 1 `POST-ACCUM` clause.
  * A `POST-ACCUM` clause may have statements that reference both source and target vertex aliases.

| 
  * Each `SELECT` statement can have multiple `POST-ACCUM` clauses.
  * Each `POST-ACCUM` clause must bind itself with one vertex alias. This can be done explicitly or implicitly.

  
[SQL-like `SELECT` statement](https://docs.tigergraph.com/gsql-ref/4.1/querying/select-statement/sql-like-select-statement) | Not supported. | Supported.  
Data modification statements | `FROM` clause can only perform one hop, which is the same as in the `SELECT` statement in V1. | `FROM` clause can only perform one hop, even though it may perform multiple hops in the `SELECT` statement.  
## [](https://docs.tigergraph.com/gsql-ref/4.1/querying/syntax-versions#_changing_a_query_from_v1_to_v2)Changing a query from V1 to V2
This section provides you with instructions to convert a V1 query into a V2 query.
GSQL can detect the syntax version of the query automatically, so there is no need to modify your queries from V1 to V2.
  1. Delete, move, or add arrowheads in the `FROM` clause.
     * If the edge is undirected, delete the arrowhead outside parentheses in the `FROM` clause.
       * For example `Source:s -(Friend:e)-> :t` becomes `Source:s -(Friend:e)- :t`
     * If the edge is directed, move the arrowheads into the parentheses after the edge type. If there is no arrowhead, you must add one after the edge type.
       * For example, `Source:s -(Is_Located_In:e)-> :t` becomes `Source:s -(Is_Located_In>:e)- :t`
This is the most common incompatibility issue between a query written in V1 and V2. Most V1 queries can run smoothly in V2 after the arrowheads are deleted.
  2. Check for `POST-ACCUM` clauses that aren’t bound to one vertex alias or are bound to more than one vertex alias.
     * In V2, every `POST-ACCUM` clause must reference one vertex alias. If your V1 query has a `POST-ACCUM` clause that reference multiple vertex aliases, you need to break the `POST-ACCUM` clause into multiple `POST-ACCUM` clauses, with each clause referencing one vertex alias only.


Since a `SELECT` statement can only perform one hop in V1, you may have had to write multiple `SELECT` statements in order to write a multi-hop query. With pattern matching in V2, you may choose to rewrite the query to use a single `SELECT` statement to perform multiple hops.
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


