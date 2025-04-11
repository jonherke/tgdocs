![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/)[Next](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/)
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
  * [TigerGraph DB Release Notes](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/4.2/modules/release-notes/pages/index.adoc)
### Contents
  * [Key New Features](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_key_new_features)
  * [Detailed List of New and Modified Features](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_detailed_list_of_new_and_modified_features)
  * [System Management Enhancements](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_system_management_enhancements)
  * [Security and Access Control Enhancements](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_security_and_access_control_enhancements)
  * [Integration Enhancements](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_integration_enhancements)
  * [API Enhancements](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_api_enhancements)
  * [Query Language Enhancements](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_query_language_enhancements)
  * [Loading Enhancemnts](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_loading_enhancemnts)
  * [Performance Improvements](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_performance_improvements)
  * [GraphStudio, Admin Portal, and Insights](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_graphstudio_admin_portal_and_insights)
  * [Fixed issues](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_fixed_issues)
  * [Fixed and Improved in 4.2.0](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_fixed_and_improved_in_4_2_0)
  * [Compatibility Issues](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_compatibility_issues)
  * [Deprecations](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_deprecations)
  * [Release notes for previous versions](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_release_notes_for_previous_versions)


# TigerGraph DB Release Notes
Table of Contents
  * [Key New Features](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_key_new_features)
  * [Detailed List of New and Modified Features](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_detailed_list_of_new_and_modified_features)
    * [System Management Enhancements](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_system_management_enhancements)
    * [Security and Access Control Enhancements](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_security_and_access_control_enhancements)
    * [Integration Enhancements](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_integration_enhancements)
    * [API Enhancements](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_api_enhancements)
    * [Query Language Enhancements](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_query_language_enhancements)
    * [Loading Enhancemnts](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_loading_enhancemnts)
    * [Performance Improvements](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_performance_improvements)
    * [GraphStudio, Admin Portal, and Insights](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_graphstudio_admin_portal_and_insights)
  * [Fixed issues](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_fixed_issues)
    * [Fixed and Improved in 4.2.0](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_fixed_and_improved_in_4_2_0)
    * [Compatibility Issues](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_compatibility_issues)
    * [Deprecations](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_deprecations)
  * [Release notes for previous versions](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_release_notes_for_previous_versions)


