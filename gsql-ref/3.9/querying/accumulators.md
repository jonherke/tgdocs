![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators)[Next](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators)
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
[Resources](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators)
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
  * [Accumulators](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/3.9/modules/querying/pages/accumulators.adoc)
### Contents
  * [Declaration of Accumulators](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_declaration_of_accumulators)
  * [Vertex-attached Accumulators](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_vertex_attached_accumulators)
  * [Global accumulators](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_global_accumulators)
  * [Example](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_example)
  * [Accumulator Types](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_accumulator_types)
  * [SumAccum](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_sumaccum)
  * [MinAccum / MaxAccum](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_minaccum_maxaccum)
  * [AvgAccum](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_avgaccum)
  * [AndAccum / OrAccum](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_andaccum_oraccum)
  * [BitwiseAndAccum / BitwiseOrAccum](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_bitwiseandaccum_bitwiseoraccum)
  * [ListAccum](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_listaccum)
  * [SetAccum](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_setaccum)
  * [BagAccum](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_bagaccum)
  * [MapAccum](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_mapaccum)
  * [ArrayAccum](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_arrayaccum)
  * [HeapAccum](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_heapaccum)
  * [GroupByAccum](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_groupbyaccum)
  * [Nested Accumulators](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_nested_accumulators)


# Accumulators
### Contents
  * [Declaration of Accumulators](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_declaration_of_accumulators)
  * [Vertex-attached Accumulators](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_vertex_attached_accumulators)
  * [Global accumulators](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_global_accumulators)
  * [Example](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_example)
  * [Accumulator Types](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_accumulator_types)
  * [SumAccum](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_sumaccum)
  * [MinAccum / MaxAccum](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_minaccum_maxaccum)
  * [AvgAccum](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_avgaccum)
  * [AndAccum / OrAccum](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_andaccum_oraccum)
  * [BitwiseAndAccum / BitwiseOrAccum](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_bitwiseandaccum_bitwiseoraccum)
  * [ListAccum](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_listaccum)
  * [SetAccum](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_setaccum)
  * [BagAccum](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_bagaccum)
  * [MapAccum](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_mapaccum)
  * [ArrayAccum](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_arrayaccum)
  * [HeapAccum](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_heapaccum)
  * [GroupByAccum](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_groupbyaccum)
  * [Nested Accumulators](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_nested_accumulators)


Accumulators are special types of variables that accumulate information about the graph during its traversal and exploration. Because they are a unique and important feature of the GSQL query language, we devote a separate section to their introduction, but additional detail on their usage will be covered in other sections, the [`SELECT` Statement section](https://docs.tigergraph.com/gsql-ref/3.9/querying/select-statement/sql-like-select-statement) in particular.
This section covers the following subset of the EBNF language definitions:
EBNF for accumulators
```
accumDeclStmt :=
     accumType localAccumName ["=" constant]
          ["," localAccumName ["=" constant]]*
    | accumType globalAccumName ["=" constant]
          ["," globalAccumName ["=" constant]]*
localAccumName := "@"accumName;
globalAccumName := "@@"accumName;

accumType := "SumAccum" "<" ( INT | FLOAT | DOUBLE | STRING) ">"
    | "MaxAccum" "<" ( INT | FLOAT | DOUBLE ) ">"
    | "MinAccum" "<" ( INT | FLOAT | DOUBLE ) ">"
    | "AvgAccum"
    | "OrAccum"
    | "AndAccum"
    | "BitwiseOrAccum"
    | "BitwiseAndAccum"
    | "ListAccum" "<" elementType ">"
    | "SetAccum" "<" elementType ">"
    | "BagAccum" "<" elementType ">"
    | "MapAccum" "<" elementType "," (baseType | accumType | tupleType) ">"
    | "HeapAccum" "<" tupleType ">" "(" simpleSize "," fieldName [ASC | DESC]
                     ["," fieldName [ASC | DESC]]* ")"
    | "GroupByAccum" "<" elementType fieldName ["," elementType fieldName]* ,
		           accumType fieldName ["," accumType fieldName]* ">"
    | "ArrayAccum" "<" accumName ">"
elementType := baseType | tupleType
gAccumAccumStmt := globalAccumName "+=" expr
accumClause := ACCUM DMLSubStmtList
postAccumClause := "POST-ACCUM" DMLSubStmtList
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

There are a number of different types of accumulators, each providing specific accumulation functions. Accumulators are declared to have one of two types of association: _global_ or _vertex-attached_.
More technically, accumulators are mutable mutex (mutual exclusion) variables shared among all the graph computation threads exploring the graph within a given query. To improve performance, the graph processing engine employs multithreaded processing. Modification of accumulators is coordinated at run-time so the accumulation operator works correctly (i.e., mutually exclusively) across all threads.
This is particularly relevant in the `ACCUM` clause. During traversal of the graph, the selected set of edges or vertices is partitioned among a group of threads. These threads have shared mutually exclusive access to the accumulators.
## [](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_declaration_of_accumulators)Declaration of Accumulators
Global accumulators can be declared anywhere in the query. Vertex-attached accumulators can be declared anywhere in the query except for in a `FOREACH` loop or `WHILE` loop. Accumulators are [block-scoped](https://docs.tigergraph.com/gsql-ref/3.9/querying/declaration-and-assignment-statements#_block_scoping) and can only be accessed in the block where they are declared.
The name of a vertex-attached accumulator begins with a single `@`.The name of a global accumulator begins with `@@`.
EBNF for Accumulator Declaration
```
accumDeclStmt := accumType localAccumName ["=" expr]
          ["," localAccumName ["=" expr]]*
        | accumType globalAccumName ["=" expr]
          ["," globalAccumName ["=" expr]]*
localAccumName := "@"accumName;
globalAccumName := "@@"accumName;
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_vertex_attached_accumulators)Vertex-attached Accumulators
Vertex-attached accumulators are mutable state variables that are attached to each vertex in the graph for the duration of the query’s lifetime. They act as run-time attributes of a vertex. They are shared, mutually exclusively, among all query processes.
Vertex-attached accumulators can be set to a value with the `=` operator. Additionally, the operator `=` can be used to update the state of the accumulator; the function of `=` depends on the accumulator type. Vertex-attached accumulators can only be accessed or updated (via = or +=) in an `ACCUM` or `POST-ACCUM` clause within a `SELECT` statement or by a `PRINT` statement.
In the example below, there are two accumulators attached to each vertex. The initial value of an accumulator of a given type is predefined, however it can be changed at declaration as in the accumulator @weight below. All vertex-attached accumulator names have a single leading at-sign `@`.
Vertex-Attached Accumulators
```
SumAccum<INT>  @neighbors;
MaxAccum<FLOAT> @weight = 2.8;
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

If there is a graph with 10 vertices, then there is an instance of `@neighbors` and `@weight` for each vertex (hence 10 of each, and 20 total accumulator instances). These are accessed via the dot operator on a vertex variable or a vertex alias (e.g., `v.@neighbor`). The accumulator operator += only impacts the accumulator for the specific vertex being referenced. A statement such as `v1.@neighbors += 1`will only impact `v1` 's `@neighbors` and not the `@neighbors` for other vertices.
## [](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_global_accumulators)Global accumulators
A global accumulator is a single mutable accumulator that can be accessed or updated within a query. The names of global accumulators start with a double at-sign `@@`.
Global Accumulators
```
SumAccum<INT>  @@totalNeighbors;
MaxAccum<FLOAT> @@entropy = 1.0;
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Global accumulators can only be assigned (using the `=` operator) outside a `SELECT` block (i.e., not within an `ACCUM` or `POST-ACCUM` clause). Global accumulators can be accessed or updated via the accumulate operator `+=` anywhere within a query, including inside a `SELECT` block.
The accumulation operation for global accumulators in an `ACCUM` clause executes once for each process. That is:
  * if the `FROM` clause uses an edge-induced selection (introduced in Section "`SELECT` Statement"), the `ACCUM` clause executes one process for each edge in the selected edge set.
  * If the `FROM` clause uses a vertex-induced selection (introduced in Section "`SELECT` Statement"), the `ACCUM` clause executes one process for each vertex in the selected vertex set.


