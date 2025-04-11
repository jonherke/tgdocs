![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns)[Next](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns)
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
[Resources](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns)
[Developer Site](https://dev.tigergraph.com/) [Community Forum](https://community.tigergraph.com/) [Knowledge Base](https://tigergraph.freshdesk.com/support/solutions)
[Download](https://dl.tigergraph.com)
[ TG Savanna](https://savanna.tgcloud.io)
### [GSQL Language Reference](https://docs.tigergraph.com/gsql-ref/3.6/intro/intro)
  *     * [Overview](https://docs.tigergraph.com/gsql-ref/3.6/intro/intro)
  *     * Tutorials
      * [GSQL 101](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/gsql-101/)
        * [Define a Schema](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/gsql-101/define-a-schema)
        * [Load Data](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/gsql-101/load-data-gsql-101)
        * [Run Built-in Queries](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/gsql-101/built-in-select-queries)
        * [Parameterized Queries](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/gsql-101/parameterized-gsql-query)
        * [Review](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/gsql-101/review)
      * [Pattern Matching Tutorial](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/)
        * [Prepare your Environment](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/prepare-environment)
        * [One-hop patterns](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns)
        * [Repeating a 1-Hop Pattern](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/repeating-a-pattern)
        * [Multiple Hop Patterns and Accumulation](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/multiple-hop-and-accumulation)
        * [Example - A Recommender](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/example)
        * [Advanced Features](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/adv/)
          * [Per Clause (Beta)](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/adv/per-clause)
          * [Conjunctive Pattern Matching (Beta)](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/adv/conjunctive-pattern-matching)
          * [Data Modification](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/adv/dml)
        * [Summary](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/summary)
      * [Accumulators Tutorial](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/accumulators-tutorial)
  *     * Database definition & Loading
      * [System & Language Basics](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/system-and-language-basics)
      * [Defining a Graph Schema](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/defining-a-graph-schema)
      * [Modifying a Graph Schema](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/modifying-a-graph-schema)
      * [Creating a Loading Job](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/creating-a-loading-job)
        * [Functions](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/)
          * [Token Functions for Attribute Expressions](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/)
            * [flatten()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/flatten)
            * [flatten_json_array()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/flatten_json_array)
            * [gsql_concat()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_concat)
            * [gsql_current_time_epoch()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_current_time_epoch)
            * [gsql_day()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_day)
            * [gsql_day_epoch()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_day_epoch)
            * [gsql_find()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_find)
            * [gsql_length()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_length)
            * [gsql_lower()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_lower)
            * [gsql_ltrim()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_ltrim)
            * [gsql_month()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_month)
            * [gsql_month_epoch()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_month_epoch)
            * [gsql_regex_match()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_regex_match)
            * [gsql_regex_replace()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_regex_replace)
            * [gsql_reverse()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_reverse)
            * [gsql_rtrim()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_rtrim)
            * [gsql_substring()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_substring)
            * [gsql_to_bool()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_to_bool)
            * [gsql_to_int()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_to_int)
            * [gsql_to_uint()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_to_uint)
            * [gsql_trim()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_trim)
            * [gsql_ts_to_epoch_seconds()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_ts_to_epoch)
            * [gsql_upper()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_upper)
            * [gsql_uuid_v4()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_uuid_v4)
            * [gsql_year()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_year)
            * [gsql_year_epoch()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/gsql_year_epoch)
            * [split()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token/split)
          * [Token Functions in WHERE Clause](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token_where/)
            * [concat()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token_where/concat)
            * [gsql_is_false()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token_where/gsql_is_false)
            * [gsql_is_not_empty()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token_where/gsql_is_not_empty)
            * [gsql_is_true()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token_where/gsql_is_true)
            * [gsql_token_equal()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token_where/gsql_token_equal)
            * [gsql_token_ignore_case_equal()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token_where/gsql_token_ignore_case_equal)
            * [to_float()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token_where/to_float)
            * [to_int()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token_where/to_int)
            * [token_len()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/token_where/token_len)
          * [Reducer functions](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/reducer/)
            * [add()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/reducer/add)
            * [and()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/reducer/and)
            * [ignore_if_exists()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/reducer/ignore_if_exists)
            * [max()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/reducer/max)
            * [min()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/reducer/min)
            * [or()](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/functions/reducer/or)
        * [Add a User-defined Token Function](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/add-token-function)
      * [Running a Loading Job](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/running-a-loading-job)
  *     * Querying
      * [Introduction](https://docs.tigergraph.com/gsql-ref/3.6/querying/)
      * [Query Language Syntax Versions](https://docs.tigergraph.com/gsql-ref/3.6/querying/syntax-versions)
      * [Queries](https://docs.tigergraph.com/gsql-ref/3.6/querying/query-operations)
      * [Distributed Query Mode](https://docs.tigergraph.com/gsql-ref/3.6/querying/distributed-query-mode)
      * [Data Types](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types)
      * [Accumulators](https://docs.tigergraph.com/gsql-ref/3.6/querying/accumulators)
      * [Operators and Expressions](https://docs.tigergraph.com/gsql-ref/3.6/querying/operators-and-expressions)
      * [Functions](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/)
        * [Aggregation Functions](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/aggregation-functions)
        * [Datetime Functions](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/datetime-functions)
        * [Edge Methods](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/edge-methods)
        * [JSON Object Methods](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/json-object-methods)
        * [JSON Array Methods](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/jsonarray-methods)
        * [Mathematical Functions](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/mathematical-functions)
        * [Miscellaneous Functions](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/miscellaneous-functions)
        * [Query User-Defined Functions](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/query-user-defined-functions)
        * [String Functions](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/string-functions)
        * [Type Conversion Functions](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/type-conversion-functions)
        * [Vertex Functions](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/vertex-methods)
      * [Declaration and Assignment Statements](https://docs.tigergraph.com/gsql-ref/3.6/querying/declaration-and-assignment-statements)
      * [SELECT Statement](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/)
        * [SELECT Statement (Syntax V1)](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/select-statement-v1)
        * [SQL-like SELECT statement](https://docs.tigergraph.com/gsql-ref/3.6/querying/select-statement/sql-like-select-statement)
      * [Control Flow Statements](https://docs.tigergraph.com/gsql-ref/3.6/querying/control-flow-statements)
      * [Data Modification Statements](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-modification-statements)
      * [Output Statements and FILE Objects](https://docs.tigergraph.com/gsql-ref/3.6/querying/output-statements-and-file-objects)
      * [Exception Statements](https://docs.tigergraph.com/gsql-ref/3.6/querying/exception-statements)
      * [Comments](https://docs.tigergraph.com/gsql-ref/3.6/querying/comments)
  *     * Appendix
      * [GSQL Style Guide](https://docs.tigergraph.com/gsql-ref/3.6/appendix/gsql-style-guide)
      * [DDL Keywords & Reserved Words](https://docs.tigergraph.com/gsql-ref/3.6/appendix/keywords-and-reserved-words)
      * [Query Language Keywords & Reserved Words](https://docs.tigergraph.com/gsql-ref/3.6/appendix/query-language-reserved-words)
      * [Formal Grammar for Query Language](https://docs.tigergraph.com/gsql-ref/3.6/appendix/complete-formal-syntax)
      * [Interpreted GSQL Limitations](https://docs.tigergraph.com/gsql-ref/3.6/appendix/interpreted-gsql-limitations)
      * [GSQL Start-to-End Process and Data Flow](https://docs.tigergraph.com/gsql-ref/3.6/appendix/gsql-start-to-end-process)
      * [Example Graphs](https://docs.tigergraph.com/gsql-ref/3.6/appendix/example-graphs)
      * [Common Errors and Problems](https://docs.tigergraph.com/gsql-ref/3.6/appendix/common-errors-and-problems)


GSQL Language Reference 3.6
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
  * [GSQL Language Reference 3.6](https://docs.tigergraph.com/gsql-ref/3.6/intro/intro)
  * Tutorials
  * [Pattern Matching Tutorial](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/)
  * [One-hop patterns](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/3.6/modules/tutorials/pages/pattern-matching/one-hop-patterns.adoc)
### Contents
  * [Introduction](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns#_introduction)
  * [1-Hop pattern](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns#_1_hop_pattern)
  * [Alternation separator](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns#_alternation_separator)
  * [Edge type wildcards](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns#_edge_type_wildcards)
  * [Vertex type wildcards](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns#_vertex_type_wildcards)
  * [Running anonymous queries without installing](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns#_running_anonymous_queries_without_installing)
  * [Examples of 1-Hop Fixed Length Query](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns#_examples_of_1_hop_fixed_length_query)
  * [Example 1](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns#_example_1)
  * [Example 2](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns#_example_2)
  * [Example 3](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns#_example_3)
  * [Example 4](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns#_example_4)
  * [Example 5](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns#_example_5)


# One-hop patterns
### Contents
  * [Introduction](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns#_introduction)
  * [1-Hop pattern](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns#_1_hop_pattern)
  * [Alternation separator](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns#_alternation_separator)
  * [Edge type wildcards](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns#_edge_type_wildcards)
  * [Vertex type wildcards](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns#_vertex_type_wildcards)
  * [Running anonymous queries without installing](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns#_running_anonymous_queries_without_installing)
  * [Examples of 1-Hop Fixed Length Query](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns#_examples_of_1_hop_fixed_length_query)
  * [Example 1](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns#_example_1)
  * [Example 2](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns#_example_2)
  * [Example 3](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns#_example_3)
  * [Example 4](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns#_example_4)
  * [Example 5](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns#_example_5)


## [](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns#_introduction)Introduction
Pattern matching by nature is declarative. It enables users to focus on specifying what they want from a query without worrying about the underlying query processing.
The pattern specifies sets of vertex types and how they are connected by edge types.
A pattern usually appears in the `FROM` clause, the most fundamental part of the query structure. A pattern can be refined further with conditions in the `WHERE` clause.
In this tutorial, we’ll start with simple one-hop path patterns, and then extend it multi-hop patterns and finally multiple-path patterns.
Pattern matching queries support nested queries.  
---  
## [](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns#_1_hop_pattern)1-Hop pattern
The easiest way to understand patterns is to start with a simple 1-Hop pattern. Even a single hop has several options. After we’ve tackled single hops, then we’ll see how to add repetition to make variable length patterns and how to connect single hops to form bigger patterns.
In GSQL syntax V2, we use the punctuation `-( )-` to denote a 1-hop pattern.
The edge type(s) is enclosed in the parentheses `()` and the hyphens `-` symbolize connection. The directionality of the connection is explicitly stated for _each_ edge type. Arrowheads are used to indicate direction: `>` or `<`.
  * For an undirected edge E, leave as is: `E`
  * For a directed edge E from left to right, use a right-pointing arrowhead: `E>`
  * For a directed edge E from right to left, use a left-pointing arrowhead: `<E`


In this notation, `E` is a placeholder for any edge in a graph. "Left" and "right" refer to the order of the actual written pattern itself.
```
Vertex_A -(Edge)- Vertex_B
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Here, Edge is to the right of Vertex_A and to the left of Vertex_B.
### [](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns#_alternation_separator)Alternation separator
In the `LDBC SNB` schema, there are two directed relationships between Person and Message.
  1. Person `LIKES` Message
  2. Message `HAS_CREATOR` Person


```
Person:p -(LIKES>:e)- Message:m
Person:p -(<HAS_CREATOR:e)- Message:m
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Despite the fact that these relationships are in opposite directions, we can use the alternation separator (the pipe) `|` to include both of them in the same pattern:
```
Person:p -((LIKES>|<HAS_CREATOR):e)- Message:m
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns#_edge_type_wildcards)Edge type wildcards
Use the underscore `_` or the keyword `ANY` to denote any undirected edge type. Empty parentheses `()` means any edge, directed or undirected.
If a type or wildcard is not given, it includes both directed and undirected edges in the results.
Example including directed and undirected edges
```
Person:p -(:e)- Message:m
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns#_vertex_type_wildcards)Vertex type wildcards
Use `_`, `ANY` or omit the vertex type to indicate any vertex type. If you omit the vertex type, you must provide a vertex alias.
The source or the target vertex set may be:
  * a vertex type `SELECT t FROM Person:s -(IS_LOCATED_IN>:e)- City:t`
  * an alternation of vertex types `SELECT t FROM (Post|Comment):s -(IS_LOCATED_IN>:e)- Country:t`
  * omitted, with only an alias, meaning any vertex type `SELECT s FROM :s -(IS_LOCATED_IN>:e)- Country:t`
  * omitted, without an alias, meaning any vertex type `SELECT t FROM -(IS_LOCATED_IN>:e)- Country:t`


Performance may be better when types are explicitly provided.  
---  
#### [](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns#_examples_of_1_hop_patterns)Examples of 1-Hop patterns
  1. `FROM X:x -(E1:e1)- Y:y`
     * E1 is an undirected edge, x and y bind to the end points of E1, and e1 is the alias of E1.
  2. `FROM X:x -(E2>:e2)- Y:y`
     * Right directed edge x binds to the source of E2; y binds to the target of E2.
  3. `FROM X:x -(<E3:e3)- Y:y`
     * Left directed edge; y binds to the source of E3; x binds to the target of E3.
  4. `FROM X:x -(:e)- Y:y`
     * Any directed or undirected edge between a member of X and a member of Y.
  5. `FROM X:x -(_:e)- Y:y`
     * Any undirected edge between a member of X and a member of Y.
  6. `FROM X:x -(_>:e)- Y:y`
     * Any right directed edge with source in X and target in Y.
  7. `FROM X:x -(<_:e)- Y:y`
     * Any left directed edge with source in Y and target in X.
  8. `FROM X:x -((<_|_):e)- Y:y`
     * Any left directed or any undirected; `|` means OR, and parentheses enclose the group of edge descriptors; e is the alias for the edge pattern `(<_|_)`.
  9. `FROM X:x -((E1|E2>|<E3):e)- Y:y`
     * Any one of the three edge patterns.
  10. `FROM X:x -()- Y:y`
     * Any directed or undirected edge between a member of X and a member of Y.
     * Same as `(<_|_>|_)` or `(:e)`.


## [](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns#_running_anonymous_queries_without_installing)Running anonymous queries without installing
In this tutorial, we will use Interpreted Mode for GSQL. Interpreted mode lets us skip the `INSTALL` step, and even run a query as soon as we create it, to offer a more interactive experience. These one-step interpreted queries are unnamed (anonymous) and parameterless.
To run an interpreted query, replace the keyword `CREATE` with `INTERPRET`.
```
INTERPRET QUERY () FOR GRAPH graph_name SYNTAX v2 { <query body> }
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Interpreted queries may run slower than installed queries, so we recommend increasing the query timeout threshold: GSQL: Set Query Timeout to 1 Minute ```
// 1 unit is 1 millisecond
SET query_timeout = 60000coffeescript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!
```
  
---  
## [](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns#_examples_of_1_hop_fixed_length_query)Examples of 1-Hop Fixed Length Query
You can copy any of the shown GSQL scripts to a file with the file extension `.gsql` and invoke it in a Linux shell to see the results.
Linux Bash
```
gsql example.gsql
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns#_example_1)Example 1
Find persons who know the person named "Viktor Akhiezer" and return the top 3 oldest such persons.
Example 1. Left-Directed Edge Pattern
```
USE GRAPH ldbc_snb
INTERPRET QUERY () SYNTAX v2 {
  // 1-hop pattern.
  friends = SELECT p
       FROM Person:s -(Knows:e)- Person:p **(1)**
       WHERE s.first_name == "Viktor" AND s.last_name == "Akhiezer"
       ORDER BY p.birthday ASC
       LIMIT 3;
  PRINT friends[friends.first_name, friends.last_name, friends.birthday];
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | In the `FROM` clause, we directly use vertex type Person as the starting vertex set. This syntax enhancement is available in syntax V2 only.  
---|---  
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
 "results": [{"friends": [
  {
   "v_id": "4398046517846",
   "attributes": {
    "friends.first_name": "Abdul-Malik",
    "friends.birthday": "1980-04-24 00:00:00",
    "friends.last_name": "Glosca"
   },
   "v_type": "Person"
  },
  {
   "v_id": "10995116279461",
   "attributes": {
    "friends.first_name": "Gregorio",
    "friends.birthday": "1980-05-13 00:00:00",
    "friends.last_name": "Cajes"
   },
   "v_type": "Person"
  },
  {
   "v_id": "6597069776731",
   "attributes": {
    "friends.first_name": "Sven",
    "friends.birthday": "1981-02-25 00:00:00",
    "friends.last_name": "Carlsson"
   },
   "v_type": "Person"
  }
 ]}]
}
coffeescript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns#_example_2)Example 2
Find the total number of comments and total number of posts liked by Viktor. A Person can reach Comments or Posts via a directed edge LIKES.
Example 2. Right-directed Edge Pattern
```
USE GRAPH ldbc_snb
INTERPRET QUERY () SYNTAX v2 {
  SumAccum<int> @comment_cnt= 0;
  SumAccum<int> @post_cnt= 0;
  // 1-hop pattern.
  Result = SELECT s
      FROM Person:s -(Likes>)- :tgt
      WHERE s.first_name == "Viktor" AND s.last_name == "Akhiezer"
      ACCUM CASE WHEN tgt.type == "Comment" THEN
              s.@comment_cnt += 1
            WHEN tgt.type == "Post" THEN
              s.@post_cnt += 1
          END;
  PRINT Result[Result.@comment_cnt, Result.@post_cnt];
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Output of Example 2.
```
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"Result": [{
  "v_id": "28587302323577",
  "attributes": {
   "Result.@post_cnt": 51,
   "Result.@comment_cnt": 108
  },
  "v_type": "Person"
 }]}]
}
coffeescript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns#_example_3)Example 3
Solve the same problem as in Example 2, but use a left-directed edge pattern.
Note below (line 8) that the source vertex set are now Comment and Post, and the target is Person.
Example 3. Left-directed Edge Pattern
```
USE GRAPH ldbc_snb
INTERPRET QUERY () SYNTAX v2{
  SumAccum<int> @comment_cnt= 0;
  SumAccum<int> @post_cnt= 0;
  Result = SELECT tgt
      FROM Person:tgt -(<Likes_Reverse)- (Comment|Post):src
      WHERE tgt.first_name == "Viktor" AND tgt.last_name == "Akhiezer"
      ACCUM CASE WHEN src.type == "Comment" THEN
              tgt.@comment_cnt += 1
            WHEN src.type == "Post" THEN
              tgt.@post_cnt += 1
          END;
 PRINT Result[Result.@comment_cnt, Result.@post_cnt];
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The output should be the same as in Example 2.
### [](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns#_example_4)Example 4
Find Viktor Akhiezer’s total number of related comments and total number of related posts. That is, a comment or post is either created by Viktor or is liked by Viktor. Note that the `HAS_CREATOR` edge type starts from `Comment|Post`, and the `LIKES` edge type starts from Person.
Example 4. Disjunctive 1-hop edge pattern.
```
USE GRAPH ldbc_snb
set query_timeout=60000
INTERPRET QUERY () SYNTAX v2{
 SumAccum<int> @comment_cnt= 0;
 SumAccum<int> @post_cnt= 0;
 Result = SELECT tgt
      FROM Person:tgt -(<Has_Creator|Likes>)- (Comment|Post):src
      WHERE tgt.first_name == "Viktor" AND tgt.last_name == "Akhiezer"
      ACCUM CASE WHEN src.type == "Comment" THEN
             tgt.@comment_cnt += 1
           WHEN src.type == "Post" THEN
             tgt.@post_cnt += 1
         END;
 PRINT Result[Result.@comment_cnt, Result.@post_cnt];
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Output of Example 4.
```
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"Result": [{
  "v_id": "28587302323577",
  "attributes": {
   "Result.@post_cnt": 96,
   "Result.@comment_cnt": 152
  },
  "v_type": "Person"
 }]}]
}
coffeescript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/tutorials/pattern-matching/one-hop-patterns#_example_5)Example 5
Find the total number of comments or posts related to "Viktor Akhiezer". This time, we count them together and, we use the wildcard `_` to represent the two types of edges: `HAS_CREATOR` and `LIKES_REVERSE`. Both are following the same direction.
Example 5. Disjunctive 1-hop edge pattern.
```
USE GRAPH ldbc_snb
INTERPRET QUERY () SYNTAX v2{
 SumAccum<int> @@cnt= 0;
 Result = SELECT tgt
      FROM Person:tgt -(<_)- (Comment|Post):src
      WHERE tgt.first_name == "Viktor" AND tgt.last_name == "Akhiezer"
      ACCUM @@cnt += 1;
 PRINT @@cnt;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Output of Example 5.
```
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"@@cnt": 248}]
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


