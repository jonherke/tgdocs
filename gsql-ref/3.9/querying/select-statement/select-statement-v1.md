![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1)[Next](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1)
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
[Resources](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1)
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
  * [Querying](https://docs.tigergraph.com/gsql-ref/3.9/querying/)
  * [SELECT Statement](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/)
  * [SELECT Statement (Syntax V1)](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/3.9/modules/querying/pages/select-statement/select-statement-v1.adoc)
### Contents
  * [FROM](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_from_clause)
  * [Source Vertex Set (SYNTAX v1)](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_source_vertex_set_syntax_v1)
  * [1-Hop Step (SYNTAX v1)](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_1_hop_step_syntax_v1)
  * [Edge Set and Target Vertex Set Options](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_edge_set_and_target_vertex_set_options)
  * [Vertex and Edge Aliases](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_vertex_and_edge_aliases)
  * [SAMPLE](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_sample)
  * [WHERE](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_where)
  * [ACCUM and POST-ACCUM](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_accum_and_post_accum)
  * [Aliases and ACCUM/POST-ACCUM Iteration Model](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_aliases_and_accumpost_accum_iteration_model)
  * [Edge/Vertex Type Inference and Conflict](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_edgevertex_type_inference_and_conflict)
  * [Rules for Updating Vertex-Attached Accumulators](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_rules_for_updating_vertex_attached_accumulators)
  * [ACCUM and POST-ACCUM Examples](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_accum_and_post_accum_examples)
  * [HAVING](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_having)
  * [ORDER BY](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_order_by)
  * [LIMIT](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_limit)


# SELECT Statement (Syntax V1)
### Contents
  * [FROM](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_from_clause)
  * [Source Vertex Set (SYNTAX v1)](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_source_vertex_set_syntax_v1)
  * [1-Hop Step (SYNTAX v1)](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_1_hop_step_syntax_v1)
  * [Edge Set and Target Vertex Set Options](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_edge_set_and_target_vertex_set_options)
  * [Vertex and Edge Aliases](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_vertex_and_edge_aliases)
  * [SAMPLE](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_sample)
  * [WHERE](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_where)
  * [ACCUM and POST-ACCUM](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_accum_and_post_accum)
  * [Aliases and ACCUM/POST-ACCUM Iteration Model](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_aliases_and_accumpost_accum_iteration_model)
  * [Edge/Vertex Type Inference and Conflict](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_edgevertex_type_inference_and_conflict)
  * [Rules for Updating Vertex-Attached Accumulators](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_rules_for_updating_vertex_attached_accumulators)
  * [ACCUM and POST-ACCUM Examples](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_accum_and_post_accum_examples)
  * [HAVING](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_having)
  * [ORDER BY](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_order_by)
  * [LIMIT](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_limit)


This page describes the GSQL `SELECT` statement in GSQL Syntax V1. The default syntax is syntax v2. To use syntax v1, you need to declare the syntax at the query level or in a [session parameter](https://docs.tigergraph.com/tigergraph-server/4.2/gsql-shell/gsql-sessions#_session_parameters).
The `SELECT` block uses a _step_ _pattern_ to select some of the graph’s vertices and edges. There are a number of optional clauses that define and/or refine the selection by constraining the vertex or edge set or the result set. The final output of a query is either a vertex set known as the _result set_ or a table.
Size limitation There is a maximum size limit of 2 GB for the result set of a SELECT block . If the result of the SELECT block is larger than 2 GB, the system will return no data. NO error message is produced.  
---  
EBNF for GSQL Select Statement
```
gsqlSelectBlock := gsqlSelectClause
        fromClause
        [sampleClause]
        [whereClause]
        [accumClause]
        [postAccumClause]*
        [havingClause]
        [orderClause]
        [limitClause]
gsqlSelectClause := vertexSetName "=" SELECT vertexAlias
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

In classic GSQL, the SELECT statement is an assignment statement with a SELECT block on the right-hand side. The initial clause is the SELECT clause: `SELECT vertexAlias`. Its purpose is to specify which set of vertices from the FROM clause is to become the output. The classic SELECT clause may contain only one item: a vertex alias defined in the FROM clause. As of v3.1, the vertex alias may be from anywhere in a multi-hop pattern, not only an endpoint. GSQL now also supports [SQL-like SELECT statements](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/sql-like-select-statement) with tabular output.
The [FROM](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_from_clause) defines a path pattern to traverse in the graph, and each vertex in the path pattern can be given a vertexAlias name. Thus, the SELECT clause picks the set of vertices at one of these points in the pattern — the source vertices, the target vertices, or those from an interior point in a multi-hop path — to be the output vertices.
The SELECT block has many optional clauses, which fit together in a logical flow. Overall, the SELECT block starts from a source set of vertices and returns a result set that is either a subset of the source vertices or a subset of their neighboring vertices. Along the way, computations can be performed on the selected vertices and edges. The figure below graphically depicts the overall SELECT data flow. While the ACCUM and POST-ACCUM clauses do not directly affect which vertices are included in the result set, they affect the data (accumulators) which are attached to those vertices.
![Basic data flow for a classic 1-hop GSQL SELECT statement](https://docs.tigergraph.com/gsql-ref/3.9/querying/_images/select_statement_data_flow_v1.1.png)
## [](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_from_clause)FROM
In classic (Syntax v1) GSQL, the FROM clause describes one step or hop pattern.
As of 3.9.3, GSQL supports openCypher patterns as an alternative to writing a FROM clause. Please see [openCypher Pattern Support in GSQL](https://docs.tigergraph.com/gsql-ref/3.9/openCypher-in-gsql/openCypher-gsql-from-clause-extension) for more details.   
---  
FROM clause
```
fromClauseV1 := FROM step
fromClauseV2 := FROM stepV2 | pathPattern ["," pathPattern]*)
fromClause := fromClauseV1 | fromClauseV2
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

A hop or step consists of going from a starting set of vertices, crossing over a set of their edges, to an ending set of vertices. We typically use the names Source and Target for the starting and ending vertex sets: `Source -(Edges)-> Target`
The step pattern defines constraints for the Source set, the Edge set, and the Target set. The result of the FROM clause can be interpreted as a 3-column virtual table called the match table. Each row is a 3-element tuple: (source vertex, connected edge, target vertex).
### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_source_vertex_set_syntax_v1)Source Vertex Set (SYNTAX v1)
Notice that the edge set and target set are optional: a step can be just source vertices (stepSourceSet).
EBNF for source-only pattern (SYNTAX v1)
```
step  := stepSourceSet ["-" "(" stepEdgeSet ")" ("-"|"->") stepVertexSet]
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Rules for Source Vertex Set in Syntax V1:
  1. The source set may only be a vertexSetName. If this the first SELECT statement in the query, then the vertexSetName is generally created as a seedsSet:
  2. The vertexSetName is optionally followed by an alias, which used in subsequent clauses to refer to the source set: ```
stepSourceSet := vertexSetName [":" vertexAlias]
vertexAlias := nameebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!
```


  
---  
For example:
```
resultSet = SELECT s FROM Source:s;
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This statement can be interpreted as "_Select all vertices s, from the vertex set Source_ ." The result is a vertex set. Below is a simple example of a vertex selection.
  * Query
  * Results


Vertex SELECT example
```
# displays all 'post'-type vertices
CREATE QUERY printAllPosts() FOR GRAPH socialNet SYNTAX V1
{
 start =  {post.*};			  # initialized with all vertices of type 'post'
 results = SELECT s FROM start:s; # select these vertices
 PRINT results;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results of Query printAllPosts
```
GSQL > RUN QUERY printAllPosts()
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
   "attributes": {
    "postTime": "2010-01-12 11:22:05",
    "subject": "Graphs"
   },
   "v_type": "post"
  },
  {
   "v_id": "10",
   "attributes": {
    "postTime": "2011-02-04 03:02:31",
    "subject": "cats"
   },
   "v_type": "post"
  },
  {
   "v_id": "2",
   "attributes": {
    "postTime": "2011-02-03 01:02:42",
    "subject": "query languages"
   },
   "v_type": "post"
  },
  {
   "v_id": "4",
   "attributes": {
    "postTime": "2011-02-07 05:02:51",
    "subject": "coffee"
   },
   "v_type": "post"
  },
  {
   "v_id": "9",
   "attributes": {
    "postTime": "2011-02-05 23:12:42",
    "subject": "cats"
   },
   "v_type": "post"
  },
  {
   "v_id": "3",
   "attributes": {
    "postTime": "2011-02-05 01:02:44",
    "subject": "cats"
   },
   "v_type": "post"
  },
  {
   "v_id": "5",
   "attributes": {
    "postTime": "2011-02-06 01:02:02",
    "subject": "tigergraph"
   },
   "v_type": "post"
  },
  {
   "v_id": "7",
   "attributes": {
    "postTime": "2011-02-04 17:02:41",
    "subject": "Graphs"
   },
   "v_type": "post"
  },
  {
   "v_id": "1",
   "attributes": {
    "postTime": "2011-03-03 23:02:00",
    "subject": "tigergraph"
   },
   "v_type": "post"
  },
  {
   "v_id": "11",
   "attributes": {
    "postTime": "2011-02-03 01:02:21",
    "subject": "cats"
   },
   "v_type": "post"
  },
  {
   "v_id": "8",
   "attributes": {
    "postTime": "2011-02-03 17:05:52",
    "subject": "cats"
   },
   "v_type": "post"
  },
  {
   "v_id": "6",
   "attributes": {
    "postTime": "2011-02-05 02:02:05",
    "subject": "tigergraph"
   },
   "v_type": "post"
  }
 ]}]
}
coffeescript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_1_hop_step_syntax_v1)1-Hop Step (SYNTAX v1)
Usually, a FROM clause has a full 1-hop step.
```
step  := stepSourceSet ["-" "(" stepEdgeSet ")" ("-"|"->") stepVertexSet]
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The symbols `-(` and `)-` enclose the stepEdgeSet and separate the three parts. Each of the three parts may also define an alias, which makes a convenient way to refer to each of the three sets of entities.
```
stepSourceSet := vertexSetName [":" vertexAlias]
stepEdgeSet := [setEdgeTypes] [":" edgeAlias]
stepVertexSet := [setVertexTypes] [":" vertexAlias]
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Below is a simple example:
```
Person:s -( (Bought|Rented):e )- (Product|Service):t
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The Source set is all Persons, but the pattern will not include all Persons. It will only include those Persons who Bought or Rented a Product or Service. Moreover, the result will be a set of matched triples: (s, e, t). For example, if Sam bought a TV and Andy rented a car, the results will include (Sam, Bought, TV) and (Andy, Rented, Car). However, these two facts do not imply (Sam, Rented, Car) or (Andy, Rented, TV).
The GSQL grammar allows the right-hand enclosure to be either `)-` or `)->`. Previously, we recommended the arrowhead `)->` . However, for better compatibility with the new V2 pattern matching syntax, we now recommend the headless version: `)-`. Syntax v2 has a specific semantic meaning for the arrowheads.  
---  
### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_edge_set_and_target_vertex_set_options)Edge Set and Target Vertex Set Options
**Rules for Edge Set and Target Set in Syntax V1:**
  1. The edge set (**`stepEdgeSet`**) and target vertex set (**`stepVertexSet`**) obey very similar rules. Each may be a set specifier (**`stepEdgeTypes`**or**`stepVertexTypes`**) followed optionally by an alias.
  2. The set specifier can be any of the following:
     * **`"_"`**or**`"ANY"`**or <blank>, which means any edge/vertex.
     * a named type (**`edgeType`**or**`vertexType`**)
     * a global SetAccum accumulator containing a set of edges or vertices (**`"@@"accumName`**)
     * a string or string set parameter which names one or more edge or vertex types (**`paramName`**) This parameterized type is one aspect of[**Dynamic Querying**](https://docs.tigergraph.com/gsql-ref/3.9/querying/query-operations).
     * A list of types, string parameters, or global accumulators, e.g., **`"(" edgeSetType ["|" edgeSetType]`**` ")"`*
     * The list of types must contain the same type of specifiers. ```
