![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management)[Next](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management)
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
  * [Access Management](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/)
  * Authorization
  * [Role Management](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/3.10/modules/user-access/pages/role-management.adoc)
### Contents
  * [Create a local role](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_create_a_local_role)
  * [Create a global role](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_create_a_global_role)
  * [View privileges of a role](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_view_privileges_of_a_role)
  * [View all users who are assigned a role](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_view_all_users_who_are_assigned_a_role)
  * [List all existing roles](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_list_all_existing_roles)
  * [Grant privileges to a role](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_grant_privileges_to_a_role)
  * [Grant type-level privilege to a role](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_grant_type_level_privilege_to_a_role)
  * [Grant attribute-level privilege to a role](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_grant_attribute_level_privilege_to_a_role)
  * [Revoke privileges from a role](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_revoke_privileges_from_a_role)
  * [Revoke type-level privileges](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_revoke_type_level_privileges)
  * [Revoke attribute-level privileges](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_revoke_attribute_level_privileges)
  * [Drop a role](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_drop_a_role)


# Role Management
### Contents
  * [Create a local role](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_create_a_local_role)
  * [Create a global role](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_create_a_global_role)
  * [View privileges of a role](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_view_privileges_of_a_role)
  * [View all users who are assigned a role](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_view_all_users_who_are_assigned_a_role)
  * [List all existing roles](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_list_all_existing_roles)
  * [Grant privileges to a role](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_grant_privileges_to_a_role)
  * [Grant type-level privilege to a role](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_grant_type_level_privilege_to_a_role)
  * [Grant attribute-level privilege to a role](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_grant_attribute_level_privilege_to_a_role)
  * [Revoke privileges from a role](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_revoke_privileges_from_a_role)
  * [Revoke type-level privileges](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_revoke_type_level_privileges)
  * [Revoke attribute-level privileges](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_revoke_attribute_level_privileges)
  * [Drop a role](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_drop_a_role)


This page explains the procedures for various role management tasks under TigerGraph’s role-based access control model.
To see role management tasks under the Access Control List (ACL) model, see [Access Control Lists (ACLs)](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/acl-management).
For Row Policy and Object-Based privilege EBNF examples see [RBAC Row Policy EBNF](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/row-policy-ebnf).  
---  
## [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_create_a_local_role)Create a local role
Local roles are deprecated and will be dropped in a future release.   
---  
### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_syntax)Syntax
```
CREATE ROLE <role_name> (, <role_name>)* [ON GRAPH <graph_name>]
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_required_privilege)Required privilege
`WRITE_ROLE`
### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_example)Example
  1. To create a local role, run the `CREATE ROLE` command like below. If you choose not to specify a graph in the command, the current scope will be used as the scope of the role:
```
GSQL > USE GRAPH example_graph
GSQL > CREATE ROLE role1, role2
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```



This will create two roles named `role1` and `role2` on graph `example_graph`. By default, these two roles do not have any privilege:
```
Successfully created local roles for graph 'example_graph': [role1, role2].
```

## [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_create_a_global_role)Create a global role
You can create a global role with the `CREATE ROLE` command.
### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_syntax_2)Syntax
```
CREATE ROLE <role_name> (, <role_name>)* ON GLOBAL
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_required_privilege_2)Required privilege
`WRITE_ROLE` on the global scope
### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_example_2)Example
  1. To create a global role, run the `CREATE ROLE` command like below. Replace `role1` with the name of the role you are creating.


