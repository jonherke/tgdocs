![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide)[Next](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide)
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
  * [Load Data](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/)
  * [Load from External Kafka](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/load-from-kafka)
  * [Kafka SSL Security Guide](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/3.11/modules/data-loading/pages/kafka-ssl-security-guide.adoc)
### Contents
  * [Introduction](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_introduction)
  * [How to Enable SSL for Kafka](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_how_to_enable_ssl_for_kafka)
  * [X509 Certificate Formats Supported](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_x509_certificate_formats_supported)
  * [Only PKCS_12 Store Type is Supported](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_only_pkcs_12_store_type_is_supported)
  * [Kafka SSL Settings](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_kafka_ssl_settings)
  * [Client Settings Precedence](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_client_settings_precedence)
  * [Instructions](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_instructions)
  * [Prerequisites](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_prerequisites)
  * [Basic Instructions on Enabling SSL for Kafka](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_basic_instructions_on_enabling_ssl_for_kafka)
  * [Instructions on Enabling SSL for MirrorMaker2](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_instructions_on_enabling_ssl_for_mirrormaker2)
  * [Instructions on Enabling SSL for Cross-Region Replication](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_instructions_on_enabling_ssl_for_cross_region_replication)
  * [How to Renew Certificates](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_how_to_renew_certificates)


# Kafka SSL Security Guide
### Contents
  * [Introduction](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_introduction)
  * [How to Enable SSL for Kafka](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_how_to_enable_ssl_for_kafka)
  * [X509 Certificate Formats Supported](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_x509_certificate_formats_supported)
  * [Only PKCS_12 Store Type is Supported](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_only_pkcs_12_store_type_is_supported)
  * [Kafka SSL Settings](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_kafka_ssl_settings)
  * [Client Settings Precedence](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_client_settings_precedence)
  * [Instructions](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_instructions)
  * [Prerequisites](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_prerequisites)
  * [Basic Instructions on Enabling SSL for Kafka](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_basic_instructions_on_enabling_ssl_for_kafka)
  * [Instructions on Enabling SSL for MirrorMaker2](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_instructions_on_enabling_ssl_for_mirrormaker2)
  * [Instructions on Enabling SSL for Cross-Region Replication](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_instructions_on_enabling_ssl_for_cross_region_replication)
  * [How to Renew Certificates](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_how_to_renew_certificates)


## [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_introduction)Introduction
Connections to Kafka brokers can be secured by SSL. All the connections from Kafka clients to Kafka brokers can be secured, including these scenarios:
  * Loading data via `fileLoader` to Kafka before it is loaded into TigerGraph.
  * Loading data via KafkaLoader including streaming job to Kafka.
  * MirrorMaker2 (MM2) to load data from external Kafka to (internal) Kafka Brokers.
  * Cross-Region Replication (CRR), which is a special case of MM2.
  * KafkaStrm-LL connect to Kafka Brokers.
  * Connection from TigerGraph engine to Kafka broker is also secured.


