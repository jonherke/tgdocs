![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/per-clause)[Next](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/per-clause)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/per-clause)
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
[Resources](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/per-clause)
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
  * [Per Clause (Beta)](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/per-clause)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/4.1/modules/tutorials/pages/pattern-matching/adv/per-clause.adoc)
### Contents
  * [Introduction](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/per-clause#_introduction)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/per-clause#_syntax)
  * [Semantics](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/per-clause#_semantics)
  * [PER Clause Examples](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/per-clause#_per_clause_examples)
  * [Performance and Best Practices](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/per-clause#_performance_and_best_practices)
  * [Use PER (target) If Possible](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/per-clause#_use_per_target_if_possible)
  * [Write Patterns with Smallest Expected Vertex Set on the Left](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/per-clause#_write_patterns_with_smallest_expected_vertex_set_on_the_left)
  * [Specify Complete Type Information](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/per-clause#_specify_complete_type_information)
  * [LDBC Benchmark Queries](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/per-clause#_ldbc_benchmark_queries)


# Per Clause (Beta)
### Contents
  * [Introduction](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/per-clause#_introduction)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/per-clause#_syntax)
  * [Semantics](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/per-clause#_semantics)
  * [PER Clause Examples](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/per-clause#_per_clause_examples)
  * [Performance and Best Practices](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/per-clause#_performance_and_best_practices)
  * [Use PER (target) If Possible](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/per-clause#_use_per_target_if_possible)
  * [Write Patterns with Smallest Expected Vertex Set on the Left](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/per-clause#_write_patterns_with_smallest_expected_vertex_set_on_the_left)
  * [Specify Complete Type Information](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/per-clause#_specify_complete_type_information)
  * [LDBC Benchmark Queries](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/per-clause#_ldbc_benchmark_queries)


## [](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/per-clause#_introduction)Introduction
Pattern matching produces a virtual match table, and the ACCUM clause acts like a FOREACH loop, executing the clause’s statement once for each row of the match table.
Patterns are paths in the graphs, and each row in the match table is a distinct path. However, paths may share some vertices or edges. Some applications do not want to do aggregations per path. Instead, they want to execute the ACCUM clause per distinct group of vertex aliases.
For example, consider the following query which counts the number of paths in a simple 2-hop pattern:
```
SumAccum<int> @@cnt;
S = SELECT t
  FROM S:s - (E1:edge1) - M:m -(E2:edge2) - T:t
  ACCUM @@cnt += 1;
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Suppose the query produces the following match table.
```
(s, edge1, m , edge2, t)//match table schema
v1, e1, v3, e2, v2 //match 1
v1, e3, v4, e4, v2 //match 2
v5, e5, v6, e6, v7 //match 3
v8, e7, v9, e8, v7 //match 4
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

By default, the ACCUM clause will execute the `@@cnt += 1`statement 4 times, for each row in the match table. The result will be `@@cnt = 4`.
For the same query, what if the user wants to
  * count the number of distinct path endings in the match table? For this case, we would want to iterate on the alias `t`.
  * count the number of distinct (start, end) pairs in the match table? For that case, we would want to iterate on distinct pairs of the aliases `(s, t)`.


To provide users with this added flexibility and finer control over ACCUM iteration, TigerGraph 3.0 adds the PER clause to pattern matching (V2) syntax.
## [](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/per-clause#_syntax)Syntax
The PER Clause is an optional clause that comes at the start of the ACCUM clause in a SELECT statement. As illustrated below, it starts with the keyword PER, and followed by a pair of parenthesis, in which user can put one or more distinct vertex aliases found in the FROM pattern.
```
selectBlock := SELECT alias
        FROM pattern
        [sampleClause]
        [whereClause]
        [[perClause] accumClause]
        [postAccumClause]*
        [havingClause]
        [orderClause]
        [limitClause]
perClause := PER (vertex_alias_1, vertex_alias_2, ...)
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**Examples**. Below are multiple examples of the PER Clause using the same FROM clause.
```
S1 = SELECT s
   FROM S:s - (E1:edge1) - M:m - (E2:edge2) - T:t
   PER (s)
   ACCUM @@cnt += 1;
S2 = SELECT t
   FROM S:s - (E1:edge1) - M:m - (E2:edge2) - T:t
   PER (t)
   ACCUM @@cnt += 1;
S3 = SELECT m
   FROM S:s - (E1:edge1) - M:m - (E2:edge2) - T:t
   PER (m)
   ACCUM @@cnt += 1;
S4 = SELECT t
   FROM S:s - (E1:edge1) - M:m - (E2:edge2) - T:t
   PER (s, t)
   ACCUM @@cnt += 1;
S5 = SELECT t
   FROM S:s - (E1:edge1) - M:m - (E2:edge2) - T:t
   PER (s, m, t)
   ACCUM @@cnt += 1;
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/per-clause#_semantics)Semantics
The PER Clause specifies a list of vertex aliases, which are used to group the rows in the match table, one group per distinct value of the alias or of the alias list. If there are N distinct groups, we will execute the ACCUM clause N times, once per distinct vertex aliases' binding. Note that the PER clause has no effect on POST-ACCUM clauses semantic, except confining the POST-ACCUM vertex alias.
Suppose s, m, and t are vertex aliases in a pattern. Below are some interpretations of the PER Clause based on the graph element bindings found in the match table.
  * `PER (s) ACCUM` means that per each distinct s vertex, execute the ACCUM clause once.
  * `PER (s,t) ACCUM` means that per each distinct (s, t) pair, execute the ACCUM clause once.
  * `PER (s,m,t) ACCUM` means that per each distinct (s, m, t) tuple, execute the ACCUM clause once.


Examples to show PER clause semantics.
```
//match table
(s, edge1, m , edge2, t)//schema
v1, e1, v3, e2, v2 //match 1
v1, e3, v4, e4, v2 //match 2
v5, e5, v6, e6, v7 //match 3
v8, e7, v9, e8, v7 //match 4
//since we have v1, v5, and v8 three distinct vertices bind to s,
//we execute ACCUM clause 3 times.
S1 = SELECT s
   FROM S:s - (E1:edge1) - M:m -(E2:edge2) - T:t
   PER (s)
   ACCUM @@cnt += 1;
//since we have v2, v7 two distinct vertices bind to t,
//we execute ACCUM clause twice.
S2 = SELECT t
   FROM S:s - (E1:edge1) - M:m -(E2:edge2) - T:t
   PER (t)
   ACCUM @@cnt += 1;
//since we have v3, v4, v6, v9 four distinct vertices bind to m,
//we execute ACCUM clause 4 times.
S3 = SELECT m
   FROM S:s - (E1:edge1) - M:m -(E2:edge2) - T:t
   PER (m)
   ACCUM @@cnt += 1;
//since we have (v1, v2), (v5, v7) and (v8, v7) three distinct vertex pairs
//bind to (s,t), we execute ACCUM clause 3 times.
S4 = SELECT t
   FROM S:s - (E1:edge1) - M:m -(E2:edge2) - T:t
   PER (s, t)
   ACCUM @@cnt += 1;

//since we have (v1, v3, v2), (v1, v4, v2), (v5, v6, v7) and (v8, v9, v7) four
//distinct vertex groups bind to (s,m,t), we execute ACCUM clause 4 times.
S5 = SELECT t
   FROM S:s - (E1:edge1) - M:m -(E2:edge2) - T:t
   PER (s, m, t)
   ACCUM @@cnt += 1;
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

If the PER Clause is used in a SELECT query block, then the vertex aliases used in the SELECT, ACCUM , and POST-ACCUM clauses must be confined to the aliases that appear in the PER clause.  
---  
Below are some illegal cases.
```
//semantic error. SELECT t, but t doesn't appear in PER clause.
S1 = SELECT t
   FROM S:s - (E1:edge1) - M:m -(E2:edge2) - T:t
   PER (s, m)
   ACCUM @@cnt += 1;
//semantic error. ACCUM t.@cnt, but t doesn't appear in PER clause.
S2 = SELECT t
   FROM S:s - (E1:edge1) - M:m -(E2:edge2) - T:t
   PER (s, m)
   ACCUM t.@cnt += 1;
//semantic error. POST-ACCUM t.@cnt, but t doesn't appear in PER clause.
S3 = SELECT s
   FROM S:s - (E1:edge1) - M:m -(E2:edge2) - T:t
   PER (s)
   ACCUM s.@cnt += 1
   POST-ACCUM t.@cnt =1;
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/per-clause#_per_clause_examples)PER Clause Examples
**Example 1.** Count the number of Countries that has a City which has a resident that likes a post.
```
USE GRAPH ldbc_snb
INTERPRET QUERY () SYNTAX v2 {
  SumAccum<int> @@cnt;
  R =  SELECT c
    FROM  Country:c -(<Is_Part_Of.<Is_Located_In.Likes>)- Post:p
    PER  (c)
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
 "results": [{"@@cnt": 111}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**Example 2.** Count the number of posts liked by a person who is located in a city that belongs to a country. (All cities are in a country, but humor us. We are reusing the same FROM pattern in several examples.)
```
USE GRAPH ldbc_snb
INTERPRET QUERY () SYNTAX v2 {
  SumAccum<int> @@cnt;
  R =  SELECT p
    FROM  Country:c -(<Is_Part_Of.<Is_Located_In.Likes>)- Post:p
    PER  (p)
    ACCUM @@cnt +=1;
  PRINT @@cnt;
}
//result
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"@@cnt": 70668}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**Example 3.** Find for each country in ("Dominican_Republic","Angola", "Cambodia") the number of posts that is liked by a person living in that country.
```
USE GRAPH ldbc_snb
INTERPRET QUERY () SYNTAX v2{
  MapAccum<string, SumAccum<int>> @@post_per_country;
  R =  SELECT p
    FROM  Country:c -(<Is_Part_Of.<Is_Located_In.Likes>)- Post:p
    WHERE c.name in ("Dominican_Republic","Angola", "Cambodia")
    PER  (c, p)
    ACCUM @@post_per_country += (c.name -> 1);
  PRINT @@post_per_country;
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
 "results": [{"@@post_per_country": {
  "Dominican_Republic": 395,
  "Angola": 12,
  "Cambodia": 4002
 }}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**Example 4.** Find for each country in ("Dominican_Republic","Angola", "Cambodia") the number of posts that is liked by a person living in that country. Use local accumulators this time.
```
USE GRAPH ldbc_snb
INTERPRET QUERY () SYNTAX v2{
 SumAccum<int> @postCnt;
 R =  SELECT c
    FROM  Country:c -(<Is_Part_Of.<Is_Located_In.Likes>)- Post:p
    WHERE c.name in ("Dominican_Republic","Angola", "Cambodia")
    PER  (c, p) //per (country, post), add 1 to c.@postCnt
    ACCUM c.@postCnt += 1;
 PRINT R;
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
 "results": [{"R": [
  {
   "v_id": "2",
   "attributes": {
    "@postCnt": 12,
    "name": "Angola",
    "id": 2,
    "url": "http://dbpedia.org/resource/Angola"
   },
   "v_type": "Country"
  },
  {
   "v_id": "67",
   "attributes": {
    "@postCnt": 4002,
    "name": "Cambodia",
    "id": 67,
    "url": "http://dbpedia.org/resource/Cambodia"
   },
   "v_type": "Country"
  },
  {
   "v_id": "11",
   "attributes": {
    "@postCnt": 395,
    "name": "Dominican_Republic",
    "id": 11,
    "url": "http://dbpedia.org/resource/Dominican_Republic"
   },
   "v_type": "Country"
  }
 ]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/per-clause#_performance_and_best_practices)Performance and Best Practices
The PER Clause not only helps users to control the semantics of the ACCUM clause, it also boosts the performance of the pattern match query, as it uses the PER clause to optimize the query execution.
To get the best performance, we recommend three guidelines for writing efficient queries.
### [](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/per-clause#_use_per_target_if_possible)Use PER (target) If Possible
Per target is in general faster than Per source. In the example below, query q2 is faster than q1. The only difference between these two queries is q2’s FROM pattern is the flip of q1’s FROM pattern.
```
USE GRAPH ldbc_snb
// not recommended, since it does per (src).
CREATE QUERY q1 () SYNTAX v2 {
 SumAccum<int> @@cnt ;
 T = SELECT c
   FROM Comment:c - (<Likes) - Person:ps - (Is_Located_In>) - City:city
   WHERE year(c.creation_date) >= 2006
   PER (c)
   ACCUM @@cnt += 1;
 PRINT @@cnt;
}
// recommended, since it does per (tgt)
USE GRAPH ldbc_snb

CREATE QUERY q2 () SYNTAX v2 {
 SumAccum<int> @@cnt ;
 T = SELECT c
   FROM City:city - (<Is_Located_In) - Person:ps - (Likes>) - Comment:c
   WHERE year(c.creation_date) >= 2006
   PER (c)
   ACCUM @@cnt += 1;
 PRINT @@cnt;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/per-clause#_write_patterns_with_smallest_expected_vertex_set_on_the_left)Write Patterns with Smallest Expected Vertex Set on the Left
The match table is built by traversing the pattern from left to right. Follow the basic principle of pruning early rather than late by orienting the query the smaller cardinality set on the left. This practice will result in producing the least number of candidate matches during the query computation. For example, if there are fewer distinct tags than persons, then query q4 is faster than q3.
```
USE GRAPH ldbc_snb
// not recommended, since the pattern starts from a large cardinality vertex type
// (Person), and ends at a small cardinality vertex type (Tag).
CREATE QUERY q3 () SYNTAX v2 {
 SumAccum<int> @cnt;
 V = SELECT s
   FROM Person:s- (Likes>)-Post:p - (<Container_Of)-:f - (Has_Tag>) - :t
   PER (s)
   ACCUM s.@cnt += 1;
 PRINT V.size();
}
// recommended, start from small cardinality end (Tag), and use per tgt
CREATE QUERY q4 () SYNTAX v2 {
  SumAccum<int> @cnt;
  V = SELECT s
    FROM Tag:t-(<Has_Tag)-Forum:f -(Container_Of>)-Post:p - (<Likes)- Person:s
    PER (s)
    ACCUM s.@cnt += 1;
  PRINT V.size();
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/per-clause#_specify_complete_type_information)Specify Complete Type Information
Specifying complete type information improves performance. For example, query q6 is faster than q5 even though they are known to be logically identical. `Forum` is the `CONTAINER_OF` `Post`, so it does not need to be specified in q5, but explicitly saying `Forum` in q6 speeds up performance.
```
USE GRAPH ldbc_snb
// we do not put Forum before :f, even if we know it.
CREATE QUERY q5 () SYNTAX v2 {
 SumAccum<int> @@person_cnt;
 V = SELECT s
   FROM Person:s- (Likes>)-Post:p - (<Container_Of)-:f - (Has_Tag>) - :t
   PER (s)
   ACCUM @@person_cnt += 1;
 PRINT @@person_cnt;
}
// recommended: we put Forum as the type info.
CREATE QUERY q6 () SYNTAX v2 {
 SumAccum<int> @@person_cnt;
 V = SELECT s
   FROM Person:s- (Likes>)-Post:p - (<Container_Of)-Forum:f - (Has_Tag>) - :t
   PER (s)
   ACCUM @@person_cnt += 1;
 PRINT @@person_cnt;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/per-clause#_ldbc_benchmark_queries)LDBC Benchmark Queries
Using the PER clause and linear regular path pattern, we have translated all of the LDBC-SNB queries. You can find them on github at <https://github.com/tigergraph/ecosys/tree/ldbc/ldbc_benchmark/tigergraph/queries_linear/queries>. Most of the queries are installed as functions. You can find sample parameter(s) of the functions from <https://github.com/tigergraph/ecosys/tree/ldbc/ldbc_benchmark/tigergraph/queries/seeds>.
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


