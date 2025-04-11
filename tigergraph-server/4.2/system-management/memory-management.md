![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management)[Next](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management)
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
  * [Resources and Processes](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/resource-and-process-mgmt)
  * [Memory Management](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/4.2/modules/system-management/pages/memory-management.adoc)
### Contents
  * [Memory usage key factors](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management#_memory_usage_key_factors)
  * [Monitor memory usage](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management#_monitor_memory_usage)
  * [Monitor query memory usage](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management#_monitor_query_memory_usage)
  * [Monitor system free memory percentage](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management#_monitor_system_free_memory_percentage)
  * [Memory State Thresholds](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management#_memory_state_thresholds)
  * [Configure Memory State Thresholds](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management#_configure_memory_state_thresholds)
  * [Limit query memory usage](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management#_limit_query_memory_usage)
  * [By system configuration](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management#_by_system_configuration)
  * [By HTTP header](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management#_by_http_header)


# Memory management
### Contents
  * [Memory usage key factors](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management#_memory_usage_key_factors)
  * [Monitor memory usage](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management#_monitor_memory_usage)
  * [Monitor query memory usage](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management#_monitor_query_memory_usage)
  * [Monitor system free memory percentage](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management#_monitor_system_free_memory_percentage)
  * [Memory State Thresholds](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management#_memory_state_thresholds)
  * [Configure Memory State Thresholds](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management#_configure_memory_state_thresholds)
  * [Limit query memory usage](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management#_limit_query_memory_usage)
  * [By system configuration](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management#_by_system_configuration)
  * [By HTTP header](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management#_by_http_header)


This page explains the key factors that affect memory usage in TigerGraph, as well as how to:
  * Monitor memory usage
  * Configure memory thresholds
  * Manage query workload distribution


## [](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management#_memory_usage_key_factors)Memory usage key factors
Below are the major factors that impact memory usage in TigerGraph:
  * Data volume
    * The biggest factor that affects memory usage in TigerGraph is the amount of data you have. Most database operations require more memory the more data you have.
  * Queries
    * Queries that read or write a high volume of data use more memory.
    * In a distributed cluster, a non-distributed query can be memory-intensive for the node where the query is run. See [Distributed Query Mode](https://docs.tigergraph.com/gsql-ref/4.2/querying/distributed-query-mode).


## [](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management#_monitor_memory_usage)Monitor memory usage
You can monitor memory usage by query and by machine.
### [](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management#_monitor_query_memory_usage)Monitor query memory usage
TigerGraph’s Graph Processing Engine (GPE) records memory usage by query at different stages of the query and saves it to the GPE logs at `$(gadmin config get System.LogRoot)/gpe/log.INFO`. This is an estimation of the query’s memory usage **on a particular node** in a TigerGraph cluster.
The log levels are set with the `gadmin` configuration command `GPE.BasicConfig.LogConfig.LogLevel`, which has the values `OFF`, `BRIEF (default)`, `DEBUG`, and `VERBOSE`.
You can monitor how much memory a query is using by searching the log file for the request ID and filter for lines that contain `"QueryMem"`:
```
$ grun all 'grep -i <request_id> $(gadmin config get System.LogRoot)/gpe/log.INFO | grep -i "querymem"'
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

You can also run a query first, and then run the following command immediately after to retrieve the most recent query logs and filter for `"QueryMem"`:
```
$ grep 'tail -n 50 $(gadmin config get System.LogRoot)/gpe/log.INFO |
  grep -i "querymem"'
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management#_step_by_step_query_memory_logging)Step by step query memory logging
This type of query memory logging may not appear for some queries due to the way GSQL handles querying internally. Specifically, it applies for queries run in GPR mode: `DISTRIBUTED` mode queries, queries run with `INTERPRET`, or when the session parameter `single_gpr` is set to `true`. Furthermore, it only appears at log levels `DEBUG` or `VERBOSE`.  
---  
The logs show memory usage by the query at different stages of its execution. The number at the end of each line indicates the number of bytes of memory utilized by the query.
The reported query memory usage is only a partial estimation of the query’s memory usage. When `STRING` and container type of local accumulators (ListAccum, MapAccum, ArrayAccum, HeapAccum, SetAccum, BagAccum) are used, the difference between the reported usage and the actual usage can differ greatly, as the memory tracker cannot accurately report the sizes of such types. The best way to evaluate the reported memory usage number is to compare the memory usage of different runs of the same query. If two runs of the same query report different numbers in terms of their memory usage, it is very likely that the query run reporting higher memory usage actually used more memory than the query run reporting lower memory usage.  
---  
For example, if we query for the memory usage for request ID `2.RESTPP_1_1.1665503463466.N` with the following command:
```
$ grun all 'grep -i 2.RESTPP_1_1.1665503463466.N $(gadmin config get System.LogRoot)/gpe/log.INFO | grep -i "querymem"'
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

We get the following response from two different nodes in a cluster:
```
I1011 08:51:03.478861 199860 gpr.cpp:206] Engine_MemoryStats|{request}|MONITORING Step{step} BeforeRun[GPR][QueryMem]{current_mem},watermark:{mem_watermark}|request:WorkerManager,4.GPE_1_2.1665503463470.N:2.RESTPP_1_1.1665503463466.N,NNN,15,0,0,0,S|step:1|current_mem:0|mem_watermark:0
I1011 08:51:04.369922 199860 gpr.cpp:265] Engine_MemoryStats|{request}|MONITORING Step{step} AfterRun[GPR][QueryMem]{current_mem},watermark:{mem_watermark}|request:WorkerManager,4.GPE_1_2.1665503463470.N:2.RESTPP_1_1.1665503463466.N,NNN,15,0,0,0,S|step:1|current_mem:132960052|mem_watermark:157689448
I1011 08:51:04.659490 199860 gpr.cpp:206] Engine_MemoryStats|{request}|MONITORING Step{step} BeforeRun[GPR][QueryMem]{current_mem},watermark:{mem_watermark}|request:WorkerManager,4.GPE_1_2.1665503463470.N:2.RESTPP_1_1.1665503463466.N,NNN,15,0,0,0,S|step:2|current_mem:132960052|mem_watermark:157689448
I1011 08:51:04.819167 199860 gpr.cpp:265] Engine_MemoryStats|{request}|MONITORING Step{step} AfterRun[GPR][QueryMem]{current_mem},watermark:{mem_watermark}|request:WorkerManager,4.GPE_1_2.1665503463470.N:2.RESTPP_1_1.1665503463466.N,NNN,15,0,0,0,S|step:2|current_mem:178609044|mem_watermark:19465093
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The following uses the third line as an example:
```
I1011 08:51:04.659490 199860 gpr.cpp:206] \
Engine_MemoryStats|{request}|MONITORING Step{step} BeforeRun[GPR][QueryMem]{current_mem}, \
watermark:{mem_watermark}| \
request:WorkerManager,4.GPE_1_2.1665503463470.N:2.RESTPP_1_1.1665503463466.N,NNN,15,0,0,0,S **(1)**
|step:2| \ **(2)**
current_mem:132960052 \ **(3)**
|mem_watermark:157689448 **(4)**
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | The request’s full ID. Note `GPE_1_2` which tells you this line of log is coming from the second node in the primary replica.  
---|---  
**2** | Internally, a query’s execution consists of many steps. This indicates the step at which the log is generated, which is helpful for TigerGraph Support during debugging.  
**3** | The current amount of memory held by the query at the time the log is taken.  
**4** | The maximum amount of memory held by the query during the course of its run.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management#_post_completion_query_memory_logging)Post-completion query memory logging
These logs appear at `BRIEF` or higher logging levels.
Upon completion of a query, TigerGraph prints out a single log line summary about the request. This log line contains the query’s overall memory usage info and looks like the following:
```
Request|ldbc_snb::default,16973825.RESTPP_1_1.1676405639909.N,NNN,16,0,0,S|Finished in 259.595 ms|Response 98 bytes|Id conversion 0|mem watermark(MiB): 0
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

To search this line, first find the request ID. Then run the following server command using your request ID.
```
grun all 'grep -i "<request id>" $(gadmin config get System.LogRoot)/gpe/INFO.* | grep -i "Finished in" | grep "mem watermark"'
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management#_monitor_system_free_memory_percentage)Monitor system free memory percentage
#### [](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management#_through_admin_portal)Through Admin Portal
If you have access to Admin Portal, you can monitor memory usage by node through the cluster monitoring tool in the [Dashboard](https://docs.tigergraph.com/gui/4.2/admin-portal/dashboard).
#### [](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management#_through_linux_commands)Through Linux commands
The following is a list of Linux commands to measure system memory and check for out-of-memory errors:
  * To check available memory on a node, run [`free -h`](https://man7.org/linux/man-pages/man1/free.1.html).
    * Use with [`grun`](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/cluster-commands#_run_commands_on_multiple_nodes) to check available memory on every node.
  * To view CPU and memory details interactively, run [`top`](https://man7.org/linux/man-pages/man1/top.1.html).
  * When a query is aborted, run [`dmesg -T`](https://man7.org/linux/man-pages/man1/dmesg.1.html)` | grep -i “oom”` to check for out of memory errors
```
[Thu Feb 4 00:41:08 2021] google_osconfig invoked oom-killer: gfp_mask=0x201da, order=0, oom_score_adj=0 **(1)**
[Thu Feb 4 00:41:08 2021] [<ffffffffafdc208d>] oom_kill_process+0x2cd/0x490
[Thu Feb 4 00:41:08 2021] [ pid ]  uid tigergraph total_vm   rss nr_ptes swapents oom_score_adj name
[Thu Feb 4 00:41:09 2021] [20183] 1004 20183 20200397  377046  5701    0       0 tg_dbs_restd
[Thu Feb 4 00:41:09 2021] Out of memory: Kill process 20183 (tg_dbs_restd) score 239 or sacrifice child
[Thu Feb 4 00:41:09 2021] Killed process 20183 (tg_dbs_restd), UID 1004, total-vm:80801588kB, anon-rss:1508400kB, file-rss:0kB, shmem-rss:0kB
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | If you see a line that says something invoked oom-killer, it means the node ran out of memory.  
---|---  


## [](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management#_memory_state_thresholds)Memory State Thresholds
GPE has memory protection to prevent out-of-memory issues. There are three memory states: 

Healthy
    
There is a healthy amount of free memory. All system operations run normally for best performance. 

Alert
    
There is a shortage of free memory. TigerGraph’s GPE system enables mechanisms to alleviate the memory pressure by moving some data onto disks and trying to use the maximum allowed threads for rebuilding. This starts to slow down the processing of new requests until the long-running queries finish and release memory. 

Critical
    
There is a critical shortage of free memory. TigerGraph’s GPE starts to abort queries to ensure system stability.
TigerGraph implements memory protection thresholds through the following environment variables. By default, the thresholds are only effective when a machine has more than 30 GB of total memory: 

`SysAlertFreePct`
    
The free memory threshold that causes TigerGraph to enter the Alert state. Default value is 30%. 

`SysMinFreePct`
    
The free memory threshold that causes TigerGraph to enter the Critical state. Default value is 10%.
### [](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management#_configure_memory_state_thresholds)Configure Memory State Thresholds
To configure these environment variables, run `gadmin config entry GPE.BasicConfig.Env`. This shows the current values of the environment variables and allows you to add new entries:
```
$ gadmin config entry GPE.BasicConfig.Env
✔ New: LD_PRELOAD=$LD_PRELOAD; LD_LIBRARY_PATH=$LD_LIBRARY_PATH; CPUPROFILE=/tmp/tg_cpu_profiler; CPUPROFILESIGNAL=12; MALLOC_CONF=prof:true,prof_active:false▐
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Add your desired memory threshold configuration after the existing environment values. Use a semicolon `;` to separate the different environment variables:
```
✔ New: LD_PRELOAD=$LD_PRELOAD; LD_LIBRARY_PATH=$LD_LIBRARY_PATH; CPUPROFILE=/tmp/tg_cpu_profiler; CPUPROFILESIGNAL=12; MALLOC_CONF=prof:true,prof_active:false;SysMinFreePct=5;SysAlertFreePct=25; **(1)**
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | This sets the critical threshold to 5 percent and the alert threshold to 25 percent.  
---|---  
Spaces have been added to the following full example for readability.
```
> gadmin config entry GPE.BasicConfig.Env
GPE.BasicConfig.Env [ LD_PRELOAD=$LD_PRELOAD; LD_LIBRARY_PATH=$LD_LIBRARY_PATH; CPUPROFILE=/tmp/tg_cpu...(too long to show the full content, please use 'gadmin config get GPE.BasicConfig.Env' to get it) ]:
The runtime environment variables, separated by ';'
✔ New: LD_PRELOAD=$LD_PRELOAD; LD_LIBRARY_PATH=$LD_LIBRARY_PATH; CPUPROFILE=/tmp/tg_cpu_profiler; CPUPROFILESIGNAL=12; MALLOC_CONF=prof:true,prof_active:false
; SysMinFreePct=20;SysAlertFreePct=30 **(1)**
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | In this example, the user has set `SysMinFreePct` to `20`, meaning that queries will start aborting automatically for stability when 20% of system memory is free (80% utilization). The user has also set `SysAlertFreePct` to `30`, so queries will start being throttled at 30% free memory (70% utilization).  
---|---  
#### [](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management#_apply_and_restart)Apply and Restart
After making a change, run `gadmin config apply` to apply the changes and `gadmin restart gpe` to restart the GPE service. Changes will take effect after the restart.
## [](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management#_limit_query_memory_usage)Limit query memory usage
There are two ways to limit the memory usage of queries:
  * By system configuration. This affects all queries on your TigerGraph instance.
  * By HTTP request header. This affects one specific query run only and overrides the system configuration.


### [](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management#_by_system_configuration)By system configuration
You can set a limit of how much memory a query is allowed to use on any single node in a cluster. If a query’s memory usage exceeds this limit on any node in a cluster, the query is aborted automatically.
To set a limit for memory usage on any node for a cluster, use the `gadmin config` command to configure the value of the parameter `GPE.QueryLocalMemLimitMB`. For example, to set the limit to 100 MB, run the following command:
```
$ gadmin config set GPE.QueryLocalMemLimitMB 100
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

You must [restart the GPE service](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/manage-services#_start_stop_or_restart_a_service) for the change to take effect.
### [](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management#_by_http_header)By HTTP header
Another way to limit the query memory usage is to specify the memory limit at the time of the request through the HTTP header `GSQL-QueryLocalMemLimitMB` when using the [Run Query REST endpoint](https://docs.tigergraph.com/tigergraph-server/4.2/API/built-in-endpoints#_run_an_installed_query_post). This applies to the specific request being run only, and overrides the system configuration.
For example, to set the limit to 100 MB, make the following request:
```
curl -X POST -H "GSQL-QueryLocalMemLimitMB: 100" -d '{"p":{"id":"Tom","type":"person"}}'
"http://localhost:14240/restpp/query/social/hello"
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