stepEdgeSet := [setEdgeTypes] [":" edgeAlias]
stepVertexSet := [setVertexTypes] [":" vertexAlias]
alias := (vertexAlias | edgeAlias)
vertexAlias := name
edgeAlias := name
stepEdgeTypes := atomicEdgeType
        | "(" edgeSetType ["|" edgeSetType]* ")"
atomicEdgeType := "_" | ANY | edgeSetType
edgeSetType := edgeType | paramName | globalAccumName
stepVertexTypes := atomicVertexType
         | "(" vertexSetType ["|" vertexSetType]* ")"
atomicVertexType := "_" | ANY | vertexSetType
vertexSetType := vertexType | paramName | globalAccumNameebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!
```


  
---  
Notation | Accepted vertex/edge types  
---|---  
(empty) | any type  
_ | any type  
ANY | any type  
vertex/edge type name | given type  
string parameter holding a vertex/edge type name | given type  
global SetAccum containing vertices or edges | given set  
(name | name …​) | UNION of two or more collections  
Parentheses are always needed around the edge type in a FROM clause: `FROM Source:s -(eType:e)- Target:t` Parentheses are also needed if a vertexEdgeType is the union of more than one or more individual edge types or vertex types: `FROM Source:s -((eType1 | eType2):e) - Target:t` Note the double set of parentheses for the edge specifier. If there is an edge alias, these parentheses are needed. If however there is no edge alias, it is legal to have just a single set of parentheses: `FROM Source:s -(eType1 | eType2) - Target:t`  
---  
Either the source vertex set ( s ) or target vertex set ( t ) can be used as the SELECT argument, which determines the result of the SELECT statement. Note the small difference in the two SELECT statements below.
Selecting source or target vertices from edge-induced selection
```
resultSet1 = SELECT s FROM source:s-(eType:e)-tType:t;  //select from the source set
resultSet2 = SELECT t FROM source:s-(eType:e)-tType:t;  //select from the target set
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

