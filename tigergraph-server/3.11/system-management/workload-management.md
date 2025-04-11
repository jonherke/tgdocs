![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management)[Next](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management)
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
  * Advanced Topics
  * [System Management](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/management-with-gadmin)
  * [Workload Management](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/3.11/modules/system-management/pages/workload-management.adoc)
### Contents
  * [Workload Queues](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_workload_queues)
  * [Configure Workload Queues](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_configure_workload_queues)
  * [List Workload Queues](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_list_workload_queues)
  * [Grant/Revoke Workload Queue Access](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_grantrevoke_workload_queue_access)
  * [Show Workload Queue Permissions](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_show_workload_queue_permissions)
  * [Check Queue Status](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_check_queue_status)
  * [Use Cases](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_use_cases)
  * [Other Query Workload Management Methods](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_other_query_workload_management_methods)
  * [Limit number of concurrent heavy queries](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_limit_number_of_concurrent_heavy_queries)
  * [Limit number of concurrent queries](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_limit_number_of_concurrent_queries)
  * [Specify replica to run query on](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_specify_replica_to_run_query_on)
  * [Query Routing Schemes](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_query_routing_schemes)
  * [Round Robin routing](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_round_robin_routing)
  * [CPU Load Aware Query Routing](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_cpu_load_aware_query_routing)


# Workload Management
### Contents
  * [Workload Queues](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_workload_queues)
  * [Configure Workload Queues](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_configure_workload_queues)
  * [List Workload Queues](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_list_workload_queues)
  * [Grant/Revoke Workload Queue Access](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_grantrevoke_workload_queue_access)
  * [Show Workload Queue Permissions](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_show_workload_queue_permissions)
  * [Check Queue Status](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_check_queue_status)
  * [Use Cases](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_use_cases)
  * [Other Query Workload Management Methods](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_other_query_workload_management_methods)
  * [Limit number of concurrent heavy queries](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_limit_number_of_concurrent_heavy_queries)
  * [Limit number of concurrent queries](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_limit_number_of_concurrent_queries)
  * [Specify replica to run query on](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_specify_replica_to_run_query_on)
  * [Query Routing Schemes](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_query_routing_schemes)
  * [Round Robin routing](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_round_robin_routing)
  * [CPU Load Aware Query Routing](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_cpu_load_aware_query_routing)


This page explains the different methods available to manage system workloads in TigerGraph.
In distributed or replicated clusters, users have multiple processing units at their disposal. Depending on their needs, they can configure [query routing schemes](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_query_routing_schemes) such as round-robin or CPU load-aware routing. For replicated clusters, queries can also be [directed to specific replicas](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_specify_replica_to_run_query_on).
## [](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_workload_queues)Workload Queues
Workload Queues help manage queries by routing them to predefined queues with specific configurations. Each queue can have properties like the maximum number of concurrent queries and delay queue size, preventing system overload. Queries can be assigned to queues based on user roles and permissions.
In 3.10, **workload queues** were introduced. Multiple independent queues can be configured, allowing application designers to decide how specific operations are handled.
Workload queues manage the following types of operations:
  * Running an installed query.
  * Interpreting ad-hoc queries.
  * Executing heavy built-in queries, commonly used for "Explore Graph" in GraphStudio.


### [](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_configure_workload_queues)Configure Workload Queues
Workload queues help control how queries are executed within the system by defining limits such as the maximum number of concurrent queries and the maximum size of the delay queue. Administrators can configure workload queues by creating, modifying, or deleting them as needed.
Each queue has the following properties:
Field | Description | Data type  
---|---|---  
`description` | The description of the queue. | `STRING` (< 256 characters)  
`isDefault` (optional) | The flag to indicate if the queue is the default queue. Must be set to `true` for exactly one queue. | `BOOL`  
`maxConcurrentQueries` | The maximum number of concurrent queries allowed in the queue. | `UINT` in the range of `(0, 131072)`  
`maxDelayQueueSize` | The maximum number of queries that can be queued in the delay queue. | `UINT` in the range of `[0, 131072)`  
#### [](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_maxconcurrentqueries_and_maxdelayqueuesize)maxConcurrentQueries and maxDelayQueueSize
`maxConcurrentQueries` and `maxDelayQueueSize` are enforced on per machine level. More specifically, it puts a limit on how many requests ONE `GPE` process can handle. For example, in a TigerGraph cluster with `4` nodes (there will be `4` `GPE` processes), the total number of qureies allowed for a `WorkloadQueue` is `4*maxConcurrentQueries`. Similarly, the total number of queries can be put into the corresponding delay queue is `4*maxDelayQueueSize`. TigerGraph internally would try to evenly distribute queries evenly among the nodes, hence, the `WorkloadQueue` from each `GPE` would be filled at a similar pace.
Before making changes, it’s a good practice to retrieve the current configuration using the **GET Workload Queue** command. After reviewing, you can update or apply new configurations using the **PUT Workload Queue** command. These commands are available both as GSQL commands and as REST endpoints.
**GSQL Commands**
  * **Retrieve Current Configuration:**


