![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr)[Next](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr)
[Developer Site](https://dev.tigergraph.com/) [Community Forum](https://community.tigergraph.com/) [Knowledge Base](https://tigergraph.freshdesk.com/support/solutions)
[Download](https://dl.tigergraph.com)
[ TG Savanna](https://savanna.tgcloud.io)
### [TigerGraph DB](https://docs.tigergraph.com/tigergraph-server/3.10/intro/)
  *     * [TigerGraph DB Release Notes](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/)
  *     * [Overview](https://docs.tigergraph.com/tigergraph-server/3.10/intro/)
    * [Get Started](https://docs.tigergraph.com/tigergraph-server/3.10/getting-started/)
      * Installation
        * [On Docker](https://docs.tigergraph.com/tigergraph-server/3.10/getting-started/docker)
        * [On Kubernetes](https://docs.tigergraph.com/tigergraph-server/3.10/getting-started/kubernetes)
        * [On Cloud Marketplace](https://docs.tigergraph.com/tigergraph-server/3.10/getting-started/cloud-images/)
          * [AWS](https://docs.tigergraph.com/tigergraph-server/3.10/getting-started/cloud-images/aws)
          * [Azure](https://docs.tigergraph.com/tigergraph-server/3.10/getting-started/cloud-images/azure)
          * [GCP](https://docs.tigergraph.com/tigergraph-server/3.10/getting-started/cloud-images/gcp)
        * [On Linux](https://docs.tigergraph.com/tigergraph-server/3.10/getting-started/linux)
          * [System Requirements](https://docs.tigergraph.com/tigergraph-server/3.10/installation/hw-and-sw-requirements)
          * [Linux On Bare Metal](https://docs.tigergraph.com/tigergraph-server/3.10/installation/bare-metal-install)
          * [Post Install Checks](https://docs.tigergraph.com/tigergraph-server/3.10/installation/post-install-check)
        * [Advanced License Issues](https://docs.tigergraph.com/tigergraph-server/3.10/installation/license)
        * [Changing Ports](https://docs.tigergraph.com/tigergraph-server/3.10/installation/change-port)
        * [Change IP or Hostname](https://docs.tigergraph.com/tigergraph-server/3.10/installation/change-ip-or-hostname)
        * [Upgrade](https://docs.tigergraph.com/tigergraph-server/3.10/installation/upgrade)
        * [Uninstallation](https://docs.tigergraph.com/tigergraph-server/3.10/installation/uninstallation)
      * [The GSQL Shell](https://docs.tigergraph.com/tigergraph-server/3.10/gsql-shell/)
        * [GSQL Shell Sessions](https://docs.tigergraph.com/tigergraph-server/3.10/gsql-shell/gsql-sessions)
        * [Using a Remote GSQL Client](https://docs.tigergraph.com/tigergraph-server/3.10/gsql-shell/using-a-remote-gsql-client)
        * [GSQL Shell (Web)](https://docs.tigergraph.com/tigergraph-server/3.10/gsql-shell/web)
    * [Create Database](https://docs.tigergraph.com/tigergraph-server/3.10/getting-started/database-definition)
      * [MultiGraph Overview](https://docs.tigergraph.com/tigergraph-server/3.10/intro/multigraph-overview)
  *     * [Load Data](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/)
      * [Overview](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/data-loading-overview)
      * [Externalize Kafka Configs](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/externalizing-kafka-configs)
      * [Load from Local Files](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-local-files)
      * [Load from Cloud Storage](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-cloud)
      * [Load from Data Warehouse](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-warehouse)
      * [Load from External Kafka](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka)
        * [Avro Data Validation through KafkaConnect](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/avro-validation-with-kafka)
        * [Kafka SSL Security Guide](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/kafka-ssl-security-guide)
      * [Load from Spark Dataframe](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe)
        * [Spark Connection Via JDBC Driver (Deprecated)](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/spark-connection-via-jdbc-driver)
      * [Manage Data Sources](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/manage-data-source)
      * [Stream from External Kafka (Deprecated)](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/data-streaming-connector/kafka)
  *     * Advanced Topics
      * [System Management](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/management-with-gadmin)
        * [Memory management](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/memory-management)
        * [Manage TigerGraph services](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/manage-services)
        * [Workload Management](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/workload-management)
        * [Metrics Reporting](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/system-metrics)
        * [Command Glossary](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/management-commands)
        * [Change Data Capture (CDC) Overview](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-overview)
          * [CDC Setup](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-setup)
          * [CDC Message Examples](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-message-example)
          * [CDC State Monitoring](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-state-monitoring)
      * [Access Management](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/)
        * Authentication
          * [Enabling User Authentication](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/enabling-user-authentication)
          * [User Credentials](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/user-credentials)
          * [Single Sign-On](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/sso)
          * [Lightweight Directory Access Protocol (LDAP)](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/ldap)
          * [OIDC JWT Authentication](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/jwt-token)
        * Authorization
          * [User Management](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/user-management)
          * [Role Management](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management)
          * [Access Control Model](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/access-control-model)
          * [Access Control Lists (ACLs)](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/acl-management)
          * [Row Policy Overview (Preview Feature)](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/rbac-row-policy/row-policy-overview)
            * [Key Concepts](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/rbac-row-policy/rbac-row-policy)
            * [Set Up Row Policy](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/rbac-row-policy/setup-row-policy)
          * [Vertex-Level Access Control (Deprecated)](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/vlac)
      * [Backup and Restore](https://docs.tigergraph.com/tigergraph-server/3.10/backup-and-restore/)
        * [Database Import/Export All Graphs](https://docs.tigergraph.com/tigergraph-server/3.10/backup-and-restore/database-import-export)
        * [Import/Export Individual Graphs](https://docs.tigergraph.com/tigergraph-server/3.10/backup-and-restore/single-graph-import-export)
        * [Backup and Restore Configurations](https://docs.tigergraph.com/tigergraph-server/3.10/backup-and-restore/configurations)
        * [Back up a Database Cluster](https://docs.tigergraph.com/tigergraph-server/3.10/backup-and-restore/backup-cluster)
        * [Restore a Database Backup from the Same Cluster](https://docs.tigergraph.com/tigergraph-server/3.10/backup-and-restore/restore-backup-same)
        * [Restore a Database Backup from Another Cluster](https://docs.tigergraph.com/tigergraph-server/3.10/backup-and-restore/cross-cluster-backup)
        * [Differential Backup](https://docs.tigergraph.com/tigergraph-server/3.10/backup-and-restore/differential-backups)
        * [Online Backup](https://docs.tigergraph.com/tigergraph-server/3.10/backup-and-restore/online-backup)
        * [Legacy Backup and Restore](https://docs.tigergraph.com/tigergraph-server/3.10/backup-and-restore/gbar-legacy)
      * [Cluster and HA Management](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/)
        * Cluster Resizing
          * [Cluster Expansion](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/expand-a-cluster)
          * [Cluster Shrinking](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/shrink-a-cluster)
          * [Cluster Repartition](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/repartition-a-cluster)
          * [Cluster Replace](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/how_to-replace-a-node-in-a-cluster)
        * [Cross-Region Replication (CRR)](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/crr-index)
          * [Set up CRR](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr)
          * [Fail over to the DR cluster](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/fail-over)
          * [Troubleshooting CRR](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/troubleshooting)
          * [CRR FAQ](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/crr-faq)
        * [High Availability (HA)](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/ha-overview)
          * [Cluster Configuration](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/ha-cluster)
          * [GSQL Server Support](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/ha-for-gsql-server)
          * [Application Server Support](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/ha-for-application-server)
          * [Cluster Commands](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands)
          * [Removal of Failed Nodes](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/remove-failed-node)
      * [Architecture](https://docs.tigergraph.com/tigergraph-server/3.10/intro/internal-architecture)
        * [MultiGraph Overview](https://docs.tigergraph.com/tigergraph-server/3.10/intro/multigraph-overview)
        * [Transaction Processing and ACID Support](https://docs.tigergraph.com/tigergraph-server/3.10/intro/transaction-and-acid)
        * [Continuous Availability Overview](https://docs.tigergraph.com/tigergraph-server/3.10/intro/continuous-availability-overview)
      * [Kubernetes](https://docs.tigergraph.com/tigergraph-server/3.10/kubernetes/)
        * [Kubernetes Operator](https://docs.tigergraph.com/tigergraph-server/3.10/kubernetes/k8s-operator/)
  *     * [Security](https://docs.tigergraph.com/tigergraph-server/3.10/security/)
      * [Auditing Privileged User Actions](https://docs.tigergraph.com/tigergraph-server/3.10/security/audit-privileged-actions)
      * [Encrypting Connections](https://docs.tigergraph.com/tigergraph-server/3.10/security/encrypting-connections)
      * [Encrypting Data At Rest](https://docs.tigergraph.com/tigergraph-server/3.10/security/encrypting-data-at-rest)
      * [File Input Policy](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy)
      * [File Output Policy](https://docs.tigergraph.com/tigergraph-server/3.10/security/file-output-policy)
      * [Configuring Login Protection](https://docs.tigergraph.com/tigergraph-server/3.10/security/login-protection)
  *     * [REST API Reference](https://docs.tigergraph.com/tigergraph-server/3.10/API/)
      * [Authentication](https://docs.tigergraph.com/tigergraph-server/3.10/API/authentication)
      * [Built-in Endpoints](https://docs.tigergraph.com/tigergraph-server/3.10/API/built-in-endpoints)
      * [Built-in Endpoints JSON Catalog](https://docs.tigergraph.com/tigergraph-server/3.10/API/json-catalog)
      * [Upsert data to graph](https://docs.tigergraph.com/tigergraph-server/3.10/API/upsert-rest)
  *     * Additional Resources
      * [Best Practices](https://docs.tigergraph.com/tigergraph-server/3.10/additional-resources/best-practice-guides/best-practices-overview)
        * [Scaling Guide](https://docs.tigergraph.com/tigergraph-server/3.10/additional-resources/best-practice-guides/best-prac-scaling-clusters)
      * Troubleshooting and FAQs
        * [Knowledge base and FAQs](https://kb.tigergraph.com/)
        * [Troubleshooting Guide](https://docs.tigergraph.com/tigergraph-server/3.10/troubleshooting/troubleshooting-guide)
        * [System Administration FAQs](https://docs.tigergraph.com/tigergraph-server/3.10/troubleshooting/system-administration-faqs)
        * [Log Files](https://docs.tigergraph.com/tigergraph-server/3.10/troubleshooting/log-files)
          * [Audit Logs](https://docs.tigergraph.com/tigergraph-server/3.10/troubleshooting/audit-log)
          * [Gathering Log Information with gcollect](https://docs.tigergraph.com/tigergraph-server/3.10/troubleshooting/gcollect)
          * [Set up Log Viewing with Elasticsearch, Kibana and Filebeat](https://docs.tigergraph.com/tigergraph-server/3.10/troubleshooting/elk-filebeat)
      * References
        * [Configuration Parameters](https://docs.tigergraph.com/tigergraph-server/3.10/reference/configuration-parameters)
        * [Return codes](https://docs.tigergraph.com/tigergraph-server/3.10/reference/return-codes)
        * [Object-Based Privilege Tables](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/rbac-row-policy/row-policy-privileges-table)
        * [List of Legacy Privilege Syntax](https://docs.tigergraph.com/tigergraph-server/3.10/reference/list-of-privileges)
        * [List of Ports](https://docs.tigergraph.com/tigergraph-server/3.10/reference/ports)
        * [Glossary](https://docs.tigergraph.com/tigergraph-server/3.10/reference/glossary)
        * [Patents and Third Party Software](https://docs.tigergraph.com/tigergraph-server/3.10/reference/patents-and-third-party-software)
        * [Legacy Version Documentation](https://docs.tigergraph.com/tigergraph-server/3.10/additional-resources/legacy-tg-versions)
        * [Comparing TigerGraph Editions](https://docs.tigergraph.com/tigergraph-server/3.10/intro/comparison-of-editions)
        * [Release and Patch Process](https://docs.tigergraph.com/tigergraph-server/3.10/intro/release-process)
        * [RBAC Row Policy EBNF](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/rbac-row-policy/row-policy-ebnf)


TigerGraph DB 3.10
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
  * [TigerGraph DB 3.10](https://docs.tigergraph.com/tigergraph-server/3.10/intro/)
  * Advanced Topics
  * [Cluster and HA Management](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/)
  * [Cross-Region Replication (CRR)](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/crr-index)
  * [Set up CRR](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/3.10/modules/cluster-and-ha-management/pages/set-up-crr.adoc)
### Contents
  * [1. Before you begin](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr#_before_you_begin)
  * [2. Procedure](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr#_procedure)
  * [2.1. Obtain the latest Backup of the primary data](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr#_obtain_the_latest_backup_of_the_primary_data)
  * [2.2. Enable CRR on the DR cluster](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr#_enable_crr_on_the_dr_cluster)
  * [2.3. Force install queries on primary](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr#_force_install_queries_on_primary)
  * [3. Restrictions on the DR cluster](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr#_restrictions_on_the_dr_cluster)
  * [4. Sync an outdated DR cluster](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr#_sync_an_outdated_dr_cluster)
  * [5. Advanced settings for CRR](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr#_advanced_settings_for_crr)
  * [5.1. Retrieve the current configuration of CRR](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr#_retrieve_the_current_configuration_of_crr)
  * [5.2. Setting up and updating the configuration](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr#_setting_up_and_updating_the_configuration)
  * [6. Updating a CRR system](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr#_updating_a_crr_system)


# Set Up Cross-Region Replication
### Contents
  * [1. Before you begin](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr#_before_you_begin)
  * [2. Procedure](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr#_procedure)
  * [2.1. Obtain the latest Backup of the primary data](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr#_obtain_the_latest_backup_of_the_primary_data)
  * [2.2. Enable CRR on the DR cluster](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr#_enable_crr_on_the_dr_cluster)
  * [2.3. Force install queries on primary](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr#_force_install_queries_on_primary)
  * [3. Restrictions on the DR cluster](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr#_restrictions_on_the_dr_cluster)
  * [4. Sync an outdated DR cluster](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr#_sync_an_outdated_dr_cluster)
  * [5. Advanced settings for CRR](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr#_advanced_settings_for_crr)
  * [5.1. Retrieve the current configuration of CRR](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr#_retrieve_the_current_configuration_of_crr)
  * [5.2. Setting up and updating the configuration](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr#_setting_up_and_updating_the_configuration)
  * [6. Updating a CRR system](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr#_updating_a_crr_system)


To set up cross-region replication (CRR), you set up Disaster Recovery (DR) clusters that sync with the primary cluster. Changes on the primary cluster are copied over to the DR cluster.
When necessary, you can fail over to a DR cluster, making it the new primary cluster.
## [](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr#_before_you_begin)1. Before you begin
  * Install TigerGraph 3.10.0 or higher on both the primary cluster and the DR cluster **in the same version**.
  * Make sure that your DR cluster has the same number of partitions as the primary cluster.
  * Make sure the username and password of the TigerGraph database user created on the DR cluster during installation matches one of the users on the primary cluster who have the `superuser` role.
  * If you choose to enable CRR and your DR cluster is in a different Virtual Private Cloud (VPC) than your primary cluster, make sure that TigerGraph is installed on your cluster with public IPs:
    * If you [install interactively](https://docs.tigergraph.com/tigergraph-server/3.10/installation/bare-metal-install#_interactive_installation), make sure that you supply the public IP of all nodes.
    * If you [install non-interactively](https://docs.tigergraph.com/tigergraph-server/3.10/installation/bare-metal-install#_non_interactive_installation), make sure in the `NodeList` field of `install_conf.json` that you are providing the public IPs for all nodes.


Make sure TigerGraph is **not** installed with a local loopback IP such as 127.0.0.1. You can verify if you are using loopback IP with `gadmin config get System.HostList` if this returns 127.0.0.1 then it means you have installed TigerGraph with loopback IP  
---  
## [](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr#_procedure)2. Procedure
The following setup is needed in order to enable Cross Region Replication.
### [](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr#_obtain_the_latest_backup_of_the_primary_data)2.1. Obtain the latest Backup of the primary data
Retrieve the latest backup, for instance, `pr_latest_backup` from the Primary Cluster. How recent the backup is will determine how much the DR cluster lags behind and how long it will take to catch up with the Primary cluster.
If there is no suitable backup, use `gadmin backup create <pr_latest_backup>` to create one. For more details refer to [Back up a Database Cluster](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/backup-cluster).
For how to restore a cluster from a backup that was created from another database cluster (cross cluster), refer to [Restore a Database Backup from Another Cluster](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/restore-cross-cluster).
For setting up a new DR cluster after failover, refer to [tigergraph-server:cluster-and-ha-management:fail-over.adoc#_set_up_a_new_dr_cluster_after_failover](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/fail-over#_set_up_a_new_dr_cluster_after_failover).
### [](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr#_enable_crr_on_the_dr_cluster)2.2. Enable CRR on the DR cluster
Run the following commands on the DR cluster to enable CRR on the DR cluster.
  1. Set Kafka Primary IP(s), Primary Port, and TopicPrefix.
Set Kafka MirrorMaker primary cluster’s IPs, with the separator of ( `,` ):
```
$ gadmin config set System.CrossRegionReplication.PrimaryKafkaIPs <PRIMARY_IP1,PRIMARY_IP2,PRIMARY_IP3>
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Set Kafka MirrorMaker primary cluster’s KafkaPort:
```
$ gadmin config set System.CrossRegionReplication.PrimaryKafkaPort 30002
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The prefix of GPE/GUI/GSQL Kafka Topic, by default is empty.
```
$ gadmin config set System.CrossRegionReplication.TopicPrefix Primary
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Apply the changes.
```
$ gadmin config apply -y
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

These steps above can be skipped if these settings are already configured properly.  
---  
  2. Enable the CRR setup.
Run with the latest backup from its primary cluster.
```
gadmin backup restore pr_latest_backup --dr
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Adding `--dr` to `gadmin backup restore <backup tag>` enables CRR in a regular restore.


Enabling Cross-Region Replication (CRR) with a backup is always recommended, as the Disaster Recovery (DR) cluster will be restored to the state of the backup. This can help avoid data inconsistency problems caused by unexpected operations or requests before the cluster becomes a DR.
For special cases, such as enabling Cross-Region Replication (CRR) for a new cluster or switching between PR and DR, backup can be omitted.
However, note that these operations should be performed when there is no traffic, because `gadmin backup restore --dr` won’t overwrite the data of the cluster before it is set to be a DR.
+ .Instead, simply run:
```
gadmin backup restore --dr
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Specifically, when switching between PR and DR, before the switch, it is necessary to [check data consistency between primary and DR](https://docs.tigergraph.com/tigergraph-server/3.9/cluster-and-ha-management/troubleshooting#_check_data_consistency_between_primary_and_dr)
Starting from version 3.10, setting System.CrossRegionReplication.Enabled to true is no longer permitted. However, setting it to `false` is still permissible. ```
$ gadmin config set System.CrossRegionReplication.Enabled true
[ Error] ParameterErr (to enable 'System.CrossRegionReplication.Enabled', please use `gadmin restore --dr xxx` to do it instead)

$ gadmin config set System.CrossRegionReplication.Enabled false
[  Info] Configuration has been changed. Please use 'gadmin config apply' to persist the changes.![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!
```
The default value of `System.CrossRegionReplication.Enabled` is `false`. User can set it back with `gadmin backup restore <latest-backup> --dr`.  
---  
### [](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr#_force_install_queries_on_primary)2.3. Force install queries on primary
Run the `INSTALL QUERY -force ALL` command on the primary cluster. After the command is finished, all other metadata operations on the primary cluster will start syncing to the DR cluster.
## [](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr#_restrictions_on_the_dr_cluster)3. Restrictions on the DR cluster
After being set up, the DR cluster will be read-only and all data update operations will be blocked. This includes the following operations:
  * All metadata operations
    * Schema changes
    * User access management operations
    * Query creation, installation, and dropping
    * User-defined function operations
  * Data-loading operations
    * Loading job operations
    * RESTPP calls that modify graph data
  * Queries that modify the graph


## [](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr#_sync_an_outdated_dr_cluster)4. Sync an outdated DR cluster
When the primary cluster executes an `IMPORT`, `DROP ALL`, or `CLEAR GRAPH STORE` GSQL command, or the `gsql --reset` bash command, the services on the DR cluster will stop syncing with the primary and become outdated.
To bring an outdated cluster back in sync, you need to generate a fresh backup of the primary cluster, and perform the setup steps detailed on this page again.
The simply run:
```
gadmin backup restore <latest-backup> --dr
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr#_advanced_settings_for_crr)5. Advanced settings for CRR
### [](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr#_retrieve_the_current_configuration_of_crr)5.1. Retrieve the current configuration of CRR
Run the `gadmin crr config` to view the current configuration of CRR. You can save it to a file with the extension "cfg" for easy reference and future adjustments.
### [](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr#_setting_up_and_updating_the_configuration)5.2. Setting up and updating the configuration
Any configuration parameters supported by Mirror-Source-Connector can be set in the configuration file, by running `gadmin crr update -c <your_crr.cfg>` to update the settings.
```
heartbeats.topic.replication.factor=1
replication.factor=1
sync.topic.acls.enabled=false
key.converter=org.apache.kafka.connect.converters.ByteArrayConverter
offset-syncs.topic.replication.factor=1
secondary.scheduled.rebalance.max.delay.ms=35000
status.storage.replication.factor=1
topics=deltaQ.* ,Metadata.* ,GSE_journal_.*
config.storage.replication.factor=1
source.cluster.alias=Primary
target.cluster.alias=Secondary
checkpoints.topic.replication.factor=1
connector.class=org.apache.kafka.connect.mirror.MirrorSourceConnector
emit.heartbeats.interval.seconds=5
header.converter=org.apache.kafka.connect.converters.ByteArrayConverter
offset.storage.replication.factor=1
source->target.enabled=true
value.converter=org.apache.kafka.connect.converters.ByteArrayConverter

[connector_mm]
name=infr_mm
# Setting Example
# We can improve throughput by adjusting the maximum parallelism.
tasks.max=4
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Do not change the values of `name`, `topics`, as this will cause the CRR to work abnormally.  
---  
## [](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr#_updating_a_crr_system)6. Updating a CRR system
From time to time, you may want to update the TigerGraph software on a CRR system. To perform this correctly, follow this sequence of steps.
  1. Stop CRR on your DR cluster.
```
$ gadmin crr stop -y
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  2. [Upgrade](https://docs.tigergraph.com/tigergraph-server/4.2/installation/upgrade) both the primary cluster and DR cluster.
  3. Start CRR on the DR cluster(From TigerGraph 3.10.0, no additional restart is required to start CRR).
```
$ gadmin crr start
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


