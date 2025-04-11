![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe)[Next](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe)
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
  * [Load Data](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/)
  * [Load from Spark Dataframe](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/3.10/modules/data-loading/pages/load-from-spark-dataframe.adoc)
### Contents
  * [Compatibility](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_compatibility)
  * [Overview](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_overview)
  * [Setup](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_setup)
  * [Download the JARs](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_download_the_jars)
  * [Create a Loading Job](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_create_a_loading_job)
  * [Configure the Connector](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_configure_the_connector)
  * [Configure Logging](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_configure_logging)
  * [Use Case Examples](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_use_case_examples)
  * [Some Helpful tips](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_some_helpful_tips)
  * [Batch Write Mode](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_batch_write_mode)
  * [Streaming Mode with Spark Structured Streaming API](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_streaming_mode_with_spark_structured_streaming_api)
  * [Load Data from Delta Lake](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_load_data_from_delta_lake)
  * [Load Data from Iceberg](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_load_data_from_iceberg)
  * [Load Data from Hudi](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_load_data_from_hudi)
  * [Loading Statistics](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_loading_statistics)
  * [Row Level Statistics](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_row_level_statistics)
  * [Object Level Statistics](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_object_level_statistics)


# Load from Spark Dataframe
Table of Contents
  * [Compatibility](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_compatibility)
  * [Overview](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_overview)
  * [Setup](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_setup)
    * [Download the JARs](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_download_the_jars)
    * [Create a Loading Job](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_create_a_loading_job)
  * [Configure the Connector](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_configure_the_connector)
    * [Configure Logging](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_configure_logging)
  * [Use Case Examples](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_use_case_examples)
    * [Some Helpful tips](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_some_helpful_tips)
    * [Batch Write Mode](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_batch_write_mode)
    * [Streaming Mode with Spark Structured Streaming API](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_streaming_mode_with_spark_structured_streaming_api)
    * [Load Data from Delta Lake](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_load_data_from_delta_lake)
    * [Load Data from Iceberg](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_load_data_from_iceberg)
    * [Load Data from Hudi](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_load_data_from_hudi)
  * [Loading Statistics](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_loading_statistics)
    * [Row Level Statistics](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_row_level_statistics)
    * [Object Level Statistics](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_object_level_statistics)


