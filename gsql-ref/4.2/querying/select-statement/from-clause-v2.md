![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2)[Next](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2)
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
[Resources](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2)
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
  * [From Clause (V2)](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/4.2/modules/querying/pages/select-statement/from-clause-v2.adoc)
### Contents
  * [FROM](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2#_from_clause)
  * [Path pattern](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2#_path_pattern)
  * [Source vertex set](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2#_source_vertex_set)
  * [Step vertex set](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2#_step_vertex_set)
  * [Path edge pattern](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2#_path_edge_pattern)
  * [Atomic edge pattern](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2#_atomic_edge_pattern)
  * [Disjunction pattern](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2#_disjunction_pattern)
  * [Pattern repetition](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2#_pattern_repetition)
  * [Pattern concatenation](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2#_pattern_concatenation)
  * [Conjunctive Pattern Matching](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2#_conjunctive_pattern_matching)
  * [Vertex and Edge Aliases](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2#_vertex_and_edge_aliases)


# FROM Clause (Syntax V2)
### Contents
  * [FROM](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2#_from_clause)
  * [Path pattern](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2#_path_pattern)
  * [Source vertex set](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2#_source_vertex_set)
  * [Step vertex set](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2#_step_vertex_set)
  * [Path edge pattern](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2#_path_edge_pattern)
  * [Atomic edge pattern](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2#_atomic_edge_pattern)
  * [Disjunction pattern](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2#_disjunction_pattern)
  * [Pattern repetition](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2#_pattern_repetition)
  * [Pattern concatenation](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2#_pattern_concatenation)
  * [Conjunctive Pattern Matching](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2#_conjunctive_pattern_matching)
  * [Vertex and Edge Aliases](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2#_vertex_and_edge_aliases)


The FROM clause in GSQL Syntax V2 is used to define path patterns for traversing the graph structure. A path pattern specifies how vertices and edges are connected and provides the basis for the query to traverse the graph. In V2, the FROM clause supports both traditional vertex-edge patterns and more advanced multi-hop patterns.
This page will focus on V2 syntax, which is an evolution of the V1 syntax, with improved flexibility and support for more complex graph traversals. While GSQL still supports the V1 syntax, we will describe the V2 style here, including examples of how to use path patterns and multiple path patterns for more complex graph queries.
## [](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2#_from_clause)`FROM`
`FROM` clause
```
fromClauseV1 := FROM step
fromClauseV2 := FROM stepV2 | pathPattern ["," pathPattern]*)
fromClause := fromClauseV1 | fromClauseV2
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

A hop or step consists of going from a starting set of vertices, crossing over a set of their edges, to an ending set of vertices. We typically use the names Source and Target for the starting and ending vertex sets: `Source -(Edges)→ Target`
## [](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2#_path_pattern)Path pattern
A path pattern specifies sets of vertex types and how they are connected by edge types.
A path pattern starts with a source vertex set, traverses through specified path edge patterns to another step vertex set. This is called a _hop_. From the other step vertex set, it can perform multiple hops and traverse to other step vertex sets.
Notice that a path pattern can be just a single source vertex set; the subsequent path edge pattern and step vertex sets are optional.
EBNF for path pattern
```
pathPattern := sourceVertexSet ["-" "(" pathEdgePattern ")" "-" stepVertexSet]*
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2#_source_vertex_set)Source vertex set
The source vertex set is the vertex set from which a path pattern starts. A source vertex set can be denoted by one of the following:
  * `_` or `ANY`, or omitted. If the source vertex type is omitted, you must give the source vertex set an [alias](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2#_vertex_and_edge_aliases).
  * Vertex type
  * A vertex set variable


Optionally, you can give a source vertex set an alias by appending the alias after a colon`:`. Although declaring an alias is optional, it is strongly recommended that you declare them. In the later clauses of the `SELECT` block , you can only refer to vertex sets in the `FROM` clause by their aliases.
EBNF for source vertex set
```
sourceVertexSet := [sourceVertexTypes] [":" vertexAlias]
sourceVertexTypes := "_" | ANY | "(" sourceVertexSetType ["|" sourceVertexSetType]* ")"
sourceVertexSetType := vertexType | vertexSetVariableName
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Belows are a few examples of valid source vertex sets in `SELECT` statements:
  * Vertex type
  * Any type
  * Vertex set


```
Result = SELECT src
  FROM Person:src -(<Likes_REVERSE)- (Comment|Post):tgt **(1)**
  WHERE src.first_name == "Viktor" AND src.last_name == "Akhiezer"
  ACCUM CASE
    WHEN tgt.type == "Comment" THEN
      src.@comment_cnt += 1
    WHEN tgt.type == "Post" THEN
      src.@post_cnt += 1
    END;
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | `Person` is a vertex type. `(Comment | POST)` combines two vertex types.  
---|---  
You can use `_` or `ANY` to represent any vertex types. You can also choose to omit the step vertex type altogether to represent any vertex type. If you choose to omit the type, you must give the step vertex set an alias.
```
Result = SELECT tgt
  FROM :s -(<Likes)- Person:tgt
  WHERE tgt.first_name == "Viktor" AND tgt.last_name == "Akhiezer"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

A source vertex set can also be represented by a vertex set variable.
```
CREATE QUERY count_friends_of_2 (VERTEX<Person> seed) FOR GRAPH Friend_Net {
  SumAccum<INT> @@num_friends = 0;
  seed_set = { seed };
  friends = SELECT v FROM seed_set:s -((Friend | Coworker):e)- :v
    ACCUM @@num_friends +=1;
  PRINT @@num_friends;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2#_step_vertex_set)Step vertex set
A vertex set that represents a step in a path pattern. Compared with [source vertex set](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2#_source_vertex_set), step vertex sets have more flexibility in how they are denoted. A step vertex set can be denoted by one of the following:
  * `_` or `ANY`, or omitted. If the step vertex type is omitted, you must give the step vertex set an alias.
  * Vertex type
  * A vertex set variable
  * A global accumulator


Optionally, you can give a source vertex set an alias by appending the alias after a colon`:`. Although declaring an alias is optional, TigerGraph strongly suggests that you declare them. In the later clauses of the `SELECT` block , you can only refer to vertex sets in the `FROM` clause by their aliases.
EBNF for step vertex set
```
stepVertexSet := [stepVertexTypes] [":" vertexAlias]
stepVertexTypes := atomicVertexType | "(" vertexSetType ["|" vertexSetType]* ")"
atomicVertexType := "_" | ANY | vertexSetType
vertexSetType := vertexType | vertexSetVariableName | globalAccumName
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Belows are a few examples of valid step vertex sets in `SELECT` statements:
  * Vertex type
  * Any type
  * Vertex set
  * Global accumulator


```
Result = SELECT tgt
  FROM Person:tgt -(<Likes_REVERSE)- (Comment|Post):src **(1)**
  WHERE tgt.firstName == "Viktor" AND tgt.lastName == "Akhiezer"
  ACCUM CASE
    WHEN src.type == "Comment" THEN
      tgt.@commentCnt += 1
    WHEN src.type == "Post" THEN
      tgt.@postCnt += 1
    END;
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | `Person` is a vertex type. `(Comment | POST)` combines two vertex types.  
---|---  
You can use `_` or `ANY` to represent any vertex types. You can also choose to omit the step vertex type altogether to represent any vertex type. If you choose to omit the type, you must give the step vertex set an alias.
```
Result = SELECT s
  FROM Person:s -(Likes>)- :tgt
  WHERE s.first_name == "Viktor" AND s.last_name == "Akhiezer"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

A step vertex set can also be represented by a vertex set variable.
```
CREATE QUERY count_friends_of_2 (VERTEX<Person> seed) FOR GRAPH Friend_Net
{
  SumAccum<INT> @@num_friends = 0;
  seed_set = { seed };
  friends = SELECT v FROM :s -((Friend | Coworker):e)- seed_set:v
   ACCUM @@num_friends +=1;
  PRINT @@num_friends;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

A step vertex set can be represented by a global accumulator of strings (the strings are vertex types). The accumulator must be of type `SetAccum`, `BagAccum` or `ListAccum`.
```
CREATE QUERY count_friends_of_2(STRING target_type) FOR GRAPH Friend_Net {
  SumAccum<INT> @@num_friends = 0;
  SetAccum<STRING> @@target_set;
  @@target_set += target_type;
  friends = SELECT s FROM :s -((Friend | Coworker):e)- @@target_set:v
   ACCUM @@num_friends +=1;
  PRINT @@num_friends;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2#_path_edge_pattern)Path edge pattern
The path edge pattern represents the relationship between a source vertex set to a step vertex set or from a step vertex set to the next step vertex set.
EBNF for path edge pattern
```
pathEdgePattern := atomicEdgePattern
         | "(" pathEdgePattern ")"
         | pathEdgePattern "." pathEdgePattern
         | disjPattern
         | starPattern
atomicEdgePattern := atomicEdgeType
    	    | atomicEdgeType ">"
    	    | "<" atomicEdgeType
atomicEdgeType := "_" | ANY | edgeSetType
disjPattern := atomicEdgePattern ("|" atomicEdgePattern)*
starPattern := ([atomicEdgePattern] | "(" disjPattern ")") "*" [starBounds]
starBounds := CONST_INT ".." CONST_INT
      | CONST_INT ".."
      | ".." CONST_INT
      | CONST_INT
```

A path edge pattern can represent one hop or repeated hops. A path edge pattern is denoted by `-()-`, where the relationship between vertex sets is specified between the parentheses.
### Atomic edge pattern
The most basic form for a path edge pattern is an atomic edge pattern. An atomic edge pattern can be one of the following:
  * `_` or `ANY`.
  * An edge type.
  * A string parameter. The value of the parameter must be an edge type and can be provided at runtime. You do not need to specify a direction when using a string parameter to specify the edge type.
  * A global `SetAccum` accumulator of strings. Each string is the name of an edge type.


If the edge is directed, an atomic edge pattern has either a left pointer `<` on the left or a right pointer `>` on the right to indicate edge direction. If the edge is undirected, the atomic edge pattern does not have a pointer. Suppose we have 3 edge types or parameters called A, B, C.
  * `A>` is a rightward facing A edge
  * `<B` is a leftward facing B edge
  * C is an undirected C edge. If C is actually a directed edge type, then there is no match.


For example:
  * `-(STUDY_AT>)-` refers to forward traversal of the directed edge type `STUDY_AT`.
  * `-(<STUDY_AT)-` refers to backward traversal of the directed edge type `STUDY_AT`.
    * This means that the right side of `-(<STUDY_AT)-` is expected to have the same type as the left side of `-(STUDY_AT>)-`.
  * `-(KNOWS)-` refers to forward traversal of the undirected `KNOWS`.
  * `-(_>)-` refers to forward traversal of any directed edge types.
  * `-(_)-` refers to forward traversal of any undirected edge types.
  * `-(<_)-` refers to backward traversal of any directed edge types.


### Disjunction pattern
Pattern disjunction allows a path edge pattern to indicate an `OR` relationship between two or more atomic patterns. If an edge matches any of the atomic patterns, the edge matches the path edge pattern.
EBNF for disjunction pattern
```
disjPattern := atomicEdgePattern ("|" atomicEdgePattern)*
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

For example:
  * `-(KNOWS|STUDY_AT>)-` refers to traversing an undirected `KNOWS` edge or a directed `STUDY_AT` edge.
  * `-(KNOWS|_>)-` refers to traversing an undirected `KNOWS` edge or any directed edge from left to right.


### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2#_pattern_repetition)Pattern repetition
The Kleene star`*` and `min..max` range specifiers repeat an edge pattern for a specified number of times. The range specifiers must be integers and must be constants. See [Repeating a 1-Hop Pattern](https://docs.tigergraph.com/gsql-ref/4.2/tutorials/pattern-matching/repeating-a-pattern) for a tutorial on how to use pattern repetition in a path edge pattern.
EBNF for star pattern
```
starPattern := ([atomicEdgePattern] | "(" disjPattern ")") "*" [starBounds]
starBounds := CONST_INT ".." CONST_INT
      | CONST_INT ".."
      | ".." CONST_INT
      | CONST_INT
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * Add `*` to the end of a pattern to have the star pattern match all paths where the edge pattern occurs one or more times.
    * For example, `Person:s - (Friendship*) - Person` matches all paths between two `Person` vertices connected by any number of `Friendship` edges.
    * The vertices in the middle do not need to be `Person` vertices. For example, a path like `person1 -(Friendship)- dog1 - (Friendship) - person2` matches the star pattern.
  * Add `*` to the end of a pattern, and then a number after the star to have the star pattern match paths where the edge pattern occurs for the specified number of times.
    * For example, `Person:s - (Friendship*2) - Person` matches all paths between two `Person` vertices connected by exactly two `Friendship` edges. The vertices in the middle do not need to be `Person` vertices.
  * Add `*` to the end of a pattern, and then a range after the star (`*x..y`) to have the star pattern match all paths where the edge pattern occurs as many times as within the specified range.
    * For example, `Employee:s - (Works_For>*2..4) - Employee` matches all paths between two `Employee` vertices with 2 - 4 right-directed `Works_For` edges. The vertices in the middle do not need to be `Person` vertices.


### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2#_pattern_concatenation)Pattern concatenation
The dot operator`.` means concatenate the two edge patterns into one. The vertex joining the two edges is omitted from the syntax. The dot operator is a shorthand, when you don’t care about the type of that intermediate vertex. `(A>.<B.C)` means a series of 3 edges, having the specified types and directions.
For example, the following `FROM` clauses produce the same source and target vertex sets. While the second `FROM` clause is more concise, it does not give you access to the intermediate vertex and edge sets.
```
SELECT x
FROM X:x -(E2>:e2)- Y:y -(<E3:e3)- Z:z -(E4:e4)- U:u; **(1)**

SELECT u
FROM X:x -(E2>.<E3.E4)- U:u; **(2)**
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | This `FROM` clauses uses a longer pattern, but gives you access to `y`, `e2`, `z` and `e4`.  
---|---  
**2** | This `FROM` clauses is more concise than the first `FROM` clause, but does not give you access to the intermediate vertex and edge sets.  
### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2#_conjunctive_pattern_matching)Conjunctive Pattern Matching
The optional repeating phrase `["," pathPattern]*` allows you to have multiple path patterns. They form a conjunction, meaning all of them must be satisfied in order to have a valid match result. See [Conjunctive Pattern Matching (Beta)](https://docs.tigergraph.com/gsql-ref/4.2/tutorials/pattern-matching/adv/conjunctive-pattern-matching) for more details.
```
fromClause := FROM (step | stepV2 | pathPattern ["," pathPattern]*)
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Each step pattern or path pattern forms a match table, one row per matching path in the graph. Each vertex alias or edge alias is one column in the table. When we have a conjunctive path, each path must share at least one vertex alias with another path. This enables the two path sets (and match tables) to be joined. Formally, we make the natural join of the two tables.
## [](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/from-clause-v2#_vertex_and_edge_aliases)Vertex and Edge Aliases
Vertex and edge _aliases_ are declared within the `FROM` clause of a `SELECT` block, by using the colon `:`, followed by the alias name. Aliases can be accessed anywhere within the same `SELECT` block. They are used to reference a single selected vertex or edge of a set. It is through the vertex or edge aliases that the attributes of these vertices or edges can be accessed.
For example, the following code snippets show two different `SELECT` statements. The first `SELECT` statement starts from a vertex set called `allVertices`, and the vertex alias name `v` can access each individual vertex from `allVertices`. The second `SELECT` statement selects a set of edges.It can use the vertex alias `s` to reference the source vertices, or the alias `t` to reference the target vertices.
Vertex variables
```
results = SELECT v FROM all_vertices:v;
results = SELECT t FROM all_vertices:s -()- :t;
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The following example shows an edge-based `SELECT` statement, declaring aliases for all three parts of the edge. In the `ACCUM` clause, the `e` and `t` aliases are assigned to local vertex and edge variables.
Edge variables
```
results = SELECT v
  FROM all_vertices:s -(:e)- :t
  ACCUM VERTEX v = t, EDGE eg = e;
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

We strongly suggest that an alias should be declared with every vertex and edge in the FROM clause, as there are several functions and features only available to vertex and edge aliases.  
---  
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


