![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy)[Next](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy)
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
  * [File Input Policy](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/3.10/modules/security/pages/gsql-file-input-policy.adoc)
### Contents
  * [Allowlist and Blocklist](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_allowlist_and_blocklist)
  * [Format](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_format)
  * [Default value for File Input Policy](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_default_value_for_file_input_policy)
  * [Unmodifiable Implicit Blocklist](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_unmodifiable_implicit_blocklist)
  * [Affected Operations](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_affected_operations)
  * [Loading Job](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_loading_job)
  * [User-Created Query](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_user_created_query)
  * [Installed Mode](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_installed_mode)
  * [Path for Configurations](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_path_for_configurations)
  * [Put UDF file](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_put_udf_file)
  * [Execute GSQL File](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_execute_gsql_file)
  * [Backward Compatibility](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_backward_compatibility)
  * [3.9.3 to 3.10.0](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_3_9_3_to_3_10_0)
  * [Limitations](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_limitations)
  * [Interpret Mode](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_interpret_mode)
  * [Dynamic Paths during Upgrade](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_dynamic_paths_during_upgrade)
  * [File Link](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_file_link)
  * [File System Permission](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_file_system_permission)
  * [Import Graph](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_import_graph)


# File Input Policy
### Contents
  * [Allowlist and Blocklist](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_allowlist_and_blocklist)
  * [Format](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_format)
  * [Default value for File Input Policy](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_default_value_for_file_input_policy)
  * [Unmodifiable Implicit Blocklist](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_unmodifiable_implicit_blocklist)
  * [Affected Operations](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_affected_operations)
  * [Loading Job](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_loading_job)
  * [User-Created Query](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_user_created_query)
  * [Installed Mode](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_installed_mode)
  * [Path for Configurations](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_path_for_configurations)
  * [Put UDF file](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_put_udf_file)
  * [Execute GSQL File](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_execute_gsql_file)
  * [Backward Compatibility](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_backward_compatibility)
  * [3.9.3 to 3.10.0](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_3_9_3_to_3_10_0)
  * [Limitations](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_limitations)
  * [Interpret Mode](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_interpret_mode)
  * [Dynamic Paths during Upgrade](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_dynamic_paths_during_upgrade)
  * [File Link](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_file_link)
  * [File System Permission](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_file_system_permission)
  * [Import Graph](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_import_graph)


GSQL file input policy allows users to apply restrictions on the location of local files used to load data to TigerGraph.
## [](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_allowlist_and_blocklist)Allowlist and Blocklist
The policy consists of an _allowlist_ and a _blocklist_ :
  * Only paths that belongs to one of the `allowlists` will be allowed for input.
  * The blocklist has higher priority over the `allowlist`.
    * Ex. If a path belongs to both the `allowlist` and `blocklist` simultaneously, the path will be blocked.
  * Users can use `gadmin config` to set the `blocklist` and `allowlist` for the file input policy.


```
gadmin config set GSQL.FileInputPolicy '["/__TG_DATA_ROOT__/gui/loading_data", "!/etc", "!/usr/lib"]'
gadmin config apply -y
gadmin restart gsql restpp -y
```

