![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export)[Next](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export)
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
  * [Manage Your Database](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/)
  * [Backup and Export](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/)
  * Export/Import
  * [Database Import/Export All Graphs](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/4.2/modules/backup-and-restore/pages/database-import-export.adoc)
### Contents
  * [Import Prerequisite](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_import_prerequisite)
  * [Known Issues](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_known_issues)
  * [EXPORT GRAPH ALL](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_export_graph_all)
  * [Required privilege](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_required_privilege)
  * [Synopsis](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_synopsis)
  * [Parameters](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_parameters)
  * [Export All Options](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_export_all_options)
  * [Output](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_output)
  * [Insufficient disk space](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_insufficient_disk_space)
  * [Export timeout](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_export_timeout)
  * [IMPORT GRAPH ALL](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_import_graph_all)
  * [Required privileges](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_required_privileges)
  * [Synopsis](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_synopsis_2)
  * [Parameters](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_parameters_2)
  * [Import All Options](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_import_all_options)
  * [Example](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_example)
  * [Loading Jobs](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_loading_jobs)
  * [Schema Change Jobs](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_schema_change_jobs)
  * [Cluster export/import](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_cluster_importexport)
  * [Export from a cluster](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_export_from_a_cluster)
  * [Import into a cluster](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_import_into_a_cluster)


# Database Import/Export All Graphs
### Contents
  * [Import Prerequisite](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_import_prerequisite)
  * [Known Issues](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_known_issues)
  * [EXPORT GRAPH ALL](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_export_graph_all)
  * [Required privilege](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_required_privilege)
  * [Synopsis](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_synopsis)
  * [Parameters](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_parameters)
  * [Export All Options](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_export_all_options)
  * [Output](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_output)
  * [Insufficient disk space](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_insufficient_disk_space)
  * [Export timeout](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_export_timeout)
  * [IMPORT GRAPH ALL](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_import_graph_all)
  * [Required privileges](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_required_privileges)
  * [Synopsis](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_synopsis_2)
  * [Parameters](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_parameters_2)
  * [Import All Options](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_import_all_options)
  * [Example](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_example)
  * [Loading Jobs](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_loading_jobs)
  * [Schema Change Jobs](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_schema_change_jobs)
  * [Cluster export/import](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_cluster_importexport)
  * [Export from a cluster](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_export_from_a_cluster)
  * [Import into a cluster](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_import_into_a_cluster)


The GSQL `EXPORT GRAPH ALL` and `IMPORT GRAPH ALL` commands perform a logical backup and restore. A database `EXPORT` contains the database’s data, and optionally some types of metadata. This data can be subsequently imported in order to recreate the same database, in the original or in a different TigerGraph platform instance.
To see how to Export/Import selected individual graphs in a database refer to [Import/Export Individual Graphs](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/single-graph-import-export).
Beginning with version 4.1, a full export package now includes access policies and template queries.  
---  
Import/export is a complement to [Backup and Restore](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/), but not a substitute. See the [Known Issues](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_known_issues) for additional considerations.  
---  
## [](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_import_prerequisite)Import Prerequisite
To import an exported database, ensure that the export files are from a database that was running **the exact same version** of TigerGraph as the database that you are importing into.
## [](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_known_issues)Known Issues
  * User-defined loading jobs containing [`DELETE` statements](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/creating-a-loading-job#_delete_statement) are not exported correctly.
  * If a graph contains vertex or edge types with a composite key, the graph data is exported in a nonstandard format that cannot be re-imported.
  * GSQL EXPORT GRAPH may fail and cause a GPE to crash when UDT type has a fixed STRING size.

  
---  
## [](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_export_graph_all)EXPORT GRAPH ALL
The `EXPORT GRAPH ALL` command reads the data and metadata for all graphs in the TigerGraph system and writes the information to a zip file in the designated folder. If the command provides no options, it performs a full export, including schema, data, template information, and user profiles.
### [](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_required_privilege)Required privilege
```
EXPORT_GRAPH
```

### [](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_synopsis)Synopsis
```
EXPORT GRAPH ALL [<export_options>] TO "<directory_name>"

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

The export directory should be empty before running the command.   
---  
### [](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_parameters)Parameters
Parameter | Description  
---|---  
`directory_name` | The path of the directory to output export files to. Must be an absolute path.  
### [](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_export_all_options)Export All Options
Option | Description  
---|---  
`-S or --SCHEMA` | Only export graph schema.  
`-T` or `--TEMPLATE` |  Only export graph schema, queries, loading jobs and UDFs.  
`-D` or `--DATA` | Must be used with either `-S` or `-T`. Export data in CSV in addition to graph schema or template.  
`-U` or `--Users` | Must be used with either `-S` or `-T`. Export users, role assignments, secrets, and tokens.  
`-P` or -`-Password` | Encrypt the exported file with a password. Users will be prompted to enter a password when using this option.  
-p | Pass to “/path/to/dir“.  
`--SEPARATOR` | Specify the column separator character. Default is ASCII char 29.  
`--EOL` | Specify the line separator character. Default is ASCII char 28.  
[Proxy users](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/ldap#_proxy_users) cannot be exported.  
---  
ASCII char 30 (RS) and 31 (US) are reserved separators that cannot be used for data export.  
---  
#### [](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_non_interactive_mode_export_graph_all)Non-Interactive Mode `export graph all`
Run the command like this to run `export graph all` in non-interactive mode.
Example:
```
export graph all -p pass to “/path/to/dir“
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_output)Output
The `EXPORT GRAPH ALL` command exports all graphs in the database.
The export contains the following categories of files:
  * Data files in CSV format, one file for each type of vertex and each type of edge in a single node.
