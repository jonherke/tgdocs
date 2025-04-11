![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/3.10/querying/distributed-query-mode)[Next](https://docs.tigergraph.com/gsql-ref/3.10/querying/distributed-query-mode)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/3.10/querying/distributed-query-mode)
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
[Resources](https://docs.tigergraph.com/gsql-ref/3.10/querying/distributed-query-mode)
[Developer Site](https://dev.tigergraph.com/) [Community Forum](https://community.tigergraph.com/) [Knowledge Base](https://tigergraph.freshdesk.com/support/solutions)
[Download](https://dl.tigergraph.com)
[ TG Savanna](https://savanna.tgcloud.io)
### [GSQL Language Reference](https://docs.tigergraph.com/gsql-ref/3.10/intro/)
  *     * [Overview](https://docs.tigergraph.com/gsql-ref/3.10/intro/)
    * [What sets GSQL apart](https://docs.tigergraph.com/gsql-ref/3.10/intro/set-gsql-apart)
  *     * Tutorials
      * [GSQL 101](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/)
        * [Define a Schema](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/define-a-schema)
        * [Load Data](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/load-data-gsql-101)
        * [Run Built-in Queries](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/built-in-select-queries)
        * [Parameterized Queries](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/parameterized-gsql-query)
        * [Review](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/gsql-101/review)
      * [Pattern Matching Tutorial](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/pattern-matching/)
        * [Prepare your Environment](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/pattern-matching/prepare-environment)
        * [One-hop patterns](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/pattern-matching/one-hop-patterns)
        * [Repeating a 1-Hop Pattern](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/pattern-matching/repeating-a-pattern)
        * [Multiple Hop Patterns and Accumulation](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/pattern-matching/multiple-hop-and-accumulation)
        * [Example - A Recommender](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/pattern-matching/example)
        * [Advanced Features](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/pattern-matching/adv/)
          * [Per Clause (Beta)](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/pattern-matching/adv/per-clause)
          * [Conjunctive Pattern Matching (Beta)](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/pattern-matching/adv/conjunctive-pattern-matching)
          * [Data Modification](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/pattern-matching/adv/dml)
        * [Summary](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/pattern-matching/summary)
      * [Accumulators Tutorial](https://docs.tigergraph.com/gsql-ref/3.10/tutorials/accumulators-tutorial)
  *     * [System & Language Basics](https://docs.tigergraph.com/gsql-ref/3.10/basics/system-and-language-basics)
  *     * [Attribute Data Types](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/attribute-data-types)
    * [Schema Definition](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/)
      * [Define a Graph Schema](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/defining-a-graph-schema)
      * [Modify a Graph Schema](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/modifying-a-graph-schema)
    * [Loading Jobs](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/loading-jobs)
      * [Create a Loading Job](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/creating-a-loading-job)
        * [Functions](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/)
          * [Token Functions](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/)
            * [flatten()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/flatten)
            * [flatten_json_array()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/flatten_json_array)
            * [gsql_concat()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_concat)
            * [gsql_current_time_epoch()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_current_time_epoch)
            * [gsql_day()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_day)
            * [gsql_day_epoch()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_day_epoch)
            * [gsql_find()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_find)
            * [gsql_length()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_length)
            * [gsql_lower()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_lower)
            * [gsql_ltrim()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_ltrim)
            * [gsql_month()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_month)
            * [gsql_month_epoch()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_month_epoch)
            * [gsql_regex_match()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_regex_match)
            * [gsql_regex_replace()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_regex_replace)
            * [gsql_reverse()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_reverse)
            * [gsql_rtrim()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_rtrim)
            * [gsql_substring()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_substring)
            * [gsql_to_bool()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_to_bool)
            * [gsql_to_int()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_to_int)
            * [gsql_to_uint()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_to_uint)
            * [gsql_trim()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_trim)
            * [gsql_ts_to_epoch_seconds()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_ts_to_epoch)
            * [gsql_upper()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_upper)
            * [gsql_uuid_v4()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_uuid_v4)
            * [gsql_year()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_year)
            * [gsql_year_epoch()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/gsql_year_epoch)
            * [split()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token/split)
          * [Token Functions in WHERE Clause](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token_where/)
            * [concat()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token_where/concat)
            * [gsql_is_false()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token_where/gsql_is_false)
            * [gsql_is_not_empty()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token_where/gsql_is_not_empty)
            * [gsql_is_true()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token_where/gsql_is_true)
            * [gsql_token_equal()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token_where/gsql_token_equal)
            * [gsql_token_ignore_case_equal()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token_where/gsql_token_ignore_case_equal)
            * [to_float()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token_where/to_float)
            * [to_int()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token_where/to_int)
            * [token_len()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/token_where/token_len)
          * [Reducer functions](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/reducer/)
            * [add()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/reducer/add)
            * [and()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/reducer/and)
            * [ignore_if_exists()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/reducer/ignore_if_exists)
            * [max()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/reducer/max)
            * [min()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/reducer/min)
            * [or()](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/functions/reducer/or)
        * [Add a User-defined Token Function](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/add-token-function)
      * [Run a Loading Job](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/running-a-loading-job)
      * [Manage Loading Jobs](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/managing-loading-job)
  *     * [Querying](https://docs.tigergraph.com/gsql-ref/3.10/querying/)
      * [Query Language Syntax Versions](https://docs.tigergraph.com/gsql-ref/3.10/querying/syntax-versions)
      * [Queries](https://docs.tigergraph.com/gsql-ref/3.10/querying/query-operations)
      * [Query Optimizer (Preview Feature)](https://docs.tigergraph.com/gsql-ref/3.10/querying/query-optimizer/)
        * [Enabling Cost-Based Optimization (Preview Feature)](https://docs.tigergraph.com/gsql-ref/3.10/querying/query-optimizer/enable-cost-optimizer)
        * [Statistics REST APIs (Preview Feature)](https://docs.tigergraph.com/gsql-ref/3.10/querying/query-optimizer/stats-api)
      * [Distributed Query Mode](https://docs.tigergraph.com/gsql-ref/3.10/querying/distributed-query-mode)
      * [Data Types](https://docs.tigergraph.com/gsql-ref/3.10/querying/data-types)
      * [Accumulators](https://docs.tigergraph.com/gsql-ref/3.10/querying/accumulators)
      * [Operators and Expressions](https://docs.tigergraph.com/gsql-ref/3.10/querying/operators-and-expressions)
      * [Functions](https://docs.tigergraph.com/gsql-ref/3.10/querying/func/)
        * [Aggregation Functions](https://docs.tigergraph.com/gsql-ref/3.10/querying/func/aggregation-functions)
        * [Datetime Functions](https://docs.tigergraph.com/gsql-ref/3.10/querying/func/datetime-functions)
        * [Edge Methods](https://docs.tigergraph.com/gsql-ref/3.10/querying/func/edge-methods)
        * [JSON Object Methods](https://docs.tigergraph.com/gsql-ref/3.10/querying/func/json-object-methods)
        * [JSON Array Methods](https://docs.tigergraph.com/gsql-ref/3.10/querying/func/jsonarray-methods)
        * [Mathematical Functions](https://docs.tigergraph.com/gsql-ref/3.10/querying/func/mathematical-functions)
        * [Miscellaneous Functions](https://docs.tigergraph.com/gsql-ref/3.10/querying/func/miscellaneous-functions)
        * [Query User-Defined Functions](https://docs.tigergraph.com/gsql-ref/3.10/querying/func/query-user-defined-functions)
        * [String Functions](https://docs.tigergraph.com/gsql-ref/3.10/querying/func/string-functions)
        * [Type Conversion Functions](https://docs.tigergraph.com/gsql-ref/3.10/querying/func/type-conversion-functions)
        * [Vertex Functions](https://docs.tigergraph.com/gsql-ref/3.10/querying/func/vertex-methods)
        * [Context Functions](https://docs.tigergraph.com/gsql-ref/3.10/querying/func/context-functions)
      * [Declaration and Assignment Statements](https://docs.tigergraph.com/gsql-ref/3.10/querying/declaration-and-assignment-statements)
      * [SELECT Statement](https://docs.tigergraph.com/gsql-ref/3.10/querying/select-statement/)
        * [SELECT Statement (Syntax V1)](https://docs.tigergraph.com/gsql-ref/3.10/querying/select-statement/select-statement-v1)
        * [SQL-like SELECT statement](https://docs.tigergraph.com/gsql-ref/3.10/querying/select-statement/sql-like-select-statement)
      * [Control Flow Statements](https://docs.tigergraph.com/gsql-ref/3.10/querying/control-flow-statements)
      * [Data Modification Statements](https://docs.tigergraph.com/gsql-ref/3.10/querying/data-modification-statements)
      * [Output Statements and FILE Objects](https://docs.tigergraph.com/gsql-ref/3.10/querying/output-statements-and-file-objects)
      * [Exception Statements](https://docs.tigergraph.com/gsql-ref/3.10/querying/exception-statements)
      * [Comments](https://docs.tigergraph.com/gsql-ref/3.10/querying/comments)
  *     * openCypher
      * [openCypher in GSQL](https://docs.tigergraph.com/gsql-ref/3.10/openCypher-in-gsql/openCypher-in-gsql)
      * [Writing and Running openCypher in GSQL Shell](https://docs.tigergraph.com/gsql-ref/3.10/openCypher-in-gsql/openCypher-in-gsql-web-shell)
      * [openCypher Pattern Support in GSQL](https://docs.tigergraph.com/gsql-ref/3.10/openCypher-in-gsql/openCypher-gsql-from-clause-extension)
  *     * Appendix
      * [GSQL Style Guide](https://docs.tigergraph.com/gsql-ref/3.10/appendix/gsql-style-guide)
      * [DDL Keywords & Reserved Words](https://docs.tigergraph.com/gsql-ref/3.10/appendix/keywords-and-reserved-words)
      * [Query Language Keywords & Reserved Words](https://docs.tigergraph.com/gsql-ref/3.10/appendix/query-language-reserved-words)
      * [Interpreted GSQL Limitations](https://docs.tigergraph.com/gsql-ref/3.10/appendix/interpreted-gsql-limitations)
      * [GSQL Start-to-End Process and Data Flow](https://docs.tigergraph.com/gsql-ref/3.10/appendix/gsql-start-to-end-process)
      * [Example Graphs](https://docs.tigergraph.com/gsql-ref/3.10/appendix/example-graphs)
      * [Common Errors and Problems](https://docs.tigergraph.com/gsql-ref/3.10/appendix/common-errors-and-problems)
      * [GSQL Cheat Sheets](https://docs.tigergraph.com/gsql-ref/3.10/appendix/cheat-sheets)
      * [Documentation Notations](https://docs.tigergraph.com/gsql-ref/3.10/appendix/notations)
    * [Legacy Version Documentation](https://docs.tigergraph.com/gsql-ref/3.10/appendix/legacy-tg-versions)


GSQL Language Reference 3.10
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
  * [GSQL Language Reference 3.10](https://docs.tigergraph.com/gsql-ref/3.10/intro/)
  * [Querying](https://docs.tigergraph.com/gsql-ref/3.10/querying/)
  * [Distributed Query Mode](https://docs.tigergraph.com/gsql-ref/3.10/querying/distributed-query-mode)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/3.10/modules/querying/pages/distributed-query-mode.adoc)
### Contents
  * [Invoke Distributed Query Mode](https://docs.tigergraph.com/gsql-ref/3.10/querying/distributed-query-mode#_invoke_distributed_query_mode)
  * [When to use Distributed Query Mode](https://docs.tigergraph.com/gsql-ref/3.10/querying/distributed-query-mode#_when_to_use_distributed_query_mode)
  * [Unsupported Features](https://docs.tigergraph.com/gsql-ref/3.10/querying/distributed-query-mode#_unsupported_features)


# Distributed Query Mode
### Contents
  * [Invoke Distributed Query Mode](https://docs.tigergraph.com/gsql-ref/3.10/querying/distributed-query-mode#_invoke_distributed_query_mode)
  * [When to use Distributed Query Mode](https://docs.tigergraph.com/gsql-ref/3.10/querying/distributed-query-mode#_when_to_use_distributed_query_mode)
  * [Unsupported Features](https://docs.tigergraph.com/gsql-ref/3.10/querying/distributed-query-mode#_unsupported_features)


In a distributed graph (where the data are spread across multiple machines), the default execution plan is as follows:
  * One machine will be selected as the execution hub, regardless of the number or the distribution of starting point vertices.
  * All the computation work for the query will take place at the execution hub. The vertex and edge data from other machines will be copied to the hub machine for processing.


TigerGraph Enterprise Edition offers a Distributed Query mode which provides a more optimized execution plan for queries which are likely to start at several machines and continue their traversal across several machines.
  * A set of machines representing one full copy of the entire graph will participate in the query. If the cluster has a replication factor of 2 (so there are two copies of each piece of data), then half the machines will participate.
  * The query executes in parallel across all the machines which have source vertex data for a given hop in the query. That is, each SELECT statement defines a 1-hop traversal from a set of source vertices to a set of target vertices. Unlike the default mode where all the needed data are brought to one machine, in Distributed Query mode, the computation moves across the cluster, following the traversal pattern of the query.
  * The output results will be gathered at one machine.


## [](https://docs.tigergraph.com/gsql-ref/3.10/querying/distributed-query-mode#_invoke_distributed_query_mode)Invoke Distributed Query Mode
To invoke Distributed Query Mode, insert the keyword `DISTRIBUTED` before `QUERY` in the query definition:
```
createQuery :=
  CREATE [OR REPLACE][DISTRIBUTED] QUERY queryName "(" [parameterList] ")"
  FOR GRAPH graphName
  [RETURNS "(" baseType | accumType ")"]
  [API "(" stringLiteral ")"]
  [SYNTAX syntaxName]
  "{" queryBody "}"
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.10/querying/distributed-query-mode#_when_to_use_distributed_query_mode)When to use Distributed Query Mode
The basic trade-off between distributed query mode and default mode is greater parallelism for the given query vs. using more system resources, which reduces the potential for concurrency with other operations. Each machine has a certain number of workers available for concurrent execution of queries. A query in default mode uses only one worker out of the whole system. (This one worker will have multiple threads for processing edge traversals in parallel.) However, a query in distributed mode uses one query worker _per machine._ This means this query can run faster, but it leaves fewer workers for other queries running concurrently.
In general, Distributed Query Mode is likely to improve the performance of a query if the query:
  * Starts at a very large set of starting point vertices.
  * Performs many hops.


For example, algorithms that compute a value for every vertex or one value for the entire graph should use Distributed Query Mode. This includes PageRank, Centrality, and Connected Component algorithms.
For applications where the same query are run many times in production, the application designer is encouraged to try both modes during development and choose the one which works better for their use case and data.  
---  
## [](https://docs.tigergraph.com/gsql-ref/3.10/querying/distributed-query-mode#_unsupported_features)Unsupported Features
The following GSQL features are not supported in Distributed Query Mode:
  * Functions
    * Miscellaneous
      * `Evaluate()`
    * Vertex methods
      * `edgeAttribute()`
      * `neighbors()`
      * `neighborAttribute()`
      * `size()`
  * Accumulator nesting limitations
    * Accumulator methods are not supported if the accumulator is nested inside another accumulator
  * A distributed query cannot call another distributed query as a [subquery](https://docs.tigergraph.com/gsql-ref/3.10/querying/operators-and-expressions#_subqueries)
  * A non-distributed query cannot call a distributed query in an `ACCUM` or `POST-ACCUM` clause


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


