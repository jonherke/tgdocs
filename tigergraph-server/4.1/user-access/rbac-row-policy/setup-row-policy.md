![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/setup-row-policy)[Next](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/setup-row-policy)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/setup-row-policy)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/setup-row-policy)
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
  * [Row Policy Overview](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/row-policy-overview)
  * [Set Up Row Policy](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/setup-row-policy)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/4.1/modules/user-access/pages/rbac-row-policy/setup-row-policy.adoc)
### Contents
  * [Prerequisites](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/setup-row-policy#_prerequisites)
  * [Row Policy](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/setup-row-policy#_row_policy)
  * [Creating Row Policies](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/setup-row-policy#_creating_row_policies)
  * [Define Your Row Policy](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/setup-row-policy#_define_your_row_policy)
  * [Apply the Row Policy](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/setup-row-policy#_apply_the_row_policy)
  * [Applying Row Policies Beyond Queries](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/setup-row-policy#_applying_row_policies_beyond_queries)
  * [Clear Row Policies](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/setup-row-policy#_clear_row_policies)
  * [Show Policy](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/setup-row-policy#_show_policy)
  * [Options](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/setup-row-policy#_options)


# Set Up Row Policy
### Contents
  * [Prerequisites](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/setup-row-policy#_prerequisites)
  * [Row Policy](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/setup-row-policy#_row_policy)
  * [Creating Row Policies](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/setup-row-policy#_creating_row_policies)
  * [Define Your Row Policy](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/setup-row-policy#_define_your_row_policy)
  * [Apply the Row Policy](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/setup-row-policy#_apply_the_row_policy)
  * [Applying Row Policies Beyond Queries](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/setup-row-policy#_applying_row_policies_beyond_queries)
  * [Clear Row Policies](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/setup-row-policy#_clear_row_policies)
  * [Show Policy](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/setup-row-policy#_show_policy)
  * [Options](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/setup-row-policy#_options)


## [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/setup-row-policy#_prerequisites)Prerequisites
This guide assumes some basic understanding of [RBAC: Row Policy Key Concepts](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/rbac-row-policy).
Additionally, before going through the examples below it’s a good idea to read through creating a user and assigning roles in our current documentation on [User Management](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/user-management) and [Role Management](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/role-management).
Lastly, it helps to create users or have users ahead of time, one with the role of `superuser` and with a role other than `superuser`, to switch between and see the row policies take effect.
## [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/setup-row-policy#_row_policy)Row Policy
Row Policies are used for fine-grained control over who can access specific data in your TigerGraph graph database. They help ensure that only authorized users with specific roles or attribute values can see certain pieces of information.
Here’s what you need to know:
  * Row policies can be applied to vertices, which are data entries, and dictate who gets access to what based on roles and attributes.
  * Use [GSQL Functions](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/rbac-row-policy#_gsql_functions) to manage these fine-grained controls and permissions.
  * A GSQL function used in a row policy must have a boolean return type, meaning it returns either "true" or "false."


### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/setup-row-policy#_creating_row_policies)Creating Row Policies
This guide will give an example of how to set a new row policy for graph `Social_Net`.
For the schema and data of graph `Social_Net`, refer to [Example Graphs](https://docs.tigergraph.com/gsql-ref/4.1/appendix/example-graphs) and for more information on loading data and defining a schema in GSQL.
In this example, a row policy will be applied on the vertex `Person`, only the users who have the role, `superuser`, can see all vertices of type `Person`, other users can only access the vertices whose attribute `gender` is `Male`.
### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/setup-row-policy#_define_your_row_policy)Define Your Row Policy
Prepare a GSQL Function to act as your row policy’s "filter." This function will determine who gets access to what.
  1. Switch to the global context in GSQL:
```
GSQL > use global
```

  2. Create a GSQL package to store the functions:
```
GSQL > create package lib
```

  3. Now, create the filter GSQL function.
This function should return true if the user meets the criteria for access. In this example, it allows access if the attribute `gender` is `Male` or if the user has the `superuser` role:
```
GSQL > create function lib.myFilter(string str) returns(bool) {
return str == "Male" OR is_granted_to_current_roles("superuser");
}
```



### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/setup-row-policy#_apply_the_row_policy)Apply the Row Policy
Now, that the filter function is ready, apply the row policy to a specific `vertex` type.
For this example, use the `Person` vertex type.
  1. Make sure that the scope is still in global:
```
GSQL > use global
```

  2. Apply the row policy to the `Person` vertex type using the filter function on the gender attribute:
```
GSQL > ALTER VERTEX Person IN GLOBAL SET ROW POLICY lib.myFilter on (gender)
```

If the filter function is not already installed, it will be installed automatically when applying the row policy.  
---  
  3. Double check if this policy can be seen at the global level.
Ex. To view row policies applied globally:
```
GSQL > show row policy
- ROW_POLICY ON Person:
lib.myFilter (gender)
```

  4. Create a Query to Test Row Policy.
Ex. From here create a simple query to test:
```
GSQL > use graph Social_Net
GSQL > create query myTest() for graph Social_Net {
vSet = {Person.*};
print vSet;
}
```

This query should print all vertices with the type `Person`. After the row policy is applied, if a user with the role `superuser` wants to run this query, they should see all vertices with the `Person` type.
Ex. Run query:
```
GSQL > install query myTest
GSQL > run query myTest()
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
    "vSet": [
  {
  "v_id": "person7",
  "v_type": "person",
  "attributes": {
    "id": "person7",
    "gender": "Male"
  }
},
{
  "v_id": "person5",
  "v_type": "person",
  "attributes": {
    "id": "person5",
    "gender": "Female"
  }
}
...
}
```

But if a user is not granted the role of `superuser`, they should only see the vertices of the `Person` type, whose attribute `gender` is `Male`.
```
GSQL > run query myTest()
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
    "vSet": [
    {
      "v_id": "person1",
      "v_type": "person",
      "attributes": {
        "id": "person1",
        "gender": "Male"
      }
    }
    ]
  }
  ]
}
```

  5. Now, to specify a row policy which is used as a vertex parameter, block the query with an exception, if this provided parameter is blocked by a row policy.
Ex. Create another simple query:
```
GSQL > use graph Social_Net
GSQL > create query myTest2(vertex v1) for graph Social_Net {
print v1;
}
GSQL > install query myTest2
```

This query will accept a universal parameter and print it. As well, users can verify if this row policy works for this query,
Ex. Run the query using "person1" on `Person`:
```
GSQL > run query myTest2(("person1" ,"Person"))
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
"v1": "person1"
}
]
}
```

But, if a user, which is not granted the role of `superuser`, they will only see an exception message
Ex. Result:
```
GSQL > run query myTest2(("person2" ,"Person"))
Used a generic vertex v1 blocked by a row policy.
```

In this case, "person1" has the attribute `gender` of `Male`, but "person2" has the attribute `gender` of `Female`. Hence, when using "person2" as the parameter, this query will raise an exception, informing the user that this query is blocked by a row policy.
  6. When trying to retrieve a vertex using [to_vertex()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_to_vertex), it will be regulated by row policies. To specify a row policy which is used as a vertex expression, block the query with an exception, if this expression is blocked by a row policy.
Ex. Create another simple query:
```
GSQL > use graph Social_Net
GSQL > create query myTest3(String vId, String vType) for graph Social_Net {
print to_vertex(vId, vType);
}
GSQL > install query myTest3
```

This query will retrieve a vertex by the defined `vId` and `vType`, and print it. As well, users can verify if this row policy works for this query,
Ex. Run the query using "person1" on `Person`:
```
GSQL > run query myTest3("person1" ,"Person")
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
"to_vertex(vId, vType)": "person1"
}
]
}
```

But, if a user, which is not granted the role of `superuser`, they will only see an exception message
Ex. Result:
```
GSQL > run query myTest3(("person2" ,"Person"))
Used a vertex in expression 'to_vertex(vId, vType)' blocked by a row policy.
```

In this case, "person1" has the attribute `gender` of `Male`, but "person2" has the attribute `gender` of `Female`. Hence, when using "person2" as the parameter, this query will raise an exception, informing the user that this query is blocked by a row policy.
  7. When trying to retrieve a vertex set using [to_vertex_set()](https://docs.tigergraph.com/gsql-ref/4.1/querying/func/vertex-methods#_to_vertex_set), it will be regulated by row policies. To specify a row policy which is used as a vertex set expression, block the query with an exception, if this expression is blocked by a row policy.
Ex. Create another simple query:
```
GSQL > use graph Social_Net
GSQL > create query myTest4(Set<String> vIds, String vType) for graph Social_Net {
print to_vertex_set(vIds, vType);
}
GSQL > install query myTest4
```

This query will retrieve a vertex set by the defined `vIds` and `vType`, and print it. As well, users can verify if this row policy works for this query,
Ex. Run the query using "person1" on `Person`:
```
GSQL > run query myTest4(["person1"] ,"Person")
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
 "to_vertex_set(vIds, vType)": [
  "person1"
 ]
}
]
}
```

But, if a user, which is not granted the role of `superuser`, they will only see an exception message.
Ex. Result:
```
GSQL > run query myTest4((["person2"] ,"Person"))
Used a vertex in expression 'to_vertex_set(vIds, vType)' blocked by a row policy.
```

In this case, "person1" has the attribute `gender` of `Male`, but "person2" has the attribute `gender` of `Female`. Hence, when using "person2" as the parameter, this query will raise an exception, informing the user that this query is blocked by a row policy.


### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/setup-row-policy#_applying_row_policies_beyond_queries)Applying Row Policies Beyond Queries
Row policies also influence built-in functions and REST API endpoints. The behavior of these functions and endpoints depends on whether the user is authorized to access certain vertices. For more information on REST API and REST API endpoints see the documentation on [REST API for GSQL Server](https://docs.tigergraph.com/tigergraph-server/4.1/API/) and [RESTPP and Informant Built-in Endpoints](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints).
Table 1. Row polices can be applied to these endpoints: REST API  
---  
GET /api/restpp/graph/{graph_name}/vertices/{vertex_type}  
GET /api/restpp/graph/{graph_name}/vertices/{vertex_type}/{vertex_id}  
DELETE /api/restpp/graph/{graph_name}/vertices/{vertex_type}/{vertex_id}  
GET /api/restpp/graph/{graph_name}/edges/{source_vertex_type}/{source_vertex_id}/{edge_type}/{target_vertex_type}/{target_vertex_id}  
DELETE /api/restpp/graph/{graph_name}/edges/{source_vertex_type}/{source_vertex_id}/{edge_type}/{target_vertex_type}/{target_vertex_id}  
GET/POST /api/restpp/kstep_expansion/{graph_name}  
GET/POST /api/restpp/shortestpath/{graph_name}  
GET/POST /api/restpp/allpaths/{graph_name}  
GET/POST /api/restpp/searchvertex/{graph_name}  
DELETE /api/restpp/graph/{graph_name}/delete_by_type/vertices/{vertex_type}/  
For the endpoints above, row policies will affect the result if the current user is not authorized to access some vertices.
Before running built-in endpoints, a user will need to generate the token, so as to enable REST++ authentication. Refer to the doc here to [generate a token](https://docs.tigergraph.com/cloud/main/solutions/access-solution/rest-requests#_3_generate_a_token).
Similar to the previous example above, to print the vertex "person2" using a built-in query a user can do so with the following command:
```
curl -w "\n" -H "Authorization: Bearer {your_token}" -s -X GET 'http://127.0.0.1:14240/restpp/graph/socialNet/vertices/person/person2'
```

If you are using a user that does not hold the role of `superuser`, you will get the following:
Ex. Result:
```
{
  "code": "611",
  "error": true,
  "message": "This entity access operation has been denied by a RBAC filter.",
  "version": {
    "api": "v2",
    "edition": "enterprise",
    "schema": 1
  }
}
```

For other cases, there are multiple results for this query. For example, the batch retrieve methods for vertex type of `Person`, will only get the vertices that pass the row policy, if a user does not hold the role of `superuser`.
```
curl -w "\n" -H "Authorization: Bearer {your_token}" -s -X GET 'http://127.0.0.1:14240/restpp/graph/socialNet/vertices/person/'
```

Ex. Result:
```
{
  "error": false,
  "message": "",
  "results": [
  {
    "attributes": {
    "gender": "Male",
    "id": "person1"
  },
  "v_id": "person1",
  "v_type": "person"
  },
  {
  "attributes": {
    "gender": "Male",
    "id": "person3"
  },
  "v_id": "person3",
  "v_type": "person"
  },
  {
  "attributes": {
    "gender": "Male",
    "id": "person6"
  },
  "v_id": "person6",
  "v_type": "person"
  },
  {
  "attributes": {
    "gender": "Male",
    "id": "person7"
  },
  "v_id": "person7",
  "v_type": "person"
  },
  {
  "attributes": {
    "gender": "Male",
    "id": "person8"
  },
  "v_id": "person8",
  "v_type": "person"
  }
  ],
  "version": {
  "api": "v2",
  "edition": "enterprise",
  "schema": 1
  }
}
```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/setup-row-policy#_clear_row_policies)Clear Row Policies
In order to release restrictions users can always clear the row policy.
For example, the built-in query `delete_by_type`, will be blocked if the vertex type specified in the query has a row policy.
To clear an existing row policy and to release the restriction, follow these commands:
```
GSQL > use global
GSQL > ALTER VERTEX person IN GLOBAL CLEAR ROW POLICY
```

After this policy is cleared successfully, show the row policies on the `global` scope again:
```
GSQL > use global
GSQL > show row policy
There is no row policy on global
```

Then, run the same query again to verify the result:
```
GSQL > run query myTest()
```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/setup-row-policy#_show_policy)Show Policy
A schema like the one below can be used to show what policies are currently active:
```
create vertex person(PRIMARY_ID id string, name string, code int)
create graph poc_graph(*)
use graph poc_graph
CREATE SCHEMA_CHANGE JOB poc_graph_sc_job {
ADD VERTEX company(PRIMARY_ID id string, name string, code int);
}
run schema_change job poc_graph_sc_job
```

Assume a `global` vertex type of `person` and a graph called `poc_graph`, with a local vertex of: `company`.
Ex. Set the row policies for them:
```
use global
alter vertex person in global set row policy lib.func on (code)
use graph poc_graph
alter vertex company in graph poc_graph set row policy lib.func on (code)
```

Ex. To show row policies on different scopes:
```
GSQL > use global
GSQL > show row policy
- ROW_POLICY ON person:
lib.func (code)
GSQL > show row policy on person
- ROW_POLICY ON person:
lib.func (code)
GSQL > use graph poc_graph
GSQL > show row policy
- ROW_POLICY ON person:
lib.func (code)
- ROW_POLICY ON company:
lib.func2 (code)
GSQL > show row policy on person
- ROW_POLICY ON person:
lib.func (code)
GSQL > show row policy on company
- ROW_POLICY ON company:
lib.func2 (code)
```

After a row policy is applied or cleared, the affected queries will be deprecated and then reinstalled automatically.
  * For a `global` type it will affect the queries in all graphs that have the `global` scope.
  * For a `local` type it will affect the queries in this corresponding `local` graph scope.


Similarly, if a schema change, which is related to a row policy, (ex: a vertex is removed from a graph) the row policy applied to this vertex will be removed as well, and queries will be reinstalled after this schema change job. This operation will reinstall all installed queries.
### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/setup-row-policy#_options)Options
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/rbac-row-policy/setup-row-policy#_n)-n
Option `-n`, will only deprecate affected queries rather than additionally reinstall them. It is helpful when applying multiple policies in a short time and after all the policies are applied, queries can be reinstall manually or be run in the `INTERPRET` mode.
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


