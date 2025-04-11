![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements)[Next](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements)
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
[Resources](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements)
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
  * [Declaration and Assignment Statements](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/4.2/modules/querying/pages/declaration-and-assignment-statements.adoc)
### Contents
  * [Variable scopes](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_variable_scopes)
  * [Block scoping](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_block_scoping)
  * [Global scoping](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_global_scoping)
  * [Declaration Statements](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_declaration_statements)
  * [Accumulators](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_accumulators)
  * [Base type variables](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_base_type_variables)
  * [Local base type variables](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_local_base_type_variables)
  * [Local container variable](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_local_container_variable)
  * [Local tuple variable](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_local_tuple_variable)
  * [Vertex set variables](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_vertex_set_variables)
  * [FILE objects](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_file_objects)
  * [Assignment and Accumulate Statements](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_assignment_and_accumulate_statements)
  * [Restrictions on Assignment Statements](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_restrictions_on_assignment_statements)
  * [LOADACCUM Statement](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_loadaccum_statement)
  * [Function Call Statements](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_function_call_statements)
  * [Clear Collection Accumulators](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_clear_collection_accumulators)


# Declaration and Assignment Statements
### Contents
  * [Variable scopes](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_variable_scopes)
  * [Block scoping](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_block_scoping)
  * [Global scoping](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_global_scoping)
  * [Declaration Statements](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_declaration_statements)
  * [Accumulators](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_accumulators)
  * [Base type variables](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_base_type_variables)
  * [Local base type variables](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_local_base_type_variables)
  * [Local container variable](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_local_container_variable)
  * [Local tuple variable](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_local_tuple_variable)
  * [Vertex set variables](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_vertex_set_variables)
  * [FILE objects](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_file_objects)
  * [Assignment and Accumulate Statements](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_assignment_and_accumulate_statements)
  * [Restrictions on Assignment Statements](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_restrictions_on_assignment_statements)
  * [LOADACCUM Statement](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_loadaccum_statement)
  * [Function Call Statements](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_function_call_statements)
  * [Clear Collection Accumulators](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_clear_collection_accumulators)


