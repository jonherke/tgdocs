![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/3.11/API/)[Next](https://docs.tigergraph.com/tigergraph-server/3.11/API/)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/3.11/API/)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/3.11/API/)
[Developer Site](https://dev.tigergraph.com/) [Community Forum](https://community.tigergraph.com/) [Knowledge Base](https://tigergraph.freshdesk.com/support/solutions)
[Download](https://dl.tigergraph.com)
[ TG Savanna](https://savanna.tgcloud.io)
### [TigerGraph DB](https://docs.tigergraph.com/tigergraph-server/3.11/intro/)
  *     * [TigerGraph DB Release Notes](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/)
  *     * [Overview](https://docs.tigergraph.com/tigergraph-server/3.11/intro/)
    * [Get Started](https://docs.tigergraph.com/tigergraph-server/3.11/getting-started/)
      * Installation
        * [On Docker](https://docs.tigergraph.com/tigergraph-server/3.11/getting-started/docker)
        * [On Kubernetes](https://docs.tigergraph.com/tigergraph-server/3.11/getting-started/kubernetes)
        * [On Cloud Marketplace](https://docs.tigergraph.com/tigergraph-server/3.11/getting-started/cloud-images/)
          * [AWS](https://docs.tigergraph.com/tigergraph-server/3.11/getting-started/cloud-images/aws)
          * [Azure](https://docs.tigergraph.com/tigergraph-server/3.11/getting-started/cloud-images/azure)
          * [GCP](https://docs.tigergraph.com/tigergraph-server/3.11/getting-started/cloud-images/gcp)
        * [On Linux](https://docs.tigergraph.com/tigergraph-server/3.11/getting-started/linux)
          * [System Requirements](https://docs.tigergraph.com/tigergraph-server/3.11/installation/hw-and-sw-requirements)
          * [Linux On Bare Metal](https://docs.tigergraph.com/tigergraph-server/3.11/installation/bare-metal-install)
          * [Post Install Checks](https://docs.tigergraph.com/tigergraph-server/3.11/installation/post-install-check)
        * [Advanced License Issues](https://docs.tigergraph.com/tigergraph-server/3.11/installation/license)
        * [Changing Ports](https://docs.tigergraph.com/tigergraph-server/3.11/installation/change-port)
        * [Upgrade](https://docs.tigergraph.com/tigergraph-server/3.11/installation/upgrade)
        * [Uninstallation](https://docs.tigergraph.com/tigergraph-server/3.11/installation/uninstallation)
      * [The GSQL Shell](https://docs.tigergraph.com/tigergraph-server/3.11/gsql-shell/)
        * [GSQL Shell Sessions](https://docs.tigergraph.com/tigergraph-server/3.11/gsql-shell/gsql-sessions)
        * [Using a Remote GSQL Client](https://docs.tigergraph.com/tigergraph-server/3.11/gsql-shell/using-a-remote-gsql-client)
        * [GSQL Shell (Web)](https://docs.tigergraph.com/tigergraph-server/3.11/gsql-shell/web)
    * [Create Database](https://docs.tigergraph.com/tigergraph-server/3.11/getting-started/database-definition)
      * [MultiGraph Overview](https://docs.tigergraph.com/tigergraph-server/3.11/intro/multigraph-overview)
  *     * [Load Data](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/)
      * [Overview](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/data-loading-overview)
      * [Externalize Kafka Configs](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/externalizing-kafka-configs)
      * [Load from Local Files](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-local-files)
      * [Load from Cloud Storage](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-cloud)
      * [Load from Data Warehouse](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-warehouse)
      * [Load from External Kafka](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-kafka)
        * [Avro Data Validation through KafkaConnect](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/avro-validation-with-kafka)
        * [Kafka SSL Security Guide](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide)
      * [Load from Spark Dataframe](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe)
        * [Spark Connection Via JDBC Driver (Deprecated)](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/spark-connection-via-jdbc-driver)
      * [Manage Data Sources](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/manage-data-source)
      * [Data Loading V2](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/data-loading-v2)
      * [Stream from External Kafka (Deprecated)](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/data-streaming-connector/kafka)
  *     * Advanced Topics
      * [System Management](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/management-with-gadmin)
        * [Memory management](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/memory-management)
        * [Manage TigerGraph services](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/manage-services)
        * [Workload Management](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management)
        * [Metrics Reporting](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/system-metrics)
        * [Command Glossary](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/management-commands)
        * [Change Data Capture (CDC) Overview](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/change-data-capture/cdc-overview)
          * [CDC Setup](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/change-data-capture/cdc-setup)
          * [CDC Message Examples](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/change-data-capture/cdc-message-example)
          * [CDC State Monitoring](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/change-data-capture/cdc-state-monitoring)
      * [Access Management](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/)
        * Authentication
          * [Enabling User Authentication](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/enabling-user-authentication)
          * [User Credentials](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/user-credentials)
          * [Single Sign-On](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/sso)
          * [Lightweight Directory Access Protocol (LDAP)](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/ldap)
          * [OIDC JWT Authentication](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/jwt-token)
        * Authorization
          * [User Management](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/user-management)
          * [Role Management](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/role-management)
          * [Access Control Model](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/access-control-model)
          * [Access Control Lists (ACLs)](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management)
          * [Row Policy Overview (Preview Feature)](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/rbac-row-policy/row-policy-overview)
            * [Key Concepts](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/rbac-row-policy/rbac-row-policy)
            * [Set Up Row Policy](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/rbac-row-policy/setup-row-policy)
          * [Vertex-Level Access Control (Deprecated)](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/vlac)
      * [Backup and Restore](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/)
        * [Database Import/Export All Graphs](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/database-import-export)
        * [Import/Export Individual Graphs](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export)
        * [Backup and Restore Configurations](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/configurations)
        * [Back up a Database Cluster](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/backup-cluster)
        * [Restore a Database Backup from the Same Cluster](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/restore-backup-same)
        * [Restore a Database Backup from Another Cluster](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/cross-cluster-backup)
        * [Differential Backup](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/differential-backups)
        * [Online Backup](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/online-backup)
        * [Legacy Backup and Restore](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/gbar-legacy)
      * [Cluster and HA Management](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/)
        * Cluster Resizing
          * [Cluster Expansion](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/expand-a-cluster)
          * [Cluster Shrinking](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/shrink-a-cluster)
          * [Cluster Repartition](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/repartition-a-cluster)
          * [Cluster Replace](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/how_to-replace-a-node-in-a-cluster)
        * [Cross-Region Replication (CRR)](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/crr-index)
          * [Set up CRR](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/set-up-crr)
          * [Fail over to the DR cluster](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/fail-over)
          * [Troubleshooting CRR](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/troubleshooting)
          * [CRR FAQ](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/crr-faq)
        * [High Availability (HA)](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/ha-overview)
          * [Cluster Configuration](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/ha-cluster)
          * [GSQL Server Support](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/ha-for-gsql-server)
          * [Application Server Support](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/ha-for-application-server)
          * [Cluster Commands](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/cluster-commands)
          * [Removal of Failed Nodes](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/remove-failed-node)
      * [Architecture](https://docs.tigergraph.com/tigergraph-server/3.11/intro/internal-architecture)
        * [MultiGraph Overview](https://docs.tigergraph.com/tigergraph-server/3.11/intro/multigraph-overview)
        * [Transaction Processing and ACID Support](https://docs.tigergraph.com/tigergraph-server/3.11/intro/transaction-and-acid)
        * [Continuous Availability Overview](https://docs.tigergraph.com/tigergraph-server/3.11/intro/continuous-availability-overview)
      * [Kubernetes](https://docs.tigergraph.com/tigergraph-server/3.11/kubernetes/)
        * [Kubernetes Operator](https://docs.tigergraph.com/tigergraph-server/3.11/kubernetes/k8s-operator/)
  *     * [Security](https://docs.tigergraph.com/tigergraph-server/3.11/security/)
      * [Auditing Privileged User Actions](https://docs.tigergraph.com/tigergraph-server/3.11/security/audit-privileged-actions)
      * [Encrypting Connections](https://docs.tigergraph.com/tigergraph-server/3.11/security/encrypting-connections)
      * [Encrypting Data At Rest](https://docs.tigergraph.com/tigergraph-server/3.11/security/encrypting-data-at-rest)
      * [File Input Policy](https://docs.tigergraph.com/tigergraph-server/3.11/security/gsql-file-input-policy)
      * [File Output Policy](https://docs.tigergraph.com/tigergraph-server/3.11/security/file-output-policy)
      * [Login Policy](https://docs.tigergraph.com/tigergraph-server/3.11/security/login-protection)
      * [Password Policy](https://docs.tigergraph.com/tigergraph-server/3.11/security/password-policy)
  *     * [REST API Reference](https://docs.tigergraph.com/tigergraph-server/3.11/API/)
      * [Authentication](https://docs.tigergraph.com/tigergraph-server/3.11/API/authentication)
      * [Built-in Endpoints](https://docs.tigergraph.com/tigergraph-server/3.11/API/built-in-endpoints)
      * [Built-in Endpoints JSON Catalog](https://docs.tigergraph.com/tigergraph-server/3.11/API/json-catalog)
      * [Upsert data to graph](https://docs.tigergraph.com/tigergraph-server/3.11/API/upsert-rest)
  *     * Additional Resources
      * [Best Practices](https://docs.tigergraph.com/tigergraph-server/3.11/additional-resources/best-practice-guides/best-practices-overview)
        * [Scaling Guide](https://docs.tigergraph.com/tigergraph-server/3.11/additional-resources/best-practice-guides/best-prac-scaling-clusters)
      * Troubleshooting and FAQs
        * [Knowledge base and FAQs](https://kb.tigergraph.com/)
        * [Troubleshooting Guide](https://docs.tigergraph.com/tigergraph-server/3.11/troubleshooting/troubleshooting-guide)
        * [System Administration FAQs](https://docs.tigergraph.com/tigergraph-server/3.11/troubleshooting/system-administration-faqs)
        * [Log Files](https://docs.tigergraph.com/tigergraph-server/3.11/troubleshooting/log-files)
          * [Audit Logs](https://docs.tigergraph.com/tigergraph-server/3.11/troubleshooting/audit-log)
          * [Gathering Log Information with gcollect](https://docs.tigergraph.com/tigergraph-server/3.11/troubleshooting/gcollect)
          * [Set up Log Viewing with Elasticsearch, Kibana and Filebeat](https://docs.tigergraph.com/tigergraph-server/3.11/troubleshooting/elk-filebeat)
      * References
        * [Configuration Parameters](https://docs.tigergraph.com/tigergraph-server/3.11/reference/configuration-parameters)
        * [Return codes](https://docs.tigergraph.com/tigergraph-server/3.11/reference/return-codes)
        * [Object-Based Privilege Tables](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/rbac-row-policy/row-policy-privileges-table)
        * [List of Legacy Privilege Syntax](https://docs.tigergraph.com/tigergraph-server/3.11/reference/list-of-privileges)
        * [List of Ports](https://docs.tigergraph.com/tigergraph-server/3.11/reference/ports)
        * [Glossary](https://docs.tigergraph.com/tigergraph-server/3.11/reference/glossary)
        * [Patents and Third Party Software](https://docs.tigergraph.com/tigergraph-server/3.11/reference/patents-and-third-party-software)
        * [Legacy Version Documentation](https://docs.tigergraph.com/tigergraph-server/3.11/additional-resources/legacy-tg-versions)
        * [Comparing TigerGraph Editions](https://docs.tigergraph.com/tigergraph-server/3.11/intro/comparison-of-editions)
        * [Release and Patch Process](https://docs.tigergraph.com/tigergraph-server/3.11/intro/release-process)
        * [RBAC Row Policy EBNF](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/rbac-row-policy/row-policy-ebnf)


TigerGraph DB 3.11
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
  * [TigerGraph DB 3.11](https://docs.tigergraph.com/tigergraph-server/3.11/intro/)
  * [REST API Reference](https://docs.tigergraph.com/tigergraph-server/3.11/API/)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/3.11/modules/API/pages/index.adoc)
### Contents
  * [Formatting query string parameters](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_query_string_parameters)
  * [Example](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_example)
  * [Input data for POST requests](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_input_data_for_post_requests)
  * [Inline data](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_inline_data)
  * [Data file](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_data_file)
  * [Formatting data in JSON](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_formatting_data_in_json)
  * [Output responses](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_output_responses)
  * [Size and time limits](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_size_and_time_limits)
  * [Request body size](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_request_body_size)
  * [GSQL query timeout](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_gsql_query_timeout)
  * [Response size](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_response_size)
  * [curl options](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_curl_options)


# TigerGraph REST API
### Contents
  * [Formatting query string parameters](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_query_string_parameters)
  * [Example](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_example)
  * [Input data for POST requests](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_input_data_for_post_requests)
  * [Inline data](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_inline_data)
  * [Data file](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_data_file)
  * [Formatting data in JSON](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_formatting_data_in_json)
  * [Output responses](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_output_responses)
  * [Size and time limits](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_size_and_time_limits)
  * [Request body size](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_request_body_size)
  * [GSQL query timeout](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_gsql_query_timeout)
  * [Response size](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_response_size)
  * [curl options](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_curl_options)


TigerGraph’s REST API endpoints exist on the REST++ and the GSQL server. REST++ (or RESTPP) is the TigerGraph customized [REST](https://en.wikipedia.org/wiki/Representational_state_transfer) server. Our API accepts URL-encoded query string parameters, [JSON](https://www.json.org/json-en.html)-encoded request bodies and returns JSON encoded responses.
This user guide provides information on how to engage with our REST APIs: the introduction section explains how to send requests, pass parameters, and format request bodies, while [Built-in Endpoints](https://docs.tigergraph.com/tigergraph-server/3.11/API/built-in-endpoints) describes in detail each endpoint and its input and output.
To submit a request, send an HTTP request to the REST++ server or the GSQL server. By default, the REST++ server listens for requests at port 9000 and the GSQL server listens on port 14240. A request needs to specify the following:
  * The request method (`GET`, `POST`, `PUT`, or `DELETE`)
  * The endpoint address
  * Any required or optional request parameters in URL encoding
  * For `POST` requests, a data payload (i.e., request body) in JSON encoding unless otherwise specified
  * In some cases, request header parameters


For requests that are sent to the GSQL server, the sender needs to provide TigerGraph user credentials for the request to be accepted. If authentication is enabled on the RESTPP server, a request token needs to be included in the request header as well.
In a test or development environment, the requester may be on the same server as REST++. In this case, the server IP is **localhost**.  
---  
## [](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_query_string_parameters)Formatting query string parameters
TigerGraph’s API endpoints accept parameters in URL encoding, which is straightforward in the case of string, number, and boolean values. However, some parameters, such as parameters for running a query, are more complex and require specific formatting.
The following table describes how to format the complex type parameter values when executing a query.
Parameter type | Description | Example  
---|---|---  
`SET` or `BAG` of primitives | Assign multiple values to the same parameter name. | A `SET<INT>` parameter named `p1` is assigned three integers: `p1=1&p1=5&p1=10`  
`VERTEX` with a defined type | Use the primary key of the vertex. | A `VERTEX<person>` parameter named `vp` is assigned a vertex whose ID is `"person1"`: `vp=person1`  
`VERTEX` without a defined type | Use `<parameter_name>.<parameter_type>` to specify the type of the parameter, and also provide the primary key of the vertex. | A `VERTEX` parameter named `va` is assigned a `person` type vertex whose ID is `"person2"` **`va=person2&va.type=person`**  
`SET` or `BAG` of vertices with a defined type | Same as a `SET` or `BAG` of primitives, where the value for each element is the primary key of the vertex. | A `SET<VERTEX<person>>` parameter named `vp` is assigned two vertices with IDs `"person3"` and `"person4"`: **`vp=person3&vp=person4`**  
`SET` or `BAG` of vertices without a defined type | The `SET` or `BAG` must be treated as an array, specifying the order of the elements with indices `[0]`, `[1]`, etc. | A `SET<VERTEX>` parameter named `vp` is assigned a `person` type vertex with an ID of `"person5"` and a `post` type vertex with an ID of `11` : **`vp[0]=person5&vp[0].type=person&vp[1]=11&vp[1].type=post`**  
### [](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_example)Example
## [](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_input_data_for_post_requests)Input data for `POST` requests
Input data for `POST` requests should be in JSON format, unless the endpoint specifically accepts data in other formats. There are two ways to supply the data: inline or in a separate file.
### [](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_inline_data)Inline data
The data should be formatted as a single string without linebreaks. If using curl, use the `-d` option, followed by the JSON string.
Syntax for a POST request with Inline Data Payload
```
curl -X POST -d 'json_string' "http://server_ip:9000/path_to_endpoint?request_parameters"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The following example uses the `POST /graph` endpoint to insert one User type vertex whose ID is `id6` into the graph called `"Social_Net"`.
Example using inline input data
```
curl -X POST -d '{"vertices":{"User":{"id6":{"id":{"value":"id6"}}}}}' "http://localhost:9000/graph/Social_Net"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_data_file)Data file
Often it will be more convenient for the input data to be in a separate file, especially if the data is large.
For curl, use `--data-binary @<path_to_file>` as in the following example:
Syntax for a POST request with Payload Data File
```
curl -X POST --data-binary @./person.csv "http://localhost:9000/ddl/poc_graph?tag=load_data&filename=f1"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_formatting_data_in_json)Formatting data in JSON
Data of primitive types, including `INT, UINT, FLOAT, DOUBLE, STRING, BOOL`, and `DATETIME`, as well as arrays and objects, follow the standard [JSON Data Interchange Syntax](https://www.json.org/json-en.html).
The following table subsection describes how to format complex data types.
Data type | Description | Example  
---|---|---  
`SET`, `LIST` or `BAG` of primitives | Use a JSON array of primitive values. | A set of primitive values: `[1, 2, 3]`  
`VERTEX` | Use a JSON object that has an `id` field whose value is the primary key of the vertex and a `type` field whose value is the type of the vertex. | A `person` vertex with an ID of `"Tom"`: `{"id": "Tom", "type": "person"}`  
`MAP` | Use a JSON object that has two JSON arrays with keys `keylist` and `valuelist`, each containing the keys and the values of the map respectively. The order of items in the valuelist should correspond to the order of items in the keylist. | A map of nations and their capitals: `{"keylist": ["England", "Germany"],` `"valuelist": ["London", "Berlin"]}`  
User-Defined Type (UDT) | Use a JSON object that has two JSON arrays with keys `keylist` and `valuelist`. The `keylist` array contains the field names of the tuple, and the `valuelist` array contains the values of the fields. The order of items in the `keylist` should correspond to the order of the fields as specified in the definition of the tuple/UDT, and the order of values in the `valuelist` should correspond to the order of items in the keylist. | Tuple schema definition: `TYPEDEF TUPLE <name STRING, age INT> person` A `person` tuple written in JSON: `{"keylist: ["name", "age"], "valuelist": ["Sam", 24]}`  
Example: UDT Definition
```
TYPEDEF TUPLE <field1 INT(1), field2 UINT, field3 STRING(10), field4 DOUBLE> myTuple
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_vertices_with_composite_keys)Vertices with composite keys
This format for vertices with composite keys does not apply to the [endpoint used to upsert data](https://docs.tigergraph.com/tigergraph-server/3.11/API/built-in-endpoints#_upsert_data_to_graph). It is only applicable to the [endpoint to run a query](https://docs.tigergraph.com/tigergraph-server/3.11/API/built-in-endpoints#_run_an_installed_query_post).   
---  
If a vertex has a composite key composed of multiple attributes, then all values for those attributes must be provided for the `"id"` field. The values can be presented either as a JSON object with key-value pairs for each attribute-value pair, or as a JSON array with a list values in the same order as defined in the schema.
The following example shows the two methods for a vertex `v` having a composite primary key composed of the three attributes `id` and `name`
  * Option 1
  * Option 2


Vertex v with composite key as JSON array
```
{
 "v":{
  "id":["Tom",456], **(1)**
  "type":"compositePerson"
 }
}
javascript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | The values in the array must be in the same order as they are defined in the schema.  
---|---  
Vertex v with composite key as JSON object
```
{
 "v":{
  "id":{
   "name":"Tom",
   "id":456
  },
  "type":"compositePerson"
 }
}
javascript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_set_or_bag_of_vertices)`SET` or `BAG` of Vertices
To describe a `SET` or `BAG` of vertices in JSON, use a JSON array with _vertex objects_ nested in the `SET` or `BAG` array.
## [](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_output_responses)Output responses
All TigerGraph REST responses are in JSON format. The output JSON object has four fields: `"version"`, `"error"`, `"message"`, and `"result"`.
  * `"version"` - this field describes the version of the running TigerGraph instance.
  * "`error"` - a boolean value to indicate if there is an error in processing the request. If there is an error, the `"error"` field will be `true`.
  * `"message"` - the error message when there is an error. If a request is successful, the field will be an empty string or a brief message conveying the result of the request.
  * `"results"` - this field contains the resulting data from the request. Details about the result of each built-in endpoint are described in the [Built-in Endpoints](https://docs.tigergraph.com/tigergraph-server/3.11/API/built-in-endpoints) section.


```
// Example response
{
 "version": {
  "api": "v2",
  "schema": 0
 },
 "error": false,
 "message": "",
 "results": [
  {
   "v_id": "id1",
   "v_type": "User",
   "attributes": {}
  }
 ]
}
javascript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

To make the JSON output more human-readable in the terminal, use the [`jq`](https://stedolan.github.io/jq/) command or Python json library built into most Linux installations: ```
curl -X method "http://server_ip:9000/path_to_endpoint?request_parameters" | jq .
curl -X method "http://server_ip:9000/path_to_endpoint?request_parameters" | python -m json.toolbash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!
```
  
---  
## [](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_size_and_time_limits)Size and time limits
The maximum length for the request URL is 8K bytes, including the query string. Requests with a large parameter size should use a data payload file instead of inline data.
### [](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_request_body_size)Request body size
The maximum size for a request body, including the payload file, is set by the system parameter `Nginx.ClientMaxBodySize`. The default value is 200 (in MB). To increase this limit, use the following `gadmin` command:
```
gadmin config set Nginx.ClientMaxBodySize NNN
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The upper limit of this setting is 1024 MB. Raising the size limit for the data payload buffer reduces the memory available for other operations, so be cautious about increasing this limit.
### [](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_gsql_query_timeout)GSQL query timeout
By default, an HTTP request in the TigerGraph system times out after 16 seconds. to customize this timeout limit for a particular query instance, you can set the GSQL-TIMEOUT parameter in the request header. If you are using curl to submit your RESTPP request, the syntax would be the following:
```
curl -X <GET/POST> -H "GSQL-TIMEOUT: <timeout value in ms>" '<request_URL>'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_response_size)Response size
You can specify the response size limit of an HTTP request with the following header:
```
curl -X <GET/POST> -H "RESPONSE-LIMIT: <size limit in byte>" '<request_URL>'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

If the response size is larger than the given limit, an error message will be returned instead of the actual query result:
```
{
 "error": true,
 "message": "The query response size is 256MB, which exceeds limit 32MB.",
 "results": [],
 "code": "REST-4000"
}
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_curl_options)`curl` options
Request examples in this guide are made using [`curl`](https://curl.se/docs/manpage.html). Below is a list of `curl` options used in our code examples:
  * `-d <data>`
    * Sends the specified data in a `POST` request to the HTTP server in the same way that a browser does when a user has filled in an HTML form and presses the submit button. This will cause curl to pass the data to the server using the content-type `application/x-www-form-urlencoded`.
    * If you start the data with the character `@`, the rest should be a filepath from which to read the data. The command `curl -d @foobar` will read data from a file named `foobar`.
  * `--data-binary <data>`
    * Sends data with a `POST` request exactly as specified with no extra processing.
  * `--fail`
    * Makes curl fail silently (no output at all) on server errors.
    * This is mostly done to enable scripts etc. to better deal with failed attempts. In normal cases when an HTTP server fails to deliver a document, it returns an HTML document stating so (which often also describes why and more). This flag will prevent curl from outputting that and return error 22.
  * `-H <header>`
    * Extra header to include in the request when sending HTTP to a server. You may specify any number of extra headers.
    * TigerGraph APIs use headers to specify [size and time limits](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_size_and_time_limits), as well as to provide RESTPP [authentication](https://docs.tigergraph.com/tigergraph-server/3.11/API/authentication#_restpp_server_requests) tokens.
  * `-s`
    * Silent or quiet mode. Don’t show a progress meter or error messages. It will still output the data you ask for, potentially even to the terminal/stdout unless you redirect it.
  * `-u <user:password>`
    * Submits the specified user name and password for server authentication.
  * `-X <request_method>`
    * Specifies a custom request method to use when communicating with the HTTP server. If this option is not used, curl will make a `GET` request by default.


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


