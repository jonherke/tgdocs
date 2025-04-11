![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/conjunctive-pattern-matching)[Next](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/conjunctive-pattern-matching)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/conjunctive-pattern-matching)
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
[Resources](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/conjunctive-pattern-matching)
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
  * [Conjunctive Pattern Matching (Beta)](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/conjunctive-pattern-matching)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/4.1/modules/tutorials/pages/pattern-matching/adv/conjunctive-pattern-matching.adoc)
### Contents
  * [What is Conjunctive Pattern Matching?](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/conjunctive-pattern-matching#_what_is_conjunctive_pattern_matching)
  * [SELECT Clause](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/conjunctive-pattern-matching#_select_clause)
  * [FROM Clause - Conjunctive Matching](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/conjunctive-pattern-matching#_from_clause_conjunctive_matching)
  * [WHERE Clause](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/conjunctive-pattern-matching#_where_clause)
  * [ACCUM Clause](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/conjunctive-pattern-matching#_accum_clause)
  * [POST-ACCUM Clause](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/conjunctive-pattern-matching#_post_accum_clause)
  * [Examples](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/conjunctive-pattern-matching#_examples)
  * [Source Vertex Set Flexibility](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/conjunctive-pattern-matching#_source_vertex_set_flexibility)


# Conjunctive Pattern Matching (Beta)
### Contents
  * [What is Conjunctive Pattern Matching?](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/conjunctive-pattern-matching#_what_is_conjunctive_pattern_matching)
  * [SELECT Clause](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/conjunctive-pattern-matching#_select_clause)
  * [FROM Clause - Conjunctive Matching](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/conjunctive-pattern-matching#_from_clause_conjunctive_matching)
  * [WHERE Clause](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/conjunctive-pattern-matching#_where_clause)
  * [ACCUM Clause](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/conjunctive-pattern-matching#_accum_clause)
  * [POST-ACCUM Clause](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/conjunctive-pattern-matching#_post_accum_clause)
  * [Examples](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/conjunctive-pattern-matching#_examples)
  * [Source Vertex Set Flexibility](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/conjunctive-pattern-matching#_source_vertex_set_flexibility)


## [](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/conjunctive-pattern-matching#_what_is_conjunctive_pattern_matching)What is Conjunctive Pattern **Matching**?
So far, we have described pattern matching as one path pattern in a FROM clause. In this section, we introduce GSQL’s capability to match **multiple** **patterns** in one FROM clause. This extension is called Conjunctive Pattern Matching (CPM), because the query asks for the conjunction (logical AND) of the patterns. To get a match, all of the patterns must be satisfied, and the patterns can interrelate. Visually, you can think of patterns formed by a set of intersecting line segments. This feature, introduced as a Beta feature in TigerGraph 3.0, enables you to express complex patterns concisely in a single query block.
In general, a CPM query block consists of multiple patterns in the FROM clause. It has a structure illustrated below.
# Conjunctive Pattern Matching Syntax
```
SelectBlock := SELECT alias
        FROM pattern
        [sampleClause]
        [whereClause]
        [ [perClause] accumClause]
        [postAccumClause]*
          ...
pattern := vertexPattern | edgePattern | (pathPattern ["," pathPattern])
// vertexPattern and edgePattern are from classic GSQL
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

We elaborate on each of the clause.
### [](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/conjunctive-pattern-matching#_select_clause)SELECT Clause
The SELECT clause selects only one vertex alias from all the patterns in the FROM clause.
### [](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/conjunctive-pattern-matching#_from_clause_conjunctive_matching)**FROM Clause - Conjunctive Matching**
This is where the conjunctive matching is expressed. The FROM clause consists of a list of path patterns, which are separated by commas. Evaluating each pattern against the underlying graph data produces a match table. If two patterns share a vertex alias, then we form the natural join of the two match tables.
For example, consider this CPM:
```
FROM X:x - (E1:e1) - Y:y - (E2>:e2) - Z:z,
   Z:z - (E3:e3) - U:u - (E4>:e4) - V:v
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The first pattern’s variables are x, e1, y, e2, and z; the second pattern’s variables are z, e3, u, e4, and v. Considering the two patterns independently would yield the follwing match table schemas:
```
#first match table
(x, e1, y, e2, z)
#second match table
(z, e3, u, e4, v)
coffeescript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/conjunctive-pattern-matching#_natural_join_of_match_tables)Natural Join of Match Tables
Natural joining two match tables compares all the shared vertex aliases between the two tables, and the resulting joined table contains all non-shared variables plus one copy of each of the shared vertex variables. Here is the match table for the CPM above:
```
#natural join result; the shared vertex variable z appears once.
(x, e1, y, e2, z, e3, u, e4, v)
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/conjunctive-pattern-matching#_valid_conjunctive_patterns)Valid Conjunctive Patterns
The match table of the conjunctive pattern match is the natural join of all the patterns' match tables. By design, a row in the CPM match table must simultaneously satisfy all the match tables.
If the match tables of the patterns in a FROM clause can be naturally joined into one match table, then the FROM clause has a valid CPM input. Otherwise, the FROM clause has an invalid pattern input list.
For example, below we show two valid CPM inputs and one invalid CPM input.
```
// a valid CPM, since the two patterns natrually join on :tgt
SELECT
FROM Person:p - (KNOWS) - :tgt,
   Post:s -(<LIKES) - :tgt
// a valid CPM, since the two patterns naturally join on :f
SELECT
FROM Person:p - (KNOWS) - :f - (LIKES>) - Post:tgt,
   :f - (LIKES>) - Comment:c
// an invalid CPM, since the two patterns do not share any vertex variables, they cannot be naturally joined. One pattern has (p, tgt); the other has (s, t).
SELECT
FROM Person:p - (KNOWS) - :tgt,
   Post:s - (<LIKES) - Person:t
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/conjunctive-pattern-matching#_where_clause)**WHERE Clause**
The predicates in the WHERE clause can use any of the vertex or edge aliases in any of the patterns, including predicates which combine variables from different constituent paths. CPM queries do not have any special restrictions on the WHERE predicate. Distance matters, however, for performance. Conditions that are local, measured both cross-path and within-path, can be resolved earlier and therefore are faster.
In the example below, `x2.age > x4.age` is a cross-pattern predicate, `e1.timestamp < e3.timestamp` is a cross-pattern predicate, and `x1.gender == x4.gender` is a local predicate of the second pattern.
```
FROM X1:x1-(E1:e1)-X2:x2-(E2:e2)-X3:x3,
   X1:x1-(E3:e3)-X4:x4
WHERE x2.age > x4.age AND e1.timestamp < e3.timestamp AND x1.gender == x4.gender
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/conjunctive-pattern-matching#_accum_clause)ACCUM Clause
You can ACCUM to any vertex variable in a CPM block.
The ACCUM clause by default will execute _*as many times*_ _*as*_ the row (match) count of the CPM match table; each execution uses one row from the match table.
ACCUM To The Three Vertex Variables of A CPM Pattern
```
//accum to x1, x2 and x4.
FROM X1:x1-(E1:e1)-X2:x2-(E2:e2)-X3:x3,
   X1:x1-(E3:e3)-X4:x4
ACCUM x1.@cnt +=1, x2.@cnt += x3.quantity, x4.@cnt += x3.quantity
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/conjunctive-pattern-matching#_post_accum_clause)POST-ACCUM Clause
POST-ACCUM for CPM behaves the same as POST-ACCUM for single path patterns. That is, each POST-ACCUM clause can refer to one vertex alias, and the clause executes iteratively over that vertex set (e.g. one vertex column in the matching table). Its statements can access the aggregated accumulator result computed in the ACCUM clause. The query can have multiple POST-ACCUM clauses, one for each vertex alias you wish to work on. The multiple POST-ACCUM clauses are processed in parallel; it doesn’t matter in what order you write them. (For each binding, the statements within a clause are executed in order.)
For example, below we have three POST-ACCUM clauses. The first one iterates through`x1`, and for each x1, we do `@@cnt += x1.@cnt`. The second and third POST-ACCUMs iterate through `x2` and `x3` respectively, and accumulates their `@cnt` accumulator value into `@@cnt`.
POST-ACCUM to a global accumulator @@cnt, using three CPM Vertex Variables
```
FROM X1:x1-(E1:e1)-X2:x2-(E2:e2)-X3:x3,
   X1:x1-(E3:e3)-X4:x4
ACCUM x1.@cnt +=1, x2.@cnt += x3.quantity, x4.@cnt += x3.quantity
POST-ACCUM @@cnt += x1.@cnt
POST-ACCUM @@cnt += x2.@cnt
POST-ACCUm @@cnt += x3.@cnt;
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/conjunctive-pattern-matching#_examples)Examples
**Example 1.** Find Viktor Akhiezer’s liked messages (100+ days after their creation) whose author’s last name begin with letter S. Output the message’s forum.
```
USE GRAPH ldbc_snb
INTERPRET QUERY () SYNTAX v2 {
 SumAccum<int> @@cnt;
 F = SELECT f
    FROM Person:s - (Likes>:e1) - :msg - (Has_Creator>) - Person:t,
       Forum:f - (Container_Of>:e2) - :msg
    WHERE s.first_name == "Viktor" AND s.last_name == "Akhiezer"
       AND t.last_name LIKE "S%"
       AND e1.creation_date >DATETIME_ADD(msg.creation_date, INTERVAL 100 DAY);
 PRINT F;
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
 "results": [{"F": [{
  "v_id": "962072688797",
  "attributes": {
   "id": 962072688797,
   "creation_date": "2011-04-12 09:36:50",
   "title": "Album 12 of Mario Santos"
  },
  "v_type": "Forum"
 }]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**Example 2.** Find any authors who wrote posts that Viktor Akhiezer’s liked and whose last name begins with S. Find the country for each of these authors and report on the countries.
```
USE GRAPH ldbc_snb
INTERPRET QUERY () SYNTAX v2 {
  SumAccum<int> @@cnt;
  C = SELECT ctry
    FROM Person:s - (Likes>:e1) - Post:msg - (Has_Creator>) - Person:t,
       :t - (Work_At>:e2) - Company:c,
       :c - (Is_Located_In>) - Country:ctry
    WHERE s.first_name == "Viktor" AND s.last_name == "Akhiezer"
       AND t.last_name LIKE "S%" ;
  PRINT C;
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
  "results": [{"C": [{
    "v_id": "93",
    "attributes": {
      "name": "Portugal",
      "id": 93,
      "url": "http://dbpedia.org/resource/Portugal"
    },
    "v_type": "Country"
  }]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**Example 3.** Given a TagClass and a Country, find all the Forums created in the given Country, containing at least one Post with Tags belonging directly to the given TagClass. The location of a Forum is identified by the location of the Forum’s moderator.
```
CREATE QUERY bi_4(STRING tc_name, STRING c_name) FOR GRAPH ldbc_snb SYNTAX v2 {
 SetAccum<vertex<Post>> @post_set;
 SumAccum<int> @person_id, @post_count;
 forum_set =
  SELECT f
  FROM Forum:f -(Has_Moderator>)- Person:a -(Is_Located_In>.Is_Part_Of>)- Country:c,
     :f -(Container_Of>)- Post:p -(Has_Tag>.Has_Type>)- Tag_Class:tc
  WHERE c.name == c_name AND tc.name == tc_name
  ACCUM f.@person_id = a.id, f.@post_set += p
  POST-ACCUM f.@post_count = f.@post_set.size(), f.@post_set.clear()
  ORDER BY f.@post_count DESC, f.id ASC
  LIMIT 3;
 PRINT forum_set[forum_set.id, forum_set.title, forum_set.creation_date,
         forum_set.@person_id, forum_set.@post_count];
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
RUN QUERY bi_4("MusicalArtist", "Burma")
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"forum_set": [
  {
   "v_id": "81903",
   "attributes": {
    "forum_set.@person_id": 5226,
    "forum_set.@post_count": 65,
    "forum_set.title": "Wall of Donald Steele-Perkins",
    "forum_set.id": 81903,
    "forum_set.creation_date": "2010-02-15 06:48:04"
   },
   "v_type": "Forum"
  },
  {
   "v_id": "137438953686",
   "attributes": {
    "forum_set.@person_id": 2199023262994,
    "forum_set.@post_count": 65,
    "forum_set.title": "Wall of Eric Law-Yone",
    "forum_set.id": 137438953686,
    "forum_set.creation_date": "2010-04-25 22:10:32"
   },
   "v_type": "Forum"
  },
  {
   "v_id": "687194810508",
   "attributes": {
    "forum_set.@person_id": 10995116283784,
    "forum_set.@post_count": 39,
    "forum_set.title": "Wall of Hector Hugh Michie",
    "forum_set.id": 687194810508,
    "forum_set.creation_date": "2010-12-19 15:33:30"
   },
   "v_type": "Forum"
  }
 ]}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**Example 4.** For a given country, count all the distinct triples of Persons such that:
  * a is a friend of b.
  * b is a friend of c
  * c is a friend of a.


Distinct means that if a certain 3 vertices appear once in the results, it will not be repeated: it will appear only once. KNOWS is an undirected relationship, so it doesn’t matter in what order we list the 3 vertices.
```
CREATE QUERY bi_17(STRING c_name) FOR GRAPH ldbc_snb SYNTAX v2 {
 TYPEDEF TUPLE <uint a, uint b, uint c> triplet;
 SetAccum<triplet> @@triplet_set;
 SumAccum<int> @@triplet_count;
 C =
  SELECT c
  FROM Country:c -(<Is_Part_Of.<Is_Located_In)- Person:p1,
     :c -(<Is_Part_Of.<Is_Located_In)- Person:p2,
     :c -(<Is_Part_Of.<Is_Located_In)- Person:p3,
     :p1 -(Knows)- :p2 -(Knows)- :p3 -(Knows)- :p1
  WHERE c.name == c_name AND p1.id < p2.id AND p2.id < p3.id
  ACCUM @@triplet_set += triplet(p1.id, p2.id, p3.id);
 @@triplet_count = @@triplet_set.size();
 @@triplet_set.clear();
 PRINT @@triplet_count;
}
// results of RUN QUERY bi_17("Spain")
{
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "enterprise",
  "api": "v2"
 },
 "results": [{"@@triplet_count": 242}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**More Examples.** We translated [LDBC-SNB](http://ldbc.github.io/ldbc_snb_docs/ldbc-snb-specification.pdf) BI and IC queries using CPM, and shared the translation in github. Please refer to the query translation [here](https://github.com/tigergraph/ecosys/tree/ldbc/ldbc_benchmark/tigergraph/queries_conjunctive/queries). Most of the queries are installed as functions, you can find sample parameter(s) of the functions from [here](https://github.com/tigergraph/ecosys/tree/ldbc/ldbc_benchmark/tigergraph/queries/seeds).
## [](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/adv/conjunctive-pattern-matching#_source_vertex_set_flexibility)Source Vertex Set Flexibility
As mentioned when we first described pattern matching, in [One-hop patterns](https://docs.tigergraph.com/gsql-ref/4.1/tutorials/pattern-matching/one-hop-patterns), the source (leftmost) vertex set can be a vertex type, an alternation of types, or even omitted.
**Example 1**. Find Viktor Akhiezer’s favorite messages' creators whose last name begins with letter S. Count them.
```
USE GRAPH ldbc_snb
// start from a vertex type "Person"
INTERPRET QUERY () SYNTAX v2 {
 SumAccum<int> @@cnt;
 F = SELECT t
    FROM Person:s -(Likes>:e1)- :msg -(Has_Creator>)- Person:t
    WHERE s.first_name == "Viktor" AND s.last_name == "Akhiezer"
       AND t.last_name LIKE "S%"
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
 "results": [{"@@cnt": 8}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**Example 2.** Same query as example 1, but without beginning with vertex types. GSQL compiler can infer the types of :s.
```
USE GRAPH ldbc_snb
// both end points of the pattern do not have vertex types.
INTERPRET QUERY () SYNTAX v2 {
 SumAccum<int> @@cnt;
 F = SELECT t
    FROM :s -(Likes>:e1)- :msg -(Has_Creator>)- :t
    WHERE s.first_name == "Viktor" AND s.last_name == "Akhiezer" AND t.last_name LIKE "S%"
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
 "results": [{"@@cnt": 2190095}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**Example 3.** Count the LIKES edge.
```
USE GRAPH ldbc_snb
// a pattern starts without any information.
INTERPRET QUERY () SYNTAX v2 {
 SumAccum<int> @@cnt;
 F = SELECT msg
    FROM -(Likes>:e1)- :msg
    ACCUM @@cnt+=1;
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
 "results": [{"@@cnt": 2190095}]
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


