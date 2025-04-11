![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model)[Next](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model)
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
  * [Access Management](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/)
  * Authorization
  * [Access Control Model](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/4.2/modules/user-access/pages/access-control-model.adoc)
### Contents
  * [Role-based access control](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_role_based_access_control)
  * [Privileges](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_privileges)
  * [Privilege scopes](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_privilege_scopes)
  * [Data CRUD privileges](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_data_crud_privileges)
  * [Fine-grained query privileges](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_fine_grained_query_privileges)
  * [Roles](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_roles)
  * [Global vs local roles](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_global_vs_local_roles)
  * [Built-in roles](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_built_in_roles)
  * [User-defined roles](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_user_defined_roles)
  * [Importing and exporting](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_importing_and_exporting)


# Access Control Model in TigerGraph
### Contents
  * [Role-based access control](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_role_based_access_control)
  * [Privileges](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_privileges)
  * [Privilege scopes](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_privilege_scopes)
  * [Data CRUD privileges](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_data_crud_privileges)
  * [Fine-grained query privileges](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_fine_grained_query_privileges)
  * [Roles](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_roles)
  * [Global vs local roles](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_global_vs_local_roles)
  * [Built-in roles](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_built_in_roles)
  * [User-defined roles](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_user_defined_roles)
  * [Importing and exporting](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_importing_and_exporting)


TigerGraph supports role-based access control (RBAC). RBAC lets you grant access to different actions on **all** of a certain type of objects on a graph, such as allowing a role to read or write all queries.
All access control is only in effect when user authentication is enabled. Authentication is not enabled by default and [must be enabled manually](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/enabling-user-authentication).   
---  
## [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_role_based_access_control)Role-based access control
TigerGraph uses role-based access control (RBAC) to manage authorization. On every graph, privileges to perform actions are assigned to roles, and roles are granted to users. Outside the permissions granted by their roles, a user has no access to the system.
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_privileges)Privileges
A privilege is permission to perform an action in a given scope. When a privilege is assigned to a role, it allows users with the role to perform the specified action in the specified scope. For example, the privilege `READ_SCHEMA` on graph `social` gives a user read permission to the schema of the graph `social`. This allows the user to run commands such as `ls` and `SHOW VERTEX` on the graph.
To view a complete list of privileges available in TigerGraph and the commands they enable a user to run, see [List of Privileges](https://docs.tigergraph.com/tigergraph-server/4.2/reference/list-of-privileges).
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_privilege_scopes)Privilege scopes
There are four different scopes for a privilege:
  * Global
  * Graph-level
  * Type-level (Only applicable to [Data CRUD privileges](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_data_crud_privileges))
  * Attribute-level (Only applicable to [Data CRUD privileges](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_data_crud_privileges))


Global privileges apply to all graphs and global objects. Graph-level privileges only apply on the graph they belong to. Type-level privileges only apply to specific vertex or edge types on a graph. Attribute-level privileges only apply to specific attributes of a vertex or edge type.
A privilege on a large scope applies to the entire scope, including all lower scopes encompassed by that scope. If you have a privilege on the graph level, you also have that privilege on the type level and attribute level for all types and attributes in that graph. If you have a privilege on the global scope, you have that privilege across all graphs, types and attributes.
Most privileges are global or graph-level. Only privileges pertaining to graph data (`CREATE_DATA`, `READ_DATA`, `UPDATE_DATA`, `DELETE_DATA`) can be granted on the type level or attribute level.
For example:
  * A role with `CREATE_QUERY` on graph `Social` can only create queries on graph `social`, but not on other graphs. In contrast, a role with `CREATE_QUERY` on the global scope can create queries on all graphs.
  * A role with `UPDATE_DATA` on the `age` attribute of the `Person` vertex on graph `Social` are allowed to run queries that update the value of the `age` attribute of `Person` vertices.
  * A role with `READ_DATA` on the global scope can run queries that read graph data on any graph, any type, or any attribute. They do not need to have privileges specifically for those graphs, types, or attributes.


### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_data_crud_privileges)Data CRUD privileges
Data CRUD privileges (`CREATE_DATA`, `READ_DATA`, `UPDATE_DATA`, `DELETE_DATA`) are special in that they can be granted on the type level and attribute level.
Data CRUD privileges only govern data access through queries and REST endpoints. Users with the `EXECUTE_LOADINGJOB` privilege do not need additional privileges in order to run a loading job that inserts or deletes vertices and edges.   
---  
The privileges govern specific ways in which a user can access and modify data. Even regarding a single REST endpoint, whether a request is authorized depends on the information that the request is accessing or modifying.
Privilege | Type level | Attribute level  
---|---|---  
`CREATE_DATA` | Permission to create vertices and edges, and specify values for all attributes for the type where the privilege is granted. | 
  * If granted on a vertex type attribute, it gives permission to create vertices, but only specify values for attributes where the user has `CREATE_DATA` privilege if the user also has `UPDATE_DATA` privilege on all attributes of that type.
    * The user must have `CREATE_DATA` privilege on the primary ID of the vertex type to be able to create vertices.
  * If granted on an edge type attribute, it gives permission to create edges, but only specify values for attributes where the user has `CREATE_DATA` privilege if the user also has `UPDATE_DATA` privilege on all attributes of that type.
  * For attributes where the user doesn’t have privilege, they must use wildcards(`_`) to use the default value for vertices/edges created by the [`INSERT INTO` statements](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-modification-statements#_insert_into_statement).

  
`READ_DATA` | Permission to access all data of the type where the privilege is granted. | Permission to access the attribute value where the privilege is granted. To grant `READ_DATA` to a specific attribute of a type, you must grant `READ_DATA` to the primary key of the type first or in the same command. For edges, you must grant `READ_DATA` to the primary key of the `FROM` and `TO` vertex types before granting `READ_DATA` to other attributes of the edge type.  
`UPDATE_DATA` | Permission to update all data of the type where the privilege is granted. | Permission to update the attribute value where the privilege is granted. `UPDATE_DATA` on all attributes is also required for creating new vertices and edges.  
`DELETE_DATA` | Permission to delete data of the type where the privilege is granted. | N/A. This privilege is not applicable on the attribute level.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_examples)Examples
Suppose we have a graph with schema as below:
```
CREATE VERTEX Person(id UINT PRIMARY KEY, name STRING, INT age)
CREATE VERTEX City(id UINT PRIMARY KEY, name STRING)
CREATE GRAPH Example_Graph(Person, City)
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

If a user were to run the following query:
```
CREATE QUERY example_query() {
 Seed = {City.*}; **(1)**
 vSet = SELECT s FROM Seed:s
     POST-ACCUM
      s.name = s.name + ".post"; **(2)**
 INSERT INTO Person VALUES ("id3", "Tom", _) **(3)**
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | This action requires `READ_DATA` on type `City`.  
---|---  
**2** | This action requires `UPDATE_DATA` on attribute `name` of type `City`.  
**3** | This action requires `UPDATE_DATA` on all attributes of type `Person` and `CREATE_DATA` on attribute `id` and `name`.  
Running the query would at a minimum require `READ_DATA` on type `City` and `UPDATE_DATA` on attribute `name` of type `City`.
If a user were to make the following REST request:
```
$ curl -X GET "http://localhost:14240/restpp/graph/Example_Graph/vertices/Person/id1"
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The request requires that the user has at least `READ_DATA` on type `Person`, or all attributes of type `Person`. However, if the user specify the attributes for the request to return:
```
$ curl -X GET "http://localhost:14240/restpp/graph/Example_Graph/vertices/Person/id1?select=age"
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The request would no longer require `READ_DATA` on the attribute `name` and only require `READ_DATA` on `id` and `age`.
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_fine_grained_query_privileges)Fine-grained query privileges
Fine-grained query privileges `CREATE_QUERY`, `READ_QUERY`, `UPDATE_QUERY`, `DROP_QUERY`, `INSTALL_QUERY`, and `EXECUTE_QUERY` are also special in terms of their scopes.
`CREATE_QUERY` can only be granted/revoked at global and graph level. `READ_QUERY`, `UPDATE_QUERY`, `DROP_QUERY`, `INSTALL_QUERY`, and `EXECUTE_QUERY` can only be granted/revoked at existing individual query objects.
These privileges govern how a user interact with specific query objects.
Built-in role `superuser` has all fine-grained query privileges on all existing queries in global. Built-in role `admin` has all fine-grained query privileges on all existing queries in the graph where `admin` is granted on.   
---  
Privilege | Global/Graph level | Query level  
---|---|---  
`CREATE_QUERY` | Permission to create query in global or specific graph where the privilege is granted. | N/A. This privilege is not applicable on the query level.  
`READ_QUERY` | N/A. This privilege is not applicable on the global or graph level. | Permission to read query content on the specific query object where the privilege is granted.  
`UPDATE_QUERY` | N/A. This privilege is not applicable on the global or graph level. | Permission to replace query content on the specific query object where the privilege is granted.  
`DROP_QUERY` | N/A. This privilege is not applicable on the global or graph level. | Permission to drop query on the specific query object where the privilege is granted.  
`INSTALL_QUERY` | N/A. This privilege is not applicable on the global or graph level. | Permission to install query on the specific query object where the privilege is granted.  
`EXECUTE_QUERY` | N/A. This privilege is not applicable on the global or graph level. | Permission to run or interpret query on the specific query object where the privilege is granted.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_examples_2)Examples
Assume we created a graph `g1` and assume user does not hold special built-in roles such as `superuser` and `admin`.
```
GSQL > CREATE GRAPH g1(*)
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

To create a query `q1`, `CREATE` privilege on query objects in global or graph `g1` is required.
```
GSQL > use graph g1
GSQL > create query q1() {print "q1";}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

