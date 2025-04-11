![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/3.10/security/encrypting-connections)[Next](https://docs.tigergraph.com/tigergraph-server/3.10/security/encrypting-connections)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/3.10/security/encrypting-connections)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/3.10/security/encrypting-connections)
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
  * [Security](https://docs.tigergraph.com/tigergraph-server/3.10/security/)
  * [Encrypting Connections](https://docs.tigergraph.com/tigergraph-server/3.10/security/encrypting-connections)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/3.10/modules/security/pages/encrypting-connections.adoc)
### Contents
  * [Prerequisites](https://docs.tigergraph.com/tigergraph-server/3.10/security/encrypting-connections#_prerequisites)
  * [Nginx-Based](https://docs.tigergraph.com/tigergraph-server/3.10/security/encrypting-connections#_nginx_based)
  * [Step 1. Obtain an SSL Certificate](https://docs.tigergraph.com/tigergraph-server/3.10/security/encrypting-connections#_step_1_obtain_an_ssl_certificate)
  * [Option 1: Using a Certificate From A Trusted Agent](https://docs.tigergraph.com/tigergraph-server/3.10/security/encrypting-connections#_option_1_using_a_certificate_from_a_trusted_agent)
  * [Option 2: Create a Self-Signed Certificate](https://docs.tigergraph.com/tigergraph-server/3.10/security/encrypting-connections#_option_2_create_a_self_signed_certificate)
  * [Change the Certificate Permission](https://docs.tigergraph.com/tigergraph-server/3.10/security/encrypting-connections#_change_the_certificate_permission)
  * [Step 2: Configure SSL with gadmin](https://docs.tigergraph.com/tigergraph-server/3.10/security/encrypting-connections#_step_2_configure_ssl_with_gadmin)
  * [Testing Your SSL Connection](https://docs.tigergraph.com/tigergraph-server/3.10/security/encrypting-connections#_testing_your_ssl_connection)


# Encrypting Connections
### Contents
  * [Prerequisites](https://docs.tigergraph.com/tigergraph-server/3.10/security/encrypting-connections#_prerequisites)
  * [Nginx-Based](https://docs.tigergraph.com/tigergraph-server/3.10/security/encrypting-connections#_nginx_based)
  * [Step 1. Obtain an SSL Certificate](https://docs.tigergraph.com/tigergraph-server/3.10/security/encrypting-connections#_step_1_obtain_an_ssl_certificate)
  * [Option 1: Using a Certificate From A Trusted Agent](https://docs.tigergraph.com/tigergraph-server/3.10/security/encrypting-connections#_option_1_using_a_certificate_from_a_trusted_agent)
  * [Option 2: Create a Self-Signed Certificate](https://docs.tigergraph.com/tigergraph-server/3.10/security/encrypting-connections#_option_2_create_a_self_signed_certificate)
  * [Change the Certificate Permission](https://docs.tigergraph.com/tigergraph-server/3.10/security/encrypting-connections#_change_the_certificate_permission)
  * [Step 2: Configure SSL with gadmin](https://docs.tigergraph.com/tigergraph-server/3.10/security/encrypting-connections#_step_2_configure_ssl_with_gadmin)
  * [Testing Your SSL Connection](https://docs.tigergraph.com/tigergraph-server/3.10/security/encrypting-connections#_testing_your_ssl_connection)


TigerGraph supports secure data-in-flight communication, using SSL/TLS encryption protocol. This applies to any outward-facing channel, including GSQL clients, RESTPP endpoints, and the GraphStudio web interface. When SSL/TLS is enabled, HTTPS takes the place of HTTP for RESTPP and GraphStudio connections.
## [](https://docs.tigergraph.com/tigergraph-server/3.10/security/encrypting-connections#_prerequisites)Prerequisites
You should have basic knowledge about how SSL works:
  1. What the SSL certificate and key are used for
  2. That an SSL certificate is bound to a domain
  3. How an SSL certificate chain works


A good primer on SSL is available at Apache’s [SSL/TLS Strong Encryption: An Introduction](https://httpd.apache.org/docs/2.4/ssl/ssl_intro.html)
## [](https://docs.tigergraph.com/tigergraph-server/3.10/security/encrypting-connections#_nginx_based)Nginx-Based
TigerGraph uses the Nginx web server, so SSL configuration makes use of some built-in support in Nginx.
<http://nginx.org/en/docs/http/configuring_https_servers.html>
## [](https://docs.tigergraph.com/tigergraph-server/3.10/security/encrypting-connections#_step_1_obtain_an_ssl_certificate)Step 1. Obtain an SSL Certificate
The two main options for obtaining an SSL Certificate are to generate your own self-signed certificate or to purchase a certificate from a trusted Certificate Authority. Regardless of which method you choose, your certificate should be chained to a trusted root certificate embedded in your browser. The options and details for producing a trusted SSL certificate are beyond the scope of this document. The focus of this document is how to configure your TigerGraph system to use the certificate to enable SSL.
### [](https://docs.tigergraph.com/tigergraph-server/3.10/security/encrypting-connections#_option_1_using_a_certificate_from_a_trusted_agent)Option 1: Using a Certificate From A Trusted Agent
First, obtain an SSL certificate from a trusted agent of your choice. Certificate vendors will provide clear instructions for ordering a certificate and then for installing it on your system.
Then you can configure the certificate with `gadmin config entry ssl`
### [](https://docs.tigergraph.com/tigergraph-server/3.10/security/encrypting-connections#_option_2_create_a_self_signed_certificate)Option 2: Create a Self-Signed Certificate
There are multiple ways to create a self-signed certificate. One example is shown below.
For simplicity, the method below will use the root certificate directly as the HTTPS server certificate. This method is satisfactory for testing but should not be used for a production system.  
---  
In the example below, the Common Name value should be your server hostname, since HTTPS certificates are bound to domain names.  
---  
Self-Signed Certificate generation example using openssl
```
$ openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout ~/nginx-selfsigned.key -out ~/nginx-selfsigned.crt
Generating a 2048 bit RSA private key
.................................................................................................................................+++
........+++
writing new private key to '/home/tigergraph/nginx-selfsigned.key'
-----
You are about to be asked to enter information that will be incorporated
into your certificate request.
What you are about to enter is what is called a Distinguished Name or a DN.
There are quite a few fields but you can leave some blank
For some fields there will be a default value,
If you enter '.', the field will be left blank.
-----
Country Name (2 letter code) [AU]:US
State or Province Name (full name) [Some-State]:California
Locality Name (eg, city) []:Redwood City
Organization Name (eg, company) [Internet Widgits Pty Ltd]:TigerGraph
Organizational Unit Name (eg, section) []:GLE
Common Name (e.g. server FQDN or YOUR name) []: my.ip.addr.num
Email Address []:engineer@tigergraph.com
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.10/security/encrypting-connections#_change_the_certificate_permission)Change the Certificate Permission
For security reasons, the certificates can only be used with permission 600 or less.
```
$ chmod 600 ~/nginx-selfsigned.*
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/3.10/security/encrypting-connections#_step_2_configure_ssl_with_gadmin)Step 2: Configure SSL with `gadmin`
With the self-signed certificate successfully generated, you can configure it with `gadmin`, so that all the HTTP traffic will be protected with SSL.
TigerGraph’s SSL only accepts PEM-encoded certificates. If you have a certificate encoded in other formats (e.g. DER), you need to [convert it to a PEM-encoded certificate](https://www.sslshopper.com/ssl-converter.html) first.  
---  
```
$ gadmin config entry ssl
​Nginx.SSL.Enable [ false ]: Enable SSL connection for all HTTP requests
New: true
Nginx.SSL.Key [ <masked> ]: Private key for SSL
New: @privateKey_file_path
Nginx.SSL.Cert [ <masked> ]: Public certificate for SSL
New: @ssl_cert_path

# This config (Nginx.ProxySSLVerify) was removed in v3.1.1
Nginx.ProxySSLVerify [ false ]: Enable verification of the proxied HTTPS server certificate. Recommend to turn on.
New: true
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

After saving the settings, apply the configuration settings.
```
gadmin config apply -y
[ Info] Successfully applied configuration change. Please restart services to make it effective immediately.
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Then restart the following services: `gsql`, `nginx`, `ts3`, and `gui`.
```
$ gadmin restart gsql nginx gui ts3 -y
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/3.10/security/encrypting-connections#_testing_your_ssl_connection)Testing Your SSL Connection
Now you may test the connection.
A direct curl request to the server will fail due to certificate verification failure:
```
$ curl https://localhost:14240
curl: (60) server certificate verification failed. CAfile: /etc/ssl/certs/ca-certificates.crt CRLfile: none
More details here: http://curl.haxx.se/docs/sslcerts.html
curl performs SSL certificate verification by default, using a "bundle"
of Certificate Authority (CA) public keys (CA certs). If the default
bundle file isn't adequate, you can specify an alternate file
using the --cacert option.
If this HTTPS server uses a certificate signed by a CA represented in
the bundle, the certificate verification probably failed due to a
problem with the certificate (it might be expired, or the name might
not match the domain name in the URL).
If you'd like to turn off curl's verification of the certificate, use
the -k (or --insecure) option.
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

In v1.2, the default TCP/IP port for Nginx has changed from 44240 to 14240, to avoid possible port conflicts with Zookeeper.  
---  
You may use the -k option to turn off the verification, but it is unsafe and not recommended.
To successfully make requests with curl, you will need to specify the certificate by using the `--cacert` parameter:
```
$ curl --cacert /home/tigergraph/nginx-selfsigned.crt https://localhost:14240
<!doctype html><html lang="en"><head><meta charset="utf-8"><title>GraphStudio</title><base href="/"><meta name="viewport" content="width=device-width,initial-scale=1"><link rel="icon" type="image/x-icon" href="favicon.ico"><link href="styles.d67299ba9f5d73aecbe2.bundle.css" rel="stylesheet"/></head><body class="mat-typography"><app-root></app-root><script type="text/javascript" src="inline.4aae6a8088c30a61d5b0.bundle.js"></script><script type="text/javascript" src="polyfills.c9b879328f3396b2bbe8.bundle.js"></script><script type="text/javascript" src="vendor.5392e4ea4f904cd1658c.bundle.js"></script><script type="text/javascript" src="main.a39087227fcdf478cd2a.bundle.js"></script></body></html>
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


