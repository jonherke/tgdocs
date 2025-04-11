![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/ldap)[Next](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/ldap)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/ldap)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/ldap)
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
  * Authentication
  * [Lightweight Directory Access Protocol (LDAP)](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/ldap)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/3.10/modules/user-access/pages/ldap.adoc)
### Contents
  * [LDAP configuration parameters](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/ldap#_ldap_configuration_parameters)
  * [Configure TigerGraph to use LDAP](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/ldap#_configure_tigergraph_to_use_ldap)
  * [Mapping Users From LDAP to TigerGraph](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/ldap#_mapping_users_from_ldap_to_tigergraph)
  * [Configure Proxy Group](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/ldap#_configure_proxy_group)
  * [Group hierarchy](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/ldap#_group_hierarchy)
  * [Commands to manage proxy groups](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/ldap#_commands_to_manage_proxy_groups)
  * [Common errors](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/ldap#_common_errors)
  * [Parameter error](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/ldap#_parameter_error)
  * [Wrong username or password](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/ldap#_wrong_username_or_password)
  * [User does not match any proxy rule](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/ldap#_user_does_not_match_any_proxy_rule)


# Lightweight Directory Access Protocol (LDAP)
### Contents
  * [LDAP configuration parameters](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/ldap#_ldap_configuration_parameters)
  * [Configure TigerGraph to use LDAP](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/ldap#_configure_tigergraph_to_use_ldap)
  * [Mapping Users From LDAP to TigerGraph](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/ldap#_mapping_users_from_ldap_to_tigergraph)
  * [Configure Proxy Group](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/ldap#_configure_proxy_group)
  * [Group hierarchy](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/ldap#_group_hierarchy)
  * [Commands to manage proxy groups](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/ldap#_commands_to_manage_proxy_groups)
  * [Common errors](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/ldap#_common_errors)
  * [Parameter error](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/ldap#_parameter_error)
  * [Wrong username or password](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/ldap#_wrong_username_or_password)
  * [User does not match any proxy rule](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/ldap#_user_does_not_match_any_proxy_rule)


TigerGraph supports LDAP authentication by allowing a TigerGraph user to log in using an LDAP username and credentials. This page provides instructions on how to configure LDAP, map LDAP users to GSQL users, as well as specific instructions for integration with Active Directory (AD).
TigerGraph LDAP authentication supports any LDAP server that follows the LDAPv3 protocol. StartTLS/SSL connection is also supported.
Some LDAP servers are configured to require a client certificate upon connection. Client certificates are not supported in TigerGraph LDAP authentication.   
---  
## [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/ldap#_ldap_configuration_parameters)LDAP configuration parameters
TigerGraph uses the following parameters for LDAP configuration.
Name | Description | Example  
---|---|---  
Security.LDAP.AdminDN | Configure the DN of LDAP user who has read access to the base DN specified above. Empty if everyone has read access to LDAP data. Default value is empty; | `nan`  
Security.LDAP.AdminPassword | Configure the password of the admin DN specified above. Needed only when `Security.LDAP.AdminDN` is specified. Default value is empty. If the value provided is a path to a script, the parameter will be set to the output of the script. | `secret`  
Security.LDAP.BaseDN | Configure LDAP search base DN, the root node to start the LDAP search for user authentication. | `nan`  
Security.LDAP.Enable | Enable LDAP authentication: default false | `false`  
Security.LDAP.GroupFilter | list of group objects on LDAP server used to retrieve group hierarchy information, default value: (objectClass=group) | (objectClass=group)  
Security.LDAP.GroupHierarchyRefreshIntervalMin | Refresh time in minutes of ldap group hierarchy information. default 240 | 60  
Security.LDAP.Hostname | Configure LDAP server hostname: default localhost | `localhost`  
Security.LDAP.Port | Configure LDAP server port: default 389 | `389`  
Security.LDAP.SearchFilter | Configure LDAP search filter. Only objects that satisfy the conditions in the filter | `(objectClass=*)`  
Security.LDAP.Secure.Protocol | Enable SSL/StartTLS for LDAP connection [none/ssl/starttls]: default none | `none`  
Security.LDAP.Secure.TrustAll | Configure to trust all LDAP servers (unsafe): default false | `false`  
Security.LDAP.Secure.TruststoreFormat | Configure the truststore format [JKS/PKCS12]: default JKS | `JKS`  
Security.LDAP.Secure.TruststorePassword | Configure the truststore password: default `changeit`. | `changeit`  
Security.LDAP.Secure.TruststorePath | Configure the truststore absolute path for the certificates used in SSL: default empty. If the value provided is a path to a script, the parameter will be set to the output of the script. | `nan`  
Security.LDAP.UsernameAttribute | Configure the username attribute name in LDAP server: default uid | `uid`  
## [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/ldap#_configure_tigergraph_to_use_ldap)Configure TigerGraph to use LDAP
To enable and configure LDAP, run the following command:
Configure LDAP:
```
$ gadmin config entry ldap
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This prompts the user to enter the values for the LDAP configuration parameters.
  1. Set `Security.LDAP.Enable` to true. This configures TigerGraph to use LDAP for authentication.
  2. For `Security.LDAP.Hostname` and `Security.LDAP.Port`, provide the hostname and port of the LDAP server.
  3. For `Security.LDAP.BaseDN`, provide the base distinguished name (DN), which specifies root node to start the search for matching entries.
     * If you are not sure what value to use for this parameter, use the domain root portion of your DN. For example, if your DN is `CN=Joe,CN=Users,DC=example,DC=com`, use `DC=example,DC=com` for your base DN.
     * To find the DN of a user, you can open a command prompt and run the command `dsquery user -name <username>`, and replace `<username>` with the full name of the user.
  4. For `Security.LDAP.SearchFilter`, specify a search filter for objects you want to include in the search. Setting the search filter to `objectClass=user` only includes user objects. Setting the search filter to `objectClass=*` includes all objects.
  5. For `Security.LDAP.UsernameAttribute`, specify the attribute of the entities on the LDAP server to use as the database username. If you are using AD, set this parameter to `sAMAccountName`.
  6. For `Security.LDAP.AdminDN`, provide the DN of a user who has read access to the specified base DN.
  7. For `Security.LDAP.Secure.Protocol`, specify the encryption protocol for LDAP connection. You must specify the same protocol as your LDAP server.
     * Set the value to `none` if your LDAP server does not use any encryption protocol. This is the default configuration.
     * For SSL, set the value to `ssl`.
     * For StartTLS, set the value to `starttls`.
  8. If you are using either SSL or StartTLS, you need to provide a truststore, specify its format and provide its password.
     * For `Security.LDAP.Secure.TruststorePath`, provide the absolute path to the truststore used in SSL.
     * For `Security.LDAP.Secure.TruststoreFormat`, specify your truststore format. Supported formats include `JKS/PKCS12`.
     * For `Security.LDAP.Secure.TruststorePassword`, specify the password to your truststore.
  9. `Security.LDAP.Secure.TrustAll` should be set to false in any production environment as this overrides SSL/TLS settings and makes TigerGraph trust all LDAP servers. However, you can set this parameter to true in a development for testing purposes.


An example configuration is shown below.
```
Example of gadmin config entry ldap

$ gadmin config entry ldap
Security.LDAP.Enable [ false ]: Enable LDAP authentication: default false
New: true
Security.LDAP.Hostname [ localhost ]: Configure LDAP server hostname: default localhost
New: ldap.tigergraph.com
Security.LDAP.Port [ 389 ]: Configure LDAP server port: default 389
New: 389
Security.LDAP.BaseDN [ ]: Configure LDAP search base DN, the root node to start the LDAP search for user authentication: must specify
New: dc=tigergraph,dc=com
Security.LDAP.SearchFilter [ (objectClass=*) ]: Configure LDAP search base DN, the root node to start the LDAP search for user authentication.
New: (objectClass=*)
Security.LDAP.UsernameAttribute [ uid ]: Configure the username attribute name in LDAP server: default uid
New: uid
Security.LDAP.AdminDN [ ]: Configure the DN of LDAP user who has read access to the base DN specified above. Empty if everyone has read access to LDAP data: default empty
New: cn=Manager,dc=tigergraph,dc=com
Security.LDAP.AdminPassword [ secret ]: Configure the password of the admin DN specified above. Needed only when admin_dn is specified: default empty
New: secret
Security.LDAP.Secure.Protocol [ none ]: Enable SSL/StartTLS for LDAP connection [none/ssl/starttls]: default none
New: none
Security.LDAP.Secure.TruststorePath [ ]: Configure the truststore absolute path for the certificates used in SSL: default empty
New: /tmp/ca_server.pkcs12
Security.LDAP.Secure.TruststoreFormat [ JKS ]: Configure the truststore format [JKS/PKCS12]: default JKS
New: PKCS12
Security.LDAP.Secure.TruststorePassword [ changeit ]: Configure the truststore password: default changeit
New: test
Security.LDAP.Secure.TrustAll [ false ]: Configure to trust all LDAP servers (unsafe): default false
New: false
[  Info] Configuration has been changed. Please use 'gadmin config apply' to persist the changes.
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/ldap#_mapping_users_from_ldap_to_tigergraph)Mapping Users From LDAP to TigerGraph
This section explains how to configure a GSQL proxy group to allow LDAP user authentication.
Proxy groups specify privileges for users who log in through LDAP. If the user’s LDAP entry matches the proxy rule of an existing proxy group, a proxy user is created to which the user logs in.
For example, if there is an attribute called `role` in the LDAP directory, and `engineering` is one of the `role` attribute values, we can create a proxy group with the proxy rule `role=engineering`. All users with the `role` attribute whose value is `engineering` are matched to the proxy group and have the privileges granted to the proxy group.
### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/ldap#_configure_proxy_group)Configure Proxy Group
Run the `CREATE GROUP` command to create a proxy group with a proxy rule.
`CREATE GROUP` command
```
CREATE GROUP developers PROXY "role=engineering" // Any user in LDAP with role=engineer is proxied to the group 'developers'
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

After creating the proxy group, you can [grant roles](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/user-management) to the group to give the proxy group privileges.
### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/ldap#_group_hierarchy)Group hierarchy
The attribute which indicates that the current DN is a child of another DN is `memberOf`. Group hierarchy can be defined by stating a membership rule `memberOf=<LDAP group Distinguished Name>`.
An example of a Distinguished Name (DN) is `CN=group1,OU=AADDC Users,DC=tigergraph,DC=com`.
For example, assume `UserA` belongs to `Subgroup1`, and `Subgroup1` is a child of `Group1` on the LDAP server for TigerGraph. If there is a proxy group `ProxyGroup1` whose rule is `memberOf=CN=Group1,OU=AADDC Users,DC=tigergraph,DC=com`, `UserA` can be authorized as a member of `ProxyGroup1`.
GSQL will update the group hierarchy information from the LDAP according to the parameter `Security.LDAP.GroupHierarchyRefreshIntervalMin` whose default value is 240.
The following API is provided to refresh the preloaded group hierarchy information. Only the superuser has privilege to execute this endpoint.
<http://host:14240/gsqlserver/gsql/ldap/refresh-group>
### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/ldap#_commands_to_manage_proxy_groups)Commands to manage proxy groups
  * `SHOW GROUP` displays information about all groups.
  * `DROP GROUP <group_name>` deletes the definition of a group.


#### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/ldap#_proxy_users)Proxy users
A proxy user is a GSQL user created to correspond to an external LDAP user. When operating within GSQL, the external LDAP user’s roles and privileges are determined by the proxy user.
Nothing needs to be configured for a proxy user. As long as the proxy rule matches, the proxy user will be automatically created upon login.
A proxy user is very similar to a normal user. The minor differences are that a proxy user cannot change their password in GSQL and that a proxy user comes with default roles inherited from the proxy group that they belong to.
It is also possible to change the roles of a specific proxy user independently. When the roles and privileges of a proxy group changes, the roles and privileges of all the proxy users belonging to this proxy group change accordingly.
Proxy groups cannot be [exported](https://docs.tigergraph.com/tigergraph-server/3.10/backup-and-restore/database-import-export).However, performing a [backup and restore](https://docs.tigergraph.com/tigergraph-server/3.10/backup-and-restore/) will preserve all proxy groups present at the time of backup.  
---  
## [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/ldap#_common_errors)Common errors
### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/ldap#_parameter_error)Parameter error
"Parameter error" means some LDAP configurations are not set properly. Most often it is because admin_dn, admin_password, or the login username and password are not set correctly. Unfortunately, we cannot know exactly what field is wrong because the LDAP server side does not respond back with such detail
### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/ldap#_wrong_username_or_password)Wrong username or password
If you are logging into a cluster, all nodes must have the certification file in the same place. If one node has the file under `/tmp/certificate/`, then all other nodes must have it in the same place to avoid this error.
### [](https://docs.tigergraph.com/tigergraph-server/3.10/user-access/ldap#_user_does_not_match_any_proxy_rule)User does not match any proxy rule
This means the LDAP is working. However, TigerGraph cannot find a matching rule for the login user. Please create a proxy group for the user.
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


