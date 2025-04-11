![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest)[Next](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest)
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
  * [Security](https://docs.tigergraph.com/tigergraph-server/4.1/security/)
  * [Encrypting Data At Rest](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/4.1/modules/security/pages/encrypting-data-at-rest.adoc)
### Contents
  * [Encryption Levels](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_encryption_levels)
  * [Kernel-level Encryption](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_kernel_level_encryption)
  * [User-Level Encryption](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_user_level_encryption)
  * [Example 1: Kernel-mode file system encryption with dm-crypt](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_example_1_kernel_mode_file_system_encryption_with_dm_crypt)
  * [Prerequisites](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_prerequisites)
  * [Instructions](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_instructions)
  * [Performance Evaluation](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_performance_evaluation)
  * [Example 2: Encrypting Data on Amazon EC2](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_example_2_encrypting_data_on_amazon_ec2)
  * [Prerequisites](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_prerequisites_2)
  * [Create an S3 Bucket](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_create_an_s3_bucket)
  * [Configure IAM roles and permission for the S3 bucket](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_configure_iam_roles_and_permission_for_the_s3_bucket)
  * [Create a KMS Key (optional)](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_create_a_kms_key_optional)
  * [Encrypt a secret password with KMS and store it in the S3 bucket](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_encrypt_a_secret_password_with_kms_and_store_it_in_the_s3_bucket)
  * [Configure EC2 with role and launch configurations](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_configure_ec2_with_role_and_launch_configurations)
  * [Performance](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_performance)


# Encrypting Data At Rest
### Contents
  * [Encryption Levels](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_encryption_levels)
  * [Kernel-level Encryption](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_kernel_level_encryption)
  * [User-Level Encryption](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_user_level_encryption)
  * [Example 1: Kernel-mode file system encryption with dm-crypt](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_example_1_kernel_mode_file_system_encryption_with_dm_crypt)
  * [Prerequisites](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_prerequisites)
  * [Instructions](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_instructions)
  * [Performance Evaluation](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_performance_evaluation)
  * [Example 2: Encrypting Data on Amazon EC2](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_example_2_encrypting_data_on_amazon_ec2)
  * [Prerequisites](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_prerequisites_2)
  * [Create an S3 Bucket](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_create_an_s3_bucket)
  * [Configure IAM roles and permission for the S3 bucket](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_configure_iam_roles_and_permission_for_the_s3_bucket)
  * [Create a KMS Key (optional)](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_create_a_kms_key_optional)
  * [Encrypt a secret password with KMS and store it in the S3 bucket](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_encrypt_a_secret_password_with_kms_and_store_it_in_the_s3_bucket)
  * [Configure EC2 with role and launch configurations](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_configure_ec2_with_role_and_launch_configurations)
  * [Performance](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_performance)


## [](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_encryption_levels)Encryption Levels
The TigerGraph graph data store uses a proprietary encoding scheme which both compresses the data and obscures the data unless the user knows the encoding/decoding scheme. In addition, the TigerGraph system supports integration with industry-standard methods for encrypting data when stored in disk ("data at rest").
Data at rest encryption can be applied at many different levels. A user can choose to use one or more level.
Encryption Level | Description | TigerGraph Support  
---|---|---  
Hardware | Use specialized hard disks which perform automatic encryption on write and decryption on read (by authorized OS users) | Invisible to TigerGraph  
Kernel-level file system | Use Linux built-in utilities to encrypt data. Root privilege required. | Invisible to TigerGraph  
User-level file system | Use Linux built-in utilities and customized libraries to encrypt data. Root privilege is not required. | Invisible to TigerGraph  
### [](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_kernel_level_encryption)Kernel-level Encryption
File system encryption employs advanced encryption algorithms. Some tools allow the user to select from a menu of encryption algorithms. It can be done either in kernel mode or user mode. To run in kernel mode, superuser permission is required.
Since Linux 2.6, device-mapper has been an infrastructure, which provides a generic way to create virtual layers of block devices with transparent encryption blocks using the kernel crypto API.
In Ubuntu, full-disk encryption is an option during the OS installation process. For other Linux distributions, the disk can be encrypted with [dm-encrypt](https://wiki.archlinux.org/index.php/Dm-crypt).
A commonly used utility is [eCryptfs](http://ecryptfs.org/), which is licensed under GPL, and it is built into some kernels, such as Ubuntu.
### [](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_user_level_encryption)User-Level Encryption
If root privilege is not available, a workaround is to use FUSE (Filesystem in User Space) to create a user-level filesystem running on top of the host operating system. While the performance may not be as good as running in kernel mode, there are more options available for customization and tuning.
## [](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_example_1_kernel_mode_file_system_encryption_with_dm_crypt)Example 1: Kernel-mode file system encryption with dm-crypt
In this example, we use dm-crypt to provide kernel-mode file system encryption. The dm-crypt utility is widely available and offers a choice of encryption algorithms. It also can be set to encrypt various units of storage — full disk, partitions, logical volumes, or files.
The basic idea of this solution is to create a file, map an encrypted file system to it, and mount it as a storage directory for TigerGraph with R/W permission only to authorized users.
### [](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_prerequisites)Prerequisites
Before you start, you will need a Linux machine on which
  * you have root permission,
  * the TigerGraph system has not yet been installed,
  * and you have sufficient disk space for the TigerGraph data you wish to encrypt. This may be on your local disk or on a separate disk you have mounted.


### [](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_instructions)Instructions
  * Install cryptsetup (cryptsetup is included with Ubuntu, but other OS users may need to install it with yum).
  * Install the TigerGraph system.
  * Grant sudo privilege to the TigerGraph OS user.
  * Stop all TigerGraph services with the following commands: gadmin stop all -y gadmin stop admin -y
  * Acting as the tigergraph OS user, run the following export commands to set variables. Replace the placeholders enclosed in angle brackets <…​> with the values of your choice:


```
# The username for TigerGraph Database System, for example: tigergraph
export db_user='<username>'
# The path of encrypted file to be created for TigerGraph storage, for example: /home/tigergraph/secretfs
export encrypted_file_path='<path-to-encrypted-file>'
# The size of encrypted file to be created (used by dd command), for example: 60G
export encrypted_file_size=<storage-size>
# The password for the encrypted file, for example: DataAtRe5tPa55w0rd
export encryption_password='<password>'
# The root directory for tigergraph, for example: $HOME/tigergraph
export tigergraph_data_root="<tigergraph-data-root>"
# Set the first available loop device for encrypted file mapping
export loop_device=$(losetup -f)
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * Create a file for TigerGraph data storage.


```
dd of=$encrypted_file_path bs=$encrypted_file_size count=0 seek=1
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * Change the permission of the file so that only the owner of the file (that is, only the tigergraph user who created the file in the previous step) will be able to access it:


```
chmod 600 $encrypted_file_path
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * Associate a loopback device with the file:


```
sudo losetup $loop_device $encrypted_file_path
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * Encrypt storage in the device. cryptsetup will use the Linux device mapper to create, in this case, $encrypted_file_path . Initialize the volume and set a password interactively with the password you set to $encryption_password :


```
sudo cryptsetup -y luksFormat $loop_device
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

If you are trying to automate the process with a script running with root TTY session , you may use the following command:
```
echo "$encryption_password" | cryptsetup -y luksFormat $loop_device
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * Open the partition, and create a mapping to $encrypted_file_path :


```
sudo cryptsetup luksOpen $loop_device tigergraph_gstore
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

If you are trying to automate the process with a script running with root TTY session , you may use the following command:
```
echo "$encryption_password" | cryptsetup luksOpen $loop_device tigergraph_gstore
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * Clear the password from bash variables and bash history.


The following commands may clear your previous bash histories as well. Instead, you may edit ~/.bash_history to selectively delete the related entries.  
---  
```
unset encryption_password
history -c
history -w
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * Create a file system and verify its status:


```
sudo mke2fs -j -O dir_index /dev/mapper/tigergraph_gstore
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * Mount the new file system to /mnt/secretfs:


```
sudo mkdir -p /mnt/secretfs
sudo mount /dev/mapper/tigergraph_gstore /mnt/secretfs
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * Change the permission to 700 so that only $db_user has access to the file system:


```
sudo chmod -R 700 /mnt/secretfs
sudo chown -R $db_user:$db_user /mnt/secretfs
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * Move the original TigerGraph files to the encrypted filesystem and make a symbolic link. If you wish to encrypt only the TigerGraph data store (called gstore), use the following commands:


```
mv $tigergraph_data_root/gstore /mnt/secretfs/gstore
ln -s /mnt/secretfs/gstore $tigergraph_data_root/gstore
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

There are other TigerGraph files which you might also consider to be sensitive and wish to encrypt. These include the dictionary, kafka data files, and log files. You could selectively identify files to protect or you could encrypt the entire TigerGraph folder(App/Data/Log/TempRoot). In this case, simply move $tigergraph_data_root instead of $tigergraph_data_root/gstore.
```
mv $tigergraph_data_root /mnt/secretfs/tigergraph
ln -s /mnt/secretfs/tigergraph $tigergraph_data_root
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The data of TigerGraph data is now stored in an encrypted filesystem. It will be automated decrypted when the tigergraph user (and only this user) accesses it.
To automatically deploy this encryption solution, you may
  1. Chain all the steps as a bash script
  2. Remove all "sudo" since the script will be running as root.
  3. Run the script as root user after TigerGraph Installation.


The setup scripts contain your encryption password. To follow good security procedures, do not leave your password in plaintext format in any files on your disk. Either remove the setup scripts or edit out the password.  
---  
### [](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_performance_evaluation)Performance Evaluation
Encryption is usually CPU-bound rather than I/O-bound. If CPU usage reamains below 100%, encryption should not cause much performance slowdown. A performance test using both small and large queries supports this prediction: for small (~1 sec) and large (~100 sec) queries, there is a ~5% slowdown due to filesystem encryption.
**GSE Cold Start (read)** | **Load Data (write)**  
---|---  
original | 45s | 809s  
encrypted | 47s | 854s  
% slowdown | 4.4% | 5.8%  
We used the TPC-H dataset with scale factor 10 ( <http://www.tpc.org/tpch/>). The data size is 23GB after loading into TigerGraph..The write test (data loading) was done by running a loading job and then killing the GPE with SIGTERM (to exit gracefully) to ensure that all kafka data is consumed.The read test (GSE cold start) measures the time from "gadmin start gse" until "online" appears in "gadmin status gse".
## [](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_example_2_encrypting_data_on_amazon_ec2)Example 2: Encrypting Data on Amazon EC2
Major cloud service providers often provide their own methodologies for encrypting data at rest. For Amazon EC2, we recommend users start by reading the AWS Security Blog: [How to Protect Data at Rest with Amazon EC2 Instance Store Encryption](https://aws.amazon.com/blogs/security/how-to-protect-data-at-rest-with-amazon-ec2-instance-store-encryption/).
In this section, we provide a simple example for configuring file system encryption for a TigerGraph running on Amazon EC2. The steps are based on those given in [How to Protect Data at Rest with Amazon EC2 Instance Store Encryption](https://aws.amazon.com/blogs/security/how-to-protect-data-at-rest-with-amazon-ec2-instance-store-encryption/), with some additions and modifications.
The basic idea of this solution is to create a file, map an encrypted file system to it, and mount it as a storage directory for TigerGraph with permission only to authorized users.
Angle brackets <…​> are used to mark placeholders which you should replace with your own values (without the angle brackets).  
---  
### [](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_prerequisites_2)**Prerequisites**
Make sure you have installed and configured [AWS CLI](https://aws.amazon.com/cli/) with keys locally.
### [](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_create_an_s3_bucket)**Create an S3 Bucket**
from Amazon Data-at-Rest blog
```
Sign in to the S3 console and choose Create Bucket .
In the Bucket Name box, type your bucket name and then choose Create .
You should see the details about your new bucket in the right pane.
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_configure_iam_roles_and_permission_for_the_s3_bucket)**Configure IAM roles and permission for the S3 bucket**
from Amazon Data-at-Rest blog
```
1.Sign in to the AWS Management Console and navigate to the IAM console . In the navigation pane, choose Policies , choose Create Policy . Choose the JSON tab, paste in the following JSON code, and then choose Review Policy . Name and describe the policy, and then choose Create Policy to save your work. For more details, see Creating Customer Managed Policies .
{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Sid": "VisualEditor0",
      "Effect": "Allow",
      "Action": "s3:GetObject",
      "Resource": "arn:aws:s3:::<your-bucket-name>/LuksInternalStorageKey"
    }
  ]
}
The preceding policy grants read access to the bucket where the encrypted password is stored. This policy is used by the EC2 instance, which requires you to configure an IAM role. You will configure KMS permissions later in this post.
(The following instructions have been updated since the original blog post.)
2."Select type of trusted entity: Choose AWS service .
3."Select the service that will use this role": Choose EC2 then choose Next: Permissions.
4.Choose the policy you created in Step 1 and then choose Next: Review.
5.On the Create role page, type your role name , a Role description, and choose Create role .
6.The newly created IAM role is now ready. You will use it when launching new EC2 instances, which will have the permission to access the encrypted password file in the S3 bucket.
javascript![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_create_a_kms_key_optional)Create a KMS Key (optional)
If you don’t have a KMS key, you can create it first:
  1. From the [IAM console](https://console.aws.amazon.com/iam/home), choose Encryption keys from the navigation pane.
  2. Select Create Key , and type in <your-key-alias> _**_
  3. For Step 2 and Step 3 , see <https://docs.aws.amazon.com/kms/latest/developerguide/create-keys.html> for advice.
  4. In Step 4 : Define Key Usage Permissions , select <your-role-name>
  5. The role now has permission to use the key.


![Screenshot of the AWS console: Create Alias and Description](https://docs.tigergraph.com/tigergraph-server/4.1/security/_images/screen-shot-2018-10-01-at-11.20.59-pm.png)
### [](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_encrypt_a_secret_password_with_kms_and_store_it_in_the_s3_bucket)Encrypt a secret password with KMS and store it in the S3 bucket
from Amazon Data-at-Rest blog
```
Next, use KMS to encrypt a secret password. To encrypt text by using KMS, you must use AWS CLI . AWS CLI is installed by default on EC2 Amazon Linux instances and you can install it on Linux, Windows, or Mac computers.
To encrypt a secret password with KMS and store it in the S3 bucket:
From the AWS CLI, type the following command to encrypt a secret password by using KMS (replace <your-region> with your region). You must have the right permissions in order to create keys and put objects in S3 (for more details, see Using IAM Policies with AWS KMS ). In this example, I have used AWS CLI on the Linux OS to encrypt and generate the encrypted password file.
aws --region <your-region> kms encrypt --key-id 'alias/<your-key-alias>' --plaintext '<your-password>' --query CiphertextBlob --output text | base64 --decode > LuksInternalStorageKey
aws s3 cp LuksInternalStorageKey s3://<your-bucket-name>/LuksInternalStorageKey
The preceding commands encrypt the password (Base64 is used to decode the cipher text). The command outputs the results to a file called LuksInternalStorageKey. It also creates a key alias (key name) that makes it easy to identify different keys; the alias is called <your-key-alias> . The file is then copied to the S3 bucket created earlier in this post.
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_configure_ec2_with_role_and_launch_configurations)Configure EC2 with role and launch configurations
In this section, you launch a new EC2 instance with the new IAM role and a bootstrap script that executes the steps to encrypt the file system.
The script in this section requires root permission, and it cannot be run manually through an ssh tunnel or by an unprivileged user.  
---  
![Screenshot of AWS console. The IAM role section is highlighted, showing the words 'poc-data-at-rest-role'. The Advanced Details section is expanded and highlighted with the 'As Text' radio button selected.](https://docs.tigergraph.com/tigergraph-server/4.1/security/_images/13.2.png)
  1. In the [EC2 console](https://console.aws.amazon.com/ec2/v2/home), launch a new instance (see [this tutorial](http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/launching-instance.html) for more details). Amazon Linux AMI 2017.09.1 (HVM), SSD Volume Type (If NOT using Amazon Linux AMI, a script the installs python, pip and AWS CLI needs to be added in the beginning).
  2. In Step 3: Configure Instance Details
    1. In IAM role , choose <your-role-name>
    2. In User Data , paste the following code block after replacing the placeholders with your values and appending TigerGraph installation script


Encryption bootstrap script
```
#!/bin/bash

db_user=tigergraph
## Initial setup to be executed on boot
##====================================
# Create an empty file. This file will be used to host the file system.
# In this example we create a <disk-size> (for example: 60G) file at <path-to-encrypted-file> (for example: /home/tigergraph/gstore_enc).
dd of=<path-to-encrypted-file> bs=<disk-size> count=0 seek=1
# Lock down normal access to the file.
chmod 600 <path-to-encrypted-file>
# Associate a loopback device with the file.
losetup /dev/loop0 <path-to-encrypted-file>
#Copy encrypted password file from S3. The password is used to configure LUKE later on.
aws s3 cp s3://<your-bucket-name>/LuksInternalStorageKey .
# Decrypt the password from the file with KMS, save the secret password in LuksClearTextKey
LuksClearTextKey=$(aws --region <your-region> kms decrypt --ciphertext-blob fileb://LuksInternalStorageKey --output text --query Plaintext | base64 --decode)
# Encrypt storage in the device. cryptsetup will use the Linux
# device mapper to create, in this case, /dev/mapper/tigergraph_gstore.
# Initialize the volume and set an initial key.
echo "$LuksClearTextKey" | cryptsetup -y luksFormat /dev/loop0
# Open the partition, and create a mapping to /dev/mapper/tigergraph_gstore.
echo "$LuksClearTextKey" | cryptsetup luksOpen /dev/loop0 tigergraph_gstore
# Clear the LuksClearTextKey variable because we don't need it anymore.
unset LuksClearTextKey
# Create a file system and verify its status.
mke2fs -j -O dir_index /dev/mapper/tigergraph_gstore
# Mount the new file system to /mnt/secretfs.
mkdir -p /mnt/secretfs
mount /dev/mapper/tigergraph_gstore /mnt/secretfs
# create user tigergraph
adduser $db_user
# Change the permission so that only tigergraph has access to the file system
chmod -R 700 /mnt/secretfs
chown -R $db_user:$db_user /mnt/secretfs
# Install TigerGraph
# Run the one-command installation script with TigerGraphh root path under /mnt/secretfs
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

It may take a few minutes for the script to complete after system launch.
Then, you should be able to launch one or more EC2 machines with an encrypted folder under /mnt/secretfs that only OS user _tigergraph_ can access.
### [](https://docs.tigergraph.com/tigergraph-server/4.1/security/encrypting-data-at-rest#_performance)Performance
Encryption is usually CPU-bound rather than I/O bound. If CPU usage is below 100%, TigerGraph tests show no significant performance downgrade.
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