To update a query `q1`, `UPDATE` privilege on query object `q1` is required unless the current user owns the query object.
```
GSQL > use graph g1
GSQL > create or replace query q1() {print "new q1";}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

To drop a query `q1`, `DROP` privilege on query object `q1` is required unless the current user owns the query object.
```
GSQL > use graph g1
GSQL > drop query q1
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

To install a query `q1`, `INSTALL` privilege on query object `q1` is required unless the current user owns the query object.
```
GSQL > use graph g1
GSQL > install query q1
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

To run/interpret a query `q1`, `EXECUTE` privilege on query object `q1` is required unless the current user owns the query object.
```
GSQL > use graph g1
GSQL > run query q1()
GSQL > interpret query q1()
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_roles)Roles
A role is a collection of privileges you can assign to users to grant them permission to perform actions on specific resources.
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_global_vs_local_roles)Global vs local roles
Local roles are deprecated, and will be dropped in a future version.   
---  
Roles can be global or local. Local roles can only be granted graph-level privileges, while global roles can be granted privileges at every level.
For example, if a user creates a role `manager` on the graph `social`:
```
GSQL > CREATE ROLE manager ON GRAPH social
Successfully created roles: [manager].
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This role can only be granted privileges on the graph `social`. It cannot be granted global privileges.
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_built_in_roles)Built-in roles
GSQL offers five built-in local roles and two built-in global roles. The built-in roles cannot be dropped. The following table details the built-in roles and their corresponding set of privileges.
**Name** | **Global or Local** | **Privilege List**  
---|---|---  
`observer` | Local | `READ_SCHEMA`, `READ_LOADINGJOB`  
`queryreader` | Local | `READ_SCHEMA`, `READ_LOADINGJOB`, `EXECUTE_LOADINGJOB`, `READ_DATA`  
`querywriter` | Local | `READ_SCHEMA`, `READ_LOADINGJOB`,`READ_QUERY`, `EXECUTE_LOADINGJOB`, `READ_DATA`, `CREATE_QUERY`, `CREATE_DATA`, `UPDATE_DATA`, `DELETE_DATA`  
`designer` | Local | `READ_SCHEMA`, `READ_LOADINGJOB`,`READ_QUERY`, `EXECUTE_LOADINGJOB`, `READ_DATA`, `CREATE_QUERY`, `CREATE_DATA`, `UPDATE_DATA`, `DELETE_DATA`, `WRITE_SCHEMA`, `WRITE_LOADINGJOB`  
`admin` | Local | `READ_SCHEMA`, `READ_LOADINGJOB`, `READ_QUERY`, `EXECUTE_LOADINGJOB`, `READ_DATA`, `CREATE_QUERY`, `CREATE_DATA`, `UPDATE_DATA`, `DELETE_DATA`, `WRITE_SCHEMA`, `WRITE_LOADINGJOB`, `WRITE_ROLE`, `WRITE_DATASOURCE`, `READ_ROLE`, `READ_USER`, `READ_PROXYGROUP`, `READ_POLICY`, `WRITE_POLICY`, `OWNERSHIP` on ALL QUERIES  
`globalobserver` | Global | `READ_SCHEMA`, `READ_LOADINGJOB` at the global scope  
`globaldesigner` | Global | Designer’s privileges on the global scope, `DROP_GRAPH` for graphs created by the same user  
`superuser` | Global | All supported RBAC privileges, , `OWNERSHIP` on ALL QUERIES  
For Row Policy related Built-in roles see [Row Policy built-in role changes](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_built-in-roles)  
---  
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_user_defined_roles)User-defined roles
Users can define roles with their own list of privileges they want to grant to the role. To learn how to create/drop user-defined roles and manage privileges for the roles, see [Role Management](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/role-management).
## [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_importing_and_exporting)Importing and exporting
When exporting and importing graphs, query-level privileges may be affected under the following circumstances:
  * **Exporting graphs without queries (`-S, --SCHEMA`)**: No query-level privileges are granted in the exported graphs since there are no queries included.
  * **Exporting graphs with queries but without users (`-T, --TEMPLATE`)**: The `OWNERSHIP` privileges for all queries will be automatically transferred to the user performing the import graph operation.
  * **LDAP users** : LDAP users are not included during the export of graphs, so any query `OWNERSHIP` privileges previously granted to LDAP users will be automatically transferred to the user performing the import graph operation.


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