In GSQL, different types of variables and objects follow different rules when it comes to variable declaration and assignment. This section discusses the different types of declaration and assignment statements and covers the following subset of the EBNF syntax:
EBNF for declaration and assignment
```
## Declarations ##
accumDeclStmt :=
     accumType localAccumName ["=" constant]
          ["," localASccumName ["=" constant]]*
    | accumType globaAccumName ["=" constant]
          ["," GlobalAccumName ["=" constant]]*
localAccumName := "@"accumName;
globalAccumName := "@@"accumName;
baseDeclStmt  := baseType name ["=" constant] ["," name ["=" constant]]*
fileDeclStmt := FILE fileVar "(" filePath ")"
fileVar := name
localVarDeclStmt := baseType varName "=" expr
vSetVarDeclStmt := vertexSetName ["(" vertexType ")"] "=" (seedSet | simpleSet | selectBlock)
simpleSet := vertexSetName
      | "(" simpleSet ")"
      | simpleSet (UNION | INTERSECT | MINUS) simpleSet
seedSet := "{" [seed ["," seed ]*] "}"
seed := '_'
   | ANY
   | vertexSetName
   | globalAccumName
   | vertexType ".*"
   | paramName
   | "SelectVertex" selectVertParams
   | vertexVarName
selectVertParams := "(" filePath "," columnId "," (columnId | name) ","
     stringLiteral "," (TRUE | FALSE) ")" ["." FILTER "(" condition ")"]
columnId := "$" (integer | stringLiteral)
## Assignment Statements ##
assignStmt := name "=" expr
      | name "." attrName "=" expr
attrAccumStmt := name "." attrName "+=" expr
lAccumAssignStmt := vertexAlias "." localAccumName ("+="| "=") expr
gAccumAssignStmt := globalAccumName ("+=" | "=") expr
loadAccumStmt := globalAccumName "=" "{" LOADACCUM loadAccumParams
                 ["," LOADACCUM loadAccumParams]* "}"
loadAccumParams := "(" filePath "," columnId ["," columnId]* ","
     stringLiteral "," (TRUE | FALSE) ")" ["." FILTER "(" condition ")"]
## Function Call Statement ##
funcCallStmt := name ["<" type ["," type]* ">"] "(" [argList] ")"
       | globaAccumName ("." funcName "(" [argList] ")")+
       | "reset_collection_accum" "(" accumName ")"
argList := expr ["," expr]*
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_variable_scopes)Variable scopes
Different types of variable declarations use different scoping rules. There are two types of scoping rules in a GSQL query:
  * [Block scoping](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_block_scoping)
  * [Global scoping](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_global_scoping)


### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_block_scoping)Block scoping
In GSQL, curly brackets, as well as `IF .. THEN`, `ELSE`, `WHILE ... DO`, `FOREACH ... DO` statements create a block. A `SELECT` statement also creates a block.A block-scoped variable declared inside a block scope is only accessible inside that scope.
Additionally, variables declared in a lower scope can use the same name as a variable already declared in a higher scope.The lower-scope declaration will take precedence over the higher-scope declaration until the end of the lower scope.
The following types of variables use block scoping:
  * [Accumulators](https://docs.tigergraph.com/gsql-ref/4.2/querying/accumulators)
  * [Base type variables](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_base_type_variables)
  * [Local base type variables](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_local_base_type_variables)
  * [File objects](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_file_objects)
  * [Vertex or edge aliases](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/#_vertex_and_edge_aliases)


### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_global_scoping)Global scoping
A global-scoped variable is always accessible anywhere in the query once it has been declared regardless of where it is declared. One also cannot declare another variable with the same name as a global-scoped variable that has already been declared.
The following types of variables use global scoping:
  * [Vertex set variables](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_vertex_set_variables)


## [](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_declaration_statements)Declaration Statements
There are six types of variable declarations in a GSQL query:
  * Accumulator
  * Base type variable
  * Local base type variable
  * Vertex set
  * File object
  * Vertex or edge aliases


The first five types each have their own declaration statement syntax and are covered in this section. Aliases are declared implicitly in a `SELECT` statement.
### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_accumulators)Accumulators
Accumulator declaration is discussed in [Accumulators](https://docs.tigergraph.com/gsql-ref/4.2/querying/accumulators#_declaration_of_accumulators).
### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_base_type_variables)Base type variables
In a GSQL query body, variables holding values of types `INT`, `UINT`, `FLOAT`, `DOUBLE`, `BOOL`, `STRING`, `DATETIME`, `VERTEX`, `EDGE`, `JSONOBJECT` and `JSONARRAY` are called base type variables. The scope of a base type variable is from the point of declaration until the end of the block where its declaration took place.
EBNF for base type variable declaration
```
baseVarDeclStmt  := baseType name ["=" expr]["," name ["=" expr]]*
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

