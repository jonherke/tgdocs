![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log)[Next](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log)
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
  * [Audit Logs](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/4.1/modules/troubleshooting/pages/audit-log.adoc)
### Contents
  * [Key Features](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_key_features)
  * [Considerations](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_considerations)
  * [Security](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_security)
  * [Performance and Scalability](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_performance_and_scalability)
  * [Configuration Commands](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_configuration_commands)
  * [Apply Configuration Changes](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_apply_configuration_changes)
  * [Setup Environment](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_setup_environment)
  * [Log File Policy](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_log_file_policy)
  * [Other Customizable Configs](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_other_customizable_configs)
  * [Consuming Audit Logs](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_consuming_audit_logs)
  * [Log Format](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_log_format)
  * [GSQL Service Audit Logs](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_gsql_service_audit_logs)
  * [REST++ API Call Audit Logs](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_rest_api_call_audit_logs)
  * [gadmin Audit Logs](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_gadmin_audit_logs)
  * [Known Issues](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_known_issues)


# Audit Logs
### Contents
  * [Key Features](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_key_features)
  * [Considerations](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_considerations)
  * [Security](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_security)
  * [Performance and Scalability](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_performance_and_scalability)
  * [Configuration Commands](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_configuration_commands)
  * [Apply Configuration Changes](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_apply_configuration_changes)
  * [Setup Environment](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_setup_environment)
  * [Log File Policy](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_log_file_policy)
  * [Other Customizable Configs](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_other_customizable_configs)
  * [Consuming Audit Logs](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_consuming_audit_logs)
  * [Log Format](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_log_format)
  * [GSQL Service Audit Logs](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_gsql_service_audit_logs)
  * [REST++ API Call Audit Logs](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_rest_api_call_audit_logs)
  * [gadmin Audit Logs](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_gadmin_audit_logs)
  * [Known Issues](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_known_issues)


Audit logs maintain a historical record of activity events, noting the time, responsible user or service, and affected entity.
Audit logs enable organizations to meet certain compliance and business policy requirements. Additionally, Administrators use audit logs to track user activity, and security teams use them to investigate breaches and ensure regulatory compliance.
## [](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_key_features)Key Features
  * The audit logs are structured in JSON format, ensuring machine-readability.
  * This format facilitates easy integration with third-party tools.
  * It eliminates the need for users to navigate through numerous log files.


## [](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_considerations)Considerations
### [](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_security)Security
  * Like other `gadmin` configurations, only the Linux user with server access can enable and configure the audit log.
  * Access to the audit log is restricted to those who have access to TigerGraph logs.
  * Sensitive data or PII in the audit log, such as credentials or sensitive query payload information is masked by default.


### [](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_performance_and_scalability)Performance and Scalability
  * Enabling audit logging records audit logs to separate files, adding a slight disk I/O workload. However, compared to the debug log, the audit log contains significantly less data, ensuring negligible performance impact.


## [](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_configuration_commands)Configuration Commands
Table 1. Users can enable, disable, and configure audit logging with the following `gadmin` configs: Configuration | Description | Type (Default Value)  
---|---|---  
`System.Audit.Enable` | Setting to enable audit logs. | boolean (false)  
`System.Audit.DataBaseName` | Modify the DataBaseName field in log file header. | name (TigerGraph)  
`System.Audit.LogDirRelativePath` | Modify the relative audit log path. | path string (<TG_LogRoot>/AuditLog/)  
`System.Audit.LogConfig.LogFileMaxDurationDay` | Modify the modification date when a new audit log file is created. | Integer (90)  
`System.Audit.LogConfig.LogFileMaxSizeMB` | Modify the audit log file’s max size. | Integer (100)  
`System.Audit.LogConfig.LogRotationFileNumber` | Modify the max amount of Audit Log files in the Audit Log folder. | Integer (100)  
`System.Audit.MaskPII` | Mask Sensitive data or PII in the audit log. | Default value is: `true`  
Additionally, all audit log files are stored in JSON format. Each log entry is a JSON object, and the log file is one JSON array of these objects.
For more information see section [Consuming Audit Logs](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_consuming_audit_logs) or for a complete list of TigerGraph `gadmin` configs see [Configuration Parameters](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters).
### [](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_apply_configuration_changes)Apply Configuration Changes
If you use `gadmin` config to change any of these parameters, you need to run `gadmin config apply -y` for it to take effect. You can change multiple parameters and then run `gadmin config apply` for all of them together
After modifying the configurations, run the following command to apply the changes:
```
$ gadmin config apply -y
$ gadmin restart gsql -y
```

## [](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_setup_environment)Setup Environment
Audit logging is disabled by default in a TigerGraph system.
To enable audit logging, use `gadmin` to run the following command to enable the setting:
```
$ gadmin config set System.Audit.Enable true
```

