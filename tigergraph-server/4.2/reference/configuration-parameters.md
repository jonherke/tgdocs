![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters)[Next](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters)
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
  * References
  * [Configuration Parameters](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/4.2/modules/reference/pages/configuration-parameters.adoc)
### Contents
  * [Admin](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_admin)
  * [Controller](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_controller)
  * [Dict](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_dict)
  * [ETCD](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_etcd)
  * [Executor](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_executor)
  * [FileLoader](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_fileloader)
  * [GPE](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_gpe)
  * [GSE](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_gse)
  * [GSQL](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_gsql)
  * [GUI](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_gui)
  * [Gadmin](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_gadmin)
  * [Informant](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_informant)
  * [Kafka](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_kafka)
  * [KafkaConnect](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_kafkaconnect)
  * [KafkaLoader](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_kafkaloader)
  * [KafkaStreamLL](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_kafkastreamll)
  * [Nginx](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_nginx)
  * [RESTPP](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_restpp)
  * [Security](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_security)
  * [System](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_system)
  * [ZK](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_zk)
  * [Environment Variables](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_environment_variables)


# Configuration Parameters
### Contents
  * [Admin](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_admin)
  * [Controller](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_controller)
  * [Dict](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_dict)
  * [ETCD](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_etcd)
  * [Executor](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_executor)
  * [FileLoader](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_fileloader)
  * [GPE](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_gpe)
  * [GSE](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_gse)
  * [GSQL](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_gsql)
  * [GUI](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_gui)
  * [Gadmin](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_gadmin)
  * [Informant](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_informant)
  * [Kafka](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_kafka)
  * [KafkaConnect](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_kafkaconnect)
  * [KafkaLoader](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_kafkaloader)
  * [KafkaStreamLL](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_kafkastreamll)
  * [Nginx](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_nginx)
  * [RESTPP](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_restpp)
  * [Security](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_security)
  * [System](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_system)
  * [ZK](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_zk)
  * [Environment Variables](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_environment_variables)