```
CREATE ROLE role1 ON GLOBAL
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This will create a role named `role1` on the global scope. By default, this role has no privileges:
```
Successfully created global roles: [role1].
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_view_privileges_of_a_role)View privileges of a role
Users with the `READ_ROLE` privilege in a scope can view the privileges on the roles in that scope.
`SHOW GRANTS TO ROLE` shows both the RBAC and ACL privileges of a role. `SHOW PRVILEGE ON ROLE` shows only the `RBAC` privileges of a role.
### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_syntax_3)Syntax
```
SHOW PRIVILEGE ON ROLE <role_name>, <role_name2> ...
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
SHOW GRANTS TO ROLE <role_name1>, <role_name2> ...
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_required_privilege_3)Required privilege
`READ_ROLE` on the global scope
### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_example_3)Example
The following command shows all privileges of the role `moderator`:
```
GSQL > USE GLOBAL
GSQL > SHOW GRANTS TO ROLE moderator
RBAC privileges of Role: "moderator"
- Global Privileges:
READ_DATA
- Graph 'Social' Privileges:
- Type 'Person' Privileges:
CREATE_DATA
- Attribute 'locationIP' Privileges:
UPDATE_DATA
ACL privileges of Role: "moderator"
No ACL privileges.
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The following command shows all privileges of the roles `role1` and `role2`:
```
GSQL > SHOW PRIVILEGE ON ROLE role1 , role2
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

To view the ACL privileges of a role, see [View ACL privileges of a role](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/acl-management#_view_acl_privileges_of_a_role).
## [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_view_all_users_who_are_assigned_a_role)View all users who are assigned a role
You can specify a role and view all users who are assigned that role.
### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_syntax_4)Syntax
```
SHOW GRANTS OF ROLE <role_name1>, <role_name2> ...
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_require_privilege)Require privilege
`READ_ROLE` and `READ_USER` on global scope
### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_example_4)Example
The following command shows all users with the role `moderator`:
```
GSQL > SHOW GRANTS OF ROLE moderator
Users with role moderator:
 tigergraph
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_list_all_existing_roles)List all existing roles
### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_syntax_5)Syntax
```
SHOW ROLE
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_required_privilege_4)Required privilege
`READ_ROLE`
### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_example_5)Example
  1. To list all existing roles, first ensure that you are in the correct scope. Run `USE <graph_name>` or `USE GLOBAL` to switch to your desired scope.
  2. Run the `SHOW ROLE` command:
```
GSQL > SHOW ROLE
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```



This will show all the roles in your current scope:
```
 - Builtin Roles:
  observer
  queryreader
  querywriter
  designer
  admin
  globaldesigner
  superuser
 - User Defined Roles:
  - Graph 'tpc_graph' Roles:
   role1
   role2
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_grant_privileges_to_a_role)Grant privileges to a role
Users with the `WRITE_ROLE` privileges on a scope can grant RBAC privileges to the roles in that scope.
### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_syntax_6)Syntax
```
GRANT PRIVILEGE <privilege_name1> (, privilege_name2)*
    [ON GRAPH <graph_name>] TO <role_name1> (, <role_name2>)*
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_require_privilege_2)Require privilege
`WRITE_ROLE`
### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_example_6)Example
  1. To grant privileges to a role, run the `GRANT PRIVILEGE` command from the GSQL shell:
```
GSQL > GRANT PRIVILEGE WRITE_QUERY, WRITE_ROLE
    ON GRAPH example_graph TO role1 , role2
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```