Once enabled, the audit log will be found in the `<System.LogRoot>/AuditLog` folder. The `<System.LogRoot>` represents the default path for all TigerGraph logs, set to `tigergraph/log` by default.
To customize the relative path for the audit log (in relation to `<System.LogRoot>`), execute the following command:
```
$ gadmin config set System.Audit.LogDirRelativePath <audit-log-relative-path>
```

You can also modify the <System.LogRoot> on your environment by:
```
$ gadmin config set System.LogRoot <log-root-path>
```

Take note that altering `<System.LogRoot>` impacts the root path for all TigerGraph logs.  
---  
## [](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_log_file_policy)Log File Policy
A new audit log file will be created when **any** of the following situations occur:
  * The GSQL service is restarted.
  * The latest audit log file size exceeds the `System.Audit.LogConfig.LogFileMaxSizeMB` value. The value of this field is `100MB` by default.
You can modify this value by running the following command:
```
$ gadmin config set System.Audit.LogConfig.LogFileMaxSizeMB <file-size>
```

  * Log files will be removed if its lifetime exceeds `System.Audit.LogConfig.LogFileMaxDurationDay`. The value of this field is `90` days by default.
You can modify this value by running the following command:
```
$ gadmin config set System.Audit.LogConfig.LogFileMaxDurationDay <max-duration-day>
```

  * Lastly, the oldest audit log file will be automatically deleted, if the amount of audit logs in the audit log folder exceeds the `System.Audit.LogConfig.LogRotationFileNumber` value. The default of this value is `100` audit logs.
You can modify this value by running the following command:
```
$ gadmin config set System.Audit.LogConfig.LogRotationFileNumber <file-number>
```



### [](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_other_customizable_configs)Other Customizable Configs
There is a “DatabaseName” field appended to the header of each audit log file. The value of this field is "TigerGraph" by default.
You can modify this value by running the following command:
```
$ gadmin config set System.Audit.DataBaseName <database-name>
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_gadmin_customizable_configs)`gadmin` Customizable Configs
You can configure `gadmin` command’s audit logging rotation rules with the following gadmin configs:
You can modify the lifetime of a file with the following command:
```
gadmin config set Gadmin.BasicConfig.LogConfig.LogFileMaxDurationDay: <lifetime of a file>
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

You can modify the file rotation size with the following command:
```
gadmin config set Gadmin.BasicConfig.LogConfig.LogFileMaxSizeMB: <file rotation size>
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

You can modify the rotation file number with the following command:
```
gadmin config set Gadmin.BasicConfig.LogConfig.LogRotationFileNumber: <the rotation file number>
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_consuming_audit_logs)Consuming Audit Logs
### [](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_log_format)Log Format
All audit log files are stored in JSON format, even when users are actively interacting with TigerGraph, so audit logs can be consumed at run time.
Audit log files are separated by GSQL service and REST++ API calls. Both having separate file names:
  * `log.AUDIT-GSQL` for the GSQL service.
  * `log.Audit-RESTPP` for direct REST++ API calls.
  * `log.Audit-GADMIN` for `gadmin` command executions.

  
---  
Here is an example of a whole audit log file:
```
[
  {"serverHostIP":"127.0.0.1","databaseName":"TigerGraph","version":"1.0","timestamp":"2023-12-20T14:42:50.243-07:00"},
  {"endpoint":"/gsql/file","clientHost":"127.0.0.1:43746","clientOSUsername":"tigergraph","userAgent":"GSQL Shell","userName":"tigergraph","authType":"USER_PASS","message":"Successfully created user 'u1'.","timestamp":"2023-12-20T14:42:50.243-07:00","actionName":"createUser","status":“SUCCESS”},
  {"endpoint":"/gsql/file","clientHost":"127.0.0.1:54746","clientOSUsername":"tigergraph","userAgent":"GSQL Shell","userName":"tigergraph","authType":"USER_PASS","message":"Successfully created query 'printVertex'.","timestamp":"2023-12-20T14:42:50.243-07:00","actionName":"createQuery","status":“SUCCESS”},
  {"endpoint":"/gsql/library","clientHost":"127.0.0.1:54770","clientOSUsername":"tigergraph",,"userName":"tigergraph","authType":"USER_PASS","message":"callTemplateQuery succeed","timestamp":"2023-12-20T14:42:50.243-07:00","actionName":"callTemplateQuery","status":“SUCCESS”}
]
```

  * Each audit log file is a JSON array of JSON objects, one object per log entry.
  * Each object is formatted as a single line for better readability of high volume data.


### [](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_gsql_service_audit_logs)GSQL Service Audit Logs
The first JSON object is the header of this file, which consists of the following fields:
```
{
  "version": "1.0",
  "timestamp":"2023-12-20T14:42:50.243-07:00",
  "dataBaseName": "TigerGraph",
  "serverHostIP": "192.168.1.1",
}
```

