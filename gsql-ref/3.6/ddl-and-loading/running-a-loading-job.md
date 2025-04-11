![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job)[Next](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job)
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
[Resources](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job)
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
  * Database definition & Loading
  * [Running a Loading Job](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/3.6/modules/ddl-and-loading/pages/running-a-loading-job.adoc)
### Contents
  * [Clearing and Initializing the Graph Store](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_clearing_and_initializing_the_graph_store)
  * [CLEAR GRAPH STORE](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_clear_graph_store)
  * [Running a Loading Job](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_running_a_loading_job)
  * [RUN LOADING JOB](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_run_loading_job)
  * [Options](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_options)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_parameters)
  * [Running Loading Jobs as REST Requests](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_running_loading_jobs_as_rest_requests)
  * [Inspecting and Managing Loading Jobs](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_inspecting_and_managing_loading_jobs)
  * [Job ID and Status](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_job_id_and_status)
  * [SHOW LOADING STATUS](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_show_loading_status)
  * [ABORT LOADING JOB](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_abort_loading_job)
  * [RESUME LOADING JOB](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_resume_loading_job)
  * [Verifying and debugging a loading job](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_verifying_and_debugging_a_loading_job)


# Running a Loading Job
### Contents
  * [Clearing and Initializing the Graph Store](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_clearing_and_initializing_the_graph_store)
  * [CLEAR GRAPH STORE](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_clear_graph_store)
  * [Running a Loading Job](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_running_a_loading_job)
  * [RUN LOADING JOB](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_run_loading_job)
  * [Options](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_options)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_parameters)
  * [Running Loading Jobs as REST Requests](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_running_loading_jobs_as_rest_requests)
  * [Inspecting and Managing Loading Jobs](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_inspecting_and_managing_loading_jobs)
  * [Job ID and Status](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_job_id_and_status)
  * [SHOW LOADING STATUS](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_show_loading_status)
  * [ABORT LOADING JOB](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_abort_loading_job)
  * [RESUME LOADING JOB](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_resume_loading_job)
  * [Verifying and debugging a loading job](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_verifying_and_debugging_a_loading_job)


## [](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_clearing_and_initializing_the_graph_store)Clearing and Initializing the Graph Store
There are two aspects to clearing the system: flushing the data and clearing the schema definitions in the catalog. Two different commands are available.
### [](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_clear_graph_store)CLEAR GRAPH STORE
The `CLEAR GRAPH STORE` command flushes all the data out of the graph store (database). By default, the system asks the user to confirm that you really want to discard all the graph data. To force the clear operation and bypass the confirmation question, use the `-HARD` option,
```
CLEAR GRAPH STORE -HARD
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Clearing the graph store does not affect the schema.
  * Use the `-HARD` option with extreme caution. There is no undo option. `-HARD` must be in all capital letters.
  * `CLEAR GRAPH STORE` stops all the TigerGraph servers (GPE, GSE, RESTPP, Kafka, and Zookeeper).
  * Loading jobs and queries are aborted.

  
---  
[`DROP ALL`](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/defining-a-graph-schema#_drop_all) clears both the data and the schema.
## [](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_running_a_loading_job)Running a Loading Job
Running a loading job executes a previously installed loading job. The job reads lines from an input source, parses each line into data tokens, and applies loading rules and conditions to create new vertex and edge instances to store in the graph data store. The input sources could be defined in the load job or could be provided when running the job. Additionally, loading jobs can also be run by submitted an HTTP request to the REST++ server.
### [](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_run_loading_job)RUN LOADING JOB
`RUN LOADING JOB` syntax for concurrent loading
```
RUN LOADING JOB [-noprint] [-dryrun] [-n [i],j] job_name [
  USING file_var [="file_path_string"][, file_var [="file_path_string"]]*
  [, CONCURRENCY=cnum][,BATCH_SIZE=bnum][,EOF="eof_mode"]
]
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

