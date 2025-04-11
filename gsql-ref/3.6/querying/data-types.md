![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types)[Next](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types)
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
[Resources](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types)
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
  * Querying
  * [Data Types](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/3.6/modules/querying/pages/data-types.adoc)
### Contents
  * [Identifiers](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_identifiers)
  * [Overview](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_overview)
  * [Base types](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_base_types)
  * [Vertex](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_vertex)
  * [Edge](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_edge)
  * [Vertex and Edge Attribute Types](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_vertex_and_edge_attribute_types)
  * [JSONOBJECT](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_jsonobject)
  * [JSONARRAY](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_jsonarray)
  * [Container types](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_container_types)
  * [Tuple](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_tuple)
  * [FILE Object](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_file_object)
  * [Query parameter types](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_query_parameter_types)


# Data Types
### Contents
  * [Identifiers](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_identifiers)
  * [Overview](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_overview)
  * [Base types](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_base_types)
  * [Vertex](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_vertex)
  * [Edge](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_edge)
  * [Vertex and Edge Attribute Types](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_vertex_and_edge_attribute_types)
  * [JSONOBJECT](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_jsonobject)
  * [JSONARRAY](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_jsonarray)
  * [Container types](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_container_types)
  * [Tuple](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_tuple)
  * [FILE Object](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_file_object)
  * [Query parameter types](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_query_parameter_types)


This section describes the data types that are native to and are supported by the GSQL Query Language. Most of the data objects used in queries come from one of three sources:
  * The query’s input parameters
  * The vertices, edges, and their attributes which are encountered when traversing the graph
  * The variables defined within the query to assist in the computational work of the query


This section covers the following subset of the EBNF language definitions:
EBNF for Data Types
```
lowercase     := [a-z]
uppercase     := [A-Z]
letter       := lowercase | uppercase
digit       := [0-9]
integer      := ["-"]digit+
real        := ["-"]("."digit+) | ["-"](digit+"."digit*)
numeric      := integer | real
stringLiteral   := '"' [~["] | '\\' ('"' | '\\')]* '"'
name := (letter | "_") [letter | digit | "_"]*  // Can be a single "_" or start with "_"
graphName := name
queryName := name
paramName := name
vertexType := name
edgeType := name
accumName := name
vertexSetName := name
attrName := name
varName := name
tupleType := name
fieldName :=name
funcName := name
type := baseType | tupleType | accumType
baseType := INT
     | UINT
     | FLOAT
     | DOUBLE
     | STRING
     | BOOL
     | VERTEX ["<" vertexType ">"]
     | EDGE
     | JSONOBJECT
     | JSONARRAY
     | DATETIME
filePath := paramName | stringLiteral
typedef := TYPEDEF TUPLE "<" tupleFields ">" tupleType
tupleFields := (baseType fieldName) | (fieldName baseType)
      ["," (baseType fieldName) | (fieldName baseType)]*
parameterType := baseType
        | [ SET | BAG ] "<" baseType ">"
        | FILE
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The legacy data type `STRING COMPRESS` has been deprecated since TigerGraph Server 3.0. You can no longer create new schema with the type `STRING COMPRESS`. As such, we have removed `STRING COMPRESS` from the documentation. Existing schemas that are using `STRING COMPRESS` can continue to function normally. If you need reference for `STRING COMPRESS`, please refer to GSQL Language Reference version 3.5 or older.  
---  
## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_identifiers)Identifiers
An identifier is the name for an instance of a language element. In the GSQL query language, identifiers are used to name elements such as a query, a variable, or a user-defined function. In the EBNF syntax, an identifier is referred as `name`. It can be a sequence of letters, digits, or underscores (`"_"`). Other punctuation characters are not supported. The initial character can only be a letter or an underscore.
name (identifier)
```
name := (letter | "_") [letter | digit | "_"]*
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_overview)Overview
Different types of data can be used in different contexts. The EBNF syntax defines several classes of data types. The most basic is called base type (`baseType`). The other independent type is `FILE`. The remaining types are either compound data types built from the independent data types, or supersets of other types. The table below gives an overview of their definitions and their uses.
EBNF term | Description | Use Case  
---|---|---  
`baseType` | `INT`, `UINT`, `FLOAT`, `DOUBLE`, `STRING`, `BOOL`, `DATETIME,` `VERTEX`, `EDGE`, + `JSONOBJECT`, or `JSONARRAY` | 
  * Base type variable
  * Query return value

  
`containerType` | `SET`, `BAG`, `LIST`, `MAP` | 
  * Local container variable

  
`tupleType` | Sequence of base types | 
  * User-defined tuple

  
