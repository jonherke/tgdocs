![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy)[Next](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy)
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
  * [Row Policies](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/row-policy-overview)
  * [Key Concepts](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/4.2/modules/user-access/pages/rbac-row-policy/rbac-row-policy.adoc)
### Contents
  * [Prerequisites](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_prerequisites)
  * [Key Concepts](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_key_concepts)
  * [Packages](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_packages)
  * [Creating Packages](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_creating_packages)
  * [Showing Packages](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_showing_packages)
  * [Dropping Packages](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_dropping_packages)
  * [GSQL Functions](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_gsql_functions)
  * [Create Function](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_create_function)
  * [Drop Function](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_drop_function)
  * [Install Function](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_install_function)
  * [Install Options](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_install_options)
  * [Show Function](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_show_function)
  * [Object-Based Privileges](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_object_based_privileges)
  * [Privilege Details](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_privilege_details)
  * [Privilege Commands](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_privilege_commands)
  * [Privilege Protection](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_privilege_protection)
  * [Context Functions](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_context_functions)
  * [current_roles()](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_current_roles)
  * [is_granted_to_current_roles(string roleName)](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_is_granted_to_current_rolesstring_rolename)


# RBAC: Row Policy Key Concepts
### Contents
  * [Prerequisites](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_prerequisites)
  * [Key Concepts](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_key_concepts)
  * [Packages](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_packages)
  * [Creating Packages](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_creating_packages)
  * [Showing Packages](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_showing_packages)
  * [Dropping Packages](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_dropping_packages)
  * [GSQL Functions](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_gsql_functions)
  * [Create Function](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_create_function)
  * [Drop Function](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_drop_function)
  * [Install Function](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_install_function)
  * [Install Options](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_install_options)
  * [Show Function](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_show_function)
  * [Object-Based Privileges](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_object_based_privileges)
  * [Privilege Details](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_privilege_details)
  * [Privilege Commands](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_privilege_commands)
  * [Privilege Protection](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_privilege_protection)
  * [Context Functions](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_context_functions)
  * [current_roles()](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_current_roles)
  * [is_granted_to_current_roles(string roleName)](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_is_granted_to_current_rolesstring_rolename)


## [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_prerequisites)Prerequisites
This guide assumes some basic understanding of TigerGraph’s query language GSQL. Refer to the [GSQL V3 Tutorial](https://github.com/tigergraph/ecosys/blob/master/demos/guru_scripts/docker/tutorial/4.x/README.md) to get started using GSQL.
## [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_key_concepts)Key Concepts
RBAC Row policy introduces a number of key concepts:
  * [Packages](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_packages): were created to serve as containers for functions, making it easier to organize and manage user created access control rules.
  * [GSQL Functions](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_gsql_functions): are a new concept to help customize how to handle attribute values and processes. Think of these as tools for fine-tuning access control.
  * [Object-Based Privileges](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_object_based_privileges): are new mechanisms for managing privileges.
  * [Context Functions](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_context_functions): are new built-in functions which can retrieve user information in a current session.
  * [Privilege Protection](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_privilege_protection): adds new RBAC privileges for `FUNCTION` and `POLICY`.


## [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_packages)Packages
Packages act like containers, helping keep everything tidy. A package can also contain sub-packages, giving an even more organized workspace.
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_creating_packages)Creating Packages
Ex. To create a package called `lib1`:
```
GSQL > create package lib1
Successfully created Packages: [lib1].
```

Ex. To create a sub-package `lib2` inside `lib1`:
```
GSQL > create package lib1.lib2
Successfully created Packages: [lib1.lib2].
```

### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_showing_packages)Showing Packages
Use the `show package` command to get a glimpse of the package organization.
Ex. To see all packages in the global scope, just type:
```
GSQL > show package
Packages on global:
- lib1
- lib3
```

