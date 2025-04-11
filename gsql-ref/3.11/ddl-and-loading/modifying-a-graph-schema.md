![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema)[Next](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema)
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
[Resources](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema)
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
  * [Schema Definition](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/)
  * [Modify a Graph Schema](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/3.11/modules/ddl-and-loading/pages/modifying-a-graph-schema.adoc)
### Contents
  * [Dynamic Schema Change - Abilities and Limitations](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_dynamic_schema_change_abilities_and_limitations)
  * [Do’s and Don’ts for Schema Change](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_dos_and_donts_for_schema_change)
  * [Global vs. local schema changes](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_global_vs_Local_schema_changes)
  * [USE GLOBAL](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_use_global)
  * [Global Privileges on Schema Change Jobs](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_global_privileges_on_schema_change_jobs)
  * [CREATE SCHEMA_CHANGE JOB](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_create_schema_change_job)
  * [ADD VERTEX | EDGE](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_add_vertex_edge)
  * [ALTER VERTEX | EDGE](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_alter_vertex_edge)
  * [ALTER …​ ADD](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_alter_add)
  * [ALTER EDGE .. ADD PAIR](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_alter_edge_add_pair)
  * [ALTER …​ DROP](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_alter_drop)
  * [ALTER VERTEX …​ WITH (Deprecated)](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_alter_vertex_with_deprecated)
  * [DROP VERTEX | EDGE](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_drop_vertex_edge)
  * [DROP TUPLE](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_drop_tuple)
  * [ADD TAG](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_add_tag)
  * [DROP TAG](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_drop_tag)
  * [RUN SCHEMA_CHANGE JOB](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_run_schema_change_job)
  * [-N Option (Local and Global)](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_n_option_local_and_global)
  * [DROP JOB SCHEMA_CHANGE](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_drop_job_schema_change)
  * [CREATE GLOBAL SCHEMA_CHANGE JOB](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_create_global_schema_change_job)
  * [ADD VERTEX | EDGE (global)](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_add_vertex_edge_global)
  * [ALTER VERTEX | EDGE](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_alter_vertex_edge_2)
  * [DROP VERTEX | EDGE (global)](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_drop_vertex_edge_global)
  * [RUN GLOBAL SCHEMA_CHANGE JOB](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_run_global_schema_change_job)
  * [-N Option](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_n_option)
  * [Impact Warning](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_impact_warning)
  * [DROP JOB GLOBAL SCHEMA_CHANGE](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_drop_job_global_schema_change)
  * [DROP ALL](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_drop_all)


# Modifying a Graph Schema
### Contents
  * [Dynamic Schema Change - Abilities and Limitations](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_dynamic_schema_change_abilities_and_limitations)
  * [Do’s and Don’ts for Schema Change](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_dos_and_donts_for_schema_change)
  * [Global vs. local schema changes](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_global_vs_Local_schema_changes)
  * [USE GLOBAL](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_use_global)
  * [Global Privileges on Schema Change Jobs](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_global_privileges_on_schema_change_jobs)
  * [CREATE SCHEMA_CHANGE JOB](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_create_schema_change_job)
  * [ADD VERTEX | EDGE](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_add_vertex_edge)
  * [ALTER VERTEX | EDGE](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_alter_vertex_edge)
  * [ALTER …​ ADD](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_alter_add)
  * [ALTER EDGE .. ADD PAIR](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_alter_edge_add_pair)
  * [ALTER …​ DROP](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_alter_drop)
  * [ALTER VERTEX …​ WITH (Deprecated)](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_alter_vertex_with_deprecated)
  * [DROP VERTEX | EDGE](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_drop_vertex_edge)
  * [DROP TUPLE](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_drop_tuple)
  * [ADD TAG](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_add_tag)
  * [DROP TAG](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_drop_tag)
  * [RUN SCHEMA_CHANGE JOB](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_run_schema_change_job)
  * [-N Option (Local and Global)](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_n_option_local_and_global)
  * [DROP JOB SCHEMA_CHANGE](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_drop_job_schema_change)
  * [CREATE GLOBAL SCHEMA_CHANGE JOB](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_create_global_schema_change_job)
  * [ADD VERTEX | EDGE (global)](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_add_vertex_edge_global)
  * [ALTER VERTEX | EDGE](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_alter_vertex_edge_2)
  * [DROP VERTEX | EDGE (global)](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_drop_vertex_edge_global)
  * [RUN GLOBAL SCHEMA_CHANGE JOB](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_run_global_schema_change_job)
  * [-N Option](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_n_option)
  * [Impact Warning](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_impact_warning)
  * [DROP JOB GLOBAL SCHEMA_CHANGE](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_drop_job_global_schema_change)
  * [DROP ALL](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_drop_all)


