![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management)[Next](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management)
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
  * [User Management](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/4.2/modules/user-access/pages/user-management.adoc)
### Contents
  * [Create a user](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_create_a_user)
  * [Username Rules for v3.9.3 and above](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_username_rules_for_v3_9_3_and_above)
  * [Username Rules for v3.9.2 and below](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_username_rules_for_v3_9_2_and_below)
  * [Syntax](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax)
  * [Required privilege](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege)
  * [Procedure](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_procedure)
  * [View roles assignments and login attempts](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_view_roles_assignments_and_login_attempts)
  * [Syntax](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax_2)
  * [Required privilege](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege_2)
  * [Procedure](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_procedure_2)
  * [View privileges of a user](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_view_privileges_of_a_user)
  * [Syntax](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax_3)
  * [Required privilege](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege_3)
  * [Procedure](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_procedure_3)
  * [Grant a role to a user/proxy group](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_grant_a_role_to_a_user)
  * [Syntax](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax_4)
  * [Required privilege](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege_4)
  * [Procedure](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_procedure_4)
  * [Revoke a role from a user](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_revoke_a_role_from_a_user)
  * [Syntax](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax_5)
  * [Required privilege](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege_5)
  * [Procedure](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_procedure_5)
  * [Grant privileges to a user](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_grant_privileges_to_a_user)
  * [Syntax](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax_6)
  * [Required privilege](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege_6)
  * [Example](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_example)
  * [Grant type-level privilege to a user](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_grant_type_level_privilege_to_a_user)
  * [Syntax](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax_7)
  * [Required privilege](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege_7)
  * [Example](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_example_2)
  * [Grant attribute-level privilege to a user](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_grant_attribute_level_privilege_to_a_user)
  * [Syntax](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax_8)
  * [Required privilege](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege_8)
  * [Example](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_example_3)
  * [Revoke privileges from a user](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_revoke_privileges_from_a_user)
  * [Syntax](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax_9)
  * [Required privilege](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege_9)
  * [Example](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_example_4)
  * [Revoke type-level privileges](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_revoke_type_level_privileges)
  * [Syntax](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax_10)
  * [Required privilege](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege_10)
  * [Example](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_example_5)
  * [Revoke attribute-level privileges](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_revoke_attribute_level_privileges)
  * [Syntax](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax_11)
  * [Required privilege](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege_11)
  * [Example](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_example_6)
  * [Change a user’s password](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_change_a_users_password)
  * [Syntax](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax_12)
  * [Required privilege](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege_12)
  * [Procedure](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_procedure_6)
  * [Drop a user](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_drop_a_user)
  * [Syntax](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax_13)
  * [Required privilege](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege_13)
  * [Procedure](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_procedure_7)