Similar to the [File Output Policy](https://docs.tigergraph.com/tigergraph-server/4.2/security/file-output-policy) the value for the config is a list of strings that start with either `!/` for the `blocklist` or `/` for the `allowlist`.
## [](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_format)Format
The format of an entry in the `blocklist` or `allowlist` follow the rules below:
  * Paths can use data root:
```
__TG_DATA_ROOT__
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Which will be translated to the actual data root when it’s used.
This is the same as `gadmin config get System.DataRoot`.   
---  
  * Paths must be an absolute path.
    * Paths must start with either `/` for `allowlist`, or `!/` for `blocklist`.
    * Dots are **not** allowed in the path (EX. `/a/../b`, `/a/./b`).
    * Paths should not end with `/` (EX.`/tmp/ → /tmp`).
      * The only exception is for the root path.
    * Some commands will implicitly convert the input relative path to an absolute path with the GSQL client working directory (where the GSQL client was invoked)
      * Examples include: `CREATE LOADING JOB`, `RUN LOADING JOB`, `CREATE CONNECTOR`.
  * No hidden path/files can be added to the `allowlist` (EX. `/home/.ssh`).
    * Hidden paths/files are allowed fto be added to the `blocklist` (EX.`!/home/.ssh`).


## [](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_default_value_for_file_input_policy)Default value for File Input Policy
The default value for the GSQL.FileInputPolicy is the same as File Output Policy: `/`
## [](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_unmodifiable_implicit_blocklist)Unmodifiable Implicit Blocklist
3.10 Input policy may cause backward compatibility issues for customer upgrading from an older version. See [Backward Compatibility](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_backward_compatibility) for more details.  
---  
This is applicable for both file `INPUT` and `OUTPUT` policy.
The unmodifiable implicit blocklist includes:
  1. Any paths with hidden directory or file, (EX. `/home/tg/.ssh/id_rsa`, `/tmp/.mydata`)
  2. Any TigerGraph sensitive paths, including:
```
[
 APP_ROOT,
 DATA_ROOT/configs,
 DATA_ROOT/kafka,
 DATA_ROOT/zk,
 DATA_ROOT/etcd,
 DATA_ROOT/gstore,
 DATA_ROOT/ssh
]
```

`APP_ROOT` is the `PARENT` directory from the path `gadmin config get System.AppRoot`. And `DATA_ROOT` is same from `gadmin config get System.DataRoot`.
  3. Linux’s system sensitive directories, including:
```
[
 /bin,
 /boot,
 /dev,
 /etc,
 /lib,
 /lib32,
 /libx32,
 /lib64,
 /opt,
 /proc,
 /run,
 /sbin,
 /srv,
 /sys,
 /usr,
 /var
]
```



## [](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_affected_operations)Affected Operations
During an upgrade, TigerGraph checks all existing queries and loading jobs and shows a `WARNING` message, if there exists blocked constant paths in queries or loading jobs. If there are any `WARNING` messages users are also prompted with a `Y/N` during upgrade to let the user decide to continue or abort upgrade.
For a non-interactive upgrade the default is `Y`.  
---  
### [](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_loading_job)Loading Job
For a loading job, the input policy only takes into account the loading jobs on local files that are `RUN` and/or `CREATE`.
“CREATE LOADING JOB” and “RUN LOADING JOB” can use relative path, and GSQL server will use the working directory (where GSQL client was invoked) as base path to resolve absolute path.  
---  
#### [](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_run_loading_job)RUN LOADING JOB
When starting to run a file loading job check the given path and apply the file input policy to it.
Below are two example cases:
  1. Path for local data file:
```
CREATE LOADING JOB load_ip FOR GRAPH test_graph {
  DEFINE FILENAME f1 = "any:/tmp/data1.csv";;
  LOAD f1
    TO VERTEX account VALUES ($0, $0),
    TO VERTEX actorIP VALUES ($1, $1),
    TO EDGE event_property VALUES ($0 account, $1 actorIP)
    ;
}
// Notice the path can be either absolute or relative
RUN LOADING JOB load_ip USING f1="m1:./resources/data_set/gsql/k_step_neighber.csv"
```

  2. Path for config file:
```
CREATE DATA_SOURCE KAFKA ka = "/tmp/kafka_broker.json" FOR GRAPH g
CREATE LOADING JOB load_kafka {
  // This path should also be considered
  DEFINE FILENAME f1 = "$ka:/tmp/kafka_topic.json";
  LOAD f1 TO VERTEX v1 VALUES($0, $1);
}
```



#### [](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_loading_job_from_directory)Loading job from Directory
Additionally, a loading job can use a directory instead of specific data file path for `FILENAME`. For example, when using the directory `/dir_1` as `FILENAME`, the TigerGraph loader will traverse all files in the directory to load data.
If users define the input policy as `['/dir_1', '!/dir_1/data_1']`, so that the directory `/dir_1` is in `allowlist`, while a file `/dir_1/data_1` is in `blocklist` the TigerGraph Loader will skip the data file `/dir_1/data_1`. While still loading other files that are not in `blocklist`. (Ex. `/dir_1/data_2`, `/dir_1/data_3`, etc…​).
Users will see a warning message in RESTPP log:
```
[WARNING] The file "/dir_1/data_1" is skipped because it violates file input policy.
```

There are 2 ways to run loading jobs:
  1. The GSQL command:
```
gsql -g G1 'run loading job load_job1'
```

  2. The GSQL API:
Use the API to start the loading job and pass in the configuration json directly in string:
```
curl --user tigergraph:tigergraph -d '
[
  {
   "name":"load_person",
   "dataSources":[
     {
      "filename":"f1",
      "name":"k1",
      "path":"",
      "config":{
        "topic":"kiwi",
        "partition_list":[
         {
           "start_offset":-2,
           "partition":0
         }
        ]
      }
     }
   ],
   "streaming":false
  }
]
' -X POST "http://localhost:8123/gsql/loading-jobs?graph=test_graph&action=start"
```



#### [](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_create_loading_job)CREATE LOADING JOB
If a path is explicitly given (Ex. `sys.data_root`) when creating a loading job, users can check the path during creation of the loading job and block it immediately if not allowed.
## [](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_user_created_query)User-Created Query
### [](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_installed_mode)Installed Mode
#### [](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_selectvertex)selectVertex
`selectVertex` will read existing vertices from a local file directly.
Users should check filepath for the function.  
---  
```
CREATE QUERY selectVertexEx(STRING filename) FOR GRAPH socialNet {
  S1 = {SelectVertex(filename, $"c1", $1, ",", true)};
  S2 = {SelectVertex(filename, $0, person, ",", true)};
  PRINT S1, S2; # Both sets of inputs product the same result
}
```

#### [](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_loadaccum)LoadAccum
`LoadAccum` is supported in a query to load data from local file into global accumulator.
```
CREATE QUERY load_accum_ex (STRING filename) FOR GRAPH Social_Net {
  TYPEDEF TUPLE<STRING aaa, VERTEX<Post> ddd> Your_Tuple;
    MapAccum<VERTEX<Person>, MapAccum<INT, Your_Tuple>> @@test_map;
    GroupByAccum<STRING a, STRING b, MapAccum<STRING, STRING> strList> @@test_group_by;
    @@test_map = { LOADACCUM (filename, $0, $1, $2, $3, ",", false)};
    @@test_group_by = { LOADACCUM ( filename, $1, $2, $3, $3, ",", true) };
  PRINT @@test_map, @@test_group_by;
}
```

## [](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_path_for_configurations)Path for Configurations
We also allow `parse` and `read` configurations from local file system. These commands can be protected by file input policy as well, including:
```
CREATE DATA_SOURCE KAFKA k1 = "/path/to/config"
// from 3.9.0
CREATE CONNECTOR FROM "/tmp/conn.cfg"
CREATE DATA_SOURCE STREAM s1 = "/tmp/ds_config.json"
```

If the object `DATA_SOURCE/CONNECTOR` is already created, and users can change the file input policy. Then the existing object won’t be affected because the config file is already read when creating the object. Also, `CREATE DATA_SOURCE` can only run with **local gsql client** , because the file is `read` from GSQL server.  
---  
## [](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_put_udf_file)Put UDF file
File input policy can also be applied to where UDF files are uploaded from. Notice the `PUT` command can also use relative path (implicitly converted to absolute path within the GSQL client working directory)
```
gsql '
PUT ExprFunctions FROM "resources/gsql/common/ExprFunctions.hpp"
'
```

Similar to [Execute GSQL File](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_execute_gsql_file), this restriction **does not** apply to remote GSQL client. It only apply to local GSQL client.  
---  
## [](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_execute_gsql_file)Execute GSQL File
There are 2 ways to execute GSQL file.
  1. In a GSQL shell:
```
GSQL > @hello.gsql
```

  2. From GSQL client directly:
```
gsql hello.gsql
gsql -f hello.gsql
```



For a remote GSQL client, users do not need to apply file input policy. However, users need to apply the file input policy to local GSQL clients to avoid reading local files.  
---  
## [](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_backward_compatibility)Backward Compatibility
When upgrading from an old version:
  * GSQL will scan constant file paths in all queries and loading jobs in all graphs.
  * If violations of default file input/output policy are found (due to [Unmodifiable Implicit Blocklist](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_unmodifiable_implicit_blocklist), a message will prompt the user to let them choose to continue or abort the upgrade.


### [](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_3_9_3_to_3_10_0)3.9.3 to 3.10.0
For more details, here is an example when upgrading from 3.9.3 to 3.10.0 and when there exists some violations of file input and output paths.
  * The TigerGraph upgrade displays 1 loading job (`loadData_1`) and 2 queries (`q1_FileInput` and `q2_FileOutput`). These 3 objects include constant paths that do not comply with the unmodifiable blocklist of file input or output policy.


Users can choose to continue or abort the upgrade.
If continued, after the upgrade, the affected queries will fail to install and the loading jobs will fail to run. Users must rewrite the query/loading job in order to install them again.  
---  
```
>> bash install.sh -U
...
Do you want to switch platform to the new version now (it can be delayed to a later time)? (y/N): y
...
[PROGRESS]: 23:30:16 Verify dict and UDF file ...
======= UPGRADE_OLD_VERSION: 3.9.3 =======
Run UDF Policy check since the config GSQL.UDF.Policy.Enable is true.
Verify UDF file at path: /home/tigergraph/tigergraph/data/gsql/udf/ExprUtil.hpp
Uploaded UDF file does not exist. Skip compatibility check on it.
Verify UDF file at path: /home/tigergraph/tigergraph/data/gsql/udf/ExprFunctions.hpp
Uploaded UDF file does not exist. Skip compatibility check on it.
Successfully finished verifying UDF compatibility.
======== Start: Backward Compatibility Check on File Input/Output Policy ========
Collecting constant paths that violate file policy ...
------ Start graph: test_graph ------
- Query q1_FileInput: [/etc/os_data]
- Query q2_FileOutput: [/home/tigergraph/tigergraph/data/gstore/tg_data]
- Loading Job loadData_1: [/tmp/.hidden/data.csv]
------ Finish graph: test_graph ------
======== Complete: Backward Compatibility Check on File Input/Output Policy ========
File input/output violations were observed on constant paths from the listed objects above.
The default file input/output policy requires file path must:
1. Use absolute path, not use relative path.
2. Not use hidden path or file like "/.ssh/data", "/.mydata".
3. Not use any TigerGraph sensitive paths, including System.AppRoot and some paths under System.DataRoot.
4. Not use Linux system sensitive paths, like "/etc", "/sys"
For more details, please check our documentation on file input/output policy.
If continue, after upgrade the affected queries will fail to install, and loading jobs will fail to run.
Successfully finished verifying catalog.
[GTEST_IL] Please check debug log at: /home/tigergraph/tigergraph-3.10.0-offline-fileinput/gsql-checker-log/DEBUG.20240208-233017.776
Do you want to continue this upgrade? [y/N]:
```

For a non-interactive upgrade (`bash install.sh -U -n`), the upgrade will choose “continue” automatically.  
---  
## [](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_limitations)Limitations
### [](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_interpret_mode)Interpret Mode
Features listed are not yet supported in **INTERPRET** mode yet.
  * `selectVertex`
  * `LoadAccum`
  * UDF functions


### [](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_dynamic_paths_during_upgrade)Dynamic Paths during Upgrade
During a TigerGraph upgrade, file input policy is not able to collect dynamic file paths during the check.
For example:
```
CREATE QUERY qDynFile(STRING filename) {
  FILE file1(filename);
    file1.println("first line");
}
```

After an upgrade, TigerGraph may throw runtime errors when a user tries to run an old script to run query or loading jobs.
For example:
```
GSQL >> RUN QUERY qDynFile("/etc/os_data")
Runtime Error: Linux system sensitive directory '/etc' is not allowed in path. Please use another path.
```

### [](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_file_link)File Link
Similar to file output policy a Linux file system supports symbolic links (symlinks) and hard links. Both symlinks and hard links are attributes of a file. A file can be marked a symlink or be a hard link to another file.
TigerGraph file input policy can only control the link in the path to block or allow it.
### [](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_file_system_permission)File System Permission
If the system user of TigerGraph installation does not have a permission to read a file, there might be an error thrown when a user attempts to read the file, even if the file is in `allowlist`.
This is also controlled by the operating system.
### [](https://docs.tigergraph.com/tigergraph-server/3.10/security/gsql-file-input-policy#_import_graph)Import Graph
Applying a file input policy on Import Graph is not yet supported in TigerGraph.
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