After a graph schema has been created , it can be modified. Data already stored in the graph and which is not logically part of the change will be retained. For example, if you had 100 Book vertices and then added an attribute to the Book schema, you would still have 100 Books, with default values for the new attribute. If you dropped a Book attribute, you still would have all your books, but one attribute would be gone.
To safely update the graph schema, the user should follow this procedure:
  * Create a schema change job, which defines a sequence of `ADD`, `ALTER` and/or `DROP` statements.
  * Run the schema change job (using **`RUN SCHEMA_CHANGE JOB <job name>`**), which will do the following:
    * Attempt the schema change.
    * If the change is successful, invalidate any loading job or query definitions which are incompatible with the new schema.
    * If the change is unsuccessful, report the failure and return to the state before the attempt.


A schema change will invalidate any loading jobs or query jobs which relate to an altered part of the schema. Specifically:
  * A loading job becomes invalid if it refers to a vertex type or an edge type that has been DROPPED or ALTERED.
  * A query becomes invalid if it refers to a vertex type, edge type, or an attribute of a type that has been DROPPED.

Invalid loading jobs are dropped, and invalid queries are uninstalled. After the schema update, the user will need to create and install new load and query jobs based on the new schema.  
---  
Load or query operations which begin before the schema change will be completed based on the pre-change schema. Load or query operations which begin after the schema change, and which have not been invalidated, will be completed based on the post-change schema.  
---  
Schema changes that are performed during times with high query or data loading volume may have a chance of failure. It is considered good practice to perform schema changes during times of low graph activity.
## [](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_dynamic_schema_change_abilities_and_limitations)Dynamic Schema Change - Abilities and Limitations
Dynamic Schema Change (DSC) acts as a traffic manager for schema change jobs. First, if there are any active loading jobs in progress when a schema change is requested, and the schema change affects a graph element included in the loading job, DSC should pause the schema change until the loading job completes.
Once the schema change begins, DSC enables a modest amount of database activity (queries and loading) during a schema change, but ONLY if those operations do not involve graph elements affected by the schema change. If the activity level is too high, there is a risk of either the schema change job not succeeding, the concurrent database activity not succeeding, or both.
For maximum safety, is it best to halt all graph activity before and during a schema change. If a schema change job fails, it can leave the graph in an inconsistent state.  
---  
Perform schema changes only when no active queries or loading jobs are running to avoid data consistency and application errors. Always abort ongoing jobs before initiating the schema change.  
---  
### [](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_dos_and_donts_for_schema_change)Do’s and Don’ts for Schema Change
Because the demands of each graph activity vary, there is no universal way to state what level of concurrent graph activity can be handled by dynamic schema change.
**Do’s:**
  * **Do backup your data before performing a schema change** as a precaution.
  * **Do perform schema changes only during no- or low-traffic periods.**


**Don’ts:**
  * **Don’t change the schema during high-traffic periods.** Schema changes during heavy operations may cause system conflicts and errors.
  * **Don’t run queries and loading jobs which you know are affected by the schema** as they will be invalidated.


**For maximum safety:**
  * **Don’t run any queries or loading jobs during schema changes.**


