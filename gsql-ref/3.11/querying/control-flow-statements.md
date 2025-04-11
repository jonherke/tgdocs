![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements)[Next](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements)
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
[Resources](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements)
[Developer Site](https://dev.tigergraph.com/) [Community Forum](https://community.tigergraph.com/) [Knowledge Base](https://tigergraph.freshdesk.com/support/solutions)
[Download](https://dl.tigergraph.com)
[ TG Savanna](https://savanna.tgcloud.io)
### [GSQL Language Reference](https://docs.tigergraph.com/gsql-ref/3.11/intro/)
  *     * [Overview](https://docs.tigergraph.com/gsql-ref/3.11/intro/)
    * [What sets GSQL apart](https://docs.tigergraph.com/gsql-ref/3.11/intro/set-gsql-apart)
  *     * Tutorials
      * [GSQL 101](https://docs.tigergraph.com/gsql-ref/3.11/tutorials/gsql-101/)
        * [Define a Schema](https://docs.tigergraph.com/gsql-ref/3.11/tutorials/gsql-101/define-a-schema)
        * [Load Data](https://docs.tigergraph.com/gsql-ref/3.11/tutorials/gsql-101/load-data-gsql-101)
        * [Run Built-in Queries](https://docs.tigergraph.com/gsql-ref/3.11/tutorials/gsql-101/built-in-select-queries)
        * [Parameterized Queries](https://docs.tigergraph.com/gsql-ref/3.11/tutorials/gsql-101/parameterized-gsql-query)
        * [Review](https://docs.tigergraph.com/gsql-ref/3.11/tutorials/gsql-101/review)
      * [Pattern Matching Tutorial](https://docs.tigergraph.com/gsql-ref/3.11/tutorials/pattern-matching/)
        * [Prepare your Environment](https://docs.tigergraph.com/gsql-ref/3.11/tutorials/pattern-matching/prepare-environment)
        * [One-hop patterns](https://docs.tigergraph.com/gsql-ref/3.11/tutorials/pattern-matching/one-hop-patterns)
        * [Repeating a 1-Hop Pattern](https://docs.tigergraph.com/gsql-ref/3.11/tutorials/pattern-matching/repeating-a-pattern)
        * [Multiple Hop Patterns and Accumulation](https://docs.tigergraph.com/gsql-ref/3.11/tutorials/pattern-matching/multiple-hop-and-accumulation)
        * [Example - A Recommender](https://docs.tigergraph.com/gsql-ref/3.11/tutorials/pattern-matching/example)
        * [Advanced Features](https://docs.tigergraph.com/gsql-ref/3.11/tutorials/pattern-matching/adv/)
          * [Per Clause (Beta)](https://docs.tigergraph.com/gsql-ref/3.11/tutorials/pattern-matching/adv/per-clause)
          * [Conjunctive Pattern Matching (Beta)](https://docs.tigergraph.com/gsql-ref/3.11/tutorials/pattern-matching/adv/conjunctive-pattern-matching)
          * [Data Modification](https://docs.tigergraph.com/gsql-ref/3.11/tutorials/pattern-matching/adv/dml)
        * [Summary](https://docs.tigergraph.com/gsql-ref/3.11/tutorials/pattern-matching/summary)
      * [Accumulators Tutorial](https://docs.tigergraph.com/gsql-ref/3.11/tutorials/accumulators-tutorial)
  *     * [System & Language Basics](https://docs.tigergraph.com/gsql-ref/3.11/basics/system-and-language-basics)
  *     * [Attribute Data Types](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/attribute-data-types)
    * [Schema Definition](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/)
      * [Define a Graph Schema](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/defining-a-graph-schema)
      * [Modify a Graph Schema](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema)
    * [Loading Jobs](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/loading-jobs)
      * [Create a Loading Job](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/creating-a-loading-job)
        * [Functions](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/)
          * [Token Functions](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token/)
            * [flatten()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token/flatten)
            * [flatten_json_array()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token/flatten_json_array)
            * [gsql_concat()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token/gsql_concat)
            * [gsql_current_time_epoch()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token/gsql_current_time_epoch)
            * [gsql_day()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token/gsql_day)
            * [gsql_day_epoch()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token/gsql_day_epoch)
            * [gsql_find()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token/gsql_find)
            * [gsql_length()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token/gsql_length)
            * [gsql_lower()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token/gsql_lower)
            * [gsql_ltrim()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token/gsql_ltrim)
            * [gsql_month()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token/gsql_month)
            * [gsql_month_epoch()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token/gsql_month_epoch)
            * [gsql_regex_match()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token/gsql_regex_match)
            * [gsql_regex_replace()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token/gsql_regex_replace)
            * [gsql_reverse()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token/gsql_reverse)
            * [gsql_rtrim()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token/gsql_rtrim)
            * [gsql_substring()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token/gsql_substring)
            * [gsql_to_bool()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token/gsql_to_bool)
            * [gsql_to_int()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token/gsql_to_int)
            * [gsql_to_uint()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token/gsql_to_uint)
            * [gsql_trim()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token/gsql_trim)
            * [gsql_ts_to_epoch_seconds()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token/gsql_ts_to_epoch)
            * [gsql_upper()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token/gsql_upper)
            * [gsql_uuid_v4()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token/gsql_uuid_v4)
            * [gsql_year()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token/gsql_year)
            * [gsql_year_epoch()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token/gsql_year_epoch)
            * [split()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token/split)
          * [Token Functions in WHERE Clause](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token_where/)
            * [concat()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token_where/concat)
            * [gsql_is_false()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token_where/gsql_is_false)
            * [gsql_is_not_empty()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token_where/gsql_is_not_empty)
            * [gsql_is_true()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token_where/gsql_is_true)
            * [gsql_token_equal()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token_where/gsql_token_equal)
            * [gsql_token_ignore_case_equal()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token_where/gsql_token_ignore_case_equal)
            * [to_float()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token_where/to_float)
            * [to_int()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token_where/to_int)
            * [token_len()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/token_where/token_len)
          * [Reducer functions](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/reducer/)
            * [add()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/reducer/add)
            * [and()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/reducer/and)
            * [ignore_if_exists()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/reducer/ignore_if_exists)
            * [max()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/reducer/max)
            * [min()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/reducer/min)
            * [or()](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/functions/reducer/or)
        * [Add a User-defined Token Function](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/add-token-function)
      * [Run a Loading Job](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/running-a-loading-job)
      * [Manage Loading Jobs](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/managing-loading-job)
  *     * [Querying](https://docs.tigergraph.com/gsql-ref/3.11/querying/)
      * [Query Language Syntax Versions](https://docs.tigergraph.com/gsql-ref/3.11/querying/syntax-versions)
      * [Queries](https://docs.tigergraph.com/gsql-ref/3.11/querying/query-operations)
      * [Query Optimizer (Preview Feature)](https://docs.tigergraph.com/gsql-ref/3.11/querying/query-optimizer/)
        * [Enabling Cost-Based Optimization (Preview Feature)](https://docs.tigergraph.com/gsql-ref/3.11/querying/query-optimizer/enable-cost-optimizer)
        * [Statistics REST APIs (Preview Feature)](https://docs.tigergraph.com/gsql-ref/3.11/querying/query-optimizer/stats-api)
      * [Distributed Query Mode](https://docs.tigergraph.com/gsql-ref/3.11/querying/distributed-query-mode)
      * [Data Types](https://docs.tigergraph.com/gsql-ref/3.11/querying/data-types)
      * [Accumulators](https://docs.tigergraph.com/gsql-ref/3.11/querying/accumulators)
      * [Operators and Expressions](https://docs.tigergraph.com/gsql-ref/3.11/querying/operators-and-expressions)
      * [Functions](https://docs.tigergraph.com/gsql-ref/3.11/querying/func/)
        * [Aggregation Functions](https://docs.tigergraph.com/gsql-ref/3.11/querying/func/aggregation-functions)
        * [Datetime Functions](https://docs.tigergraph.com/gsql-ref/3.11/querying/func/datetime-functions)
        * [Edge Methods](https://docs.tigergraph.com/gsql-ref/3.11/querying/func/edge-methods)
        * [JSON Object Methods](https://docs.tigergraph.com/gsql-ref/3.11/querying/func/json-object-methods)
        * [JSON Array Methods](https://docs.tigergraph.com/gsql-ref/3.11/querying/func/jsonarray-methods)
        * [Mathematical Functions](https://docs.tigergraph.com/gsql-ref/3.11/querying/func/mathematical-functions)
        * [Miscellaneous Functions](https://docs.tigergraph.com/gsql-ref/3.11/querying/func/miscellaneous-functions)
        * [Query User-Defined Functions](https://docs.tigergraph.com/gsql-ref/3.11/querying/func/query-user-defined-functions)
        * [String Functions](https://docs.tigergraph.com/gsql-ref/3.11/querying/func/string-functions)
        * [Type Conversion Functions](https://docs.tigergraph.com/gsql-ref/3.11/querying/func/type-conversion-functions)
        * [Vertex Functions](https://docs.tigergraph.com/gsql-ref/3.11/querying/func/vertex-methods)
        * [Context Functions](https://docs.tigergraph.com/gsql-ref/3.11/querying/func/context-functions)
      * [Declaration and Assignment Statements](https://docs.tigergraph.com/gsql-ref/3.11/querying/declaration-and-assignment-statements)
      * [SELECT Statement](https://docs.tigergraph.com/gsql-ref/3.11/querying/select-statement/)
        * [SELECT Statement (Syntax V1)](https://docs.tigergraph.com/gsql-ref/3.11/querying/select-statement/select-statement-v1)
        * [SQL-like SELECT statement](https://docs.tigergraph.com/gsql-ref/3.11/querying/select-statement/sql-like-select-statement)
      * [Control Flow Statements](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements)
      * [Data Modification Statements](https://docs.tigergraph.com/gsql-ref/3.11/querying/data-modification-statements)
      * [Output Statements and FILE Objects](https://docs.tigergraph.com/gsql-ref/3.11/querying/output-statements-and-file-objects)
      * [Exception Statements](https://docs.tigergraph.com/gsql-ref/3.11/querying/exception-statements)
      * [Comments](https://docs.tigergraph.com/gsql-ref/3.11/querying/comments)
      * [Write Query Output to Cloud](https://docs.tigergraph.com/gsql-ref/3.11/querying/write-query-data-to-cloud)
  *     * openCypher
      * [openCypher in GSQL](https://docs.tigergraph.com/gsql-ref/3.11/openCypher-in-gsql/openCypher-in-gsql)
      * [Writing and Running openCypher in GSQL Shell](https://docs.tigergraph.com/gsql-ref/3.11/openCypher-in-gsql/openCypher-in-gsql-web-shell)
      * [openCypher Pattern Support in GSQL](https://docs.tigergraph.com/gsql-ref/3.11/openCypher-in-gsql/openCypher-gsql-from-clause-extension)
  *     * Appendix
      * [GSQL Style Guide](https://docs.tigergraph.com/gsql-ref/3.11/appendix/gsql-style-guide)
      * [DDL Keywords & Reserved Words](https://docs.tigergraph.com/gsql-ref/3.11/appendix/keywords-and-reserved-words)
      * [Query Language Keywords & Reserved Words](https://docs.tigergraph.com/gsql-ref/3.11/appendix/query-language-reserved-words)
      * [Interpreted GSQL Limitations](https://docs.tigergraph.com/gsql-ref/3.11/appendix/interpreted-gsql-limitations)
      * [GSQL Start-to-End Process and Data Flow](https://docs.tigergraph.com/gsql-ref/3.11/appendix/gsql-start-to-end-process)
      * [Example Graphs](https://docs.tigergraph.com/gsql-ref/3.11/appendix/example-graphs)
      * [Common Errors and Problems](https://docs.tigergraph.com/gsql-ref/3.11/appendix/common-errors-and-problems)
      * [GSQL Cheat Sheets](https://docs.tigergraph.com/gsql-ref/3.11/appendix/cheat-sheets)
      * [Documentation Notations](https://docs.tigergraph.com/gsql-ref/3.11/appendix/notations)
    * [Legacy Version Documentation](https://docs.tigergraph.com/gsql-ref/3.11/appendix/legacy-tg-versions)


GSQL Language Reference 3.11
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
  * [GSQL Language Reference 3.11](https://docs.tigergraph.com/gsql-ref/3.11/intro/)
  * [Querying](https://docs.tigergraph.com/gsql-ref/3.11/querying/)
  * [Control Flow Statements](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/3.11/modules/querying/pages/control-flow-statements.adoc)
### Contents
  * [Differences in Block Syntax](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_differences_in_block_syntax)
  * [IF Statement](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_if_statement)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_syntax)
  * [Examples](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_examples)
  * [CASE Statement](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_case_statement)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_syntax_2)
  * [Examples](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_examples_2)
  * [WHILE Statement](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_while_statement)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_syntax_3)
  * [Examples](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_examples_3)
  * [FOREACH Statement](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_foreach_statement)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_syntax_4)
  * [Limitations](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_limitations)
  * [FOREACH …​ IN RANGE](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_foreach_in_range)
  * [Query-body-level FOREACH Examples](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_query_body_level_foreach_examples)
  * [DML-sub FOREACH Examples](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_dml_sub_foreach_examples)
  * [CONTINUE and BREAK Statements](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_continue_and_break_statements)
  * [Examples](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_examples_4)


# Control Flow Statements
### Contents
  * [Differences in Block Syntax](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_differences_in_block_syntax)
  * [IF Statement](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_if_statement)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_syntax)
  * [Examples](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_examples)
  * [CASE Statement](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_case_statement)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_syntax_2)
  * [Examples](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_examples_2)
  * [WHILE Statement](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_while_statement)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_syntax_3)
  * [Examples](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_examples_3)
  * [FOREACH Statement](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_foreach_statement)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_syntax_4)
  * [Limitations](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_limitations)
  * [FOREACH …​ IN RANGE](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_foreach_in_range)
  * [Query-body-level FOREACH Examples](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_query_body_level_foreach_examples)
  * [DML-sub FOREACH Examples](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_dml_sub_foreach_examples)
  * [CONTINUE and BREAK Statements](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_continue_and_break_statements)
  * [Examples](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_examples_4)


The GSQL Query Language includes a comprehensive set of control flow statements to empower sophisticated graph traversal and data computation: `IF/ELSE`, `CASE`, `WHILE`, and `FOREACH`.
## [](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_differences_in_block_syntax)Differences in Block Syntax
Note that any of these statements can be used as a query-body statement or as a DML-sub level statement.
If the control flow statement is at the query-body level, then its block(s) of statements are query-body statements ( _queryBodyStmts_ ). In a _queryBodyStmts_ block, each individual statement ends with a semicolon, so there is always a semicolon at the end.
If the control flow statement is at the DML-sub level, then its block(s) of statements are DML-sub statements ( _dmlSubStmtList_ ). In a _dmlSubStmtList_ block, a comma separates statements, but there is no punctuation at the end.
For more detailed general examples of the difference between query-body statements and DML-sub statements, see [statement types](https://docs.tigergraph.com/gsql-ref/3.11/querying/query-operations#_statement_types).
## [](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_if_statement)`IF` Statement
The `IF` statement provides conditional branching: execute a block of statements ( `queryBodyStmts` or `dmlSubStmtList` ) only if a given _condition_ is true. The `IF` statement allows for zero or more `ELSE-IF` clauses, followed by an optional `ELSE` clause. The `IF` statement can be used either at the query-body level or at the DML-sub-statement level. (See the [note about differences in block syntax](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_differences_in_block_syntax).)
### [](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_syntax)Syntax
`IF` syntax
```
queryBodyIfStmt := IF condition THEN queryBodyStmts
         [ELSE IF condition THEN queryBodyStmts ]*
         [ELSE queryBodyStmts ] END
dmlSubIfStmt :=  IF condition THEN dmlSubStmtList
         [ELSE IF condition THEN dmlSubStmtList ]*
         [ELSE dmlSubStmtList ] END
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

If an `IF` condition is not true, then the flow proceeds to the next `ELSE IF` condition. When a true condition is encountered, its corresponding block of statements is executed, and then the `IF` statement terminates (skipping any remaining `ELSE-IF` or `ELSE` clauses). If an `ELSE` clause is present, its block of statements are executed if none of the preceding conditions are true. Overall, the functionality can be summarized as "execute the first block of statements whose conditional test is true."
IF semantics
```
// if then
IF x == 5 THEN y = 10; END;   # y is assigned to 10 only if x is 5.
// if then else
IF x == 5 THEN y = 10;    # y is 10 only if x is 5.
ELSE y = 20; END;      # y is 20 only if x is NOT 5.
// if with ELSE IF
IF x == 5 THEN y = 10;    # y is 10 only if x is 5.
ELSE IF x == 7 THEN y = 5;  # y is 5 only if x is 7.
ELSE y = 20; END;      # y is 20 only if x is NOT 5 and NOT 7.
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_examples)Examples
  * Query
  * Results


This query counts the number of friends a person has, and optionally include coworkers in that count
Simple IF-ELSE at query-body level
```
CREATE QUERY count_friends_of2(VERTEX<Person> seed, BOOL include_coworkers) FOR GRAPH Friend_Net
{
  SumAccum<INT> @@num_friends = 0;
  start = {seed};
  IF include_coworkers THEN
    friends = SELECT v FROM start -((Friend | Coworker):e)- :v
      ACCUM @@num_friends +=1;
  ELSE
    friends = SELECT v FROM start -(Friend:e)- :v
      ACCUM @@num_friends +=1;
  END;
  PRINT @@num_friends, include_coworkers;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
RUN QUERY count_friends_of2("person2", false)
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{
  "@@num_friends": 2,
  "include_coworkers": false
 }]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * Query
  * Results


This query uses a more advanced activity calculation, taking into account number of posts and number of likes that a user made.
```
CREATE QUERY calculate_in_depth_activity(VERTEX<Person> seed) FOR GRAPH Social_Net
{
  SumAccum<INT> @@number_posts = 0;
  SumAccum<INT> @@number_likes = 0;
  start = {seed};
  result = SELECT post_vertex FROM start -(Posted>:e)- :post_vertex
    ACCUM @@number_posts += 1;
  result = SELECT liked_post FROM start -(Liked>:e)- :liked_post
    ACCUM @@number_likes += 1;
  IF @@number_posts < 2 THEN
    IF @@number_likes < 1 THEN
      PRINT "Not very active";
    ELSE
      PRINT "Semi-active";
    END;
  ELSE IF @@number_posts < 3 THEN
    IF @@number_likes < 2 THEN
      PRINT "Semi-active";
    ELSE
      PRINT "Active";
    END;
  ELSE
    PRINT "Very active";
  END;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
RUN QUERY calculate_in_depth_activity("person1")
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{"Semi-active": "Semi-active"}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_case_statement)`CASE` Statement
The `CASE` statement provides conditional branching: execute a block of statements only if a given condition is true. `CASE` statements can be used as query-body statements or DML-sub-statements. (See [note about differences in block syntax](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_differences_in_block_syntax).)
### [](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_syntax_2)Syntax
`CASE` syntax
```
queryBodyCaseStmt := CASE (WHEN condition THEN queryBodyStmts)+ [ELSE queryBodyStmts] END
        | CASE expr (WHEN constant THEN queryBodyStmts)+ [ELSE queryBodyStmts] END
dmlSubCaseStmt := CASE   (WHEN condition THEN dmlSubStmtList)+ [ELSE dmlSubStmtList] END
        | CASE expr (WHEN constant THEN dmlSubStmtList)+ [ELSE dmlSubStmtList] END
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

One `CASE` statement contains one or more `WHEN-THEN` clauses, each `WHEN` presenting one expression. The `CASE` statement may also have one `ELSE` clause whose statements are executed if none of the preceding conditions are true.
There are two syntax of the `CASE` statement: one equivalent to an if-else statement, and the other is structured like a switch statement. The if-else version evaluates the boolean _condition_ within each `WHEN` clause and executes the first block of statements whose _condition_ is true. The optional concluding `ELSE` clause is executed only if all `WHEN` clause conditions are false.
The switch version evaluates the expression following the keyword `WHEN` and compares its value to the expression immediately following the keyword `CASE`. These expressions do not need to be boolean; the `CASE` statement compares pairs of expressions to see if their values are equal. The first `WHEN-THEN` clause to have an expression value equal to the `CASE` expression value is executed; the remaining clauses are skipped. The optional `ELSE` clause is executed only if no `WHEN` clause expression has a value matching the `CASE` value.
CASE Semantics
```
STRING drink = "Juice";
// CASE statement: if-else version
CASE
 WHEN drink == "Juice" THEN @@calories += 50
 WHEN drink == "Soda" THEN @@calories += 120
 ...
 ELSE @@calories = 0    // Optional else-clause
END
// Since drink = "Juice", 50 will be added to calories
// CASE statement: switch version
CASE drink
 WHEN "Juice" THEN @@calories += 50
 WHEN "Soda" THEN @@calories += 120
 ...
 ELSE @@calories = 0  // Optional else-clause
END
// Since drink = "Juice", 50 will be added to calories
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_examples_2)Examples
  * Query
  * Results


This query tallies male and female friends of the starting vertex.
```
CREATE QUERY count_gender_of_friends(VERTEX<Person> seed) FOR GRAPH Social_Net{
  SumAccum<INT> @@males = 0;
  SumAccum<INT> @@females = 0;
  SumAccum<INT> @@unknown = 0;
  starting_vertex = {seed};
  people = SELECT v FROM starting_vertex -(Friend:e)-:v
    ACCUM
      CASE v.gender
        WHEN "Male" THEN @@males += 1
        WHEN "Female" THEN @@females +=1
      ELSE @@unknown += 1
    END;
	PRINT @@males, @@females, @@unknown;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Example 2 Results for Query count_gender_of_friends
```
RUN QUERY countGenderOfFriends("person4")
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{
  "@@males": 2,
  "@@unknown": 0,
  "@@females": 1
 }]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * Query
  * Results


This query gives each user post a rating based on the subject and how many likes it has.
```
CREATE QUERY rate_posts() FOR GRAPH Social_Net API("v2") {
  SumAccum<INT> @rating = 0;
  all_people = {Person.*};
  results = SELECT v FROM all_people -(:e)- Post:v
    ACCUM CASE e.type
      WHEN "Posted" THEN
        CASE
          WHEN v.subject == "cats" THEN v.@rating += -1
          WHEN v.subject == "Graphs" THEN v.@rating += 2
          WHEN v.subject == "tigergraph" THEN v.@rating += 10
        END
      WHEN "Liked" THEN v.@rating += 3 END;
  PRINT results[results.@rating];
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Example 4 Results for Query ratePosts
```
GSQL > RUN QUERY rate_posts()
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{"results": [
  {
   "v_id": "0",
   "attributes": {"results.@rating": 11},
   "v_type": "post"
  },
  {
   "v_id": "10",
   "attributes": {"results.@rating": 2},
   "v_type": "post"
  },
  {
   "v_id": "2",
   "attributes": {"results.@rating": 0},
   "v_type": "post"
  },
  {
   "v_id": "4",
   "attributes": {"results.@rating": 6},
   "v_type": "post"
  },
  {
   "v_id": "9",
   "attributes": {"results.@rating": -1},
   "v_type": "post"
  },
  {
   "v_id": "3",
   "attributes": {"results.@rating": 2},
   "v_type": "post"
  },
  {
   "v_id": "5",
   "attributes": {"results.@rating": 10},
   "v_type": "post"
  },
  {
   "v_id": "7",
   "attributes": {"results.@rating": 2},
   "v_type": "post"
  },
  {
   "v_id": "1",
   "attributes": {"results.@rating": 10},
   "v_type": "post"
  },
  {
   "v_id": "11",
   "attributes": {"results.@rating": -1},
   "v_type": "post"
  },
  {
   "v_id": "8",
   "attributes": {"results.@rating": 2},
   "v_type": "post"
  },
  {
   "v_id": "6",
   "attributes": {"results.@rating": 13},
   "v_type": "post"
  }
 ]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_while_statement)`WHILE` Statement
The WHILE statement provides unbounded iteration over a block of statements. WHILE statements can be used as query-body statements or DML-sub-statements. (See the [note about differences in block syntax](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_differences_in_block_syntax).)
### [](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_syntax_3)Syntax
WHILE syntax
```
queryBodyWhileStmt := WHILE condition [LIMIT simpleSize] DO queryBodyStmts END
dmlSubWhileStmt :=  WHILE condition [LIMIT simpleSize] DO dmlSubStmtList END
simpleSize := integer | varName | paramName
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The `WHILE` statement iterates over its body ( _queryBodyStmts_ or _dmlSubStmtList_ ) until the _condition_ evaluates to false or until the iteration limit is met. A _condition_ is any expression that evaluates to a boolean. The condition is evaluated before each iteration. `CONTINUE` statements can be used to change the control flow within the while block. `BREAK` statements can be used to exit the while loop.
A `WHILE` statement may have an optional `LIMIT` clause. `LIMIT` clauses has a constant positive integer value or integer variable to constrain the maximum number of loop iterations. The example below demonstrates how the `LIMIT` behaves.
If a limit value is not specified, it is possible for a WHILE loop to iterate infinitely. It is the responsibility of the query author to design the condition logic so that it is guaranteed to eventually be true (or to set a limit).  
---  
The following three `WHILE` statements behave the same. Each terminates when `v.size == 0` or after 5 iterations of the loop.
WHILE LIMIT semantics
```
WHILE v.size() !=0 LIMIT 5 DO
  // Statements
END;
INT iter = 0;
WHILE (v.size() !=0) AND (iter < 5) DO
  // Statements
  iter = iter + 1;
END;
INT iter = 0;
WHILE v.size() !=0 DO
  IF iter == 5 THEN BREAK; END;
  // Statements
	iter = iter + 1;
END;
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_examples_3)Examples
Below are a number of examples that demonstrate the use of `WHILE` statements.
  * Query
  * Results


The following query finds all vertices which are reachable from a starting seed vertex (i.e., breadth-first search)
Example 1. Simple WHILE loop
```
CREATE QUERY reachable(VERTEX<Person> seed) FOR GRAPH Work_Net
{
  OrAccum @visited;
  reachable_vertices = {};
  visited_vertices (ANY) = {seed};
  // Loop terminates when all neighbors are visited
  WHILE visited_vertices.size() !=0 DO
  // s is all neighbors of visited_vertices which have not been visited
    visited_vertices = SELECT s
      FROM visited_vertices-(:e)-:s
      WHERE s.@visited == FALSE
      POST-ACCUM
        s.@visited = true;
    reachable_vertices = reachable_vertices UNION visited_vertices;
  END;
  PRINT reachable_vertices;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
RUN QUERY reachable("person1")
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{"reachableVertices": [
  {
   "v_id": "person3",
   "attributes": {
    "interestList": ["teaching"],
    "skillSet": [ 6, 1, 4 ],
    "skillList": [ 4, 1, 6 ],
    "locationId": "jp",
    "interestSet": ["teaching"],
    "@visited": true,
    "id": "person3"
   },
   "v_type": "person"
  },
  {
   "v_id": "person9",
   "attributes": {
    "interestList": [ "financial", "teaching" ],
    "skillSet": [ 2, 7, 4 ],
    "skillList": [ 4, 7, 2 ],
    "locationId": "us",
    "interestSet": [ "teaching", "financial" ],
    "@visited": true,
    "id": "person9"
   },
   "v_type": "person"
  },
  {
   "v_id": "person4",
   "attributes": {
    "interestList": ["football"],
    "skillSet": [ 10, 1, 4 ],
    "skillList": [ 4, 1, 10 ],
    "locationId": "us",
    "interestSet": ["football"],
    "@visited": true,
    "id": "person4"
   },
   "v_type": "person"
  },
  {
   "v_id": "person7",
   "attributes": {
    "interestList": [ "art", "sport" ],
    "skillSet": [ 6, 8 ],
    "skillList": [ 8, 6 ],
    "locationId": "us",
    "interestSet": [ "sport", "art" ],
    "@visited": true,
    "id": "person7"
   },
   "v_type": "person"
  },
  {
   "v_id": "person1",
   "attributes": {
    "interestList": [ "management", "financial" ],
    "skillSet": [ 3, 2, 1 ],
    "skillList": [ 1, 2, 3 ],
    "locationId": "us",
    "interestSet": [ "financial", "management" ],
    "@visited": true,
    "id": "person1"
   },
   "v_type": "person"
  },
  {
   "v_id": "person5",
   "attributes": {
    "interestList": [ "sport", "financial", "engineering" ],
    "skillSet": [ 5, 2, 8 ],
    "skillList": [ 8, 2, 5 ],
    "locationId": "can",
    "interestSet": [ "engineering", "financial", "sport" ],
    "@visited": true,
    "id": "person5"
   },
   "v_type": "person"
  },
  {
   "v_id": "person6",
   "attributes": {
    "interestList": [ "music", "art" ],
    "skillSet": [ 10, 7 ],
    "skillList": [ 7, 10 ],
    "locationId": "jp",
    "interestSet": [ "art", "music" ],
    "@visited": true,
    "id": "person6"
   },
   "v_type": "person"
  },
  {
   "v_id": "person2",
   "attributes": {
    "interestList": ["engineering"],
    "skillSet": [ 6, 5, 3, 2 ],
    "skillList": [ 2, 3, 5, 6 ],
    "locationId": "chn",
    "interestSet": ["engineering"],
    "@visited": true,
    "id": "person2"
   },
   "v_type": "person"
  },
  {
   "v_id": "person8",
   "attributes": {
    "interestList": ["management"],
    "skillSet": [ 2, 5, 1 ],
    "skillList": [ 1, 5, 2 ],
    "locationId": "chn",
    "interestSet": ["management"],
    "@visited": true,
    "id": "person8"
   },
   "v_type": "person"
  },
  {
   "v_id": "company3",
   "attributes": {
    "country": "jp",
    "@visited": true,
    "id": "company3"
   },
   "v_type": "company"
  },
  {
   "v_id": "company2",
   "attributes": {
    "country": "chn",
    "@visited": true,
    "id": "company2"
   },
   "v_type": "company"
  },
  {
   "v_id": "company1",
   "attributes": {
    "country": "us",
    "@visited": true,
    "id": "company1"
   },
   "v_type": "company"
  },
  {
   "v_id": "person10",
   "attributes": {
    "interestList": [ "football", "sport" ],
    "skillSet": [3],
    "skillList": [3],
    "locationId": "us",
    "interestSet": [ "sport", "football" ],
    "@visited": true,
    "id": "person10"
   },
   "v_type": "person"
  }
 ]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * Query
  * Results


This query finds all vertices reachable within two hops from a starting seed vertex (i.e., breadth-first search)
```
CREATE QUERY reachable_within_two(VERTEX<Person> seed) FOR GRAPH Work_Net
{
  OrAccum @visited;
  reachable_vertices = {};
  visited_vertices (ANY) = {seed};
  // loop terminates when all neighbors within 2-hops of the seed vertex are visited
  WHILE visited_vertices.size() !=0 LIMIT 2 DO
    // s is all neighbors of visited_vertices which have not been visited
    visited_vertices = SELECT s
      FROM visited_vertices-(:e)-:s
      WHERE s.@visited == false
      POST-ACCUM
        s.@visited = true;
    reachable_vertices = reachable_vertices UNION visited_vertices;
  END;
  PRINT reachable_vertices;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
RUN QUERY reachable_within_two("person1")
[
 {
  "reachable_vertices": [
   {
    "attributes": {
     "@visited": true,
     "id": "person6",
     "interest_list": [
      "music",
      "art"
     ],
     "interest_set": [
      "music",
      "art"
     ],
     "location_id": "jp",
     "skill_list": [
      7,
      10
     ],
     "skill_set": [
      7,
      10
     ]
    },
    "v_id": "person6",
    "v_type": "Person"
   },
   {
    "attributes": {
     "@visited": true,
     "country": "chn",
     "id": "company2"
    },
    "v_id": "company2",
    "v_type": "Company"
   },
   {
    "attributes": {
     "@visited": true,
     "country": "us",
     "id": "company1"
    },
    "v_id": "company1",
    "v_type": "Company"
   },
   {
    "attributes": {
     "@visited": true,
     "id": "person10",
     "interest_list": [
      "football",
      "sport"
     ],
     "interest_set": [
      "football",
      "sport"
     ],
     "location_id": "us",
     "skill_list": [
      3
     ],
     "skill_set": [
      3
     ]
    },
    "v_id": "person10",
    "v_type": "Person"
   },
   {
    "attributes": {
     "@visited": true,
     "id": "person4",
     "interest_list": [
      "football"
     ],
     "interest_set": [
      "football"
     ],
     "location_id": "us",
     "skill_list": [
      4,
      1,
      10
     ],
     "skill_set": [
      4,
      1,
      10
     ]
    },
    "v_id": "person4",
    "v_type": "Person"
   },
   {
    "attributes": {
     "@visited": true,
     "id": "person3",
     "interest_list": [
      "teaching"
     ],
     "interest_set": [
      "teaching"
     ],
     "location_id": "jp",
     "skill_list": [
      4,
      1,
      6
     ],
     "skill_set": [
      4,
      1,
      6
     ]
    },
    "v_id": "person3",
    "v_type": "Person"
   },
   {
    "attributes": {
     "@visited": true,
     "id": "person7",
     "interest_list": [
      "art",
      "sport"
     ],
     "interest_set": [
      "art",
      "sport"
     ],
     "location_id": "us",
     "skill_list": [
      8,
      6
     ],
     "skill_set": [
      8,
      6
     ]
    },
    "v_id": "person7",
    "v_type": "Person"
   },
   {
    "attributes": {
     "@visited": true,
     "id": "person2",
     "interest_list": [
      "engineering"
     ],
     "interest_set": [
      "engineering"
     ],
     "location_id": "chn",
     "skill_list": [
      2,
      3,
      5,
      6
     ],
     "skill_set": [
      2,
      3,
      5,
      6
     ]
    },
    "v_id": "person2",
    "v_type": "Person"
   },
   {
    "attributes": {
     "@visited": true,
     "id": "person1",
     "interest_list": [
      "management",
      "financial"
     ],
     "interest_set": [
      "management",
      "financial"
     ],
     "location_id": "us",
     "skill_list": [
      1,
      2,
      3
     ],
     "skill_set": [
      1,
      2,
      3
     ]
    },
    "v_id": "person1",
    "v_type": "Person"
   },
   {
    "attributes": {
     "@visited": true,
     "id": "person5",
     "interest_list": [
      "sport",
      "financial",
      "engineering"
     ],
     "interest_set": [
      "sport",
      "financial",
      "engineering"
     ],
     "location_id": "can",
     "skill_list": [
      8,
      2,
      5
     ],
     "skill_set": [
      8,
      2,
      5
     ]
    },
    "v_id": "person5",
    "v_type": "Person"
   },
   {
    "attributes": {
     "@visited": true,
     "id": "person8",
     "interest_list": [
      "management"
     ],
     "interest_set": [
      "management"
     ],
     "location_id": "chn",
     "skill_list": [
      1,
      5,
      2
     ],
     "skill_set": [
      1,
      5,
      2
     ]
    },
    "v_id": "person8",
    "v_type": "Person"
   },
   {
    "attributes": {
     "@visited": true,
     "id": "person9",
     "interest_list": [
      "financial",
      "teaching"
     ],
     "interest_set": [
      "financial",
      "teaching"
     ],
     "location_id": "us",
     "skill_list": [
      4,
      7,
      2
     ],
     "skill_set": [
      4,
      7,
      2
     ]
    },
    "v_id": "person9",
    "v_type": "Person"
   }
  ]
 }
]
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_foreach_statement)`FOREACH` Statement
The `FOREACH` statement provides bounded iteration over a block of statements. `FOREACH` statements can be used as query-body statements or DML-sub-statements. See the [note about differences in block syntax](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_differences_in_block_syntax).
### [](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_syntax_4)Syntax
`FOREACH` syntax
```
queryBodyForEachStmt := FOREACH forEachControl DO queryBodyStmts END
dmlSubForEachStmt :=  FOREACH forEachControl DO dmlSubStmtList END
forEachControl := ( iterationVar | "(" keyVar ("," valueVar)+ ")") (IN | ":") setBagExpr
        | iterationVar IN RANGE "[" expr "," expr"]" ["." STEP(" expr ")"]
iterationVar := name
keyVar := name
valueVar := name
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The formal syntax for `forEachControl` appears can be broken down into the following cases:
  * `name IN setBagExpr`
  * `(key, value) pair IN setBagExpr` // because it’s a Map
  * `name IN RANGE [ expr, expr ]`
  * `name IN RANGE [ expr, expr ].STEP ( expr )`


Note that `setBagExpr` includes container accumulators and explicit sets.
### [](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_limitations)Limitations
The `FOREACH` statement has the following restrictions:
  * In a DML-sub level `FOREACH`, it is never permissible to update the loop variable (the variable declared before `IN`, e.g., `var` in “FOREACH var IN setBagExpr”).
  * In a query-body level `FOREACH`, in most cases it is not permissible to update the loop variable. The following exceptions apply:
    * If the iteration is over a `ListAccum`, its values can be updated.
    * If the iteration is over a `MapAccum`, its values can be updated, but its keys cannot.
  * If the iteration is over a set of vertices, it is not permissible to access (read or write) their vertex-attached accumulators.
  * A query-body-level `FOREACH` cannot iterate over a set or bag of constants. For example, `FOREACH` i in (1,2,3) is not supported. However, DML-sub `FOREACH` does support this.


### [](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_foreach_in_range)`FOREACH …​ IN RANGE`
The `FOREACH` statement has an optional `RANGE` clause `RANGE[expr, expr]`, which can be used to define the iteration collection. Optionally, the range may specify a step size: `RANGE[expr, expr].STEP(expr)`
Each `expr` must evaluate to an integer. Any of the integers may be negative, but the step `expr` may not be 0.
The clause `RANGE[a,b].STEP(c)` produces the sequence of integers from `a` to `b`, inclusive, with step size `c`. That is, (a,a+c,a+2∗c,a+3∗c,...a+k∗c), where k = the largest integer such that |k∗c|≤|b−a|.
If the `.STEP` method is not given, then the step size c = 1.
  * Query
  * Results


Nested `FOREACH IN RANGE` with MapAccum
```
CREATE QUERY foreach_range_ex() FOR GRAPH Social_Net {
  ListAccum<INT> @@t;
  Start = {Person.*};
  FOREACH i IN RANGE[0, 2] DO
    @@t += i;
    L = SELECT Start
      FROM Start
      WHERE Start.id == "person1"
      ACCUM
        FOREACH j IN RANGE[0, i] DO
          @@t += j
        END;
  END;
  PRINT @@t;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results for Query foreachRangeEx
```
GSQL > RUN QUERY foreach_range_ex()
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{"@@t": [ 0, 0, 1, 0, 1, 2, 0, 1, 2 ]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * Query
  * Results


The following `FOREACH` statement uses a specified step value for iterating through the range.
```
CREATE QUERY foreach_range_step(INT a, INT b, INT c) FOR GRAPH Minimal_Net {
  ListAccum<INT> @@t;
  FOREACH i IN RANGE[a,b].step(c) DO
    @@t += i;
  END;
  PRINT @@t;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The step value can be positive for an ascending range or negative for a descending range. If the step has the wrong polarity, then the loop has zero iterations; that is, the exit condition is already satisfied.
```
RUN QUERY foreach_range_step(100,0,-9)
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"@@t": [
  100,
  91,
  82,
  73,
  64,
  55,
  46,
  37,
  28,
  19,
  10,
  1
 ]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_query_body_level_foreach_examples)Query-body-level FOREACH Examples
  * Query
  * Results


This query counts the number of companies whose country matches the provided string.
```
CREATE QUERY company_count(STRING country_name) FOR GRAPH Work_Net {
  ListAccum<STRING> @@company_list;
  INT country_count;
  start = {ANY};
  // Select all vertices with type "Company", and append country attribute from all company vertices to list accum
  s = SELECT v FROM start:v
    WHERE v.type == "Company"
    ACCUM @@company_list += v.country;
  // Iterate the ListAccum and compare each element to the country_name parameter
  FOREACH item in @@company_list DO
    IF item == country_name THEN
      country_count = country_count + 1;
    END;
  END;
 PRINT country_count;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
RUN QUERY company_count("us")
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"country_count": 2}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * Query
  * Results


This query counts the number of employees from a given country and list their IDs.
```
CREATE QUERY employee_by_country(STRING country_name) FOR GRAPH Work_Net {
  MapAccum <STRING, ListAccum<STRING>> @@employees;
  // Start will have a set of all person type vertices
  start = {Person.*};
  // Build a map using person location_id as a key and a list of strings to hold multiple person ids
  s = SELECT v FROM start:v
    ACCUM @@employees += (v.location_id -> v.id);
  // Iterate the map using (key,value) pairs
  FOREACH (key,val) IN @@employees DO
    IF key == country_name THEN
    PRINT val.size();
      // Nested foreach to iterate over the list of person ids
      FOREACH employee in val DO
        PRINT employee;
      END;
      // MapAccum keys are unique so we can BREAK out of the loop
      BREAK;
    END;
  END;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
RUN QUERY employee_by_country("us")
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [
  {"val.size()": 5},
  {"employee": "person7"},
  {"employee": "person1"},
  {"employee": "person4"},
  {"employee": "person9"},
  {"employee": "person10"}
 ]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_dml_sub_foreach_examples)DML-sub FOREACH Examples
  * Query
  * Results


This query shows post topics liked by users and show total likes per topic.
```
CREATE QUERY topic_likes() FOR GRAPH Social_Net {
  SetAccum<STRING> @@person_osts;
  SumAccum<INT> @post_likes;
  MapAccum<STRING,INT> @@likes_by_topic;
  start = {Person.*};
  // Find all user posts and generate a set of post topics
  // (set has no duplicates)
  posts = SELECT g FROM start - (Posted>) - :g
     ACCUM @@person_posts += g.subject;
  // Use set of topics to increment how many times a specific
  // post is liked by other users
  liked_posts = SELECT f FROM start - (Liked>) - :f
    ACCUM FOREACH x in @@person_posts DO
    CASE WHEN (f.subject == x) THEN
      f.@post_likes += 1
      END
    END
  // Aggregate all liked totals by topic
  POST-ACCUM @@likes_by_topic += (f.subject -> f.@post_likes);
  // Display the number of likes per topic
  PRINT @@likes_by_topic;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
GSQL > RUN QUERY topic_likes()
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{"@@likesByTopic": {
  "cats": 3,
  "coffee": 2,
  "Graphs": 3,
  "tigergraph": 1
 }}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * Query
  * Results


This query shows a summary of the number of friends all persons have by gender.
```
CREATE QUERY friend_gender() FOR GRAPH Social_Net {
  ListAccum<STRING> @friend_gender;
  SumAccum<INT> @@male_gender_count;
  SumAccum<INT> @@female_gender_count;
  start = {Person.*};
  // Record a list showing each friend's gender
  social_members = SELECT s FROM start:s -(Friend)- :g
    ACCUM s.@friend_gender += (g.gender)
  // Loop over each list of genders and total them
    POST-ACCUM
      FOREACH a in s.@friend_gender DO
        CASE WHEN (a == "Male") THEN
          @@male_gender_count += 1
        ELSE
          @@female_gender_count += 1
        END
      END;
  PRINT @@male_gender_count;
  PRINT @@female_gender_count;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
GSQL > RUN QUERY friend_gender()
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [
  {"@@maleGenderCount": 11},
  {"@@femaleGenderCount": 7}
 ]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_continue_and_break_statements)`CONTINUE` and `BREAK` Statements
The `CONTINUE` and `BREAK` statements can only be used within a block of a `WHILE` or `FOREACH` statement. The `CONTINUE` statement branches control flow to the end of the loop, skipping any remaining statements in the current iteration, and proceeding to the next iteration. That is, everything in the loop block after the `CONTINUE` statement will be skipped, and then the loop will continue as normal.
The `BREAK` statement branches control flow out of the loop, i.e., it will exit the loop and stop iteration.
### [](https://docs.tigergraph.com/gsql-ref/3.11/querying/control-flow-statements#_examples_4)Examples
Below are a number of examples that demonstrate the use of `BREAK` and `CONTINUE`.
Continue and Break Semantics
```
// While loop with continue statement
  INT i = 0;
  INT nCount = 0;
  WHILE i < 10 DO
    i = i + 1;
    IF (i % 2 == 0) { CONTINUE; }
    nCount = nCount + 1;
  END;
  // i is 10, nCount is 5 (skips the increment for every even i).
  // While loop with a break statement
  i = 0;
  WHILE i < 10 DO
    IF (i == 5) { BREAK; } # When i is 5 the loop is exited
    i = i + 1;
  END;
// i is now 5
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * Query
  * Results


This query finds posts of a given person, and post of friends of that person, friends of friends, etc. until a post about cats is found. The number of friend-hops to reach is the 'degree' of cats.
```
CREATE QUERY find_degree_of_cats(VERTEX<Person> seed) FOR GRAPH Social_Net
{
  SumAccum<INT> @@degree = 0;
  OrAccum @@found_cat_post = FALSE;
  OrAccum @visited = FALSE;
  friends (ANY) = {seed};
  WHILE @@found_cat_post != true AND friends.size() > 0 DO
    posts = SELECT v FROM friends-(Posted>:e)-:v
      ACCUM CASE WHEN v.subject == "cats" THEN
        @@found_cat_post += true
      END;
    IF @@found_cat_post THEN
      BREAK;
    END;
    friends = SELECT v FROM friends-(Friend:e)-:v
      WHERE v.@visited == false
      ACCUM v.@visited = true;
    @@degree += 1;
  END;
  PRINT @@degree;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
RUN QUERY find_degree_of_cats("person2")
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"@@degree": 2}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * Query
  * Results


This query finds all 3-hop friends of a starting vertex. Count coworkers as friends if there are not enough friends
```
CREATE QUERY find_enough_friends(VERTEX<Person> seed) FOR GRAPH Friend_Net
{
  // Keep track of the distance from the seed
  SumAccum<INT> @@distance = 0;
  OrAccum @visited = false;
  visited_vertices = {seed};
  WHILE true LIMIT 3 DO
    @@distance += 1;
    // Traverse from visited_vertices to its friends
    friends = SELECT v
      FROM visited_vertices -(Friend:e)- :v
      WHERE v.@visited == false
      POST-ACCUM v.@visited = true;
    PRINT @@distance, friends;
    // If number of friends at this level is sufficient, finish this iteration
    IF visited_vertices.size() >= 2 THEN
      visited_vertices = friends;
      CONTINUE;
    END;
    // If fewer than 4 friends, add in coworkers
    coworkers = SELECT v
      FROM visited_vertices -(Coworker:e)- :v
      WHERE v.@visited == false
      POST-ACCUM v.@visited = true;
    visited_vertices = friends UNION coworkers;
    PRINT @@distance, coworkers;
  END;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

findEnoughFriends.json Example 2 Results
```
RUN QUERY find_enough_friends("person1")
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [
  {
   "@@distance": 1,
   "friends": [
    {
     "v_id": "person4",
     "attributes": {
      "@visited": true,
      "id": "person4"
     },
     "v_type": "Person"
    },
    {
     "v_id": "person2",
     "attributes": {
      "@visited": true,
      "id": "person2"
     },
     "v_type": "Person"
    },
    {
     "v_id": "person3",
     "attributes": {
      "@visited": true,
      "id": "person3"
     },
     "v_type": "Person"
    }
   ]
  },
  {
   "coworkers": [
    {
     "v_id": "person5",
     "attributes": {
      "@visited": true,
      "id": "person5"
     },
     "v_type": "Person"
    },
    {
     "v_id": "person6",
     "attributes": {
      "@visited": true,
      "id": "person6"
     },
     "v_type": "Person"
    }
   ],
   "@@distance": 1
  },
  {
   "@@distance": 2,
   "friends": [
    {
     "v_id": "person1",
     "attributes": {
      "@visited": true,
      "id": "person1"
     },
     "v_type": "Person"
    },
    {
     "v_id": "person8",
     "attributes": {
      "@visited": true,
      "id": "person8"
     },
     "v_type": "Person"
    },
    {
     "v_id": "person9",
     "attributes": {
      "@visited": true,
      "id": "person9"
     },
     "v_type": "Person"
    }
   ]
  },
  {
   "@@distance": 3,
   "friends": [
    {
     "v_id": "person7",
     "attributes": {
      "@visited": true,
      "id": "person7"
     },
     "v_type": "Person"
    },
    {
     "v_id": "person10",
     "attributes": {
      "@visited": true,
      "id": "person10"
     },
     "v_type": "Person"
    },
    {
     "v_id": "person12",
     "attributes": {
      "@visited": true,
      "id": "person12"
     },
     "v_type": "Person"
    }
   ]
  }
 ]
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


