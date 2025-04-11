![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/3.11/querying/data-modification-statements)[Next](https://docs.tigergraph.com/gsql-ref/3.11/querying/data-modification-statements)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/3.11/querying/data-modification-statements)
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
[Resources](https://docs.tigergraph.com/gsql-ref/3.11/querying/data-modification-statements)
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
  * [Querying](https://docs.tigergraph.com/gsql-ref/3.11/querying/)
  * [Data Modification Statements](https://docs.tigergraph.com/gsql-ref/3.11/querying/data-modification-statements)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/3.11/modules/querying/pages/data-modification-statements.adoc)
### Contents
  * [Query-body DELETE Statement](https://docs.tigergraph.com/gsql-ref/3.11/querying/data-modification-statements#_query_body_delete_statement)
  * [DML-sub DELETE Statement](https://docs.tigergraph.com/gsql-ref/3.11/querying/data-modification-statements#_dml_sub_delete_statement)
  * [INSERT INTO Statement](https://docs.tigergraph.com/gsql-ref/3.11/querying/data-modification-statements#_insert_into_statement)
  * [Query-Body INSERT](https://docs.tigergraph.com/gsql-ref/3.11/querying/data-modification-statements#_query_body_insert)
  * [DML-sub INSERT](https://docs.tigergraph.com/gsql-ref/3.11/querying/data-modification-statements#_dml_sub_insert)
  * [UPDATE Statement](https://docs.tigergraph.com/gsql-ref/3.11/querying/data-modification-statements#_update_statement)
  * [Assignment statements](https://docs.tigergraph.com/gsql-ref/3.11/querying/data-modification-statements#_assignment_statements)


# Data Modification Statements
### Contents
  * [Query-body DELETE Statement](https://docs.tigergraph.com/gsql-ref/3.11/querying/data-modification-statements#_query_body_delete_statement)
  * [DML-sub DELETE Statement](https://docs.tigergraph.com/gsql-ref/3.11/querying/data-modification-statements#_dml_sub_delete_statement)
  * [INSERT INTO Statement](https://docs.tigergraph.com/gsql-ref/3.11/querying/data-modification-statements#_insert_into_statement)
  * [Query-Body INSERT](https://docs.tigergraph.com/gsql-ref/3.11/querying/data-modification-statements#_query_body_insert)
  * [DML-sub INSERT](https://docs.tigergraph.com/gsql-ref/3.11/querying/data-modification-statements#_dml_sub_insert)
  * [UPDATE Statement](https://docs.tigergraph.com/gsql-ref/3.11/querying/data-modification-statements#_update_statement)
  * [Assignment statements](https://docs.tigergraph.com/gsql-ref/3.11/querying/data-modification-statements#_assignment_statements)


The GSQL language provides full support for vertex and edge insertion, deletion, and attribute update.
**Modifications to the graph data do not take effect until the entire query is completed (committed)**. If one step needs to see the changes of an earlier step, you must separate the work into separate queries run in sequence.   
---  
## [](https://docs.tigergraph.com/gsql-ref/3.11/querying/data-modification-statements#_query_body_delete_statement)Query-body `DELETE` Statement
The query-body `DELETE` statement deletes a given set of edges or vertices.This statement can only be used as a query-body statement. Deletion at the DML-sub level is served by the [DML-sub `DELETE` statement](https://docs.tigergraph.com/gsql-ref/3.11/querying/data-modification-statements#_dml_sub_delete_statement).
The GSQL `DELETE` operation is a cascading deletion. If a vertex is deleted, then all edges which connect to it are automatically deleted as well.
### Syntax
EBNF
```
queryBodyDeleteStmt := DELETE alias FROM pathPattern [whereClause]
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The `FROM` clause in the `DELETE` statement follows the same rules as those in the `FROM` clause in a `SELECT` statement. However, the `FROM` clause in the `DELETE` statement only supports 1-hop, instead of multiple hops in the `SELECT` statement.
The `WHERE` clause can filter the items in the path pattern.
### Examples
Below are two examples, one for deleting vertices and one for deleting edges.
Deleting vertices
```
CREATE QUERY delete_ex() FOR GRAPH Work_Net {
  // Delete all "Person" vertices with location equal to "us"
  S = {Person.*};
  DELETE s FROM S:s
    WHERE s.location_id == "us";
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Deleting edges
```
CREATE QUERY delete_ex_2() FOR GRAPH Work_Net {
  // Delete all "Works_For" edges where the person's location is "us"
  S = {Person.*};
  DELETE e FROM S:s -(Works_For:e)- Company:t
    WHERE s.location_id == "us";
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The following query can be used to observe the effect of the delete statements. This query counts the person vertices who work in the US and the `Works_For` edges for persons in the US. When the initial `Work_Net` test data loaded, there are 5 persons and 9 Works_For edges for locationId = "us".
If query `delete_ex2` is run, there are 5 persons but 0 `Works_For` edges. Next, if the deleteEx query is run, the `works_at_US` query then finds 0 persons and 0 `Works_For` edges.
Query to check the results of deleteEx and deleteEx2
```
CREATE QUERY count_at_location(STRING loc) FOR GRAPH Work_Net {
  SetAccum<EDGE> @@sel_edge;
  Start = {Person.*};
  SV = SELECT s FROM Start:s
    WHERE s.location_id == loc;
  PRINT SV.size() AS num_vertices;
  SE = SELECT s FROM Start:s -(Works_For:e)- Company:t
    WHERE s.location_id == loc
    ACCUM @@sel_edge += e;
    PRINT @@sel_edge.size() AS num_edges;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Below are the results of the queries in sequence:
  * Query
  * Results


deleteEx.run
```
RUN QUERY count_at_location("us")
RUN QUERY delete_ex2()
RUN QUERY count_at_location("us")
RUN QUERY deleteEx()
RUN QUERY count_at_location("us")
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results from DeleteEx Example
```
// Before any deletions
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [
  {"numVertices": 5},
  {"numEdges": 9}
 ]
}
// Delete edges
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": []
}
// After deleting edges
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [
  {"numVertices": 5},
  {"numEdges": 0}
 ]
}
// Delete vertices
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": []
}
// After deleting vertices
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [
  {"numVertices": 0},
  {"numEdges": 0}
 ]
}
javascript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.11/querying/data-modification-statements#_dml_sub_delete_statement)DML-sub `DELETE` Statement
DML-sub `DELETE` is a DML-sub statement which deletes one vertex or edge each time it is called. Deletion at the query-body level is served by the [Query-body DELETE statement](https://docs.tigergraph.com/gsql-ref/3.11/querying/data-modification-statements#_query_body_delete_statement).
In practice, this statement resides within the body of a `SELECT…​ACCUM/POST-ACCUM` clause, so it is called once for each member of a selected vertex set or edge set.
The GSQL DELETE operation is a cascading deletion. If a vertex is deleted, then all edges which connect to it are automatically deleted as well.
The `ACCUM` clause iterates over an edge set, which can encounter the same vertex multiple times. If you wish to delete a vertex, it is best practice to place the DML-sub `DELETE` statement in the POST-ACCUM clause rather than in the ACCUM clause.  
---  
### Syntax
EBNF
```
dmlSubDeleteStmt := DELETE "(" alias ")"
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### Examples
The following example uses and modifies the graph data for `Social_Net`.
`DELETE` within `ACCUM` vs. `POST-ACCUM`
```
CREATE QUERY delete_posts(VERTEX<Person> seed) FOR GRAPH Social_Net {
	// Remove any post vertices posted by the given user
  start = {seed};
	/* Best practice is to delete a vertex in a POST-ACCUM, which only
	 occurs once for each vertex v, guaranteeing that a vertex is not
	 deleted more than once */
	post_accum_deleted_posts = SELECT v FROM start -(Posted>:e)- Post:v
    POST-ACCUM DELETE (v);
	/* Possible, but not recommended as the DML-sub DELETE statement occurs
	 once for each edge of the vertex v */
	accum_deleted_posts = SELECT v FROM start -(Posted>:e)- Post:v
    ACCUM DELETE (v);
}
// Need a separate query to display the results, because deletions don't take effect during the query.
CREATE QUERY select_user_posts(VERTEX<Person> seed) FOR GRAPH Social_Net {
  start = {seed};
  user_posts = SELECT v FROM start -(Posted>:e)- Post:v;
  PRINT user_posts;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

For example, the following sequence of `select_user_posts` and `delete_posts` queries
deletePosts.run
```
RUN QUERY select_user_posts("person3")
RUN QUERY delete_posts("person3")
RUN QUERY select_user_posts("person3")
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

will produce the following result:
Results from DeletePosts Example
```
// Before the deletion
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{"userPosts": [{
  "v_id": "2",
  "attributes": {
   "postTime": "2011-02-03 01:02:42",
   "subject": "query languages"
  },
  "v_type": "post"
 }]}]
}
// Deletion; no output results requested at this point
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": []
}
// After the deletion
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [{"userPosts": []}]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.11/querying/data-modification-statements#_insert_into_statement)`INSERT INTO` Statement
The `INSERT INTO` statement adds edges or vertices to the graph. When the ID value(s) for the inserted vertex/edge match those of an existing vertex/edge, the new values will overwrite the old values. To insert an edge, its endpoint vertices must already exist, either before running the query or inserted earlier in that query. The `INSERT INTO` statement can be used as a query-body-level statement or a DML-sub statement.
Like any other data modification in a query, the insertion does not take effect until the entire query is completed.
```
insertStmt := insertVertexStmt | insertEdgeStmt
insertVertexStmt := INSERT INTO (vertexType | name)
         ["(" PRIMARY_ID ["," attrName]* ")"]
         VALUES "(" ( "_" | expr ) ["," ("_" | expr)]*] ")"
insertEdgeStmt  := INSERT INTO (edgeType | EDGE name)
         ["("
          FROM "," TO “,”
          [(DISCRIMINATOR "(" attrName ("," attrName)* ")") ]
         ")"]
         VALUES "(" ( "_" | expr ) [vertexType]
         ["," ( "_" | expr ) [vertexType] ["," ("_" | expr)]*] ")"
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

There are two options for specifying the attributes of the vertex or edge type for the values provided:
  * Provide a value for the ID(s) and then each attribute, in the canonical order for the vertex or edge type. In this case, it is not necessary to explicitly name the attributes, since it is assumed that every attribute is being referenced, in order.
INSERT with implicit attribute names
```
INSERT INTO vertex_or_edge_type VALUES (full_list_of_parameter_values)
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * Name the specific attributes to be set, and then provide a corresponding list of values. The attributes can be in any order, with the exception that the IDs must come first. That is, to insert a vertex, the first attribute name must be `PRIMARY_ID`. To insert an edge, the first two attribute names must be `FROM` and `TO`.
INSERT with explicit attribute names
```
INSERT INTO vertex_type (PRIMARY_ID, specified_attributes)
VALUES (ID, values_for_specified_attributes)
INSERT INTO edge_type (FROM, TO, specified_attributes)
VALUES (value_for_from_vertex, value_for_to_vertex, **(1)**
  values_for_specified_attributes)
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | `value_for_from_vertex` and `value_for_to_vertex` can either be the ID of the vertex followed by the vertex type, separated by a space or a vertex variable.  For each attribute value, provide either an expression _expr_ or _, which means the default value for that attribute type. The optional _name_ which follows the first two (id) values is to specify the source vertex type and target vertex type, if the edge type had been defined with wildcard vertex types.  
---|---  


### [](https://docs.tigergraph.com/gsql-ref/3.11/querying/data-modification-statements#_query_body_insert)Query-Body INSERT
The following query illustrates query-body level `INSERT` statements: insert new `Company` vertices and `Works_For` edges into the `Works_Net` graph.
INSERT statement
```
CREATE QUERY insert_ex(STRING name, STRING name2, STRING name3, STRING comp) FOR GRAPH Work_Net {
  /* Vertex insertion
   Adds 2 'Company' vertices. One is located in the USA, and a sister company in Japan.
  Company:
   Company(PRIMARY_ID client_id STRING, id STRING, country STRING) */
  INSERT INTO Company VALUES ( comp, comp, "us" );
  INSERT INTO Company (PRIMARY_ID, country) VALUES ( comp + "_jp", "jp" );
  /* Edge insertion
  Adds a 'Works_For' edge from person 'name' to the company 'comp', filling in default
  values for startYear (0), startMonth (0), and fullTime (false).
  Works_For:
  Works_For(FROM person, TO company, startYear INT, startMonth INT, fullTime BOOL) */
  INSERT INTO Works_For VALUES (name Person, comp Company, _, _, _);
  /* Adds a 'Works_For' edge from person 'name2' to the company 'comp', filling in
    default values for startMonth (0), but specifying values for startYear and
    fullTime. */
  INSERT INTO Works_For (FROM, TO, start_year, full_time) VALUES (name2 Person, comp Company, 2017, true);
  /* Adds a 'Works_For' edge from person 'name3' to the company 'comp', filling in
  default values for startMonth (0), and fullTime (false) but specifying a value
  for startYear (2017). */
  INSERT INTO Works_For (FROM, TO, start_year) VALUES (name3 Person, comp Company, 2000 + 17);
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The following query can be used to check the effect of the previous query. Prior to running `insertEx`, running `whoWorksForCompany("gsql")` will find 0 `companies` called `"gsql"` and 0 `Works_For` edges for company `"gsql"`.
If we then run the query `insertEx("tic", "tac", "toe", "gsql")`, then `insertEx("gsql")` will find a company called `"gsql"` and another one called `"gsql_jp"`. Moreover, it will find 3 edges, tic, tac, and toe, with different values for the `startMonth`, `startYear`, and fullTime parameters.
Query to check the results of insertEx
```
CREATE QUERY who_works_for_company(STRING comp) FOR GRAPH Works_Net {
  SetAccum<EDGE> @@set_edge;
  Comps = {Company.*};
  PRINT Comps[Comps.id];  // output api v2
  Pers = {Person.*};
  S = SELECT s
    FROM Pers:s -(Works_For:e)- :t
    WHERE t.id == comp
    ACCUM @@set_edge += e;
  PRINT @@set_edge;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

To insert an edge with a discriminator value specified, use the `DISCRIMINATOR` keyword to specify the discriminator attributes and specify the values in order. For example, the following statement inserts an edge between two vertices with the discriminator values being 2019 and 01, respectively.
```
INSERT INTO Study_At (FROM, TO, DISCRIMINATOR(class_year, class_month))
  VALUES ("Alice" Person, "CMU" University, 2019, 01);
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/3.11/querying/data-modification-statements#_dml_sub_insert)DML-sub INSERT
The following example shows a DML-sub level INSERT. Because the statement applies to all companies, several vertices will be inserted.
DML-sub INSERT statement
```
CREATE QUERY add_new_child_company(STRING name) FOR GRAPH Work_Net {
  // Adds a child company of a given company name. The new child company is in japan
  all_companies = {Company.*};
  X = SELECT s
    FROM all_companies:s
    WHERE s.id == name
    ACCUM
      INSERT INTO Company VALUES ( name + "_jp", name + "_jp", "jp" );
}
// Adds separate query to list the companies, before and after the insertion
CREATE QUERY list_company_names(STRING country_filter) FOR GRAPH Works_Net {
 all_companies = {Company.*};
 C = SELECT s
   FROM all_companies:s
   WHERE s.country == country_filter;
 PRINT C.size() AS num_companies;
 PRINT C;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/gsql-ref/3.11/querying/data-modification-statements#_example)Example
The following queries add a child company in Japan to the US-based company `company3`. List all the Japan-based companies before and after the insertion.
addNewChildCompany.run
```
RUN QUERY list_company_names("jp")
RUN QUERY add_new_child_company("company4")
RUN QUERY list_company_names("jp")
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results from addNewChildCompany Example
```
# Before insertion
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [
  {"numCompanies": 1},
  {"C": [{
   "v_id": "company3",
   "attributes": {
    "country": "jp",
    "id": "company3"
   },
   "v_type": "company"
  }]}
 ]
}
# insert company "company4_jp"
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": []
}
# after insertion
{
 "error": false,
 "message": "",
 "version": {
  "edition": "developer",
  "schema": 0,
  "api": "v2"
 },
 "results": [
  {"numCompanies": 2},
  {"C": [
   {
    "v_id": "company3",
    "attributes": {
     "country": "jp",
     "id": "company3"
    },
    "v_type": "company"
   },
   {
    "v_id": "company4_jp",
    "attributes": {
     "country": "jp",
     "id": "company4_jp"
    },
    "v_type": "company"
   }
  ]}
 ]
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.11/querying/data-modification-statements#_update_statement)`UPDATE` Statement
The `UPDATE` statement updates the attributes of vertices or edges.
### Syntax
EBNF
```
updateStmt := UPDATE alias FROM pattern SET dmlSubStmtList [whereClause]
pattern := (vertexPattern | edgePattern)
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The set of vertices or edges to update is described in the `FROM` clause, following the same rules as the [`FROM` clause in a `SELECT` statement](https://docs.tigergraph.com/gsql-ref/3.11/querying/select-statement/). In the `SET` clause, the `dmlSubStmtList` contains assignment statements to update the attributes of a vertex or edge. Both simple base type attributes and collection type attributes can be updated. These assignment statements use the vertex or edge aliases declared in the `FROM` clause. The optional `WHERE` clause supports boolean conditions to filter the items in the vertex set or edge set.
### Examples
`UPDATE` statement example
```
CREATE QUERY update_ex() FOR GRAPH Work_Net {
  // This query changes all "Person" vertices with location equal to "us" to "USA"
  S = {Person.*};
  UPDATE s FROM S:s
  SET s.location_id = "USA", // simple base type attribute
    s.skill_list = [1,2,3] // collection-type attribute
  WHERE s.location_id == "us";
  // The update cannot become effective within this query, so PRINT S still show "us".
  PRINT S;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The `UPDATE` statement can only be used as a query-body-level statement. However, DML-sub level updates are still possible by using other statement types. A vertex attribute’s value can be updated within the `POST-ACCUM` clause of a `SELECT` block by using the assignment operator (`=`); An edge attribute’s value can be updated within the `ACCUM` clause of a `SELECT` block by using the assignment operator. In fact, the `UPDATE` statement is equivalent to a `SELECT` statement with `ACCUM` and/or `POST-ACCUM` to update the vertex or edge attribute values.
Updating a vertex’s attribute value in an `ACCUM` clause is not allowed, because the update can occur multiple times in parallel, and possibly result in a non-deterministic value. If the vertex attribute value update depends on an edge attribute value, use the vertex-attached accumulators to save the value and update the vertex attribute’s value in the `POST-ACCUM` clause.  
---  
The query below uses a `SELECT` statement instead of an `UPDATE` statement and performs the same update as the query above.
```
CREATE QUERY update_ex2() FOR GRAPH Work_Net {
  S = {Person.*};
  X = SELECT s
    FROM S:s
    WHERE S.location_id == "USA"
    POST-ACCUM S.location_id = "us",
      S.skill_list = [3,2,1];
  PRINT S;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.11/querying/data-modification-statements#_assignment_statements)Assignment statements
In addition to `UPDATE` statements and `SELECT` statements, a simple assignment statement at the query-body level can be used to update the attribute value of a single vertex or edge, if the vertex or edge has been assigned to a variable or parameter.
Update by assignment
```
// Change the given person's location
CREATE QUERY update_by_assignment(VERTEX<Person> v, STRING new_location)
  FOR GRAPH Work_Net {
 v.location_id = new_location;
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


