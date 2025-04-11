![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions)[Next](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions)
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
[Resources](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions)
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
  * [String Functions](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/4.1/modules/querying/pages/func/string-functions.adoc)
### Contents
  * [ascii()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_ascii)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters)
  * [Example](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_example)
  * [chr()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_chr)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_2)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_2)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_2)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_2)
  * [Examples](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_examples)
  * [difference()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_difference)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_3)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_3)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_3)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_3)
  * [Examples](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_examples_2)
  * [find_in_set()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_find_in_set)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_4)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_4)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_4)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_4)
  * [Example](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_example_2)
  * [gsql_uuid_v4()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_gsql_uuid_v4)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_5)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_5)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_5)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_5)
  * [insert()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_insert)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_6)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_6)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_6)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_6)
  * [Examples](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_examples_3)
  * [instr()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_instr)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_7)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_7)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_7)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_7)
  * [Example](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_example_3)
  * [left()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_left)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_8)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_8)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_8)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_8)
  * [length()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_length)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_9)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_9)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_9)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_9)
  * [Example](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_example_4)
  * [ltrim()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_ltrim)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_10)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_10)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_10)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_10)
  * [lower()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_lower)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_11)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_11)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_11)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_11)
  * [Example](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_example_5)
  * [lpad()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_lpad)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_12)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_12)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_12)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_12)
  * [Example](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_example_6)
  * [repeat()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_repeat)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_13)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_13)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_13)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_13)
  * [Example](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_example_7)
  * [replace()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_replace)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_14)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_14)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_14)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_14)
  * [Examples](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_examples_4)
  * [reverse()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_reverse)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_15)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_15)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_15)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_15)
  * [Examples](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_examples_5)
  * [right()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_right)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_16)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_16)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_16)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_16)
  * [rpad()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_rpad)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_17)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_17)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_17)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_17)
  * [Example](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_example_8)
  * [rtrim()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_rtrim)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_18)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_18)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_18)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_18)
  * [soundex()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_soundex)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_19)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_19)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_19)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_19)
  * [Examples](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_examples_6)
  * [space()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_space)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_20)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_20)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_20)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_20)
  * [Examples](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_examples_7)
  * [substr()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_substr)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_21)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_21)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_21)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_21)
  * [Example](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_example_9)
  * [translate()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_translate)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_22)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_22)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_22)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_22)
  * [Examples](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_examples_8)
  * [trim()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_trim)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_23)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_23)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_23)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_23)
  * [Example](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_example_10)
  * [upper()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_upper)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_24)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_24)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_24)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_24)
  * [Example](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_example_11)


# String Functions
### Contents
  * [ascii()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_ascii)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters)
  * [Example](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_example)
  * [chr()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_chr)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_2)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_2)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_2)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_2)
  * [Examples](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_examples)
  * [difference()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_difference)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_3)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_3)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_3)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_3)
  * [Examples](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_examples_2)
  * [find_in_set()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_find_in_set)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_4)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_4)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_4)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_4)
  * [Example](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_example_2)
  * [gsql_uuid_v4()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_gsql_uuid_v4)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_5)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_5)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_5)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_5)
  * [insert()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_insert)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_6)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_6)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_6)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_6)
  * [Examples](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_examples_3)
  * [instr()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_instr)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_7)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_7)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_7)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_7)
  * [Example](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_example_3)
  * [left()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_left)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_8)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_8)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_8)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_8)
  * [length()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_length)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_9)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_9)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_9)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_9)
  * [Example](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_example_4)
  * [ltrim()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_ltrim)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_10)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_10)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_10)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_10)
  * [lower()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_lower)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_11)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_11)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_11)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_11)
  * [Example](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_example_5)
  * [lpad()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_lpad)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_12)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_12)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_12)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_12)
  * [Example](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_example_6)
  * [repeat()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_repeat)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_13)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_13)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_13)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_13)
  * [Example](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_example_7)
  * [replace()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_replace)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_14)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_14)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_14)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_14)
  * [Examples](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_examples_4)
  * [reverse()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_reverse)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_15)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_15)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_15)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_15)
  * [Examples](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_examples_5)
  * [right()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_right)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_16)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_16)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_16)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_16)
  * [rpad()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_rpad)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_17)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_17)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_17)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_17)
  * [Example](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_example_8)
  * [rtrim()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_rtrim)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_18)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_18)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_18)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_18)
  * [soundex()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_soundex)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_19)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_19)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_19)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_19)
  * [Examples](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_examples_6)
  * [space()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_space)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_20)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_20)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_20)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_20)
  * [Examples](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_examples_7)
  * [substr()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_substr)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_21)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_21)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_21)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_21)
  * [Example](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_example_9)
  * [translate()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_translate)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_22)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_22)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_22)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_22)
  * [Examples](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_examples_8)
  * [trim()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_trim)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_23)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_23)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_23)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_23)
  * [Example](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_example_10)
  * [upper()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_upper)
  * [Syntax](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_24)
  * [Description](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_24)
  * [Return type](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_24)
  * [Parameters](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_24)
  * [Example](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_example_11)


