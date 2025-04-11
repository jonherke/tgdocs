![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation)[Next](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation)
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
[Resources](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation)
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
  * Tutorials
  * [Pattern Matching Tutorial](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/)
  * [Multiple Hop Patterns and Accumulation](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/3.9/modules/tutorials/pages/pattern-matching/multiple-hop-and-accumulation.adoc)
### Contents
  * [Multiple Hop Pattern Shortest Path Semantics](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_multiple_hop_pattern_shortest_path_semantics)
  * [2-hop pattern](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_2_hop_pattern)
  * [3-hop pattern](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_3_hop_pattern)
  * [Unnamed Intermediate Vertex Set](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_unnamed_intermediate_vertex_set)
  * [Shortest Paths Only for Variable Length Patterns](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_shortest_paths_only_for_variable_length_patterns)
  * [Additional Details about Pattern Matching](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_additional_details_about_pattern_matching)
  * [SELECT Clause](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_select_clause)
  * [FROM Clause](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_from_clause)
  * [WHERE Clause](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_where_clause)
  * [Path Patterns as a Regular Expression Language](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_path_patterns_as_a_regular_expression_language)
  * [Working with Your Pattern Matches](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_working_with_your_pattern_matches)
  * [ACCUM Clause](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_accum_clause)
  * [POST-ACCUM Clause](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_post_accum_clause)
  * [Examples of Multiple Hop Pattern Match](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_examples_of_multiple_hop_pattern_match)
  * [Example 1](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_example_1)
  * [Example 2](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_example_2)
  * [Example 3](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_example_3)
  * [Multi-Block Queries](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_multi_block_queries)
  * [Example 1](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_example_1_2)
  * [Example 2](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_example_2_2)
  * [Example 4](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_example_4)


# Multiple Hop Patterns and Accumulation
### Contents
  * [Multiple Hop Pattern Shortest Path Semantics](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_multiple_hop_pattern_shortest_path_semantics)
  * [2-hop pattern](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_2_hop_pattern)
  * [3-hop pattern](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_3_hop_pattern)
  * [Unnamed Intermediate Vertex Set](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_unnamed_intermediate_vertex_set)
  * [Shortest Paths Only for Variable Length Patterns](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_shortest_paths_only_for_variable_length_patterns)
  * [Additional Details about Pattern Matching](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_additional_details_about_pattern_matching)
  * [SELECT Clause](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_select_clause)
  * [FROM Clause](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_from_clause)
  * [WHERE Clause](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_where_clause)
  * [Path Patterns as a Regular Expression Language](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_path_patterns_as_a_regular_expression_language)
  * [Working with Your Pattern Matches](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_working_with_your_pattern_matches)
  * [ACCUM Clause](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_accum_clause)
  * [POST-ACCUM Clause](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_post_accum_clause)
  * [Examples of Multiple Hop Pattern Match](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_examples_of_multiple_hop_pattern_match)
  * [Example 1](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_example_1)
  * [Example 2](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_example_2)
  * [Example 3](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_example_3)
  * [Multi-Block Queries](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_multi_block_queries)
  * [Example 1](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_example_1_2)
  * [Example 2](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_example_2_2)
  * [Example 4](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_example_4)