# User Management
### Contents
  * [Create a user](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_create_a_user)
  * [Username Rules for v3.9.3 and above](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_username_rules_for_v3_9_3_and_above)
  * [Username Rules for v3.9.2 and below](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_username_rules_for_v3_9_2_and_below)
  * [Syntax](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax)
  * [Required privilege](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege)
  * [Procedure](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_procedure)
  * [View roles assignments and login attempts](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_view_roles_assignments_and_login_attempts)
  * [Syntax](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax_2)
  * [Required privilege](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege_2)
  * [Procedure](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_procedure_2)
  * [View privileges of a user](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_view_privileges_of_a_user)
  * [Syntax](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax_3)
  * [Required privilege](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege_3)
  * [Procedure](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_procedure_3)
  * [Grant a role to a user/proxy group](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_grant_a_role_to_a_user)
  * [Syntax](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax_4)
  * [Required privilege](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege_4)
  * [Procedure](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_procedure_4)
  * [Revoke a role from a user](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_revoke_a_role_from_a_user)
  * [Syntax](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax_5)
  * [Required privilege](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege_5)
  * [Procedure](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_procedure_5)
  * [Grant privileges to a user](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_grant_privileges_to_a_user)
  * [Syntax](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax_6)
  * [Required privilege](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege_6)
  * [Example](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_example)
  * [Grant type-level privilege to a user](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_grant_type_level_privilege_to_a_user)
  * [Syntax](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax_7)
  * [Required privilege](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege_7)
  * [Example](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_example_2)
  * [Grant attribute-level privilege to a user](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_grant_attribute_level_privilege_to_a_user)
  * [Syntax](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax_8)
  * [Required privilege](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege_8)
  * [Example](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_example_3)
  * [Revoke privileges from a user](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_revoke_privileges_from_a_user)
  * [Syntax](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax_9)
  * [Required privilege](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege_9)
  * [Example](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_example_4)
  * [Revoke type-level privileges](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_revoke_type_level_privileges)
  * [Syntax](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax_10)
  * [Required privilege](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege_10)
  * [Example](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_example_5)
  * [Revoke attribute-level privileges](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_revoke_attribute_level_privileges)
  * [Syntax](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax_11)
  * [Required privilege](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege_11)
  * [Example](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_example_6)
  * [Change a user’s password](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_change_a_users_password)
  * [Syntax](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax_12)
  * [Required privilege](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege_12)
  * [Procedure](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_procedure_6)
  * [Drop a user](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_drop_a_user)
  * [Syntax](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax_13)
  * [Required privilege](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege_13)
  * [Procedure](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_procedure_7)


This page explains the procedures for various user management tasks under TigerGraph’s role-based access control(RBAC) model.
## [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_create_a_user)Create a user
You can run the `CREATE USER` command to create a user.
## [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_username_rules_for_v3_9_3_and_above)Username Rules for v3.9.3 and above
v3.9.3 expanded the variety of characters users can access while creating a username from previous versions.   
---  
A username is treated as a `STRING` in GSQL, regardless of the syntax structure, format, or characters used.   
---  
**Usernames** may contain any Unicode characters **except** the following:
  1. May not contain these characters: `\r`, `\n`, `\0`, `\b`, `\t`, `\a`, `\v`.
  2. May not contain any `SPACE`.


In the GSQL client, backquotes ( ``` ) must be used as a delimiter to enclose usernames which is not a valid email and does not follow the pattern [a-zA-Z_][a-zA-Z0-9]*. Delimiters are not stored internally.   
---  
## [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_username_rules_for_v3_9_2_and_below)Username Rules for v3.9.2 and below
For v3.9.2 and below please follow these guidelines when creating a username.   
---  
**Usernames** must match a regex pattern of `[a-zA-Z_][a-zA-Z0-9]*`, or be an email. You may also use non-ascii characters, such as Chinese and Kanji characters.
Additionally, usernames may **not** contain the following characters:
  1. `\`, `(`, `)`, `[`, `]`, `:`, `<`, `>`, `;`, `,`, `@`, `\r`, `\n`, `\f`, `\t`, `\\`, `\0`, `\b`.
  2. A username may not start with a dot ( `.` ) or have multiple dots ( `…​` or `a.b..c…​` ) in a sequence.


Backquotes ( ``` ) must be used as a delimiter to enclose usernames which do not follow the pattern `[a-zA-Z_][a-zA-Z0-9]*`. Delimiters are not stored internally.   
---  
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax)Syntax
```
CREATE USER
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege)Required privilege
`WRITE_USER`
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_procedure)Procedure
  1. From the GSQL shell, run the `CREATE USER` command:
```
GSQL > CREATE USER
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  2. Enter the user information in the prompts that follow:
Example 1: Create user
```
User Name : user1
New Password : ************
Re-enter Password : ************
The user "user1" is created.
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Example 2: Create user with email
```
User Name : a@b.com
New Password : ************
Re-enter Password : ************
The user "a@b.com" is created.
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Example 3: Create user with special characters (**Only** v3.9.3)
```
User Name : `:"/.,@#$%^*()_+=-`
New Password : ************
Re-enter Password : ************
The user ":"/.,@#$%^*()_+=-" is created.
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```



#### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_non_interactive_mode)Non-Interactive Mode
Run the command like this to run `create user` in non-interactive mode.
Example:
```
GSQL > create user -u user1 -p pass1
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

