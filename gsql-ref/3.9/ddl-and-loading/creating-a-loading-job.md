![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job)[Next](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job)
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
[Resources](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job)
[Developer Site](https://dev.tigergraph.com/) [Community Forum](https://community.tigergraph.com/) [Knowledge Base](https://tigergraph.freshdesk.com/support/solutions)
[Download](https://dl.tigergraph.com)
[ TG Savanna](https://savanna.tgcloud.io)
### [GSQL Language Reference](https://docs.tigergraph.com/gsql-ref/3.9/intro/)
  *     * [Overview](https://docs.tigergraph.com/gsql-ref/3.9/intro/)
    * [What sets GSQL apart](https://docs.tigergraph.com/gsql-ref/3.9/intro/set-gsql-apart)
  *     * Tutorials
      * [GSQL 101](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/gsql-101/)
        * [Define a Schema](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/gsql-101/define-a-schema)
        * [Load Data](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/gsql-101/load-data-gsql-101)
        * [Run Built-in Queries](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/gsql-101/built-in-select-queries)
        * [Parameterized Queries](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/gsql-101/parameterized-gsql-query)
        * [Review](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/gsql-101/review)
      * [Pattern Matching Tutorial](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/)
        * [Prepare your Environment](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/prepare-environment)
        * [One-hop patterns](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/one-hop-patterns)
        * [Repeating a 1-Hop Pattern](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/repeating-a-pattern)
        * [Multiple Hop Patterns and Accumulation](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation)
        * [Example - A Recommender](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/example)
        * [Advanced Features](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/adv/)
          * [Per Clause (Beta)](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/adv/per-clause)
          * [Conjunctive Pattern Matching (Beta)](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/adv/conjunctive-pattern-matching)
          * [Data Modification](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/adv/dml)
        * [Summary](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/summary)
      * [Accumulators Tutorial](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/accumulators-tutorial)
  *     * [System & Language Basics](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics)
  *     * [Attribute Data Types](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/attribute-data-types)
    * [Schema Definition](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/)
      * [Define a Graph Schema](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/defining-a-graph-schema)
      * [Modify a Graph Schema](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/modifying-a-graph-schema)
    * [Loading Jobs](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/loading-jobs)
      * [Create a Loading Job](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job)
        * [Functions](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/)
          * [Token Functions](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/)
            * [flatten()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/flatten)
            * [flatten_json_array()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/flatten_json_array)
            * [gsql_concat()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/gsql_concat)
            * [gsql_current_time_epoch()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/gsql_current_time_epoch)
            * [gsql_day()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/gsql_day)
            * [gsql_day_epoch()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/gsql_day_epoch)
            * [gsql_find()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/gsql_find)
            * [gsql_length()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/gsql_length)
            * [gsql_lower()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/gsql_lower)
            * [gsql_ltrim()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/gsql_ltrim)
            * [gsql_month()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/gsql_month)
            * [gsql_month_epoch()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/gsql_month_epoch)
            * [gsql_regex_match()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/gsql_regex_match)
            * [gsql_regex_replace()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/gsql_regex_replace)
            * [gsql_reverse()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/gsql_reverse)
            * [gsql_rtrim()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/gsql_rtrim)
            * [gsql_substring()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/gsql_substring)
            * [gsql_to_bool()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/gsql_to_bool)
            * [gsql_to_int()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/gsql_to_int)
            * [gsql_to_uint()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/gsql_to_uint)
            * [gsql_trim()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/gsql_trim)
            * [gsql_ts_to_epoch_seconds()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/gsql_ts_to_epoch)
            * [gsql_upper()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/gsql_upper)
            * [gsql_uuid_v4()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/gsql_uuid_v4)
            * [gsql_year()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/gsql_year)
            * [gsql_year_epoch()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/gsql_year_epoch)
            * [split()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/split)
          * [Token Functions in WHERE Clause](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token_where/)
            * [concat()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token_where/concat)
            * [gsql_is_false()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token_where/gsql_is_false)
            * [gsql_is_not_empty()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token_where/gsql_is_not_empty)
            * [gsql_is_true()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token_where/gsql_is_true)
            * [gsql_token_equal()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token_where/gsql_token_equal)
            * [gsql_token_ignore_case_equal()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token_where/gsql_token_ignore_case_equal)
            * [to_float()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token_where/to_float)
            * [to_int()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token_where/to_int)
            * [token_len()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token_where/token_len)
          * [Reducer functions](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/reducer/)
            * [add()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/reducer/add)
            * [and()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/reducer/and)
            * [ignore_if_exists()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/reducer/ignore_if_exists)
            * [max()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/reducer/max)
            * [min()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/reducer/min)
            * [or()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/reducer/or)
        * [Add a User-defined Token Function](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/add-token-function)
      * [Run a Loading Job](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/running-a-loading-job)
      * [Manage Loading Jobs](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/managing-loading-job)
  *     * [Querying](https://docs.tigergraph.com/gsql-ref/3.9/querying/)
      * [Query Language Syntax Versions](https://docs.tigergraph.com/gsql-ref/3.9/querying/syntax-versions)
      * [Queries](https://docs.tigergraph.com/gsql-ref/3.9/querying/query-operations)
      * [Query Optimizer (Preview Feature)](https://docs.tigergraph.com/gsql-ref/3.9/querying/query-optimizer/)
        * [Enabling Cost-Based Optimization (Preview Feature)](https://docs.tigergraph.com/gsql-ref/3.9/querying/query-optimizer/enable-cost-optimizer)
        * [Statistics REST APIs (Preview Feature)](https://docs.tigergraph.com/gsql-ref/3.9/querying/query-optimizer/stats-api)
      * [Distributed Query Mode](https://docs.tigergraph.com/gsql-ref/3.9/querying/distributed-query-mode)
      * [Data Types](https://docs.tigergraph.com/gsql-ref/3.9/querying/data-types)
      * [Accumulators](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators)
      * [Operators and Expressions](https://docs.tigergraph.com/gsql-ref/3.9/querying/operators-and-expressions)
      * [Functions](https://docs.tigergraph.com/gsql-ref/3.9/querying/func/)
        * [Aggregation Functions](https://docs.tigergraph.com/gsql-ref/3.9/querying/func/aggregation-functions)
        * [Datetime Functions](https://docs.tigergraph.com/gsql-ref/3.9/querying/func/datetime-functions)
        * [Edge Methods](https://docs.tigergraph.com/gsql-ref/3.9/querying/func/edge-methods)
        * [JSON Object Methods](https://docs.tigergraph.com/gsql-ref/3.9/querying/func/json-object-methods)
        * [JSON Array Methods](https://docs.tigergraph.com/gsql-ref/3.9/querying/func/jsonarray-methods)
        * [Mathematical Functions](https://docs.tigergraph.com/gsql-ref/3.9/querying/func/mathematical-functions)
        * [Miscellaneous Functions](https://docs.tigergraph.com/gsql-ref/3.9/querying/func/miscellaneous-functions)
        * [Query User-Defined Functions](https://docs.tigergraph.com/gsql-ref/3.9/querying/func/query-user-defined-functions)
        * [String Functions](https://docs.tigergraph.com/gsql-ref/3.9/querying/func/string-functions)
        * [Type Conversion Functions](https://docs.tigergraph.com/gsql-ref/3.9/querying/func/type-conversion-functions)
        * [Vertex Functions](https://docs.tigergraph.com/gsql-ref/3.9/querying/func/vertex-methods)
      * [Declaration and Assignment Statements](https://docs.tigergraph.com/gsql-ref/3.9/querying/declaration-and-assignment-statements)
      * [SELECT Statement](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/)
        * [SELECT Statement (Syntax V1)](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1)
        * [SQL-like SELECT statement](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/sql-like-select-statement)
      * [Control Flow Statements](https://docs.tigergraph.com/gsql-ref/3.9/querying/control-flow-statements)
      * [Data Modification Statements](https://docs.tigergraph.com/gsql-ref/3.9/querying/data-modification-statements)
      * [Output Statements and FILE Objects](https://docs.tigergraph.com/gsql-ref/3.9/querying/output-statements-and-file-objects)
      * [Exception Statements](https://docs.tigergraph.com/gsql-ref/3.9/querying/exception-statements)
      * [Comments](https://docs.tigergraph.com/gsql-ref/3.9/querying/comments)
  *     * openCypher
      * [openCypher in GSQL](https://docs.tigergraph.com/gsql-ref/3.9/openCypher-in-gsql/openCypher-in-gsql)
      * [Writing and Running openCypher in GSQL Shell](https://docs.tigergraph.com/gsql-ref/3.9/openCypher-in-gsql/openCypher-in-gsql-web-shell)
      * [openCypher Pattern Support in GSQL](https://docs.tigergraph.com/gsql-ref/3.9/openCypher-in-gsql/openCypher-gsql-from-clause-extension)
  *     * Appendix
      * [GSQL Style Guide](https://docs.tigergraph.com/gsql-ref/3.9/appendix/gsql-style-guide)
      * [DDL Keywords & Reserved Words](https://docs.tigergraph.com/gsql-ref/3.9/appendix/keywords-and-reserved-words)
      * [Query Language Keywords & Reserved Words](https://docs.tigergraph.com/gsql-ref/3.9/appendix/query-language-reserved-words)
      * [Interpreted GSQL Limitations](https://docs.tigergraph.com/gsql-ref/3.9/appendix/interpreted-gsql-limitations)
      * [GSQL Start-to-End Process and Data Flow](https://docs.tigergraph.com/gsql-ref/3.9/appendix/gsql-start-to-end-process)
      * [Example Graphs](https://docs.tigergraph.com/gsql-ref/3.9/appendix/example-graphs)
      * [Common Errors and Problems](https://docs.tigergraph.com/gsql-ref/3.9/appendix/common-errors-and-problems)
      * [GSQL Cheat Sheets](https://docs.tigergraph.com/gsql-ref/3.9/appendix/cheat-sheets)
      * [Documentation Notations](https://docs.tigergraph.com/gsql-ref/3.9/appendix/notations)
    * [Legacy Version Documentation](https://docs.tigergraph.com/gsql-ref/3.9/appendix/legacy-tg-versions)


GSQL Language Reference 3.9
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
  * [GSQL Language Reference 3.9](https://docs.tigergraph.com/gsql-ref/3.9/intro/)
  * [Loading Jobs](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/loading-jobs)
  * [Create a Loading Job](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/3.9/modules/ddl-and-loading/pages/creating-a-loading-job.adoc)
### Contents
  * [Loading job capabilities](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_job_capabilities)
  * [Concurrent Loading](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_concurrent_loading)
  * [CREATE LOADING JOB](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_create_loading_job)
  * [Loading data to global vertices and edges](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_data_to_global_vertices_and_edges)
  * [Example](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_example)
  * [DROP JOB statement](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_drop_job_statement)
  * [DEFINE statements](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_define_statements)
  * [DEFINE FILENAME](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_define_filename)
  * [DEFINE HEADER](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_define_header)
  * [DEFINE INPUT_LINE_FILTER](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_define_input_line_filter)
  * [Load statement](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_load_statement)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_syntax)
  * [Destination clause](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_destination_clause)
  * [Examples](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_examples)
  * [WHERE clause](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_where_clause)
  * [TAGS clause (Deprecated)](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_tags_clause_deprecated)
  * [USING clause](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_using_clause)
  * [Loading JSON data](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_json_data)
  * [Loading Parquet data](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_parquet_data)
  * [Attributes and attribute expressions](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_attributes_and_attribute_expressions)
  * [Cumulative loading](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_cumulative_loading)
  * [More complex attribute expressions](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_more_complex_attribute_expressions)
  * [Loading a DOUBLE or FLOAT attribute](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_a_double_or_float_attribute)
  * [Loading a DATETIME attribute](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_a_datetime_attribute)
  * [Loading a BOOL attribute](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_a_bool_attribute)
  * [Loading a User-defined type (UDT) attribute](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_a_user_defined_type_udt_attribute)
  * [Loading a LIST or SET attribute](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_a_list_or_set_attribute)
  * [Loading a MAP attribute](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_a_map_attribute)
  * [Loading composite key attributes](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_composite_key_attributes)
  * [Loading Wildcard Type Edges](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_wildcard_type_edges)
  * [Token functions](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_token_functions)
  * [Token functions for attribute expressions](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_token_functions_for_attribute_expressions)
  * [Token functions in the WHERE clause](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_token_functions_in_the_where_clause)
  * [User-defined token functions](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_user_defined_token_functions)
  * [Reducer functions](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_reducer_functions)
  * [TEMP_TABLE and flatten functions](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_temp_table_and_flatten_functions)
  * [One-level flatten function](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_one_level_flatten_function)
  * [Two-level flatten function](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_two_level_flatten_function)
  * [Flatten a JSON array of primitive values](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_flatten_a_json_array_of_primitive_values)
  * [Flatten a JSON array of JSON objects](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_flatten_a_json_array_of_json_objects)
  * [Flatten a JSON object in a CSV file](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_flatten_a_json_object_in_a_csv_file)
  * [DELETE statement](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_delete_statement)


# Creating a Loading Job
### Contents
  * [Loading job capabilities](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_job_capabilities)
  * [Concurrent Loading](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_concurrent_loading)
  * [CREATE LOADING JOB](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_create_loading_job)
  * [Loading data to global vertices and edges](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_data_to_global_vertices_and_edges)
  * [Example](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_example)
  * [DROP JOB statement](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_drop_job_statement)
  * [DEFINE statements](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_define_statements)
  * [DEFINE FILENAME](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_define_filename)
  * [DEFINE HEADER](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_define_header)
  * [DEFINE INPUT_LINE_FILTER](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_define_input_line_filter)
  * [Load statement](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_load_statement)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_syntax)
  * [Destination clause](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_destination_clause)
  * [Examples](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_examples)
  * [WHERE clause](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_where_clause)
  * [TAGS clause (Deprecated)](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_tags_clause_deprecated)
  * [USING clause](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_using_clause)
  * [Loading JSON data](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_json_data)
  * [Loading Parquet data](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_parquet_data)
  * [Attributes and attribute expressions](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_attributes_and_attribute_expressions)
  * [Cumulative loading](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_cumulative_loading)
  * [More complex attribute expressions](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_more_complex_attribute_expressions)
  * [Loading a DOUBLE or FLOAT attribute](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_a_double_or_float_attribute)
  * [Loading a DATETIME attribute](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_a_datetime_attribute)
  * [Loading a BOOL attribute](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_a_bool_attribute)
  * [Loading a User-defined type (UDT) attribute](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_a_user_defined_type_udt_attribute)
  * [Loading a LIST or SET attribute](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_a_list_or_set_attribute)
  * [Loading a MAP attribute](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_a_map_attribute)
  * [Loading composite key attributes](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_composite_key_attributes)
  * [Loading Wildcard Type Edges](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_wildcard_type_edges)
  * [Token functions](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_token_functions)
  * [Token functions for attribute expressions](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_token_functions_for_attribute_expressions)
  * [Token functions in the WHERE clause](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_token_functions_in_the_where_clause)
  * [User-defined token functions](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_user_defined_token_functions)
  * [Reducer functions](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_reducer_functions)
  * [TEMP_TABLE and flatten functions](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_temp_table_and_flatten_functions)
  * [One-level flatten function](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_one_level_flatten_function)
  * [Two-level flatten function](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_two_level_flatten_function)
  * [Flatten a JSON array of primitive values](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_flatten_a_json_array_of_primitive_values)
  * [Flatten a JSON array of JSON objects](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_flatten_a_json_array_of_json_objects)
  * [Flatten a JSON object in a CSV file](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_flatten_a_json_object_in_a_csv_file)
  * [DELETE statement](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_delete_statement)


After a graph schema has been created, the system is ready to load data into the graph store. The GSQL language offers commands for data loading which perform many of the same data conversion, mapping, filtering, and merging operations that are found in enterprise ETL (Extract, Transform, and Load) systems.
The GSQL system can read structured or semi-structured data from text files. The loading language syntax is geared towards tabular or JSON data, but conditional clauses and data manipulation functions allow for reading data that is structured in a more complex or irregular way. For tabular data, each line in the data file contains a series of data values, separated by commas, tabs, spaces, or any other designated ASCII characters (only single character separators are supported). A line should contain only data values and separators, without extra whitespace. From a tabular view, each line of data is a row, and each row consists of a series of column values.
Loading data is a two-step process.
  1. First, a loading job is defined with a `CREATE LOADING JOB` statement.
  2. Next, the job is executed with a `RUN LOADING JOB` statement.


These two statements, and the components of the loading job, are detailed below.
The structure of a loading job will be presented hierarchically, top-down:
`CREATE LOADING JOB`, which may contain a set of DEFINE and LOAD statements
  * `DEFINE` statements
  * `LOAD` statements, which can have several clauses


**All blank spaces are meaningful in string fields in CSV and JSON**. Either pre-process your data files to remove extra spaces, or use GSQL’s token processing functions `gsql_trim`, `gsql_ltrim`, and `gsql_rtrim` ([Token functions](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_token_functions)).   
---  
User privileges for running loading jobs are treated as separate from privileges regarding reading and writing data to vertices and edges. A user can create and run loading jobs even without the privileges to modify vertex and edge data. For more information, see [Access Control Model in TigerGraph](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model).   
---  
## [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_job_capabilities)Loading job capabilities
TigerGraph’s syntax for defining and running loading jobs offers several advantages:
  * The TigerGraph platform can handle concurrent loading jobs, which can greatly increase throughput.
  * The data file locations can be specified at compile time or at run time. Run-time settings override compile-time settings.
  * A loading job definition can include several input files. When running the job, the user can choose to run only part of the job by specifying only some of the input files.
  * Loading jobs can be monitored, aborted, and restarted.


### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_concurrent_loading)Concurrent Loading
Among its several duties, the RESTPP component manages loading jobs. There can be multiple RESTPP-LOADER subcomponents, each of which can handle a loading job independently. The maximum number of concurrent loading jobs is set by the configuration parameter `FileLoader.ReplicaNumber`.
Furthermore, if the TigerGraph graph is distributed (partitioned) across multiple machine nodes, each machine’s RESTPP-LOADER(s) can be put into action. Each RESTPP-LOADER only reads local input data files, but the resulting graph data can be stored on any machine in the cluster.
To maximize loading performance in a cluster, use at least two loaders per machine, and assign each loader approximately the same amount of data.   
---  
A concurrent-capable loading job can logically be separated into parts according to each file variable. When a concurrent-capable loading job is compiled, a [RESTPP endpoint](https://docs.tigergraph.com/tigergraph-server/4.2/API/built-in-endpoints#_run_a_loading_job) is generated for the loading job, which you can call to load data into your graph as an alternative to `RUN LOADING JOB`.
Example loading jobs and data files for the `Book_Rating` schema defined earlier in the document are available in the `$(gadmin config get System.AppRoot)/document/examples` folder in your TigerGraph platform installation.  
---  
## [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_create_loading_job)`CREATE LOADING JOB`
The `CREATE LOADING JOB` statement is used to define a block of `DEFINE`, `LOAD`, and `DELETE` statements for loading data to or removing data from a particular graph. The sequence of statements is enclosed in curly braces. Each statement in the block, including the last one, should end with a semicolon.
CREATE LOADING JOB syntax
```
CREATE LOADING JOB job_name FOR GRAPH Graph_Name {
  [zero or more DEFINE statements;] **(1)**
  [zero or more LOAD statements;] | [zero or more DELETE statements;] **(2)**
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | While one loading job may define multiple data sources (files), keep the number below 100 for best performance.  
---|---  
**2** | A loading job may contain either `LOAD` or `DELETE` statements but not both. A loading job that includes both will be rejected when the `CREATE` statement is executed.  
### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_data_to_global_vertices_and_edges)Loading data to global vertices and edges
The `CREATE VERTEX` and `CREATE EDGE` commands create global vertices and edges. See the [CREATE VERTEX](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/defining-a-graph-schema#_create_vertex) and [CREATE EDGE](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/defining-a-graph-schema#_create_edge) pages for more detail.
Global vertex and edge type data is shared across all graphs, no matter which graph it is loaded to. In other words, if `v1` and `e2` are of `GLOBAL` type, the data loaded in this loading job will be accessible in other graphs that use `v1` and `e2` vertices and edges.
To create a local vertex or edge, run a schema change job after a graph has already been created and use the `ADD VERTEX` or `ADD EDGE` command to add a vertex or edge to a single graph. See [Global vs. local schema changes](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/modifying-a-graph-schema#_global_vs_local_schema_changes) for more information.
### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_example)Example
Loading Job Example
```
CREATE LOADING JOB job_1 FOR GRAPH Graph_1 {
  DEFINE FILENAME file1 = "/data/v1.csv"; **(1)**
  DEFINE FILENAME file2;
  LOAD file1 TO VERTEX v1 VALUES ($0, $1, $2);
  LOAD file2 TO EDGE e2 VALUES ($0, $1);
}
RUN LOADING JOB job1 USING file1="m1:/data/v1_1.csv", file2="m2:/data/e2.csv" **(2)**
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | File path specified at compile time.  
---|---  
**2** | Run-time specification will override path specified at compile time.  
## [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_drop_job_statement)`DROP JOB` statement
To drop (remove) a job, run `DROP JOB job_name`. The job will be removed from GSQL. To drop all jobs, run either of the following commands:
```
DROP JOB ALL
DROP JOB *
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The scope of `DROP JOB ALL` depends on the user’s current scope. If the user has set a working graph, then `DROP ALL` removes all the jobs for that graph. If a superuser has set their scope to be global, then `DROP JOB ALL` removes all jobs across all graph spaces.
## [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_define_statements)`DEFINE` statements
A `DEFINE` statement is used to define a local variable or expression to be used by the subsequent `LOAD` statements in the loading job.
### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_define_filename)`DEFINE FILENAME`
The `DEFINE FILENAME` statement defines a filename variable. The variable can then be used later in the `JOB` block by a `LOAD` statement to identify its data source. Every concurrent loading job must have at least one `DEFINE FILENAME` statement.
Having more than 100 file or folder sources will degrade performance. Consider either consolidating sources or splitting your work into separate loading jobs.   
---  
```
DEFINE FILENAME filevar ["=" filepath_string ];
filepath_string = (path | " all :" path | " any :" path | mach_aliases " :" path ["," mach_aliases ":" path ]*)
mach_aliases = name["|"name]*
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_parameters)Parameters 

`filevar`
    
The name of the filename variable. 

`filepath_string`
    
The `filevar` is optionally followed by a `filepath_string`, which tells the job where to find input data. `filepath_string` is a string value and should start and end with double quotes.
There are four options for `filepath_string`:
  * An absolute or relative path for either a file or a folder **on the machine where the job is run**. If it is a folder, then the loader will attempt to load each non-hidden file in the folder. If this path is not valid when `CREATE LOADING JOB` is executed, GSQL will report an error.
An absolute path may begin with the [session parameter](https://docs.tigergraph.com/tigergraph-server/4.2/gsql-shell/gsql-sessions) `$sys.data_root`.
  * An absolute or relative path for either a file or a folder **on all machines in the cluster** : If the path is prefixed with `all:`, then the loading job will attempt to run on every machine in the cluster which has a RESTPP component, and each machine will look locally for data at _path_. **If the path is invalid on any of the machines, the job will be aborted**. Also, the session parameter `$sys.data_root` may not be used.
`ALL:path` examples
```
"ALL:/data/graph.csv"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * An absolute or relative path for either a file or a folder **on any machine in the cluster** : If the path is prefixed with `any:`, then the loading job will attempt to run on every machine in the cluster which has a RESTPP component, and each machine will look locally for data at the specified path. **If the path is invalid on any of the machines, those machines where the path is not valid are skipped.** Also, the session parameter `$sys.data_root` may not be used.
`ANY:path` examples
```
"ANY:/data/graph.csv"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * **A list of machine-specific paths** : A machine alias is a name such as m1, m2, etc. which is defined when the cluster configuration is set. For this option, the `filepath_string` may include a list of paths, separated by commas. If several machines have the same path, the paths can be grouped together by using a list of machine aliases, with the vertical bar "|" as a separator. The loading job will run on whichever machines are named; each RESTPP-LOADER will work on its local files.
machine-specific path example
```
"m1:/data1.csv, m2|m3|m5:/data/data2.csv"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```



### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_define_header)`DEFINE HEADER`
The `DEFINE HEADER` statement defines a sequence of column names for an input data file. The first column name maps to the first column, the second column name maps to the second column, etc.
```
DEFINE HEADER header_name = " column_name "[," column_name "]*;
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_define_input_line_filter)`DEFINE INPUT_LINE_FILTER`
This statement is not supported in a [Kafka loading job](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/data-loading-overview).   
---  
The `DEFINE INPUT_LINE_FILTER` statement defines a named Boolean expression whose value depends on column attributes from a row of input data. When combined with a `USING reject_line_rule` clause in a `LOAD` statement, the filter determines whether an input line is ignored or not.
```
DEFINE INPUT_LINE_FILTER filter_name = boolean_expression_using_column_variables;
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_load_statement)Load statement
A `LOAD` statement describes how to parse a data line into column values (tokens), and then describes how the values should be used to create a new vertex or edge instance.
One `LOAD` statement can be used to generate multiple vertices or edges, each vertex or edge having its own _destination clause_ , as shown below. Additionally, two or more LOAD statements may refer to the same input data file. In this case, the GSQL loader will merge their operations so that both of their operations are executed in a single pass through the data file.
The `LOAD` statement has many options. This reference guide provides examples of key features and options. Tutorials such as [GSQL 101](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#tutorials:gsql-101/) provide additional solution- and application-oriented examples.
Different `LOAD` statement types have different rules for the [`USING` clause](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_using_clause); see the `USING` clause section below for specifics.
### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_syntax)Syntax
```
LOAD [ filepath_string|filevar|TEMP_TABLE table_name ]
   destination_clause [, destination_clause ]*
   [ TAGS clause ]
   [ USING clause ];
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

`filevar` must have been previously defined in a `DEFINE FILENAME` statement.
`filepath_string` must satisfy the same rules given above in the `DEFINE FILENAME` section.
### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_destination_clause)Destination clause
A _destination clause_ describes how the tokens from a data source should be used to construct one of three types of data objects: a vertex, an edge, or a row in a [temporary table](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_temp_table_and_flatten_functions) (`TEMP_TABLE`). This section describes destination clauses for loading to vertices and edges.
Vertex Destination Clause
```
TO VERTEX vertex_type_name VALUES (id_expr [, attr_expr]*)
  [WHERE conditions]
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Edge Destination Clause
```
TO EDGE edge_type_name VALUES (source_id_expr [source_type_expr],
                target_id_expr [target_type_expr]
                [, attr_expr]*)
  [WHERE conditions]
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

For the `TO VERTEX` and `TO EDGE` destination clauses, the following rules for its parameters apply:
  * The `vertex_type_name` or `edge_type_name` must match the name of a vertex or edge type previously defined in a `CREATE VERTEX` or `CREATE UNDIRECTED|DIRECTED EDGE` statement.
  * The values in the value list_(`id_expr`, `attr_expr1`, `attr_expr2`,…​)_ are assigned to the ID(s) and attributes of a new vertex or edge instance, in the same order in which they are listed in the `CREATE` statement.
  * `id_expr` obeys the same attribute rules as `attr_expr`, except that only `attr_expr` can use the reducer function, which is introduced later.
  * For edge clauses, the `source_id_expr` and `target_id_expr` can each optionally be followed by a `source_type_expr` and `target_type_expr`, respectively. The `source_type_expr` and `target_type_expr` must evaluate to one of the allowed endpoint vertex types for the given edge type. By specifying the vertex type, this tells the loader what id types to expect. This may be important when the edge type is defined to accept more than one type of source/target vertex.


To support fast, out-of-order loading, **if one or both of the endpoint vertices of an edge do not yet exist, the loader will create vertices with the necessary IDs and default attribute values.** If the vertex data is loaded later, it will be automatically merged with the automatically created vertices. The user can disable this feature and perform regular referential integrity checking by setting the `VERTEX_MUST_EXIST` option to `true`.  
---  
Take care that your data sources do not have unintentional empty fields.
  * Prior to version 3.9.2, an empty primary ID field is accepted as valid. From 3.9.2+, it will be rejected.

  
---  
### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_examples)Examples
Suppose we have the following vertex and edge types:
```
CREATE VERTEX Person (pid STRING PRIMARY KEY, birthdate DATETIME)
CREATE VERTEX Company (cid INT PRIMARY KEY, industry STRING)
CREATE DIRECTED EDGE Visit (FROM Person, TO Person
             | FROM Person, TO Company, year INT)
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_vertex_loading)Vertex loading
The `Person` vertex type has a primary ID `pid` and an attribute `birthdate`. If we have the following CSV file with two columns:
```
Name,DOB
Sam,1994-05-01
Chris,1985-12-25
Pat,1996-11-13
Joe,1975-11-02
Taylor,1988-04-25
csv![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

If we want to use a person’s name as their primary ID, and load the DOB column into their `birthdate` attribute, we can use the following `LOAD` statement:
```
LOAD file1 TO VERTEX Person VALUES ($"Name", $"DOB") USING HEADER = "TRUE"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_edge_loading)Edge loading
A `Visit` edge can connect two `Person` vertices or a `Person` to a `Company`. A `Person` has a string ID, while a Company has an `INT` ID. Then suppose the `Visit` edge source data comes from a single CSV file, containing both variants of edges. Note that the 2nd column (`$1`) contains either `Person` or `Company`, and that the 3rd column (`$2`) contains either a string or an integer.
```
Sam,Person,Joe,2012
Sam,Company,4057,2017
Chris,Company,9401,2016
Pat,Person,Taylor,2020
csv![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Using the optional `target_type_expr` field, we can load both variants of the `Visit` edge with a single clause.
```
LOAD file2 TO EDGE Visit VALUES ($0, $2 $1, $3) USING SEPARATOR=",";
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**Known issue** : Prior to v3.9.2, when loading data into edge types defined with multiple `FROM-TO` vertex pairs, the load statement must include a `USING` clause, even if all options are default. "Multiple `FROM-TO` vertex pairs" means something like this: `CREATE DIRECTED EDGE Member_Of (FROM Person, TO Org | FROM Org, TO Org, joined DATETIME)`  
---  
### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_where_clause)WHERE clause
The `WHERE` clause is an optional clause. The `WHERE` clause’s condition is a boolean expression. The expression may use column token variables, token functions, and operators which are described below. The expression is evaluated for each input data line. If the condition is true, then the vertex or edge instance is loaded into the graph store. If the condition is false, then this instance is skipped. Note that all attribute values are treated as string values in the expression, so the type conversion functions `to_int()` and `to_float()`, which are described below, are provided to enable numerical conditions.
#### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_operators_in_the_where_clause)Operators in the WHERE Clause
The GSQL Loader language supports most of the standard arithmetic, relational, and boolean operators found in C++. Standard operator precedence applies, and parentheses provide the usual override of precedence. 

Arithmetic Operators
    
`+`, `-`, `*`, `/`, `^`. Numeric operators can be used to express complex operations between numeric types. Just as in ordinary mathematical expressions, parentheses can be used to define a group and to modify the order of precedence.
Because computers can only store approximations for most `DOUBLE` and `FLOAT` type values, testing these data types for exact equality or inequality is not recommended. Instead, one should allow for an acceptable amount of error. The following example checks if `$0` is equal to `5`, with an error of 0.00001 permitted: ```
WHERE to_float($0) BETWEEN 5-0.00001 AND 5+0.00001gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!
```
  
--- 

Relational Operators
      
`<`, `>`, `==`, `!=`, `⇐`, `>=`. Comparisons can be performed between two numeric values or between two string values. 

Predicate Operators
     

`AND`, `OR`, `NOT`
    
operators are the same as in SQL. They can be used to combine multiple conditions together. E.g., _$0 < "abc" AND $1 > "abc"_ selects the rows with the first token less than "abc" and the second token greater than "abc". E.g., _NOT $1 < "abc"_ selects the rows with the second token greater than or equal to "abc". 

`IS NUMERIC`
    
`<token> IS NUMERIC` returns true if `<token>` is in numeric format. Numeric format include integers, decimal notation, and exponential notation. Specifically, `IS NUMERIC` is true if token matches the following regular expression: `(/-) ? [0-9] + (.[0-9]) ? [0-9] * ((e/E)(/-) ? [0-9] +) ?`. Any leading space and trailing space is skipped, but no other spaces are allowed. For example, `$0 IS NUMERIC` checks whether the first token is in numeric format. 

`IS EMPTY`
    
`<token> IS EMPTY` returns true if `<token>` is an empty string. For example, `$1 IS EMPTY` checks whether the second token is empty. 

`IN` 
    
`<token> IN ( <set_of_values> )` returns true if `<token>` is equal to one member of a set of specified values. The values may be string or numeric types. For example, `$2 IN ("abc", "def", "lhm")` tests whether the third token equals one of the three strings in the given set. For example, `to_int($3) IN (10, 1, 12, 13, 19)` tests whether the fourth token equals one of the specified five numbers. 

`BETWEEN …​ AND`
    
`<token> BETWEEN <lower_val> AND <upper_val>` returns true if `<token>` is within the specified range, inclusive of the endpoints. The values may be string or numeric types. For example, `$4 BETWEEN "abc" AND "def"` checks whether the fifth token is greater than or equal to "abc" and also less than or equal to "def"; `to_float($5) BETWEEN 1 AND 100.5` checks whether the sixth token is greater than or equal to 1.0 and less than or equal to 100.5.
#### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#token-functions-in-where-clause)Token functions in the WHERE clause
The GSQL loading language provides several built-in functions for the `WHERE` clause.
The token functions in the WHERE clause and those token functions used for attribute expression are different. They cannot be used interchangeably.
Function name | Output type | Description of function  
---|---|---  
[to_int( _main_string_ )](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token_where/to_int) | `INT` | Converts _main_string_ to an integer value.  
[to_float( _main_string_ )](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token_where/to_float) | `FLOAT` | Converts _main_string_ to a float value.  
[concat( _string1, string2_ )](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token_where/concat) | `STRING` | Returns a string which is the concatenation of _string1_ and _string2_ .  
[token_len( _main_string_ )](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token_where/token_len) | INT | Returns the length of _main_string._  
[gsql_is_not_empty_string( _main_string_ )](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token_where/gsql_is_not_empty) | `BOOL` | Returns true if _main_string_ is empty after removing white space. Returns false otherwise.  
[gsql_token_equal( _string1, string2_ )](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token_where/gsql_token_equal) | `BOOL` | Returns true if _string1_ is exactly the same (case-sensitive) as _string2_ . Returns false otherwise.  
[gsql_token_ignore_case_equal( _string1, string2_ )](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token_where/gsql_token_ignore_case_equal) | `BOOL` | Returns true if _string1_ is exactly the same (case-insensitive) as _string2_. Returns false otherwise.  
[gsql_is_true( _main_string_ )](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token_where/gsql_is_true) | `BOOL` | Returns true if _main_string_ is either "t" or "true" (case-insensitive). Returns false otherwise.  
[gsql_is_false( _main_string_ )](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token_where/gsql_is_false) | `BOOL` | Returns true if _main_string_ is either "f" or "false" (case-insensitive). Returns false otherwise.  
### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_tags_clause_deprecated)`TAGS` clause (Deprecated)
Tag-based Vertex-Access Access Control is deprecated as of October 2023. TigerGraph will be introducing a more flexible scheme in an upcoming release.   
---  
The `TAGS` clause specifies the tags to be applied to the vertices loaded by the `LOAD` statement.
```
TAGS "(" tag_name (, tag_name)* ")" BY [ OR | OVERWRITE ]
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

If a `LOAD` statement has a `TAGS` clause, it will tag the vertices with the tags specified in the `TAGS` clause. Before vertices can be loaded and tagged with a `LOAD` statement, the vertex type must first be [marked as taggable](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/modifying-a-graph-schema#_alter_vertex_edge), and [the tags must be defined](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/modifying-a-graph-schema#_add_tag).
Users have two options when it comes to how to merge tags if the target vertices exist in the graph:
  * `BY OR`: Add the new tags to the existing set of tags.
  * `BY OVERWRITE`: Overwrite existing tags with the new tags.


### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_using_clause)`USING` clause
A `USING` clause contains one or more optional parameter value pairs:
```
USING parameter=value [,parameter=value]*
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

If multiple `LOAD` statements use the same source (the same file path, the same temporary data table, or the same file variable), the `USING` clauses in these `LOAD` statements must be the same. Therefore, we recommend that if multiple destination clauses share the same source, put all of these destination clauses into the same `LOAD` statement.  
---  
Parameter | Description | Allowed values  
---|---|---  
`SEPARATOR` | Specifies the special character that separates tokens (columns) in the data file. |  Any single ASCII character. Default: comma `,`
  * `\t for tab`
  * `\xy` for ASCII decimal code `xy`

  
`EOL` | Specifies the end-of-line character. |  Any ASCII sequence Default: `\n`(system-defined newline character or character sequence)  
`QUOTE` |  Specifies explicit boundary markers for string tokens, either single or double quotation marks. The parser will not treat separator characters found within a pair of quotation marks as a separator. For example, if the parsing conditions are `QUOTE="double", SEPARATOR=","`, the comma in `"Leonard,Euler"` will not separate Leonard and Euler into separate tokens.
  * If `QUOTE` is not declared, quotation marks are treated as ordinary characters.
  * If `QUOTE` is declared, but a string does not contain a matching pair of quotation marks, then the string is treated as if `QUOTE` is not declared.
  * Only the string inside the first pair of quote (from left to right) marks are loaded. For example `QUOTE="double"`, the string `a"b"c"d"e` will be loaded as b.
  * There is no escape character in the loader, so the only way to include quotation marks within a string is for the string body to use one type of quote (single or double) and to declare the other type as the string boundary marker.

| 
  * `"single"` for `'`
  * `"double"` for `"`

  
`HEADER` |  Whether the data file’s first line is a header line. The header assigns names to the columns. The `LOAD` statement must refer to an actual file with a valid header. |  `"true"`, `"false"`. Both values are strings and must be enclosed in double quotes. Default is `"false"`  
`USER_DEFINED_HEADER` | Specifies the name of the header variable, when a header has been defined in the loading job, rather than in the data file | The variable name in the preceding `DEFINE HEADER` statement  
`REJECT_LINE_RULE` | If the filter expression evaluates to true, then do not use this input data line. Not supported in a [ loading job](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/). | name of filter from a preceding `DEFINE INPUT_LINE_FILTER` statement  
`JSON_FILE` | Whether each line is a json object (see [Loading JSON Data](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_json_data) below for more details) |  `true`, `false` Default is `false`  
`NEW_VERTEX_ONLY` |  If true, treat vertices as insert-only. If the input data refers to a vertex which already exists, do not update it. If false, upsert vertices. |  `true`, `false` Default is `false`  
`VERTEX_MUST_EXIST` | If true, only insert or update an edge if both endpoint vertices already exist. If false, always insert new edges, creating endpoint vertices as needed, using given id and default values for other parameters. |  `true`, `false` Default is "false"  
### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_json_data)Loading JSON data
When the USING option `JSON_FILE="true"` is used, the loader loads JSON objects instead of tabular data. A JSON object is an unordered set of key/value pairs, where each value may itself be an array or object, leading to nested structures.A colon separates each key from its value, and a comma separates items in a collection.
**The JSON loader requires that each input line has exactly one JSON object (see[JSON lines](https://jsonlines.org/).**
The JSON loader uses JSON values as tokens, that is, the second part of each JSON key/value pair. In a GSQL loading job, a JSON field is identified by a dollar sign `$` followed by the colon-separated sequence of nested key names to reach the value from the top level. For example, given the JSON object `{"abc":{"def": "this_value"}}`, the identifier `$"abc":"def"` is used to access `"this_value"`.The double quotes are mandatory.
An example is shown below:
  * Loading job
  * .json file


JSON loading using EOL
```
CREATE VERTEX encoding (PRIMARY_ID id STRING, length FLOAT default 10)
CREATE UNDIRECTED EDGE encoding_edge (FROM encoding, TO encoding)
CREATE GRAPH encoding_graph (*)
CREATE LOADING JOB json_load FOR GRAPH encoding_graph {
 LOAD "encoding.jsonl" TO VERTEX encoding
  VALUES ($"encoding", $"indent":"length") USING JSON_FILE="true";
}
RUN LOADING JOB json_load
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

encoding.jsonl
```
{"encoding": "UTF-7","plug-ins":["c"],"indent" : { "length" : 30, "use_space": true }}
{"encoding":"UTF-1","indent":{"use_space": "dontloadme"}, "plug-ins" : [null, true, false] }
{"plug-ins":["C","c++"],"indent":{"length" : 3, "use_space": false},"encoding":"UTF-6"}
javascript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

[Download `encoding.jsonl`](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/_attachments/encoding.json)
In the aforementioned file, the order of fields are not fixed and some fields are missing. The JSON loader ignores the order and accesses the fields by the nested key names. The missing fields are loaded with default values. The result vertices are:
id | attr1  
---|---  
"UTF-7" | 30  
"UTF-1" | 0  
"UTF-6" | 3  
### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_parquet_data)Loading Parquet data
TigerGraph can load data from Parquet files using our loader. For more details on how to set up a Kafka data streaming connector and loading jobs, see [Data Loading Overview](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/data-loading-overview).
When loading Parquet data, INT96 data types are not supported. If your data source uses INT96 data types, the corresponding attribute in your graph will be left empty.   
---  
TigerGraph uses the JSON loading functionality to read data from Parquet files, so the [JSON specific information](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_json_data) in the previous section applies.
In order to load Parquet data, you need to:
  1. Specify `"file.reader.type": "parquet"` in the S3 file configuration file or argument
  2. Specify `JSON_FILE="true"` in the USING clause of the LOAD statements
  3. Refer to JSON keys (≈ Parquet "column names") instead of column numbers


You should consider adding `USING EOF="true"` to your `RUN LOADING JOB` statement to explicitly indicate to the loading job to stop after consuming all data from the Parquet source, not to expect further entries.
An example of a Parquet loading setup is shown below:
```
CREATE DATA_SOURCE S3 s3ds = "{\"file.reader.settings.fs.s3a.access.key\":\"myaccesskey\",\"file.reader.settings.fs.s3a.secret.key\":\"mysecretkey\"}" FOR GRAPH companyGraph
CREATE LOADING JOB parquet_load FOR GRAPH companyGraph {
  DEFINE FILENAME f = "$s3ds:{\"file.uris\": \"s3://mybucket/mydata.parquet\", \"file.reader.type\": \"parquet\"}";
  LOAD f
   TO VERTEX members VALUES($"members", $"members") USING JSON_FILE="true";
}
RUN LOADING JOB parquet_load USING EOF="true"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_attributes_and_attribute_expressions)Attributes and attribute expressions
A `LOAD` statement processes each line of an input file, splitting each lin into a sequence of tokens. Each destination clause provides a token-to-attribute mapping which defines how to construct a new vertex, an edge, or a temp table row instance (e.g., one data object). The tokens can also be thought of as the column values in a table. There are two ways to refer to a column, by position or by name. Assuming a column has a name, either method may be used, and both methods may be used within one expression.
**By Position** : The columns (tokens) are numbered from left to right, starting with $0. The next column is $1, and so on.
**By Name** : Columns can be named, either through a header line in the input file, or through a `DEFINE HEADER` statement. If a header line is used, then the first line of the input file should be structured like a data line, using the same separator characters, except that each column contains a column name string instead of a data value.Names are enclosed in double quotes, e.g. `$"age"`.
**Data file name:** $sys.file_name refers to the current input data file.
In a simple case, a token value is copied directly to an attribute.For example, in the following `LOAD` statement,
Example: using $sys.file_name in an attribute expression
```
LOAD "xx/yy/a.csv" TO VERTEX Person VALUES ($0, $1, $sys.file_name)
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * The `PRIMARY_ID` of a person vertex comes from column `$0` of the file "xx/yy/a.csv".
  * The next attribute of a person vertex comes from column `$1`.
  * The next attribute of a person vertex is given the value "xx/y/a.csv" (the filename itself).


Users do not need to explicitly define a primary ID. Given the attributes, one will be selected as the primary key.  
---  
### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_cumulative_loading)Cumulative loading
A basic principle in the GSQL Loader is cumulative loading. Cumulative loading means that a particular data object might be written to (i.e., loaded) multiple times, and the result of the multiple loads may depend on the full sequence of writes. This usually means that If a data line provides a valid data object, and the `WHERE` clause and `OPTION` clause are satisfied, then the data object is loaded.
  * **Valid input** : For each input data line, each destination clause constructs one or more new data objects. To be a **valid data object,** it must have an ID value of the correct type, have correctly typed attribute values, and satisfy the optional `WHERE` clause. If the data object is not valid, the object is rejected (skipped) and counted as an error in the log file. The rules for invalid attributes values are summarized below:
    1. `UINT`: Any non-digit character. (Out-of-range values cause overflow instead of rejection)
    2. `INT`: Any non-digit or non-sign character. (Out-of-range values cause overflow instead of rejection)
    3. `FLOAT` and `DOUBLE`: Any wrong format
    4. `STRING`, `FIXED_BINARY`: N/A
    5. `DATETIME`: Wrong format, invalid date time, or out of range.
    6. `BOOL`: Any value not listed later.
    7. Complex type: Depends on the field type or element type. Any invalid field (in `UDT`), element (in `LIST` or `SET`), key or value (in `MAP`) causes rejection.
  * **New data objects:** If a valid data object has a new ID value, then the data object is added to the graph store. Any attributes which are missing are assigned the default value for that data type or for that attribute.
  * **Overwriting existing data objects** : If a valid data object has an ID value for an existing object, then the new object overwrites the existing data object, with the following clarifications and exceptions:
    1. The attribute values of the new object overwrite the attribute values of the existing data object.
    2. **Missing tokens** : If a token is missing from the input line so that the generated attribute is missing, then that attribute retains its previous value.


A STRING token is never considered missing; if there are no characters, then the string is the empty string  
---  
  * **Skipping an attribute** : A `LOAD` statement can specify that a particular attribute should **not** be loaded by using the special character _ (underscore) as its attribute expression (attr_expr). You can not skip the primary key attributes for vertices or discriminator attributes for edges.


For example, the following statement skips the next-to-last attribute. This technique is used when it is known that the input data file does not contain data for every attribute.
```
LOAD TO VERTEX Person VALUES ($0, $1, _, $2)
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  1. If the load operation is creating a new vertex or edge, then the skipped attribute will be assigned the default value.
  2. If the load operation is overwriting an existing vertex or edge, then the skipped attribute will retain its existing value.


### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_more_complex_attribute_expressions)More complex attribute expressions
An attribute expression may use column tokens (e.g., `$0`), literals (constant numeric or string values), any of the built-in loader token functions, or a user-defined token function. Attribute expressions may **not** contain mathematical or boolean operators (such as `+`, `*`, `AND`). The rules for attribute expressions are the same as those for id expressions, but an attribute expression can additionally use a reducer function:
  * _id_expr_ := $column_number | $"column_name" | constant | $sys.file_name | token_function_name(_id_expr_ [, _id_expr_ ]*)
  * _attr_expr_ := _id_expr_ | REDUCE(reducer_function_name(id __expr_))


Note that token functions can be nested, that is, a token function can be used as an input parameter for another token function. The built-in loader token/reducer functions and user-defined token functions are described in the section "Built-In Loader Token Functions".
The subsections below describe details about loading particular data types.
### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_a_double_or_float_attribute)Loading a `DOUBLE` or `FLOAT` attribute
A floating point value has the basic format
```
[sign][digits].[digits](e|E)[sign][digits]
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

In the first case, the decimal point and following digits are required. In the second case, some digits are required (looking like an integer), and the following decimal point and digits are optional.
In both cases, the leading sign ("+" or "-") is optional. The exponent, using "e" or "E", is optional. Commas and extra spaces are not allowed.
Examples of valid and invalid floating point values
```
# Valid floating point values
-198256.03
+16.
-.00036
7.14285e15
9.99E-22

# Invalid floating point values
-198,256.03
9.99 E-22
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_a_datetime_attribute)Loading a `DATETIME` attribute
When loading data into a `DATETIME` attribute, the GSQL loader automatically reads a string representation of DateTime information and convert it to internal DateTime representation. The loader accepts any of the following string formats:
  * `%Y-%m-%d %H:%M:%S` (e.g., 2011-02-03 01:02:03)
  * `%Y/%m/%d %H:%M:%S` (e.g., 2011/02/03 01:02:03)
  * `%Y-%m-%dT%H:%M:%S.000z` (e.g., 2011-02-03T01:02:03.123z, 123 will be ignored)
  * `%Y-%m-%d` (only date, no time, e.g., 2011-02-03)
  * `%Y/%m/%d` (only date, no time, e.g., 2011/02/03)
  * Any integer value (Unix Epoch time, where Jan 1, 1970 at 00:00:00 is integer 0)


Format notation:
%Y is a 4-digit year. A 2-digit year is not a valid value.
%m and %s are a month (1 to 12) and a day (1 to 31), respectively. Leading zeroes are optional.
%H, %M, %S are hours (0 to 23), minutes (0 to 59) and seconds (0 to 59), respectively. Leading zeroes are optional.
When loading data, the loader checks whether the values of year, month, day, hour, minute, second are out of the valid range. If any invalid value is present, e.g. '2010-13-05' or '2004-04-31 00:00:00', the attribute is invalid and the object (vertex or edge) is not created.
#### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_load_static_datetime_values)Load static `DATETIME` values
GSQL automatically converts correctly formatted strings in a data source file into `DATETIME` values during loading. However, if you want to load static `DATETIME` values, you need to use `to_datetime()` to convert the strings into `DATETIME` values.
Once the strings have been converted to `DATETIME` values, you can use other `DATETIME` functions to modify the value you want loaded to the attribute.
For example, the following destination clause always loads the difference in the number of seconds (the first value minus the second value) between `"2020-01-01 00:00:00"` and `"2020-01-01 04:13:12"`, which is -2866392.
```
TO EDGE date_time_edge VALUES ($"account_id", $"account_id",
    datetime_diff(to_datetime("2020-01-01 00:00:00"), to_datetime("2020-02-03 04:13:12"))
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_a_bool_attribute)Loading a `BOOL` attribute
When loading data from CSV files the following values are accepted for BOOL attributes :
  * True: `TRUE`,`True`,`true`,`1`
  * False: `FALSE`,`False`,`false`,`0`


When loading data from JSON documents, the valid BOOL values are `true` and `false`.
### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_a_user_defined_type_udt_attribute)Loading a User-defined type (UDT) attribute
To load a UDT attribute, state the name of the UDT type, followed by the list of attribute expressions for the UDT’s fields, in parentheses. See the example below.
Load UDT example
```
TYPEDEF TUPLE <f1 INT (1), f2 UINT, f3 STRING (10), f4 DOUBLE > My_Tuple  // define a UDT
CREATE VERTEX Vertex_UDT (id STRING PRIMARY KEY, att_udt My_Tuple)
CREATE GRAPH Test_Graph (Vertex_UDT)
CREATE LOADING JOB load_udt FOR GRAPH Test_Graph {
  DEFINE FILENAME f;
  LOAD f TO VERTEX Vertex_UDT VALUES ($0, My_Tuple($1, $2, $3, $4));
  // $1 is loaded as f1, $2 is loaded as f2, and so on
}
RUN LOADING JOB load_udt USING f="./udt.csv"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_a_list_or_set_attribute)Loading a LIST or SET attribute
There are three methods to load a `LIST` or a `SET`.
The first method is to load multiple rows of data that share the same ID values and append the individual attribute values to form a collection of values. The collections are formed incrementally by reading one value from each eligible data line and appending the new value into the collection. When the loading job processes a line, it checks to see whether a vertex or edge with that id value(s) already exists or not. If the id value(s) is new, then a new vertex or edge is created with a new list/set containing the single value. If the id(s) has been used before, then the value from the new line is appended to the existing list/set. Below shows an example:
  * Schema and loading job
  * Data file


Example: Cumulative loading of multiple rows to a SET/LIST
```
CREATE VERTEX Test_Vertex (PRIMARY_ID id STRING, iset SET<INT>, ilist LIST<INT>)
CREATE UNDIRECTED EDGE Test_Edge(FROM Test_vertex, TO Test_vertex)
CREATE GRAPH Test_Set_List (*)
CREATE LOADING JOB load_set_list FOR GRAPH Test_Set_List {
 DEFINE FILENAME f;
 LOAD f TO VERTEX Test_Vertex VALUES ($0, $1, $1);
}
RUN LOADING JOB load_set_list USING f="./list_set_vertex.csv"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

[Download list_set_vertex.csv](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/_attachments/list_set_vertex.csv)
list_set_vertex.csv
```
1,10
3,30
1,20
3,30
3,40
1,20
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The job `load_set_list` will load two `test_vertex` vertices because there are two unique id values in the data file.Vertex 1 has attribute values with `iset = [10,20]` and `ilist = [10,20,20]`.Vertex 3 has values `iset = [30,40]` and `ilist = [30, 30, 40]`.Note that a set doesn’t contain duplicate values, while a list can contain duplicate values.
Because GSQL loading is multi-threaded, the order of values loaded into a LIST might not match the input order.  
---  
If the input file contains multiple columns which should be all added to the LIST or SET, then a second method is available.Use the LIST() or SET() function as in the example below:
Example: loading multiple columns to a SET/LIST
```
CREATE VERTEX V_Set (PRIMARY_ID id STRING, nick_names SET<STRING>)
CREATE VERTEX V_List (PRIMARY_ID id STRING, lucky_nums LIST<INT>)
CREATE GRAPH Test_Graph (*)
CREATE LOADING JOB load_set_list FOR GRAPH Test_Graph {
  DEFINE FILENAME f;
  LOAD f TO VERTEX v_set VALUES ($0, SET($1,$2,$3));
  LOAD f TO VERTEX v_list VALUES ($0, LIST($2,$4));
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The third method is to use the `SPLIT()` function to read a compound token and split it into a collection of elements, to form a `LIST` or `SET` collection. The `SPLIT()` function takes two arguments: the column index and the element separator. The element separator should be distinct from the separator throughout the whole file.Below shows an example:
  * Schema and loading job
  * Data file


Example: SET/LIST loading by SPLIT() example
```
CREATE VERTEX Test_Vertex (PRIMARY_ID id STRING, ustrset SET<STRING>, ilist LIST<INT>)
CREATE UNDIRECTED EDGE Test_Edge(FROM Test_Vertex, TO Test_Vertex)
CREATE GRAPH Test_Split (*)
CREATE LOADING JOB set_list_job FOR GRAPH Test_Split {
  DEFINE FILENAME f;
  LOAD f TO VERTEX Test_Vertex VALUES ($0, SPLIT($1,"|") , SPLIT($2,"#"));
}
RUN LOADING JOB set_list_job USING f="./split_list_set.csv"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

[Download split_test_set.csv](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/_attachments/split_list_set.csv)
split_list_set.csv
```
vid,names,numbers
v1,mike|tom|jack, 1 # 2 # 3
v2,john, 5 # 4 # 8
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The `SPLIT()` function cannot be used for UDT type elements.  
---  
### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_a_map_attribute)Loading a MAP attribute
There are three methods to load a `MAP`.
The first method is to load multiple rows of data that share the same ID values. The maps are formed incrementally by reading one key-value pair from each eligible data line. When the loading job processes a line, it checks to see whether a vertex or edge with that id value(s) already exists or not:
  * If the ID value(s) is new, then a new vertex or edge is created with a new map containing the single key-value pair.
  * If the ID(s) has been used before, then the loading job checks whether the key exists in the map or not.
    * If the key doesn’t exist in the map, the new key-value pair is inserted.
    * If the key does exist, the newly loaded value replaces the old value.


The loading order might not be the same as the order in the raw data. If a data file contains multiple lines with the same ID and same key but different values, loading them together results in a nondeterministic final value for that key.  
---  
#### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_load_rows_of_key_value_pairs_by_id)Load rows of key-value pairs by ID
To load rows of key-value pairs by ID, use the arrowhead `->` to indicate the key-value pair relationship between the columns, and enclose them in parentheses.
For example, key-value pairs with tokens in column 2 as keys and tokens in column 3 as values is denoted by the following: `($1 -> $2)`.
Loading a MAP by method 1: -> separator
```
CREATE VERTEX V_Map (PRIMARY_ID id STRING, att_map MAP<INT, STRING>)
CREATE GRAPH Test_Graph (*)
CREATE LOADING JOB load_map FOR GRAPH Test_Graph {
  DEFINE FILENAME f;
  LOAD f TO VERTEX v_map VALUES ($0, ($1 -> $2));
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_load_key_value_pairs_in_multiple_columns_with_map)Load key-value pairs in multiple columns with `MAP()`
The second method is to use the `MAP()` function. If there are multiple key-value pairs among multiple columns, `MAP()` can load them together:
Loading a MAP by method 2: MAP() function
```
CREATE VERTEX V_Map (PRIMARY_ID id STRING, att_map MAP<INT, STRING>)
CREATE GRAPH Test_Graph (*)
CREATE LOADING JOB load_map FOR GRAPH Test_Graph {
  DEFINE FILENAME f;
  LOAD f TO VERTEX V_Map VALUES ($0, MAP(($1 -> $2), ($3 -> $4)));
  // $1 and $3 are keys and $2 and $4 are the corresponding values.
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_load_key_value_pairs_by_splitting_values_in_one_column)Load key-value pairs by splitting values in one column
The third method is to use the `SPLIT()` function. The `SPLIT()` function can be used when the key-value pair is in one column and separated by a key-value separator, or multiple key-value pairs are in one column and separated by element separators and key-value separators.
`SPLIT()` has three parameters: The first is the column index, the second is the key-value separator, and the third is the element separator. The third parameter is optional. If one row of raw data only has one key-value pair, the third parameter can be skipped. Below are the examples without and with the given element separator.
  * Data file 1
  * Data file 2
  * Loading job


[Download one_key_value.csv](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/_attachments/one_key_value.csv)
Example data with one key-value pair per line
```
vid,key_value
v1,1:mike
v2,2:tom
v1,3:lucy
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

[Download multi_key_value.csv](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/_attachments/multi_key_value.csv)
Example data with multiple key-value pairs per line
```
vid,key_value_list
v1,1:mike#4:lin
v2,2:tom
v1,3:lucy#1:john#6:jack
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Loading a MAP by method 3: SPLIT() function
```
CREATE VERTEX v_map (PRIMARY_ID id STRING, att_map MAP<INT, STRING>)
CREATE GRAPH Test_Graph (*)
CREATE LOADING JOB load_map FOR GRAPH Test_Graph {
  DEFINE FILENAME f;
  LOAD f TO VERTEX v_map VALUES ($0, SPLIT($1, ":", "#"));
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The `SPLIT()` function cannot be used for UDT type elements.  
---  
### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_composite_key_attributes)Loading composite key attributes
Loading a Composite Key for a vertex works no differently than normal loading. Simply load all the attributes as you would for a vertex with a single-attribute primary key. The primary key will automatically be constructed from the appropriate attributes.
When loading to an edge where either `TO_VERTEX` or `FROM_VERTEX` contains a composite key, the composite set of attributes must be enclosed in parentheses. See the example below.
Example: loading composite key to vertex and edge
```
// Schema setup
CREATE VERTEX Composite_Person (id uint, name string, PRIMARY KEY (name,id))
CREATE VERTEX Composite_Movie (id uint, title string, country string, year uint, primary key (title,year,id))
CREATE DIRECTED EDGE Composite_Roles (from Composite_Person,to Composite_Movie, role string) with reverse_edge="composite_roles_reverse"
CREATE GRAPH My_Graph(*)
// Loading job
CREATE LOADING JOB composite_load FOR GRAPH My_Graph {
 LOAD "$sys.data_root/movies.csv" TO VERTEX Composite_Movie VALUES
    ($"id", $"title", $"country" ,$"year") USING header ="true", separator=",";
 LOAD "$sys.data_root/persons.csv" TO VERTEX Composite_Person VALUES
    ($"id",$"name") USING header = "true", separator =",";
 LOAD "$sys.data_root/compositeroles.csv" TO EDGE Composite_Roles VALUES
    (($"personName", $"personId"),($"movieTitle",$"movieYear",$"movieId"),$"role")
    USING header="true", separator = ",";
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_wildcard_type_edges)Loading Wildcard Type Edges
If an edge has been defined using a wildcard vertex type, a vertex type name must be specified, following the vertex id, in a `LOAD` statement for the edge. An example is shown below:
Example: explicit vertex typing for an untyped edge
```
// Schema setup
CREATE VERTEX User (PRIMARY_ID id UINT)
CREATE VERTEX Product (PRIMARY_ID id UINT)
CREATE VERTEX Picture (PRIMARY_ID id UINT)
CREATE UNDIRECTED EDGE Purchase (FROM *, TO *)
CREATE GRAPH Test_Graph(*)
// Loading job
CREATE LOADING JOB test_2 FOR GRAPH Test_Graph {
  DEFINE FILENAME f;
  LOAD f
   TO EDGE Purchase VALUES ($0 User, $1 Product),
   TO EDGE Purchase VALUES ($0 User, $2 Picture);
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_token_functions)Token functions
Token functions are functions in the DDL language that operate on tokens.Some may be used to construct attribute expressions and some may be used for conditional expressions in the `WHERE` clause.
To use a token function, replace the attribute in the destination clause of the `LOAD` statement with the function call.The arguments of the function can be a column from the `FILE` object.
#### Example
```
CREATE LOADING JOB load_orders {
  DEFINE FILENAME f;
  LOAD f
    TO VERTEX Order VALUES (gsql_trim($"id"), $"date");
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_token_functions_for_attribute_expressions)Token functions for attribute expressions
The following token functions can be used in an ID or attribute expression
Function | Output type | Description  
---|---|---  
gsql_reverse(_in_string_) | string | Returns a string with the characters in the reverse order of the input string _in_string_.  
gsql_concat(_string1, string2,…​,stringN_) | string | Returns a string which is the concatenation of all the input strings.  
gsql_uuid_v4() | string | Returns a version-4 UUID.  
gsql_split_by_space(_in_string_) | string | Returns a modified version of _in_string_ , in which each space character is replaced with ASCII 30 (decimal).  
gsql_substring(_str_ , _beginIndex_ [, _length_]) | string | Returns the substring beginning at _beginIndex_ , having the given _length_.  
gsql_find(_str_ , _substr_) | int | Returns the start index of the substring within the string. If it is not found, then return -1.  
gsql_length(_str_) | int | Returns the length of the string.  
gsql_replace(_str_ , _oldToken_ , _newToken_ [, _max_]) | string | Returns the string resulting from replacing all matchings of _oldToken_ with _newToken_ in the original string. If a _max_ count is provided, there can only be up to that many replacements.  
gsql_regex_replace(_str_ , _regex_ , _replaceSubstr_) | string | Returns the string resulting from replacing all substrings in the input string that match the given _regex_ token with the substitute string.  
gsql_regex_match(_str_ , _regex_) | bool | Returns true if the given string token matches the given regex token and false otherwise.  
gsql_to_bool(_in_string_) | bool | Returns true if the _in_string_ is either "t" or "true", with case-insensitive checking. Returns false otherwise.  
gsql_to_uint(_in_string_) | uint | 
  * If _in_string_ is the string representation of an unsigned int, the function returns that integer.
  * If _in_string_ is the string representation of a non-negative float, the function returns that number cast as an int.

  
gsql_to_int(_in_string_) | int | 
  * If _in_string_ is the string representation of an int, the function returns that integer.
  * If _in_string_ is the string representation of a float, the function returns that number cast as an int.

  
gsql_ts_to_epoch_seconds(_timestamp_) | uint | Converts a timestamp in canonical string format to Unix epoch time, which is the int number of seconds since Jan. 1, 1970. Refer to the timestamp input format note below.  
gsql_current_time_epoch(0) | uint | Returns the current time in Unix epoch seconds. *By convention, the input parameter should be 0, but it is ignored.  
flatten (_column_to_be_split, group_separator, 1_) flatten (_column_to_be_split, group_separator, sub_field_separator, number_of_sub_fields_in_one_group_) | See [`TEMP_TABLE` and flatten functions](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_temp_table_and_flatten_functions).  
flatten_json_array (_$"array_name"_) flatten_json_array (_$"array_name", $"sub_obj_1", $"sub_obj_2", …​, $"sub_obj_n"_) | See [`TEMP_TABLE` and flatten functions](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_temp_table_and_flatten_functions).  
split(_column_to_be_split, element_separator_) split(_column_to_be_split, key_value_separator, element _separator_) |  See [Loading a LIST or SET attribute](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_a_list_or_set_attribute) See [Loading a MAP attribute](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_loading_a_map_attribute)  
gsql_upper(_in_string_) | string | Returns the input string in upper-case.  
gsql_lower(_in_string_) | string | Returns the input string in lower-case.  
gsql_trim(_in_string_) | string | Trims whitespace from the beginning and end of the input string.  
gsql_ltrim(_in_string_) gsql_rtrim(_in_string_) | string | Trims white space from either the beginning or the end of the input string (Left or right).  
gsql_year(_timestamp_) | int | Returns 4-digit year from [timestamp](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_timestamp_input_format).  
_gsql_month(timestamp)_ | int | Returns month (1-12) from [timestamp](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_timestamp_input_format).  
gsql_day(_timestamp_) | int | Returns day (1-31) from [timestamp](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_timestamp_input_format).  
gsql_year_epoch(_epoch_) | int | Returns 4-digit year from Unix epoch time, which is the int number of seconds since Jan. 1, 1970.  
gsql_month_epoch(_epoch_) | int | Returns month (1-12) from Unix epoch time, which is the int number of seconds since Jan. 1, 1970.  
gsql_day_epoch(_epoch_) | int | Returns day (1-31) from Unix epoch time, which is the int number of seconds since Jan. 1, 1970.  
#### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_timestamp_input_format)Timestamp input format
The timestamp parameter should be in one of the following formats:
  * `"%Y-%m-%d %H:%M:%S"`
  * `"%Y/%m/%d %H:%M:%S"`
  * `"%Y-%m-%dT%H:%M:%S.000z"`
    * Text after the dot `.` is ignored


### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_token_functions_in_the_where_clause)Token functions in the `WHERE` clause
See [Token functions in the WHERE clause](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#token-functions-in-where-clause).
### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_user_defined_token_functions)User-defined token functions
Users can write their own token functions in C++ and install them in the GSQL system. To learn how to add a user-defined token function, see [Add a User-defined Token Function](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/add-token-function).
### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_reducer_functions)Reducer functions
A reducer function aggregates multiple values of a non-ID attribute into one attribute value of a single vertex or edge. Reducer functions are computed incrementally; that is, each time a new input token is applied, a new resulting value is computed.
To reduce and load aggregate data to an attribute, the attribute expression has the following form:
```
REDUCE(reducer_function (input_expr))
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

`reducer_function` is one of the functions in the following table. `input_expr` can include non-reducer functions, but reducer functions cannot be nested.
Each reducer function is overloaded so that one function can be used for several data types:
  * For primitive data types, the output type is the same as the type of the input expression `input_expr`.
  * For `LIST`, `SET`, and `MAP` containers, the _input_expr_ type is one of the [allowed element types](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/attribute-data-types#_collection_types) for these containers. The output is the entire container.


Function name | Return value  
---|---  
`max(arg)` | `INT`, `UINT`, `FLOAT`, `DOUBLE`: maximum of all `arg` values cumulatively received  
`min(arg)` | `INT`, `UINT`, `FLOAT`, `DOUBLE`: minimum of all `arg` values cumulatively received  
`add(arg)` | 
  * `INT`, `UINT`, `FLOAT`, `DOUBLE`: sum of all `arg` values cumulatively received
  * `STRING`: concatenation of all arg values cumulatively received
  * `LIST`, `SET` element: list/set of all `arg` values cumulatively received
  * `MAP` (key → value) pair: key-value dictionary of all key-value pair `arg` values cumulatively received:
    * If the values in the key-value pairs are `INT` or `DOUBLE` types, the return values are the sums of all values by key.
    * If the values in the key-value pairs are `STRING` type, the return values are concatenation of all values by key.
    * If the values in the key-value pairs are `UDT` or `DATETIME` types, the return values are the last loaded value.
If loading into an existing vertex, the new loaded key-value pairs accumulate with the existing pairs in the same way.

  
`and(arg)` | 
  * `BOOL`: `AND` of all `arg` values cumulatively received
  * `INT`, `UINT`: bitwise `AND` of all `arg` values cumulatively received

  
`or(arg)` | 
  * BOOL: `OR` of all `arg` values cumulatively received
  * INT, UINT: bitwise `OR` of all `arg` values cumulatively received

  
`overwrite(arg)` | 
  * Non-container: `arg`
  * `LIST`, `SET`: new list/set containing only `arg`

  
`ignore_if_exists(arg)` | Any: If an attribute value already exists, return(retain) the existing value.Otherwise, return(load) `arg` .  
Each function supports a certain set of attribute types. Calling a reducer function with an incompatible type crashes the service. In order to prevent that, use the `WHERE` clause together with `IS NUMERIC` or other operators, functions, predicates for type checking if necessary.  
---  
## [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_temp_table_and_flatten_functions)`TEMP_TABLE` and flatten functions
The keyword `TEMP_TABLE` triggers the use of a temporary data table which is used to store data generated by one `LOAD` statement, for use by a later `LOAD` statement.Earlier we introduced the syntax for loading data to a `TEMP_TABLE`:
TEMP_TABLE Destination Clause
```
TO TEMP_TABLE table_name (id_name [, attr_name]*) VALUES (id_expr [, attr_expr]*)
  [WHERE conditions] [OPTION (options)]
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This clause is designed to be used in conjunction with the `flatten` or `flatten_json_array` function in one of the `attr_expr` expressions.The flatten function splits a multi-value field into a set of records.Those records can first be stored in a temporary table, and then the temporary table can be loaded into vertices and/or edges.Only one flatten function is allowed in one temp table destination clause.
There are two versions of the flatten function: One parses single-level groups and the other parses two-level groups.There are also two versions of the flatten_json_array function: One splits an array of primitive values, and the other splits an array of JSON objects.
### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_one_level_flatten_function)One-level flatten function
`flatten (column_to_be_split, separator, 1)` is used to parse a one-level group into individual elements. An example is shown below:
The following loading job contains two `LOAD` statements. The first one loads input data to `Book` vertices and to a `TEMP_TABLE`. The second one loads the `TEMP_TABLE` data to `Genre` vertices and `Book_Genre` edges.
  * Schema and loading jobs
  * Data file


One-level Flatten Function loading (load_book_flatten1.gsql)
```
CREATE LOADING JOB load_books_flatten_1 FOR GRAPH Book_Rating {
  DEFINE FILENAME f;
  LOAD f
   TO VERTEX Book VALUES ($0, $1, _),
   TO TEMP_TABLE t1 (bookcode,genre) VALUES ($0, flatten ($2,",",1)) **(1)**
   USING QUOTE="double", SEPARATOR="|";
  LOAD TEMP_TABLE t1
   TO VERTEX Genre VALUES ($"genre", $"genre"),
   TO EDGE Book_Genre VALUES ($"bookcode", $"genre");
}
RUN LOADING JOB load_books_flatten_1 USING f="../data/book1.dat"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

[Download book1.dat](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/_attachments/book1.dat)
book1.dat
```
101|"Harry Potter and the Philosopher's Stone"|"fiction,fantasy,young adult"
102|"The Three-Body Problem"|"fiction,science fiction,Chinese"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Line 5 says that the third column (`$2`) of each input line should be split into separate tokens, with comma (`,`) as the separator. Each token will have its own row in table `t1`. The first column is labeled `bookcode` with value `$0` and the second column is `genre` with one of the `$2` tokens. The contents of `TEMP_TABLE t1` are shown below:
bookcode | genre  
---|---  
101 | fiction  
101 | fantasy  
101 | young_adult  
102 | fiction  
102 | science_fiction  
102 | Chinese  
Then, lines 8 to 10 say to read `TEMP_TABLE t1` and to do the following for each row:
  * Create a `Genre` vertex for each new value of `genre`.
  * Create a `Book_Genre` edge from `bookcode` to `genre`. In this case, each row of `TEMP_TABLE t1` generates one `Book_Genre` edge.


The final graph will contain two `Book` vertices (101 and 102), five Genre vertices, and six `Book_Genre` edges.
List of all Book_Genre edges after loading
```
{
 "results": [{"@@edgeSet": [
  {
   "from_type": "Book",
   "to_type": "Genre",
   "directed": false,
   "from_id": "101",
   "to_id": "fiction",
   "attributes": {},
   "e_type": "Book_Genre"
  },
  {
   "from_type": "Book",
   "to_type": "Genre",
   "directed": false,
   "from_id": "101",
   "to_id": "fantasy",
   "attributes": {},
   "e_type": "Book_Genre"
  },
  {
   "from_type": "Book",
   "to_type": "Genre",
   "directed": false,
   "from_id": "102",
   "to_id": "sciencevfiction",
   "attributes": {},
   "e_type": "Book_Genre"
  },
  {
   "from_type": "Book",
   "to_type": "Genre",
   "directed": false,
   "from_id": "101",
   "to_id": "young adult",
   "attributes": {},
   "e_type": "Book_Genre"
  },
  {
   "from_type": "Book",
   "to_type": "Genre",
   "directed": false,
   "from_id": "102",
   "to_id": "fiction",
   "attributes": {},
   "e_type": "Book_Genre"
  },
  {
   "from_type": "Book",
   "to_type": "Genre",
   "directed": false,
   "from_id": "102",
   "to_id": "Chinese",
   "attributes": {},
   "e_type": "Book_Genre"
  }
 ]}]
}
javascript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_two_level_flatten_function)Two-level flatten function
flatten (_column_to_be_split, group_separator, sub_field_separator, number_of_sub_fields_in_one_group_) is used for parse a two-level group into individual elements. Each token in the main group may itself be a group, so there are two separators: one for the top level and one for the second level. An example is shown below.
book2.dat
```
101|"Harry Potter and the Philosopher's Stone"|"FIC:fiction,FTS:fantasy,YA:young adult"
102|"The Three-Body Problem"|"FIC:fiction,SF:science fiction,CHN:Chinese"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The flatten function now has four parameters instead of three. The additional parameter is used to record the genre_name in the Genre vertices.
Two-level Flatten Function loading (book_flatten2_load.gsql)
```
CREATE LOADING JOB load_books_flatten_2 FOR GRAPH Book_Rating {
  DEFINE FILENAME f;
  LOAD f
    TO VERTEX Book VALUES ($0, $1, _),
    TO TEMP_TABLE t2(bookcode,genre_id,genre_name) VALUES ($0, flatten($2,",",":",2))
    USING QUOTE="double", SEPARATOR="|";
  LOAD TEMP_TABLE t2
    TO VERTEX Genre VALUES($"genre_id", $"genre_name"),
    TO EDGE Book_Genre VALUES($"bookcode", $"genre_id");
}
RUN LOADING JOB load_books_flatten_2 USING f="book2.dat"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

In this example, in the genres column ($2), there are multiple groups, and each group has two sub-fields, genre_id and genre_name. After running the loading job, the file book2.dat will be loaded into the TEMP_TABLE t2 as shown below.
bookcode | genre_id  
---|---  
101 | FIC | fiction  
101 | FTS | fantasy  
101 | YA | young adult  
102 | FIC | fiction  
102 | SF | science fiction  
102 | CHN | Chinese  
### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_flatten_a_json_array_of_primitive_values)Flatten a JSON array of primitive values
When loading JSON lines, each line is a JSON object. If a value field of the JSON object is a JSON array of primitive values , you can use `flatten_json_array()` to flatten the array:
  * Data file
  * Loading job
  * Temporary table


For example, if we have the following [JSON line file](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/_attachments/encoding2.json). The `plug-in` field is a JSON array of primitive values:
encoding2.json
```
{"plug-ins" : ["C", "c++"],"encoding" : "UTF-6","indent" : { "length" : 3, "use_space": false}}
javascript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The function flattens the array, and loads each item in the array into a temporary table. Each value in the array creates a record.
```
CREATE VERTEX Encoding (PRIMARY_ID id STRING, length FLOAT DEFAULT 10)
CREATE UNDIRECTED EDGE Encoding_Edge (FROM encoding, TO encoding)
CREATE GRAPH Encoding_Graph (*)
CREATE LOADING JOB json_flatten FOR GRAPH Encoding_Graph {
  LOAD "encoding2.json" TO TEMP_TABLE t2 (name, length)
   VALUES (flatten_json_array($"plug-ins"), $"indent":"length") USING JSON_FILE ="true";
  LOAD TEMP_TABLE t2
   TO VERTEX encoding VALUES ($"name", $"length");
}
RUN LOADING JOB json_flatten
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The data and loading job creates the following temporary table:
id | length  
---|---  
C | 3  
c++ | 3  
### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_flatten_a_json_array_of_json_objects)Flatten a JSON array of JSON objects
When loading JSON lines, each line is a JSON object. If a value field of the JSON object is a JSON array of JSON objects , you can use `flatten_json_array()` to flatten the array:
When splitting a JSON array of JSON objects, the primitive values in the array are skipped and only JSON objects are processed.
  * Data file
  * Loading job


For example, if we have the following [JSON line file](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/_attachments/encoding3.json). There is a `plug-in` field in each JSON object, and it is an array.
encoding3.json
```
{"encoding":"UTF-1","indent":{"use_space": "dontloadme"}, "plug-ins" : [null, true, false, {"lang":"golang","prop":{"age":"noidea"}}]}
{"encoding": "UTF-8", "plug-ins" : [{"lang": "pascal", "score":"1.0", "prop":{"age":"old"}}, {"lang":"c++", "score":2.0}],"indent":{"length" :12,"use_space": true}}
{"encoding": "UTF-7", "plug-ins" : [{"lang":"java", "score":2.22}, {"lang":"python", "score":3.0},{"lang":"go", "score":4.0, "prop":{"age":"new"}}],"indent" : { "length" : 30, "use_space": true }}
{"plug-ins" : ["C", "c++"],"encoding" : "UTF-6","indent" : { "length" : 3, "use_space": false}}
javascript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The `flatten_json_array()` function in the destination clause returns three values to the three columns in the temporary table. The `lang` field corresponds to the `name` column; the `score` field corresponds to the `score` column; the `age` field of the `prop` field corresponds to the `prop_age` column. These columns are subsequently loaded into to the vertices.
The fourth line in the original file does not generate any value, because the `plug-in` field does not contain any JSON object.
json_flatten_array_test.gsql
```
CREATE VERTEX Encoding3 (PRIMARY_ID id STRING, score FLOAT default -1.0, age STRING default "Unknown", length INT default -1)
CREATE UNDIRECTED EDGE Encoding3_Edge (FROM Encoding3, TO Encoding3)
CREATE GRAPH Encoding_Graph (*)
CREATE LOADING JOB json_flatten_array FOR GRAPH Encoding_Graph {
 LOAD "encoding3.json" TO TEMP_TABLE t3 (name, score, prop_age, indent_length)
  VALUES (flatten_json_array($"plug-ins", $"lang", $"score", $"prop":"age"), $"indent":"length")
  USING JSON_FILE="true";
 LOAD TEMP_TABLE t3
  TO VERTEX encoding3 VALUES ($"name", $"score", $"prop_age", $"indent_length");
}
RUN LOADING JOB json_flatten_array
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_flatten_a_json_object_in_a_csv_file)Flatten a JSON object in a CSV file
The function can also be used to flatten a JSON object in a CSV file.
  * Data file
  * Loading job
  * Temporary table


If we have [the following CSV file](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/_attachments/encoding.csv). The second column in the CSV file is a JSON object we want to flatten.
encoding.csv
```
golang|{"prop":{"age":"noidea"}}
pascal|{"score":"1.0", "prop":{"age":"old"}}
c++|{"score":2.0, "indent":{"length":12, "use_space": true}}
java|{"score":2.22, "prop":{"age":"new"}, "indent":{"use_space":"true", "length":2}}
python|{ "prop":{"compiled":"false"}, "indent":{"length":4}, "score":3.0}
go|{"score":4.0, "prop":{"age":"new"}}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

`flatten_json_array()` can be used in this case without the `USING JSON_FILE="true"` clause:
json_flatten_cvs.gsql
```
CREATE VERTEX Encoding3 (PRIMARY_ID id STRING, score FLOAT default -1.0, age STRING default "Unknown", length INT default -1)
CREATE UNDIRECTED EDGE Encoding3_Edge (FROM Encoding3, TO Encoding3)
CREATE GRAPH Encoding_Graph (*)
CREATE LOADING JOB json_flatten_cvs FOR GRAPH Encoding_Graph {
 LOAD "encoding.csv" TO TEMP_TABLE t4 (name, score, prop_age, indent_length)
  VALUES ($0,flatten_json_array($1, $"score", $"prop":"age", $"indent":"length"))
  USING SEPARATOR="|";
 LOAD TEMP_TABLE t4
  TO VERTEX Encoding3 VALUES ($"name", $"score", $"prop_age", $"indent_length");
}
RUN LOADING JOB json_flatten_cvs
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The example generates the temporary table shown below:
id | score | age | length  
---|---|---|---  
golang | -1 (default) | noidea | -1 (default)  
pascal | 1 | old | -1 (default)  
c++ | 2 | unknown (default) | 12  
java | 2.22 | new | 2  
python | 3 | unknown (default) | 4  
go | 4 | new | -1 (default)  
## [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/creating-a-loading-job#_delete_statement)DELETE statement
In addition to loading data, a loading job can be used to perform the opposite operation: deleting vertices and edges, using the `DELETE` statement.
Just as a `LOAD` statement uses the tokens from each input line to set the id and attribute values of a vertex or edge to be created, a `DELETE` statement uses the tokens from each input line to specify the id value of the item(s) to be deleted.
There are four variations of the DELETE statement.The syntax of the four cases is shown below.
DELETE VERTEX | EDGE Syntax
```
CREATE LOADING JOB abc FOR GRAPH Graph_Name {
 DEFINE FILENAME f;
 // Delete each vertex which has the given vertex type and primary id.
 DELETE VERTEX vertex_type_name (PRIMARY_ID id_expr) FROM f [WHERE condition] ;
 // Delete each edge which has the given edge type, source vertex id, target vertex id, and discriminator value if provided.
 DELETE EDGE edge_type_name (FROM id_expr, TO id_expr[, DISCRIMINATOR (id_expr)] ) FROM f [WHERE condition] ;
 // Delete all edges which have the given edge type and source vertex id. (Destination vertex id is left open.)
 DELETE EDGE edge_type_name (FROM id_expr) FROM f [WHERE condition] ;
 // Delete all edges which have the given source vertex id. (Edge type and destination vertex id are left open.)
 DELETE EDGE * (FROM id_expr vertex_type_name) FROM f [WHERE condition] ;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

An example using Book_Rating data is shown below:
DELETE example
```
// Delete all user occupation edges if the user is in the new files, then load the new files
CREATE LOADING JOB clean_user_occupation FOR GRAPH Book_Rating {
 DEFINE FILENAME f;
 DELETE EDGE User_Occupation (FROM $0) FROM f;
}
CREATE LOADING JOB load_user_occupation FOR GRAPH Book_Rating {
 DEFINE FILENAME f;
 LOAD f TO EDGE User_Occupation VALUES ($0,$1);
}
RUN LOADING JOB clean_user_occupation USING f="./data/User_Occupation_update.dat"
RUN LOADING JOB load_user_occupation USING f="./data/User_Occupation_update.dat"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The following example shows how to delete edge instances that match the discriminator value from the data file:
```
DELETE EDGE Study_At (from $"person_id", to $"university_id",
  DISCRIMINATOR($"class_year", $"class_month")) from f;
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Multiple edges that match certain criteria can be deleted at the same time.
DELETE example for multiple edges
```
// Delete all edges matching a from_id
GSQL > DELETE FROM Medium-(signIn)->Account WHERE from_id=="3076"
// Delete all edges matching a from_id and a to_id
GSQL > DELETE FROM Medium-(signIn)->Account WHERE from_id=="3076" AND to_id=="40348"
// Delete a certain number of edges matching a pattern using ORDER BY … and LIMIT
GSQL > DELETE FROM Medium-(signIn)->Account WHERE from_id=="3076" AND to_id=="40348" ORDER BY creationDate DESC LIMIT 1
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

In the last example, the `LIMIT` keyword is used with `ORDER BY` to remove the top result. If `LIMIT` were set greater than `1`, it would remove additional results, starting at the most recent `creationDate` and moving down.
There is a separate DELETE statement in the GSQL Query Language. The query delete statement can leverage the query language’s ability to explore the graph and to use complex conditions to determine which items to delete. In contrast, the loading job delete statement requires that the id values of the items to be deleted must be specified in advance in an input file.  
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