## [](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_multiple_hop_pattern_shortest_path_semantics)Multiple Hop Pattern Shortest Path Semantics
Repeating the same hop is useful sometimes, but the real power of pattern matching comes from expressing multi-hop patterns, with specific characteristics for each hop. For example, the well-known product recommendation phrase "People who bought this product also bought this other product" is expressed by the following 2-hop pattern:
```
FROM This_Product:p -(<Bought:b1)- Customer:c -(Bought>:b2)- Product:p2
WHERE p2 != p
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

As you see, a 2-hop pattern is a simple concatenation and merging of two 1-hop patterns where the two patterns share a common endpoint. Below, Y:y is the connecting end point.
### [](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_2_hop_pattern)2-hop pattern
```
FROM X:x - (E1:e1) - Y:y - (E2>:e2) - Z:z
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Similarly, a 3-hop pattern concatenates three 1-hop patterns in sequence, each pair of adjacent hops sharing one end point. Below, Y:y and Z:z are the connecting end points.
### [](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_3_hop_pattern)3-hop pattern
```
FROM X:x - (E2>:e2) - Y:y - (<E3:e3) - Z:z - (E4:e4) - U:u
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

In general, we can connect N 1-hop patterns into an N-hop pattern. The database will search the graph topology to find subgraphs that match this N-hop pattern.
## [](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_unnamed_intermediate_vertex_set)Unnamed Intermediate Vertex Set
A multi-hop pattern has two endpoint vertex sets and one or more intermediate vertex sets. If the query does not need to express any conditions for an intermediate vertex set, then the vertex set can be omitted and the two surrounding edge sets can be joined with a simple `.`. For example, in the 2-hop pattern example above, if we do not need to specify the type of the intermediate vertex Y, nor need to refer to it in any of the query’s other clauses (such as WHERE or ACCUM), then the pattern can be reduced as follows:
```
FROM X:x - (E1.E2>) - Z:z
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Note that when we abbreviate that path in this way, we do not support aliases for the edges or intermediate vertices in the abbreviated section.  
---  
## [](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_shortest_paths_only_for_variable_length_patterns)Shortest Paths Only for Variable Length Patterns
If a pattern has a Kleene star to repeat an edge, GSQL pattern matching selects only the _shortest paths_ which match the pattern. If we did not apply this restriction, computer science theory tells us that the computation time could be unbounded or extreme (NP = non-polynomial, to be technical). If we instead matched ALL paths regardless of length when a Kleene star is used without an upper bound, there could be an infinite number of matches, if there are loops in the graph. Even without loops or with an upper bound, the number of paths to check grows exponentially with the number of hops.
![Figure 3. Shortest Path Illustration](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/_images/screen-shot-2019-05-22-at-12.41.56-am.png)
For the pattern `1 - (_*) - 5` in Figure 3 above, you can see the following:
  * **There are TWO shortest paths: 1-2-3-4-5 and 1-2-6-4-5**
    * These have 4 hops, so we can stop searching after 4 hops. This makes the task tractable.
  * If we search for ALL paths which do not repeat any vertices:
    * There are THREE non-repeated-vertex paths: 1-2-3-4-5, 1-2-6-4-5, and 1-2-9-10-11-12-4-5
    * The actual number of matches is small, but the number of paths is theoretically very large.
  * If we search for ALL paths which do not repeat any edges:
    * There are FOUR non-repeated-edge paths: 1-2-3-4-5, 1-2-6-4-5, 1-2-9-10-11-12-4-5, and 1-2-3-7-8-3-4-5
    * The actual number of matches is small, but number of paths to consider is NP.
  * If we search for ALL paths with no restrictions:
    * There are an infinite number of matches, because we can go around the 3-7-8-3 cycle any number of times.


