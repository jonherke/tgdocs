![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/configurations)[Next](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/configurations)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/configurations)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/configurations)
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
  * Advanced Topics
  * [Backup and Restore](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/)
  * [Backup and Restore Configurations](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/configurations)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/3.11/modules/backup-and-restore/pages/configurations.adoc)
### Contents
  * [Prerequisites](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/configurations#_prerequisites)
  * [Configuration parameters](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/configurations#_configuration_parameters)
  * [Configure System.Backup.S3.Endpoint](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/configurations#_configure_system_backup_s3_endpoint)
  * [Backup to AWS S3](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/configurations#_backup_to_aws_s3)
  * [Backup to ABS (Azure Blob Storage)](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/configurations#_backup_to_abs_azure_blob_storage)
  * [Backup to GCS (Google Cloud Storage)](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/configurations#_backup_to_gcs_google_cloud_storage)


# Backup and Restore Configurations
### Contents
  * [Prerequisites](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/configurations#_prerequisites)
  * [Configuration parameters](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/configurations#_configuration_parameters)
  * [Configure System.Backup.S3.Endpoint](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/configurations#_configure_system_backup_s3_endpoint)
  * [Backup to AWS S3](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/configurations#_backup_to_aws_s3)
  * [Backup to ABS (Azure Blob Storage)](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/configurations#_backup_to_abs_azure_blob_storage)
  * [Backup to GCS (Google Cloud Storage)](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/configurations#_backup_to_gcs_google_cloud_storage)


This page describes the configuration options available for backup and restore on TigerGraph and how to set them. You can use `gadmin config set <parameter>` to change the value of any parameter.
`gadmin config entry backup` will walk you though all the available backup comfiguration parameters interactively. Enter a value for the ones you want to change; move past the ones you don’t want to set.   
---  
After configuring the parameters, run `gadmin config apply -y` to apply the new parameter values.
To save to cloud storage, the container name and access credentials need to be configured. After the [table of configuration parameters](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/configurations#_configuration_parameters), you will find instructions for configuring backup to
  * [to AWS S3](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/configurations#_backup_to_aws_s3)
  * [to Azure Blob Storage](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/configurations#_backup_to_abs_azure_blob_storage)
  * [to Google Cloud Storage](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/configurations#_backup_to_gcs_google_cloud_storage)


## [](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/configurations#_prerequisites)Prerequisites
  * You have access to the TigerGraph Linux user account on your cluster. All commands must be run from the TigerGraph Linux user.


## [](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/configurations#_configuration_parameters)Configuration parameters
The following is a list of configurations available for backup and restore.
For `System.Backup.Local.Enable`, `System.Backup.S3.Enable`, `System.Backup.ABS.Enable`, and `System.Backup.GCS.Enable`, only one can be enabled at a time.   
---  
Configuration parameter | Description | Default  
---|---|---  
System.Backup.Local.Enable | Whether to store the database backup data to a local path. | `false`  
System.Backup.Local.Path | Local path to store the backup files. Required if backup is to be stored locally. | `null`  
System.Backup.S3.Enable | Enables or disables backup to AWS S3 or S3-compatible services such as Ceph S3. | `false`  
System.Backup.S3.AWSAccessKeyID | AWS Access Key ID for authentication (deprecated, use `System.Backup.S3.AccessKeyID` instead, which has a higher priority.) | `null`  
System.Backup.S3.AWSSecretAccessKey | AWS Secret Access Key for authentication (deprecated, use `System.Backup.S3.SecretAccessKey` instead, which has a higher priority.) **NOTE** : If setting this in interactive mode, store the key in a file and provide the path to the file, e.g., `@/tmp/test_secret`. | `null`  
System.Backup.S3.AccessKeyID | Access key ID for authentication for AWS S3 or S3-compatible services. | `nan`  
System.Backup.S3.SecretAccessKey | Secret Access Key for authentication for AWS S3 or S3-compatible services. **NOTE** : If setting this in interactive mode, store the key in a file and provide the path to the file, e.g., `@/tmp/test_secret`. | `nan`  
System.Backup.S3.BucketName | Bucket for AWS S3 or S3-compatible services. | `nan`  
System.Backup.S3.Endpoint | A URL used to interact with the S3 (AWS S3/S3-compatible) service. It can be used for AWS S3 VPC Endpoint, customer endpoint, or S3-compatible service. For regular AWS S3, leave it empty. | `nan`  
System.Backup.S3.RoleARN | The AWS role for accessing s3 buckets. S3 Role ARN takes priority over access keys. For more information, see [AWS role ARN documentation](https://docs.aws.amazon.com/IAM/latest/APIReference/API_Role.html). **NOTE** : This is only for AWS S3, and TigerGraph assumes the credentials for using `sts:AssumeRole` have been set up. You can verify the credentials are ready by running [aws sts assume-role](https://docs.aws.amazon.com/cli/latest/reference/sts/assume-role.html#examples). One way to set up credentials is to configure access key id, secret access key and region with AWS CLI `aws configure`. | `nan`  
System.Backup.ABS.Enable | Enables or disables backup to ABS (Azure Blob Storage). | `false`  
System.Backup.ABS.ContainerName | Azure storage account container | `nan`  
System.Backup.ABS.AccountName | Azure storage account name for authentication. | `nan`  
System.Backup.ABS.AccountKey | Account key for the Azure storage account. **NOTE** : If setting this in interactive mode, store the key in a file and provide the path to the file, e.g., `@/tmp/test_key`. | `nan`  
System.Backup.ABS.Endpoint | Optional Blob service endpoint; if not given, the default endpoint [https://<account-name>.blob.core.windows.net](https://<account-name>.blob.core.windows.net) will be used. | `nan`  
System.Backup.GCS.Enable | Enables or disables backup to Google Cloud Storage (GCS). | `false`  
System.Backup.GCS.BucketName | GCS bucket. | `nan`  
System.Backup.GCS.AccessKeyID | Access Key for a GCS HMAC Key. | `nan`  
System.Backup.GCS.Secret | Secret for a GCS HMAC Key. **NOTE** : If setting this in interactive mode, store the key in a file and provide the path to the file, e.g., `@/tmp/test_secret`. | `nan`  
System.Backup.GCS.Endpoint | GCS Storage URI. | `https://storage.googleapis.com[](https://storage.googleapis.com)`  
System.Backup.TimeoutSec | Timeout limit for the backup operation in seconds | `18000`  
System.Backup.CompressProcessNumber | Number of concurrent processes for compression during backup. `0` means the number of processes used to compress is equal to the number of CPU cores on each node. We recommending keeping the default value `10`. | `10`  
System.Backup.DecompressProcessNumber | The number of concurrent processes for decompression during the restore. | `8`  
System.Backup.CompressionLevel | The backup compression level strikes a balance between size and speed. The better compression, the longer it takes. ("BestSpeed", "DefaultCompression", "BestCompression") | "DefaultCompression"  
## [](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/configurations#_configure_system_backup_s3_endpoint)Configure System.Backup.S3.Endpoint
## [](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/configurations#_backup_to_aws_s3)Backup to AWS S3
Typically, there’s no need to configure the `System.Backup.S3.Endpoint` parameter on a TigerGraph Server. This is because the system auto-detects the regional endpoint for AWS S3 backups.
Users should configure this parameter **only** for special cases, such as:
  * When using S3 in FIPS mode.
  * When connecting to a private or localized cloud environment.
  * When integrating with an S3-compatible service that requires a specific endpoint.


Except for the above specific situations, leave it empty. For more information please see [AWS Service Endpoints](https://docs.aws.amazon.com/general/latest/gr/s3.html#s3_region).
To configure backup files to an AWS S3 Bucket for an on-premises TigerGraph Server cluster, complete the following steps:
  1. Create an S3 bucket in AWS
  2. Create an AWS IAM user
  3. Create an IAM policy that ensures the IAM user has sufficient access to the bucket itself, and contents within the bucket
```
{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Action": [
        "s3:PutObject",
        "s3:ListBucket",
        "s3:GetObject",
        "s3:GetBucketLocation"
      ],
      "Effect": "Allow",
      "Resource": [
        "arn:aws:s3:::<bucket-name>",
        "arn:aws:s3:::<bucket-name>/*"
      ]
    }
  ]
}
```

  4. Create an `AccessKeyID` and `SecretAccessKey` for the IAM user
TigerGraph clusters use long-lived credentials to authenticate to AWS as the IAM user, allowing TigerGraph access to put backup files into the S3 bucket. These credentials are also used to read and copy files during a Restore process.
  5. Configure each of the following parameters on the linux command line:
Enable storing backup data in S3
```
gadmin config set "System.Backup.S3.Enable" "true"
```

Specify bucket name
```
gadmin config set "System.Backup.S3.BucketName" "<bucket-name>"
```

Set S3 backup AccessKeyID
```
gadmin config set "System.Backup.S3.AccessKeyID" "<access-key-id>"
```

Set S3 backup SecretAccessKey
```
gadmin config set "System.Backup.S3.SecretAccessKey" "<secret-access-key>"
```

Alternatively, instead of using `AccessKeyID` and `SecretAccessKey`, you may use [AWS Role ARN](https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_identifiers.html#identifiers-arnsp) for the authentication.
```
gadmin config set "System.Backup.S3.RoleARN" "arn:aws:iam::account:role/role-name-with-path"
```

Apply the new parameter values
```
gadmin config apply -y
```



Now you are ready to [perform a backup](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/backup-cluster).
## [](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/configurations#_backup_to_abs_azure_blob_storage)Backup to ABS (Azure Blob Storage)
Similar to backing up to AWS S3, once the Azure Blob Storage Container is created and configured properly (refer to [Introduction to Azure Blob Storage](https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blobs-introduction)), then configure it to be your backup storage via the following steps.
  1. Enable storing backup data to ABS, and ensure other backup types are disabled.
```
gadmin config set "System.Backup.ABS.Enable" "true"
```

  2. Specify the backup ABS Endpoint(or leave it empty if the default endpoint is okay)
```
gadmin config set "System.Backup.ABS.Endpoint" "https://<account-name>.blob.core.windows.net"
```

  3. Specify ABS ContainerName
```
gadmin config set "System.Backup.ABS.ContainerName" "<container-name>"
```

  4. Set ABS backup AccountName
```
gadmin config set "System.Backup.ABS.AccountName" "<account-name>"
```

  5. Set ABS backup AccountKey
```
gadmin config set "System.Backup.ABS.AccountKey" "<account-key>"
```

  6. Apply the new parameter values
```
gadmin config apply -y
```



Now you are ready to [perform a backup](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/backup-cluster).
## [](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/configurations#_backup_to_gcs_google_cloud_storage)Backup to GCS (Google Cloud Storage)
Similar to backing up to ABS, prepare the proper [HMAC keys](https://cloud.google.com/storage/docs/authentication/hmackeys). Then configure it to be your backup storage via the following steps.
  1. Enable storing backup data to GCS, and ensure other backup types are disabled.
```
gadmin config set "System.Backup.GCS.Enable" "true"
```

  2. Specify GCS BucketName
```
gadmin config set "System.Backup.GCS.BucketName" "<bucket-name>"
```

  3. Set GCS backup AccessKey
```
gadmin config set "System.Backup.GCS.AccessKey" "<access-key>"
```

  4. Set GCS backup Secret
```
gadmin config set "System.Backup.GCS.Secret" "<secret>"
```

  5. Apply the new parameter values
```
gadmin config apply -y
```



Now you are ready to [perform a backup](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/backup-cluster).
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


