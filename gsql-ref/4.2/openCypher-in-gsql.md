![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/)[Next](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/)
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
[Resources](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/)
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
  * [openCypher in GSQL](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/4.2/modules/openCypher-in-gsql/pages/index.adoc)
### Contents
  * [openCypher Features in GSQL](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_opencypher_features_in_gsql)
  * [Clauses](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_clauses)
  * [Operators](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_operators)
  * [Functions](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_functions)
  * [Expressions](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_expressions)
  * [openCypher Features Not Yet Supported](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_opencypher_features_not_yet_supported)
  * [Clauses](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_clauses_2)
  * [Operators](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_operators_2)
  * [Functions](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_functions_2)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_syntax)
  * [OpenCypher vs. GSQL Schema Models](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_key_differences_gsql_vs_opencypher)
  * [Example](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_example)


# openCypher in GSQL
### Contents
  * [openCypher Features in GSQL](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_opencypher_features_in_gsql)
  * [Clauses](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_clauses)
  * [Operators](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_operators)
  * [Functions](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_functions)
  * [Expressions](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_expressions)
  * [openCypher Features Not Yet Supported](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_opencypher_features_not_yet_supported)
  * [Clauses](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_clauses_2)
  * [Operators](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_operators_2)
  * [Functions](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_functions_2)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_syntax)
  * [OpenCypher vs. GSQL Schema Models](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_key_differences_gsql_vs_opencypher)
  * [Example](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_example)


