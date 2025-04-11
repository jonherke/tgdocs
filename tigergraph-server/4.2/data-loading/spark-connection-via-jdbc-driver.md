![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver)[Next](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver)
[Developer Site](https://dev.tigergraph.com/) [Community Forum](https://community.tigergraph.com/) [Knowledge Base](https://tigergraph.freshdesk.com/support/solutions)
[Download](https://dl.tigergraph.com)
[ TG Savanna](https://savanna.tgcloud.io)
### [TigerGraph DB](https://docs.tigergraph.com/tigergraph-server/4.2/intro/)
  *     * [TigerGraph DB Release Notes](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/)
  *     * [Architecture](https://docs.tigergraph.com/tigergraph-server/4.2/intro/internal-architecture)
      * [Transaction Processing and ACID Support](https://docs.tigergraph.com/tigergraph-server/4.2/intro/transaction-and-acid)
      * [Continuous Availability Overview](https://docs.tigergraph.com/tigergraph-server/4.2/intro/continuous-availability-overview)
  *     * Get Started
      * [Installation](https://docs.tigergraph.com/tigergraph-server/4.2/getting-started/)
        * [On Docker](https://docs.tigergraph.com/tigergraph-server/4.2/getting-started/docker)
        * [On Linux](https://docs.tigergraph.com/tigergraph-server/4.2/getting-started/linux)
          * [Hardware and Software Requirements](https://docs.tigergraph.com/tigergraph-server/4.2/installation/hw-and-sw-requirements)
          * [Linux On Bare Metal](https://docs.tigergraph.com/tigergraph-server/4.2/installation/bare-metal-install)
          * [Post Install Checks](https://docs.tigergraph.com/tigergraph-server/4.2/installation/post-install-check)
        * [On Kubernetes](https://docs.tigergraph.com/tigergraph-server/4.2/getting-started/kubernetes)
        * [On Cloud Marketplace](https://docs.tigergraph.com/tigergraph-server/4.2/getting-started/cloud-images/)
          * [AWS](https://docs.tigergraph.com/tigergraph-server/4.2/getting-started/cloud-images/aws)
          * [Azure](https://docs.tigergraph.com/tigergraph-server/4.2/getting-started/cloud-images/azure)
          * [GCP](https://docs.tigergraph.com/tigergraph-server/4.2/getting-started/cloud-images/gcp)
        * [Advanced License Issues](https://docs.tigergraph.com/tigergraph-server/4.2/installation/license)
        * [Changing Ports](https://docs.tigergraph.com/tigergraph-server/4.2/installation/change-port)
        * [Change IP or Hostname](https://docs.tigergraph.com/tigergraph-server/4.2/installation/change-ip-or-hostname)
        * [Upgrade](https://docs.tigergraph.com/tigergraph-server/4.2/installation/upgrade)
        * [Uninstallation](https://docs.tigergraph.com/tigergraph-server/4.2/installation/uninstallation)
      * [The GSQL Shell](https://docs.tigergraph.com/tigergraph-server/4.2/gsql-shell/)
        * [GSQL Shell Sessions](https://docs.tigergraph.com/tigergraph-server/4.2/gsql-shell/gsql-sessions)
        * [Using a Remote GSQL Client](https://docs.tigergraph.com/tigergraph-server/4.2/gsql-shell/using-a-remote-gsql-client)
        * [The GSQL Shell](https://docs.tigergraph.com/tigergraph-server/4.2/gsql-shell/)
  *     * [Clustering](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/)
      * Cluster Resizing
        * [Cluster Expansion](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/expand-a-cluster)
        * [Cluster Shrinking](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/shrink-a-cluster)
        * [Cluster Repartition](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/repartition-a-cluster)
        * [Removal of Failed Nodes](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/remove-failed-node)
        * [Replace a Node](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/how_to-replace-a-node-in-a-cluster)
      * [Cross-Region Replication](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/crr-index)
        * [Set Up Cross-Region Replication](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/set-up-crr)
        * [Fail over to the DR cluster](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/fail-over)
        * [Troubleshooting CRR](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/troubleshooting)
        * [Cross-Region Replication FAQ](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/crr-faq)
      * [High Availability](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-overview)
        * [High Availability Cluster Configuration](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-cluster)
        * [Region Aware Cluster Configuration](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/region-aware)
        * [GSQL Server HA](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server)
        * [Application Server HA](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-application-server)
      * [Cluster Commands](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/cluster-commands)
  *     * [Set Up Data Connectors](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/)
      * [Overview](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/data-loading-overview)
      * [Load from Local Files](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/load-local-files)
      * [from Cloud Storage](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/load-from-cloud)
      * [from Data Warehouse](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/load-from-warehouse)
      * [from External Kafka](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/load-from-kafka)
        * [Avro Data Validation](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/avro-validation-with-kafka)
        * [Kafka SSL Security Guide](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/kafka-ssl-security-guide)
      * [from Spark](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/load-from-spark-dataframe)
      * [to Spark](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe)
      * [Externalize Kafka Configs](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/externalizing-kafka-configs)
      * [Manage Data Sources](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/manage-data-source)
      * [Data Loading V2 (Beta)](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/data-loading-v2)
  *     * [Querying](https://docs.tigergraph.com/tigergraph-server/4.2/data-querying/README)
      * [Define a Graph Schema](https://docs.tigergraph.com/tigergraph-server/4.2/getting-started/database-definition)
  *     * [Manage Your Database](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/)
      * [GADMIN Utility](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/management-commands)
      * [Access Management](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/)
        * Authentication
          * [Enabling User Authentication](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/enabling-user-authentication)
          * [User Credentials](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-credentials)
          * [Single Sign-On](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/sso)
          * [Lightweight Directory Access Protocol (LDAP)](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/ldap)
          * [OIDC JWT Authentication](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/jwt-token)
        * Authorization
          * [User Management](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management)
          * [Access Control Model](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model)
          * [Fine-Grained Query Privileges](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/fine-grained-query-privileges)
            * [Migrate Query Privileges from 3.x to 4.1](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/query-privilege-migration)
          * [Role Management](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/role-management)
          * [Row Policies](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/row-policy-overview)
            * [Key Concepts](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy)
            * [Set Up Row Policy](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/setup-row-policy)
          * [Access Control Lists (ACLs) (Deprecated)](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/acl-management)
      * [Backup and Export](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/)
        * [Backup and Restore Configurations](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/configurations)
        * [Back up a Database Cluster](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/backup-cluster)
        * [Incremental Backup](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/incremental-backup)
        * [Online Backup](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/online-backup)
        * Restore
          * [Restore](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/restore-backup-same)
          * [Restore to a Different Cluster](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/restore-cross-cluster)
          * [Point-in-Time Restore](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/point-in-time-restore)
        * Export/Import
          * [Database Import/Export All Graphs](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export)
          * [Import/Export Individual Graphs](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/single-graph-import-export)
        * [Legacy Backup and Restore](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/gbar-legacy)
        * [Change Data Capture (CDC)](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/change-data-capture/cdc-overview)
          * [CDC Setup](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/change-data-capture/cdc-setup)
          * [CDC Message Examples](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/change-data-capture/cdc-message-example)
          * [CDC Monitoring and Reset](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/change-data-capture/cdc-state-monitoring)
      * [Kubernetes](https://docs.tigergraph.com/tigergraph-server/4.2/kubernetes/)
        * [Kubernetes Operator](https://docs.tigergraph.com/tigergraph-server/4.2/kubernetes/k8s-operator/)
      * [Logs](https://docs.tigergraph.com/tigergraph-server/4.2/troubleshooting/log-files)
      * [Resources and Processes](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/resource-and-process-mgmt)
        * [Memory Management](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management)
        * [Service Management](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/manage-services)
        * [Workload Management](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/workload-management)
        * [Using gadmin](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/management-with-gadmin)
        * [Metrics Reports](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/system-metrics)
      * [Security](https://docs.tigergraph.com/tigergraph-server/4.2/security/)
        * [Auditing Privileged User Actions](https://docs.tigergraph.com/tigergraph-server/4.2/security/audit-privileged-actions)
        * [Encrypting Connections](https://docs.tigergraph.com/tigergraph-server/4.2/security/encrypting-connections)
        * [Encrypting Data At Rest](https://docs.tigergraph.com/tigergraph-server/4.2/security/encrypting-data-at-rest)
        * [File Input Policy](https://docs.tigergraph.com/tigergraph-server/4.2/security/gsql-file-input-policy)
        * [File Output Policy](https://docs.tigergraph.com/tigergraph-server/4.2/security/file-output-policy)
        * [Login Policy](https://docs.tigergraph.com/tigergraph-server/4.2/security/login-protection)
        * [Password Policy](https://docs.tigergraph.com/tigergraph-server/4.2/security/password-policy)
  *     * References
      * [Best Practices](https://docs.tigergraph.com/tigergraph-server/4.2/additional-resources/best-practice-guides/best-practices-overview)
      * [Configuration Parameters](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters)
      * [gadmin Commands](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/management-commands)
      * [REST Endpoints](https://docs.tigergraph.com/tigergraph-server/4.2/API/)
        * [GSQL Endpoints](https://docs.tigergraph.com/tigergraph-server/4.2/API/gsql-endpoints)
        * [RESTPP & Infra Endpoints](https://docs.tigergraph.com/tigergraph-server/4.2/API/built-in-endpoints)
        * [Upsert Data](https://docs.tigergraph.com/tigergraph-server/4.2/API/upsert-rest)
      * [RBAC Object-Based Privileges](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/row-policy-privileges-table)
        * [RBAC Row Policy EBNF](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/row-policy-ebnf)
        * [List of Legacy Privilege Syntax](https://docs.tigergraph.com/tigergraph-server/4.2/reference/list-of-privileges)
      * [List of Ports](https://docs.tigergraph.com/tigergraph-server/4.2/reference/ports)
      * [Return codes](https://docs.tigergraph.com/tigergraph-server/4.2/reference/return-codes)
      * [Troubleshooting and FAQs](https://docs.tigergraph.com/tigergraph-server/4.2/troubleshooting/troubleshooting-guide)
      * More References
        * [Compare TigerGraph Editions](https://docs.tigergraph.com/tigergraph-server/4.2/intro/comparison-of-editions)
        * [Documentation for Legacy Versions](https://docs.tigergraph.com/tigergraph-server/4.2/additional-resources/legacy-tg-versions)
        * [Patents and Third Party Software](https://docs.tigergraph.com/tigergraph-server/4.2/reference/patents-and-third-party-software)
        * [TigerGraph Glossary](https://docs.tigergraph.com/tigergraph-server/4.2/reference/glossary)
        * [TigerGraph Release And Patch Process](https://docs.tigergraph.com/tigergraph-server/4.2/intro/release-process)


TigerGraph DB 4.2 Pre
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
  * [TigerGraph DB 4.2 Pre](https://docs.tigergraph.com/tigergraph-server/4.2/intro/)
  * [Spark Connection Via JDBC Driver (Deprecated)](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/4.2/modules/data-loading/pages/spark-connection-via-jdbc-driver.adoc)
### Contents
  * [Load from a Data Lake via Spark](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver#_load_from_a_data_lake_via_spark)
  * [1) Write a Spark DataFrameWriter](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver#_1_write_a_spark_dataframewriter)
  * [2) Create a Loading Job](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver#_2_create_a_loading_job)
  * [Advanced Usages with Spark](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver#_advanced_usages_with_spark)
  * [Enable SSL with Spark](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver#_enable_ssl_with_spark)
  * [Load Statistics](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver#_load_statistics)
  * [Configuration Options with Spark](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver#_configuration_options_with_spark)
  * [Specific Usages for a Spark DataFrame in TigerGraph](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver#_specific_usages_for_a_spark_dataframe_in_tigergraph)
  * [Bulk Load](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver#_bulk_load)
  * [Capture Changes in Batch Queries](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver#_capture_changes_in_batch_queries)
  * [Full Example](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver#_full_example)


# Spark Connection Via JDBC Driver (Deprecated)
### Contents
  * [Load from a Data Lake via Spark](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver#_load_from_a_data_lake_via_spark)
  * [1) Write a Spark DataFrameWriter](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver#_1_write_a_spark_dataframewriter)
  * [2) Create a Loading Job](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver#_2_create_a_loading_job)
  * [Advanced Usages with Spark](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver#_advanced_usages_with_spark)
  * [Enable SSL with Spark](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver#_enable_ssl_with_spark)
  * [Load Statistics](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver#_load_statistics)
  * [Configuration Options with Spark](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver#_configuration_options_with_spark)
  * [Specific Usages for a Spark DataFrame in TigerGraph](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver#_specific_usages_for_a_spark_dataframe_in_tigergraph)
  * [Bulk Load](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver#_bulk_load)
  * [Capture Changes in Batch Queries](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver#_capture_changes_in_batch_queries)
  * [Full Example](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver#_full_example)


Please see [Load from Spark Dataframe](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/load-from-spark-dataframe) for information on the Spark connector.  
---  
Apache Spark is a popular big data distributed processing system which is frequently used in data management ETL process and Machine Learning applications.
Using the open-source type 4 JDBC Driver for TigerGraph, you can read and write data between Spark and TigerGraph. This is a two-way data connection.
![Diagram showing streaming and static data sources using Apache Spark and the TigerGraph JDBC server to perform two-way communication with TigerGraph services. The TigerGraph services shown are Graph Insights and applications, graph business intelligence, and graph visualization, all under the theme of Real-Time Graph Analytics.](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/_images/load-from-spark-via-jdbc.png)
Figure 1. Apache Spark, containing streaming and static data sources, uses the JDBC driver to communicate back and forth with TigerGraph in order to perform graph analytics.
The GitHub Link to the JDBC Driver is <https://github.com/tigergraph/ecosys/tree/master/tools/etl/tg-jdbc-driver>
The README file there provides more details.
TigerGraph JDBC connector is streaming in data via REST endpoints. No data throttle mechanism is in place yet. When the incoming concurrent JDBC connection number exceeds the configured hardware capacity limit, the overload may cause the system to stop responding. If you use spark job to connect TigerGraph via JDBC, we recommend your concurrent spark loading jobs be capped at 10 with the following per job configuration. This limits the concurrent JDBC connections to 40. ```
—-num-executors 2 /* 2 executors per job */
—-executor-cores 2 /* 1 executor take 2 cores */
```
  
---  
## [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver#_load_from_a_data_lake_via_spark)Load from a Data Lake via Spark
### [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver#_1_write_a_spark_dataframewriter)1) Write a Spark `DataFrameWriter`
Spark DataFrame `write` method with TigerGraph JDBC connector supports writing data from arbitrary data sources to pre-defined TigerGraph GSQL loading jobs, through a `/ddl` endpoint.
The DataFrame will be converted to delimited data and sent to TigerGraph by micro batches.
You need to choose names for a GSQL loading job and its data files that you will be using in Step 2.   
---  
Example: `DataFrameWriter` as "df"
```
df.write.mode("overwrite").format("jdbc").options(
  Map(
    "driver" -> "com.tigergraph.jdbc.Driver",
    "url" -> "jdbc:tg:http://host:port",
    "username" -> "tigergraph",
    "password" -> "tigergraph",
    "token" -> "token",
    "graph" -> "Social", // graph name
    "dbtable" -> "job load_Social", // loading job name, "job" is required
    "filename" -> "file1", // filename defined in the loading job
    "sep" -> ",", // separator between columns
    "eol" -> "\n", // end of line
    "batchsize" -> "10000"))
  .save()
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The `sep` and `eol` will be used to convert the `DataFrame` to delimited data and that will be sent to the filename defined by the loading job.
Example: DataFrame
```
> DataFrame
+-----+---+------+
| _c0|_c1|  _c2|
+-----+---+------+
| Tom| 23| male|
|Jerry| 45| male|
|Jenny| 33|female|
|Lizzy| 19|female|
+-----+---+------+
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Example: Delimited Data
```
Tom,23,male
Jerry,45,male
Jenny,33,female
Lizzy,19,female
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver#_2_create_a_loading_job)2) Create a Loading Job
Write a GSQL loading job, using the job and file names that you used in step 1, to map data from the CSV file(s) to TigerGraph vertices and edges.
Example:
```
CREATE LOADING JOB load_Social FOR GRAPH Social {
  DEFINE FILENAME file1;
  DEFINE FILENAME file2;
  LOAD file1 TO VERTEX Person VALUES ($0, $1, $2);
  LOAD file2 TO EDGE Friendship VALUES ($0, $1);
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The loading job above, `load_Social` loads the 1st, 2nd, and 3rd columns of source file, `file1`, to the 1st, 2nd, and 3rd attributes of the vertex `Person`.
See the pages [Creating a Loading Job](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/creating-a-loading-job), [Running a Loading Job](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/running-a-loading-job) and [Loading Jobs as a REST Endpoint](https://docs.tigergraph.com/tigergraph-server/4.2/API/built-in-endpoints#_loading_jobs) for more information about loading jobs in TigerGraph.
## [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver#_advanced_usages_with_spark)Advanced Usages with Spark
### [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver#_enable_ssl_with_spark)Enable SSL with Spark
Add the following options to your scala script:
```
  "trustStore" -> "trust.jks",
  "trustStorePassword" -> "password",
  "trustStoreType" -> "JKS",
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

And run it with `--files` option like this:
```
/path/to/spark/bin/spark-shell --jars /path/to/tigergraph-jdbc-driver-${VERSION}.jar --files /path/to/trust.jks -i test.scala
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The `--files` should be provided the JKS file path, while the `"trustStore" → "trust.jks"` should be the JKS filename only.
### [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver#_load_statistics)Load Statistics
TigerGraph JDBC connector is streaming in data via REST endpoints. No data throttle mechanism is in place yet. When the incoming concurrent JDBC connection number exceeds the configured hardware capacity limit, the overload may cause the system to stop responding. If you use a Spark job to connect TigerGraph via JDBC, we recommend your concurrent Spark loading jobs be capped at 10 with the following per job configuration. This limits the concurrent JDBC connections to 40.  
---  
To load data from files:
Example: 2 executors per job where each executor takes 2 cores.
```
/path/to/spark/bin/spark-shell --jars /path/to/tigergraph-jdbc-driver-${VERSION}.jar -—num-executors 2 —-executor-cores 2 -i test.scala
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Example: Invoke loading job
```
val df = sc.textFile("/path/to/your_file", 100).toDF()
df.write.mode("append").format("jdbc").options(
  Map(
    "driver" -> "com.tigergraph.jdbc.Driver",
    "url" -> "jdbc:tg:http://127.0.0.1:14240",
    "username" -> "tigergraph",
    "password" -> "tigergraph",
    "graph" -> "ldbc_snb",
    "dbtable" -> "job load_ldbc_snb", // loading job name
    "filename" -> "v_comment_file", // filename defined in the loading job
    "sep" -> "|", // separator between columns
    "eol" -> "\n", // End Of Line
    "batchsize" -> "10000",
    "debug" -> "0",
    "logFilePattern" -> "/tmp/jdbc.log")).save()
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**If your TG version is 3.9.0 or higher, please use the following new features:**
  * `jobid`: Since the Spark loading is sending data in multiple batches, it’s hard to collect the loading stats of all the batches. The `jobid` is a new connection property that helps aggregate the stats of each batch loading, so the overall loading stats can be easily acquired.
  * `max_num_error`: The threshold of the error objects count within the `jobid`. The loading job will be aborted when reaching the limit. `jobid` is required.
  * `max_percent_error`: Is the threshold of the error objects percentage within the `jobid`. The loading job will be aborted when reaching the limit. `jobid` is required.


For a more detailed example, please refer to the [GitHub link](https://github.com/tigergraph/ecosys/blob/master/tools/etl/tg-jdbc-driver/tg-jdbc-examples/src/main/java/com/tigergraph/jdbc/examples/SparkLoadingJob.scala#L55-L57).   
---  
**For the`"batchsize"` option:**
  * **If it is set too small** , lots of time will be spent on setting up connections.
  * **If it is too large** , the http payload may exceed limit (the default TigerGraph Rest++ maximum payload size is 128MB). Furthermore, a large `"batchsize"` may result in high jitter performance.


To bypass the disk IO limitation, it is better to put the raw data file on a different disk other than the one used by TigerGraph.
## [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver#_configuration_options_with_spark)Configuration Options with Spark
Property Name | Default | Meaning | Required  
---|---|---|---  
`driver` | (none) | Fully qualified domain name(FQCN) of the JDBC driver: `com.tigergraph.jdbc.Driver`. | Yes  
`url` | (none) | The JDBC URL to connect to: `jdbc:tg:http(s)://ip:port`, this port is the one used by GraphStudio. | Yes  
`graph` | (none) | The graph name. | Yes  
`version` | 3.9.0 | The TigerGraph version. | Yes  
`username` | tigergraph | TigerGraph username. | If [REST++ authentication](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/enabling-user-authentication) is enabled, a username/password or token is required.  
`password` | tigergraph | TigerGraph password. | If [REST++ authentication](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/enabling-user-authentication) is enabled, a username/password or token is required.  
`token` | (none) | A token used to authenticate RESTPP requests. Request a token | If [REST++ authentication](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/enabling-user-authentication) is enabled, a username/password or token is required.  
`jobid` (TG version >= 3.9.0) | (none) | A unique ID for tracing aggregated loading statistics. | No  
`max_num_error` (TG version >= 3.9.0) | (none) | The threshold of the error objects count within the `jobid`. The loading job will be aborted when reaching the limit. `jobid` is required. | No  
`max_percent_error` (TG version >= 3.9.0) | (none) | The threshold of the error objects percentage within the `jobid`. The loading job will be aborted when reaching the limit. `jobid` is required. | No  
`filename` | (none) | The filename defined in the loading job. | Yes  
`sep` | (none) | Column separator. E.g., ,. | Yes  
`eol` | (none) | Line separator. E.g., \n. | Yes  
`dbtable` | (none) | The specification of the operation of the form: `operation_type` `operation_object`. For loading job: `job JOB_NAME`; E.g. for querying loading statistics: `jobid JOB_ID`. | Yes  
`batchsize` | 1000 | Maximum number of lines per POST request. | Yes  
`debug` | 2 | Log level:0 → ERROR, 1 → WARN, 2 → INFO, 3 → DEBUG | Yes  
`logFilePattern` | (none) | The log file name pattern, e.g., "/tmp/tigergraph-jdbc-driver.log", the log will be printed to stderr when it is not given | all  
`ip_list` | (none) | A string that contains IP addresses of TigerGraph nodes separated by a comma, which can be used for load balancing. E.g., `192.168.0.50,192.168.0.51,192.168.0.52` | No  
`trustStore` | (none) | Filename of the truststore which stores the SSL certificate. Please add `--files /path/to/trust.jks` when submitting the Spark job. | No  
`trustStorePassword` | (none) | Password of the truststore. | No  
`trustStoreType` | (none) | Truststore type, e.g., jks. | No  
`sslHostnameVerification` | true | Whether to verify the host name in the url matches the host name in the certificate. | No  
`queryTimeout` | RESTPP.Factory.DefaultQueryTimeoutSec | The timeout (s) for REST++ request. | No  
`connectTimeout` | 30 | The connect timeout (s) for HTTP client. | No  
## [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver#_specific_usages_for_a_spark_dataframe_in_tigergraph)Specific Usages for a Spark DataFrame in TigerGraph
### [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver#_bulk_load)Bulk Load
To read the full delta table as a Spark DataFrame and a bulk load to TigerGraph:
```
val df = spark.read.format("delta").load("/tmp/delta-table")
df.write.mode("overwrite").format("jdbc").options(
  Map(
    "driver" -> "com.tigergraph.jdbc.Driver",
    "url" -> "jdbc:tg:http://host:port",
    ...))
  .save()
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver#_capture_changes_in_batch_queries)Capture Changes in Batch Queries
  1. Enable the change data feed option on the Delta table:
```
ALTER TABLE myDeltaTable SET TBLPROPERTIES (delta.enableChangeDataFeed = true)
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  2. Capture the changes into a DataFrame:
Example 1: Version is type `int` or `long`:
```
val df = spark.read.format("delta")
  .option("readChangeFeed", "true")
  .option("startingVersion", 0)
  .option("endingVersion", 10)
  .table("myDeltaTable")
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Example 2: Timestamps as formatted as `timestamp`:
```
val df = spark.read.format("delta")
  .option("readChangeFeed", "true")
  .option("startingTimestamp", "2021-04-21 05:45:46")
  .option("endingTimestamp", "2021-05-21 12:00:00")
  .table("myDeltaTable")
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Example 3: Providing only the starting Version/timestamp:
```
val df = spark.read.format("delta")
  .option("readChangeFeed", "true")
  .option("startingVersion", 0)
  .table("myDeltaTable")
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Example 4: Path to table:
```
val df = spark.read.format("delta")
  .option("readChangeFeed", "true")
  .option("startingTimestamp", "2021-04-21 05:45:46")
  .load("pathToMyDeltaTable")
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  3. Filter the changes:
The DataFrame containing the changes of the Delta table has [3 additional columns](https://docs.databricks.com/en/delta/delta-change-data-feed.html#what-is-the-schema-for-the-change-data-feed):
Column name | Type | Values  
---|---|---  
`_change_type` | String | insert, update_preimage , update_postimage, delete  
`_commit_version` | Long | The Delta log or table version containing the change.  
`_commit_timestamp` | Timestamp | The timestamp associated when the commit was created.  
A TigerGraph GSQL loading job only supports an insertion or an updating type, so filtering of the result is needed:
```
df.filter($"_change_type" === "insert" || $"_change_type" === update_postimage)
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  4. Select original data columns:
```
df.select("_c0", "_c1", "_c2")
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  5. Write the DataFrame to TigerGraph:
```
df.write.mode("overwrite").format("jdbc").options(
  Map(
    "driver" -> "com.tigergraph.jdbc.Driver",
    "url" -> "jdbc:tg:http://host:port",
    ...))
  .save()
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```



### [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver#_full_example)Full Example
Below is a full example of the previous steps with more options.
Capture changes + filter the insertion and updating:
```
val df = spark.read.format("delta")
  .option("readChangeFeed", "true")
  .option("startingVersion", 0)
  .option("endingVersion", 10)
  .table("myDeltaTable")
  .filter($"_change_type" === "insert" || $"_change_type" === update_postimage)
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Now write the changes from the DataFrame to TigerGraph
```
df.write.mode("overwrite").format("jdbc").options(
  Map(
    "driver" -> "com.tigergraph.jdbc.Driver",
    "url" -> "jdbc:tg:http://host:port",
    "username" -> "tigergraph",
    "password" -> "tigergraph",
    "token" -> "token",
    "graph" -> "Social", // graph name
    "dbtable" -> "job load_Social", // loading job name, "job" is required
    "filename" -> "file1", // filename defined in the loading job
    "sep" -> ",", // separator between columns
    "eol" -> "\n", // end of line
    "batchsize" -> "10000"))
  .save()
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