## [](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_global_vs_Local_schema_changes)Global vs. local schema changes
Users must have the global scope to interact with global schema change jobs (create, delete, run). See [`USE GLOBAL`](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_use_global).  
---  
### [](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_use_global)`USE GLOBAL`
The `USE GLOBAL` command changes a superuser’s mode to Global mode. In global mode, a superuser can define or modify global vertex and edge types, as well as specifying which graphs use those global types. For example, the user should run `USE GLOBAL` before creating or running a `GLOBAL SCHEMA_CHANGE JOB`.
### [](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_global_privileges_on_schema_change_jobs)Global Privileges on Schema Change Jobs
Only users with the `WRITE_SCHEMA` privilege on the global scope can add, alter, or drop global vertex types or global edge types, which are those that are created using `CREATE VERTEX` or `CREATE EDGE`. This rule applies even if the vertex or edge type is used in only one graph. To make these changes, the user uses a `GLOBAL SCHEMA_CHANGE JOB`.
Only users with the `WRITE_SCHEMA` privilege on the corresponding graph can add, alter, or drop local vertex types or local edge types which are created in the context of that graph. Local vertex and edge types are created using an `ADD` statement inside a `SCHEMA_CHANGE JOB` on one particular graph. To alter or drop any of these local types, the admin user uses a regular `SCHEMA_CHANGE JOB`.
To see which vertices or edges are global, run the `ls` command:
```
>USE GLOBAL
>ls
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

By restricting the `ls` command to only global types, any local types will not appear in the results. Use the `USE` command with a specific graph to view all vertices and edges on that graph, including local types, then compare the results to find which types are local.
Vertex and edge types can share the same name as long as they are defined and used in different scopes. That is, different graphs can have local vertex and edge types with the same name. In addition, graphs can also have local types that share the same name with global types, as long as the global types with the same name are not used in the graph definition.  
---  
The two types of schema change jobs are described below.
## [](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_create_schema_change_job)`CREATE SCHEMA_CHANGE JOB`
The `CREATE SCHEMA_CHANGE JOB` block defines a sequence of `ADD`, `ALTER`, and `DROP` statements for changing a particular graph. It does not perform the schema change.
CREATE SCHEMA_CHANGE JOB syntax
```
CREATE SCHEMA_CHANGE JOB job_name FOR GRAPH Graph_Name {
  [sequence of DROP, ALTER, and ADD statements, each line ending with a semicolon]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

One use of `CREATE SCHEMA_CHANGE JOB` is to define an additional vertex type and edge type to be the structure for a secondary index. For example, if you wanted to index the `postal_code` attribute of the `User` vertex, you could create a `Postal_Code_IDX (PRIMARY_ID id string, code string)` vertex type and `Has_Postal_Code (FROM User, TO Postal_Code_IDX)` edge type. Then create an index structure having one edge from each `User` to a `Postal_Code_IDX` vertex.
If a `SCHEMA_CHANGE JOB` defines a new edge type which connects to a new vertex type, the `ADD VERTEX` statement should precede the related `ADD EDGE` statement.However, the `ADD EDGE` and `ADD VERTEX` statements can be in the same `SCHEMA_CHANGE` `JOB`.  
---  
## [](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_add_vertex_edge)`ADD VERTEX | EDGE`
The `ADD` statement defines a new type of vertex or edge and automatically adds it to a graph schema. The syntax for the `ADD VERTEX | EDGE` statement is analogous to that of the `CREATE VERTEX | EDGE` statements. It may only be used within a `SCHEMA_CHANGE JOB`.
  * ADD VERTEX
  * ADD EDGE


```
ADD VERTEX Vertex_Type_Name ( PRIMARY_ID id_name id_type
  [, attribute_name type [DEFAULT default_value] ]* )
  [WITH [STATS="none"|"outdegree_by_edgetype"][primary_id_as_attribute="true"]]
```

```
ADD UNDIRECTED EDGE Edge_Type_Name (
  FROM Vertex_Type_Name "," TO Vertex_Type_Name
  [ "|" FROM Vertex_Type_Name "," TO Vertex_Type_Name]*
  [ "," DISCRIMINATOR "(" attribute_name type ["," attribute_name type]* ")" ]
  [ "," attribute_name type [DEFAULT default_value]]*
)
```

For example, the following statement in a schema change job adds a directed edge `Study_At` with source vertex `Person` and target vertex `University`. with the attributes `class_year` and `class_month` as their discriminator:
```
ADD DIRECTED EDGE Study_At (From Person, To University,
  DISCRIMINATOR(class_year INT, class_month INT));
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_alter_vertex_edge)`ALTER VERTEX | EDGE`
The `ALTER` statement adds attributes to or removes attributes from an existing vertex type or edge type. It may only be used within a `SCHEMA_CHANGE` `JOB`. The basic format is as follows:
Syntax
```
ALTER VERTEX|EDGE object_type_name ADD|DROP ATTRIBUTE (attribute_list);
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_alter_add)`ALTER …​ ADD`
`ALTER …​ ADD` can add attributes to vertex or edge types. You cannot make changes to a vertex type’s primary key or an edge types discriminator.
Added attributes are appended to the end of the schema. The new attributes may include `DEFAULT` fields. To add attributes to a vertex type, the syntax is as follows:
Syntax
```
ALTER VERTEX Vertex_Type_Name ADD
  ATTRIBUTE (attribute_name type [DEFAULT default_value]
  [',' attribute_name type [DEFAULT default_value]]* );
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

For example:
```
ALTER VERTEX Company ADD ATTRIBUTE (industry
STRING, market_cap DOUBLE)
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

