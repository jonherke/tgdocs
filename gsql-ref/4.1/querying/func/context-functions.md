![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions)[Next](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions)
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
[Resources](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions)
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
  * [Querying](https://docs.tigergraph.com/gsql-ref/4.1/querying/)
  * [Functions](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/)
  * [Context Functions](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/4.1/modules/querying/pages/func/context-functions.adoc)
### Contents
  * [Enable Context Functions](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_enable_context_functions)
  * [current_roles()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_current_roles)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_syntax)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_description)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_return_type)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_parameters)
  * [Example](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_example)
  * [is_granted_to_current_roles(string roleName)](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_is_granted_to_current_rolesstring_rolename)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_syntax_2)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_description_2)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_return_type_2)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_parameters_2)
  * [Example](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_example_2)


# Context Functions
### Contents
  * [Enable Context Functions](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_enable_context_functions)
  * [current_roles()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_current_roles)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_syntax)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_description)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_return_type)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_parameters)
  * [Example](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_example)
  * [is_granted_to_current_roles(string roleName)](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_is_granted_to_current_rolesstring_rolename)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_syntax_2)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_description_2)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_return_type_2)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_parameters_2)
  * [Example](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_example_2)


Context functions are a set of built-in functions that provide insights into the user’s information during their current session. They offer valuable insights into user roles, making it easier to manage access and privileges within TigerGraph.
They work in: `INSTALLED` queries, `INTERPRET` queries, and [GSQL Functions](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_gsql_functions).
## [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_enable_context_functions)Enable Context Functions
Before users can use Context Functions, you must enable REST authentication. If it's not enabled, users will see an error message. To learn more about REST authentication see [REST API Authentication](https://docs.tigergraph.com/tigergraph-server/4.2/API/authentication).
In order to use the context functions explicitly, ensure that the user holds the `READ_ROLE` privilege on the current graph, unless a [Row Policy](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/setup-row-policy#_row_policy) already includes the [Context Functions](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_context_functions).
## [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_current_roles)current_roles()
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_syntax)Syntax
`current_roles()`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_description)Description
Returns a `SetAccum` of strings of role names granted to the current user.
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_return_type)Return type
`STRING`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_parameters)Parameters
Parameter | Description | Data type  
---|---|---  
None | None | None  
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_example)Example
Then, run a query like this:
```
GSQL > create query test() {
print current_roles();
}
```

Ex. The result will show the user’s roles:
```
GSQL > run query test()
{
  "version": {
    "edition": "enterprise",
    "api": "v2",
    "schema": 0
  },
  "error": false,
  "message": "",
  "results": [
  {
    "current_roles()": [
      "USregion",
      "NAregion"
    ]
  }
  ]
}
```

## [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_is_granted_to_current_rolesstring_rolename)is_granted_to_current_roles(string roleName)
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_syntax_2)Syntax
`is_granted_to_current_roles( "roleName" )`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_description_2)Description
Returns true/false if the current user holds a particular role specified in the parameter.
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_return_type_2)Return type
`BOOL`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_parameters_2)Parameters
Parameter | Description | Data type  
---|---|---  
`roleName` | A role name to check against current users roles. | `STRING`  
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/context-functions#_example_2)Example
Ex. Create a query that prints `is_granted_to_current_roles()` and input `USregion`:
```
create query test2() {
print is_granted_to_current_roles("USregion");
}
```

Ex. Run the query and the result will show whether the user has the specified role:
```
GSQL > run query test2()
{
  "version": {
    "edition": "enterprise",
    "api": "v2",
    "schema": 0
  },
  "error": false,
  "message": "",
  "results": [
  {
    "is_granted_to_current_roles(\"USregion\")": true
  }
  ]
}
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


