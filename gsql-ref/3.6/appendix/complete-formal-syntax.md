![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/gsql-ref/3.6/appendix/complete-formal-syntax)[Next](https://docs.tigergraph.com/gsql-ref/3.6/appendix/complete-formal-syntax)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/gsql-ref/3.6/appendix/complete-formal-syntax)
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
[Resources](https://docs.tigergraph.com/gsql-ref/3.6/appendix/complete-formal-syntax)
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
  * Appendix
  * [Formal Grammar for Query Language](https://docs.tigergraph.com/gsql-ref/3.6/appendix/complete-formal-syntax)


[Edit this Page](https://github.com/tigergraph/gsql-docs/edit/3.6/modules/appendix/pages/complete-formal-syntax.adoc)
### Contents
  * [Notation Used to Define Syntax](https://docs.tigergraph.com/gsql-ref/3.6/appendix/complete-formal-syntax#_notation_used_to_define_syntax)
  * [GSQL Query Language EBNF](https://docs.tigergraph.com/gsql-ref/3.6/appendix/complete-formal-syntax#_gsql_query_language_ebnf)


# Formal Grammar for Query Language
### Contents
  * [Notation Used to Define Syntax](https://docs.tigergraph.com/gsql-ref/3.6/appendix/complete-formal-syntax#_notation_used_to_define_syntax)
  * [GSQL Query Language EBNF](https://docs.tigergraph.com/gsql-ref/3.6/appendix/complete-formal-syntax#_gsql_query_language_ebnf)


This is the definition for the GSQL Query Language syntax. It is defined as a set of rules expressed in EBNF notation.
## [](https://docs.tigergraph.com/gsql-ref/3.6/appendix/complete-formal-syntax#_notation_used_to_define_syntax)Notation Used to Define Syntax
This defines the EBNF notation used to describe the syntax. Rules contains terminal and non-terminal symbols. A terminal symbol is a base-level symbol which expresses literal output. All symbols in single or double quotes (e.g., '+', "=", ")", "10") are terminal symbols. A non-terminal symbol is defined as some combination of terminal and non-terminal symbols. The left-hand side of a rule is always a non-terminal; this rule defines the non-terminal. The example rule below defines assignmentStmt (that is, an Assignment Statement) to be a name followed by an equal sign followed by an expression, operator, and expression with a terminating semi-colon. AssignmentStmt, name, and expr are all non-terminals. Additionally, all KEYWORDS are in all-capitals and are terminal symbols. The ":=" is part of EBNF and states the left hand side can be expanded to the right hand side.
EBNF Syntax example: A rule
```
assignmentStmt := name "=" expr op expr ";"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

A **vertical bar |** in EBNF indicates choice. Choose either the symbol on the left or on the right. A sequence of vertical bars means choose any one of the symbols in the sequence.
EBNF Syntax: vertical bar
```
op := "+" | "-" | "*" | "/"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**Square brackets [ ]** indicate an optional part or group of symbols. **Parentheses ( )** group symbols together. The rule below defines a constant to be one, two, or three digits preceded by an optional plus or minus sign.
EBNF Syntax: Square brackets and parentheses
```
constant := ["+" | "-"] (digit | (digit digit) | (digit digit digit))
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**Star *** and **plus +** are symbols in EBNF for closure. Star means zero or more occurrences, and plus means one or more occurrences. The following defines intConstant to be an optional plus or minus followed by one or more digits. It also defines floatConstant to be an optional plus or minus followed by zero or more digits followed by a decimal followed by one or more digits. The star and plus also can be applied to groups of symbols as in the definition of list. The non-terminal list is defined as a parenthesized list of comma-separated expressions (expr). The list has at least one expression which can be followed by zero or more comma-expression pairs.
EBNF Syntax: square brackets and parentheses
```
intConstant := ["+" | "-"] digit+
floatConstant := ["+" | "-"] digit* "." digit+
list := "(" expr ["," expr]* ")"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/gsql-ref/3.6/appendix/complete-formal-syntax#_gsql_query_language_ebnf)GSQL Query Language EBNF
```
#########################################################
## EBNF for GSQL Query Language
createQuery := CREATE [OR REPLACE] [DISTRIBUTED] QUERY queryName
        "(" [parameterList] ")"
        [FOR GRAPH graphName]
        [RETURNS "(" baseType | accumType ")"]
        [API "(" stringLiteral ")"]
        [SYNTAX syntaxName]
        "{" queryBody "}"
interpretQuery := INTERPRET QUERY "(" ")"
        [FOR GRAPH graphName]
        [SYNTAX syntaxName]
        "{" queryBody "}"
parameterValueList := parameterValue ["," parameterValue]*
parameterValue := parameterConstant
        | "[" parameterValue ["," parameterValue]* "]" // BAG or SET
        | "(" stringLiteral "," stringLiteral ")"    // a generic VERTEX value
parameterConstant := numeric | stringLiteral | TRUE | FALSE
parameterList := parameterType paramName ["=" constant]
         ["," parameterType paramName ["=" constant]]*
syntaxName := name
queryBody := [typedefs] [declExceptStmts] queryBodyStmts
typedefs := (typedef ";")+
declStmts := (declStmt ";")+
declStmt := baseDeclStmt | accumDeclStmt | fileDeclStmt
declExceptStmts := (declExceptStmt ";")+
queryBodyStmts := (queryBodyStmt ";")+
queryBodyStmt := assignStmt      // Assignment
        | vSetVarDeclStmt   // Declaration
        | declStmts      // Declaration
        | lAccumAssignStmt   // Assignment
        | gAccumAssignStmt   // Assignment
        | gAccumAccumStmt   // Assignment
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
installQuery := INSTALL QUERY [installOptions] ( "*" | ALL |queryName ["," queryName]* )
runQuery := (RUN | INTERPRET) QUERY [runOptions] queryName "(" parameterValueList ")"
showQuery := SHOW QUERY queryName
dropQuery := DROP QUERY ( "*" | ALL | queryName ["," queryName]* )
#########################################################
## Types and names
lowercase     := [a-z]
uppercase     := [A-Z]
letter       := lowercase | uppercase
digit       := [0-9]
integer      := ["-"]digit+
real        := ["-"]("."digit+) | ["-"](digit+"."digit*)
numeric      := integer | real
stringLiteral   := '"' [~["] | '\\' ('"' | '\\')]* '"'
name := (letter | "_") [letter | digit | "_"]*  // can be a single "_" or start with "_"
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
fieldName := name
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
#########################################################
## Accumulators
accumDeclStmt := accumType localAccumName ["=" constant]
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
gAccumAccumStmt := globalAccumName "+=" expr
###############################################################################
## Operators, Functions, and Expressions
constant := numeric | stringLiteral | TRUE | FALSE | GSQL_UINT_MAX
     | GSQL_INT_MAX | GSQL_INT_MIN | TO_DATETIME "(" stringLiteral ")"
mathOperator := "*" | "/" | "%" | "+" | "-" | "<<" | ">>" | "&" | "|"
condition := expr
      | expr comparisonOperator expr
      | expr [ NOT ] IN setBagExpr
      | expr IS [ NOT ] NULL
      | expr BETWEEN expr AND expr
      | "(" condition ")"
      | NOT condition
      | condition (AND | OR) condition
      | (TRUE | FALSE)
      | expr [NOT] LIKE expr [ESCAPE escape_char]
comparisonOperator := "<" | "<=" | ">" | ">=" | "==" | "!="
aggregator := COUNT | MAX | MIN | AVG | SUM
expr := name
  | globalAccumName
		| name "." name
		| name "." localAccumName ["\'"]
		| name "." name "." name "(" [argList] ")"
  | name "." name "(" [argList] ")" [ "." FILTER "(" condition ")" ]
		| name ["<" type ["," type]* ">"] "(" [argList] ")"
		| name "." localAccumName ("." name "(" [argList] ")")+ ["." name]
		| globalAccumName ("." name "(" [argList] ")")+ ["." name]
		| COALESCE "(" [argList] ")"
		| aggregator "(" [DISTINCT] setBagExpr ")"
		| ISEMPTY "(" setBagExpr ")"
		| expr mathOperator expr
		| "-" expr
		| "(" expr ")"
		| "(" argList "->" argList ")"	// key value pair for MapAccum
		| "[" argList "]"        // a list
		| constant
		| setBagExpr
		| name "(" argList ")"     // function call or a tuple object
setBagExpr := name
    | globalAccumName
  	 | name "." name
		  | name "." localAccumName
		  | name "." localAccumName ("." name "(" [argList] ")")+
		  | name "." name "(" [argList] ")" [ "." FILTER "(" condition ")" ]
		  | globalAccumName ("." name "(" [argList] ")")+
		  | setBagExpr (UNION | INTERSECT | MINUS) setBagExpr
		  | "(" argList ")"
		  | "(" setBagExpr ")"
#########################################################
## Declarations and Assignments ##
## Declarations ##
baseDeclStmt  := baseType name ["=" expr] ["," name ["=" expr]]*
fileDeclStmt := FILE fileVar "(" filePath ")"
fileVar := name
localVarDeclStmt := baseType varName "=" expr
assignDeclLocalTuple := (tupleTypeName | anonymousTupleType) localTupleVal "=" expr
vSetVarDeclStmt := vertexSetName ["(" vertexType ")"]
          "=" (seedSet | simpleSet | selectBlock)
simpleSet := vertexSetName | "(" simpleSet ")"
      | simpleSet (UNION | INTERSECT | MINUS) simpleSet
seedSet := "{" [seed ["," seed ]*] "}"
seed := '_'
   | ANY
   | vertexSetName
   | globalAccumName
   | vertexType ".*"
   | paramName
   | "SelectVertex" selectVertParams
selectVertParams := "(" filePath "," columnId "," (columnId | name) ","
         stringLiteral "," (TRUE | FALSE) ")" ["." FILTER "(" condition ")"]
columnId := "$"(integer | stringLiteral)
## Assignment Statements ##
assignStmt := name "=" expr
      | name "." attrName "=" expr
attrAccumStmt := name "." attrName "+=" expr
lAccumAssignStmt := vertexAlias "." localAccumName ("+="| "=") expr
gAccumAssignStmt := globalAccumName ("+=" | "=") expr
loadAccumStmt := globalAccumName "=" "{" LOADACCUM loadAccumParams
                 ["," LOADACCUM loadAccumParams]* "}"
loadAccumParams := "(" filePath "," columnId ["," [columnId]* ","
        stringLiteral "," (TRUE | FALSE) ")" ["." FILTER "(" condition ")"]
## Function Call Statement ##
funcCallStmt := name ["<" type ["," type"]* ">"] "(" [argList] ")"
       | globalAccumName ("." funcName "(" [argList] ")")+
argList := expr ["," expr]*

#########################################################
## Select Statement
selectStmt := gsqlSelectBlock
       | sqlSelectBlock
gsqlSelectBlock := gsqlSelectClause
        fromClause
        [sampleClause]
        [whereClause]
        [accumClause]
        [postAccumClause]*
        [havingClause]
        [orderClause]
        [limitClause]
sqlSelectBlock := sqlSelectClause
        fromClause
        [whereClause]
        [groupByClause]
        [havingClause]
        [orderClause]
        [limitClause]
gsqlSelectClause := vertexSetName "=" SELECT vertexAlias
sqlSelectClause := SELECT [DISTINCT] columnExpr ("," columnExpr)*
          INTO tableName
columnExpr := expr [AS columnName]
      | aggregator "("[DISTINCT] expr ")" [AS columnName]
columnName := name
tableName := name
fromClause := FROM (step | stepV2 | pathPattern ["," pathPattern]*)
step  := stepSourceSet ["-" "(" stepEdgeSet ")" ("-"|"->") stepVertexSet]
stepV2 := stepVertexSet ["-" "(" stepEdgeSet ")" "-" stepVertexSet]
stepSourceSet := vertexSetName [":" vertexAlias]
stepEdgeSet := [stepEdgeTypes] [":" edgeAlias]
stepVertexSet := [stepVertexTypes] [":" vertexAlias]
alias := (vertexAlias | edgeAlias)
vertexAlias := name
edgeAlias := name
stepEdgeTypes := atomicEdgeType | "(" edgeSetType ["|" edgeSetType]* ")"
atomicEdgeType := "_" | ANY | edgeSetType
edgeSetType := edgeType | paramName | globalAccumName
stepVertexTypes := atomicVertexType | "(" vertexSetType ["|" vertexSetType]* ")"
atomicVertexType := "_" | ANY | vertexSetType
vertexSetType := vertexType | paramName | globalAccumName
#----------# Pattern Matching #----------#
pathPattern := stepVertexSet ["-" "(" pathEdgePattern ")" "-" stepVertexSet]*
pathEdgePattern := atomicEdgePattern
         | "(" pathEdgePattern ")"
         | pathEdgePattern "." pathEdgePattern
         | disjPattern
         | starPattern
atomicEdgePattern := atomicEdgeType
    	    | atomicEdgeType ">"
    	    | "<" atomicEdgeType
disjPattern := atomicEdgePattern ("|" atomicEdgePattern)*
starPattern := ([atomicEdgePattern] | "(" disjPattern ")") "*" [starBounds]
starBounds := CONST_INT ".." CONST_INT
      | CONST_INT ".."
      | ".." CONST_INT
      | CONST_INT
#--------------------------------------#
sampleClause := SAMPLE ( expr | expr "%" ) EDGE WHEN condition
       | SAMPLE expr TARGET WHEN condition
       | SAMPLE expr "%" TARGET PINNED WHEN condition
whereClause := WHERE condition
accumClause := [perClauseV2] ACCUM dmlSubStmtList
perClauseV2 := PER "(" alias ["," alias] ")"
postAccumClause := "POST-ACCUM" dmlSubStmtList
dmlSubStmtList := dmlSubStmt ["," dmlSubStmt]*
dmlSubStmt := assignStmt      // Assignment
      | funcCallStmt     // Function Call
      | gAccumAccumStmt   // Assignment
      | lAccumAccumStmt   // Assignment
      | attrAccumStmt    // Assignment
      | vAccumFuncCall    // Function Call
      | localVarDeclStmt   // Declaration
      | dmlSubCaseStmt    // Control Flow
      | dmlSubIfStmt     // Control Flow
      | dmlSubWhileStmt   // Control Flow
      | dmlSubForEachStmt  // Control Flow
      | BREAK        // Control Flow
      | CONTINUE       // Control Flow
      | insertStmt      // Data Modification
      | dmlSubDeleteStmt   // Data Modification
      | printlnStmt     // Output
      | logStmt       // Output

vAccumFuncCall := vertexAlias "." localAccumName ("." funcName "(" [argList] ")")+
groupByClause := GROUP BY groupExpr ("," groupExpr)*
groupExpr := expr
havingClause := HAVING condition
orderClause := ORDER BY expr [ASC | DESC] ["," expr [ASC | DESC]]*
limitClause := LIMIT ( expr | expr "," expr | expr OFFSET expr )
#########################################################
## Control Flow Statements ##
queryBodyIfStmt := IF condition THEN queryBodyStmts
         [ELSE IF condition THEN queryBodyStmts ]*
         [ELSE queryBodyStmts ] END
dmlSubIfStmt :=  IF condition THEN dmlSubStmtList
         [ELSE IF condition THEN dmlSubStmtList ]*
         [ELSE dmlSubStmtList ] END
queryBodyCaseStmt := CASE (WHEN condition THEN queryBodyStmts)+ [ELSE queryBodyStmts] END
        | CASE expr (WHEN constant THEN queryBodyStmts)+ [ELSE queryBodyStmts] END
dmlSubCaseStmt := CASE   (WHEN condition THEN dmlSubStmtList)+ [ELSE dmlSubStmtList] END
        | CASE expr (WHEN constant THEN dmlSubStmtList)+ [ELSE dmlSubStmtList] END
queryBodyWhileStmt := WHILE condition [LIMIT simpleSize] DO queryBodyStmts END
dmlSubWhileStmt :=  WHILE condition [LIMIT simpleSize] DO dmlSubStmtList END
simpleSize := integer | varName | paramName
queryBodyForEachStmt := FOREACH forEachControl DO queryBodyStmts END
dmlSubForEachStmt :=  FOREACH forEachControl DO dmlSubStmtList END
forEachControl := ( iterationVar | "(" keyVar ("," valueVar)+ ")") (IN | ":") setBagExpr
        | iterationVar IN RANGE "[" expr "," expr"]" ["." STEP "(" expr ")"]
iterationVar := name
keyVar := name
valueVar := name
#########################################################
## Other Data Modifications Statements ##
queryBodyDeleteStmt := DELETE alias FROM pattern [whereClause]
dmlSubDeleteStmt := DELETE "(" alias ")"
updateStmt := UPDATE alias FROM pattern SET dmlSubStmtList [whereClause]
insertStmt := insertVertexStmt | insertEdgeStmt
insertVertexStmt := INSERT INTO (vertexType | name)
         ["(" PRIMARY_ID ["," attrName]* ")"]
         VALUES "(" ( "_" | expr ) ["," ("_" | expr)]*] ")"
insertEdgeStmt  := INSERT INTO (edgeType | EDGE name)
         ["(" FROM "," TO ["," attrName]* ")"]
         VALUES "(" ( "_" | expr ) [vertexType]
         ["," ( "_" | expr ) [vertexType] ["," ("_" | expr)]*] ")"
#########################################################
## Output Statements ##
printStmt := PRINT printExpr ("," printExpr)* [WHERE condition] [TO_CSV (filePath | fileVar)]
printExpr := (expr | vExprSet) [ AS jsonKey]
      | tableName
vExprSet := expr "[" vSetProj ("," vSetProj)* "]"
vSetProj := expr [ AS jsonKey]
jsonKey := name
printlnStmt := fileVar ".println" "(" expr ("," expr)* ")"
logStmt := LOG "(" condition "," argList ")"
returnStmt := RETURN expr
#########################################################
## Exception Statements ##
declExceptStmt := EXCEPTION exceptVarName "(" errorInt ")"
exceptVarName := name
errorInt   := integer

raiseStmt    := RAISE exceptVarName [errorMsg]
errorMsg    := "(" expr ")"

tryStmt     := TRY queryBodyStmts EXCEPTION caseExceptBlock+ [elseExceptBlock] END ";"
caseExceptBlock := WHEN exceptVarName THEN queryBodyStmts
elseExceptBlock := ELSE queryBodyStmts
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


