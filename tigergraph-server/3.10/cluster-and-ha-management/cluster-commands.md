![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands)[Next](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands)
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
  * [Cluster and HA Management](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/)
  * [High Availability (HA)](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/ha-overview)
  * [Cluster Commands](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/3.10/modules/cluster-and-ha-management/pages/cluster-commands.adoc)
### Contents
  * [Connection between nodes](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_connection_between_nodes)
  * [Connect to another node via SSH](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_connect_to_another_node_via_ssh)
  * [File operations](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_file_operations)
  * [Copy files on the specified nodes](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_copy_files_on_the_specified_nodes)
  * [Download file from another node](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_download_file_from_another_node)
  * [Run commands on multiple nodes](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_run_commands_on_multiple_nodes)
  * [Run commands sequentially](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_run_commands_sequentially)
  * [Run commands in parallel](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_run_commands_in_parallel)
  * [Display cluster information](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_display_cluster_information)
  * [Show current GSQL leader](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_show_current_gsql_leader)
  * [Show current node IP](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_show_current_node_ip)
  * [Show current node number and servers](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_show_current_node_number_and_servers)
  * [Show deployment information](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_show_deployment_information)
  * [Show graph status](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_show_graph_status)


# Cluster Commands
### Contents
  * [Connection between nodes](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_connection_between_nodes)
  * [Connect to another node via SSH](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_connect_to_another_node_via_ssh)
  * [File operations](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_file_operations)
  * [Copy files on the specified nodes](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_copy_files_on_the_specified_nodes)
  * [Download file from another node](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_download_file_from_another_node)
  * [Run commands on multiple nodes](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_run_commands_on_multiple_nodes)
  * [Run commands sequentially](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_run_commands_sequentially)
  * [Run commands in parallel](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_run_commands_in_parallel)
  * [Display cluster information](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_display_cluster_information)
  * [Show current GSQL leader](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_show_current_gsql_leader)
  * [Show current node IP](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_show_current_node_ip)
  * [Show current node number and servers](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_show_current_node_number_and_servers)
  * [Show deployment information](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_show_deployment_information)
  * [Show graph status](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_show_graph_status)


