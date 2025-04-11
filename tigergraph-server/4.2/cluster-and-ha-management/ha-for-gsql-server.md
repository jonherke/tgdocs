![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server)[Next](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server)
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
  * [Clustering](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/)
  * [High Availability](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-overview)
  * [GSQL Server HA](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/4.2/modules/cluster-and-ha-management/pages/ha-for-gsql-server.adoc)
### Contents
  * [Design overview](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server#_design_overview)
  * [Role of primary GSQL server](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server#_role_of_primary_gsql_server)
  * [Role of standby GSQL servers](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server#_role_of_standby_gsql_servers)
  * [Configuring HA for the GSQL server](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server#_configuring_ha_for_the_gsql_server)
  * [Setting GSQL HA Failover](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server#_setting_gsql_ha_failover)
  * [User Impact and Changes](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server#_user_impact_and_changes)
  * [UDF and token function retrieval](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server#_udf_and_token_function_retrieval)
  * [File Path Configuration](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server#_file_path_configuration)
  * [GSQL Client connection setup](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server#_gsql_client_connection_setup)


# High Availability Support for GSQL Server
### Contents
  * [Design overview](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server#_design_overview)
  * [Role of primary GSQL server](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server#_role_of_primary_gsql_server)
  * [Role of standby GSQL servers](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server#_role_of_standby_gsql_servers)
  * [Configuring HA for the GSQL server](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server#_configuring_ha_for_the_gsql_server)
  * [Setting GSQL HA Failover](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server#_setting_gsql_ha_failover)
  * [User Impact and Changes](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server#_user_impact_and_changes)
  * [UDF and token function retrieval](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server#_udf_and_token_function_retrieval)
  * [File Path Configuration](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server#_file_path_configuration)
  * [GSQL Client connection setup](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server#_gsql_client_connection_setup)


TigerGraph has built-in HA for all the internal critical components. That is, if one component becomes unavailable, then a corresponding component located within another cluster node can take over. Due to the criticality of the interworking of these internal components, users are advised not to alter the number of such internal nodes except as advised by Tigergraph Support or Professional Services.
When a cluster is [initially installed](https://docs.tigergraph.com/tigergraph-server/4.2/installation/bare-metal-install) or [resized](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/repartition-a-cluster), the installer will automatically select an appropriate number of service components. For components which comprise the core storage and compute engine (such GSE, GPE, and REST API servers), one service component per cluster node is appropriate. For other components, like the GSQL server, having one component per node is excessive for large clusters. The maximum number of GSQL servers is 5, regardless of cluster size.
## [](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server#_design_overview)Design overview
The **first five nodes** in a TigerGraph cluster each run a GSQL server. One of the GSQL servers is the primary server, while other servers are standby servers that provide high availability for client connections. The primary and standby servers are referred to as "leaders" and "followers" inside GSQL.
![Diagram visualizing the architecture of a TigerGraph cluster with high availability.](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/_images/gsql-ha.png)
Figure 1. A TigerGraph cluster contains local clients and GSQL servers, one of which is the primary GSQL server. The standby servers send redirect requests to the primary server.
### [](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server#_role_of_primary_gsql_server)Role of primary GSQL server
The primary GSQL server performs the following tasks:
  * Processes client connections
  * Processes query requests from GSQL clients
  * Processes user management requests


When the primary server fails, a standby server becomes the new primary server. When the old primary server is restored, it becomes a GSQL standby server.
### [](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server#_role_of_standby_gsql_servers)Role of standby GSQL servers
  * Redirect requests to the primary server
  * Help the primary server check for the existence of source data files and parse file headers (if ANY is chosen)


## [](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server#_configuring_ha_for_the_gsql_server)Configuring HA for the GSQL server
### [](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server#_setting_gsql_ha_failover)Setting GSQL HA Failover
Use the `gadmin config` command to get/set the following configurations related to GSQL High Availability.
The first is the heartbeat interval in milliseconds. The second is the number of consecutively missed heartbeats that will trigger switching to a backup server. It must be at least 2 to allow 1 heartbeat miss.
```
Controller.LeaderElectionHeartBeatIntervalMS = 2000
Controller.LeaderElectionHeartBeatMaxMiss = 4
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

For example, if we use `LeaderElectionHeartBeatIntervalMS = 2000` and `LeaderElectionHeartBeatMaxMiss = 4` as shown above, then the total timeout is 2 × 4 = 8 seconds. In this case, the current primary server will be switched if its heartbeat has stopped for more than 8 seconds.
## [](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server#_user_impact_and_changes)User Impact and Changes
### [](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server#_udf_and_token_function_retrieval)UDF and token function retrieval
The m1 node of a cluster stores the following files that may contain user-defined C++ functions to customize GSQL:
  * GSQL loader’s Token functions
  * ExprFunctions
  * ExprUtil


The GSQL server will retrieve these user source code files in the following priority order when it needs them:
  * Via GitHub/GitHub enterprise (if configuration is set),
  * Files uploaded via `PUT` commands
  * Default files that are shipped with the product


#### [](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server#_user_source_code_in_github_code_repository)User source code in GitHub code repository
This mode requires public network access or GitHub enterprise server access. Provide the following `gadmin` configuration:
```
GSQL.GithubUserAcessToken # the credential, or "anonymous", empty means not using github
GSQL.GithubRepository   # e.g. tigergraph/ecosys
GSQL.GithubBranch     # optional; default is "main" branch, e.g. demo_github
GSQL.GithubPath      # path to the directory in the github that has TokenBank.cpp, ExprFunctions.hpp, ExprUtil.hpp, e.g. sample_code/src
GSQL.GithubUrl      # optional, used for github enterprise, e.g. https://api.github.com
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Example:
```
gadmin config set GSQL.GithubUserAcessToken anonymous
gadmin config set GSQL.GithubRepository tigergraph/ecosys
gadmin config set GSQL.GithubBranch demo_github
gadmin config set GSQL.GithubPath sample_code/src
gadmin config apply
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

When the GSQL server needs to compile the files, it will retrieve them from GitHub if the GitHub access is configured as above. It will retry 3 times, with a five-second timeout each time. If the connection fails, it will go to the next priority level method, i.e. file uploaded via `PUT` commands.
**Upload source code**
```
PUT TokenBank FROM "path/to/a/file"
PUT ExprFunctions FROM "path/to/a/file"
PUT ExprUtil FROM "path/to/a/file"
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**Example:**
```
temp_TokenBank=$tempDir/tmp_TokenBank.cpp
temp_ExprFunctions=$tempDir/tmp_ExprFunctions.hpp
temp_ExprUtil=$tempDir/tmp_ExprUtil.hpp
eval gsql 'PUT TokenBank FROM \"$temp_TokenBank\"'
eval gsql 'PUT ExprFunctions FROM \"$temp_ExprFunctions\"'
eval gsql 'PUT ExprUtil FROM \"$temp_ExprUtil\"'
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**Download source code**
```
GET TokenBank TO "path/to/a/file"
GET ExprFunctions TO "path/to/a/file"
GET ExprUtil TO "path/to/a/file"
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**Example:**
```
temp_TokenBank2=$tempDir/tmp_TokenBank_2.cpp
temp_ExprFunctions2=$tempDir/tmp_ExprFunctions_2.hpp
temp_ExprUtil2=$tempDir/tmp_ExprUtil_2.hpp
echo "GET TokenBank.cpp, ExprFunctions.hpp and ExprUtil.hpp to current node."
eval gsql 'GET TokenBank TO \"$temp_TokenBank2\"'
eval gsql 'GET ExprFunctions TO \"$temp_ExprFunctions2\"'
eval gsql 'GET ExprUtil TO \"$temp_ExprUtil2\"'
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The uploaded files will be saved to all nodes. Users need to have the `READ_FILE` privilege to run `GET` and the `WRITE_FILE` privilege to run `PUT`.
With the GET command, the user can download the corresponding file from the primary node to a local directory at the current cluster node.
With the PUT command, the local file will be copied to all cluster nodes, including itself.
**Example usage scenario to update the files:**
```
// Download the current file via GET, or create a new file from draft;
GET TokenBank TO "/myFolder/file.cpp"
// Upload the file via PUT
PUT TokenBank FROM "/myFolder/file.cpp"
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

For each cluster node, TokenBank.cpp is stored at:
```
 $(gadmin config get System.DataRoot)/gsql/tokenbank/
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

ExprFunctions.hpp and ExprUtil.hpp files are stored at:
```
 $(gadmin config get System.DataRoot)/gsql/udf/
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The full path should be provided including the file name for PUT/GET, eg:
```
put ExprFunctions from "/home/path/tmp/ExprFunc.hpp"
get TokenBank to "doc/path/tmp/myTB.cpp"
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

In the first command, we used the absolute path, while in the second command, we used the relative path. Both are supported, however, `~` is not supported (such as in `~/tmp/x.hpp`).
If you use a folder name, the default file name will be used.
```
put ExprFunctions from "/home/path/tmp"
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This will use an ExprFunctions.hpp file under the server directory "/home/path/tmp" for PUT.
```
get TokenBank to "home/path/tmp/"
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This will create/overwrite the file "home/path/tmp/TokenBank.cpp".
If the file name is given in the path, its file extension must match the file type expected.
```
put ExprFunctions from "/home/path/tmp/test1.gsql"
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This is not allowed, since PUT/GET ExprFunctions must use `.hpp` as the file extension.
#### [](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server#_default_file_shipped_with_tigergraph_package)Default file shipped with TigerGraph package
If the corresponding file is not found, the GSQL Primary server will use the default file in the package. These default files are at:
```
$(gadmin config get System.AppRoot)/dev/gdk/gsql/src/TokenBank/TokenBank.cpp
$(gadmin config get System.AppRoot)/dev/gdk/gsql/src/QueryUdf/ExprUtil.hpp
$(gadmin config get System.AppRoot)/dev/gdk/gsql/src/QueryUdf/ExprFunctions.hpp
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server#_file_path_configuration)File Path Configuration
Before TigerGraph version 3.1, the file path used in loading jobs referred to the file in m1, unless the user specified the machine name before the path `(ALL, ANY, m1, m2,…​)`. Now, the primary server can be running on any machine, and can be switched. This means the GSQL server may or may not find the file. To be backwards-compatible with previous versions of TigerGraph, prefix a machine name if the client is in the TigerGraph cluster.
Users can specify the node ID before the path using `ALL, ANY, m1, m2` and so on. Declaring ALL or ANY as host ID will load files from every cluster node.
Use the syntax `m1|m3|m4` to declare the combination of several nodes.
If the hosts are not specified, it will look for the host ID of the current node that is running the loading job, (through searching the nodes in $(gadmin config get GSQL.BasicConfig.Nodes)). If not found, it will use node `m1` by default.
```
# current refers to /path/to/csv in m1
LOAD "/path/to/csv" TO VERTEX vt VALUES($0)
LOAD "ALL:/path/to/csv" TO VERTEX vt VALUES($0)
LOAD "m1|m2:/path/to/csv" TO VERTEX vt VALUES($0)
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

A data source can be created and used with a file path or a JSON string.
```
create data_source kafka k1 for graph poc_graph
set k1 = "/tmp/kafka_config.json"
create data_source kafka k2 = "/tmp/kafka_config.json"
CREATE LOADING JOB load_kafka FOR GRAPH poc_graph {
 DEFINE FILENAME f1 = "$k1:/tmp/topic_partition_config.json";
 LOAD f1
   TO VERTEX MyNode VALUES ($2)
   USING SEPARATOR="|";
}
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server#_gsql_client_connection_setup)GSQL Client connection setup
The GSQL client can connect to the GSQL server in one of several ways according to the following priority order:
#### [](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server#_using_ip_address)Using IP address
Users can specify the IP address and port when calling the GSQL client using `gsql -i` or `gsql -ip`. For example:
```
gsql -ip 192.168.11.32:14240,192.168.11.34:14240,192.168.11.36
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The GSQL clients will try these IPs and ports one by one. The port is optional. Port `14240`, the default port for the GSQL server, will be used if no port is specified.
#### [](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server#_using_gsql_ip_configuration)Using GSQL IP Configuration
If `gsql -i` or `gsql -ip` are not used, the GSQL client will search the file `gsql_server_ip_config` where the user runs the GSQL client. The file gsql_server_ip_config should be a one-line file such as shown below. GSQL client will traverse the ips and ports in the file in its order.
```
172.18.0.101,172.18.0.102:14240,172.18.0.103:14240
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The port number is also optional here, using `14240` by default.
#### [](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server#_using_default_local_server)Using default local server
If `gsql -i` or `gsql -ip` are not used, and the file `gsql_server_ip_config` does not exist where `gsql` is called, the GSQL client will try to connect to the local server at `127.0.0.1:8123`.
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


