![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe)[Next](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe)
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
  * [Load Data](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/)
  * [Load from Spark Dataframe](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/3.11/modules/data-loading/pages/load-from-spark-dataframe.adoc)
### Contents
  * [Prerequisites](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_prerequisites)
  * [Download the TigerGraph Spark Connector](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_download_the_tigergraph_spark_connector)
  * [Configure Logging](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_configure_logging)
  * [Create a Loading Job](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_create_a_loading_job)
  * [Overview](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_overview)
  * [Usage](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_usage)
  * [Database Connection](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_database_connection)
  * [Batch Write](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_batch_write)
  * [Write with Spark Structured Streaming API](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_write_with_spark_structured_streaming_api)
  * [Connector Options](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_connector_options)
  * [Common Options](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_common_options)
  * [Writer Options](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_writer_options)
  * [Use Cases](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_use_cases)
  * [Load Data from Delta Lake](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_load_data_from_delta_lake)
  * [Load Data from Iceberg](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_load_data_from_iceberg)
  * [Load Data from Hudi](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_load_data_from_hudi)
  * [Loading Statistics](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_loading_statistics)
  * [Row Level Statistics](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_row_level_statistics)
  * [Object Level Statistics](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_object_level_statistics)


# Load from Spark Dataframe
### Contents
  * [Prerequisites](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_prerequisites)
  * [Download the TigerGraph Spark Connector](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_download_the_tigergraph_spark_connector)
  * [Configure Logging](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_configure_logging)
  * [Create a Loading Job](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_create_a_loading_job)
  * [Overview](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_overview)
  * [Usage](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_usage)
  * [Database Connection](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_database_connection)
  * [Batch Write](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_batch_write)
  * [Write with Spark Structured Streaming API](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_write_with_spark_structured_streaming_api)
  * [Connector Options](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_connector_options)
  * [Common Options](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_common_options)
  * [Writer Options](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_writer_options)
  * [Use Cases](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_use_cases)
  * [Load Data from Delta Lake](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_load_data_from_delta_lake)
  * [Load Data from Iceberg](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_load_data_from_iceberg)
  * [Load Data from Hudi](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_load_data_from_hudi)
  * [Loading Statistics](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_loading_statistics)
  * [Row Level Statistics](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_row_level_statistics)
  * [Object Level Statistics](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_object_level_statistics)