This page lists the string functions available in the GSQL query language. Examples of string functions are converting to uppercase or lowercase, padding or trimming characters, extracting substrings and comparing phonetic values for English words.
For type conversion functions, such as converting a `STRING` to an `int` or `DATETIME`, please see the [Type Conversion Functions](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/type-conversion-functions) page.
## [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_ascii)ascii()
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax)Syntax
`ascii( str )`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description)Description
Returns the ASCII (numeric) position of the first character in a string. If the argument is an empty string, returns 0.
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type)Return type
`INT`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters)Parameters
Parameter | Description | Data type  
---|---|---  
`str` | A string value | `STRING`  
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_example)Example
```
ascii("") => 0
ascii("A") => 65
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_chr)chr()
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_2)Syntax
`chr( n )`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_2)Description
Converts an integer to a character according to its ASCII position. If the input value `n` is greater than 255, returns the character at the position of the modulo of `n / 256`.
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_2)Return type
`STRING`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_2)Parameters
Parameter | Description | Data type  
---|---|---  
`n` | An integer value | `INT`  
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_examples)Examples
```
chr(65) => 'A'
chr(322) => 'B'
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_difference)difference()
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_3)Syntax
`difference(str1, str2)`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_3)Description
Compares the [Soundex codes](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_soundex) of two strings and returns an integer. The return value ranges from 0 to 4, and it indicates the similarity between the input strings' phonetic representation values.
0 indicates weak similarity, and 4 indicates strong similarity with identical phonetic representation values.
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_3)Return type
`INT`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_3)Parameters
Parameter | Description | Data type  
---|---|---  
`str1` | A string value | `STRING`  
`str2` | A string value | `STRING`  
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_examples_2)Examples
```
difference("Johnson", "Jonson") => 4
difference("Adams", "Addamms") => 4
difference("Mary", "Bob") => 2
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_find_in_set)find_in_set()
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_4)Syntax
`find_in_set(str, str_list)`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_4)Description
Returns the position of a string within a list of strings separated by commas.
If `string` is not found in `string_list`, this function returns -1.
`find_in_set` does _not_ ignore whitespace after a comma. For example, `find_in_set("a", "b, a, a") = -1`, indicating that `a` is not an element in the list. This happens because the second and third elements of the list are `space+a`, rather than `a`.   
---  
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_4)Return type
`INT`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_4)Parameters
Parameter | Description | Data type  
---|---|---  
`str` | A string value | `STRING`  
`str_list` | A string representation of a list of strings. | `STRING`  
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_example_2)Example
```
find_in_set("a","b,c,d") => -1
find_in_set("a","a,b,c") => 0
find_in_set("a","b,a,d") => 1
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_gsql_uuid_v4)gsql_uuid_v4()
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_5)Syntax
`gsql_uuid_v4()`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_5)Description
Generates and returns a [version-4 universally unique identifier (UUID)](https://en.wikipedia.org/wiki/Universally_unique_identifier#Version_4_\(random\)).
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_5)Return type
`STRING`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_5)Parameters
None.
## [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_insert)insert()
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_6)Syntax
`insert(str1, position[, number], str2)`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_6)Description
Inserts a string within a string at the specified position and for a certain number of characters, and replaces a specified number of characters starting from the insertion position. The starting index is 0.
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_6)Return type
`STRING`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_6)Parameters
Parameter | Description | Data type  
---|---|---  
`str1` | The string to insert another string into | `STRING`  
`position` | The index of the starting position to insert the string | `INT`  
`number` | Optional. The number of characters from the original string that will be replaced. If the argument is left off, it defaults to 0. | `STRING`  
`str2` | The string to be inserted | `STRING`  
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_examples_3)Examples
```
insert("tigergraph.com", 0, 10, "Example") => "Example.com”
insert("tigergraph.com", 0, 2, "Example") => "Examplegergraph.com”
insert("tigergraph.com", 2, 20, "Example") => ”tiExample”
insert("Complete blank.", 9, "every ") => "Complete every blank."
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_instr)instr()
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_7)Syntax
`instr (str, substr [, position, occurrence])`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_7)Description
Searches a string `str` for a substring `substr` and returns the location of the substring in the string. If a substring that is equal to `substr` is found, then the function returns an integer indicating the position of the first character of this substring. If no such substring is found, then the function returns -1.
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_7)Return type
`INT`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_7)Parameters
Parameter | Description | Data type  
---|---|---  
`str` | The string to search | `STRING`  
`substr` | The string to search for in `str` | `STRING`  
`position` | Optional. The position is a nonzero integer indicating the character of `str` from where the search begins. If omitted, it defaults to 0. The first position in the string is 0. If `position` is negative, then the function counts backward from the end of `str` and then searches backward from the resulting position. | `STRING`  
`occurrence` | Optional, The occurrence is an integer indicating which occurrence of `substr` in `str` the function should search for. | `STRING`  
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_example_3)Example
```
instr("This is the thing", "Th") -> 0;
instr("This is the thing", "is", 3) -> 5;
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_left)left()
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_8)Syntax
`left(str, number_of_chars)`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_8)Description
Extracts a number of characters from a string starting from position 0 (capturing left to right).
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_8)Return type
`STRING`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_8)Parameters
Parameter | Description | Data type  
---|---|---  
`str` | A string value | `STRING`  
`number_of_chars` | The number of characters to extract | `INT`  
## [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_length)length()
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_9)Syntax
`length(str)`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_9)Description
Returns the length of the input string.
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_9)Return type
`INT`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_9)Parameters
Parameter | Description | Data type  
---|---|---  
`str` | The string whose length to evaluate | `STRING`  
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_example_4)Example
```
length("hello world") -> 11
length("") -> 0
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_ltrim)ltrim()
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_10)Syntax
`ltrim( str[, set] )`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_10)Description
Removes all occurrences of the characters contained in a set from a string from the left side.
The function begins scanning the string from its first character, removing all characters that appear in `set` until reaching a character not in `set`, then returning the result.
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_10)Return type
`STRING`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_10)Parameters
Parameter | Description | Data type  
---|---|---  
`str` | A string value | `STRING`  
`set` | Optional. A string of characters. The distinct characters from the string form the set. If not specified, it defaults to a single space. | `STRING`  
## [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_lower)lower()
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_11)Syntax
`lower(str)`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_11)Description
Returns the input string with all letters in lowercase.
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_11)Return type
`STRING`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_11)Parameters
Parameter | Description | Data type  
---|---|---  
`str` | The string to convert to lowercase | `STRING`  
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_example_5)Example
```
lower("GSQL") -> "gsql"
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_lpad)lpad()
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_12)Syntax
`lpad(str, padded_length [, pad_str] )`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_12)Description
Pads the left side of a string with another pad string. If the pad string `pad_str` is omitted, it will pad with white space. If the parameter length is smaller than the original string, it will truncate the string from the right side.
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_12)Return type
`STRING`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_12)Parameters
Parameter | Description | Data type  
---|---|---  
`str` | The string to pad characters to | `STRING`  
`padded_length` | The number of characters to return. If the `padded_length` is smaller than the original string, the `lpad` function will truncate the string to the size of `padded_length`. | `INT`  
`pad_str` | Optional. This is the string that will be padded to the left-hand side of `str`. If this parameter is omitted, the `lpad` function will pad spaces to the left side of `str`. | `STRING`  
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_example_6)Example
```
 lpad("PQR", 5) -> " PQR"
 lpad("PQR", 2) -> "PQ"
 lpad("PQR", 10, "ABC") -> "ABCABCAPQR"
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_repeat)repeat()
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_13)Syntax
`repeat(str, repetitions)`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_13)Description
Repeats a string the given number of times, with no intervening space.
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_13)Return type
`STRING`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_13)Parameters
Parameter | Description | Data type  
---|---|---  
`str` | The original string | `STRING`  
`repetitions` | The number of times to include `str` in the output. | `INT`  
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_example_7)Example
```
 repeat("Abcd", 2) -> "AbcdAbcd"
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_replace)replace()
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_14)Syntax
`replace(str, str_to_replace [, replacement_str])`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_14)Description
Replaces a sequence of characters in a string with another set of characters.
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_14)Return type
`STRING`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_14)Parameters
Parameter | Description | Data type  
---|---|---  
`str` | The original string whose substrings are to be replaced | `STRING`  
`str_to_replace` | The string that will be searched for and replaced in `str` | `STRING`  
`replacement_str` | Optional. The string that will replace `str_to_replace`. If omitted, `replace()` removes all occurrences of `string_to_replace` and returns the resulting string. | `STRING`  
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_examples_4)Examples
```
 replace("SSQLL", "S", "G") -> "GGQLL"
 replace("SSQLL", "SQL", "Q") -> "SQL"
 replace("SSQLL", "L") -> "SSQ"
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_reverse)reverse()
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_15)Syntax
`reverse(str)`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_15)Description
Returns a string with its characters in reverse order.
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_15)Return type
`STRING`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_15)Parameters
Parameter | Description | Data type  
---|---|---  
`str` | The original string | `STRING`  
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_examples_5)Examples
```
 reverse("0246813579") -> "9753186420"
 reverse("Never odd or even") -> "neve ro ddo reveN"
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_right)right()
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_16)Syntax
`right(str, number_of_chars)`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_16)Description
Extracts a number of characters from a string starting from the right.
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_16)Return type
`STRING`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_16)Parameters
Parameter | Description | Data type  
---|---|---  
`str` | A string value | `STRING`  
`number_of_chars` | The number of characters to extract | `INT`  
## [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_rpad)rpad()
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_17)Syntax
`rpad(str, padded_length [, pad_str] )`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_17)Description
Pads the right side of a string (`str`) with another pad string. If the pad string (`pad_str`) is omitted, it will pad with white space. If the parameter length is smaller than the original string, it will truncate the string from the right side.
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_17)Return type
`STRING`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_17)Parameters
Parameter | Description | Data type  
---|---|---  
`str` | The string to pad characters to | `STRING`  
`padded_length` | The number of characters to return. If the `padded_length` is smaller than the original string, the `lpad` function will truncate the string to the size of `padded_length`. | `INT`  
`pad_str` | Optional. This is the string that will be padded to the right-hand side of `str`. If this parameter is omitted, the `lpad` function will pad spaces to the right side of `str`. | `STRING`  
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_example_8)Example
```
rpad("PQR", 5) -> "PQF "
lpad("PQR", 2) -> "PQ"
lpad("PQR", 10, "ABC") -> "ABCABCAPQR"
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_rtrim)rtrim()
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_18)Syntax
`rtrim( str [,set] )`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_18)Description
Removes all occurrences of the characters contained in a set from a string from the right side.
The function begins scanning the string from its last character and removes all characters that appear in `set` until reaching a character not in `set` and then returns the result.
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_18)Return type
`STRING`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_18)Parameters
Parameter | Description | Data type  
---|---|---  
`str` | A string value | `STRING`  
`set` | Optional. A string of characters. The distinct characters from the string form the set. If not specified, it defaults to a single space. | `STRING`  
## [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_soundex)soundex()
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_19)Syntax
`soundex( str )`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_19)Description
Returns a character string containing the [Soundex](https://en.wikipedia.org/wiki/Soundex) code of `str`. This function lets you compare words that are spelled differently, but sound alike in English.
Soundex is a phonetic algorithm defined in _The Art of Computer Programming_ , Volume 3: Sorting and Searching, by Donald E. Knuth, as follows:
  1. Retain the first letter of the string and remove all other occurrences of the following letters: a, e, h, i, o, u, w, y.
  2. Assign numbers to the remaining letters (after the first) as follows:
```
b, f, p, v = 1
c, g, j, k, q, s, x, z = 2
d, t = 3
l = 4
m, n = 5
r = 6
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  3. If two or more letters with the same number were adjacent in the original name (before step 1), or adjacent except for any intervening h and w, then retain the first letter and omit the rest of all the adjacent letters with the same number.
  4. Return the first four bytes padded with 0.


### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_19)Return type
`STRING`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_19)Parameters
Parameter | Description | Data type  
---|---|---  
`str` | A string value | `STRING`  
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_examples_6)Examples
```
soundex("Ashcraft") => "A261"
soundex("Burroughs") => "B620"
soundex("Burrows") => "B620"
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_space)space()
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_20)Syntax
`space( n )`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_20)Description
Returns a string that contains the specified number of space characters
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_20)Return type
`STRING`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_20)Parameters
Parameter | Description | Data type  
---|---|---  
`n` | An integer value | `INT`  
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_examples_7)Examples
```
space(0) = ””
space(1) = ” ”
space(5) = ”   ”
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_substr)substr()
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_21)Syntax
`substr(str, start [, length])`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_21)Description
Returns the substring indicated by the start point and length. If the parameter length is omitted, then the returned substring will extend to the end of the given input string.
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_21)Return type
`STRING`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_21)Parameters
Parameter | Description | Data type  
---|---|---  
`str` | The string to extract substring from | `STRING`  
`start` | The position that indicates the start of the substring | `INT`  
`length` | Optional. The length of the substring. If omitted, the substring will extend from `start` to the end of `str`. | `INT`  
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_example_9)Example
```
substr("ABCDE", 2) -> "CDE"
substr("ABCDE", 2, 2) -> "CD"
substr("ABCDE", -2, 1) -> "D"
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_translate)translate()
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_22)Syntax
`translate( str_origin, characters, translations )`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_22)Description
Returns the string from the first argument after the characters specified in the second argument are translated into the characters specified at the same index in the third argument.
The function will return an error if `characters` and `translations` have different lengths.
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_22)Return type
`STRING`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_22)Parameters
Parameter | Description | Data type  
---|---|---  
`str_origin` | A string value | `STRING`  
`characters` | A string of characters | `STRING`  
`translations` | A string of characters | `STRING`  
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_examples_8)Examples
```
translate(”Hello world”, "", "") => ”Hello world”
translate(”Hello world”, "o", "U") => ”HellU wUrld”
translate(”Hello world”, "lo", "aU") => ”HeaaU wUrad”
translate(””, "lo", "aU") => ””
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_trim)trim()
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_23)Syntax
`trim( [ [ LEADING | TRAILING | BOTH ] [removal_char FROM] ] str )`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_23)Description
Trims characters from the leading and/or trailing ends of a string.
By using one of the keywords `LEADING`, `TRAILING`, or `BOTH`, the user can specify that characters are to be removed from the left end, right end, or both ends of the string respectively. `BOTH` is the default and will be used if no keywords are specified.
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_23)Return type
`STRING`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_23)Parameters
Parameter | Description | Data type  
---|---|---  
`removal_char` | Optional. The character to remove. If `removal_char` is not specified, the function will remove whitespaces, including spaces, tabs, and newlines. If `removal_char` is specified, the user must also write the keyword `FROM` between `removal_char` and `str`. | `STRING`  
`str` | A string value. | `STRING`  
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_example_10)Example
```
trim(" Abc  ") => "Abc"
trim( LEADING " a A  ") => "a A  "
trim( TRAILING "a" FROM "aa ABC aaa") => "aa ABC "
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_upper)upper()
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_syntax_24)Syntax
`upper(str)`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_description_24)Description
Returns the input string with all letters in uppercase.
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_return_type_24)Return type
`STRING`
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_parameters_24)Parameters
Parameter | Description | Data type  
---|---|---  
`str` | The string to convert to uppercase | `STRING`  
### [](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/string-functions#_example_11)Example
```
upper("gsql") -> "GSQL"
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

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


