![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/)[Next](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/)
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
  * [TigerGraph DB Release Notes](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/3.10/modules/release-notes/pages/index.adoc)
### Contents
  * [Key New Features](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_key_new_features)
  * [Detailed List of New and Modified Features](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_detailed_list_of_new_and_modified_features)
  * [TigerGraph Server](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_tigergraph_server)
  * [GSQL Command and Querying Language](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_gsql_command_and_querying_language)
  * [System Management and Monitoring Enhancements](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_system_management_and_monitoring_enhancements)
  * [Kubernetes Operator](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_kubernetes_operator)
  * [Security](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_security)
  * [TigerGraph Suite Updates](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_tigergraph_suite_updates)
  * [Admin Portal](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_admin_portal)
  * [GraphStudio](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_graphstudio)
  * [TigerGraph Insights](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_tigergraph_insights)
  * [Fixed issues](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_fixed_issues)
  * [Fixed and Improved in 3.10.3](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_fixed_and_improved_in_3_10_3)
  * [Fixed and Improved in 3.10.2](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_fixed_and_improved_in_3_10_2)
  * [Fixed and Improved in 3.10.1](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_fixed_and_improved_in_3_10_1)
  * [Fixed and Improved in 3.10.0](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_fixed_and_improved_in_3_10_0)
  * [Known Issues and Limitations](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_known_issues_and_limitations)
  * [Compatibility Issues](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_compatibility_issues)
  * [Deprecations](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_deprecations)
  * [Release notes for previous versions](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_release_notes_for_previous_versions)


# TigerGraph DB Release Notes
Table of Contents
  * [Key New Features](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_key_new_features)
  * [Detailed List of New and Modified Features](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_detailed_list_of_new_and_modified_features)
    * [TigerGraph Server](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_tigergraph_server)
    * [GSQL Command and Querying Language](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_gsql_command_and_querying_language)
    * [System Management and Monitoring Enhancements](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_system_management_and_monitoring_enhancements)
    * [Kubernetes Operator](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_kubernetes_operator)
    * [Security](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_security)
  * [TigerGraph Suite Updates](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_tigergraph_suite_updates)
    * [Admin Portal](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_admin_portal)
    * [GraphStudio](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_graphstudio)
    * [TigerGraph Insights](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_tigergraph_insights)
  * [Fixed issues](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_fixed_issues)
    * [Fixed and Improved in 3.10.3](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_fixed_and_improved_in_3_10_3)
    * [Fixed and Improved in 3.10.2](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_fixed_and_improved_in_3_10_2)
    * [Fixed and Improved in 3.10.1](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_fixed_and_improved_in_3_10_1)
    * [Fixed and Improved in 3.10.0](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_fixed_and_improved_in_3_10_0)
  * [Known Issues and Limitations](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_known_issues_and_limitations)
    * [Compatibility Issues](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_compatibility_issues)
    * [Deprecations](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_deprecations)
  * [Release notes for previous versions](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_release_notes_for_previous_versions)