When a concurrent loading job is submitted, it is assigned a job ID number, which is displayed on the GSQL console. The user can use this job ID to refer to the job, for a status update, to abort the job, or to restart the job. These operations are described later in this section.
### [](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_options)Options
#### [](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_noprint)`-noprint`
By default, the command will print several lines of status information while the loading is running. If the -noprint option is included, the output will omit the progress and summary details, but it will still display the job id and the location of the log file.
Example of minimal output when `-noprint` option is used
```
Kick off the following job:
 JobName: load_videoE, jobid: gsql_demo_m1.1525091090494
 Loading log: '/usr/local/tigergraph/logs/restpp/restpp_loader_logs/gsql_demo/gsql_demo_m1.1525091090494.log'
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_dryrun)`-dryrun`
If -dryrun is used, the system will read the data files and process the data as instructed by the job, but will NOT load any data into the graph. This option can be a useful diagnostic tool.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_n_i_j)`-n [i], j`
The `-n` option limits the loading job to processing only a range of lines of each input data file. The -n flag accepts one or two arguments.
For example, `-n 50` means read lines 1 to 50. `-n 10, 50` means read lines 10 to 50. The special symbol `$` is interpreted as "last line", so `-n 10,$` means reads from line 10 to the end.
### [](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_parameters)Parameters
Below are the parameters available for the `RUN QUERY` command introduced by the `USING` clause.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_filevar_list)`filevar` list
The optional `USING` clause may contain a list of file variables. Each file variable may optionally be assigned a `filepath_string`, obeying the same format as in the `CREATE LOADING JOB`. This list of file variables determines which parts of a loading job are run and what data files are used.
  * When a loading job is compiled, it generates one RESTPP endpoint for each `filevar` and `filepath_string`. As a consequence, a loading job can be run in parts. When `RUN LOADING JOB` is executed, only those endpoints whose `filevar` or file identifier (`__GSQL_FILENAME_n__`) is mentioned in the `USING` clause will be used. However, if the `USING` clause is omitted, then the entire loading job will be run.
  * If a `filepath_string` is given, it overrides the `filepath_string` defined in the loading job. If a particular `filevar` is not assigned a `filepath_string` either in the loading job or in the `RUN LOADING JOB` statement, then an error is reported and the job exits.


#### [](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_concurrency)`CONCURRENCY`
The `CONCURRENCY` parameter sets the maximum number of concurrent requests that the loading job may send to the GPE. The default is 256.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_batch_size)`BATCH_SIZE`
The `BATCH_SIZE` parameter sets the number of data lines included in each concurrent request sent to the GPE. The default is 8192.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_eof)`EOF`
This is a boolean parameter. The loader has two modes: streaming mode (`"False"`) and EOF mode (`"True"`). The default mode is (`"False"`): streaming mode.
  * In streaming mode, loading will never stop until the job is aborted.
  * In EOF mode, loading will stop after consuming the provided file objects.


### [](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_running_loading_jobs_as_rest_requests)Running Loading Jobs as REST Requests
Another way to run a loading job is through the `POST /ddl/{graph_name}` endpoint of the REST++ server. Since the REST++ server has more direct access to the graph processing engine, this can execute more quickly than a `RUN LOADING JOB` statement in GSQL. For details on how to use the endpoint, please see [Run a loading job](https://docs.tigergraph.com/tigergraph-server/3.6/API/built-in-endpoints#_run_a_loading_job).
## [](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_inspecting_and_managing_loading_jobs)Inspecting and Managing Loading Jobs
Starting with v2.0, there are now commands to check loading job status, abort a loading job and, restart a loading job.
### [](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_job_id_and_status)Job ID and Status
When a loading job starts, the GSQL server assigns it a job id and displays it for the user to see. The job id format is typically the name of the graph, followed by the machine alias, following by a code number, e.g., `gsql_demo_m1.1525091090494`
Example of `SHOW LOADING STATUS` output
```
Kick off the following job, i.e.
 JobName: load_test1, jobid: demo_graph_m1.1523663024967
 Loading log: '/home/tigergraph/tigergraph/logs/restpp/restpp_loader_logs/demo_graph/demo_graph_m1.1523663024967.log'
