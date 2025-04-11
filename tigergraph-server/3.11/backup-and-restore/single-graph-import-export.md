![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export)[Next](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export)
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
  * [Import/Export Individual Graphs](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/3.11/modules/backup-and-restore/pages/single-graph-import-export.adoc)
### Contents
  * [Import Prerequisite](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_import_prerequisite)
  * [Export Selected Graphs](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_export_selected_graphs)
  * [Required privilege](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_required_privilege)
  * [Example](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_example)
  * [GraphNameList](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_graphnamelist)
  * [Synopsis](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_synopsis)
  * [Output](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_output)
  * [Insufficient disk space](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_insufficient_disk_space)
  * [Export timeout](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_export_timeout)
  * [Import Selected Graphs](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_import_selected_graphs)
  * [Required privileges](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_required_privileges)
  * [Example](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_example_2)
  * [Synopsis](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_synopsis_2)
  * [Loading Jobs](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_loading_jobs)
  * [Schema Change Jobs](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_schema_change_jobs)
  * [Known Issues and Workarounds](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_known_issues_and_workarounds)
  * [[tg_]ExprFunction.hpp](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_tg_exprfunction_hpp)


# Import/Export Individual Graphs
### Contents
  * [Import Prerequisite](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_import_prerequisite)
  * [Export Selected Graphs](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_export_selected_graphs)
  * [Required privilege](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_required_privilege)
  * [Example](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_example)
  * [GraphNameList](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_graphnamelist)
  * [Synopsis](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_synopsis)
  * [Output](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_output)
  * [Insufficient disk space](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_insufficient_disk_space)
  * [Export timeout](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_export_timeout)
  * [Import Selected Graphs](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_import_selected_graphs)
  * [Required privileges](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_required_privileges)
  * [Example](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_example_2)
  * [Synopsis](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_synopsis_2)
  * [Loading Jobs](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_loading_jobs)
  * [Schema Change Jobs](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_schema_change_jobs)
  * [Known Issues and Workarounds](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_known_issues_and_workarounds)
  * [[tg_]ExprFunction.hpp](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_tg_exprfunction_hpp)


The GSQL `EXPORT GRAPH` and `IMPORT GRAPH` commands perform a logical backup and restore of selected individual graphs specified by the user in a `GraphNameList`. A graph export contains the graph’s data, and optionally some types of metadata. This data can be subsequently imported in order to recreate the same graph data, in the original or in a different TigerGraph platform instance.
To see how to Export/Inport all graphs in a database at once refer to [Database Import/Export All Graphs](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/database-import-export).
Import/export is a complement to [Backup and Restore](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/), but not a substitute.  
---  
## [](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_import_prerequisite)Import Prerequisite
To import an exported graph, ensure that the export files are from a database that was running **the exact same version** of TigerGraph as the database that you are importing into.
## [](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_export_selected_graphs)Export Selected Graphs
The `EXPORT GRAPH` command reads the data and metadata for all indvdually selected graphs in the `GraphNameList` and writes the information to a `.zip` file in the designated folder. It inherits [Export All options](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/database-import-export#_export_all_options) but has the following differences.
**If the user provides no options to the command, it will export:**
  * Data
  * Schema Change Jobs
  * Loading Jobs
  * Vertex/Edge Types
  * Queries
  * Indices
  * UDFs
  * All `tuples` & `typedef` accumulators
  * And other features that belong to the specified graph


**It will NOT export:**
  * Packages
  * ACL privileges (If queries or users/roles are **NOT** exported.)
    * In this case, the queries in charge of ACL privileges will **NOT** be exported.
  * Additionally, by default, it will **NOT** export, unless specified option `--user`:
    * Users
    * Roles
    * Secrets
    * And tokens


### [](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_required_privilege)Required privilege
`EXPORT_GRAPH`
### [](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_example)Example
```
EXPORT GRAPH (ALL|GraphNameList) to "/path/to/export"
GSQL![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_graphnamelist)`GraphNameList`
`GraphNameList` is a list of graph names. The separator is comma `,` . ( e.g., `graphName1`, `graphName1,graphName2` )
### [](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_synopsis)Synopsis
```
EXPORT GRAPH (ALL|GraphNameList) [<export_options>] TO "<directory_name>"
exportOptions ::=
(-S | --SCHEMA | -T | --TEMPLATE | -D | --DATA | -U | --USERS | -P | --PASSWORD pwd)

  -S, --SCHEMA    Only Schema will be exported
  -T, --TEMPLATE   Only Schema, Queries, Loading Jobs, UDFs
  -D, --DATA     Only Data Sources will be exported
  -U, --USERS     Includes Permissions, Secrets, and Tokens
  -P, --PASSWORD   Encrypt with password. User will be prompted
    --SEPARATOR   Specify a column separator
    --EOL      Specify a line separator
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_output)Output
The export output contains the following categories of files:
  * Data files in CSV format, one file for each type of vertex and each type of edge in a single node.
