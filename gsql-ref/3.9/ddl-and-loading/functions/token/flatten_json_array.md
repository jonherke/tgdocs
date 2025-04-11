![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/flatten_json_array)[Next](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/flatten_json_array)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/flatten_json_array)
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
[Resources](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/flatten_json_array)
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
  * [Functions](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/)
  * [Token Functions](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/)
  * [flatten_json_array()](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/flatten_json_array)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/3.9/modules/ddl-and-loading/pages/functions/token/flatten_json_array.adoc)
### Contents
  * [Syntax](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/flatten_json_array#_syntax)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/flatten_json_array#_parameters)
  * [Examples](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/flatten_json_array#_examples)
  * [Flatten a JSON array of primitive values](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/flatten_json_array#_flatten_a_json_array_of_primitive_values)
  * [Flatten a JSON array of JSON objects](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/flatten_json_array#_flatten_a_json_array_of_json_objects)
  * [Flatten a JSON object in a CSV file](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/flatten_json_array#_flatten_a_json_object_in_a_csv_file)


# flatten_json_array()
### Contents
  * [Syntax](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/flatten_json_array#_syntax)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/flatten_json_array#_parameters)
  * [Examples](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/flatten_json_array#_examples)
  * [Flatten a JSON array of primitive values](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/flatten_json_array#_flatten_a_json_array_of_primitive_values)
  * [Flatten a JSON array of JSON objects](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/flatten_json_array#_flatten_a_json_array_of_json_objects)
  * [Flatten a JSON object in a CSV file](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/flatten_json_array#_flatten_a_json_object_in_a_csv_file)


This function parses a JSON array of primitive values or JSON objects, as well as JSON objects in a column of a CSV file.
When it flattens a JSON array of primitive values, it returns all the values in the array, each value creating its own record. When it flattens a JSON array of JSON objects, it returns all the values of fields specified in the parameters; each parameter is a column, and each object creates a record.
## [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/flatten_json_array#_syntax)Syntax
  * `flatten_json_array(array_name)`
  * `flatten_json_array (array_name, sub_obj_1, …, sub_obj_n)`
  * `flatten_json_array (column_name, sub_obj_1, …, sub_obj_n)`


## [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/flatten_json_array#_parameters)Parameters
The function can be used to flatten a JSON array of primitive values (strings, numbers and booleans), a JSON array of JSON objects or a JSON object in a CSV file.
When it flattens an array of primitive values, it only takes one parameter: 

array_name
    
Required. The name of the array field in the JSON object.
When it flattens an array of JSON objects, it takes multiple parameters: 

array_name
    
Required. The name of the array field in the JSON object. 

sub_obj_1…​n
    
Required. The name of the fields in the JSON object.
When it flattens a of JSON object in a CSV column, it takes multiple parameters: 

array_name
    
Required. The name of the column containing the JSON object values. 

sub_obj_1…​n
    
Required. The name of the fields in the JSON object.
## [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/flatten_json_array#_examples)Examples
### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/flatten_json_array#_flatten_a_json_array_of_primitive_values)Flatten a JSON array of primitive values
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
### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/flatten_json_array#_flatten_a_json_array_of_json_objects)Flatten a JSON array of JSON objects
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

### [](https://docs.tigergraph.com/gsql-ref/3.9/ddl-and-loading/functions/token/flatten_json_array#_flatten_a_json_object_in_a_csv_file)Flatten a JSON object in a CSV file
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