The result will be a list of all the packages that have been created. To get a more detailed view, including sub-packages and objects within a specific package specify the package name.
Ex. To see details of `lib1`:
```
GSQL > show package lib1
Packages "lib1":
- Sub-Packages:
- lib2
- Object:
- Functions:
- lib1.func1(string s) RETURNS (bool)
- Template Queries:
- test1(string a, int b)
```

This command will reveal what’s inside "lib1" including GSQL functions and Template Queries.
To `show packages` based on a naming pattern like "lib" use `-r "[pattern].*"`
Ex. To show packages that start with `lib`:
```
GSQL > show package -r "lib.*"
lib1
lib1.lib2
lib3
lib3.lib2
```

## [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_dropping_packages)Dropping Packages
Dropping a package is to remove the package. Doing this will also remove all sub-packages and objects within it.
Ex. To drop the `lib1` package, including all sub-packages:
```
GSQL > drop package lib1
Successfully dropped Packages: [lib1].
```

## [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_gsql_functions)GSQL Functions
A GSQL Function is a new schema-free catalog object, which only supports limited GSQL syntax. GSQL functions are like custom tools for performing specific tasks in GSQL, but it’s important to note that they can’t use schema related entities like vertices and edges.
Right now, GSQL Functions can only be used specifically in the context of row policies and to control access at the row level.  
---  
Follow these rules to ensure it works seamlessly within row policies.
  * **Parameter Types** : Use primitive data types like `bool`, `uint`, `int`, `float`, `double`, `string`, and `datetime` as building blocks and inputs to GSQL Functions.
  * **Return Types** : GSQL Functions can give one of three results: `bool`, `uint`, or `int`.
  * **Simplicity for Efficiency** : To keep things simple and optimized, GSQL Functions can only have one level of nested control flows.
  * **Calling Other Functions** : GSQL functions, can utilize some built-in functions:
    * [String Functions](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/string-functions)
    * [Mathematical Functions](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/mathematical-functions)
  * **Context Function** : GSQL functions support new [Context Functions](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_context_functions) like:
    * [current_roles()](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_current_roles)
    * [is_granted_to_current_roles(string roleName)](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_is_granted_to_current_rolesstring_rolename)
  * **No Custom Functions Inside GSQL** : Users are restricted from creating their own functions within a GSQL function.


### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_create_function)Create Function
To create a GSQL Function, declare the function, specify its parameters, define its body, and set the expected return type.
Ex. Here’s a simple example creating a function called `func2` in the `lib1` package:
```
GSQL > create function lib1.func2(int param1, float param2, string param3) returns (bool)
{
  // Function's code goes here
  // Use parameters, variables, control flows, and more
  // In the end, the function returns a result of type bool
}
```

Ex. Here’s a more detailed example with some example values:
```
GSQL > create function lib1.func2(int param1, float param2, string param3) returns (bool)
{
  EXCEPTION zero (40001);       // Exception declaration
  int i = 0;            	// Variable declaration
  bool result = false;       	// Variable declaration
  i = param1;           	// Variable assignment
  string j = upper(param3); 		// Variable declaration with function call
  SumAccum<String> @@ss;   		// Global accum declaration
  @@ss += param3;       			// Global accum assignment
  IF i == 0 THEN       			// If control flow
  raise zero ("Error: i is zero"); 	// Raise exception statement
  END;               			// end of control flow
  CASE param3           			 // Case-when control flow
  WHEN "ENG" THEN result = true;
  WHEN "MANAGER" THEN result = false;
  ELSE result = param2 > 2.1;
  END;               			// end of control flow
  RETURN result;         			// Return statement
}
```

It is important to note, GSQL Functions **do not** support cases where functions have two nested control flows.
Ex. The example below will **not** work:
```
GSQL > create function p1.f6(string label, string company_name, int age) returns (bool)
{
  if label == "ENG" then
    if age > 2 then
      return true;
    end;
  end;
  return false;
}
```

In order to support nested control flows, a GSQL Function would need to be written like the case below.
Ex. The example below will work:
```
create function p1.f6(string label, string company_name, int age) returns (bool)
{
  if label == "ENG" AND age > 2 then
      return true;
    end;
  return false;
}
```

### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_drop_function)Drop Function
To remove a GSQL function from a package, use `drop function`.
Ex. This drops the "lib1.func2" function:
```
GSQL > drop function lib1.func2
Successfully dropped function: [lib1.func2].
```

Ex. To drop functions, but that does not include functions in the sub-packages:
```
GSQL > drop function lib1.*
Successfully dropped functions: [lib1.func1, lib1.func2].
```

### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_install_function)Install Function
To make functions available for use, they must be installed.
Ex. This installs the `lib1.func2` and shows an example install message:
```
GSQL > install function lib1.func1
Start installing functions for package 'lib1' ...
Package function: lib1-func1
Select 'm1' as compile server, now connecting ...
Node 'm1' is prepared as compile server.
[=================================================] 100% (1/1)
Function installation finished for package 'lib1'.
```

Ex. To install all functions use one of these commands:
```
GSQL > install function ALL
GSQL > install function **
```

Specific functions can also be excluded or included. To install functions in a specific package (ex. `lib1`).
Ex. This command would **exclude** functions in the `lib1` sub-packages.
```
GSQL > install function lib1.*
```

Ex. This command would install functions in a specific package (ex. `lib1`) and also include functions in the sub-packages:
```
GSQL > install function lib1.**
```

### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_install_options)Install Options
Additionally, two options are available for function installation.
Ex. The `-force` option forcefully installs this GSQL function.
```
GSQL > install function -force lib1.func2
```

Ex. The `-debug` option enables a debug feature for this GSQL function.
```
GSQL > install function -debug lib1.func2
```

### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_show_function)Show Function
To see what functions are available, use the `show function` command. This command shows specific functions, functions within a package, or even all functions.
Ex. To show details for the `lib1.func2` function:
```
GSQL > show function lib1.func2
create function lib1.func2() returns (bool) {
RETURN true;
}
```

Ex. To show all functions in the `lib1` package, but do not include functions in the sub-packages:
```
GSQL > show function lib1.*
create function lib1.func1() returns (bool) {
RETURN true;
}
create function lib1.func2() returns (bool) {
RETURN true;
}
```

Ex. Use `-r` to show all functions that start with `lib`:
```
GSQL > show function -r "lib.*"
create function lib1.func1() returns (bool) {
RETURN true;
}
create function lib1.func2() returns (bool) {
RETURN true;
}
create function lib2.func1() returns (bool) {
RETURN true;
}
```

Ex. To show all functions available:
```
GSQL > show function *
create function lib1.func1() returns (bool) {
RETURN true;
}
create function lib1.func2() returns (bool) {
RETURN true;
}
create function lib2.func1() returns (bool) {
RETURN true;
}
```

## [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_object_based_privileges)Object-Based Privileges
This mechanism allows users to grant or revoke privileges based on specific objects. Allowing users to specify the privilege names, objects, and other details.
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_privilege_details)Privilege Details
Here are some important terms and details for object-based privileges:
  * **Privilege Names** : Are the specific privileges that can be granted or revoked, such as `ACCESS`, `CREATE`, `READ`, etc.
  * **Privilege Objects** : Are the objects to which the privileges apply. They can be things like `GLOBAL`, `VERTEX`, `EDGE`, etc.
  * **Privilege Scopes** : Define where these privileges apply, like `GRAPH`, `PACKAGE`, or `GLOBAL`.


To see a complete list, as well as the [legacy privilege syntax](https://docs.tigergraph.com/tigergraph-server/4.2/reference/list-of-privileges) that the object-base privilege relate to, go to the [Object-Based Privilege Tables](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/row-policy-privileges-table).
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_privilege_commands)Privilege Commands
To grant or revoke object-based privileges, use these commands.
Ex. Granting Privileges:
```
GRANT privilegeNames ON privilegeObjects IN privilegeScopes TO userOrRoleNames
```

Ex. Revoking Privileges:
```
REVOKE privilegeNames ON privilegeObjects IN privilegeScopes FROM userOrRoleNames
```

