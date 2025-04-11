![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/fine-grained-query-privileges)[Next](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/fine-grained-query-privileges)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/fine-grained-query-privileges)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/fine-grained-query-privileges)
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
  * [Fine-Grained Query Privileges](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/fine-grained-query-privileges)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/4.2/modules/user-access/pages/fine-grained-query-privileges.adoc)
### Contents
  * [Summary](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/fine-grained-query-privileges#_summary)
  * [Usage Examples](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/fine-grained-query-privileges#_usage_examples)
  * [Legacy RBAC Privilege Syntax Usage](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/fine-grained-query-privileges#_legacy_rbac_privilege_syntax_usage)
  * [Turn On/Off Legacy RBAC Syntax Usage](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/fine-grained-query-privileges#_turn_onoff_legacy_rbac_syntax_usage)
  * [Behaviour Changes In Legacy RBAC Privilege Syntax Related With Query Privileges](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/fine-grained-query-privileges#_behaviour_changes_in_legacy_rbac_privilege_syntax_related_with_query_privileges)
  * [Forbidden Legacy RBAC Privilege Syntax Related With Query Privileges](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/fine-grained-query-privileges#_forbidden_legacy_rbac_privilege_syntax_related_with_query_privileges)


# Fine-Grained Query Privileges
### Contents
  * [Summary](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/fine-grained-query-privileges#_summary)
  * [Usage Examples](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/fine-grained-query-privileges#_usage_examples)
  * [Legacy RBAC Privilege Syntax Usage](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/fine-grained-query-privileges#_legacy_rbac_privilege_syntax_usage)
  * [Turn On/Off Legacy RBAC Syntax Usage](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/fine-grained-query-privileges#_turn_onoff_legacy_rbac_syntax_usage)
  * [Behaviour Changes In Legacy RBAC Privilege Syntax Related With Query Privileges](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/fine-grained-query-privileges#_behaviour_changes_in_legacy_rbac_privilege_syntax_related_with_query_privileges)
  * [Forbidden Legacy RBAC Privilege Syntax Related With Query Privileges](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/fine-grained-query-privileges#_forbidden_legacy_rbac_privilege_syntax_related_with_query_privileges)


## [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/fine-grained-query-privileges#_summary)Summary
In earlier versions of TigerGraph prior to 4.1, query privileges in TigerGraph are managed at the global and graph level with `READ_QUERY` and `WRITE_QUERY` privileges. For example, if a user has `READ_QUERY` privilege on graph `g1`, then the user can read any queries under graph `g1`. If a user has `WRITE_QUERY` privilege on global, then the user can create or replace any query under any graph in TigerGraph.
With fine-grained query privileges, the following changes will take effect:
  * `WRITE_QUERY` privilege is deprecated. It has been split into privileges such as `CREATE_QUERY`, `UPDATE_QUERY` and `DROP_QUERY`.
  * New privileges `INSTALL_QUERY`, `EXECUTE_QUERY` and `OWNERSHIP` are added.


`OWNERSHIP` is a special privilege introduced in version 4.1. It is granted automatically to the user who creates a query. The entity (a user or a role) who owns a query holds all privileges on a query. That means this entity can read, update, drop, install, and execute this query. An entity with `OWNERSHIP` privilege (e.g., the creator) on a query can grant privileges to other entities, including the `OWNERSHIP` privilege. Once the `OWNERSHIP` privilege is granted to another entity, the previous owner loses `OWNERSHIP` privilege on this query. Each object can have only one explicit owner entity. Users with the `superuser` role hold the `OWNERSHIP` privilege on all queries in all graphs implicitly. Users with the `admin` role in one graph hold the `OWNERSHIP` privilege on all queries in this graph implicitly.  
---  
  * Query privilege scope changes:
    * `CREATE_QUERY` privilege can only be granted/revoked at global and graph level.
    * `READ_QUERY`, `UPDATE_QUERY`, `DROP_QUERY`, `INSTALL_QUERY` and `EXECUTE_QUERY` privileges can only be granted/revoked at individual query level.
    * `OWNERSHIP` privilege can only be granted at the individual query level and only to one entity, e.g.: a user or a user-defined role.


With above changes, corresponding grant/revoke commands and query related operations are also changed. Details of such changes will be displayed in the following sections.
## [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/fine-grained-query-privileges#_usage_examples)Usage Examples
We strongly recommend using object-based syntax for granting/revoking fine-grained query privileges.  
---  
Below are several commands for common use cases of granting/revoking fine-grained query privileges.
Example: Grant `CREATE` privilege at global level to role `r1`:
```
GSQL > GRANT CREATE ON ALL QUERIES IN GLOBAL to r1
The privilege "CREATE" is successfully granted on "ALL QUERIES" IN GLOBAL to role: r1
```

Note that `UPDATE` privilege depends on `READ` privilege. You need to grant `READ` before `UPDATE`, and revoke `UPDATE` before `READ`.
Example: Grant `READ` and `UDPATE` privileges on existing specific query objects `q1`, `q2` in graph `g1` to user `u1`:
```
GSQL > GRANT READ, UPDATE ON QUERY q1, q2 IN GRAPH g1 to u1
The privileges "READ, UPDATE" are successfully granted on "QUERY q1, q2" IN GRAPH g1 to user: u1
```

Example: Revoke `INSTALL` and `EXECUTE` privileges on all existing queries at global level from user `u1`:
```
GSQL > REVOKE INSTALL, EXECUTE ON ALL QUERIES IN GLOBAL FROM u1
The privileges "EXECUTE, INSTALL" are successfully revoked on "ALL QUERIES" IN GLOBAL from user: u1
```

If you want to revoke query privileges on specific existing query objects from a user or a role, make sure the user or role has the query privileges on all involved query objects.
Ex. Revoke `DROP` privileges on existing specific query objects `q1`, `q2` in graph `g1` from role `r1`:
```
// role r1 must already have DROP privilege on query q1, q2.
GSQL > REVOKE DROP ON QUERY q1, q2 IN GRAPH g1 FROM r1
The privilege "DROP" is successfully revoked on "QUERY q1, q2" IN GRAPH g1 from role: r1
```

For individual query level privileges, you can only grant/revoke on existing query objects.  
---  
Example: Grant `READ` and `UDPATE` privileges on existing queries `q1`, `q2` in graph `g1` to user `u1`, then create new query `q3`:
```
GSQL > use graph g1
GSQL > GRANT READ, UPDATE ON ALL QUERIES IN GRAPH g1 to u1
GSQL > show privilege on user u1
User: "u1"
 - Graph 'g1' Privileges:
   - Query 'q1' Privileges:
    READ_QUERY
    UPDATE_QUERY
   - Query 'q2' Privileges:
    READ_QUERY
    UPDATE_QUERY
GSQL > create query q3() for graph g1 {print "q3";}
GSQL > show privilege on user u1
User: "u1"
 - Graph 'g1' Privileges:
   - Query 'q1' Privileges:
    READ_QUERY
    UPDATE_QUERY
   - Query 'q2' Privileges:
    READ_QUERY
    UPDATE_QUERY
```

Example: Grant `OWNERSHIP` privilege on existing query q3 in graph `g1` to user `u1`:
```
GSQL > use graph g1
GSQL > GRANT OWNERSHIP ON QUERY q3 IN GRAPH g1 TO u1
Transfer the ownership of query q3 in graph g1 from entity tigergraph to entity u1
The privilege "OWNERSHIP" is successfully granted on "QUERY q3" IN GRAPH g1 to user: u1
GSQL > show privilege on user u1
User: "u1"
 - Graph 'g1' Privileges:
   - Query 'q1' Privileges:
    READ_QUERY
    UPDATE_QUERY
   - Query 'q2' Privileges:
    READ_QUERY
    UPDATE_QUERY
   - Query 'q3' Privileges:
    OWNER
```

After this step, `u1` becomes the owner of `q3` and owns all privileges on `q3`. `u1` can read, update, drop, install, and execute query `q3`. At the same time, `u1` can grant the query privileges to other entities, including the `OWNERSHIP` privilege.  
---  
## [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/fine-grained-query-privileges#_legacy_rbac_privilege_syntax_usage)Legacy RBAC Privilege Syntax Usage
With the introduction of new fine-grained query privileges, there are certain query privilege syntax usages become deprecated. If you still want to use them, you can control via adding/removing `ALLOW_LEGACY_RBAC_SYNTAX=true` in `GSQL.BasicConfig.Env`.
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/fine-grained-query-privileges#_turn_onoff_legacy_rbac_syntax_usage)Turn On/Off Legacy RBAC Syntax Usage
Ex. Adding `ALLOW_LEGACY_RBAC_SYNTAX=true`
```
$ gadmin config get GSQL.BasicConfig.Env
CPATH=$CPATH; LD_LIBRARY_PATH=$LD_LIBRARY_PATH;
$ gadmin config set 'GSQL.BasicConfig.Env CPATH=$CPATH; LD_LIBRARY_PATH=$LD_LIBRARY_PATH;ALLOW_LEGACY_RBAC_SYNTAX=true;'
$ gadmin config apply -y
$ gadmin restart gsql -y
```

Ex. Removing `ALLOW_LEGACY_RBAC_SYNTAX=true`
```
$ gadmin config get GSQL.BasicConfig.Env
CPATH=$CPATH; LD_LIBRARY_PATH=$LD_LIBRARY_PATH; ALLOW_LEGACY_RBAC_SYNTAX=true;
$ gadmin config set 'GSQL.BasicConfig.Env CPATH=$CPATH; LD_LIBRARY_PATH=$LD_LIBRARY_PATH;'
$ gadmin config apply -y
$ gadmin restart gsql -y
```

### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/fine-grained-query-privileges#_behaviour_changes_in_legacy_rbac_privilege_syntax_related_with_query_privileges)Behaviour Changes In Legacy RBAC Privilege Syntax Related With Query Privileges
Certain legacy privilege commands related with query privileges will change its behavior starting in 4.1.
  * `GRANT PRIVILEDGE WRITE_QUERY ON GLOBAL TO r1`
    * `CREATE_QUERY` privilege will be granted on all existing graphs to role `r1`.
    * `READ_QUERY`, `UPDATE_QUERY`, `DROP_QUERY`, `INSTALL_QUERY`, `EXECUTE_QUERY` privileges will be granted on all existing queries in each of existing graphs.
  * `GRANT PRIVILEDGE READ_QUERY ON GRAPH g1 TO r1`
    * `READ_QUERY` privilege will be granted on all existing queries in graph `g1` to role `r1`.
  * `GRANT WRITE ON ALL QUERIES IN GRAPH g1 TO r1`
    * `CREATE_QUERY` privilege will be granted on graph `g1` to role `r1`
    * `READ_QUERY`, `UPDATE_QUERY`, `DROP_QUERY`, `INSTALL_QUERY`, `EXECUTE_QUERY` privileges will be granted on all existing queries in graph `g1` to role `r1`.


### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/fine-grained-query-privileges#_forbidden_legacy_rbac_privilege_syntax_related_with_query_privileges)Forbidden Legacy RBAC Privilege Syntax Related With Query Privileges
Forbidden legacy RBAC privilege syntax usages are no longer supported even if `ALLOW_LEGACY_RBAC_SYNTAX=true` is set.  
---  
  * `REVOKE PRIVILEGE WRITE_QUERY ON [GRAPH <graph_name> | GLOBAL ] FROM <role_name>`
    * Directly revoking `WRITE_QUERY` privilege in a graph or in global is no longer supported.
  * `REVOKE PRIVILEGE READ_QUERY ON [GRAPH <graph_name> | GLOBAL ] FROM <role_name>`
    * Directly revoking `READ_QUERY` privilege in a graph or in global is no longer supported.
  * `REVOKE WRITE ON ALL QUERIES IN [GRAPH <graph_name> | GLOBAL] FROM <role_name>`
    * Directly revoking `WRITE` on all existing query objects in a graph or in all graphs is no longer supported.


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