However, for cluster environments, since the data files are spread across the nodes, they will not be included in the zip file.  
---  
  * GSQL DDL command files created by the export command. The import command uses these files to recreate the graph schema(s) and reload the data.
  * Copies of the database’s queries, loading jobs, and user-defined functions.
  * GSQL command files used to recreate the users and their privileges.


The following files are created in the specified directory when exporting and are then zipped into a single file named `ExportedGraph.zip`.
If the file is password-protected, it can only be unzipped using the GSQL command `IMPORT GRAPH ALL`. The security features prevent users from directly unzipping it.  
---  
  * A `DBImportExport_<Graph_Name>.gsql` for each graph called `Graph_Name` in a multigraph database that contains a series of GSQL DDL statements that do the following:
    * Create the exported graph, along with its local vertex, edge, and tuple types,
    * Create the loading jobs from the exported graphs
    * Create data source file objects
    * Create queries
  * A `graph_<Graph_Name>/` folder for each graph in a multigraph database containing data for local vertex/edge types in `<Graph_Name>`. For each vertex or edge type called `<type>`, there is one of the following two data files:
    * `vertex_<type>.csv`
    * `edge_<type>.csv`
  * `global.gsql` - DDL job to create all global vertex and edge types, data sources, packages, template queries and functions.
  * `tuple.gsql` - DDL job to create all User Defined Tuples.
  * `policies.gsql` - DDL job to create policies.
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
  * Users:
    * `users.gsql` - DDL to create all exported users, import Secrets and Tokens and grant permissions.