```
GET WORKLOAD QUEUE
```

  * **Update Configuration:**


```
PUT WORKLOAD QUEUE FROM "/path/to/queue.json"
```

**REST Endpoints**
  * **Retrieve Current Configuration:**


```
GET /gsqlserver/gsql/workload-manager/configs
```

  * **Configure Workload Queues**


```
POST /gsqlserver/gsql/workload-manager/configs
```

**Examples**
  1. **Retrieve Current Configuration:**


```
curl -X GET -u tigergraph:tigergraph \
 <hostname>:<nginx-port>/gsqlserver/gsql/workload-manager/configs
```

  1. **Modify Workload Queue Configuration:**


```
curl -X POST -u tigergraph:tigergraph \
<hostname>:<nginx-port>/gsqlserver/gsql/workload-manager/configs \
-d '{"isEnabled":true,"queues":{"OLTP":{"description":"OLTP queries","isDefault":false,"maxConcurrentQueries":100,"maxDelayQueueSize":200}}}'
```

**Response Status Codes**
**For GET Workload Queue**
Status Code | Description  
---|---  
200 | The queue configurations were successfully retrieved.  
403 | The user does not have the `READ_WORKLOAD_QUEUE` privilege.  
500 | Server error occurred while processing the request.  
**For PUT Workload Queue**
Status Code | Description  
---|---  
200 | The queue configurations were successfully uploaded.  
400 | The payload is ill-formed.  
403 | The user does not have the `WRITE_WORKLOAD_QUEUE` privilege.  
409 | Conflict in the configuration, such as multiple queues set as default.  
500 | Server error occurred while processing the request.  
**maxConcurrentQueries and maxDelayQueueSize** Each workload queue has two critical properties to manage system resources:
  1. **maxConcurrentQueries:** Defines the maximum number of queries that can run simultaneously in a queue. This helps prevent resource contention and ensures that the system does not become overloaded.
  2. **maxDelayQueueSize:** Specifies the maximum number of queries that can wait in a queue when the current workload exceeds the concurrent query limit. If this limit is reached, new queries are rejected until the queue has capacity.