## [](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_additional_details_about_pattern_matching)Additional Details about Pattern Matching
Each vertex set or edge set in a pattern (except edges with Kleene stars) can have an alias variable associated with it. When the query runs and finds matches, it associates, or binds, each alias to the matching vertices or edges in the graph.
### [](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_select_clause)SELECT Clause
The SELECT clause specifies the output vertex set of a SELECT statement. For a multiple-hop pattern, we can select any vertex alias in the pattern. The example below shows the 4 possible choices for the given pattern:
SELECT Clause Can Select Any Vertex Alias
```
// select starting end point x
SELECT x
FROM X:x-(E2>:e2)-Y:y-(<E3:e3)-Z:z-(E4:e4)-U:u;
// select y
SELECT y
FROM X:x-(E2>:e2)-Y:y-(<E3:e3)-Z:z-(E4:e4)-U:u;
// select z
SELECT z
FROM X:x-(E2>:e2)-Y:y-(<E3:e3)-Z:z-(E4:e4)-U:u;
// select ending end point u
SELECT u
FROM X:x-(E2>:e2)-Y:y-(<E3:e3)-Z:z-(E4:e4)-U:u;
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_from_clause)FROM Clause
For a multiple-hop pattern, if you don’t need to refer to the intermediate vertex points, you can just use `.` to connect the edge patterns, giving a more succinct representation. For example, below we remove y and z, and connect E2>, <E3 and E4 using the period symbol. Note that you cannot have an alias for a multi-hop sequence like E2>.<E3.E4.
Omitting intermediate vertex y and z.
```
// select starting end point x
SELECT x
FROM X:x-(E2>:e2)-Y:y-(<E3:e3)-Z:z-(E4:e4)-U:u;
// if we don't need to access y, z, we can write
SELECT u
FROM X:x-(E2>.<E3.E4)-U:u;
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_where_clause)WHERE Clause
Each predicate (simple true/false condition) can refer to any of the aliases in the path. As with any database query, more complex conditions may not be as performant as simpler queries with simpler, more local predicate conditions. Consider the pattern and query below:
```
FROM X1:x1-(E1:e1)-X2:x2-(E2:e2)-X3:x3-(E3:e3)-X4:x4
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

WHERE Clause Support both Local Predicate and Cross-hop predicates.
```
// (x1, e1, x2) belongs to the 1st-hop
// (x2, e2, x3) belongs to the 2nd-hop
// (x3, e3, x4) belongs to the last-hop
// below x1.age > x2.age is a local predicate
// x2.@cnt != x4.@cnt is a cross-hop predicate
// (x1.salary + x3.salary) < x4.salary is a cross-hop predicate
SELECT x
FROM X1:x1-(E1:e1)-X2:x2-(E2:e2)-X3:x3-(E3:e3)-X4:x4
WHERE x1.age>x2.age AND x2.@cnt!=x4.@cnt AND (x1.salary+x3.salary)<x4.salary
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_path_patterns_as_a_regular_expression_language)Path Patterns as a Regular Expression Language
GSQL’s pattern matching syntax provides the essentials for a regular expression language for paths in graphs. Consider the three basic requirements for a regular expression language:
  1. **The empty set** -→ A path of length zero (no match)
  2. **Concatenation** -→ Combine paths together. You can write an N-hop pattern, and M-hop pattern, and then combine them to have an (N+M)-hop pattern.
  3. **Alternation (either-or)** -→ You can use alternation for both vertex sets and edge sets, e.g. `FROM (Source1 | Source2) -(Edge1> | <Edge 2)- (Target1 | Target2)` Note: This is not the same as `FROM (Source1 -(Edge1>)- Target 1)  |  (Source2 -(<Edge2)- Target 2)` The latter can be achieved by writing two SELECT query blocks and getting the UNION of their results.


## [](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_working_with_your_pattern_matches)Working with Your Pattern Matches
The point of pattern matching is to identity sets of graph entities that match your input pattern. Once you’ve done that, GSQL enables you to do advanced and efficient computation on that data, from simply counting the matches to advanced algorithms and analytics. This section compares accumulation in the current Pattern Matching syntax to earlier versions.
### [](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_accum_clause)ACCUM Clause
Just as in classic GSQL syntax, the ACCUM clause is executed once (in parallel) for each set of vertices and edges in the graph which match the pattern and constraints given in the FROM and WHERE clauses. You can think of FROM-WHERE as producing a virtual table. The columns of this matching table are the alias variables from the FROM clause pattern, and the rows are each possible set of vertex and edge aliases (e.g. a path) which fit the pattern.
A simple 1-hop pattern, which could be syntax v1 or v2, looks like this:
```
FROM Person:A -(IS_LOCATED_IN:B)- City:C
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

produces a match table with 3 columns: A, B, and C. Each row is a tuple (A,B,C) where there is a `has_lived_in` edge B from a `Person` vertex A to a `City` vertex C. We say that the match table provides a _binding_ between the pattern aliases and graph’s vertices and edges. A multi-hop pattern simply has more columns than a 1-hop pattern.
The `ACCUM` clause iterates through **all** matches. If you do not have an alias on every vertex in the pattern, then the number of **distinct** matches may be less than the total number of matches.  
---  
For example, consider the following clauses:
```
FROM Person:A -(KNOWS.KNOWS)- Person.C
WHERE C.email = "Andy@www.com"
ACCUM C.@patternCount += 1
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This finds the friends of the friends of `Andy@www.com`. Suppose Andy knows 3 persons (Larry, Moe, and Curly) who know Wendy. The accumulator `C.@patternCount` will be incremented 3 times for C = Wendy. This is similar to a SQL `SELECT C, COUNT(*) ... GROUP BY C` query. There is no alias for the vertex in the middle of `KNOWS.KNOWS` so the identities of Larry, Moe, and Curly cannot be reported.
### [](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_post_accum_clause)`POST-ACCUM` Clause
At the end of the `ACCUM` clause, all the requested accumulation (`+=`) operators are processed in bulk, and the updated values are now visible. You can now use `POST-ACCUM` clauses to perform a second, different round of computation on the results of your pattern matching.
The `ACCUM` clause executes **for each full path** that matches the pattern in the `FROM` clause. In contrast, the `POST-ACCUM` clause executes **for each vertex** in one vertex set (e.g. one vertex column in the matching table); its statements can access the aggregated accumulator result computed in the `ACCUM` clause. If you want to perform per-vertex updates for more than one vertex alias, you should use a separate `POST-ACCUM` clause for each vertex alias. The multiple `POST-ACCUM` clauses are processed in parallel; it doesn’t matter in what order you write them. (For each binding, the statements within a clause are executed in order.)
For example, below we have two `POST-ACCUM` clauses. The first one iterates through `s`, and for each `s`, we do `s.@cnt2 += s.@cnt1`. The second `POST-ACCUM` iterations through `t`.
```
USE GRAPH ldbc_snb
INTERPRET QUERY () SYNTAX v2 {
 SumAccum<int> @cnt1;
 SumAccum<int> @cnt2;
 R  = SELECT s
     FROM Person:s-(Likes>) -:msg - (Has_Creator>)-Person:t
     WHERE s.first_name == "Viktor" AND s.last_name == "Akhiezer"
        AND t.last_name LIKE "S%" AND year(msg.creation_date) == 2012
     ACCUM s.@cnt1 +=1 //execute this per match of the FROM pattern.
     POST-ACCUM s.@cnt2 += s.@cnt1 //execute once per s.
     POST-ACCUM t.@cnt2 +=1;//execute once per t
 PRINT R [R.first_name, R.last_name, R.@cnt1, R.@cnt2];
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

which produces the result
```
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"R": [{
  "v_id": "28587302323577",
  "attributes": {
   "R.first_name": "Viktor",
   "R.last_name": "Akhiezer",
   "R.@cnt1": 3,
   "R.@cnt2": 3
  },
  "v_type": "Person"
 }]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

