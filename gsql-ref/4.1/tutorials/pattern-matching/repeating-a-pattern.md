![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/repeating-a-pattern)[Next](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/repeating-a-pattern)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/repeating-a-pattern)
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
[Resources](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/repeating-a-pattern)
[Developer Site](https://dev.tigergraph.com/) [Community Forum](https://community.tigergraph.com/) [Knowledge Base](https://tigergraph.freshdesk.com/support/solutions)
[Download](https://dl.tigergraph.com)
[ TG Savanna](https://savanna.tgcloud.io)
### [GSQL Language Reference](https://docs.tigergraph.com/gsql-ref/4.1/intro/)
  *     * [Overview](https://docs.tigergraph.com/gsql-ref/4.1/intro/)
    * [What sets GSQL apart](https://docs.tigergraph.com/gsql-ref/4.1/intro/set-gsql-apart)
  *     * [GSQL Tutorials](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/)
      * [GSQL V3 Tutorial](https://github.com/tigergraph/ecosys/blob/master/demos/guru_scripts/docker/tutorial/4.x/README.md)
      * [Accumulators Tutorial](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/accumulators-tutorial)
  *     * [System & Language Basics](https://docs.tigergraph.com/gsql-ref/4.1/basics/system-and-language-basics)
  *     * [Attribute Data Types](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/attribute-data-types)
    * [Schema Definition](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/)
      * [Define a Graph Schema](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema)
      * [Modify a Graph Schema](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/modifying-a-graph-schema)
    * [Loading Jobs](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/loading-jobs)
      * [Create a Loading Job](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/creating-a-loading-job)
        * [Functions](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/)
          * [Token Functions](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/)
            * [flatten()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/flatten)
            * [flatten_json_array()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/flatten_json_array)
            * [gsql_concat()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_concat)
            * [gsql_current_time_epoch()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_current_time_epoch)
            * [gsql_day()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_day)
            * [gsql_day_epoch()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_day_epoch)
            * [gsql_find()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_find)
            * [gsql_length()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_length)
            * [gsql_lower()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_lower)
            * [gsql_ltrim()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_ltrim)
            * [gsql_month()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_month)
            * [gsql_month_epoch()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_month_epoch)
            * [gsql_regex_match()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_regex_match)
            * [gsql_regex_replace()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_regex_replace)
            * [gsql_reverse()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_reverse)
            * [gsql_rtrim()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_rtrim)
            * [gsql_substring()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_substring)
            * [gsql_to_bool()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_to_bool)
            * [gsql_to_int()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_to_int)
            * [gsql_to_uint()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_to_uint)
            * [gsql_trim()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_trim)
            * [gsql_ts_to_epoch_seconds()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_ts_to_epoch)
            * [gsql_upper()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_upper)
            * [gsql_uuid_v4()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_uuid_v4)
            * [gsql_year()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_year)
            * [gsql_year_epoch()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/gsql_year_epoch)
            * [split()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token/split)
          * [Token Functions in WHERE Clause](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token_where/)
            * [concat()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token_where/concat)
            * [gsql_is_false()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token_where/gsql_is_false)
            * [gsql_is_not_empty()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token_where/gsql_is_not_empty)
            * [gsql_is_true()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token_where/gsql_is_true)
            * [gsql_token_equal()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token_where/gsql_token_equal)
            * [gsql_token_ignore_case_equal()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token_where/gsql_token_ignore_case_equal)
            * [to_float()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token_where/to_float)
            * [to_int()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token_where/to_int)
            * [token_len()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/token_where/token_len)
          * [Reducer functions](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/reducer/)
            * [add()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/reducer/add)
            * [and()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/reducer/and)
            * [ignore_if_exists()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/reducer/ignore_if_exists)
            * [max()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/reducer/max)
            * [min()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/reducer/min)
            * [or()](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/functions/reducer/or)
        * [Add a User-defined Token Function](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/add-token-function)
      * [Run a Loading Job](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/running-a-loading-job)
      * [Manage Loading Jobs](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/managing-loading-job)
  *     * [Querying](https://docs.tigergraph.com/gsql-ref/4.1/querying/)
      * [Query Language Syntax Versions](https://docs.tigergraph.com/gsql-ref/4.1/querying/syntax-versions)
      * [Queries](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-operations)
      * [Query Optimizer (Preview Feature)](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/)
        * [Enabling Cost-Based Optimization (Preview Feature)](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/enable-cost-optimizer)
        * [Statistics REST APIs (Preview Feature)](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-optimizer/stats-api)
      * [Distributed Query Mode](https://docs.tigergraph.com/gsql-ref/4.1/querying/distributed-query-mode)
      * [Data Types](https://docs.tigergraph.com/gsql-ref/4.1/querying/data-types)
      * [Accumulators](https://docs.tigergraph.com/gsql-ref/4.1/querying/accumulators)
      * [Operators and Expressions](https://docs.tigergraph.com/gsql-ref/4.1/querying/operators-and-expressions)
      * [Functions](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/)
        * [Aggregation Functions](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/aggregation-functions)
        * [Context Functions](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions)
        * [Datetime Functions](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/datetime-functions)
        * [Edge Methods](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/edge-methods)
        * [JSON Object Methods](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/json-object-methods)
        * [JSON Array Methods](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/jsonarray-methods)
        * [List Functions](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/list-functions)
        * [Mathematical Functions](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/mathematical-functions)
        * [Miscellaneous Functions](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/miscellaneous-functions)
        * [Query User-Defined Functions](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/query-user-defined-functions)
        * [String Functions](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions)
        * [Type Conversion Functions](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/type-conversion-functions)
        * [Vector Functions](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vector-functions)
        * [Vertex Functions](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods)
      * [Declaration and Assignment Statements](https://docs.tigergraph.com/gsql-ref/4.1/querying/declaration-and-assignment-statements)
      * [SELECT Statement](https://docs.tigergraph.com/gsql-ref/4.1/querying/select-statement/)
        * [SELECT Statement (Syntax V1)](https://docs.tigergraph.com/gsql-ref/4.1/querying/select-statement/select-statement-v1)
        * [SQL-like SELECT statement](https://docs.tigergraph.com/gsql-ref/4.1/querying/select-statement/sql-like-select-statement)
      * [Control Flow Statements](https://docs.tigergraph.com/gsql-ref/4.1/querying/control-flow-statements)
      * [Data Modification Statements](https://docs.tigergraph.com/gsql-ref/4.1/querying/data-modification-statements)
      * [Output Statements and FILE Objects](https://docs.tigergraph.com/gsql-ref/4.1/querying/output-statements-and-file-objects)
      * [Exception Statements](https://docs.tigergraph.com/gsql-ref/4.1/querying/exception-statements)
      * [Comments](https://docs.tigergraph.com/gsql-ref/4.1/querying/comments)
      * [Write Query Output to Cloud](https://docs.tigergraph.com/gsql-ref/4.1/querying/write-query-data-to-cloud)
  *     * openCypher
      * [OpenCypher Tutorial (on GitHub)](https://github.com/tigergraph/ecosys/blob/master/demos/guru_scripts/docker/tutorial/4.x/Cypher.md)
      * [openCypher in GSQL](https://docs.tigergraph.com/gsql-ref/4.1/openCypher-in-gsql/openCypher-in-gsql)
      * [Writing and Running openCypher in GSQL Shell](https://docs.tigergraph.com/gsql-ref/4.1/openCypher-in-gsql/openCypher-in-gsql-web-shell)
      * [openCypher Pattern Support in GSQL](https://docs.tigergraph.com/gsql-ref/4.1/openCypher-in-gsql/openCypher-gsql-from-clause-extension)
  *     * Appendix
      * [GSQL Style Guide](https://docs.tigergraph.com/gsql-ref/4.1/appendix/gsql-style-guide)
      * [DDL Keywords & Reserved Words](https://docs.tigergraph.com/gsql-ref/4.1/appendix/keywords-and-reserved-words)
      * [Query Language Keywords & Reserved Words](https://docs.tigergraph.com/gsql-ref/4.1/appendix/query-language-reserved-words)
      * [Interpreted GSQL Limitations](https://docs.tigergraph.com/gsql-ref/4.1/appendix/interpreted-gsql-limitations)
      * [GSQL Start-to-End Process and Data Flow](https://docs.tigergraph.com/gsql-ref/4.1/appendix/gsql-start-to-end-process)
      * [Example Graphs](https://docs.tigergraph.com/gsql-ref/4.1/appendix/example-graphs)
      * [Common Errors and Problems](https://docs.tigergraph.com/gsql-ref/4.1/appendix/common-errors-and-problems)
      * [GSQL Cheat Sheets](https://docs.tigergraph.com/gsql-ref/4.1/appendix/cheat-sheets)
      * [Documentation Notations](https://docs.tigergraph.com/gsql-ref/4.1/appendix/notations)
    * [Legacy Version Documentation](https://docs.tigergraph.com/gsql-ref/4.1/appendix/legacy-tg-versions)


GSQL Language Reference 4.1
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
  * [GSQL Language Reference 4.1](https://docs.tigergraph.com/gsql-ref/4.1/intro/)
  * [Repeating a 1-Hop Pattern](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/repeating-a-pattern)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/4.1/modules/tutorials/pages/pattern-matching/repeating-a-pattern.adoc)
### Contents
  * [Remarks](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/repeating-a-pattern#_remarks)
  * [No alias allowed for edge with Kleene star](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/repeating-a-pattern#_no_alias_allowed_for_edge_with_kleene_star)
  * [Shortest path semantics](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/repeating-a-pattern#_shortest_path_semantics)
  * [Examples of Variable Hop Queries](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/repeating-a-pattern#_examples_of_variable_hop_queries)
  * [Example 1](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/repeating-a-pattern#_example_1)
  * [Example 2](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/repeating-a-pattern#_example_2)
  * [Example 3](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/repeating-a-pattern#_example_3)
  * [Example 4](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/repeating-a-pattern#_example_4)
  * [Example 5](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/repeating-a-pattern#_example_5)
  * [Example 6](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/repeating-a-pattern#_example_6)


# Repeating a 1-Hop Pattern
### Contents
  * [Remarks](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/repeating-a-pattern#_remarks)
  * [No alias allowed for edge with Kleene star](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/repeating-a-pattern#_no_alias_allowed_for_edge_with_kleene_star)
  * [Shortest path semantics](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/repeating-a-pattern#_shortest_path_semantics)
  * [Examples of Variable Hop Queries](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/repeating-a-pattern#_examples_of_variable_hop_queries)
  * [Example 1](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/repeating-a-pattern#_example_1)
  * [Example 2](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/repeating-a-pattern#_example_2)
  * [Example 3](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/repeating-a-pattern#_example_3)
  * [Example 4](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/repeating-a-pattern#_example_4)
  * [Example 5](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/repeating-a-pattern#_example_5)
  * [Example 6](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/repeating-a-pattern#_example_6)


A common pattern is the two-step "Friend of a Friend".
This is related to the question "Do I know any famous people?" Even if you aren’t friends with any famous people, at least one of _your friends'_ friends might be famous. That’s a one-hop pattern, repeated twice.
In terms of data throughput on a network, you can also ask "If everyone who receives a message passes it along to everyone else they know, how many entities will receive it?"
GSQL pattern matching makes it easy to express such variable-length patterns which repeat a single hop. Everything else stays the same as introduced in the previous section, except we append an asterisk (or _Kleene star_) and an optional _min..max_ range to an edge pattern.
  * (E*) means edge type E repeats any number of times (including zero)
  * (E*1..3) means edge type E occurs one to three times.


Below are more illustrative examples:
  * **1-hop star pattern — repetition of an edge pattern 0 or more times**
    1. `FROM X:x -(E*)- Y:y`
    2. `FROM X:x -(F>*)- Y:y`
    3. `FROM X:x -(<G*)- Y:y`
    4. `FROM X:x -(_*)- Y:y`
       * Any undirected edge can be chosen at each repetition.
    5. `FROM X:x -(_>*)- Y:y`
       * Any right-directed edge can be chosen at each repetition.
    6. `FROM X:x -(<_*)- Y:y`
       * Any left-directed edge can be chosen at each repetition.
    7. `FROM X:x -((E|F>|<G)*)- Y:y`
       * Either E, F> or <G can be chosen at each repetition.
  * **1-hop star pattern with bounds**
    1. `FROM X:x -(E*2..)- Y:y`
       * Lower bounds only. There is a chain of at least 2 E edges.
    2. `FROM X:x -(F>*..3)- Y:y`
       * Upper bounds only. There is a chain of between 0 and 3 F edges.
    3. `FROM X:x -(<G*3..5)- Y:y`
       * Both Lower and Upper bounds. There is a chain of 3 to 5 G edges.
    4. `FROM X:x -((E|F>|<G)*3)- Y:y`
       * Exact bound. There is a chain of exactly 3 edges, where each edge is either E, F>, or <G.


## [](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/repeating-a-pattern#_remarks)Remarks
### [](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/repeating-a-pattern#_no_alias_allowed_for_edge_with_kleene_star)No alias allowed for edge with Kleene star
An edge alias may not be used when a Kleene star is used. The reason is that when there are a variable number of edges, we cannot associate or bind the alias to a specific edge in the pattern.
### [](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/repeating-a-pattern#_shortest_path_semantics)Shortest path semantics
When an edge is repeated with a Kleene star, only the shortest matching occurrences are selected. See the example below:
![Figure 2 Shortest Path Illustration.](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/_images/screen-shot-2019-05-19-at-2.33.35-am.png)
In Figure 2, or Pattern `1 -(E>*)- 4`, any of the following paths reach 4 from 1.
  * 1→2→3→4
  * 1→2→3→5→6→2→3→4
  * any path that goes through the cycle 2→3→5→6→2 two or more times and jumps out at 3.


The first path is shorter than the rest; it is considered the only match.
## [](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/repeating-a-pattern#_examples_of_variable_hop_queries)Examples of Variable Hop Queries
In this tutorial, we will use the Interpreted Mode for GSQL so that we can skip the INSTALL step and run a query as soon as we create it. These one-step interpreted queries are unnamed (anonymous) and parameterless.
You can copy any of the shown GSQL scripts to a file with the file extension `.gsql` and invoke it in a Linux shell to see the results.
Linux Bash
```
gsql example.gsql
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/repeating-a-pattern#_example_1)Example 1
Find the direct or indirect superclass (including the self class) of the tag_class whose name is "TennisPlayer".
Example 1. Directed Edge Pattern Unconstrained Repetition
```
USE GRAPH ldbc_snb
INTERPRET QUERY () SYNTAX v2 {
 tag_class1 = SELECT t
        FROM Tag_Class:s - (Is_Subclass_Of>*) - Tag_Class:t
        WHERE s.name == "TennisPlayer";
  PRINT tag_class1;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Note below that the starting vertex s, whose name is TennisPlayer, is also a match, using a path with zero hops.
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
 "results": [{"tag_class1": [
  {
   "v_id": "211",
   "attributes": {
    "name": "Person",
    "id": 211,
    "url": "http://dbpedia.org/ontology/Person"
   },
   "v_type": "Tag_Class"
  },
  {
   "v_id": "239",
   "attributes": {
    "name": "Agent",
    "id": 239,
    "url": "http://dbpedia.org/ontology/Agent"
   },
   "v_type": "Tag_Class"
  },
  {
   "v_id": "0",
   "attributes": {
    "name": "Thing",
    "id": 0,
    "url": "http://www.w3.org/2002/07/owl#Thing"
   },
   "v_type": "Tag_Class"
  },
  {
   "v_id": "149",
   "attributes": {
    "name": "Athlete",
    "id": 149,
    "url": "http://dbpedia.org/ontology/Athlete"
   },
   "v_type": "Tag_Class"
  },
  {
   "v_id": "59",
   "attributes": {
    "name": "TennisPlayer",
    "id": 59,
    "url": "http://dbpedia.org/ontology/TennisPlayer"
   },
   "v_type": "Tag_Class"
  }
 ]}]
}
coffeescript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/repeating-a-pattern#_example_2)Example 2
Find the immediate superclass of the tag_class whose name is "tennis_player". (This is equivalent to a 1-hop non-repeating pattern.)
Example 2. Exactly 1 Repetition of A Directed Edge
```
USE GRAPH ldbc_snb
INTERPRET QUERY () SYNTAX v2 {
  tag_class1 = SELECT t
    FROM Tag_Class:s - (Is_Subclass_Of>*1) - Tag_Class:t
    WHERE s.name == "TennisPlayer";
  PRINT tag_class1;
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
 "results": [{"tag_class1": [{
  "v_id": "149",
  "attributes": {
   "name": "Athlete",
   "id": 149,
   "url": "http://dbpedia.org/ontology/Athlete"
  },
  "v_type": "Tag_Class"
 }]}]
}
coffeescript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/repeating-a-pattern#_example_3)Example 3
Find the 1 to 2 hops direct and indirect superclasses of the tag_class whose name is "TennisPlayer".
Example 3. 1 to 2 Repetition Of A Directed Edge.
```
USE GRAPH ldbc_snb
INTERPRET QUERY () SYNTAX v2 {
 tag_class1 = SELECT t
        FROM Tag_Class:s - (Is_Subclass_Of>*1..2) - Tag_Class:t
        WHERE s.name == "TennisPlayer";
  PRINT tag_class1;
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
 "results": [{"tag_class1": [
  {
   "v_id": "211",
   "attributes": {
    "name": "Person",
    "id": 211,
    "url": "http://dbpedia.org/ontology/Person"
   },
   "v_type": "Tag_Class"
  },
  {
   "v_id": "149",
   "attributes": {
    "name": "Athlete",
    "id": 149,
    "url": "http://dbpedia.org/ontology/Athlete"
   },
   "v_type": "Tag_Class"
  }
 ]}]
}
coffeescript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/repeating-a-pattern#_example_4)Example 4
Find the superclasses within 2 hops of the tag_class whose name is "TennisPlayer".
Example 4. Up-to 2 Repetition Of A Directed Edge.
```
USE GRAPH ldbc_snb
INTERPRET QUERY () SYNTAX v2 {
 tag_class1 = SELECT t
        FROM Tag_Class:s - (Is_Subclass_Of>*..2) - Tag_Class:t
        WHERE s.name == "TennisPlayer";
  PRINT tag_class1;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Output of Example 4
```
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"tag_class1": [
  {
   "v_id": "211",
   "attributes": {
    "name": "Person",
    "id": 211,
    "url": "http://dbpedia.org/ontology/Person"
   },
   "v_type": "Tag_Class"
  },
  {
   "v_id": "149",
   "attributes": {
    "name": "Athlete",
    "id": 149,
    "url": "http://dbpedia.org/ontology/Athlete"
   },
   "v_type": "Tag_Class"
  },
  {
   "v_id": "59",
   "attributes": {
    "name": "TennisPlayer",
    "id": 59,
    "url": "http://dbpedia.org/ontology/TennisPlayer"
   },
   "v_type": "Tag_Class"
  }
 ]}]
}
coffeescript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/repeating-a-pattern#_example_5)Example 5
Find the superclasses at least one hop from the tag_class whose name is "TennisPlayer".
Example 5. At Least 1 Repetition Of A Directed Edge.
```
USE GRAPH ldbc_snb
INTERPRET QUERY () SYNTAX v2 {
 tag_class1 = SELECT t
        FROM Tag_Class:s - (Is_Subclass_Of>*1..) - Tag_Class:t
        WHERE s.name == "TennisPlayer";
  PRINT tag_class1;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Output of Example 5
```
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"tag_class1": [
  {
   "v_id": "211",
   "attributes": {
    "name": "Person",
    "id": 211,
    "url": "http://dbpedia.org/ontology/Person"
   },
   "v_type": "Tag_Class"
  },
  {
   "v_id": "239",
   "attributes": {
    "name": "Agent",
    "id": 239,
    "url": "http://dbpedia.org/ontology/Agent"
   },
   "v_type": "Tag_Class"
  },
  {
   "v_id": "0",
   "attributes": {
    "name": "Thing",
    "id": 0,
    "url": "http://www.w3.org/2002/07/owl#Thing"
   },
   "v_type": "Tag_Class"
  },
  {
   "v_id": "149",
   "attributes": {
    "name": "Athlete",
    "id": 149,
    "url": "http://dbpedia.org/ontology/Athlete"
   },
   "v_type": "Tag_Class"
  }
 ]}]
}
coffeescript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/repeating-a-pattern#_example_6)Example 6
Find the 3 most recent comments that are liked or created by Viktor Akhiezer and the total number of comments liked or created by the same person.
Example 6. Disjunctive 1-Repetition Directed Edge.
```
USE GRAPH ldbc_snb
INTERPRET QUERY () SYNTAX v2{
 SumAccum<INT> @@comment_cnt = 0;
 // find top 3 latest comments that is liked or created by Viktor Akhiezer
 // and the total number of comments related to Viktor Akhiezer
 top_3_comments = SELECT p
         FROM Person:s - ((<Has_Creator|Likes>)*1) - Comment:p
         WHERE s.first_name == "Viktor" AND s.last_name == "Akhiezer"
         ACCUM @@comment_cnt += 1
         ORDER BY p.creation_date DESC
         LIMIT 3;
 PRINT top_3_comments;
 // total number of comments related to Viktor Akhiezer
 PRINT @@comment_cnt;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Output of Example 6
```
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [
  {"top_3_comments": [
   {
    "v_id": "2061584720640",
    "attributes": {
     "browser_used": "Chrome",
     "length": 4,
     "location_ip": "194.62.64.117",
     "id": 2061584720640,
     "creation_date": "2012-09-06 06:46:31",
     "content": "fine"
    },
    "v_type": "Comment"
   },
   {
    "v_id": "2061590804929",
    "attributes": {
     "browser_used": "Chrome",
     "length": 83,
     "location_ip": "194.62.64.117",
     "id": 2061590804929,
     "creation_date": "2012-09-04 16:16:56",
     "content": "About Muttiah Muralitharan, mit by nine degrees, five degrees being thAbout Steve M"
    },
    "v_type": "Comment"
   },
   {
    "v_id": "2061586872389",
    "attributes": {
     "browser_used": "Chrome",
     "length": 90,
     "location_ip": "31.216.177.175",
     "id": 2061586872389,
     "creation_date": "2012-08-28 14:54:46",
     "content": "About Hector Berlioz, his compositions Symphonie fantastique and GraAbout Who Knew, the gu"
    },
    "v_type": "Comment"
   }
  ]},
  {"@@comment_cnt": 152}
 ]
}
coffeescript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

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