Both properties are enforced at the per-machine level in a cluster. Setting the values too high may degrade performance. It’s recommended to keep `maxConcurrentQueries` below three times the number of physical CPU cores in a machine. Any configuration changes require a GPE restart to take effect.  
---  
### [](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_list_workload_queues)List Workload Queues
Displays a list of all workload queues available to the current user, including their configurations and permissions.
**GSQL Command**
```
LIST WORKLOAD QUEUE
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**REST Endpoints**
```
GET /restpp/workload-manager/queue
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**Example Request**
```
curl -X GET -u tigergraph:tigergraph \
 <hostname>:<nginx-port>/restpp/workload-manager/queue
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**Example Response** The response will include the information available to the general users.
```
[
 {
  "id": "AdHoc",
  "description": "Ad-hoc queries",
  "isDefault": true
 },
 {
  "id": "OLTP",
  "description": "OLTP queries"
 }
]
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**Response Status Codes**
Status Code | Description  
---|---  
200 | The queue info has been retrieved successfully.  
403 | The user doesn’t have the privilege `READ_DATA`.  
### [](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_grantrevoke_workload_queue_access)Grant/Revoke Workload Queue Access
You can grant or revoke workload queues to a user based on its user name, groups, and/or roles.
**GSQL Command**
```
# GRANT
GRANT WORKLOAD QUEUE <queue_name> TO USER <user1>, <user2>
# REVOKE
REVOKE WORKLOAD QUEUE <queue_name> FROM USER <user1>, <user2>
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**REST Endpoint**
```
POST /gsqlserver/gsql/workload-manager/permission
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**Request Body** The request body expects a JSON object with the following schema:
```
{
 "OLTP": {
  "granted": {
   "USER": []
   "GROUP": ["*"]
   "ROLE": ["r1", "r2"]
  }
 }
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The request body must have the following fields at the top level:
Field | Description | Data type  
---|---|---  
`action` | `GRANT` or `REVOKE` (case insensitive) | `STRING`  
`queue` | The ID of the queue to be granted or revoked. | `STRING`  
`user` (optional) | The list of the user names to be granted/revoked. | `STRING` or `STRING[]`  
`group` (optional) | The list of the group names to be granted/revoked. | `STRING` or `STRING[]`  
`role` (optional) | The list of the role names to be granted/revoked. | `STRING` or `STRING[]`  
  * You can use the wildcard " * " to grant/revoke the queue to all users, groups, or roles.
  * Note that " * " must be the only entry in the list when available.

  
---  
**Example Request**
Grant the queue `OLTP` to the user `u1` and `u2`:
```
curl -X GET -u tigergraph:tigergraph \
 <hostname>:<nginx-port>/gsqlserver/gsql/workload-manager/permission \
 -d '{"action": "grant", "queue": "OLTP", "user": ["u1", "u2"]}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Revoke the queue `scheduled_jobs` from all users and the role `r1`:
```
curl -X GET -u tigergraph:tigergraph \
 <hostname>:<nginx-port>/gsqlserver/gsql/workload-manager/permission \
 -d '{"action": "REVOKE" "queue": "scheduled_jobs", "user": "*", role": ["r1"]}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**Response Status Codes**
Status Code | Description  
---|---  
200 | The queue has been granted/revoked successfully.  
400 | The payload is ill-formed so none of the given entities could be granted/revoked.  
403 | The user doesn’t have the privilege `WRITE_WORKLOAD_QUEUE`  
Unlike REST API, the GSQL commands don’t allow you to specify USER, GROUP, and ROLE in a command. You must use separate commands for each entity type.  
---  
### [](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_show_workload_queue_permissions)Show Workload Queue Permissions
The `SHOW WORKLOAD QUEUE` command lists detailed information about workload queues, including their permissions, descriptions, and limits. It is primarily used to inspect queue settings and permissions.
**GSQL Command** To show the permission info of all queues:
```
SHOW WORKLOAD QUEUE
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

