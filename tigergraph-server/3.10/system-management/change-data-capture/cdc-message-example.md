![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-message-example)[Next](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-message-example)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-message-example)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-message-example)
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
  * [System Management](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/management-with-gadmin)
  * [Change Data Capture (CDC) Overview](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-overview)
  * [CDC Message Examples](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-message-example)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/3.10/modules/system-management/pages/change-data-capture/cdc-message-example.adoc)
### Contents
  * [Message Format Fields](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-message-example#_message_format_fields)
  * [mid](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-message-example#_mid)
  * [Other Message Fields](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-message-example#_other_message_fields)
  * [Message Examples](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-message-example#_message_examples)
  * [CDC Message with Type: Vertex](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-message-example#_cdc_message_with_type_vertex)
  * [CDC Message with Type: Vertex-Type](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-message-example#_cdc_message_with_type_vertex_type)
  * [CDC Message with Type: Edge](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-message-example#_cdc_message_with_type_edge)


# CDC Message Examples
### Contents
  * [Message Format Fields](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-message-example#_message_format_fields)
  * [mid](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-message-example#_mid)
  * [Other Message Fields](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-message-example#_other_message_fields)
  * [Message Examples](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-message-example#_message_examples)
  * [CDC Message with Type: Vertex](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-message-example#_cdc_message_with_type_vertex)
  * [CDC Message with Type: Vertex-Type](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-message-example#_cdc_message_with_type_vertex_type)
  * [CDC Message with Type: Edge](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-message-example#_cdc_message_with_type_edge)


## [](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-message-example#_message_format_fields)Message Format Fields
### [](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-message-example#_mid)mid
`mid` is a message identifier field composed of concatenated elements, as exemplified by `2|1701548849757|33|2|1`. It is constructed by combining four or five elements, depending on its type, and each element is separated by `|`.
There are two types: **Non-transaction** and **Transaction** :
  * **Non-transaction** types have 4 elements: `partitionID | timestamp | tid | index`
  * **Transaction** types have 5 elements: `partitionID | timestamp | tid | split_index | index`


In the previous example, it signifies a **Transaction** with 5 elements: originating from partition `2|`, committed at epoch time `1701548849757|`, with transaction ID `33|`, split_index of `2|`, and lastly an index of `1|`. The current message is the second message in the third batch of the transaction.
Table 1. This table breaks down the “mid” field elements: “mid” Field Elements | Explain  
---|---  
`partitionID` | Source GPE partition of the CDC message. It starts from 1.  
`timestamp` | Same as the timestamp field in the CDC message.  
`tid` | A CDC message consistently corresponds to a delta message, both of which are part of a "delta batch" in the delta Kafka queue. The "tid" denotes the position or index of the delta batch to which the original delta message is mapped. This index starts from 1, and a transaction encompasses multiple delta batches. For CDC messages within a transaction, the "tid" corresponds to the “tid” of the last message, specifically the COMMIT message.  
`split_index` | This element is exclusive to transactions. In the context of a transaction, the split_index represents the position of the delta batch among all delta batches for the same transaction. It follows a 0-indexed format.  
`index` | The index of the delta message in its delta batch. It’s 0-indexed.  
### [](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-message-example#_other_message_fields)Other Message Fields
Table 2. Other message fields are outlined in the table below: Field | Value Type: “Possible Values”  
---|---  
`type` | String: “vertex” / ”vertex-type” / ”edge”  
`operator` | String: ”insert” / ”insert-only” / ”delete”  
`timestamp` | UINT64: “**Non-transaction** : birth epoch time.” / “**Transaction** : epoch time of transaction commit message.”  
`typename` | String: “type name of updated type”.  
`content` | See [Content Field Value Types and "Possible Values"](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-message-example#_content_field_value_types_and_possible_values) below.  
#### [](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-message-example#_content_field_value_types_and_possible_values)Content Field Value Types and "Possible Values"
  * **Key** is the affected attribute name.
  * **Value** is json object with **2** fields:
    1. “**op** ”: This defines how to apply the value to existing attribute value. It can be one of: `"Overwrite"`, `"Add"`, `"Max"`, `"Min"`, `"And"`, `"Or"`, `"IgnoreIfExisted"`, `"Minus"`, `"ReplaceOrAdd"`.
    2. “Value”: As in this example below:
```
`"content": {
"actors": {
"op": "Add",
"value": [
"i1",
"m2"
]
},
...
}`
```



## [](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-message-example#_message_examples)Message Examples
### [](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-message-example#_cdc_message_with_type_vertex)CDC Message with Type: Vertex
This CDC message example indicates insertion, modification, or deletion of a vertex entity:
```
{
"mid": "1|1701548849757|1|0",
"operator": "insert",
"timestamp": 1701548849757,
"type": "vertex",
"typename": "Company",
"vid": 99999999,
"uid": "comp1",
"content": {
  "cid": {
    "op": "Overwrite",
    "value": 2345
  },
  "startDate": {
    "op": "Overwrite",
    "value": "2001-01-01 08:00:00"
    }
  }
}
```

#### [](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-message-example#_fields_for_cdc_message_with_type_vertex)Fields for CDC Message with Type: Vertex
Field | Description  
---|---  
`vid` | Internal vertex id, eg: `1234567890`.  
`uid` | External vertex id, eg: `"abc123"`. This could be `primary_id/primary key/composite keys`. And it will not appear in the content.  
#### [](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-message-example#_possible_operators_for_cdc_message_with_type_vertex)Possible Operators for CDC Message with Type: Vertex
“operator” | Note  
---|---  
`insert` | Insert a new vertex, or modify some attribute values  
`insert-only` | Insert new vertex if not existing, otherwise ignore it. For now, this is only triggered in one case: when inserting an edge, the target vertex will be implicitly inserted with this “insert-only” operator.  
`delete` | Delete a vertex will implicitly delete all edges that use that vertex as source or target. TigerGraph CDC service will **NOT** produce CDC messages for such “implicit edge deletion”.  
### [](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-message-example#_cdc_message_with_type_vertex_type)CDC Message with Type: Vertex-Type
This CDC message example indicates operations on all existing entities of a specific **vertex-type** :
```
{
"mid": "1|1701548854014|2|0",
"operator": "delete",
"timestamp": 1701548854014,
"type": "vertex-type",
"typename": "Person",
"content": {}
}
```

#### [](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-message-example#_possible_operators_for_cdc_message_with_type_vertex_type)Possible operators for CDC Message with type vertex-type
Table 3. The "operator" can only be "deleted": “operator” | Note  
---|---  
`delete` | Delete will delete all vertices of a vertex type and will also implicitly delete all edges that use that vertex as source or target. TigerGraph CDC service will **NOT** produce CDC messages for such “implicit edge deletion”.  
### [](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-message-example#_cdc_message_with_type_edge)CDC Message with Type: Edge
This CDC message example indicate insertion, modification, or deletion of a edge entity:
```
{
"mid": "1|1701569966031|3|0",
"operator": "insert",
"timestamp": 1701569966031,
"type": "edge",
"typename": "Creates",
"hasreverseedge": true,
"discriminator": "c1:1",
"from": {
  "type": "Person",
  "vid": 12345678,
  "uid": "person2"
},
"to": {
  "type": "Company",
  "vid": 87654321,
  "uid": "comp2"
},
"content": {
  "attr_list_tuple": {
    "op": "Add",
    "value": [
      "i: 2, u: 0, f: 3, d: 3, dt: 1222819200, b: 0, s: m2"
      ]
    },
  "attr_map_tuple": {
    "op": "ReplaceOrAdd",
    "value": {
      "2011-10-20": "i: 2, u: 0, f: 3, d: 3, dt: 1222819200, b: 0, s: m2"
      }
    }
  }
}
```

#### [](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-message-example#_fields_for_cdc_message_with_type_edge)Fields for CDC Message with Type: Edge
Field | Optional? | Note  
---|---|---  
`from` | No | Json object with 3 fields: **type** : vertex type name of source vertex **vid** : internal vertex id of source vertex **uid** : external vertex id of source vertex. This could be `primary_id/primary key/composite` keys. For composite keys, the key is separated by a `,`.  
`to` | No | Same as `from` field, but for target vertex.  
`hasreverseedge` | Yes | Bool type. When the value is `true`, it means the updated edge type has also reverse edge types. If it’s `false` this field will be omitted.  
`discriminator` | Yes | String type. Only exists if the updated edge is multi-edge. It’s the discriminator string separated by a `:`.  
#### [](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-message-example#_possible_operators_for_cdc_message_with_type_edge)Possible Operators for CDC Message with Type: Edge
“operator” | Note  
---|---  
`insert` | Insert a new edge, or modified attribute values. If source vertex is missing when inserting edge, TigerGraph will implicitly insert source vertex with all default values on its attributes. For now, TigerGraph CDC Service will **NOT** produce CDC messages for such “implicit source vertex insertion”.  
`delete` | Deletion of an edge  
#### [](https://docs.tigergraph.com/tigergraph-server/3.10/system-management/change-data-capture/cdc-message-example#_extra_cdc_message_for_edge_update)Extra CDC message for Edge Update
Edge updates may include additional information in specific scenarios.
In such cases, TigerGraph CDC will generate an additional CDC message for the corresponding "extra" edge.
Case | Description  
---|---  
For directed edge without reverse edge type ("Simple Edge Type") | When a directed edge is inserted without a reverse edge type, TigerGraph automatically creates the source and/or target vertex if they do not exist. CDC messages are generated: - For the source vertex: Only if it is new and has `primary_id_as_attribute="true"`. - For the target vertex: Always if it is new.  
For undirected edge, and directed edge with reverse edge type ("Complex Edge Type") | For insertion/modification/deletion on an undirected edge, or directed edge with a reverse edge type, TigerGraph will update 2 edges simultaneously: the “origin” edge and the “extra” edge with switched source and target vertex. When Undirected Edge or Directed Edge is inserted With a Reverse Edge Type, TigerGraph automatically creates the source and/or target vertex if they don’t exist: - **CDC messages** are generated for both source and target vertices only if they are new and have `primary_id_as_attribute="true"`.  
**NOTE** :Starting from version 3.10.3, CDC produces the source vertex with "insert-only" for edge insertion in **Single-partition clusters** when the source/target vertex is new (doesn’t exist before) and uses `primary_id_as_attribute="true"`.
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