The GSQL audit log will record any user-triggered activity handled by the GSQL server, whether initiated by a GSQL shell command or sent as a REST request to the GSQL server. This includes operations such as:
  * Log in
  * Change password
  * Create or drop a user
  * Grant/drop a role (the role and target username are logged)
  * Create a secret (the secret alias is logged)
  * Create a query
  * Run/interpret a query
  * Create a loading job
  * Run a loading job


In general, the log entry include the timestamp, the user id, the action type, and the object being acted on. The graph name is logged for queries and loading jobs.
The following information is masked (excluded from the audit logs) by default, but it will be included if the system configuration parameter `System.Audit.MaskPII` is set to `false`:
  * The body of a query, when creating a query
  * Input argument values, when running or interpreting a query
  * Filename(s) of the data source, when running a loading job

  
---  
Each activity will have its own audit log entry and fields.  
---  
The `createQuery` activity will produce an audit log entry with the following fields:
```
{
  "timestamp":"2023-12-20T14:42:50.243-07:00",
  "userName": "tigergraph",
  "authType": "password",
  "clientHost": "<IP or FQDN>:<Port>",
  "clientOSUsername":"OSusername",
  "userAgent": "GSQL Shell",
  "endpoint": "/gsql/file",
  "actionName": "createQuery",
  "status": “SUCCESS”,
  "message": "Successfully created query 'query_name'"
}
```

For user `login/auth` related activities, one more field called `failedAttempts` is added to the JSON. This field indicates how many times this user failed to provide the correct credentials.
Here is an example for user login event:
```
{
  "timestamp": "2023-12-20T14:42:50.243-07:00",
  "userName": "tigergraph",
  "authType": "SAML SSO",
  "clientHost": "<IP or FQDN>:<Port>",
  "clientOSUsername":"tigergraph",
  "userAgent": "GraphStudio",
  "endpoint": "/gsql/simpleauth",
  "actionName": "login",
  "failedAttempts" : 1,
  "status" : "FAILURE",
  "message": "Username doesn't exist"
}
```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_rest_api_call_audit_logs)REST++ API Call Audit Logs
Audit logs for REST++ calls are found in the `log.Audit-RESTPP` file. They are similar to GSQL service audit logs, such as, the status for API calls will be either `SUCCESS` or `FAILURE`, but they are different in these ways:
  * The duration is the runtime cost with seconds.
  * The code will be the return codes from the REST++ server, see [Return Codes](https://docs.tigergraph.com/tigergraph-server/4.2/reference/return-codes#_rest).
  * A new field `requestId` is also added.


Values in `requestParams` and `requestBody` will be masked if they contain PII data.
Here is an example of the REST++ call event:
```
{
 "timestamp": "2023-10-02T15:06:18.365Z",
 "userName": "tigergraph",
 "authType": "token",
 "clientHost": "<IP or FQDN>:<Port>",
 "userAgent": "curl",
 "endpoint": "/restpp/query/{graph_name}/{query_name}",
 "actionName": "runQuery",
 "status": "SUCCESS",
 "duration": 3.24,
 "requestId": "16842763.RESTPP_1_1.1561401340785.N",
 "requestParams": "",
 "requestBody": "",
 "code": "REST-0000",
 "message": "<success/error message>"
}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_gadmin_audit_logs)gadmin Audit Logs
Audit logs for gadmin command executions are found in the `log.Audit-GADMIN` file.
Besides the basic information such as `timestamp`, `OS`, `username`, they capture the `gadmin` commands executed on the node and the outcomes:
Here is an example of the event after running command: `gadmin start all`
```
{
"timestamp": "2024-05-13 23:45:34.940",
"session id": 1418,
"OS username": "tigergraph",
"host": "10.128.0.48",
"command": "gadmin start all",
"status": "SUCCESS"
}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/4.1/troubleshooting/audit-log#_known_issues)Known Issues
  * Even when REST++ authentication is enabled and when a request that failed due to an invalid request parameter, the username in the corresponding audit log will be marked as `unknown` instead of the actual username.
    * This is because request parameter validation happens before token validation. Thus, REST++ calls do not know the username before it gets printed in the audit log.
  * If the user logs into TG Cloud using SSO, they will not be required to provide credentials again when opening GraphStudio.
    * Therefore, the login event would not be reflected in the audit log, but the user’s subsequent operations (`create query`, `install query`, etc.) will be recorded in the audit log as normal.
  * [Fixed in 3.10.2 and 4.1.1] The real client IP address could be removed or masked by a firewall or another intermediate redirect layer before arriving at the TigerGraph service.
    * Thus, TigerGraph cannot get the actual client ip, instead it will put the ip address of the last layer who forwarded the request to TigerGraph service in the audit log.


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