To show the permission info of a specific queue, for example `OLTP`:
```
SHOW WORKLOAD QUEUE OLTP
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**REST Endpoint**
```
GET /gsqlserver/gsql/workload-manager/permission
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**Example Request** To retrieve the permission info of the queue `OLTP`:
```
curl -X GET -u tigergraph:tigergraph \
 localhost:14240/gsql/v1/workload-manager/permission?id=OLTP
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**Example Response**
The response will be the combination of configs and permission, e.g.
```
{
 "OLTP": {
  "description": "OLTP queries",
  "isDefault": false,
  "maxConcurrentQueries": 100,
  "maxDelayQueueSize": 200,
  "granted": {
   "USER": [],
   "GROUP": ["*"],
   "ROLE": ["r1", "r2"]
  }
 }
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**Response Status Codes**
Status Code | Description  
---|---  
200 | The queue info has been retrieved successfully.  
403 | The user doesn’t have the privilege `READ_WORKLOAD_QUEUE`.  
  * Use `SHOW WORKLOAD QUEUE` to inspect queue configurations and access permissions.
  * This command focuses on **visibility of queue settings** , unlike `GET WORKLOAD QUEUE`, which exports configurations.

  
---  
### [](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_check_queue_status)Check Queue Status
You can use the following API to check the status of the workload queues for monitoring purposes.
```
POST /restpp/workload-manager/queuestatus
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Return the status of the given workload queue on each GPE instance.
**Request Body**
Field | Description | Data type  
---|---|---  
queuelist (optional) | The list of the ID of the WorkloadQueue. If not specified, all queues will be shown. | `STRING[]`  
mode (optional) | `stats` or `verbose` (case-sensitive). If not specified, `stats` will be used. | `STRING`  
For `mode` field, if `stats` is specified, response only gives the numbers of queries waiting and running. If `verbose` is specified, the response will include the the request Ids of the queries that are waiting and running.
If Request Body is not provided, response is generated as if both fields are using the default values.
**Example Request**
```
curl -X POST -u tigergraph:tigergraph \
 <hostname>:<nginx-port>/restpp/workload-manager/queuestatus \
  -d '{"queuelist": ["AdHoc"], "mode": "verbose"}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**Example Response**
```
{
 "version": {
  "edition": "enterprise",
  "api": "v2",
  "schema": 0
 },
 "error": false,
 "message": "Completes",
 "WorkloadQueueStatusByInstances": [
  {
   "version": {
    "edition": "enterprise",
    "api": "v2",
    "schema": 0
   },
   "error": false,
   "message": "",
   "results": {
    "GPE_2_1": [
     {
      "WorkloadQueueName": "AdHoc",
      "maxConcurrentQueries": 1,
      "maxDelayQueueSize": 2,
      "runningQueries": [
       "196702.RESTPP_1_1.1707799387957.N"
      ],
      "delayQueries": [
       "65630.RESTPP_1_1.1707799387958.N"
      ]
     }
    ]
   }
  },
  {
   "version": {
    "edition": "enterprise",
    "api": "v2",
    "schema": 0
   },
   "error": false,
   "message": "",
   "results": {
    "GPE_1_1": [
     {
      "WorkloadQueueName": "AdHoc",
      "maxConcurrentQueries": 1,
      "maxDelayQueueSize": 2,
      "runningQueries": [
       "94.RESTPP_1_1.1707799387957.N"
      ],
      "delayQueries": [
       "131167.RESTPP_1_1.1707799387959.N"
      ]
     }
    ]
   }
  }
 ],
 "code": "REST-0000"
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_use_cases)Use Cases
Suppose we have configured the following workload queues that are the output of the `SHOW WORKLOAD QUEUE` command:
```
{
 "OLTP": {
  "description": "OLTP queries",
  "isDefault": true,
  "maxConcurrentQueries": 100,
  "maxDelayQueueSize": 100,
  "granted": {
   "USER": [],
   "GROUP": ["g1", "g2"],
   "ROLE": []
  }
 },
 "scheduled_jobs": {
  "description": "Scheduled jobs",
  "maxConcurrentQueries": 5,
  "maxDelayQueueSize": 0,
  "granted": {
   "USER": ["u1"],
   "GROUP": [],
   "ROLE": ["r1"]
  }
 },
 "AdHoc": {
  "description": "Ad-hoc queries",
  "isDefault": false,
  "maxConcurrentQueries": 10,
  "maxDelayQueueSize": 10,
  "granted": {
   "USER": [],
   "GROUP": ["g3"],
   "ROLE": ["r2"]
  }
 }
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**Running a Query**
When running a query, you can specify the workload queue to run the query on. If the queue is not specified, the query will be routed to the default queue. To specify the queue in the GSQL shell, you can use the `-queue` option, e.g.
```
RUN QUERY -queue AdHoc q1()
```

or you can use the HTTP header `Workload-Queue`:
```
curl -X POST -u tigergraph:tigergraph \
 -H "Workload-Queue: AdHoc" \
 <hostname>:14240/restpp/query/ldbc_snb/q1"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

If the given queue is not granted to the current user, the query will be rejected with the error code `REST-14000` and return `HTTP 422 Unprocessable Entity`.
For example, if the user `tigergraph` who does not belong to the group `g3` or holds the role `r2` tries to run a query on the queue `AdHoc`, the query will be rejected.
If the queue is full of capacity, the query will be rejected.  
---  
## [](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_other_query_workload_management_methods)Other Query Workload Management Methods
### [](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_limit_number_of_concurrent_heavy_queries)Limit number of concurrent heavy queries
This configuration is deprecated as of TG 3.10.0 and will be removed in a future release. This is ignored once the [workload queue](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_workload_queue) feature is enabled.   
---  
TigerGraph has a few built-in queries that are memory-intensive, here referred to as "heavy". These queries tend to be invoked by applications such as GraphStudio. You can set a limit of how many of these heavy queries are allowed to run concurrently by configuring the parameter `RESTPP.WorkLoadManager.MaxHeavyBuiltinQueries` with the [`gadmin config` command](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/management-commands#_gadmin_config).
For example, to set the maximum number of heavy built-in queries to 10, run the following command:
```
$ gadmin config set RESTPP.WorkLoadManager.MaxHeavyBuiltinQueries 10
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

You must [restart the RESTPP service](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/manage-services#_start_stop_or_restart_a_service) for the change to take effect.
### [](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_limit_number_of_concurrent_queries)Limit number of concurrent queries
This configuration is deprecated as of TG 3.10.0 and will be removed in a future release. This is ignored once the [workload queue](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_workload_queue) feature is enabled.   
---  
You can use the `RESTPP.WorkLoadManager.MaxConcurrentQueries` parameter to set a limit of how many queries are allowed to be running concurrently. The count of these queries **does not include** the built-in heavy queries.
For example, to specify that there can only be 50 concurrent queries at a time, excluding the heavy built-in queries, change the value of the configuration parameter to 50 with the [`gadmin config` command](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/management-commands#_gadmin_config):
```
$ gadmin config set RESTPP.WorkLoadManager.MaxConcurrentQueries 50
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

If the maximum number of concurrent queries is reached, newly submitted queries are placed in a delay queue, and begin to run as the currently running queries finish. If the queue is at capacity, newly submitted queries are rejected. and you need wait until there is capacity to run the query again. You can adjust the size of the queue with the configuration parameter `RESTPP.WorkLoadManager.MaxDelayQueueSize`.
For example, to specify that a maximum 20 queries may remain in the queue, run the following command:
```
$ gadmin config set RESTPP.WorkLoadManager.MaxDelayQueueSize 20
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

You must [restart the RESTPP service](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/manage-services#_start_stop_or_restart_a_service) for the change to take effect.
### [](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_specify_replica_to_run_query_on)Specify replica to run query on
On a distributed cluster, you can specify on which replica you want a query to be run through the [Run Query REST endpoint](https://docs.tigergraph.com/tigergraph-server/4.2/API/built-in-endpoints#_run_an_installed_query_post).
For example, to run the query on the primary cluster, use the `GSQL-REPLICA` header when running a query and set its value to 1:
Specify that the query run on the primary cluster
```
curl -X POST -H "GSQL-REPLICA: 1" -d '{"p":{"id":"Tom","type":"person"}}'
"http://localhost:14240/restpp/query/social/hello"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_query_routing_schemes)Query Routing Schemes
In a distributed or replicated cluster, REST++ automatically routes queries to different GPEs, in order to spread the workload.
If [GSQL-REPLICA](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_specify_replica_to_run_query_on) header is used when invoking a query, this header overrides the routing scheme for that query.   
---  
### [](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_round_robin_routing)Round Robin routing
The default query routing scheme is round-robin. The first query is managed by GPE 0, the next query by GPE 1, and so on. After the last GPE, the cycle returns to GPE 0.
Version 3.9.3 adds a system configuration parameter `RESTPP.CPULoadAware.Mode` to enable system administrators to select other query routing schemes:
  * Mode = 0 (default): Round-Robin
  * Mode = 1: CPU Load Aware


### [](https://docs.tigergraph.com/tigergraph-server/3.11/system-management/workload-management#_cpu_load_aware_query_routing)CPU Load Aware Query Routing
When this query routing mode is selected, REST++ tries to direct incoming queries to the GPEs that are currently less busy.
Specifically, the system periodically polls CPU usage data to find a GPE whose CPU usage percentage is below `RESTPP.QueryRouting.TargetSelectionCPUThreshold` (default 50).
If no GPE satisfies the CPU threshold condition, REST++ falls back to the default behavior (round-robin selection).
Example: Change CPU Load Threshold and Enable CPU Load Aware routing
```
$ gadmin config entry RESTPP.QueryRouting.TargetSelectionCPUThreshold 40
$ gadmin config entry RESTPP.QueryRouting.Mode 1
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


