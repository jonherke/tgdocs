![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka)[Next](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka)
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
  * [Load from External Kafka](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/3.10/modules/data-loading/pages/load-from-kafka.adoc)
### Contents
  * [Example Schema](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_example_schema)
  * [Create Data Source Object](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_create_data_source_object)
  * [Configure the Kafka source](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_configure_the_kafka_source)
  * [Create a loading job](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_create_a_loading_job)
  * [Example loading job from external Kafka](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_example_loading_job_from_external_kafka)
  * [Define filenames](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_define_filenames)
  * [Specify the data mapping](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_specify_the_data_mapping)
  * [Avro Data Validation](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_avro_data_validation)
  * [Run the loading job](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_run_the_loading_job)
  * [Manage and monitor your loading job](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_manage_and_monitor_your_loading_job)
  * [Manage loading job concurrency](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_manage_loading_job_concurrency)
  * [Kafka Loader Auto-Restart](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_kafka_loader_auto_restart)
  * [Known Issues with Loading](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_known_issues_with_loading)


# Load from External Kafka
Table of Contents
  * [Example Schema](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_example_schema)
  * [Create Data Source Object](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_create_data_source_object)
    * [String Literals](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_string_literals)
    * [Configure the Kafka source](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_configure_the_kafka_source)
      * [Configuration Settings](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_configuration_settings)
        * [Component Prefix](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_component_prefix)
        * [Security Protocols](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_security_protocols)
      * [Supported Configuration Examples](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_supported_configuration_examples)
        * [PLAINTEXT](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_plaintext)
        * [SSL](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_ssl)
        * [SASL_PLAINTEXT](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_sasl_plaintext)
        * [SASL_SSL](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_sasl_ssl)
        * [Third Party SASL Mechanism](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_third_party_sasl_mechanism)
      * [Schema Registry Service](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_schema_registry_service)
  * [Create a loading job](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_create_a_loading_job)
    * [Example loading job from external Kafka](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_example_loading_job_from_external_kafka)
    * [Define filenames](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_define_filenames)
      * [Kafka file descriptors](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_kafka_file_descriptors)
      * [Filename parameters](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_filename_parameters)
    * [Specify the data mapping](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_specify_the_data_mapping)
    * [Avro Data Validation](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_avro_data_validation)
  * [Run the loading job](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_run_the_loading_job)
  * [Manage and monitor your loading job](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_manage_and_monitor_your_loading_job)
  * [Manage loading job concurrency](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_manage_loading_job_concurrency)
  * [Kafka Loader Auto-Restart](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_kafka_loader_auto_restart)
  * [Known Issues with Loading](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_known_issues_with_loading)