This page documents a list of advanced Linux commands that simplify platform operations that are performed often during debugging, especially on high availability (HA) clusters. Only the TigerGraph platform owner (the Linux user created during installation) has access to the commands on this page.
Users are advised to use these commands only at the guidance and recommendation of TigerGraph support.  
---  
## [](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_connection_between_nodes)Connection between nodes
### [](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_connect_to_another_node_via_ssh)Connect to another node via SSH
```
$ gssh <node_name>
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This command allows you to connect to another node in your cluster via SSH.
#### [](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_example)Example:
```
# Originally on m1
[tigergraph@ip-172-31-88-111 ~]$ gssh m3
Last login: Fri Apr 23 18:24:27 2021
# Now connected to m3 via ssh
[[tigergraph@ip-172-31-93-187 ~]$
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_file_operations)File operations
### [](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_copy_files_on_the_specified_nodes)Copy files on the specified nodes
```
$ gscp <all|component_name|node_list> <source_path> <target_dir>
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This command allows you to copy files from the current node to target folders on multiple nodes at the same time. The file or directory on the current node specified by the source path will be copied into the target folder on every node.
If the target folder does not exist at the path given, the target folder will be created automatically. You can also specify multiple source files or directories, in which case, the source paths need to be absolute paths, put in quotes, and separated by a space.
You can specify the nodes where you want the copy operation to occur in the following ways:
  * `gscp all <source_path> <target_dir>` will execute the command on all nodes
  * `gscp <component_name> <source_path> <target_dir>` will execute the command on nodes where the component you specified is running
  * `gscp <node_list> <source_path> <target_dir>` will execute the command on the nodes you specify in the node list


#### [](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_example_2)Example
  * Single source
  * Multiple sources


```
$ gscp all /tmp/gscp_test /tmp/gscp_test_folder
### Connecting to local server 172.31.91.54 ...
### Connecting to remote server 172.31.88.179 ...
### Connecting to remote server 172.31.91.208 ...
// A copy of gscp_test is on every node
$ grun all 'ls /tmp/gscp_text_folder'
### Connecting to local server 172.31.91.54 ...
gscp_test
### Connecting to remote server 172.31.88.179 ...
gscp_test
### Connecting to remote server 172.31.91.208 ...
gscp_test
// Copy file to the target folder only on nodes where GPE is running
$ gscp gpe /tmp/gscp_test1 /tmp/gscp_test_folder
// Copy file to a specified list of nodes
$ gscp m1,m2 /tmp/gscp_test3 /tmp/gscp_test_folder
cpp![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
$ gscp all "/tmp/gscp_test1 /tmp/gscp_test2" /tmp/gscp_test_folder
### Connecting to local server 172.31.91.54 ...
### Connecting to remote server 172.31.88.179 ...
### Connecting to remote server 172.31.91.208 ...
// Copies of both files are on every node
$ grun all 'ls /tmp/gscp_text_folder'
### Connecting to local server 172.31.91.54 ...
gscp_test1 gscp_test2
### Connecting to remote server 172.31.88.179 ...
gscp_test1 gscp_test2
### Connecting to remote server 172.31.91.208 ...
gscp_test1 gscp_test2
cpp![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_download_file_from_another_node)Download file from another node
```
$ gfetch <all|component_name|node_list> <source_path> <target_dir>
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This command downloads a file or directory from every specified node to the target directory on the current node.
#### [](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_example_3)Example
```
$ gfetch all ~/test.txt ~/test_folder
### Connecting to local server 172.31.91.54 ...
### Connecting to remote server 172.31.88.179 ...
### Connecting to remote server 172.31.91.208 ...
scp: /home/tigergraph/test.txt: No such file or directory
// Nothing is downloaded if the file does not exist on a node
$ ls ~/test_folder
test.txt_m1 test.txt_m2
cpp![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_run_commands_on_multiple_nodes)Run commands on multiple nodes
### [](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_run_commands_sequentially)Run commands sequentially
```
$ grun <all|component_name|node_list> '<command>'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This command allows you to run commands on a specified list of nodes in your cluster one by one, and the output from every node will be visible to the terminal. `grun` will wait for the command to finish running on one node before executing the command on the next node.
You can specify which nodes to run commands on in the following ways:
  * `grun all '<command>'` will execute the command on all nodes
  * `grun <component_name> '<command>'` will execute the command on nodes where the component you specified is running
  * `grun <node_list> '<command>'` will execute the commands on the nodes you specify in the node list


#### [](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_example_4)Example
  * All nodes
  * By component name
  * By node list


```
grun all 'echo "hello world"'
### Connecting to local server 172.31.91.54 ...
hello world
### Connecting to remote server 172.31.88.179 ...
hello world
### Connecting to remote server 172.31.91.208 ...
hello world
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
# Run 'echo "hello world"' on every node where GPE is running
grun gpe 'echo "hello world"'
### Connecting to local server 172.31.91.54 ...
hello world
### Connecting to remote server 172.31.88.179 ...
hello world
### Connecting to remote server 172.31.91.208 ...
hello world
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
grun m1,m3 'echo "hello world"'
### Connecting to local server 172.31.91.54 ...
hello world
### Connecting to remote server 172.31.91.208 ...
hello world
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_run_commands_in_parallel)Run commands in parallel
```
$ grun_p <all|component_name|node_list> '<command>'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This command allows you to run commands on a specified list of nodes in your cluster in parallel. The output will be visible to the terminal where the `grun_p` command was run. You can specify the nodes to run commands on in the following ways:
  * `grun_p all '<command>'` will execute the command on all nodes
  * `grun_p <component_name> '<command>'` will execute the command on nodes where the component you specified is running
  * `grun_p <node_list> '<command>'` will execute the commands on the nodes you specify in the node list. The list of nodes should be separated by a comma, e.g.: `m1,m2`


  * All nodes 
  * By component
  * By node list


```
$ grun_p all 'echo "hello world"'
### Connecting to local server 172.31.91.54 ...
### Connecting to remote server 172.31.88.179 ...
### Connecting to remote server 172.31.91.208 ...
### ---- (m1)_172.31.91.54 ---0--
hello world
### ---- (m2)_172.31.88.179 ---0--
hello world
### ---- (m3)_172.31.91.208 ---0--
hello world
aspnet![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
$ grun_p gpe 'echo "hello world"'

### Connecting to local server 172.31.91.54 ...

### Connecting to remote server 172.31.88.179 ...

### Connecting to remote server 172.31.91.208 ...

### ---- (m1)_172.31.91.54 ---0--
hello world

### ---- (m2)_172.31.88.179 ---0--
hello world

### ---- (m3)_172.31.91.208 ---0--
hello world
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
$ grun_p m1,m3 'echo "hello world"'

### Connecting to local server 172.31.91.54 ...

### Connecting to remote server 172.31.91.208 ...

### ---- (m1)_172.31.91.54 ---0--
hello world

### ---- (m3)_172.31.91.208 ---0--
hello world
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_display_cluster_information)Display cluster information
### [](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_show_current_gsql_leader)Show current GSQL leader
```
$ gsql -leader
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This command outputs the name of the current GSQL leader as well as the leader’s IP address.
#### [](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_example_5)Example
```
$ gsql -leader
m1 : 192:192:19:219
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_show_current_node_ip)Show current node IP
```
$ gmyip
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This command returns the private IP address of your current node.
#### [](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_example_6)Example:
```
$ gmyip
172.31.93.187 # Current node IP address
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_show_current_node_number_and_servers)Show current node number and servers
```
$ ghostname
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This command returns your current node number as well as all servers that are running on the current node.
#### [](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_example_7)Example
In this example, `m1` is the current node number, and `ADMIN#1`, `admin#1` etc. are all servers that are running on `m1`.
```
$ ghostname
m1 ADMIN#1 admin#1 CTRL#1 ctrl#1 DICT#1 dict#1 ETCD#1 etcd#1 EXE_1 exe_1 GPE_1#1 gpe_1#1 GSE_1#1 gse_1#1 GSQL#1 gsql#1 GUI#1 gui#1 IFM#1 ifm#1 KAFKA#1 kafka#1 KAFKACONN#1 kafkaconn#1 KAFKASTRM-LL_1 kafkastrm-ll_1 NGINX#1 nginx#1 RESTPP#1 restpp#1 TS3_1 ts3_1 TS3SERV#1 ts3serv#1 ZK#1 zk#1
cpp![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_show_deployment_information)Show deployment information
```
$ gssh
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The `gssh` command, when used without arguments, outputs information about server deployments in your cluster. The output contains the names and IP addresses of every node. For each node, the output shows the full list of servers that are running on the node. For each server, the output shows the full list of the nodes that the server is running on.
#### [](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_example_8)Example
```
$ gssh
Usage: gssh m1|gpe_1#1|gse1_1#1|...
Usage: ----------------Available hosts--------------
Host *
  IdentityFile /home/tigergraph/.ssh/tigergraph_rsa
  Port 22
Host m1 ADMIN#1 admin#1 CTRL#1 ctrl#1 DICT#1 dict#1 ETCD#1 etcd#1 EXE_1 exe_1 GPE_1#1 gpe_1#1 GSE_1#1 gse_1#1 GSQL#1 gsql#1 GUI#1 gui#1 IFM#1 ifm#1 KAFKA#1 kafka#1 KAFKACONN#1 kafkaconn#1 KAFKASTRM-LL_1 kafkastrm-ll_1 NGINX#1 nginx#1 RESTPP#1 restpp#1 TS3_1 ts3_1 TS3SERV#1 ts3serv#1 ZK#1 zk#1
  HostName 172.31.91.54
Host m2 ADMIN#2 admin#2 CTRL#2 ctrl#2 DICT#2 dict#2 ETCD#2 etcd#2 EXE_2 exe_2 GPE_2#1 gpe_2#1 GSE_2#1 gse_2#1 GSQL#2 gsql#2 GUI#2 gui#2 IFM#2 ifm#2 KAFKA#2 kafka#2 KAFKACONN#2 kafkaconn#2 KAFKASTRM-LL_2 kafkastrm-ll_2 NGINX#2 nginx#2 RESTPP#2 restpp#2 TS3_2 ts3_2 ZK#2 zk#2
  HostName 172.31.88.179
Host m3 ADMIN#3 admin#3 CTRL#3 ctrl#3 DICT#3 dict#3 ETCD#3 etcd#3 EXE_3 exe_3 GPE_3#1 gpe_3#1 GSE_3#1 gse_3#1 GSQL#3 gsql#3 GUI#3 gui#3 IFM#3 ifm#3 KAFKA#3 kafka#3 KAFKACONN#3 kafkaconn#3 KAFKASTRM-LL_3 kafkastrm-ll_3 NGINX#3 nginx#3 RESTPP#3 restpp#3 TS3_3 ts3_3 ZK#3 zk#3
  HostName 172.31.91.208
#cluster.nodes: m1:172.31.91.54,m2:172.31.88.179,m3:172.31.91.208
#admin.servers: m1,m2,m3
#ctrl.servers: m1,m2,m3
#dict.servers: m1,m2,m3
#etcd.servers: m1,m2,m3
#exe.servers: m1,m2,m3
#gpe.servers: m1,m2,m3
#gse.servers: m1,m2,m3
#gsql.servers: m1,m2,m3
#gui.servers: m1,m2,m3
#ifm.servers: m1,m2,m3
#kafka.servers: m1,m2,m3
#kafkaconn.servers: m1,m2,m3
#kafkastrm-ll.servers: m1,m2,m3
#nginx.servers: m1,m2,m3
#restpp.servers: m1,m2,m3
#ts3.servers: m1,m2,m3
#ts3serv.servers: m1
#zk.servers: m1,m2,m3
#log.root: /home/tigergraph/tigergraph/log
#app.root: /home/tigergraph/tigergraph/app/3.1.1
#data.root: /home/tigergraph/tigergraph/data
aspnet![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_show_graph_status)Show graph status
```
$ gstatusgraph
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This command returns the size of your data, the number of existing vertices and edges, and the number of deleted and skipped vertices on every node in your cluster. If you are running TigerGraph on a single node, it will return the same information for that one node.
#### [](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_single_node_example)Single-node example
```
$ gstatusgraph
=== graph ===
[GRAPH ] Graph was loaded (/home/tigergraph/tigergraph/data/gstore/0/part/):
[m1   ] Partition size: 437MiB, IDS size: 103MiB, Vertex count: 3181724, Edge count: 34512076, NumOfDeletedVertices: 0 NumOfSkippedVertices: 0
[WARN  ] Above vertex and edge counts are for internal use which show approximate topology size of the local graph partition. Use DML to get the correct graph topology information
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/3.10/cluster-and-ha-management/cluster-commands#_cluster_example)Cluster example
```
$ gstatusgraph
=== graph ===
[GRAPH ] Graph was loaded (/home/tigergraph/tigergraph/data/gstore/0/part/):
[m1   ] Partition size: 246MiB, IDS size: 31MiB, Vertex count: 1152822, Edge count: 10908545, NumOfDeletedVertices: 0 NumOfSkippedVertices: 0
[m2   ] Partition size: 248MiB, IDS size: 31MiB, Vertex count: 1157325, Edge count: 11004342, NumOfDeletedVertices: 0 NumOfSkippedVertices: 0
[m3   ] Partition size: 225MiB, IDS size: 29MiB, Vertex count: 1049883, Edge count: 10009479, NumOfDeletedVertices: 0 NumOfSkippedVertices: 0
[WARN  ] Above vertex and edge counts are for internal use which show approximate topology size of the local graph partition. Use DML to get the correct graph topology information
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

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