However, for cluster environments, since the data files are spread across the nodes, they will not be included in the zip file.  
---  
  * GSQL DDL command files created by the export command. The import command uses these files to recreate the graph schema(s) and reload the data.
  * Copies of the database’s queries, loading jobs, and user-defined functions.
  * GSQL command files used to recreate the users and their privileges.
  * An encrypted file containing the Access Control List (ACL) privilege catalog. **(If queries or users/roles are NOT exported.)**
When exporting graphs, ACLs are only exported when both queries and users are exported.
    * If you use the `-U` option without using the `-T` option, there is no ACL on the exported graphs because there are no queries.
    * If you use the `-T` option without using the `-U` option, the ACL entries on the exported are reset to the _unspecified_ status.  
---  


The following files are created in the specified directory when exporting and are then zipped into a single file named `ExportedGraph.zip`.
If the file is password-protected, it can only be unzipped using the GSQL command `IMPORT GRAPH`. The security features prevent users from directly unzipping it.  
---  
  * A `DBImportExport_<Graph_Name>.gsql` for each graph called `Graph_Name` in a multigraph database that contains a series of GSQL DDL statements that do the following:
    * Create the exported graph, along with its local vertex, edge, and tuple types,
    * Create the loading jobs from the exported graphs
    * Create data source file objects
    * Create queries
  * A `graph_<Graph_Name>/` folder for each graph in a multigraph database containing data for local vertex/edge types in `<Graph_Name>`. For each vertex or edge type called `<type>`, there is one of the following two data files:
    * `vertex_<type>.csv`
    * `edge_<type>.csv`
  * `global.gsql` - DDL job to create all global vertex and edge types, and data sources.
  * `tuple.gsql` - DDL job to create all User Defined Tuples.
  * Exported data and jobs used to restore the data:
    * `GlobalTypes/` - folder containing data for global vertex/edge types
      * `vertex_name.csv`
      * `edge_name.csv`
    * `run_loading_jobs.gsql` - DDL created by the export command which will be used during import:
      * Temporary global schema change job to add user-defined indexes. This schema job is dropped after it has run.
      * Loading jobs to load data for global and local vertex/edges.
  * Database’s saved queries, loading jobs, and schema change jobs
    * `SchemaChangeJob/` -* folder containing DDL for schema change jobs. See section "Schema Change Jobs" for more information
      * `Global_Schema_Change_Jobs.gsql` contains all global schema change jobs
      * `Graph_Name_Schema_Change_Jobs.gsql` contains schema change jobs for each graph `Graph_Name`
  * User-defined functions
    * `Tokenbank.cpp` - copy of `<tigergraph.root.dir>/app/<VERSION_NUM>/dev/gdk/gsql/src/TokenBank/TokenBank.cpp`
    * `ExprFunctions.hpp` - copy of `<tigergraph.root.dir>/app/<VERSION_NUM>dev/gdk/gsql/src/QueryUdf/ExprFunctions.hpp`
    * `ExprUtil.hpp` - copy of `<tigergraph.root.dir>/app/<VERSION_NUM>/dev/gdk/gsql/src/QueryUdf/ExprUtil.hpp`
  * Users (Only if specified with `--users`):
    * `users.gsql` - DDL to create all exported users, import Secrets and Tokens and grant permissions.
  * ACL privilege catalog **(If queries or users/roles are NOT exported.)** :
    * `ACLDict/1/ACLPrivilegeCatalog.json`. An encrypted file containing the ACL privilege catalog.