This will allow users with the roles `role1` and `role2` to edit and install queries, as well as modify roles on the graph `example_graph`. To see a full list of privileges and the command they allow users to run, see [List of Legacy Privilege Syntax](https://docs.tigergraph.com/tigergraph-server/3.10/reference/list-of-privileges).
To grant [ACL privileges](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/access-control-model#_access_control_lists) to a role, see [Grant ACL privileges to a role](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/acl-management#_grant_acl_privilege_to_a_role).
## [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_grant_type_level_privilege_to_a_role)Grant type-level privilege to a role
Users with the `WRITE_ROLE` privileges on a scope can grant RBAC privileges to the roles in that scope.
### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_syntax_7)Syntax
```
GRANT PRIVILEGE privilege_name1 , privilege_name2... ON VERTEX/EDGE <graph_name>.<type.name> TO <role_name> , <role_name2>...
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_required_privilege_5)Required privilege
`WRITE_ROLE` and the privilege being granted
### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_example_7)Example
The following command grants the `READ_DATA` and `CREATE_DATA` privilege on vertex type `Person` to `role2` and `role2`.
```
GRANT PRIVILEGE READ_DATA, CREATE_DATA ON VERTEX G1.Person TO role1, role2
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This allows users with `role1` and `role2` to read all attribute values of type `Person` vertices. However, to insert new vertices, the user must also have `UPDATE_DATA` on all attributes of vertex type `Person`.
## [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_grant_attribute_level_privilege_to_a_role)Grant attribute-level privilege to a role
You can grant certain privileges (`READ_DATA`, `CREATE_DATA`, `UPDATE_DATA`) on an attribute level to a role. The privilege only applies to the specified attributes of the specified type.
### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_syntax_8)Syntax
```
GRANT PRIVILEGE privilege_name1 , privilege_name2... ON VERTEX/EDGE <graph_name>.<type.name> (<attribute1>, <attribute2> ...) TO <role_name> , <role_name2>...
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

`from` and `to` are edge attributes that represent the source vertex and target vertex of an edge. When you grant access to these attributes, `from` and `to` are case-sensitive. You must use lower-case to indicate these two attributes.
### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_required_privilege_6)Required privilege
`WRITE_ROLE` and the privilege being granted
### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_example_8)Example
The following command grants the `READ_DATA` privilege on the `id` and `age` attribute of the vertex type `Person` to `example_role`.
```
GRANT PRIVILEGE READ_DATA ON VERTEX G1.person (id, age) TO example_role
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This allows users with `example_role` to read the `id` and `age` attribute values of `Person` vertices. However, if the type `Person` has other attributes, such as an `SSN` attribute with their social security number, users who don’t have the `READ_DATA` privilege on that attribute are not able to access its attribute value.
The following command grants the `READ_DATA` privilege on the `to` attribute of the edge type `Knows` to `example_role`:
```
GRANT PRIVILEGE READ_DATA ON edge ldbc_snb.Knows(to) TO example_role **(1)**
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | `to` must be lower-case.  
---|---  
## [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_revoke_privileges_from_a_role)Revoke privileges from a role
Users with the `WRITE_ROLE` privileges on a scope can revoke RBAC privileges from the roles in that scope.
### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_syntax_9)Syntax
```
REVOKE PRIVILEGE <privilege_name1> (, privilege_name2)*
    [ON GRAPH <graph_name>] FROM <role_name1> (, <role_name2>)*
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_required_privilege_7)Required privilege
`WRITE_ROLE`
### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_example_9)Example
  1. To revoke privileges from a role, run the `REVOKE PRIVILEGE` command from the GSQL shell:
```
GSQL > REVOKE PRIVILEGE WRITE_QUERY
    ON GRAPH example_graph FROM role1
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```



This will revoke the `WRITE_QUERY` privilege from the role `role1` on graph `example_graph.`
To revoke [ACL privileges](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/access-control-model#_access_control_lists) from a role, see [Revoke ACL privileges from a role](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/acl-management#_revoke_acl_privilege_from_a_role).
## [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_revoke_type_level_privileges)Revoke type-level privileges
You can revoke certain privileges from the type level with the `REVOKE PRIVILEGE` command.
If the privilege has already been granted on the global scope or on the graph level, then revoking the privilege on the type level does not revoke the privilege in effect.
### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_syntax_10)Syntax
```
REVOKE PRIVILEGE <privilege_name1>, <privilege_name2> ... ON VERTEX/EDGE <graph_name>.<type.name> FROM <role_name> , <role_name2>...
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_required_privilege_8)Required privilege
`WRITE_ROLE`
### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_example_10)Example
The following command revokes the `UPDATE_DATA` privilege on type `Friendship` from `role1`, and `role1`:
```
REVOKE PRIVILEGE UPDATE_DATA ON EDGE Social.Friendship FROM role1, role2
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_revoke_attribute_level_privileges)Revoke attribute-level privileges
You can revoke certain privileges from the attribute level with the `REVOKE PRIVILEGE` command.
If the privilege has already been granted on the global scope, on the graph level, or type level, then revoking the privilege on the type level does not revoke the privilege in effect.
### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_syntax_11)Syntax
```
REVOKE PRIVILEGE privilege_name1 , privilege_name2... ON VERTEX/EDGE <graph_name>.<type.name> (<attribute1>, <attribute2> ...) FROM <role_name> , <role_name2>...
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_required_privilege_9)Required privilege
`WRITE_ROLE` and the privilege being granted
### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_example_11)Example
The following command revokes `CREATE_DATA` and `UPDATE_DATA` on the `startdata` attribute from `role1` and `role2`.
If the user doesn’t have these privileges, they are not able to create new edges of type `Friendship`.
```
REVOKE PRIVILEGE CREATE_DATA, UPDATE_DATA ON EDGE Social.Friendship (startdata) FROM role1, role2
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_drop_a_role)Drop a role
### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_syntax_12)Syntax
```
DROP ROLE <role_name> (, <role_name2>)*
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_required_privilege_10)Required privilege
`WRITE_ROLE`
### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/role-management#_example_12)Example
  1. To drop a role, run the `DROP ROLE` command from the GSQL shell:
```
GSQL > DROP ROLE role1 , role2
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```



This will drop the roles `role1` and `role2`. This will also revoke the roles from users who have been granted these roles.
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