for special case use “`“ username“`“ to include the username  
---  
## [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_view_roles_assignments_and_login_attempts)View roles assignments and login attempts
The `SHOW USER` command displays the role assignments, as well as the login attempts, of the current user. If the current user has the `READ_USER` privilege
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax_2)Syntax
```
SHOW USER
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege_2)Required privilege
`READ_USER` for displaying roles of other users
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_procedure_2)Procedure
From the GSQL shell, run the `SHOW USER` command:
```
GSQL > SHOW USER
- Name: testUser
  - Global Roles: superuser
  - LastSuccessLogin: Thu Sep 22 12:43:07 UTC 2022
  - NextValidLogin: Thu Sep 22 12:43:07 UTC 2022 **(1)**
  - FailedAttempts: 0
  - ShowAlterPasswordWarning: false
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | The next time the user is allowed to attempt login. For more information, see [Configuring Login Protection](https://docs.tigergraph.com/tigergraph-server/4.2/security/login-protection)  
---|---  
If the user running the command has the `READ_USER` privilege, information on all users is displayed. Otherwise, only the current user’s information is displayed.
## [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_view_privileges_of_a_user)View privileges of a user
Users with the `READ_USER` privilege in a scope can view the RBAC privileges of the users in that scope.
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax_3)Syntax
```
SHOW PRIVILEGE ON USER <username> (, <username>)*
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege_3)Required privilege
`READ_USER`
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_procedure_3)Procedure
  1. From the GSQL shell, run the `SHOW PRIVILEGE ON USER` command :
```
GSQL > SHOW PRIVILEGE ON USER tigergraph
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```



The above command will show the privileges of user `tigergraph`:
```
User: "tigergraph"
 - Global Privileges:
  READ_SCHEMA
  WRITE_SCHEMA
  READ_LOADINGJOB
  EXECUTE_LOADINGJOB
  WRITE_LOADINGJOB
  CREATE_QUERY
  READ_DATA
  WRITE_DATA
  WRITE_DATASOURCE
  READ_ROLE
  WRITE_ROLE
  READ_USER
  WRITE_USER
  READ_PROXYGROUP
  WRITE_PROXYGROUP
  READ_FILE
  WRITE_FILE
  DROP_GRAPH
  EXPORT_GRAPH
  CLEAR_GRAPHSTORE
  DROP_ALL
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_grant_a_role_to_a_user)Grant a role to a user/proxy group
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax_4)Syntax
```
GRANT ROLE <role_name1> (, role_name2)* [ON GRAPH <graph_name>]
 TO <username1>|<proxy_group_name1> (, <username2> | <proxy_group_name>2)*
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege_4)Required privilege
`WRITE_ROLE`
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_procedure_4)Procedure
  1. Start the GSQL shell and make sure you are using the correct graph
```
$ gsql
GSQL > USE GRAPH example_graph
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  2. From the GSQL shell, run the `GRANT ROLE` command. You can grant multiple roles to multiple users:
```
GSQL > GRANT ROLE role1 , role2 ON GRAPH example_graph TO user1, user2
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```



The above command will grant roles `role1` and `role2` on graph `example_graph` to users `user1` and `user2`.
## [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_revoke_a_role_from_a_user)Revoke a role from a user
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax_5)Syntax
```
REVOKE ROLE <roleName1> (, <roleName2)* [ON GRAPH <graphName>]
    FROM <userName1> (, <userName2>)*
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege_5)Required privilege
`WRITE_ROLE`
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_procedure_5)Procedure
  1. Start the GSQL shell and make sure you are using the correct graph
```
$ gsql
GSQL > USE GRAPH example_graph
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  2. From the GSQL shell, run the `REVOKE_ROLE` command. You can revoke multiple roles from multiple users at the same time:
```
GSQL > REVOKE ROLE role1, role2 ON GRAPH example_graph
    FROM user1, user2
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```