## [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_how_to_enable_ssl_for_kafka)How to Enable SSL for Kafka
Firstly, users need to request or generate certificates before enabling SSL for Kafka. Refer to [self-signed certificates](https://docs.tigergraph.com/tigergraph-server/4.2/security/encrypting-connections#_option_2_create_a_self_signed_certificate) for instructions on how to generate self-signed certificate.
### [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_x509_certificate_formats_supported)X509 Certificate Formats Supported
The only format of certificate supported is `PEM`. Other formats like `DER` should be firstly converted to `PEM` to enable Kafka SSL.
See [Security](https://docs.tigergraph.com/tigergraph-server/4.2/security/) for more information on Security in TigerGraph.
### [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_only_pkcs_12_store_type_is_supported)Only `PKCS_12 Store` Type is Supported
X509 certificates are stored in key/trust stores.
Only store type `PKCS_12(P12)`:
```
Path to key store: <DataRoot>/configs/kafka/conf/credential/key_store.p12
Path to key store: <DataRoot>/configs/kafka/conf/credentials/trust_store.p12
```

JKS is current NOT yet supported.  
---  
## [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_kafka_ssl_settings)Kafka SSL Settings
A few configuration settings are introduced to enable and manager Kafka security (SSL):
Setting | Description | Default Value  
---|---|---  
Kafka.Security.ClientConf.ProtocolForAllClients |  If specified, all clients must use the specified protocol. Legal values include:
  * <empty-string>
  * ssl
  * plaintext

If it’s not specified, clients can choose a preferred protocol. | `<empty-string>`  
Kafka.Security.ClientConf.InterBrokerProtocol |  It is the protocol for inter-broker communication. The value can be:
  * <empty-string>
  * ssl
  * plaintext

It can be overridden by `Kafka.Security.ClientConf.ProtocolForAllClients`. | `<empty-string>`  
Kafka.Security.ClientConf.InfraProtocol |  It is the protocol for infra-kafka communication. The value can be:
  * <empty-string>
  * plaintext
  * ssl

It can be overridden by `Kafka.Security.ClientConf.ProtocolForAllClients`. | `<empty-string>`  
Kafka.Security.ClientConf.EngineProtocol |  It is the protocol for engine-kafka communication. The value can be:
  * <empty-string>
  * plaintext
  * ssl

It can be overridden by `Kafka.Security.ClientConf.ProtocolForAllClients`. | `<empty-string>`  
Kafka.Security.SSL.Enable | Enable Kafka TLS encryption. Can either be `true` or `false` | `false `  
Kafka.Security.SSL.Port | Kafka SSL listening port. | `30001`  
Kafka.Security.SSL.Certificate | Kafka broker certificate in PEM format. Usage: `@file/path/to/certificate` | `"@/home/graphsql/tmp/certificates/xyz.pem"`  
Kafka.Security.SSL.PrivateKey | Kafka broker private key in PEM format. Usage: "@file/path/to/certificate" | `"@/home/graphsql/tmp/certificates/xyz.pem"`  
Kafka.Security.SSL.Passphrase | Passphrase for SSL private key, trust store and key store. Should not be empty when SSL is enabled for Kafka | `<empty-string>`  
### [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_client_settings_precedence)Client Settings Precedence
  * SSL.Enable < ClientConf.InterBrokerProtocol < ClientConf.ProtocolForAllClients
  * SSL.Enable < ClientConf.InfraProtocol < ClientConf.ProtocolForAllClients
  * SSL.Enable < ClientConf.EngineProtocol < ClientConf.ProtocolForAllClients


## [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_instructions)Instructions
### [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_prerequisites)Prerequisites
As mentioned above, users need to generate certificates in PEM format.
Basically two certificates (or a certificate chain) need to be generated:
  * Public certificate(chain), which includes:
    * `Root-CA-Cert`
    * (Optional) `intermediate-CA-Cert`
    * `Leaf-Cert` (Machine Public Certificate)
  * Private Key of machine (leaf private key).


### [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_basic_instructions_on_enabling_ssl_for_kafka)Basic Instructions on Enabling SSL for Kafka
Please run the `gadmin` commands below to enable SSL for Kafka:
```
gadmin config set Kafka.Security.SSL.Passphrase <passphrase for key/trust store/private key>
gadmin config set Kafka.Security.SSL.Enable true
#NOTE: this chain includes: leaf public cert ← (optional) intermediate-CA-cert ← CA-Root cert
gadmin config set Kafka.Security.SSL.Certificate <@path_to_public_certificate_chain>
gadmin config set Kafka.Security.SSL.PrivateKey <@path_to_private_key>
gadmin config apply -y
gadmin restart all -y
```

### [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_instructions_on_enabling_ssl_for_mirrormaker2)Instructions on Enabling SSL for MirrorMaker2
Settings below need be added to connector configuration:
See [Basic Configurations](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#tigergraph-server:data-loading:data-streaming-connector/kafka.adoc#_basic_configurations) for more infomration on connection configurations.  
---  
  * `source.cluster.bootstrap.servers=<Source_Kafka_SSL_Broker_List>`
  * `target.cluster.bootstrap.servers=<Target_Kafka_SSL_Broker_List>`
  * `source.cluster.security.protocol=SSL`
  * `target.cluster.security.protocol=SSL`


A full connector configuration example, with schema registry:
```
connector.class=org.apache.kafka.connect.mirror.MirrorSourceConnector
source.cluster.alias=Primary
target.cluster.alias=Secondary
source.cluster.bootstrap.servers=195.0.0.1:30001
target.cluster.bootstrap.servers=127.0.0.1:30001
source.cluster.security.protocol=SSL
source->target.enabled=true
topics=${topic_avro_with_registry}
replication.factor=1
sync.topic.acls.enabled=false
checkpoints.topic.replication.factor=1
heartbeats.topic.replication.factor=1
offset-syncs.topic.replication.factor=1
offset.storage.replication.factor=1
status.storage.replication.factor=1
config.storage.replication.factor=1
emit.heartbeats.interval.seconds=5
secondary.scheduled.rebalance.max.delay.ms=35000
key.converter=org.apache.kafka.connect.converters.ByteArrayConverter
header.converter=org.apache.kafka.connect.converters.ByteArrayConverter
value.converter=com.tigergraph.kafka.connect.converters.TigerGraphAvroConverter
value.converter.schema.registry.url=http://127.0.0.1:8081
[connector_mm]
name=connector_name_with_schema_registry
tasks.max=10
```

### [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_instructions_on_enabling_ssl_for_cross_region_replication)Instructions on Enabling SSL for Cross-Region Replication
```
gadmin config set System.CrossRegionReplication.PrimaryKafkaIPs <Primary_Kafka_Broker_Comma_Separated_IPs>
#Default port number is: 30001
gadmin config set System.CrossRegionReplication.PrimaryKafkaPort <Primary_Kafka_Broker_SSL_Port>
gadmin init kafka -y
gadmin backup restore --dr -y
```

#### [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_optional_instructions)Optional Instructions
Users can use still enable/disable some or all the clients connected to Kafka brokers using these configuration settings:
```
Kafka.Security.ClientConf.InterBrokerProtocol
Kafka.Security.ClientConf.InfraProtocol
Kafka.Security.ClientConf.EngineProtocol
```

Precedence of these settings are described in the [Client Settings Precedence](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_client_settings_precedence) section.
## [](https://docs.tigergraph.com/tigergraph-server/3.11/data-loading/kafka-ssl-security-guide#_how_to_renew_certificates)How to Renew Certificates
Open sourced public tool KeyTool can be used to manage the key/trust store with store type `PCKS_12(P12)`.
Usually, `CA Root` certs have much longer expiry than `leaf certs`. They are not going to be expired in a few years or even 10+ years, but users can still renew it if they want to.
Here is the instructions users can follow to renew certificates:
  1. (Optional) Insert a new `CA Root public cert` using KeyTool to the truststore under the path mentioned above. This needs to be done on all the nodes before next steps;
    1. Insert a new private/public key pair of leaf (machine) certificates into the `keystore.p12`.
    2. (Optional) Users can still delete the old certificate from the `keystore.p12`.
    3. Restart services including:
      1. Kafka
      2. KafkaStrm-LL
      3. KafkaConnect
      4. GPE
      5. GSE


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


