![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods)[Next](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods)
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
[Resources](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods)
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
  * [Vertex Functions](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/3.6/modules/querying/pages/func/vertex-methods.adoc)
### Contents
  * [Vertex alias methods](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_vertex_alias_methods)
  * [edgeAttribute()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_edgeattribute)
  * [filter()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_filter)
  * [getAttr()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_getattr)
  * [neighborAttribute()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_neighborattribute)
  * [neighbors()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_neighbors)
  * [outdegree()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_outdegree)
  * [setAttr()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_setattr)
  * [VLAC vertex alias methods (Deprecated)](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_vlac_vertex_alias_methods_deprecated)
  * [addTags()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_addtags)
  * [differenceTags()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_differencetags)
  * [getTags()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_gettags)
  * [hasTags()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_hastags)
  * [isTaggable()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_istaggable)
  * [intersectTags()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_intersecttags)
  * [removeAllTags()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_removealltags)
  * [removeTags()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_removetags)
  * [Vertex functions](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_vertex_functions)
  * [getvid()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_getvid)
  * [selectVertex()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_selectvertex)
  * [to_vertex()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_to_vertex)
  * [to_vertex_set()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_to_vertex_set)


# Vertex Functions
### Contents
  * [Vertex alias methods](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_vertex_alias_methods)
  * [edgeAttribute()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_edgeattribute)
  * [filter()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_filter)
  * [getAttr()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_getattr)
  * [neighborAttribute()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_neighborattribute)
  * [neighbors()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_neighbors)
  * [outdegree()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_outdegree)
  * [setAttr()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_setattr)
  * [VLAC vertex alias methods (Deprecated)](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_vlac_vertex_alias_methods_deprecated)
  * [addTags()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_addtags)
  * [differenceTags()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_differencetags)
  * [getTags()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_gettags)
  * [hasTags()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_hastags)
  * [isTaggable()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_istaggable)
  * [intersectTags()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_intersecttags)
  * [removeAllTags()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_removealltags)
  * [removeTags()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_removetags)
  * [Vertex functions](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_vertex_functions)
  * [getvid()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_getvid)
  * [selectVertex()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_selectvertex)
  * [to_vertex()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_to_vertex)
  * [to_vertex_set()](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_to_vertex_set)


This page lists the vertex functions that are available in the GSQL query language. The functions are divided into three categories.
  * Vertex alias methods
    * Methods available to vertex aliases
  * Vertex-level access control(VLAC) vertex alias methods
    * Methods available to vertex aliases that are related to vertex tags.
  * Vertex functions
    * Functions that return a vertex or vertex set, or functions that are closely related to certain attributes of `VERTEX` type variables.


## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_vertex_alias_methods)Vertex alias methods
This section lists the built-in methods of vertex aliases. Methods can be accessed by the dot (`.`) operator.
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_edgeattribute)`edgeAttribute()`
#### Syntax
`v.edgeAttribute( edgeType, attrName )`
#### Description
From a vertex, traverse edges of a specified type and return the bag of values for a specified edge attribute.
#### Return type
`BagAccum<attrType>`
#### Parameters
Parameter | Description | Data type  
---|---|---  
`edgeType` | The edge type to traverse | `STRING`  
`attrName` | The attribute whose value to retrieve | `STRING`  
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_filter)`filter()`
#### Syntax
```
v.neighbors().filter( condition )
v.neighborAttribute().filter( condition )
v.edgeAttribute().filter( condition )
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### Description
This function is appended to [`neighbors()`](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_neighbors), [`neighborAttribute()`](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_neighborattribute), or [`edgeAttribute()`](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_edgeattribute) to filter the output set according to a filter condition. Only elements that satisfy the condition will be returned.
#### Return type
`BagAccum`
#### Parameters
Parameter | Description | Data type  
---|---|---  
`condition` | An expression that evaluates to a boolean value | `BOOL`  
#### Example
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

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_getattr)`getAttr()`
#### Syntax
`v.getAttr(attrName, attrType)`
#### Description
Returns the value of a vertex attribute on the vertex.
#### Return type
`attrType`
#### Parameters
Parameter | Description | Data type  
---|---|---  
`attrName` | A vertex attribute | `STRING`  
`attrType` | The type of the attribute value | `STRING`  
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_neighborattribute)`neighborAttribute()`
#### Syntax
`v.neighborAttribute( edgeType, targetVertexType, attrName )`
#### Description
From a vertex, traverses edges of a specified type to its neighbors of a specified type, and returns the set of values for a specified attribute.
#### Return type
`BagAccum<attrType>`
#### Parameters
Parameter | Description | Data type  
---|---|---  
`edgeType` | The edge type to traverse | `STRING`  
`targetVertexType` | The target vertex type to visit | `STRING`  
`attrName` | An attribute of the target vertex type | `STRING`  
#### Example
For the following graph:
![Diagram of a graph of Person vertices connected to each other with friendship edges. Each vertex is connected to one or two other vertices except for 'Dan', who is connected to three.](https://docs.tigergraph.com/gsql-ref/3.6/querying/_images/image%20\(79\).png)
```
# If v is Jenny
v.neighborAttribute("friendship", "person", "state") -> ["ca", "ny", "ca"]
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_neighbors)`neighbors()`
#### Syntax
`v.neighbors([edgeType])`
#### Description
Returns the out-neighbors or undirected neighbors of the vertex. If edge types are provided, it will only return the neighbors connected by the specified edge types.
#### Return type
`BagAccum<VERTEX>`
#### Parameters
Parameter | Description | Data type  
---|---|---  
`edgeType` | Optional. An edge type or a collections of edge types. | `STRING`, `SET<STRING>`, `SetAccum<STRING>`, `BagAccum<STRING>`, `ListAccum<STRING>`  
#### Example
For the following graph:
![Diagram of a graph of Person vertices connected to each other with friendship edges. Each vertex is connected to one or two other vertices except for 'Dan', who is connected to three.](https://docs.tigergraph.com/gsql-ref/3.6/querying/_images/image%20\(79\)%20\(1\).png)
```
# If v is Jenny
v.neighbors() -> ["Dan", "Amily", "Tom"]
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_outdegree)`outdegree()`
#### Syntax
`v.outdegree([edgeType])`
#### Description
Returns the number of outgoing or undirected edges connected to the vertex. If edge types are provided, it will only return the number of edges of the specified types.
#### Return type
`INT`
#### Parameters
Parameter | Description | Data type  
---|---|---  
`edgeType` | Optional. An edge type or a collection of edge types. | `STRING`, `SET<STRING>`, `SetAccum<STRING>`, `BagAccum<STRING>`, `ListAccum<STRING>`  
**Note on outdegree()** : This function reads a metadata value stored with each vertex, to avoid traversing the graph and thus have a fast response. The snapshot transaction semantics means that outdegree() may sometimes read an old value if there are concurrent write transactions. To guarantee an accurate count, traverse the neighboring edges and count them with a SumAccum, or use a function like neighbors() and then use size() on the set.
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_setattr)`setAttr()`
#### Syntax
`v.setAttr( attrName, newValue )`
#### Description
Sets the specified attribute of a vertex to a new value.
#### Return type
No return value.
#### Parameters
Parameter | Description | Data type  
---|---|---  
`attrName` | The name of an attribute | `STRING`  
`newValue` | The new value for the attribute | The type of the attribute.  
## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_vlac_vertex_alias_methods_deprecated)VLAC vertex alias methods (Deprecated)
Tag-based Vertex-Access Access Control is deprecated as of October 2023. TigerGraph will be introducing a more flexible scheme in an upcoming release.   
---  
This section covers the vertex alias methods used to access and modify tags on vertices,
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_addtags)`addTags()`
#### Syntax
`v.addTags(STRING tag1,... STRING tagN)`
#### Description
Adds the tags provided in the argument list to the vertex.
#### Return type
No return value.
#### Parameters
Parameter | Description | Data type  
---|---|---  
`tagN` | A tag to add to the vertex | `STRING`  
#### Example:
```
CREATE QUERY addTagsToPerson() {
 Seed = { any };
 # person1 ~ person5 will be tagged as public.
 vSet = SELECT s
     FROM Seed:s
     WHERE s.id IN ("person1","person2","person3","person4","person5")
     ACCUM s.addTags("public");
 # person6 and person7 will be tagged as public and vip.
 vSet = SELECT s
     FROM Seed:s
     WHERE s.id IN ("person6","person7")
     ACCUM s.addTags("vip", "public");
 # person8 will be tagged as vip
 vSet = SELECT s
     FROM Seed:s
     WHERE s.id == "person8"
     ACCUM s.addTags("vip");
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_differencetags)`differenceTags()`
#### Syntax
`v.differenceTags( v2 )`
#### Description
Returns the difference in tags between the vertex and another vertex as a set.
#### Return type
`SET<STRING>`
#### Paramters
Parameter | Description | Data type  
---|---|---  
`v2` | A vertex | `VERTEX`  
#### Example:
```
// return the difference set of tags between two vertices
CREATE QUERY exampleDifferencetags() {
 SetAccum<string> @vAcc;
 vSet = { any };
 vSet = SELECT s
     FROM vSet:s -(_)- :t
     WHERE t.type == "person"
     ACCUM s.@vAcc += s.differenceTags(t);
 PRINT vSet[vSet.@vAcc];
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_gettags)`getTags()`
#### Syntax
`v.getTags()`
#### Descriptions
Returns the vertex’s tags as a set. If the vertex has no tags or is untaggable, it returns an empty set.
#### Return type
`SET<STRING>`
#### Parameters
None.
#### Example:
```
//print the tags of each vertices, in 2 different ways.
CREATE QUERY exampleGettags() {
 SetAccum<string> @vAcc;
 vSet = { any };
 vSet = SELECT s
     FROM vSet:s
     ACCUM s.@vAcc += s.getTags();
 PRINT vSet[vSet.@vAcc];
 PRINT vSet[vSet.gettags()];
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Tip: `getTags()` can be used within a `PRINT` statement:
  * `PRINT R [R.getTags()];`
  * or `PRINT R WITH TAGS` which is syntax sugar, except that it won’t print `"R.getTags()": []` for non-taggable vertices.


### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_hastags)`hasTags()`
#### Syntax
`hasTags( tag1, tag2, ..., tagN )`
#### Description
Returns `true` if the vertex has every tag provided in the argument list and returns `false` if it does not.
#### Return type
`BOOL`
#### Parameters
Parameter | Description | Data type  
---|---|---  
`tagN` | A string. | `STRING`  
#### Example:
```
USE GRAPH socialNet
CREATE QUERY findVertexWithTag(STRING tag) {
 seed = { ANY };
 res =
  SELECT v
  FROM seed:v
  WHERE v.hasTags(tag)
  ORDER BY v.id;
 PRINT res WITH TAGS;
}
INSTALL QUERY findVertexWithTag
RUN QUERY findVertexWithTag("vip")
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The output of the query would be:
```
{
 "error": false,
 "message": "",
 "version": {
  "schema": 2,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"res": [
  {
   "v_id": "person6",
   "attributes": {
    "gender": "Male",
    "id": "person6",
    "res.gettags()": [
     "vip",
     "public"
    ]
   },
   "v_type": "person"
  },
  {
   "v_id": "person7",
   "attributes": {
    "gender": "Male",
    "id": "person7",
    "res.gettags()": [
     "vip",
     "public"
    ]
   },
   "v_type": "person"
  },
  {
   "v_id": "person8",
   "attributes": {
    "gender": "Male",
    "id": "person8",
    "res.gettags()": ["vip"]
   },
   "v_type": "person"
  }
 ]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_istaggable)`isTaggable()`
#### Syntax
`v.isTaggable()`
#### Description
Returns true if the vertex is taggable.
#### Return type
`BOOL`
#### Parameters
None
#### Example:
```
//count the number of taggable vertices in the graph.
CREATE QUERY countIstaggable() for graph poc_graph_tag {
 SumAccum<int> @@count;
 vSet = { any };
 vSet = SELECT s
     FROM vSet:s
     WHERE s.isTaggable()
     ACCUM @@count += 1;
 PRINT @@count;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_intersecttags)`intersectTags()`
#### Syntax
`v.intersectTags( v2 )`
#### Description
Returns the common tags between the vertex and another vertex as a set.
#### Return type
`SET<STRING>`
#### Example:
```
//return the intersect set of tags between two vertices.
CREATE QUERY exampleIntersecttags() {
 SetAccum<string> @vAcc;
 vSet = { any };
 vSet = SELECT s
     FROM vSet:s -(_)- :t
     WHERE t.type == "person"
     ACCUM s.@vAcc += s.intersectTags(t);
 PRINT vSet[vSet.@vAcc];
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_removealltags)`removeAllTags()`
#### Syntax
`v.removeAllTags()`
#### Description
Removes all tags from the vertex.
#### Return type
No return value.
#### Parameters
None
#### Example:
```
//remove all tags from all person vertices.
CREATE QUERY removealltagsFromPerson() {
 vSet = { person.* };
 # remove all tags from all person vertices
 vSet = SELECT s
     FROM vSet:s
     ACCUM s.removeAllTags();
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_removetags)`removeTags()`
#### Syntax
`removeTags( tag1, tag2, ..., tagN )`
#### Description
Removes the tags provided in the argument list from the vertex.
#### Return type
No return value.
#### Parameters
Parameter | Description | Data type  
---|---|---  
`tagN` | A string value | `STRING`  
#### Example
```
//remove tag “vip” and “public” from all person vertices.
CREATE QUERY removetagsFromPerson() {
 vSet = { person.* };
 # remove tag vip and public from all person vertices
 vSet = SELECT s
     FROM vSet:s
     ACCUM s.removeTags("vip", "public");
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_vertex_functions)Vertex functions
The functions in this section either have return values of vertex or vertex set type or are closely related to vertex attributes.
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_getvid)`getvid()`
#### Syntax
`getvid( v )`
#### Description
Returns the _internal_ ID number of a vertex.
The internal ID is not the primary ID which the user assigned when creating the vertex. However, there is a 1-to-1 mapping between the external ID (`primary_id`) and internal ID.
The engine can access the internal ID faster than accessing the external ID, so if a query needs unique values for a large number of vertices, but doesn’t care about particular values, `getvid()` can be a useful option. For example, in many community detection algorithms, we start by assigning every vertex a unique community ID. Then, as the algorithm progresses, some vertices will join the community of one of their neighbors, giving up their current community ID and copying the IDs of their neighbors.
#### Return type
`INT`
#### Parameters
Parameter | Description | Data type  
---|---|---  
`v` | A vertex alias. | Vertex alias  
#### Example 

Query
    
```
CREATE QUERY getvid_ex () FOR GRAPH socialNet {
MinAccum<int> @cc_id = 0;    //each vertex's tentative component id
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


Result
    
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

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_selectvertex)`selectVertex()`
#### Syntax
`selectVertex( filepath, vertexIdColumn, vertexTypeColumn, seperator, header)`
#### Description
Reads a data file that lists particular vertices of the graph and returns the corresponding vertex set.This function can only be used in a vertex set variable declaration statement as a seed set and the vertices in the data file **must already be in the graph**.The data file must be organized as a table with one or more columns.One column must be for vertex ID.Optionally, another column is for vertex type.
#### Return type
`SET<VERTEX>`
#### Parameters
Parameter | Description | Data type  
---|---|---  
`filePath` | The absolute file path of the input file to be read. A relative path is not supported. | `STRING`  
`vertexIdColumn` |  The vertex ID column position. The index for column positions starts at 0. Therefore, to designate the first column as the ID column, set this parameter to `$0`. |  `$ num` If `header` is set to true, `$ "column_name"` is also acceptable.  
`vertexTypeColumn` | The vertex type column position or a specific vertex type. |  `$ num` If `header` is set to true,`$ "column_name"` is also acceptable. Alternatively, a vertex type without double quotes.  
`separator` | The column separator character. | `STRING`  
`header` | Whether this file has a header. | `BOO  
#### Example
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

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_to_vertex)`to_vertex()`
Running `to_vertex() and to_vertex_set()` requires real-time conversion of an external ID to a GSQL internal ID, which is a relatively slow process. Therefore,
  * If the user can always know the id before running the query, define the query with `VERTEX` or `SET<VERTEX>` parameters instead of `STRING` or `SET<STRING>` parameters, and avoid calling `to_vertex()` or `to_vertex_set()`.
  * Calling `to_vertex_set()` one time is much faster than calling `to_vertex()` multiple times. Use `to_vertex_set()` instead of `to_vertex()` as much as possible.

  
---  
#### Syntax
`to_vertex( id, vertex_type )`
#### Description
Returns a vertex from a string ID and vertex type. If a vertex with the provided ID and type does not exist, the function will throw a run-time error.
#### Return type
`VERTEX`
#### Parameters
Parameter | Description | Data type  
---|---|---  
`id` | The ID of a vertex | `STRING`  
`vertex_type` | The type of the vertex | `STRING`  
#### Example
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

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods#_to_vertex_set)`to_vertex_set()`
#### Syntax
`to_vertex_set( id_set, vertex_type)`
#### Description
Returns a vertex set from a set or bag of string IDs and a vertex type. If there are invalid IDs in the set, those IDs will be skipped and the response will contain a warning message. If the vertex type does not exist, the function will throw a run-time error.
#### Return type
`SET<VERTEX>`
#### Parameters
Parameter | Description | Data type  
---|---|---  
`id_set` | A set of vertex IDs | `SET<STRING>, BAG<STRING>`  
`vertex_type` | The type of the vertices | `STRING`  
#### Example
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


