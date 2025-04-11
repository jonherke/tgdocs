![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/query-privilege-migration)[Next](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/query-privilege-migration)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/query-privilege-migration)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/query-privilege-migration)
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
  * Advanced Topics
  * [Access Management](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/)
  * Authorization
  * [Fine-Grained Query Privileges](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/fine-grained-query-privileges)
  * [Migrate Query Privileges from 3.x to 4.1](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/query-privilege-migration)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/4.1/modules/user-access/pages/query-privilege-migration.adoc)
### Contents
  * [Migrate ACL Privileges](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/query-privilege-migration#_migrate_acl_privileges)
  * [Migrate Query ACL Owner](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/query-privilege-migration#_migrate_query_acl_owner)
  * [Migrate Query ACL Reader](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/query-privilege-migration#_migrate_query_acl_reader)
  * [Migrate Query ACL Executor](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/query-privilege-migration#_migrate_query_acl_executor)
  * [Migrate Role-based Access Control(RBAC) Object-Based Query Privileges](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/query-privilege-migration#_migrate_role_based_access_controlrbac_object_based_query_privileges)
  * [Changes for Built-in roles](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/query-privilege-migration#_changes_for_builtin_roles)
  * [Migrate RBAC READ_QUERY privilege](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/query-privilege-migration#_migrate_rbac_read_query)
  * [Migrate RBAC WRITE_QUERY privilege](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/query-privilege-migration#_migrate_rbac_write_query)


# Query Privilege Migration
### Contents
  * [Migrate ACL Privileges](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/query-privilege-migration#_migrate_acl_privileges)
  * [Migrate Query ACL Owner](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/query-privilege-migration#_migrate_query_acl_owner)
  * [Migrate Query ACL Reader](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/query-privilege-migration#_migrate_query_acl_reader)
  * [Migrate Query ACL Executor](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/query-privilege-migration#_migrate_query_acl_executor)
  * [Migrate Role-based Access Control(RBAC) Object-Based Query Privileges](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/query-privilege-migration#_migrate_role_based_access_controlrbac_object_based_query_privileges)
  * [Changes for Built-in roles](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/query-privilege-migration#_changes_for_builtin_roles)
  * [Migrate RBAC READ_QUERY privilege](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/query-privilege-migration#_migrate_rbac_read_query)
  * [Migrate RBAC WRITE_QUERY privilege](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/query-privilege-migration#_migrate_rbac_write_query)


This page provides detailed procedures for migrating query privileges when upgrading to TigerGraph 4.1 from 3.x. It also outlines the specific privileges required to successfully carry out the migration process.
To see user management tasks under the [Access Control List (ACL)](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/access-control-model#_access_control_lists) model, see [Access Control Lists (ACLs) (Deprecated)](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/acl-management).
To see Role-based Access Control(RBAC) Object-Based privileges, see [rbac-row-policy/rbac-row-policy.adoc#_object_based_privileges](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/rbac-row-policy#_object_based_privileges).
## [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/query-privilege-migration#_migrate_acl_privileges)Migrate ACL Privileges
Starting with TigerGraph 4.1.0, Access Control Lists (ACLs) are deprecated.
Query ACL privileges should be migrated automatically during upgrade.
### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/query-privilege-migration#_migrate_query_acl_owner)Migrate Query ACL Owner
The query ACL owner will be granted `OWNERSHIP` privilege on the query owned by this user/role after upgrade.
### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/query-privilege-migration#_migrate_query_acl_reader)Migrate Query ACL Reader
The query ACL readers will be granted `READ` privilege on the same query after upgrade.
### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/query-privilege-migration#_migrate_query_acl_executor)Migrate Query ACL Executor
The query ACL executors will be granted `EXECUTE` privilege on the same query after upgrade.
In some cases, query ACL privileges can’t be migrated successfully. Then the owner of queries will become the user who operates the upgrade procedure. Contact TigerGraph Support if you need help retaining ACL-like privileges after upgrading from version 3.x to 4.x.  
---  
## [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/query-privilege-migration#_migrate_role_based_access_controlrbac_object_based_query_privileges)Migrate Role-based Access Control(RBAC) Object-Based Query Privileges
Query Object-Based privileges are introduced in TigerGraph 4.1. `CREATE` privilege on queries will exist only at the global and local graph scope. Other query privileges, including `READ`, `UPDATE`, `DROP`, `INSTALL`, `EXECUTE` and `OWNERSHIP`, will exist only at the query scope.
All existing Query privileges will be migrated into Query Object-Based privileges during upgrade and be fully backwards-compatible with existing queries.
### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/query-privilege-migration#_changes_for_builtin_roles)Changes for Built-in roles
`READ_QUERY` and `WRITE_QUERY` privileges will be removed from all built-in roles. The roles held `WRITE_QUERY` privilege before 4.1 will hold `CREATE_QUERY` privilege in the same scope since 4.1. `superuser` will be the owner of all queries. `admin` in one graph will be the owner of all queries in a local graph.
To check the detailed changes for all built-in roles, please check the following table.
**Name** | **Global or Local** | **Removed Privilege** | **New Privileges**  
---|---|---|---  
`observer` | Local | `READ_QUERY` | N/A  
`queryreader` | Local | `READ_QUERY` | N/A  
`querywriter` | Local | `WRITE_QUERY` | `CREATE_QUERY`  
`designer` | Local | `WRITE_QUERY` | `CREATE_QUERY`  
`admin` | Local | `WRITE_QUERY` | `CREATE_QUERY`, `OWNERSHIP` on ALL QUERIES  
`globaldesigner` | Global | `WRITE_QUERY` | `CREATE_QUERY`  
`superuser` | Global | `WRITE_QUERY` | `CREATE_QUERY`, `OWNERSHIP` on ALL QUERIES  
### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/query-privilege-migration#_migrate_rbac_read_query)Migrate RBAC READ_QUERY privilege
`READ_QUERY` privilege will be migrated to `READ_QUERY` privilege on the query object level for all existing queries since we only keep query-level `READ_QUERY` privilege for all queries.
This migration process may be different for existing `READ_QUERY` privileges granted to built-in roles vs. user-defined roles.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/query-privilege-migration#_migrate_rbac_read_query_privilege_for_built_in_roles)Migrate RBAC READ_QUERY privilege for Built-in roles
The `READ_QUERY` privilege in global and graph level scopes for built-in roles is deprecated in TigerGraph 4.1. For the detailed changes of built-in roles, please refer to the table above.
If users were granted built-in roles with `READ_QUERY` privileges before upgrade, the `READ_QUERY` privileges will be granted to the users directly with all existing queries in the same scope.
For example:
  * User `Alice` is granted with the built-in role `observer` in graph `recommend` in TigerGraph 3.10, and there are two queries `query1` and `query2` in graph `recommend`. After the upgrade to TigerGraph 4.1, user `Alice` will have the `READ_QUERY` privileges on queries `query1` and `query2` in graph `recommend`.


#### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/query-privilege-migration#_migrate_rbac_read_query_privilege_for_user_defined_roles)Migrate RBAC READ_QUERY privilege for User-Defined roles
If users were granted user-defined roles with `READ_QUERY` privileges before upgrade, the `READ_QUERY` privileges will be granted to the same role with all existing queries in the same scope.
For example:
  * User `Bob` was granted the user-defined role `myRole` with `READ_QUERY` privilege in graph `recommend` in TigerGraph 3.10, and there are two queries `query1` and `query2` in graph `recommend`. After the upgrade to TigerGraph 4.1, role `myRole` will have the `READ_QUERY` privileges on query `query1` and `query2` in graph `recommend`. User `Bob` can still read queries `query1` and `query2` since he is still granted the role `myRole`.


### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/query-privilege-migration#_migrate_rbac_write_query)Migrate RBAC WRITE_QUERY privilege
Prior to TigerGraph 4.1, `WRITE_QUERY` privilege permited making any type of change to a query. Hence, `WRITE_QUERY` privilege will be migrated to all privileges except `OWNERSHIP` for all existing queries, including `READ_QUERY`, `UPDATE_QUERY`, `DROP_QUERY`, `INSTALL_QUERY`, `EXECUTE_QUERY` on each query object and `CREATE_QUERY` on the same scope for `WRITE_QUERY` privilege.
Similarly, this migration process differs for `WRITE_QUERY` privileges when users are granted built-in roles vs. user-defined roles.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/query-privilege-migration#_migrate_rbac_write_query_privilege_for_built_in_roles)Migrate RBAC WRITE_QUERY privilege for Built-in roles
The `WRITE_QUERY` privilege is deprecated in TigerGraph 4.1. For the detailed changes of built-in roles, please refer to the table above.
If users were granted built-in roles with `WRITE_QUERY` privileges before upgrade, the following privileges, `READ_QUERY`, `UPDATE_QUERY`, `DROP_QUERY`, `INSTALL_QUERY`, `EXECUTE_QUERY`, will be granted to the users directly with all existing queries in the same scope.
For example:
  * User `Alice` was granted the built-in role `designer` in graph `recommend` in TigerGraph 3.10, and there are two queries `query1` and `query2` in graph `recommend`. After the upgrade to TigerGraph 4.1, user `Alice` will hold the `READ_QUERY`, `UPDATE_QUERY`, `DROP_QUERY`, `INSTALL_QUERY`, `EXECUTE_QUERY` privileges on queries `query1` and `query2` in graph `recommend`. At the same time, user `Alice` can still create queries in graph `recommend` since she still holds the role `designer` in graph `recommend`, which provides the `CREATE_QUERY` privilege in graph `recommend`.


#### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/query-privilege-migration#_migrate_rbac_write_query_privilege_for_user_defined_roles)Migrate RBAC WRITE_QUERY privilege for User-Defined roles
The `WRITE_QUERY` privilege in global and graph level scopes for user-defined roles is deprecated in TigerGraph 4.1.
If users were granted user-defined roles with `WRITE_QUERY` privileges before upgrade, the following privileges `READ_QUERY`, `UPDATE_QUERY`, `DROP_QUERY`, `INSTALL_QUERY`, `EXECUTE_QUERY`, will all be granted to the same role with all existing queries in the same scope. At the same time, `CREATE_QUERY` privilege on the same scope will be granted to the same role in the same scope.
For example:
  * User `Bob` was granted with the user-defined role `myRole` with `WRITE_QUERY` in graph `recommend` in TigerGraph 3.10, and there are two queries, `query1` and `query2` in graph `recommend`. After the upgrade to TigerGraph 4.1, role `myRole` will have the `CREATE_QUERY` privilege in graph `recommend`, and `READ_QUERY`, `UPDATE_QUERY`, `DROP_QUERY`, `INSTALL_QUERY`, `EXECUTE_QUERY` privileges on query `query1` and `query2` in graph `recommend`. User `Bob` can still create queries in graph `recommend`, and read, update, drop, install and execute existing queries `query1` and `query2` since he is still granted the role `myRole`.


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


