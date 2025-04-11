![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints)[Next](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints)
[Developer Site](https://dev.tigergraph.com/) [Community Forum](https://community.tigergraph.com/) [Knowledge Base](https://tigergraph.freshdesk.com/support/solutions)
[Download](https://dl.tigergraph.com)
[ TG Savanna](https://savanna.tgcloud.io)
### [TigerGraph DB](https://docs.tigergraph.com/tigergraph-server/4.1/intro/)
  *     * [TigerGraph DB Release Notes](https://docs.tigergraph.com/tigergraph-server/4.1/release-notes/)
  *     * [Overview](https://docs.tigergraph.com/tigergraph-server/4.1/intro/)
    * [Get Started](https://docs.tigergraph.com/tigergraph-server/4.1/getting-started/)
      * Installation
        * [On Docker](https://docs.tigergraph.com/tigergraph-server/4.1/getting-started/docker)
        * [On Kubernetes](https://docs.tigergraph.com/tigergraph-server/4.1/getting-started/kubernetes)
        * [On Cloud Marketplace](https://docs.tigergraph.com/tigergraph-server/4.1/getting-started/cloud-images/)
          * [AWS](https://docs.tigergraph.com/tigergraph-server/4.1/getting-started/cloud-images/aws)
          * [Azure](https://docs.tigergraph.com/tigergraph-server/4.1/getting-started/cloud-images/azure)
          * [GCP](https://docs.tigergraph.com/tigergraph-server/4.1/getting-started/cloud-images/gcp)
        * [On Linux](https://docs.tigergraph.com/tigergraph-server/4.1/getting-started/linux)
          * [System Requirements](https://docs.tigergraph.com/tigergraph-server/4.1/installation/hw-and-sw-requirements)
          * [Linux On Bare Metal](https://docs.tigergraph.com/tigergraph-server/4.1/installation/bare-metal-install)
          * [Post Install Checks](https://docs.tigergraph.com/tigergraph-server/4.1/installation/post-install-check)
        * [Advanced License Issues](https://docs.tigergraph.com/tigergraph-server/4.1/installation/license)
        * [Changing Ports](https://docs.tigergraph.com/tigergraph-server/4.1/installation/change-port)
        * [Change IP or Hostname](https://docs.tigergraph.com/tigergraph-server/4.1/installation/change-ip-or-hostname)
        * [Upgrade](https://docs.tigergraph.com/tigergraph-server/4.1/installation/upgrade)
        * [Uninstallation](https://docs.tigergraph.com/tigergraph-server/4.1/installation/uninstallation)
      * [The GSQL Shell](https://docs.tigergraph.com/tigergraph-server/4.1/gsql-shell/)
        * [GSQL Shell Sessions](https://docs.tigergraph.com/tigergraph-server/4.1/gsql-shell/gsql-sessions)
        * [Using a Remote GSQL Client](https://docs.tigergraph.com/tigergraph-server/4.1/gsql-shell/using-a-remote-gsql-client)
        * [GSQL Shell (Web)](https://docs.tigergraph.com/tigergraph-server/4.1/gsql-shell/web)
    * [Create Database](https://docs.tigergraph.com/tigergraph-server/4.1/getting-started/database-definition)
      * [MultiGraph Overview](https://docs.tigergraph.com/tigergraph-server/4.1/intro/multigraph-overview)
  *     * [Load Data](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/)
      * [Overview](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/data-loading-overview)
      * [Load from Local Files](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-local-files)
      * [Load from Cloud Storage](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-from-cloud)
      * [Load from Data Warehouse](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-from-warehouse)
      * [Load from External Kafka](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-from-kafka)
        * [Avro Data Validation through KafkaConnect](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/avro-validation-with-kafka)
        * [Kafka SSL Security Guide](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/kafka-ssl-security-guide)
      * [Load from Spark Dataframe](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-from-spark-dataframe)
      * [Read to Spark Dataframe](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/read-to-spark-dataframe)
      * [Externalize Kafka Configs](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/externalizing-kafka-configs)
      * [Manage Data Sources](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/manage-data-source)
      * [Data Loading V2 (Beta)](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/data-loading-v2)
      * [Stream from External Kafka (Deprecated)](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/data-streaming-connector/kafka)
  *     * Advanced Topics
      * [System Management](https://docs.tigergraph.com/tigergraph-server/4.1/system-management/management-with-gadmin)
        * [Memory management](https://docs.tigergraph.com/tigergraph-server/4.1/system-management/memory-management)
        * [Manage TigerGraph services](https://docs.tigergraph.com/tigergraph-server/4.1/system-management/manage-services)
        * [Workload Management](https://docs.tigergraph.com/tigergraph-server/4.1/system-management/workload-management)
        * [Metrics Reporting](https://docs.tigergraph.com/tigergraph-server/4.1/system-management/system-metrics)
        * [Command Glossary](https://docs.tigergraph.com/tigergraph-server/4.1/system-management/management-commands)
        * [Change Data Capture (CDC) Overview](https://docs.tigergraph.com/tigergraph-server/4.1/system-management/change-data-capture/cdc-overview)
          * [CDC Setup](https://docs.tigergraph.com/tigergraph-server/4.1/system-management/change-data-capture/cdc-setup)
          * [CDC Message Examples](https://docs.tigergraph.com/tigergraph-server/4.1/system-management/change-data-capture/cdc-message-example)
          * [CDC Monitoring and Reset](https://docs.tigergraph.com/tigergraph-server/4.1/system-management/change-data-capture/cdc-state-monitoring)
      * [Access Management](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/)
        * Authentication
          * [Enabling User Authentication](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/enabling-user-authentication)
          * [User Credentials](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/user-credentials)
          * [Single Sign-On](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/sso)
          * [Lightweight Directory Access Protocol (LDAP)](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/ldap)
          * [OIDC JWT Authentication](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token)
        * Authorization
          * [User Management](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/user-management)
          * [Access Control Model](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/access-control-model)
          * [Fine-Grained Query Privileges](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/fine-grained-query-privileges)
            * [Migrate Query Privileges from 3.x to 4.1](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/query-privilege-migration)
          * [Role Management](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/role-management)
          * [Row Policy Overview](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/row-policy-overview)
            * [Key Concepts](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/rbac-row-policy)
            * [Set Up Row Policy](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/setup-row-policy)
          * [Access Control Lists (ACLs) (Deprecated)](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/acl-management)
      * [Backup and Restore](https://docs.tigergraph.com/tigergraph-server/4.1/backup-and-restore/)
        * [Backup and Restore Configurations](https://docs.tigergraph.com/tigergraph-server/4.1/backup-and-restore/configurations)
        * [Back up a Database Cluster](https://docs.tigergraph.com/tigergraph-server/4.1/backup-and-restore/backup-cluster)
        * [Differential Backup](https://docs.tigergraph.com/tigergraph-server/4.1/backup-and-restore/differential-backups)
        * [Online Backup](https://docs.tigergraph.com/tigergraph-server/4.1/backup-and-restore/online-backup)
        * [Restore a Database Backup from the Same Cluster](https://docs.tigergraph.com/tigergraph-server/4.1/backup-and-restore/restore-backup-same)
        * [Restore a Database Backup from Another Cluster](https://docs.tigergraph.com/tigergraph-server/4.1/backup-and-restore/restore-cross-cluster)
        * [Point-in-Time Restore](https://docs.tigergraph.com/tigergraph-server/4.1/backup-and-restore/point-in-time-restore)
        * [Database Import/Export All Graphs](https://docs.tigergraph.com/tigergraph-server/4.1/backup-and-restore/database-import-export)
        * [Import/Export Individual Graphs](https://docs.tigergraph.com/tigergraph-server/4.1/backup-and-restore/single-graph-import-export)
        * [Legacy Backup and Restore](https://docs.tigergraph.com/tigergraph-server/4.1/backup-and-restore/gbar-legacy)
      * [Cluster and HA Management](https://docs.tigergraph.com/tigergraph-server/4.1/cluster-and-ha-management/)
        * Cluster Resizing
          * [Cluster Expansion](https://docs.tigergraph.com/tigergraph-server/4.1/cluster-and-ha-management/expand-a-cluster)
          * [Cluster Shrinking](https://docs.tigergraph.com/tigergraph-server/4.1/cluster-and-ha-management/shrink-a-cluster)
          * [Cluster Repartition](https://docs.tigergraph.com/tigergraph-server/4.1/cluster-and-ha-management/repartition-a-cluster)
          * [Cluster Replace](https://docs.tigergraph.com/tigergraph-server/4.1/cluster-and-ha-management/how_to-replace-a-node-in-a-cluster)
        * [Cross-Region Replication (CRR)](https://docs.tigergraph.com/tigergraph-server/4.1/cluster-and-ha-management/crr-index)
          * [Set up CRR](https://docs.tigergraph.com/tigergraph-server/4.1/cluster-and-ha-management/set-up-crr)
          * [Fail over to the DR cluster](https://docs.tigergraph.com/tigergraph-server/4.1/cluster-and-ha-management/fail-over)
          * [Troubleshooting CRR](https://docs.tigergraph.com/tigergraph-server/4.1/cluster-and-ha-management/troubleshooting)
          * [CRR FAQ](https://docs.tigergraph.com/tigergraph-server/4.1/cluster-and-ha-management/crr-faq)
        * [High Availability (HA)](https://docs.tigergraph.com/tigergraph-server/4.1/cluster-and-ha-management/ha-overview)
          * [Cluster Configuration](https://docs.tigergraph.com/tigergraph-server/4.1/cluster-and-ha-management/ha-cluster)
          * [Region Aware Cluster Configuration](https://docs.tigergraph.com/tigergraph-server/4.1/cluster-and-ha-management/region-aware)
          * [GSQL Server HA](https://docs.tigergraph.com/tigergraph-server/4.1/cluster-and-ha-management/ha-for-gsql-server)
          * [Application Server HA](https://docs.tigergraph.com/tigergraph-server/4.1/cluster-and-ha-management/ha-for-application-server)
          * [Cluster Commands](https://docs.tigergraph.com/tigergraph-server/4.1/cluster-and-ha-management/cluster-commands)
          * [Removal of Failed Nodes](https://docs.tigergraph.com/tigergraph-server/4.1/cluster-and-ha-management/remove-failed-node)
      * [Architecture](https://docs.tigergraph.com/tigergraph-server/4.1/intro/internal-architecture)
        * [MultiGraph Overview](https://docs.tigergraph.com/tigergraph-server/4.1/intro/multigraph-overview)
        * [Transaction Processing and ACID Support](https://docs.tigergraph.com/tigergraph-server/4.1/intro/transaction-and-acid)
        * [Continuous Availability Overview](https://docs.tigergraph.com/tigergraph-server/4.1/intro/continuous-availability-overview)
      * [Kubernetes](https://docs.tigergraph.com/tigergraph-server/4.1/kubernetes/)
        * [Kubernetes Operator](https://docs.tigergraph.com/tigergraph-server/4.1/kubernetes/k8s-operator/)
  *     * [Security](https://docs.tigergraph.com/tigergraph-server/4.1/security/)
      * [Auditing Privileged User Actions](https://docs.tigergraph.com/tigergraph-server/4.1/security/audit-privileged-actions)
      * [Encrypting Connections](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-connections)
      * [Encrypting Data At Rest](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest)
      * [File Input Policy](https://docs.tigergraph.com/tigergraph-server/4.1/security/gsql-file-input-policy)
      * [File Output Policy](https://docs.tigergraph.com/tigergraph-server/4.1/security/file-output-policy)
      * [Login Policy](https://docs.tigergraph.com/tigergraph-server/4.1/security/login-protection)
      * [Password Policy](https://docs.tigergraph.com/tigergraph-server/4.1/security/password-policy)
  *     * [REST API Reference](https://docs.tigergraph.com/tigergraph-server/4.1/API/)
      * [GSQL Endpoints](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints)
      * [RESTPP & Infra Endpoints](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints)
      * [Upsert Data](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest)
  *     * Additional Resources
      * [Best Practices](https://docs.tigergraph.com/tigergraph-server/4.1/additional-resources/best-practice-guides/best-practices-overview)
        * [Scaling Guide](https://docs.tigergraph.com/tigergraph-server/4.1/additional-resources/best-practice-guides/best-prac-scaling-clusters)
      * Troubleshooting and FAQs
        * [Knowledge base and FAQs](https://kb.tigergraph.com/)
        * [Troubleshooting Guide](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/troubleshooting-guide)
        * [System Administration FAQs](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/system-administration-faqs)
        * [Log Files](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/log-files)
          * [Audit Logs](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log)
          * [Gathering Log Information with gcollect](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/gcollect)
          * [Set up Log Viewing with Elasticsearch, Kibana and Filebeat](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/elk-filebeat)
      * References
        * [Configuration Parameters](https://docs.tigergraph.com/tigergraph-server/4.1/reference/configuration-parameters)
        * [Return codes](https://docs.tigergraph.com/tigergraph-server/4.1/reference/return-codes)
        * [Object-Based Privilege Tables](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/row-policy-privileges-table)
        * [List of Legacy Privilege Syntax](https://docs.tigergraph.com/tigergraph-server/4.1/reference/list-of-privileges)
        * [List of Ports](https://docs.tigergraph.com/tigergraph-server/4.1/reference/ports)
        * [Glossary](https://docs.tigergraph.com/tigergraph-server/4.1/reference/glossary)
        * [Patents and Third Party Software](https://docs.tigergraph.com/tigergraph-server/4.1/reference/patents-and-third-party-software)
        * [Legacy Version Documentation](https://docs.tigergraph.com/tigergraph-server/4.1/additional-resources/legacy-tg-versions)
        * [Comparing TigerGraph Editions](https://docs.tigergraph.com/tigergraph-server/4.1/intro/comparison-of-editions)
        * [Release and Patch Process](https://docs.tigergraph.com/tigergraph-server/4.1/intro/release-process)
        * [RBAC Row Policy EBNF](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/row-policy-ebnf)


TigerGraph DB 4.1
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
  * [TigerGraph DB 4.1](https://docs.tigergraph.com/tigergraph-server/4.1/intro/)
  * [REST API Reference](https://docs.tigergraph.com/tigergraph-server/4.1/API/)
  * [RESTPP & Infra Endpoints](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/4.1/modules/API/pages/built-in-endpoints.adoc)
### Contents
  * [System Utilities](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_system_utilities)
  * [Echo](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_echo)
  * [Health check (public)](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_health_check_public)
  * [List all endpoints](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_list_all_endpoints)
  * [Show component versions](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_show_component_versions)
  * [Monitor system metrics (OpenMetrics format)](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_monitor_system_metrics_openmetrics_format)
  * [Monitor system metrics by category](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_monitor_system_metrics_by_category)
  * [Show query performance](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_show_query_performance)
  * [Show service status](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_show_service_status)
  * [Rebuild graph engine](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_rebuild_graph_engine)
  * [Check deleted vertices](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_deleted_vertex_check)
  * [Authentication](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_authentication)
  * [Remove expired tokens](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_remove_expired_tokens)
  * [Loading jobs](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_loading_jobs)
  * [Run a Loading Job](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_run_a_loading_job)
  * [Graphs](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_graphs)
  * [Run built-in functions on graph](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_run_built_in_functions_on_graph)
  * [Show graph schema metadata](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_show_graph_schema_metadata)
  * [Upsert data to graph](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_upsert_data_to_graph)
  * [Clear the graph store](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_clear_the_graph_store)
  * [Vertices](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_vertices)
  * [Insert vertices](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_insert_vertices)
  * [List vertices](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_list_vertices)
  * [Retrieve a vertex](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_retrieve_a_vertex)
  * [Delete vertices](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_delete_vertices)
  * [Delete vertices by type](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_delete_vertices_by_type)
  * [Delete a vertex](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_delete_a_vertex)
  * [Edges](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_edges)
  * [Insert edges](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_insert_edges)
  * [List edges of a vertex](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_list_edges_of_a_vertex)
  * [List edges of a vertex by edge type](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_list_edges_of_a_vertex_by_edge_type)
  * [List edges of a vertex by edge type and target type](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_list_edges_of_a_vertex_by_edge_type_and_target_type)
  * [Retrieve edge by source, target, and edge type](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_retrieve_edge_by_source_target_and_edge_type)
  * [Retrieve edge by source, target, edge type, and discriminator](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_retrieve_edge_by_source_target_edge_type_and_discriminator)
  * [Delete one or more edges by source, target, and edge type](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_delete_one_or_more_edges_by_source_target_and_edge_type)
  * [Delete an edge by source, target, edge type and discriminator](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_delete_an_edge_by_source_target_edge_type_and_discriminator)
  * [Queries](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_queries)
  * [Get query metadata](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_get_query_metadata)
  * [Install a query](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_install_a_query)
  * [Check query installation status](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_check_query_installation_status)
  * [Run an installed query (GET)](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_run_an_installed_query_get)
  * [Run an installed query (POST)](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_run_an_installed_query_post)
  * [Run an interpreted query](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_run_an_interpreted_query)
  * [List running queries of a graph](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_list_running_queries_of_a_graph)
  * [List all running queries](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_list_all_running_queries)
  * [Show all delayed queries](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_show_all_delayed_queries)
  * [Abort a query](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_abort_a_query)
  * [Check query status (Detached Mode)](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_check_query_status_detached_mode)
  * [Check query results (Detached Mode)](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_check_query_results_detached_mode)
  * [Get information about a template query](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_get_information_about_a_template_query)
  * [Run a template query](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_run_a_template_query)
  * [Data Consistency Check](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_data_consistency_check)
  * [Path-Finding Algorithms](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_path_finding_algorithms)
  * [Input Parameters and Output Format for Path-Finding](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_input_parameters_and_output_format_for_path_finding)
  * [Find shortest path](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_find_shortest_path)
  * [Find all paths](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_find_all_paths)


# RESTPP and Informant Built-in Endpoints
Table of Contents
  * [System Utilities](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_system_utilities)
    * [Echo](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_echo)
    * [Health check (public)](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_health_check_public)
    * [List all endpoints](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_list_all_endpoints)
    * [Show component versions](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_show_component_versions)
    * [Monitor system metrics (OpenMetrics format)](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_monitor_system_metrics_openmetrics_format)
    * [Monitor system metrics by category](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_monitor_system_metrics_by_category)
    * [Show query performance](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_show_query_performance)
    * [Show service status](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_show_service_status)
    * [Rebuild graph engine](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_rebuild_graph_engine)
    * [Check deleted vertices](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_deleted_vertex_check)
  * [Authentication](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_authentication)
    * [Remove expired tokens](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_remove_expired_tokens)
  * [Loading jobs](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_loading_jobs)
    * [Run a Loading Job](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_run_a_loading_job)
  * [Graphs](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_graphs)
    * [Run built-in functions on graph](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_run_built_in_functions_on_graph)
    * [Show graph schema metadata](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_show_graph_schema_metadata)
    * [Upsert data to graph](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_upsert_data_to_graph)
    * [Clear the graph store](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_clear_the_graph_store)
  * [Vertices](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_vertices)
    * [Insert vertices](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_insert_vertices)
    * [List vertices](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_list_vertices)
    * [Retrieve a vertex](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_retrieve_a_vertex)
    * [Delete vertices](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_delete_vertices)
    * [Delete vertices by type](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_delete_vertices_by_type)
    * [Delete a vertex](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_delete_a_vertex)
  * [Edges](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_edges)
    * [Insert edges](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_insert_edges)
    * [List edges of a vertex](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_list_edges_of_a_vertex)
    * [List edges of a vertex by edge type](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_list_edges_of_a_vertex_by_edge_type)
    * [List edges of a vertex by edge type and target type](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_list_edges_of_a_vertex_by_edge_type_and_target_type)
    * [Retrieve edge by source, target, and edge type](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_retrieve_edge_by_source_target_and_edge_type)
    * [Retrieve edge by source, target, edge type, and discriminator](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_retrieve_edge_by_source_target_edge_type_and_discriminator)
    * [Delete one or more edges by source, target, and edge type](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_delete_one_or_more_edges_by_source_target_and_edge_type)
    * [Delete an edge by source, target, edge type and discriminator](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_delete_an_edge_by_source_target_edge_type_and_discriminator)
  * [Queries](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_queries)
    * [Get query metadata](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_get_query_metadata)
    * [Install a query](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_install_a_query)
    * [Check query installation status](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_check_query_installation_status)
    * [Run an installed query (`GET`)](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_run_an_installed_query_get)
    * [Run an installed query (`POST`)](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_run_an_installed_query_post)
    * [Run an interpreted query](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_run_an_interpreted_query)
    * [List running queries of a graph](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_list_running_queries_of_a_graph)
    * [List all running queries](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_list_all_running_queries)
    * [Show all delayed queries](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_show_all_delayed_queries)
    * [Abort a query](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_abort_a_query)
    * [Check query status (Detached Mode)](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_check_query_status_detached_mode)
    * [Check query results (Detached Mode)](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_check_query_results_detached_mode)
    * [Get information about a template query](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_get_information_about_a_template_query)
    * [Run a template query](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_run_a_template_query)
    * [Data Consistency Check](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_data_consistency_check)
  * [Path-Finding Algorithms](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_path_finding_algorithms)
    * [Input Parameters and Output Format for Path-Finding](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_input_parameters_and_output_format_for_path_finding)
    * [Find shortest path](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_find_shortest_path)
    * [Find all paths](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_find_all_paths)


This page is an updated version of the REST API endpoints which were avaiable in TigerGraph 3.x. TigerGraph 4.1+ adds many new endpoints to the GSQL server which were not available in TigerGraph 3.x. For these new endpoints, see [GSQL Endpoints](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints).
REST Server Ports For all TigerGraph Cloud solutions created on or after June 20, 2022, use port 443 for REST endpoints. In 4.1.0 and later versions, for all TigerGraph Server solutions not on TigerGraph Cloud, port 9000 is no longer exposed. Please use port 14240 instead.  
---  
## [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_system_utilities)System Utilities
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_echo)Echo
`GET restpp/echo` `POST restpp/echo`
These endpoints are simple diagnostic utilities, which respond with the following message if the RESTPP server is up and running.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_sample_request)Sample request:
GET /echo Request and Response
```
curl -X GET "http://localhost:14240/restpp/echo"
{
  "error": false,
  "message": "Hello GSQL"
}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

`POST /echo` has the same response as `GET /echo`.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters)Parameters:
Name | Required | Description  
---|---|---  
`sleep` | No | Integer that indicates the number of seconds for which the response will be delayed.  
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_health_check_public)Health check (public)
`GET /api/ping`
This endpoint performs a simple server health check. It listens on port 14240 and does not require authentication. If you ping it and the server is running, it will respond with the message "pong".
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_sample_request_2)Sample request:
```
curl 'http://localhost:14240/api/ping'
{
 "error": "false",
 "message": "pong",
 "results": {}
}
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_2)Parameters:
None
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_list_all_endpoints)List all endpoints
`GET /restpp/endpoints/{graph_name}`
This endpoint returns a list of the installed endpoints and their parameters. There are three types of endpoints:
  * _Built-in endpoints_ which are preinstalled in the TigerGraph system
  * _Dynamic endpoints_ which are generated when compiling GSQL queries
  * _Static endpoints_ which are user-installed endpoints


To include one or more of the endpoint types in the output, include the endpoint type in the parameter query string and set its value to `true`. If no type parameters are provided, all endpoints are returned.
Example: Report on all built-in endpoints
```
curl -X GET "http://localhost:14240/restpp/endpoints?builtin=true" | jq .
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_response)Response
There are over a dozen built-in endpoints, and some have several parameters, so the formatted JSON output of all built-in endpoints is over 300 lines long. It is listed in full in Appendix A. Below is a small excerpt of the output:
Subset of GET /endpoints output
```
  "GET /endpoints": {
    "parameters": {
      "builtin": {
        "default": "false",
        "max_count": 1,
        "min_count": 0,
        "type": "BOOL"
      },
      "dynamic": {
        "default": "false",
        "max_count": 1,
        "min_count": 0,
        "type": "BOOL"
      },
      "static": {
        "default": "false",
        "max_count": 1,
        "min_count": 0,
        "type": "BOOL"
      }
    }
  }
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_3)Parameters:
Name | Required | Description  
---|---|---  
`builtin` | No | Takes a boolean value. Returns built-in endpoints if true.  
`dynamic` | No | Takes a boolean value. Returns dynamic endpoints if true.  
`static` | No | Takes a boolean value. Returns user-installed endpoints if true.  
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_show_component_versions)Show component versions
`GET /restpp/version`
This endpoint returns the Git versions of all components of the system.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_example)Example 

Request
    
```
curl -X GET "http://localhost:14240/restpp/version"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Response
    
```
{"error":"false", "message":"TigerGraph RESTPP:
 --- Version ---
product       release_2.6.0_05-09-2020 ab1e3d0da6237c27468d6cabb90900119d63759d 2020-04-15 15:46:29 -0700
olgp         release_2.6.0_05-09-2020 046c745088106b69920b9bdb3bd15969de409e92 2020-05-01 19:10:27 -0700
topology       release_2.6.0_05-09-2020 c028af100117f2051b619436c3aa4febc810bf36 2020-04-22 08:44:07 -0700
gpe         release_2.6.0_05-09-2020 34b9e86ef7b5fdaa106637e7db1d8a9e080a0aa2 2020-04-19 09:42:59 -0700
gse         release_2.6.0_05-09-2020 ed2c2351357aa9077fa4dee7ea7a01f8ad2f7585 2020-05-11 01:18:54 -0700
third_party     release_2.6.0_05-09-2020 4bce6990bae5be2b91e9201693ceb66341d3f204 2020-04-19 09:42:56 -0700
utility       release_2.6.0_05-09-2020 2ce197d3edb3557bdd66ed1a4194309908d6197e 2020-04-20 21:19:34 -0700
realtime       release_2.6.0_05-09-2020 52a82b454437c73b47d846acd5803ab0d9f54a45 2020-04-22 08:44:11 -0700
er          release_2.6.0_05-09-2020 a3e6cb7606fb74984c75cae9bbd4d2112fdbf73a 2020-05-01 19:10:33 -0700
gle         release_2.6.0_05-09-2020 d8bdbd1cf346e181aa9a317c704dd7b3b11b4658 2020-05-06 00:51:04 -0700
bigtest       release_2.6.0_05-09-2020 2f64c47b7a5ac1834ead9a22eef8d42241117853 2019-12-12 01:31:35 -0800
document       release_2.6.0_05-09-2020 6327094bd76b2dbc8f4625108d547827344b5091 2019-12-13 16:30:13 -0800
glive        release_2.6.0_05-09-2020 93f61ea06fe42759c808fc58ff6245c9954d5447 2020-02-05 22:40:24 -0800
gap         release_2.6.0_05-09-2020 e798efb595545bf91c449034566857c41f52449a 2020-04-29 22:47:26 -0700
gst         release_2.6.0_05-09-2020 1b695c02f277efad0ddfb2deab710ae0158409da 2020-04-29 22:47:32 -0700
gus         release_2.6.0_05-09-2020 eee784502b5387844e462305bae419954784da6f 2020-04-29 22:47:20 -0700
blue_features    release_2.6.0_05-09-2020 5d7a4e8d806519f529274b331496d3bc78f01990 2020-04-15 15:46:38 -0700
blue_commons     release_2.6.0_05-09-2020 432763afc49bf986aed4731e50254243d3665bc3 2019-07-30 03:34:46 -0700
"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_monitor_system_metrics_openmetrics_format)Monitor system metrics (OpenMetrics format)
`GET /informant/metrics` `POST /informant/metrics`
**Server** : Informant
This endpoint returns system metrics regarding CPU usage, memory usage, network usage, diskspace, service status, or engine QPS data in OpenMetrics format, allowing you to integrate this endpoint with observability platforms such as Datadog or Prometheus.
Metrics are updated every 60 seconds by default. This interval can be adjusted with the [`System.Metrics` parameters](https://docs.tigergraph.com/tigergraph-server/4.1/reference/configuration-parameters).
This endpoint does not require any privileges.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_total_and_available_capacity)Total and Available Capacity
Beginning with Version 3.10.2, the metrics output will include additional information, about both the total and the available (unallocated) amount of CPU and memory capacity, per node. This is in addition to the information about how much is currently being used.
For example:
```
# HELP tigergraph_cpu_available Percentage of available CPU capacity
# TYPE tigergraph_cpu_available gauge
tigergraph_cpu_available{host_id="m1",service_name=""} 98.2397232055664
# HELP tigergraph_cpu_logical_cores_total Total number of logical CPU cores of a node
# TYPE tigergraph_cpu_logical_cores_total gauge
tigergraph_cpu_logical_cores_total{host_id="m1",service_name=""} 8
# HELP tigergraph_cpu_available Percentage of available CPU capacity
# TYPE tigergraph_cpu_available gauge
tigergraph_cpu_available{host_id="m1",service_name=""} 98.2397232055664
# HELP tigergraph_cpu_logical_cores_total Total number of logical CPU cores of a node
# TYPE tigergraph_cpu_logical_cores_total gauge
tigergraph_cpu_logical_cores_total{host_id="m1",service_name=""} 8
```

The total number of CPU logical cores and the available memory are included in the summary section.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_including_the_host_name)Including the Host Name
As of verison 3.10.1, if the configuration parameter `System.Metrics.IncludeHostName` is set to `true`, the hostname/ip will be included in all metrics output, in OpenMetrics format, as part of the variable labels.
Otherwise, the default is `false` and the response will not include hostname/ip as part of the variable labels.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_4)Parameters:
None
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_sample_request_3)Sample request:
  * Request
  * Response


```
$ curl "http://localhost:14240/informant/metrics"
```

```
# HELP tigergraph_cpu_available Percentage of available CPU capacity
# TYPE tigergraph_cpu_available gauge
tigergraph_cpu_available{host_id="m1",service_name=""} 98.2397232055664
# HELP tigergraph_cpu_logical_cores_total Total number of logical CPU cores of a node
# TYPE tigergraph_cpu_logical_cores_total gauge
tigergraph_cpu_logical_cores_total{host_id="m1",service_name=""} 8
# HELP tigergraph_cpu_usage Percentage of CPU usage by component. Service name empty means usage of the whole node
# TYPE tigergraph_cpu_usage gauge
tigergraph_cpu_usage{host_id="m1",service_name=""} 1.7602790594100952
tigergraph_cpu_usage{host_id="m1",service_name="ADMIN"} 0.04377374425530434
tigergraph_cpu_usage{host_id="m1",service_name="CTRL"} 0.03333035483956337
tigergraph_cpu_usage{host_id="m1",service_name="DICT"} 0.02717098779976368
tigergraph_cpu_usage{host_id="m1",service_name="ETCD"} 0.06599369645118713
tigergraph_cpu_usage{host_id="m1",service_name="EXE"} 0.3078765571117401
tigergraph_cpu_usage{host_id="m1",service_name="GPE"} 0.057431410998106
tigergraph_cpu_usage{host_id="m1",service_name="GSQL"} 0.42731526494026184
tigergraph_cpu_usage{host_id="m1",service_name="GUI"} 0.0015482305316254497
tigergraph_cpu_usage{host_id="m1",service_name="IFM"} 0.06652917712926865
tigergraph_cpu_usage{host_id="m1",service_name="KAFKA"} 0.7873504757881165
tigergraph_cpu_usage{host_id="m1",service_name="KAFKACONN"} 0.6024601459503174
tigergraph_cpu_usage{host_id="m1",service_name="KAFKASTRM-LL"} 0.26026034355163574
tigergraph_cpu_usage{host_id="m1",service_name="NGINX"} 0
tigergraph_cpu_usage{host_id="m1",service_name="RESTPP"} 0.848330557346344
tigergraph_cpu_usage{host_id="m1",service_name="ZK"} 0.08272281289100647
# HELP tigergraph_diskspace_free Free Disk space in megabytes by directory.
# TYPE tigergraph_diskspace_free gauge
tigergraph_diskspace_free{host_id="m1",mount_point="/",path="/home/tigergraph",path_name="Home"} 59276.48828125
tigergraph_diskspace_free{host_id="m1",mount_point="/",path="/home/tigergraph/tigergraph/data/gstore",path_name="Gstore"} 59276.4921875
tigergraph_diskspace_free{host_id="m1",mount_point="/",path="/home/tigergraph/tigergraph/data/kafka",path_name="Kafka"} 59276.4921875
tigergraph_diskspace_free{host_id="m1",mount_point="/",path="/home/tigergraph/tigergraph/log",path_name="Log"} 59276.484375
# HELP tigergraph_diskspace_usage Disk usage in megabytes by directory.
# TYPE tigergraph_diskspace_usage gauge
tigergraph_diskspace_usage{host_id="m1",mount_point="/",path="/home/tigergraph",path_name="Home"} 47280.34765625
tigergraph_diskspace_usage{host_id="m1",mount_point="/",path="/home/tigergraph/tigergraph/data/gstore",path_name="Gstore"} 0
tigergraph_diskspace_usage{host_id="m1",mount_point="/",path="/home/tigergraph/tigergraph/data/kafka",path_name="Kafka"} 0.85546875
tigergraph_diskspace_usage{host_id="m1",mount_point="/",path="/home/tigergraph/tigergraph/log",path_name="Log"} 4.1015625
# HELP tigergraph_memory_available Memory available in megabytes for programs to allocate
# TYPE tigergraph_memory_available gauge
tigergraph_memory_available{host_id="m1",service_name=""} 26603
# HELP tigergraph_memory_total Total memory of the node in megabytes
# TYPE tigergraph_memory_total gauge
tigergraph_memory_total{host_id="m1",service_name=""} 32092
# HELP tigergraph_memory_usage Memory usage in megabytes by component. Service name empty means usage of the whole node
# TYPE tigergraph_memory_usage gauge
tigergraph_memory_usage{host_id="m1",service_name=""} 4555
tigergraph_memory_usage{host_id="m1",service_name="ADMIN"} 55
tigergraph_memory_usage{host_id="m1",service_name="CTRL"} 39
tigergraph_memory_usage{host_id="m1",service_name="DICT"} 48
tigergraph_memory_usage{host_id="m1",service_name="ETCD"} 26
tigergraph_memory_usage{host_id="m1",service_name="EXE"} 44
tigergraph_memory_usage{host_id="m1",service_name="GPE"} 127
tigergraph_memory_usage{host_id="m1",service_name="GSQL"} 891
tigergraph_memory_usage{host_id="m1",service_name="GUI"} 33
tigergraph_memory_usage{host_id="m1",service_name="IFM"} 36
tigergraph_memory_usage{host_id="m1",service_name="KAFKA"} 428
tigergraph_memory_usage{host_id="m1",service_name="KAFKACONN"} 564
tigergraph_memory_usage{host_id="m1",service_name="KAFKASTRM-LL"} 334
tigergraph_memory_usage{host_id="m1",service_name="NGINX"} 4
tigergraph_memory_usage{host_id="m1",service_name="RESTPP"} 340
tigergraph_memory_usage{host_id="m1",service_name="ZK"} 95
# HELP tigergraph_network_connections Number of open TCP connections.
# TYPE tigergraph_network_connections gauge
tigergraph_network_connections{host_id="m1"} 202
# HELP tigergraph_network_traffic Network traffic in bytes since the service started.
# TYPE tigergraph_network_traffic gauge
tigergraph_network_traffic{direction="incoming",host_id="m1"} 1.2802625793e+10
tigergraph_network_traffic{direction="outgoing",host_id="m1"} 1.00515261e+08
# HELP tigergraph_service_status Tigergraph service status. Partiton or replica empty means no partition or replica for that service.
# TYPE tigergraph_service_status gauge
tigergraph_service_status{partition="",replica="1",service_name="ADMIN"} 6
tigergraph_service_status{partition="",replica="1",service_name="CTRL"} 6
tigergraph_service_status{partition="",replica="1",service_name="DICT"} 6
tigergraph_service_status{partition="",replica="1",service_name="ETCD"} 6
tigergraph_service_status{partition="",replica="1",service_name="GSQL"} 6
tigergraph_service_status{partition="",replica="1",service_name="GUI"} 6
tigergraph_service_status{partition="",replica="1",service_name="IFM"} 6
tigergraph_service_status{partition="",replica="1",service_name="KAFKA"} 6
tigergraph_service_status{partition="",replica="1",service_name="KAFKACONN"} 6
tigergraph_service_status{partition="",replica="1",service_name="NGINX"} 6
tigergraph_service_status{partition="",replica="1",service_name="RESTPP"} 6
tigergraph_service_status{partition="",replica="1",service_name="ZK"} 6
tigergraph_service_status{partition="1",replica="",service_name="EXE"} 6
tigergraph_service_status{partition="1",replica="",service_name="KAFKASTRM-LL"} 6
tigergraph_service_status{partition="1",replica="1",service_name="GPE"} 9
tigergraph_service_status{partition="1",replica="1",service_name="GSE"} 27
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_monitor_system_metrics_by_category)Monitor system metrics by category
`POST /informant/metrics/get/{metrics_category}`
**Server** : Informant
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_path_parameters)Path Parameters
`{metrics_category}` is one of the following: (`cpu-memory`, `diskspace` , `network`, `qps`)
`qps` means "queries per second".
The output will be in JSON format.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_input_filter)Input Filter
A filter to limit the output may be provided as a JSON-formatted payload (e.g., by using the `curl -d` option). The filtering options are different for each metrics category. The filter may include any or all of the supported fields, which are described below.
Filter template for `/informant/metrics/get/cpu-memory`
```
{
 "ServiceDescriptors": [
   {
    "ServiceName": "<service_name>",
    "Partition": <partition_number (int32)>,
    "Replica": <replica_number (int32)>
   }
   ... **(1)**
  ],
  "TimeRange":{
   "StartTimestampNS": "<time in nanoseconds (string)>",
   "EndTimestampNS": "<time in nanoseconds (string)>"
  },
  "HostID": "<the node ID, such as m1 or m2>",
  "CPUUsage": <return all metrics with CPU usage greater than this value in percent (float)>,
  "MemoryUsage": <return all metrics with memory usage greater than this value in megabytes (int32)>,
  "LatestNum": <the number of items per serviceID to return, most recent first (int32)>
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | List additional services, as needed.  
---|---  
[3.9.2] The query payload for CPU and memory usage has changed from having a single ServiceDescriptor to having a list of ServiceDescriptors.   
---  
Filter template for `/informant/metrics/get/diskspace`
```
{
 "TimeRange": {
  "StartTimestampNS": "<time in nanoseconds (string)>",
  "EndTimestampNS": "<time in nanoseconds (string)>"
 },
 "PathName": "<either log, kafka, gstore, or home>",
 "HostID": "<the node ID, such as m1 or m2>",
 "LatestNum": <the number of items per serviceID to return, most recent first (int32)>
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Filter template for `/informant/metrics/get/network`
```
{
 "TimeRange": {
  "StartTimestampNS": "<time in nanoseconds (string)>",
  "EndTimestampNS": "<time in nanoseconds (string)>"
 },
 "HostID": "<the node ID, such as m1 or m2>",
 "LatestNum": <the number of items per serviceID to return, most recent first (int32)>
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Filter template for `/informant/metrics/get/qps`
```
{
 "TimeRange": {
  "StartTimestampNS": "<time in nanoseconds (string)>",
  "EndTimestampNS": "<time in nanoseconds (string)>"
 },
 "ServiceDescriptor": {
  "ServiceName": "<service_name>",
  "Partition": <partition_number (int32)>,
  "Replica": <replica_number (int32)>
 },
 "HostID": "<the node ID, such as m1 or m2>",
 "LatestNum": <the number of items per serviceID to return, most recent first (int32)>
 "Endpoint": "<endpoint URL>"
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_examples)Examples
Get disk space report from host `m2`
```
curl -X POST localhost:14240/informant/metrics/get/diskspace -d '{"HostID":"m2"}'
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Get a network usage report with the two most recent items
```
curl -X POST localhost:14240/informant/metrics/get/network -d '{"LatestNum":"2"}'
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Get a CPU and memory report for the GSE service with partition and replica number specified
```
curl -X POST localhost:14240/informant/metrics/get/cpu-memory -d '{"ServiceDescriptors":[{"ServiceName":"gse","Partition": 1,"Replica":1}]}'
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The Service Status request returns a map of the following service codes:
```
ServiceStatus_value = map[string]int32{
"StatusUnchanged": 0,
"StatusUnknown":  3,
"Online":     6,
"Warmup":     9,
"Readonly":    12,
"Starting":    15,
"Paused":     18,
"Stopping":    21,
"Offline":     24,
"Down":      27,
}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_show_query_performance)Show query performance
`GET /restpp/statistics/{graph_name}`
This endpoint returns real-time query performance statistics over the given time period, as specified by the `seconds` parameter. Seconds are measured up to 60, so the `seconds` parameter must be a positive integer less than or equal to 60.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_sample_request_4)Sample request:
The return object is a hash of the endpoints and their performance data.
This example shows two endpoints (`/graph/vertex` and `/statistics`) called during the past 60 seconds.
  * Request
  * Response


```
curl -X GET "http://localhost:14240/restpp/statistics/poc_graph?seconds=60" | jq '.'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
{
 "GET /graph/vertices/{vertex_type}/{vertex_id}": {
  "CompletedRequests": 8,
  "QPS": 0.08,
  "TimeoutRequests": 0,
  "AverageLatency": 130,
  "MaxLatency": 133,
  "MinLatency": 128,
  "LatencyPercentile": [
   200,
   200,
   200,
   200,
   200,
   200,
   200,
   200,
   200,
   200
  ]
 },
 "GET /statistics": {
  "CompletedRequests": 4226,
  "QPS": 42.26,
  "TimeoutRequests": 0,
  "AverageLatency": 2,
  "MaxLatency": 125,
  "MinLatency": 0,
  "LatencyPercentile": [
   10,
   10,
   10,
   10,
   10,
   10,
   10,
   10,
   10,
   200
  ]
 }
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Each endpoint has the following attributes:
  * `CompletedRequests` - the number of completed requests.
  * `QPS` - query per second.
  * `TimeoutRequests` - the number of requests not returning before the system-configured timeout limit. Timeout requests are not included in the calculation of QPS.
  * `AverageLatency` - the average latency of completed requests.
  * `MaxLatency` - the maximum latency of completed requests.
  * `MinLatency` - the minimum latency of completed requests.
  * `LatencyPercentile` - The latency distribution. The number of elements in this array depends on the `segments` parameter of this endpoint whose default value is 10, meaning the percentile range 0-100% will be divided into ten equal segments: 0%-10%, 11%-20%, etc. `Segments` must be between 1 and 100.


If there is no query sent in the past given seconds, an empty json will be returned.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_5)Parameters:
Name | Required | Description  
---|---|---  
`seconds` | Yes | Positive integer less than 60 that indicates how many seconds back from the current time the statistics report will cover.  
`segments` | No | Integer that indicates the number of segments that the `LatencyPercentile` array in the response will be split into. The value for this endpoint must be between 1 and 100. The default value is 10.  
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_show_service_status)Show service status
`POST /informant/current-service-status`
**Server** : informant
This endpoint returns the status of the TigerGraph services specified in the request.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_6)Parameters:
None
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_request_body)Request body:
The endpoint requires a request body in the following format:
```
{
  "ServiceDescriptors": [ **(1)**
    {
      "ServiceName": <service_name>, **(2)**
      "Partition": <partition_number>, **(3)**
      "Replica": <replica_number> **(4)**
    }
    ... **(5)**
  ]
}
javascript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | `ServiceDescriptors` is a required field. It is a list of objects with keys `ServiceName`, and optionally `Partition` and `Replica`.  
---|---  
**2** | Required field. The name of the service to return status on. Below are the accepted values for the field and their corresponding services: 
  * `"GPE"`: GPE
  * `"GSE"`: GSE
  * `"RESTPP"`: RESTPP
  * `"GSQL"`: GSQL
  * `"IFM"`: INFORMANT
  * `"GUI"`: GUI
  * `"CTRL"`: CONTROLLER
  * `"KAFKA"`: KAFKA
  * `"ETCD"`: ETCD
  * `"ZK"`: ZOOKEEPER
  * `"NGINX"`: NGINX
  * `"DICT"`: DICT
  * `"ADMIN"`: ADMIN

  
**3** | Optional. Number of the partition to request service status on. If not provided, the response will contain service status on all partitions.  
**4** | Optional. Number of the replica to request service status on. If not provided, the response will contain service status on all replicas.  
**5** | You can supply more than one service descriptor. The response from the endpoint will contain all service status requested.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_return_value)Return value
The return value contains the status for every service descriptor in the request. The most important information is in the `ServiceStatus` and `ProcessState` fields:
```
{
 "ServiceStatusEvents": [
  {
   "EventMeta": {
    "Targets": [
     {
      "ServiceName": "IFM"
     }
    ],
    "EventId": "154e8f53716b403eb02af19d863745c6",
    "SpanId": "ServiceStatusSelfReport",
    "TimestampNS": "1635841759229416893",
    "Source": {
     "ServiceName": "GPE",
     "Replica": 1,
     "Partition": 2
    }
   },
   "ServiceDescriptor": { **(1)**
    "ServiceName": "GPE",
    "Replica": 1,
    "Partition": 2
   },
   "ServiceStatus": "Online", **(2)**
   "ProcessState": "Running" **(3)**
  }
 ]
}
javascript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | The service descriptor for the status being returned.  
---|---  
**2** | The last recorded status of the service.  
**3** | The last recorded state of the Linux process behind the service. It’s possible for a process to be running without being served or able to respond to requests. For example, when TigerGraph is starting up, GPE is in the "Warmup" state and cannot respond to requests, but the process is still running.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_example_2)Example
  * Request
  * Response


```
curl -X POST http://localhost:14240/informant/current-service-status -d '{ "ServiceDescriptors": [{ "ServiceName": "gpe","Partition": 2, "Replica": 1}]}' | jq
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
{
 "ServiceStatusEvents": [
  {
   "EventMeta": {
    "Targets": [
     {
      "ServiceName": "IFM"
     }
    ],
    "EventId": "154e8f53716b403eb02af19d863745c6",
    "SpanId": "ServiceStatusSelfReport",
    "TimestampNS": "1635841759229416893",
    "Source": {
     "ServiceName": "GPE",
     "Replica": 1,
     "Partition": 2
    }
   },
   "ServiceDescriptor": {
    "ServiceName": "GPE",
    "Replica": 1,
    "Partition": 2
   },
   "ServiceStatus": "Online",
   "ProcessState": "Running"
  }
 ]
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_rebuild_graph_engine)Rebuild graph engine
`GET /restpp/rebuildnow/{graph_name}` `POST /restpp/rebuildnow/{graph_name}`
[**Required privilege**](https://docs.tigergraph.com/tigergraph-server/4.2/reference/list-of-privileges): Graph-level READ DATA
When new data is being loaded into the graph (such as new vertices or edges), data is first stored in memory before it is saved to disk permanently. TigerGraph runs a rebuild of the Graph Processing Engine (GPE) to commit the data in memory to disk every 30 seconds, but you can also call this endpoint to trigger a rebuild immediately.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_7)Parameters:
Name | Required | Description  
---|---|---  
`threadnum` | No | Number of threads used to execute the rebuild. If not specified, the number specified in the `.tg.cfg` file (`"RebuildThreadNumber"`) in the home directory of the server on which TigerGraph is running will be used; it is set to 3 by default. The maximum value for this parameter is the number of vCPUs per node in your distributed system. If you are running a single-node server, the maximum is the number of vCPUs on that node. You can run `lscpu` in your Linux server command line and look in the `CPU(s)` column to view the number of vCPUs.  
`vertextype` | No | Vertex type to perform the rebuild for. If not provided, the rebuild will be run for all the vertex types.  
`segid` | No | Segment ID of the segments to rebuild. If not provided, all segments will be rebuilt. In general, it is recommended not to provide this parameter and rebuild all segments.  
`path` | No | Path to save the summary of the rebuild to. If not provided, the default path is `/tmp/rebuildnow`  
`force` | No | Boolean value that indicates whether to perform rebuilds for segments for which there are no records of new data. Normally, a rebuild would skip such segments, but if `force` is set true, the segments will not be skipped.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_example_3)Example
```
curl -X GET 'http://localhost:14240/restpp/rebuildnow/social'

# JSON response
{
 "version": {
  "edition": "enterprise",
  "api": "v2",
  "schema": 0
 },
 "error": false,
 "message": "RebuildNow finished, please check details in the folder: /tmp/rebuildnow",
 "results": [],
 "code": "REST-0000"
}

# Example summary file
cat finished.summary.txt
[SELECTED]	Segment id: 106, vertextype: 0, vertexsubtypeid: 0, vertexcount: 187732, edgecount: 563196, deletevertexcount: 0, postqueue_pos: 16344, transaction id: 16344, rebuild ts: 1573106412990
[SKIPPED]	Segment id: 6, vertextype: 0, vertexsubtypeid: 0, vertexcount: 85732, edgecount: 3106, deletevertexcount: 0, postqueue_pos: 16344, transaction id: 16344, rebuild ts: 1573106412900
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_deleted_vertex_check)Check deleted vertices
`GET /restpp/deleted_vertex_check`
[**Required privilege**](https://docs.tigergraph.com/tigergraph-server/4.2/reference/list-of-privileges): Graph-level READ DATA
In certain rare cases, TigerGraph’s Graph Processing Engine (GPE) and Graph Storage Engine (GSE) might be out of sync on vertex deletion information. When this happens, some vertices might exist on one of the components, but not the other. Even though these errors are exceedingly rare, TigerGraph provides an endpoint that allows you to check the deleted vertices on GSE and GPE to see if they are out of sync.
The check passes if there are no discrepancies between the GSE and GPE in terms of deleted vertices. If there is a discrepancy, the check fails and the return result will contain the IDs of the deleted vertices that are not synced properly. If you are running TigerGraph on a distributed cluster, the check will be performed on each node of the cluster, and the endpoint will return a list containing the results of the check for every node.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_8)Parameters:
Name | Required | Description  
---|---|---  
`threadnum` | No |  Integer that indicates the number of threads used to execute the deleted vertex check jobs. The default value is 6.  
`segid` | No |  IDs of segments to perform the deleted vertex check for. If none is provided, the check will be performed on all segments.  
`vertextype` | No |  Vertex types to perform the deleted vertex check for. If none is provided, the check will be performed on all vertex types.  
`verbose` | No |  Integer that indicates the level of detail in the return results. Here is a list of accepted values and their corresponding level of detail:
  * `0` (default) : Only return whether the check passed and the list of unsynced vertex IDs
  * `1`: In addition to the previous level, also return vertex count information
  * `2`: In addition to the previous level, return vertex count information for every segment
  * `4`: In addition to the previous level, also return the IDs of deleted vertices for every segment

  
`log` | No |  Integer that indicates the log level of the deleted vertex check. This log is not returned in the endpoint’s HTTP response, but is printed to the logs of the GPE component at `/tigergraph/log/gpe/log.INFO`
  * `0` (default): Report brief log for the check as a whole
  * `1`: Report logs for each segment
  * `2`: Report additional logs on the obtained deleted ID list

  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_example_4)Example:
```
# Passing check performed on a single-node database
curl -X GET "http://localhost:14240/restpp/deleted_vertex_check?threadnum=10&verbose=0" |jq .
{
 "version": {
  "edition": "enterprise",
  "api": "v2",
  "schema": 0
 },
 "error": false,
 "message": "check passed",
 "results": [
  {
   "GPE": "GPE_1_1",
   "PassCheck": true,
   "UnSyncList": []
  }
 ],
 "code": "REST-0000"
}
# Failed check performed on a distributed cluster
curl -X GET 'http://localhost:14240/restpp/deleted_vertex_check?threadnum=10&verbose=0&vertextype=region' |jq .
{
 "version": {
  "edition": "enterprise",
  "api": "v2",
  "schema": 0
 },
 "error": false,
 "message": "check failed",
 "results": [
  {
   "GPE": "GPE_2_1",
   "PassCheck": false,
   "UnSyncList": [
    {
     "Segid": 193,
     "IsRemote": false,
     "VertexType": "region",
     "GPEDelHash": 7013042118817697000,
     "IDSDelHash": 202375168
    }
   ]
  },
  {
   "GPE": "GPE_3_1",
   "PassCheck": false,
   "UnSyncList": [
    {
     "Segid": 193,
     "IsRemote": true,
     "VertexType": "region",
     "GPEDelHash": 7013042118817697000,
     "IDSDelHash": 202375168
    }
   ]
  },
  {
   "GPE": "GPE_1_1",
   "PassCheck": false,
   "UnSyncList": [
    {
     "Segid": 193,
     "IsRemote": true,
     "VertexType": "region",
     "GPEDelHash": 7013042118817697000,
     "IDSDelHash": 202375168
    }
   ]
  }
 ],
 "code": "REST-0000"
}
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_authentication)Authentication
As of 4.1.0, the use of plaintext tokens in authentication is deprecated. Use `/gsql/v1/tokens` trough 14240 port instead, refer to [GSQL Endpoints](https://docs.tigergraph.com/tigergraph-server/4.2/API/gsql-endpoints) instead.  
---  
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_remove_expired_tokens)Remove expired tokens
`DELETE /expiredtoken`
**Server** : GSQL
This endpoint removes expired authentication tokens. A user is always allowed to remove their own expired tokens. If a user tries to delete tokens that belong to other users, they need to have [the `WRITE_USER` privilege](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/access-control-model#_privileges).
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_sample_request_5)Sample request:
The following request deletes all expired tokens. This request requires the privilege `WRITE_USER`:
```
curl -X DELETE "https://localhost:14240/expiredtoken"
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The following request deletes all expired tokens that belong to users `u1` and `u2` as well as all tokens created with secrets `s1` and `s2`. This request requires the privilege `WRITE_USER`
```
curl -X DELETE 'localhost:14240/expiredtoken' -d '{"user":["u1","u2"],"secret":["s1","s2"]}'
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_request_body_2)Request body:
The request body is optional. If not provided a request body, a request deletes all expired tokens.
```
{
  "user": ["string"], **(1)**
  "secret": ["string"] **(2)**
}
javascript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | Users whose expired tokens to remove. Optional.  
---|---  
**2** | If a token is created with one of the secrets in the list, they are removed by the request. Optional.  
The secrets and users provided in the request body do not have to correlate with each other. A request deletes all tokens associated with any of the users and secrets contained in the payload.
The request is atomic: if any of the provided users or secrets are invalid, or if a user doesn’t have the privilege to remove tokens that belong to one of the users or secrets provided, no tokens will be removed by the request.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_9)Parameters:
None
## [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_loading_jobs)Loading jobs
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_run_a_loading_job)Run a Loading Job
`POST /restpp/ddl/{graph_name}`
[**Required privilege**](https://docs.tigergraph.com/tigergraph-server/4.2/reference/list-of-privileges): Graph-level EXECUTE_LOADINGJOB
This endpoint is for loading data into a graph. It submits data as an HTTP request payload, to be loaded into the graph by the DDL Loader. The data payload can be formatted as generic CSV or JSON. For more details, please see [GSQL Language Reference Part 1 - Defining Graphs and Loading Data](https://docs.tigergraph.com/gsql-ref/4.1/basics/system-and-language-basics).
If the loading job references multiple files, multiple HTTP requests are needed to complete the loading job since you can only provide data for one filename variable at a time. The loading job will skip the `LOAD` statements referencing filename variables that the request didn’t provide data for.
To provide data for a filename variable, put the data in the request body and use the `filename` parameter (explained in the parameter table below) to match the variable name defined in the loading job.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_request_body_3)Request body:
The request body is the data to be loaded (either in CSV or JSON format).
Curl allows you to read the data from an input file by using the @ symbol:
`curl -X POST --data-binary @./company.csv "http://…"`
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_sample_request_6)Sample request:
In this example, the loading job is dependent on three filename variables (`f1` and `f3`) and one filepath string. Therefore, three HTTP requests are needed to complete the loading job.
```
# Loading job
CREATE LOADING JOB load_data for GRAPH poc_graph {
  DEFINE FILENAME f1;
  DEFINE FILENAME f3;
  LOAD f1 to VERTEX person VALUES ($0, $0);
  LOAD "/home/data/company.csv" to VERTEX company VALUES ($0, $0);
  LOAD f3 to EDGE work_at VALUES ($0, $1, $3, $4, $5);
}
# Provide data for for the second LOAD statement
curl -X POST --data-binary @./another_company.csv "http://localhost:14240/restpp/ddl/poc_graph?tag=load_data&filename=__GSQL_FILENAME_0__" | jq
{
 "version": {
  "edition": "enterprise",
  "api": "v2",
  "schema": 0
 },
 "error": false,
 "message": "",
 "results": [
  {
   "sourceFileName": "Online_POST",
   "statistics": {
    "validLine": 7927,
    "rejectLine": 0,
    "failedConditionLine": 0,
    "notEnoughToken": 0,
    "invalidJson": 0,
    "oversizeToken": 0,
    "vertex": [
     {
      "typeName": "company",
      "validObject": 7,
      "noIdFound": 0,
      "invalidAttribute": 0,
      "invalidPrimaryId": 0,
      "invalidSecondaryId": 0,
      "incorrectFixedBinaryLength": 0
     }
    ],
    "edge": [],
    "deleteVertex": [],
    "deleteEdge": []
   }
  }
 ],
 "code": "REST-0000"
}
# Provide data for filename f1 for the first LOAD statement
curl -X POST --data-binary @./person.csv "http://localhost:14240/restpp/ddl/poc_graph?tag=load_data&filename=f1"
# Provide data for filename f3 for the third LOAD statement
curl -X POST --data-binary @./work_at.csv "http://localhost:14240/restpp/ddl/poc_graph?tag=load_data&filename=f3"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_10)Parameters:
Name | Required | Description  
---|---|---  
`tag` | Yes | Loading job name defined in your DDL loading job  
`filename` | Yes | File variable name or file path for the file containing the data  
`header` | No | If the value is true, the first line of the data file is a header line and will not be loaded as data. The default is false.  
`sep` | No | Separator of CSV data. If your data is JSON, you do not need to specify this parameter. The default separator is a comma`","`  
`eol` | No | End-of-line character. Only one or two characters are allowed, except for the special case "\r\n". The default value is `"\n"`  
`ack` | No | `"all"`: request will return after all GPE instances have acknowledged the `POST` request. `"none"`: request will return immediately after RESTPP processed the `POST` request.  
`timeout` | No | Timeout in seconds. If set to 0, use system-wide endpoint timeout setting.  
`concise` | No | Boolean value that indicates whether to return concise results of the data loading request. Concise results will only include the number of vertices and edges added or deleted, and will omit information such as the number of valid and invalid lines in the default response.  
If there are special characters in your parameter values, the special characters should use [URL encoding](https://www.w3schools.com/tags/ref_urlencode.asp). To avoid confusion about whether you should you one or two backslashes, we do not support backslash escapes for the `eol` or `sep` parameter.
The maximum size of data you can upload via this endpoint is controlled by the [`Nginx.ClientMaxBodySize`](https://docs.tigergraph.com/tigergraph-server/4.1/API/#_request_body_size) configuration parameter (default is 200 MB).
## [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_graphs)Graphs
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_run_built_in_functions_on_graph)Run built-in functions on graph
`POST /restpp/builtins/{graph_name}`
This endpoint runs a set of built-in functions and returns relevant statistics about a graph.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_request_body_4)Request body:
This endpoint expects a data payload in the request body that specifies which function to run on the graph. Depending on the function being run, different fields may also be expected in the request body.
Here is a list of functions supported by this endpoint and their corresponding data payload format.
  * `stat_vertex_attr`
    * Returns the minimum, maximum, and average values of the given vertex type’s `int`, `uint`, `float` and `double` attributes, and the count of `true` and `false` of a boolean attribute.
    * Data payload fields:
      * `"function": "stat_vertex_attr"`: This specifies that the function to run is `stat_vertex_attr`.
      * `"type"`: The vertex type whose attribute values to report on. Required field. It also accepts the wildcard value `*`, in which case, all vertex types are included.
  * `stat_edge_attr`
    * Returns the minimum, maximum, and average values of the given edge type’s `int`, `uint`, `float` and `double` attributes, and the count of `true` and `false` of a boolean attribute.
    * Data payload fields:
      * `"function": stat_edge_attr`
      * `"type"`: The edge type whose attribute values to report on. Required field. It also accepts the wildcard value `*` , in which case all edge types are included.
      * `"from_type"`: Optional. The source vertex type of the edges to report on.
      * `"to_type"`: Optional. The target vertex type of the edges to report on.
  * `stat_vertex_number`
    * Returns the number of vertices of the given vertex type.
    * Data payload fields:
      * `"function"`: `"stat_vertex_number"`
      * `"type"`: Required field. The vertex type of the vertices to count. It also accepts the wildcard value `*`, in which case, all vertex types are included.
  * `stat_edge_number`
    * Returns the number of edges of the given edge type
    * Data payload fields:
      * `"function": "stat_edge_number"`
      * `"type"`: Required field. The edge type of the edges to count. It also accepts the wildcard value `*`.
      * `"from_type"`: Optional. The source vertex type of the edges to report on.
      * `"to_type"`: Optional. The target vertex type of the edges to report on.


#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_sample_requests)Sample requests:
Below is an example request running `stat_vertex_attr` on `socialNet` and its output. The vertex type `"Person"` has a `uint` attribute `"age"`.
```
curl -X POST "http://localhost:14240/restpp/builtins/socialNet" \
-d '{"function":"stat_vertex_attr","type":"Person"}' | jq .
{
 "version": {
   "api": "v2",
   "schema": 0
  },
 "error": false,
 "message": "",
 "results": [
  {
   "vertexName": "Person",
   "attributeStat": [
    {
     "vattrName": "age",
     "MAX": 64,
     "MIN": 15,
     "AVG": 36.5
    }
   ]
  }
 ]
}
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Here is an example request running `stat_edge_attr` on `socialNet` and its output. The edge type `"Liked"` has a float attribute `"strength"`.
```
curl -X POST "http://localhost:14240/restpp/builtins/socialNet" \
-d '{"function":"stat_edge_attr","type":"Liked", "from_type":"*", "to_type":"*"}' | jq .
{
 "version": {
  "api": "v2",
  "schema": 0
 },
 "error": false,
 "message": "",
 "results": [
  {
   "e_type": "Liked",
   "attributes": {
    "weight": {
     "MAX": 2.5,
     "MIN": 1,
     "AVG": 1.375
    }
   }
  }
 ]
}
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Here is an example request running `stat_vertex_number` and its output.
```
curl -X POST "http://localhost:14240/restpp/builtins/socialNet" \
-d '{"function":"stat_vertex_number","type":"*"}' | jq .
{
 "version": {
  "api": "v2",
  "schema": 0
 },
 "error": false,
 "message": "",
 "results": [
  {
   "v_type": "User",
   "count": 4
  },
  {
   "v_type": "Page",
   "count": 4
  },
  {
   "v_type": "Product",
   "count": 7
  },
  {
   "v_type": "DescWord",
   "count": 7
  },
  {
   "v_type": "NameUser",
   "count": 9
  },
  {
   "v_type": "VidUser",
   "count": 4
  },
  {
   "v_type": "Video",
   "count": 5
  },
  {
   "v_type": "AttributeTag",
   "count": 4
  }
 ]
}
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_11)Parameters:
Name | Required | Default value | Description  
---|---|---|---  
`realtime` | No | False | Force built-in functions to rerun queries instead of using cached data, which is resource-intensive but more accurate if the graph is frequently updated.  
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_show_graph_schema_metadata)Show graph schema metadata
`GET /gsql/v1/schema`
**Server** : GSQL
The endpoint returns schema details about a vertex type, an edge type, or the entire graph schema. Authentication credentials need to be provided.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_sample_request_7)Sample request:
```
curl -u tigergraph:tigergraph \
"localhost:14240/gsql/v1/schema?graph=workNet&type=company"
{
 "error": false,
 "message": "",
 "results": {
  "Config": {
   "STATS": "OUTDEGREE_BY_EDGETYPE",
   "PRIMARY_ID_AS_ATTRIBUTE": false
  },
  "Attributes": [
   {
    "AttributeType": {
     "Name": "STRING"
    },
    "IsPartOfCompositeKey": false,
    "PrimaryIdAsAttribute": false,
    "AttributeName": "id",
    "HasIndex": false,
    "IsPrimaryKey": false
   },
   {
    "AttributeType": {
     "Name": "STRING"
    },
    "IsPartOfCompositeKey": false,
    "PrimaryIdAsAttribute": false,
    "AttributeName": "country",
    "HasIndex": false,
    "IsPrimaryKey": false
   }
  ],
  "PrimaryId": {
   "AttributeType": {
    "Name": "STRING"
   },
   "IsPartOfCompositeKey": false,
   "PrimaryIdAsAttribute": false,
   "AttributeName": "clientId",
   "HasIndex": false,
   "IsPrimaryKey": false
  },
  "Name": "company"
 }
}
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**Vertex schema object fields:**
  * **`Name`**: the vertex type name, same as the input parameter "type"
  * **`PrimaryId`**: details about the primary id
  * **`Attributes`**: details about each attribute, listed in order
  * **`Config`**: details about global properties of the vertex type


**Edge schema object fields:**
  * **`Name`**: the edge type name, same as the input parameter "type"
  * **`FromVertexTypeName`**: source vertex type name
  * **`ToVertexTypeName`**: target vertex type name
  * **`Attributes`**: details about each attribute, listed in order
  * **`IsDirected`**: whether the edge is directed
  * **`Config`**: additional details about global properties of the edge type


**Graph schema object fields:**
  * **`GraphName`**: the graph name, same as the input parameter "graph"
  * **`VertexTypes`**: an array of _vertex schema objects_. Each vertex schema object is exactly the JSON output if that specific vertex type had been specified.
  * **`EdgeTypes`**: an array of _edge schema objects_. Each edge schema object is exactly the JSON output if that specific edge type had been specified.


```
{
 "error": false,
 "message": "",
 "results": {
  "GraphName": "workNet",
  "VertexTypes": [
   {
    "Config": {...},
    "Attributes": [...],
    "PrimaryId": {...},
    "Name": "person"},
   {
    "Config": {...},
    "Attributes": [...],
    "PrimaryId": {...},
    "Name": "company"}
  ],
  "EdgeTypes": [
   {
    "IsDirected": false,
    "ToVertexTypeName": "company",
    "Config": {},
    "Attributes": [...],
    "FromVertexTypeName": "person",
    "Name": "worksFor"
   }
  ]
 }
}
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_12)Parameters:
Name | Required | Description  
---|---|---  
`graph` | Yes | The name of the graph whose schema to retrieve.  
`type` | No | The vertex or edge type whose details to retrieve. If not provided, the endpoint will provide a _graph schema object_ containing the schema details of the entire graph.  
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_upsert_data_to_graph)Upsert data to graph
The endpoint for upserting data to graph is more complicated than most other REST endpoints and is documented on a separate page. See [Upsert data to graph](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest).
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_clear_the_graph_store)Clear the graph store
`GET /gsql/v1/clear-store`
**Server** : GSQL-Server
[**Required privilege**](https://docs.tigergraph.com/tigergraph-server/4.2/reference/list-of-privileges): Global-level CLEAR_GRAPHSTORE
This endpoint is available in v3.9.2+.
This endpoint permanently deletes all the data out of the graph store (database), for all graphs. It does not delete the database schema, nor does it delete queries or loading jobs. It is equivalent to the GSQL command [CLEAR GRAPH STORE](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/running-a-loading-job#_clear_graph_store).
This operation is not reversible. The deleted data cannot be recovered.  
---  
## [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_vertices)Vertices
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_insert_vertices)Insert vertices
To insert vertices or edges, use the [Upsert data to graph](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest) endpoint.
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_list_vertices)List vertices
`GET /restpp/graph/{graph_name}/vertices/{vertex_type}`
This endpoint returns all vertices having the type `vertex_type` in a graph.
This endpoint requires the [`READ_DATA` privilege](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/access-control-model#_data_crud_privileges) on the vertex type.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_sample_request_8)Sample request:
  * Request
  * Response


```
curl -X GET "http://localhost:14240/restpp/graph/socialNet/vertices/User"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
{
 "version": {
  "api": "v2",
  "schema": 0
 },
 "error": false,
 "message": "",
 "results": [
  {
   "v_id": "id1",
   "v_type": "User",
   "attributes": {}
  },
  {
   "v_id": "id2",
   "v_type": "User",
   "attributes": {}
  }
  // ... all vertices in graph socialNet of type User
 ]
}
javascript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_13)Parameters:
Name | Required | Description  
---|---|---  
`count_only` | No | Takes a boolean value. If the value is true, the `results` field will only contain the count of how many vertices were selected. Default is `false`.  
`select` | No | Attributes of the selected vertices to return. The parameter takes a list, which is a string of comma-separated values, and will only return the attributes that are provided.  
`filter` | No | Conditions used to filter the returned vertices. The parameter takes a list of conditions, which is a string of comma-separated values. If any filter conditions are provided, the endpoint will only return the vertices that satisfy the conditions. Six comparison operators are supported for this parameter: `=`, `!=`, `>`, `>=`, `<` and `<=`. If the value on the right side of an operator is a string literal, it should be enclosed in double-quotes.  
`limit` | No | Integer value that specifies the total number of vertices to return  
`sort` | No | Attributes to sort the results by. The parameter takes a list, which is a string of comma-separated values, and will sort the returned vertices based on the attributes provided in the list in order. Add "-" in front of the attribute to sort in descending order.  
`timeout` | No | Integer that specifies the number of seconds after which the query will time out. If the parameter is set to 0 or isn’t provided, the system-wide endpoint timeout setting is applied.  
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_retrieve_a_vertex)Retrieve a vertex
`GET /restpp/graph/{graph_name}/vertices/{vertex_type}/{vertex_id}`
This endpoint returns a single vertex by its vertex ID. This endpoint requires the [`READ_DATA` privilege](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/access-control-model#_data_crud_privileges) on the vertex type.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_sample_request_9)Sample request:
  * Request
  * Response


```
curl -X GET "http://localhost:14240/restpp/graph/socialNet/vertices/User/id1"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
{
 "version": {
  "api": "v2",
  "schema": 0
 },
 "error": false,
 "message": "",
 "results": [
  {
   "v_id": "id1",
   "v_type": "User",
   "attributes": {}
  }
 ]
}
javascript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_14)Parameters:
Name | Required | Description  
---|---|---  
`select` | No | Attributes of the selected vertices to return. The parameter takes a list, which is a string of comma-separated values, and will only return the attributes that are provided.  
`timeout` | No | Integer that specifies the number of seconds after which the query will time out. If the parameter is set to 0 or isn’t provided, the system-wide endpoint timeout setting is applied.  
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_delete_vertices)Delete vertices
`DELETE /restpp/graph/{graph_name}/vertices/{vertex_type}`
This endpoint deletes vertices by their vertex type. The delete operation is a cascading deletion. If a vertex is deleted, then all edges connected to it are automatically deleted as well.
This endpoint requires the [`DELETE_DATA` privilege](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/access-control-model#_data_crud_privileges) on the vertex type.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_sample_request_10)Sample request:
The response object will contain a `"deleted_vertices"` field that indicates the number of vertices that were deleted. 

Request
    
```
curl -X DELETE "http://localhost:14240/restpp/graph/socialNet/vertices/User"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Response
    
```
{
 "version": {
  "edition": "enterprise",
  "api": "v2",
  "schema": 0
 },
 "error": false,
 "message": "",
 "results": {
  "v_type": "person",
  "deleted_vertices": 3
 }
}
javascript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_15)Parameters:
Name | Required | Description  
---|---|---  
`permanent` | No | Takes a boolean value. If the value is true, the deleted vertex IDs can never be inserted back, unless the graph is dropped or the graph store is cleared.  
`filter` | No | Conditions used to filter the vertices to delete. The parameter takes a list of conditions, which is a string of comma-separated values. If any filter conditions are provided, the endpoint will only delete the vertices that satisfy the conditions. Six comparison operators are supported for this parameter: `=`, `!=`, `>`, `>=`, `<` and `⇐`. If the value on the right side of an operator is a string literal, it should be enclosed in double-quotes.  
`limit` | No | Integer value that specifies the total number of vertices to delete.  
`sort` | No | Attributes to sort the vertices by. In delete operations,`sort` should always be used together with `limit`. The endpoint will delete the number of vertices under the limit specified in the order specified. The parameter takes a list of attributes, and the endpoint will sort all vertices based on the attributes provided in the list in order. Add `"-"` in front of the attribute to sort by that attribute in descending order.  
`timeout` | No | Integer that specifies the number of seconds after which the query will time out. If the parameter is set to `0` or isn’t provided, the system-wide endpoint timeout setting is applied.  
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_delete_vertices_by_type)Delete vertices by type
`DELETE /restpp/graph/{graph_name}/delete_by_type/vertices/{vertex_type}`
This endpoint deletes all vertices of the given vertex type in a graph. This endpoint requires the [`DELETE_DATA` privilege](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/access-control-model#_data_crud_privileges) on the vertex type.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_sample_request_11)Sample request:
```
curl -X DELETE "http://localhost:14240/restpp/graph/poc_graph/delete_by_type/vertices/person"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_16)Parameters:
Name | Required | Description  
---|---|---  
`permanent` | No | Takes a boolean value. If the value is true, the deleted vertex IDs can never be inserted back, unless the graph is dropped or the graph store is cleared.  
`ack` | No | If the parameter is set to "none", the delete operation doesn’t need to get acknowledgment from any GPE. If it is set to "all" (default), the operation needs to get acknowledgment from all GPEs.  
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_delete_a_vertex)Delete a vertex
`DELETE /restpp/graph/{graph_name}/vertices/{vertex_type}/{vertex_id}`
This endpoint requires the [`DELETE_DATA` privilege](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/access-control-model#_data_crud_privileges) on the vertex type.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_sample_request_12)Sample request:
  * Request
  * Response


```
curl -X DELETE "http://localhost:14240/restpp/graph/socialNet/vertices/User/id1"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
{
 "version": {
  "edition": "enterprise",
  "api": "v2",
  "schema": 0
 },
 "error": false,
 "message": "",
 "results": {
  "v_type": "User",
  "deleted_vertices": 1
 }
}
javascript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_17)Parameters:
Name | Required | Description  
---|---|---  
`timeout` | no | Integer that specifies the number of seconds after which the query will time out. If the parameter is set to 0 or isn’t provided, the system-wide endpoint timeout setting is applied.  
## [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_edges)Edges
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_insert_edges)Insert edges
To insert vertices or edges, use the [Upsert data to graph](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest) endpoint.
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_list_edges_of_a_vertex)List edges of a vertex
`GET /restpp/graph/{graph_name}/edges/{source_vertex_type}/{source_vertex_id}`
This endpoint returns all edges which are connected to a given vertex ID in the graph.
This endpoint requires the [`READ_DATA` privilege](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/access-control-model#_data_crud_privileges) on the types or attributes being queried.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_sample_request_13)Sample request:
  * Request
  * Response


```
curl -X GET "http://localhost:14240/restpp/graph/socialNet/edges/VidUser/0?limit=2"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
{
 "version": {
  "api": "v2",
  "schema": 0
 },
 "error": false,
 "message": "",
 "results": [
  {
   "e_type": "User_Video",
   "directed": false,
   "from_id": "0",
   "from_type": "VidUser",
   "to_id": "2",
   "to_type": "Video",
   "attributes": {
    "rating": 5.2,
    "date_time": 0
   }
  },
  {
   "e_type": "User_Video",
   "directed": false,
   "from_id": "0",
   "from_type": "VidUser",
   "to_id": "0",
   "to_type": "Video",
   "attributes": {
    "rating": 6.8,
    "date_time": 0
   }
  }
 ]
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_18)Parameters:
Name | Required | Description  
---|---|---  
`count_only` | No | Takes a boolean value. If the value is true, the `results` field will only contain the count of how many edges were selected. Default is `false`.  
`select` | No | Attributes of the selected edges to return. The parameter takes a list, which is a string of comma-separated values. If `select` is provided, the edges returned will only show the attributes provided.  
`filter` | No | Conditions used to filter the edges to return. The parameter takes a list of conditions, which is a string of comma-separated values. If any filter conditions are provided, the endpoint will only return the edges that satisfy the conditions. Six comparison operators are supported for this parameter: `=`, `!=`, `>`, `>=`, `<` and `<=`. If the value on the right side of an operator is a string literal, it should be enclosed in double-quotes.  
`limit` | No | Integer value that specifies the maximum limit of the total number of edges to return.  
`sort` | No | Attributes to sort the results by. The parameter takes a list, which is a string of comma-separated values, and will sort all the edges based on the attributes provided in the list in order. Add `"-"` in front of the attribute to sort in descending order.  
`timeout` | No | Integer that specifies the number of seconds after which the query will time out. If the parameter is set to `0` or isn’t provided, system-wide endpoint timeout setting is applied.  
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_list_edges_of_a_vertex_by_edge_type)List edges of a vertex by edge type
`GET /restpp/graph/{graph_name}/edges/{source_vertex_type}/{source_vertex_id}/{edge_type}`
This endpoint lists all the edges of a specified type connected to a given vertex ID in the graph.
This endpoint requires the [`READ_DATA` privilege](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/access-control-model#_data_crud_privileges) on the types or attributes being queried.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_sample_request_14)Sample request:
```
curl -X GET "http://localhost:14240/restpp/graph/socialNet/edges/VidUser/0/User_Video?limit=2"
{
 "version": {
  "api": "v2",
  "schema": 0
 },
 "error": false,
 "message": "",
 "results": [
  {
   "e_type": "User_Video",
   "directed": false,
   "from_id": "0",
   "from_type": "VidUser",
   "to_id": "2",
   "to_type": "Video",
   "attributes": {
    "rating": 5.2,
    "date_time": 0
   }
  },
  {
   "e_type": "User_Video",
   "directed": false,
   "from_id": "0",
   "from_type": "VidUser",
   "to_id": "0",
   "to_type": "Video",
   "attributes": {
    "rating": 6.8,
    "date_time": 0
   }
  }
 ]
}
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_19)Parameters:
Name | Required | Description  
---|---|---  
`count_only` | No | Takes a boolean value. If the value is true, the `results` field will only contain the count of how many edges were selected. Default is `false`.  
`select` | No | Attributes of the selected edges to return. The parameter takes a list, which is a string of comma-separated values. If `select` is provided, the edges returned will only show the attributes provided.  
`filter` | No | Conditions used to filter the edges to return. The parameter takes a list of conditions, which is a string of comma-separated values. If any filter conditions are provided, the endpoint will only return the edges that satisfy the conditions. Six comparison operators are supported for this parameter: `=`, `!=`, `>`, `>=`, `<` and `<=`. If the value on the right side of an operator is a string literal, it should be enclosed in double quotes.  
`limit` | No | Integer value that specifies the maximum limit of the total number of edges to return.  
`sort` | No | Attributes to sort the results by. The parameter takes a list, which is a string of comma-separated values, and will sort all the edges based on the attributes provided in the list in order. Add `"-"` in front of the attribute to sort in descending order.  
`timeout` | No | Integer that specifies the number of seconds after which the query will time out. If the parameter is set to `0` or isn’t provided, system-wide endpoint timeout setting is applied.  
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_list_edges_of_a_vertex_by_edge_type_and_target_type)List edges of a vertex by edge type and target type
```
GET /restpp/graph/{graph_name}/edges/{source_vertex_type}/{source_vertex_id}/{edge_type}/{target_vertex_type}
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This endpoint lists edges connected to a given vertex by edge type and target vertex type.
This endpoint requires the [`READ_DATA` privilege](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/access-control-model#_data_crud_privileges) on the types or attributes being queried.
Use `"_"` for `edge_type` in the URL to permit any edge type.  
---  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_sample_request_15)Sample request:
  * Request
  * Response


```
curl -X GET "http://localhost:14240/restpp/graph/socialNet/edges/VidUser/0/User_Video/Video?limit=2"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
{
 "version": {
  "api": "v2",
  "schema": 0
 },
 "error": false,
 "message": "",
 "results": [
  {
   "e_type": "User_Video",
   "directed": false,
   "from_id": "0",
   "from_type": "VidUser",
   "to_id": "2",
   "to_type": "Video",
   "attributes": {
    "rating": 5.2,
    "date_time": 0
   }
  },
  {
   "e_type": "User_Video",
   "directed": false,
   "from_id": "0",
   "from_type": "VidUser",
   "to_id": "0",
   "to_type": "Video",
   "attributes": {
    "rating": 6.8,
    "date_time": 0
   }
  }
 ]
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_20)Parameters:
Name | Required | Description  
---|---|---  
`count_only` | No | Takes a boolean value. If the value is true, the `results` field will only contain the count of how many edges were selected. Default is `false`.  
`not_wildcard` | No | Boolean value that indicates whether or not `"_"` supplied in the endpoint URL is a wildcard. If the parameter is true, `"_"` is interpreted literally to select only edges with edge type name equal to underscore.  
`select` | No | Attributes of the selected edges to return. The parameter takes a list, which is a string of comma-separated values. If `select` is provided, the edges returned will only show the attributes provided.  
`filter` | No | Conditions used to filter the edges to return. The parameter takes a list of conditions, which is a string of comma-separated values. If any filter conditions are provided, the endpoint will only return the edges that satisfy the conditions. Six comparison operators are supported for this parameter: `=`, `!=`, `>`, `>=`, `<` and `<=`. If the value on the right side of an operator is a string literal, it should be enclosed in double-quotes.  
`limit` | No | Integer value that specifies the maximum limit of the total number of edges to return.  
`sort` | No | Attributes to sort the results by. The parameter takes a list, which is a string of comma-separated values, and will sort all the edges based on the attributes provided in the list in order. Add `"-"` in front of the attribute to sort in descending order.  
`timeout` | No | Integer that specifies the number of seconds after which the query will time out. If the parameter is set to `0` or isn’t provided, the system-wide endpoint timeout setting is applied.  
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_retrieve_edge_by_source_target_and_edge_type)Retrieve edge by source, target, and edge type
```
GET /restpp/graph/{graph_name}/edges/{source_vertex_type}/{source_vertex_id}/{edge_type}/{target_vertex_type}/{target_vertex_id}
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This endpoint returns the edge of a specified type between a source vertex and a target vertex. If the edge type isn’t defined with a [discriminator](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_discriminator), the source, target and edge type uniquely identify an edge. If the edge type is defined with a discriminator, this endpoint returns all edges of the edge type between the source and target vertices.
This endpoint requires the [`READ_DATA` privilege](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/access-control-model#_data_crud_privileges) on the types or attributes being queried.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_sample_request_16)Sample request:
  * Request
  * Response


```
curl -X GET "http://localhost:14240/restpp/graph/socialNet/edges/VidUser/0/User_Video/Video/2"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
{
 "version": {
  "api": "v2",
  "schema": 0
 },
 "error": false,
 "message": "",
 "results": [
  {
   "e_type": "User_Video",
   "directed": false,
   "from_id": "0",
   "from_type": "VidUser",
   "to_id": "2",
   "to_type": "Video",
   "attributes": {
    "rating": 5.2,
    "date_time": 0
   }
  }
  ]
 }
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_21)Parameters:
Name | Required | Description  
---|---|---  
`select` | No | Attributes of the selected edges to return. The parameter takes a list, which is a string of comma-separated values. If `select` is provided, the edges returned will only show the attributes provided.  
`timeout` | No | Integer that specifies the number of seconds after which the query will time out. If the parameter is set to `0` or isn’t provided, the system-wide endpoint timeout setting is applied.  
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_retrieve_edge_by_source_target_edge_type_and_discriminator)Retrieve edge by source, target, edge type, and discriminator
```
GET /restpp/graph/{graph_name}/edges/{source_vertex_type}/{source_vertex_id}/{edge_type}
/{target_vertex_type}/{target_vertex_id}/{discriminator}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This endpoint allows you to retrieve an edge by its source, target, edge type, and [discriminator](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_discriminator).
If the discriminator has multiple attributes, use `,` as a separator. But if the attributes already have commas in a string discriminator, use `\` as an escape character to escape the commas. The backslash escape character can escape the escape character itself as well.  
---  
This endpoint requires the `READ_DATA` privilege on the types or attributes being queried.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_sample_request_17)Sample request:
  * Single-attribute discriminator
  * Composite discriminator


```
curl -X GET 'http://localhost:14240/restpp/graph/multiedge/edges/Person/4/transfer/Person/30/2431'
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
curl -X GET "http://localhost:14240/restpp/graph/multiedge/edges/Person/9/transfer2/Account/9/77,1117,2010-04-09%2003:57:01" **(1)**
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | `%20` is the URL encoding for a space character.  
---|---  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_22)Parameters:
Name | Required | Description  
---|---|---  
`select` | No | Attributes of the selected edges to return. The parameter takes a list, which is a string of comma-separated values. If `select` is provided, the edges returned will only show the attributes provided.  
`timeout` | No | Integer that specifies the number of seconds after which the query will time out. If the parameter is set to `0` or isn’t provided, the system-wide endpoint timeout setting is applied.  
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_delete_one_or_more_edges_by_source_target_and_edge_type)Delete one or more edges by source, target, and edge type
```
DELETE /restpp/graph/{graph_name}/edges/{source_vertex_type}/{source_vertex_id}/{edge_type}/{target_vertex_type}/{target_vertex_id}
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Deletes an edge by its source vertex type and ID, target vertex type and ID, as well as edge type. If the edge type isn’t defined with a [discriminator](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_discriminator), the source, target and edge type uniquely identify an edge.
If the edge type is defined with a discriminator, this endpoint deletes all edges of the edge type between the source and target vertices. If you want to delete a specific edge by its discriminator, see [Delete an edge by source, target, edge type and discriminator](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_delete_an_edge_by_source_target_edge_type_and_discriminator).
This endpoint requires the [`DELETE_DATA` privilege](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/access-control-model#_data_crud_privileges) and `READ_DATA` on the types or attributes being queried.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_batch_edge_delete)Batch edge delete
To delete multiple edges, provide the source and target vertex IDs to delete all edgs connecting source and target.
Delete all transfers between account 40381 and 10327
```
curl -s -X DELETE 'http://localhost:14240/restpp/graph/multiedge/edges/Account/40381/transfer/Account/10327' | jq .
```

Provide only the source to delete all edges from that source, or the source ID and a target type only without the target ID.
```
// Delete all transfers from account 24601
curl -s -X DELETE 'http://localhost:14240/restpp/graph/multiedge/edges/Account/24601/transfer' | jq .
// Delete all transfers to Person vertices from account 24601
curl -s -X DELETE 'http://localhost:14240/restpp/graph/multiedge/edges/Account/24601/transfer/Person' | jq .
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_sample_request_18)Sample request:
  * Request
  * Response


```
curl -X DELETE "https://crunch.i.tgcloud.io:14240/restpp/graph/CrunchBasePre_2013/edges/person/p:23601/work_for_company/company/c:14478"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
{
 "version": {
  "edition": "enterprise",
  "api": "v2",
  "schema": 0
 },
 "error": false,
 "message": "",
 "results": [
  {
   "e_type": "work_for_company",
   "deleted_edges": 1
  }
 ]
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_23)Parameters:
Name | Required | Description  
---|---|---  
`timeout` | No | Integer that specifies the number of seconds after which the query will time out. If the parameter is set to 0 or isn’t provided, the system-wide endpoint timeout setting is applied.  
`filter=<attribute value expression>` | No | Filter that specifies a specific value of a specific edge attribute to delete. For example, `filter=amount>100` would match edges with `amount` attributes greater than `100`.  
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_delete_an_edge_by_source_target_edge_type_and_discriminator)Delete an edge by source, target, edge type and discriminator
```
DELETE /restpp/graph/{graph_name}/edges/{source_vertex_type}/{source_vertex_id}/{edge_type}
/{target_vertex_type}/{target_vertex_id}/{discriminator}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This endpoint allows you to delete an edge by its source, target, edge type, and [discriminator](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_discriminator).
If the discriminator has multiple attributes, use `,` as a separator. But if the attributes already have commas in a string discriminator, use `\` as an escape character to escape the commas. The backslash escape character can escape the escape character itself as well.  
---  
This endpoint requires the `DELETE_DATA` privilege on the type of the edge being queried.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_sample_request_19)Sample request:
  * Single-attribute discriminator
  * Composite discriminator


```
curl -X DELETE 'http://localhost:14240/restpp/graph/multiedge/edges/Person/4/transfer/Person/30/2431'
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
curl -X DELETE "http://localhost:14240/restpp/graph/multiedge/edges/Person/9/transfer2/Account/9/77,1117,2010-04-09%2003:57:01" **(1)**
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | `%20` is the URL encoding for a space character.  
---|---  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_24)Parameters:
Name | Required | Description  
---|---|---  
`timeout` | no | Integer that specifies the number of seconds after which the query will time out. If the parameter is set to 0 or isn’t provided, the system-wide endpoint timeout setting is applied.  
## [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_queries)Queries
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_get_query_metadata)Get query metadata
`GET /gsql/v1/queries/info`
Returns metadata details about a query. In particular, it lists the input parameters in the same order as they exist in the query (in the form of a JSON array of JSON objects) and outputs `PRINT` statement syntax. **This endpoint exists on port 14240 and requests are sent to the GSQL server.** Therefore, you should provide authentication credentials in the request.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_sample_request_20)Sample request:
  * Request
  * Response


```
curl -u tigergraph:tigergraph -X GET "http://localhost:14240/gsql/v1/queries/info?graph=workNet&query=to_vertex_setTest"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
{
 "output": [
  {
   "v": "vertex"
  },
  {
   "@@v2": "SetAccum<vertex>"
  },
  {
   "S2": [
    {
     "v_id": "int",
     "attributes": {
      "interestList": "INT_LIST",
      "skillSet": "INT_SET",
      "skillList": "INT_LIST",
      "locationId": "STRING",
      "interestSet": "INT_SET",
      "id": "STRING"
     },
     "v_type": "person"
    },
    {
     "v_id": "int",
     "attributes": {
      "country": "STRING",
      "id": "STRING"
     },
     "v_type": "company"
    }
   ]
  },
  {
   "SDIFF.size()": "int"
  }
 ],
 "input": [
  {
   "uid": "string"
  },
  {
   "uids": "set<string>"
  },
  {
   "vtype": "string"
  }
 ],
 "queryname": "to_vertex_setTest",
 "error": false,
 "message": "",
 "version": {
  "schema": 0,
  "edition": "DEVELOPER_EDITION",
  "api": "V2"
 }
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The JSON response object contains three fields:
  * **`queryname`**: name of the query, same as the query input parameter.
  * **`input`**: Ordered list of the input parameter names and data types in the same order as they are in the query.
  * **`output`**: JSON object that follows the same structure of the query’s output. For each key-value pair, the key is the name that appears in the query output, while the values are the data types of the output.


#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_25)Parameters:
Name | Required | Description  
---|---|---  
`graph` | Yes | Name of the graph  
`query` | Yes | Name of the query  
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_install_a_query)Install a query
`POST /gsql/v1/queries/install`
Once queries has been created for a graph, the user can use the `POST /gsql/v1/queries/install` endpoint to make a request to install one or multiple queries.
Once the GSQL server has received the `POST` request, it creates an installation request and returns a request location containing a request ID, with which you can [check the installation status of all the queries in the request](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_check_query_installation_status). An installation request will wait in the background for any currently running processes to complete.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_26)Parameters:
Name | Required | Description  
---|---|---  
`graph` | Yes | The name of the graph the queries belong to  
`queries` | Yes |  The names of the queries to install. If `queries` is set to `all` or `*`, the endpoint installs all queries. To pass in the names of multiple queries, enter the same parameter multiple times with the names of the queries you want to install.  
`async` | No | If `true`, install the query in the background and return a requestId which can be used to check the status of the installation.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_sample_request_21)Sample request:
In the below example, the user requests to install all queries on the graph `poc_graph` by using the `*` wildcard.
  * Request
  * Response


```
curl --user tigergraph:tigergraph -X POST 'http://localhost:14240/gsql/v1/queries/install?graph=social&queries=khop_d'
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
{
  "location": "/gsql/queries/install/1234", **(1)**
  "error": false,
  "message": "Request 1234 successfully created",
  "results": ""
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | URI where the request can be found. `1234` is the ID of the request.  
---|---  
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_check_query_installation_status)Check query installation status
`GET /gsql/v1/queries/install/{requestid}`
This endpoint takes a request location generated by the `POST /gsql/v1/queries/install` endpoint and returns the state of the installation request for each query, as well as the overall state of the request itself.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_27)Parameters:
None.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_sample_request_22)Sample request:
In the below example, the user requests information about the queries installed in the above `POST` example. The response shows that three query install requests were made with `POST`: queries `t1`, `t2`, and `t3`.
At the time of response, `t1` had installed successfully, while the other two were still running in the background.
  * Request
  * Response


```
curl --user tigergraph:tigergraph -X GET 'http://localhost:14240/gsql/v1/queries/install/1234'
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
{
 "state": "RUNNING", **(1)**
 "error": false,
 "message": "",
 "results": "",
 "queries": [
  {
   "name": "t1",
   "state": "SUCCESS"
  },
  {
   "name": "t2",
   "state": "RUNNING"
  },
  {
   "name": "t3",
   "state": "RUNNING"
  }
 ],
 "graph": "poc_graph"
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | The installation request state shown with `state` shows the overall status of the query installation request. It will return `SUCCESS` even if some queries fail to install, as long as each query has been given a chance to install. If the overall status is `SUCCESS` but each query has failed, it indicates that something is wrong with the queries. If the overall status is `FAILURE`, it indicates that something is wrong with the installation job itself independent of the queries. It will return `NEW` if the query installation request has been made, but the resource manager is occupied with another request at the time the user made the overall status request.  
---|---  
If you install all queries and receive a state of `SUCCESS` for one or more queries that had been installed previously, it does not mean that they were reinstalled. A returned state of `SUCCESS` is a confirmation that a query is ready to be run.  
---  
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_run_an_installed_query_get)Run an installed query (`GET`)
`GET /restpp/query/{graph_name}/{query_name}`
Each time a new TigerGraph query is installed, a dynamic endpoint is generated. This new endpoint enables the user to run the new TigerGraph query through HTTP requests and giving the parameters in URL or in a data payload. In the case of a `GET` request, parameters should be passed in through the query string.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_28)Parameters:
Name | Required | Description  
---|---|---  
`read_committed` | No | Boolean value that indicates whether to use [read-committed isolation level](https://en.wikipedia.org/wiki/Isolation_\(database_systems\)#Read_committed) for the query. At the read committed level, it is guaranteed that any data read is committed at the moment it is read. By default, it is off.  
To use the `read_commited` parameter, `read_commited` must be defined as a parameter in the query itself. The content of the query does not have to use the parameter, but the parameter must be defined. For example: `CREATE QUERY PageRank( …​, INT iteration, …​, BOOL read_committed) FOR GRAPH Example_Graph`  
---  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_query_parameter_passing)Query parameter passing
When using a `GET` request to run an installed query, the query parameters are [passed in through the query string of the URL](https://docs.tigergraph.com/tigergraph-server/4.1/API/#_query_string_parameters).
Parameter type | Query string format | Example  
---|---|---  
Set or bag of primitives |  Assign multiple values to the same parameter name. | A set `p1` of integers: `p1=1&p1=5&p1=10`  
`VERTEX<type>` |  Use the ID of the vertex: `parameterName=vertex_id` | A vertex with parameter name `vp` and an ID of person2: `vp=person2`  
`VERTEX` (type not pre-specified) |  Use two query string parameters:
  * `parameterName=vertex_id`
  * `parameterName.type=vertex_type`

| A vertex with parameter name `va` , type `person` and ID `person1`: `va=person1&va.type=person`  
Set or bag of `VERTEX<type>` |  Assign multiple vertex IDs to the same `SET` or `BAG` parameter name. | A set parameter named `vp` of vertices of type person: `vp=person3&vp=person4`  
Set or bag of `VERTEX` (type not pre-specified) |  The `SET` or `BAG` must be treated as an array. A vertex ID and type must be provided for the vertex element at each index. | A set parameter named `vp` of vertices: `vp[0]=person1&vp[0].type=person&vp[1]=11&vp[1].type=post`  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_specify_replica)Specify replica
If you have a TigerGraph HA cluster, you can specify a query to run on a particular replica with the HTTP header `GSQL-REPLICA`. The value of the header needs to be an integer within the range `[1, (cluster replication factor)]`. If you supply an invalid value for the header, the request will return an error.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_specify_thread_limit)Specify thread limit
When running a query through RESTPP, you can specify a limit on the number of threads that the query is allowed to use on each node through the HTTP header `GSQL-THREAD-LIMIT`. The number of threads used by a query means the number of vCPUs used by the query. By default, a query will use all threads that are available on a machine.
For example, if you have a cluster of three nodes, each with 8 vCPUs, then a query will use all 8 threads available on a node in the cluster by default. By providing a thread limit in the request header, you can limit the query to only use a number of threads under the limit.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_sample_requests_2)Sample requests:
To run a query that takes a parameter of a set of strings (`str`), a vertex parameter(v), and a parameter of a set of vertices:
  * Query
  * Request


```
CREATE QUERY print_params(SET<STRING> str, VERTEX v, SET<VERTEX> party)
FOR GRAPH Social {
 PRINT str, v, party;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

To pass in the value for a set parameter, enter the values of all set elements to the name of the parameter multiple times. If the type of a vertex is not specified, specify it by adding a parameter `<typeName>.type` and specify the type:
```
$ curl -X GET "http://localhost:14240/restpp/query/social/print_params?str=hello&str=world&v=Mary&party=Tobias&party=Jenny&party.type=person&v.type=person"
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

To run query `hello` on a graph named `social`, and the query parameter is of type `VERTEX<person>` whose ID is `"Tom"`
Running a query via HTTP request
```
curl -X GET "http://localhost:14240/restpp/query/social/hello?p=Tom"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Limiting the query to use under 4 threads
```
curl -x GET -H "GSQL-THREAD-LIMIT: 4" "http://localhost:14240/restpp/query/social/hello?p=Tom"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Specifying the query to run on the first replica
```
curl -X GET -H "GSQL-REPLICA: 2" "http://localhost:14240/restpp/query/social/hello?p=Tom"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Specifying the query to run on the primary cluster
```
curl -X GET -H "GSQL-REPLICA: 1" "http://localhost:14240/restpp/query/social/hello?p=Tom"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_run_an_installed_query_post)Run an installed query (`POST`)
`POST /restpp/query/{graph_name}/{query_name}`
Users can also run queries through a `POST` request, which allows them to pass query parameters in JSON format. This is especially helpful when the query takes complex parameters.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_format_of_file_in_json_format)Format of file in JSON format
```
{
  "parameter_1":"value_1",
  "parameter_2":"value_2"
}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_format_of_post_request)Format of POST request
```
curl -X POST --data-binary @./<sample_file> "http://localhost:14240/restpp/query/<sample_graph>/<sample_query>"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_29)Parameters:
Name | Required | Description  
---|---|---  
`read_committed` | No | Boolean value that indicates whether to use [read-committed isolation level](https://en.wikipedia.org/wiki/Isolation_\(database_systems\)#Read_committed) for the query. At the read committed level, it is guaranteed that any data read is committed at the moment it is read. By default, it is off.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_query_parameter_passing_2)Query parameter Passing
When using a `POST` request to run an installed query, the query parameters are passed in through the request body and [encoded in JSON format](https://docs.tigergraph.com/tigergraph-server/4.1/API/#_formatting_data_in_json). The formatting rules for the JSON payload are the same as [using JSON to pass in parameters in the `RUN QUERY` command](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-operations#_parameter_json_object).
Parameter type | Syntax | Example  
---|---|---  
`DATETIME` | Use a string formatted as `"YYYY-MM-DD HH-MM-SS"` | `"2019-02-19 19:19:19"`  
Set or bag of primitives | Use a JSON array containing the primitive values | `["a", "list", "of", "args"]`  
`VERTEX<type>` | Use a JSON object containing a field `"id"` for the vertex ID and a field `"type"` for the type of the vertex | `{"id": "person1", "type": "person"}`  
`VERTEX` (type not specified) | Use a JSON object containing a field `"id"` for the vertex ID | `{"id": "person1"}`  
Set or bag of `VERTEX<type>` | Use a JSON array containing a list of JSON `VERTEX<type>` object | `[{"id": "person1"}, {"id": "person2"}]`  
Set or bag of vertices of unspecified types | Use a JSON array containing a list of JSON `VERTEX` | `[{"id": "person1","type": "person"},{"id": "person2","type": "person"}]`  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_headers)Headers
The Run Query endpoint accepts a number of headers that allow you to configure the way the query is run:
Name | Description  
---|---  
`GSQL-REPLICA` | The replica where the query is to be run. The value of the header needs to be an integer within the range 1 to the replication factor of the cluster. If you supply an invalid value for the header, the request returns an error. A cluster that has only one copy of the database has a replication factor of 1.  
`GSQL-THREAD-LIMIT` | Maximum limit on the number of threads that the query is allowed to use on each node. By default, a query will use all threads that are available on a machine. For example, if you have a cluster of three nodes, each with 8 vCPUs, then a query will use all 8 threads available on a node in the cluster by default. By providing a thread limit in the request header, you can limit the query to only use a number of threads under the limit.  
`GSQL-QueryLocalMemLimitMB` | Maximum limit of how much memory a query is allowed to use on any single node in a cluster. By default, there is no limit to the amount of memory a query is allowed to consume until the overall free memory reaches a critical level.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_sample_request_23)Sample request:
To run a query that takes a parameter of a set of strings (`str`), a vertex parameter(v), and a parameter of a set of vertices (`party`):
  * Query
  * Request
  * Request body


```
CREATE QUERY print_params(SET<STRING> str, VERTEX v, SET<VERTEX<Person>> party) FOR GRAPH Social {
 PRINT str, v, party;
}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
$ curl -X POST -d @<path_to_request_body> ""http://localhost:14240/restpp/query/Social/print_params"
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
{
	"v": {"id": "Jenny", "type": "Person"}, **(1)**
	"str": ["hello", "world"], **(2)**
	"party": [
		{"id": "Mary"},
		{"id": "Tobias}
	] **(3)**
}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | Provides the value for parameter `v`, which is a `Person` type vertex with ID `Jenny`. The `type` field is required because the original query definition does not specify vertex type.  
---|---  
**2** | Provides the value for parameter `str`, which is a set of strings with two elements `"hello"` and `"world"`.  
**3** | Provides the value for parameter `party`, which is a set of `Person` type vertices. The `type` field is optional for the vertex elements in the set because the original query definition specifies vertex type.  
The query in this sample request takes a parameter of type `VERTEX<person>`:
```
curl -X POST -d '{"p":{"id":"Tom","type":"person"}}'
"http://localhost:14240/restpp/query/social/hello"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Specify that the query run on the first replica
```
curl -X POST -H "GSQL-REPLICA: 2" -d '{"p":{"id":"Tom","type":"person"}}'
"http://localhost:14240/restpp/query/social/hello"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Specify that the query run on the primary cluster
```
curl -X POST -H "GSQL-REPLICA: 1" -d '{"p":{"id":"Tom","type":"person"}}'
"http://localhost:14240/restpp/query/social/hello"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Specify that the query run with a limit of 4 threads
```
curl -X POST -H "GSQL-THREAD-LIMIT: 4" -d '{"p":{"id":"Tom","type":"person"}}' "http://localhost:14240/restpp/query/social/hello"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Installed queries can run in [Detached Mode](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-operations#_detached_mode_async_option). To do this, use the `GSQL-ASYNC`header and set its value to `true`. The [results](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_check_query_status_detached_mode) and [status](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints.adoc#_check_query_status_detached_mode) of the queries run in Detached Mode can be retrieved with a query ID, which is returned immediately when queries are executed in Detached Mode.  
---  
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_run_an_interpreted_query)Run an interpreted query
`POST /gsql/v1/queries/interpret`
This endpoint runs a GSQL query in Interpreted Mode. The query body should be supplied at the data payload, and the query’s parameters are supplied as the URL’s query string. **This endpoint exists on the GSQL server on port 14240.**
This request goes directly to the GSQL server (port 14240) instead of the RESTPP server, so the username and password must be specified in the header. If you are using curl, you can use the `-u` option as shown below.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_request_body_5)Request body:
The request body for this endpoint should be the entire `INTERPRET QUERY` statement.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameter_passing)Parameter passing:
When running an interpreted query through this endpoint, the query parameters should be [passed in through the URL query string](https://docs.tigergraph.com/tigergraph-server/4.1/API/#_query_string_parameters).
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_sample_request_24)Sample request:
```
curl --fail -u <my_username>:<my_password> -X POST "http://localhost:14240/gsql/v1/queries/interpret?a=10" -d 'INTERPRET QUERY (INT a) FOR GRAPH gsql_demo {
  PRINT a;
 }'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_list_running_queries_of_a_graph)List running queries of a graph
`GET /restpp/showprocesslist/{graph_name}`
This endpoint reports statistics of running queries of a graph: the query’s request ID, start time, expiration time, and the REST endpoint’s URL. This includes installed queries. interpreted queries, as well as built-in queries.
If you are running a TigerGraph cluster, this endpoint only shows queries running on the node to which the request is sent, not all running queries on the cluster.
This endpoint requires the `READ_DATA` privilege on the graph you are querying.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_sample_request_25)Sample request:
  * Request
  * Response


```
curl -X GET "http://localhost:14240/restpp/showprocesslist/poc_graph" | jq .
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
{
 "version": {
  "edition": "enterprise",
  "api": "v2",
  "schema": 0
 },
 "error": false,
 "message": "",
 "results": [
  {
   "requestid": "65538.RESTPP_1_1.1558386411523.N",
   "startTime": "2019-05-20 14:06:51.523",
   "expirationTime": "2019-05-20 14:15:11.523",
   "url": "/sleepgpe?milliseconds=100001"
  },
  {
   "requestid": "196609.RESTPP_1_1.1558386401478.N",
   "startTime": "2019-05-20 14:06:41.478",
   "expirationTime": "2019-05-20 14:15:01.478",
   "url": "/sleepgpe?milliseconds=100000"
  }
 ],
 "code": "REST-0000"
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_30)Parameters:
No Parameters.
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_list_all_running_queries)List all running queries
`GET /restpp/showprocesslistall`
This endpoint reports the statistics of all running queries across all graphs on a TigerGraph instance: the query’s request ID, start time, expiration time, and the REST endpoint’s URL. This includes installed queries. interpreted queries, as well as built-in queries.
If you are running a TigerGraph cluster, this endpoint only shows queries running on the node to which the request is sent, not all running queries on the cluster.
If a high volume of queries are running, invoking the endpoint can be an expensive operation that should be used with caution.   
---  
This endpoint requires the `READ_DATA` privilege on the global scope.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_sample_request_26)Sample request:
  * Request
  * Response


```
$ curl -X GET "http://localhost:14240/restpp/showprocesslistall" |jq
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
 % Total  % Received % Xferd Average Speed  Time  Time   Time Current
                 Dload Upload  Total  Spent  Left Speed
100  671 100  671  0   0  655k   0 --:--:-- --:--:-- --:--:-- 655k
{
 "version": {
  "edition": "enterprise",
  "api": "v2",
  "schema": 0
 },
 "error": false,
 "message": "",
 "results": [
  {
   "requestid": "15.RESTPP_1_1.1660165648633.N", **(1)**
   "startTime": "2022-08-10 21:07:28.633",
   "expirationTime": "2022-08-10 21:07:44.633", **(2)**
   "url": "/query/Social/rngExample",
   "elapsedTime": 3385
  },
  {
   "requestid": "65551.RESTPP_1_1.1660165648638.N",
   "startTime": "2022-08-10 21:07:28.638",
   "expirationTime": "2022-08-10 21:07:44.638",
   "url": "/query/Work_Net/rngExample",
   "elapsedTime": 3380
  },
  {
   "requestid": "131087.RESTPP_1_1.1660165648723.N",
   "startTime": "2022-08-10 21:07:28.723",
   "expirationTime": "2022-08-10 21:07:44.723",
   "url": "/query/Entity_Resolution/rngExample",
   "elapsedTime": 3295
  }
 ],
 "code": "REST-0000"
}
```

**1** | Each request to run a query sent to the REST server has a unique ID that can be used to look up the request in the system logs.  
---|---  
**2** | The time at which the query will time out.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_31)Parameters:
No parameters.
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_show_all_delayed_queries)Show all delayed queries
`GET /restpp/showdelayedlistall`
When queries beyond the maximum concurrent query amount (specified in the `RESTPP.WorkLoadManager.MaxConcurrentQueries` parameter) are submitted, they are sent to the delay or overflow queue. This overflow queue length is limited by the `RESTPP.WorkLoadManager.MaxDelayQueueSize` parameter. Use this endpoint to get a list of all queries waiting in the delay/overflow queue.
Query timeout time is not affected by the time spent in the delayed queue.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_sample_request_27)Sample request:
  * Request
  * Response


```
$ curl -X GET "http://localhost:14240/restpp/showdelayedlistall" |jq
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
{
 "version": {
  "edition": "enterprise",
  "api": "v2",
  "schema": 2
 },
 "error": false,
 "message": "",
 "results": [
  {
   "requestidPartial": "1670970545942",
   "startTime": "2022-12-13 22:29:05.942",
   "url": "/query/ldbc_snb/LTQ1?gap=60&qtf=vwlm_a_007",
   "elapsedTime": 2023
  },
  {
   "requestidPartial": "1670970545943",
   "startTime": "2022-12-13 22:29:05.943",
   "url": "/query/ldbc_snb/LTQ1?gap=60&qtf=vwlm_a_008",
   "elapsedTime": 2022
  },
  {
   "requestidPartial": "1670970545942",
   "startTime": "2022-12-13 22:29:05.942",
   "url": "/query/ldbc_snb/LTQ1?gap=60&qtf=vwlm_a_004",
   "elapsedTime": 2023
  },
 ],
 "code": "REST-0000"
}
```

The /abortquery API is not available for queries in the queue. The `expirationTime` attribute is also not available.   
---  
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_abort_a_query)Abort a query
`GET /restpp/abortquery/{graph_name}`
[**Required privilege**](https://docs.tigergraph.com/tigergraph-server/4.2/reference/list-of-privileges): Graph-level DELETE_DATA
This endpoint safely aborts a selected query by ID or all queries of an endpoint by endpoint URL of a graph.
If you are running a TigerGraph cluster, this endpoint only allows you to abort a query sent to the requested node, not any query in the cluster.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_sample_request_28)Sample request:
  * Request
  * Response


```
curl -X GET "localhost:14240/restpp/abortquery/poc_graph?requestid=16842763.RESTPP_1_1.1561401340785.N&requestid=16973833.RESTPP_1_1.1561401288421.N"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
{
 "version": {
  "edition": "enterprise",
  "api": "v2",
  "schema": 0
 },
 "error": false,
 "message": "",
 "results": [
  {
   "aborted_queries": [
    {
     "requestid": "16842763.RESTPP_1_1.1561401340785.N",
     "url": "/sleepgpe?milliseconds=110000"
    },
    {
     "requestid": "16973833.RESTPP_1_1.1561401288421.N",
     "url": "/sleepgpe?milliseconds=100000"
    }
   ]
  }
 ],
 "code": "REST-0000"
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_32)Parameters:
Name | Required | Description  
---|---|---  
`requestid` | No | The ID of the query to abort. It can take a single query ID or the string `"all"`. If `requestid` is set to all. It will abort all running queries.  
`url` | No | The endpoint whose running queries to abort. You must specify the base of the endpoint’s URL, but then use a wildcard to allow for different parameters. For example, to abort all running queries for the endpoint `/sleepgpe`, use `url=/sleepgpe.*`  
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_check_query_status_detached_mode)Check query status (Detached Mode)
`GET /restpp/query_status`
This endpoint allows you to check the status of a query run in [detached mode](https://docs.tigergraph.com/gsql-ref/4.1/querying/query-operations#_detached_mode_async_option).
If you are running a TigerGraph cluster, this endpoint only allows you to check the status of a query running on the node to which the request is sent, not all nodes on the cluster.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_33)Parameters:
Parameter | Required | Description  
---|---|---  
`requestid` | No | String ID of the request. The parameter can have the value `all`, in which case the endpoint returns one status report for each running request. If not specified, the value of the parameter defaults to `all`.  
`graph_name` | No | The name of the graph whose running queries to report on. If not specified, the endpoint returns queries running on the first created graph on the node to which the request is sent.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_sample_request_29)Sample request:
  * Request
  * Response


```
curl -s -X GET "http://localhost:14240/restpp/query_status?graph_name=poc_graph&requestid=4.RESTPP_1_1.1599672031541.N"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
{
 "version": {
  "edition": "enterprise",
  "api": "v2",
  "schema": 0
 },
 "error": false,
 "message": "",
 "results": [{
  "requestid": "4.RESTPP_1_1.1599672031541.N", **(1)**
  "startTime": "2020-09-09 10:20:31.541", **(2)**
  "expirationTime": "2020-09-09 10:20:47.541", **(3)**
  "url": "/query/ldbc_snb/countIndirectFriends?pid=21990232555889", **(4)**
  "elapsedTime": 19, **(5)**
  "status": "success" **(6)**
 }]
}
javascript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | The query ID associated with the given query status JSON object.  
---|---  
**2** | The timestamp for the start time of the given query.  
**3** | The timestamp for when the given query times out. The default timeout limit is 16 seconds and can be set using the [`GSQL-TIMEOUT`](https://docs.tigergraph.com/tigergraph-server/4.1/API/#_gsql_query_timeout) header.  
**4** | URL of the given query.  
**5** | Elapsed real time of the given query measured in milliseconds. For completed queries, the value shows the total runtime of the request. For ongoing queries, it shows the amount of time taken so far.  
**6** | The status of the given query. Possible values are `“success”`, `“timeout”`, `“aborted”`, or `“running”`.  
If one or more of the provided query IDs (`requestid`) are invalid, the return JSON will include an `unknown_requestid` field containing all the invalid query IDs. If a query ID is marked as unknown, it means either the query does not exist or that it was not run in Detached Mode.
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_check_query_results_detached_mode)Check query results (Detached Mode)
`GET /restpp/query_result`
This endpoint allows you to check the results of queries run in Detached Mode if they have finished running. If the query is still running, the endpoint will respond with an error and a message saying `"Unable to retrieve result for query <requestid>"`. Ensure that the query is finished before checking its result.
This endpoint only allows you to check the results of a query sent to the requested node, not any query in the graph.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_sample_request_30)Sample request:
  * Request
  * Response


```
curl -s -X GET "http://localhost:14240/restpp/query_result?requestid=196611.RESTPP_1_1.1630601692834.N"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
{
 "error": false,
 "message": "",
 "version": {
  "edition": "enterprise",
  "api": "v2",
  "schema": 0
 },
 "results": [{"vSet": [{
  "v_id": "21990232555889",
  "attributes": {"vSet.@friendCount": 13677},
  "v_type": "Person"
 }]}]
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_34)Parameters:
Name | Required | Description  
---|---|---  
`requestid` | Yes | String ID of the query.  
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_get_information_about_a_template_query)Get information about a template query
`GET /gsql/v1/library/{functionName}`
This endpoint returns the template definition, query name, and query parameters for a template query.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_sample_request_31)Sample request:
  * Request
  * Response


```
curl -X GET --user tigergraph:tigergraph --url 'http://localhost:14240/gsql/v1/library/gds.community.louvain'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
{
 "error": false,
 "message": "",
 "results": [
  {
   "query": <GSQL definition of the Louvain algorithm, omitted for length>,
   "name": "louvain",
   "params": {
    "file_path": {
     "default": "",
     "type": "STRING",
     "min_count": 0
    },
    <additional parameters for the Louvain algorithm, omitted for length>
    "e_type": {
     "max_count": 2147483647,
     "type": "STRING",
     "min_count": 0
    }
   }
  }
 ]
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_35)Parameters:
Name | Required | Description  
---|---|---  
`functionName` | Yes | The template name that will be returned in the response  
`isRegularExpression` | No | Enables regular expression searching for the function name, following [Java regular expression patterns](https://docs.oracle.com/javase/7/docs/api/java/util/regex/Pattern.html). For example, `gds.*` returns all queries that begin with `gds`.  
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_run_a_template_query)Run a template query
`POST /gsql/v1/library/{libraryName}?graph=<graph name>`
This endpoint runs a template query on a given graph. Query parameters are passed in JSON format in the body of the POST request.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_sample_request_32)Sample request:
  * Request
  * Response


```
curl -X POST --user tigergraph:tigergraph \
 --url 'http://localhost:14240/gsql/v1/library/gds.community.louvain?graph=poc_graph' \
 --data '{
      "v_type": [
       "members"
      ],
      "e_type": [
       "member_work_company"
      ],
      "wt_attr": "positionId",
      "max_iter": 10,
      "result_attr": "",
      "file_path": "",
      "print_info": true
     }'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

See the documentation for the [Louvain](https://docs.tigergraph.com/graph-ml/3.10/community-algorithms/louvain) algorithm for more information about the algorithm parameters.
JSON Algorithm Parameters
```
{
 "params":{
  "param1": 1,
  "param2": ["1","2","3"],
  "param3": false,
  "param4": ["id1", "id2"],
  "param4.type": "vertexType",
  "param5": ["id1", "id2"],
  "param6": "id",
  "param6.type": "vertexType",
 }
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
{
 "error": false,
 "message": "",
 "results": {
  "error": false,
  "message": "",
  "version": {
   "schema": 1,
   "edition": "enterprise",
   "api": "v2"
  },
  "results": [
   {"@@comp_group_by_size_map": {}},
   {"sizes": {}},
   {"Start": []}
  ]
 },
 "generatedQueryName": "gds_community_louvain_1502296930"
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_36)Parameters:
Name | Required | Description  
---|---|---  
`functionName` | Yes | The template query that will be run on the given graph.  
`graph` | Yes | The graph name that the template query will run on.  
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_data_consistency_check)Data Consistency Check
`GET /restpp/data_consistency_check`
[**Required privilege**](https://docs.tigergraph.com/tigergraph-server/4.2/reference/list-of-privileges): Global-level DELETE_DATA
In order to provide peace of mind for TigerGraph operation teams managing HA clusters, a new tool was introduced in version 3.6.3 (via a service endpoint) to check high level consistency of data on both HA and Distributed Clusters. This tool can be easily incorporated into the regular operational process to provide up-to-date summary info on the integrity of your data on all servers.
This tool checks for any discrepancies of vertex and edge counts among GPE replicas as well as between GPE and GSE. If there is a discrepancy, it reports a list of the cluster nodes, vertices, and edges that are mismatched. On a distributed cluster (a cluster with more than one partition), this tool performs the check on each node of the partition cluster and returns results for all nodes. If a discrepancy is detected, we recommend that you contact TigerGraph Support for the best way to restore consistency.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_37)Parameters:
Name | Required | Description  
---|---|---  
`threadnum` | No | Integer that indicates the number of threads used to execute the deleted vertex check jobs. This parameter is optional and the default value is `6` if none is provided.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_sample_request_33)Sample request:
  * Request
  * Response


```
curl -X GET http://localhost:14240/restpp/data_consistency_check | jq .
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
{
 "version": {
  "edition": "enterprise",
  "api": "v2",
  "schema": 0
 },
 "error": false,
 "message": "check passed",
 "results": {
  "GPESelfCheck": [
   {
    "Partition": 1,
    "PassCheck": true,
    "UnSyncList": []
   }
  ],
  "GPEGSECheck": [
   {
    "GPE": "GPE_1_1",
    "PassCheck": true,
    "UnSyncList": []
   }
  ]
 },
 "code": "REST-0000"
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_path_finding_algorithms)Path-Finding Algorithms
The TigerGraph platform comes with two built-in endpoints, `/shortestpath` and `/allpaths`, which return either the shortest or all unweighted paths connecting a set of source vertices to a set of target vertices. The table below summarizes the two path-finding endpoints.
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_input_parameters_and_output_format_for_path_finding)Input Parameters and Output Format for Path-Finding
Each REST endpoint reads a JSON-formatted payload that describes the input parameters. These parameters specify which vertices and edges may be on the paths, additional conditions on the attributes of the vertices and edges, and the maximum length of a path.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_source_and_target_vertices)Source and target vertices
Each endpoint must have either a **source** or **sources** key and either a **target** or **targets** parameter. The source and target parameters describe a single vertex. The format for a vertex object is as follows:
`{"type" : "<vertex_type_name>", "id" : "<vertex_id>"}.`
The sources and targets parameters are JSON arrays containing a list of vertex objects.
**Filters** The payload may also have an array of filter conditions, to restrict the vertices or edges in the paths. Each individual filter is a JSON object which describes a condition on one vertex type or edge type. A filter object has one or two key-value pairs:
`{"type": "<vertex_or_edge_type>", "condition": "<attribute_condition>"}`
  * `"type":` the vertex type or edge type to be filtered
  * `"condition"` (optional): a boolean expression on one attribute of the given vertex type or edge type. `and` and `or` may be used to make compound expressions.


Example of a filter array:
```
[{"type": "bought", "condition": "price < \"100\" and quality == \"good\""},
 {"type": "sold",  "condition": "price > \"100\" or quality != \"good\""}]
markup![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Note that all filtering conditions in **`vertexFilters`**and**`edgeFilters`**are combined with the`or` relationship, i.e., if a vertex (or edge) fulfills any one of the filter conditions, then this vertex (or edge) will be included in the resulting paths.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_output)Output
The JSON output is a list of vertices and a list of edges. Each vertex and each edge is listed in full with all attributes. The collections of vertices and edges are not in path order.
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_find_shortest_path)Find shortest path
`POST /restpp/shortestpath/{graph_name}`
This endpoint takes a source vertex or a set of source vertices and a target vertex or a set of target vertices. It returns the shortest path between the source and the target. If the source is a set of vertices, the resulting path will begin with one of the vertices in the set. If the target is a set of vertices, the resulting path will end with one of the vertices in the set.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_request_body_6)Request body:
This endpoint expects a request body that describes the source and target vertex or vertex set. Below is a table of all the fields in the request body.
Key | Type | Description  
---|---|---  
`source` | vertex object | Each path must start from this vertex. Mutually exclusive with `sources`.  
`sources` | vertex array | Each path must start from one of these vertices. Mutually exclusive with `source`.  
`target` | vertex object | Each path must end at this vertex. Mutually exclusive with `targets`.  
`targets` | vertex array | Each path must end at one of these vertices. Mutually exclusive with `target`.  
`vertexFilters` | filter array | (OPTIONAL) Restrict the paths to those whose vertices satisfy any of the given filters.  
`edgeFilters` | filter array | (OPTIONAL) Restrict the paths to those whose edges satisfy any of the given filters. See details of filters above.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_sample_request_34)Sample request:
  * Request
  * Response


```
curl -s -X POST "http://localhost:14240/restpp/shortestpath/movieNet" \
-d '{
 "sources":[{"type":"VidUser","id":"2"}],
 "targets":[{"type":"VidUser","id":"0"}, {"type":"VidUser","id":"3"}],
 "edgeFilters":[{"type":"User_Video","condition":"rating > 5 and date_time > 1000"}],
 "maxLength":4
}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
{
 "version": { "edition": "developer", "api": "v2", "schema": 0 },
 "error": false,
 "message": "Cannot get 'vertex_filters' filters, use empty filter.",
 "results": [
  {
   "vertices": [
    { "v_id": "3","v_type": "VidUser","attributes": { "name": "Dale" }},
    { "v_id": "0","v_type": "Video","attributes": { "name": "Solo", "year", 2018 }},
    { "v_id": "0","v_type": "VidUser","attributes": { "name": "Angel" }},
   ],
   "edges": [
    {
     "e_type": "User_Video", "from_id": "0", "from_type": "Video",
     "to_id": "0", "to_type": "VidUser", "directed": false,
     "attributes": { "rating": 6.8, "date_time": 15000 }
    },
    {
     "e_type": "User_Video", "from_id": "0", "from_type": "Video",
     "to_id": "3", "to_type": "VidUser", "directed": false,
     "attributes": { "rating": 6.6, "date_time": 16000 }
    }
   ]
  }
 ]
}
javascript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_38)Parameters:
Key | Required | Description  
---|---|---  
`maxLength` | No | Integer that specified the maximum length of a shortest path. The default value is 6.  
`allShortestPaths` | No | If **true** , the endpoint will return all shortest paths between the source and target. Default is **false** , meaning that the endpoint will return only one path.  
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_find_all_paths)Find all paths
`POST /restpp/allpaths/{graph_name}`
This endpoint finds all paths between a source vertex (or vertex set) and target vertex (or vertex set).
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_request_body_7)Request body:
This endpoint expects a request body that describes the source and target vertex or vertex set. Below is a table of all the fields in the request body.
Key | Type | Description  
---|---|---  
`source` | vertex object | Each path must start from this vertex. Mutually exclusive with `sources`.  
`sources` | vertex array | Each path must start from one of these vertices. Mutually exclusive with `source`.  
`target` | vertex object | Each path must end at this vertex. Mutually exclusive with `targets`.  
`targets` | vertex array | Each path must end at one of these vertices. Mutually exclusive with `target`.  
`vertexFilters` | filter array | (OPTIONAL) Restrict the paths to those whose vertices satisfy any of the given filters.  
`edgeFilters` | filter array | (OPTIONAL) Restrict the paths to those whose edges satisfy any of the given filters. See details of filters above.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_parameters_39)Parameters:
Name | Required | Description  
---|---|---  
`maxLength` | Yes | Maximum path length.  
The current implementation of this endpoint will include paths with loops. Since it is possible to go around a loop an infinite number of times, it is important that you select the smallest value of maxLength which you consider appropriate. Even if there are no loops in your graph, a smaller maxLength will allow your query to run faster.  
---  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints#_sample_request_35)Sample request:
The example below requests all paths up to maximum length `3` between the source vertex set `{Video 0}` and the target vertex set `{AttributeTag "action"}`. The path may only contain Video vertices where `year >= 1984`. The result includes 3 paths: AttrributeTag "action" — Video 0 AttrributeTag "action" — Video 3 — VidUser 4 — Video 0 AttrributeTag "action" — Video 2 — VidUser 0 — Video 0
  * Request
  * Response


```
curl -s -X POST "http://localhost:14240/restpp/allpaths/movieNet" -d '{
 "sources":[{"type":"Video","id":"0"}],
 "targets":[{"type": "AttributeTag", "id":"action"}],
 "vertexFilters":[{"type":"Video", "condition":"year >= 1984"}],
 "maxLength": 3
}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

```
{
 "version": { "edition": "developer", "api": "v2", "schema": 0 },
 "error": false,
 "message": "Cannot get 'edge_filters' filters, use empty filter.",
 "results": [
  {
   "vertices": [
    { "v_id": "action","v_type": "AttributeTag","attributes": {}},
    { "v_id": "3","v_type": "VidUser","attributes": { "name": "Dale" }},
    { "v_id": "0","v_type": "VidUser","attributes": { "name": "Angel" }},
    { "v_id": "0","v_type": "Video","attributes": { "name": "Solo", "year": 2018 }},
    { "v_id": "2","v_type": "Video","attributes": { "name": "Thor", "year": 2011 }},
    { "v_id": "4","v_type": "Video","attributes": { "name": "Ran", "year": 1985 }}
   ],
   "edges": [
    {
     "e_type": "Video_AttributeTag", "from_id": "0", "from_type": "Video",
     "to_id": "action", "to_type": "AttributeTag", "directed": false,
     "attributes": { "weight": 1, "date_time": 0 }
    },
    {
     "e_type": "Video_AttributeTag", "from_id": "4", "from_type": "Video",
     "to_id": "action", "to_type": "AttributeTag", "directed": false,
     "attributes": { "weight": 1, "date_time": 11000 }
    },
    {
     "e_type": "User_Video", "from_id": "3", "from_type": "VidUser",
     "to_id": "4", "to_type": "Video", "directed": false,
     "attributes": { "rating": 8.4, "date_time": 12000 }
    },
    {
     "e_type": "User_Video", "from_id": "3", "from_type": "VidUser",
     "to_id": "0", "to_type": "Video", "directed": false,
     "attributes": { "rating": 6.6, "date_time": 16000 }
    },
    {
     "e_type": "Video_AttributeTag", "from_id": "2", "from_type": "Video",
     "to_id": "action", "to_type": "AttributeTag", "directed": false,
     "attributes": { "weight": 1, "date_time": 0 }
    },
    {
     "e_type": "User_Video", "from_id": "2", "from_type": "VidUser",
     "to_id": "0", "to_type": "Video", "directed": false,
     "attributes": { "rating": 7.4, "date_time": 17000 }
    },
    {
     "e_type": "User_Video", "from_id": "0", "from_type": "Video",
     "to_id": "0", "to_type": "VidUser", "directed": false,
     "attributes": { "rating": 6.8, "date_time": 15000 }
    }
   ]
  }
 ]
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Other versions of pathfinding algorithms are available in the [GSQL Graph Algorithm Library](https://docs.tigergraph.com/graph-ml/3.10/intro/).
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


