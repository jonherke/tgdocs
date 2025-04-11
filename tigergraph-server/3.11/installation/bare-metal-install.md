![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/3.11/installation/bare-metal-install)[Next](https://docs.tigergraph.com/tigergraph-server/3.11/installation/bare-metal-install)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/3.11/installation/bare-metal-install)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/3.11/installation/bare-metal-install)
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
  * [Get Started](https://docs.tigergraph.com/tigergraph-server/3.11/getting-started/)
  * Installation
  * [On Linux](https://docs.tigergraph.com/tigergraph-server/3.11/getting-started/linux)
  * [Linux On Bare Metal](https://docs.tigergraph.com/tigergraph-server/3.11/installation/bare-metal-install)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/3.11/modules/installation/pages/bare-metal-install.adoc)
### Contents
  * [1. Prerequisites](https://docs.tigergraph.com/tigergraph-server/3.11/installation/bare-metal-install#_prerequisites)
  * [1.1. For Oracle Linux and RedHat distros](https://docs.tigergraph.com/tigergraph-server/3.11/installation/bare-metal-install#_for_oracle_linux_and_redhat_distros)
  * [2. Non-Interactive Installation](https://docs.tigergraph.com/tigergraph-server/3.11/installation/bare-metal-install#_non_interactive_installation)
  * [2.1. Extract Package](https://docs.tigergraph.com/tigergraph-server/3.11/installation/bare-metal-install#_extract_package)
  * [2.2. Edit Configuration File](https://docs.tigergraph.com/tigergraph-server/3.11/installation/bare-metal-install#_edit_configuration_file)
  * [2.3. Run Installation Script](https://docs.tigergraph.com/tigergraph-server/3.11/installation/bare-metal-install#_run_installation_script)
  * [3. Interactive Installation](https://docs.tigergraph.com/tigergraph-server/3.11/installation/bare-metal-install#_interactive_installation)
  * [3.1. Extract Package](https://docs.tigergraph.com/tigergraph-server/3.11/installation/bare-metal-install#_extract_package_2)
  * [3.2. Run Installation Script](https://docs.tigergraph.com/tigergraph-server/3.11/installation/bare-metal-install#_run_installation_script_2)


# Installation on Bare Metal
### Contents
  * [1. Prerequisites](https://docs.tigergraph.com/tigergraph-server/3.11/installation/bare-metal-install#_prerequisites)
  * [1.1. For Oracle Linux and RedHat distros](https://docs.tigergraph.com/tigergraph-server/3.11/installation/bare-metal-install#_for_oracle_linux_and_redhat_distros)
  * [2. Non-Interactive Installation](https://docs.tigergraph.com/tigergraph-server/3.11/installation/bare-metal-install#_non_interactive_installation)
  * [2.1. Extract Package](https://docs.tigergraph.com/tigergraph-server/3.11/installation/bare-metal-install#_extract_package)
  * [2.2. Edit Configuration File](https://docs.tigergraph.com/tigergraph-server/3.11/installation/bare-metal-install#_edit_configuration_file)
  * [2.3. Run Installation Script](https://docs.tigergraph.com/tigergraph-server/3.11/installation/bare-metal-install#_run_installation_script)
  * [3. Interactive Installation](https://docs.tigergraph.com/tigergraph-server/3.11/installation/bare-metal-install#_interactive_installation)
  * [3.1. Extract Package](https://docs.tigergraph.com/tigergraph-server/3.11/installation/bare-metal-install#_extract_package_2)
  * [3.2. Run Installation Script](https://docs.tigergraph.com/tigergraph-server/3.11/installation/bare-metal-install#_run_installation_script_2)


This guide describes how to install TigerGraph on bare-metal infrastructure.
The installation guide covers installation as a single node or as a multi-node cluster, interactively or non-interactively.
If you are planning to set up a cluster with High Availability (HA) or Cross-Region Replication (CRR), please read the following pages first:
  * [High Availability Cluster Configuration](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/ha-cluster)
  * [Cross-Region Replication](https://docs.tigergraph.com/tigergraph-server/3.11/cluster-and-ha-management/crr-index)


If you are performing an upgrade of an existing TigerGraph installation, please see [Upgrading an Existing Installation](https://docs.tigergraph.com/tigergraph-server/3.11/installation/upgrade) instead.   
---  
## [](https://docs.tigergraph.com/tigergraph-server/3.11/installation/bare-metal-install#_prerequisites)1. Prerequisites
  * Your machines meet the minimum [_Hardware and Software Requirements_](https://docs.tigergraph.com/tigergraph-server/3.11/installation/hw-and-sw-requirements).
    * The installation machine can be within or outside the cluster. If outside the cluster, the installation machine still needs to be a Linux machine.
  * A [TigerGraph system package](https://dl.tigergraph.com/).
  * A TigerGraph license key, for either a [free trial](https://dl.tigergraph.com/) or a purchased enterprise license.
  * Every machine in the cluster has a Linux superuser with the same username and password, or same username and SSH key.
  * If you are installing a cluster, ensure that every machine has the same SSH port and that the port stays open during installation.
    * SSH port does not need to be 22. You can specify a custom port number during installation.
  * All [ports used for internal communication](https://docs.tigergraph.com/tigergraph-server/3.11/reference/ports) **must** be allowed for a correct TigerGraph installation and usage.
  * All provisioned machines must be in the same region if installing on cloud.
  * All provisioned machines must have the same CPU, RAM and disk size.
  * All provisioned machines must have enough disk space available (≥ 50 GB) for TigerGraph Cluster installation.
  * All provisioned machines must be running SSD disk types.
  * All provisioned machines must have all clocks in-sync.
  * All provisioned machines must allow password-less SSH for the Linux superuser.
  * All provisioned machines must be serving only TigerGraph.


### [](https://docs.tigergraph.com/tigergraph-server/3.11/installation/bare-metal-install#_for_oracle_linux_and_redhat_distros)1.1. For Oracle Linux and RedHat distros
If you install on Oracle Linux Server (OEL) or RedHat (RHEL), there are a few additional prerequisites.
  1. For each node, create an OS user and password.
```
sudo useradd NEW-USER
sudo passwd NEW-USER
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  2. Add the new user to the AllowUsers row in the `/etc/ssh/sshd_config` file.
```
AllowUsers OLD-USER NEW-USER
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  3. Restart sshd.
```
/sbin/service sshd restart
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```



This adds firewall rules to allow TCP communication between nodes in the cluster. The installation process will prompt you for these steps. If you have already completed them, ignore and continue.
## [](https://docs.tigergraph.com/tigergraph-server/3.11/installation/bare-metal-install#_non_interactive_installation)2. Non-Interactive Installation
In non-interactive installation, you specify all the desired configurations in a JSON file, and run the installation script with the configurations specified in the file. This is the recommended approach as it allows you to see all your configurations in one place and diagnose issues more easily.
### [](https://docs.tigergraph.com/tigergraph-server/3.11/installation/bare-metal-install#_extract_package)2.1. Extract Package
Extract the package by running the following command to create a folder named `tigergraph-<version>-offline`. The filename of your package may vary depending on the product edition and version.
```
$ tar -xvzf tigergraph-<version>.tar.gz
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.11/installation/bare-metal-install#_edit_configuration_file)2.2. Edit Configuration File
Navigate to the `tigergraph-<version>-offline` folder and open the configuration file called `install_conf.json`.
Edit the configuration file according to your needs, pay extra attention to the following entries:
  * **TigerGraph Username and Password** : A TigerGraph database has a built-in superuser, whose default username and password are `tigergraph`. You can either customize the username and password now or after installation. If the username already exists, the installer will skip creating a new user.
Deploying a database without changing the password for the TigerGraph superuser is a security risk.   
---  
  * **SSHPort** : By default, the SSH port is `22`, if this port is open in all the provisioned machines you can leave it as it is. Otherwise change the port to the actual SSH port in your environment. The SSH port number **must** be the same across all the provisioned machines.
  * **PrivateKeyFile** and **PublicKeyFile** : The TigerGraph installer creates these keys by default, so these fields are optional. If you want to pass your own keys you can add the absolute paths here.
  * **NodeList** : The list of your provisioned machines IPs in the following JSON format:
```
  "NodeList": [
   "m1: 123.456.78.99",
   "m2: 123.456.78.98",
   "m3: 123.456.78.97",
   "m4: 123.456.78.96"
  ]
javascript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

    * For single server installation, you only specify the IP address for m1. You can either use loop-back address (e.g. `127.0.0.1`) or the public IP of the machine. if you use loop-back address IP for m1, you do not need to specify any sudo user for `SudoUser` or authentication method in the `Method` section.
    * Users can also provide the hostnames in the NodeList:
Ex. Node and `hostname` pair in `install_conf.json` file:
```
"NodeList": [
 "m1: hostname1",
 "m2: hostname2",
 "m3: hostname3",
 "m4: hostname4"
]"
javascript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * **SudoUser** : Username of the sudo user who will be used to execute the installation on all nodes. This user **must** exist on all the provisioned machines
  * **Authentication Method** : This refers to how the above sudo user will authenticate between the provisioned machines. It can authenticate via password (chose the `P` method and pass the password) or via SSH key (choose the `K` method and pass the absolute path for the SSH key).
  * **ReplicationFactor** : The number of replicas in your cluster. Refer to [Replication factor](https://docs.tigergraph.com/tigergraph-server/3.11/intro/continuous-availability-overview#_continuous_availability__definitions) for detailed description.


#### [](https://docs.tigergraph.com/tigergraph-server/3.11/installation/bare-metal-install#_example)2.2.1. Example
The following is an example configuration:
```
{
 "BasicConfig": {
  "TigerGraph": {
   "Username": "mark",
   "Password": "markpassword",
   "SSHPort": 22,
   "PrivateKeyFile": "",
   "PublicKeyFile": ""
  },
  "RootDir": {
   "AppRoot": "/home/tigergraph/tigergraph/app",
   "DataRoot": "/home/tigergraph/tigergraph/data",
   "LogRoot": "/home/tigergraph/tigergraph/log",
   "TempRoot": "/home/tigergraph/tigergraph/tmp"
  },
  "License": "<license>",
  "NodeList": [
   "m1: 123.456.78.99",
   "m2: 123.456.78.98",
   "m3: 123.456.78.97",
   "m4: 123.456.78.96"
  ]
 },
 "AdvancedConfig": {
  "ClusterConfig": {
   "LoginConfig": {
    "SudoUser": "tom",
    "Method": "K",
    "P": "<sudo_user_password>",
    "K": "/home/tom/mykey.pem"
   },
   "ReplicationFactor": 2
  }
 }
}
javascript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.11/installation/bare-metal-install#_run_installation_script)2.3. Run Installation Script
Save the configuration changes and run `sudo ./install.sh -n` to install the TigerGraph Cluster in non-interactive mode based on the configuration you passed in the `install_conf.json` file.
## [](https://docs.tigergraph.com/tigergraph-server/3.11/installation/bare-metal-install#_interactive_installation)3. Interactive Installation
With interactive installation, you **do not** need to edit the `install_conf.json` configuration file as you will be asked **interactively** to pass the required information while you install TigerGraph.
### [](https://docs.tigergraph.com/tigergraph-server/3.11/installation/bare-metal-install#_extract_package_2)3.1. Extract Package
Extract the package by running the following command to create a folder named `tigergraph-<version>-offline`. The filename of your package may vary depending on the product edition and version.
```
$ tar -xvzf tigergraph-<version>.tar.gz
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.11/installation/bare-metal-install#_run_installation_script_2)3.2. Run Installation Script
Navigate to the `tigergraph-<version>-offline`` folder and run the `install.sh` script with the following commands:
```
$ cd tigergraph-<version>-offline

#sudo not requried for standalone installation
$ sudo ./install.sh
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Provide the information that the installer asks for below:
You may choose to hit Enter to skip and use the system default or enter a new value.  
---  
  * Your installation method, you can choose:
    * Install using an IP Address.
    * Install using a hostname.
![image 20240328 142603](https://docs.tigergraph.com/tigergraph-server/3.11/installation/_images/image-20240328-142603.png)
  * Your agreement to the License Terms and Conditions
  * Your license key
  * Username for the Linux user who will own and manage the TigerGraph platform
    * The installer creates a Linux user with this username who is the only authorized user that can run `gadmin` commands to manage the TigerGraph Platform.
    * If the installation and data folders are modified from their defaults, the newly created user must have appropriate permissions for these folders. The installation folder requires read/write/execute access, and the other folders require read/write access.
  * Password for the Linux user who will own and manage the TigerGraph platform
  * Path to where the installation folder will be
  * Path to where the data folder will be
  * Path to where the log folder will be
    * For production systems, it’s recommended that you use a separate disk partition to store log files to prevent out-of-space issues.
  * Path to where the temp folder will be
  * The SSH port for your machine


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


