![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/4.2/tutorials/pattern-matching/adv/dml)[Next](https://docs.tigergraph.com/gsql-ref/4.2/tutorials/pattern-matching/adv/dml)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/4.2/tutorials/pattern-matching/adv/dml)
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
[Resources](https://docs.tigergraph.com/gsql-ref/4.2/tutorials/pattern-matching/adv/dml)
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
  * [Data Modification](https://docs.tigergraph.com/gsql-ref/4.2/tutorials/pattern-matching/adv/dml)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/4.2/modules/tutorials/pages/pattern-matching/adv/dml.adoc)
### Contents
  * [INSERT](https://docs.tigergraph.com/gsql-ref/4.2/tutorials/pattern-matching/adv/dml#_insert)
  * [UPDATE](https://docs.tigergraph.com/gsql-ref/4.2/tutorials/pattern-matching/adv/dml#_update)
  * [DELETE](https://docs.tigergraph.com/gsql-ref/4.2/tutorials/pattern-matching/adv/dml#_delete)


# Data Modification
### Contents
  * [INSERT](https://docs.tigergraph.com/gsql-ref/4.2/tutorials/pattern-matching/adv/dml#_insert)
  * [UPDATE](https://docs.tigergraph.com/gsql-ref/4.2/tutorials/pattern-matching/adv/dml#_update)
  * [DELETE](https://docs.tigergraph.com/gsql-ref/4.2/tutorials/pattern-matching/adv/dml#_delete)


Pattern Matching GSQL supports Insert, Update, and Delete operations. The syntax is identical to that in classic GSQL (v1), though the full range of data modification operations are not yet supported.
In general, data modification can be at two levels in GSQL:
  1. Top level. The statement does not need to be embedded within any other statement.
  2. Within a SELECT query statement. The FROM-WHERE clauses define a match table, and the data modification is performed based on the vertex and edge information in the match table. The GSQL specifications calls these within-SELECT statements **DML-sub statements**.


  * Insert, Update, and Delete currently work in compiled mode only (e.g., you must run INSTALL QUERY before RUN QUERY.) Data Modification in interpreted mode is not yet available.
  * SELECT queries with data modification may only have one POST-ACCUM clause.

  
---  
## [](https://docs.tigergraph.com/gsql-ref/4.2/tutorials/pattern-matching/adv/dml#_insert)INSERT
Pattern matching Insert is supported at both the top-level and within-SELECT levels, using the same syntax as in classic GSQL. You can insert vertices and edges.
  * For a top-level statement, use [INSERT INTO](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-modification-statements#_insert_into_statement),
  * Inside an ACCUM or POST-ACCUM clause, use the [DML-sub INSERT](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-modification-statements#_dml_sub_insert) statement.


**Example 1.** Create a Person vertex, whose name is Tiger Woods. Next, find Viktor’s favorite 2012 posts' authors, whose last name is prefixed with S. Finally, insert Knows edges connecting Tiger Woods with Viktor’s favorite authors.
```
USE GRAPH ldbc_snb
// find Viktor's 2012 favorite posts' authors, whose last_name begins with S.
INTERPRET QUERY() SYNTAX V2 {
 R = SELECT t
    FROM Person:s -(Likes>)- :msg -(Has_Creator>)- Person:t
    WHERE s.first_name == "Viktor" AND s.last_name == "Akhiezer"
     AND t.last_name LIKE "S%" AND year(msg.creation_date) == 2012;
 PRINT R[R.id, R.first_name, R.last_name];
}
// results
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"R": [
  {
   "v_id": "8796093025410",
   "attributes": {
    "R.first_name": "Priyanka",
    "R.id": 8796093025410,
    "R.last_name": "Singh"
   },
   "v_type": "Person"
  },
  {
   "v_id": "2199023260091",
   "attributes": {
    "R.first_name": "Janne",
    "R.id": 2199023260091,
    "R.last_name": "Seppala"
   },
   "v_type": "Person"
  },
  {
   "v_id": "15393162796846",
   "attributes": {
    "R.first_name": "Mario",
    "R.id": 15393162796846,
    "R.last_name": "Santos"
   },
   "v_type": "Person"
  }
 ]}]
}

// create a Person node, whose name is tiger,
// and connect this Person with above Victor's favorite authors
CREATE QUERY insert_edge_and_vertex () SYNTAX v2{
 // add a celebrity person node using INSERT INTO statement.
 INSERT INTO Person VALUES (100000000,"Tiger", "Woods", "m", _, _,_,_,_,_);
 R = SELECT t
    FROM Person:s -(Likes>)- :msg -(Has_Creator>)- Person:t
    WHERE s.first_name == "Viktor" AND s.last_name == "Akhiezer"
     AND t.last_name LIKE "S%" AND year(msg.creation_date) == 2012
    PER (s, t)
    ACCUM
      // add edges connecting "tiger" and t with a 6/1/2020 time stamp
      INSERT INTO Knows VALUES(100000000, t, to_datetime("2020-06-01"));
 PRINT R [R.id, R.first_name, R.last_name];
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

You can verify the result by running a simple built-in REST endpoint.
Check the inserted vertex.
Linux Shell
```
// check the inserted vertex
curl -X GET "http://localhost:14240/restpp/graph/ldbc_snb/vertices/Person/100000000" | jq .
// result
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
   "v_id": "100000000",
   "v_type": "Person",
   "attributes": {
    "id": 100000000,
    "first_name": "Tiger",
    "last_name": "Woods",
    "gender": "m",
    "birthday": "1970-01-01 00:00:00",
    "creation_date": "1970-01-01 00:00:00",
    "locationIP": "",
    "browserUsed": "",
    "speaks": [],
    "email": []
   }
  }
 ]
}
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Check the inserted edges.
Linux file
```
// check the inserted edges using tiger's id (100,000,000)
curl -X GET "http://localhost:14240/restpp/graph/ldbc_snb/edges/Person/100000000/Knows" | jq .
// result
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
   "e_type": "Knows",
   "directed": false,
   "from_id": "100000000",
   "from_type": "Person",
   "to_id": "8796093025410",
   "to_type": "Person",
   "attributes": {
    "creation_date": "2020-06-01 00:00:00"
   }
  },
  {
   "e_type": "Knows",
   "directed": false,
   "from_id": "100000000",
   "from_type": "Person",
   "to_id": "2199023260091",
   "to_type": "Person",
   "attributes": {
    "creation_date": "2020-06-01 00:00:00"
   }
  },
  {
   "e_type": "Knows",
   "directed": false,
   "from_id": "100000000",
   "from_type": "Person",
   "to_id": "15393162796846",
   "to_type": "Person",
   "attributes": {
    "creation_date": "2020-06-01 00:00:00"
   }
  }
 ]
}
// note you can use the vertex lookup API to verify the three connected authors. E.g
curl -X GET "http://localhost:14240/restpp/graph/ldbc_snb/vertices/Person/8796093025410" | jq .
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/4.2/tutorials/pattern-matching/adv/dml#_update)UPDATE
  * Top-level UPDATE statements are not yet supported in syntax v2. Vertex attributes can only be updated in POST-ACCUM clause, and edge attributes can only be updated in the ACCUM clause.
  * To perform within-SELECT updates, the FROM pattern can only be a _*single hop, fixed length*_ pattern.

  
---  
**Example 2.** For all Knows edges that connect Viktor Akhiezer and his friends whose last_name begins with "S", update the edge creation_date to "2020-10-01". Also, for the Person vertex (Tiger Woods) update the vertex’s creation_date and language he speaks.
```
CREATE QUERY update_knows_ts () SYNTAX v2 {
 // update the vertex tiger's attributes
 // creation_date and languages spoken in POST-ACCUM
 R = SELECT p
   FROM Person:p
   WHERE p.first_name == "Tiger" AND p.last_name == "Woods"
   POST-ACCUM
      // update simple base type attribute
      p.creation_date = to_datetime("2020-6-1"),
      // update collection-type attribute
      p.speaks = ("english", "golf");
 // DML-sub level, update Knows edge attribute "creation_date" in ACCUM
 R = SELECT t
    FROM Person:s-(Knows:e) -:t
    WHERE s.first_name == "Tiger" and s.last_name == "Woods"
    //update the Knows edge time stamp
    ACCUM e.creation_date = to_datetime("2020-10-01");
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

To verify the update, we can use REST calls.
Check Tiger Woods' creation_date and language he speaks.
Linux Shell
```
curl -X GET "http://localhost:14240/restpp/graph/ldbc_snb/vertices/Person/100000000" | jq .
// result
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
   "v_id": "100000000",
   "v_type": "Person",
   "attributes": {
    "id": 100000000,
    "first_name": "Tiger",
    "last_name": "Woods",
    "gender": "m",
    "birthday": "1970-01-01 00:00:00",
    "creation_date": "2020-06-01 00:00:00",
    "location_ip": "",
    "browser_used": "",
    "speaks": [
     "english",
     "golf"
    ],
    "email": []
   }
  }
 ]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Check Knows edges whose source is tiger woods.
Linux Shell
```
curl -X GET "http://localhost:14240/restpp/graph/ldbc_snb/edges/Person/100000000/Knows" | jq .
// result
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
   "e_type": "Knows",
   "directed": false,
   "from_id": "100000000",
   "from_type": "Person",
   "to_id": "8796093025410",
   "to_type": "Person",
   "attributes": {
    "creation_date": "2020-10-01 00:00:00"
   }
  },
  {
   "e_type": "Knows",
   "directed": false,
   "from_id": "100000000",
   "from_type": "Person",
   "to_id": "2199023260091",
   "to_type": "Person",
   "attributes": {
    "creation_date": "2020-10-01 00:00:00"
   }
  },
  {
   "e_type": "Knows",
   "directed": false,
   "from_id": "100000000",
   "from_type": "Person",
   "to_id": "15393162796846",
   "to_type": "Person",
   "attributes": {
    "creation_date": "2020-10-01 00:00:00"
   }
  }
 ]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/4.2/tutorials/pattern-matching/adv/dml#_delete)DELETE
You can use delete () function to delete edges and vertices in ACCUM and POST-ACCUM clauses.
  * Top-levels DELETE statements are not yet supported in SYNTAX v2.
  * Edges can only be deleted in the ACCUM clause.
  * For best performance, vertices should be deleted in the POST-ACCUM clause.
  * To perform within-SELECT deletes, the FROM pattern can only be a _*single hop, fixed length*_ pattern.

  
---  
**Example 3.** Delete vertex Tiger Woods and its Knows edges.
```
CREATE QUERY delete_edge_and_vertex () SYNTAX v2 {
 R = SELECT t
    FROM Person:s -(Knows:e)- Person:t
    WHERE s.first_name == "Tiger" AND s.last_name == "Woods"
    ACCUM
      //delete edges
      DELETE(e)
    POST-ACCUM DELETE(s); //delete src vertex

 PRINT R [R.id, R.first_name, R.last_name];
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

To verify the result, you can use built-in REST calls.
```
curl -X GET "http://localhost:14240/restpp/graph/ldbc_snb/vertices/Person/100000000" | jq .
#vertexresults
{
 "version": {
  "edition": "enterprise",
  "api": "v2",
  "schema": 0
 },
 "error": true,
 "message": "The input vertex id '100000000' is not a valid vertex id for vertex type = Person.",
 "code": "601"
}
curl -X GET "http://localhost:14240/restpp/graph/ldbc_snb/edges/Person/100000000/Knows" | jq .
#edge results
{
 "version": {
  "edition": "enterprise",
  "api": "v2",
  "schema": 0
 },
 "error": true,
 "message": "The input source_vertex_id '100000000' is not a valid vertex id for vertex type = Person.",
 "code": "601"
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


