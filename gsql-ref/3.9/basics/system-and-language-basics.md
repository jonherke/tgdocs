![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics)[Next](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics)
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
[Resources](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics)
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
  * [System & Language Basics](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/3.9/modules/basics/pages/system-and-language-basics.adoc)
### Contents
  * [Language basics](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics#_language_basics)
  * [Running GSQL](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics#_running_gsql)
  * [GSQL client session timeout](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics#_gsql_client_session_timeout)
  * [Multiple shell sessions](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics#_multiple_shell_sessions)
  * [Multi-line mode - BEGIN, END, ABORT](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics#_multi_line_mode_begin_end_abort)
  * [Command files and inline commands](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics#_command_files_and_inline_commands)
  * [Help and information](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics#_help_and_information)
  * [--reset option](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics#_reset_option)
  * [Summary](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics#_summary)
  * [Session parameters](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics#_session_parameters)
  * [Examples](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics#_examples)


# System & Language Basics
### Contents
  * [Language basics](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics#_language_basics)
  * [Running GSQL](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics#_running_gsql)
  * [GSQL client session timeout](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics#_gsql_client_session_timeout)
  * [Multiple shell sessions](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics#_multiple_shell_sessions)
  * [Multi-line mode - BEGIN, END, ABORT](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics#_multi_line_mode_begin_end_abort)
  * [Command files and inline commands](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics#_command_files_and_inline_commands)
  * [Help and information](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics#_help_and_information)
  * [--reset option](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics#_reset_option)
  * [Summary](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics#_summary)
  * [Session parameters](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics#_session_parameters)
  * [Examples](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics#_examples)


This page describes the basic elements that make up the GSQL Data Definition and Loading as well as the GSQL Query Language, as well as how to run GSQL commands through the GSQL shell.
## [](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics#_language_basics)Language basics
  * **Identifiers**. Identifiers are user-defined names for types and variables. An identifier is case-sensitive and consists of letters, digits, and the underscore character `_`. Identifiers cannot begin with a digit.
  * **Keywords and Reserved Words**. Keywords are words with a predefined semantic meaning in the language. Keywords are not case-sensitive. Reserved words are set aside for use by the language, either now or in the future. Reserved words may not be reused as user-defined identifiers. In most cases, a keyword is also a reserved word. For example, `VERTEX` is a keyword. It is also a reserved word, so `VERTEX` may not be used as an identifier.
  * **Statements**. Each line corresponds to one statement (except in multi-line mode). Usually, there is no punctuation at the end of a top-level statement. Some statements, such as `CREATE LOADING JOB`, are block statements which enclose a set of statements within themselves. Some punctuation may be needed to separate the statements within a block.
  * **Comments** Within a command file, comments are text that is ignored by the language interpreter. Single-line comments begin with either `#` or `//`. A comment may be on the same line as interpreted code. Text to the left of the comment marker is interpreted, and text to the right of the marker is ignored. Multi-line comment blocks begin with `/*` and end with `*/`.


## [](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics#_running_gsql)Running GSQL
To enter the GSQL shell and work in interactive mode, type `gsql` from an operating system shell prompt. A username, password, and a graph name may also be provided on the command line.
GSQL command syntax for entering interactive mode
```
gsql [-u username] [-p password] [-g gname]
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

If a username is provided but not a password, the GSQL system will then ask for the user’s password:
Login example with username
```
os$ gsql -u victor
Password for victor : ***
GSQL >
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

If a username is not given, GSQL assumes that you are attempting to log in as the default `tigergraph` user, and prompts for the default password of `tigergraph`:
Login example without username
```
os$ gsql
Password for tigergraph : *****
GSQL >
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

To exit the GSQL shell, type either `exit` or `quit` at the GSQL prompt:
`GSQL> EXIT` or `GSQL> QUIT`
### [](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics#_gsql_client_session_timeout)GSQL client session timeout
For added security, you can configure your GSQL client session to automatically timeout after a period of inactivity. Set the `GSQL_CLIENT_IDLE_TIMEOUT_SEC` bash environment variable to be the desired number of seconds before timeout. Then every time you start a GSQL session, the idle timeout will be applied. To disable the timeout, omit `<num_sec>`. The default setting is no timeout.
Using the Linux export command to set the environment variable:
```
tigergraph@123:~$ export GSQL_CLIENT_IDLE_TIMEOUT_SEC=10
tigergraph@123:~$ gsql
Welcome to TigerGraph.
GSQL > Session timeout after 10 seconds idle.
tigergraph@123:~$ export GSQL_CLIENT_IDLE_TIMEOUT_SEC=
tigergraph@123:~$ gsql
Welcome to TigerGraph.
GSQL >
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics#_multiple_shell_sessions)Multiple shell sessions
Multiple shell sessions of GSQL may be run at the same time. This feature can be used to have multiple clients (human or machine) using the system to perform concurrent operations. A basic locking scheme is used to maintain isolation and consistency.
### [](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics#_multi_line_mode_begin_end_abort)Multi-line mode - BEGIN, END, ABORT
In interactive mode, the default behavior is to treat each line as one statement; the GSQL interpreter will activate as soon as the End-Of-Line character is entered.
Multi-line mode allows the user to enter several lines of text without triggering immediate execution. This is useful when a statement is very long and the user would like to split it into multiple lines. It is also useful when defining a job, because jobs typically contain multiple statements.
To enter multi-line mode, use the command `BEGIN`. The end-of-line character is now disabled from triggering execution. The shell remains in multi-line mode until the command `END` is entered, which will trigger the execution of the multi-line block. In the example below, `BEGIN` and `END` are used to allow the `SELECT` statement to be split into several lines:
Example: BEGIN and END defining a multi-line block
```
BEGIN
SELECT member_id, last_name, first_name, date_joined, status
  FROM Member
  WHERE age >= 21
  ORDER BY last_name, first_name
END
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Alternately, the `ABORT` command exits multi-line mode and discards the multi-line block.
### [](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics#_command_files_and_inline_commands)Command files and inline commands
A command file is a text file containing a series of GSQL statements. Blank lines and comments are ignored. By convention, GSQL command files end with the suffix `.gsql` , but this is not a requirement.
Command files are always run in multi-line mode, so `BEGIN` and `END` statements are not needed. Command files may be run either from within the GSQL shell by prefixing the filename with an @ symbol:
`GSQL> @file.gsql`
or from the operating system (i.e., a Linux shell) by giving the filename as the argument after gsql:
`$ gsql file.gsql`
Similarly, a single GSQL command can be run by enclosing the command string in quotation marks and placing it at the end of the GSQL statement. Either single or double quotation marks. It is recommended to use single quotation marks to enclose the entire command and double quotation marks to enclose any strings within the command.
Login example with inline command or command file
```
gsql [-u username] [-g graphname] ['command_string' | command_file]
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

In the example below, the file name_query.gsql contains the multi-line `CREATE QUERY` block to define the query `names_similar`.
Example using command files and inline commands
```
$ gsql pagerank_query.gsql
$ gsql 'INSTALL QUERY names_similar'
$ gsql 'RUN QUERY names_similar (0,"michael","jackson",100)'
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics#_help_and_information)Help and information
The `help` command displays a summary of the available GSQL commands:
`GSQL> HELP [BASIC|QUERY]`
Note that the HELP command has options for showing more details about certain categories of commands.
The `ls` command displays the _catalog_ : all the vertex types, edge types, graphs, queries, jobs, and session parameters which have been defined by the user.
### [](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics#_reset_option)--reset option
The `--reset` option will clear the entire graph data store and erase all related definitions (graph schema, loading jobs, and queries) from the Dictionary. The data deletion cannot be undone; use with extreme caution. The REST++, GPE, and GSE modules will be turned off.
```
$ gsql --reset
Resetting the catalog.
Shutdown restpp gse gpe ...
Graph store /home/tigergraph/tigergraph/gstore/0/ has been cleared!
The catalog was reset and the graph store was cleared.
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics#_summary)Summary
The tables below summarize the basic commands introduced so far.
#### [](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics#_gsql_commands)GSQL commands
Command | Description  
---|---  
`HELP[BASIC|QUERY]` | Display the help menu for all or a subset of the commands  
`LS` | Display the catalog, which records all the vertex types, edge types, graphs, queries, jobs, and session parameters that have been defined for the current active graph. See notes below concerning graph- and role-dependent visibility of the catalog.  
`BEGIN` | Enter multi-line edit mode (only for console mode within the shell)  
`END` | Finish multi-line edit mode and execute the multi-line block.  
`ABORT` | Abort multi-line edit mode and discard the multi-line block.  
`@file.gsql` | Run the gsql statements in the command file `file.gsql` from within the GSQL shell.  
#### [](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics#_system_shell_commands)System shell commands
Command | Description  
---|---  
`gsql file.gsql` | Run the gsql statements in the command file `file.gsql` from an operating system shell.  
`gsql 'command_string'` | Run a single gsql statement from the operating system shell.  
`gsql --reset` | Clear the graph store and erase the dictionary.  
## [](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics#_session_parameters)Session parameters
Session parameters are built-in system variables whose values are valid during the current session; their values do not endure after the session ends. In interactive command mode, a session starts and ends when entering and exiting interactive mode, respectively. When running a command file, the session lasts during the execution of the command file.
Use the `SET` command to set the value of a session parameter:
```
SET session_parameter = value
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Session Parameter | Meaning and Usage  
---|---  
`sys.data_root` | The value should be a string, representing the absolute or relative path to the folder where data files are stored. After the parameter has been set, a loading statement can reference this parameter with `$sys.data_root`.  
`gsql_src_dir` | The value should be a string, representing the absolute or relative path to the root folder for the GSQL system installation. After the parameter has been set, a loading statement can reference this parameter with `$gsql_src_dir`.  
`exit_on_error` |  When this parameter is `true` (default), if a semantic error occurs while running a GSQL command file, the GSQL shell will terminate. Accepted parameter values: `true`, `false` (case-insensitive). If the parameter is set to `false`, then a command file which is syntactically correct will continue running, even if certain runtime errors in these commands occur:
  * `CREATE QUERY`
  * `INSTALL QUERY`
  * `RUN JOB`

Semantic errors include a reference to a nonexistent entity or an improper reuse of an entity. This session parameter does not affect GSQL interactive mode; GSQL interactive mode does not exit on any error. This session parameter does not affect syntactic errors: GSQL will always exit on a syntactic error.  
`syntax_version` | The version of GSQL to be used for this session. Accepted values are `v1` or `v2`.  
`export_timeout` | The timeout limit for the command `EXPORT GRAPH ALL` in milliseconds. The default value is around 138 hours.  
`single_gpr` | Changes the internal engine framework for single queries to the engine framework currently used for distributed queries, also known as GPR. Enabling this mode may increase performance in certain cases. Default value is `false`. The loop variable in a `FOREACH[](https://docs.tigergraph.com/gsql-ref/3.9/querying/control-flow-statements#_foreach_statement)`[ loop](https://docs.tigergraph.com/gsql-ref/3.9/querying/control-flow-statements#_foreach_statement) with this option enabled is treated as a copy, while normally, changes to the loop variable will change the value in the set or bag expression.  
`cost-opt` | Whether to use [cost-based optimization](https://docs.tigergraph.com/gsql-ref/3.9/querying/query-optimizer/) when installing a query. If set to true, query installation during this session uses cost-based optimization.  
### [](https://docs.tigergraph.com/gsql-ref/3.9/basics/system-and-language-basics#_examples)Examples
  * File
  * Results


The following is example file that contains semantic errors. If a file is correct in syntax, the command file continues even after encountering semantically incorrect statements.
Example of exit_on_error = FALSE
```
SET exit_on_error = FALSE
CREATE VERTEX v(PRIMARY_ID id INT, name STRING)
CREATE VERTEX v(PRIMARY_ID id INT, weight FLOAT) // error 1: can't define VERTEX v
CREATE UNDIRECTED EDGE e2 (FROM u, TO v) // error 2: vertex type u doesn't exist
CREATE UNDIRECTED EDGE e1 (FROM v, TO v)
CREATE GRAPH g(v) // error 3: no graph definition has no edge type
CREATE GRAPH g2(*)
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
$ gsql exitOnError.gsql
The vertex type v is created.
Semantic Check Fails: The vertex name v is used by another object! Please use a different name.
failed to create the vertex type v
Semantic Check Fails: FROM or TO vertex type does not exist!
failed to create the edge type e2
The edge type e1 is created.
Semantic Check Fails: There is no edge type specified! Please specify at least one edge type!
The graph g could not be created!
Restarting gse gpe restpp ...
Finish restarting services in 11.955 seconds!
The graph g2 is created.
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