Job "demo_graph_m1.1523663024967" loading status
[RUNNING] m1 ( Finished: 3 / Total: 4 )
 [LOADING] /data/output/company.data
 [=============            ] 20%, 200 kl/s
 [LOADED]
 +-------------------------------------------------------------------+
 |        FILENAME |  LOADED LINES |  AVG SPEED |  DURATION|
 | /data/output/movie.dat |      100 |   100 l/s |   1.00 s|
 |/data/output/person.dat |      100 |   100 l/s |   1.00 s|
 | /data/output/roles.dat |      200 |   200 l/s |   1.00 s|
 +-------------------------------------------------------------------+
[RUNNING] m2 ( Finished: 1 / Total: 2 )
 [LOADING] /data/output/company.data
 [==========================      ] 60%, 200 kl/s
 [LOADED]
 +-------------------------------------------------------------------+
 |        FILENAME |  LOADED LINES |  AVG SPEED |  DURATION|
 | /data/output/movie.dat |      100 |   100 l/s |   1.00 s|
 +-------------------------------------------------------------------+
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

By default, an active loading job will display periodic updates of its progress. There are two ways to inhibit these automatic output displays:
  * Run the loading job with the `-noprint` option.
  * After the loading job has started, enter CTRL+C. This will abort the output display process, but the loading job will continue.


### [](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_show_loading_status)`SHOW LOADING STATUS`
The command `SHOW LOADING STATUS` shows the current status of either a specified loading job or all current jobs:
SHOW LOADING JOB syntax
```
SHOW LOADING STATUS job_id|ALL
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The display format is the same as that displayed during the periodic progress updates of the [`RUN LOADING JOB` command](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_run_loading_job). If you do not know the job id, but you know the job name and possibly the machine, then the ALL option is a handy way to see a list of active job ids.
### [](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_abort_loading_job)`ABORT LOADING JOB`
The command ABORT LOADING JOB aborts either a specified load job or all active loading jobs:
ABORT LOADING JOB syntax
```
ABORT LOADING JOB job_id|ALL
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The output will show a summary of aborted loading jobs.
ABORT LOADING JOB example
```
gsql -g demo_graph "abort loading job all"
Job "demo_graph_m1.1519111662589" loading status
[ABORT_SUCCESS] m1
[SUMMARY] Finished: 0 / Total: 2
 +--------------------------------------------------------------------------------------+
 |         FILENAME |  LOADED LINES |  AVG SPEED |  DURATION |  PERCENTAGE|
 | /home/tigergraph/data.csv |    23901701 |   174 kl/s |  136.83 s |     65 %|
 |/home/tigergraph/data1.csv |       0 |    0 l/s |   0.00 s |     0 %|
 +--------------------------------------------------------------------------------------+
Job "demo_graph_m2.1519111662615" loading status
[ABORT_SUCCESS] m2
[SUMMARY] Finished: 0 / Total: 2
 +--------------------------------------------------------------------------------------+
 |         FILENAME |  LOADED LINES |  AVG SPEED |  DURATION |  PERCENTAGE|
 | /home/tigergraph/data.csv |    23860559 |   175 kl/s |  136.23 s |     65 %|
 |/home/tigergraph/data1.csv |       0 |    0 l/s |   0.00 s |     0 %|
 +--------------------------------------------------------------------------------------+
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_resume_loading_job)`RESUME LOADING JOB`
The command RESUME LOADING JOB will restart a previously-run job which ended for some reason before completion.
RESUME LOADING JOB syntax
```
RESUME LOADING JOB job_id
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