TigerGraph Server 4.2.0 Preview was released on April 3, 2025.
TigerGraph Server 4.2.0 Alpha was released on March 4, 2025.
TigerGraph 4.2’s feature set is an enhancement of what was available in 4.1.2. Therefore, features that were in 4.1.2 are not considered New Features.  
---  
## [](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_key_new_features)Key New Features
  * **[Hybrid Vector Search](https://docs.tigergraph.com/gsql-ref/4.2/vector/)** : Scalable storage and similarity search for vector attributes associated with vertices.
    * New `VECTOR` attribute data type with real-time updates
    * Fast approximate nearest neighborhood (ANN), with automatic indexing, incremental indexing
    * hybrid graph + vector search in GSQL
  * **[Incremental Backup](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/incremental-backup)** which efficiently backs up only what has changed since the last backup/restore event.
  * **[Rolling Upgrades of maintenance versions](https://docs.tigergraph.com/tigergraph-server/4.2/installation/upgrade#_rolling_upgrade)** for HA clusters (Preview).
  * **[GQL/OpenCypher path pattern syntax](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/#_from_clause)** , within GSQL syntax
  * **Run ad hoc queries directly** ([non-procedural interpreted queries](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes))
  * **[Community Edition of TigerGraph Database](https://docs.tigergraph.com/tigergraph-server/4.2/intro/comparison-of-editions)** :
    * Up to 200GB graph data + 100GB vector data, single server only
    * Some enterprise features not included. Community support only
    * See the full [comparison of editions](https://docs.tigergraph.com/tigergraph-server/4.2/intro/comparison-of-editions).


## [](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_detailed_list_of_new_and_modified_features)Detailed List of New and Modified Features
### [](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_system_management_enhancements)System Management Enhancements
  * **[Incremental Backup](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/incremental-backup)** which efficiently backs up only what has changed since the last backup/restore event.
  * **[Rolling Upgrades of maintenance versions](https://docs.tigergraph.com/tigergraph-server/4.2/installation/upgrade#_rolling_upgrade)** for HA clusters (Preview).
  * **[Restore option`--keepusers`](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/restore-backup-same#_options_for_restore)** to keep the database users in the current database, not the ones from the backup file.
  * **Backup to[Azure](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/configurations#_backup_to_abs_azure_blob_storage) and [GCP](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/configurations#_backup_to_gcs_google_cloud_storage) cloud storage**, analogous to existing support for backup to AWS S3.
  * **More graceful[user-initiated shutdown](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/manage-services#_graceful_shutdown_of_restpp)** of RESTPP and GPE services.
  * **Backup HA Enhancement** : backup can still work even if a node is down or a region is down.
  * **[Kubernetes Operator update](https://github.com/tigergraph/ecosys/blob/master/k8s/README.md)**[ to v1.5.0](https://github.com/tigergraph/ecosys/blob/master/k8s/README.md) with numerous new features
    * CRR replication, Auto cluster monitoring during creation, upgrade pre-check support, rolling upgrades, backoff delay for job retries to improve resilience


### [](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_security_and_access_control_enhancements)Security and Access Control Enhancements
  * **[JWT authentication](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/jwt-token#_user_guide_overview) for all REST endpoints**, including GSQL endpoints.
  * **New[built-in role](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model#_built_in_roles): globalobserver**, used in Savanna, for minimal privileges: `READ_SCHEMA` and `READ_LOADINGJOB`.
  * **Two new[access privileges](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/row-policy-privileges-table): READ_LOG and APP_ACCESS_LOG** to grant read-only access to log files. `APP_ACCESS_LOG` is specifically designed for [ access from GraphStudio or Savanna](https://docs.tigergraph.com/gui/4.2/admin-portal/monitoring/log-viewer#_privilges).


### [](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_integration_enhancements)Integration Enhancements
  * **[Writing query output to an S3 object](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_s3_object)** can now be configured at the user session level instead at the system administration level, for better alignment of roles and privileges.
  * Updated Kafka from 2.5.1 to 3.6.2. Updated Zookeeper from 3.6.3 to 3.8.4.


### [](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_api_enhancements)API Enhancements
  * **New endpoints to[fetch schema information and sample data from Snowflake](https://docs.tigergraph.com/tigergraph-server/4.2/API/gsql-endpoints#_get_schema_information_from_a_snowflake_data_source)**.
  * Added a **REST endpoint to[delete user-defined function files](https://docs.tigergraph.com/tigergraph-server/4.2/API/gsql-endpoints#_delete_udt_files)**.
  * The **Interpret Query endpoint`POST /gsql/v1/queries/interpret`** can now be used with queries that have a [datetype parameter](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-operations#_complex_type_parameter_passing).
  * The **Edge Upsert endpoint** now supports [upserting the multiple edges of a discriminated edge](https://docs.tigergraph.com/tigergraph-server/4.2/API/upsert-rest#_upserting_multi_edges_with_discriminators) in a single API request.


### [](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_query_language_enhancements)Query Language Enhancements
  * Multiple enhancements to **Syntax V3** , which combines GSQL + OpenCypher + GQL Pattern Matching:
    * **[GQL/OpenCypher path pattern syntax](https://docs.tigergraph.com/gsql-ref/4.2/querying/select-statement/#_from_clause)** , within GSQL syntax
    * **Run ad hoc OpenCypher queries and single GSQL SELECT blocks directly** ([non-procedural interpreted queries](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-modes))
    * **[comparison operators`=` and `<>`](https://docs.tigergraph.com/gsql-ref/4.2/querying/operators-and-expressions#_comparison_operators_and_conditions)** as alternatives to `==` and `!=` in WHERE conditions.
    * **[OPTIONAL MATCH](https://github.com/tigergraph/ecosys/blob/master/tutorials/Cypher.md#optional-match), COALESCE, and IS [NOT] NULL** (OpenCypher)
    * **[type() and labels() functions](https://docs.tigergraph.com/gsql-ref/4.2/openCypher-in-gsql/#_opencypher_features_in_gsql)** (OpenCypher)
  * **[Map and List query parameter types](https://docs.tigergraph.com/gsql-ref/4.2/querying/data-types#_query_parameter_types)** are now supported.
  * **LIKE:[<string1> LIKE <string pattern>](https://docs.tigergraph.com/gsql-ref/4.2/querying/operators-and-expressions#_like)** can be used anywhere a condition is allowed, and <string pattern> can include functions.
  * **[Simple CASE expressions and Searched CASE expressions](https://docs.tigergraph.com/gsql-ref/4.2/querying/operators-and-expressions#_case_expressions)**
  * **Bitwise Accumulators** : official support for [comparison and bitwise logic operators](https://docs.tigergraph.com/gsql-ref/4.2/querying/accumulators#_bitwise_comparison_and_logic_operators).
  * **[Configuation parameter`GSQL.Github.Enabled`](https://docs.tigergraph.com/gsql-ref/4.2/querying/func/query-user-defined-functions#_use_github_to_store_udfs)** to enable retrieving UDFs from a Github repository.
  * **[Query Profiler](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-profiling)** to analyze query execution and performance.


### [](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_loading_enhancemnts)Loading Enhancemnts
  * **[Multi-character separators between data fields](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/creating-a-loading-job#_using_clause)** in loading jobs.


  * **[Schema Change options](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/modifying-a-graph-schema#_run_schema_change_options)** `-force` and `warn` to specify the behavior when loading jobs run during a schema change.
  * **Introduced[`DISABLED` Loading Job status](https://docs.tigergraph.com/gsql-ref/4.2/ddl-and-loading/modifying-a-graph-schema#_side_effects_of_schema_change)** for jobs which have a schema conflict as a result of a Schema Change.


### [](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_performance_improvements)Performance Improvements
  * **[Query Plan Caching](https://docs.tigergraph.com/gsql-ref/4.2/querying/query-optimizer/query-plan-cache)** , to speed up the run time of repeated queries.


### [](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_graphstudio_admin_portal_and_insights)GraphStudio, Admin Portal, and Insights
  * See the [release notes for Insights 4.2](https://docs.tigergraph.com/insights/4.2/release-notes/).


## [](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_fixed_issues)Fixed issues
### [](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_fixed_and_improved_in_4_2_0)Fixed and Improved in 4.2.0
#### [](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_functionality)Functionality
  * Fixed issue where the loading job status was incorrectly cleaned up in advance due to an inaccurate loading job counter (TP-4741).
  * Fixed issue where the loader would fail silently, and now it reports an error directly if the loader fails to start (TP-6420).
  * Fixed issue where loading an empty file triggered a failure loop (TP-6530).
  * Added the 'graph' field to CDC messages generated by the TigerGraph CDC service (CORE-4147).
  * Fixed issue with audit error codes being logged when a CDC message fails to deliver to external Kafka (CORE-4249).
  * Fixed critical disk issue caused by the rebuilder getting stuck in a partitioned cluster after dropping vertex or edge attributes (CORE-4303).
  * Fixed issue where CDC EDGE messages with "UNKNOWN" ID were not removed when a query deleted a vertex and edge simultaneously (CORE-4457).
  * Fixed issue where the primary ID was missing when inserting a vertex implicitly from loading an edge in a single-partition cluster and the target vertex used "primary_id_as_attribute=true" (GLE-7562).
  * Fixed issue with running the TigerGraph command `gcollect` on Kubernetes (TP-6353).
  * Added support for debug mode when a pod restart fails due to a PostStartHookError (TP-7228).
  * Added namespace as a suffix of the HostName in HostList on Kubernetes (TP-6214).
  * Fixed query compilation errors when iterating over `FOREACH` to retrieve an accum type attribute with the `-single` or `distributed` keyword; ensured operations between two different `GroupByAccums` hold the same data types and field names (GLE-8507).
  * Fixed issue with double quotes in literal strings during the creation of a loading job (GLE-8630).
  * Fixed the inability to fetch dynamic file output policy during query execution (GLE-4847).
  * Fixed issue where sensitive information was not removed from the browser localStorage, ensuring better security (APPS-1066)
  * Fixed a query installation failure for single-node queries that initialize vertex set variables in conditional branches, such as `if-else` or `case-when` statements (GLE-7369).
  * Added a button to refetch real-time graph statistics on the Load Data page in Graph Studio (APPS-2565).
  * Added the Standard Triangle Counting Algorithm to the built-in query list on the Write Query page in Graph Studio (APPS-3429).
  * Fixed the issue where query creation failed with a "query not found" prompt in Graph Studio (APPS-3624).
  * Removed the requirement to restart the GSQL service after modifying the SSO settings in Admin Portal (APPS-3167).
  * Allowed aborting a query in Graph Studio (APPS-3487).
  * Added a new page for changing passwords in TigerGraph Suite (APPS-3423).
  * Checked that the buffer length is non-negative before reading a file (TP-6690).
  * Fixed the issue where unauthorized users could access sensitive data, including superuser info, via the `/gsql/v1/users` API endpoint (GLE-8290).
  * Fixed `NoSuchElementException` thrown when removing all authentication tokens (GLE-8937).
  * Fixed issue with data source creation failing to sync to Disaster Recovery (DR) due to complex payload handling (GLE-9617).
  * Fixed bug with the `to_vertex_set` function (GLE-8083).
  * Unblocked the usage of the keyword “function” as a vertex/edge/attribute name (GLE-9803).
  * Fixed the backup restoration issue where GSQL was in a warmup state when importing GSQL data (TP-6949).
  * Fixed the metrics issue where `tigergraph_cpu_usage` exceeded 100 and `tigergraph_cpu_available` was negative under high load (TP-7127).
  * Fixed issue where failed backups in corner cases caused the Engine to pause for an extended period, leading to subsequent query timeouts (CORE-4532).
  * Fixed an issue where incremental backups could hang when based on a full backup with no data (CORE-4110).
  * Resolved the issue with downloading GSQL output files larger than 3GB in AdminPortal (APPS-3271).
  * Fixed an issue where the `GSQL-TIMEOUT` header was not being forwarded in the `/api/graphql/gsql` endpoint (APPS-3648).
  * Fixed a bug where local accumulators defined across multiple lines in a query were misinterpreted as a file in the GSQL client (GLE-8261).


#### [](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_improvements)Improvements
  * Improved performance of GSQL queries containing DELETE statements intended for deleting all vertices of a given type (GLE-8328).
  * Corrected the logic for the SelectVertex() function so it throws an error if the filePath is not an absolute path.


### [](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_compatibility_issues)Compatibility Issues
Description | Version Introduced  
---|---  
To apply a [File Input Policy](https://docs.tigergraph.com/tigergraph-server/4.2/security/gsql-file-input-policy) or [File Output Policy](https://docs.tigergraph.com/tigergraph-server/4.2/security/file-output-policy) change, now both `gsql` and `restpp` servers must be restarted: `gadmin restart gsql restpp -y` | v4.2.0  
The [`--incremental` option for backup](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/incremental-backup) now performs a true incremental backup instead of a differential backup. | v4.2.0  
In [CDC messages](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/change-data-capture/cdc-message-example#_message_examples), the format of **tuple values** has changed. | v4.2.0  
SelectVertex() may not be used with a relative filepath but previously this was not enforced. It is now enforced. | v4.2.0  
The 'graph' field is now included in [CDC messages](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/change-data-capture/cdc-message-example#_message_examples) generated by the TigerGraph CDC service. | v3.11.0, v4.1.1  
In [CDC messages](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/change-data-capture/cdc-message-example#_message_examples), the format of **map values** has changed. | v3.11.0, v4.1.1  
A full export package now includes access policies and template queries. | v4.1.0  
Users could encounter file input/output policy violations when upgrading a TigerGraph version. See [Input policy backward compatibility.](https://docs.tigergraph.com/tigergraph-server/4.2/security/gsql-file-input-policy#_backward_compatibility) | v3.10.0  
When a PRINT argument is an expression, the output uses the expression as the key (label) for that output value. To better support Antlr processing, PRINT now removes any spaces from that key. For example, `count(DISTINCT @@ids)` becomes `count(DISTINCT@@ids)`. | v3.9.3+  
Betweenness Centrality algorithm: `reverse_edge_type (STRING)` parameter changed to `reverse_edge_type_set (SET<STRING>)`, to be consistent with `edge_type_set` and similar algorithms. | v3.9.2+  
For vertices with string-type primary IDs, vertices whose ID is an empty string will now be rejected. | v3.9.2+  
The default mode for the Kafka Connector changed from EOF="false" to EOF="true". | v3.9.2+  
The default retention time for two monitoring services `Informant.RetentionPeriodDays` and `TS3.RetentionPeriodDays` has reduced from 30 to 7 days. | v3.9.2+  
The filter for `/informant/metrics/get/cpu-memory` now accepts a list of ServiceDescriptors instead of a single ServiceDescriptor. | v3.9.2+  
Some user-defined functions (UDFs) may no longer be accepted due to [increased security screening](https://docs.tigergraph.com/tigergraph-server/4.2/security/#_udf_file_scanning).
  * UDFs may no longer be called `to_string()`. This is now a built-in GSQL function.
  * UDF names may no longer use the `tg_` prefix. Any user-defined function that began with `tg_` must be renamed or removed in `ExprFunctions.hpp`.

| v3.9+  
### [](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_deprecations)Deprecations
Description | Deprecated | Removed  
---|---|---  
The `--meta` option for backup is no longer needed because metadata is now included automatically with backup files. | 3.9.2 | 4.2.0  
Streaming connector for external Kafka (3.6 to 3.9.2 version) | 3.9.3 | 4.2.0  
The format for tuple structures in CDC messages will change in a future version. The future format is likely to be similar to the [new format for maps](https://docs.tigergraph.com/tigergraph-server/4.1/system-management/change-data-capture/cdc-message-example#_cdc_message_with_type_edge). | 4.1.1 | 4.2  
## [](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/#_release_notes_for_previous_versions)Release notes for previous versions
  * [Release notes - TigerGraph 4.1](https://docs.tigergraph.com/tigergraph-server/4.1/release-notes/)
  * [Release notes - TigerGraph 3.11](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/)
  * [Release notes - TigerGraph 3.10](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/)
  * [Release notes - TigerGraph 3.9](https://docs.tigergraph.com/tigergraph-server/3.9/release-notes/)
  * [Release notes - TigerGraph 3.6](https://docs.tigergraph.com/tigergraph-server/3.6/release-notes/)


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