`accumType` | Family of specialized data objects which support accumulation operations | 
  * Accumulate and aggregate data, when traversing a set of vertices or edges (Details are in the [Query Lang Spec - Accumulators](https://docs.tigergraph.com/gsql-ref/3.6/querying/accumulators) chapter.)

  
`FILE` | `FILE` object | 
  * Global sequential data object, linked to a text file

  
`parameterType` | `baseType` (except `EDGE` or `JSONOBJECT`), a set or bag of `baseType`, or `FILE` object | 
  * Query parameter

  
`elementType` | `baseType`, or identifier | 
  * Element for most types of container accumulators: `SetAccum`, `BagAccum`, `GroupByAccum`, key of a `MapAccum` element

  
`type` | `baseType`, identifier, or `accumType` | 
  * Element of a `ListAccum`, value of a `MapAccum` element
  * Local variable

  
## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_base_types)Base types
The query language supports the following _base types_ , which can be declared and assigned anywhere within their scope. Any of these base types may be used when defining a global variable, a local variable, a query return value, a parameter, part of a tuple, or an element of a container accumulator. Accumulators are described in detail in a later section.
EBNF
```
baseType := INT
     | UINT
     | FLOAT
     | DOUBLE
     | STRING
     | BOOL
     | VERTEX ["<" vertexType ">"]
     | EDGE
     | JSONOBJECT
     | JSONARRAY
     | DATETIME
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The default value of each base type is shown in the table below. The default value is the initial value of a base type variable (see Section "Variable Types" for more details), or the default return value for some functions.
The first seven types (`INT`, `UINT`, `FLOAT`, `DOUBLE`, `BOOL`, `STRING`, and `DATETIME`) are the same ones mentioned in the "[Attribute Data Types](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/system-and-language-basics#<em>attribute_data_types)" section of [_GSQL Language Reference, Part 1](https://docs.tigergraph.com/gsql-ref/3.6/ddl-and-loading/system-and-language-basics).
Type | Default value | Literal  
---|---|---  
`INT` | `0` | A signed integer: `-3`  
`UINT` | `0` | An unsigned integer: `5`  
`FLOAT` | `0` | A decimal: `3.14159`  
`DOUBLE` | `0` | A decimal with greater precision than `FLOAT`  
`BOOL` | `false` | `TRUE` or `FALSE`  
`STRING` | `""` | Characters enclosed by double quotes: `"Hello"`  
`DATETIME` | `1970-01-01 00:00:00` | No literal. Can be converted from a correctly formatted string with [`to_datetime()`](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/type-conversion-functions#_to_datetime).  
`VERTEX` | `"Unknown"` | No literal.  
`EDGE` | No edge: `{}` | No literal.  
`JSONOBJECT` | An empty object: `{}` | No literal. Can be converted from a correctly formatted string with [`parse_json_object()`](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/type-conversion-functions#_parse_json_object).  
`JSONARRAY` | An empty array: `[]` | No literal. Can be converted from a correctly formatted string with [`parse_json_array()`](https://docs.tigergraph.com/gsql-ref/3.6/querying/func/type-conversion-functions#_parse_json_array).  
`FLOAT` and `DOUBLE` input values must be in fixed point `d.dddd` _**_ format, where `d` is a digit. Output values will be printed in either fixed point for exponential notation, whichever is more compact. The GSQL Loader can read FLOAT and DOUBLE values with exponential notation (e.g., 1.25 E-7).  
---  
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_vertex)Vertex
`VERTEX` is considered a base type in the GSQL query language. Both query parameters and variables in a query body can be of type `VERTEX`.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_vertex_types)Vertex types
A graph schema defines specific vertex types. Each vertex type has its own set of attributes. The parameter or variable type can be restricted by giving the vertex type in angle brackets `<>` after the keyword `VERTEX`. A vertex variable declared without a specifier is called a _generic_ vertex variable.
Generic and typed vertex variables
```
VERTEX anyVertex;
VERTEX<person> owner;
```

All vertices have a built-in attribute `type`. The built-in attribute is of type string. You can access it with the dot (`.`) operator.
For example, if you declare a vertex variable `VERTEX<person> personVertex`, then `personVertex.type` returns `"person"`.
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_edge)Edge
`EDGE` is considered a base type in the GSQL query language. Both query parameters and variables in a query body can be of type `EDGE`.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_edge_types)Edge types
A graph schema defines specific edge types. Each edge type has its own set of attributes. The parameter or variable type can be restricted by giving the edge type in angle brackets `<>` after the keyword `EDGE`. An edge variable declared without a specifier is called a _generic_ edge variable.
Generic and typed edge variables
```
EDGE anyEdge;
EDGE<friendship> friendEdge;
```

All edges have a built-in attribute `type`. The built-in attribute is of type string. You can access it with the dot (`.`) operator.
For example, if you define an edge variable `EDGE<friendship> friendEdge`, then `friendEdge.type` returns `"Friendship"`.
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_vertex_and_edge_attribute_types)Vertex and Edge Attribute Types
The following table maps vertex or edge attribute types in the Data Definition Language (DDL) to GSQL query language types. If an attribute of a vertex or edge is referenced in a GSQL query, they will be automatically converted to their corresponding data type in the GSQL query language.
DDL | GSQL Query  
---|---  
`INT` | `INT`  
`UINT` | `UINT`  
`FLOAT` | `FLOAT`  
`DOUBLE` | `DOUBLE`  
`BOOL` | `BOOL`  
`STRING` | `STRING`  
`SET< type >` | `SetAccum< type >`  
`LIST< type >` | `ListAccum< type >`  
`MAP <key_type, value_type>` | `MapAccum <key_type, value_type>`  
`DATETIME` | `DATETIME`  
### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_jsonobject)`JSONOBJECT`
A `JSONOBJECT` instance’s external representation (as input and output) is a string, starting and ending with curly braces (`{}`) which enclose an unordered list of key-value pairs. `JSONOBJECT` is immutable. No operator is allowed to alter its value.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_assign_a_jsonobject_value_to_a_base_type_variable)Assign a `JSONOBJECT` value to a base type variable
There is no `JSONOBJECT` literal in the GSQL query language. Therefore, to assign value to a `JSONOBJECT` base type variable in GSQL, you need to use the `parse_json_object()` function to convert a string representation of s JSON object to a `JSONOBJECT` value.
For example, the following line declares a variable `han` with a `JSONOBJECT` value:
```
JSONOBJECT han = parse_json_object("{\"f_name\": \"Han\", \"l_name\": \"Solo\"}");
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_jsonarray)`JSONARRAY`
A `JSONARRAY` is represented as a string, starting and ending with square brackets (`[]`)which enclose an ordered list of _values_. `JSONARRAY` is immutable. No operator is allowed to alter its value.
#### [](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_assign_a_jsonarray_value_to_a_base_type_variable)Assign a `JSONARRAY` value to a base type variable
There is no `JSONARRAY` literal in the GSQL query language. Therefore, to assign value to a `JSONARRAY` base type variable in GSQL, you need to use the `parse_json_array()` function to convert a string representation of s JSON object to a `JSONARRAY` value.
For example, the following line declares a variable `fruits` with a `JSONARRAY` value:
```
JSONARRAY fruits = parse_json_array("[\"apple\", \"banana\", \"citrus\"]");
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_container_types)Container types
Container types include the following data types:
  * `SET`
  * `BAG`
  * `LIST`
  * `MAP`


Table 1. Container types Type | Literal | Example | Default value  
---|---|---|---  
`SET` | Elements enclosed by parentheses, separated by commas. | `(1, 2, 3)` | Empty set.  
`BAG` | Elements enclosed by parentheses, separated by commas. | `(1, 1, 2)` | Empty bag.  
`LIST` | Elements enclosed by square brackets, separated by commas. | `[1, 2, 3]` | Empty list.  
`MAP` | No literal. | N/A | Empty map.  
To see how container type variables are declared in a GSQL query, see [Local container variables](https://docs.tigergraph.com/gsql-ref/3.6/querying/declaration-and-assignment-statements#_local_container_variable).
## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_tuple)Tuple
A tuple is a user-defined data structure consisting of a fixed sequence of base type variables. Tuple types can be created and named using a `TYPEDEF` statement. Tuples must be defined first, before any other statements in a query.
EBNF for tuples
```
typedef := TYPEDEF TUPLE "<" tupleFields ">" tupleType
tupleFields := (baseType fieldName) | (fieldName baseType)
      ["," (baseType fieldName) | (fieldName baseType)]*
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

A tuple can also be defined in a graph schema and then can be used as a vertex or edge attribute type. A tuple type that has been defined in the graph schema does not need to be re-defined in a query.
The vertex type `person` contains two complex attributes:
  * `secretInfo` of type `SECRET_INFO`, which a user-defined tuple
  * `portfolio` of type `MAP<STRING, DOUBLE>`


`Investment_Net` Schema
```
TYPEDEF TUPLE <age UINT (4), mothers_name STRING(20) > SECRET_INFO
CREATE VERTEX Person(PRIMARY_ID person_id STRING, portfolio MAP<STRING, DOUBLE>, secret_info SECRET_INFO)
CREATE VERTEX Stock_Order(PRIMARY_ID order_id STRING, ticker STRING, order_size UINT, price FLOAT)
CREATE UNDIRECTED EDGE make_order(FROM Person, TO Stock_Order, order_time DATETIME)
CREATE GRAPH Investment_Net (*)
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The query below reads both the `SECRET_INFO` tuple and the portfolio MAP. The tuple type does not need to be redefined in the query. To read and save the map, we define a [`MapAccum`](https://docs.tigergraph.com/gsql-ref/3.6/querying/accumulators#_mapaccum) with the same types for key and value as the `portfolio` attribute. In addition, the query creates a new tuple type, `ORDER_RECORD`.
  * Query
  * Result


```
CREATE QUERY tuple_ex(VERTEX<Person> p) FOR GRAPH Investment_Net{
  TYPEDEF TUPLE <STRING ticker, FLOAT price, DATETIME order_time> Order_Record; **(1)**
  SetAccum<Secret_Info> @@info; **(2)**
  ListAccum<Order_Record> @@order_records;
  MapAccum<STRING, DOUBLE> @@portf;
  INIT = {p};
  // Get person p's secret_info and portfolio
  X = SELECT v FROM INIT:v
    ACCUM @@portf += v.portfolio, @@info += v.secret_info;
  // Search person p's orders to record ticker, price, and order time.
  // Note that the tuple gathers info from both edges and vertices.
  orders = SELECT t
    FROM INIT:s -(Make_Order:e)-Stock_Order:t
    ACCUM @@order_records += Order_Record(t.ticker, t.price, e.order_time);
  PRINT @@portf, @@info;
  PRINT @@order_records;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | This statement defines a new tuple `Order_Record` at the top of the query.  
---|---  
**2** | `Secret_Info` has already been defined in [`Investment_Net` Schema](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#Investment_Net-schema).  
```
GSQL > RUN QUERY tuple_ex("person1")
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
   "@@info": [{
    "mothers_name": "JAMES",
    "age": 25
   }],
   "@@portf": {
    "AAPL": 3142.24,
    "MS": 5000,
    "G": 6112.23
   }
  },
  {"@@order_records": [
   {
    "ticker": "B",
    "price": 202.32001,
    "order_time": "2017-03-03 18:42:30"
   },
   {
    "ticker": "AAPL",
    "price": 34.42,
    "order_time": "2017-03-03 18:42:28"
   },
   {
    "ticker": "A",
    "price": 50.55,
    "order_time": "2017-03-03 18:42:29"
   }
  ]}
 ]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_file_object)`FILE` Object
A `FILE` object is a sequential data storage object, associated with a text file on the local machine.
When referring to a `FILE` object, we always capitalize the word `FILE` to distinguish it from ordinary files.  
---  
When a `FILE` object is declared, associated with a particular text file, any existing content in the text file will be erased. During the execution of the query, content written to the `FILE` will be appended to the `FILE`. When the query where the `FILE` was declared finishes running, the `FILE` contents are saved to the text file.
A `FILE` object can be passed as a parameter to another query. When a query receives a `FILE` object as a parameter, it can append data to that `FILE`, as can every other query which receives this `FILE` object as a parameter.
## [](https://docs.tigergraph.com/gsql-ref/3.6/querying/data-types#_query_parameter_types)Query parameter types
Input parameters to a query can be base type (except `EDGE` , `JSONARRAY`, or `JSONOBJECT`). A parameter can also be a `SET` or `BAG` which uses base type (except `EDGE` , `JSONARRAY`, or `JSONOBJECT`) as the element type. A `FILE` object can also be a parameter. Within the query, `SET` and `BAG` are converted to [`SetAccum`](https://docs.tigergraph.com/gsql-ref/3.6/querying/accumulators#_setaccum) and [`BagAccum`](https://docs.tigergraph.com/gsql-ref/3.6/querying/accumulators#_bagaccum), respectively.
A query parameter is immutable. It cannot be assigned a new value within the query. The `FILE` object is a special case. It is passed by reference, meaning that the receiving query gets a link to the original `FILE` object. The receiving query can write to the `FILE` object.  
---  
EBNF
```
parameterType := INT
        | UINT
        | FLOAT
        | DOUBLE
        | STRING
        | BOOL
        | VERTEX ["<" vertexType ">"]
        | DATETIME
        | [ SET | BAG ] "<" baseType ">"
        | FILE
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Examples of collection type parameters
```
(SET<VERTEX<person> p1, BAG<INT> ids, FILE f1)
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