For users that grant privileges in the legacy privilege syntax, transitioning to object-based privilege syntax is simple.
Table 1. Compare Legacy and Object based syntax: Privilege Syntax | Example  
---|---  
Legacy | grant privilege READ_DATA, CREATE_DATA, UPDATE_DATA, DELETE_DATA on global to role1  
Object-Based | grant READ, CREATE, UPDATE, DELETE on ALL DATA in global to role1  
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_privilege_protection)Privilege Protection
Additionally, there are new RBAC privileges to protect the `FUNCTION` and `POLICY`.
Table 2. FUNCTION Privilege | Levels | Operations  
---|---|---  
USE | global/package/function | show function apply row policy  
WRITE | global/package/function | create/replace/drop function  
Table 3. Policy Privilege | Levels | Operations  
---|---|---  
READ | global/graph | show applied policy  
WRITE | global/graph | apply row policy clear row policy  
Table 4. For built-in roles, there are some changes as well: Built-in Role | New Privilege  
---|---  
superuser | USE_FUNCTION WRITE_FUNCTION on global level READ_POLICY WRITE_POLICY on global level  
admin | READ_POLICY WRITE_POLICY on graph level  
For a complete list of Built-in roles see [Built-in Roles](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_built_in_roles)  
---  
## [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_context_functions)Context Functions
[Context Functions](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/context-functions) are a set of new built-in functions that provide insights into the user’s information during their current session. They offer valuable insights into user roles, making it easier to manage access and privileges within TigerGraph.
They work in: `INSTALLED` queries, `INTERPRET` queries, and [GSQL Functions](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_gsql_functions).
Before users can use Context Functions, they must enable REST authentication. If it's not enabled, users will see an error message. To learn more about REST authentication see [REST API Authentication](https://docs.tigergraph.com/tigergraph-server/4.2/API/authentication).
Additionally, in order to use the context functions explicitly, ensure that the user holds the `READ_ROLE` privilege on the current graph, unless a [Row Policy](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/setup-row-policy#_row_policy) already includes the context functions.
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_current_roles)current_roles()
The `current_roles()` function gives users the role names granted to the current user, presented as a `SetAccum` of strings. For instance, a user holds the roles `USregion` and `NAregion`, when this user runs a query or GSQL Function with `current_roles()`, it will return a `SetAccum` containing the strings, `USregion` and `NAregion`.
Ex. Create the roles:
```
GSQL > create role USregion
GSQL > create role NAregion
GSQL > grant role USregion, NAregion to user1
GSQL > grant read on all roles in global to USregion
GSQL > grant read on all data in global to USregion
```

Ex. Create a query with `current_roles()` :
```
GSQL > create query test() {
print current_roles();
}
```

Ex. The result will show the user’s roles:
```
GSQL > run query test()
{
  "version": {
    "edition": "enterprise",
    "api": "v2",
    "schema": 0
  },
  "error": false,
  "message": "",
  "results": [
  {
    "current_roles()": [
      "USregion",
      "NAregion"
    ]
  }
  ]
}
```

### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy#_is_granted_to_current_rolesstring_rolename)is_granted_to_current_roles(string roleName)
`is_granted_to_current_roles()` tells if the current user holds a particular role specified in the parameter. This function returns a boolean value.
Ex. Syntax:
```
is_granted_to_current_roles("USregion")
```

This should return true, because the user’s role set contains `USregion` that was granted in the previous section.
Ex. Create a query that prints `is_granted_to_current_roles()` and input `USregion`:
```
create query test2() {
print is_granted_to_current_roles("USregion");
}
```

Ex. Run the query and the result will show whether the user has the specified role:
```
GSQL > run query test2()
{
  "version": {
    "edition": "enterprise",
    "api": "v2",
    "schema": 0
  },
  "error": false,
  "message": "",
  "results": [
  {
    "is_granted_to_current_roles(\"USregion\")": true
  }
  ]
}
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