openCypher is a popular open-source declarative query language for property graphs. More about openCypher can be found at [openCypher.org](http://opencypher.org).
TigerGraph supports the majority of openCypher features, embedded within its native GSQL language. This page lists the features currently [supported](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_opencypher_features_in_gsql) and features [not yet supported ](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_opencypher_features_not_yet_supported).
It also describes how the different [schema models in OpenCypher vs. GSQL](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_key_differences_gsql_vs_opencypher) affect some queries.
From version 4.1.2, certain restrictions on the `MATCH` and `WITH` clauses have been eliminated.  
---  
## [](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_opencypher_features_in_gsql)openCypher Features in GSQL
### [](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_clauses)Clauses
Clause | Description  
---|---  
DELETE | Delete graph elements — nodes and relationships. Any node to be deleted must also have all associated relationships explicitly deleted.  
DETACH DELETE | Writing Delete a node or set of nodes. All associated relationships will automatically be deleted.  
LIMIT | Reading sub-clause A sub-clause used to constrain the number of records in the output.  
MATCH | Reading Specify the patterns to search for in the database. See below for restrictions before version **4.1.2**.  
MANDATORY MATCH | Reading Specify the patterns to search for in the database, and fail if no match is found.  
OPTIONAL MATCH | Reading Specify the patterns to search for in the database while using nulls for missing parts of the pattern.  
ORDER BY [ASC[ENDING] DESC[ENDING]] | Reading sub-clause A sub-clause following  
RETURN or WITH | Specifying that the output should be sorted in either ascending (the default) or descending order.  
RETURN … [AS] | Projecting Defines what to include in the query result set.  
SKIP | Reading/Writing A sub-clause defining from which record to start including the records in the output.  
WHERE | Reading sub-clause A sub-clause used to add constraints to the patterns in a MATCH clause, or to filter the results of a WITH clause.  
WITH … [AS] | Projecting Allows query parts to be chained together, piping the results from one to be used as starting points or criteria in the next. See below for restrictions before version **4.1.2**.  
### [](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_operators)Operators
Operator | Description  
---|---  
% | Mathematical Modulo division  
* | Mathematical Multiplication  
+ | Mathematical Addition  
+ | String Concatenation  
+ | List Concatenation  
- | Mathematical Subtraction or unary minus  
. | General Property access  
/ | Mathematical Division  
< | Comparison Less than  
< = | Comparison Less than or equal to  
<> | Comparison Inequality  
= | Comparison Equality  
> | Comparison Greater than  
>= | Comparison Greater than or equal to  
AND | Boolean Conjunction  
CONTAINS | String comparison Case-sensitive inclusion search  
DISTINCT | General Duplicate removal  
ENDS WITH | String comparison Case-sensitive suffix search  
IN List | List element existence check  
IS NOT NULL | Comparison Non-null check  
IS NULL | Comparison null check  
NOT | Boolean Negation  
OR | Boolean Disjunction  
STARTS WITH | String comparison Case-sensitive prefix search  
XOR | Boolean Exclusive disjunction  
[ ] | General Subscript (dynamic property access)  
[ ] | List Subscript (accessing element(s) in a list)  
^ | Mathematical Exponentiation  
### [](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_functions)Functions
Operator | Value type | Description  
---|---|---  
abs() | Numeric | Returns the absolute value of a number.  
acos() | Numeric | Returns the arccosine of a number in radians.  
asin() | Numeric | Returns the arcsine of a number in radians.  
atan() | Numeric | Returns the arctangent of a number in radians.  
atan2() | Numeric | Returns the arctangent2 of a set of coordinates in radians.  
avg() | Numeric | Returns the average of a set of numeric values.  
ceil() | Numeric | eturns the smallest floating point number that is greater than or equal to a number and equal to a mathematical integer.  
coalesce() | Scalar | Returns the first non-null value in a list of expressions.  
cos() | Numeric | Returns the cosine of a number.  
cot() | Numeric | Returns the cotangent of a number.  
count() | Numeric | Returns the number of values or records.  
degrees() | Numeric | Converts radians to degrees.  
e() | Numeric | Returns the base of the natural logarithm, e.  
elementId() | Scalar | Returns the String id of a relationship or node.  
exp() | Numeric | Returns e^n, where e is the base of the natural logarithm, and n is the value of the argument expression.  
floor() | Numeric | Returns the largest floating point number that is less than or equal to a number and equal to a mathematical integer.  
head() | Scalar | Returns the first element in a list.  
id() | Scalar | Returns the id of a relationship or node.  
labels() | List | Returns a list containing the string representations for all the labels of a node.  
last() | Scalar | Returns the last element in a list.  
left() | String | Returns a string containing the specified number of leftmost characters of the original string.  
log() | Numeric | Returns the natural logarithm of a number.  
log10() | Numeric | Returns the common logarithm (base 10) of a number.  
lTrim() | String | Returns the original string with leading whitespace removed.  
max() | Numeric | Returns the maximum value in a set of values.  
min() | Numeric | Returns the minimum value in a set of values.  
pi() | Numeric | Returns the mathematical constant pi.  
radians() | Numeric | Converts degrees to radians.  
rand() | Numeric | Returns a random floating point number in the range from 0 (inclusive) to 1 (exclusive); i.e. [0, 1).  
range() | List | Returns a list comprising all integer values within a specified range.  
replace() | String | Returns a string in which all occurrences of a specified string in the original string have been replaced by another (specified) string.  
reverse() | String | Returns a string in which the order of all characters in the original string have been reversed.  
right() | String | Returns a string containing the specified number of rightmost characters of the original string.  
round() | Numeric | Returns the value of a number rounded to the nearest integer.  
rTrim() | String | Returns the original string with trailing whitespace removed.  
sign() | Numeric | Returns the signum of a number: 0 if the number is 0, -1 for any negative number, and 1 for any positive number.  
sin() | Numeric | Returns the sine of a number.  
size() | Numeric | Returns the number of items in a list. (When applied to a list)  
split() | List | Returns a list of strings resulting from the splitting of the original string around matches of the given delimiter.  
sqrt() | Numeric | Returns the square root of a number.  
stDev() | Numeric | Returns the standard deviation for the given value over a group for a sample of a population.  
stDevP() | Numeric | Returns the standard deviation for the given value over a group for an entire population  
substring() | String | Returns a substring of the original string, beginning with a 0-based index start and length.  
sum() | Numeric | Returns the sum of a set of numeric values.  
tail() | List | Returns all but the first element in a list.  
tan() | Numeric | Returns the tangent of a number.  
timestamp() | Scalar | Returns the difference, measured in milliseconds, between the current time and midnight, January 1, 1970 UTC.  
trim() | String | Returns the original string with leading and trailing whitespace removed.  
toLower() | String | Returns the original string in lowercase.  
toString() | String | Converts an integer, float or boolean value to a string.  
toUpper() | String | Returns the original string in uppercase.  
toBoolean() | Scalar | Converts a string value to a boolean value.  
toFloat() | Scalar | Converts an integer or string value to a floating point number.  
toInteger() | Scalar | Converts a floating point or string value to an integer value.  
type() | Scalar | Returns the string representation of the relationship type.  
### [](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_expressions)Expressions
Expression | Description  
---|---  
CASE | A generic conditional expression, similar to if/else statements available in other languages.  
## [](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_opencypher_features_not_yet_supported)openCypher Features Not Yet Supported
### [](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_clauses_2)Clauses
Clause | Description  
---|---  
CALL […YIELD] | Reading/Writing Invoke a procedure deployed in the database.  
CREATE | Writing create nodes and relationships.  
MERGE | Reading/Writing Ensures that a pattern exists in the graph. Either the pattern already exists, or it needs to be created.  
REMOVE | Writing Remove properties and labels from nodes and relationships.  
SET | Writing Update labels on nodes and properties on nodes and relationships.  
UNION | Set operations Combines the result of multiple queries. Duplicates are removed.  
UNION ALL | Set operations Combines the result of multiple queries. Duplicates are retained.  
UNWIND … [AS] | Projecting Expands a list into a sequence of records.  
### [](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_operators_2)Operators
N/A
### [](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_functions_2)Functions
Function | Value Type | Description  
---|---|---  
collect() | Numeric | Returns a list containing the values returned by an expression.  
endNode() | Scalar | Returns the end node of a relationship.  
exists() | Boolean | Returns true if a match for the pattern exists in the graph, or if the specified property exists in the node, relationship or map.  
keys() | List | Returns a list containing the string representations for all the property names of a node, relationship, or map.  
length() | Numeric | Returns the length of a path.  
nodes() | List | Returns a list containing all the nodes in a path.  
percentileCont() | Numeric | Returns the percentile of the given value over a group using linear interpolation.  
percentileDisc() | Numeric | Returns the percentile of the given value over a group using a rounding method.  
properties() | Map | Returns a map containing all the properties of a node or relationship.  
relationships() | List | Returns a list containing all the relationships in a path.  
reverse() | List | Returns a list in which the order of all elements in the original list have been reversed.  
size() of a pattern expression | Numeric | Returns the number of subgraphs matching the pattern expression.  
size() of a string | Numeric | Returns the size of a string.  
startNode() | Scalar | Returns the start node of a relationship.  
### [](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_syntax)Syntax
These were limitations before **4.1.2** – certain openCypher syntax were not supported:
  * Queries with a **WITH** clause that **does not** implicitly group by exactly one vertex variable.
    1. 0 vertex variables as group key
```
MATCH (u:User {name: "John"}) // find all users with the same friend count as John
WITH   u.friendCount AS fc  // note, u not included in group key list
MATCH (o:User {friendCount: fc})
…
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

    2. More than 1 vertex variables as group key
```
MATCH (u1) -[:communication]- (x) -[:communication]- (u2)
WITH   u1, u2, COUNT(x) // we support only u1 or only u2 in list
…
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * Queries introducing path variables
```
MATCH p = (u1) -[e1:communication]- (x) -[e2:communication]- (u2)	// p is path var
…
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * Queries whose **MATCH** pattern **does not** include at least one vertex variable from immediately preceding **WITH** clause.
```
MATCH (u:user) -[:communication]- (o)
WITH   u, …
MATCH (x) -[:communication]-(y)		// this pattern must refer to u
…
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * Queries with disconnected **MATCH** pattern fragments
```
MATCH (x:user), (y:user)
WHERE x.friendCount = y.friendCount
…
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * Pattern fragments (x:user) and (y:user) **are not** connected by edge traversal or by sharing vertex variables.


## [](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_key_differences_gsql_vs_opencypher)OpenCypher vs. GSQL Schema Models
GSQL, the language and storage engine, is strongly typed and **schema-first** :
  * Every vertex and edge belongs to a previously defined _type_.
  * Each type had a characteristics set of properties (attributes); there are no optional properties.


OpenCypher is **schema-optional** :
  * A vertex or edge _may_ have a _label_.
  * A label _may_ be associated with characteristic set of properties.
  * An individual vertex or edge could have additional properties.


This fundamental difference impacts how OpenCypher queries behave in each system.
### [](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_example)Example
Consider the following OpenCypher query:
```
MATCH (p)
RETURN p.firstName, p.year
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_how_gsql_opencypher_mode_interprets_this_query)How GSQL OpenCypher mode Interprets This Query
Since GSQL OpenCypher enforces a predefined schema, the query:
  * Only considers vertex types that contain both `firstName` and `year` attributes
  * Returns values only if both attributes exist in a given vertex type


If a vertex type does not have both attributes, it is ignored entirely.
#### [](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_how_opencypher_interprets_this_query)How OpenCypher Interprets This Query
OpenCypher does not enforce a schema, so the query:
  * Processes all vertex types, regardless of their attributes
  * Returns values for existing attributes but returns `NULL` for attributes that do not exist


#### [](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_importance)Key Considerations
For users migrating from OpenCypher to GSQL OpenCypher, it is important to understand that:
  * In GSQL, queries must align with the predefined schema.
  * Unlike OpenCypher, GSQL does not return NULL for missing attributes: if a vertex does not contain all required attributes, it is not included in the result.
  * A query attempting to access a non-existent attribute in GSQL may either return no results or be rejected if no matching vertex type exists.


By understanding this distinction, users can write more effective OpenCypher queries tailored to GSQL OpenCypher’s schema-first approach.
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