A base type variable can be declared and accessed anywhere in the query. To declare a base type variable, specify the data type and the variable name. Optionally, you can initialize the variable by assigning it a value with the assignment operator (`=`) and the desired value on the right side. You can declare multiple variables of the same type in a single declaration statement.
```
CREATE QUERY base_type_variable() {
  STRING a;
  DOUBLE num1, num2 = 3.2;
  INT year = 2020, month = 12, day = 115;
  INT b = rand(5);
  PRINT a, b, num1;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

When a base type variable is assigned a new value in an `ACCUM` or `POST-ACCUM` clause, the change will not take place until exiting the clause. Therefore, if there are multiple assignment statements for the same base type variable in an `ACCUM` or `POST-ACCUM` clause, only the last one will take effect.
For example, in the following query, a base type variable is assigned a new value in the `ACCUM` clause, but the change will not take place until the clause ends. Therefore, the accumulator will not receive the value and will hold a value of 0 at the end of the query.
```
CREATE QUERY base_type_variable() FOR GRAPH Social_Net {
  MaxAccum<INT> @@max_date_glob;
  DATETIME dt;
  all_user = {Person.*};
  all_user = SELECT src
    FROM all_user:src - (Liked>:e) - Post
    ACCUM
      dt = e.action_time,      // dt isn't updated yet
      @@max_date_glob += datetime_to_epoch(dt);
  PRINT @@max_date_glob, dt; // @@max_date_glob will be 0
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_local_base_type_variables)Local base type variables
Base type variables declared in a DML-sub statement, such as in a statement inside an `ACCUM`, `POST-ACCUM`, or `UPDATE SET` clause, are called _local_ _base type variables_.
Local base type variables are block-scoped and are accessible in the block where they are declared only. Within a local base type variable’s scope, you cannot declare another local base type variable, local container variable, or local tuple variable with the same name at the same level. However, you can declare a local base type variable or local container variable with the same name at a lower level, where the lower-level declaration will take precedence over the previous declaration.
In a `POST-ACCUM` clause, each local base type variable may only be used in source vertex statements or only in target vertex statements, not both.
EBNF for local base type variable declaration and initialization
```
localVarDeclStmt := baseType varName "=" expr
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Local base type variables are not subject to the assignment restrictions of regular base type variables. Their values can be updated inside an `ACCUM` or `POST-ACCUM` clause and the change will take place immediately.
#### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_example)Example:
  * Query
  * Result


Base type variable declaration in DML statements
```
CREATE QUERY local_variable(VERTEX<Person> m1) FOR GRAPH Social_Net {
  // An example showing a local base type variable succeeds
  // where a base type variable fails
  MaxAccum<INT> @@max_date, @@max_date_glob;
  DATETIME dt_glob;
  all_user = {Person.*};
  all_user = SELECT src
    FROM all_user:src - (Liked>:e) - Post
    ACCUM
      DATETIME dt = e.action_time,   // Declare and assign local dt
      dt_glob = e.action_time,     // dt_glob isn't updated yet
      @@max_date   += datetime_to_epoch(dt),
      @@max_date_glob += datetime_to_epoch(dt_glob);
  PRINT @@max_date, @@max_date_glob, dt_glob; // @@max_date_glob will be 0
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

localVariable Query Results
```
GSQL > RUN QUERY local_variable("person1")
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{
  "@@max_date": 1263618953,
  "dt_glob": "2010-01-16 05:15:53",
  "@@max_date_glob": 0
 }]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_local_container_variable)Local container variable
Variables declared inside a DML-block storing container type values are called _local container type variables_. Their values can be updated inside an `ACCUM` or `POST-ACCUM` clause and the change will take place immediately.
Local container variables can store values of a specified type. The following types are allowed:
Container type | Element type  
---|---  
`SET` | `INT`, `UINT`, `DOUBLE`, `FLOAT`, `STRING`, `JSONOBJECT`, `JSONARRAY`,`BOOL` `EDGE`, `DATETIME`, tuple  
`BAG` | `INT`, `UINT`, `DOUBLE`, `FLOAT`, `STRING`, `JSONOBJECT`, `JSONARRAY`,`BOOL`, `VERTEX` `EDGE`, `DATETIME`, tuple  
`LIST` | `INT`, `UINT`, `DOUBLE`, `FLOAT`, `STRING`, `JSONOBJECT`, `JSONARRAY`,`BOOL`, `VERTEX` `EDGE`, `DATETIME`, `ListAccum` (Up to 3 levels of nesting), tuple  
`MAP` | 
  * Key types: `INT`, `UINT`, `DOUBLE`, `FLOAT`, `STRING`, `JSONOBJECT`, `JSONARRAY`,`BOOL`, `VERTEX` `EDGE`, `DATETIME`, tuple
  * Value types: `INT`, `UINT`, `DOUBLE`, `FLOAT`, `STRING`, `JSONOBJECT`, `JSONARRAY`,`BOOL`, `VERTEX` `EDGE`, `DATETIME`, tuple, any accumulator type except for `HeapAccum`

  
You must declare which type the container variable will be storing when you declare the container variable.
  * EBNF
  * Example


```
localContainerDeclStmt := containerType "<" type ">" varName "=" expr
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
SET<INT> set1 = (1, 2, 3) **(1)**
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | The declaration can only take place in a DML block.  
---|---  
Local container variables are block-scoped and are accessible in the block where they are declared only. Within a local container variable’s scope, you cannot declare another local container variable, local tuple variable, or local base type variable with the same name at the same level. However, you can declare a variable with the same name at a lower level, where the lower-level declaration will override the previous declaration.
In a `POST-ACCUM` clause, each local container variable may only be used in source vertex statements or only in target vertex statements, not both.
#### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_query_example)Query example
In the following example, the `SELECT` statement in the main query declares three local container variables, each containing:
  * A base type
  * A user-defined tuple
  * An anonymous tuple


  * Main query
  * Subquery 1
  * Subquery 2


```
CREATE QUERY test() FOR GRAPH POC_Graph {
  TYPEDEF TUPLE<INT i, STRING s> Main_Tuple;
  SumAccum<INT> @@A;
  SetAccum<Main_Tuple> @@set_acc;
  SetAccum<Main_Tuple> @@set_acc2;
  L0 = { Person.* };
  L1 = SELECT p
    FROM L0:p
    ACCUM
    // Local container with base type
    List<INT> a = sub_query1(p),
    FOREACH e IN a DO
     @@A += e,
    // user defined tuple
    Set<Main_Tuple> set_A = sub_query2(p)
    @@set_acc += set_A,
    // anonymous tuple(define signature of tuple in declaration)
    Set<tuple<INT, STRING>> set_B = sub_query2(p),
    @@set_acc2 += set_B
   end;
 print @@A;
 print @@set_acc;
 print @@set_acc2;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
CREATE QUERY sub_query1 (VERTEX node) FOR GRAPH POC_Graph
returns(ListAccum<int>)
{
  ListAccum<INT> @@res;
  Start = { node };
  Result = select t from Start:t
  Accum @@res += 1;
  return @@res;
}
```

```
CREATE QUERY sub_query2 (VERTEX node) FOR GRAPH POC_Graph
RETURNS (SetAccum<TUPLE<INT, STRING>>){
  TYPEDEF TUPLE<INT i, STRING s> Sub_Tuple;
  SetAccum<Sub_Tuple> @@res;
  v_set = { Person.* };
  Result1 = SELECT p FROM v_set:p
    WHERE p.name == "Charlie"
    ACCUM @@res += Sub_Tuple(-1, "hello");
  RETURN @@res;
}
```

### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_local_tuple_variable)Local tuple variable
Variables declared inside a DML-block storing tuple values are called _local tuple variables_. The value of a local tuple variable is assigned at declaration. The value of a local tuple variable can be updated inside an `ACCUM` or `POST-ACCUM` clause and the change will take place immediately.
Local tuple variables are block-scoped and are accessible in the block where they are declared only. Within a local tuple variable’s scope, you cannot declare another local tuple variable, local container variable, or local base type variable with the same name at the same level. However, you can declare a variable with the same name at a lower level, where the lower-level declaration will override the previous declaration.
You can declare tuple variables of defined types and anonymous types.
#### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_syntax)Syntax
```
assignDeclLocalTuple := (tupleTypeName | anonymousTupleType) localTupleVal = expr
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_example_2)Example
```
CREATE QUERY test_udf() FOR GRAPH POC_Graph {
   TYPEDEF TUPLE<INT i, STRING s> Main_Tuple;
   SetAccum<Main_Tuple> @@set_acc;
   SetAccum<Main_Tuple> @@set_acc2;
  L0 = { Person.* };
  L1 = SELECT p
    FROM L0:p
    WHERE p.name == "Charlie"
    ACCUM
      Main_Tuple a = Main_Tuple(1, "well"), **(1)**
      @@set_acc += a,
      TUPLE<INT, STRING> b = Main_Tuple(2, "good"), **(2)**
      @@set_acc2 += b;
 PRINT @@set_acc;
 PRINT @@set_acc2;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | This statement defines a local tuple variable `a` with a defined tuple type.  
---|---  
**2** | This statement defines a local tuple variable `b` with an anonymous tuple type. Beside using another tuple type, you can also return an anonymous tuple from a [subquery](https://docs.tigergraph.com/gsql-ref/4.2/querying/operators-and-expressions#_subqueries) to assign value to the local tuple variable.  
### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_vertex_set_variables)Vertex set variables
Variables that contain a set of one or more vertices are called vertex set variables. Vertex set variables play a special role within GSQL queries. They are used for both the input and output of `SELECT` statements.
In Syntax V1, before the first `SELECT` statement in a query, a vertex set variable must be declared and initialized. This initial vertex set is called the _seed set_. The current default syntax - Syntax V2 - no longer has this requirement.   
---  
Vertex set variables are global-scoped. They are also the only type of variable that isn’t explicitly typed during declaration. To declare a vertex set variable, assign an initial set of vertices to the variable name.
EBNF for Vertex Set Variable Declaration
```
vSetVarDeclStmt := vertexSetName ["(" vertexType ")"] "=" (seedSet | simpleSet | selectBlock)
simpleSet := vertexSetName
   | "(" simpleSet ")"
   | simpleSet (UNION | INTERSECT | MINUS) simpleSet
seedSet := "{" [seed ["," seed ]*] "}"
seed := '_'
   | ANY
   | vertexSetName
   | globalAccumName
   | vertexType ".*"
   | paramName
   | "SelectVertex" selectVertParams
   | vertexVarName
selectVertParams := "(" filePath "," columnId "," (columnId | name) ","
   stringLiteral "," (TRUE | FALSE) ")" ["." FILTER "(" condition ")"]
columnId := "$" (integer | stringLiteral)
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The query below lists all ways of assigning a vertex set variable an initial set of vertices (that is, forming a seed set).
  * A vertex parameter, untyped or typed, enclosed in curly brackets
  * A vertex set parameter, untyped or typed
  * A global `SetAccum<VERTEX>` accumulator, untyped or typed
  * A vertex type followed by `.*` to indicate all vertices of that type, optionally enclosed in curly brackets.
  * `_` or `ANY` to indicate all vertices, optionally enclosed in curly brackets.
  * A list of vertex IDs in an external file
  * Copy of another vertex set
  * A combination of individual vertices, vertex set parameters, or base type variables, enclosed in curly brackets
  * Union of vertex set variables
  * A vertex variable enclosed in curly brackets


Vertex set example
```
CREATE QUERY seed_set_example (VERTEX v1, VERTEX<Person> v2, SET<VERTEX> v3, SET<VERTEX<Person>> v4) FOR GRAPH Social_Net {
  SetAccum<VERTEX> @@test_set;
  SetAccum<VERTEX<Person>> @@test_set2;
  VERTEX v5 = to_vertex("person1", "Person"); // vertex variable
  S1 = { v1 };  // Untyped vertex parameter enclosed in curly brackets
  S2 = { v2 };  // Typed vertex parameter enclosed in curly brackets
  S3 = v3;            // Untyped vertex set parameter
  S4 = v4;            // Typed vertex set parameter
  S5 = @@test_set;        // Untyped global set accumulator
  S6 = @@test_set2;        // Typed global set accumulator
  S7 = ANY;           // All vertices
  S8 = Person.*;         // All person vertices
  S9 = {_};           // Equivalent to ANY, braces are optional
  S10 = SelectVertex("absolute_path_to_input_file", $0, Post, ",", false); **(1)**
  S11 = S1;           // copy of another vertex set
  S12 = {@@test_set, v2, v3};   // Individual vertex: v2
                 // Vertex set parameter: v3
                 // Global accumulator: @@test_set
                 // Inside curly brackets cannot be put another
                 // Seedset, e.g., S1
  S13 = S11 UNION S12;      // But we can use UNION to combine S1
  S14 = { v5 };         // Vertex variable enclosed in curly brackets
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | See [SelectVertex()](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/vertex-methods#_selectvertex).  
---|---  
When declaring a vertex set variable, you may opt to specify the vertex set type for the vertex set variable by enclosing the type in parentheses after the variable name.
If the vertex set variable set type is not specified explicitly, GSQL determines the type implicitly by the vertex set value. The type can be `ANY`, `_` (equivalent to `ANY`), or any explicit vertex type(s).
#### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_assignment)Assignment
After a vertex set variable is declared, the vertex type of the vertex set variable is immutable. Every assignment (e.g. `SELECT` statement) to this vertex set variable must match the type. The following is an example in which we must declare the vertex set variable type.
Vertex set variable type
```
CREATE QUERY vertex_set_variable_type_example (VERTEX<Person> m1) FOR GRAPH Social_Net {
  INT ite = 0;
  S (ANY) = {m1};  // ANY is necessary
  WHILE ite < 5 DO
    S = SELECT t
      FROM S:s - (ANY:e) - ANY:t;
    ite = ite + 1;
  END;
  PRINT S;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

In the above example, the query returns the set of vertices after a 5-step traversal from the input `person` vertex. Because the type of vertex parameter `m1` is `person`, the GSQL engine will implicitly assign `S` to be `person` type, making it unnecessary to explicitly define the vertex type of `S`. However, if `S` is assigned to `person` type, the `SELECT` statement inside the `WHILE` loop causes a type-checking error, because the `SELECT` block will generate all connected vertices, including non-person vertices. Therefore, `S` must be declared as an ANY-type vertex set variable.
### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_file_objects)`FILE` objects
A `FILE` object is a sequential text storage object, associated with a text file on the local machine.
EBNF for FILE object declaration
```
fileDeclStmt := FILE fileVar "(" filePath ")"
fileVar := name
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

When a `FILE` object is declared, associated with a particular text file, any existing content in the text file will be erased. During the execution of the query, content written to or printed to the `FILE` object will be appended to the `FILE` object. When the query where the `FILE` object is declared finishes running, the content of the `FILE` object is saved to the text file.
#### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_example_3)Example
File object query example
```
CREATE QUERY get_US_worker_interests (STRING file_location) FOR GRAPH Work_Net {
  // Declare FILE object f1
  FILE f1 (file_location);
  // Initialize a seed set of all person vertices
  P = {Person.*};
  PRINT "header" TO_CSV f1;
  // Select workers located in the US and print their interests onto
  // the FILE object
  US_workers = SELECT v FROM P:v
    WHERE v.location_id == "us"
    ACCUM f1.println(v.id, v.interest_list);
  PRINT "footer" TO_CSV f1;
}
INSTALL QUERY get_US_worker_interests
RUN QUERY get_US_worker_interests("/home/tigergraph/fileEx.txt")
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_assignment_and_accumulate_statements)Assignment and Accumulate Statements
Assignment statements are used to set or update the value of a variable after it has been declared. This applies to base type variables, vertex set variables, and accumulators. Accumulators also have the special += accumulate statement, which was discussed in the Accumulator section. Assignment statements can use expressions to define the new value of the variable.
EBNF for Assignment Statements
```
## Assignment Statement ##
assignStmt := name "=" expr     # baseType variable, vertex set variable
      | name "." name "=" expr   # attribute of a vertex or edge
attrAccumStmt := name "." attrName "+=" expr
lAccumAssignStmt := vertexAlias "." localAccumName ("+="| "=") expr
gAccumAssignStmt := globalAccumName ("+=" | "=") expr
loadAccumStmt := globalAccumName "=" "{" "LOADACCUM" loadAccumParam
                 ["," "LOADACCUM" loadAccumParams]* "}"
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Vertex and edge (non-accumulator) attributes can use the += operator in an ACCUM or POST-ACCUM clause to perform parallel accumulation. ```
attrAccumStmt := name "."attrName "+=" exprebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!
```
  
---  
### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_restrictions_on_assignment_statements)Restrictions on Assignment Statements
In general, assignment statements can take place anywhere after the variable has been declared. However, there are some restrictions. These restrictions apply to "inner level" statements which are within the body of a higher-level statement:
  * The `ACCUM` or `POST-ACCUM` clause of a `SELECT` statement
  * The `SET` clause of an `UPDATE` statement
  * The body of a `FOREACH` statement


  * Global accumulator assignment is not permitted within the body of `SELECT` or `UPDATE` statements
  * Base type variable assignment is permitted in `ACCUM` or `POST-ACCUM` clauses, but the change in value will not take place until exiting the clause. Therefore, if there are multiple assignment statements for the same variable, only the final one will take effect.
  * Vertex attribute assignment is not permitted in an `ACCUM` clause. However, edge attribute assignment is permitted. This is because the `ACCUM` clause iterates over an edge set.
  * There are additional restrictions within `FOREACH` loops for the loop variable. See the Data Modification section.

  
---  
### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_loadaccum_statement)`LOADACCUM` Statement
```
loadAccumStmt := globalAccumName "=" "{" LOADACCUM loadAccumParams
                 ["," LOADACCUM loadAccumParams]* "}"
loadAccumParams := "(" filePath "," columnId ["," [columnId]* ","
     stringLiteral "," (TRUE | FALSE) ")" ["."FILTER "(" condition ")"]
columnId := "$"(integer | stringLiteral)
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

`LOADACCUM()` can initialize a global accumulator by loading data from a file. `LOADACCUM()` has 3+n parameters explained in the table below, where n is the number of fields in the accumulator.
Any accumulator using generic `VERTEX` as an element type cannot be initialized by `LOADACCUM()`.  
---  
#### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_parameters)Parameters
Name | Type | Description  
---|---|---  
`filePath` | String | The absolute file path of the input file to be read. A relative path is not supported.  
`columnId` | String or number | The column position(s) or column name(s) of the data file that supply data values to each field of the accumulator.  
`separator` | Single-character string | The separator of columns.  
`header` | Boolean | Whether this file has a header.  
One assignment statement can have multiple `LOADACCUM()` function calls. However, every `LOADACCUM()` referring to the same file in the same assignment statement must use the same separator and header parameter values.
#### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_example_4)Example
  * Data
  * Query
  * Result


loadAccumInput.csv
```
person1,1,"test1",3
person5,2,"test2",4
person6,3,"test3",5
csv![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
CREATE QUERY load_accum_ex (STRING filename) FOR GRAPH Social_Net {
  TYPEDEF TUPLE<STRING aaa, VERTEX<Post> ddd> Your_Tuple;
  MapAccum<VERTEX<Person>, MapAccum<INT, Your_Tuple>> @@test_map;
  GroupByAccum<STRING a, STRING b, MapAccum<STRING, STRING> strList> @@test_group_by;
  @@test_map = { LOADACCUM (filename, $0, $1, $2, $3, ",", false)};
  @@test_group_by = { LOADACCUM ( filename, $1, $2, $3, $3, ",", true) };
  PRINT @@test_map, @@test_group_by;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
GSQL > RUN QUERY load_accum_ex("/file_directory/loadAccumInput.csv")
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{
  "@@testGroupBy": [
   {
    "a": "3",
    "b": "\"test3\"",
    "strList": {"5": "5"}
   },
   {
    "a": "2",
    "b": "\"test2\"",
    "strList": {"4": "4"}
   }
  ],
  "@@testMap": {
   "person1": {"1": {
    "aaa": "\"test1\"",
    "ddd": "3"
   }},
   "person6": {"3": {
    "aaa": "\"test3\"",
    "ddd": "5"
   }},
   "person5": {"2": {
    "aaa": "\"test2\"",
    "ddd": "4"
   }}
  }
 }]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_function_call_statements)Function Call Statements
```
funcCallStmt := name ["<" type ["," type]* ">"] "(" [argList] ")"
       | globalAccumName ("." funcName "(" [argList] ")")+
       | "reset_collection_accum" "(" accumName ")"
argList := expr ["," expr]*
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Typically, a function call returns a value and so is part of an [expression](https://docs.tigergraph.com/gsql-ref/4.2/querying/operators-and-expressions). In some cases, however, the function does not return a value (i.e., returns `VOID`) or the return value can be ignored, so the function call can be used as an entire statement. This is a Function Call Statement.
Examples of Function Call statements
```
ListAccum<STRING> @@list_acc;
BagAccum<INT> @@bag_acc;
...
// Examples of function call statements
@@list_acc.clear();
@@bag_acc.removeAll(0);
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements#_clear_collection_accumulators)Clear Collection Accumulators
Collection accumulators (e.g., `ListAccum`, `SetAccum`, `MapAccum`) grow in size as data is added. Particularly for vertex-attached accumulators, if the number of vertices is large, their memory consumption can be significant. It can improve system performance to clear or reset collection accumulators during a query as soon as their data is no longer needed. Running the `reset_collection_accum()` function resets the collection(s) to be zero-length (empty). If the argument is a vertex-attached accumulator, then the entire set of accumulators is reset.
```
"reset_collection_accum" "(" accumName ")"
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

`reset_collection_accum` only works in DISTRIBUTED mode queries. If the query is not in distributed mode, the reset does not take place.  
---  
  * Query
  * Results


```
CREATE DISTRIBUTED QUERY reset_accum() FOR GRAPH Work_Net SYNTAX v2 {
  ListAccum<STRING> @stuff;
  ListAccum<STRING> @@all_stuff;
  Comp = SELECT c
    FROM  Person:p -(Works_For:w)- Company:c
    ACCUM  c.@stuff += p.id,
      @@all_stuff += p.id,
      c.@stuff += p.location_id,
      @@all_stuff += p.location_id,
      FOREACH interest IN p.interest_list DO
        c.@stuff += interest,
        @@all_stuff += interest
      END;
  // Display accum size: should be full
  PRINT Comp[Comp.@stuff.size()] AS stuff_count;
  PRINT @@all_stuff.size() AS all_stuff_count;
  reset_collection_accum(@stuff);
  reset_collection_accum(@@all_stuff);
  // display accum size: should be empty
  PRINT Comp[Comp.@stuff.size()] AS stuff_clear;
  PRINT @@all_stuff.size() AS all_stuff_clear;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [
  {"stuff_count": [
   {
    "v_id": "company2",
    "attributes": {"Comp.@stuff.size()": 23},
    "v_type": "Company"
   },
   {
    "v_id": "company4",
    "attributes": {"Comp.@stuff.size()": 7},
    "v_type": "Company"
   },
   {
    "v_id": "company3",
    "attributes": {"Comp.@stuff.size()": 12},
    "v_type": "Company"
   },
   {
    "v_id": "company1",
    "attributes": {"Comp.@stuff.size()": 21},
    "v_type": "Company"
   },
   {
    "v_id": "company5",
    "attributes": {"Comp.@stuff.size()": 4},
    "v_type": "Company"
   }
  ]},
  {"all_stuff_count": 67},
  {"stuff_clear": [
   {
    "v_id": "company2",
    "attributes": {"Comp.@stuff.size()": 0},
    "v_type": "Company"
   },
   {
    "v_id": "company4",
    "attributes": {"Comp.@stuff.size()": 0},
    "v_type": "Company"
   },
   {
    "v_id": "company3",
    "attributes": {"Comp.@stuff.size()": 0},
    "v_type": "Company"
   },
   {
    "v_id": "company1",
    "attributes": {"Comp.@stuff.size()": 0},
    "v_type": "Company"
   },
   {
    "v_id": "company5",
    "attributes": {"Comp.@stuff.size()": 0},
    "v_type": "Company"
   }
  ]},
  {"all_stuff_clear": 0}
 ]
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


