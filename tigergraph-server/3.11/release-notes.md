![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/)[Next](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/)
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
  * [TigerGraph DB Release Notes](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/3.11/modules/release-notes/pages/index.adoc)
### Contents
  * [Detailed List of New and Modified Features](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_detailed_list_of_new_and_modified_features)
  * [Backup and Restore Enhancements](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_backup_and_restore_enhancements)
  * [Security Enhancements](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_security_enhancements)
  * [High Availability (HA) Enhancements](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_high_availability_ha_enhancements)
  * [Data Streaming/Connector Enhancements](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_data_streamingconnector_enhancements)
  * [System Management and Monitoring Enhancements](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_system_management_and_monitoring_enhancements)
  * [Kubernetes Operator Enhancements](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_kubernetes_operator_enhancements)
  * [TigerGraph Suite](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_tigergraph_suite)
  * [GraphStudio](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_graphstudio)
  * [TigerGraph Insights](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_tigergraph_insights)
  * [Fixed issues](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_fixed_issues)
  * [Fixed and Improved in 3.11.1](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_fixed_and_improved_in_3_11_1)
  * [Fixed and Improved in 3.11.0](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_fixed_and_improved_in_3_11_0)
  * [Known Issues and Limitations](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_known_issues_and_limitations)
  * [Compatibility Issues](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_compatibility_issues)
  * [Deprecations](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_deprecations)
  * [Release notes for previous versions](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_release_notes_for_previous_versions)


# TigerGraph DB Release Notes
Table of Contents
  * [Detailed List of New and Modified Features](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_detailed_list_of_new_and_modified_features)
    * [Backup and Restore Enhancements](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_backup_and_restore_enhancements)
    * [Security Enhancements](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_security_enhancements)
    * [High Availability (HA) Enhancements](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_high_availability_ha_enhancements)
    * [Data Streaming/Connector Enhancements](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_data_streamingconnector_enhancements)
    * [System Management and Monitoring Enhancements](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_system_management_and_monitoring_enhancements)
    * [Kubernetes Operator Enhancements](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_kubernetes_operator_enhancements)
  * [TigerGraph Suite](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_tigergraph_suite)
    * [GraphStudio](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_graphstudio)
    * [TigerGraph Insights](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_tigergraph_insights)
  * [Fixed issues](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_fixed_issues)
    * [Fixed and Improved in 3.11.1](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_fixed_and_improved_in_3_11_1)
    * [Fixed and Improved in 3.11.0](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_fixed_and_improved_in_3_11_0)
  * [Known Issues and Limitations](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_known_issues_and_limitations)
    * [Compatibility Issues](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_compatibility_issues)
    * [Deprecations](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_deprecations)
  * [Release notes for previous versions](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_release_notes_for_previous_versions)