### [](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_insufficient_disk_space)Insufficient disk space
If not enough disk space is available for the data to be exported, the system returns an error message indicating not all data has been exported. Some data may have already been written to disk. If an insufficient disk error occurs, the files will not be zipped, due to the possibility of corrupted data which would then corrupt the zip file. The user should clear enough disk space, including deleting the partially exported data, before reattempting the export.
It is possible for all the files to be written to disk and then to run out of disk space during the zip operation. If that is the case, the system will report this error. The unzipped files will be present in the specified export directory.  
---  
### [](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_export_timeout)Export timeout
If the timeout limit is reached during export, the system returns an error message indicating not all data has been exported. Some data may have already been written to disk. If a timeout error occurs, the files will not be zipped. The user should delete the export files, increase the timeout limit and then rerun the export.
The timeout limit is controlled by the session parameter `export_timeout`. The default timeout is ~138 hours. To change the timeout limit, use the command:
```
SET EXPORT_TIMEOUT = <timeout_in_ms>
GSQL![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_import_selected_graphs)Import Selected Graphs
The `IMPORT GRAPH` command unzips the `.zip` file `ExportedGraph.zip` located in the designated folder, and then runs the GSQL command files.
`IMPORT GRAPH` does not execute like `drop all` as with [IMPORT GRAPH ALL](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/database-import-export#_export_graph_all) before importing specified graphs.
Instead they import with these conditons:
  * If there are global level any VERTEX/EDGE, and the importing `tarball` also contains the VERTEX/EDGE type with the same name 2 things could happen:
    1. If the attributes between them are different, the import process will be aborted, and report error.
    2. If the signature (`attributeName`, `attributeType`, `primary_id_as_attribute`, `primaryKey`, `compositeKeys`, `edgeDiscriminator`, or `UDT` types) are exactly same, the VERTEX/EDGE creation process will be skipped, and continue.
  * If a graph name specified in the arguments is not found within the `tarball`, an error will be thrown, and the import statement does nothing.
  * If a graph name specified in the arguments is already existing in current schema, the importing process will be aborted.
  * The UDFs will be merged automatically for `[tg_]ExprFunctions.hpp` if possible, else an error will be reported.
  * For `[tg_]ExprUtils.hpp & TokenBank.hpp`, a warning will be reported if the `MD5sum` are different between importing one and existing one.
  * If `GraphNameList --user` is provided, the existent users will be retained. If users are exported, the users will be imported as well.


Please be extra cautious when importing databases as it can overwrite the current solution, resulting in the deletion of existing schemas, load jobs, queries, and data files. Importing a new solution cannot be undone to restore the previous state, regardless of whether the import succeeds or fails. Therefore, create a complete backup beforehand in case you need to restore the database: [Back up a Database Cluster](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/backup-cluster) For security purposes, TigerGraph has two `gadmin` commands, `GSQL.UDF.Policy.Enable` and `GSQL.UDF.Policy.HeaderAllowlist` to prevent malicious code execution during import. Please refer to the section on [UDF Security](https://docs.tigergraph.com/gsql-ref/3.11/querying/func/query-user-defined-functions#udf-security) to ensure that UDFs comply with the security specifications. This will help you import the solution successfully.  
---  
### [](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_required_privileges)Required privileges
`WRITE_SCHEMA`, `WRITE_QUERY`, `WRITE_LOADINGJOB`, `EXECUTE_LOADINGJOB`, `DROP ALL`, `WRITE_USERS`
### [](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_example_2)Example
```
IMPORT GRAPH (ALL|GraphNameList) from "/path/to/exported/data"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_synopsis_2)Synopsis
```
IMPORT GRAPH (ALL|GraphNameList) [import_options] FROM "<filename>"
importOptions ::= [-P | --PASSWORD ] [ (-KU | -- keep-users]
-P, --PASSWORD   Decrypt with password. User will be prompted.
-KU, --KEEP-USERS  Do not delete user identities before importing
ebnf![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_loading_jobs)Loading Jobs
There are two sets of loading jobs:
  * Those that were in the **catalog** of the database which was exported. These are embedded in the file `DBImportExport_Graph_Name.gsql`
  * Those that are created by `EXPORT GRAPH` and are used to assist with the import process. These are embedded in the file `run_loading_jobs.gsql`.


The catalog loading jobs are not needed to restore the data. They are included for archival purposes.
Some special rules apply to importing loading jobs. Some catalog loading jobs will not be imported.  
---  
  1. If a catalog loading job contains `DEFINE FILENAME F = "/path/to/file/"`, the path will be removed and the imported loading job will only contain `DEFINE FILENAME F`. This is to allow a loading job to still be imported even though the file may no longer exist or the path may be different due to moving to another TigerGraph instance.
  2. If a specific file path is used directly in the LOAD statement, and the file cannot be found, the loading job cannot be created and will be skipped. For example, `LOAD "/path/to/file" to vertex v1` cannot be created if `/path/to/file` does not exist.
  3. Any file path using `$sys.data_root` will be skipped. This is because the value of `$sys.data_root` is not retained from an export. During an import, `$sys.data_root` is set to the root folder of the import location.


### [](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_schema_change_jobs)Schema Change Jobs
There are two sets of schema change jobs:
  1. Those that were in the catalog of the database which was exported. These are stored in the folder `/SchemaChangeJobs`.
  2. Those that were created by `EXPORT GRAPH` and are used to assist with the import process. These are in the `run_loading_jobs.gsql` command file. The jobs are dropped after the import command is finished with them.


The database’s schema change jobs are not executed during the import process. This is because if a schema change job had been run before the export, then the exported schema already reflects the result of the schema change job. The directory `/SchemaChangeJobs` contains these files:
  * `Global_Schema_Change_Jobs.gsql` contains all global schema change jobs
  * `<Graph_Name>_Schema_Change_Jobs.gsql` contains schema change jobs for each graph `<Graph_Name>`.


## [](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_known_issues_and_workarounds)Known Issues and Workarounds
### [](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export#_tg_exprfunction_hpp)`[tg_]ExprFunction.hpp`
`[tg_]ExprFunction.hpp` will be automatically merged while importing single graphs. In some cases below, query compilation may fail if one of the below issues are not solved. There are several known issues:
  1. If the `[tg_]ExprUtil.hpp` or `TokenBank.cpp` are different from the existing ones, users will get a warning message and a workaround will be shown as below:
```
Importing UDF Functions
Failed to merge ExprFunctions automatically.
Warning: The import file /TIGERGRAPH/tmp/import_UDF_automatically_merge/exported/ExprFunctions.hpp is inconsistent with the existing file ExprFunctions.hpp.
Manually fix should be done by following commands:
1. Run commands: GSQL 'GET ExprFunctions TO "/path/to/store/file"'
2. Cherry-pick the changes from /TIGERGRAPH/tmp/import_UDF_automatically_merge/exported/ExprFunctions.hpp to "/path/to/store/file"
3. Run commands: GSQL 'PUT ExprFunctions FROM "/path/to/store/file"'
PUT ExprFunctions skipped.
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  2. Inline variables, including `headers`, `namespace`, `macro` should be handled manually. For example, the below statements will not be auto-merged and moving the below component to an existing UDF as in the steps above, is the workaround.
```
#include <stdio.h>
#define MACRO 1
using namespace std;
int a = 1;
typedef std::string string;
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

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