If the job is finished, this command will do nothing. The RESUME command should pick up where the previous run ended; that is, it should not load the same data twice.
RESUME LOADING JOB example
```
gsql -g demo_graph "RESUME LOADING JOB demo_graph_m1.1519111662589"
[RESUME_SUCCESS] m1
[MESSAGE] The current job got resummed
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job#_verifying_and_debugging_a_loading_job)Verifying and debugging a loading job
Every loading job creates a log file. When the job starts, GSQL display the location of the log file.
This file contains the following information which most users will find useful:
  * A list of all the parameter and option settings for the loading job
  * A copy of the status information that is printed
  * Statistics report on the number of lines successfully read and parsed


The statistics report include how many objects of each type is created, and how many lines are invalid due to different reasons. This report also shows which lines cause the errors.
There are two types of statistics shown in the report:
  * File-level: The number of lines
  * Data-object-level: The number of objects


If a file level error occurs, e.g., a line does not have enough columns, this line of data is skipped for all LOAD statements in this loading job. If an object level error or failed condition occurs, only the corresponding object is not created, i.e., all other objects in the same loading job are still created if no object level error or failed condition for each corresponding object.
File level statistics | Explanation  
---|---  
Valid lines | The number of valid lines in the source file  
Reject lines | The number of lines which are rejected by reject_line_rules  
Invalid Json format | The number of lines with invalid JSON format  
Not enough token | The number of lines with missing column(s)  
Oversize token | The number of lines with oversize token(s). Please increase "OutputTokenBufferSize" in the `tigergraph/app/<VERSION_NUM>/dev/gdk/gsql/config` file.  
Object level statistics | Explanation  
---|---  
Valid Object | The number of objects which have been loaded successfully  
No ID found | The number of objects in which PRIMARY_ID is empty  
Invalid Attributes | The number of invalid objects caused by wrong data format for the attribute type  
Invalid primary id | The number of invalid objects caused by wrong data format for the PRIMARY_ID type  
incorrect fixed binary length | The number of invalid objects caused by the mismatch of the length of the data to the type defined in the schema  
Note that failing a `WHERE` clause is not necessarily a bad result. If the user’s intent for the `WHERE` clause is to select only certain lines, then it is natural for some lines to pass and some lines to fail.
Below is an example.
```
CREATE VERTEX Movie (PRIMARY_ID id UINT, title STRING, country STRING, year UINT)
CREATE DIRECTED EDGE Sequel_Of (FROM Movie, TO Movie)
CREATE GRAPH Movie_Graph(*)
CREATE LOADING JOB load_movie FOR GRAPH Movie_Graph{
 DEFINE FILENAME f
 LOAD f TO VERTEX Movie VALUES ($0, $1, $2, $3) WHERE to_int($3) < 2000;
}
RUN LOADING JOB load_movie USING f="movie.dat"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

movie.dat
```
0,abc,USA,-1990
1,abc,CHN,1990
2,abc,CHN,1990
3,abc,FRA,2015
4,abc,FRA,2005
5,abc,USA,1990
6,abc,1990
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The above loading job and data generate the following report
load_output.log (tail)
```
--------------------Statistics------------------------------
Valid lines:       6
Reject lines:      0
Invalid Json format:   0
Not enough token:    1 [ERROR] (e.g. 7)
Oversize token:     0
Vertex:         Movie
Valid Object:      3
No ID found:       0
Invalid Attributes:   1 [ERROR] (e.g. 1:year)
Invalid primary id:   0
Incorrect fixed
binary length:      0
Passed condition lines: 4
Failed condition lines: 2 (e.g. 4,5)
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

There are a total of 7 data lines. The report shows that
  * Six of the lines are valid data lines
  * One line - Line 7 - does not have enough tokens.


Of the 6 valid lines,
  * Three of the 6 valid lines generate valid movie vertices.
  * One line has an invalid attribute (Line 1: year)
  * Two lines (Lines 4 and 5) do not pass the WHERE clause.


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


