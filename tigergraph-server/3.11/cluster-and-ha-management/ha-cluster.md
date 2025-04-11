![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/ha-cluster)[Next](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/ha-cluster)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/ha-cluster)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/ha-cluster)
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
  * [Cluster and HA Management](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/)
  * [High Availability (HA)](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/ha-overview)
  * [Cluster Configuration](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/ha-cluster)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/3.11/modules/cluster-and-ha-management/pages/ha-cluster.adoc)
### Contents
  * [System Requirements (Minimal Configurations)](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/ha-cluster#_system_requirements_minimal_configurations)
  * [Configuring HA settings](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/ha-cluster#_configuring_ha_settings)
  * [Configure HA settings during installation](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/ha-cluster#_configure_ha_settings_during_installation)
  * [Resize a running cluster](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/ha-cluster#_resize_a_running_cluster)
  * [Configure bucket number to reduce data skew](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/ha-cluster#_configure_bucket_number_to_reduce_data_skew)
  * [Example](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/ha-cluster#_example)


# High Availability Cluster Configuration
### Contents
  * [System Requirements (Minimal Configurations)](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/ha-cluster#_system_requirements_minimal_configurations)
  * [Configuring HA settings](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/ha-cluster#_configuring_ha_settings)
  * [Configure HA settings during installation](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/ha-cluster#_configure_ha_settings_during_installation)
  * [Resize a running cluster](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/ha-cluster#_resize_a_running_cluster)
  * [Configure bucket number to reduce data skew](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/ha-cluster#_configure_bucket_number_to_reduce_data_skew)
  * [Example](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/ha-cluster#_example)


TigerGraph HA service provides load balancing when all components are operational, as well as automatic failover in the event of a service disruption.
The following terms describe the size and dimension of a HA cluster: 

replication factor
    
Total number of instances of your data. Each instance of data may be partitioned across multiple machines. 

partitioning factor
    
Number of machines across which one copy of the data is distributed. In practice, the partitioning factor of a cluster is decided by dividing the total number of machines in the cluster by the replication factor. 

cluster size
    
Total number of machines in the cluster.
If an HA cluster has both a replication factor of 2 and a partitioning factor of 3, the cluster has a total of six machines. With the six machines, the cluster maintains two instances of the data, each distributed across three machines.
Replication and distribution both increase query throughput and improve system resiliency. There is no upper limit for either partitioning factor or replication factor.
For example, the following cluster has a replication factor of 2 and a cluster size of 10, which produces a partitioning factor of 10/2=5.
![Diagram explaining the mathematical relationship between the partitioning and replication factors and the number of machines in the cluster.](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/_images/cluster_arch.png)
Figure 1. Replication factor vs. partitioning factor
## [](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/ha-cluster#_system_requirements_minimal_configurations)System Requirements (Minimal Configurations)
  * To enable HA, the minimum _replication factor_ is 2.
  * HA also requires a minimum _cluster size_ of 3, so the absolute smallest HA cluster would be 1x3 (a single-server database with 3 instances).
  * The smallest HA cluster using partitioning would be 2x2.
  * If you choose to resize a cluster after installation, ensure every node across the cluster is running the same version of TigerGraph.


## [](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/ha-cluster#_configuring_ha_settings)Configuring HA settings
There are two ways of configuring HA settings for a cluster:
  * Configure HA settings [during installation](https://docs.tigergraph.com/tigergraph-server/3.11/installation/bare-metal-install#_step_2_configure_installation_settings).
  * [Expand](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/expand-a-cluster) or [Shrink a Cluster](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/shrink-a-cluster) after installation.


### [](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/ha-cluster#_configure_ha_settings_during_installation)Configure HA settings during installation
Configuring a HA cluster is part of platform [installation](https://docs.tigergraph.com/tigergraph-server/3.11/installation/bare-metal-install).
During TigerGraph platform installation, specify the replication factor. The default value for replication factor is 1, which means high availability is not set up for the cluster.
You do not explicitly set the partitioning factor. Instead, the TigerGraph system will set the partitioning factor through the following formula:
`partitioning factor = (number of machines / replication factor)`
If the division does not produce an integer, some machines will be left unused. For example, if you install a 7-node cluster with a replication factor of 2, the resulting configuration is 2-way HA for a database with a partitioning factor of 3. One machine is left unused.
### [](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/ha-cluster#_resize_a_running_cluster)Resize a running cluster
In addition to configuring HA settings during installation, you can also resize a running cluster.
Cluster resizing allows you to perform the following:
  * [Cluster Expansion](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/expand-a-cluster)
  * [Cluster Shrinking](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/shrink-a-cluster)
  * [Cluster Repartition](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/repartition-a-cluster)


During cluster resizing, you should expect a brief amount of cluster downtime, during which your cluster will not be able to respond to requests. The specific amount of downtime varies depending on your cluster size, machine memory and CPU, etc. For reference:
Table 1. Expansion downtime - Example 1 Before expansion | After expansion  
---|---  
Replication factor | 2 | 2  
Partitioning factor | 2 | 4  
Data volume (per copy) | 100 GB  
Instance type | GCP EC2 with 8 vCPUs and 32 GB memory  
Downtime | About 4 minutes  
Table 2. Expansion downtime - Example 2 Before expansion | After expansion  
---|---  
Replication factor | 2 | 4  
Partitioning factor | 4 | 4  
Data volume (per copy) | 500 GB  
Instance type | GCP EC2 with 8 vCPUs and 32 GB memory  
Downtime | About 9 minutes  
## [](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/ha-cluster#_configure_bucket_number_to_reduce_data_skew)Configure bucket number to reduce data skew
When you set up an HA cluster, TigerGraph automatically distributes data across different partitions in buckets for every instance of your data. The default number of buckets is fixed and does not change based on the number of partitions. When the number of buckets cannot be evenly divided by the number of partitions, more data is distributed to the partitions with extra buckets, resulting in data skew. However, you can configure the number of buckets before data loading to reduce or avoid data skew.
The number of buckets is controlled by the parameter `GPE.NumberOfHashBucketInBit`. The number of buckets equals 2 to the power of the value of the parameter `GPE.NumberOfHashBucketInBit`.
The default value of `GPE.NumberOfHashBucketInBit` is 5. Therefore, a cluster has 25=32 buckets by default.
This means that data skew happens when you have a partition number that cannot evenly divide 32. Data skew is more significant when the modulus M=NbucketmodNpartition is closer to half of Npartition, where Nbucket is the number of buckets, and Npartition is the number of partitions.
To minimize data skew as well as resource contention issues that can be caused by a high number of buckets, choose a low bucket number that leaves the modulus close to **either 0** or **the number of partitions**.
We **do not suggest** you adjust the bucket number to be lower than the default value. A bucket number that is too low might negatively impact performance.   
---  
### [](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/ha-cluster#_example)Example
For example, if each instance of your data has 9 partitions, the 32 buckets are distributed as follows:
Partition | Buckets  
---|---  
Partition #1 | Bucket #1 | Bucket #10 | Bucket #19 | Bucket #28  
Partition #2 | Bucket #2 | Bucket #11 | Bucket #20 | Bucket #29  
Partition #3 | Bucket #3 | Bucket #12 | Bucket #21 | Bucket #30  
Partition #4 | Bucket #4 | Bucket #13 | Bucket #22 | Bucket #31  
Partition #5 | Bucket #5 | Bucket #14 | Bucket #23 | Bucket #32  
Partition #6 | Bucket #6 | Bucket #15 | Bucket #24  
Partition #7 | Bucket #7 | Bucket #16 | Bucket #25  
Partition #8 | Bucket #8 | Bucket #17 | Bucket #26  
Partition #9 | Bucket #9 | Bucket #18 | Bucket #27  
Partitions #1 to #5 each have 4 buckets, while partitions #6 to #9 only have 3 buckets. This means that each partition between #1 to #5 has 33% more data than a partition between #6 and #9. Therefore, partitions #1 to #5 altogether end up storing 20 / 32 = 62.5% percent of the data, when they should only store 5 / 9 = 55.5%.
To reduce data skew in this scenario, the number of partitions should divide more evenly into the number of buckets. Change `GPE.NumberOfHashBucketInBit` to `6` by running the following command:
```
$ gadmin config set GPE.NumberOfHashBucketInBit 6
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This leaves the cluster with 26=64 buckets. Each partition has 7 buckets, and only partition 1 has one extra bucket.
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