To add to an edge’s endpoint vertex types or attributes, the syntax is as follows:
Syntax
```
ALTER EDGE Edge_Type_Name ADD
  [ATTRIBUTE (attribute_name type [DEFAULT default_value]
  [',' attribute_name type [DEFAULT default_value]]* )];
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_alter_edge_add_pair)`ALTER EDGE .. ADD PAIR`
`ALTER EDGE ... ADD PAIR` adds one or more edge pairs, which refer to the `FROM` and `TO` vertex types of an edge type. To add an edge pair, put the vertex type names in parentheses after keywords `FROM` and `TO`.
Syntax
```
ALTER EDGE Edge_Type ADD PAIR
"(" FROM Vertex_Type, TO Vertex_Type (| FROM Vertex_Type, TO Vertex_Type)* ")”
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_example)Example
In the example below, the first statement in the schema change job will add an edge pair (`FROM Person, TO Company`) to the edge type `Visit`. The second example adds two edge pairs to the edge type `Has_Pet`; the edge type can now connect both `Person` and `Dog` vertices, as well as `Person` and `Bird` vertices.
```
CREATE SCHEMA_CHANGE JOB job_2 FOR GRAPH Example_Graph {
 ALTER EDGE Visit ADD PAIR (FROM Person, TO Company);
 ALTER EDGE Has_Pet ADD PAIR (FROM Person, TO Dog | FROM Person, TO Bird);
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_alter_drop)`ALTER …​ DROP`
The syntax for ALTER …​ DROP is analogous to that of ALTER …​ ADD.
Syntax
```
ALTER VERTEX|EDGE Object_Type_Name DROP ATTRIBUTE (
   attribute_name [',' attribute_name]* );
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_alter_vertex_with_deprecated)`ALTER VERTEX …​ WITH` (Deprecated)
Tag-based Vertex-Level Access Control is deprecated as of October 2023. This feature will be completely removed in v4.0.   
---  
`The` statement `ALTER VERTEX WITH TAGGABLE` is used to mark a vertex type as taggable or untaggable. Vertex types are untaggable by default. When a vertex type is marked as taggable, the vertex type can be used to [create a tag-based graph](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/defining-a-graph-schema#_create_graph___as_beta). Additionally, users with the tag-access privilege can tag vertices whose vertex type is marked as taggable.
Syntax
```
ALTER VERTEX Vertex_Type_Name WITH TAGGABLE = ("true" | "false")
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_drop_vertex_edge)`DROP VERTEX | EDGE`
The DROP statement removes the specified vertex type or edge type from the database dictionary. The DROP statement should only be used when graph operations are not in progress.
Syntax
```
DROP VERTEX Vertex_Type_Name [',' Vertex_Type_Name]*
DROP EDGE Edge_Type_Name [',' Edge_Type_Name]*
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_drop_tuple)`DROP TUPLE`
For tuples that are defined within a graph schema, you can drop them by using the following command.
Syntax
```
DROP TUPLE Tuple_Name [',' Tuple_Name]*
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_add_tag)`ADD TAG`
Tag-based Vertex-Access Access Control is deprecated as of October 2023. TigerGraph will be introducing a more flexible scheme in an upcoming release.   
---  
`ADD TAG` defines a tag for the graph. Tags can be used to create tag-based graphs, allowing for finer grain access control.
Syntax for ADD TAG
```
ADD TAG <tag_name> [DESCRIPTION <tag_description>]
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_drop_tag)`DROP TAG`
Tag-based Vertex-Access Access Control is deprecated as of October 2023. TigerGraph will be introducing a more flexible scheme in an upcoming release.   
---  
`DROP TAG` drops a tag or multiple tags from the schema, and deletes the tag from each vertex to which it is attached. `DROP TAG` cannot be run if the tag to be dropped is used in the definition of a tag-based graph; the graph must be dropped first.
Syntax for DROP TAG
```
DROP TAG <tag_name> ["," <tag_name>]*
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_run_schema_change_job)`RUN SCHEMA_CHANGE JOB`
`RUN SCHEMA_CHANGE JOB job_name` performs the schema change job. After the schema has been changed, the GSQL system checks all existing GSQL queries. If an existing GSQL query uses a dropped vertex, edge, or attribute, the query becomes invalid, and GSQL will show the message "Query _Query_Name_ becomes invalid after schema update, please update it.".
Below is an example. The schema change job add_reviews adds a Review vertex type and two edge types to connect reviews to users and books, respectively.
SCHEMA_CHANGE JOB example
```
USE GRAPH Book_rating
CREATE SCHEMA_CHANGE JOB add_reviews FOR GRAPH Book_Rating {
  ADD VERTEX Review (PRIMARY_ID id UINT, review_date DATETIME, url STRING);
  ADD UNDIRECTED EDGE Wrote_Review (FROM User, TO Review);
  ADD UNDIRECTED EDGE Review_Of_Book (FROM Review, TO Book);
}
RUN SCHEMA_CHANGE JOB add_reviews
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_n_option_local_and_global)-N Option (Local and Global)
Additionally, an option `-N` is currently supported for both local and global schema change jobs. See [`-N` Option](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_n_option) for more details.
## [](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_drop_job_schema_change)`DROP JOB SCHEMA_CHANGE`
To drop (remove) a schema change job, run `DROP JOB schema_change_job` name from the GSQL shell. The specific schema change job will be removed from GSQL. Refer to the [Creating a Loading Job page](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/creating-a-loading-job#_drop_job_statement) for more information about dropping jobs.
```
GSQL > USE GRAPH Book_rating
GSQL > DROP JOB local_schema_change123
The job local_schema_change123 is dropped!
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_create_global_schema_change_job)`CREATE GLOBAL SCHEMA_CHANGE JOB`
The `CREATE GLOBAL SCHEMA_CHANGE JOB` block defines a sequence of `ADD`, `ALTER`, and `DROP` statements that modify either the attributes or the graph membership of global vertex or edge types. Unlike the non-global schema change job, the header does not include a graph name. However, the `ADD`/`ALTER`/`DROP` statements in the body do mention graphs.
Syntax
```
CREATE GLOBAL SCHEMA_CHANGE JOB job_name {
  [sequence of global DROP, ALTER, and ADD statements, each line ending with a semicolon]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Although both global and local schema change jobs have `ADD` and `DROP` statements, they have different meanings. The table below outlines the differences.
Local | Global  
---|---  
`ADD` | Defines a new local vertex/edge type; adds it to the graph’s domain | Adds one or more existing global vertex/edge types to a graph’s domain.  
`DROP` | Deletes a local vertex/edge type and its vertex/edge instances | Removes one or more existing global vertex/edge types from a graph’s domain.  
`ALTER` | Adds or drops attributes from a local vertex/edge type. | Adds or drops attributes from a global vertex/edge type, which may affect several graphs.  
Remember to include a semicolon at the end of each `DROP`, `ALTER`, or `ADD` statement within the JOB block.  
---  
### [](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_add_vertex_edge_global)`ADD VERTEX | EDGE` (global)
The ADD statement adds existing global vertex or edge types to one of the graphs.
Syntax
```
ADD VERTEX Vertex_Type_Name [',' Vertex_Type_Name...] TO GRAPH Graph_Name;
ADD EDGE Edge_Type_Name [',' Edge_Type_Name...] TO GRAPH Graph_Name;
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_alter_vertex_edge_2)`ALTER VERTEX | EDGE`
The `ALTER` statement is used to add attributes to or remove attributes from an existing vertex type or edge type.
It can also be used to add or remove source (`FROM`) vertex types or destination (`TO`) vertex types of an edge type. It may only be used within a `SCHEMA_CHANGE JOB`. The basic format is as follows:
Syntax
```
ALTER VERTEX|EDGE Object_Type_Name ADD|DROP ATTRIBUTE (attribute_list);
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_alter_add_2)`ALTER …​ ADD`
Added attributes are appended to the end of the schema. The new attributes may include default fields. To add attributes to a vertex type, the syntax is as follows:
Syntax
```
ALTER VERTEX Vertex_Type_Name ADD
  ATTRIBUTE (attribute_name type [DEFAULT default_value]
  [',' attribute_name type [DEFAULT default_value]]* );
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

For example:
```
ALTER VERTEX Company ADD ATTRIBUTE (industry
STRING, market_cap DOUBLE)
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

To add to an edge’s endpoint vertex types or attributes, the syntax is as follows:
Syntax
```
ALTER EDGE Edge_Type_Name ADD
  [FROM (Vertex_Type_Name [','Vertex_Type_Name])]
  [TO (Vertex_Type_Name [','Vertex_Type_Name])]
  [ATTRIBUTE (attribute_name type [DEFAULT default_value]
  [',' attribute_name type [DEFAULT default_value]]* )];
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

For example:
```
ALTER EDGE Like ADD TO (Animal) ATTRIBUTE (suggested_by STRING)
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_alter_edge_add_pair_2)`ALTER EDGE .. ADD PAIR`
`ALTER EDGE ... ADD PAIR` adds one or more edge pairs, which refer to the `FROM` and `TO` vertex types of an edge type. To add an edge pair, put the vertex type names in parentheses after keywords `FROM` and `TO`.
Syntax
```
ALTER EDGE Edge_Type ADD PAIR
"(" FROM Vertex_Type, TO Vertex_Type (| FROM Vertex_Type, TO Vertex_Type)* ")”
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

##### [](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_example_2)Example
In the following example below, the first statement in the schema change job will add an edge pair (`FROM person, TO company`) to the edge type `visit`. The second example adds two edge pairs to the edge type `has_pet`; the edge type can now connect both `person` and `dog` vertices, as well as `person` and `bird` vertices.
```
CREATE GLOBAL SCHEMA_CHANGE JOB job_2 FOR GRAPH Example_Graph {
 ALTER EDGE Visit ADD PAIR (FROM Person, TO Company);
 ALTER EDGE Has_Pet ADD PAIR (FROM Person, TO Dog | FROM Person, TO Bird);
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_alter_drop_2)`ALTER …​ DROP`
The syntax for `ALTER ... DROP` is analogous to that of `ALTER ... ADD`.
ALTER …​ DROP
```
ALTER VERTEX|EDGE Object_Type_Name DROP ATTRIBUTE (
   attribute_name [',' attribute_name]* );
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_alter_vertex_with_beta)`ALTER VERTEX ... WITH` (Beta)
The statement `ALTER VERTEX WITH TAGGABLE` is used to mark a vertex type as taggable or untaggable. Vertex types are untaggable by default. When a vertex type is marked as taggable, the vertex type can be used to [create a tag-based graph](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/defining-a-graph-schema#_create_graph___as_beta). Additionally, users with the tag-access privilege can tag vertices whose vertex type is marked as taggable.
ALTER VERTEX WITH TAGGABLE
```
ALTER VERTEX Vertex_Type_Name WITH TAGGABLE = ("true" | "false")
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_drop_vertex_edge_global)**`DROP VERTEX | EDGE`(global)**
The DROP statement removes specified global vertex or edge types from one of the graphs. The command does not delete any data.  
---  
drop vertex / edge
```
DROP VERTEX Vertex_Type_Name [',' Vertex_Type_Name...] FROM GRAPH Graph_Name;
DROP EDGE Edge_Type_Name  [',' Edge_Type_Name...] FROM GRAPH Graph_Name;
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_run_global_schema_change_job)`RUN GLOBAL SCHEMA_CHANGE JOB`
`RUN GLOBAL SCHEMA_CHANGE JOB job_name` performs a global schema change job. After the schema has been changed, the GSQL system checks all existing GSQL queries. If an existing GSQL query uses a dropped vertex, edge, or attribute, the query becomes invalid, and GSQL will show the message "Query _query_name_ becomes invalid after schema update, please update it.".
Below is an example. The schema change alter_friendship_make_library drops the on_date attribute from the friend_of edge and adds Book type to the library graph.
GLOBAL SCHEMA_CHANGE JOB example
```
USE GLOBAL
CREATE GRAPH Library()
CREATE GLOBAL SCHEMA_CHANGE JOB alter_friendship_make_library {
  ALTER EDGE Friend_Of DROP ATTRIBUTE (on_date);
  ADD VERTEX Book TO GRAPH library;
}
RUN GLOBAL SCHEMA_CHANGE JOB alter_friendship_make_library
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_n_option)`-N` Option
Additionally, an option `-N` is currently supported for both local and global schema change jobs.
Option `-N`, for both global and local scopes, will mark the queries as deprecated and the user will need to manually re-install the deprecated queries.  
---  
Local jobs with the `-N` option will skip recompile and reinstall queries created for the local graph.
Example
```
RUN SCHEMA_CHANGE JOB test_job -N
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Global jobs with the `-N` option will skip recompile and re-install queries.
Example
```
RUN GLOBAL SCHEMA_CHANGE JOB test_job -N
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_impact_warning)Impact Warning
A notification will be displayed to help users understand the impact of running a global or local schema change on a query.
The warning message will be as follows:
```
WARNING: When modifying the graph schema, reinstalling all affected queries is required, and the duration of this process may vary based on the number and complexity of the queries. To skip query reinstallation, you can run with the '-N' option, but manual reinstallation of queries will be necessary afterwards.
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Users can skip this message by using the `-N` option with the schema change job and the queries will not be reinstalled.
#### [](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_examples)Examples
This first example runs a schema change job without the option `-N`.
```
GLE_6714 (main) $ gsql 2_run_schemage_cahnge_job.gsql
Using graph 'person_movie'
WARNING: When modifying the graph schema, reinstalling all affected queries is required, and the duration of this process may vary based on the number and complexity of the queries. To skip query reinstallation, you can run with the '-N' option, but manual reinstallation of queries will be necessary afterwards.
Kick off schema change job schema_change_job
Doing schema change on graph 'person_movie' (current version: 1)
Trying to add local edge 'has_director' and its reverse edge 'reverse_has_director' to the graph 'person_movie'.
Graph person_movie updated to new version 2
Validating existing queries for graph person_movie ...
Start installing queries, about 1 minute ...
Select 'm1' as compile server, now connecting ...
Node 'm1' is prepared as compile server.
[========================================================================================================] 100% (0/0)
Query installation finished.
The job schema_change_job completes in 6.621 seconds!
Local schema change succeeded.
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This example runs a global schema change job with the option `-N`.
```
GLE_6714 (main) $ cat 3_run_schemage_cahnge_job_without_warning.gsql
RUN GLOBAL SCHEMA_CHANGE JOB global_schema_change_job -N
GLE_6714 (main) $ gsql 3_run_schemage_cahnge_job_without_warning.gsql
Kick off global schema change job global_schema_change_job
Doing schema change on graph 'person_movie' (current version: 2)
Trying to add global edge 'has_friend' and its reverse edge 'reverse_has_friend' to the graph 'person_movie'.
Doing schema change on the global schema (current version: 67)
Graph person_movie updated to new version 3
Global schema change succeeded.
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_drop_job_global_schema_change)`DROP JOB GLOBAL SCHEMA_CHANGE`
Global schema change jobs can be dropped by using the DROP JOB command. Refer to the [Creating a Loading Job page](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/creating-a-loading-job) for more information about dropping jobs.
DROP GLOBAL SCHEMA_CHANGE JOB example
```
USE GLOBAL
DROP JOB alter_friendship_make_library
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/modifying-a-graph-schema#_drop_all)`DROP ALL`
The `DROP ALL` command clears the entire graph store (i.e. deletes all data) and removes all data-related definitions from the catalog: vertex types, edge types, graph types, jobs, and queries. It will also erase graph-specific roles.
See [DROP ALL](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/defining-a-graph-schema#_drop_all) for more details.
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


