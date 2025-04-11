![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
[Products](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/enable-cost-optimizer)
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
[Resources](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/enable-cost-optimizer)
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
  * Profile and Optimize
  * [Query Optimizer (Preview)](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/)
  * [Enable Query Optimizer](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/enable-cost-optimizer)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/4.2/modules/querying/pages/query-optimizer/enable-cost-optimizer.adoc)
### Contents
  * [1. Before you begin](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/enable-cost-optimizer#_before_you_begin)
  * [2. Procedure](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/enable-cost-optimizer#_procedure)
  * [2.1. Identify referenced types and attributes](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/enable-cost-optimizer#_identify_referenced_types_and_attributes)
  * [2.2. Compute cardinality data](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/enable-cost-optimizer#_compute_cardinality_data)
  * [2.3. Compute histogram data](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/enable-cost-optimizer#_compute_histogram_data)
  * [2.4. Install query with -COST option](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/enable-cost-optimizer#_install_query_with_cost_option)


# Enabling Cost-Based Optimization
### Contents
  * [1. Before you begin](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/enable-cost-optimizer#_before_you_begin)
  * [2. Procedure](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/enable-cost-optimizer#_procedure)
  * [2.1. Identify referenced types and attributes](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/enable-cost-optimizer#_identify_referenced_types_and_attributes)
  * [2.2. Compute cardinality data](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/enable-cost-optimizer#_compute_cardinality_data)
  * [2.3. Compute histogram data](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/enable-cost-optimizer#_compute_histogram_data)
  * [2.4. Install query with -COST option](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/enable-cost-optimizer#_install_query_with_cost_option)


This page walks you through the steps to enable cost-based optimization.
Query Optimizer is currently a Preview Feature. Preview Features give users an early look at future production-level features. Preview Features should not be used for production deployments.  
---  
## [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/enable-cost-optimizer#_before_you_begin)1. Before you begin
  * You have created a query that contains a [`SELECT` statement](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/) that uses a [path pattern](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/#_path_pattern) in its `FROM` clause with one or more hops.
  * You have the privilege to install queries on the graph where you are operating.


## [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/enable-cost-optimizer#_procedure)2. Procedure
The following is the procedure to enable cost-based optimization when installing a query.
### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/enable-cost-optimizer#_identify_referenced_types_and_attributes)2.1. Identify referenced types and attributes
You need to identify the vertex and edge types for which you need to compute the following statistics:
  * Cardinality: the number of instances for each type
  * Histogram: the distribution of values for an attribute


#### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/enable-cost-optimizer#_cardinality)2.1.1. Cardinality
You need to compute cardinality data for the following vertex and edge types:
  * Any vertex type referenced in the path pattern of a `FROM` clause.
  * Any _refined edge type_. A _refined edge type_ means an edge type with a specified pair of `from` and `to` vertex types as well as their reverse edge types if they exist.


#### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/enable-cost-optimizer#_histogram)2.1.2. Histogram
You need to compute histograms for the following attributes:
  * Any vertex attribute referenced in a [`WHERE` clause](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/#_where) in a `SELECT` statement in the query.
  * Any _refined edge type_ attribute referenced in a [`WHERE` clause](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/#_where) in a `SELECT` statement in the query.
    * A _refined edge type_ means an edge type with a specified pair of `from` and `to` vertex types as well as their reverse edge types if they exist.


If you are not sure which types and attributes you need to compute histogram data for a query, you can try [installing that query with the cost-based optimizer enabled](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/enable-cost-optimizer#_install_query_with_cost_option) first. The optimizer produces a helpful recommendation if it sees any types/attributes that don’t have statistics computed for them.
For example, to optimize the following query:
```
CREATE OR REPLACE QUERY example3() FOR GRAPH ldbc_snb SYNTAX V2 {
 vSet = SELECT p
    FROM Tag:t - (<HAS_TAG) - Comment:m - (<LIKES:e) - Person:p
    WHERE p.gender == "female" AND t.id != 100 AND e.creationDate > to_datetime("2010-10-01 16:00")
    LIMIT 50;
    PRINT vSet;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

You need the following histogram statistics:
  * `gender` attribute of type `Person`
  * `id` attribute of type `Tag`
  * `creationDate` attribute of type `LIKES` from `Person` to `Comment`.


### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/enable-cost-optimizer#_compute_cardinality_data)2.2. Compute cardinality data
To compute cardinality data (the count of each type), use the [`POST :14240/gsql/v1/stats/cardinality` endpoint](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/stats-api#_compute_cardinality_statistics).
For example, to compute the cardinality data of the vertex `Person` in graph `ldbc_snb`, make the following request:
```
curl -s --user tigergraph:tigergraph \
-H 'Content-Type: application/json' \
-X POST "http://localhost:14240/gsql/v1/stats/card?graph=ldbc_snb&vertex=Person"
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

For another example, to compute the cardinality data of the refined edge type `LIKES` from a `Person` vertex to a `Comment` vertex, make the following request:
```
curl -s --user tigergraph:tigergraph \
-H 'Content-Type: application/json' \
-X POST "http://localhost:14240/gsql/v1/stats/card?graph=ldbc_snb&edge=LIKES&from=Person&to=Comment"
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

For best results, compute the cardinality data for every type you identified in the previous step, each with its own request.
### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/enable-cost-optimizer#_compute_histogram_data)2.3. Compute histogram data
To compute histogram data, use the [`POST :14240/gsql/v1/stats/histogram` endpoint](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/stats-api#_compute_histogram_statistics).
For example, to compute the histogram data for attribute `gender` of vertex type `Person` on graph `ldbc_snb`, make the following request:
```
$ $ curl --user tigergraph:tigergraph \
-H 'Content-Type: application/json' \
-X POST "http://localhost:14240/gsql/v1/stats/histogram" \
-d '{"graph":"ldbc_snb", "vertex":"Person", "attribute":"gender", "bucket":10}'
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

To compute the histogram data for attribute `creationDate` of refined edge type `LIKES` from vertex type `Person` to vertex type `Comment`, make the following request:
```
$ curl -s --user tigergraph:tigergraph \
-H 'Content-Type: application/json' \
-X POST "http://localhost:14240/gsql/v1/stats/histogram" \
-d '{"graph":"ldbc_snb", "edge":"LIKES", "from":"Person", "to":"Comment", "attribute":"creationDate", "bucket":10}' | jq .
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

For best results, compute the histogram data for every attribute referenced in a `WHERE` clause of a `SELECT` statement.
### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/enable-cost-optimizer#_install_query_with_cost_option)2.4. Install query with `-COST` option
Now that the relevant statistics are available to the query optimizer, you can install the query with cost-based optimization. To use the cost-based optimization during installation, use the [`-COST` option](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-operations#_install_query) when installing the query.
For example, to install the query `example3`, run `INSTALL QUERY -COST example3`.
Alternatively, set [the `cost_opt` session parameter](https://docs.tigergraph.com/gsql-ref/4.2/basics/running-gsql#_session_parameters) to true by running `set cost_opt = true` in the GSQL shell. This enables cost-based optimization for the rest of your GSQL session. You no longer need to supply the `-COST` option when installing queries if the `cost_opt` parameter is set to true.
If you missed any cardinality or histogram data, the optimizer warns you about which types are missing, so you can compute the data for any missing type or attribute.
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