The above command will revoke roles `role1` and `role2` on graph `example_graph` from users `user1` and `user2`.
## [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_grant_privileges_to_a_user)Grant privileges to a user
Only users with the WRITE_USER privilege at the global level can grant RBAC privileges to other users.
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax_6)Syntax
```
GRANT <privilegeName1> (, <privilegeName2>)* ON <privilegeObjects>
    [IN <privilegeScopes>]? TO <user_name1> (, <user_name2>)*
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege_6)Required privilege
`WRITE_USER`
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_example)Example
  1. To grant privileges to a user, run the `GRANT PRIVILEGE` command from the GSQL shell:
```
GSQL > GRANT WRITE ON ALL ROLES
    IN GRAPH example_graph TO user1 , user2
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```



This command will allow `user1` and `user2` to modify roles on the graph `example_graph`. Specifically, they can create, modify, or delete roles for that graph. To see a full list of privilege objects and the types of privileges they each may have, see [Object-Based Privilege Tables](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/row-policy-privileges-table)
## [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_grant_type_level_privilege_to_a_user)Grant type-level privilege to a user
You can grant certain privileges (`READ_DATA`, `CREATE_DATA`, `DELETE_DATA`, `UPDATE_DATA`) on a type level to users. The privilege only applies to the specified types.
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax_7)Syntax
```
GRANT <privilege_name1> (, <privilege_name2>)* ON VERTEX/EDGE <type_name> IN GRAPH <graph_name> TO <user_name> (, <user_name2>)*
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege_7)Required privilege
`WRITE_USER` and the privilege being granted
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_example_2)Example
The following command grants the `READ_DATA` and `CREATE_DATA` privilege on vertex type `Person` to `user1` and `user2`.
```
GRANT READ, CREATE ON VERTEX Person IN GRAPH G1 TO user1, user2
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This allows `user1` and `user2` to read all attribute values of type `Person` vertices in graph `G1`. However, to insert new vertices, the user must also have `UPDATE_DATA` on all attributes of vertex type `Person`.
## [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_grant_attribute_level_privilege_to_a_user)Grant attribute-level privilege to a user
You can grant certain privileges (`READ_DATA`, `CREATE_DATA`, `UPDATE_DATA`) on an attribute level to a user. The privilege only applies to the specified attributes of the specified type.
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax_8)Syntax
```
GRANT <privilege_name1> (, <privilege_name2>)* ON VERTEX/EDGE <type_name> ATTRIBUTE <attribute_name> (, <attribute_name2>)* IN GRAPH <graph_name> TO <user_name> (, <user_name2>)*
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