TigerGraph Server 3.10.3 LTS was released on Jan 28, 2025.
TigerGraph Server 3.10.2 LTS was released on Oct 18, 2024.
TigerGraph Server 3.10.1 LTS was released on May 7, 2024.
TigerGraph Server 3.10.0 preview version was released on March 13, 2024.
LTS versions are supported for 24 months from their initial GA release (X.X.1) and should be the choice for production deployments.
## [](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_key_new_features)Key New Features
  * [Change Data Capture (CDC)](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-overview) - This equips TigerGraph users with the capability to automatically capture and stream data changes to external Kafka systems maintained by the user. Additionally, CDC can be [configured](https://docs.tigergraph.com/gui/3.10/admin-portal/components/cdc) in [Admin Portal](https://docs.tigergraph.com/gui/3.10/admin-portal/overview).
  * [Workload Queue](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/workload-management#_workload_queue) - Configure workload queues so that queries are routed to the appropriate queues during runtime.
  * [Spark Connector](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe) - A new dedicated connector used with Apache Spark to read data from a Spark DataFrame and write to TigerGraph.
  * [Online Backup](https://docs.tigergraph.com/tigergraph-server/3.10/backup-and-restore/online-backup) - Minimizes blocking time during backups, allowing successful execution of post requests for TigerGraph users.
  * [Differential Backup](https://docs.tigergraph.com/tigergraph-server/3.10/backup-and-restore/differential-backups) - Ensure data files that have changed since the most recently completed full backup are backed up without any data lost.
  * [Refined Upgrading process](https://docs.tigergraph.com/tigergraph-server/3.10/installation/upgrade#_upgrading_from_3_x) - Changes to the upgrading process to allow a TigerGraph upgrade without having to upgrade the K8’s operator.
  * [Support Non-Interactive Upgrade](https://docs.tigergraph.com/tigergraph-server/3.10/installation/upgrade#_option_n) - The user can use option `-n` to avoid input ( `y/n` ) to switch to the new version.
  * [Global Schema Restrict to Global Scope](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/modifying-a-graph-schema#_global_vs_local_schema_changes) - Users must have the global scope to interact with global schema change jobs (create, delete, run).


## [](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_detailed_list_of_new_and_modified_features)Detailed List of New and Modified Features
### [](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_tigergraph_server)TigerGraph Server
  * [3.10.1] [Two new configurations to help tune re-builder scheduling logic](https://docs.tigergraph.com/tigergraph-server/3.10/reference/configuration-parameters#_environment_variables) - When running `GPE.BasicConfig.Env.` there are two new configurations `SegmentMetaFlushAlways` and `SegmentMetaForceFlushIntervalSec` to help fine tune re-builder scheduling.
  * [3.10.1] [Ubuntu 22.04 is now certified](https://docs.tigergraph.com/tigergraph-server/3.10/installation/hw-and-sw-requirements#_certified_operating_systems) - Ubuntu 22.04 is now one of TigerGraph’s certified OS systems.
  * [3.10.1] [Audit log support for direct RESTPP API calls](https://docs.tigergraph.com/tigergraph-server/3.10/troubleshooting/audit-log#_rest_api_call_audit_logs) - Audit logs now record direct REST++ API Calls.
  * [3.10.1] Added new [Return Codes](https://docs.tigergraph.com/tigergraph-server/3.10/reference/return-codes):
    * `REST-4000` - Response time exceeds the timeout limit.
    * `REST-10020` - License has expired.
    * `REST-10021` - Access to the file has failed.
    * `REST-30001` - The parameter is invalid (general error).
  * [3.10.1] [New configuration field System.Metrics.IncludeHostName](https://docs.tigergraph.com/tigergraph-server/3.10/reference/configuration-parameters) - Users now have the option to include hostname/ip in the metrics output in OpenMetrics format.
  * [3.10.1] [Nodes can now be paired with hostnames in installation](https://docs.tigergraph.com/tigergraph-server/3.10/installation/bare-metal-install) - Users now can set the node by ip or hostname during installation. This is supported in both interactive and non-interactive installation.
  * [3.10.1] [Make request with GSQL-Secret](https://docs.tigergraph.com/cloud/main/solutions/access-solution/rest-requests#_secret_request) - users can now use the authorization secret in a request header as a GSQL-Secret.
  * [3.10.1] [Four new reserved keywords](https://docs.tigergraph.com/gsql-ref/3.10/appendix/keywords-and-reserved-words) - `FUNCTION`, `OPENCYPHER`, `POLICY`, and `ROW` have all been added to the DDL GSQL reserved words and keywords list.
  * [Audit Logs](https://docs.tigergraph.com/tigergraph-server/3.10/troubleshooting/audit-log) - Audit logs maintain a historical record of activity events, noting the time, responsible user or service, and affected entity.
  * [Import/Export Individual Graphs](https://docs.tigergraph.com/tigergraph-server/3.10/backup-and-restore/single-graph-import-export) - Users can now import or export individually selected graphs.
  * [Updates to the Set Up CRR](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/set-up-crr) - Updates to the Cross-Region Replication (CRR) setup enable this feature to flow into the `gadmin backup restore` process preventing a writable gap.
  * [Externalizing Kafka Configs using Config Provider](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/externalizing-kafka-configs) - TigerGraph’s Kafka connector config will use a reference to retrieve the config value from an external source.
  * [Two new flags for gadmin backup create](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/management-commands#_gadmin_backup_create) - added two parameters to enable data consistency checks during the backup.


### [](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_gsql_command_and_querying_language)GSQL Command and Querying Language
  * [Context Functions](https://docs.tigergraph.com/gsql-ref/3.10/querying/func/context-functions) - Context functions are a set of new built-in functions that provide insights into the user’s information and work inside `INSTALLED` queries, `INTERPRET` queries, and [GSQL Functions](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/rbac-row-policy/rbac-row-policy#_gsql_functions).
  * [Command Updates](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/management-commands) - Added new flag `--local` to commands [gadmin start](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/management-commands#_gadmin_start) and [gadmin stop](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/management-commands#_gadmin_stop ) reducing the time required to start/stop local services.
  * [GSQL Data Streaming Improvements](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_improvements) - Improvements to GSQL data streaming that reduce the CPU usage, improve performance, optimizes Disk usage, and increases stability and cohesion.


#### [](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_loading)Loading
  * [Support for Snowflake Data Warehouse](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-warehouse) - Added support for loading data from Snowflake, another popular data warehouse.
  * [Support for PostgreSql Data Warehouse](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-warehouse) - Added support for loading data from PostgreSql, another popular data warehouse.
  * [Avro Data Validation with KafkaConnect](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/avro-validation-with-kafka) - The KafkaConnect feature flag `ErrorTolerance` enables data loading services to handle malformed data and report errors effectively
  * [Local file and Kafka loader Auto-Restart](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/ha-overview#_file_and_kafka_loaders_ha_with_auto_restart) - Local file and Kafka loader will now auto restart if it unexpectedly quits.


#### [](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_schema)Schema
  * New non-interactive mode GSQL operations - Added four new non-interactive mode for operations [create user](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/user-management#_non_interactive_mode), [alter password](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/user-management#_non_interactive_mode), [export graph all](https://docs.tigergraph.com/tigergraph-server/3.10/backup-and-restore/database-import-export#_non_interactive_mode_export_graph_all), and [import graph all](https://docs.tigergraph.com/tigergraph-server/3.10/backup-and-restore/database-import-export#_non_interactive_mode_import_graph_all).


#### [](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_querying_and_query_management)Querying and Query Management
  * [3.10.1] [New impact warnings when running schema change job](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/modifying-a-graph-schema#_impact_warning) - Added a warning message when running the global or local schema change job so, users can understand the impact of running a global or local schema change on a query.
  * [Support Edge Accumulators](https://docs.tigergraph.com/gsql-ref/3.10/querying/accumulators#_edge_accumulators) - Support for edge accumulators for a single-hop distributed query.
  * [Option -N to schema change job](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/modifying-a-graph-schema#_run_global_schema_change_job) - Added an option to `RUN SCHEMA_CHANGE JOB` that skips recompile and reinstall queries.


### [](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_system_management_and_monitoring_enhancements)System Management and Monitoring Enhancements
  * [3.10.2] **[Enhanced Metrics Reports](https://docs.tigergraph.com/tigergraph-server/3.10/API/built-in-endpoints#_monitor_system_metrics_openmetrics_format)** Total and available capacity for CPU and memory are now reported by the `/informant/metrics` endpoint.


### [](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_kubernetes_operator)Kubernetes Operator
  * [3.10.1] [Kubernetes Operator is GA](https://docs.tigergraph.com/tigergraph-server/3.10/kubernetes/k8s-operator/) - The Kubernetes Operator is now in GA with 3.10.1.
  * [Added new fields](https://github.com/tigergraph/ecosys/blob/master/k8s/docs/07-reference/configure-tigergraph-cluster-cr-with-yaml-manifests.md) - `.spec.tigergraphConfig` in TigerGraph CR and a new option `--tigergraph-config` in kubectl-tg plugin.
  * [Updates to cluster creation using YAML](https://github.com/tigergraph/ecosys/blob/k8s-operator/0.1.0/k8s/docs/07-reference/configure-tigergraph-cluster-cr-with-yaml-manifests.md) - Improvements to the configurations to align with the database.
  * [Support for mounting multiple PVC and PV for pods](https://github.com/tigergraph/ecosys/blob/k8s-operator/0.1.0/k8s/docs/03-deploy/multiple-persistent-volumes-mounting.md) - Added two optional fields `additionalStorages` and `spec.storage` to customize the PV for TigerGraph pods.
  * [Support for customizing of pods](https://github.com/tigergraph/ecosys/blob/k8s-operator/0.1.0/k8s/docs/03-deploy/customize-tigergraph-pod.md) - Customize the pods or containers, for example, users can add more customized labels and annotations or change the security context of the containers.
  * [Pause a running cluster](https://github.com/tigergraph/ecosys/blob/k8s-operator/0.1.0/k8s/docs/07-reference/configure-tigergraph-cluster-cr-with-yaml-manifests.md) - Added a new field `.spec.pause` in TigerGraph CR and a new subcommand `kubectl tg pause` in `kubectl-tg plugin`. Users scan set `.spec.pause=true` to pause a running cluster and resume it by setting `.spec.pause=false`.


### [](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_security)Security
  * [3.10.1] [SSO Match Strategy Extension](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/sso#_match_strategy_extensions) - SSO match strategy has been extended to allow matches via regular expression.
  * [3.10.1] [Added a JWT Token config](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/jwt-token#_optional_configurations) - `Security.JWT.Audience` added to allow users to set a JWT Token authentication that verifies if the `aud` (recipient for which the JWT is intended) defined in JWT Token matches the configured one or not.
  * [RBAC: Row Policy (Preview Feature)](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/rbac-row-policy/row-policy-overview) - is used to control access to specific rows of data in TigerGraph. See also [RBAC Row Policy EBNF](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/rbac-row-policy/row-policy-ebnf) for examples.
  * [Object-Based Privileges](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/rbac-row-policy/rbac-row-policy#_object_based_privileges) - This mechanism allows users to grant or revoke privileges based on specific objects. See [Object-Based Privilege Tables](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/rbac-row-policy/row-policy-privileges-table) for a complete list.
  * [OIDC JWT Authentication](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/jwt-token) - Provides token-based authentication in JSON web token (JWT) format, allows TigerGraph users better control over application access.
  * [File Input Policy](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy) - `GSQL.fileInputPolicy` allows users to apply restrictions on the location of local files used to load data to TigerGraph.
  * [Kafka Security via SSL](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/kafka-ssl-security-guide) - Kafka brokers can be secured by SSL including the connections from Kafka clients to Kafka brokers.


## [](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_tigergraph_suite_updates)TigerGraph Suite Updates
### [](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_admin_portal)Admin Portal
  * [Change Data Capture (CDC)](https://docs.tigergraph.com/gui/3.10/admin-portal/components/cdc) can be enabled in [Admin Portal](https://docs.tigergraph.com/gui/3.10/admin-portal/overview).
  * [SSO.OIDC via Okta](https://docs.tigergraph.com/gui/3.10/admin-portal/security/sso-oidc-okta) - Support for Standard OIDC Authorization Code Flow for general purpose adds more security for logins to Admin Portal Users.


### [](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_graphstudio)GraphStudio
  * [Single Graph Import and Export Support](https://docs.tigergraph.com/gui/3.10/graphstudio/export-and-import-solution) - Allow users to choose a single graph and the data when they export or import data in GraphStudio.
  * [New GUI command to disable concurrent sessions ](https://docs.tigergraph.com/tigergraph-server/3.10/reference/configuration-parameters#_gui) - `GUI.EnableConcurrentSession` allows users to disable concurrent sessions so that multiple browsers cannot log in with the same username at the same time, revoking the previous session and warning the user to re-login.


### [](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_tigergraph_insights)TigerGraph Insights
  * [Changing Single Value Widget to Value Widget](https://docs.tigergraph.com/insights/3.10/widgets/single-value) - Modified the value element of insights to support the mapping of multiple values.
  * [Added Markdown Widget](https://docs.tigergraph.com/insights/3.10/widgets/markdown-widget) - This addition allows users to add formatted text, links, images, and other rich content to the dashboards.
  * [Conditional Styling Widget Update](https://docs.tigergraph.com/insights/3.10/widgets/conditional-styling) - Conditional styling can now be applied to edges, with the addition of an `always` [option](https://docs.tigergraph.com/insights/3.10/widgets/conditional-styling#_always_option) in the condition dropdown.
  * [Added Scatter Chart Widget](https://docs.tigergraph.com/insights/3.10/widgets/scatter-plot-widget) - The scatter chart will provide a visual representation of the relationship between two numerical variables, allowing users to identify patterns or correlations in the data.


## [](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_fixed_issues)Fixed issues
### [](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_fixed_and_improved_in_3_10_3)Fixed and Improved in 3.10.3
#### [](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_functionality)Functionality
  * Fixed issue where query installation failed for single-node queries that initialize vertex set variables in conditional branches (e.g., if-else or case-when statements) (GLE-8845).
  * Fixed query compilation error when iterating through a `FOREACH` statement to retrieve an accum type attribute in a query compiled with the `-single` or `distributed` keyword. Ensured operations between two different `GroupByAccums` hold the same data types and field names (GLE-9053).
  * Fixed a parsing issue with loading job creation when using double quotes inside a string literal (GLE-8696).
  * Fixed an issue where schema changes could fail to occur during the loading process due to a lock not being removed (GLE-7572).
  * Fixed disk critical issue caused by the rebuilder getting stuck in a partitioned cluster after dropping vertex or edge attributes (CORE-4356).
  * Fixed an issue where failed backups in rare cases could cause the engine to pause for a long time, leading to query timeouts (CORE-4499).
  * Fixed issue where CDC EDGE messages with "UNKNOWN" ID were not removed when a query deleted a vertex and its associated edge (CORE-4491).
  * Fixed issue where "UNKNOWN" ID appeared in CDC messages under heavy load conditions on GSE (CORE-4443).
  * Fixed issue preventing downloading of GSQL output files larger than 3GB in the AdminPortal, impacting the GUS component (APPS-3277).
  * Fixed issue preventing downloading of GSQL output files larger than 3GB in the AdminPortal, impacting the EXE component (TP-6745).
  * Ensured GSQL and the GUI are online before importing data during the restore process (TP-6947).


#### [](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_improvements)Improvements
  * Improved the performance of GSQL queries containing delete statements intended for deleting all vertices of a given type (GLE-8930).


### [](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_fixed_and_improved_in_3_10_2)Fixed and Improved in 3.10.2
  * Fixed issue where local accumulators defined across multiple lines in a query were misinterpreted in the GSQL client (GLE-8259).
  * Fixed issue in the post-upgrade check that causes the upgrade to abort due to insufficient permissions to the /tmp directory (GLE-8005).
  * Fixed issue where loading jobs with a `WHERE` condition would hang after upgrading from an older version (GLE-7953).
  * Added an error report if a schema check is requested but cannot be performed because the GPE is in warmup status (GLE-7898).
  * Fixed situation where a query containing a `BREAK` or `CONTINUE` statements could produce incorrect results (GLE-7874).
  * Fixed regression problem with installing queries which create lists containing mixed types of numeric data (GLE-7928).
  * Resolved an intermittent deadlock in Informant that caused `gadmin status` to fail (TP-5930).
  * Fixed int64 value underflow error by explicitly type casting uint64 (CORE-4108).
  * Restored the ability to run the TigerGraph `gcollect` command on Kubernetes (TP-6351).
  * Fixed issue with database import hanging caused by the status of a loading job not being received by Kafka streaming library (TP-5772).
  * Allowed installation to continue on Oracle and RedHat Linux, 8 even if the TigerGraph user is not listed in AllowedUsers in /etc/ssh/sshd_config (TP-5105).
  * Fixed an issue so IMPORT ALL will no longer fail due to the schema size being very large (GLE-6505).


### [](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_fixed_and_improved_in_3_10_1)Fixed and Improved in 3.10.1
#### [](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_functionality_2)Functionality
  * Fixed known issue where the attribute name `memberOf` was case-sensitive. It is now case-insensitive (GLE-6660).
  * Fixed issue of clarity for error message/log when global `schema_change` failed for adding edge but it’s relied on vertex does not exist (GLE-6751).
  * Fixed issue where installation was halted due to TigerGraph disks mounted with `noexec` on AppRoot or DataRoot, preventing execution (TP-4929).
  * Fixed issue where there was a delay in loading response times due to syntax detection process in GSQL (GLE-6822).
  * Fixed issue were there was a GPE failure reported during query execution prompting relocation from `/tmp` to `System.TempRoot` (GLE-5536).
  * Fixed issue where incorrect error response occurred when specified graph does not exist (APS-2824).
  * Fixed issue where users encountered error `Vertex expansion failed: c.default.post is not a function` during Explore Neighbors operation in Insight (APS-2840).


#### [](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_security_2)Security
  * Enhanced security by disabling unapproved SSL/TLS protocols of `DHE-RSA-AES128-GCM-SHA256` and `DHE-RSA-AES256-GCM-SHA384` and upgrading to TLS 1.3 in Nginx (APPS-2729).


### [](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_fixed_and_improved_in_3_10_0)Fixed and Improved in 3.10.0
#### [](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_functionality_3)Functionality
  * Fixed issue where if the primary node is offline, access to Graph Studio was interrupted, but resumed once the primary node is back online (APPS-258).
  * Fixed issue where some `GPR` and `Interpret` queries that specified the built-in `filter()` function would fail installation because of a row policy or tag filter (GLE-6448).
  * Fixed issue when restarting Restpp and resulted in the task count being greater than the actual number (TP-4498).
  * Fixed Issue in 3.9.3 and 3.10.0 versions could not run a GSQL query when a single node is down in a High Availability cluster. See [3.9.2 and below](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/ha-overview#_3_9_2_and_below) versions workaround for more details.
  * Fixed issue when changes would not save when switching to fullscreen and back in Insights (APPS-2197).
  * Fixed issues where a vertex would not move after expanding in `Explore Graph` (APPS-2540).
  * Fixed issue in Exception statements where if it was placed before any query-body statements, it would cause both branches of an `IF-ELSE` statement to be executed (GLE-3998).
  * Fixed issue where an error in how the `ACCUM` clause is transformed, results in a transformed query with a semantic error. See [accumulator types](https://docs.tigergraph.com/gsql-ref/3.10/querying/accumulators#_accumulator_types) for more details on valid types (GLE-5695).
  * Fixed issue when parsing a negative float parameter to GSQL CLI in `{key:value}` format would create an argument error (GLE-5875).


#### [](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_crashes_and_deadlocks)Crashes and Deadlocks
  * Fixed GPE crash during query execution when accumulators values are not vaild. See [accumulator types](https://docs.tigergraph.com/gsql-ref/3.10/querying/accumulators#_accumulator_types) for more details (GLE-4411).


#### [](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_improvements_2)Improvements
  * Improved by significantly reducing the CPU usage when a large number of loading jobs are started at the same time (TP-4159).
  * Improved the write speed of loading jobs (TP-4159).
  * Improved disk usage optimization by restricting a loading job in waiting status to only consumes disk resources when it actually writes data (TP-4474).
  * Improved stability and cohesion of the connector and loader, which helps create better synchronization and reduces inconsistencies in the statuses (TP-4158).
  * Improved significantly the pause time during backups from a few minutes to a couple of seconds, regardless of the data size. (CORE-3000).
  * Improved data consistency during the backup and restore process (Core-3000).
  * Improved availability when one KSL server in error state (TP-4378 & TP-4593).
  * Improved the required privilege for `/rebuildnow` and `/deleted_vertex_check` making both now `Graph-level “READ DATA”` privilege and now able to run on DR cluster in CRR feature.(CORE-3291).
  * Improved exception statements by adding a [default exception format](https://docs.tigergraph.com/gsql-ref/3.10/querying/exception-statements#_exception_format_not_defined_in_query) available in cases where the exception is not defined in the query (GLE-5854)
  * Improved long-running RESTPP requests and will now use less memory (CORE-3027).
  * Improved log files names from `log.AUDIT` to `log.AUDIT-GSQL` (GLE-6496).
  * Improved audit log `timestamp` format by extending format from `2023-12-20 14:42:50.25` to this `2023-12-20T14:42:50.243-07:00` (GLE-6395).
  * Improved `userAgent` field clarity in audit logs when authenticating failed. Audit log will now record the correct user agent (GLE-6404).
  * Improved audit logs by adding operating system’s username to the audit log record (GLE-6394).
  * Improved SearchFile experience by increasing the `GRPC_CLIENT_TIMEOUT` (APPS-2711).
  * Improved functionality of the `ExprFunction` file to automatically remove the leftover “to_string” function in ExprFunction file (GLE-5834).
  * Improved retention strategy for `EventQueue` that improved timely monitoring of the utilization of disk space (TP-4920).
  * Improved service logs accuracy to show SSO users username in log (APPS-2496).


## [](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_known_issues_and_limitations)Known Issues and Limitations
Description | Found In | Workaround | Fixed In  
---|---|---|---  
Running either `EXPORT GRAPH ALL` or `IMPORT GRAPH ALL` resets the TigerGraph superuser’s password back to its default value. | 3.9.1 | After running either command, change the superuser’s password to make it secure again. | TBD  
[EXPORT GRAPH ALL](https://docs.tigergraph.com/tigergraph-server/3.10/backup-and-restore/database-import-export) does not correctly handle loading jobs containing `DELETE` statements nor graph elements with composite keys. `EXPORT GRAPH ALL` may fail if the data includes a `UDT` with a fixed string size. | 3.2 | TBD  
When using [IMPORT ALL](https://docs.tigergraph.com/tigergraph-server/3.10/backup-and-restore/database-import-export) if a users schema size in the `.zip` file is exceedingly large, the import may fail with an error messages like this: `Large catalog file key: /1/ReplicaList.json` | 3.2 | 
  * 3.9 and below users need to run the import process manually by executing the GSQL scripts in the `.zip`.
  * 3.10.0 and above users should [import single or smaller batches of multiple graphs](https://docs.tigergraph.com/tigergraph-server/3.10/backup-and-restore/single-graph-import-export).

| TBD  
If importing a role, policy, or function that has a different signature or content from the existing one, the one being imported will be skipped and not aborted. For example:
  * If the original function is: `create function lib1.func2(int param1, float param2, string param3) returns (bool) {}`.
  * And the user imports the new function: `create function lib1.func2(int param1) returns (bool) {}`. This second one will be skipped.

| 3.10.0 | Users need to re-create (delete and create) the imported role, policy, or function manually, and make sure that the importing one meets the requirements set by the existing one. | TBD  
[Row Policy (Preview Feature)](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/rbac-row-policy/row-policy-overview) does not yet filter or check vertex attribute data in upsert operations, such as:
  * A query with insert statements.
  * A file or Kafka loading job.
  * A DDL loading request.
  * Or a standard upsert request.

| 3.10.0 | Users should restrict the access of creating/running queries and loading jobs for roles related to row policy. | TBD  
In file INPUT and OUTPUT policy, if there exists 2 path (`path1` and `path2`) in the configured policy list and `path1` is parent path of `path2`, then `path1` may not be effective. | 3.2 and 3.10.0 | Users should avoid using paths if they are nested. For example, avoid this scenario, path2 = `"/tmp/more"` and path1= `"/tmp"`. | 3.10.1  
It has been observed that an issue happens when RESTPP will send a request to all gpes, and if one is down, the request sent to it will `timeout`. Including the `consistency_check` request will also mark as `timeout`. | 3.10.0 | 
  1. Run `/rebuildnow` to rebuild all the segments. |  Running `/rebuildnow` when one gpe is down will result in the request timeout. This does not mean the request failed, instead only the currently running GPE will do the rebuild, and any rebuild requests sent to the down GPEs will result in a timeout.  
---  
  2. Run `/data_consistency_check?realtime=false` to check the consistency.


TBD  
While running `EXPORT GRAPH` if the disk space is not enough, or the data has not been detected, the export data will get stuck loading. | 3.10.0 | Restart all services in Admin Portal or the backend. | TBD  
`[tg_]ExprFunction.hpp` will be automatically merged while importing single graphs. In some cases, query compilation may fail. | 3.10.0 | See [Known Issues and Workarounds](https://docs.tigergraph.com/tigergraph-server/3.10/backup-and-restore/single-graph-import-export#_known_issues_and_workarounds) | TBD  
Upgrading from a previous version of TigerGraph has known issues. | 3.10.0 | See section [Known Issues and Workarounds](https://docs.tigergraph.com/tigergraph-server/3.10/installation/upgrade#_known_issues_and_workarounds) for more details. | TBD  
Input Policy feature has known limitations. | 3.10.0 | See section [Input Policy Limitations](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_limitations) for more details. | TBD  
Change Data Capture (CDC) feature has known limitations. | 3.10.0 | See section [CDC Limitations](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-overview#_cdc_limitations) for more details. | TBD  
If the `FROM` clause pattern is a multi-hop and the `ACCUM` clause reads both primitive and container type attributes or accumulators of a vertex, the internal query rewriting logic may generate an invalid rewritten output. | 3.9.3 | This results in the error message: `It is not allowed to mix primitive types and accumulator types in GroupByAccum`. | TBD  
Users may see a high CPU usage caused by Kafka prefetching when there is no query or posting request. | 3.9.3 | TBD | TBD  
GSQL query compiler may report a false error for a valid query using a vertex set variable (e.g. `Ent` in `reverse_traversal_syntax_err`) to specify the midpoint or target vertex of a path in a FROM clause pattern. | TBD | TBD | TBD  
If a loading job is expected to load from a large batch of files or Kafka queues (e.g. more than 500), the job’s status may not be updated for an extended period of time. | 3.9.3 | In this case, users should check the loader log file as an additional reference for loading status. | TBD  
When a GPE/GSE is turned off right after initiating a loading job, the loading job is terminated internally. However, users may still observe the loading job as running on their end. | 3.9.3 | Please see [Troubleshooting Loading Job Delays](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/running-a-loading-job) for additional details. | TBD  
For v3.9.1 and v3.9.2 when inserting a new edge in `GPR` and `INTERPRET` mode, the GPE will print out a warning message because a discriminator string is not set for new-inserted edges. Creating an inconsistent problem in delta message for GPR and `INTERPRET` mode. | 3.9.2 | Please see [Troubleshooting Loading Job Delays](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/running-a-loading-job) for additional details. | 3.9.3  
GSQL `EXPORT GRAPH` may fail and cause a GPE to crash when UDT type has a fixed STRING size. | TBD | TBD | TBD  
After a global loading job is running for a while a fail can be encountered when getting the loading status due to `KAFKASTRM-LL` not being online, when actually the status is online. Then the global loading process will exit and fail the local job after timeout while waiting the global loading job to finish. | TBD | TBD | TBD  
When the memory usage approaches 100%, the system may stall because the process to elect a new GSE leader did not complete correctly. | TBD | This lockup can be cleared by restarting the GSE. | TBD  
If the CPU and memory utilization remain high for an extended period during a schema change on a cluster, a GSE follower could crash, if it is requested to insert data belonging to the new schema before it has finished handling the schema update. | TBD | TBD | TBD  
When available memory becomes very low in a cluster and there are a large number of vertex deletions to process, some remote servers might have difficulty receiving the metadata needed to be aware of all the deletions across the full cluster. The mismatched metadata will cause the GPE to go down. | TBD | TBD | TBD  
Subqueries with SET<VERTEX> parameters cannot be run in Distributed or Interpreted mode. | TBD | ([Limited Distributed model support](https://docs.tigergraph.com/gsql-ref/3.10/querying/operators-and-expressions#_subquery_limitations) is added in 3.9.2.) | TBD  
Upgrading a cluster with 10 or more nodes to v3.9.0 requires a patch. | 3.9 | Please contact TigerGraph Support if you have a cluster this large. Clusters with nine or fewer nodes do not require the patch. | 3.9.1  
Downsizing a cluster to have fewer nodes requires a patch. | 3.9.0 | Please contact TigerGraph Support. | TBD  
During peak system load, loading jobs may sometimes display an inaccurate loading status. | 3.9.0 | This issue can be remediated by continuing to run `SHOW LOADING STATUS` periodically to display the up-to-date status. | TBD  
When managing many loading jobs, pausing a data loading job may result in longer-than-usual response time. | TBD | TBD | TBD  
Schema change jobs may fail if the server is experiencing a heavy workload. | TBD | To remedy this, avoid applying schema changes during peak load times. | TBD  
User-defined Types (UDT) do not work if exceeding string size limit. | TBD | Avoid using UDT for variable length strings that cannot be limited by size. | TBD  
Unable to handle the tab character `\t` properly in AVRO or Parquet file loading. It will be loaded as `\\t`. | TBD | TBD | TBD  
If `System.Backup.Local.Enable` is set to `true`, this also enables a daily full backup at 12:00am UTC. | 3.9.0 | TBD | 3.9.1  
The data streaming connector does not handle NULL values; the connector may operate properly if a NULL value is submitted. | TBD | Users should replace NULL with an alternate value, such as empty string "" for STRING data, 0 for INT data, etc. (NULL is not a valid value for the TigerGraph graph data store.) | TBD  
Automatic message removal is an Alpha feature of the Kafka connector. It has several [known issues](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-cloud#_known_issues_with_loading). | TBD | TBD | TBD  
The `DATETIME` data type is not supported by the `PRINT … TO CSV` statement. | 3.9.0 | TBD | 3.9.1  
The LDAP keyword `memberOf` for declaring group hierarchy is case-sensitive. | 3.9 | Check the case of the keywords for `memberOf`. This has been fixed in versions 3.10.1 and above. | 3.10.1  
After performing a backup and restoring it, all vertex IDs (v_ids) may become "UNKNOWN." This occurs when the local schema is deleted before restoring the backup. This issue results in a mismatch between the Graph Processing Engine (GPE) and the Graph Schema Engine (GSE), which causes data inconsistency. | 3.10.1 |  To fix this issue, users can do one of the following:
  * Run the `gsql drop all` command before restoring the backup.
  * Alternatively, run the backup restore again.

| 3.10.2 and 4.1.0 and later.  
A GPE crash occurs when a `DELETE` operation is performed on multi-edge types in CDC without specifying a discriminator. This happens when no `filter` or `limit` is applied to constrain the operation, causing the Graph Processing Engine (GPE) to crash. | 3.10.0 | Delete multi-edge types one at a time to avoid causing a GPE crash. | 4.1.1  
### [](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_compatibility_issues)Compatibility Issues
Description | Version Introduced  
---|---  
Users could encounter file input/output policy violations when upgrading a TigerGraph version. See [Input policy backward compatibility.](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_backward_compatibility) | v3.10.0  
When a PRINT argument is an expression, the output uses the expression as the key (label) for that output value. To better support Antlr processing, PRINT now removes any spaces from that key. For example, `count(DISTINCT @@ids)` becomes `count(DISTINCT@@ids)`. | v3.9.3+  
Betweenness Centrality algorithm: `reverse_edge_type (STRING)` parameter changed to `reverse_edge_type_set (SET<STRING>)`, to be consistent with `edge_type_set` and similar algorithms. | v3.9.2+  
For vertices with string-type primary IDs, vertices whose ID is an empty string will now be rejected. | v3.9.2+  
The default mode for the Kafka Connector changed from EOF="false" to EOF="true". | v3.9.2+  
The default retention time for two monitoring services `Informant.RetentionPeriodDays` and `TS3.RetentionPeriodDays` has reduced from 30 to 7 days. | v3.9.2+  
The filter for `/informant/metrics/get/cpu-memory` now accepts a list of ServiceDescriptors instead of a single ServiceDescriptor. | v3.9.2+  
Some user-defined functions (UDFs) may no longer be accepted due to [increased security screening](https://docs.tigergraph.com/tigergraph-server/3.10/security/#_udf_file_scanning).
  * UDFs may no longer be called `to_string()`. This is now a built-in GSQL function.
  * UDF names may no longer use the `tg_` prefix. Any user-defined function that began with `tg_` must be renamed or removed in `ExprFunctions.hpp`.

| v3.9+  
### [](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_deprecations)Deprecations
Description | Deprecated | Removed  
---|---|---  
The use of plaintext tokens in [authentication](https://docs.tigergraph.com/tigergraph-server/3.10/API/authentication) is deprecated. Use [OIDC JWT Authentication](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/jwt-token) instead. | 3.10.0 | 4.1  
The command `gbar` is removed and is no longer available. However, if you are using a version of TigerGraph before 3.10.0 you can still use `gbar` to [create a backup with gbar](https://docs.tigergraph.com/tigergraph-server/3.10/backup-and-restore/gbar-legacy) of the primary cluster. See also [Backup and Restore with gbar](https://docs.tigergraph.com/tigergraph-server/3.10/backup-and-restore/gbar-legacy) on how to create a backup. | 3.7 | 3.10.0  
[Vertex-level Access Control (VLAC)](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/vlac) and [VLAC Methods](https://docs.tigergraph.com/gsql-ref/3.10/querying/func/vertex-methods) are now deprecated. | 3.10.0 | 4.0  
[Spark Connection via JDBC Driver](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/spark-connection-via-jdbc-driver) is now deprecated and will no longer be supported. | 3.10.0 | TBD  
`Build Graph Patterns` is deprecated and will not be updated or supported and instead we are focusing on [Insights](https://docs.tigergraph.com/insights/3.10/widgets/) as the tool of choice for building visual queries. | v3.9.3 | TBD  
Kubernetes classic mode (non-operator) is deprecated. | v3.9 | TBD  
The `WRITE_DATA` RBAC privilege is deprecated. | v3.7 | TBD  
## [](https://docs.tigergraph.com/tigergraph-server/3.10/release-notes/#_release_notes_for_previous_versions)Release notes for previous versions
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


