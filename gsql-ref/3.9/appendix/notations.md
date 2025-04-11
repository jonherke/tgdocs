![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/3.9/appendix/notations)[Next](https://docs.tigergraph.com/gsql-ref/3.9/appendix/notations)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/3.9/appendix/notations)
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
[Resources](https://docs.tigergraph.com/gsql-ref/3.9/appendix/notations)
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
  * Appendix
  * [Documentation Notations](https://docs.tigergraph.com/gsql-ref/3.9/appendix/notations)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/3.9/modules/appendix/pages/notations.adoc)
### Contents
  * [Long lines](https://docs.tigergraph.com/gsql-ref/3.9/appendix/notations#_long_lines)
  * [Repeated zero or more times](https://docs.tigergraph.com/gsql-ref/3.9/appendix/notations#_repeated_zero_or_more_times)
  * [Optional content](https://docs.tigergraph.com/gsql-ref/3.9/appendix/notations#_optional_content)
  * [Quotation Marks](https://docs.tigergraph.com/gsql-ref/3.9/appendix/notations#_quotation_marks)
  * [Choices](https://docs.tigergraph.com/gsql-ref/3.9/appendix/notations#_choices)
  * [Placeholder identifiers and values](https://docs.tigergraph.com/gsql-ref/3.9/appendix/notations#_placeholder_identifiers_and_values)
  * [Shell prompts](https://docs.tigergraph.com/gsql-ref/3.9/appendix/notations#_shell_prompts)
  * [Keywords](https://docs.tigergraph.com/gsql-ref/3.9/appendix/notations#_keywords)


# Documentation Notations
### Contents
  * [Long lines](https://docs.tigergraph.com/gsql-ref/3.9/appendix/notations#_long_lines)
  * [Repeated zero or more times](https://docs.tigergraph.com/gsql-ref/3.9/appendix/notations#_repeated_zero_or_more_times)
  * [Optional content](https://docs.tigergraph.com/gsql-ref/3.9/appendix/notations#_optional_content)
  * [Quotation Marks](https://docs.tigergraph.com/gsql-ref/3.9/appendix/notations#_quotation_marks)
  * [Choices](https://docs.tigergraph.com/gsql-ref/3.9/appendix/notations#_choices)
  * [Placeholder identifiers and values](https://docs.tigergraph.com/gsql-ref/3.9/appendix/notations#_placeholder_identifiers_and_values)
  * [Shell prompts](https://docs.tigergraph.com/gsql-ref/3.9/appendix/notations#_shell_prompts)
  * [Keywords](https://docs.tigergraph.com/gsql-ref/3.9/appendix/notations#_keywords)


The GSQL Language Reference uses conventional notation for software documentation. In particular, note the following:
## [](https://docs.tigergraph.com/gsql-ref/3.9/appendix/notations#_long_lines)Long lines
For more convenient display, long statements in this guide may sometimes be displayed on multiple lines. This is for display purposes only; the actual code must be entered as a single line (unless the multi-line mode is used). When necessary, the examples may show a shell prompt before the start of a statement, to clearly mark where each statement begins.
Example: A `SELECT` query is grammatically a single statement, so GSQL requires that it be entered as a single line.
Long statement displayed as one line
```
SELECT *|attribute_name FROM vertex_type_name [WHERE conditions] [ORDER BY attribute1,attribute2,...] [LIMIT k]
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

However, the statement is easier to read and to understand when displayed one clause per line:
Long statement displayed on multiple lines but with only one prompt
```
SELECT *|attribute_name
  FROM vertex_type_name
  [WHERE conditions]
  [ORDER BY attribute1,attribute2,...]
  [LIMIT k]
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.9/appendix/notations#_repeated_zero_or_more_times)Repeated zero or more times
In template code, it is sometimes desirable to show that a term is repeated an arbitrary number of times. For example, a vertex definition contains zero or more user-defined attributes. A loading job contains one or more LOAD statements. In formal template code, if an asterisk (Kleene star) immediately follows option brackets, then the bracketed term can be repeated zero or more times.
For example:
```
TO VERTEX|EDGE object_name VALUES ( id_expr [, attr_expr ]*)
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The previous template code means that the `VALUES` list contains at least one attribute expression. It may be followed by any number of additional attribute expressions. Each additional attribute expression must be preceded by a comma.
## [](https://docs.tigergraph.com/gsql-ref/3.9/appendix/notations#_optional_content)Optional content
Square brackets are used to enclose a portion that is optional. Options can be nested. Square brackets themselves are rarely used as part of the GSQL language itself. Example: In the `RUN JOB` statement, the -n flag is optional. If used, -n is to be followed by a value.
```
RUN JOB [-n count ] job_name
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Sometimes, options are nested, which means that an inner option can only be used if the outer option is used:
```
RUN JOB [-n [ first_line_num , ] last_line_num ] job_name
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

means that _first_line_num_ may be specified if and only if _last_line_num_ is specified first. These options provide three possible forms for this statement:
```
RUN JOB job_name
RUN JOB -n last_line_num job_name
RUN JOB -n first_line_num , last_line_num job_name
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.9/appendix/notations#_quotation_marks)Quotation Marks
When quotation marks are shown, they are to be typed as shown (unless stated otherwise). A placeholder for a string value does not have quotation marks in the template code, but if a template is converted to actual code, quotation marks should be used around string values.
## [](https://docs.tigergraph.com/gsql-ref/3.9/appendix/notations#_choices)Choices
The vertical bar | is used to separate the choices when the syntax requires that the user choose one out of a set of values. Example: Either the keyword `VERTEX` or `EDGE` is to be used. Also, note the inclusion of quotation marks.
Template:
```
LOAD " file_path " TO VERTEX|EDGE object_type_name VALUES (id_expr, attr_expr1 , attr_expr2 ,...)
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Possible actual values:
```
LOAD "data/users.csv" TO VERTEX user VALUES ($0, $1, $2)
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The user-defined identifiers are _edge_type_name_ , _vertex_type_name1_ , _vertex_type_name2_ , _attribute_name_ and _default_value_ . As explained in the Create Vertex section, **type** is one of the attribute data types.
## [](https://docs.tigergraph.com/gsql-ref/3.9/appendix/notations#_placeholder_identifiers_and_values)Placeholder identifiers and values
In template code, any token that is not a keyword, a literal value, or punctuation is a placeholder identifier or a placeholder value. Example:
```
CREATE UNDIRECTED EDGE edge_type_name (FROM vertex_type_name1 , TO vertex_type_name2 ,
attribute_name type [DEFAULT default_value ],...)
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

=== In a very few cases, some option keywords are case-sensitive. For example, in the command to delete all data from the graph store, clear graph store -HARD   
---  
the option -HARD must be in all capital letters. ===
## [](https://docs.tigergraph.com/gsql-ref/3.9/appendix/notations#_shell_prompts)Shell prompts
Most of the examples in this document take place within the GSQL shell. When clarity is needed, a GSQL shell prompt is represented by a greater-than arrow: `>` When a command is to be issued from the operating system, outside the GSQL shell, the prompt is the following: `$`
## [](https://docs.tigergraph.com/gsql-ref/3.9/appendix/notations#_keywords)Keywords
In the GSQL language, keywords are not case-sensitive, but user-defined identifiers are case-sensitive. In code examples, keywords are in all caps to make clear the distinction between keywords and user-defined identifiers.
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


