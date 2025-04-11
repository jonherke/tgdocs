![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/3.11/querying/exception-statements)[Next](https://docs.tigergraph.com/gsql-ref/3.11/querying/exception-statements)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/3.11/querying/exception-statements)
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
[Resources](https://docs.tigergraph.com/gsql-ref/3.11/querying/exception-statements)
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
  * [Exception Statements](https://docs.tigergraph.com/gsql-ref/3.11/querying/exception-statements)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/3.11/modules/querying/pages/exception-statements.adoc)
### Contents
  * [Default Exception Response](https://docs.tigergraph.com/gsql-ref/3.11/querying/exception-statements#_default_exception_response)
  * [Exception format not defined in query](https://docs.tigergraph.com/gsql-ref/3.11/querying/exception-statements#_exception_format_not_defined_in_query)
  * [User-Defined Exception Behavior](https://docs.tigergraph.com/gsql-ref/3.11/querying/exception-statements#_user_defined_exception_behavior)
  * [EXCEPTION Declaration Statement](https://docs.tigergraph.com/gsql-ref/3.11/querying/exception-statements#_exception_declaration_statement)
  * [RAISE Statement](https://docs.tigergraph.com/gsql-ref/3.11/querying/exception-statements#_raise_statement)
  * [TRY…​EXCEPTION Statement for Custom Error Handling](https://docs.tigergraph.com/gsql-ref/3.11/querying/exception-statements#_tryexception_statement_for_custom_error_handling)
  * [Exception Handling Flowchart](https://docs.tigergraph.com/gsql-ref/3.11/querying/exception-statements#_exception_handling_flowchart)


# Exception Statements
### Contents
  * [Default Exception Response](https://docs.tigergraph.com/gsql-ref/3.11/querying/exception-statements#_default_exception_response)
  * [Exception format not defined in query](https://docs.tigergraph.com/gsql-ref/3.11/querying/exception-statements#_exception_format_not_defined_in_query)
  * [User-Defined Exception Behavior](https://docs.tigergraph.com/gsql-ref/3.11/querying/exception-statements#_user_defined_exception_behavior)
  * [EXCEPTION Declaration Statement](https://docs.tigergraph.com/gsql-ref/3.11/querying/exception-statements#_exception_declaration_statement)
  * [RAISE Statement](https://docs.tigergraph.com/gsql-ref/3.11/querying/exception-statements#_raise_statement)
  * [TRY…​EXCEPTION Statement for Custom Error Handling](https://docs.tigergraph.com/gsql-ref/3.11/querying/exception-statements#_tryexception_statement_for_custom_error_handling)
  * [Exception Handling Flowchart](https://docs.tigergraph.com/gsql-ref/3.11/querying/exception-statements#_exception_handling_flowchart)


This section describes how the GSQL language responds to exceptions and supports user-defined exception handling . An exception is a run-time error. The GSQL language supports both built-in system exceptions and user-defined exceptions. Built-in exceptions include GSQL language exceptions (such as out-of-range value, wrong data type, and illegal operation), and errors arising in other TigerGraph components or from the operation system.
The GSQL query language also supports user-defined exception responses, also known as exception handling. This section covers the following syntax for user-defined exception behavior:
```
#########################################################
## Exception Statements ##
declExceptStmt := EXCEPTION exceptVarName "(" errorCode ")"
exceptVarName := name
errorCode   := integer
raiseStmt    := RAISE exceptVarName [errorMsg]
errorMsg    := "(" expr ")"
tryStmt     := TRY queryBodyStmts EXCEPTION caseExceptBlock+
          [elseExceptBlock] END ";"
caseExceptBlock := WHEN exceptVarName THEN queryBodyStmts
elseExceptBlock := ELSE queryBodyStmts
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.11/querying/exception-statements#_default_exception_response)**Default Exception Response**
When an exception occurs during the execution of a query, the default response is the following:
  * The query will not execute any more statements; it will exit.
  * If the query was run using the RUN QUERY command, then an error message will be displayed.
  * If the query was run by invoking the GET /query REST++ endpoint, then the output will be a simple JSON object. Some errors have a error "code" field; others do no t:


Output of Unhandled Exception (query run as REST Endpoint)
```
{
 "error": true,
 "message": "<errorMsg>"
 "code": "<errType><errorCode>"
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The example below show two common errors: wrong data type and divide-by-zero. First we define a simple query that divides 100.0 by the query’s input parameter.
```
CREATE QUERY excpBuiltin(INT n1) FOR GRAPH Minimal_Net {
 PRINT 100.0/n1;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

We then test three cases:
  1. A valid input (such as n1 = 7)
  2. Wrong data type (n1 = "A")
  3. Divide by zero (n1 = 0)


First we test using the GSQL interface. When the query runs without error, the output is in JSON format. Where there is a built-in exception, however, only an error message is displayed.
Exception response for RUN QUERY
```
GSQL > RUN QUERY excp_builtin(7)
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{"100.0/n1": 14.28571}]
}
GSQL > RUN QUERY excp_builtin("a")
Values of parameter n1 must be INT64 type, invalid value [a] provided.
GSQL > RUN QUERY excp_builtin(0)
Runtime Error: divider is zero.
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The situation is a little different when running the query as a REST++ endpoint. The output is always in JSON format.
As of TigerGraph v1.2, the format for the GET /query endpoint has changed. The graph name must now be specified after /query: `/query/{graph_name}/{query_name}`  
---  
Exception response for GET /query request
```
$ curl -X GET "http://localhost:9000/query/minimalNet/excpBuiltin?n1=7"
{
  "error": false,
  "message": "",
  "results": [
    {
      "100.0/n1": 14.28571
    }
  ],
  "version": {
    "edition": "developer",
    "api": "v2",
    "schema": 0
  }
}
$ curl -X GET "http://localhost:9000/query/minimalNet/excpBuiltin?n1=a"
{
  "code": "REST-30000",
  "error": true,
  "message": "Values of parameter n1 must be INT64 type, invalid value [a] provided.",
  "version": {
    "edition": "developer",
    "api": "v2",
    "schema": 0
  }
}
$ curl -X GET "http://localhost:9000/query/minimalNet/excpBuiltin?n1=0"
{
  "error": true,
  "message": "Runtime Error: divider is zero.",
  "version": {
    "edition": "developer",
    "api": "v2",
    "schema": 0
  }
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.11/querying/exception-statements#_exception_format_not_defined_in_query)Exception format not defined in query
A default exception format is available in cases where the exception is not defined in the query.
This format reads as follows:
  * `Exception <name> is raised with an error code of <code>`.


Example
```
create or replace query test_q(bool b) {
  EXCEPTION UsedFalseBoolean (80005);
  if not b then
   raise UsedFalseBoolean; // EXCEPTION message not defined here.
  end;
  print "Used true boolean in main.";
}
install query test_q
run query test(false)
Exception UsedFalseBoolean is raised with error code 80005
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.11/querying/exception-statements#_user_defined_exception_behavior)**User-Defined Exception Behavior**
A query author can specify what should be the response if a particular type of exception occurs within a particular specified block of statements.
The following statement types are available to specify a user-defined exception condition or a user-defined exception response.
  * The EXCEPTION Declaration Statement names a user-defined exception.
  * The RAISE Statement indicates that one of the user-defined exceptions has occurred.
  * The TRY…​EXCEPTION Statement is used to define and apply user-defined exception handling to a block of query-body statements. This can be used with or without preceding user-defined EXCEPTION and RAISE statements.


Built-in exceptions always take precedence over user-defined exceptions. Therefore, user-defined exceptions can only be used to catch conditions that would not be caught by a built-in exception. This means that built—​in exceptions are best used to capture situations which are legal according to the general syntax and semantics of the GSQL query language, but which are illegal or undesirable for a particular user application.  
---  
### [](https://docs.tigergraph.com/gsql-ref/3.11/querying/exception-statements#_exception_declaration_statement)**EXCEPTION Declaration Statement**
```
declExceptStmt := EXCEPTION exceptVarName "(" errorCode ")"
exceptVarName := name
errorCode   := integer
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

To use a user-defined exception, it must first be declared. An exception declaration statement declares a user-defined exception type, assigning a name and identification number. The id number errorCode must be greater than 40,000. Numbers 40,000 and lower are reserved for system exceptions. Exception statements must be placed before any query-body statements, after accumulator declaration statements . A query can declare multiple exception types.
### [](https://docs.tigergraph.com/gsql-ref/3.11/querying/exception-statements#_raise_statement)`RAISE` Statement
```
raiseStmt := RAISE exceptVarName [errorMsg]
errorMsg := "(" expr ")"
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The RAISE statement announces that a user-defined exception has just occurred. The exceptVarName must match one of the exceptions that was previously declared. An optional error message can be specified. Once the RAISE statement is executed, the flow of execution changes. If the RAISE statement is not within a TRY clause, then the query ends with the default exception response, using the error code and error message defined by the exception type and RAISE statements. If the RAISE is within a TRY statement, then execution jumps to the EXCEPTION handling clause of the TRY statement.
A RAISE statement itself does not include the conditions that define the exception. Typically, the user will use an IF…​THEN statement and place the RAISE statement within the THEN clause.
In the current version, a RAISE statement can only be used as a query-body-statement. It cannot be used as a DML-sub-statement. In particular, you cannot RAISE an exception inside a SELECT statement.  
---  
The example below defines and checks for two types of exceptions: an empty input set (40001) and no matching edges (40002). Remember that the minimum allowed code number is 40001.
Example: Unhandled User-Defined Exceptions
```
CREATE QUERY excp_count_activity(SET<VERTEX<Person>> v_set, STRING e_type) FOR GRAPH Social_Net {
  /* Count how many edges there are from each member of the input person set to posts, along the specified edge type. */
  MapAccum<STRING,INT> @@all_count;
  EXCEPTION empty_list (40001);
  EXCEPTION no_edges  (40002);
  IF ISEMPTY(v_set) THEN
    RAISE empty_list ("Error: Input parameter 'v_set' (type SET<VERTEX<Person>>) is empty");
  END;
  Start = v_set;
  Results = SELECT s
    FROM Start:s -(:e)- post:t
    WHERE e.type == e_type
    ACCUM @@all_count += (t.subject -> 1);
  IF Results.size() == 0 THEN
    RAISE no_edges ("Error: No '" + eType + "' edges from the vertex set");
  END;
  PRINT @@all_count;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results
```
// Valid input: no exceptions
$ curl -X GET "http://localhost:9000/query/socialNet/excpCountActivity?v_set=person2&vSet=person6&eType=posted"
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{
  "@@allCount": {
   "cats": 1,
   "tigergraph": 2
  }
 }]
}
// empty input set (due to spelling error in parameter name)
$ curl -X GET "http://localhost:9000/query/socialNet/excpCountActivity?vset=person2&vset=person6&eType=posted"
{
 "code": "40001",
 "error": true,
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "message": "Error: Input parameter 'vSet' (type SET<VERTEX<person>>) is empty"
}

// no edges (due to unknown edge type)
$ curl -X GET "http://localhost:9000/query/socialNet/excpCountActivity?vSet=person2&vSet=person6&eType=commented"
{
 "code": "40002",
 "error": true,
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "message": "Error: No 'commented' edges from the vertex set"
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.11/querying/exception-statements#_tryexception_statement_for_custom_error_handling)TRY…​EXCEPTION Statement for Custom Error Handling
```
tryStmt     := TRY queryBodyStmts EXCEPTION caseExceptBlock [elseExceptBlock] END ";"
caseExceptBlock := WHEN exceptVarName THEN queryBodyStmts+
elseExceptBlock := ELSE queryBodyStmts
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The `TRY…​EXCEPTION` Statement is used to define and apply user-defined exception handling to a block of query-body statements. A `TRY…​EXCEPTION` statement can be nested within a `TRY` block or `EXCEPTION` block.
The current version of GSQL does not support custom handling of built-in exceptions. Therefore, if a built-in exception occurs, it ignores the `TRY..EXCEPTION` blocks and simply applies the default handling, and the query aborts. In future updates, we plan to support custom handling of both custom exceptions (`RAISE`) and built-in exception with the `TRY…​EXCEPTION` block.  
---  
The `TRY…​EXCEPTION` Statement is a compound statement containing two blocks. The first block (`TRY`) consists of the query-body statements for which custom error handling should be applied. The second block (`EXCEPTION`) contains a series of WHEN…​THEN exception handling clauses. Each exception handling clause names an exception type and specifies what actions to take in the event of the exception. An optional ELSE clause contains handling statements for all other exceptions. The following text and visual flowchart details how the TRY…​ EXCEPTION block handles an exception.
When an exception occurs within a TRY block, the flow of execution skips the remainder of the TRY block and jumps to the EXCEPTION block. The GSQL flow now seeks to match the exception type with a handler. After executing the handling statements in the THEN or ELSE clause, the flow skips the remainder of the EXCEPTION block and continues with the statement following the END statement. However, if there is no matching WHEN or ELSE handler, then the exception is propagated. That is, the RAISE state is maintained after exiting the EXCEPTION block. If the TRY…​EXCEPTION block is nested inside another TRY block, then the handling process is repeated at this upper level. This repeats until either the exception is handled or there are no more TRY…​EXCEPTION blocks.
Finally, if the unhandled exception is not within a TRY block, then the query is aborted, and the default exception response is the output.
![Illustration of a nested TRY block with an EXCEPTION statement](https://docs.tigergraph.com/gsql-ref/3.11/querying/_images/2%20\(3\).png)
**Case 1: If cond1 is true** in the outer TRY block,
  * RAISE A and jump to the output EXCEPTION block.


Handled by ELSE HandStmtsZ.
**Case 2: If cond2 is true** in the inner TRY block,
  * RAISE A and jump to the inner EXCEPTION block.


Handled by handStmtsX;
**Case 3: If cond3 is true** in the inner TRY block,
  * RAISE B and jump to the inner EXCEPTION block. There is no matching handler here, so propagate the exception. Jump to the outer EXCEPTION block. Handled by handStmtsY.


**Custom Handling Example:**
The following example is a modified shortest path query. It looks for all paths from a source to a target in a computer network. It uses breadth-first search and stops at depth N when it has found at least one path at depth N, or it has searched the entire graph. There are three conditions which will cause it to RAISE an exception and abort the search:
  1. Seeing an edge with a negative connection speed (because the graph has bad data).
  2. Seeing an edge with a very slow connection speed (again because the graph has bad data).
  3. If no path was found in the graph (the search is already over, but we skip printing results).


Note that cases 1 and 2 do NOT mean that a negative or slow speed edge is actually on a shortest path, only that the query noticed a bad edge during its search. Also, because we cannot RAISE within the SELECT block, we use a workaround: set an integer variable with an error code. Immediately after the SELECT block, test the integer variable and RAISE exceptions as needed.
Example: Path Search with Exceptions
```
CREATE QUERY comp_path_valid (VERTEX<Computer> src, VERTEX<Computer> tgt, BOOL en_excp) FOR GRAPH Computer_Net {
/* Find valid paths in a computer network from a source to a target.
 Stop search once you have found some paths.
 3 Exceptions: (1) Negative connection speed, (2) Slow connection speed, (3) No path.
Set en_excp=true to raise exceptions. en_excp=false will find paths, good or bad. */
	OrAccum @@reached, @visited;
	ListAccum<STRING> @paths;
	DOUBLE min_speed = 0.4;
	INT err;
	EXCEPTION neg_speed (40001);
	EXCEPTION slow_speed (40002);
	EXCEPTION not_reached (40003);
	TRY
		Start = {src};
		// Initialize: path to src is itself.
		Start = SELECT s
			FROM Start:s
			ACCUM s.@paths = s.id;
		WHILE Start.size() != 0 AND NOT @@reached DO
			Start = SELECT t
				FROM Start:s -(:e)- :t
				WHERE t.@visited == false
				ACCUM CASE
					WHEN e.connection_speed < 0 THEN err = 1
					WHEN e.connection_speed < min_speed THEN err = 2
					WHEN t == tgt THEN @@reached += true
    END,
    // List1 * List2 -> List(each elem of List1 concat w/each elem of List2)
					t.@paths += (s.@paths * ["~"]) * [t.id]
				POST-ACCUM t.@visited = true;
    IF err == 1 AND en_excp THEN
				RAISE neg_speed ("Negative Speed");
    ELSE IF err == 2 AND en_excp THEN
				RAISE slow_speed ("Slow Speed");
			END;
		END;
		IF NOT @@reached AND en_excp THEN
			RAISE not_reached ("No path to target");
		ELSE
			result = {tgt};
			PRINT result[result.@paths];
		END;
	EXCEPTION
		WHEN neg_speed THEN PRINT "bad path: negative speed";
		WHEN slow_speed THEN PRINT "bad path: slow speed";
		WHEN not_reached THEN PRINT "no path from source to target";
	END;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

As the data in Appendix D show:
  * Any search passing through c1 will see negative edges.
  * Any search passing through c12 will see negative and slow edges.
  * Any search passing through c14 will see negative edges.


The results for 5 cases are shown: 1 valid search plus each of the 3 exception conditions. The 5th case is the same as the 4th, but exception handling is not enabled.
```
GSQL > RUN QUERY compPathValid("c10","c12",true)
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{"Result": [{
  "v_id": "c12",
  "attributes": {"Result.@paths": ["c10~c11~c12"]},
  "v_type": "computer"
 }]}]
}
GSQL > RUN QUERY compPathValid("c1","c12",true)
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{"bad path: negative speed": "bad path: negative speed"}]
}
GSQL > RUN QUERY compPathValid("c10","c13",true)
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{"bad path: slow speed": "bad path: slow speed"}]
}
GSQL > RUN QUERY compPathValid("c24","c25",true)
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{"no path from source to target": "no path from source to target"}]
}
GSQL > RUN QUERY compPathValid("c24","c25",false)
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{"Result": [{
  "v_id": "c25",
  "attributes": {"Result.@paths": []},
  "v_type": "computer"
 }]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.11/querying/exception-statements#_exception_handling_flowchart)Exception Handling Flowchart
The flowchart below summarizes all the cases for triggering and handling exceptions, both user-defined and built-in.
![Visualization of the ways exceptions are raised and handled. Queries are only aborted if a built-in exception occurs or the RAISE statement is not in a TRY block.](https://docs.tigergraph.com/gsql-ref/3.11/querying/_images/3.png)
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