resultSet1 is based on the source end of the edges. resultSet2 is based on the target end of the selected edges. However, resultSet1 is NOT identical to the Source vertex set. It is only those members of Source which connect to an eType edge and then to a tType vertex. Other clauses (presented later in this "SELECT Statement" section, can do additional filtering of the Source set.
We strongly suggest that an alias should be declared with every vertex and edge in the FROM clause, as there are several functions and features which are only available to vertex and edge aliases.  
---  
It is legal to declare an alias without explicitly stating an edge/target type. See the examples below.
  * Target vertex type inference
  * Edge type inference


```
resultSet3 = SELECT v FROM Source:v-(eType:e)-(V1|V2):t;
resultSet4 = SELECT v FROM Source:v-(eType:e)-:t;
resultSet5 = SELECT v FROM Source:v-(eType:e)-ANY:t;
resultSet6 = SELECT v FROM Source:v-(eType:e)-_:t;
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
resultSet7 = SELECT v FROM Source:v-((E1|E2|E3):e)-tType:t;
resultSet8 = SELECT v FROM Source:v-(:e)-tType:t;
resultSet9 = SELECT v FROM Source:v-(_:e)-tType:t;
resultSet10 = SELECT v FROM Source:v-(ANY:e)-tType:t;
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The following are a set of queries that demonstrate edge-induced SELECT blocks. The allPostsLiked and allPostsMade queries show how the target vertex type can be omitted. The allPostsLikedOrMade query uses the "|" operator to select multiple types of edges.
  * Query
  * Results


Edge induced SELECT example
```
# uses various SELECT statements (some of which are equivalent) to print out
# either the posts made by the given user, the posts liked by the given
# user, or the posts made or liked by the given user.
CREATE QUERY printAllPosts2(vertex<person> seed) FOR GRAPH socialNet SYNTAX V1
{
	start = {seed}; # initialize starting set of vertices

	# --- statements produce equivalent results
	# select all 'post' vertices which can be reached from 'start' in one hop
	# 	using an edge of type 'liked'
	allPostsLiked = SELECT targetVertex FROM start -(liked:e)- post:targetVertex;
	# select all vertices of any type which can be reached from 'start' in one hop
	# 	using an edge of type 'liked'
	allPostsLiked = SELECT targetVertex FROM start -(liked:e)- :targetVertex;
	# ----

	# --- statements produce equivalent results
	# start with the vertex set from above, and traverse all edges of type "posted"
 	# 	(locally those edges are just given a name 'e' in case they need accessed)
 	# 	and return all vertices of type 'post' which can be reached within one-hop of 'start' vertices
	allPostsMade = SELECT targetVertex FROM start -(posted:e)- post:targetVertex;
	# start with the vertex set from above, and traverse all edges of type "posted"
 	# 	(locally those edges are just given a name 'e' in case they need accessed)
 	# 	and return all vertices of any type which can be reached within one-hop of 'start' vertices
	allPostsMade = SELECT targetVertex FROM start -(posted:e)- :targetVertex;
	# ----

	# --- statements produce equivalent results
	# select all vertices of type 'post' which can be reached from 'start' in one hop
	# 	using an edge of any type
	# not equivalent to any statement. because it doesn't restrict the edge type,
	# 	this will include any vertex connected by 'liked' or 'posted' edge types
	allPostsLikedOrMade = SELECT t FROM start -(:e)- t;
	# select all vertices of type 'post' which can be reached from 'start' in one hop
	#	using an edge of type either 'posted' or 'liked'
	allPostsLikedOrMade = SELECT t FROM start -((posted|liked):e)- post:t;
	# select all vertices of any type which can be reached from 'start' in one hop
	#	using an edge of type either 'posted' or 'liked/
	allPostsLikedOrMade = SELECT t FROM start -((posted|liked):e)- :t;
	#option for simplified parentheses in edge pattern:
	allPostsLikedOrMade = SELECT t FROM start - (posted|liked)- :t
	# ----
	PRINT allPostsLiked;
  PRINT allPostsMade;
  PRINT allPostsLikedOrMade;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results of Query printAllPosts2
```
GSQL > RUN QUERY printAllPosts2("person2")
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [
  {"allPostsLiked": [
   {
    "v_id": "0",
    "attributes": {
     "postTime": "2010-01-12 11:22:05",
     "subject": "Graphs"
    },
    "v_type": "post"
   },
   {
    "v_id": "3",
    "attributes": {
     "postTime": "2011-02-05 01:02:44",
     "subject": "cats"
    },
    "v_type": "post"
   }
  ]},
  {"allPostsMade": [{
   "v_id": "1",
   "attributes": {
    "postTime": "2011-03-03 23:02:00",
    "subject": "tigergraph"
   },
   "v_type": "post"
  }]},
  {"allPostsLikedOrMade": [
   {
    "v_id": "0",
    "attributes": {
     "postTime": "2010-01-12 11:22:05",
     "subject": "Graphs"
    },
    "v_type": "post"
   },
   {
    "v_id": "3",
    "attributes": {
     "postTime": "2011-02-05 01:02:44",
     "subject": "cats"
    },
    "v_type": "post"
   },
   {
    "v_id": "1",
    "attributes": {
     "postTime": "2011-03-03 23:02:00",
     "subject": "tigergraph"
    },
    "v_type": "post"
   }
  ]}
 ]
}
GSQL > RUN QUERY printAllPosts2("person6")
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [
  {"allPostsLiked": [{
   "v_id": "8",
   "attributes": {
    "postTime": "2011-02-03 17:05:52",
    "subject": "cats"
   },
   "v_type": "post"
  }]},
  {"allPostsMade": [
   {
    "v_id": "10",
    "attributes": {
     "postTime": "2011-02-04 03:02:31",
     "subject": "cats"
    },
    "v_type": "post"
   },
   {
    "v_id": "5",
    "attributes": {
     "postTime": "2011-02-06 01:02:02",
     "subject": "tigergraph"
    },
    "v_type": "post"
   }
  ]},
  {"allPostsLikedOrMade": [
   {
    "v_id": "10",
    "attributes": {
     "postTime": "2011-02-04 03:02:31",
     "subject": "cats"
    },
    "v_type": "post"
   },
   {
    "v_id": "5",
    "attributes": {
     "postTime": "2011-02-06 01:02:02",
     "subject": "tigergraph"
    },
    "v_type": "post"
   },
   {
    "v_id": "8",
    "attributes": {
     "postTime": "2011-02-03 17:05:52",
     "subject": "cats"
    },
    "v_type": "post"
   }
  ]}
 ]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This example is another edge selection that uses the "|" operator to select edges that have target vertices of multiple types.
  * Query
  * Results


Edge induced SELECT example
```
# uses a SELECT statement to print out everything related to a given user
# 	this includes posts that the user liked, posts that the user made, and friends
# 	of the user
CREATE QUERY printAllRelatedItems(vertex<person> seed) FOR GRAPH socialNet SYNTAX V1
{
	sourceVertex = {seed};
	# -- statements produce equivalent output
	# returns all vertices of type either 'person' or 'post' that can be reached
	# 	from the sourceVertex set using one edge of any type
	everythingRelated = SELECT v FROM sourceVertex -(:e)- (person|post):v;
	# returns all vertices of any type that can be reached from the sourceVertex
	# 	using one edge of any type
	# this statement is equivalent to the above one because the graph schema only
	#	has vertex types of either 'person' or 'post'. if there were more vertex
	#	types present, these would not be equivalent.
	everythingRelated = SELECT v FROM sourceVertex -(:e)- :v;
	# --
	PRINT everythingRelated;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
GSQL > RUN QUERY printAllRelatedItems("person2")
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{"everythingRelated": [
  {
   "v_id": "0",
   "attributes": {
    "postTime": "2010-01-12 11:22:05",
    "subject": "Graphs"
   },
   "v_type": "post"
  },
  {
   "v_id": "person3",
   "attributes": {
    "gender": "Male",
    "id": "person3"
   },
   "v_type": "person"
  },
  {
   "v_id": "person1",
   "attributes": {
    "gender": "Male",
    "id": "person1"
   },
   "v_type": "person"
  },
  {
   "v_id": "3",
   "attributes": {
    "postTime": "2011-02-05 01:02:44",
    "subject": "cats"
   },
   "v_type": "post"
  },
  {
   "v_id": "1",
   "attributes": {
    "postTime": "2011-03-03 23:02:00",
    "subject": "tigergraph"
   },
   "v_type": "post"
  }
 ]}]
}
GSQL > RUN QUERY printAllRelatedItems("person6")
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{"everythingRelated": [
  {
   "v_id": "person4",
   "attributes": {
    "gender": "Female",
    "id": "person4"
   },
   "v_type": "person"
  },
  {
   "v_id": "10",
   "attributes": {
    "postTime": "2011-02-04 03:02:31",
    "subject": "cats"
   },
   "v_type": "post"
  },
  {
   "v_id": "5",
   "attributes": {
    "postTime": "2011-02-06 01:02:02",
    "subject": "tigergraph"
   },
   "v_type": "post"
  },
  {
   "v_id": "person8",
   "attributes": {
    "gender": "Male",
    "id": "person8"
   },
   "v_type": "person"
  },
  {
   "v_id": "8",
   "attributes": {
    "postTime": "2011-02-03 17:05:52",
    "subject": "cats"
   },
   "v_type": "post"
  }
 ]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_vertex_and_edge_aliases)Vertex and Edge Aliases
Vertex and edge _aliases_ are declared within the FROM clause of a SELECT block, by using the character ":", followed by the alias name. Aliases can be accessed anywhere within the same SELECT block. They are used to reference a single selected vertex or edge of a set. It is through the vertex or edge aliases that the attributes of these vertices or edges can be accessed.
For example, the following code snippets show two different SELECT statements. The first SELECT statement starts from a vertex set called allVertices, and the vertex alias name **v** can access each individual vertex from allVertices. The second SELECT statement selects a set of edges. It can use the vertex alias **s** to reference the source vertices, or the alias **t** to reference the target vertices.
Vertex variables
```
results = SELECT v FROM allVertices:v;
results = SELECT t FROM allVertices:s -()-> :t;
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The following example shows an edge-based SELECT statement, declaring aliases for all three parts of the edge. In the ACCUM clause, the `e` and `t` aliases are assigned to local vertex and edge variables.
Edge variables
```
results = SELECT v
     FROM allVertices:s -(:e)- :t
     ACCUM VERTEX v = t, EDGE eg = e;
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

We strongly suggest that an alias should be declared with every vertex and edge in the FROM clause, as there are several functions and features only available to vertex and edge aliases.  
---  
## [](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_sample)SAMPLE
The SAMPLE clause is an optional clause that selects a uniform random sample from the population of edges or target vertices specified in the FROM argument.
  * In **V1** syntax, the `SAMPLE` clause supports left-to-right directed edges and undirected edges.
  * In **V2** and **V3** syntax, the `SAMPLE` clause supports left-to-right directed and undirected edges. Right-to-left directed edges (e.g., `FROM start:s <-(:e)- :v`) are not supported in either V2 or V3 syntax.
  * The `SAMPLE` clause does not guarantee returning the exact number of elements; it may return fewer than the requested number.

  
---  
If you want to sample from a set of vertices directly, not from edges or from neighboring (target) vertices, then the following technique is simpler and faster:  
---  
Select k random vertices from a vertex set S
```
random = SELECT s
     FROM S:s
     LIMIT k;
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The SAMPLE clause draws from the edge population consisting of those edges which satisfy all three parts — source set, edge type, and target type — of the FROM clause. The SAMPLE clause is intended to provide a representative sample of the distribution of edges (or vertices) connected to _hub_ vertices, instead of dealing with all edges. A _hub_ vertex is a vertex with a relatively high degree. (The _degree_ of a vertex is the number of edges which connect to it. If edges are directional, one can distinguish between indegree and outdegree.)
EBNF for Sample Clause
```
sampleClause := SAMPLE ( expr | expr "%" ) EDGE WHEN condition # sample an absolute number (or a percentage) of edges for each source vertex.
       | SAMPLE expr TARGET WHEN condition       # sample an absolute number of edges incident to each target vertex.
       | SAMPLE expr "%" TARGET PINNED WHEN condition  # sample a percentage of edges incident to each target vertex.
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The expression following SAMPLE specifies the sample size, either an absolute number or a percentage of the population. The expression in sampleClause must evaluate to a positive integer. There are two sampling methods. One is sampling based on edge id. The other is based on target vertex id: if a target vertex id is sampled, all edges from this source vertex to the sampled target vertex are sampled.
Note: Currently, the WHEN condition that can be used with a SAMPLE clause is limited strictly to checking if the result of a function call on a vertex is greater than or greater than/equal to some number.  
---  
Given that the sampling is random, some details of each of the example queries may change each time they are run.
The following query displays two modes of sampling: an absolute number of edges from a source vertex and a percentage of edges from a source vertex. We use the computerNet graph (see Appendix D). In computerNet, there are 31 vertices and 43 edges, but only 7 vertices are source vertices. Moreover, c1, c12, and c23 are hub nodes, with at least 10 outgoing edges each. For the absolute count case, we set the size to 1 edge per source vertex, which is equivalent to a random walk. We expect exactly 7 edges to be selected. For the percentage sampling case, we sample 33% of the edges for vertices which have 3 or more outgoing edges. We expect about 15 edges, but the number may vary.
  * Query
  * Results


sampleEx3: SAMPLE based on edges per source vertex
```
CREATE QUERY sampleEx3() FOR GRAPH computerNet SYNTAX V1
{
  MapAccum<STRING,ListAccum<STRING>> @@absEdges; // record each selected edge as (src->tgt)
  SumAccum<INT> @@totalAbs;
  MapAccum<STRING,ListAccum<STRING>> @@pctEdges; // record each selected edge as (src->tgt)
  SumAccum<INT> @@totalPct;
  start = {computer.*};
  # Sample one outgoing edge per source vertex = Random Walk
  absSample = SELECT v FROM start:s -(:e)- :v
       SAMPLE 1 EDGE WHEN s.outdegree() >= 1  # sample 1 target vertex from each source vertex
       ACCUM @@absEdges += (s.id -> v.id),
          @@totalAbs += 1;
  PRINT @@totalAbs, @@absEdges;
  pctSample = SELECT v FROM start:s -(:e)- :v
       SAMPLE 33% EDGE WHEN s.outdegree() >= 3 # select ~1/3 of edges when outdegree >= 3
       ACCUM @@pctEdges += (s.id -> v.id),
          @@totalPct += 1;
  PRINT @@totalPct, @@pctEdges;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

sampleEx3.json
```
GSQL > RUN QUERY sampleEx3()
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [
  {
   "@@totalAbs": 7,
   "@@absEdges": {
    "c4": ["c23"],
    "c11": ["c12"],
    "c10": ["c11"],
    "c12": ["c14"],
    "c23": ["c26"],
    "c14": ["c24"],
    "c1": ["c10"]
   }
  },
  {
   "@@totalPct": 13,
   "@@pctEdges": {
    "c4": ["c23"],
    "c11": ["c12"],
    "c10": ["c11"],
    "c12": [
     "c14",
     "c15",
     "c19"
    ],
    "c23": [
     "c29",
     "c25"
    ],
    "c14": [
     "c24",
     "c23"
    ],
    "c1": [
     "c3",
     "c8",
     "c2"
    ]
   }
  }
 ]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Below is an example of using SELECT to only traverse one edge for each source vertex. The vertex-attached accumulators @timesTraversedNoSample and @timesTraversedWithSample are used to keep track of the number of times an edge is traversed to reach the target vertex. Without using sampling, this occurs once for each edge; thus @timesTraversedNoSample has the same number as the in-degree of the vertex. With sampling edges, the number of edges is restricted. This is reflected in the @timesTraversedWithSample accumulator. Notice the difference in the result set. Because only one edge per source vertex is traversed when the SAMPLE clause is used, not all target vertices are reached. The vertex **company3** has 3 incident edges, but in one instance of the query execution, it is never reached. Additionally, **company2** has 6 incident edges, but only 4 source vertices sampled an edge incident to **company2** .
  * Query
  * Results


example of SAMPLE using an absolute number of edges
```
CREATE QUERY sampleEx1() FOR GRAPH workNet SYNTAX V1
{
	SumAccum<INT> @timesTraversedNoSample;
	SumAccum<INT> @timesTraversedWithSample;
	workers = {person.*};
	# the 'beforeSample' result set encapsulates the normal functionality of
	# a SELECT statement, where 'timesTraversedNoSample' vertex accumulator is increased for
	# each edge incident to the vertex.
	beforeSample = SELECT v FROM workers:t -(:e)- :v
		    ACCUM v.@timesTraversedNoSample += 1;
	# The 'afterSample' result set is formed by those vertices which can be
	# reached when for each source vertex, only one edge is used for traversal.
	# This is demonstrated by the values of 'timesTraversedWithSample' vertex accumulator, which
	# is increased for each edge incident to the vertex which is used in the
	# sample.
	afterSample = SELECT v FROM workers:t -(:e)- :v
		   SAMPLE 1 EDGE WHEN t.outdegree() >= 1		# only use 1 edge from the source vertex
		   ACCUM v.@timesTraversedWithSample += 1;
	PRINT beforeSample;
	PRINT afterSample;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

sampleEx1.json
```
GSQL > RUN QUERY sampleEx1()
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [
  {"beforeSample": [
   {
    "v_id": "company4",
    "attributes": {
     "country": "us",
     "@timesTraversedNoSample": 1,
     "@timesTraversedWithSample": 1,
     "id": "company4"
    },
    "v_type": "company"
   },
   {
    "v_id": "company5",
    "attributes": {
     "country": "can",
     "@timesTraversedNoSample": 1,
     "@timesTraversedWithSample": 1,
     "id": "company5"
    },
    "v_type": "company"
   },
   {
    "v_id": "company3",
    "attributes": {
     "country": "jp",
     "@timesTraversedNoSample": 3,
     "@timesTraversedWithSample": 3,
     "id": "company3"
    },
    "v_type": "company"
   },
   {
    "v_id": "company2",
    "attributes": {
     "country": "chn",
     "@timesTraversedNoSample": 6,
     "@timesTraversedWithSample": 4,
     "id": "company2"
    },
    "v_type": "company"
   },
   {
    "v_id": "company1",
    "attributes": {
     "country": "us",
     "@timesTraversedNoSample": 6,
     "@timesTraversedWithSample": 3,
     "id": "company1"
    },
    "v_type": "company"
   }
  ]},
  {"afterSample": [
   {
    "v_id": "company4",
    "attributes": {
     "country": "us",
     "@timesTraversedNoSample": 1,
     "@timesTraversedWithSample": 1,
     "id": "company4"
    },
    "v_type": "company"
   },
   {
    "v_id": "company5",
    "attributes": {
     "country": "can",
     "@timesTraversedNoSample": 1,
     "@timesTraversedWithSample": 1,
     "id": "company5"
    },
    "v_type": "company"
   },
   {
    "v_id": "company3",
    "attributes": {
     "country": "jp",
     "@timesTraversedNoSample": 3,
     "@timesTraversedWithSample": 3,
     "id": "company3"
    },
    "v_type": "company"
   },
   {
    "v_id": "company2",
    "attributes": {
     "country": "chn",
     "@timesTraversedNoSample": 6,
     "@timesTraversedWithSample": 4,
     "id": "company2"
    },
    "v_type": "company"
   },
   {
    "v_id": "company1",
    "attributes": {
     "country": "us",
     "@timesTraversedNoSample": 6,
     "@timesTraversedWithSample": 3,
     "id": "company1"
    },
    "v_type": "company"
   }
  ]}
 ]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Since the PRINT statements are placed at the end of query, the two vertex sets _beforeSample_ and _afterSample_ are almost identical, showing the final values of both accumulators@timesTraversedNoSample and @timesTraversedWithSample. There is one difference: company3 is not included in afterSample because none of the sample-selected edges reached company3.  
---  
## [](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_where)WHERE
The WHERE clause is an optional clause that constrains edges and vertices specified in the FROM and SAMPLE clauses.
EBNF for Where Clause
```
whereClause := WHERE condition
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The WHERE clause uses a boolean condition to test each vertex or edge in the FROM set (or the sampled vertex and edge sets, if the SAMPLE clause was used).
If the expression evaluates to false for vertex/edge X, then X excluded from further consideration in the result set. The expression may use constants or any variables or parameters within the scope of the SELECT, arithmetic operators (+, -, *, /,%), comparison operators (==, !=, <, <=, >,>=), boolean operators (AND, OR, NOT), set operators (IN, NOT IN) and parentheses to enforce precedence. The WHERE conditional expression may use any of the variables within its scope (global accumulators, vertex set variables, query input parameters, the FROM clause’s vertex and edge sets (or their vertex and edge aliases), or any of the attributes or accumulators of the vertex/edge sets.) For a more formal explanation of condition, see the EBNF definitions of *condition* and **expr.**
Using built-in vertex and edge attributes and functions, such as .type and .neighbors(), the WHERE clause can be used to implement sophisticated selection rules for the edge traversal. In the following example, the selection conditions are completely specified in the WHERE clause, with no edge types or vertex types mentioned in the FROM clause.
WHERE used as a filter
```
resultSet1 = SELECT v FROM S:v-((E1|E2|E3):e)-(V1|V2):t;
resultSet2 = SELECT v FROM S:v-(:e)-:t
					 WHERE t.type IN ("V1", "V2") AND
						  t IN v.neighbors("E1|E2|E3")
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The following examples demonstrate using the WHERE clause to limit the resulting vertex set based on a vertex attribute.
  * Query
  * Results


Basic SELECT WHERE
```
CREATE QUERY printCatPosts() FOR GRAPH socialNet SYNTAX V1 {
	posts = {post.*};
	catPosts = SELECT v FROM posts:v		# select only those post vertices
        WHERE v.subject == "cats"; # which have a subset of 'cats'
	PRINT catPosts;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results for Query printCatPosts
```
GSQL > RUN QUERY printCatPosts()
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{"catPosts": [
  {
   "v_id": "10",
   "attributes": {
    "postTime": "2011-02-04 03:02:31",
    "subject": "cats"
   },
   "v_type": "post"
  },
  {
   "v_id": "9",
   "attributes": {
    "postTime": "2011-02-05 23:12:42",
    "subject": "cats"
   },
   "v_type": "post"
  },
  {
   "v_id": "3",
   "attributes": {
    "postTime": "2011-02-05 01:02:44",
    "subject": "cats"
   },
   "v_type": "post"
  },
  {
   "v_id": "11",
   "attributes": {
    "postTime": "2011-02-03 01:02:21",
    "subject": "cats"
   },
   "v_type": "post"
  },
  {
   "v_id": "8",
   "attributes": {
    "postTime": "2011-02-03 17:05:52",
    "subject": "cats"
   },
   "v_type": "post"
  }
 ]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * Query
  * Results


SELECT WHERE using IN operator
```
CREATE QUERY findGraphFocusedPosts() FOR GRAPH socialNet SYNTAX V1
{
	posts = {post.*};
	results = SELECT v FROM posts:v					# select only post vertices
		WHERE v.subject IN ("Graph", "tigergraph");	# which have a subject of either 'Graph' or 'tigergraph'
	PRINT results;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results for Query findGraphFocusedPosts
```
GSQL > RUN QUERY findGraphFocusedPosts()
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
   "v_id": "5",
   "attributes": {
    "postTime": "2011-02-06 01:02:02",
    "subject": "tigergraph"
   },
   "v_type": "post"
  },
  {
   "v_id": "1",
   "attributes": {
    "postTime": "2011-03-03 23:02:00",
    "subject": "tigergraph"
   },
   "v_type": "post"
  },
  {
   "v_id": "6",
   "attributes": {
    "postTime": "2011-02-05 02:02:05",
    "subject": "tigergraph"
   },
   "v_type": "post"
  }
 ]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