TigerGraph Server 3.11.1 was released on December 18, 2024.
TigerGraph Server 3.11.0 preview version was released on October 25, 2024.
Features in the preview stage should not be used for production purposes. General Availability (GA) versions of the feature will be available in a later release.
## [](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_detailed_list_of_new_and_modified_features)Detailed List of New and Modified Features
### [](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_backup_and_restore_enhancements)Backup and Restore Enhancements
  * **[Point in Time Restore](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/point-in-time-restore)** : Users can roll back the database to a moment they select, not only the time of an available backup snapshots.
  * **[Role ARN for Backup to AWS S3 buckets](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/configurations#_configure_backup_to_aws_s3_endpoint)** : Users can use AWS Role ARNs (Amazon Resource Names) for convenient and secure management of backups.
  * [3.11.1] **[Backup to Azure and Google clouds](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/configurations)** : Backup operations can be configured to store files on Azure and Google cloud storage, adding to existing support for AWS backup storage.
  * The **[--custom-tag flag](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/backup-cluster#_data_backup)** gives users more control over the naming of backup files.
  * See also [High Availability (HA) Enhancements](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_high_availability_ha_enhancements)


### [](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_security_enhancements)Security Enhancements
  * **[Password Complexity and Rotation Rules](https://docs.tigergraph.com/tigergraph-server/3.11/security/password-policy)** : Administrators can specify rules for the complexity of passwords and how long or how many times a password may be used, in order to improve security and help organizations to satisfy compliance requirements.
  * **[Expanded Audit Log Coverage](https://docs.tigergraph.com/tigergraph-server/3.11/troubleshooting/audit-log)** : Audit logs now include `gadmin` activity, for more complete audit coverage.


### [](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_high_availability_ha_enhancements)High Availability (HA) Enhancements
  * **[Data Loading HA (Beta)](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/data-loading-v2)** : If the database is replicated, this data loading mode offers faster loading, reduced disk usage, and HA with automatic failover. Available for TigerGraph’s [data streaming connectors](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/manage-data-source) for cloud storage, Kafka, data warehouses, and Spark.
  * **[Change Data Capture (CDC) HA](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/change-data-capture/cdc-overview#_cdc_ha)** : CDC continues to function as long as at least one replica per partition is online. Previously, Replica 1 needed to remain operational.
  * **Backup HA** : Backups remain available even if a node fails. Previously, backups were unavailable if a node failed.


### [](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_data_streamingconnector_enhancements)Data Streaming/Connector Enhancements
  * **[Malformed Loading Data Inspector](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/managing-loading-job#_show_loading_error)** : `SHOW LOADING ERROR` presents a sample of malformed data lines and their error types to an authorized user, enabling them to quickly locate and diagnose loading problems.
  * **[Data Export to AWS S3](https://docs.tigergraph.com/gsql-ref/3.11/querying/data-types#_file_object)** : Export query results in CSV format directly to AWS S3 buckets for efficient data sharing and analysis
  * **[Stream Data into Spark](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/read-to-spark-dataframe)** : Using the Spark data source reader API, users can run TigerGraph queries and stream the output to Spark as DataFrames. Streaming the output lifts the 2GB query response size limitation for non-streaming output.
  * **Notification for Stuck Loader** : If loading is stuck or acting abnormally, the loader sends an alert message to the console, including a diagnosis, enabling users to take timely action.
  * See also [High Availability (HA) Enhancements](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_high_availability_ha_enhancements)


### [](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_system_management_and_monitoring_enhancements)System Management and Monitoring Enhancements
  * New options and optimized behavior in `GADMIN CONFIG APPLY` to [restart only those services](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/management-commands#_gadmin_config_apply) that have been affected by configuration changes.
  * **[Enhanced Metrics Reports](https://docs.tigergraph.com/tigergraph-server/3.11/API/built-in-endpoints#_monitor_system_metrics_openmetrics_format)** Total and available capacity for CPU and memory are now reported by the `/informant/metrics` endpoint.
  * Added a `graph` field (name of the graph) to [CDC messages](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/change-data-capture/cdc-message-example).
  * Revised the format of the `content` field in [CDC messages](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/change-data-capture/cdc-message-example) to be consistent with the [POST request data format](https://docs.tigergraph.com/tigergraph-server/3.11/API/#_formatting_data_in_json).


### [](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_kubernetes_operator_enhancements)Kubernetes Operator Enhancements
  * TigerGraph Operator 1.2.0 introduces several significant new features, including the ability to create services for sidecar containers, support for cluster storage resizing, new lifecycle hooks for TigerGraph CR, and enhanced Multi-AZ cluster resiliency.
TigerGraph K8s Operator 1.2.0 details
    * **[Region Awareness with Pod Topology Spread Constraints](https://github.com/tigergraph/ecosys/blob/k8s-operator/1.2.0/k8s/docs/03-deploy/region-awareness-with-pod-topology-spread-constraints.md)** : Improve workload distribution and availability by enabling region awareness.
    * **[Automatic Expansion of PVCs for TigerGraph CR](https://github.com/tigergraph/ecosys/blob/k8s-operator/1.2.0/k8s/docs/04-manage/expand-storage.md)** : Simplify storage management with automated Persistent Volume Claim (PVC) resizing.
    * **[New Lifecycle Hooks for TigerGraph CR](https://github.com/tigergraph/ecosys/blob/k8s-operator/1.2.0/k8s/docs/03-deploy/lifecycle-of-tigergraph.md)** : Utilize preDeleteAction and prePauseAction lifecycle hooks for better control and automation during cluster operations.
    * **[Service Creation for Sidecar Containers](https://github.com/tigergraph/ecosys/blob/k8s-operator/1.2.0/k8s/docs/03-deploy/configure-services-of-sidecar-containers.md)** : Easily create services for sidecar containers with TigerGraph CR.
    * **[Enhanced Debugging Mode](https://github.com/tigergraph/ecosys/blob/k8s-operator/1.2.0/k8s/docs/04-manage/debug-mode.md)** : Debug more effectively with the newly introduced debugging mode in the operator.
    * **[Customization of MaxConcurrentReconciles for the operator](https://github.com/tigergraph/ecosys/blob/k8s-operator/1.2.0/k8s/docs/03-deploy/tigergraph-on-eks.md#install-tigergraph-operator)** : Fine tune TigerGraph operator’s performance by customizing the maximum number of concurrent reconciles.


## [](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_tigergraph_suite)TigerGraph Suite
### [](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_graphstudio)GraphStudio
  * **Highlight Connected Edges When Hovering Over a Vertex** : to show users the relationships and structure at a glance. Also available in Insights.
  * **Collapsible Sidebar** : to let users use their screen space more effiently.


  * **Mandatory Password Change upon Expiration** : A password must be changed when it expires or reaches a time/usage limit, enhancing security protocols. Not available on TigerGraph Cloud.
  * **Customizable Naming of Reverse Edges** : enables data modelers to apply more intuitive and domain-specific names.


### [](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_tigergraph_insights)TigerGraph Insights
  * **Downloadable Query Output** : as CSV or JSON
  * **"Tree" View Respects Direction of Directed Edges** : to depict hierarchical structures and dependencies more meaningfully
  * **Support for Variables in Markdown Widget** : for more context-aware and interactive dashboard displays


## [](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_fixed_issues)Fixed issues
### [](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_fixed_and_improved_in_3_11_1)Fixed and Improved in 3.11.1
#### [](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_functionality)Functionality
  * Fixed issue where the loading job would hang when loading a blank file with only a header line (TP-6635).
  * Fixed issue where the job status was not correctly reported when the loading job failed to start (TP-6131).
  * Fixed issue with query installation failure for single-node queries which initialize vertex set variables in conditional branches (GLE-8846).
  * Fixed issue with error codes in the log when a CDC message failed to deliver to external Kafka (CORE-4326).
  * Fixed critical disk issue caused by the rebuilder getting stuck in a partitioned cluster after dropping vertex or edge attributes (CORE-4357).
  * Fixed issue where local accumulators defined across multiple lines in a query were misinterpreted as a file in the GSQL client (GLE-8260).
  * Fixed issue with loading job progress requiring a read graph lock, which could block schema change operations (GLE-8825).


#### [](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_improvements)Improvements
  * Improved the performance of GSQL queries containing delete statements intended for deleting all vertices of a given type (GLE-8931).
  * Added validation to prevent EXE from reading files with negative length and enforced gRPC message maximum size when the length was too large (TP-6764).
  * Added the 'graph' field to CDC messages generated by the TigerGraph CDC service (CORE-4146).


### [](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_fixed_and_improved_in_3_11_0)Fixed and Improved in 3.11.0
#### [](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_functionality_2)Functionality
  * Fixed issue where local accumulators defined across multiple lines in a query were misinterpreted in the GSQL client (GLE-8259).
  * Fixed issue in the post-upgrade check that causes the upgrade to abort due to insufficient permissions to the /tmp directory (GLE-8005).
  * Fixed issue where loading jobs with a `WHERE` condition would hang after upgrading from an older version (GLE-7953).
  * Fixed situation where a query containing a `BREAK` or `CONTINUE` statements could produce incorrect results (GLE-7874).
  * Fixed regression problem with installing queries which create lists containing mixed types of numeric data (GLE-7928).
  * Fixed int64 value underflow error by explicitly type casting uint64 (CORE-4108).
  * Fixed an issue so IMPORT ALL will no longer fail due to the schema size being very large (GLE-6505).
  * Restored the ability to run the TigerGraph `gcollect` command on Kubernetes (TP-6351).


#### [](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_crashes_and_deadlocks)Crashes and Deadlocks
  * Resolved an intermittent deadlock in Informant that caused `gadmin status` to fail (TP-5930).
  * Fixed issue with database import hanging caused by the status of a loading job not being received by Kafka streaming library (TP-5772).


#### [](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_improvements_2)Improvements
  * Added an error report if a schema check is requested but cannot be performed because the GPE is in warmup status (GLE-7898).
  * Allowed installation to continue on Oracle and RedHat Linux, 8 even if the TigerGraph user is not listed in AllowedUsers in /etc/ssh/sshd_config (TP-5105).


## [](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_known_issues_and_limitations)Known Issues and Limitations
Description | Found In | Workaround | Fixed In  
---|---|---|---  
Running either `EXPORT GRAPH ALL` or `IMPORT GRAPH ALL` resets the TigerGraph superuser’s password back to its default value. | 3.9.1 | After running either command, change the superuser’s password to make it secure again. | TBD  
[EXPORT GRAPH ALL](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/database-import-export) does not correctly handle loading jobs containing `DELETE` statements nor graph elements with composite keys. `EXPORT GRAPH ALL` may fail if the data includes a `UDT` with a fixed string size. | 3.2 | TBD  
If importing a role, policy, or function that has a different signature or content from the existing one, the one being imported will be skipped and not aborted. For example:
  * If the original function is: `create function lib1.func2(int param1, float param2, string param3) returns (bool) {}`.
  * And the user imports the new function: `create function lib1.func2(int param1) returns (bool) {}`. This second one will be skipped.

| 3.10.0 | Users need to re-create (delete and create) the imported role, policy, or function manually, and make sure that the importing one meets the requirements set by the existing one. | TBD  
[Row Policy (Preview Feature)](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/rbac-row-policy/row-policy-overview) does not yet filter or check vertex attribute data in upsert operations. Such as,
  * A query with insert statements.
  * A file or Kafka loading job.
  * A DDL loading request.
  * Or a standard upsert request.

| 3.10.0 | Users should restrict the access of creating/running queries and loading jobs for roles related to row policy. | TBD  
In file INPUT and OUTPUT policy, if there exists 2 path (`path1` and `path2`) in the configured policy list and `path1` is parent path of `path2`, then `path1` may not be effective. | 3.2 and 3.10.0 | Users should avoid using paths if they are nested. For example, avoid this scenario, path2 = `"/tmp/more"` and path1= `"/tmp"`. | 3.10.1  
It has been observed that an issue happens when RESTPP will send a request to all gpes, and if one is down, the request sent to it will `timeout`. Including the `consistency_check` request will also mark as `timeout`. | 3.10.0 | 
  1. Run `/rebuildnow` to rebuild all the segments. |  Running `/rebuildnow` when one gpe is down will result in the request timeout. This does not mean the request failed, instead only the currently running GPE will do the rebuild, and any rebuild requests sent to the down GPEs will result in a timeout.  
---  
  2. Run `/data_consistency_check?realtime=false` to check the consistency.


TBD  
While running `EXPORT GRAPH` if the disk space is not enough, or the data has not been detected, the export data will get stuck loading. | 3.10.0 | Restart all services in Admin Portal or the backend. | TBD  
`[tg_]ExprFunction.hpp` will be automatically merged while importing single graphs. In some cases, query compilation may fail. | 3.10.0 | See [Known Issues and Workarounds](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_known_issues_and_workarounds) | TBD  
Upgrading from a previous version of TigerGraph has known issues. | 3.10.0 | See section [Known Issues and Workarounds](https://docs.tigergraph.com/tigergraph-server/3.11/installation/upgrade#_known_issues_and_workarounds) for more details. | TBD  
Input Policy feature has known limitations. | 3.10.0 | See section [Input Policy Limitations](https://docs.tigergraph.com/tigergraph-server/3.11/security/gsql-file-input-policy#_limitations) for more details. | TBD  
Change Data Capture (CDC) feature has known limitations. | 3.10.0 | See section [CDC Limitations](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/change-data-capture/cdc-overview#_cdc_limitations) for more details. | TBD  
If the `FROM` clause pattern is a multi-hop and the `ACCUM` clause reads both primitive and container type attributes or accumulators of a vertex, the internal query rewriting logic may generate an invalid rewritten output. | 3.9.3 | This results in the error message: `It is not allowed to mix primitive types and accumulator types in GroupByAccum`. | TBD  
Users may see a high CPU usage caused by Kafka prefetching when there is no query or posting request. | 3.9.3 | TBD | TBD  
GSQL query compiler may report a false error for a valid query using a vertex set variable (e.g. `Ent` in `reverse_traversal_syntax_err`) to specify the midpoint or target vertex of a path in a FROM clause pattern. | TBD | TBD | TBD  
If a loading job is expected to load from a large batch of files or Kafka queues (e.g. more than 500), the job’s status may not be updated for an extended period of time. | 3.9.3 | In this case, users should check the loader log file as an additional reference for loading status. | TBD  
When a GPE/GSE is turned off right after initiating a loading job, the loading job is terminated internally. However, users may still observe the loading job as running on their end. | 3.9.3 | Please see [Troubleshooting Loading Job Delays](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/running-a-loading-job) for additional details. | TBD  
For v3.9.1 and v3.9.2 when inserting a new edge in `GPR` and `INTERPRET` mode, the GPE will print out a warning message because a discriminator string is not set for new-inserted edges. Creating an inconsistent problem in delta message for GPR and `INTERPRET` mode. | 3.9.2 | Please see [Troubleshooting Loading Job Delays](https://docs.tigergraph.com/gsql-ref/3.11/ddl-and-loading/running-a-loading-job) for additional details. | 3.9.3  
GSQL `EXPORT GRAPH` may fail and cause a GPE to crash when UDT type has a fixed STRING size. | TBD | TBD | TBD  
After a global loading job is running for a while a fail can be encountered when getting the loading status due to `KAFKASTRM-LL` not being online, when actually the status is online. Then the global loading process will exit and fail the local job after timeout while waiting the global loading job to finish. | TBD | TBD | TBD  
When the memory usage approaches 100%, the system may stall because the process to elect a new GSE leader did not complete correctly. | TBD | This lockup can be cleared by restarting the GSE. | TBD  
If the CPU and memory utilization remain high for an extended period during a schema change on a cluster, a GSE follower could crash, if it is requested to insert data belonging to the new schema before it has finished handling the schema update. | TBD | TBD | TBD  
When available memory becomes very low in a cluster and there are a large number of vertex deletions to process, some remote servers might have difficulty receiving the metadata needed to be aware of all the deletions across the full cluster. The mismatched metadata will cause the GPE to go down. | TBD | TBD | TBD  
Subqueries with SET<VERTEX> parameters cannot be run in Distributed or Interpreted mode. | TBD | ([Limited Distributed model support](https://docs.tigergraph.com/gsql-ref/3.11/querying/operators-and-expressions#_subquery_limitations) is added in 3.9.2.) | TBD  
Upgrading a cluster with 10 or more nodes to v3.9.0 requires a patch. | 3.9 | Please contact TigerGraph Support if you have a cluster this large. Clusters with nine or fewer nodes do not require the patch. | 3.9.1  
Downsizing a cluster to have fewer nodes requires a patch. | 3.9.0 | Please contact TigerGraph Support. | TBD  
During peak system load, loading jobs may sometimes display an inaccurate loading status. | 3.9.0 | This issue can be remediated by continuing to run `SHOW LOADING STATUS` periodically to display the up-to-date status. | TBD  
When managing many loading jobs, pausing a data loading job may result in longer-than-usual response time. | TBD | TBD | TBD  
Schema change jobs may fail if the server is experiencing a heavy workload. | TBD | To remedy this, avoid applying schema changes during peak load times. | TBD  
User-defined Types (UDT) do not work if exceeding string size limit. | TBD | Avoid using UDT for variable length strings that cannot be limited by size. | TBD  
Unable to handle the tab character `\t` properly in AVRO or Parquet file loading. It will be loaded as `\\t`. | TBD | TBD | TBD  
If `System.Backup.Local.Enable` is set to `true`, this also enables a daily full backup at 12:00am UTC. | 3.9.0 | TBD | 3.9.1  
The data streaming connector does not handle NULL values; the connector may operate properly if a NULL value is submitted. | TBD | Users should replace NULL with an alternate value, such as empty string "" for STRING data, 0 for INT data, etc. (NULL is not a valid value for the TigerGraph graph data store.) | TBD  
Automatic message removal is an Alpha feature of the Kafka connector. It has several [known issues](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-cloud#_known_issues_with_loading). | TBD | TBD | TBD  
The `DATETIME` data type is not supported by the `PRINT … TO CSV` statement. | 3.9.0 | TBD | 3.9.1  
The LDAP keyword `memberOf` for declaring group hierarchy is case-sensitive. | 3.9 | Check the case of the keywords for `memberOf`. This has been fixed in versions 3.10.1 and above. | 3.10.1  
### [](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_compatibility_issues)Compatibility Issues
Description | Version Introduced  
---|---  
The 'graph' field is now included in [CDC messages](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/change-data-capture/cdc-message-example#_message_examples) generated by the TigerGraph CDC service. | v3.11.0  
In [CDC messages](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/change-data-capture/cdc-message-example#_message_examples), the format of **map values** has changed. | v3.11.0  
Users could encounter file input/output policy violations when upgrading a TigerGraph version. See [Input policy backward compatibility.](https://docs.tigergraph.com/tigergraph-server/3.11/security/gsql-file-input-policy#_backward_compatibility) | v3.10.0  
When a PRINT argument is an expression, the output uses the expression as the key (label) for that output value. To better support Antlr processing, PRINT now removes any spaces from that key. For example, `count(DISTINCT @@ids)` becomes `count(DISTINCT@@ids)`. | v3.9.3+  
Betweenness Centrality algorithm: `reverse_edge_type (STRING)` parameter changed to `reverse_edge_type_set (SET<STRING>)`, to be consistent with `edge_type_set` and similar algorithms. | v3.9.2+  
For vertices with string-type primary IDs, vertices whose ID is an empty string will now be rejected. | v3.9.2+  
The default mode for the Kafka Connector changed from EOF="false" to EOF="true". | v3.9.2+  
The default retention time for two monitoring services `Informant.RetentionPeriodDays` and `TS3.RetentionPeriodDays` has reduced from 30 to 7 days. | v3.9.2+  
The filter for `/informant/metrics/get/cpu-memory` now accepts a list of ServiceDescriptors instead of a single ServiceDescriptor. | v3.9.2+  
Some user-defined functions (UDFs) may no longer be accepted due to [increased security screening](https://docs.tigergraph.com/tigergraph-server/3.11/security/#_udf_file_scanning).
  * UDFs may no longer be called `to_string()`. This is now a built-in GSQL function.
  * UDF names may no longer use the `tg_` prefix. Any user-defined function that began with `tg_` must be renamed or removed in `ExprFunctions.hpp`.

| v3.9+  
### [](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_deprecations)Deprecations
Description | Deprecated | Removed  
---|---|---  
The use of plaintext tokens in [authentication](https://docs.tigergraph.com/tigergraph-server/3.11/API/authentication) is deprecated. Use [OIDC JWT Authentication](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/jwt-token) instead. | 3.10.0 | 4.1  
The command `gbar` is removed and is no longer available. However, if you are using a version of TigerGraph before 3.10.0 you can still use `gbar` to [create a backup with gbar](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/gbar-legacy) of the primary cluster. See also [Backup and Restore with gbar](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/gbar-legacy) on how to create a backup. | 3.7 | 3.10.0  
[Vertex-level Access Control (VLAC)](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/vlac) and [VLAC Methods](https://docs.tigergraph.com/gsql-ref/3.11/querying/func/vertex-methods#_vlac_vertex_alias_methods_deprecated) are now deprecated and will no longer be supported. | 3.10.0 | 4.0  
[Spark Connection via JDBC Driver](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/spark-connection-via-jdbc-driver) is now deprecated and will no longer be supported. | 3.10.0 | TBD  
`Build Graph Patterns` is deprecated and will not be updated or supported and instead we are focusing on [Insights](https://docs.tigergraph.com/insights/3.11/widgets/) as the tool of choice for building visual queries. | v3.9.3 | TBD  
Kubernetes classic mode (non-operator) is deprecated. | v3.9 | TBD  
The `WRITE_DATA` RBAC privilege is deprecated. | v3.7 | TBD  
## [](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/#_release_notes_for_previous_versions)Release notes for previous versions
  * [Release notes - TigerGraph 3.10](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/)
  * [Release notes - TigerGraph 3.9](https://docs.tigergraph.com/tigergraph-server/3.9/release-notes/)
  * [Release notes - TigerGraph 3.6](https://docs.tigergraph.com/tigergraph-server/3.6/release-notes/)


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