This method is for only for v3.9.3 and higher versions. For earlier versions, please refer to [Stream from an External Kafka Cluster (Deprecated)](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/data-streaming-connector/kafka).  
---  
After you have [defined a graph schema](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/defining-a-graph-schema), you can create a loading job, specify your data sources, and run the job to load data.
The steps for loading from local files, cloud storage, or any other supported sources are similar. We will call out whether a particular step is common for all loading or specific to a data source or loading mode.
## [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_example_schema)Example Schema
Example schema taken from LDBC_SNB
```
//Vertex Types:
CREATE VERTEX Person(PRIMARY_ID id UINT, firstName STRING, lastName STRING,
 gender STRING, birthday DATETIME, creationDate DATETIME, locationIP STRING,
 browserUsed STRING, speaks SET<STRING>, email SET<STRING>)
 WITH STATS="OUTDEGREE_BY_EDGETYPE", PRIMARY_ID_AS_ATTRIBUTE="true"
CREATE VERTEX Comment(PRIMARY_ID id UINT, creationDate DATETIME,
 locationIP STRING, browserUsed STRING, content STRING, length UINT)
 WITH STATS="OUTDEGREE_BY_EDGETYPE", PRIMARY_ID_AS_ATTRIBUTE="true"
//Edge Types:
CREATE DIRECTED EDGE HAS_CREATOR(FROM Comment, TO Person)
 WITH REVERSE_EDGE="HAS_CREATOR_REVERSE"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_create_data_source_object)Create Data Source Object
A data source object provides a standard interface for all supported data source types, so that loading jobs can be written without regard for the data source.
When you create the object, you specify its details (type, access credentials, etc.) in the form of a JSON object. The JSON object can either be read in from a file or provided inline.
Inline mode is required when creating data sources for TigerGraph Cloud instances.  
---  
In the following example, we create a data source named `s1`, and read its configuration information from a file called `ds_config.json`.
```
USE GRAPH ldbc_snb
CREATE DATA_SOURCE s1 = "ds_config.json" FOR GRAPH ldbc_snb
php![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Older versions of TigerGraph required a keyword after `DATA_SOURCE` such as `STREAM` or `KAFKA`.  
---  
Inline JSON data format when creating a data source
```
CREATE DATA_SOURCE s1 = "{
type: <type>,
key: <value>
}" FOR GRAPH ldbc_snb
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_string_literals)String Literals
String literals can be represented according to the following options:
  * Enclosed with double quote `"`.
  * Enclosed with triple double quotes `"""`.
  * Enclosed with triple single quotes `'''`.


In the case of JSON that does not contain a colon `:` or a comma `,` the double quotes `"` can be omitted.
Alternate quote syntax for inline JSON data
```
CREATE DATA_SOURCE s1 = """{
"type": "<type>",
"key": "<value>"
}""" FOR GRAPH ldbc_snb
php![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Either a period `.` or `_` can be used for separation in the specified key name. Example: `first.second` or `first_second`.
### [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_configure_the_kafka_source)Configure the Kafka source
The TigerGraph connector to external Kafka sources makes use of [Apache Kafka Mirrormaker](https://cwiki.apache.org/confluence/pages/viewpage.action?pageId=27846330).
In addition, users can utilize external sources to provide configurations for Kafka connectors. These sources include files, Vault, and environment variables. See [Externalizing Kafka Configurations](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/externalizing-kafka-configs).  
---  
To configure the data source object, the minimum requirement is the address of the external source Kafka cluster:
Data source configuration for external Kafka
```
{
 "type": "mirrormaker",
 "source.cluster.bootstrap.servers": "<broker_addrs>"
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_configuration_settings)Configuration Settings
Field | Description  
---|---  
`<prefix>.security.protocol` | Protocol used to communicate with brokers. Valid values are: `PLAINTEXT`, `SSL, `SASL_PLAINTEXT`, `SASL_SSL`. The default is `PLAINTEXT`.  
`<prefix>.sasl.mechanism` | SASL mechanism used for client connections. This may be any mechanism for which a security provider is available. GSSAPI is the default mechanism. Third party providers require configuring `<prefix>.sasl.kerberos.service.name` and `<prefix>.sasl.client.callback.handler.class` as well as placing the third party jar under `$(gadmin config get System.Approot)/kafka/libs/`.  
`<prefix>.sasl.kerberos.service.name` | The Kerberos principal name used by your Kafka brokers. This could be defined in either JAAS configuration or Kafka’s configuration.  
`<prefix>.sasl.jaas.config` | JAAS login context parameters for SASL connections in the format used by JAAS configuration files. See [JAAS Login Configuration File](https://docs.oracle.com/javase/8/docs/technotes/guides/security/jgss/tutorials/LoginConfigFile.html) for details.  
`<prefix>.sasl.client.callback.handler.class` | Name of java handler class required for third party `<prefix>.sasl.mechanism` which must be placed under `$(gadmin config get System.Approot)/kafka/libs/`.  
`<prefix>.ssl.endpoint.identification.algorithm` | The endpoint identification algorithm used to validate server hostname in the server certificate. Default is `https`. If the value is set to an empty string, this will disable server host name verification.  
`<prefix>.ssl.keystore.location` | The location of the key store file.  
`<prefix>.ssl.keystore.password` | The password of the key store file.  
`<prefix>.ssl.key.password` | The password of the private key in the key store file or the PEM key specified in `ssl.keystore.key`.  
`<prefix>.ssl.truststore.location` | The location of the trust store file.  
`<prefix>.ssl.truststore.password` | The password for the trust store file.  
##### [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_component_prefix)Component Prefix
Replace the `<prefix>` with the appropriate identifier:
  * `[admin | producer | consumer]`
  * `[source | target].cluster`
  * `[source | target].cluster.[admin | producer | consumer]`


##### [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_security_protocols)Security Protocols
If the source cluster is configured for SSL or SASL protocols, you need to provide the following SSL/SASL credentials in order to communicate with the source cluster.
  * If the source cluster uses SASL, you need to upload the keytab of each Kerberos principal to every node of your TigerGraph cluster at the same absolute path.
  * If the source cluster uses SSL, see our documentation [Kafka SSL Security Guide](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/kafka-ssl-security-guide)
  * If the source cluster uses SASL **and** SSL, you need to upload the keytab of each Kerberos principal, as well as the key store and truststore to every node of your TigerGraph cluster. Each file must be at the same absolute path on all nodes.


The following configurations are required for admin, producer and consumer. Kafka allows SSL settings overriding, respecting security settings with the following precedence:
  * `generic.ssl.setting` < `source/target.cluster.ssl.setting` < `admin/producer/consumer.ssl.setting`.


If both source and target clusters are sharing the same SSL settings, user can set generic settings for both source/target clusters and all the rols(admin/producer/consumer).
For example, user can set `ssl.keystore.location="/path/to/key/store"` instead of:
  * `source.cluster.ssl.keystore.location="/path/to/key/store"`
  * `admin.ssl.keystore.location="/path/to/key/store"`
  * `source.cluster.admin.ssl.keystore.location="/path/to/key/store"`.


If source and target clusters have different SSL settings, it is possible to set cluster wide SSL configs.
For example, user can set: `target.cluster.ssl.truststore.password="/password/for/trust/store"` instead of:
  * `target.cluster.producer.ssl.trust.password="/password/for/trust/store"`.


Note: SSL is now well supported by TigerGraph, we recommend users to set up regular SSL rather than SASL + PlainText/SSL.
#### [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_supported_configuration_examples)Supported Configuration Examples
##### [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_plaintext)PLAINTEXT
```
{
 "type": "mirrormaker",
 "source.cluster.bootstrap.servers": "<KAFKAURL>:<PORT>"
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

##### [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_ssl)SSL
Need to configure:
  * `<prefix>.security.protocol`
  * `<prefix>.ssl.<field>`


```
{
 "type": "mirrormaker",
 "source.cluster.bootstrap.servers": "<KAFKAURL>:<PORT>",
 "consumer.security.protocol": "SSL",
 "consumer.ssl.endpoint.identification.algorithm": "none",
 "consumer.ssl.keystore.location": "/path/to/client.keystore.jks",
 "consumer.ssl.keystore.password": "******",
 "consumer.ssl.key.password": "******",
 "consumer.ssl.truststore.location": "/path/to/client.truststore.jks",
 "consumer.ssl.truststore.password": "******",
 "source.admin.security.protocol": "SSL",
 "source.admin.ssl.endpoint.identification.algorithm": "none",
 "source.admin.ssl.keystore.location": "/path/to/client.keystore.jks",
 "source.admin.ssl.keystore.password": "******",
 "source.admin.ssl.key.password": "******",
 "source.admin.ssl.truststore.location": "/path/to/client.truststore.jks",
 "source.admin.ssl.truststore.password": "******",
 "producer.security.protocol": "SSL",
 "producer.ssl.endpoint.identification.algorithm": "none",
 "producer.ssl.keystore.location": "/path/to/client.keystore.jks",
 "producer.ssl.keystore.password": "******",
 "producer.ssl.key.password": "******",
 "producer.ssl.truststore.location": "/path/to/client.truststore.jks",
 "producer.ssl.truststore.password": "******"
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

##### [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_sasl_plaintext)SASL_PLAINTEXT
Need to configure:
  * `<prefix>.security.protocol`
  * `<prefix>.sasl.<field>`


```
{
 "type": "mirrormaker",
 "source.cluster.bootstrap.servers": "<KAFKAURL>:<PORT>",
 "consumer.security.protocol": "SASL_PLAINTEXT",
 "consumer.sasl.mechanism": "<GSSAPI | PLAIN | etc>",
 "consumer.sasl.jaas.config": "<jaas_conf_content>",
 "source.admin.security.protocol": "SASL_PLAINTEXT",
 "source.admin.sasl.mechanism": "<GSSAPI | PLAIN | etc>",
 "source.admin.sasl.jaas.config": "<jaas_conf_content>",
 "producer.security.protocol": "SASL_PLAINTEXT",
 "producer.sasl.mechanism": "<GSSAPI | PLAIN | etc>",
 "producer.sasl.jaas.config": "<jaas_conf_content>",
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

##### [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_sasl_ssl)SASL_SSL
Need to configure:
  * `<prefix>.security.protocol`
  * `<prefix>.sasl.<field>`
  * `<prefix>.ssl.<field>`


```
{
 "type": "mirrormaker",
 "source.cluster.bootstrap.servers": "<KAFKAURL>:<PORT>",
 "consumer.security.protocol": "SASL_SSL",
 "consumer.sasl.mechanism": "<GSSAPI | PLAIN | etc>",
 "consumer.sasl.jaas.config": "<jaas_conf_content>",
 "consumer.ssl.endpoint.identification.algorithm": "none",
 "consumer.ssl.keystore.location": "/path/to/client.keystore.jks",
 "consumer.ssl.keystore.password": "******",
 "consumer.ssl.key.password": "******",
 "consumer.ssl.truststore.location": "/path/to/client.truststore.jks",
 "consumer.ssl.truststore.password": "******",
 "source.admin.security.protocol": "SASL_PLAINTEXT",
 "source.admin.sasl.mechanism": "<GSSAPI | PLAIN | etc>",
 "source.admin.sasl.jaas.config": "<jaas_conf_content>",
 "source.admin.ssl.endpoint.identification.algorithm": "none",
 "source.admin.ssl.keystore.location": "/path/to/client.keystore.jks",
 "source.admin.ssl.keystore.password": "******",
 "source.admin.ssl.key.password": "******",
 "source.admin.ssl.truststore.location": "/path/to/client.truststore.jks",
 "source.admin.ssl.truststore.password": "******",
 "producer.security.protocol": "SASL_PLAINTEXT",
 "producer.sasl.mechanism": "<GSSAPI | PLAIN | etc>",
 "producer.sasl.jaas.config": "<jaas_conf_content>",
 "producer.ssl.endpoint.identification.algorithm": "none",
 "producer.ssl.keystore.location": "/path/to/client.keystore.jks",
 "producer.ssl.keystore.password": "******",
 "producer.ssl.key.password": "******",
 "producer.ssl.truststore.location": "/path/to/client.truststore.jks",
 "producer.ssl.truststore.password": "******"
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

##### [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_third_party_sasl_mechanism)Third Party SASL Mechanism
For both `SASL` and `SASL_SSL` when a third party mechanism it is necessary to:
  * Include the `<prefix>.sasl.jaas.config` in addition to the `<prefix>.sasl.client.callback.handler.class` in the configuration
  * Place the third party jar under `$(gadmin config get System.Approot)/kafka/libs/`


Example SASL Configuration with third party mechanism
```
{
 "type": "mirrormaker",
 "source.cluster.bootstrap.servers": "<KAFKAURL>:<PORT>",
 "consumer.security.protocol": "SASL_PLAINTEXT",
 "consumer.sasl.mechanism": "<AWS_MSK_IAM | OAUTHBEARER | etc>",
 "consumer.sasl.jaas.config": "<jaas_conf_content>",
 "consumer.sasl.client.callback.handler.class": "<handler class name for third party>",
 "source.admin.security.protocol": "SASL_PLAINTEXT",
 "source.admin.sasl.mechanism": "<AWS_MSK_IAM | OAUTHBEARER | etc>",
 "source.admin.sasl.jaas.config": "<jaas_conf_content>",
 "source.admin.sasl.client.callback.handler.class": "<handler class name for third party>",
 "producer.security.protocol": "SASL_PLAINTEXT",
 "producer.sasl.mechanism": "<AWS_MSK_IAM | OAUTHBEARER | etc>",
 "producer.sasl.jaas.config": "<jaas_conf_content>",
 "producer.sasl.client.callback.handler.class": "<handler class name for third party>"
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_schema_registry_service)Schema Registry Service
If there is a [schema registry service](https://docs.confluent.io/platform/current/schema-registry/index.html) containing the record schema of the source topic, please add it to the data source configuration:
```
"value.converter.schema.registry.url": "schema_registry_url"
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Currently, only Avro schema is supported.   
---  
## [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_create_a_loading_job)Create a loading job
A loading job tells the database how to construct vertices and edges from data sources. The loading job body has two parts:
  1. DEFINE statements create variables to refer to data sources. These can refer to actual files or be placeholder names. The actual data sources can be given when running the loading job.
  2. LOAD statements specify how to take the data fields from files to construct vertices or edges.


### [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_example_loading_job_from_external_kafka)Example loading job from external Kafka
The following is an example loading job from and external Kafka cluster.
Example loading job from external Kafka
```
USE GRAPH ldbc_snb
CREATE DATA_SOURCE s1 = "ds_config.json" FOR GRAPH ldbc_snb
CREATE LOADING JOB load_data FOR GRAPH ldbc_snb {
 DEFINE FILENAME file_Comment = "$s1:topic_Comment";
 DEFINE FILENAME file_Person = "$s1:topic_Person";
 DEFINE FILENAME file_Comment_hasCreator_Person =
  "$s1:topic_Comment_hasCreator_Person";
 LOAD file_Comment
  TO VERTEX Comment
   VALUES ($1, $0, $2, $3, $4, $5) USING separator="|";
 LOAD file_Person
  TO VERTEX Person
   VALUES ($1, $2, $3, $4, $5, $0, $6, $7,
    SPLIT($8,";"), SPLIT($9,";")) USING separator="|";
 LOAD file_Comment_hasCreator_Person
  TO EDGE HAS_CREATOR
   VALUES ($1, $2) USING separator="|";
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_define_filenames)Define filenames
First we define _filenames_ , which are local variables referring to data files (or data objects).
The terms `FILENAME` and `filevar` are used for legacy reasons, but a `filevar` can also be an object in a data object store.   
---  
DEFINE FILENAME syntax
```
DEFINE FILENAME filevar ["=" file_descriptor ];
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The file descriptor can be specified at compile-time or at runtime. Runtime settings override compile-time settings:
Specifying file descriptor at runtime
```
RUN LOADING JOB job_name USING filevar=file_descriptor_override
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

While a loading job may have multiple `FILENAME` variables , they must all refer to the same `DATA_SOURCE` object.   
---  
#### [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_kafka_file_descriptors)Kafka file descriptors
The file descriptor has three valid formats. You can simply provide the Kafka topic name and use default settings. Or, you can provide configuration details including the topic, either in a JSON file or as inline JSON content.
```
DEFINE FILENAME file_name = "$[data source name]:[topic]";
DEFINE FILENAME file_name = "$[data source name]:[json config file]";
DEFINE FILENAME file_name = "$[data source name]:[inline json content]";
php![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

For example:
```
// Format 1: topic only
DEFINE FILENAME file_Person = "$s1:topic_Person";
// Format 2: topic and configuration file
DEFINE FILENAME file_Person = "$s1:myfile.json";
// Format 3: topic and inline configuration
DEFINE FILENAME file_Person="""$s1:{
  "topic": "topic_Person",
  "tasks.max": "10"
}""";
go![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_filename_parameters)Filename parameters
These are the required and optional configuration parameters:
Parameter | Description | Required? | Default value  
---|---|---|---  
topic | The source topic name | Required | N/A  
tasks.max | The maximum number of tasks used to consume the source topic. You can increase this value when the source topic contains multiple partitions. | Optional | 1  
num.partitions | The number of partitions to use. When loading data, each partition is distributed evenly across each node. If one filename contains much more data than others, consider using a larger partition number. | Optional | 3  
value.converter | Converter class used to convert between Kafka Connect format and the serialized form that is written to Kafka. This controls the format of the values in messages written to or read from Kafka. If records are in Avro format with Schema Registry service, use `com.tigergraph.kafka.connect.converters.TigerGraphAvroConverter`. If records are in Avro format without using Schema Registry service, use `com.tigergraph.kafka.connect.converters.TigerGraphAvroConverterWithoutSchemaRegistry`. If records are in plaintext or JSON format, use `org.apache.kafka.connect.converters.ByteArrayConverter`. | Optional | N/A  
For Avro data with schema registry,you must set both `value.converter.schema.registry.url` when defining the DATA_SOURCE and `value.converter` when defining a FILENAME.   
---  
### [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_specify_the_data_mapping)Specify the data mapping
Next, we use LOAD statements to describe how the incoming data will be loaded to attributes of vertices and edges. Each LOAD statement handles the data mapping, and optional data transformation and filtering, from one filename to one or more vertex and edge types.
LOAD statement syntax
```
LOAD [ source_object|filevar|TEMP_TABLE table_name ]
 destination_clause [, destination_clause ]*
 [ TAGS clause ] **(1)**
 [ USING clause ];
php![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | As of v3.9.3, TAGS are deprecated.  
---|---  
Let’s break down one of the LOAD statements in our example:
Example loading job for local files
```
LOAD file_Person TO VERTEX Person
  VALUES($1, $2, $3, $4, $5, $0, $6, $7,
    SPLIT($8, ";"), SPLIT($9, ";"))
  USING SEPARATOR="|", HEADER="true", EOL="\n";
php![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * `$0`, `$1`,…​ refer to the first, second, …​ columns in each line a data file.
  * `SEPARATOR="|"` says the column separator character is the pipe (`|`). The default is comma (`,`).
  * `HEADER="true"` says that the first line in the source contains column header names instead of data. These names can be used instead of the columnn numbers.
  * `SPLIT` is one of GSQL’s ETL functions. It says that there is a multi-valued column, which has a separator character to mark the subfields in that column.


Refer to [Creating a Loading Job](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/creating-a-loading-job) in the GSQL Language Reference for descriptions of all the options for loading jobs.
When loading JSON or Avro data,
  * The USING option JSON_FILE="true" must be included.
  * Refer to JSON keys (or Avro field names) instead of column index numbers.

E.g., ```
LOAD file_Comment TO VERTEX Comment
 VALUES ($"id", $"content") USING JSON_FILE="TRUE"php![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!
```
  
---  
### [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_avro_data_validation)Avro Data Validation
In certain scenarios, users could load data in Avro format to TigerGraph DB, via an external Kafka connector, such as MirrorMakerConnector and experience malformed data errors during this process. See our documentation on [Avro Data Validation with KafkaConnect](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/avro-validation-with-kafka) for help.
## [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_run_the_loading_job)Run the loading job
Use the command `RUN LOADING JOB` to run the loading job.
RUN LOADING JOB basic syntax (some options omitted)
```
RUN LOADING JOB [-noprint] job_name [
 USING filevar [="file_descriptor"][, filevar [="file_descriptor"]]*
 [,EOF="eof_mode"]
]
php![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**-noprint**
By default, the loading job will run in the foreground and print the loading status and statistics after you submit the job. If the `-noprint` option is specified, the job will run in the background after displaying the job ID and the location of the log file.
**filevar list**
The optional `USING` clause may contain a list of file variables. Each file variable may optionally be assigned a `file_descriptor`, obeying the same format as in `CREATE LOADING JOB`. This list of file variables determines which parts of a loading job are run and what data files are used.
When a loading job is compiled, it generates one RESTPP endpoint for each `filevar` and source_object. As a consequence, a loading job can be run in parts. When `RUN LOADING JOB` is executed, only those endpoints whose filevar or file identifier (`_GSQL_FILENAME_n_`) is mentioned in the`USING` clause will be used. However, if the `USING` clause is omitted, then the entire loading job will be run.
If a `file_descriptor` is given, it overrides the `file_descriptor` defined in the loading job. If a particular `filevar` is not assigned a `file_descriptor` either in the loading job or in the `RUN LOADING JOB` statement, an error is reported and the job exits.
A loading job from an external Kafka clusters runs in streaming mode regardless of the `EOF` setting, i.e., it continuously read new records from the source topic.   
---  
## [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_manage_and_monitor_your_loading_job)Manage and monitor your loading job
When a loading job starts, the GSQL server assigns it a job ID and displays it for the user to see. There are four key commands to monitor and manage loading jobs:
```
SHOW LOADING STATUS job_id|ALL
ABORT LOADING JOB job_id|ALL
RESUME LOADING JOB job_id
SHOW LOADING ERROR job_id
php![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

`SHOW LOADING STATUS` shows the current status of either a specified loading job or all current jobs, this command should be within the scope of a graph:
```
GSQL > USE GRAPH graph_name
GSQL > SHOW LOADING STATUS ALL
php![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

For each loading job, the above command reports the following information:
  * Loading status
  * Loaded lines/Loaded objects/Error lines
  * Average loading speed
  * Size of loaded data
  * Duration


When inspecting all current jobs with `SHOW LOADING STATUS ALL`, the jobs in the `FINISHED` state will be omitted as they are considered to have successfully finished. You can use `SHOW LOADING STATUS job_id` to check the historical information of finished jobs. If the report for this job contains error data, you can use `SHOW LOADING ERROR job_id` to see the original data that caused the error.
See [Managing and Inspecting a Loading Job](https://docs.tigergraph.com/gsql-ref/3.10/ddl-and-loading/managing-loading-job) for more details.
## [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_manage_loading_job_concurrency)Manage loading job concurrency
See [Loading Job Concurrency](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/loading-concurrency) for how to manage the concurrency of loading jobs.
## [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_kafka_loader_auto_restart)Kafka Loader Auto-Restart
See [High Availability (HA) Overview](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-overview#_support_file_and_kafka_loader_by_auto_restart).
## [](https://docs.tigergraph.com/tigergraph-server/3.10/data-loading/load-from-kafka#_known_issues_with_loading)Known Issues with Loading
TigerGraph does not store NULL values. Therefore, your input data should not contain any NULLs.   
---  
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