WHERE NOT limitations The NOT operator may not be used in combination with the .type attribute selector. To check if an edge or vertex type is not equal to a given type, use the != operator. See the example below.  
---  
The following example shows the equivalence of using `WHERE` as a type filter as well as its limitations.
  * Query
  * Results


SELECT WHERE using AND/OR
```
# finds female person in the social network. all of the following statements
# are equivalent (i.e., produce the same results)
CREATE QUERY findFemaleMembers() FOR GRAPH socialNet SYNTAX V1
{
	allVertices = {ANY}; # includes all posts and person
	females = SELECT v FROM allVertices:v
		 WHERE v.type  == "person" AND
		 	  v.gender != "Male";
	females = SELECT v FROM allVertices:v
		 WHERE v.type  == "person" AND
		 	  v.gender == "Female";
	females = SELECT v FROM allVertices:v
		 WHERE v.type    == "person" AND
		 	  NOT v.gender == "Male";
	females = SELECT v FROM allVertices:v
		 WHERE v.type    != "post" AND
		 	  NOT v.gender == "Male";
 	# does not compile. cannot use NOT operator in combination with type attribute
	#females = SELECT v FROM allVertices:v
	#	 WHERE NOT v.type  != "person" AND
	#	 	  NOT v.gender == "Male";
 	# does not compile. cannot use NOT operator in combination with type attribute
	#females = SELECT v FROM allVertices:v
	#	 WHERE NOT v.type  == "post" AND
	#	 	  NOT v.gender == "Male";
	personVertices = {person.*};
	females = SELECT v FROM personVertices:v
		  WHERE NOT v.gender == "Male";
	females = SELECT v FROM personVertices:v
		  WHERE v.gender != "Male";
	females = SELECT v FROM personVertices:v
		  WHERE v.gender != "Male" AND true;
	females = SELECT v FROM personVertices:v
		  WHERE v.gender != "Male" OR false;
	PRINT females;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results for Query findFemaleMembers
```
GSQL > RUN QUERY findFemaleMembers()
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{"females": [
  {
   "v_id": "person4",
   "attributes": {
    "gender": "Female",
    "id": "person4"
   },
   "v_type": "person"
  },
  {
   "v_id": "person5",
   "attributes": {
    "gender": "Female",
    "id": "person5"
   },
   "v_type": "person"
  },
  {
   "v_id": "person2",
   "attributes": {
    "gender": "Female",
    "id": "person2"
   },
   "v_type": "person"
  }
 ]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The following example uses edge attributes to determine which workers are registered as full time for some company.
  * Query
  * Results


WHERE using edge attributes
```
# find all workers who are full time at some company
CREATE QUERY fullTimeWorkers() FOR GRAPH workNet SYNTAX V1
{
	start = {person.*};
	fullTimeWorkers = SELECT v FROM start:v -(worksFor:e)- company:t
			WHERE e.fullTime;	# fullTime is a boolean attribute on the edge
	PRINT fullTimeWorkers;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

fullTimeWorkers Results
```
GSQL > RUN QUERY fullTimeWorkers()
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{"fullTimeWorkers": [
  {
   "v_id": "person4",
   "attributes": {
    "interestList": ["football"],
    "skillSet": [ 10, 1, 4 ],
    "skillList": [ 4, 1, 10 ],
    "locationId": "us",
    "interestSet": ["football"],
    "id": "person4"
   },
   "v_type": "person"
  },
  {
   "v_id": "person11",
   "attributes": {
    "interestList": [ "sport", "football" ],
    "skillSet": [10],
    "skillList": [10],
    "locationId": "can",
    "interestSet": [ "football", "sport" ],
    "id": "person11"
   },
   "v_type": "person"
  },
  {
   "v_id": "person10",
   "attributes": {
    "interestList": [ "football", "sport" ],
    "skillSet": [3],
    "skillList": [3],
    "locationId": "us",
    "interestSet": [ "sport", "football" ],
    "id": "person10"
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
    "id": "person1"
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
    "id": "person8"
   },
   "v_type": "person"
  },
  {
   "v_id": "person12",
   "attributes": {
    "interestList": [
     "music",
     "engineering",
     "teaching",
     "teaching",
     "teaching"
    ],
    "skillSet": [ 2, 5, 1 ],
    "skillList": [ 1, 5, 2, 2, 2 ],
    "locationId": "jp",
    "interestSet": [ "teaching", "engineering", "music" ],
    "id": "person12"
   },
   "v_type": "person"
  },
  {
   "v_id": "person3",
   "attributes": {
    "interestList": ["teaching"],
    "skillSet": [ 6, 1, 4 ],
    "skillList": [ 4, 1, 6 ],
    "locationId": "jp",
    "interestSet": ["teaching"],
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
    "id": "person9"
   },
   "v_type": "person"
  }
 ]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

If multiple edge types are specified in edge-induced selection, the WHERE clause should use OR to separate each edge type or each target vertex type. For example, Multiple Edge Type WHERE clause ```
CREATE QUERY multipleEdgeTypeWhereEx(vertex<person> m1) FOR GRAPH socialNet SYNTAX V1 {
 allUser = {m1};
 FilteredUser = SELECT s
   FROM allUser:s - ((posted|liked|friend):e) - (post|person):t
   # WHERE e.actionTime > epoch_to_datetime(1) AND t.gender == "Male";
   WHERE ( e.type == "liked" AND e.actionTime > epoch_to_datetime(1) ) OR
      ( e.type == "friend" AND t.gender == "Male" )
      ;
 PRINT FilteredUser;
}gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!
```
The above query is compilable. However, if we use line 5 as the WHERE clause instead, the query is not compilable. The edge-type conflict checking detects an error, because i t uses attributes from both "liked" edges and "friend" edges without separating them out by OR.  
---  
## [](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_accum_and_post_accum)ACCUM and POST-ACCUM
The optional ACCUM and POST-ACCUM clauses enable sophisticated aggregation and other computations across the set of vertices or edges selected by the preceding FROM, SAMPLE, and WHERE clauses. A query can contain one or both of these clauses. The statements in an ACCUM clause are applied for every edge in an edge-induced selection or every vertex in a vertex-induced selection.
If there is more than one statement in the ACCUM clause, the statements are separated by commas and executed sequentially for each selected element. However, the TigerGraph system uses parallelism to improve performance. Within an ACCUM clause, each edge is handled by a separate process. As such, there is no fixed order in which the edges are processed within the ACCUM clause and the edges should not be treated as executing sequentially. The accumulators are mutex variables shared among each of these processes. The results of any accumulation within the ACCUM clause is not complete until all edges are traversed. Any inspection of an intermediate result within the ACCUM is incomplete and may not be that meaningful.
The statements within the ACCUM clause are executed sequentially for a given vertex or edge. However, there is no fixed order in which a vertex set or edge set is processed.  
---  
The optional POST-ACCUM clause enables aggregation and other computations across the set of vertices (but not edges) selected by the preceding clauses. POST-ACCUM can be used without ACCUM. If it is preceded by an ACCUM clause, then it can be used for 2-stage accumulative computation: a first stage in ACCUM followed by a second stage in POST-ACCUM.
Each statement within the POST-ACCUM clause can refer to either source vertices or target vertices but not both.  
---  
Since the ACCUM clause iterates over edges, and often two edges will connect to the same source vertex or to the same target vertex, the ACCUM clause can be repeated multiple times for one vertex.
Operations that are to be performed exactly once per vertex should be performed in the POST-ACCUM clause.  
---  
The primary purpose of the ACCUM or POST-ACCUM clause is to collect information about the graph by updating accumulators (via += or =). See the "Accumulator" section for details on the += operation. However, other kinds of statements (e.g., branching, iteration, local assignments) are permitted to support more complex computations or to log activity. The EBNF syntax below defines the allowable kinds of statements that can occur within an ACCUM or POST-ACCUM. The **dmlSubStmt** list is similar to the **queryBodyStmt** list which applies to statements outside of a SELECT block; it is important to note the differences. Each of these statement types is discussed in one of the main sections of this reference document.
EBNF for ACCUM and POST-ACCUM Clauses
```
accumClause := [perClauseV2] ACCUM dmlSubStmtList
perClauseV2 := PER "(" alias ["," alias] ")"
postAccumClause := POST-ACCUM dmlSubStmtList
dmlSubStmtList := dmlSubStmt ["," dmlSubStmt]*
dmlSubStmt := assignStmt      // Assignment
      | funcCallStmt     // Function Call
      | gAccumAccumStmt   // Assignment
      | lAccumAccumStmt   // Assignment
      | attrAccumStmt    // Assignment
      | vAccumFuncCall    // Function Call
      | localVarDeclStmt   // Declaration
      | dmlSubCaseStmt    // Control Flow
      | dmlSubIfStmt     // Control Flow
      | dmlSubWhileStmt   // Control Flow
      | dmlSubForEachStmt  // Control Flow
      | BREAK        // Control Flow
      | CONTINUE       // Control Flow
      | insertStmt      // Data Modification
      | dmlSubDeleteStmt   // Data Modification
      | printlnStmt     // Output
      | logStmt       // Output
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Note that dml-sub-statements do not include global accumulator assignment statement (gAccumAssignStmt) but global accumulator accumulation statement (gAccumAccumStmt). Global accumulators may perform accumulation += but not assignment "=" within these clauses.  
---  
There are additional restrictions on dml-sub level statements:
  * Global variable assignment is permitted in ACCUM or POST-ACCUM clauses, but the change in value will not take place until the query completes. Therefore, if there are multiple assignment statements for the same variable, only the final one will take effect.
  * Vertex attribute assignment "=" is not permitted in an ACCUM clause. However, edge attribute assignment is permitted. This is because the ACCUM clause iterates over an edge set. Vertex attribute assignment is permitted in the POST-ACCUM clause. Like all updates, the change in value does not take place until the query completes.

  
---  
### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_aliases_and_accumpost_accum_iteration_model)Aliases and ACCUM/POST-ACCUM Iteration Model
To reference each element of the selected set, use the aliases defined in the FROM clause. For example, assume that we have the following aliases:
Example of vertex and edge aliases
```
FROM source:s -(edgeTypes:e)- targetTypes:t # edge-induced selection
FROM source:v                # vertex-induced selection
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Let (V1, V2,…​ Vn) be the vertices in the vertex-induced selection . The following pseudocode emulates ACCUM clause behavior.
Model for ACCUM behavior in vertex-induced selection
```
FOREACH v in (V1,V2,...Vn) DO # iterations may occur in parallel, in unknown order
 dmlSubStmts referencing v
DONE
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Let E = (E1, E2,…​ En) be the edges in the edge-induced selected set. Further, let S = (S1,S1,…​Sn) and T= (T1,T2,…​Tn) be the multisets (bags) of source vertices and target vertices which correspond to the edge set. S and T are bags, because they can contain repeated elements.
Model for ACCUM behavior in edge-induced selection
```
FOREACH i in (1..n) DO # iterations may occur in parallel, in unknown order
 dmlSubStmts referencing e, s, t, which really means e_i, s_i, t_i
DONE
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Note that any reference to the source alias s or target alias t is for the endpoint vertices of the current edge.
Similarly, the POST-ACCUM clause acts like a FOREACH loop on the vertex result set specified in the SELECT clause (e.g., either S or T).
### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_edgevertex_type_inference_and_conflict)Edge/Vertex Type Inference and Conflict
If multiple edge types are specified in edge-induced selection, each ACCUM statement in ACCUM clause checks whether edge types are conflicted. If only a subset of edge types are effective in an ACCUM statement , this statement is not executed on other edge types. For example:
Multiple Edge Type ACCUM statement check
```
CREATE QUERY multipleEdgeTypeCheckEx(vertex<person> m1) FOR GRAPH socialNet SYNTAX V1 {
 ListAccum<STRING> @@testList1, @@testList2, @@testList3;
 allUser = {m1};
 allUser = SELECT s
     FROM allUser:s - ((posted|liked|friend):e) - (post|person):t
     ACCUM @@testList1 += to_string(datetime_to_epoch(e.actionTime))
       ,@@testList2 += t.gender
       #,@@testList3 += to_string(datetime_to_epoch(e.actionTime)) + t.gender # illegal
        ;
 PRINT @@testList1, @@testList2, @@testList3;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

In the above example, line 6 is only executed on "liked" edges, because "actionTime" is the attribute of "liked" edge only. Similarly, line 7 is only executed on "friend" edges, because "gender" is the attribute of "person" only, and only "friend" edge uses "person" as target vertex. However, line 8 causes a compilation error, because it uses multiple edges where some edges cannot be supported in a part of the statement, i.e., "liked" edges doesn’t have t.gender, "friend" edges doesn’t have e.actionTime.
We strongly suggest that if multiple edge types are specified in edge-induced selection, ACCUM clauses should uses CASE statement (see Section "Control Flow Statements" for more details) to separate the operation on each edge type or each target vertex type (or combination of target vertex type and edge type). The edge-type conflict checking then checks the ACCUM statement inside each THEN/ELSE blocks based on the condition. For example, Multiple Edge Type ACCUM statement check 2 ```
CREATE QUERY multipleEdgeTypeCheckEx2(vertex<person> m1) FOR GRAPH socialNet SYNTAX V1 {
 ListAccum<STRING> @@testList1;
 allUser = {m1};
 allUser = SELECT s
      FROM allUser:s - ((posted|liked|friend):e) - (post|person):t
      ACCUM CASE
          WHEN e.type == "liked" THEN  # for liked edges
           @@testList1 += to_string(datetime_to_epoch(e.actionTime))
          WHEN e.type == "friend" THEN  # for friend edges
           @@testList1 += t.gender
          ELSE   # For the remained edge type, which is posted edges
           @@testList1 += to_string(datetime_to_epoch(t.postTime))
         END
      ;
 PRINT @@testList1;
}gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!
```
The above query is compilable. However, if we switch line 8 and line 10, the edge-type conflict checking generates errors because "liked" edges doesn’t support t.gender and "friend" edges doesn’t support e.actionTime.  
---  
Similar to the ACCUM clause, if multiple source/target vertex types are specified in edge-induced selection and the POST-ACCUM clauses accesses source/target vertex, each ACCUM statement in POST-ACCUM clause checks whether source/target vertex types are conflicted. If only a subset of source/target vertex types are effective in a POST-ACCUM statement, this statement is not executed on other source/target vertex types.
Similar to ACCUM clause, we strongly suggest that if multiple source/target vertex types are specified in edge-induced selection and the POST-ACCUM clauses accesses source/target vertex, POST-ACCUM clauses should uses CASE statement (see Section "Control Flow Statements" for more details) to separate the operation on each source/target vertex type. The vertex type conflict checking then checks the ACCUM statement inside each THEN/ELSE blocks based on the condition.  
---  
### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_rules_for_updating_vertex_attached_accumulators)Rules for Updating Vertex-Attached Accumulators
Prior to v1.0, a vertex-attached accumulator could only be updated in an ACCUM or POST-ACCUM clause and only if its vertex was selected for by the preceding FROM-SAMPLE-WHERE clauses.
Beginning in v1.0, there are additional circumstances where a vertex-attached accumulator may be updated. Vertices which are _referenced via a vertex-attached accumulator of a selected vertex_ may have their vertex-attached accumulators updated in the ACCUM clause (but not in the POST-ACCUM clause). That is, a vertex referenced by an selected vertex can be updated, with some limitations explained below. Some examples will help to illustrate this more complex condition.
  * Suppose a query declares a vertex-attached _accumulator which holds vertex information_ . We call this a **vertex-holding accumulator** . This could take several forms:
    * A scalar accumulator, e.g., MaxAccum< **VERTEX** > @maxV;
    * A collection accumulator: e.g., ListAccum< **VERTEX** > @listV;
    * An accumulator containing tuple(s), where the tuple type contains a **VERTEX** field.
  * If a vertex V is selected, then not only can V’s accumulators be updated, but the vertices stored in its vertex-holding accumulators can also be updated, in the ACCUM clause.
  * Before these indirectly referenced vertices can be used, they need to be **activated** . There are two ways to activate an indirect vertex:
    * A vertex from a vertex-holding accumulator is first assigned to a local vertex variable. The vertex can then be updated through the local vertex variable.


```
ACCUM
 VERTEX<person> mx = tgt.@maxV,  # assign to local variable
     mx.@curId += src.id   # access via local variable
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * A FOREACH loop can iterate on a vertex-holding collection accumulator. The vertices can now be updated through the loop variable.


```
ACCUM
 FOREACH vtx IN src.@setIds DO  # iterate on collection accumulator
   vtx.@curId += tgt.id    # access via loop variable
 END
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The following uses are NOT supported by the new rules:
  * Indirectly activated vertices may not be updated in the POST-ACCUM clause or outside a SELECT statement.
  * Passing a vertex into the query as an input parameter is not a route to activation.
  * Using a global vertex-holding accumulator is not a route to activation.
  * If a vertex is being indirectly activated by assigning it to a local variable (e.g., a variable declaring in ACCUM or POST-ACCUM), note the following rule, which always applies to all local variables:
    * A local variable can be declared and initialized in an ACCUM block once. It cannot be redeclared or reassigned later in the ACCUM block.

  
---  
The following query demonstrates updates to indirectly activated vertices.
  * Query
  * Results


Updating an Indirectly-Referenced Vertex
```
CREATE QUERY vUpdateIndirectAccum() FOR GRAPH socialNet SYNTAX V1 {
 SetAccum<VERTEX<person>> @posters;
 SetAccum<VERTEX<person>> @fellows;
  Persons = {person.*};
  # To each post, attach a list of persons who liked the post
  likedPosts = SELECT p
    FROM Persons:src -(liked:e)- post:p
    ACCUM
    	p.@posters += src;
  # To each person who liked a post, attach a list of everyone
  # who also liked one of this person's liked posts.
	likedPosts = SELECT src
		FROM likedPosts:src
		ACCUM
		 FOREACH v IN src.@posters DO
		  v.@fellows += src.@posters
		 END
    ORDER BY src.subject;
	PRINT Persons[Persons.@fellows];
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results from Query vUpdateIndirectAccums
```
GSQL > RUN QUERY vUpdateIndirectAccess()
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{"Persons": [
  {
   "v_id": "person4",
   "attributes": {"Persons.@fellows": [
    "person8",
    "person4"
   ]},
   "v_type": "person"
  },
  {
   "v_id": "person3",
   "attributes": {"Persons.@fellows": [ "person2", "person1", "person3" ]},
   "v_type": "person"
  },
  {
   "v_id": "person7",
   "attributes": {"Persons.@fellows": ["person7"]},
   "v_type": "person"
  },
  {
   "v_id": "person1",
   "attributes": {"Persons.@fellows": [ "person2", "person1", "person3" ]},
   "v_type": "person"
  },
  {
   "v_id": "person5",
   "attributes": {"Persons.@fellows": ["person5"]},
   "v_type": "person"
  },
  {
   "v_id": "person6",
   "attributes": {"Persons.@fellows": ["person6"]},
   "v_type": "person"
  },
  {
   "v_id": "person2",
   "attributes": {"Persons.@fellows": [ "person2", "person1", "person3" ]},
   "v_type": "person"
  },
  {
   "v_id": "person8",
   "attributes": {"Persons.@fellows": [ "person8", "person4" ]},
   "v_type": "person"
  }
 ]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_accum_and_post_accum_examples)ACCUM and POST-ACCUM Examples
We now show several examples. This example demonstrates how ACCUM or POST-ACCUM can be used to count the number of vertices in the given set.
  * Query
  * Results


Accum and PostAccum Semantics
```
#Show Accum PostAccum Behavior
CREATE QUERY accumPostAccumSemantics() FOR GRAPH workNet SYNTAX V1 {
 SumAccum<INT> @@vertexOnlyAccum;
 SumAccum<INT> @@vertexOnlyPostAccum;
 SumAccum<INT> @@vertexOnlyWhereAccum;
 SumAccum<INT> @@vertexOnlyWherePostAccum;
 SumAccum<INT> @@sourceWithEdgeAccum;
 SumAccum<INT> @@sourceWithEdgePostAccum;
 SumAccum<INT> @@targetWithEdgeAccum;
 SumAccum<INT> @@targetWithEdgePostAccum;
 #Seed start set with all company vertices
 start = {company.*};
 #Select all vertices in source set start
 selectVertexSet = SELECT v from start:v
					#Happens once for each vertex discovered
					ACCUM @@vertexOnlyAccum += 1
					#Happens once for each vertex in the result set "v"
					POST-ACCUM @@vertexOnlyPostAccum += 1;
 #Select all vertices in source set start with a where constraint
 selectVertexSetWhere = SELECT v from start:v WHERE (v.country == "us")
						#Happens once for each vertex discovered that also
						# meets the constraint condition
						ACCUM @@vertexOnlyWhereAccum += 1
						#Happens once for each vertex in the result set "v"
						POST-ACCUM @@vertexOnlyWherePostAccum += 1;
 #Select all source "s" vertices in set start and explore all "worksFor" edge paths
 selectSourceWithEdge = SELECT s from start:s -(worksFor)- :t
		 		    	 #Happens once for each "worksFor" edge discovered
						 ACCUM @@sourceWithEdgeAccum += 1
						#Happens once for each vertex in result set "s" (source)
						POST-ACCUM @@sourceWithEdgePostAccum += 1;
 #Select all target "t" vertices found from exploring all "worksFor" edge paths from set start
 selectTargetWithEdge = SELECT t from start:s -(worksFor)- :t
						 #Happens once for each "worksFor" edge discovered
						 ACCUM @@targetWithEdgeAccum += 1
						 #Happens once for each vertex in result set "t" (target)
						 POST-ACCUM @@targetWithEdgePostAccum += 1;
 PRINT @@vertexOnlyAccum;
 PRINT @@vertexOnlyPostAccum;
 PRINT @@vertexOnlyWhereAccum;
 PRINT @@vertexOnlyWherePostAccum;
 PRINT @@sourceWithEdgeAccum;
 PRINT @@sourceWithEdgePostAccum;
 PRINT @@targetWithEdgeAccum;
 PRINT @@targetWithEdgePostAccum;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

accumPostAccumSemantics Result
```
GSQL > RUN QUERY accumPostAccumSemantics()
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [
  {"@@vertexOnlyAccum": 5},
  {"@@vertexOnlyPostAccum": 5},
  {"@@vertexOnlyWhereAccum": 2},
  {"@@vertexOnlyWherePostAccum": 2},
  {"@@sourceWithEdgeAccum": 17},
  {"@@sourceWithEdgePostAccum": 5},
  {"@@targetWithEdgeAccum": 17},
  {"@@targetWithEdgePostAccum": 12}
 ]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This example uses ACCUM to find all the subjects a user posted about.
  * Query
  * Results


Vertex ACCUM Example
```
# For each person, make a list of all their post subjects
CREATE QUERY userPosts() FOR GRAPH socialNet SYNTAX V1 {
 ListAccum<STRING> @personPosts;
 start = {person.*};
 # Find all user post topics and append them to the vertex list accum
 userPostings = SELECT s FROM start:s -(posted)- :g
         ACCUM s.@personPosts += g.subject;
 PRINT userPostings;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results for Query userPosts
```
GSQL > RUN QUERY userPosts()
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{"userPostings": [
  {
   "v_id": "person4",
   "attributes": {
    "gender": "Female",
    "@personPosts": ["cats"],
    "id": "person4"
   },
   "v_type": "person"
  },
  {
   "v_id": "person3",
   "attributes": {
    "gender": "Male",
    "@personPosts": ["query languages"],
    "id": "person3"
   },
   "v_type": "person"
  },
  {
   "v_id": "person7",
   "attributes": {
    "gender": "Male",
    "@personPosts": [ "cats", "tigergraph" ],
    "id": "person7"
   },
   "v_type": "person"
  },
  {
   "v_id": "person1",
   "attributes": {
    "gender": "Male",
    "@personPosts": ["Graphs"],
    "id": "person1"
   },
   "v_type": "person"
  },
/*** other vertices omitted ***/
 ]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This example shows each person’s posted vertices and each person’s like behaviors (liked edges).
  * Query
  * Results


`ACCUM<VERTEX>` and `ACCUM<EDGE>` Example
```
# Show each user's post and liked post time
CREATE QUERY userPosts2() FOR GRAPH socialNet SYNTAX V1 {
 ListAccum<VERTEX> @personPosts;
 ListAccum<EDGE> @personLikedInfo;
 start = {person.*};
 # Find all user post topics and append them to the vertex list accum
 userPostings = SELECT s FROM start:s -(posted)- :g
         ACCUM s.@personPosts += g;
 userPostings = SELECT s from start:s -(liked:e)- :g
         ACCUM s.@personLikedInfo += e;
 PRINT start;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results from Query userPosts2
```
GSQL > RUN QUERY userPosts2()
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{"start": [
  {
   "v_id": "person4",
   "attributes": {
    "gender": "Female",
    "@personPosts": ["3"],
    "id": "person4",
    "@personLikedInfo": [{
     "from_type": "person",
     "to_type": "post",
     "directed": true,
     "from_id": "person4",
     "to_id": "4",
     "attributes": {"actionTime": "2010-01-13 03:16:05"},
     "e_type": "liked"
    }]
   },
   "v_type": "person"
  },
  {
   "v_id": "person7",
   "attributes": {
    "gender": "Male",
    "@personPosts": [ "9", "6" ],
    "id": "person7",
    "@personLikedInfo": [{
     "from_type": "person",
     "to_type": "post",
     "directed": true,
     "from_id": "person7",
     "to_id": "10",
     "attributes": {"actionTime": "2010-01-12 11:22:05"},
     "e_type": "liked"
    }]
   },
   "v_type": "person"
  },
  {
   "v_id": "person1",
   "attributes": {
    "gender": "Male",
    "@personPosts": ["0"],
    "id": "person1",
    "@personLikedInfo": [{
     "from_type": "person",
     "to_type": "post",
     "directed": true,
     "from_id": "person1",
     "to_id": "0",
     "attributes": {"actionTime": "2010-01-11 11:32:00"},
     "e_type": "liked"
    }]
   },
   "v_type": "person"
  },
/*** other vertices omitted ***/
 ]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This example counts the total number of times each topic is used.
  * Query
  * Results


Global ACCUM Example
```
# Show number of total posts by topic
CREATE QUERY userPostsByTopic() FOR GRAPH socialNet SYNTAX V1 {
 MapAccum<STRING, INT> @@postTopicCounts;
 start = {person.*};
 # Append subject and update the appearance count in the global map accum
 posts = SELECT g FROM start -(posted)- :g
		 ACCUM @@postTopicCounts += (g.subject -> 1);
 PRINT @@postTopicCounts;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results for Query userPostsByTopic
```
GSQL > RUN QUERY userPostsByTopic()
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{"@@postTopicCounts": {
  "cats": 5,
  "coffee": 1,
  "query languages": 1,
  "Graphs": 2,
  "tigergraph": 3
 }}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This is an example of using ACCUM and POST-ACCUM in conjunction. The ACCUM traverses the graph and finds all people who live and work in the same country. After this is determined, POST-ACCUM examines each vertex (person) to see if they work where they live.
  * Query
  * Results


Vertex POST-ACCUM Example
```
#Show all person who both work and live in the same country
CREATE QUERY residentEmployees() FOR GRAPH workNet SYNTAX V1 {
 ListAccum<STRING> @company;
 OrAccum @worksAndLives;
 start = {person.*};

 employees = SELECT s FROM start:s -(worksFor)- :c
       #If a person works for a company in the same country where they live
       # add the company to the list
       ACCUM CASE WHEN (s.locationId == c.country) THEN
              s.@company += c.id
             END
       #Check each vertex and see if a person works where they live
       POST-ACCUM CASE WHEN (s.@company.size() > 0) THEN
              s.@worksAndLives += True
             ELSE
              s.@worksAndLives += False
             END;
 PRINT employees WHERE (employees.@worksAndLives == True);
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

residentEmployees Result
```
GSQL > RUN QUERY residentEmployees()
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{"employees": [
  {
   "v_id": "person11",
   "attributes": {
    "interestList": [
     "sport",
     "football"
    ],
    "skillSet": [10],
    "skillList": [10],
    "@worksAndLives": true,
    "locationId": "can",
    "interestSet": [ "football", "sport" ],
    "id": "person11",
    "@company": ["company5"]
   },
   "v_type": "person"
  },
  {
   "v_id": "person10",
   "attributes": {
    "interestList": [ "football", "sport" ],
    "skillSet": [3],
    "skillList": [3],
    "@worksAndLives": true,
    "locationId": "us",
    "interestSet": [ "sport", "football" ],
    "id": "person10",
    "@company": ["company1"]
   },
   "v_type": "person"
  },
  {
   "v_id": "person1",
   "attributes": {
    "interestList": [ "management", "financial" ],
    "skillSet": [ 3, 2, 1 ],
    "skillList": [ 1, 2, 3 ],
    "@worksAndLives": true,
    "locationId": "us",
    "interestSet": [ "financial", "management" ],
    "id": "person1",
    "@company": ["company1"]
   },
   "v_type": "person"
  },
  {
   "v_id": "person2",
   "attributes": {
    "interestList": ["engineering"],
    "skillSet": [ 6, 5, 3, 2 ],
    "skillList": [ 2, 3, 5, 6 ],
    "@worksAndLives": true,
    "locationId": "chn",
    "interestSet": ["engineering"],
    "id": "person2",
    "@company": ["company2"]
   },
   "v_type": "person"
  }
 ]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This is an example of a POST-ACCUM only that counts the number people with a particular gender.
  * Query
  * Results


Global POST-ACCUM Example
```
#Count the number of person of	a given	gender
CREATE QUERY personGender(STRING gender) FOR GRAPH socialNet SYNTAX V1 {
 SumAccum<INT> @@genderCount;
 start = {ANY};
 # Select all person vertices and check the gender attribute
 friends = SELECT v FROM start:v
      WHERE v.type == "person"
      POST-ACCUM CASE WHEN (start.gender == gender) THEN
             @@genderCount += 1
            END;
 PRINT @@genderCount;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results for Query personGender
```
GSQL > RUN QUERY personGender("Female")
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{"@@genderCount": 3}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_having)HAVING
The optional HAVING clause provides constraints on the result set of the SELECT. The constraints are applied **after** ACCUM and POST-ACCUM actions. This differs from the WHERE clause, which is applied **before** the ACCUM and POST-ACCUM actions.
EBNF for HAVING Clause
```
havingClause := HAVING condition
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The condition in a `HAVING` clause is applied to each vertex in the `SELECT` set (either source or target vertices) which also fulfilled the `FROM` and `WHERE` conditions. The `HAVING` clause is intended to test one or more of the accumulator variables that were updated in the `ACCUM` or `POST-ACCUM` clause, though the condition may be anything that equates to a boolean value. If the condition is false for a particular vertex, then that vertex is excluded from the result set.
The following example demonstrates using the HAVING clause to constrain a result set based on the vertex accumulator variable which was updated during the ACCUM clause.
  * Query
  * Results


Example 1. HAVING
```
# find all persons meeting a given activityThreshold, based on how many posts or likes a person has made
CREATE QUERY activeMembers(int activityThreshold) FOR GRAPH socialNet SYNTAX V1
{
    SumAccum<int> @activityAmount;
    start = {person.*};
    result = SELECT v FROM start:v -(:e)- post:tgt
             ACCUM v.@activityAmount +=1
	           HAVING v.@activityAmount >= activityThreshold;
    PRINT result;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

If the activityThreshold parameter is set to 3, the query returns 5 vertices:
Example 1 Results
```
GSQL > RUN QUERY activeMembers(3)
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{"result": [
  {
   "v_id": "person7",
   "attributes": {
    "gender": "Male",
    "@activityAmount": 3,
    "id": "person7"
   },
   "v_type": "person"
  },
  {
   "v_id": "person5",
   "attributes": {
    "gender": "Female",
    "@activityAmount": 3,
    "id": "person5"
   },
   "v_type": "person"
  },
  {
   "v_id": "person6",
   "attributes": {
    "gender": "Male",
    "@activityAmount": 3,
    "id": "person6"
   },
   "v_type": "person"
  },
  {
   "v_id": "person2",
   "attributes": {
    "gender": "Female",
    "@activityAmount": 3,
    "id": "person2"
   },
   "v_type": "person"
  },
  {
   "v_id": "person8",
   "attributes": {
    "gender": "Male",
    "@activityAmount": 3,
    "id": "person8"
   },
   "v_type": "person"
  }
 ]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

If the activityThreshold parameter is set to 2, the query would return 8 vertices. With activityThreshold = 4, the query would return no vertices.
The following example demonstrates the equivalence of a SELECT statement in which the condition for the HAVING clause is always true.
  * Query
  * Results


Example 2. HAVING with literal condition
```
# find all person meeting a given activityThreshold, based on how many posts or likes a person has made
CREATE QUERY printMemberActivity() FOR GRAPH socialNet SYNTAX V1
{
    SumAccum<int> @activityAmount;
    start = {person.*};
		### --- equivalent statements -----
    result = SELECT v FROM start:v -(:e)- post:tgt
					   ACCUM v.@activityAmount +=1
					   HAVING true;
		result = SELECT v FROM start:v -(:e)- post:tgt
					   ACCUM v.@activityAmount +=1;
		### -----
    PRINT result;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results from Query printMemberActivity
```
GSQL > RUN QUERY printMemberActivity()
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{"result": [
  {
   "v_id": "person4",
   "attributes": {
    "gender": "Female",
    "@activityAmount": 4,
    "id": "person4"
   },
   "v_type": "person"
  },
  {
   "v_id": "person3",
   "attributes": {
    "gender": "Male",
    "@activityAmount": 4,
    "id": "person3"
   },
   "v_type": "person"
  },
  {
   "v_id": "person7",
   "attributes": {
    "gender": "Male",
    "@activityAmount": 6,
    "id": "person7"
   },
   "v_type": "person"
  },
  {
   "v_id": "person1",
   "attributes": {
    "gender": "Male",
    "@activityAmount": 4,
    "id": "person1"
   },
   "v_type": "person"
  },
  {
   "v_id": "person5",
   "attributes": {
    "gender": "Female",
    "@activityAmount": 6,
    "id": "person5"
   },
   "v_type": "person"
  },
  {
   "v_id": "person6",
   "attributes": {
    "gender": "Male",
    "@activityAmount": 6,
    "id": "person6"
   },
   "v_type": "person"
  },
  {
   "v_id": "person2",
   "attributes": {
    "gender": "Female",
    "@activityAmount": 6,
    "id": "person2"
   },
   "v_type": "person"
  },
  {
   "v_id": "person8",
   "attributes": {
    "gender": "Male",
    "@activityAmount": 6,
    "id": "person8"
   },
   "v_type": "person"
  }
 ]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The following shows an example of equivalent result sets from using WHERE vs. HAVING. Recall that the WHERE clause is evaluated before the ACCUM and that the HAVING clause is evaluated after the ACCUM. Both constrain the result set based on a condition that vertices must meet.
  * Query
  * Results


Example 3. HAVING vs. WHERE
```
# Compute the total post activity for each male person.
# Because the gender of the vertex does not change, evaluating whether the person vertex
# is male before (WHERE) the ACCUM clause or after (HAVING) the ACCUM clause does not
# change the result. However, if the condition in the HAVING clause could change within
# the ACCUM clause, these statements would produce different results.
CREATE QUERY activeMaleMembers() FOR GRAPH socialNet SYNTAX V1
{
  SumAccum<INT> @activityAmount;
  start = {person.*};
  ### --- statements produce equivalent results
  result1 = SELECT v FROM start:v -(:e)- post:tgt
           WHERE v.gender == "Male"
           ACCUM v.@activityAmount +=1;
  result2 = SELECT v FROM start:v -(:e)- post:tgt
           ACCUM v.@activityAmount +=1
           HAVING v.gender == "Male";
  PRINT result1;
  PRINT result2;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results from Query ActiveMaleMembers
```
[
 {
  "result1": [
   {
    "attributes": {
     "@activityAmount": 6,
     "gender": "Male",
     "id": "person7"
    },
    "v_id": "person7",
    "v_type": "person"
   },
   {
    "attributes": {
     "@activityAmount": 4,
     "gender": "Male",
     "id": "person3"
    },
    "v_id": "person3",
    "v_type": "person"
   },
   {
    "attributes": {
     "@activityAmount": 6,
     "gender": "Male",
     "id": "person8"
    },
    "v_id": "person8",
    "v_type": "person"
   },
   {
    "attributes": {
     "@activityAmount": 6,
     "gender": "Male",
     "id": "person6"
    },
    "v_id": "person6",
    "v_type": "person"
   },
   {
    "attributes": {
     "@activityAmount": 4,
     "gender": "Male",
     "id": "person1"
    },
    "v_id": "person1",
    "v_type": "person"
   }
  ]
 },
 {
  "result2": [
   {
    "attributes": {
     "@activityAmount": 4,
     "gender": "Male",
     "id": "person1"
    },
    "v_id": "person1",
    "v_type": "person"
   },
   {
    "attributes": {
     "@activityAmount": 4,
     "gender": "Male",
     "id": "person3"
    },
    "v_id": "person3",
    "v_type": "person"
   },
   {
    "attributes": {
     "@activityAmount": 6,
     "gender": "Male",
     "id": "person6"
    },
    "v_id": "person6",
    "v_type": "person"
   },
   {
    "attributes": {
     "@activityAmount": 6,
     "gender": "Male",
     "id": "person7"
    },
    "v_id": "person7",
    "v_type": "person"
   },
   {
    "attributes": {
     "@activityAmount": 6,
     "gender": "Male",
     "id": "person8"
    },
    "v_id": "person8",
    "v_type": "person"
   }
  ]
 }
]
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The following example has a compilation error because the result set is taken from the source vertices, but the HAVING condition is checking the target vertices.
  * Query
  * Results


Example 4. HAVING the wrong vertex set
```
# find all person having a post subject about cats
# This query is illegal because the having condition is testing the wrong vertex set
CREATE QUERY printMemberAboutCats() FOR GRAPH socialNet SYNTAX V1
{
    start = {person.*};
    result = SELECT v FROM start:v -(:e)- post:tgt
             HAVING tgt.subject == "cats";
    PRINT result;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Compilation Error for printMemberAboutCats
```
> gsql printMemberAboutCats.gsql
Semantic Check Error in query printMemberAboutCats (SEM-50): line 8, col 33
The SELECT block selects src, but the HAVING clause uses tgt
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_order_by)ORDER BY
The optional ORDER BY clause sorts the result set.
EBNF for ORDER BY Clause
```
orderClause := ORDER BY expr [ASC | DESC] ["," expr [ASC | DESC]]*
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

ASC specifies ascending order (least value first), and DESC specifies descending order (greatest value first). If neither is specified, then ascending order is used. Each expr must refer to the attributes or accumulators of a member of the result set, and the expr must evaluate to a sortable value (e.g., a number or a string). ORDER BY offers hierarchical sorting by allowing a comma-separated list of expressions, sorting first by the leftmost expr. It uses the next expression only to sort items where the current sort expr results in identical values. Any items in the result set which cannot be sorted (because the sort expressions do not pertain to them) will appear at the end of the set, after the sorted items.
In tabular SELECT queries, the ORDER BY expressions may only be SELECT column aliases.  
---  
The following example demonstrates the use of ORDER BY with multiple expressions. The returned vertex set is first ordered by the number of friends of the vertex, and then ordered by the number of coworkers of that vertex.
  * Query
  * Results


topPopular.gsql: ORDER BY Descending
```
# find the most popular people, sorting first based on the number as friends
# and then in case of a tie by the number of coworkers
CREATE QUERY topPopular() FOR GRAPH friendNet SYNTAX V1
{
	SumAccum<INT> @numFriends;
	SumAccum<INT> @numCoworkers;
	start = {person.*};
	result = SELECT v FROM start -((friend|coworker):e)- person:v
	    	 ACCUM CASE WHEN e.type == "friend" THEN v.@numFriends += 1
		    	  WHEN e.type == "coworker" THEN v.@numCoworkers += 1
		    END
		 ORDER BY v.@numFriends DESC, v.@numCoworkers DESC;
	PRINT result;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

topPopular.json
```
GSQL > RUN QUERY topPopular()
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{"result": [
  {
   "v_id": "person9",
   "attributes": {
    "@numCoworkers": 3,
    "@numFriends": 5,
    "id": "person9"
   },
   "v_type": "person"
  },
  {
   "v_id": "person8",
   "attributes": {
    "@numCoworkers": 1,
    "@numFriends": 4,
    "id": "person8"
   },
   "v_type": "person"
  },
  {
   "v_id": "person12",
   "attributes": {
    "@numCoworkers": 1,
    "@numFriends": 4,
    "id": "person12"
   },
   "v_type": "person"
  },
  {
   "v_id": "person6",
   "attributes": {
    "@numCoworkers": 4,
    "@numFriends": 3,
    "id": "person6"
   },
   "v_type": "person"
  },
  {
   "v_id": "person1",
   "attributes": {
    "@numCoworkers": 3,
    "@numFriends": 3,
    "id": "person1"
   },
   "v_type": "person"
  },
  {
   "v_id": "person4",
   "attributes": {
    "@numCoworkers": 5,
    "@numFriends": 2,
    "id": "person4"
   },
   "v_type": "person"
  },
  {
   "v_id": "person3",
   "attributes": {
    "@numCoworkers": 3,
    "@numFriends": 2,
    "id": "person3"
   },
   "v_type": "person"
  },
  {
   "v_id": "person2",
   "attributes": {
    "@numCoworkers": 3,
    "@numFriends": 2,
    "id": "person2"
   },
   "v_type": "person"
  },
  {
   "v_id": "person10",
   "attributes": {
    "@numCoworkers": 1,
    "@numFriends": 2,
    "id": "person10"
   },
   "v_type": "person"
  },
  {
   "v_id": "person7",
   "attributes": {
    "@numCoworkers": 6,
    "@numFriends": 1,
    "id": "person7"
   },
   "v_type": "person"
  },
  {
   "v_id": "person5",
   "attributes": {
    "@numCoworkers": 5,
    "@numFriends": 1,
    "id": "person5"
   },
   "v_type": "person"
  },
  {
   "v_id": "person11",
   "attributes": {
    "@numCoworkers": 1,
    "@numFriends": 1,
    "id": "person11"
   },
   "v_type": "person"
  }
 ]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/select-statement-v1#_limit)LIMIT
The optional LIMIT clause sets constraints on the number and ranking of items included in the final result set.
EBNF for LIMIT Clause
```
limitClause := LIMIT ( expr | expr "," expr | expr OFFSET expr )
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Each of the expr must evaluate to a nonnegative integer. To understand LIMIT, note that the tentative result set is held in the computer as a list of vertices. If the query has an ORDER BY clause, the order is specified; otherwise the list order is unknown. Assume we number the vertices as v_1 , v_2 , …​, v_n . The LIMIT clause specifies a range of vertices, starting from a lower position in the list to an upper position.
There are three forms:
LIMIT scenarios
```
result = SELECT v FROM S -(:e)- :v LIMIT k;		 # case 1: k = Count
result = SELECT v FROM S -(:e)- :v LIMIT j, k; 	 # case 2: j = Offset from the start of the list, k = Count
result = SELECT v FROM S -(:e)- :v LIMIT k OFFSET j; # case 3: k = Count, j = Offset from the start of the list
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Case 1: LIMIT k
  * When a single expr is provided, LIMIT returns the first **k** elements from the tentative result set. If there are fewer than **k** elements available, then all elements will be returned in the result set. If k=5 and the tentative result set has at least 5 items, then the final result list will be [ v_1 , v_2 , v_3 , v_4 , v_5 ].


Case 2: LIMIT j, k
  * When a comma separates two expressions, LIMIT treats the first expression **j** as an offset. That is, it skips the first **j** items in the list. The second expr **k** tells the maximum number of items items to include. If the list has at least 7 items, then LIMIT 2, 5 would return [ v_3 , v_4 , v_5, v_6 _,_ v_7 ].


Case 3: LIMIT k OFFSET j
  * The behavior of Case 3 is the same as that of Case 2, except that the syntax is different. The keyword OFFSET separates the two expressions, and the count comes before the offset, rather than vice versa. If the list has at least 7 items, then LIMIT 5 OFFSET 2 would return [ v_3 , v_4 , v_5, v_6 , v_7 ].


If any of the expressions evaluate to a negative integer, the results are undefined.
OFFSET is intended for result sets which are in a known order. It is a compile time error to use OFFSET without the ORDER BY clause.  
---  
The following examples demonstrate the various forms of the LIMIT clause.
The first example shows the LIMIT clause when used as an upper limit. It returns a result set with a maximum size of 4 elements in the set.
  * Query
  * Results


limitEx1.gsql: LIMIT by some number
```
CREATE QUERY limitEx1(INT k) FOR GRAPH friendNet SYNTAX V1
{
    start = {person.*};
    result1 = SELECT v FROM start:v
        ORDER BY v.id
        LIMIT k;
		PRINT result1[result1.id]; // api v2
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

limit1Ex.json Results
```
GSQL > RUN QUERY limitEx1(4)
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{"result1": [
  {
   "v_id": "person1",
   "attributes": {"result1.id": "person1"},
   "v_type": "person"
  },
  {
   "v_id": "person10",
   "attributes": {"result1.id": "person10"},
   "v_type": "person"
  },
  {
   "v_id": "person11",
   "attributes": {"result1.id": "person11"},
   "v_type": "person"
  },
  {
   "v_id": "person12",
   "attributes": {"result1.id": "person12"},
   "v_type": "person"
  }
 ]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The following example shows how to use the LIMIT clause with an offset.
  * Query
  * Results


limit2Ex.gsql: LIMIT with lower-bound and size
```
CREATE QUERY limitEx2(INT j, INT k) FOR GRAPH friendNet SYNTAX V1
{
    start = {person.*};
    result2 = SELECT v FROM start:v
        ORDER BY v.id
        LIMIT j, k;
    PRINT result2[result2.id]; // api v2
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

limit2Ex.json Results
```
GSQL > RUN QUERY limitEx2(2,3)
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{"result2": [
  {
   "v_id": "person11",
   "attributes": {"result2.id": "person11"},
   "v_type": "person"
  },
  {
   "v_id": "person12",
   "attributes": {"result2.id": "person12"},
   "v_type": "person"
  },
  {
   "v_id": "person2",
   "attributes": {"result2.id": "person2"},
   "v_type": "person"
  }
 ]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The following example shows the alternative syntax for a result size limit with an offset. This time we try larger values for offset and size. In a large data set, limitTest(5,20) might return 20 vertices, but since we don’t have 25 vertices in the original data, the output was fewer than 20 vertices.
  * Query
  * Results


limit3Ex.gsql: LIMIT with OFFSET
```
CREATE QUERY limitEx3(INT j, INT k) FOR GRAPH friendNet SYNTAX V1
{
    start = {person.*};
    result3 = SELECT v FROM start:v
        ORDER BY v.id
        LIMIT k OFFSET j;
    PRINT result3[result3.id]; // api v2
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

limit3Ex.json Results
```
GSQL > RUN QUERY limitEx3(5,20)
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{"result3": [
  {
   "v_id": "person3",
   "attributes": {"result3.id": "person3"},
   "v_type": "person"
  },
  {
   "v_id": "person4",
   "attributes": {"result3.id": "person4"},
   "v_type": "person"
  },
  {
   "v_id": "person5",
   "attributes": {"result3.id": "person5"},
   "v_type": "person"
  },
  {
   "v_id": "person6",
   "attributes": {"result3.id": "person6"},
   "v_type": "person"
  },
  {
   "v_id": "person7",
   "attributes": {"result3.id": "person7"},
   "v_type": "person"
  },
  {
   "v_id": "person8",
   "attributes": {"result3.id": "person8"},
   "v_type": "person"
  },
  {
   "v_id": "person9",
   "attributes": {"result3.id": "person9"},
   "v_type": "person"
  }
 ]}]
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