The TigerGraph Spark Connector employs [Apache Spark](https://spark.apache.org) to read data from a Spark DataFrame (or Data Lake) and write to TigerGraph. This connector has multiple optimizations for high performance, scalability, and management.
In TigerGraph 3.11+, it can also be used to [to stream data from TigerGraph into Spark](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/read-to-spark-dataframe) as a Dataframe.
Users can leverage it to connect TigerGraph to the Spark ecosystem and load data from any Spark data sources, e.g.:
  * Distributed file system: HDFS, S3, GCS and ABS
  * Streaming source: Kafka
  * Data warehouse: [BigQuery](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/load-from-warehouse#_bigquery), [Snowflake](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/load-from-warehouse#_snowflake), [PostgreSql](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/load-from-warehouse#_postgresql), and Redshift
  * Open table format: [Delta Lake](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/load-from-spark-dataframe#_load_data_from_delta_lake), [Iceberg](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/load-from-spark-dataframe#_load_data_from_iceberg) and [Hudi](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/load-from-spark-dataframe#_load_data_from_hudi)


The legacy [Spark Connection Via JDBC Driver](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver) is deprecated. Please migrate to this new connector.  
---  
## [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_prerequisites)Prerequisites
  * TigerGraph 3.6.0 or higher. Job-level loading statistics are available in v3.10+.
  * Spark 3.2 or higher with Scala 2.12 and Scala 2.13.
  * JAVA 8 or higher.


### [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_download_the_tigergraph_spark_connector)Download the TigerGraph Spark Connector
This connector can be downloaded from the Maven central repository: [Maven Central](https://central.sonatype.com/artifact/com.tigergraph/tigergraph-spark-connector/overview). The connector is available in three formats:
  * `tigergraph-spark-connector-<version>.jar`: The `JAR` file containing only the compiled classes of the connector, which does not include any dependencies.
  * `tigergraph-spark-connector-<version>-jar-with-dependencies.jar`: The `JAR` file that includes compiled classes, as well as all the dependencies.
  * `tigergraph-spark-connector-<version>.tar.gz`: The compressed `TAR` archive that includes `tigergraph-spark-connector-<version>.jar` and dependencies in separate `JAR` files.


To use the TigerGraph Spark connector in a Spark shell:
use the `--jars` option:
```
spark-shell --jars tigergraph-spark-connector-<version>-jar-with-dependencies.jar
```

If you want to include the TigerGraph Spark Connector in your Spark installation, add the `JAR` with dependencies to Spark’s `jars` folder.  
---  
### [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_configure_logging)Configure Logging
We highly recommend setting the log level to `info` to monitor the execution. There are two methods to enable logging for the connector.
#### [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_connector_default_logger)Connector Default Logger
The connector has a built-in logger based on _java.util.logging_. To activate it, set the option `log.level` to 2, which enables info-level logging.
Please refer to [Common Options](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_common_options) to learn more about `log.level` and `log.file` options.
#### [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_spark_logger)Spark Logger
Configure Spark Log4j by `$SPARK_HOME/conf/log4j2.properties` as follows, or other SLF4j bindings if any:
```
logger.tg.name = com.tigergraph
logger.tg.level = info
```

### [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_create_a_loading_job)Create a Loading Job
This loading map should map the dataframe’s columns to the desired graph element attributes.
Example of simple graph schema and loading job
```
CREATE VERTEX Comment (PRIMARY_ID id UINT, creationDate DATETIME,
 locationIP STRING, browserUsed STRING, content STRING, length UINT)
 WITH primary_id_as_attribute="TRUE", STATS="outdegree_by_edgetype"
CREATE GRAPH demo_graph (*)
USE GRAPH demo_graph
CREATE LOADING JOB load_Comment FOR GRAPH demo_graph {
  DEFINE FILENAME file_Comment;
  LOAD file_Comment
    TO VERTEX Comment VALUES ($1, $0, $2, $3, $4, $5)
    USING header="true", separator="|";
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_overview)Overview
The first step is the read data into a Spark dataframe. Then, using a TigerGraph loading job which maps data fields from the dataframe into graph elements, the connector pulls data from Spark into TigerGraph.
Spark dataframe:
```
+--------------------+-------------+-------------+-----------+--------------------+------+
|    creationDate|      id|  locationIP|browserUsed|       content|length|
+--------------------+-------------+-------------+-----------+--------------------+------+
|2012-07-04T06:10:...|7696585588755| 46.23.82.182|  Firefox|         LOL|   3|
|2012-08-22T17:22:...|8246341402699| 27.62.125.4|   Chrome|       roflol|   6|
|2012-05-08T21:02:...|7146829775042| 61.1.50.205|   Chrome|       roflol|   6|
|2012-11-22T01:25:...|9345853030654|190.95.68.192|  Firefox|About Sergei Eise...|  79|
|2012-11-11T08:59:...|9345853030710|166.75.225.76|   Chrome|        good|   4|
+--------------------+-------------+-------------+-----------+--------------------+------+
```

The connector concatenates columns to delimited data.
If the following options are used,
```
- loading.separator = "|"
- loading.eol = "\n"
```

then the processed data would be
```
2012-07-04T06:10:43.489+00:00|7696585588755|46.23.82.182|Firefox|LOL|3
2012-08-22T17:22:20.315+00:00|8246341402699|27.62.125.4|Chrome|roflol|6
2012-05-08T21:02:39.145+00:00|7146829775042|61.1.50.205|Chrome|roflol|6
2012-11-22T01:25:39.670+00:00|9345853030654|190.95.68.192|Firefox|About Sergei Eisenstein, pioneering SAbout Steven Spielberg, makers in thAbout|79
2012-11-11T08:59:21.311+00:00|9345853030710|166.75.225.76|Chrome|good|4
```

The processed data will be sent to TigerGraph in batches as CSV file sources for the loading job:
```
- loading.job = "load_Comment"
- loading.filename = "file_Comment"
```

To let TigerGraph parse the data correctly, please make sure you set `loading.separator` and `loading.eol` to chracters which do not appear in your data fields.
## [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_usage)Usage
### [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_database_connection)Database Connection
Connection options object You may find it convenient to bundle the options related to making a database connection in a data object (e.g., `tgOptions`) and then use `.options(tgOptions)` when running the connector. Moreover, placing the user credentials in a data object keeps them separate from the connection commands.  
---  
Predefined connection options:
```
val tgOptions = Map(
  "url" -> "http(s)://<tg_node_host>:<tg_nginx_port>",
  "version" -> "<tg_version>",
  "graph" -> "<graph_name>",
  "username" -> "<username>",
  "password" -> "<password>"
)
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Authentication methods Using username/password has the advantage that this authentication method will automatically refresh an access token as needed. If you choose to use a token, please make sure the lifetime of the token is long enough for the loading job.  
---  
### [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_batch_write)Batch Write
Read data from any Spark data sources into the dataframe:
```
val df = spark.read.json("path/to/Comment.json")
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Batch write the data into TigerGraph:
```
df.write
  .format("tigergraph")
  .mode("append")
  .options(tgOptions)
  .option("loading.job", "load_Comment")
  .option("loading.filename", "file_Comment")
  .option("loading.separator", "|")
  .option("log.level", "2")
  .option("log.file", "/tmp/tigergraph-spark-connector.log")
  .save()
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_write_with_spark_structured_streaming_api)Write with Spark Structured Streaming API
Read data from any Spark streaming data sources into the dataframe:
```
val df = spark.readStream
  .format("kafka")
  .option("subscribe", "Comment")
  .load()
  .selectExpr("CAST(value AS STRING)").as[(String)]
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Streaming write data to TigerGraph:
```
df.writeStream
  .outputMode("append")
  .format("tigergraph")
  .option("checkpointLocation", "/path/to/checkpoint")
  .options(tgOptions)
  .option("loading.job", "load_Comment")
  .option("loading.filename", "file_Comment")
  .option("loading.separator", "|")
  .option("log.level", "2")
  .option("log.file", "/tmp/tigergraph-spark-connector.log")
  .start()
  .awaitTermination()
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_connector_options)Connector Options
### [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_common_options)Common Options
Beginning with version 0.2.0 of the connector, the following [connector options](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_connector_options) are required: `version`, `log.level`, and `log.file`.  
---  
Key | Default Value | Description | Group  
---|---|---|---  
`url` | (none) | The connection URL to TigerGraph cluster. It can be a list of URLs separated by comma for load balancing. The port number can be retrieved by `gadmin config get Nginx.Port`. For TGCloud users, the default port number is 443. Example: http(s)://192.168.1.1:14240, http(s)://192.168.1.2:14240, http(s)://192.168.1.3:14240 | General  
`version` | (none) | TigerGraph version, e.g., "3.10.1", "4.1.0". | General  
`graph` | (none) | The graph name. | General  
`username` | (none) | The GSQL username. | Authentication (The username/password pair or secret based authentication is more preferred than a fixed token, as it can generate and refresh token automatically.)  
`password` | (none) | The GSQL password. | Authentication  
`secret` | (none) | The GSQL secret, which is recommended for TGCloud users. | Authentication  
`token` | (none) | The classic Bearer token or JWT(since 3.10.1) for RESTPP authentication. | Authentication  
`ssl.mode` | basic | The SSL mode. Supported values: `basic`, `verifyCA` and `verifyHostname`. When setting it to `verifyCA` or `verifyHostname`, the truststore file should be given. | SSL  
`ssl.truststore` | (none) | Filename of the truststore which stores the SSL certificate chains. Add `--files /path/to/trust.jks` when submitting the Spark job. | SSL  
`ssl.truststore.type` | JKS | Truststore type, e.g., JKS, PKCS12 | SSL  
`ssl.truststore.password` | (none) | Password of the truststore. | SSL  
`io.connect.timeout.ms` | 30000 | Connect timeout in ms. | Transport Timeout  
`io.read.timeout.ms` | 60000 | Socket read timeout in ms. | Transport Timeout  
`io.retry.interval.ms` | 5000 | The initial retry interval for transport timeout. | Transport Timeout  
`io.max.retry.interval.ms` | 10000 | The maximum retry interval for transport timeout. | Transport Timeout  
`io.max.retry.attempts` | 5 | The maximum retry attempts for transport timeout. | Transport Timeout  
`log.level` | (none) | The log level of the default logger. Available values: "0", "1", "2" and "3", which represent "ERROR", "WARN", "INFO" and "DEBUG". The Spark logging configurations(log4j) will be omitted if this option is set. The log will be printed to stderr unless `log.file` is set. | Logging  
`log.file` | (none) | The log file name pattern, e.g., "/tmp/tigergraph-spark-connector.log". It requires setting `log.level` first. | Logging  
### [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_writer_options)Writer Options
Key | Default Value | Description | Group  
---|---|---|---  
`loading.job` | (none) | The GSQL loading job name. | Loading Job  
`loading.filename` | (none) | The filename defined in the loading job. | Loading Job  
`loading.separator` | , | The column separator. | Loading Job  
`loading.eol` | \n | The line separator. | Loading Job  
`loading.batch.size.bytes` | 2097152 | The maximum batch size in bytes. | Loading Job  
`loading.timeout.ms` | (none) | The loading timeout per batch. | Loading Job  
`loading.max.percent.error` | (none) | The threshold of the error objects count. The loading job will be aborted when reaching the limit. Only available for TigerGraph version 3.10.0+. | Loading Job  
`loading.max.num.error` | (none) | The threshold of the error objects percentage. The loading job will be aborted when reaching the limit. Only available for TigerGraph version 3.10.0+. | Loading Job  
`loading.retry.interval.ms` | 5000 | The initial retry interval for transient server errors. | Loading Job  
`loading.max.retry.interval.ms` | 30000 | The maximum retry interval for transient server errors. | Loading Job  
`loading.max.retry.attempts` | 10 | The maximum retry attempts for transient server errors. | Loading Job  
## [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_use_cases)Use Cases
### [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_load_data_from_delta_lake)Load Data from Delta Lake
#### [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_batch_write_2)Batch Write
Load delta table to Spark dataframe:
```
val df = spark.read.format("delta")
  .load("/path/to/delta/table")
  .select(
    "creationDate",
    "id",
    "locationIP",
    "browserUsed",
    "content",
    "length"
  )
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Batch write the data into TigerGraph:
```
df.write
  .format("tigergraph")
  .mode("append")
  .options(tgOptions)
  .option("loading.job", "load_Comment")
  .option("loading.filename", "file_Comment")
  .option("loading.separator", "|")
  .option("log.level", "2")
  .option("log.file", "/tmp/tigergraph-spark-connector.log")
  .save()
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_streaming_writecdc)Streaming Write(CDC)
Streaming read from delta table:
```
val df = spark.readStream
  .format("delta")
  .option("readChangeFeed", "true")
  .load("/path/to/delta/table")
  .filter(
    $"_change_type" === "insert" || $"_change_type" === "update_postimage"
  )
  .select(
    "creationDate",
    "id",
    "locationIP",
    "browserUsed",
    "content",
    "length"
  )
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Streaming write data to TigerGraph:
```
df.writeStream
  .outputMode("append")
  .format("tigergraph")
  .option("checkpointLocation", "/path/to/checkpoint")
  .options(tgOptions)
  .option("loading.job", "load_Comment")
  .option("loading.filename", "file_Comment")
  .option("loading.separator", "|")
  .start()
  .option("log.level", "2")
  .option("log.file", "/tmp/tigergraph-spark-connector.log")
  .awaitTermination()
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

For more details on Delta Lake see [Welcome to the Delta Lake documentation — Delta Lake Documentation](https://docs.delta.io/latest/index.html).
### [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_load_data_from_iceberg)Load Data from Iceberg
#### [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_batch_write_3)Batch Write
Load Iceberg table to Spark dataframe:
```
val df = spark.table("catalog.db.table")
  .select(
    "creationDate",
    "id",
    "locationIP",
    "browserUsed",
    "content",
    "length"
  )
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Batch write the data into TigerGraph:
```
df.write
  .format("tigergraph")
  .mode("append")
  .options(tgOptions)
  .option("loading.job", "load_Comment")
  .option("loading.filename", "file_Comment")
  .option("loading.separator", "|")
  .option("log.level", "2")
  .option("log.file", "/tmp/tigergraph-spark-connector.log")
  .save()
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_streaming_writecdc_2)Streaming Write(CDC)
Streaming read from Iceberg table:
```
val df = spark.readStream
  .format("iceberg")
  .option("stream-from-timestamp", 0L)
  .load("catalog.db.table")
  .select(
    "creationDate",
    "id",
    "locationIP",
    "browserUsed",
    "content",
    "length"
  )
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Streaming write data to TigerGraph:
```
df.writeStream
  .outputMode("append")
  .format("tigergraph")
  .option("checkpointLocation", "/path/to/checkpoint")
  .options(tgOptions)
  .option("loading.job", "load_Comment")
  .option("loading.filename", "file_Comment")
  .option("loading.separator", "|")
  .option("log.level", "2")
  .option("log.file", "/tmp/tigergraph-spark-connector.log")
  .start()
  .awaitTermination()
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

For more details on Iceberg see [Iceberg Apache: Getting Started](https://iceberg.apache.org/docs/1.3.1/getting-started/)
### [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_load_data_from_hudi)Load Data from Hudi
#### [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_batch_write_4)Batch Write
Load Hudi table to Spark dataframe:
```
val df = spark.read
  .format("hudi")
  .load("/path/to/hudi/table")
  .select(
    "creationDate",
    "id",
    "locationIP",
    "browserUsed",
    "content",
    "length"
  )
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Batch write the data into TigerGraph
```
df.write
  .format("tigergraph")
  .mode("append")
  .options(tgOptions)
  .option("loading.job", "load_Comment")
  .option("loading.filename", "file_Comment")
  .option("loading.separator", "|")
  .option("log.level", "2")
  .option("log.file", "/tmp/tigergraph-spark-connector.log")
  .save()
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_streaming_writecdc_3)Streaming Write(CDC)
Streaming read from Hudi table:
```
val df = spark.readStream
  .format("hudi")
  .load("/path/to/hudi/table")
  .select(
    "creationDate",
    "id",
    "locationIP",
    "browserUsed",
    "content",
    "length"
  )
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Streaming write data to TigerGraph:
```
df.writeStream
  .outputMode("append")
  .format("tigergraph")
  .option("checkpointLocation", "/path/to/checkpoint")
  .options(tgOptions)
  .option("loading.job", "load_Comment")
  .option("loading.filename", "file_Comment")
  .option("loading.separator", "|")
  .option("log.level", "2")
  .option("log.file", "/tmp/tigergraph-spark-connector.log")
  .start()
  .awaitTermination()
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

For more details on Hudi see [Spark Guide | Apache Hudi](https://hudi.apache.org/docs/quick-start-guide/).
## [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_loading_statistics)Loading Statistics
When you configure the logging properly and set log level to `info`, the loading statistics will be logged.
There are 3 levels of stats:
  * **Batch level** : Data will be loaded to TigerGraph in micro batches. The count of malformed or invalid data of each batch will be logged.
  * **Partition level** : The data source can contain multiple partitions, and the log will show how many rows of a partition has been sent to TigerGraph.
  * **Job Level (only available for TigerGraph 3.10+)** : The overall loading statistics of the Spark job aggregated by TigerGraph service KAFKASTRM-LL. This requires providing username and password to query `/gsqlserver` endpoint.


Sample loading statistics:
```
24/01/22 16:15:45 INFO TigerGraphBatchWrite: Overall loading statistics: [ {
  "overall" : {
    "duration" : 15792,
    "size" : 48675207,
    "progress" : 0,
    "startTime" : 1706770863875,
    "averageSpeed" : 29546,
    "id" : "test_graph.load_Comment.spark.all.1706770859889",
    "endTime" : 1706770879667,
    "currentSpeed" : 29546,
    "statistics" : {
      "fileLevel" : {
        "validLine" : 466594,
        "notEnoughToken" : 0,
        "tokenExceedsBuffer" : 0,
        "rejectLine" : 0
      },
      "objectLevel" : {
        "vertex" : [ {
        "validObject" : 466593,
        "typeName" : "Comment",
        "invalidPrimaryId" : 1
        } ]
      }
    }
  },
  "workers" : [ {
    "tasks" : [ {
      "filename" : "file_Comment"
    } ]
  }, {
  "tasks" : [ {
    "filename" : "file_Comment"
    } ]
  } ]
} ]
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_row_level_statistics)Row Level Statistics
Row Level Statistics | Description  
---|---  
`validLine` | Number of valid raw data lines parsed.  
`rejectLine` | Number of raw data lines rejected by the reject line rule in the loading script.  
`notEnoughToken` | Number of raw data lines with fewer tokens than what was specified by the loading script.  
`badCharacter` | Number of raw data lines containing invalid characters.  
`tokenExceedsBuffer` | Number of raw data lines containing oversize tokens (see `gadmin config get GSQL.OutputTokenBufferSize`).  
`emptyLine` | Number of raw data lines that are empty.  
### [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe#_object_level_statistics)Object Level Statistics
Object Level Statistics | Description  
---|---  
`validObject` | Number of data records created.  
`passedCondition` | Number of token lists which passed the WHERE predicate filter.  
`failedCondition` | Number of token lists which failed the WHERE predicate filter.  
`invalidPrimaryId` | Number of token lists where the id token is invalid.  
`noIdFound` | Number of token lists where the id token is empty.  
`invalidAttribute` | Number of token lists where at least one of the attribute tokens is invalid.  
`incorrectFixedBinaryLength` | Number of token lists where at least one of the tokens corresponding to a UDT type attribute is invalid.  
`invalidVertexType` | Number of token lists where at least one of the tokens corresponding to an edge type’s source/target vertex type is invalid.  
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