This page provides a comprehensive list of system configuration parameters. See [Guide to management with gadmin](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/management-with-gadmin) for how to use `gadmin config` to set configuration parameters.
The parameters are organized by TigerGraph internal component, listed here in alphabetical order: `Admin`, `Controller`, `Dict`, etc.
In addition, the last table is for runtime environment variables. Each component may have a set of environment variables which are set by `xxx.BasicConfig.Env`. See `Admin.BasicConfig.Env` below for an example.
## [](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_admin)Admin
Name | Description | Example  
---|---|---  
Admin.BasicConfig.Env | A list of `<environment variable>=<value>` pairs, separated by `;` | `LD_LIBRARY_PATH=$LD_LIBRARY_PATH;`  
Admin.BasicConfig.LogConfig.LogFileMaxDurationDay | The maximum number of days to retain old log files based on the timestamp encoded in their filename | `90`  
Admin.BasicConfig.LogConfig.LogFileMaxSizeMB | The maximum size in megabytes of the log file before it gets rotated | `100`  
Admin.BasicConfig.LogConfig.LogLevel | The log level(`INFO`,`WARN`,`ERROR`), default is `INFO` | `INFO`  
Admin.BasicConfig.LogConfig.LogRotationFileNumber | The maximum number of old log files to retain | `100`  
Admin.BasicConfig.LogDirRelativePath | The relative path (to the System.LogRoot) of the log directory for Admin | `admin`  
Admin.BasicConfig.Nodes | The node list for Admin | `[{"HostID":"m1","Partition":0,"Replica":1},{"HostID":"m2","Partition":0,"Replica":2}]`  
Admin.Port | The port for Admin | `12471`  
## [](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_controller)Controller
Name | Description | Example  
---|---|---  
Controller.BasicConfig.Env | A list of `<environment variable>=<value>` pairs, separated by `;` | `nan`  
Controller.BasicConfig.LogConfig.LogFileMaxDurationDay | The maximum number of days to retain old log files based on the timestamp encoded in their filename | `90`  
Controller.BasicConfig.LogConfig.LogFileMaxSizeMB | The maximum size in megabytes of the log file before it gets rotated | `100`  
Controller.BasicConfig.LogConfig.LogLevel | The log level(`DEBUG`,`INFO`,`WARN`,`ERROR`,`PANIC`,`FATAL`), default is `INFO` | `INFO`  
Controller.BasicConfig.LogConfig.LogRotationFileNumber | The maximum number of old log files to retain | `100`  
Controller.BasicConfig.LogDirRelativePath | The relative path (to the System.LogRoot) of log directory for Controller | `controller`  
Controller.BasicConfig.Nodes | The nodes to deploy Controller | `[{"HostID":"m1","Partition":0,"Replica":1},{"HostID":"m2","Partition":0,"Replica":2}]`  
Controller.ConfigRepoRelativePath | The relative path (to the System.DataRoot) of config repo where the service config files are stored | `configs`  
Controller.Connect.PrunerEnabled | Whether to automatically remove data that was already loaded by GSQL in Kafka. | `true`  
Controller.Connect.PruneIntervalMin | The wait time, in minutes, between each prune job that removes data already loaded by GSQL in Kafka. Accepts an integer from 1 to 59, inclusive. | `1`  
Controller.FileRepoRelativePath | The relative path (to the System.DataRoot) of the file repo for file management | `files`  
Controller.FileRepoVersionNum | The maximum version of files to keep in the file repo | `3`  
Controller.LeaderElectionHeartBeatIntervalMS | The maximum interval(milliseconds) at which each service should call controller leader election service to be considered alive. | `6000`  
Controller.LeaderElectionHeartBeatMaxMiss | The maximum number of heartbeats that can be missed before one service is considered dead by the controller | `5`  
Controller.Port | The serving gRPC (Google Remote Procedure Call) port for Controller | `9188`  
## [](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_dict)Dict
Name | Description | Example  
---|---|---  
Dict.BasicConfig.Env | A list of `<environment variable>=<value>` pairs, separated by `;` | `LD_LIBRARY_PATH=$LD_LIBRARY_PATH;`  
Dict.BasicConfig.LogConfig.LogFileMaxDurationDay | The maximum number of days to retain old log files based on the timestamp encoded in their filename | `90`  
Dict.BasicConfig.LogConfig.LogFileMaxSizeMB | The maximum size in megabytes of the log file before it gets rotated | `100`  
Dict.BasicConfig.LogConfig.LogRotationFileNumber | The maximum number of old log files to retain | `100`  
Dict.BasicConfig.LogDirRelativePath | The relative path (to the System.LogRoot) of log directory for Dict | `dict`  
Dict.BasicConfig.Nodes | The node list for Dict | `[{"HostID":"m1","Partition":0,"Replica":1},{"HostID":"m2","Partition":0,"Replica":2}]`  
Dict.Port | The port for Dict | `17797`  
## [](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_etcd)ETCD
Name | Description | Example  
---|---|---  
ETCD.BasicConfig.Env | A list of `<environment variable>=<value>` pairs, separated by `;` | `ETCD_UNSUPPORTED_ARCH=arm64`  
ETCD.BasicConfig.LogConfig.LogFileMaxDurationDay | The maximum number of days to retain old log files based on the timestamp encoded in their filename | `90`  
ETCD.BasicConfig.LogConfig.LogFileMaxSizeMB | The maximum size in megabytes of the log file before it gets rotated | `100`  
ETCD.BasicConfig.LogConfig.LogLevel | The log level(`DEBUG`,`INFO`,`WARN`,`ERROR`,`PANIC`,`FATAL`), default is `INFO` | `INFO`  
ETCD.BasicConfig.LogConfig.LogRotationFileNumber | The maximum number of old log files to retain | `100`  
ETCD.BasicConfig.LogDirRelativePath | The relative path (to the System.LogRoot) of the log directory for ETCD | `etcd`  
ETCD.BasicConfig.Nodes | The node list for ETCD | `[{"HostID":"m1","Partition":0,"Replica":1},{"HostID":"m2","Partition":0,"Replica":2}]`  
ETCD.ClientPort | The port of ETCD to listen for client traffic | `20000`  
ETCD.DataRelativePath | The data dir of etcd under `$DataRoot` | `etcd`  
ETCD.ElectionTimeoutMS | Time (in milliseconds) for an election to timeout | `1000`  
ETCD.HeartbeatIntervalMS | Time (in milliseconds) of a heartbeat interval | `100`  
ETCD.MaxRequestBytes | Maximum client request size in bytes the server will accept | `52428800`  
ETCD.MaxSnapshots | Maximum number of snapshot files to retain (0 is unlimited) | `5`  
ETCD.MaxTxnOps | Maximum number of operations permitted in a transaction | `8192`  
ETCD.MaxWals | Maximum number of wal files to retain (0 is unlimited) | `5`  
ETCD.PeerPort | The port of ETCD to listen for peer traffic | `20001`  
ETCD.SnapshotCount | Number of committed transactions to trigger a snapshot to disk | `50000`  
## [](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_executor)Executor
Name | Description | Example  
---|---|---  
Executor.BasicConfig.Env | A list of `<environment variable>=<value>` pairs, separated by `;` | `nan`  
Executor.BasicConfig.LogConfig.LogFileMaxDurationDay | The maximum number of days to retain old log files based on the timestamp encoded in their filename | `90`  
Executor.BasicConfig.LogConfig.LogFileMaxSizeMB | The maximum size in megabytes of the log file before it gets rotated | `100`  
Executor.BasicConfig.LogConfig.LogLevel | The log level(`DEBUG`,`INFO`,`WARN`,`ERROR`,`PANIC`,`FATAL`), default is `INFO` | `INFO`  
Executor.BasicConfig.LogConfig.LogRotationFileNumber | The maximum number of old log files to retain | `100`  
Executor.BasicConfig.LogDirRelativePath | The relative path (to the System.LogRoot) of log directory for Executor | `executor`  
Executor.BasicConfig.Nodes | The nodes to deploy Executors | `[{"HostID":"m1","Partition":1,"Replica":0},{"HostID":"m2","Partition":2,"Replica":0}]`  
Executor.DataRelativePath | The data dir of executor under $DataRoot | `executor`  
Executor.FileTransferConcurrency | The maximum concurrency for Executor file transfer | `10`  
Executor.FileTransferPort | The port for Executor to do file transfer | `9178`  
Executor.FileVersionNum | The maximum version of files to keep | `10`  
Executor.Port | The serving port for Executor | `9177`  
Executor.WatchDogIntervalMS | The process status check interval (ms) | `1000`  
## [](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_fileloader)FileLoader
Name | Description | Example  
---|---|---  
FileLoader.BasicConfig.Env | A list of `<environment variable>=<value>` pairs, separated by `;` | `nan`  
FileLoader.BasicConfig.LogConfig.LogFileMaxDurationDay | The maximum number of days to retain old log files based on the timestamp encoded in their filename | `90`  
FileLoader.BasicConfig.LogConfig.LogFileMaxSizeMB | The maximum size in megabytes of the log file before it gets rotated | `100`  
FileLoader.BasicConfig.LogConfig.LogLevel | The log level(`OFF`, `BRIEF`, `DEBUG`, `VERBOSE`), default is `BRIEF` | `BRIEF`  
FileLoader.BasicConfig.LogConfig.LogRotationFileNumber | The maximum number of old log files to retain | `100`  
FileLoader.BasicConfig.LogDirRelativePath | The relative path (to the System.LogRoot) of log directory for FileLoader | `fileLoader`  
FileLoader.Factory.DefaultLoadingTimeoutSec | The default per request loading timeout (s) for FileLoader | `600`  
FileLoader.Factory.DefaultQueryTimeoutSec | The default query timeout (s) for FileLoader | `16`  
FileLoader.Factory.DynamicEndpointRelativePath | FileLoader’s relative (to data root) path to store the dynamic endpoint | `fileLoader/endpoint/`  
FileLoader.Factory.DynamicSchedulerRelativePath | FileLoader’s relative (to data root) path to store the dynamic scheduler | `fileLoader/scheduler/`  
FileLoader.Factory.EnableAuth | Enable authentication of FileLoader | `false`  
FileLoader.Factory.HandlerCount | FileLoader’s handler count | `4`  
FileLoader.Factory.StatsIntervalSec | FileLoader’s time interval to collect stats (e.g. QPS) | `60`  
FileLoader.GPEResponseBasePort | The port of FileLoader to accept GPE response | `8400`  
FileLoader.GSEResponseBasePort | The port of FileLoader to accept GSE response | `8500`  
FileLoader.ReplicaNumber | The number of replicas of Fileloader per node | `1`  
## [](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_gpe)GPE
Name | Description | Example  
---|---|---  
GPE.BasicConfig.Env | A list of `<environment variable>=<value>` pairs, separated by `;` | `LD_PRELOAD=$LD_PRELOAD; LD_LIBRARY_PATH=$LD_LIBRARY_PATH; CPUPROFILE=/tmp/tg_cpu_profiler; CPUPROFILESIGNAL=34; MALLOC_CONF=prof:true,prof_active:false; ZMQ_KEEPALIVE=1`  
GPE.BasicConfig.LogConfig.LogFileMaxDurationDay | The maximum number of days to retain old log files based on the timestamp encoded in their filename | `90`  
GPE.BasicConfig.LogConfig.LogFileMaxSizeMB | The maximum size in megabytes of the log file before it gets rotated | `100`  
GPE.BasicConfig.LogConfig.LogLevel | The log level (`OFF`, `BRIEF`, `DEBUG`, `VERBOSE`), default is `BRIEF` | `BRIEF`  
GPE.BasicConfig.LogConfig.LogRotationFileNumber | The maximum number of old log files to retain | `100`  
GPE.BasicConfig.LogDirRelativePath | The relative path (to the System.LogRoot) of log directory for GPE | `gpe`  
GPE.BasicConfig.Nodes | The node list for GPE | `[{"HostID":"m1","Partition":1,"Replica":1},{"HostID":"m2","Partition":1,"Replica":2}]`  
GPE.Disk.CompressMethod | The compression method of GPE disk data | `nan`  
GPE.Disk.DiskStoreRelativePath | The path (relative to temp root) to store GPE temporary disk data | `gpe/disks`  
GPE.Disk.LoadThreadNumber | The number of threads to load from disk | `1`  
GPE.Disk.SaveThreadNumber | The number of threads to save to disk | `1`  
GPE.EdgeDataMemoryLimit | The memory limit for edge data. | `-1`  
GPE.GPE2GPEResponsePort | The GPE port for receiving response back from other GPEs | `7501`  
GPE.GPERequestPort | The GPE port for receiving requests | `7502`  
GPE.IdResponsePort | The GPE port for receiving id response from GSE | `7500`  
GPE.Kafka.BatchMsgNumber | The number of messages to send in one batch when using async mode. The producer will wait until either this number of messages are ready to send or queue buffer max ms is reached. | `64`  
GPE.Kafka.CompressCodec | This parameter allows you to specify the compression codec for all data generated by this producer. Valid values are none, gzip and snappy. | `none`  
GPE.Kafka.FetchErrorBackoffTimeMS | How long to postpone the next fetch request for a topic+partition in case of a fetch error. | `6`  
GPE.Kafka.FetchWaitMaxTimeMS | The maximum amount of time the server will block before answering the fetch request if there isn’t sufficient data to immediately satisfy fetch min bytes. | `10`  
GPE.Kafka.MsgMaxBytes | Maximum transmit message size. | `10485760`  
GPE.Kafka.QueueBufferMaxMsgNumber | The maximum number of unsent messages that can be queued up the producer when using async mode before either the producer must be blocked or data must be dropped. | `64`  
GPE.Kafka.QueueBufferMaxTimeMS | Maximum time to buffer data when using async mode. | `1`  
GPE.Kafka.QueueMinMsgNumber | Minimum number of messages per topic+partition in the local consumer queue. | `100000`  
GPE.Kafka.RequestRequiredAcks | This field indicates how many acknowledgements the leader broker must receive from ISR brokers before responding to the request. | `1`  
GPE.LeaderElectionTTLSec | The time-to-live of a GPE election participant. A GPE will be kicked out of election if one GPE is not responsive after the TTL. | `30`  
GPE.MemoryLimitMB | The total topology memory limit. For graphs with large topology data, this parameter can limit the system memory used for topology data in order to free up memory for query processing. This parameter takes precedence over the `EdgeDataMemoryLimit` and `VertexDataMemoryLimit` parameters. | `-1`  
GPE.NumberOfHashBucketInBit | The number of bits used to represent hash bucket counts. | `5`  
GPE.RebuildThreadNumber | The number of rebuild threads for GPE | `3`  
GPE.StopTimeoutMS | Stop GPE timeout. Default 300000 (300s) | `200000`  
GPE.VertexDataMemoryLimit | The memory limit for vertex data in the topology. | `-1`  
## [](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_gse)GSE
Name | Description | Example  
---|---|---  
GSE.BasicConfig.Env | A list of `<environment variable>=<value>` pairs, separated by `;` Some of the environment variables: `MaxLicenseViolation`: max license violation times, default/max value: 3; `LicenseCheckInterval`: how often (in seconds) to check license violations, default/max value: 300; `UpdateGraphInterval`: how often (in seconds) to pull topology info from Zookeeper, default/max value: 300 | `LD_PRELOAD=$LD_PRELOAD; LD_LIBRARY_PATH=$LD_LIBRARY_PATH; CPUPROFILE=/tmp/tg_cpu_profiler; CPUPROFILESIGNAL=34; MALLOC_CONF=prof:true,prof_active:false`  
GSE.BasicConfig.LogConfig.LogFileMaxDurationDay | The maximum number of days to retain old log files based on the timestamp encoded in their filename | `90`  
GSE.BasicConfig.LogConfig.LogFileMaxSizeMB | The maximum size in megabytes of the log file before it gets rotated | `100`  
GSE.BasicConfig.LogConfig.LogLevel | The log level(`OFF`, `BRIEF`, `DEBUG`, `VERBOSE`), default is `BRIEF` | `BRIEF`  
GSE.BasicConfig.LogConfig.LogRotationFileNumber | The maximum number of old log files to retain | `100`  
GSE.BasicConfig.LogDirRelativePath | The relative path (to the System.LogRoot) of log directory for GSE | `gse`  
GSE.BasicConfig.Nodes | The node list for GSE | `[{"HostID":"m1","Partition":1,"Replica":1},{"HostID":"m2","Partition":1,"Replica":2}]`  
GSE.IdRequestPort | The id request serving port of GSE | `6500`  
GSE.JournalTopicPrefix | Kafka Topic prefix of GSE journal storage/replication | `GSE_journal_`  
GSE.LeaderElectionTTLSec | The time-to-live of a GSE election participant. A GSE will be kicked out of election if one GSE is not responsive after the TTL. | `30`  
GSE.RLSPort | The serving port of GSE RLS | `8900`  
GSE.StopTimeoutMS | Stop GSE timeout | `300000`  
## [](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_gsql)GSQL
Name | Description | Example  
---|---|---  
GSQL.BasicConfig.Env | A list of `<environment variable>=<value>` pairs, separated by `;` | `CPATH=$CPATH; LD_LIBRARY_PATH=$LD_LIBRARY_PATH;`  
GSQL.BasicConfig.LogConfig.LogFileMaxSizeMB | The maximum size in megabytes of the log file before it gets rotated | `100`  
GSQL.BasicConfig.LogConfig.LogLevel | GSQL log level: `ERROR`, `INFO`, `DEBUG` | `INFO`  
GSQL.BasicConfig.LogConfig.LogRotationFileNumber | The maximum number of old log files to retain | `100`  
GSQL.BasicConfig.LogDirRelativePath | The relative path (to the System.LogRoot) of log directory for GSQL | `gsql`  
GSQL.BasicConfig.Nodes | The node list for GSQL | `[{"HostID":"m1","Partition":0,"Replica":1},{"HostID":"m2","Partition":0,"Replica":2}]`  
GSQL.CatalogBackupFileMaxDurationDay | The maximum number of days for catalog backup files to retain | `30`  
GSQL.CatalogBackupFileMaxNumber | The maximum number of catalog backup files to retain | `20`  
GSQL.DataRelativePath | The data dir of gsql under $DataRoot | `gsql`  
GSQL.EnableStringCompress | Enable string compress | `false`  
GSQL.FileOutputPolicy | The policy to control file outputs in GSQL queries | `["/"]`  
GSQL.GithubBranch | The working branch in provided repository. Will use `master' as the default branch | `nan`  
GSQL.GithubPath | The path to the directory in the github that has TokenBank.cpp, ExprFunctions.hpp, ExprUtil.hpp, e.g. sample_code/src | `nan`  
GSQL.GithubRepository | The repository name, e.g. tigergraph/ecosys | `nan`  
GSQL.GithubUrl | The url that is used for github enterprise, e.g. https://api.github.com | `nan`  
GSQL.GithubUserAcessToken | The credential for github. Set it to `anonymous' for public access, or empty to not use github | `nan`  
`GSQL.GithubEnabled` | To Enable the retrieval of UDFs (such as ExprFunctions.hpp, ExprUtils.hpp, etc.) from GitHub (default `false`). | `false`  
GSQL.GrpcMessageMaxSizeMB | The maximum size of grpc message request of gsql | `40`  
GSQL.HA.BufferedReaderBufferSizeBytes | Customizes the buffer size (in bytes) for messages sent between GSQL servers in a HA cluster. | `8192` (bytes). If it is set below `8192`, GSQL will reset it to `8192`. Must be a positive 32-bit integer (less than `2147483647`).  
GSQL.LoginLimit.InitialWaitTimeSec | The amount of time in seconds a user has to wait for the subsequent login after the number of successive failed login attempts reaches the initial threshold. | `10`  
GSQL.LoginLimit.InitialThreshold | The number of successive failed login attempts since the last successful login to apply the wait time for the subsequent login attempts. Set 0 to disable the rate limiting. | `5`  
GSQL.LoginLimit.SecondaryThreshold | The number of successive failed login attempts after reaching the initial threshold that the wait time will be doubled for every this number of successive failed login attempts afterward. | `2`  
GSQL.ManageCatalogTimeoutSec | GSQL connection timeout (second) to admin server when trying to download/upload/delete catalog. Default value: 20 | 20  
GSQL.MaxAuthTokenLifeTimeSec | The maximum lifetime of auth token in seconds, 0 means unlimited | `0`  
GSQL.OutputTokenBufferSize | The buffer size for output token from GSQL | `16000000`  
GSQL.Port | The server port for GSQL | `8123`  
GSQL.QueryResponseMaxSizeByte | Maximum response size in byte | `33554432`  
GSQL.RESTPPRefreshTimeoutSec | Refresh time in Seconds of Restpp | `60`  
GSQL.SchemaIndexFileNumber | File number | `10`  
GSQL.TokenCleaner.GraceTimeSec | The grace time (in seconds) for expired tokens to exist without being cleaned | `0`  
GSQL.TokenCleaner.IntervalTimeSec | The running interval of TokenCleaner in seconds | `10800`  
GSQL.UDF.EnablePutTokenBank | Whether to enable the `PUT` command to upload a TokenBank file. | `false`  
GSQL.UDF.EnablePutExpr | Whether to enable the `PUT` command to upload an ExprFunction file. | `false`  
GSQL.UDF.Policy.Enable | Whether to enforce a policy on the contents of UDF files (see [UDF file scanning](https://docs.tigergraph.com/tigergraph-server/4.2/security/#_udf_file_scanning)). | `true`  
GSQL.UDF.Policy.HeaderAllowlist | A default set of C++ headers that are allowed to be included in a UDF file. | `["stdlib.h", "string", "tuple", "vector", "list", "deque", "arrays", "forward_list", "queue", "priority_queue", "stack", "set", "multiset", "map", "multimap", "unordered_set", "unordered_multiset", "unordered_map", "unordered_multimap", "iterator", "sstream", "algorithm", "math.h"]`  
GSQL.UserInfoLimit.TokenSizeLimit | The max number of tokens allowed | `60000`  
GSQL.UserInfoLimit.UserCatalogFileMaxSizeByte | The file size limit for user metadata in byte | `2097152`  
GSQL.UserInfoLimit.UserSizeLimit | The max number of users allowed | `12000`  
GSQL.WaitServiceOnlineTimeoutSec | Timeout to wait for all services online | `300`  
GSQL.QueryPlanCache.Enable | Enables the [query plan cache](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-plan-cache), default is `true` | `true`  
GSQL.QueryPlanCache.Capacity | Maximum number of [queries in the cache](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-plan-cache). Range from 1 : 100,000. default is 10,000. | `10000`  
## [](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_gui)GUI
Name | Description | Example  
---|---|---  
GUI.BasicConfig.Env | A list of `<environment variable>=<value>` pairs, separated by `;` | `nan`  
GUI.BasicConfig.LogConfig.LogFileMaxDurationDay | The maximum number of days to retain old log files based on the timestamp encoded in their filename | `90`  
GUI.BasicConfig.LogConfig.LogFileMaxSizeMB | The maximum size in megabytes of the log file before it gets rotated | `100`  
GUI.BasicConfig.LogConfig.LogLevel | The log level(`DEBUG`,`INFO`,`WARN`,`ERROR`,`PANIC`,`FATAL`), default is `INFO` | `INFO`  
GUI.BasicConfig.LogConfig.LogRotationFileNumber | The maximum number of old log files to retain | `100`  
GUI.BasicConfig.LogDirRelativePath | The relative path (to the System.LogRoot) of log directory for GUI | `gui`  
GUI.BasicConfig.Nodes | The node list for GraphStudio | `[{"HostID":"m1","Partition":0,"Replica":1},{"HostID":"m2","Partition":0,"Replica":2}]`  
GUI.ClientIdleTimeSec | The maximum idle time of client-side GraphStudio and AdminPortal before inactivity logout | `604800`  
GUI.Cookie.DurationSec | GUI Cookie duration time in seconds | `86400`  
GUI.Cookie.SameSite | Default mode: 1; Lax mode: 2; Strict mode: 3; None mode: 4 | `3`  
GUI.EnableConcurrentSession | Enable or disable concurrent sessions for GUI. Setting to `false` will disable concurrent sessions.The default value is `true`. | `true`  
GUI.DataDirRelativePath | The relative path of gui data folder (to the System.DataRoot) | `gui`  
GUI.EnableDarkTheme | The boolean value on whether or not GUI should enable dark theme | `true`  
GUI.GraphQLConfig.SchemaRefreshPeriod | The schema refresh period of GraphQL service | `10`  
GUI.GraphStatCheckIntervalSec | The internval(in seconds) GraphStudio wait before checking the graph statistics | `10`  
GUI.HTTPRequest.RetryMax | GUI http request max retry times | `4`  
GUI.HTTPRequest.RetryWaitMaxSec | GUI HTTP request max retry waiting time in seconds | `30`  
GUI.HTTPRequest.RetryWaitMinSec | GUI HTTP request minimum retry waiting time in seconds | `1`  
GUI.HTTPRequest.TimeoutSec | GUI HTTP request timeout in seconds | `604800`  
GUI.Port | The serving port for GraphStudio Websocket communication | `14242`  
GUI.RESTPPResponseMaxSizeBytes | The RESTPP response size limit bytes. | `33554432`  
GUI.TempDirRelativePath | The relative path of gui temp folder (to the System.TempRoot) | `gui`  
GUI.TempFileMaxDurationDay | GUI temp file max duration time in days | `7`  
## [](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_gadmin)Gadmin
Name | Description | Example  
---|---|---  
Gadmin.StartServiceDefaultTimeoutMS | The start one service default timeout in milliseconds | `30000`  
Gadmin.StartStopRequestTimeoutMS | The start/stop service default request timeout in milliseconds | `600000`  
Gadmin.StopServiceDefaultTimeoutMS | The stop one service default request timeout in milliseconds. Default 200000 (200s). | `30000`  
## [](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_informant)Informant
Name | Description | Example  
---|---|---  
Informant.BasicConfig.Env | A list of `<environment variable>=<value>` pairs, separated by `; | `nan`  
Informant.BasicConfig.LogConfig.LogFileMaxDurationDay | The maximum number of days to retain old log files based on the timestamp encoded in their filename | `90`  
Informant.BasicConfig.LogConfig.LogFileMaxSizeMB | The maximum size in megabytes of the log file before it gets rotated | `100`  
Informant.BasicConfig.LogConfig.LogLevel | The log level(`DEBUG`,`INFO`,`WARN`,`ERROR`,`PANIC`,`FATAL`), default is `INFO` | `INFO`  
Informant.BasicConfig.LogConfig.LogRotationFileNumber | The maximum number of old log files to retain | `100`  
Informant.BasicConfig.LogDirRelativePath | The relative path (to the System.LogRoot) of log directory for Informant | `informant`  
Informant.BasicConfig.Nodes | The nodes to deploy Informant | `[{"HostID":"m1","Partition":0,"Replica":1},{"HostID":"m2","Partition":0,"Replica":2}]`  
Informant.DBRelativePath | The relative path (to the System.DataRoot) of informant database source folder | `informant/db`  
Informant.GrpcPort | The grpc server port for Informant | `9166`  
Informant.RestPort | The restful server port for Informant | `9167`  
Informant.RetentionPeriodDay | The period in days for local data records to be kept, set to -1 for forever (not advised). Longer retention results in higher disk space usage and slower search for historical status | `7` (default. Prior to v3.9.2, the default was 30.)  
## [](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_kafka)Kafka
Name | Description | Example  
---|---|---  
Kafka.BasicConfig.Env | A list of `<environment variable>=<value>` pairs, separated by `;` | `nan`  
Kafka.BasicConfig.LogConfig.LogFileMaxSizeMB | The maximum size in megabytes of the log file before it gets rotated | `100`  
Kafka.BasicConfig.LogConfig.LogLevel | The log level for kafka (`TRACE`, `DEBUG`, `INFO`, `WARN`, `ERROR`, `FATAL`, `OFF`) | `INFO`  
Kafka.BasicConfig.LogConfig.LogRotationFileNumber | The maximum number of old log files to retain | `100`  
Kafka.BasicConfig.LogDirRelativePath | The relative path (to the System.LogRoot) of log directory for Kafka | `kafka`  
Kafka.BasicConfig.Nodes | The node list for Kafka | `[{"HostID":"m1","Partition":0,"Replica":1},{"HostID":"m2","Partition":0,"Replica":2}]`  
Kafka.DataRelativePath | The data dir of kafka under $DataRoot | `kafka`  
Kafka.IOThreads | The number of threads for Kafka IO | `2`  
Kafka.LogFlushIntervalMS | The threshold of time for flushing log (ms) | `10000`  
Kafka.LogFlushIntervalMessage | The threshold of message for flushing log | `10000`  
Kafka.MessageMaxSizeMB | The maximum size of a message of Kafka to be produced (megabytes) | `10`  
Kafka.MinInsyncReplicas | The minimal number of insync replicas that must acknowledge, when producer sets acks to `all' | `1`  
Kafka.NetworkThreads | The number of threads for Kafka Network | `4`  
Kafka.Port | The serving port for Kafka | `30002`  
Kafka.RetentionHours | The minimum age of a log file of Kafka to be eligible for deletion (hours) | `168`  
Kafka.RetentionSizeGB | The minimum size of a log file of Kafka to be eligible for deletion (gigabytes) | `40`  
Kafka.StartTimeoutMS | Start kafka timeout | `300000`  
Kafka.TopicReplicaFactor | The default replica number for each topic | `1`  
## [](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_kafkaconnect)KafkaConnect
Name | Description | Example  
---|---|---  
KafkaConnect.AllowedTaskPerCPU | [v3.9.2+] Maximum number of allowed connector tasks = (#CPUs) x AllowedTaskPerCPU. Range is [0.5,10]. It is recommended to stay below 2.0. | `1.5` (default)  
KafkaConnect.BasicConfig.Env | A list of `<environment variable>=<value>` pairs, separated by `;` | `nan`  
KafkaConnect.BasicConfig.LogConfig.LogFileMaxSizeMB | The maximum size in megabytes of the log file before it gets rotated | `100`  
KafkaConnect.BasicConfig.LogConfig.LogLevel | The log level for kafka connect (`TRACE`, `DEBUG`, `INFO`, `WARN`, `ERROR`, `FATAL` `OFF`) | `INFO`  
KafkaConnect.BasicConfig.LogConfig.LogRotationFileNumber | The maximum number of old log files to retain | `100`  
KafkaConnect.BasicConfig.LogDirRelativePath | The relative path (to the System.LogRoot) of log directory for Kafka connect | `kafkaconn`  
KafkaConnect.BasicConfig.Nodes | The node list for Kafka connect | `[{"HostID":"m1","Partition":0,"Replica":1},{"HostID":"m2","Partition":0,"Replica":2}]`  
KafkaConnect.MaxMemorySizeMB | The max memory usage limit of Kafka Connect in MB. | 10240  
KafkaConnect.MaxRequestSize | The max request size of kafka connect producer | `5242880`  
KafkaConnect.OffsetFlushIntervalMS | The interval at which Kafka connect tasks’ offsets are committed | `10000`  
KafkaConnect.Port | The port used for kafka connect | `30003`  
KafkaConnect.ReconnectBackoffMS | The amount of time to wait before attempting to reconnect to a given host | `500`  
KafkaConnect.RetryBackoffMS | The amount of time to wait before attempting to retry a failed fetch request to a given topic partition | `10000`  
## [](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_kafkaloader)KafkaLoader
Name | Description | Example  
---|---|---  
KafkaLoader.BasicConfig.Env | A list of `<environment variable>=<value>` pairs, separated by `;` | `nan`  
KafkaLoader.BasicConfig.LogConfig.LogFileMaxDurationDay | The maximum number of days to retain old log files based on the timestamp encoded in their filename | `90`  
KafkaLoader.BasicConfig.LogConfig.LogFileMaxSizeMB | The maximum size in megabytes of the log file before it gets rotated | `100`  
KafkaLoader.BasicConfig.LogConfig.LogLevel | The log level(`OFF`, `BRIEF`, `DEBUG`, `VERBOSE`), default is `BRIEF` | `BRIEF`  
KafkaLoader.BasicConfig.LogConfig.LogRotationFileNumber | The maximum number of old log files to retain | `100`  
KafkaLoader.BasicConfig.LogDirRelativePath | The relative path (to the System.LogRoot) of log directory for KafkaLoader | `kafkaLoader`  
KafkaLoader.Factory.DefaultLoadingTimeoutSec | The default per request loading timeout (s) for KafkaLoader | `600`  
KafkaLoader.Factory.DefaultQueryTimeoutSec | The default query timeout (s) for KafkaLoader | `16`  
KafkaLoader.Factory.DynamicEndpointRelativePath | KafkaLoader’s relative (to data root) path to store the dynamic endpoint | `kafkaLoader/endpoint/`  
KafkaLoader.Factory.DynamicSchedulerRelativePath | KafkaLoader’s relative (to data root) path to store the dynamic scheduler | `kafkaLoader/scheduler/`  
KafkaLoader.Factory.EnableAuth | Enable authentication of KafkaLoader | `false`  
KafkaLoader.Factory.HandlerCount | KafkaLoader’s handler count | `4`  
KafkaLoader.Factory.StatsIntervalSec | KafkaLoader’s time interval to collect stats (e.g. QPS) | `60`  
KafkaLoader.GPEResponseBasePort | The port of KafkaLoader to accept GPE response | `9400`  
KafkaLoader.GSEResponseBasePort | The port of KafkaLoader to accept GSE response | `9500`  
KafkaLoader.ReplicaNumber | The number of replica of kafkaloader per node | `1`  
## [](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_kafkastreamll)KafkaStreamLL
Name | Description | Example  
---|---|---  
KafkaStreamLL.BasicConfig.Env | A list of `<environment variable>=<value>` pairs, separated by `;` | `nan`  
KafkaStreamLL.BasicConfig.LogConfig.LogFileMaxSizeMB | The maximum size in megabytes of the log file before it gets rotated | `100`  
KafkaStreamLL.BasicConfig.LogConfig.LogLevel | The log level for Kafka stream LoadingLog (`TRACE`, `DEBUG`, `INFO`, `WARN`, `ERROR`, `FATAL`, `OFF`) | `INFO`  
KafkaStreamLL.BasicConfig.LogConfig.LogRotationFileNumber | The maximum number of old log files to retain | `100`  
KafkaStreamLL.BasicConfig.LogDirRelativePath | The relative path (to the System.LogRoot) of log directory for Kafka stream LoadingLog | `kafkastrm-ll`  
KafkaStreamLL.BasicConfig.Nodes | The node list for Kafka stream LoadingLog | `[{"HostID":"m1","Partition":1,"Replica":0},{"HostID":"m2","Partition":2,"Replica":0}]`  
KafkaStreamLL.MaxPartitionFetchBytes | Max partition fetch bytes size | `104857600`  
KafkaStreamLL.Port | The port used for Kafka stream LoadingLog | `30004`  
KafkaStreamLL.ReplicaNumber | The number of standby replicas. Standby replicas are shadow copies of local state stores | `1`  
KafkaStreamLL.StateDirRelativePath | The relative folder path for Kafka stream LoadingLog state | `kafkastrm-ll`  
## [](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_nginx)Nginx
Name | Description | Example  
---|---|---  
Nginx.AllowedCIDRList | The allowlist of IPv4/IPv6 CIDR blocks to restrict the application access, separate in comma. | `0.0.0.0/0, ::/0`  
Nginx.BasicConfig.LogConfig.LogFileMaxDurationDay | The maximum number of days to retain old log files based on the timestamp encoded in their filename | `90`  
Nginx.BasicConfig.LogConfig.LogFileMaxSizeMB | The maximum size in megabytes of the log file before it gets rotated | `100`  
Nginx.BasicConfig.LogConfig.LogRotationFileNumber | The maximum number of old log files to retain | `100`  
Nginx.BasicConfig.LogDirRelativePath | The relative path (to the System.LogRoot) of log directory for Nginx | `nginx`  
Nginx.BasicConfig.Nodes | The node list for Nginx | `[{"HostID":"m1","Partition":0,"Replica":1},{"HostID":"m2","Partition":0,"Replica":2}]`  
Nginx.ClientMaxBodySize | The maximum request size for Nginx in MB | `200`  
Nginx.ConfigTemplate | The template to generate nginx config. Please use `@filepath` to parse template from file. Check the default template first at <https://docs.tigergraph.com.(Warning>: Don’t modify the reserved keywords(string like **UPPER_CASE**) in template.) | `worker_processes _WORKER_PROCESSES_;\ndaemon off;\npid  _NGINX_PID_PATH_;\n\nevents {\n worker_connections 10240;\n}\n\nhttp {\n\n  server_tokens off;\n\n  map $request_uri $request_uri_path {\n    \~(?P\u003cpath\u003e[?]**)(\\?.**)?$\" $path;\n  }\n\n log_format combined_no_query '$remote_addr - $remote_user [$time_local] '\n      '\"$request_method $request_uri_path $server_protocol\" $status $body_bytes_sent '\n      '\"$http_referer\" \"$http_user_agent\"';\n\n\t#Set allowed CIDR blocks\n_CIDR_LIST_\n  types {\n    text/html                    html htm shtml;\n    text/css                     css;\n    text/xml                     xml;\n    image/gif                    gif;\n    image/jpeg                    jpeg jpg;\n    application/javascript              js;\n    application/atom+xml               atom;\n    application/rss+xml               rss;\n\n    text/mathml                   mml;\n    text/plain                    txt;\n    text/vnd.sun.j2me.app-descriptor         jad;\n    text/vnd.wap.wml                 wml;\n    text/x-component                 htc;\n\n    image/png                    png;\n    image/svg+xml                  svg svgz;\n    image/tiff                    tif tiff;\n    image/vnd.wap.wbmp                wbmp;\n    image/webp                    webp;\n    image/x-icon                   ico;\n    image/x-jng                   jng;\n    image/x-ms-bmp                  bmp;\n\n    font/woff                    woff;\n    font/woff2                    woff2;\n\n    application/java-archive             jar war ear;\n    application/json                 json;\n    application/mac-binhex40             hqx;\n    application/msword                doc;\n    application/pdf                 pdf;\n    application/postscript              ps eps ai;\n    application/rtf                 rtf;\n    application/vnd.apple.mpegurl          m3u8;\n    application/vnd.google-earth.kml+xml       kml;\n    application/vnd.google-earth.kmz         kmz;\n    application/vnd.ms-excel             xls;\n    application/vnd.ms-fontobject          eot;\n    application/vnd.ms-powerpoint          ppt;\n    application/vnd.oasis.opendocument.graphics   odg;\n    application/vnd.oasis.opendocument.presentation odp;\n    application/vnd.oasis.opendocument.spreadsheet  ods;\n    application/vnd.oasis.opendocument.text     odt;\n    application/vnd.openxmlformats-officedocument.presentationml.presentation\n                             pptx;\n    application/vnd.openxmlformats-officedocument.spreadsheetml.sheet\n                             xlsx;\n    application/vnd.openxmlformats-officedocument.wordprocessingml.document\n                             docx;\n    application/vnd.wap.wmlc             wmlc;\n    application/x-7z-compressed           7z;\n    application/x-cocoa               cco;\n    application/x-java-archive-diff         jardiff;\n    application/x-java-jnlp-file           jnlp;\n    application/x-makeself              run;\n    application/x-perl                pl pm;\n    application/x-pilot               prc pdb;\n    application/x-rar-compressed           rar;\n    application/x-redhat-package-manager       rpm;\n    application/x-sea                sea;\n    application/x-shockwave-flash          swf;\n    application/x-stuffit              sit;\n    application/x-tcl                tcl tk;\n    application/x-x509-ca-cert            der pem crt;\n    application/x-xpinstall             xpi;\n    application/xhtml+xml              xhtml;\n    application/xspf+xml               xspf;\n    application/zip                 zip;\n\n    application/octet-stream             bin exe dll;\n    application/octet-stream             deb;\n    application/octet-stream             dmg;\n    application/octet-stream             iso img;\n    application/octet-stream             msi msp msm;\n\n    audio/midi                    mid midi kar;\n    audio/mpeg                    mp3;\n    audio/ogg                    ogg;\n    audio/x-m4a                   m4a;\n    audio/x-realaudio                ra;\n\n    video/3gpp                    3gpp 3gp;\n    video/mp2t                    ts;\n    video/mp4                    mp4;\n    video/mpeg                    mpeg mpg;\n    video/quicktime                 mov;\n    video/webm                    webm;\n    video/x-flv                   flv;\n    video/x-m4v                   m4v;\n    video/x-mng                   mng;\n    video/x-ms-asf                  asx asf;\n    video/x-ms-wmv                  wmv;\n    video/x-msvideo                 avi;\n  }\n  default_type application/octet-stream;\n  client_max_body_size _MAX_BODY_SIZE_;\n\n  access_log _NGINX_LOG_PER_RESTPP_ combined_no_query;\n  error_log _NGINX_ERR_PER_RESTPP_;\n  fastcgi_temp_path _TEMP_ROOT_;\n  fastcgi_buffers 256 8k;\n\n   [BEGIN] customized headers \n  _HEADER_CONFIG_\n   [END] customized headers \n\n\n  keepalive_timeout 900s;\n\n  upstream fastcgi_backend {\n   server unix:_FASTCGI_PASS_;\n   keepalive 128;\n  }\n\n  # Use upstream derivative for listing all gsql server \n  # that could be used in requesttoken proxy_pass\n  _ENABLE_RESTPP_AUTH_ upstream gsql_token_server {\n  _ENABLE_RESTPP_AUTH_ _GSQL_TOKEN_SERVER_LIST_\n  _ENABLE_RESTPP_AUTH_ }\n\n  # Use upstream derivative to list all informant server\n  upstream informant_server {\n   _INFORMANT_SERVER_LIST_\n  }\n\n  upstream gsql_server {\n   server localhost:_GSQL_SERVER_PORT_ max_fails=10;\n  }\n\n  # Keep it for backward compatibility\n  server {\n    add_header Strict-Transport-Security \"max-age=63072000; includeSubdomains; preload\";\n    ssl_protocols TLSv1.2;\n    ssl_ciphers ECDHE-ECDSA-AES128-GCM-SHA256:ECDHE-RSA-AES128-GCM-SHA256:ECDHE-ECDSA-AES256-GCM-SHA384:ECDHE-RSA-AES256-GCM-SHA384:ECDHE-ECDSA-CHACHA20-POLY1305:ECDHE-RSA-CHACHA20-POLY1305:DHE-RSA-AES128-GCM-SHA256:DHE-RSA-AES256-GCM-SHA384;\n    ssl_prefer_server_ciphers on;\n    listen    _PORT_PER_RESTPP_ _GUI_CONNECTION_TYPE_;\n    server_name localhost;\n    large_client_header_buffers _LARGE_CLIENT_HEADER_BUFFER_NUM_ _LARGE_CLIENT_HEADER_BUFFER_SIZE_;\n\n    fastcgi_read_timeout 72000s;\n    fastcgi_send_timeout 72000s;\n\n    _SSL_CERT_ATTR_ _SSL_CERT_PATH_; # if SSL is disabled, here should be ''\n    _SSL_KEY_ATTR_ _SSL_KEY_PATH_; # if SSL is disabled, here should be ''\n\n\n    location / {\n      fastcgi_pass fastcgi_backend;\n      fastcgi_keep_conn on;\n      fastcgi_param REQUEST_METHOD $request_method;\n      fastcgi_param CONTENT_TYPE  $content_type;\n      fastcgi_param CONTENT_LENGTH $content_length;\n      fastcgi_param REQUEST_URI   $request_uri;\n      fastcgi_param GSQL_ASYNC   $http_gsql_async;\n      fastcgi_param GSQL_TIMEOUT  $http_gsql_timeout;\n      fastcgi_param GSQL_MEMLIMIT  $http_gsql_memlimit;\n      fastcgi_param RESPONSE_LIMIT $http_response_limit;\n    }\n\n    # To ensure the performance of RESTPP, this rule shouldn’t be enabled\n    # unless restpp.authentication is True.\n    # And for performance consideration,\n    !!!!!!!  DO NOT USE REGULAR EXPRESSION HERE !!!!!!!\n    _ENABLE_RESTPP_AUTH_ location = /requesttoken {\n    _ENABLE_RESTPP_AUTH_   proxy_ssl_verify _PROXY_SSL_VERIFY_;\n    _ENABLE_RESTPP_AUTH_   proxy_set_header X-Real-IP $remote_addr;\n    _ENABLE_RESTPP_AUTH_   proxy_pass _REQUEST_TOKEN_PROTOCOL_://gsql_token_server;\n    _ENABLE_RESTPP_AUTH_ }\n  }\n\n  server {\n\t\tlisten _NGINX_SERVICES_PORT_ _GUI_CONNECTION_TYPE_;\n  ssl_protocols TLSv1.2;\n\t\tlarge_client_header_buffers _LARGE_CLIENT_HEADER_BUFFER_NUM_ _LARGE_CLIENT_HEADER_BUFFER_SIZE_;\n\t\tproxy_buffer_size _PROXY_BUFFER_SIZE_;\n\t\tproxy_buffers _PROXY_BUFFERS_NUM_ _PROXY_BUFFERS_SIZE_;\n\t\tproxy_busy_buffers_size _PROXY_BUSY_BUFFERS_SIZE_;\n\n\t\t_SSL_CERT_ATTR_ _SSL_CERT_PATH_; # if SSL is disabled, here should be ''\n\t\t_SSL_KEY_ATTR_ _SSL_KEY_PATH_; # if SSL is disabled, here should be ''\n\n\t\tlocation / {\n\t\t\t Set whether to enable compression\n\t\t\tgzip on;\n\t\t\tgzip_types\n\t\t\t\tapplication/javascript # works significantly with javascript files in GUI\n\t\t\t;\n\t\t\troot _TOOLS_STATIC_FOLDER_;\n\t\t\ttry_files $uri $uri/ @backend;\n\t\t}\n\n\t\tlocation /assets/img/user-uploaded-icons/ {\n\t\t\talias _GUI_DATA_FOLDER_/user_icons/;\n\t\t\ttry_files $uri $uri/ = 404;\n\t\t}\n\n  location /gsql/ {\n\t\t\t# Set whether to enable compression\n\t\t\tgzip on;\n\t\t\tgzip_types\n\t\t\t\tapplication/javascript # works significantly with javascript files in GUI\n\t\t\t;\n\t\t\talias _GSHELL_STATIC_FOLDER_/;\n\t\t\ttry_files $uri $uri/ = 404;\n\t\t}\n\n  location = /gsql {\n\t\t\trewrite /gsql /gsql/ last;\n\t\t}\n\n  location ^~/insights/ {\n\t\t\t# Set whether to enable compression\n\t\t\tgzip on;\n\t\t\tgzip_types\n\t\t\t\tapplication/javascript # works significantly with javascript files in GUI\n\t\t\t;\n\t\t\talias _INSIGHTS_STATIC_FOLDER_/;\n\t\t\ttry_files $uri $uri/ /insights/index.html;\n\t\t}\n\n  location = /insights {\n\t\t\trewrite /insights /insights/ last;\n\t\t}\n\n  location /graphql/ {\n\t\t\t# Set whether to enable compression\n\t\t\tgzip on;\n\t\t\tgzip_types\n\t\t\t\tapplication/javascript # works significantly with javascript files in GUI\n\t\t\t;\n\t\t\talias _GRAPHQL_STATIC_FOLDER_/;\n\t\t\ttry_files $uri $uri/ = 404;\n\t\t}\n\n  location = /graphql {\n\t\t\trewrite /graphql /graphql/ last;\n\t\t}\n\n  location /studio/ {\n\t\t\t# Set whether to enable compression\n\t\t\tgzip on;\n\t\t\tgzip_types\n\t\t\t\tapplication/javascript # works significantly with javascript files in GUI\n\t\t\t;\n\t\t\talias _GST_STATIC_FOLDER_/;\n\t\t\ttry_files $uri $uri/ = 404;\n\t\t}\n\n  location = /studio {\n\t\t\trewrite /studio /studio/ last;\n\t\t}\n\n\t\tlocation /admin/ {\n\t\t\t# Set whether to enable compression\n\t\t\tgzip on;\n\t\t\tgzip_types\n\t\t\t\tapplication/javascript # works significantly with javascript files in GUI\n\t\t\t;\n\t\t\talias _ADMIN_PORTAL_STATIC_FOLDER_/;\n\t\t\ttry_files $uri $uri/ = 404;\n\t\t}\n\n  location = /admin {\n\t\t\trewrite /admin /admin/ last;\n\t\t}\n\n\t\tlocation @backend {\n\t\t\tproxy_read_timeout 604800s;\n\t\t\tproxy_set_header X-Real-IP $remote_addr;\n\t\t\tproxy_pass http://localhost[](http://localhost):_GUI_WEBSERVER_PORT_;\n\t\t}\n\n\t\tlocation ~ ^/informant/(?\u003cinformant_uri\u003e.**) {\n   \t\t\trewrite ^/informant/(.**) /$informant_uri break;\n   \t\t\tproxy_read_timeout 3600s;\n   \t\t\tproxy_set_header X-Real-IP $remote_addr;\n   \t\t\tproxy_pass http://informant_server;\n[](http://informant_server;\\n)  \t\t}\n\n\t\tlocation ~ ^/gsqlserver/(?\u003cgsql_uri\u003e.**) {\t\n\t\t\trewrite ^/gsqlserver/(.**) /$gsql_uri break;\n\t\t\tproxy_read_timeout 604800s;\n\t\t\tproxy_set_header X-Real-IP $remote_addr;\n\t\t\tproxy_pass http://gsql_server;\n\t\t\tproxy_http_version[](http://gsql_server;\\n\\t\\t\\tproxy_http_version) 1.1;\n\t\t\tproxy_buffering off;\n\t\t}\n\n\t\t# This RESTPP endpoint shares the same security configuration\n\t\tfastcgi_read_timeout 72000s;\n\t\tfastcgi_send_timeout 72000s;\n\n\t\t_ENABLE_RESTPP_AUTH_ location ~ ^/restpp/(?\u003ctoken_uri\u003erequesttoken.**) {\n\t\t_ENABLE_RESTPP_AUTH_   rewrite ^/restpp/(.**) /$token_uri break;\n\t\t_ENABLE_RESTPP_AUTH_   proxy_ssl_verify _PROXY_SSL_VERIFY_;\n\t\t_ENABLE_RESTPP_AUTH_   proxy_set_header X-Real-IP $remote_addr;\n\t\t_ENABLE_RESTPP_AUTH_   proxy_pass _REQUEST_TOKEN_PROTOCOL_://gsql_token_server;\n\t\t_ENABLE_RESTPP_AUTH_ }\n\n\t\tlocation ~ ^/restpp/(.*) {\n\t\t\tfastcgi_pass fastcgi_backend;\n\t\t\tfastcgi_keep_conn on;\n\t\t\tfastcgi_param REQUEST_METHOD $request_method;\n\t\t\tfastcgi_param CONTENT_TYPE  $content_type;\n\t\t\tfastcgi_param CONTENT_LENGTH $content_length;\n\t\t\tfastcgi_param REQUEST_URI   $1?$query_string; # the url pattern matched above\n\t\t\tfastcgi_param GSQL_TIMEOUT  $http_gsql_timeout;\n\t\t\tfastcgi_param GSQL_MEMLIMIT  $http_gsql_memlimit;\n   fastcgi_param GSQL_ASYNC   $http_gsql_async;\n\t\t\tfastcgi_param RESPONSE_LIMIT $http_response_limit;\t      \n\t\t}\n\t}\n}\n"`  
Nginx.Port | The serving port for Nginx | `14240`  
Nginx.ResponseHeaders | The customized headers in HTTP Response | `[{"FieldName":"X-Frame-Options","FieldValue":"SAMEORIGIN"}]`  
Nginx.SSL.Cert | Public certificate for SSL. (Could use @cert_file_path to parse the certificate from file) | `nan`  
Nginx.SSL.Enable | Enable SSL connection for all HTTP requests | `false`  
Nginx.SSL.Key | Private key for SSL. (Could use @key_file_path to parse the key from file) | `nan`  
Nginx.WorkerProcessNumber | The number of worker processes for Nginx | `4`  
## [](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_restpp)RESTPP
Name | Description | Example  
---|---|---  
RESTPP.BasicConfig.Env | A list of `<environment variable>=<value>` pairs, separated by `;` | `LD_PRELOAD=$LD_PRELOAD; LD_LIBRARY_PATH=$LD_LIBRARY_PATH; REPORT_FIRST_N_LINES=$REPORT_FIRST_N_LINES`  
RESTPP.AsyncQuery.ResultFileMaxDurationDay | The maximum number of days to retain asynchronous query result files. The default is 2. | `3`  
RESTPP.AsyncQuery.CleanIntervalHour | Interval in hours between executions of the thread to clean out asynchronous query result files older than `MaxDurationDay`. The default is 24. | `12`  
RESTPP.BasicConfig.LogConfig.LogFileMaxDurationDay | The maximum number of days to retain old log files based on the timestamp encoded in their filename | `90`  
RESTPP.BasicConfig.LogConfig.LogFileMaxSizeMB | The maximum size in megabytes of the log file before it gets rotated | `100`  
RESTPP.BasicConfig.LogConfig.LogLevel | The log level(`OFF`, `BRIEF`, `DEBUG`, `VERBOSE`), default is `BRIEF` | `BRIEF`  
RESTPP.BasicConfig.LogConfig.LogRotationFileNumber | The maximum number of old log files to retain | `100`  
RESTPP.BasicConfig.LogDirRelativePath | The relative path (to the System.LogRoot) of log directory for RESTPP | `restpp`  
RESTPP.BasicConfig.Nodes | The node list for RESTPP | `[{"HostID":"m1","Partition":0,"Replica":1},{"HostID":"m2","Partition":0,"Replica":2}]`  
RESTPP.FCGISocketBackLogMaxCnt | RESTPP fcgi socket backlog max length which is the listen queue depth used in the listen() call. | `36864`  
RESTPP.FCGISocketFileRelativePath | The relative path of FCGI socket for RESTPP-Nginx communitation under $TempRoot | `rest/restpp-nginx.fcgi.sock`  
RESTPP.Factory.DefaultLoadingTimeoutSec | The default per request loading timeout (s) for RESTPP | `600`  
RESTPP.Factory.DefaultQueryTimeoutSec | The default query timeout (s) for RESTPP | `16`  
RESTPP.Factory.DynamicEndpointRelativePath | RESTPP’s relative (to data root) path to store the dynamic endpoint | `restpp/endpoint/`  
RESTPP.Factory.DynamicSchedulerRelativePath | RESTPP’s relative (to data root) path to store the dynamic scheduler | `restpp/scheduler/`  
RESTPP.Factory.EnableAuth | Enable authentication of RESTPP | `false`  
RESTPP.Factory.HandlerCount | RESTPP’s handler count | `4`  
RESTPP.Factory.QueryMemoryLimitMB | The memory limit of query runs for container on disk. The default value is -1, meaning no limit | `-1`  
RESTPP.Factory.StatsIntervalSec | RESTPP’s time interval to collect stats (e.g. QPS) | `60`  
RESTPP.GPEResponsePort | The port of RESTPP to accept GPE response | `5400`  
RESTPP.GSEResponsePort | The port of RESTPP to accept GSE response | `5500`  
RESTPP.HttpServer.Enable | Enable RESTPP’s http server | `false`  
RESTPP.HttpServer.Port | RESTPP’s http server port | `10000`  
RESTPP.HttpServer.WorkerNum | RESTPP’s http server worker number | `2`  
RESTPP.LoadedOffsetTraceBackHr | The trace back time (hour) of loaded offset, offsets will not be reported beyond the specified time | `24`  
RESTPP.NginxPort | The port of RESTPP to accept upstream Nginx requests | `9000`  
RESTPP.WorkLoadManager.MaxHeavyBuiltinQueries | The maximum number of concurrent “heavy“ built-in queries (kstep_expansion, searchvertex, allpaths, shortestpath) on a restpp server | `100`  
RESTPP.WorkLoadManager.MaxConcurrentQueries | The maximum number of concurrent queries allowed to run, **excluding** heavy queries | `50`  
RESTPP.WorkLoadManager.MaxDelayQueueSize | The maximum number of concurrent queries in the delay queue | `20`  
RESTPP.QueryRouting.Mode | Set the query routing mode (0=RoundRobin, 1=CPULoadAware) | `0`  
RESTPP.QueryRouting.TargetSelectionCPUThreshold | Set the query routing mode CPU usage threshold | `50`  
## [](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_security)Security
Name | Description | Example  
---|---|---  
Security.JWT.RSA.PublicKey | Configure a RSA public key for [OIDC JWT Authentication](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/jwt-token). | `gadmin config set Security.JWT.RSA.PublicKey <public-key content or URL or @filepath>`  
Security.JWT.HMAC.Secret | Configure a HMAC Secret for [OIDC JWT Authentication](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/jwt-token). | `gadmin config set Security.JWT.HMAC.Secret <shared-secret-key content or URL or @filepath>`  
Security.JWT.Issuer | Configure the `iss` claim that will be verified against this configured value for [OIDC JWT Authentication](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/jwt-token). | `gadmin config set Security.JWT.Issuer "<issuer-name>"`  
Security.JWT.Audience | Configure this JWT Token authentication to verify if the `aud` (recipient for which the JWT is intended) defined in the JWT Token matches the configured one or not for [OIDC JWT Authentication](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/jwt-token). | `gadmin config set Security.JWT.Audience "<audience-name>"`  
Security.LDAP.AdminDN | Configure the DN of LDAP user who has read access to the base DN specified above. Empty if everyone has read access to LDAP data: default empty | `nan`  
Security.LDAP.AdminPassword | Configure the password of the admin DN specified above. Needed only when admin_dn is specified: default empty | `secret`  
Security.LDAP.BaseDN | Configure LDAP search base DN, the root node to start the LDAP search for user authentication: must specify | `nan`  
Security.LDAP.Enable | Enable LDAP authentication: default false | `false`  
Security.LDAP.GroupFilter | list of group objects on LDAP server used to retrieve group hierarchy information, default value: (objectClass=group) | (objectClass=group)  
Security.LDAP.GroupHierarchyRefreshIntervalMin | Refresh time in minutes of ldap group hierarchy information. default 240 | 60  
Security.LDAP.Hostname | Configure LDAP server hostname: default localhost | `localhost`  
Security.LDAP.Port | Configure LDAP server port: default 389 | `389`  
Security.LDAP.SearchFilter | Configure LDAP search base DN, the root node to start the LDAP search for user authentication. | `(objectClass=*)`  
Security.LDAP.Secure.Protocol | Enable SSL/StartTLS for LDAP connection [none/ssl/starttls]: default none | `none`  
Security.LDAP.Secure.TrustAll | Configure to trust all LDAP servers (unsafe): default false | `false`  
Security.LDAP.Secure.TruststoreFormat | Configure the truststore format [JKS/PKCS12]: default JKS | `JKS`  
Security.LDAP.Secure.TruststorePassword | Configure the truststore password: default changeit | `changeit`  
Security.LDAP.Secure.TruststorePath | Configure the truststore absolute path for the certificates used in SSL: default empty | `nan`  
Security.LDAP.UsernameAttribute | Configure the username attribute name in LDAP server: default uid | `uid`  
Security.SSO.OIDC.OP.AccessTokenURL | The API to request access token from OP. Required for OIDC code flow, not needed for implicit flow. Type: `STRING` | `https://op.example.com/oauth/token[](https://op.example.com/oauth/token)`  
Security.SSO.OIDC.BuiltinUser | The builtin user for OIDC, default: _GSQL_ oidc | `_GSQL_oidc`  
Security.SSO.OIDC.CallBackUrl | TigerGraph service provider callback URL: default <http://127.0.0.1:14240> | `http://127.0.0.1:14240[](http://127.0.0.1:14240)`  
Security.SSO.OIDC.ClaimAsUserID | The OIDC claim which will be used as username in TigerGraph Type: `STRING` | `email`  
Security.SSO.OIDC.Enable | Enable OIDC based SSO [true/false]: default false | `false`  
Security.SSO.OIDC.OP.ClientId | The client id assigned by Openid Provider when registers TigerGraph | `nan`  
Security.SSO.OIDC.OP.ClientSecret | The client secret generated by OIDC provider, this config is only needed if algorithm is HMAC type | `nan`  
Security.SSO.OIDC.OP.JWKSUrl | The url of the OpenID provider to retrieve the public JSON web key set, e.g. https://op.example.com/.well-known/jwks.json. It is only needed if algorithm is RSA type | `https://op.example.com/.well-known/jwks.json[](https://op.example.com/.well-known/jwks.json)`  
Security.SSO.OIDC.OP.Issuer | Required, not needed for TG-Cloud. Entity that issues a set of claims. Type: `STRING` | <https://example.issuer.tigergraph.com>.  
Security.SSO.OIDC.OP.SSOUrl | Single Sign-On URL: default <https://op.example.com/oauth/authorize> | `https://op.example.com/oauth/authorize[](https://op.example.com/oauth/authorize)`  
Security.SSO.OIDC.OP.SigAlgorithm | Define the algorithm that OIDC provider used to sign the ID token, [RS256/HS256/…]: default RS256 | `RS256`  
Security.SSO.OIDC.OrganizationId | The organization ID for cloud OpenId server | `nan`  
Security.SSO.OIDC.ResponseType | Define the kind of credential that OIDC provider will return [code/token/id_token/code id_token/…]: default code | `code`  
Security.SSO.OIDC.Scope | Specifies the claims (or user attributes) to retrieve, separated by a space [openid email/openid profile/…]: default openid profile (means user’s full profile). | `openid profile`  
Security.SSO.OIDC.OP.UserInfoURL | Required for OIDC code flow, not needed for implicit flow. The API to request user information via an access token. Type: `STRING` | `https://op.example.com/userinfo[](https://op.example.com/userinfo)`  
Security.SSO.SAML.AssertionSigned | Require Identity Provider to sign assertions: default true | `true`  
Security.SSO.SAML.AuthnRequestSigned | Sign AuthnRequests before sending to Identity Provider: default true | `true`  
Security.SSO.SAML.BuiltinUser | The builtin user for SAML | `_GSQL_saml`  
Security.SSO.SAML.Enable | Enable SAML2-based SSO: default false | `false`  
Security.SSO.SAML.IDP.EntityId | Identity Provider Entity ID: default <http://idp.example.com> | `http://idp.example.com[](http://idp.example.com)`  
Security.SSO.SAML.IDP.SSOUrl | Single Sign-On URL: default <http://idp.example.com/sso/saml> | `http://idp.example.com/sso/saml[](http://idp.example.com/sso/saml)`  
Security.SSO.SAML.IDP.X509Cert | Identity Provider’s x509 Certificate filepath: default empty. You can use @/cert/file/path to pass the certificate from a file. | `nan`  
Security.SSO.SAML.MetadataSigned | Sign Metadata: default true | `true`  
Security.SSO.SAML.RequestedAuthnContext | Authentication context (comma separate multiple values) | `nan`  
Security.SSO.SAML.ResponseSigned | Require Identity Provider to sign SAML responses: default true | `true`  
Security.SSO.SAML.SP.Hostname | TigerGraph Service Provider URL: default <http://127.0.0.1:14240> | `http://127.0.0.1:14240[](http://127.0.0.1:14240)`  
Security.SSO.SAML.SP.PrivateKey | Content of the host machine’s RSA private key. You can use @/privatekey/file/path to pass the certificate from a file. | `nan`  
Security.SSO.SAML.SP.X509Cert | Content of the x509 Certificate: default empty. You can use @/cert/file/path to pass the certificate from a file. | `nan`  
Security.SSO.SAML.SignatureAlgorithm | Signiture algorithm [rsa-sha1/rsa-sha256/rsa-sha384/rsa-sha512]: default rsa-sha256 | `rsa-sha256`  
## [](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_system)System
Name | Description | Example  
---|---|---  
System.AppRoot | The root directory for TigerGraph applications | `/home/tigergraph/tigergraph/app`  
System.Audit.Enable | Setting to enable audit logs. | `System.Audit.Enable true`  
System.Audit.DatabaseName | Modify the DataBaseName field in log file header. | `System.Audit.DataBaseName <database-name>`  
System.Audit.LogDirRelativePath | Modify the relative audit log path. | `System.Audit.LogDirRelativePath <audit-log-relative-path>`  
System.Audit.LogConfig.LogFileMaxDurationDay | Modify the audit log file’s modification date. | `System.Audit.LogConfig.LogFileMaxDurationDay <max-duration-day>`  
System.Audit.LogConfig.LogFileMaxSizeMB | Modify the audit log file’s max size. | `System.Audit.LogConfig.LogFileMaxSizeMB <file-size>`  
System.Audit.LogConfig.LogRotationFileNumber | Modify the max amount of Audit Log files in the Audit Log folder. | `System.Audit.LogConfig.LogRotationFileNumber <file-number>`  
System.Audit.MaskPII | Mask Sensitive data or PII in the audit log. Default value is: `true`. If it is `false`, the PII data will not be masked. | `System.Audit.MaskPII true`  
System.AuthToken | The authorization token for TigerGraph services | `Va2V7mdpTY5ErZRmTBBRqYtkgR7CiGbF`  
System.Backup.CompressProcessNumber | The number of concurrent process for compression during backup. Value `0` means the number of processes used to compress equals the node CPU’s cores. | `0`  
System.Backup.DecompressProcessNumber | The number of concurrent processes for decompression during the restore. | `8`  
System.Backup.CompressionLevel | The backup compression level strikes a balance between size and speed. The better compression, the longer it takes. ("BestSpeed", "DefaultCompression", "BestCompression") | "DefaultCompression"  
System.Backup.Local.Enable | Backup data to local path **IMPORTANT** : If set to `true`, this also enables a daily full backup at 12:00am UTC. | `false`  
System.Backup.Local.Path | The path to store the backup files | `nan`  
System.Backup.S3.AWSAccessKeyID | AWS Access Key ID for authentication (deprecated, use System.Backup.S3.AccessKeyID instead, which has a higher priority.) | `nan`  
System.Backup.S3.AWSSecretAccessKey | AWS Secret Access Key for authentication (deprecated, use System.Backup.S3.SecretAccessKey instead, which has a higher priority.) | `nan`  
System.Backup.S3.AccessKeyID | Access key ID for authentication for AWS S3 or S3-compatible services. | `nan`  
System.Backup.S3.SecretAccessKey | Secret Access Key for authentication for AWS S3 or S3-compatible services. | `nan`  
System.Backup.S3.RoleARN | The AWS role for accessing s3 buckets. S3 Role ARN takes priority over access keys. For more information, see [AWS role ARN documentation](https://docs.aws.amazon.com/IAM/latest/APIReference/API_Role.html). **NOTE** : This is only for AWS S3, and TigerGraph assumes the credentials for using `sts:AssumeRole` have been set up. You can verify the credentials are ready by running [aws sts assume-role](https://docs.aws.amazon.com/cli/latest/reference/sts/assume-role.html#examples). One way to set up credentials is to configure access key id, secret access key and region with AWS CLI `aws configure`. | `nan`  
System.Backup.S3.BucketName | Bucket for AWS S3 or S3-compatible services. | `nan`  
System.Backup.S3.Enable | Enables or disables backup to AWS S3 or S3-compatible services such as Ceph S3. | `false`  
System.Backup.S3.Endpoint | A URL used to interact with the S3 (AWS S3/S3-compatible) service. It can be used for AWS S3 VPC Endpoint, customer endpoint, or S3-compatible service. For regular AWS S3, leave it empty. | null  
System.Backup.ABS.Enable | Enables or disables backup to ABS (Azure Blob Storage). | `false`  
System.Backup.ABS.ContainerName | Azure storage account container | `nan`  
System.Backup.ABS.AccountName | Azure storage account name for authentication. | `nan`  
System.Backup.ABS.AccountKey | Account key for the Azure storage account. | `nan`  
System.Backup.ABS.Endpoint | Optional Blob service endpoint; if not given, the default endpoint [https://<account-name>.blob.core.windows.net](https://<account-name>.blob.core.windows.net) will be used. | `nan`  
System.Backup.GCS.Enable | Enables or disables backup to Google Cloud Storage (GCS). | `false`  
System.Backup.GCS.BucketName | GCS bucket. | `nan`  
System.Backup.GCS.AccessKeyID | Access Key for a GCS HMAC Key. | `nan`  
System.Backup.GCS.Secret | Secret for a GCS HMAC Key. | `nan`  
System.Backup.GCS.Endpoint | GCS Storage URI. | `https://storage.googleapis.com[](https://storage.googleapis.com)`  
System.Backup.TimeoutSec | The backup timeout in seconds | `18000`  
System.CrossRegionReplication.Enabled | Enable Kafka Mirrormaker | `false`  
System.CrossRegionReplication.PrimaryKafkaIPs | Kafka mirrormaker primary cluster’s IPs, separator by `,' | `nan`  
System.CrossRegionReplication.PrimaryKafkaPort | Kafka mirrormaker primary cluster’s KafkaPort | `30002`  
System.CrossRegionReplication.TopicPrefix | The prefix of GPE/GUI/GSQL Kafka Topic, by default is empty. For details of what it does and how it is used, please refer to [Set Up Cross-Region Replication](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/set-up-crr). | `nan`  
System.DataRoot | The root directory for data | `/home/tigergraph/tigergraph/data`  
System.Event.EventInputTopic | Kafka topic name of event input queue | `EventInputQueue`  
System.Event.EventOffsetFolderRelativePath | The relative path (to the System.DataRoot) of the folder to keep track of Kafka offsets for event input/output queue | `offset`  
System.Event.EventOutputTopic | Kafka topic name of event output queue | `EventOutputQueue`  
System.Event.MetricsTopic | Kafka topic name of metrics event queue | `MetricsQueue`  
System.HostList | The aliases and hostnames/IPs for nodes | `[{"ID":"m1","Hostname":"192.168.1.1","Region":"r1"},{"ID":"m2","Hostname":"192.168.1.2","Region":"r2"}]`  
System.License | The license key for TigerGraph system | `nan`  
System.LogRoot | The root directory for TigerGraph logs | `/home/tigergraph/tigergraph/log`  
System.Metrics.CPUIntervalSec | The CPU metric data collect interval (s) | `60`  
System.Metrics.DiskspaceIntervalSec | The diskspace metric data collect interval (s) | `300`  
System.Metrics.MemoryIntervalSec | The memory metric data collect interval (s) | `60`  
System.Metrics.NetworkIntervalSec | The network metric data collect interval (s) | `60`  
System.Metrics.QPSIntervalSec | The QPS metric data collect interval (s) | `60`  
System.Metrics.IncludeHostName | If set to true, the hostname/ip will be included in all metrics output, in OpenMetrics format, as part of the variable labels. Otherwise, the default is `false` and the response will not include hostname/ip as part of the variable labels. As in the example [Monitor system metrics (OpenMetrics format)](https://docs.tigergraph.com/tigergraph-server/4.2/API/built-in-endpoints#_monitor_system_metrics_openmetrics_format) | `System.Metrics.IncludeHostName true`  
System.SSH.ConfigFileRelativePath | The relative path (to the System.DataRoot) of SSH config file | `ssh/ssh_config`  
System.SSH.Port | SSH port | `22`  
System.SSH.User.Password | OS User password (optional if using privatekey) | `tigergraph`  
System.SSH.User.Privatekey | OS user private key path | `nan`  
System.SSH.User.Username | OS Username for TigerGraph database | `tigergraph`  
System.TempRoot | The temporary directory for TigerGraph applications | `/home/tigergraph/tigergraph/tmp`  
## [](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_zk)ZK
Name | Description | Example  
---|---|---  
ZK.BasicConfig.Env | A list of `<environment variable>=<value>` pairs, separated by `;` | `ZK_SERVER_HEAP=4096;`  
ZK.BasicConfig.LogConfig.LogFileMaxSizeMB | The maximum size in megabytes of the log file before it gets rotated | `100`  
ZK.BasicConfig.LogConfig.LogLevel | The log level for zk (`TRACE`, `DEBUG`, `INFO`, `WARN`, `ERROR`, `FATAL`, `OFF`) | `INFO`  
ZK.BasicConfig.LogConfig.LogRotationFileNumber | The maximum number of old log files to retain | `100`  
ZK.BasicConfig.LogDirRelativePath | The relative path (to the System.LogRoot) of log directory for ZK | `zk`  
ZK.BasicConfig.Nodes | The node list for Zookeeper | `[{"HostID":"m1","Partition":0,"Replica":1},{"HostID":"m2","Partition":0,"Replica":2}]`  
ZK.DataRelativePath | The data dir of zookeeper under $DataRoot | `zk`  
ZK.ElectionPort | The port for Zookeeper to do leader election | `3888`  
ZK.ForceSync | The force synchronize property of zookeeper | `false`  
ZK.InitLimit | The amount of time, in ticks(by default 2s for one tick), to allow followers to connect and sync to a leader. Increased this value as needed, if the amount of data managed by ZooKeeper is large | `30`  
ZK.Port | The serving port for Zookeeper | `19999`  
ZK.QuorumPort | The port for Zookeeper to do peer communication | `2888`  
ZK.StartTimeoutMS | Start zookeeper timeout | `120000`  
## [](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_environment_variables)Environment Variables
An environment variable is set using its `xxx.Basic.ConfigEnv` configuration parameter, where `xxx` is the name of its associated component.
If you use `gadmin config set GPE.BasicConfig.Env` or `gadmin config entry GPE.BasicConfig.Env`, users will be able to add entries for GPE runtime environment variables.
Component | Name | Description | Example  
---|---|---|---  
GSQL | `GPE_DSC_APPLY_TIMEOUT_MINUTE`, GSQL.Basic.ConfigEnv | [v3.9.2+] Timeout (minutes) for dynamic schema change. Default = 30 | 30  
RESPP | `SSL_CA_CERT`, RESETPP.BasicConfig.Env | Set the CA certificate `SSL_CA_CERT` to establish the connection with the URL being set with [OIDC JWT Authentication](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/jwt-token). | `SSL_CA_CERT=/home/tigergraph/cacertificate/example/;`  
GPE | `SegmentMetaFlushAlways`, GPE.BasicConfig.Env | 
  * If this entry is added with value `true`, TigerGraph will refresh on-disk segment meta for all segments without data updates during re-builder scheduling. Default is set to `false`.
  * Setting this flag can ensure the most aggressive refresh logic, which can benefit Kafka retention and lower the disk usage most promptly. But it can cause slow scheduling in lower `WRITE IO` environment like `EFS`, `S3`, and not release the memory efficiently.

| `SegmentMetaFlushAlways=true`  
`SegmentMetaForceFlushIntervalSec`, GPE.BasicConfig.Env | 
  * This entry is only effective when `SegmentMetaFlushAlways=false`.
  * If a segment has no data update, TigerGraph will still need to refresh the on-disk segment meta files after an interval. Default to 600 sec (10 minutes).
  * Lowering the interval value means a more aggressive refresh logic, which can benefit Kafka retention and lower the disk usage more promptly. But can cause slow scheduling in lower WRITE IO environment like EFS, S3, and memory not released efficiently.

| `SegmentMetaForceFlushIntervalSec=600`  
`CDCKafkaFlushTimeoutMs`, GPE.BasicConfig.Env | 
  * When a GPE service shuts down, CDC will try to flush all generated cdc messages to external kafka.
  * When set to -1, there is an infinite timeout, which may slow the GPE shutdown.

| `CDCKafkaFlushTimeoutMs=-1`  
`CDCDeltaBufferCapInMB`, GPE.BasicConfig.Env | In-memory buffer limit for delta message in CDC service. | `CDCDeltaBufferCapInMB=10`  
`DIMDeltaBufferCapInMB`, GPE.BasicConfig.Env | In-memory buffer limit for “vertex-deletion“ delta message in deleted id map service. | `DIMDeltaBufferCapInMB=100`  
`DIMCacheLimitInMB`, GPE.BasicConfig.Env | In-memory cache limit for deleted id map. | `DIMCacheLimitInMB=1024`  
`DIMPurgeIntervalInMin`, GPE.BasicConfig.Env | Interval for purging outdated entries in deleted id map. | `DIMPurgeIntervalInMin=30`  
`TransactionStoreMemLimit`, GPE.BasicConfig.Env | The value must be uint64_t type and in unit: Byte. The default value is 4194304, which means 4 MB. | `TransactionStoreMemLimit=4194304`  
`TransactionSizeLimit`, GPE.BasicConfig.Env | 
  * The value 1073741824 stands for 1GB threshold. The value must be uint64_t type and in uint: Byte.
  * The default value is 0. When the value is 0, the threshold is dynamically decided by TigerGraph, based on current memory usage statistics.

| `TransactionSizeLimit=1073741824`  
`FieldSizeLimit`, GPE.BasicConfig.Env | 
  * Specifies the maximum number of bytes (as an unsigned integer `UINT`) for a single field in a data record
  * The default is 104,857,600 = 100 MB. The maximum is 2^64 -1 = 16 exabytes

| `FieldSizeLimit=20000`  
`ContainerLengthLimit`, GPE.BasicConfig.Env | 
  * Specifies the maximum number of entries allowed in a container
  * The default value is 1,048,576 bytes = 1MB .The maximum is 2^64 -1 = 16 exabytes

| `ContainerLengthLimit=10000`  
GSE | `ServFromDisk`, GSE.BasicConfig.Env | 
  * When set to `1`, vertex ID data remains on disk rather than being loaded into memory. This will help reduce the GSE startup time significantly, with the trade-off of slight slower performance for data loading and query processing. Default = `0`: vertex ID is loaded into memory.
  * GSE will perform a one-time DB format conversion during the first startup after turning this flag on. The conversion time depends on the number of vertices. After the conversion, GSE must then be restarted for the conversion to take effect. NOTE: The built-in endpoints [`/deleted_vertex_check`](https://docs.tigergraph.com/tigergraph-server/4.2/API/built-in-endpoints#_deleted_vertex_check) and [`/data_consistency_check`](https://docs.tigergraph.com/tigergraph-server/4.2/API/built-in-endpoints#_data_consistency_check) are not supported when ServFromDisk = 1, as they require the full scan which can take significant time.

| `ServFromDisk=1`  
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