`from` and `to` are edge attributes that represent the source vertex and target vertex of an edge. When you grant access to these attributes, `from` and `to` are case-sensitive. You must use lower-case to indicate these two attributes.
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege_8)Required privilege
`WRITE_USER` and the privilege being granted
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_example_3)Example
The following command grants the `READ_DATA` privilege on the `id` and `age` attribute of the vertex type `Person` to `example_user`.
```
GRANT READ ON VERTEX person ATTRIBUTE id, age IN GRAPH G1 TO example_user
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This allows the user `example_user` to read the `id` and `age` attribute values of `Person` vertices in graph `G1`. However, if the type `Person` has other attributes, such as an `SSN` attribute with their social security number, users who don’t have the `READ_DATA` privilege on that attribute are not able to access its attribute value.
The following command grants the `READ_DATA` privilege on the `to` attribute of the edge type `Knows` to `example_user`:
```
GRANT READ ON EDGE Knows ATTRIBUTE to IN GRAPH ldbc_snb TO example_user **(1)**
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | `to` must be lower-case.  
---|---  
## [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_revoke_privileges_from_a_user)Revoke privileges from a user
Users with the `WRITE_USER` privileges on global can revoke RBAC privileges from the users.
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax_9)Syntax
```
REVOKE <privilegeName1> (, <privilegeName2>)* ON <privilegeObjects>
    [IN <privilegeScopes>]? FROM <user_name1> (, <user_name2>)*
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege_9)Required privilege
`WRITE_USER`
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_example_4)Example
  1. To revoke privileges from a user, run the `REVOKE PRIVILEGE` command from the GSQL shell:
```
GSQL > REVOKE WRITE ON ALL ROLES
    IN GRAPH example_graph TO user1
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```



This will revoke the `WRITE_ROLE` privilege from the user `user1` on graph `example_graph.`
## [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_revoke_type_level_privileges)Revoke type-level privileges
You can revoke certain privileges from the type level with the `REVOKE PRIVILEGE` command.
Revoking a privilege at the type does not affect privileges granted at higher levels (e.g., global or graph level). For instance, if a user has `READ_DATA`` on a vertex type globally, revoking this privilege at the type level will not prevent the user from accessing the vertex type.
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax_10)Syntax
```
REVOKE <privilege_name1> (, <privilege_name2>)* ON VERTEX/EDGE <type_name> IN GRAPH <graph_name> FROM <user_name> (, <user_name2>)*
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege_10)Required privilege
`WRITE_USER`
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_example_5)Example
The following command revokes the `UPDATE_DATA` privilege on type `Friendship` from `user1`, and `user2`:
```
REVOKE UPDATE ON EDGE Friendship IN GRAPH Social FROM user1, user2
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_revoke_attribute_level_privileges)Revoke attribute-level privileges
You can revoke certain privileges from the attribute level with the `REVOKE PRIVILEGE` command.
Revoking a privilege at the type does not affect privileges granted at higher levels (e.g., global, graph level or type level). For instance, if a user has `READ_DATA`` on a vertex type globally, revoking this privilege at the attribute level will not prevent the user from accessing the vertex attribute type.
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax_11)Syntax
```
REVOKE <privilege_name1> (, <privilege_name2>)* ON VERTEX/EDGE <type_name> ATTRIBUTE <attribute_name> (, <attribute_name>)* IN GRAPH <graph_name> FROM <user_name> (, <user_name2>)*
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege_11)Required privilege
`WRITE_ROLE` and the privilege being granted
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_example_6)Example
The following command revokes `CREATE_DATA` and `UPDATE_DATA` on the `startdata` attribute from `user1` and `user2`.
If the user doesn’t have these privileges, they are not able to create new edges of type `Friendship`.
```
REVOKE CREATE, UPDATE ON EDGE Friendship ATTRIBUTE startdata IN GRAPH Social FROM user1, user2
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_change_a_users_password)Change a user’s password
Users can change their own passwords used for login without needing any privilege. Users with the `WRITE_USER` privilege can change the passwords of other users.
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax_12)Syntax
```
ALTER PASSWORD <username>
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege_12)Required privilege
`WRITE_USER` for changing the password of a user other than the current user
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_procedure_6)Procedure
  1. From the GSQL shell, run the following command. Replace `username` with the user whose password you want to change
```
GSQL > ALTER PASSWORD username
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  2. Enter the new password in the prompt that follows.


#### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_non_interactive_mode_2)Non-Interactive Mode
Run the command like this to run `alter password` in non-Interactive Mode.
Example:
```
GSQL > alter password -u user1 -p pass2
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_drop_a_user)Drop a user
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_syntax_13)Syntax
```
DROP USER <user1> (,<user2>)*
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_required_privilege_13)Required privilege
`WRITE_USER`
### [](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management#_procedure_7)Procedure
  1. From the GSQL shell, run the `DROP USER` command. You can drop multiple users in the same command.
```
GSQL > DROP USER user1, a@b.com, `:"/.,@#$%^*()_+=-`
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  2. GSQL will confirm that the users you entered have been dropped


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


