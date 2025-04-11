![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries)[Next](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries)
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
[Resources](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries)
[Developer Site](https://dev.tigergraph.com/) [Community Forum](https://community.tigergraph.com/) [Knowledge Base](https://tigergraph.freshdesk.com/support/solutions)
[Download](https://dl.tigergraph.com)
[ TG Savanna](https://savanna.tgcloud.io)
### [GSQL Language Reference](https://docs.tigergraph.com/gsql-ref/4.2/intro/)
  *     * [Query Language Tutorials](https://docs.tigergraph.com/gsql-ref/4.2/tutorials/)
      * [What sets GSQL apart](https://docs.tigergraph.com/gsql-ref/4.2/intro/set-gsql-apart)
      * [GSQL V3 Tutorial](https://github.com/tigergraph/ecosys/blob/master/tutorials/GSQL.md)
      * [Accumulators Tutorial](https://docs.tigergraph.com/gsql-ref/4.2/tutorials/accumulators-tutorial)
      * [TigerGraph OpenCypher](https://github.com/tigergraph/ecosys/blob/master/tutorials/Cypher.md)
      * [Hybrid Vector Search](https://github.com/tigergraph/ecosys/tree/master/tutorials/vector)
  *     * [Running GSQL](https://docs.tigergraph.com/gsql-ref/4.2/basics/running-gsql)
  *     * [Defining a Schema](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/)
      * [Data Types](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/attribute-data-types)
      * [Define a Graph Schema](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/defining-a-graph-schema)
      * [Modify a Graph Schema](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/modifying-a-graph-schema)
    * [Loading Data](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/loading-jobs)
      * [Create a Loading Job](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/creating-a-loading-job)
        * [Functions](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/)
          * [Token Functions](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/)
            * [flatten()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/flatten)
            * [flatten_json_array()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/flatten_json_array)
            * [gsql_concat()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_concat)
            * [gsql_current_time_epoch()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_current_time_epoch)
            * [gsql_day()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_day)
            * [gsql_day_epoch()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_day_epoch)
            * [gsql_find()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_find)
            * [gsql_length()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_length)
            * [gsql_lower()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_lower)
            * [gsql_ltrim()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_ltrim)
            * [gsql_month()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_month)
            * [gsql_month_epoch()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_month_epoch)
            * [gsql_regex_match()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_regex_match)
            * [gsql_regex_replace()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_regex_replace)
            * [gsql_reverse()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_reverse)
            * [gsql_rtrim()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_rtrim)
            * [gsql_substring()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_substring)
            * [gsql_to_bool()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_to_bool)
            * [gsql_to_int()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_to_int)
            * [gsql_to_uint()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_to_uint)
            * [gsql_trim()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_trim)
            * [gsql_ts_to_epoch_seconds()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_ts_to_epoch)
            * [gsql_upper()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_upper)
            * [gsql_uuid_v4()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_uuid_v4)
            * [gsql_year()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_year)
            * [gsql_year_epoch()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/gsql_year_epoch)
            * [split()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token/split)
          * [Token Functions in WHERE Clause](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token_where/)
            * [concat()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token_where/concat)
            * [gsql_is_false()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token_where/gsql_is_false)
            * [gsql_is_not_empty()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token_where/gsql_is_not_empty)
            * [gsql_is_true()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token_where/gsql_is_true)
            * [gsql_token_equal()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token_where/gsql_token_equal)
            * [gsql_token_ignore_case_equal()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token_where/gsql_token_ignore_case_equal)
            * [to_float()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token_where/to_float)
            * [to_int()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token_where/to_int)
            * [token_len()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/token_where/token_len)
          * [Reducer functions](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/reducer/)
            * [add()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/reducer/add)
            * [and()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/reducer/and)
            * [ignore_if_exists()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/reducer/ignore_if_exists)
            * [max()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/reducer/max)
            * [min()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/reducer/min)
            * [or()](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/functions/reducer/or)
        * [Add a User-defined Token Function](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/add-token-function)
      * [Run a Loading Job](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/running-a-loading-job)
      * [Manage Loading Jobs](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/managing-loading-job)
  *     * [Querying Choices](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes)
    * [Create and Run Queries](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-operations)
      * [Distributed Query Mode](https://docs.tigergraph.com/gsql-ref/4.2/querying/distributed-query-mode)
    * [GSQL Language](https://docs.tigergraph.com/gsql-ref/4.2/querying/)
      * [GSQL Syntax Versions](https://docs.tigergraph.com/gsql-ref/4.2/querying/syntax-versions)
      * [Data Types](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types)
      * [Accumulators](https://docs.tigergraph.com/gsql-ref/4.2/querying/accumulators)
      * [SELECT Statement](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/)
        * [SELECT Statement (Syntax V1)](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/select-statement-v1)
        * [SQL-like SELECT statement](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/sql-like-select-statement)
      * [Operators and Expressions](https://docs.tigergraph.com/gsql-ref/4.2/querying/operators-and-expressions)
      * [Functions](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/)
        * [Aggregation Functions](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/aggregation-functions)
        * [Context Functions](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/context-functions)
        * [Datetime Functions](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/datetime-functions)
        * [Edge Methods](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/edge-methods)
        * [JSON Object Methods](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/json-object-methods)
        * [JSON Array Methods](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/jsonarray-methods)
        * [List Functions](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/list-functions)
        * [Mathematical Functions](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/mathematical-functions)
        * [Miscellaneous Functions](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/miscellaneous-functions)
        * [Query User-Defined Functions](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/query-user-defined-functions)
        * [String Functions](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/string-functions)
        * [Type Conversion Functions](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/type-conversion-functions)
        * [Vector Functions](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/vector-functions)
        * [Vertex Functions](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/vertex-methods)
      * [Declaration and Assignment Statements](https://docs.tigergraph.com/gsql-ref/4.2/querying/declaration-and-assignment-statements)
      * [Control Flow](https://docs.tigergraph.com/gsql-ref/4.2/querying/control-flow-statements)
      * [Updating Data](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-modification-statements)
      * [Writing Output](https://docs.tigergraph.com/gsql-ref/4.2/querying/output-statements-and-file-objects)
        * [Write Output to Cloud](https://docs.tigergraph.com/gsql-ref/4.2/querying/write-output-to-cloud)
      * [Exception Statements](https://docs.tigergraph.com/gsql-ref/4.2/querying/exception-statements)
      * [Comments](https://docs.tigergraph.com/gsql-ref/4.2/querying/comments)
    * Profile and Optimize
      * [Query Plan Cache](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-plan-cache)
      * [Query Profiling](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling)
      * [Query Optimizer (Preview)](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/)
        * [Enable Query Optimizer](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/enable-cost-optimizer)
        * [Statistics REST APIs](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/stats-api)
  *     * [openCypher in GSQL](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/)
      * [Writing and Running openCypher in GSQL Shell](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/openCypher-in-gsql-web-shell)
      * [openCypher Pattern Support in GSQL](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/openCypher-gsql-from-clause-extension)
  *     * [Vector Searches](https://docs.tigergraph.com/gsql-ref/4.2/vector/)
  *     * Appendix
      * [Common Errors and Problems](https://docs.tigergraph.com/gsql-ref/4.2/appendix/common-errors-and-problems)
      * [DLL Keywords & Reserved Words](https://docs.tigergraph.com/gsql-ref/4.2/appendix/keywords-and-reserved-words)
      * [Documentation Notation](https://docs.tigergraph.com/gsql-ref/4.2/appendix/notations)
      * [Example Graphs](https://docs.tigergraph.com/gsql-ref/4.2/appendix/example-graphs)
      * [GSQL Cheat Sheets](https://docs.tigergraph.com/gsql-ref/4.2/appendix/cheat-sheets)
      * [GSQL Start-to-End Process and Data Flow](https://docs.tigergraph.com/gsql-ref/4.2/appendix/gsql-start-to-end-process)
      * [GSQL Style Guide](https://docs.tigergraph.com/gsql-ref/4.2/appendix/gsql-style-guide)
      * [Interpreted GSQL Limitations](https://docs.tigergraph.com/gsql-ref/4.2/appendix/interpreted-gsql-limitations)
      * [Legacy Version Documentation](https://docs.tigergraph.com/gsql-ref/4.2/appendix/legacy-tg-versions)
      * [Query Language Keywords & Reserved Words](https://docs.tigergraph.com/gsql-ref/4.2/appendix/query-language-reserved-words)


GSQL Language Reference 4.2 Pre
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
  * [GSQL Language Reference 4.2 Pre](https://docs.tigergraph.com/gsql-ref/4.2/intro/)
  * [CREATE/INSTALL QUERY](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/4.2/modules/querying/pages/create-and-install-queries.adoc)
### Contents
  * [CREATE QUERY](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries#_create_query)
  * [Required privilege](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries#_required_privilege)
  * [Basic Syntax and Example](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries#_basic_syntax_and_example)
  * [Full Syntax and Options](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries#_full_syntax_and_options)
  * [Key Parts of CREATE QUERY](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries#_key_parts_of_create_query)
  * [Examples](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries#_examples)
  * [Default query parameter values](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries#_default_query_parameter_values)
  * [Dynamic querying](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries#_dynamic_querying)
  * [Draft queries](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries#_draft_queries)
  * [Statement types](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries#_statement_types)
  * [INSTALL QUERY](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries#_install_query)


# Create and Install Queries
Table of Contents
  * [CREATE QUERY](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries#_create_query)
    * [Required privilege](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries#_required_privilege)
    * [Basic Syntax and Example](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries#_basic_syntax_and_example)
    * [Full Syntax and Options](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries#_full_syntax_and_options)
    * [Key Parts of CREATE QUERY](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries#_key_parts_of_create_query)
    * [Examples](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries#_examples)
    * [Default query parameter values](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries#_default_query_parameter_values)
    * [Dynamic querying](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries#_dynamic_querying)
    * [Draft queries](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries#_draft_queries)
  * [Statement types](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries#_statement_types)
  * [INSTALL QUERY](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries#_install_query)


This page describes the [CREATE QUERY](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries#_create_query) and [INSTALL QUERY](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries#_install_query) commands, the steps that precede running an installed (compiled) procedural query. See
## [](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries#_create_query)CREATE QUERY
Define and store a procedural query in the catalog for future use. The syntax of the query is checked but it is not compiled.
### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries#_required_privilege)Required privilege
`CREATE_QUERY` or `UPDATE_QUERY`
  * To create a new query, `CREATE_QUERY` privilege is needed.
  * To replace (update) a query, `UPDATE_QUERY` privilege is needed.


### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries#_basic_syntax_and_example)Basic Syntax and Example
Basic Syntax, with only the most common options
```
createQuery := CREATE [OR REPLACE] [DISTRIBUTED] [OPENCYPHER] queryName
        "(" [parameterList] ")"
        [FOR GRAPH graphName]
        "{" queryBody "}"
queryBody := [declStmts] queryBodyStmts
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Example
```
CREATE OR REPLACE DISTRIBUTE QUERY listTopBooks **(1)**
  (INT k = 10) **(2)**
{
  AvgAccum<INT> @avg_rating; **(3)**
  books = SELECT b **(4)**
    FROM (u:User) -[r:User_Book_Rating]- (b:Book)
    ACCUM b.@avg_rating := r.rating
    ORDER BY b.@avg_rating DESC
    LIMIT k;
  PRINT books;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | The `queryName` is `listTopBooks`.  
---|---  
**2** | The `[parameterList]` is a single parameter with a default value of 10.  
**3** | There is one `declStmt` : a local accumulator AvgAccum to compute average ratings of books.  
**4** | The `queryBodyStmts` has one `SELECT` and one `PRINT` statement.  
### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries#_full_syntax_and_options)Full Syntax and Options
Full syntax for CREATE QUERY
```
createQuery := CREATE [OR REPLACE] [TEMPLATE | DISTRIBUTED] QUERY
        [packageName["."packageName].]queryName
        "(" [parameterList] ")"
        [FOR GRAPH graphName]
        [RETURNS "(" baseType | accumType ")"]
        [API "(" apiName ")"]
        [SYNTAX syntaxName]
        "{" queryBody "}"
queryBody := [typedefs] [declExceptStmts] queryBodyStmts
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries#_key_parts_of_create_query)Key Parts of CREATE QUERY 

`OR REPLACE`
    
If the optional keywords `OR REPLACE` are included, then this query definition, if error-free, replaces a previous definition with the same query name. If the original query was installed, you’ll need to reinstall the new query.
However, if there are any errors in this query definition, then the previous query definition is maintained. If the `OR REPLACE` option is not used, GSQL rejects a `CREATE QUERY` command that uses an existing name. 

`DISTRIBUTED`
    
The `DISTRIBUTED` option applies only to installations where the graph has been distributed across a cluster. If specified, the query will run with a different execution model which may give better performance for queries that traverse a large portion of the cluster. For details, see [Distributed Query Mode.](https://docs.tigergraph.com/gsql-ref/4.2/querying/distributed-query-mode) 

`queryName`
    
Name of the query. 

`parameterList`
    
A list of parameters for the query. The parameter list for a query follows the following form:
```
parameterType paramName ["=" constant] ["," parameterType paramName ["=" constant]]*
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

For a list of allowed data types for query parameters, see [Query parameter types](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_query_parameter_types). 

`FOR GRAPH graphName`
    
Specifies the graph that the query is created on. This clause is optional if you have already specified a working graph either when entering GSQL or through the `USE GRAPH` command. 

`RETURNS` clause
    
The optional `RETURNS` clause makes the query a subquery and specifies the data type to be returned in the `RETURN` statement of the subquery. For more information, see [Subqueries](https://docs.tigergraph.com/gsql-ref/4.2/querying/operators-and-expressions#_subqueries). 

`API v2`
    
Specifies the JSON output format. The only option is v2. 

`SYNTAX syntaxName`
    
Specifies the GSQL syntax version to be used by the query. See the [GSQL Syntax Versions](https://docs.tigergraph.com/gsql-ref/4.2/querying/syntax-versions) for an outline of the differences. See [Pattern Matching tutorial](https://docs.tigergraph.com/gsql-ref/4.2/tutorials/pattern-matching/) for details on v2. 

`queryBody`
    
The query body contains a sequence of data retrieval-and-computation statements.
Typedefs allow the definition of custom types for use within the body. The declarations support the definition of _accumulators_ (see Chapter "[Accumulators](https://docs.tigergraph.com/gsql-ref/4.2/querying/accumulators)" for more details) and global/local variables. All accumulators and global variables must be declared before any statements.There are various types of statements that can be used within the body.
Typically, the core statement(s) in the body of a query is one or more `SELECT`, `UPDATE`, `INSERT`, `DELETE` statements. The language supports conditional statements such as an `IF` statement as well as looping constructs such as `WHILE` and `FOREACH`. It also supports calling functions, assigning variables, printing, and modifying the graph data.
The query body may include calls to other queries. That is, the other queries are treated as subquery functions. See the subsection on "[subqueries](https://docs.tigergraph.com/gsql-ref/4.2/querying/operators-and-expressions#_subqueries)".
Additionally, GSQL supports openCypher syntax in the query body. See pages [openCypher in GSQL](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/), [Writing and Running openCypher in GSQL Shell](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/openCypher-in-gsql-web-shell), and [openCypher Pattern Support in GSQL](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/openCypher-gsql-from-clause-extension) to learn more about openCypher and for examples.
### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries#_examples)Examples
Example of a `CREATE QUERY` statement
```
CREATE QUERY create_query_ex (STRING uid) FOR GRAPH Social_Net RETURNS (int) SYNTAX v2 {
  // declaration statements
  users = {Person.*};
  // body statements
  posts = SELECT p
    FROM users:u-(Posted>)-:p
    WHERE u.id == uid;
  PRINT posts;
  RETURN posts.size();
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries#_default_query_parameter_values)Default query parameter values
You can specify default values for parameters of primitive types when creating a query. Primitive types include:
  * `INT`
  * `UINT`
  * `FLOAT`
  * `DOUBLE`
  * `STRING`
  * `BOOL`
  * `DATETIME`


To specify the default value for a parameter, use the assignment operator (`=`) after the parameter name and specify the default value:
Example of a `CREATE QUERY` command with a default parameter value
```
CREATE QUERY create_query_ex (STRING uid = "Tom") FOR GRAPH Social_Net RETURNS (int) SYNTAX v2 {
  // declaration statements
  users = {Person.*};
  // body statements
  posts = SELECT p
    FROM users:u-(Posted>)-:p
    WHERE u.id == uid;
  PRINT posts;
  RETURN posts.size();
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

To specify the default value of a `DATETIME` type parameter, use the `to_datetime()` function. You cannot use other functions that return a `DATETIME` value to specify the default value. For example, the following query definition sets the default value of `d1` to `2023-01-01 00:00:00`.
```
CREATE QUERY print_default(DATETIME d1 = to_datetime("2023-01-01 00:00:00")) {
  PRINT d1;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries#_dynamic_querying)Dynamic querying
TigerGraph 3.0+ supports Dynamic Querying. This means the query can be written and installed as a saved procedure without referencing a particular graph. Schema details — the name of the graph, vertex types, edge types, and attributes — can all be parameterized and only need to be specified at run time.
Here are the ingredients for a dynamic query:
  * **Graph name:** When [creating a query](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-operations#_create_query), **`FOR GRAPH graphName`**is optional, as long as the graph has been specified already. The graph name can be specified either when entering GSQL:**`GSQL -g graphName [<gsql_command>]`**or once inside the GSQL shell, by using the**`USE GRAPH graphName`**command.
  * **Vertex type and edge type in`SELECT` statements**. Typically, the [`FROM` clause](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/#_from_clause) mentions the name of specific vertex types and edge types. String or string set parameters can be used for edge and target types instead.
  * **Attribute names**. The [`getAttr` and `setAttr` functions](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/vertex-methods), which take attribute name and data type as string parameters, can be used to parameterize attribute access.
  * `INSERT` **statements** : If you are using [`INSERT`](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-modification-statements#_insert_into_statement) to add data to your graph, you need to specify what type of vertex or edge you want to add.This can also be parameterized.


The following example demonstrates Dynamic GSQL Query techniques using the [PageRank algorithm](https://docs.tigergraph.com/graph-ml/3.10/centrality-algorithms/pagerank) from our Graph Data Science library. The query is written with schema information embedded statically in it:
  * graph name = social
  * vertex type = Page
  * edge type = Link
  * vertex attribute = Score


  * Embedded schema
  * Dynamic querying


```
CREATE QUERY page_rank (FLOAT max_change=0.00, INT max_iter=25,
  FLOAT damping=0.85) // parameters
  FOR GRAPH Gsql_Demo
  {
  MaxAccum<float> @@max_diff = 9999;
  SumAccum<float> @rcvd_score = 0;
  SumAccum<float> @score = 1;
  Start = {Page.*};
  WHILE @@maxDiff > max_change LIMIT max_iter DO
    @@maxDiff = 0;
    V = SELECT s
      FROM Start:s -(Linkto:e)- Page:t    // hardcoded types
      ACCUM t.@rcvd_score += s.@score/(s.outdegree("Linkto")) // Param
      POST-ACCUM s.@score = (1.0-damping) + damping * s.@rcvd_score, s.@rcvd_score = 0, @@max_diff += abs(s.@score - s.@score');
  END;
  V = SELECT s FROM Start:s
   POST-ACCUM s.Score = s.@score;  // hardcoded attribute
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
CREATE QUERY pagerank_dyn (FLOAT max_change=0.00, INT max_iter=25,
 FLOAT damping=0.85, STRING v_type, STRING e_type, STRING attr)
{
  MaxAccum<FLOAT> @@max_diff = 9999;
  SumAccum<FLOAT> @rcvd_score = 0;
  SumAccum<FLOAT> @score = 1;
  Start = {v_type};
  WHILE @@max_diff > max_change LIMIT max_iter DO
    @@max_diff = 0;
    V = SELECT s
      FROM Start:s -(e_type:e)- v_type:t // Parameterized
      ACCUM t.@rcvd_score += s.@score/(s.outdegree(e_type)) //param
      POST-ACCUM s.@score = (1.0-damping) + damping * s.@rcvd_score,
        s.@rcvd_score = 0,
        @@max_diff += abs(s.@score - s.@score');
  END;
  V = SELECT s FROM Start:s
    POST-ACCUM s.setAttr(attr, s.@score); // Parameterized
}
RUN QUERY pagerank_dyn(_,_,_,"Page", "Link", "Score")
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries#_draft_queries)Draft queries
GSQL internally has two statuses for queries, `DRAFT` and `VALID`.
If your query passes the semantic checks upon running the `CREATE QUERY` command, it is saved automatically in `VALID` status. If not, along with the error statement, a message appears to indicate the draft status.
In this example, the first query gets saved upon running `CREATE QUERY`, while the second one remains a draft.
```
GSQL > CREATE QUERY valid_query(){  print 1; }
Successfully created queries: [valid_query].

GSQL > BEGIN
GSQL > CREATE QUERY draft_query(){
GSQL >  PRINT;
GSQL >  PRINT "I am a draft"
GSQL > }
GSQL > END
line 2:7 mismatched input ';' expecting {ABORT, AND, ANY, AVG, BY, COALESCE, COMMIT, COUNT, DATETIME_ADD, DATETIME_SUB, DISTINCT, FALSE, FILE, GROUP, INSERT, ISEMPTY, LASTHOP, LIST, LOG, MAP, MATCH, MAX, MIN, NOT, NOW, OR, PATH, PER, RANGE, REPLACE, SELECT_VERTEX, SET, SRC, SUM, TGT, TO_DATETIME, TRIM, TRUE, UPDATE, GSQL_INT_MAX, GSQL_INT_MIN, GSQL_UINT_MAX, '__ENGINE__E_ATTR', '__ENGINE__SRC_ATTR', '__ENGINE__TGT_ATTR', '__ENGINE__V_ATTR', '__ENGINE__SRC_VAL', '__ENGINE__TGT_VAL', '__ENGINE__V_VAL', '__ENGINE__MESSAGE', '__ENGINE__CONTEXT', '__ENGINE__REQUEST', '__ENGINE__SERVICEAPI', '(', '[', '-', '.', '_', CONST_INT, CONST_STR, NAME, GACCNAME}
line 4:0 mismatched input '}' expecting {TO_CSV, WHERE, ',', ';'}
Parsing encountered 2 syntax error(s)
Saved as draft query with type/semantic error: [draft_query].
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Because the query status is determined and saved internally, there are no commands for users to choose to save valid queries as `DRAFT` status.
Queries are not saved as drafts in the following situations:
  * The user does not have the correct permissions to create a query.
  * An existing valid query has the same name, and there is no `REPLACE` command used while creating the new query.
  * An existing valid query is called by another query.
    * The new query will change its signature (parameters or return type).
  * A circular call is detected, where `queryA` calls `queryB and `queryB` calls `queryA`.
    * However, a recursive call (A calls A) is allowed.


If a query is saved as a draft before it reaches valid status, any queries that call it are also set to draft status.
If a user creates a query, this user becomes the owner of this query automatically. For a detailed description, please refer to xref:xref:tigergraph-server:user-access:fine-grained-query-privileges.adoc  
---  
## [](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries#_statement_types)Statement types
A _statement_ is a standalone instruction that expresses an action to be carried out. The most common statements are _data manipulation language (DML) statements_. DML statements include the `SELECT`, `UPDATE`, `INSERT INTO`, `DELETE FROM`, and `DELETE` statements.
A GSQL query has two levels of statements. The upper-level statement type is called _query-body-level statement_ , or _*query-body statement*_ for short. This statement type is part of either the top-level block or a query-body control flow block. For example, each of the statements at the top level directly under `CREATE QUERY` is a query-body statement. If one of the statements is a `CASE` statement with several `THEN` blocks, each of the statements in the `THEN` blocks is also a query-body statement. Each query-body statement ends with a semicolon.
The lower-level statement type is called _DML-sub-level statement_ or _DML-sub statement_ for short. This statement type is used inside certain query-body DML statements, to define particular data manipulation actions.DML-sub-statements are comma-separated. There is no comma or semicolon after the last DML-sub-statement in a block. For example, one of the top-level statements is a `SELECT` statement, each of the statements in its `ACCUM` clause is a DML-sub-statement. If one of those DML-sub-statements is a `CASE` statement, each of the statement in the `THEN` blocks is a DML-sub-statement.
There is some overlap in the types. For example, an assignment statement can be used either at the query-body level or the DML-sub-level.
```
queryBodyStmts := (queryBodyStmt ";")+
queryBodyStmt := assignStmt      // Assignment
        | vSetVarDeclStmt   // Declaration
        | gAccumAssignStmt   // Assignment
        | gAccumAccumStmt   // Assignment
        | lAccumAccumStmt   // Assignment
        | funcCallStmt     // Function Call
        | selectStmt      // Select
        | queryBodyCaseStmt  // Control Flow
        | queryBodyIfStmt   // Control Flow
        | queryBodyWhileStmt  // Control Flow
        | queryBodyForEachStmt // Control Flow
        | BREAK        // Control Flow
        | CONTINUE       // Control Flow
        | updateStmt      // Data Modification
        | insertStmt      // Data Modification
        | queryBodyDeleteStmt // Data Modification
        | printStmt      // Output
        | printlnStmt     // Output
        | logStmt       // Output
        | returnStmt      // Output
        | raiseStmt      // Exception
        | tryStmt       // Exception
DMLSubStmtList := DMLSubStmt ["," DMLSubStmt]*
DMLSubStmt := assignStmt      // Assignment
      | funcCallStmt     // Function Call
      | gAccumAccumStmt   // Assignment
      | lAccumAccumStmt   // Assignment
      | attrAccumStmt    // Assignment
      | vAccumFuncCall    // Function Call
      | localVarDeclStmt   // Declaration
      | DMLSubCaseStmt    // Control Flow
      | DMLSubIfStmt     // Control Flow
      | DMLSubWhileStmt   // Control Flow
      | DMLSubForEachStmt  // Control Flow
      | BREAK        // Control Flow
      | CONTINUE       // Control Flow
      | insertStmt      // Data Modification
      | DMLSubDeleteStmt   // Data Modification
      | printlnStmt     // Output
      | logStmt       // Output
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Guidelines for understanding statement type hierarchy:
  * Top-level statements are Query-Body type (each statement ending with a semicolon).
  * The statements within a DML statement are DML-sub statements (comma-separated list).
  * The blocks within a Control Flow statement have the same type as the entire Control Flow statement itself.


Schematic illustration of relationship between queryBodyStmt and DMLSubStmt
```
CREATE QUERY stmt_types (parameterList) FOR GRAPH g [
	other queryBodyStmt1;
	ControlFlow queryBodyStmt2  // ControlFlow inside top level.
		other queryBodyStmt2.1;   // subStmts in ControlFlow are queryBody unless inside DML.
		ControlFlow queryBodyStmt2.2 // ControlFlow inside ControlFlow inside top level
			other queryBodyStmt2.2.1;
			other queryBodyStmt2.2.2;
		END;
		DML queryBodyStmt2.3   // DML inside ControlFlow inside top-level
			other DMLSubStmt2.3.1,  // switch to DMLSubStmt
			other DMLSubStmt2.3.2
		;
	END;
	DML queryBodyStmt3      // DML inside top level.
		other DMLSubStmt3.1,   // All subStmts in DML must be DMLSubStmt type
		ControlFlow DMLSubStmt3.2 // ControlFlow inside DML inside top level
			other DMLSubStmt3.2.1,
			other DMLSubStmt3.2.2
		,
		DML DMLsubStmt3.3
			other DMLSubStmt3.3.1,
			other DMLSubStmt3.3.2
	;
	other queryBodyStmt4;
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Here is a descriptive list of query-body statements:
EBNF term | Common Name | Description  
---|---|---  
assignStmt | Assignment Statement | See "Declaration and Assignment Statements"  
vSetVarDeclStmt | Vertex Set Variable Declaration Statement | See "Declaration and Assignment Statements"  
gAccumAssignStmt | Global Accumulator Assignment Statement | See "Declaration and Assignment Statements"  
gAccumAccumStmt | Global Accumulator Accumulation Statement | See "Declaration and Assignment Statements"  
lAccumAccumStmt | Local Accumulator Accumulation Statement | See "Declaration and Assignment Statements"  
funcCallStmt | Functional Call or Query Call Statement | See "Declaration and Assignment Statements"  
selectStmt | SELECT Statement | See "SELECT Statement"  
queryBodyCaseStmt | query-body CASE statement | See "Control Flow Statements"  
queryBodyIfStmt | query-body IF statement | See "Control Flow Statements"  
queryBodyWhileStmt | query-body WHILE statement | See "Control Flow Statements"  
queryBodyForEachStmt | query-body FOREACH statement | See "Control Flow Statements"  
updateStmt | UPDATE Statement | See "Data Modification Statements"  
insertStmt | INSERT INTO statement | See "Data Modification Statements"  
queryBodyDeleteStmt | Query-body DELETE Statement | See "Data Modification Statements"  
printStmt | PRINT Statement | See "Output Statements"  
logStmt | LOG Statement | See Output Statements"  
returnStmt | RETURN Statement | See "Output Statements"  
raiseStmt | PRINT Statement | See "Exception Statements"  
tryStmt | TRY Statement | See "Exception Statements"  
Here is a descriptive list of DML-sub-statements:
EBNF term | Common Name | Description  
---|---|---  
assignStmt | Assignment Statement | See "Declaration and Assignment Statements"  
funcCallStmt | Functional Call Statement | See "Declaration and Assignment Statements"  
gAccumAccumStmt | Global Accumulator Accumulation Statement | See "Declaration and Assignment Statements"  
lAccumAccumStmt | Local Accumulator Accumulation Statement | See "Declaration and Assignment Statements"/  
attrAccumStmt | Attribute Accumulation Statement | See "Declaration and Assignment Statements"  
vAccumFuncCall | Vertex-attached Accumulator Function Call Statement | See "Declaration and Assignment Statements"  
localVarDeclStmt | Local Variable Declaration Statement | See "SELECT Statement"  
insertStmt | INSERT INTO Statement | See "Control Flow Statements"  
DMLSubDeleteStmt | DML-sub DELETE Statement | See "Data Modification Statements"  
DMLSubcaseStmt | DML-sub CASE statement | See "Data Modification Statements"  
DMLSubIfStmt | DML-sub IF statement | See "Data Modification Statements"  
DMLSubForEachStmt | DML-sub FOREACH statement | See "Data Modification Statements"  
DMLSubWhileStmt | DML-sub WHILE statement | See "Data Modification Statements"  
logStmt | LOG Statement | See "Output Statements"  
## [](https://docs.tigergraph.com/gsql-ref/4.2/querying/create-and-install-queries#_install_query)INSTALL QUERY
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


