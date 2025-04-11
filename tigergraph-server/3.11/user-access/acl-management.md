![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management)[Next](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management)
[Developer Site](https://dev.tigergraph.com/) [Community Forum](https://community.tigergraph.com/) [Knowledge Base](https://tigergraph.freshdesk.com/support/solutions)
[Download](https://dl.tigergraph.com)
[ TG Savanna](https://savanna.tgcloud.io)
### [TigerGraph DB](https://docs.tigergraph.com/tigergraph-server/3.11/intro/)
  *     * [TigerGraph DB Release Notes](https://docs.tigergraph.com/tigergraph-server/3.11/release-notes/)
  *     * [Overview](https://docs.tigergraph.com/tigergraph-server/3.11/intro/)
    * [Get Started](https://docs.tigergraph.com/tigergraph-server/3.11/getting-started/)
      * Installation
        * [On Docker](https://docs.tigergraph.com/tigergraph-server/3.11/getting-started/docker)
        * [On Kubernetes](https://docs.tigergraph.com/tigergraph-server/3.11/getting-started/kubernetes)
        * [On Cloud Marketplace](https://docs.tigergraph.com/tigergraph-server/3.11/getting-started/cloud-images/)
          * [AWS](https://docs.tigergraph.com/tigergraph-server/3.11/getting-started/cloud-images/aws)
          * [Azure](https://docs.tigergraph.com/tigergraph-server/3.11/getting-started/cloud-images/azure)
          * [GCP](https://docs.tigergraph.com/tigergraph-server/3.11/getting-started/cloud-images/gcp)
        * [On Linux](https://docs.tigergraph.com/tigergraph-server/3.11/getting-started/linux)
          * [System Requirements](https://docs.tigergraph.com/tigergraph-server/3.11/installation/hw-and-sw-requirements)
          * [Linux On Bare Metal](https://docs.tigergraph.com/tigergraph-server/3.11/installation/bare-metal-install)
          * [Post Install Checks](https://docs.tigergraph.com/tigergraph-server/3.11/installation/post-install-check)
        * [Advanced License Issues](https://docs.tigergraph.com/tigergraph-server/3.11/installation/license)
        * [Changing Ports](https://docs.tigergraph.com/tigergraph-server/3.11/installation/change-port)
        * [Upgrade](https://docs.tigergraph.com/tigergraph-server/3.11/installation/upgrade)
        * [Uninstallation](https://docs.tigergraph.com/tigergraph-server/3.11/installation/uninstallation)
      * [The GSQL Shell](https://docs.tigergraph.com/tigergraph-server/3.11/gsql-shell/)
        * [GSQL Shell Sessions](https://docs.tigergraph.com/tigergraph-server/3.11/gsql-shell/gsql-sessions)
        * [Using a Remote GSQL Client](https://docs.tigergraph.com/tigergraph-server/3.11/gsql-shell/using-a-remote-gsql-client)
        * [GSQL Shell (Web)](https://docs.tigergraph.com/tigergraph-server/3.11/gsql-shell/web)
    * [Create Database](https://docs.tigergraph.com/tigergraph-server/3.11/getting-started/database-definition)
      * [MultiGraph Overview](https://docs.tigergraph.com/tigergraph-server/3.11/intro/multigraph-overview)
  *     * [Load Data](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/)
      * [Overview](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/data-loading-overview)
      * [Externalize Kafka Configs](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/externalizing-kafka-configs)
      * [Load from Local Files](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-local-files)
      * [Load from Cloud Storage](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-cloud)
      * [Load from Data Warehouse](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-warehouse)
      * [Load from External Kafka](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-kafka)
        * [Avro Data Validation through KafkaConnect](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/avro-validation-with-kafka)
        * [Kafka SSL Security Guide](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide)
      * [Load from Spark Dataframe](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-spark-dataframe)
        * [Spark Connection Via JDBC Driver (Deprecated)](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/spark-connection-via-jdbc-driver)
      * [Manage Data Sources](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/manage-data-source)
      * [Data Loading V2](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/data-loading-v2)
      * [Stream from External Kafka (Deprecated)](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/data-streaming-connector/kafka)
  *     * Advanced Topics
      * [System Management](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/management-with-gadmin)
        * [Memory management](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/memory-management)
        * [Manage TigerGraph services](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/manage-services)
        * [Workload Management](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management)
        * [Metrics Reporting](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/system-metrics)
        * [Command Glossary](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/management-commands)
        * [Change Data Capture (CDC) Overview](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/change-data-capture/cdc-overview)
          * [CDC Setup](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/change-data-capture/cdc-setup)
          * [CDC Message Examples](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/change-data-capture/cdc-message-example)
          * [CDC State Monitoring](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/change-data-capture/cdc-state-monitoring)
      * [Access Management](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/)
        * Authentication
          * [Enabling User Authentication](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/enabling-user-authentication)
          * [User Credentials](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/user-credentials)
          * [Single Sign-On](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/sso)
          * [Lightweight Directory Access Protocol (LDAP)](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/ldap)
          * [OIDC JWT Authentication](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/jwt-token)
        * Authorization
          * [User Management](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/user-management)
          * [Role Management](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/role-management)
          * [Access Control Model](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/access-control-model)
          * [Access Control Lists (ACLs)](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management)
          * [Row Policy Overview (Preview Feature)](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/rbac-row-policy/row-policy-overview)
            * [Key Concepts](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/rbac-row-policy/rbac-row-policy)
            * [Set Up Row Policy](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/rbac-row-policy/setup-row-policy)
          * [Vertex-Level Access Control (Deprecated)](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/vlac)
      * [Backup and Restore](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/)
        * [Database Import/Export All Graphs](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/database-import-export)
        * [Import/Export Individual Graphs](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/single-graph-import-export)
        * [Backup and Restore Configurations](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/configurations)
        * [Back up a Database Cluster](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/backup-cluster)
        * [Restore a Database Backup from the Same Cluster](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/restore-backup-same)
        * [Restore a Database Backup from Another Cluster](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/cross-cluster-backup)
        * [Differential Backup](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/differential-backups)
        * [Online Backup](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/online-backup)
        * [Legacy Backup and Restore](https://docs.tigergraph.com/tigergraph-server/3.11/backup-and-restore/gbar-legacy)
      * [Cluster and HA Management](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/)
        * Cluster Resizing
          * [Cluster Expansion](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/expand-a-cluster)
          * [Cluster Shrinking](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/shrink-a-cluster)
          * [Cluster Repartition](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/repartition-a-cluster)
          * [Cluster Replace](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/how_to-replace-a-node-in-a-cluster)
        * [Cross-Region Replication (CRR)](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/crr-index)
          * [Set up CRR](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/set-up-crr)
          * [Fail over to the DR cluster](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/fail-over)
          * [Troubleshooting CRR](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/troubleshooting)
          * [CRR FAQ](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/crr-faq)
        * [High Availability (HA)](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/ha-overview)
          * [Cluster Configuration](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/ha-cluster)
          * [GSQL Server Support](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/ha-for-gsql-server)
          * [Application Server Support](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/ha-for-application-server)
          * [Cluster Commands](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/cluster-commands)
          * [Removal of Failed Nodes](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/remove-failed-node)
      * [Architecture](https://docs.tigergraph.com/tigergraph-server/3.11/intro/internal-architecture)
        * [MultiGraph Overview](https://docs.tigergraph.com/tigergraph-server/3.11/intro/multigraph-overview)
        * [Transaction Processing and ACID Support](https://docs.tigergraph.com/tigergraph-server/3.11/intro/transaction-and-acid)
        * [Continuous Availability Overview](https://docs.tigergraph.com/tigergraph-server/3.11/intro/continuous-availability-overview)
      * [Kubernetes](https://docs.tigergraph.com/tigergraph-server/3.11/kubernetes/)
        * [Kubernetes Operator](https://docs.tigergraph.com/tigergraph-server/3.11/kubernetes/k8s-operator/)
  *     * [Security](https://docs.tigergraph.com/tigergraph-server/3.11/security/)
      * [Auditing Privileged User Actions](https://docs.tigergraph.com/tigergraph-server/3.11/security/audit-privileged-actions)
      * [Encrypting Connections](https://docs.tigergraph.com/tigergraph-server/3.11/security/encrypting-connections)
      * [Encrypting Data At Rest](https://docs.tigergraph.com/tigergraph-server/3.11/security/encrypting-data-at-rest)
      * [File Input Policy](https://docs.tigergraph.com/tigergraph-server/3.11/security/gsql-file-input-policy)
      * [File Output Policy](https://docs.tigergraph.com/tigergraph-server/3.11/security/file-output-policy)
      * [Login Policy](https://docs.tigergraph.com/tigergraph-server/3.11/security/login-protection)
      * [Password Policy](https://docs.tigergraph.com/tigergraph-server/3.11/security/password-policy)
  *     * [REST API Reference](https://docs.tigergraph.com/tigergraph-server/3.11/API/)
      * [Authentication](https://docs.tigergraph.com/tigergraph-server/3.11/API/authentication)
      * [Built-in Endpoints](https://docs.tigergraph.com/tigergraph-server/3.11/API/built-in-endpoints)
      * [Built-in Endpoints JSON Catalog](https://docs.tigergraph.com/tigergraph-server/3.11/API/json-catalog)
      * [Upsert data to graph](https://docs.tigergraph.com/tigergraph-server/3.11/API/upsert-rest)
  *     * Additional Resources
      * [Best Practices](https://docs.tigergraph.com/tigergraph-server/3.11/additional-resources/best-practice-guides/best-practices-overview)
        * [Scaling Guide](https://docs.tigergraph.com/tigergraph-server/3.11/additional-resources/best-practice-guides/best-prac-scaling-clusters)
      * Troubleshooting and FAQs
        * [Knowledge base and FAQs](https://kb.tigergraph.com/)
        * [Troubleshooting Guide](https://docs.tigergraph.com/tigergraph-server/3.11/troubleshooting/troubleshooting-guide)
        * [System Administration FAQs](https://docs.tigergraph.com/tigergraph-server/3.11/troubleshooting/system-administration-faqs)
        * [Log Files](https://docs.tigergraph.com/tigergraph-server/3.11/troubleshooting/log-files)
          * [Audit Logs](https://docs.tigergraph.com/tigergraph-server/3.11/troubleshooting/audit-log)
          * [Gathering Log Information with gcollect](https://docs.tigergraph.com/tigergraph-server/3.11/troubleshooting/gcollect)
          * [Set up Log Viewing with Elasticsearch, Kibana and Filebeat](https://docs.tigergraph.com/tigergraph-server/3.11/troubleshooting/elk-filebeat)
      * References
        * [Configuration Parameters](https://docs.tigergraph.com/tigergraph-server/3.11/reference/configuration-parameters)
        * [Return codes](https://docs.tigergraph.com/tigergraph-server/3.11/reference/return-codes)
        * [Object-Based Privilege Tables](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/rbac-row-policy/row-policy-privileges-table)
        * [List of Legacy Privilege Syntax](https://docs.tigergraph.com/tigergraph-server/3.11/reference/list-of-privileges)
        * [List of Ports](https://docs.tigergraph.com/tigergraph-server/3.11/reference/ports)
        * [Glossary](https://docs.tigergraph.com/tigergraph-server/3.11/reference/glossary)
        * [Patents and Third Party Software](https://docs.tigergraph.com/tigergraph-server/3.11/reference/patents-and-third-party-software)
        * [Legacy Version Documentation](https://docs.tigergraph.com/tigergraph-server/3.11/additional-resources/legacy-tg-versions)
        * [Comparing TigerGraph Editions](https://docs.tigergraph.com/tigergraph-server/3.11/intro/comparison-of-editions)
        * [Release and Patch Process](https://docs.tigergraph.com/tigergraph-server/3.11/intro/release-process)
        * [RBAC Row Policy EBNF](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/rbac-row-policy/row-policy-ebnf)


TigerGraph DB 3.11
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
  * [TigerGraph DB 3.11](https://docs.tigergraph.com/tigergraph-server/3.11/intro/)
  * Advanced Topics
  * [Access Management](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/)
  * Authorization
  * [Access Control Lists (ACLs)](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/3.11/modules/user-access/pages/acl-management.adoc)
### Contents
  * [Modify ACL passwords](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_modify_acl_passwords)
  * [Set ACL password](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_set_acl_password)
  * [Change ACL password](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_change_acl_password)
  * [Delete ACL password](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_delete_acl_password)
  * [Modify ACL privileges](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_modify_acl_privileges)
  * [Change query owner](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_change_query_owner)
  * [Grant ACL privilege to a role](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_grant_acl_privilege_to_a_role)
  * [Revoke ACL privilege from a role](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_revoke_acl_privilege_from_a_role)
  * [Revert access control to RBAC](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_revert_access_control_to_rbac)
  * [Disallow access for all](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_disallow_access_for_all)
  * [View ACL privileges](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_view_acl_privileges)
  * [View ACL entries on a query](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_view_acl_entries_on_a_query)
  * [View ACL privileges of a user](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_view_acl_privileges_of_a_user_)
  * [View ACL privileges of a role](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_view_acl_privileges_of_a_role)


# Access Control Lists (ACLs)
### Contents
  * [Modify ACL passwords](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_modify_acl_passwords)
  * [Set ACL password](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_set_acl_password)
  * [Change ACL password](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_change_acl_password)
  * [Delete ACL password](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_delete_acl_password)
  * [Modify ACL privileges](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_modify_acl_privileges)
  * [Change query owner](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_change_query_owner)
  * [Grant ACL privilege to a role](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_grant_acl_privilege_to_a_role)
  * [Revoke ACL privilege from a role](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_revoke_acl_privilege_from_a_role)
  * [Revert access control to RBAC](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_revert_access_control_to_rbac)
  * [Disallow access for all](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_disallow_access_for_all)
  * [View ACL privileges](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_view_acl_privileges)
  * [View ACL entries on a query](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_view_acl_entries_on_a_query)
  * [View ACL privileges of a user](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_view_acl_privileges_of_a_user_)
  * [View ACL privileges of a role](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_view_acl_privileges_of_a_role)


Access Control Lists (ACLs) allow you finer-grained control over access to queries. Using GSQL commands, you can change the owner of a query, grant ACL privileges on a query to a role, and view the ACL privileges on a user, a role, or a query.
## [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_modify_acl_passwords)Modify ACL passwords
### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_set_acl_password)Set ACL password
By default, users don’t have ACL passwords. They can choose to set an ACL password. Once a user’s ACL password is set, changing the ACL of queries owned by the user requires entering the user’s ACL password.
#### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_syntax)Syntax
  * Interactive
  * Non-interactive


```
ALTER [USER <username>] ACL PASSWORD
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This will prompt you to enter your ACL password.
```
ALTER [USER <username>] ACL PASSWORD SET <new_acl_password>
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_required_privilege)Required privilege
  * None if a user is setting their own ACL password
  * `WRITE_USER` if a user is setting the ACL password of another user


#### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_procedure)Procedure
  * Change password of current user
  * Change password of another user


To change the password of the current user, run the following command:
```
GSQL > ALTER ACL PASSWORD SET "example_Password" **(1)**
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | Putting the password in double quotes allow you to use special characters. You can enter a password without the double quotes, in which case you are only able to use alphanumerical characters.  
---|---  
To change the ACL password of another user, run the following command and replace `user1` with the user whose ACL password you want to change:
```
GSQL > ALTER USER user1 ACL PASSWORD SET examplePassword **(1)**
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | Since the password isn’t enclosed in double quotes, only alphanumerical characters are allowed.  
---|---  
### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_change_acl_password)Change ACL password
To change the ACL password of a user whose password has already been set, you need to enter their current ACL password.
#### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_syntax_2)Syntax
```
ALTER [USER <username>] ACL PASSWORD SET <new_acl_password> REPLACE <current_acl_password>
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_required_privilege_2)Required privilege
  * None if a user is changing their own ACL password.
  * `WRITE_USER` for changing the ACL password of another user.


In both scenarios, changing ACL password requires the current password.
#### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_procedure_2)Procedure
  * Change password of current user
  * Change password of another user


To change the password of the current user, run the following command and replace `"current_password"` with the current password of the user:
```
GSQL > ALTER ACL PASSWORD SET "new_password" REPLACE "current_password" **(1)**
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | Putting the password in double quotes allow you to use special characters. You can enter a password without the double quotes, in which case you are only able to use alphanumerical characters.  
---|---  
To change the password of another user, run the following command and replace `"current_password"` with the current password of the user:
```
GSQL > ALTER USER user1 ACL PASSWORD SET newPassword REPLACE currentPassword **(1)**
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | Since the password isn’t enclosed in double quotes, only alphanumerical characters are allowed.  
---|---  
### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_delete_acl_password)Delete ACL password
Users can delete their own ACL password or another user’s ACL password if they have the sufficient privilege and the current ACL password.
#### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_syntax_3)Syntax
```
ALTER [USER <username>] ACL PASSWORD CLEAR REPLACE <current_acl_password>
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_required_privilege_3)Required privilege
  * None if a user is deleting their own ACL password.
  * `WRITE_USER` for deleting the ACL password of another user.


In both scenarios, deleting ACL password requires the current password.
#### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_procedure_3)Procedure
  * Deleting password of current user
  * Deleting password of another user


To delete the ACL password of the current user, run the following command and replace `"current_password"` with the current password of the user:
```
GSQL > ALTER ACL PASSWORD CLEAR REPLACE "current_password"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

To delete the ACL password of another user, run the following command and replace `"current_password"` with the current password of the user:
```
GSQL > ALTER USER user1 ACL PASSWORD CLEAR REPLACE "current_password"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_modify_acl_privileges)Modify ACL privileges
### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_change_query_owner)Change query owner
With the ACL password of the current query owner, the owner themself or users with the `WRITE ROLE` privilege can change the owner of a query. If the current owner of the query doesn’t have an ACL password, then changing the owner does not require a password.
If a query does not have a current owner due to upgrades from an older version of TigerGraph, then anyone with the `WRITE_ROLE` privilege can run the command to change the query owner.
#### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_syntax_4)Syntax
```
CHANGE OWNER OF QUERY <query_name> TO <username> [SECURED BY <acl_password>] **(1)**
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | If current ACL password is not supplied in the command, GSQL prompts the user for the ACL password if the query owner has an ACL password.  
---|---  
#### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_required_privilege_4)Required privilege
  * None if the query is owned by the current user
  * `WRITE_ROLE` if the query is owned by another user


#### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_procedure_4)Procedure
To change the owner of a query, run the following command and replace `owner_password` with the ACL password of the query owner.
```
GSQL > CHANGE OWNER OF QUERY my_query TO user1 SECURED BY "owner_acl_password"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_grant_acl_privilege_to_a_role)Grant ACL privilege to a role
The owner and **only** the owner of a query can grant ACL privileges on the query to specified roles. To grant an ACL privilege, the query owner must themselves have the corresponding RBAC privilege.
#### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_syntax_5)Syntax
```
GRANT ACL PRIVILEGE ( READ | EXECUTE ) ON QUERY <query_name> TO <role1> (, <role2> ...)* [SECURED BY <owner_acl_password>] **(1)**
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | If current ACL password is not supplied in the command, GSQL prompts the user for the ACL password if the query owner has an ACL password.  
---|---  
#### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_required_privilege_5)Required privilege
  * `READ_QUERY` for granting `READ` privilege on the query.
  * `READ_DATA` for granting `EXECUTE` privilege on queries that do not update the graph.
  * `READ_DATA` and appropriate CRUD privileges for granting `EXECUTE` privilege on queries that create, update, or delete data of the graph.
    * For queries that update existing vertices and edges, the `UPDATE_DATA` privilege is needed.
    * For queries that delete vertices or edges, the `DELETE_DATA` privilege is needed.
    * For queries that create vertices or edges, the ACL privilege situation can be more complicated. See [Data CRUD privileges](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/access-control-model#_data_crud_privileges).


#### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_procedure_5)Procedure
To grant `READ` privilege for a query `example_query` to a role `example_role`, run the following command. To grant `EXECUTE` privilege instead, replace `READ` with `EXECUTE`:
```
GSQL > GRANT ACL PRIVILEGE READ ON QUERY example_query TO example_role
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_revoke_acl_privilege_from_a_role)Revoke ACL privilege from a role
The owner of a query can revoke ACL privileges on the query from a role. If the ACL entry for a privilege (either `READ` or `EXECUTE`) becomes empty after removing specified roles, the [entry status](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/access-control-model#_acl_entry_status) for the privilege becomes `NOBODY`. When the ACL entry status for a privilege is `NOBODY`, no one, including the query owner, can access the query in the corresponding manner.
The effect of revoking ACL privileges from all roles in an entry by revoking from specified roles is different from [revoking ACL privileges from all using the keyword `ALL`](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_revert_access_control_to_rbac).  
---  
#### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_syntax_6)Syntax
```
REVOKE ACL PRIVILEGE ( READ | EXECUTE ) ON QUERY <query_name> FROM <role1> (, <role2>, ... )* [SECURED BY <owner_acl_password>] **(1)**
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | If current ACL password is not supplied in the command, GSQL prompts the user for the ACL password if the query owner has an ACL password.  
---|---  
#### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_required_privilege_6)Required privilege
None. Only query owner can run the command. If the query owner set their ACL password, running the command requires entering the ACL password.
#### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_procedure_6)Procedure
To revoke ACL `READ` privilege on `example_query` from `role1`, run the following command and replace `owner_acl_password` with the ACL password of the owner. If you want to remove `EXECUTE` privilege, replace `READ` with `EXECUTE`.
```
GSQL > REVOKE ACL PRIVILEGE READ ON QUERY example_query FROM role1 SECURED BY
"owner_acl_password"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_revert_access_control_to_rbac)Revert access control to RBAC
The owner of a query can choose to revert access control governance of a query to RBAC by changing its ACL entry status to unspecified.
#### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_syntax_7)Syntax
```
REVOKE ACL PRIVILEGE ( READ | EXECUTE ) ON QUERY <query_name> FROM ALL [SECURED BY <owner_acl_password>] **(1)**
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | If current ACL password is not supplied in the command, GSQL prompts the user for the ACL password if the query owner has an ACL password.  
---|---  
#### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_required_privilege_7)Required privilege
None. Only query owner can run the command. If the query owner set their ACL password, running the command requires entering the ACL password.
#### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_procedure_7)Procedure
To revert access control on read operations on `example_query` to RBAC, run the following command and replace `owner_acl_password` with the ACL password of the owner. If you want to revert access control for `RUN QUERY` (`EXECUTE` privilege), replace `READ` with `EXECUTE`.
```
GSQL > REVOKE ACL PRIVILEGE READ ON QUERY example_query FROM ALL SECURED BY
"owner_acl_password"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_disallow_access_for_all)Disallow access for all
If the query owner grants a type of ACL privilege on a query to `NOBODY`, no one will be able to access the query, including the query owner.
#### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_syntax_8)Syntax
```
GRANT ACL PRIVILEGE ( READ | EXECUTE ) ON QUERY <query_name> TO NOBODY [ SECURED BY <owner_acl_password> ] **(1)**
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | If current ACL password is not supplied in the command, GSQL prompts the user for the ACL password if the query owner has an ACL password.  
---|---  
#### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_required_privilege_8)Required privilege
None. Only query owner can run this command. If the query owner set their ACL password, running the command requires entering the ACL password.
#### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_procedure_8)Procedure
To disallow read access to query `example_query`, run the following command as the query owner. If the query owner set an ACL password, you need to use the `SECURED BY` option to enter the ACL password.
```
GSQL > GRANT ACL PRIVILEGE READ ON QUERY example_query TO NOBODY
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_view_acl_privileges)View ACL privileges
### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_view_acl_entries_on_a_query)View ACL entries on a query
You can view the entries on a query’s access control list. The ACL shows the owner of the query, as well as which roles can read or execute the query.
#### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_syntax_9)Syntax
```
SHOW ACL PRIVILEGE ON QUERY <query1> (, <query2> ...)*
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_required_privilege_9)Required privilege
#### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_procedure_9)Procedure
To view the access control list of `query1` and `query2`, run the following command:
```
GSQL > SHOW ACL PRIVILEGE ON QUERY query1, query2
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_view_acl_privileges_of_a_user_)View ACL privileges of a user
You can view the ACL privileges of a user. This allows you to see the queries owned by the user, as well as the queries that the user has read and execute access to on all graphs where you have the `READ_USER` privilege.
#### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_syntax_10)Syntax
```
SHOW ACL PRIVILEGE ON USER <user1> (, <user2> ...)*
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_required_privilege_10)Required privilege
`READ_USER`
#### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_procedure_10)Procedure
To view the ACL privileges of `user1` and `user2`, run the following command:
```
GSQL > SHOW ACL PRIVILEGE ON USER user1, user2
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_view_acl_privileges_of_a_role)View ACL privileges of a role
You can view the ACL privileges of a role. This shows the queries the role has read or execute access to on all graphs where you have the `READ_ROLE` privilege.
#### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_syntax_11)Syntax
```
SHOW ACL PRIVILEGE ON ROLE <role1> (, <role1> ...)*
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_required_privilege_11)Required privilege
`READ_ROLE`
#### [](https://docs.tigergraph.com/tigergraph-server/3.11/user-access/acl-management#_procedure_11)Procedure
To view the ACL privileges of role `role1` and `role2`, run the following command:
```
SHOW ACL PRIVILEGE ON ROLE role1, role2
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

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


