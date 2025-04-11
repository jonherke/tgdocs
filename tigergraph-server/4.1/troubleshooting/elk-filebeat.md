![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/elk-filebeat)[Next](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/elk-filebeat)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/elk-filebeat)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/elk-filebeat)
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
  * Additional Resources
  * Troubleshooting and FAQs
  * [Log Files](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/log-files)
  * [Set up Log Viewing with Elasticsearch, Kibana and Filebeat](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/elk-filebeat)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/4.1/modules/troubleshooting/pages/elk-filebeat.adoc)
### Contents
  * [1. Before you begin](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/elk-filebeat#_before_you_begin)
  * [2. Procedure](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/elk-filebeat#_procedure)
  * [2.1. Configure Elasticsearch for remote access](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/elk-filebeat#configure-elasticsearch-for-remote-access)
  * [2.2. Configure Kibana with Elasticsearch and enable remote access](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/elk-filebeat#configure-kibana-with-elasticsearch-and-enable-remote-access)
  * [3. Configure Filebeat](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/elk-filebeat#configure-filebeat)


# Set up Log Viewing with Elasticsearch, Kibana and Filebeat
### Contents
  * [1. Before you begin](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/elk-filebeat#_before_you_begin)
  * [2. Procedure](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/elk-filebeat#_procedure)
  * [2.1. Configure Elasticsearch for remote access](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/elk-filebeat#configure-elasticsearch-for-remote-access)
  * [2.2. Configure Kibana with Elasticsearch and enable remote access](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/elk-filebeat#configure-kibana-with-elasticsearch-and-enable-remote-access)
  * [3. Configure Filebeat](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/elk-filebeat#configure-filebeat)


The TigerGraph system produces extensive and detailed logs about each of its components. Starting with TigerGraph 3.2, TigerGraph provides a `gadmin` utility that allows users to easily view log files through an Elasticsearch, Kibana, and Filebeat setup. This page offers a step-by-step guide to set up log viewing for all components in a TigerGraph cluster with Elastic search, Kibana, and Filebeat.
## [](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/elk-filebeat#_before_you_begin)1. Before you begin
  * [Install Elasticsearch](https://www.elastic.co/guide/en/elasticsearch/reference/current/install-elasticsearch.html) on a machine that is running TigerGraph.
    * If you have a TigerGraph cluster, you only need to install Elasticsearch on one node.
  * [Install Kibana](https://www.elastic.co/guide/en/kibana/current/install.html) on the same machine where you installed Elasticsearch.
  * [Install Filebeat](https://www.elastic.co/guide/en/beats/filebeat/current/filebeat-installation-configuration.html).
    * If you have a TigerGraph cluster, you need to install Filebeat on all nodes in the cluster.


## [](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/elk-filebeat#_procedure)2. Procedure
### [](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/elk-filebeat#configure-elasticsearch-for-remote-access)2.1. Configure Elasticsearch for remote access
The default Elasticsearch settings only allow the Elasticsearch service to be accessed from the same machine it starts from. In order to allow Elasticsearch to receive log files from other servers in the cluster, we have to make the following edits to the file at `/etc/elasticsearch/elasticsearch.yml`
```
network.host: "<server_private_ip>"
discovery.seed_hosts: ["<server_private_ip>"]
# server_private_ip refers to the private ip address of the machine where
# elasticsearch is installed
cluster.initial_master_nodes: [ "node-1" ]
# "node-1" is the default name of the Elasticsearch node. If you changed
# the default name, you would use the name you chose instead
```

After editing the configurations, restart the Elasticsearch service.
Elasticsearch is a memory-intensive service. For more information on memory management for Elasticsearch, see [ Managing and Troubleshooting Elasticsearch Memory](https://www.elastic.co/blog/managing-and-troubleshooting-elasticsearch-memory).
### [](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/elk-filebeat#configure-kibana-with-elasticsearch-and-enable-remote-access)2.2. Configure Kibana with Elasticsearch and enable remote access
You need to make the following changes to the file at `/etc/kibana/kibana.yml:`
  * To allow remote access, change the value of `server.host` to the IP address or DNS name of the Kibana server. Since the Kibana server is on the same machine as Elasticsearch, this value should be the same private IP that you specified as Elasticsearch’s `network.host`.
  * Additionally, you need to provide the address of the Elasticsearch server in the `elasticsearch.hosts` setting. By default, Elasticsearch is on port 9200, so the value for this setting should be `["server_private_ip:9200"]`


After editing the configurations, restart the Kibana service.
## [](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/elk-filebeat#configure-filebeat)3. Configure Filebeat
Finally, we need to configure Filebeat to have each component on each node send its logs to the Elasticsearch server. To do so, run the following gadmin command:
```
gadmin log build filebeat <--host={ip_address_1}[,{ip_address_n}]*>
```

The command outputs a Filebeat configuration file `filebeat.yml` . The following options are available:
Option | Description  
---|---  
`--host=<ip_list>` | Required. The list of IP addresses of the nodes whose logs you want to send to the Elasticsearch server. Example: `+ --host=10.128.0.97,10.128.0.99,10.128.0.100+`  
`--from-beginning` | Optional. If this flag is provided, Filebeat will harvest all log files including the oldest. If not included, Filebeat will only harvest the logs since the most recent time each service started.  
`--path=<path_to_file>` | Optional. The path to output the configuration file. By default, the command outputs the configuration file `filebeat.yml` to the current directory.  
`--service=<service_list>` | Optional. The services you want Filebeat to monitor. By default, all services are included. Example: --service=  
After generating the `filebeat.yml` file, copy it to the directory `/etc/filebeat` on every node, and restart the Filebeat service on each node.
After the service restarts, you should be able to view the logs through Kibana’s user interface in your browser at `server_ip:5601`.
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