Example
```
EXPORT GRAPH ALL TO "/tmp/export_graphs/"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_insufficient_disk_space)Insufficient disk space
If not enough disk space is available for the data to be exported, the system returns an error message indicating not all data has been exported. Some data may have already been written to disk. If an insufficient disk error occurs, the files will not be zipped, due to the possibility of corrupted data which would then corrupt the zip file. The user should clear enough disk space, including deleting the partially exported data, before reattempting the export.
It is possible for all the files to be written to disk and then to run out of disk space during the zip operation. If that is the case, the system will report this error. The unzipped files will be present in the specified export directory.  
---  
### [](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_export_timeout)Export timeout
If the timeout limit is reached during export, the system returns an error message indicating not all data has been exported. Some data may have already been written to disk. If a timeout error occurs, the files will not be zipped. The user should delete the export files, increase the timeout limit and then rerun the export.
The timeout limit is controlled by the session parameter `export_timeout`. The default timeout is ~138 hours. To change the timeout limit, use the command:
```
SET EXPORT_TIMEOUT = <timeout_in_ms>
GSQL![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_import_graph_all)IMPORT GRAPH ALL
The `IMPORT GRAPH ALL` command unzips the `.zip` file `ExportedGraph.zip` located in the designated folder, and then runs the GSQL command files.
`IMPORT GRAPH ALL` erases the current database (equivalent to running `DROP ALL`). The current version does not support incremental or supplemental changes to an existing database (except for the `--keep-users` option).
`IMPORT GRAPH ALL` looks for specific filenames. If either the zip file or any of its contents are renamed by the user, `IMPORT GRAPH ALL` may fail.
Any separator character defined in the export step is automatically included in the exported file. There is no need to specify the separator during import.
Please be extra cautious when importing databases as it can overwrite the current solution, resulting in the deletion of existing schemas, load jobs, queries, and data files. Importing a new solution cannot be undone to restore the previous state, regardless of whether the import succeeds or fails. Therefore, create a complete backup beforehand in case you need to restore the database: [Back up a Database Cluster](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/backup-cluster) For security purposes, TigerGraph has two `gadmin` commands, `GSQL.UDF.Policy.Enable` and `GSQL.UDF.Policy.HeaderAllowlist` to prevent malicious code execution during import. Please refer to the section on [UDF Security](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/query-user-defined-functions#udf-security) to ensure that UDFs comply with the security specifications. This will help you import the solution successfully.  
---  
### [](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_required_privileges)Required privileges
`WRITE_SCHEMA`, `CREATE_QUERY`, `WRITE_LOADINGJOB`, `EXECUTE_LOADINGJOB`, `DROP ALL`, `WRITE_USERS`
### [](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_synopsis_2)Synopsis
```
IMPORT GRAPH ALL [import_options] FROM "<filename>"
importOptions ::= [-P | --PASSWORD ] [ (-KU | -- keep-users]
  -P, --PASSWORD   Decrypt with password. User will be prompted.
  -p,         Pass from “/path/to/dir“.
  -KU, --KEEP-USERS  Do not delete user identities before importing
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_parameters_2)Parameters
Parameter | Description  
---|---  
`filename` | The path to the zip file produced by the `EXPORT GRAPH ALL` command. Must be an absolute path.  
### [](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_import_all_options)Import All Options
Option | Description  
---|---  
`-P` or `--PASSWORD` | Decrypt with password. You will be prompted to enter a password when using this option.  
`-KU` or `--KEEP-USERS` |  Keep the current users during the import operation. New users from the imported graph will still be added. Global roles from the current database are kept if you use this option. Local roles are dropped since the graphs themselves are dropped. If you have global roles with local privileges, those privileges are dropped from the global roles as well. You must include this option if you run the `IMPORT GRAPH` command as a user other than the default superuser `tigergraph`.   
### [](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_example)Example
```
IMPORT GRAPH ALL FROM "/tmp/export_graphs/"
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_non_interactive_mode_import_graph_all)Non-Interactive Mode `import graph all`
Run the command like this to run `import graph all` in non-interactive mode.
Example:
```
import graph all -p pass from “/path/to/dir“
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_loading_jobs)Loading Jobs
There are two sets of loading jobs:
  * Those that were in the **catalog** of the database which was exported. These are embedded in the file `DBImportExport_Graph_Name.gsql`
  * Those that are *created by `EXPORT GRAPH ALL` and are used to assist with the import process. These are embedded in the file `run_loading_jobs.gsql`.


The catalog loading jobs are not needed to restore the data. They are included for archival purposes.
Some special rules apply to importing loading jobs. Some catalog loading jobs will not be imported.  
---  
  1. If a catalog loading job contains `DEFINE FILENAME F = "/path/to/file/"`, the path will be removed and the imported loading job will only contain `DEFINE FILENAME F`. This is to allow a loading job to still be imported even though the file may no longer exist or the path may be different due to moving to another TigerGraph instance.
  2. If a specific file path is used directly in the LOAD statement, and the file cannot be found, the loading job cannot be created and will be skipped. For example, `LOAD "/path/to/file" to vertex v1` cannot be created if `/path/to/file` does not exist.
  3. Any file path using `$sys.data_root` will be skipped. This is because the value of `$sys.data_root` is not retained from an export. During an import, `$sys.data_root` is set to the root folder of the import location.


### [](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_schema_change_jobs)Schema Change Jobs
There are two sets of schema change jobs:
  1. Those that were in the catalog of the database which was exported. These are stored in the folder `/SchemaChangeJobs`.
  2. Those that were created by `EXPORT GRAPH ALL` and are used to assist with the import process. These are in the `run_loading_jobs.gsql` command file. The jobs are dropped after the import command is finished with them.


The database’s schema change jobs are not executed during the import process. This is because if a schema change job had been run before the export, then the exported schema already reflects the result of the schema change job. The directory `/SchemaChangeJobs` contains these files:
  * `Global_Schema_Change_Jobs.gsql` contains all global schema change jobs
  * `<Graph_Name>_Schema_Change_Jobs.gsql` contains schema change jobs for each graph `<Graph_Name>`.


## [](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_cluster_importexport)Cluster export/import
Importing and exporting clusters is not fully automated in the current version. The database can be exported and imported by following some additional steps.
### [](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_export_from_a_cluster)Export from a cluster
Rather than creating a single export zip file, the `EXPORT GRAPH ALL` command creates a file for each machine.
To export, run `EXPORT GRAPH ALL` from the GSQL shell on one node. The `EXPORT GRAPH` command does not bundle all the files to one server, and it does not compress each server’s files to one zip file. Some files, including the data files, are exported to each server, while some files are only on the local server where `EXPORT GRAPH` was run.
### [](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_import_into_a_cluster)Import into a cluster
The following are the steps to import an export file to a cluster.
If you’re exporting from a single-node cluster, the `ExportedGraph.zip` can be directly imported, so you don’t need the source and target clusters to have the same number of servers. If you’re exporting from a smaller cluster to a larger one, you must transfer the dataset files along with the zip file to the appropriate nodes in the target cluster.
For importing from a larger cluster to a smaller one, you’ll need to combine the dataset files, which can be easily done using GraphStudio. If you’re using the `gsql CLI`, remember to combine all exported data from each node and transfer them to the new cluster before importing.
#### [](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_1_transfer_files_to_new_cluster)1. Transfer files to new cluster
Transfer the export files from the export servers to the corresponding servers in the new cluster. For example, the files on the m1 node of the cluster that exported the graphs must be copied to the m1 server on the cluster that is importing the export files.
The export file on every node must share the same absolute path.
#### [](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export#_2_run_import_graph_all)2. Run `IMPORT GRAPH ALL`
Run the `IMPORT GRAPH ALL` command from the server that corresponds to the server where `EXPORT GRAPH ALL` was run.
For example, if you exported from the m2 node in a cluster, you also need to run the `IMPORT GRAPH ALL` command from the m2 node of the cluster you are importing the export files into.
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


