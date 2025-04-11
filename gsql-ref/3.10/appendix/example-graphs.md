![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/3.10/appendix/example-graphs)[Next](https://docs.tigergraph.com/gsql-ref/3.10/appendix/example-graphs)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/3.10/appendix/example-graphs)
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
[Resources](https://docs.tigergraph.com/gsql-ref/3.10/appendix/example-graphs)
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
  * Appendix
  * [Example Graphs](https://docs.tigergraph.com/gsql-ref/3.10/appendix/example-graphs)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/3.10/modules/appendix/pages/example-graphs.adoc)
### Contents
  * [Work_Net](https://docs.tigergraph.com/gsql-ref/3.10/appendix/example-graphs#_work_net)
  * [Social_Net](https://docs.tigergraph.com/gsql-ref/3.10/appendix/example-graphs#_social_net)
  * [Friend_Net](https://docs.tigergraph.com/gsql-ref/3.10/appendix/example-graphs#_friend_net)
  * [Computer_Net](https://docs.tigergraph.com/gsql-ref/3.10/appendix/example-graphs#_computer_net)
  * [Minimal_Net](https://docs.tigergraph.com/gsql-ref/3.10/appendix/example-graphs#_minimal_net)
  * [Investment_Net](https://docs.tigergraph.com/gsql-ref/3.10/appendix/example-graphs#_investment_net)


# Example Graphs
### Contents
  * [Work_Net](https://docs.tigergraph.com/gsql-ref/3.10/appendix/example-graphs#_work_net)
  * [Social_Net](https://docs.tigergraph.com/gsql-ref/3.10/appendix/example-graphs#_social_net)
  * [Friend_Net](https://docs.tigergraph.com/gsql-ref/3.10/appendix/example-graphs#_friend_net)
  * [Computer_Net](https://docs.tigergraph.com/gsql-ref/3.10/appendix/example-graphs#_computer_net)
  * [Minimal_Net](https://docs.tigergraph.com/gsql-ref/3.10/appendix/example-graphs#_minimal_net)
  * [Investment_Net](https://docs.tigergraph.com/gsql-ref/3.10/appendix/example-graphs#_investment_net)


Below is the listing of the graph create&load command files and data files to generate the six example graphs used in this document: `Work_Net` , `Social_Net`, `Friend_Net`, `Computer_Net` , `Minimal_Net` , and `Investment_Net`.
The zip file `example_graphs_v3.zip` contains all of these files. Each graph has its own folder.
To create a particular graph, go in its folder and run the following command:
`gsql graph_create.gsql`
[Download Example Graph files](https://docs.tigergraph.com/gsql-ref/3.10/appendix/_attachments/example_graphs_v3.zip)
## [](https://docs.tigergraph.com/gsql-ref/3.10/appendix/example-graphs#_work_net)Work_Net
Schema for Work_Net
```
DROP ALL
CREATE VERTEX Person(PRIMARY_ID person_id STRING, id STRING, location_id STRING, skill_set SET<INT>, skill_list LIST<INT>, interest_set SET<STRING>, interest_list LIST<STRING>)
CREATE VERTEX Company(PRIMARY_ID client_id STRING, id STRING, country STRING)
CREATE UNDIRECTED EDGE Works_For(FROM Person, TO Company, start_year INT, start_month INT, full_time BOOL)
CREATE GRAPH Work_Net(*)
USE GRAPH Work_Net
CREATE LOADING JOB load_member FOR GRAPH Work_Net {
 DEFINE FILENAME f;
 LOAD f
  TO VERTEX Person VALUES($0, $0, $1, _, _, SPLIT($3,"|"), SPLIT($3,"|") ),
  TO TEMP_TABLE t2(id, skill) VALUES ($0, flatten($2,"|",1));
 LOAD TEMP_TABLE t2
  TO VERTEX Person VALUES($0, _, _, $"skill", $"skill", _, _);
}
CREATE LOADING JOB load_company FOR GRAPH Work_Net {
 DEFINE FILENAME f;
 LOAD f TO VERTEX Company VALUES($0, $0, $1);
}
CREATE LOADING JOB load_member_company FOR GRAPH Work_Net {
 DEFINE FILENAME f;
 LOAD f TO EDGE Works_For VALUES($0, $1, $2, $3, $4);
}
RUN LOADING JOB load_member USING f="./persons"
RUN LOADING JOB load_company USING f="./companies"
RUN LOADING JOB load_member_company USING f="./person_company"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

file: persons (vertices)
```
person1,us,1|2|3,management|financial
person2,chn,2|3|5|6,engineering
person3,jp,4|1|6,teaching
person4,us,4|1|10,football
person5,can,|8|2|5,sport|financial|engineering
person6,jp,7|10,music|art
person7,us,8|6,art|sport
person8,chn,1|5|2,management
person9,us,4|7|2,financial|teaching
person10,us,3,football|sport
person11,can,10,sport|football
person12,jp,1|5|2|2|2,music|engineering|teaching|teaching|teaching
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

file: company (vertices)
```
company1,us
company2,chn
company3,jp
company4,us
company5,can
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

file: person_company (edges)
```
person1,company1,2016,1,1
person1,company2,2014,3,0
person2,company1,2015,7,1
person2,company2,2012,6,0
person3,company1,2016,6,1
person4,company2,2013,2,1
person5,company2,2016,4,0
person6,company1,2015,1,1
person7,company2,2016,3,0
person7,company3,2014,1,0
person8,company1,2013,2,1
person9,company2,2015,12,1
person9,company3,2016,11,1
person10,company1,2016,2,1
person10,company3,2014,5,0
person11,company5,2016,5,1
person12,company4,2014,1,1
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.10/appendix/example-graphs#_social_net)Social_Net
Schema for Social_Net
```
DROP ALL
CREATE VERTEX Person(PRIMARY_ID person_id STRING, id STRING, gender STRING) WITH STATS="OUTDEGREE_BY_EDGETYPE"
CREATE UNDIRECTED EDGE Friend(FROM Person, TO Person)
CREATE VERTEX Post(PRIMARY_ID post_id UINT, subject STRING, post_time DATETIME)
CREATE DIRECTED EDGE Posted(FROM Person, TO Post)
CREATE DIRECTED EDGE Liked(FROM Person, TO Post, action_time DATETIME)
CREATE GRAPH Social_Net(*)
USE GRAPH Social_Net
CREATE LOADING JOB load_member FOR GRAPH Social_Net {
 DEFINE FILENAME f;
 LOAD f TO VERTEX Person VALUES($0, $0, $1) ;
}
CREATE LOADING JOB load_friend FOR GRAPH Social_Net {
 DEFINE FILENAME f;
 LOAD f TO EDGE Friend VALUES($0, $1) ;
}
CREATE LOADING JOB load_post FOR GRAPH Social_Net {
 DEFINE FILENAME f;
 LOAD f TO VERTEX Post VALUES($0, $1, $2);
}
CREATE LOADING JOB load_posted FOR GRAPH Social_Net {
 DEFINE FILENAME f;
 LOAD f TO EDGE Posted VALUES($0, $1) ;
}
CREATE LOADING JOB load_liked FOR GRAPH Social_Net {
 DEFINE FILENAME f;
 LOAD f TO EDGE Liked VALUES($0, $1, $2) ;
}
RUN LOADING JOB load_member USING f="./persons"
RUN LOADING JOB load_friend USING f="./friends"
RUN LOADING JOB load_post USING f="./posts"
RUN LOADING JOB load_posted USING f="./posted"
RUN LOADING JOB load_liked USING f="./liked"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

file: persons (vertices)
```
person1,Male
person2,Female
person3,Male
person4,Female
person5,Female
person6,Male
person7,Male
person8,Male
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

file: friends (edges)
```
person1,person2
person2,person3
person3,person4
person4,person5
person4,person6
person5,person7
person6,person8
person7,person8
person8,person1
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

file: posts (vertices)
```
0,Graphs,2010-01-12 11:22:05
1,tigergraph,2011-03-03 23:02:00
2,query languages,2011-02-03 01:02:42
3,cats,2011-02-05 01:02:44
4,coffee,2011-02-07 05:02:51
5,tigergraph,2011-02-06 01:02:02
6,tigergraph,2011-02-05 02:02:05
7,Graphs,2011-02-04 17:02:41
8,cats,2011-02-03 17:05:52
9,cats,2011-02-05 23:12:42
10,cats,2011-02-04 03:02:31
11,cats,2011-02-03 01:02:21
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

file: posted (edges)
```
person1,0
person2,1
person3,2
person4,3
person5,4
person5,11
person6,5
person6,10
person7,6
person7,9
person8,7
person8,8
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

file: liked (edges)
```
person1,0,2010-01-11 11:32:00
person2,0,2010-01-12 10:52:15
person2,3,2010-01-11 16:02:26
person3,0,2010-01-16 05:15:53
person4,4,2010-01-13 03:16:05
person5,6,2010-01-12 21:12:05
person6,8,2010-01-14 11:23:05
person7,10,2010-01-12 11:22:05
person8,4,2010-01-11 03:26:05
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.10/appendix/example-graphs#_friend_net)Friend_Net
Schema for Friend_Net
```
DROP ALL
CREATE VERTEX Person(PRIMARY_ID person_id STRING, id STRING)
CREATE UNDIRECTED EDGE Friend(FROM Person, TO Person)
CREATE UNDIRECTED EDGE Coworker(FROM Person, TO Person)
CREATE GRAPH Friend_Net(*)
USE GRAPH Friend_Net
CREATE LOADING JOB load_member FOR GRAPH Friend_Net {
 DEFINE FILENAME f;
 LOAD f TO VERTEX Person VALUES($0, $0);
}
CREATE LOADING JOB load_friend FOR GRAPH Friend_Net {
 DEFINE FILENAME f;
 LOAD f TO EDGE Friend VALUES($0, $1);
}
CREATE LOADING JOB load_coworker FOR GRAPH Friend_Net {
 DEFINE FILENAME f;
 LOAD f TO EDGE Coworker VALUES($0, $1);
}
RUN LOADING JOB load_member USING f="./persons"
RUN LOADING JOB load_friend USING f="./friends"
RUN LOADING JOB load_coworker USING f="./coworkers"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

file: persons (vertices)
```
person1
person2
person3
person4
person5
person6
person7
person8
person9
person10
person11
person12
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

file: friends (edges)
```
person1,person2
person1,person3
person1,person4
person2,person8
person3,person9
person4,person6
person5,person6
person6,person9
person7,person9
person8,person10
person9,person8
person10,person12
person11,person12
person12,person8
person12,person9
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

file: coworkers (edges)
```
person1,person4
person1,person5
person1,person6
person2,person3
person2,person4
person3,person5
person3,person6
person4,person5
person4,person6
person5,person6
person6,person5
person7,person9
person7,person5
person7,person4
person8,person9
person9,person2
person10,person7
person11,person7
person12,person7
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.10/appendix/example-graphs#_computer_net)Computer_Net
DDL commands for Computer_Net
```
DROP ALL
CREATE VERTEX Computer(PRIMARY_ID comp_id STRING, id STRING)
CREATE DIRECTED EDGE Connected(FROM Computer, TO Computer, connection_speed DOUBLE, security_level INT)
CREATE GRAPH Computer_Net(*)
USE GRAPH Computer_Net
CREATE LOADING JOB load_computer FOR GRAPH Computer_Net {
 DEFINE FILENAME f;
 LOAD f TO VERTEX Computer VALUES($0, $0);
}
CREATE LOADING JOB load_connection FOR GRAPH Computer_Net {
 DEFINE FILENAME f;
 LOAD f TO EDGE Connected VALUES($0, $1, $2, $3);
}
RUN LOADING JOB load_computer USING f="./computers"
RUN LOADING JOB load_connection USING f="./connections"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

file: computers (vertices)
```
c1
c2
c3
c4
c5
c6
c7
c8
c9
c10
c11
c12
c13
c14
c15
c16
c17
c18
c19
c20
c21
c22
c23
c24
c25
c26
c27
c28
c29
c30
c31
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

file: connections (edges)
```
c1,c2,16.0,3
c1,c3,64.0,3
c1,c4,64.0,2
c1,c5,16.5,3
c1,c6,64.3,3
c1,c7,3.2,3
c1,c8,-3.5,3
c1,c9,-5.1,1
c1,c10,15.5,3
c1,c10,.5,1
c1,c10,126,3
c10,c11,16,3
c11,c12,.5,3
c12,c13,-0.5,3
c12,c14,0.16,4
c12,c15,1e2,3
c12,c16,3.516e3,3
c12,c17,5.12e-3,2
c12,c18,-2.34e-5,1
c12,c19,-0.000000000234,5
c12,c20,0.000123e-5,4
c12,c21,1000e3,1
c12,c22,0.000123e10,1
c14,c23,123456e-6,1
c14,c24,123456e5,3
c23,c24,64,2
c23,c25,16,2
c23,c26,32,2
c23,c27,16,2
c23,c28,3,1
c23,c29,32,2
c23,c30,16,2
c23,c25,3,2
c23,c26,3,2
c23,c27,64,2
c23,c28,32,2
c23,c29,3,2
c23,c30,3,2
c23,c31,32,2
c4,c23,16,2
c4,c23,32,2
c4,c23,64,2
c4,c23,3,2
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.10/appendix/example-graphs#_minimal_net)Minimal_Net
graph_create.gsql for Minimal_Net
```
DROP ALL
CREATE VERTEX Test_V(PRIMARY_ID id STRING)
CREATE UNDIRECTED EDGE Test_E(FROM Test_V, TO Test_V)
CREATE GRAPH Minimal_Net(*)
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

There is no loading job or data for Minimal_Net (hence, "minimal.")
## [](https://docs.tigergraph.com/gsql-ref/3.10/appendix/example-graphs#_investment_net)Investment_Net
graph_create.gsql for Investment_Net
```
DROP ALL
TYPEDEF TUPLE <age UINT (4), mothers_name STRING(20) > Secret_Info
CREATE VERTEX Person(PRIMARY_ID person_id STRING, portfolio MAP<STRING, DOUBLE>, secret_info Secret_Info)
CREATE VERTEX Stock_Order(PRIMARY_ID order_id STRING, ticker STRING, order_size UINT, price FLOAT)
CREATE UNDIRECTED EDGE Make_Order(FROM Person, TO Stock_Order, order_time DATETIME)
CREATE GRAPH Investment_Net (*)
USE GRAPH Investment_Net
CREATE LOADING JOB load_person FOR GRAPH Investment_Net {
 DEFINE FILENAME f;
  LOAD f
  TO VERTEX Person VALUES($0, SPLIT($1, ":", ";"), Secret_Info( $2, $3 ) );
}
CREATE LOADING JOB load_order FOR GRAPH Investment_Net {
 DEFINE FILENAME f;
  LOAD f
  TO VERTEX Stock_Order VALUES($1, $3, $4, $5),
  TO EDGE Make_Order VALUES($0, $1, $2);
}
RUN LOADING JOB load_person USING f="./persons"
RUN LOADING JOB load_order USING f="./orders"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

file: persons (vertices)
```
person1,AAPL:3142.24;G:6112.23;MS:5000.00,25,JAMES
person2,A:5242.62;GCI:5331.21;BAH:3200.00,67,SMITH
person3,AA:5223.73;P:7935.00;BAK:6923.52,45,WILLIAMS
person4,ACH:3542.62;S:6521.55;BABA:4030.52,51,ANTHONY
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

file: orders (vertices and edges)
```
person1,0,1488566548,AAPL,500,34.42
person1,1,1488566549,A,210,50.55
person1,2,1488566550,B,211,202.32
person2,3,1488566555,S,2,42.44
person3,4,1488566155,ABC,2,52.44
person4,5,1488566255,Z,2,62.34
person4,6,1488566655,S,2,10.01
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