Since global accumulators are shared in a mutually exclusive manner among processes, they behave very differently than a non-accumulator variable (see the [Declaration Statements](https://docs.tigergraph.com/gsql-ref/3.9/querying/declaration-and-assignment-statements#_declaration_statements) section for more details) in an `ACCUM` clause.
Take the following code example. The global accumulator `@@globalRelationshipCount` is accumulated for every `Works_For` edge traversed since it is shared among processes. Conversely, `Relationship_Count` appears to have only been incremented once.
This is because a non-accumulator variable is not shared among processes. Each process has its own separate unshared copy of `Relationship_Count` and increments the original value by one. (E.g., each process increments **Relationship_Count** from 0 to 1.) There is no accumulation and the final value is one.
### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_example)Example
  * Query
  * Results


Global Variable vs Global Accumulator
```
// Count the total number of employment relationships for all companies
CREATE QUERY count_employment_relationships() FOR GRAPH Work_Net SYNTAX V2 {
  INT local_relationship_count;
  SumAccum<INT> @@global_relationship_count;
  start = {Company.*};
  companies = SELECT s FROM start:s -(Works_For)- :t
    ACCUM @@global_relationship_count += 1,
    local_relationship_count = local_relationship_count + 1;
  PRINT local_relationship_count;
  PRINT @@global_relationship_count;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

countEmploymentRelationship.json Results
```
GSQL > RUN QUERY count_employment_relationships()
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [
  {"local_relationship_count": 1},
  {"@@global_relationship_count": 17}
 ]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_accumulator_types)Accumulator Types
The following are the accumulator types we currently support. Each type of accumulator supports one or more data types.
EBNF for Accumulator Types
```
accumType := "SumAccum" "<" ( INT | FLOAT | DOUBLE | STRING) ">"
		  | "MaxAccum" "<" ( INT | FLOAT | DOUBLE ) ">"
 	   | "MinAccum" "<" ( INT | FLOAT | DOUBLE ) ">"
   	 | "AvgAccum"
		  | "OrAccum"
		  | "AndAccum"
    | "BitwiseOrAccum"
    | "BitwiseAndAccum"
		  | "ListAccum" "<" type ">"
		  | "SetAccum" "<" elementType ">"
		  | "BagAccum" "<" elementType ">"
    | "MapAccum" "<" elementType "," (baseType | accumType | tupleType) ">"
    | "HeapAccum" "<" tupleType ">" "(" simpleSize "," fieleName [ASC | DESC]
                ["," fieldName [ASC | DESC]]* ")"
		  | "GroupByAccum" "<" elementType fieldName ["," elementType fieldName]* ,
		            accumType fieldName ["," accumType fieldName]* ">"
    | "ArrayAccum" "<" accumName ">"
elementType := baseType | tupleType
gAccumAccumStmt := globaAccumName "+=" expr
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The accumulators fall into two major groups :
  * **Scalar Accumulators** store a single value:
    * SumAccum
    * MinAccum, MaxAccum
    * AvgAccum
    * AndAccum, OrAccum
    * BitwiseAndAccum, BitwiseOrAccum
  * **Collection Accumulators** store a set of values:
    * ListAccum
    * SetAccum
    * BagAccum
    * MapAccum
    * ArrayAccum
    * HeapAccum
    * GroupByAccum


The details of each accumulator type are summarized in this table. The Accumulation Operation column explains how the accumulator `exampleAccum` is updated when the statement `exampleAccum += newVal` is executed. Following the table are example queries for each accumulator type.
Table 1. Accumulator Types and Their Accumulation Behavior Accumulator type (Case Sensitive) | Default Initial Value | Accumulation operation  
---|---|---  
`SumAccum<INT>` | 0 | Adds right operand to `SumAccum`.  
`SumAccum<FLOAT or DOUBLE>` | 0.0 | Adds right operand to `SumAccum`.  
`SumAccum<STRING>` | Empty string | Concatenates `SumAccum` and right operand.  
`MaxAccum<INT>` | `INT_MIN` | Updates the value of `MaxAccum` to the greater between `MaxAccum` and right operand.  
`MaxAccum<FLOAT or DOUBLE>` | `FLOAT_MIN` or `DOUBLE_MIN` | Updates the value of `MaxAccum` to the greater between `MaxAccum` and right operand.  
`MaxAccum<STRING>` | Empty string | Updates the value of `MaxAccum` to the greater between `MaxAccum` and right operand according to UTF-8 lexicographical ordering.  
`MaxAccum<VERTEX>` | Vertex with internal ID `0` | Updates the value of `MaxAccum` to the vertex with greater internal ID between `MaxAccum` and right operand.  
`MaxAccum<tupleType>` | Default for each field of the tuple | Updates the value of `MaxAccum` to the greater between `MaxAccum` and right operand. `tupleType` is a user-defined sequence of base types. Ordering is hierarchical, using the leftmost field of the tuple first, then the next field, and so on.  
`MinAccum<INT>` | `INT_MAX` | Updates the value of `MinAccum` to the lesser between `MinAccum` and right operand.  
`MinAccum<FLOAT or DOUBLE>` | `FLOAT_MAX` or `DOUBLE_MAX` | Updates the value of `MinAccum` to the lesser between `MinAccum` and right operand.  
`MinAccum<STRING>` | empty string | Updates the value of `MinAccum` to the lesser between `MinAccum` and right operand according to UTF-8 lexicographical ordering.  
`MinAccum<VERTEX>` | unknown | Updates the value of `MinAccum` to the vertex with lesser internal ID between `MinAccum` and right operand.  
`MinAccum<tupleType>` | Default for each field of the tuple | Updates the value of `MinAccum` to the lesser between `MinAccum` and right operand. `tupleType` is a user-defined sequence of baseTypes. Ordering is hierarchical, using the leftmost field of the tuple first, then the next field, and so on.  
`AvgAccum` | 0.0 (double precision) | Updates `AvgAccum` to double precision average of right operand and all previous values accumulated to `AvgAccum`  
`AndAccum` | True | Updates `AndAccum` to boolean `AND` of right operand and `AndAccum`.  
`OrAccum` | False | Updates `OrAccum` to boolean `OR` of right operand and `AndAccum`.  
`BitwiseAndAccum` | -1 (INT) = 64-bit sequence of 1s | Updates `BitwiseAndAccum` to boolean `AND` of right operand and `BitwiseAndAccum`.  
`BitwiseOrAccum` | 0 (INT) = 64-bit sequence of 0s | Updates `BitwiseOrAccum` to boolean `OR` of right operand and `BitwiseORAccum`.  
`ListAccum< type >` | Empty list | Appends right operand to end of `ListAccum`.  
`SetAccum< type >` | empty set | Updates `SetAccum` to union of right operand and `SetAccum`. right operand can be a single value or a set/bag.  
`BagAccum<type>` | Empty bag | Updates `BagAccum` to union of right operand and `BagAccum`. Right operand can be a single value or a set/bag.  
`MapAccum< type, type >` | Empty map | Adds or updates a key-value pair of `MapAccum`.  
`ArrayAccum< accumType >` | Empty list | See the [ArrayAccum](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_arrayaccum) section below for details.  
`HeapAccum< tuple >(heapSize, sortKey)` | Empty heap | Inserts right operand into HeapAccum, maintaining the heap in sorted order, according to the sort key(s) and size limit declared for this `HeapAccum`.  
`GroupByAccum< _type [, type] , accumType [, accumType]*_ >`|  Empty group by map | Adds or updates a key:value pair GroupByAccum. See Section [GroupByAccum](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_groupbyaccum) for more details.  
### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_sumaccum)SumAccum
The `SumAccum` type computes and stores the cumulative sum of numeric values or the cumulative concatenation of text values. The output of a `SumAccum` is a single numeric or string value. `SumAccum` variables operate on values of type `INT`, `UINT`, `FLOAT`, `DOUBLE`, or `STRING` only.
The `=` operator updates the accumulator's state. For `INT`, `FLOAT`, and `DOUBLE` types, `= arg` performs a numeric addition, while for the `STRING` value type `+= arg` concatenates `arg` to the current value of the `SumAccum`.
#### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_example_2)Example
  * Query
  * Results


SumAccum Example
```
CREATE QUERY sum_accum_ex() FOR GRAPH Minimal_Net {
  SumAccum<INT>  @@int_accum;
  SumAccum<FLOAT> @@float_accum;
  SumAccum<DOUBLE> @@double_accum;
  SumAccum<STRING> @@string_accum;
  @@int_accum = 1;
  @@int_accum += 1;
  @@float_accum = @@int_accum;
  @@float_accum = @@float_accum / 3;
  @@double_accum = @@float_accum * 8;
  @@double_accum += -1;
  @@string_accum = "Hello ";
  @@string_accum += "World";
  PRINT @@int_accum;
  PRINT @@float_accum;
  PRINT @@double_accum;
  PRINT @@string_accum;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

sumAccumEx.json Result
```
GSQL > RUN QUERY sum_accum_ex()
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [
  {"@@int_accum": 2},
  {"@@float_accum": 0.66667},
  {"@@double_accum": 4.33333},
  {"@@string_accum": "Hello World"}
 ]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_minaccum_maxaccum)MinAccum / MaxAccum
The `MinAccum` and `MaxAccum` types calculate and store the cumulative minimum or the cumulative maximum of a series of values. The output of a `MinAccum` or a `MaxAccum` is a single value of the type that was passed in. `MinAccum` and `MaxAccum` variables operate on values of type `INT, UINT, FLOAT, DOUBLE, STRING, TUPLE`, and `VERTEX` (with optional specific vertex type) only.
For `MinAccum`, `+= arg` checks if the current value held is less than `arg` and stores the smaller of the two. `MaxAccum` behaves the same, with the exception that it checks for and stores the greater instead of the lesser of the two.
#### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_example_3)Example
  * Query
  * Results


MinAccum and MaxAccum Example
```
CREATE QUERY min_max_accum_ex() FOR GRAPH Minimal_Net {
  MinAccum<INT> @@min_accum;
  MaxAccum<FLOAT> @@max_accum;
  @@min_accum += 40;
  @@min_accum += 20;
  @@min_accum += -10;
  @@max_accum += -1.1;
  @@max_accum += 2.5;
  @@max_accum += 2.8;
  PRINT @@min_accum;
  PRINT @@max_accum;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
GSQL > RUN QUERY min_max_accum_Ex()
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [
  {"@@min_accum": -10},
  {"@@max_accum": 2.8}
 ]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

String minimum and maximum values are based on their UTF-8 codes, which is a multilingual superset of the ASCII codes. Within ASCII, `a` is less than `z`, uppercase is less than lowercase, and digits are less than alphabetic characters.
`MinAccum` and `MaxAccum` operating on `VERTEX` types have a special comparison. They do not compare vertex ids, but TigerGraph internal ids, which might not be in the same order as the external ids. Comparing internal ids is much faster, so `MinAccum/MaxAccum<VERTEX>` provides an efficient way to compare and select vertices. This is helpful for some graph algorithms that require the vertices to be numbered and sortable. For example, the following query returns one post from each person. The returned vertex is not necessarily the vertex with the alphabetically largest id.
  * Query
  * Results


This query returns one random post vertex from each person
```
CREATE QUERY min_max_accum_vertex() FOR GRAPH Social_Net api("v2") {
 MaxAccum<VERTEX> @max_vertex;
 all_user = {Person.*};
 all_user = SELECT src
      FROM all_user:src -(Posted>)- Post:tgt
      ACCUM src.@max_vertex += tgt
      ORDER BY src.id;
 PRINT all_user[all_user.@max_vertex]; // api v2
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

minMaxAccumVertex.json Result
```
GSQL > RUN QUERY min_max_accum_vertex()
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{"allUser": [
  {
   "v_id": "person1",
   "attributes": {"allUser.@maxVertex": "0"},
   "v_type": "person"
  },
  {
   "v_id": "person2",
   "attributes": {"allUser.@maxVertex": "1"},
   "v_type": "person"
  },
  {
   "v_id": "person3",
   "attributes": {"allUser.@maxVertex": "2"},
   "v_type": "person"
  },
  {
   "v_id": "person4",
   "attributes": {"allUser.@maxVertex": "3"},
   "v_type": "person"
  },
  {
   "v_id": "person5",
   "attributes": {"allUser.@maxVertex": "11"},
   "v_type": "person"
  },
  {
   "v_id": "person6",
   "attributes": {"allUser.@maxVertex": "10"},
   "v_type": "person"
  },
  {
   "v_id": "person7",
   "attributes": {"allUser.@maxVertex": "9"},
   "v_type": "person"
  },
  {
   "v_id": "person8",
   "attributes": {"allUser.@maxVertex": "7"},
   "v_type": "person"
  }
 ]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Tuple data types are treated as hierarchical structures, where the first field used for ordering is the leftmost one. When a tuple is used as an element of a `MinAccum` or `MaxAccum`, tuple fields can be directly accessed from the accumulator. For example, if we have the following tuple type and `MaxAccum` :
```
TYPEDEF TUPLE <FLOAT weight> Edge_Weight
MinAccum<EDGE_WEIGHT> @@acc_test;
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Then the `weight` field of the tuple can be accessed directly from the `MinAccum` through the dot operator(`.`):
```
@@acc_test.weight // Will return the weight field value for the EDGE_WEIGHT
         // type tuple stored in the MaxAccum
cpp![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_avgaccum)AvgAccum
The AvgAccum type calculates and stores the cumulative mean of a series of numeric values. Internally, its state information includes the sum value of all inputs and a count of how many input values it has accumulated. The output is the mean value; the sum and the count values are not accessible to the user.
The data type of an AvgAccum variable is not declared; all AvgAccum accumulators accept inputs of type `INT`, `UINT`, `FLOAT`, and `DOUBLE`. The output is always `DOUBLE` type.
The `+= arg` operation updates the AvgAccum variable’s state to be the mean of all the previous arguments along with the current argument. The `= arg` operation clears the previously accumulated state and sets the new state to be `arg` with a count of one.
#### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_example_4)Example
  * Query
  * Results


AvgAccum Example
```
CREATE QUERY avg_accum_ex() FOR GRAPH Minimal_Net {
  AvgAccum @@average_accum;
  @@average_accum += 10;
  @@average_accum += 5.5; // avg = (10+5.5) / 2.0
  @@average_accum += -1; // avg = (10+5.5-1) / 3.0
  PRINT @@average_accum; // 4.8333...
  @@average_accum = 99;  // reset
  @@average_accum += 101; // avg = (99 + 101) / 2
  PRINT @@average_accum; // 100
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
GSQL > RUN QUERY avg_accum_ex()
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [
  {"@@average_accum": 4.83333},
  {"@@average_accum": 100}
 ]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_andaccum_oraccum)AndAccum / OrAccum
The AndAccum and OrAccum types calculate and store the cumulative result of a series of boolean operations. The output of an AndAccum or an OrAccum is a single boolean value (`TRUE` or `FALSE`). AndAccum and OrAccum variables operate on boolean values only. The data type does not need to be declared.
For AndAccum, `+= arg` updates the state to be the logical `AND` between the current boolean state and `arg`. OrAccum behaves the same, with the exception that it stores the result of a logical `OR` operation.
#### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_example_5)Example
  * Query
  * Results


AndAccum and OrAccum Example
```
CREATE QUERY and_or_accum_ex() FOR GRAPH Minimal_Net {
  AndAccum @@and_accum_var; // (default value = TRUE)
  OrAccum @@or_accum_var; // (default value = FALSE)
  @@and_accum_var += TRUE; // T and T = T
  @@and_accum_var += FALSE; // T and F = F
  @@and_accum_var += TRUE; // F and T = F
  PRINT @@and_accum_var;
  @@or_accum_var += FALSE; // F or F == F
  @@or_accum_var += TRUE;  // F or T == T
  @@or_accum_var += FALSE; // T or F == T
  PRINT @@or_accum_var;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
GSQL > RUN QUERY and_or_accum_ex()
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [
  {"@@and_accum_var": false},
  {"@@or_accum_var": true}
 ]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_bitwiseandaccum_bitwiseoraccum)BitwiseAndAccum / BitwiseOrAccum
The BitwiseAndAccum and BitwiseOrAccum types calculate and store the cumulative result of a series of bitwise boolean operations and store the resulting bit sequences. The default length for both BitwiseAndAccum and BitwiseOrAccum is 64 bit. You can specify the length of both types by appending the desired length in angle brackets`<>`.
Fundamental to understanding and using bitwise operations is the knowledge that integers are stored in base-2 representation as a 64-bit sequence of 1s and 0s. "Bitwise" means that each bit is treated as a separate boolean value, with 1 representing true and 0 representing false. Hence, an integer is equivalent to a sequence of boolean values. Computing the Bitwise `AND` of two numbers A and B means computing the bit sequence C where the jth bit of C, denoted Cj, is equal to Aj `AND` Bj.
#### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_declaration)Declaration
A bitwise accumulator has different declaration syntax depending on its length:
  * When a bitwise accumulator length is less than or equal to 64 bit, it’s assigned using one integer. The integer is converted to a 64-bit sequence of 1s and 0s. Overflow on the left is ignored.
  * When a bitwise accumulator length is longer than 64 bit, it’s assigned using an array of two integers. Each integer is converted to a 64-bit sequence of 1s and 0s. The integer in the second position will take up the first 64 bits from the right of the sequence, and the integer on the left will take up the remaining bits. Any overflowing bits will be ignored.


For example, if you are declaring an 80-bit BitwiseAndAccum:
```
@@bit80<80> = [123, 456]
```

456 represents the 64-bit sequence `0000….000111001000` (zeros omitted), and 123 represents the 64-bit sequence `0000000000…00001111011` (zeros omitted).
When the two integers are joined together, the 64-bit sequence on the right (456) takes up the 64 bits from the right. The 64-bit sequence on the left (123) takes up the remaining 16 bits and the overflow on the left is ignored.
The resulting BitwiseAndAccum prints as below:
```
0000000001111011 (16bits in total) 0000000...000111001000 (64bits in total)
```

#### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_accumulation_behavior)Accumulation behavior
For BitwiseAndAccum, `+= arg` updates the accumulator’s state to be the Bitwise `AND` of the current state and `arg`. BitwiseOrAccum behaves the same, with the exception that it computes a Bitwise `OR`.
Bitwise Operations and Negative Integers Most computer systems represent negative integers using "2’s complement" format, where the uppermost bit has special significance. Operations that affect the uppermost bit are crossing the boundary between positive and negative numbers, and vice versa.  
---  
#### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_functions)Functions
This is a list of methods of BitwiseAndAccum and BitwiseOrAccum. If a method returns an `BitwiseAndAccum` or `BitwiseOrAccum`, it returns the same type as the instance that calls the method.
Table 2. Bitwise accumulator functions Function | Return type | Accessor/Mutator | Description  
---|---|---|---  
`.reset()` | None. | Mutator | Sets all bits to 0.  
`.cardinality()` | `INT` | Accessor | Returns the number of 1s.  
`.get( index )` | `INT` | Accessor |  Returns the 1 or 0 at the provided index.
  * `index`: `INT`. The position of the bit value to return.

  
`.set( )` | None. | Mutator | Sets all bits to 1.  
`.set( index, value )` | None. | Mutator |  Sets the bit at the provided index to the desire value.
  * `index`: `INT`. The position of the bit
  * `value`: `BOOL`. The value of the bit.

  
`.flip( index )` | None. | Mutator | Flips the bit at the specified index. If the bit is 0, changes it to 1 and vice versa.  
`.flip( fromIndex [, toIndex ] )` | None. | Mutator | Flips the bits in the specified range.  
`.xor ( accum )` | None. | Mutator | Compares two bitwise accumulators of the same length. Returns a Bitwise accumulator whose every bit is the exclusive `OR` result between the two bitwise accumulators.  
`.and ( accum )` | None. | Mutator | Compares two bitwise accumulators of the same length. Returns a bitwise accumulator whose every bit is the `AND` result between the two bitwise accumulators.  
`.or ( accum )` | None. | Mutator | Compares two bitwise accumulators of the same length. Returns a Bitwise accumulator whose every bit is the `OR` result between the two bitwise accumulators.  
#### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_example_6)Example
  * Query
  * Results


```
CREATE QUERY bitwise_accum_ex() FOR GRAPH Minimal_Net {
  BitwiseAndAccum @@bw_and_accum_var; // default value = 64-bits of 1 = -1 (INT)
  BitwiseOrAccum  @@bw_or_accum_var;  // default value = 64-bits of 0 = 0 (INT))
  // 11110000 = 240
  // 00001111 =  15
  // 10101010 = 170
  // 01010101 =  85
  // BitwiseAndAccum
  @@bw_and_accum_var += 170; // 11111111 & 10101010 -> 10101010
  @@bw_and_accum_var +=  85; // 10101010 & 01010101 -> 00000000
  PRINT @@bw_and_accum_var;  // 0
  @@bw_and_accum_var = 15;   // reset to 00001111
  @@bw_and_accum_var += 85;  // 00001111 & 01010101 -> 00000101
  PRINT @@bw_and_accum_var;  // 5
  // BitwiseOrAccum
  @@bw_or_accum_var += 170; // 00000000 | 10101010 -> 10101010
  @@bw_or_accum_var +=  85; // 10101010 | 01010101 -> 11111111 = 255
  PRINT @@bw_or_accum_var;  // 255
  @@bw_or_accum_var = 15;   // reset to 00001111
  @@bw_or_accum_var += 85;  // 00001111 | 01010101 -> 01011111 = 95
  PRINT @@bw_or_accum_var;  // 95
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
GSQL > RUN QUERY bitwise_accum_ex()
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [
  {"@@bw_and_accum_var": "0000000000000000000000000000000000000000000000000000000000000000"},
  {"@@bw_and_accum_var": "0000000000000000000000000000000000000000000000000000000000000101"},
  {"@@bw_or_accum_var": "0000000000000000000000000000000000000000000000000000000011111111"},
  {"@@bw_or_accum_var": "0000000000000000000000000000000000000000000000000000000001011111"}
 ]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_listaccum)ListAccum
The ListAccum type maintains a sequential collection of elements. The output of a ListAccum is a list of values in the order the elements were added. The element type can be any base type or tuple. Additionally, a ListAccum can contain a nested collection of type ListAccum. Nesting of ListAccums is limited to a depth of three.
The `+= arg` operation appends `arg` to the end of the list. In this case, `arg` may be either a single element or another ListAccum.
ListAccum supports two additional operations:
  * `@list1 + @list2` creates a new ListAccum, which contains the elements of `@list1` followed by the elements of `@list2`. The two ListAccums must have identical data types.
  * `@list1 * @list2` (`STRING` data only) generates a new list of strings consisting of all permutations of an element of the first list followed by an element of the second list.


ListAccum also supports the following class functions.
Functions that modify the ListAccum (mutator functions) can be used only under the following conditions:
  * Mutator functions of global accumulators may only be used at the query-body level.
  * Mutator functions of vertex-attached accumulators may only be used in a `POST-ACCUM` clause.

  
---  
Function (T is the element type) | Return type | Accessor / Mutator | Description  
---|---|---|---  
`.size()` | `INT` | Accessor | Returns the number of elements in the list.  
`.contains( T _val_ )`| `BOOL` | Accessor | Returns true if the list does contain `value`, and false if it doesn’t.  
`.get( INT _idx_ )`|  T | Accessor | Returns the value at the given _index_ position in the list. The index begins at 0. If the index is out of bound (including any negative value), the default value of the element type is returned.  
`.clear()` | `VOID` | Mutator | Clears the list so it becomes empty with size 0.  
`.update (INT _index,_ T _value_ )`| `VOID` | Mutator | Assigns _value_ to the list element at position _index_.  
`.remove(INT _index_)`| `VOID` | Mutator | Removes value at the specified index. If the index is invalid, the function will do nothing.  
`.removeOne(T _value_)`| `VOID` | Mutator | Removes the first matching value. If there is no matching value, the function will do nothing.  
`.removeAll(T _value_)`| `VOID` | Mutator | Removes all matching values. If there is no matching value, the function will do nothing.  
#### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_examples)Examples
  * Query
  * Results


```
CREATE QUERY list_accum_ex() FOR GRAPH Minimal_Net {
  ListAccum<INT> @@int_list_accum;
  ListAccum<STRING> @@string_list_accum;
  ListAccum<STRING> @@string_multiply_list_accum;
  ListAccum<STRING> @@string_addition_accum;
  ListAccum<STRING> @@letter_list_accum;
  ListAccum<ListAccum<STRING>> @@nested_list_accum;
  @@int_list_accum = [1,3,5];
  @@int_list_accum += [7,9];
  @@int_list_accum += 11;
  @@int_list_accum += 13;
  @@int_list_accum += 15;
  PRINT @@int_list_accum;
  PRINT @@int_list_accum.get(0), @@int_list_accum.get(1);
  PRINT @@int_list_accum.get(8); // Out of bound: default value of int: 0
  // Other built-in functions
  PRINT @@int_list_accum.size();
  PRINT @@int_list_accum.contains(2);
  PRINT @@int_list_accum.contains(3);
  @@string_list_accum += "Hello";
  @@string_list_accum += "World";
  PRINT @@string_list_accum; // ["Hello","World"]
  @@letter_list_accum += "a";
  @@letter_list_accum += "b";
  // ListA + ListB produces a new list equivalent to ListB appended to ListA.
  // Ex: [a,b,c] + [d,e,f] => [a,b,c,d,e,f]
  @@string_addition_accum = @@string_list_accum + @@letter_list_accum;
  PRINT @@string_addition_accum;
  // Multiplication produces a list of all list-to-list element combinations (STRING TYPE ONLY)
  // Ex: [a,b] * [c,d] = [ac, ad, bc, bd]
  @@string_multiply_list_accum = @@string_list_accum * @@letter_list_accum;
  PRINT @@string_multiply_list_accum;
  // Two dimensional list (3 dimensions is possible as well)
  @@nested_list_accum += [["foo", "bar"], ["Big", "Bang", "Theory"], ["String", "Theory"]];
  PRINT @@nested_list_accum;
  PRINT @@nested_list_accum.get(0);
  PRINT @@nested_list_accum.get(0).get(1);
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
GSQL > RUN QUERY list_accum_ex()
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [
  {"@@int_list_accum": [
   1,
   3,
   5,
   7,
   9,
   11,
   13,
   15
  ]},
  {
   "@@int_list_accum.get(1)": 3,
   "@@int_list_accum.get(0)": 1
  },
  {"@@int_list_accum.get(8)": 0},
  {"@@int_list_accum.size()": 8},
  {"@@int_list_accum.contains(2)": false},
  {"@@int_list_accum.contains(3)": true},
  {"@@string_list_accum": [
   "Hello",
   "World"
  ]},
  {"@@string_addition_accum": [
   "Hello",
   "World",
   "a",
   "b"
  ]},
  {"@@string_multiply_list_accum": [
   "Helloa",
   "Worlda",
   "Hellob",
   "Worldb"
  ]},
  {"@@nested_list_accum": [
   [
    "foo",
    "bar"
   ],
   [
    "Big",
    "Bang",
    "Theory"
   ],
   [
    "String",
    "Theory"
   ]
  ]},
  {"@@nested_list_accum.get(0)": [
   "foo",
   "bar"
  ]},
  {"@@nested_list_accum.get(0).get(1)": "bar"}
 ]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * Query
  * Results


Example for update function on a global ListAccum
```
CREATE QUERY list_accum_update_ex() FOR GRAPH Work_Net {
  // Global List_accum
  ListAccum<INT> @@int_list_accum;
  ListAccum<STRING> @@string_list_accum;
  ListAccum<BOOL> @@pass_fail;
  @@int_list_accum += [0,2,4,6,8];
  @@string_list_accum += ["apple","banana","carrot","daikon"];
  // Global update at Query-Body Level
  @@pass_fail += @@int_list_accum.update(1,-99);
  @@pass_fail += @@int_list_accum.update(@@int_list_accum.size()-1,40);  // last element
  @@pass_fail += @@string_list_accum.update(0,"zero"); // first element
  @@pass_fail += @@string_list_accum.update(4,"four"); // FAIL: out-of-range
  PRINT @@int_list_accum, @@string_list_accum, @@pass_fail;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results in listAccumUpdateEx.json
```
GSQL > RUN QUERY list_accum_update_ex()
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{
  "@@passFail": [ true, true, true, false ],
  "@@intListAccum": [ 0, -99, 4, 6, 40 ],
  "@@stringListAccum": [ "zero", "banana", "carrot", "daikon" ]
 }]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * Query
  * Results


Example for update function on a vertex-attached ListAccum
```
CREATE QUERY list_accum_update_ex2(SET<VERTEX<Person>> seed) FOR GRAPH Work_Net api("v2") {
  // Each person has an LIST<INT> of skills and a LIST<STRING> of interests.
  // This function copies their lists into ListAccums, and then udpates the last
  // int with -99 and updates the last string with "fizz".
  ListAccum<INT> @int_list;
  ListAccum<STRING> @string_list;
  ListAccum<STRING> @@int_fails, @@str_fails;
  S0 (Person) = seed;
  S1 = SELECT s
    FROM S0:s
    ACCUM
      s.@int_list = s.skill_list,
      s.@string_list = s.interest_list
    POST-ACCUM
      INT len = s.@int_list.size(),
      IF NOT s.@int_list.update(len-1,-99) THEN
        @@int_fails += s.id END,
        INT len2 = s.@string_list.size(),
      IF NOT s.@string_list.update(len2-1,"fizz") THEN
        @@str_fails += s.id
      END
    ;
  PRINT S1[S1.skill_list, S1.interest_list, S1.@int_list, S1.@string_list]; // api v2
  PRINT @@int_fails, @@str_fails;
}
// RUN QUERY list_accum_update_ex2(["person1","person5"])
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
GSQL > RUN QUERY list_accum_update_ex2(["person1","person5"])
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [
  {"S1": [
   {
    "v_id": "person1",
    "attributes": {
     "S1.@int_list": [
      1,
      2,
      -99
     ],
     "S1.skill_list": [
      1,
      2,
      3
     ],
     "S1.interest_list": [
      "management",
      "financial"
     ],
     "S1.@string_list": [
      "management",
      "fizz"
     ]
    },
    "v_type": "Person"
   },
   {
    "v_id": "person5",
    "attributes": {
     "S1.@int_list": [
      8,
      2,
      -99
     ],
     "S1.skill_list": [
      8,
      2,
      5
     ],
     "S1.interest_list": [
      "sport",
      "financial",
      "engineering"
     ],
     "S1.@string_list": [
      "sport",
      "financial",
      "fizz"
     ]
    },
    "v_type": "Person"
   }
  ]},
  {
   "@@int_fails": [],
   "@@str_fails": []
  }
 ]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_setaccum)SetAccum
The SetAccum type maintains a collection of unique elements.The output of a SetAccum is a list of elements in arbitrary order. A SetAccum instance can contain values of one type. The element type can be any base type or tuple.
For SetAccum, the `+= arg` operation adds a non-duplicate element or set of elements to the set. If an element is already represented in the set, then the SetAccum state does not change.
SetAccum also can be used with the three canonical set operators: `UNION`, `INTERSECT`, and `MINUS` (see the [Set/Bag Expression and Operators](https://docs.tigergraph.com/gsql-ref/3.9/querying/operators-and-expressions#_setbag_expression_and_operators) section for more details).
SetAccum also supports the following class functions.
Functions that modify the SetAccum (mutator functions) can be used only under the following conditions:
  * Mutator functions of global accumulators may only be used at the query-body level.
  * Mutator functions of vertex-attached accumulators may only be used in a `POST-ACCUM` clause.

  
---  
Function (T is the element type) | Return type | Accessor / Mutator | Description  
---|---|---|---  
`size()` | `INT` | Accessor | Returns the number of elements in the set.  
`contains( T value )` | `BOOL` | Accessor | Returns true if the set contains `value`. Returns false if the set doesn’t contain `value`.  
`remove( T value )` | `VOID` | Mutator | Removes `value` from the set.  
`clear()` | `VOID` | Mutator | Clears the set so it becomes empty with size 0.  
#### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_example_7)Example
  * Query
  * Results


SetAccum Example
```
# SetAccum Example
CREATE QUERY setAccumEx() FOR GRAPH Minimal_Net {
 SetAccum<INT> @@intSetAccum;
 SetAccum<STRING> @@stringSetAccum;
 @@intSetAccum += 5;
 @@intSetAccum.clear();
 @@intSetAccum += 4;
 @@intSetAccum += 11;
 @@intSetAccum += 1;
 @@intSetAccum += 11; # Sets do not store duplicates
 @@intSetAccum += (1,2,3,4); # Can create simple sets this way
 PRINT @@intSetAccum;
 @@intSetAccum.remove(2);
 PRINT @@intSetAccum AS RemovedVal2; # Demostrate remove.
 PRINT @@intSetAccum.contains(3);
 @@stringSetAccum += "Hello";
 @@stringSetAccum += "Hello";
 @@stringSetAccum += "There";
 @@stringSetAccum += "World";
 PRINT @@stringSetAccum;
 PRINT @@stringSetAccum.contains("Hello");
 PRINT @@stringSetAccum.size();
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

setAccumEx.json Result
```
GSQL > RUN QUERY set_accum_ex()
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [ {"@@intSetAccum": [ 3, 2, 1, 11, 4 ]},
  {"@@intSetAccum.contains(3)": true},
  {"@@stringSetAccum": [ "World", "There", "Hello" ]},
  {"@@stringSetAccum.contains(Hello)": true},
  {"@@stringSetAccum.size()": 3}
 ]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_bagaccum)BagAccum
The BagAccum type maintains a collection of elements with duplicated elements allowed. The output of a BagAccum is a list of elements in arbitrary order. A BagAccum instance can contain values of one type. The element type can be any base type or tuple.
For BagAccum, the `+= arg` operation adds an element or bag of elements to the bag.
BagAccum also supports the `+` operator:
  * `@bag1 + @bag2` creates a new BagAccum, which contains the elements of `@bag1` and the elements of `@bag2`. The two BagAccums must have identical data types.


BagAccum also supports the following class functions.
Functions which modify the BagAccum (mutator functions) can be used only under the following conditions:
  * Mutator functions of global accumulators may only be used at the query-body level.
  * Mutator functions of vertex-attached accumulators may only be used in a `POST-ACCUM` clause.

  
---  
Function (T is the element type) | Return type | Accessor / Mutator | Description  
---|---|---|---  
`size()` | `INT` | Accessor | Returns the number of elements in the bag.  
`contains( T value )` | `BOOL` | Accessor | Returns true/false if the bag does/doesn’t contain `value` .  
`clear()` | `VOID` | Mutator | Clears the bag so it becomes empty with size 0.  
`remove( T value )` | `VOID` | Mutator | Removes one instance of _value_ from the bag.  
`removeAll( T value )` | `VOID` | Mutator | Removes all instances of the given value from the bag.  
#### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_example_8)Example
  * Query
  * Results


BagAccum Example
```
CREATE QUERY bag_accum_ex() FOR GRAPH Minimal_Net {
  //Unordered collection
  BagAccum<INT>    @@int_bag_accum;
  BagAccum<STRING> @@string_bag_accum;
  @@int_bag_accum += 5;
  @@int_bag_accum.clear();
  @@int_bag_accum += 4;
  @@int_bag_accum += 11;
  @@int_bag_accum += 1;
  @@int_bag_accum += 11;     //Bag accums can store duplicates
  @@int_bag_accum += (1,2,3,4);
  PRINT @@int_bag_accum;
  PRINT @@int_bag_accum.size();
  PRINT @@int_bag_accum.contains(4);
  @@string_bag_accum += "Hello";
  @@string_bag_accum += "Hello";
  @@string_bag_accum += "There";
  @@string_bag_accum += "World";
  PRINT @@string_bag_accum.contains("Hello");
  @@string_bag_accum.remove("Hello");    //Remove one matching element
  @@string_bag_accum.removeAll("There"); //Remove all matching elements
  PRINT @@string_bag_accum;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
GSQL > RUN QUERY bag_accum_ex()
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [
  {"@@int_bag_accum": [
   2,
   3,
   1,
   1,
   11,
   11,
   4,
   4
  ]},
  {"@@int_bag_accum.size()": 8},
  {"@@int_bag_accum.contains(4)": true},
  {"@@string_bag_accum.contains(\"Hello\")": true},
  {"@@string_bag_accum": [
   "World",
   "Hello"
  ]}
 ]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_mapaccum)MapAccum
The MapAccum type maintains a collection of (key → value) pairs. The output of a MapAccum is a set of key and value pairs in which the keys are unique.
The key type of a MapAccum can be all base types or tuples. If the key type is `VERTEX`, then only the vertex’s ID is stored and displayed.
The value type of a MapAccum can be all base types, tuples, or any type of accumulator, except for HeapAccum.
For MapAccum, the `+= (key→val)` operation adds a key-value element to the collection if the key is not yet used in the MapAccum. If the MapAccum already contains the key, then the corresponding value is _accumulated_ to the current value, where the accumulation operation depends on the data type of the value:
  * Strings are concatenated.
  * Lists are appended.
  * Numerical values are added.
  * `DATETIME` and `ENUM` types are overwritten by the latest value.


MapAccum also supports the `+` operator, which combines two MapAccums:
  * `@map1 + @map2` creates a new MapAccum, which contains the key-value pairs of `@map2` added to the key-value pairs of `@map1`.
  * The values at the same key accumulates from the left side to the right side in the same way as in the accumulation operation.
  * You can also use the `+=` operator to combine two MapAccums. The behavior is identical.


The two MapAccums must have identical data types.
The `=` operator in MapAccum is used to **overwrite** the entire MapAccum, not just the value of a specific key. When you use the `=` operator, the entire MapAccum is cleared, and all existing key-value pairs are erased. The MapAccum is then restarted with the key-value pair provided on the right side of the = operator.
  * The `=` operator completely replaces the current MapAccum, erasing all the existing key-value pairs.
  * This operator is useful when you want to reset the MapAccum to only contain the new key-value pair and remove any prior data.


For example, consider the following case where the `=` operator is used:
```
@@int_map_accum = ("baz" -> 1);
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

In this case, the entire MapAccum is cleared, and only the `"baz" → 1` key-value pair remains. Any previous data, such as other keys like `"foo"` or `"bar"`, will be erased.
  * The = operator completely erases all existing key-value pairs in the MapAccum.
  * Unlike the `+=` operator, which accumulates values, the `=` operator resets the MapAccum with the new key-value pair, discarding all prior data.

  
---  
MapAccum also supports the following class functions.
Functions that modify the MapAccum (mutator functions) can be used only under the following conditions:
  * Mutator functions of global accumulators may only be used at the query-body level.
  * Mutator functions of vertex-attached accumulators may only be used in a `POST-ACCUM` clause.

  
---  
Function (`KEY` is the key type) | Return type | Accessor / Mutator | Description  
---|---|---|---  
`.size()` | `INT` | Accessor | Returns the number of elements in the map.  
`.containsKey( KEY key )` | `BOOL` | Accessor | Returns true if the map does contain `key` and false if it doesn’t.  
`.get( KEY key )` | _value_ type | Accessor | Returns the value which the map associates with `key`. If the map doesn’t contain key, then the return value is undefined.  
`.clear()` | `VOID` | Mutator | Clears the map so it becomes empty with size 0.  
`.remove( KEY key )` | `VOID` | Mutator | Removes the key-value pair with the specified key. If there is no matching key, then the function will do nothing.  
#### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_example_9)Example
  * Query
  * Results


MapAccum Example
```
CREATE QUERY map_accum_ex() FOR GRAPH Minimal_Net {
  // Map(Key, Value)
  // Keys can be INT or STRING only
  MapAccum<STRING, INT> @@int_map_accum;
  MapAccum<INT, STRING> @@string_map_accum;
  MapAccum<INT, MapAccum<STRING, STRING>> @@nested_map_accum;
  @@int_map_accum += ("foo" -> 1);
  @@int_map_accum.clear();
  @@int_map_accum += ("foo" -> 3);
  @@int_map_accum += ("bar" -> 2);
  @@int_map_accum += ("baz" -> 2);
  @@int_map_accum += ("baz" -> 1); //add 1 to existing value
  PRINT @@int_map_accum.containsKey("baz");
  PRINT @@int_map_accum.get("bar");
  PRINT @@int_map_accum.get("root");
  @@string_map_accum += (1 -> "apple");
  @@string_map_accum += (2 -> "pear");
  @@string_map_accum += (3 -> "banana");
  @@string_map_accum += (4 -> "a");
  @@string_map_accum += (4 -> "b"); //append "b" to existing value
  @@string_map_accum += (4 -> "c"); //append "c" to existing value
  PRINT @@int_map_accum;
  PRINT @@string_map_accum;
  //Checking and getting keys
  if @@string_map_accum.containsKey(1) THEN
    PRINT @@string_map_accum.get(1);
  END;
  //Map nesting
  @@nested_map_accum += ( 1 -> ("foo" -> "bar") );
  @@nested_map_accum += ( 1 -> ("flip" -> "top") );
  @@nested_map_accum += ( 2 -> ("fizz" -> "pop") );
  @@nested_map_accum += ( 1 -> ("foo" -> "s") );
  PRINT @@nested_map_accum;
  IF @@nested_map_accum.containsKey(1) THEN
    IF @@nested_map_accum.get(1).containsKey("foo") THEN
       PRINT @@nested_map_accum.get(1).get("foo");
    END;
  END;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
GSQL > RUN QUERY map_accum_ex()
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [
  {"@@int_map_accum.containsKey(\"baz\")": true},
  {"@@int_map_accum.get(\"bar\")": 2},
  {"@@int_map_accum.get(\"root\")": 0},
  {"@@int_map_accum": {
   "bar": 2,
   "foo": 3,
   "baz": 3
  }},
  {"@@string_map_accum": {
   "1": "apple",
   "2": "pear",
   "3": "banana",
   "4": "abc"
  }},
  {"@@string_map_accum.get(1)": "apple"},
  {"@@nested_map_accum": {
   "1": {
    "foo": "bars",
    "flip": "top"
   },
   "2": {"fizz": "pop"}
  }},
  {"@@nested_map_accum.get(1).get(\"foo\")": "bars"}
 ]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_arrayaccum)ArrayAccum
The ArrayAccum type maintains an array of accumulators. An array is a fixed-length sequence of elements, with direct access to elements by position. The ArrayAccum has these particular characteristics:
  * The elements are accumulators, not primitive or base data types. All accumulators, except HeapAccum, MapAccum, and GroupByAccum, can be used.
  * An ArrayAccum instance can be multidimensional. There is no limit to the number of dimensions.
  * The size can be set at run-time (dynamically).
  * There are operators which update the entire array efficiently.


When an ArrayAccum is declared, the instance name should be followed by a pair of brackets for each dimension. The brackets may either contain an integer constant to set the size of the array, or they may be empty. In that case, the size must be set with the reallocate function before the ArrayAccum can be used.
ArrayAccum declaration example
```
ArrayAccum<SetAccum<STRING>> @@names[10];
ArrayAccum<SetAccum<INT>> @@ids[][]; // 2-dimensional, size to be determined
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Because each element of an ArrayAccum itself is an accumulator, the operators =, +=, and + can be used in two contexts: accumulator-level and element-level.
#### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_element_level_operations)**Element-level operations**
If @A is an ArrayAccum of length 6, then @A[0] and @A[5] refer to its first and last elements, respectively. Referring to an ArrayAccum element is like referring to an accumulator of that type. For example, given the following definitions:
```
ArrayAccum<SumAccum<INT>> @@Sums[3];
ArrayAccum<ListAccum<STRING>> @@Lists[2];
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

then @@Sums[0], @@Sums[1], and @@Sums[2] each refer to an individual SumAccum<INT>, and @@Lists[0] and @@Lists[1] each refer to a ListAccum<STRING>, supporting all the operations for those accumulator and data types.
```
@@Sums[1] = 1;
@@Sums[1] += 2; // value is now 3
@@Lists[0] = "cat";
@@Lists[0] += "egory"; // value is now "category"
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_accumulator_level_operations)Accumulator-level operations
The operators =, +=, and + have special meanings when applied to an ArrayAccum as a whole. There operations efficiently update an entire ArrayAccum. All ArrayAccums must have the same element type.
Operator | Description | Example  
---|---|---  
= | Sets the ArrayAccum on the left equal to the ArrayAccum on the right. The two ArrayAccums must have the same element type, but the left-side ArrayAccum will change its size and dimensions to match the one on the right side. | @A = @B;  
+ | Performs element-by-element addition of two ArrayAccums of the same type and size. The result is a new ArrayAccum of the same size. | @C = @A + @B; // @A and @B must be the same size  
+= | Performs element-by-element accumulation (+=) from the right-side ArrayAccum to the left-side ArrayAccum. They must be the same type and size. | @A += @B; // @A and @B must be the same size  
ArrayAccum also supports the following class functions.
Functions that modify the ArrayAccum (mutator functions) can be used only under the following conditions:
  * Mutator functions of global accumulators may only be used at the query-body level.
  * Mutator functions of vertex-attached accumulators may only be used in a `POST-ACCUM` clause.

  
---  
Function | Return type | Accessor / Mutator | Description  
---|---|---|---  
`size()` | INT | Accessor | Returns the total number of elements in the (multidimensional) array. For example, the size of an ArrayAccum declared as @A[3][4] is 12.  
`reallocate( INT, …​ )` | VOID | Mutator | Discards the previous ArrayAccum instance and creates a new ArrayAccum, with the size(s) given. An N-dimensional ArrayAccum requires N integer parameters. The reallocate function cannot be used to change the number of dimensions.  
#### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_example_10)Example
  * Query
  * Results


Example of ArrayAccum Element-level Operations
```
CREATE QUERY array_accum_elem() FOR GRAPH Minimal_Net {
	ArrayAccum<SumAccum<DOUBLE>> @@aa_sumD[2][2]; // 2D Sum Double
	ArrayAccum<SumAccum<STRING>> @@aa_sumS[2][2]; // 2D Sum String
	ArrayAccum<MaxAccum<INT>> @@aa_max[2];
	ArrayAccum<MinAccum<UINT>> @@aa_min[2];
	ArrayAccum<AvgAccum> @@aa_avg[2];
	ArrayAccum<AndAccum<BOOL>> @@aa_and[2];
	ArrayAccum<OrAccum<BOOL>> @@aa_or[2];
	ArrayAccum<BitwiseAndAccum> @@aa_bit_and[2];
	ArrayAccum<BitwiseOrAccum> @@aa_bit_or[2];
	ArrayAccum<ListAccum<INT>> @@aa_list[2][2];  // 2D List
	ArrayAccum<SetAccum<FLOAT>> @@aa_setF[2];
	ArrayAccum<BagAccum<DATETIME>> @@aa_bagT[2];
	// for test data
	ListAccum<STRING> @@words;
	BOOL toggle = false;
	@@words += "1st"; @@words += "2nd"; @@words += "3rd"; @@words += "4th";
	// Int: a[0] += 1, 2;  a[1] += 3, 4
	// Bool: alternate true/false
	// Float: a[0] += 1.111, 2.222; a[1] += 3.333, 4.444
	// 2D Double: a[0][0] += 1.111, 2.222;  a[0][1] += 5.555, 6.666;
	//     a[1][0] += 3.333, 4.444;  a[0][1] += 7.777, 8.888;
	FOREACH i IN RANGE [0,1] DO
		FOREACH n IN RANGE [1, 2] DO
			toggle = NOT toggle;
			@@aa_max[i] += i*2 + n;
			@@aa_min[i] += i*2 + n;
			@@aa_avg[i] += i*2 + n;
			@@aa_and[i] += toggle;
			@@aa_or[i] += toggle;
			@@aa_bit_and[i] += i*2 + n;
			@@aa_bit_or[i] += i*2 + n;
			@@aa_setF[i] += (i*2 + n)/0.9;
			@@aa_bagT[i] += epoch_to_datetime(i*2 + n);
			FOREACH j IN RANGE [0,1] DO
				@@aa_sumD[i][j] += (j*4 + i*2 + n)/0.9;
				@@aa_sumS[i][j] += @@words.get((j*2 + i + n)%4);
				@@aa_list[i][j] += j*4 +i*2 + n ;
			END;
		END;
	END;
	PRINT @@aa_sumD;		PRINT @@aa_sumS;
	PRINT @@aa_max;		PRINT @@aa_min;		PRINT @@aa_avg;
	PRINT @@aa_and;		PRINT @@aa_or;
	PRINT @@aa_bit_and;	PRINT @@aa_bit_or;
	PRINT @@aa_list;		PRINT @@aa_setF;		PRINT @@aa_bagT;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
GSQL > RUN QUERY array_accum_elem()
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [
  {"@@aa_sumD": [
   [
    3.33333,
    12.22222
   ],
   [
    7.77778,
    16.66667
   ]
  ]},
  {"@@aa_sumS": [
   [
    "2nd3rd",
    "4th1st"
   ],
   [
    "3rd4th",
    "1st2nd"
   ]
  ]},
  {"@@aa_max": [
   2,
   4
  ]},
  {"@@aa_min": [
   1,
   3
  ]},
  {"@@aa_avg": [
   1.5,
   3.5
  ]},
  {"@@aa_and": [
   false,
   false
  ]},
  {"@@aa_or": [
   true,
   true
  ]},
  {"@@aa_bit_and": [
   "0000000000000000000000000000000000000000000000000000000000000000",
   "0000000000000000000000000000000000000000000000000000000000000000"
  ]},
  {"@@aa_bit_or": [
   "0000000000000000000000000000000000000000000000000000000000000011",
   "0000000000000000000000000000000000000000000000000000000000000111"
  ]},
  {"@@aa_list": [
   [
    [
     1,
     2
    ],
    [
     5,
     6
    ]
   ],
   [
    [
     3,
     4
    ],
    [
     7,
     8
    ]
   ]
  ]},
  {"@@aa_setF": [
   [
    2.22222,
    1.11111
   ],
   [
    4.44444,
    3.33333
   ]
  ]},
  {"@@aa_bagT": [
   [
    2,
    1
   ],
   [
    4,
    3
   ]
  ]}
 ]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * Query
  * Results


```
CREATE QUERY array_accum_op3(INT lenA) FOR GRAPH Minimal_Net {
	ArrayAccum<SumAccum<INT>> @@arrayA[5]; // Original size
	ArrayAccum<SumAccum<INT>> @@arrayB[2];
	ArrayAccum<SumAccum<INT>> @@arrayC[][]; // No size
	STRING msg;
	@@arrayA.reallocate(lenA); // Set/Change size dynamically
	@@arrayB.reallocate(lenA+1);
	@@arrayC.reallocate(lenA, lenA+1);
	// Initialize arrays
	FOREACH i IN RANGE[0,lenA-1] DO
		@@arrayA[i] += i*i;
		FOREACH j IN RANGE[0,lenA] DO
			@@arrayC[i][j] += j*10 + i;
		END;
	END;
	FOREACH i IN RANGE[0,lenA] DO
		@@arrayB[i] += 100-i;
	END;
	msg = "Initial Values";
	PRINT msg, @@arrayA, @@arrayB, @@arrayC;
  msg = "Test 1: A = C, C = B";	// = operator
  @@arrayA = @@arrayC;		// change dimensions: 1D <- 2D
  @@arrayC = @@arrayB;		// change dimensions: 2D <- 1D
  PRINT msg, @@arrayA, @@arrayC;
  msg = "Test 2: B += C"; 		// += operator
  @@arrayB += @@arrayC; 		// B and C must have same size & dim
  PRINT msg, @@arrayB, @@arrayC;
  msg = "Test 3: A = B + C"; 		// + operator
  @@arrayA = @@arrayB + @@arrayC; // B & C must have same size & dim
  PRINT msg, @@arrayA; 			// A changes size & dim
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
RUN QUERY ArrayAccumOp3(3)
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
   "msg": "Initial Values",
   "@@arrayC": [
    [
     0,
     10,
     20,
     30
    ],
    [
     1,
     11,
     21,
     31
    ],
    [
     2,
     12,
     22,
     32
    ]
   ],
   "@@arrayB": [
    100,
    99,
    98,
    97
   ],
   "@@arrayA": [
    0,
    1,
    4
   ]
  },
  {
   "msg": "Test 1: A = C, C = B",
   "@@arrayC": [
    100,
    99,
    98,
    97
   ],
   "@@arrayA": [
    [
     0,
     10,
     20,
     30
    ],
    [
     1,
     11,
     21,
     31
    ],
    [
     2,
     12,
     22,
     32
    ]
   ]
  },
  {
   "msg": "Test 2: B += C",
   "@@arrayC": [
    100,
    99,
    98,
    97
   ],
   "@@arrayB": [
    200,
    198,
    196,
    194
   ]
  },
  {
   "msg": "Test 3: A = B + C",
   "@@arrayA": [
    300,
    297,
    294,
    291
   ]
  }
 ]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * Query
  * Results


```
CREATE QUERY array_accum_local() FOR GRAPH Social_Net API("v2") {
	// Count each person's edges by type
	// friend/liked/posted edges are type 0/1/2, respectively
	ArrayAccum<SumAccum<INT>> @edges_by_type[3];
	persons = {Person.*};
	persons = SELECT s
		FROM persons:s -(:e)- :t
		ACCUM CASE e.type
			WHEN "Friend" THEN s.@edges_by_type[0] += 1
			WHEN "Liked" THEN s.@edges_by_type[1] += 1
			WHEN "Posted" THEN s.@edges_by_type[2] += 1
			END
		ORDER BY s.id;
	//PRINT persons.@edges_by_type; // api v1
  PRINT persons[persons.@edges_by_type]; // api v2
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
GSQL > RUN QUERY array_accum_local()
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
   "v_id": "person1",
   "attributes": {"Persons.@edgesByType": [ 2, 1, 1 ]},
   "v_type": "person"
  },
  {
   "v_id": "person2",
   "attributes": {"Persons.@edgesByType": [ 2, 2, 1 ]},
   "v_type": "person"
  },
  {
   "v_id": "person3",
   "attributes": {"Persons.@edgesByType": [ 2, 1, 1 ]},
   "v_type": "person"
  },
  {
   "v_id": "person4",
   "attributes": {"Persons.@edgesByType": [ 3, 1, 1 ]},
   "v_type": "person"
  },
  {
   "v_id": "person5",
   "attributes": {"Persons.@edgesByType": [ 2, 1, 2 ]},
   "v_type": "person"
  },
  {
   "v_id": "person6",
   "attributes": {"Persons.@edgesByType": [ 2, 1, 2 ]},
   "v_type": "person"
  },
  {
   "v_id": "person7",
   "attributes": {"Persons.@edgesByType": [ 2, 1, 2 ]},
   "v_type": "person"
  },
  {
   "v_id": "person8",
   "attributes": {"Persons.@edgesByType": [ 3, 1, 2 ]},
   "v_type": "person"
  }
 ]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_heapaccum)HeapAccum
The HeapAccum type maintains a sorted collection of tuples and enforces a maximum number of tuples in the collection. The output of a HeapAccum is a sorted collection of tuple elements. The `=` operation adds a tuple to the collection in sorted order. If the HeapAccum is already at maximum capacity when the `=` operator is applied, then the tuple which is last in the sorted order is dropped from the HeapAccum. Sorting of tuples is performed on one or more defined tuple fields ordered either ascending or descending. Sorting precedence is performed based on defined tuple fields from left to right.
You must have defined a custom [tuple type](https://docs.tigergraph.com/gsql-ref/3.9/querying/data-types#_tuple) to declare a `HeapAccum`, and one of the fields in the tuple must be a data type that can be sorted.
The declaration syntax is outlined in the figure below:
HeapAccum declaration syntax
```
HeapAccum<tupleType>( [capacity,] field_a [ASC|DESC],... , field_z [ASC|DESC]);
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

In the declaration of the `HeapAccum`, the keyword `HeapAccum` is followed by the tuple type in angle brackets `< >`. This is followed by a parenthesized list of two or more parameters.
  * If the first parameter is a positive integer, it sets the maximum number of tuples that the HeapAccum may store.
  * The subsequent parameters are a subset of the tuple’s field, which are used as sort keys. The sort key hierarchy is from left to right, with the leftmost key being the primary sort key. The keywords `ASC` and `DESC` indicate Ascending (lowest value first) or Descending (highest value first) sort order. Ascending order is the default.


HeapAccum supports comparison with the `==` and the `!=` operators. Comparison (and assignment with the `+=` operator) is only possible if two HeapAccums hold the same types of tuple and have the same sort order and direction.
HeapAccum capacity does not affect comparison. Only the actual contents of are evaluated during comparison.
#### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_functions_2)Functions
HeapAccum also supports the following class functions.
Functions that modify the `HeapAccum` (mutator functions) can be used only under the following conditions:
  * Mutator functions of global accumulators may only be used at the query-body level.
  * Mutator functions of vertex-attached accumulators may only be used in a `POST-ACCUM` clause.

  
---  
Function | Return type | Accessor / Mutator | Description  
---|---|---|---  
`size()` | `INT` | Accessor | Returns the number of elements in the heap.  
`top()` | `tupleType` | Accessor | Returns the top tuple. If this heap is empty, returns a tuple with each element equal to the default value.  
`pop()` | `tupleType` | Mutator | Returns the top tuple and removes it from the heap. If this heap is empty, returns a tuple with each element equal to the default value.  
`resize( INT newSize)` | `VOID` | Mutator | Changes the maximum capacity of the heap.  
`clear()` | `VOID` | Mutator | Clears the heap so it becomes empty with size 0.  
#### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_example_11)Example
  * Query
  * Results


```
CREATE QUERY heap_accum_ex() FOR GRAPH Minimal_Net {
  TYPEDEF tuple<STRING first_name, STRING last_name, INT score> Test_Results;
  //Heap with max size of 4 sorted descending by score then ascending last name
  HeapAccum<Test_Results>(4, score DESC, last_name ASC) @@top_test_results;
  PRINT @@top_test_results.top();
  @@top_test_results += Test_Results("Bruce", "Wayne", 80);
  @@top_test_results += Test_Results("Peter", "Parker", 80);
  @@top_test_results += Test_Results("Tony", "Stark", 100);
  @@top_test_results += Test_Results("Bruce", "Banner", 95);
  @@top_test_results += Test_Results("Jean", "Summers", 95);
  @@top_test_results += Test_Results("Clark", "Kent", 80);
  //Show element with the highest sorted position
  PRINT @@top_test_results.top();
  PRINT @@top_test_results.top().first_name, @@top_test_results.top().last_name, @@top_test_results.top().score;
  PRINT @@top_test_results;
  //Increase the size of the heap to add more elements
  @@top_test_results.resize(5);
  //Find the size of the current heap
  PRINT @@top_test_results.size();
  @@top_test_results += Test_Results("Bruce", "Wayne", 80);
  @@top_test_results += Test_Results("Peter", "Parker", 80);
  PRINT @@top_test_results;
  //Resizing smaller WILL REMOVE excess elements from the HeapAccum
  @@top_test_results.resize(3);
  PRINT @@top_test_results;
  //Increasing capacity will not restore dropped elements
  @@top_test_results.resize(5);
  PRINT @@top_test_results;
  //Removes all elements from the Heap_accum
  @@top_test_results.clear();
  PRINT @@top_test_results.size();
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
GSQL > RUN QUERY heap_accum_ex()
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [
  {"@@top_test_results.top()": {
   "score": 0,
   "last_name": "",
   "first_name": ""
  }},
  {"@@top_test_results.top()": {
   "score": 100,
   "last_name": "Stark",
   "first_name": "Tony"
  }},
  {
   "@@top_test_results.top().first_name": "Tony",
   "@@top_test_results.top().last_name": "Stark",
   "@@top_test_results.top().score": 100
  },
  {"@@top_test_results": [
   {
    "score": 100,
    "last_name": "Stark",
    "first_name": "Tony"
   },
   {
    "score": 95,
    "last_name": "Banner",
    "first_name": "Bruce"
   },
   {
    "score": 95,
    "last_name": "Summers",
    "first_name": "Jean"
   },
   {
    "score": 80,
    "last_name": "Kent",
    "first_name": "Clark"
   }
  ]},
  {"@@top_test_results.size()": 4},
  {"@@top_test_results": [
   {
    "score": 100,
    "last_name": "Stark",
    "first_name": "Tony"
   },
   {
    "score": 95,
    "last_name": "Banner",
    "first_name": "Bruce"
   },
   {
    "score": 95,
    "last_name": "Summers",
    "first_name": "Jean"
   },
   {
    "score": 80,
    "last_name": "Kent",
    "first_name": "Clark"
   },
   {
    "score": 80,
    "last_name": "Parker",
    "first_name": "Peter"
   }
  ]},
  {"@@top_test_results": [
   {
    "score": 100,
    "last_name": "Stark",
    "first_name": "Tony"
   },
   {
    "score": 95,
    "last_name": "Banner",
    "first_name": "Bruce"
   },
   {
    "score": 95,
    "last_name": "Summers",
    "first_name": "Jean"
   }
  ]},
  {"@@top_test_results": [
   {
    "score": 100,
    "last_name": "Stark",
    "first_name": "Tony"
   },
   {
    "score": 95,
    "last_name": "Banner",
    "first_name": "Bruce"
   },
   {
    "score": 95,
    "last_name": "Summers",
    "first_name": "Jean"
   }
  ]},
  {"@@top_test_results.size()": 0}
 ]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_groupbyaccum)GroupByAccum
The GroupByAccum is a compound accumulator, an accumulator of accumulators. At the top level, it is a MapAccum where both the key and the value can have multiple fields, each of them an accumulator type.
GroupByAccum syntax
```
GroupByAccum<type [, type]* , accumType [, accumType]* >
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

In the EBNF above, the **type** terms form the key set, and the **accumType** terms form the map’s value. Since they are accumulators, they perform a grouping. Like a MapAccum, if we try to store a (key→value) whose key has already been used, then the new value will accumulate to the data which is already stored. In this case, each field of the multiple-field value has its own accumulation function. One way to think about GroupByAccum is that each unique key is a group ID.
In GroupByAccum, the key types can be base type or tuple. The accumulators are used for aggregating group values. Each accumulator type can be any type including HeapAccum. Each base type and each accumulator type must be followed an alias. Below is an example declaration.
```
TYPEDEF TUPLE <id INT, name STRING, age INT> My_Tuple;
TYPEDEF HeapAccum <My_Tuple> (2, name desc, age desc, id asc) My_Heap;
GroupByAccum<INT a, STRING b,
       MaxAccum<INT> maxa,
       ListAccum<ListAccum<INT>> lists,
       My_Heap h> @@group;
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

To add new data to this GroupByAccum, the data should be formatted as **(key1, key2 → value1, value2)** .
GroupByAccum also supports the following class functions.
Functions that modify the GroupByAccum (mutator functions) can be used only under the following conditions:
  * Mutator functions of global accumulators may only be used at the query-body level.
  * Mutator functions of vertex-attached accumulators may only be used in a `POST-ACCUM` clause.

  
---  
Function (`KEY1..KEYn` are the key types) | Return type | Accessor / Mutator | Description  
---|---|---|---  
`size()` | `INT` | Accessor | Returns the number of elements in the heap.  
`get( KEY1 _key_value1_ , KEY2 _key_value2_ …​ )`|  element type(s) of the accumulator(s) | Accessor | Returns the values from each accumulator in the group associating with the given key(s). If the key(s) doesn’t exist, return the default value(s) of the accumulator type(s).  
`containsKey( KEY1 _key_value1_ , KEY2 _key_value2_…​ )`| `BOOL` | Accessor | Returns true/false if the accumulator contains the key(s)  
`clear()` | `VOID` | Mutator | Clears the heap so it becomes empty with size 0.  
`remove ( KEY1 _key_value1_ , KEY2 _key_value2_ …​ )`|  VOID | Mutator | Removes the group associating with the key(s)  
#### [](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_example_12)Example
  * Query
  * Results


GroupByAccum Example
```
CREATE QUERY group_by_accum_ex () FOR GRAPH Social_Net {
  // declare HeapAccum type and tuple used in the HeapAccum
  TYPEDEF TUPLE <id INT, name STRING, age INT> My_Tuple;
  TYPEDEF HeapAccum <My_Tuple> (2, name DESC, age DESC, id asc) My_Heap;
  // declaration, first two primitive type are group by keys; the rest accumulator type are aggregates
  GroupByAccum<INT a, STRING b, MaxAccum<INT> maxa, ListAccum<ListAccum<INT>> lists> @@group;
  GroupByAccum<STRING gender, MapAccum<VERTEX<Person>, DATETIME> m> @@group2;
  GroupByAccum<INT age, My_Heap h> @@group4;
  // nested GroupByAccum
  GroupByAccum<INT a, MaxAccum<INT> maxa, GroupByAccum<INT a, MaxAccum<INT> maxa> heap> @@group3;
  Start = { Person.* };
  // usage of global GroupByAccum
  @@group += (1, "a" -> 1, [1]);
  @@group += (1, "a" -> 2, [2]);
  @@group += (2, "b" -> 1, [4]);
  @@group3 += (2 -> 1, (2 -> 0) );
  @@group3 += (2 -> 1, (2 -> 5) );
  @@group3 += (2 -> 5, (3 -> 3) );
  PRINT @@group, @@group.get(1, "a"), @@group.get(1, "a").lists, @@group.containsKey(1, "c"), @@group3;
  // HeapAccum inside GroupByAccum
  @@group4 += (29->My_Tuple(1,"aaa", 18));
  @@group4 += (29->My_Tuple(2,"bbb", 19));
  @@group4 += (29->My_Tuple(3,"ccc", 20));
  PRINT @@group4;
  // two kinds of foreach
  FOREACH g IN @@group DO
    PRINT g.a, g.b, g.maxa, g.lists;
  END;
  FOREACH (g1,g2,g3,g4) IN @@group DO
    PRINT g1,g2,g3,g4;
  END;
  S = SELECT v
   FROM Start:v - (Liked:e) - Post:t
   ACCUM @@group2 += (v.gender -> (v -> e.action_time));
  PRINT @@group2, @@group2.get("Male").m, @@group2.get("Female").m;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
GSQL > RUN QUERY group_by_accum_ex()
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
   "@@group.get(1,a).lists": [
    [1],
    [2]
   ],
   "@@group3": [{
    "a": 2,
    "heap": [
     {
      "a": 3,
      "maxa": 3
     },
     {
      "a": 2,
      "maxa": 5
     }
    ],
    "maxa": 5
   }],
   "@@group.containsKey(1,c)": false,
   "@@group.get(1,a)": {
    "lists": [
     [1],
     [2]
    ],
    "maxa": 2
   },
   "@@group": [
    {
     "a": 2,
     "b": "b",
     "lists": [[4]],
     "maxa": 1
    },
    {
     "a": 1,
     "b": "a",
     "lists": [
      [1],
      [2]
     ],
     "maxa": 2
    }
   ]
  },
  {
   "g.b": "b",
   "g.maxa": 1,
   "g.lists": [[4]],
   "g.a": 2
  },
  {
   "g.b": "a",
   "g.maxa": 2,
   "g.lists": [
    [1],
    [2]
   ],
   "g.a": 1
  },
  {
   "g1": 2,
   "g2": "b",
   "g3": 1,
   "g4": [[4]]
  },
  {
   "g1": 1,
   "g2": "a",
   "g3": 2,
   "g4": [
    [1],
    [2]
   ]
  },
  {
   "@@group2.get(Male).m": {
    "person3": 1263618953,
    "person1": 1263209520,
    "person8": 1263180365,
    "person7": 1263295325,
    "person6": 1263468185
   },
   "@@group2": [
    {
     "gender": "Male",
     "m": {
      "person3": 1263618953,
      "person1": 1263209520,
      "person8": 1263180365,
      "person7": 1263295325,
      "person6": 1263468185
     }
    },
    {
     "gender": "Female",
     "m": {
      "person4": 1263352565,
      "person2": 2526519281,
      "person5": 1263330725
     }
    }
   ],
   "@@group2.get(Female).m": {
    "person4": 1263352565,
    "person2": 2526519281,
    "person5": 1263330725
   }
  }
 ]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_nested_accumulators)Nested Accumulators
Certain collection accumulators may be nested. That is, an accumulator may contain a collection of elements where the elements themselves are accumulators. For example:
```
ListAccum<ListAccum<INT>> @@matrix; // a 2-dimensional jagged array of integers. Each inner list has its own unique size.
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Only ListAccum, ArrayAccum, MapAccum, and GroupByAccum can contain other accumulators. However, not all combinations of collection accumulators are allowed. The following constraints apply:
  1. ListAccum: ListAccum is the only accumulator type that can be nested within ListAccum:
```
ListAccum<ListAccum<INT>>
ListAccum<ListAccum<ListAccum<INT>>>
ListAccum<SetAccum<INT>> // illegal
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  2. MapAccum: All accumulator types, except for HeapAccum, can be nested within MapAccum as the value type. For example,
```
MapAccum<STRING, ListAccum<INT>>
MapAccum<INT, MapAccum<INT, STRING>>
MapAccum<VERTEX, SumAccum<INT>>
MapAccum<STRING, SetAccum<VERTEX>>
MapAccum<STRING, GroupByAccum<VERTEX a, MaxAccum<INT> maxs>>
MapAccum<SetAccum<INT>, INT> # illegal
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  3. GroupByAccum: All accumulator types can be nested within GroupByAccum as the accumulator type. For example:
```
GroupByAccum<INT a, STRING b, MaxAccum<INT> maxs, ListAccum<ListAccum<INT>> lists>
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  4. ArrayAccum: Unlike the other accumulators in this list, where nesting is optional, nesting is mandatory for ArrayAccum. See the [ArrayAccum](https://docs.tigergraph.com/gsql-ref/3.9/querying/accumulators#_arrayaccum) section.


It is legal to define nested ListAccums to form a multidimensional array. Note the declaration statements and the nested [ bracket ] notation in the example below:
  * Query
  * Results


```
CREATE QUERY nested_accum_ex() FOR GRAPH Minimal_Net {
  ListAccum<ListAccum<INT>> @@_2d_list;
  ListAccum<ListAccum<ListAccum<INT>>> @@_3d_list;
  ListAccum<INT> @@_1d_list;
  SumAccum <INT> @@sum = 4;
  @@_1d_list += 1;
  @@_1d_list += 2;
  // add 1D-list to 2D-list as element
  @@_2d_list += @@_1d_list;
  // add 1D-enum-list to 2D-list as element
  @@_2d_list += [@@sum, 5, 6];
  // combine 2D-enum-list and 2d-list
  @@_2d_list += [[7, 8, 9], [10, 11], [12]];
  // add an empty 1D-list
  @@_1d_list.clear();
  @@_2d_list += @@_1d_list;
  // combine two 2D-list
  @@_2d_list += @@_2d_list;
  PRINT @@_2d_list;
  // test 3D-list
  @@_3d_list += @@_2d_list;
  @@_3d_list += [[7, 8, 9], [10, 11], [12]];
  PRINT @@_3d_list;
}
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
GSQL > RUN QUERY nested_accum_ex()
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [
  {"@@_2d_list": [
   [
    1,
    2
   ],
   [
    4,
    5,
    6
   ],
   [
    7,
    8,
    9
   ],
   [
    10,
    11
   ],
   [12],
   [],
   [
    1,
    2
   ],
   [
    4,
    5,
    6
   ],
   [
    7,
    8,
    9
   ],
   [
    10,
    11
   ],
   [12],
   []
  ]},
  {"@@_3d_list": [
   [
    [
     1,
     2
    ],
    [
     4,
     5,
     6
    ],
    [
     7,
     8,
     9
    ],
    [
     10,
     11
    ],
    [12],
    [],
    [
     1,
     2
    ],
    [
     4,
     5,
     6
    ],
    [
     7,
     8,
     9
    ],
    [
     10,
     11
    ],
    [12],
    []
   ],
   [
    [
     7,
     8,
     9
    ],
    [
     10,
     11
    ],
    [12]
   ]
  ]}
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