However, the following is not allowed, since it involves two aliases (t and s) in one `POST-ACCUM` clause.
```
 POST-ACCUM t.@cnt1 += 1,
      s.@cnt1 += 1
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Also, you may not use more than one alias in a single assignment. The following is not allowed:
```
 POST-ACCUM t.@cnt1 += s.@cnt + 1
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_examples_of_multiple_hop_pattern_match)Examples of Multiple Hop Pattern Match
You can copy any of the shown GSQL scripts to a file with the file extension `.gsql` and invoke it in a Linux shell to see the results.
Linux Bash
```
gsql example.gsql
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_example_1)Example 1
Find the 3rd superclass of the Tag class whose name is "TennisPlayer".
Example 1. Succinct Representation Of Multiple-hop Pattern
```
USE GRAPH ldbc_snb
INTERPRET QUERY () SYNTAX v2 {
 Tag_Class1 =
    SELECT t
    FROM Tag_Class:s-(Is_Subclass_Of>.Is_Subclass_Of>.Is_Subclass_Of>)-Tag_Class:t
    WHERE s.name == "TennisPlayer";
 PRINT Tag_Class1;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Output of Example 1
```
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"Tag_Class1": [{
  "v_id": "239",
  "attributes": {
   "name": "Agent",
   "id": 239,
   "url": "http://dbpedia.org/ontology/Agent"
  },
  "v_type": "Tag_Class"
 }]}]
}
coffeescript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_example_2)Example 2
Find in which continents were the 3 most recent messages in Jan 2011 created.
Example 2. Disjunction in a Succinct Representation of a Multiple-hop Pattern
```
USE GRAPH ldbc_snb
INTERPRET QUERY () SYNTAX v2{
 SumAccum<String> @continent_name;
 acc_msg_continent =
         SELECT s
         FROM (Comment|Post):s-(Is_Located_In>.Is_Part_Of>)-Continent:t
         WHERE year(s.creation_date) == 2011 AND month(s.creation_date) == 1
         ACCUM s.@continent_name = t.name
         ORDER BY s.creation_date DESC
         LIMIT 3;
 PRINT acc_msg_continent;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Output of Example 2
```
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"acc_msg_continent": [
  {
   "v_id": "824634837528",
   "attributes": {
    "browser_used": "Internet Explorer",
    "@continent_name": "Asia",
    "length": 115,
    "image_file": "",
    "location_ip": "87.251.6.121",
    "id": 824634837528,
    "creation_date": "2011-01-31 23:58:03",
    "lang": "tk",
    "content": "About Adolf Hitler, iews. His writings and methods were often adapted to need and circumstance, although there were"
   },
   "v_type": "Post"
  },
  {
   "v_id": "824636727408",
   "attributes": {
    "browser_used": "Firefox",
    "@continent_name": "Europe",
    "length": 3,
    "location_ip": "31.2.225.17",
    "id": 824636727408,
    "creation_date": "2011-01-31 23:57:46",
    "content": "thx"
   },
   "v_type": "Comment"
  },
  {
   "v_id": "824640012997",
   "attributes": {
    "browser_used": "Firefox",
    "@continent_name": "Asia",
    "length": 7,
    "location_ip": "27.112.21.246",
    "id": 824640012997,
    "creation_date": "2011-01-31 23:54:28",
    "content": "no way!"
   },
   "v_type": "Comment"
  }
 ]}]
}
coffeescript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_example_3)Example 3
Find Viktor Akhiezer’s favorite author of 2012 whose last name begins with the letter 'S'. Also find how many LIKES Viktor has given to the author’s post or comment.
Example 3. Multiple-hop Pattern With Accumulator Applied To All Matched Paths
```
USE GRAPH ldbc_snb
INTERPRET QUERY () SYNTAX v2{
 SumAccum<int> @likes_cnt;
 favorite_authors =
      SELECT t
      FROM Person:s-(Likes>) -:msg - (Has_Creator>)-Person:t
      WHERE s.first_name == "Viktor" AND s.last_name == "Akhiezer"
           AND t.last_name LIKE "S%" AND year(msg.creation_date) == 2012
      ACCUM t.@likes_cnt +=1;
 PRINT favorite_authors[favorite_authors.first_name, favorite_authors.last_name, favorite_authors.@likes_cnt];
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Output of Example 3
```
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"favorite_authors": [
  {
   "v_id": "8796093025410",
   "attributes": {
    "favorite_authors.last_name": "Singh",
    "favorite_authors.@likes_cnt": 1,
    "favorite_authors.first_name": "Priyanka"
   },
   "v_type": "Person"
  },
  {
   "v_id": "2199023260091",
   "attributes": {
    "favorite_authors.last_name": "Seppala",
    "favorite_authors.@likes_cnt": 1,
    "favorite_authors.first_name": "Janne"
   },
   "v_type": "Person"
  },
  {
   "v_id": "15393162796846",
   "attributes": {
    "favorite_authors.last_name": "Santos",
    "favorite_authors.@likes_cnt": 1,
    "favorite_authors.first_name": "Mario"
   },
   "v_type": "Person"
  }
 ]}]
}
coffeescript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_multi_block_queries)Multi-Block Queries
We have shown how complex multi-hop patterns, containing even a conjunctive of patterns, can be expressed in a single FROM clause of a single SELECT query. There are times, however, when it is better or necessary to write a query with more than one SELECT block. This could be because of the need to do computation and decision matching in stages, to make the query easier to read, or to optimize performance.
Regardless of the reason, GSQL has always supported writing procedural queries containing multiple SELECT query blocks. Moreover, each SELECT statement outputs a vertex set. This vertex set can be used in the FROM clause of a subsequent SELECT block.
For example, if Set1, Set2, and Set3 were the outputs of three previous SELECT blocks in this query, then each of these FROM clauses can take place later in the query:
  * `FROM   Set1:x1 -(mh1)- :x2 -(mh2)- Set3:x3`
  * `FROM   :x1 -(mh1)- :x2 -(mh2)- Set3:x3`
  * `FROM   Set2:x1 -(mh1)- :x2 -(mh2)- Set2:x3`


### [](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_example_1_2)Example 1
Find Viktor Akhiezer’s liked messages whose authors' last names begin with S. Find these authors' alumni count.
```
USE GRAPH ldbc_snb
// a computed vertex set F is used to constrain the second pattern.
INTERPRET QUERY () SYNTAX v2 {
 SumAccum<int> @@cnt;
 F = SELECT t
    FROM :s -(Likes>:e1)- :msg -(Has_Creator>)- :t
    WHERE s.first_name == "Viktor" AND s.last_name == "Akhiezer" AND t.last_name LIKE "S%";
 Alumni = SELECT p
      FROM Person:p -(Study_At>) -:u - (<Study_At)- F:s
      WHERE s != p
      Per (p)
      POST-ACCUM @@cnt+=1;
 PRINT @@cnt;
}
// results
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"@@cnt": 223}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_example_2_2)Example 2
Find Viktor Akhiezer’s liked posts' authors A, and his liked comments' authors B. Count the universities that members from groups A and B studied at.
```
USE GRAPH ldbc_snb
// A and B are used to constrain the third pattern.
INTERPRET QUERY () SYNTAX v2 {
 SumAccum<int> @@cnt;
 A = SELECT t
    FROM :s -(Likes>:e1)- Post:msg -(Has_Creator>)- :t
    WHERE s.first_name == "Viktor" AND s.last_name == "Akhiezer" ;

 B = SELECT t
    FROM :s -(Likes>:e1)- Comment:msg -(Has_Creator>)- :t
    WHERE s.first_name == "Viktor" AND s.last_name == "Akhiezer" ;
 Univ = SELECT u
     FROM A:p -(Study_At>) -:u - (<Study_At)- B:s
     WHERE s != p
     Per (u)
     POST-ACCUM @@cnt+=1;
 PRINT @@cnt;
}

// results
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"@@cnt": 4}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**Example 3.** Find Viktor Akhiezer’s liked posts' authors A. See how many pairs of persons exist in A such that one person likes a message authored by another person.
```
USE GRAPH ldbc_snb
// a computed vertex set A is used twice in the second pattern.
INTERPRET QUERY () SYNTAX v2 {
 SumAccum<int> @@cnt;
 A = SELECT t
    FROM :s -(Likes>:e1)- Post:msg -(Has_Creator>)- :t
    WHERE s.first_name == "Viktor" AND s.last_name == "Akhiezer" ;
 A = SELECT p
   FROM A:p -(Likes>) -:msg - (Has_Creator>) - A:p2
   WHERE p2 != p
   Per (p, p2)
   ACCUM @@cnt +=1;

 PRINT @@cnt;
}
// results
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"@@cnt": 8341}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.9/tutorials/pattern-matching/multiple-hop-and-accumulation#_example_4)Example 4
Find how many messages are created and liked by the same person whose first name begins with the letter T.
```
USE GRAPH ldbc_snb
// the same alias is used twice in a pattern
INTERPRET QUERY () SYNTAX v2 {
 SumAccum<int> @@cnt;
 A = SELECT msg
    FROM :s -(Likes>:e1)- :msg -(Has_Creator>)- :s
    WHERE s.first_name LIKE "T%"
    PER (msg)
    ACCUM @@cnt +=1;

 PRINT @@cnt;
}
// results
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"@@cnt": 207}]
}

// to further verify, we picked one message from the above query result.
// see if there exists a person who likes her own message.
INTERPRET QUERY () SYNTAX v2 {
  R = SELECT s
    FROM :msg -(Has_Creator>)- :s
    WHERE msg.id == 1374390714042;
  T = SELECT s
     FROM R:s -(Likes>)- :msg
     WHERE msg.id == 1374390714042;
 PRINT R;
 PRINT T;
}
// results
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [
  {"R": [{
   "v_id": "13194139533433",
   "attributes": {
    "birthday": "1985-11-26 00:00:00",
    "browser_used": "Internet Explorer",
    "gender": "female",
    "speaks": [
     "uk",
     "ro",
     "en"
    ],
    "last_name": "Kofler",
    "location_ip": "31.131.28.133",
    "id": 13194139533433,
    "creation_date": "2011-01-29 01:14:27",
    "first_name": "Taras",
    "email": [
     "Taras13194139533433@gmail.com",
     "Taras13194139533433@yahoo.com"
    ]
   },
   "v_type": "Person"
  }]},
  {"T": [{
   "v_id": "13194139533433",
   "attributes": {
    "birthday": "1985-11-26 00:00:00",
    "browser_used": "Internet Explorer",
    "gender": "female",
    "speaks": [
     "uk",
     "ro",
     "en"
    ],
    "last_name": "Kofler",
    "location_ip": "31.131.28.133",
    "id": 13194139533433,
    "creation_date": "2011-01-29 01:14:27",
    "first_name": "Taras",
    "email": [
     "Taras13194139533433@gmail.com",
     "Taras13194139533433@yahoo.com"
    ]
   },
   "v_type": "Person"
  }]}
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