The TigerGraph Spark Connector employs [Apache Spark](https://spark.apache.org) to read data from a Spark DataFrame (or Data Lake) and write to TigerGraph. This connector has multiple optimizations for high performance, scalability, and management.
## [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_compatibility)Compatibility
  * TigerGraph 3.6.0 or higher. Job level loading statistics are only available for v3.10+.
  * Spark 3.2 or higher with Scala 2.12 and Scala 2.13.
  * JAVA 8 or higher.


Users can leverage it to connect TigerGraph to the Spark ecosystem and load data from any Spark-compatible data sources, such as:
  * Distributed file system: HDFS, S3, GCS and ABS
  * Streaming source: Kafka
  * Data warehouse: [BigQuery](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/load-from-warehouse#_bigquery), [Snowflake](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/load-from-warehouse#_snowflake), [PostgreSql](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/load-from-warehouse#_postgresql), and Redshift
  * Open table format: [Delta Lake](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/load-from-spark-dataframe#_load_data_from_delta_lake), [Iceberg](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/load-from-spark-dataframe#_load_data_from_iceberg) and [Hudi](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/load-from-spark-dataframe#_load_data_from_hudi)


The legacy [Spark Connection Via JDBC Driver](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver) is deprecated. Please migrate to this new connector.  
---  
## [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_overview)Overview
The first step is to read data into a Spark dataframe. Then, using a TigerGraph loading job which maps data fields from the dataframe into graph elements, the connector pulls data from Spark into TigerGraph.
Spark dataframe example:
```
+--------------------+-------------+-------------+-----------+--------------------+------+
|    creationDate|      id|  locationIP|browserUsed|       content|length|
+--------------------+-------------+-------------+-----------+--------------------+------+
|2012-07-04T06:10:...|7696585588755| 46.23.82.182|  Firefox|         LOL|   3|
|2012-08-22T17:22:...|8246341402699| 27.62.125.4|   Chrome|       roflol|   6|
|2012-05-08T21:02:...|7146829775042| 61.1.50.205|   Chrome|       roflol|   6|
|2012-11-22T01:25:...|9345853030654|190.95.68.192|  Firefox|About Sergei Eise...|  79|
|2012-11-11T08:59:...|9345853030710|166.75.225.76|   Chrome|        good|   4|
+--------------------+-------------+-------------+-----------+--------------------+------+
```

The connector concatenates columns to delimited data:
```
  - loading.separator = "|"
  - loading.eol = "\n"
the processed data would be:
  2012-07-04T06:10:43.489+00:00|7696585588755|46.23.82.182|Firefox|LOL|3
  2012-08-22T17:22:20.315+00:00|8246341402699|27.62.125.4|Chrome|roflol|6
  2012-05-08T21:02:39.145+00:00|7146829775042|61.1.50.205|Chrome|roflol|6
  2012-11-22T01:25:39.670+00:00|9345853030654|190.95.68.192|Firefox|About Sergei Eisenstein, pioneering SAbout Steven Spielberg, makers in thAbout|79
  2012-11-11T08:59:21.311+00:00|9345853030710|166.75.225.76|Chrome|good|4
```

The processed data will be sent to TigerGraph batch by batch:
```
  - loading.job = "load_Comment"
  - loading.filename = "file_Comment"
```

To let TigerGraph parse the data chunk correctly, please make sure you are setting `loading.separator` and `loading.eol` to characters which do not appear in your data fields.
## [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_setup)Setup
### [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_download_the_jars)Download the JARs
This connector can be downloaded from the Maven central repository: [Maven Central](https://central.sonatype.com/artifact/com.tigergraph/tigergraph-spark-connector/overview). The connector is available in 3 release formats:
  * `tigergraph-spark-connector-<version>.jar`: The `JAR` file containing only the compiled classes of the connector, which does not include any dependencies.
  * `tigergraph-spark-connector-<version>-jar-with-dependencies.jar`: The `JAR` file that includes compiled classes, as well as all the dependencies.
  * `tigergraph-spark-connector-<version>.tar.gz`: The compressed `TAR` archive that includes `tigergraph-spark-connector-<version>.jar` and dependencies in separate `JAR` files.


To use the TigerGraph Spark connector in a Spark shell, use the `--jars` option:
```
spark-shell --jars tigergraph-spark-connector-<version>-jar-with-dependencies.jar
```

If you want to include the TigerGraph Spark Connector in your Spark installation, add the `JAR` with dependencies to Spark’s `jars` folder.  
---  
### [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_create_a_loading_job)Create a Loading Job
This loading job should map the dataframe’s columns to the desired graph element attributes.
Example of simple graph schema and loading job
```
gsql '
  CREATE VERTEX Comment (PRIMARY_ID id UINT, creationDate DATETIME, locationIP STRING, browserUsed STRING, content STRING, length UINT) WITH primary_id_as_attribute="TRUE", STATS="outdegree_by_edgetype"
  CREATE GRAPH demo_graph (*)
'
gsql -g demo_graph '
  CREATE LOADING JOB load_Comment FOR GRAPH test_graph {
    DEFINE FILENAME file_Comment;
    LOAD file_Comment
      TO VERTEX Comment VALUES ($1, $0, $2, $3, $4, $5) USING header="true", separator="|";
 }
'
```

## [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_configure_the_connector)Configure the Connector
If you are using Spark Connector 0.2.0+, the following configuration parameters are required: `version`, `log.level`,`log.path`.  
---  
Key | Default Value | Description | Group  
---|---|---|---  
`url` | (none) | The connection URL to TigerGraph cluster. It can be a list of URLs separated by comma for load balancing. Example: <http://192.168.1.1:14240>, <http://192.168.1.2:14240>, <http://192.168.1.3:14240> | General  
`graph` | (none) | The graph name.  
`username` | (none) | The GSQL username. | Authentication (You can choose any authentication method for data loading, but it’s recommended to give username/password pair, which can generate and refresh token automatically.)  
`password` | (none) | The GSQL password. | Authentication  
`secret` | (none) | The GSQL secret. | Authentication  
`token` | (none) | The Bearer token for RESTPP. | Authentication  
`loading.job` | (none) | The GSQL loading job name. | Loading Job  
`loading.filename` | (none) | The filename defined in the loading job. | Loading Job  
`loading.separator` | , | The column separator. | Loading Job  
`loading.eol` | \n | The line separator. | Loading Job  
`loading.batch.size.bytes` | 2097152 | The maximum batch size in bytes. | Loading Job  
`loading.timeout.ms` | (none) | The loading timeout per batch. | Loading Job  
`loading.max.percent.error` | (none) | The threshold of the error objects count. The loading job will be aborted when reaching the limit. Only available for TigerGraph version 3.10.0+. | Loading Job  
`loading.max.num.error` | (none) | The threshold of the error objects percentage. The loading job will be aborted when reaching the limit. Only available for TigerGraph version 3.10.0+. | Loading Job  
`loading.retry.interval.ms` | 5000 | The initial retry interval for transient server errors. | Loading Job  
`loading.max.retry.attempts` | 10 | The maximum retry attempts for transient server errors. | Loading Job  
`loading.max.retry.interval.ms` | 30000 | The maximum retry interval for transient server errors. | Loading Job  
`ssl.mode` | basic | The SSL mode: basic, verifyCA and verifyHostname. When setting it to verifyCA and verifyHostname, the truststore file should be given. | SSL  
`ssl.truststore` | (none) | Filename of the truststore which stores the SSL certificate chains. Add `--files /path/to/trust.jks` when submitting the Spark job. | SSL  
`ssl.truststore.type` | JKS | Truststore type, e.g., JKS, PKCS12 | SSL  
`ssl.truststore.password` | (none) | Password of the truststore. | SSL  
`io.connect.timeout.ms` | 30000 | Connect timeout in ms. | Transport Timeout  
`io.read.timeout.ms` | 60000 | Socket read timeout in ms. | Transport Timeout  
`io.retry.interval.ms` | 5000 | The initial retry interval for transport timeout. | Transport Timeout  
`io.max.retry.interval.ms` | 10000 | The maximum retry interval for transport timeout. | Transport Timeout  
`io.max.retry.attempts` | 5 | The maximum retry attempts for transport timeout. | Transport Timeout  
### [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_configure_logging)Configure Logging
It’s highly recommended to set log level to `info` to monitor the loading status. Configure the Spark log4j `conf/log4j2.properties` as follows, or other SLF4j bindings if any:
```
logger.tg.name = com.tigergraph
logger.tg.level = info
```

## [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_use_case_examples)Use Case Examples
### [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_some_helpful_tips)Some Helpful tips
  * **Authentication methods**


It is simpler to authenticate with the username/password or secret because this mode automatically maintains a valid token; otherwise, make sure the lifetime of your token is long enough for the loading job.
  * **High Availabilty**


To support fault tolerance and failover, please provide the URL of all nodes in the option `url`, e.g., "url" → "https://m1:14240,https://m2:14240,https://m3:14240,https://m4:14240",
### [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_batch_write_mode)Batch Write Mode
Create the variables:
```
val GRAPH = "demo_graph"
val URL = "http(s)://hostname:port[,http(s)://hostname:port]*"
val USERNAME = "tigergraph"
val PASSWORD = "tigergraph"
val LOADING_JOB = "load_Comment"
val FILENAME = "file_Comment"
val SEPARATOR = "|"
val VERSION = "3.10.1"
val LOG_LEVEL = "2"
val LOG_PATH = "/tmp/tigergraph-spark-connector.log"
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Read data from any Spark data sources into the dataframe:
```
val df = spark.read.json("path/to/person.json")
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Batch write the data into TigerGraph:
```
df.write
  .format("tigergraph")
  .mode("append")
  .options(
    Map(
      "graph" -> GRAPH,
      "url" -> URL,
      "username" -> USERNAME,
      "password" -> PASSWORD,
      "loading.job" -> LOADING_JOB,
      "loading.filename" -> FILENAME,
      "loading.separator" -> SEPARATOR,
      "version" -> VERSION,
      "log.level" -> LOG_LEVEL,
      "log.path" -> LOG_PATH
    )
  )
  .save()
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_streaming_mode_with_spark_structured_streaming_api)Streaming Mode with Spark Structured Streaming API
Create the variables:
```
val GRAPH = "Social_Net"
val URL = "http(s)://hostname:port"
val USERNAME = "tigergraph"
val PASSWORD = "tigergraph"
val LOADING_JOB = "load_person"
val FILENAME = "f1"
val SEPARATOR = "|"
val VERSION = "3.10.1"
val LOG_LEVEL = "2"
val LOG_PATH = "/tmp/tigergraph-spark-connector.log"
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Read data from any Spark streaming data sources into the dataframe:
```
val df = spark.readStream
  .format("kafka")
  .option("subscribe", "person")
  .load()
  .selectExpr("CAST(value AS STRING)").as[(String)]
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Streaming write data to TigerGraph:
```
df.writeStream
  .outputMode("append")
  .format("tigergraph")
  .option("checkpointLocation", "/path/to/checkpoint")
  .options(
    Map(
      "graph" -> GRAPH,
      "url" -> URL,
      "username" -> USERNAME,
      "password" -> PASSWORD,
      "loading.job" -> LOADING_JOB,
      "loading.filename" -> FILENAME,
      "loading.separator" -> SEPARATOR,
      "version" -> VERSION,
      "log.level" -> LOG_LEVEL,
      "log.path" -> LOG_PATH
    )
  )
  .start()
  .awaitTermination()
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_load_data_from_delta_lake)Load Data from Delta Lake
#### [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_batch_write)Batch Write
Load delta table to Spark dataframe:
```
val df = spark.read.format("delta")
  .load("/path/to/delta/table")
  .select(
    "creationDate",
    "id",
    "locationIP",
    "browserUsed",
    "content",
    "length"
  )
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Batch write the data into TigerGraph:
```
df.write
  .format("tigergraph")
  .mode("append")
  .options(
    Map(
      "graph" -> GRAPH,
      "url" -> URL,
      "username" -> USERNAME,
      "password" -> PASSWORD,
      "loading.job" -> LOADING_JOB,
      "loading.filename" -> FILENAME,
      "loading.separator" -> SEPARATOR,
      "version" -> VERSION,
      "log.level" -> LOG_LEVEL,
      "log.path" -> LOG_PATH
    )
  )
  .save()
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_streaming_writecdc)Streaming Write(CDC)
Streaming read from delta table:
```
val df = spark.readStream
  .format("delta")
  .option("readChangeFeed", "true")
  .load("/path/to/delta/table")
  .filter(
    $"_change_type" === "insert" || $"_change_type" === "update_postimage"
  )
  .select(
    "creationDate",
    "id",
    "locationIP",
    "browserUsed",
    "content",
    "length"
  )
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Streaming write data to TigerGraph:
```
df.writeStream
  .outputMode("append")
  .format("tigergraph")
  .option("checkpointLocation", "/path/to/checkpoint")
  .options(
    Map(
      "graph" -> GRAPH,
      "url" -> URL,
      "username" -> USERNAME,
      "password" -> PASSWORD,
      "loading.job" -> LOADING_JOB,
      "loading.filename" -> FILENAME,
      "loading.separator" -> SEPARATOR,
      "version" -> VERSION,
      "log.level" -> LOG_LEVEL,
      "log.path" -> LOG_PATH
    )
  )
  .start()
  .awaitTermination()
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

For more details on Delta Lake see [Welcome to the Delta Lake documentation — Delta Lake Documentation](https://docs.delta.io/latest/index.html).
### [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_load_data_from_iceberg)Load Data from Iceberg
#### [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_batch_write_2)Batch Write
Load Iceberg table to Spark dataframe:
```
val df = spark.table("catalog.db.table")
  .select(
    "creationDate",
    "id",
    "locationIP",
    "browserUsed",
    "content",
    "length"
  )
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Batch write the data into TigerGraph:
```
df.write
  .format("tigergraph")
  .mode("append")
  .options(
    Map(
      "graph" -> GRAPH,
      "url" -> URL,
      "username" -> USERNAME,
      "password" -> PASSWORD,
      "loading.job" -> LOADING_JOB,
      "loading.filename" -> FILENAME,
      "loading.separator" -> SEPARATOR,
      "version" -> VERSION,
      "log.level" -> LOG_LEVEL,
      "log.path" -> LOG_PATH
    )
  )
  .save()
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_streaming_writecdc_2)Streaming Write(CDC)
Streaming read from Iceberg table:
```
val df = spark.readStream
  .format("iceberg")
  .option("stream-from-timestamp", 0L)
  .load("catalog.db.table")
  .select(
    "creationDate",
    "id",
    "locationIP",
    "browserUsed",
    "content",
    "length"
  )
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Streaming write data to TigerGraph:
```
df.writeStream
  .outputMode("append")
  .format("tigergraph")
  .option("checkpointLocation", "/path/to/checkpoint")
  .options(
    Map(
      "graph" -> GRAPH,
      "url" -> URL,
      "username" -> USERNAME,
      "password" -> PASSWORD,
      "loading.job" -> LOADING_JOB,
      "loading.filename" -> FILENAME,
      "loading.separator" -> SEPARATOR,
      "version" -> VERSION,
      "log.level" -> LOG_LEVEL,
      "log.path" -> LOG_PATH
    )
  )
  .start()
  .awaitTermination()
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

For more details on Iceberg see [Iceberg Apache: Getting Started](https://iceberg.apache.org/docs/1.3.1/getting-started/)
### [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_load_data_from_hudi)Load Data from Hudi
#### [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_batch_write_3)Batch Write
Load Hudi table to Spark dataframe:
```
val df = spark.read
  .format("hudi")
  .load("/path/to/hudi/table")
  .select(
    "creationDate",
    "id",
    "locationIP",
    "browserUsed",
    "content",
    "length"
  )
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Batch write the data into TigerGraph
```
df.write
  .format("tigergraph")
  .mode("append")
  .options(
    Map(
      "graph" -> GRAPH,
      "url" -> URL,
      "username" -> USERNAME,
      "password" -> PASSWORD,
      "loading.job" -> LOADING_JOB,
      "loading.filename" -> FILENAME,
      "loading.separator" -> SEPARATOR,
      "version" -> VERSION,
      "log.level" -> LOG_LEVEL,
      "log.path" -> LOG_PATH
    )
  )
  .save()
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_streaming_writecdc_3)Streaming Write(CDC)
Streaming read from Hudi table:
```
val df = spark.readStream
  .format("hudi")
  .load("/path/to/hudi/table")
  .select(
    "creationDate",
    "id",
    "locationIP",
    "browserUsed",
    "content",
    "length"
  )
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Streaming write data to TigerGraph:
```
df.writeStream
  .outputMode("append")
  .format("tigergraph")
  .option("checkpointLocation", "/path/to/checkpoint")
  .options(
    Map(
      "graph" -> GRAPH,
      "url" -> URL,
      "username" -> USERNAME,
      "password" -> PASSWORD,
      "loading.job" -> LOADING_JOB,
      "loading.filename" -> FILENAME,
      "loading.separator" -> SEPARATOR,
      "version" -> VERSION,
      "log.level" -> LOG_LEVEL,
      "log.path" -> LOG_PATH
    )
  )
  .start()
  .awaitTermination()
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

For more details on Hudi see [Spark Guide | Apache Hudi](https://hudi.apache.org/docs/quick-start-guide/).
## [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_loading_statistics)Loading Statistics
When you configure the logging properly and set log level to `info`, the loading statistics will be logged.
There are 3 levels of stats:
  * **Batch level** : data will be loaded to TigerGraph in micro batches. The counts of malformed or invalid data of the batch will be logged.
  * **Partition level** : the data source can contain multiple partitions, and the log will show how many rows of the partition have been sent to TigerGraph.
  * **Job Level (available for TigerGraph 3.10+)** : The overall loading statistics of the Spark job aggregated by TigerGraph service KAFKASTRM-LL. This requires providing username and password to the query/gsqlserver endpoint.


Sample loading statistics:
```
24/01/22 16:15:45 INFO TigerGraphBatchWrite: Overall loading statistics: [ {
  "overall" : {
    "duration" : 15792,
    "size" : 48675207,
    "progress" : 0,
    "startTime" : 1706770863875,
    "averageSpeed" : 29546,
    "id" : "test_graph.load_Comment.spark.all.1706770859889",
    "endTime" : 1706770879667,
    "currentSpeed" : 29546,
    "statistics" : {
      "fileLevel" : {
        "validLine" : 466594,
        "notEnoughToken" : 0,
        "tokenExceedsBuffer" : 0,
        "rejectLine" : 0
      },
      "objectLevel" : {
        "vertex" : [ {
        "validObject" : 466593,
        "typeName" : "Comment",
        "invalidPrimaryId" : 1
        } ]
      }
    }
  },
  "workers" : [ {
    "tasks" : [ {
      "filename" : "file_Comment"
    } ]
  }, {
  "tasks" : [ {
    "filename" : "file_Comment"
    } ]
  } ]
} ]
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_row_level_statistics)Row Level Statistics
Row Level Statistics | Description  
---|---  
`validLine` | Number of valid raw data lines parsed.  
`rejectLine` | Number of raw data lines rejected by the reject line rule in the loading script.  
`notEnoughToken` | Number of raw data lines with fewer tokens than what was specified by the loading script.  
`badCharacter` | Number of raw data lines containing invalid characters.  
`tokenExceedsBuffer` | Number of raw data lines containing oversize tokens (see `gadmin config get GSQL.OutputTokenBufferSize`).  
`emptyLine` | Number of raw data lines that are empty.  
### [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-spark-dataframe#_object_level_statistics)Object Level Statistics
Object Level Statistics | Description  
---|---  
`validObject` | Number of data records created.  
`passedCondition` | Number of token lists which passed the WHERE predicate filter.  
`failedCondition` | Number of token lists which failed the WHERE predicate filter.  
`invalidPrimaryId` | Number of token lists where the id token is invalid.  
`noIdFound` | Number of token lists where the id token is empty.  
`invalidAttribute` | Number of token lists where at least one of the attribute tokens is invalid.  
`incorrectFixedBinaryLength` | Number of token lists where at least one of the tokens corresponding to a UDT type attribute is invalid.  
`invalidVertexType` | Number of token lists where at least one of the tokens corresponding to an edge type’s source/target vertex type is invalid.  
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


