![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token)[Next](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token)
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
  * Authentication
  * [OIDC JWT Authentication](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/4.1/modules/user-access/pages/jwt-token.adoc)
### Contents
  * [OIDC JWT Authentication in TigerGraph](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_oidc_jwt_authentication_in_tigergraph)
  * [What is OIDC?](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_what_is_oidc)
  * [What is JWT?](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_what_is_jwt)
  * [Authentication Workflow](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_authentication_workflow)
  * [Access Token](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_access_token)
  * [User Guide Overview](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_user_guide_overview)
  * [Scope of Access](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_scope_of_access)
  * [Apply Configuration Changes](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_apply_configuration_changes)
  * [Enable RESTPP Authentication](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_enable_restpp_authentication)
  * [Setup JWT Token gadmin Configuration](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_setup_jwt_token_gadmin_configuration)
  * [Configuration](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_configuration)
  * [Non-Interactive](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_non_interactive)
  * [Optional Configurations](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_optional_configurations)
  * [Interactive](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_interactive)
  * [Generate a 3rd Party JWT Token](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_generate_a_3rd_party_jwt_token)
  * [Use JWT Token](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_use_jwt_token)
  * [Potential Error Messages](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_potential_error_messages)
  * [CA certificate](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_ca_certificate)
  * [Usage of GSQL JWT Token](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_usage_of_gsql_jwt_token)
  * [create JWT Token](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_create_jwt_token)
  * [drop JWT Token](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_drop_jwt_token)
  * [check JWT Token](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_check_jwt_token)


# OIDC JWT Authentication
### Contents
  * [OIDC JWT Authentication in TigerGraph](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_oidc_jwt_authentication_in_tigergraph)
  * [What is OIDC?](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_what_is_oidc)
  * [What is JWT?](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_what_is_jwt)
  * [Authentication Workflow](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_authentication_workflow)
  * [Access Token](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_access_token)
  * [User Guide Overview](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_user_guide_overview)
  * [Scope of Access](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_scope_of_access)
  * [Apply Configuration Changes](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_apply_configuration_changes)
  * [Enable RESTPP Authentication](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_enable_restpp_authentication)
  * [Setup JWT Token gadmin Configuration](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_setup_jwt_token_gadmin_configuration)
  * [Configuration](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_configuration)
  * [Non-Interactive](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_non_interactive)
  * [Optional Configurations](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_optional_configurations)
  * [Interactive](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_interactive)
  * [Generate a 3rd Party JWT Token](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_generate_a_3rd_party_jwt_token)
  * [Use JWT Token](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_use_jwt_token)
  * [Potential Error Messages](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_potential_error_messages)
  * [CA certificate](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_ca_certificate)
  * [Usage of GSQL JWT Token](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_usage_of_gsql_jwt_token)
  * [create JWT Token](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_create_jwt_token)
  * [drop JWT Token](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_drop_jwt_token)
  * [check JWT Token](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_check_jwt_token)


OpenID Connect (OIDC) token-based authentication in JSON web token (JWT) format, allows TigerGraph users better control over application access. Helping to secure users and their data.
## [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_oidc_jwt_authentication_in_tigergraph)OIDC JWT Authentication in TigerGraph
Some basic understanding of TigerGraph’s user access through [Enabling User Authentication](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/enabling-user-authentication) and [Built-in API Endpoints](https://docs.tigergraph.com/tigergraph-server/4.2/API/built-in-endpoints#_authentication) is recommended before continuing.
### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_what_is_oidc)What is OIDC?
OpenID Connect (OIDC) serves as an identity layer integrated with the OAuth 2.0 framework. It enables third-party applications to authenticate the end-user’s identity and access basic user profile information.
For more information on OIDC see [OpenID’s documentation](https://openid.net/developers/how-connect-works/).
### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_what_is_jwt)What is JWT?
OIDC utilizes JSON web tokens (JWTs), obtainable through flows that adhere to OAuth 2.0 specifications. JWTs are an open standard. It allows for a JSON object to be exchanged between two parties securely and in a compact and easily containable way.
For more information please see the documentation [Introduction to JSON Web Tokens](https://jwt.io/introduction).
### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_authentication_workflow)Authentication Workflow
At a high level the authentication workflow is as following:
![AutheticationWorkflow](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/_images/AutheticationWorkflow.png)
  1. The user application or the client requests authorization from the third-party OIDC server or authorization server.
  2. The authorization server validates the request and, if successful, responds with an access token.
  3. The user application or the client uses the access token with the Bearer authentication scheme in the HTTP Authorization header to access a protected resource from the TG RESTPP server.


### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_access_token)Access Token
A JWT includes a JSON object containing information meant for sharing.
To ensure data integrity, each JWT is cryptographically signed, preventing unauthorized modification by clients or malicious parties. The `payload` data within the JWT consists of key-value pairs, commonly referred to as JWT "claims".
These claims encompass essential information such as details about the authenticated user, issue time, expiration time, and various other attributes.
For more information on claims, please see this link on [Json Web Token Claims](https://auth0.com/docs/secure/tokens/json-web-tokens/json-web-token-claims).
Here is a sample encoded JWT Token:
```
eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiIxMjM0NTY3ODkwIiwibmFtZSI6IkpvaG4gRG9lIiwiaWF0IjoxNTE2MjM5MDIyfQ.SflKxwRJSMeKKF2QT4fwpMeJf36POk6yJV_adQssw5c
```

And here is an example of the decoded output:
```
# header
{
"alg":"RS256",
"typ":"JWT"
}
# payload data
{
"iss": "TigerGraph Inc",
"aud": ["a","b"],
"exp": 1647334196,
"sub": "kevin",
"iat": 1516239022,
"graph": "test_graph"
}
# signature
RSASHA256(
base64UrlEncode(header) + "." +
base64UrlEncode(payload),
<Public-Key>,
<Private-Key>)
)
```

Let’s now break down this output in more detail.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_header)Header
The JSON Object Signing and Encryption Header comprises a set of Header Parameters. That consists of a name/value pairs like the hashing algorithm being used (e.g. HMAC, or RSA) as `alg` and the `typ` or type of token.
```
# header
{
"alg":"RS256",
"typ":"JWT"
}
```

Supported cryptographic algorithms for both signing and verification are below:
Supported Algorithm | Types  
---|---  
HMAC | HS256, HS384, HS512  
RSA | RS256, RS384, RS512  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_payload)Payload
The payload contains statements about the entity (typically, the user) and any additional attributes, which are again, referred to as `claims`.
In this example, our entity is a user.
```
# payload data
{
"iss": "TigerGraph Inc",
"aud": ["a","b"],
"exp": 1647334196,
"sub": "kevin",
"iat": 1516239022,
"graph": "test_graph"
}
```

Currently supported claims are as follows:
Claim / Payload Field | Type | Description  
---|---|---  
`iss` | string | [optional] Issuer of the JWT Token.  
`aud` | string | [optional] Recipient for which the JWT is intended.  
`exp` | int | Time after which the JWT expires.  
`sub` | string | Subject of the JWT, this is the TigerGraph Username  
`iat` | int | Time at which the JWT was issued; can be used to determine age of the JWT  
`graph` | string | [optional] Graph reference in the token. Defines the scope of the privileges for the user. The scope is set to global if no “graph” is specified.  
For more information on claims and claims not yet supported, please see [JWT documentation](https://jwt.io/introduction), under the section head “Payload”.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_signature)Signature
The signature is used to verify that the sender of the JWT is who it says it is and to ensure that the message wasn’t changed along the way.
```
# signature
RSASHA256(
base64UrlEncode(header) + "." +
base64UrlEncode(payload),
<Public-Key>,
<Private-Key>)
)
```

To create the signature, the Base64-encoded header and payload are taken, along with a secret or private key, and signed with the algorithm specified in the header.
HMAC and RSA algorithms are supported for signing and verification.
## [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_user_guide_overview)User Guide Overview
To use a JWT token for authentication three things should be done first.
  * Enable RESTPP Authentication
  * Configure the JWT Token
  * Generate a 3rd Party JWT Token


These three steps can be done in any order.
For testing purposes, users can generate a public key using a public tool such as <https://cryptotools.net/rsagen> or use the public key generated from the [JWT token generator](https://docs.google.com/document/d/1aIfIM6fmjbFaqjbQtTeA9gEigdt9nx7JCw09-Fwp3C4/edit?not_in_iframe=true#heading=h.3ogx2q89izf3).
Ensure that the public key configured and the public key in the JWT Token match.  
---  
### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_scope_of_access)Scope of Access
Access tokens **without** the `graph` claim are global tokens and inherit all permissions of the user on any graph.
Tokens **with** the `graph` claim only inherit permissions for the specified graph assigned to the user.
### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_apply_configuration_changes)Apply Configuration Changes
When using `gadmin config` to change any parameters, you need to run `gadmin config apply -y` for it to take effect. You can change multiple parameters and then run `gadmin config apply` for all of them together.
After modifying the configurations, run the following commands to apply the changes:
```
gadmin config apply -y
gadmin restart restpp -y
```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_enable_restpp_authentication)Enable RESTPP Authentication
Enable RESTPP Authentication with this command:
```
gadmin config set RESTPP.Factory.EnableAuth true
```

## [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_setup_jwt_token_gadmin_configuration)Setup JWT Token gadmin Configuration
### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_configuration)Configuration
Users can set the URL for public key or secret settings with:
```
Security.JWT.RSA.PublicKey
```

or
```
Security.JWT.HMAC.Secret
```

There are two ways to configure a public key or secret of a JWT token in TigerGraph through `gadmin config` set.
  * Non-Interactive
  * Interactive


Both instances, users need to specify the URL of the public key or secret in the configuration or use `“@filepath”` when specifying either the public or secret key content from a separate file in your environment.
### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_non_interactive)Non-Interactive
Users can configure JWT token non-interactively by using the `gadmin` CLI tool by running one of these commands for RSA or HMAC.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_rsa)RSA
For RSA, run the command below:
```
$ gadmin config set Security.JWT.RSA.PublicKey <public-key content or URL or @filepath>
```

Ex: Public-key content
```
$ gadmin config set Security.JWT.RSA.PublicKey "
> -----BEGIN PUBLIC KEY-----
> MIGfMA0GCSqGSIb3DQEBAQUAA4GNADCBiQKBgQCmFEHTpcKKKUl/L/gu5Vt5xKTT
> FCj1YpJmsGabB6p5MqlDhXP/UZg29vVxN5eTXKULv8ITWcSDfYQ1YmDmj0cP8kDu
> n5WhOYiBK7vufuECtgQ1B8fMMCd7RMoqdnQLrwGDTFqqVm6jfOXnbXDX6zfkAnmv
> qDxmUcsvNZMzoDOvyQIDAQAB
> ----END PUBLIC KEY----
> "
[  Info] Configuration has been changed. Please use 'gadmin config apply' to persist the changes.
```

Ex: URL
```
$ gadmin config set Security.JWT.RSA.PublicKey https://storage.com/qe-test-data/public_key_test.pem
[  Info] Configuration has been changed. Please use 'gadmin config apply' to persist the changes.
```

Ex: @”filepath”
```
$ gadmin config set Security.JWT.RSA.PublicKey @test.pem
[  Info] Configuration has been changed. Please use 'gadmin config apply' to persist the changes.
```

#### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_hmac)HMAC
For HMAC, run the command below:
```
$ gadmin config set Security.JWT.HMAC.Secret <shared-secret-key content or URL or @filepath>
```

Ex: shared-secret-key content:
```
$ gadmin config set Security.JWT.HMAC.Secret "S2V5LU11c3QtQmUtYXQtbGVhc3QtMzItYnl0ZXMtaW4tbGVuZ3RoIQ=="
[  Info] Configuration has been changed. Please use 'gadmin config apply' to persist the changes.
```

Ex: URL
```
$ gadmin config set Security.JWT.HMAC.Secret https://storage.com/qe-test-data/public_key_test.pem
[  Info] Configuration has been changed. Please use 'gadmin config apply' to persist the changes.
```

Ex: @”filepath”
```
$ gadmin config set Security.JWT.HMAC.Secret @test.pem
[  Info] Configuration has been changed. Please use 'gadmin config apply' to persist the changes.
```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_optional_configurations)Optional Configurations
This next configurations are optional.
Users may also specify the JWT issuer and audience. The default for both these claims are empty.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_security_jwt_issuer)Security.JWT.Issuer
Ex: Security.JWT.Issuer
```
$ gadmin config set Security.JWT.Issuer "<issuer-name>"
```

If Security.JWT.Issuer is configured, the `iss` claim will be verified against this configured value. Otherwise, the issuer will not be verified.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_security_jwt_audience)Security.JWT.Audience
Ex: Security.JWT.Audience
```
$ gadmin config set Security.JWT.Audience "<audience-name>"
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Users can set this JWT Token authentication to verify if the `aud` (recipient for which the JWT is intended) defined in the JWT Token matches the configured one or not.
If the user configures this claim and the token does not match with a value in the `aud` string, then the JWT will fail.
Example of failed response
```
{"version":{"edition":"enterprise","api":"v2","schema":0},"error":true,"message":"Access Denied because the input token = 'eyJh****4WgE' contains audience [a,b], which doesn't include the configured one c","code":"REST-10016"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Audience strings are case-sensitive.  
---  
### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_interactive)Interactive
Additionally, users can set up JWT, interactively, by running this command to begin security configuration: `gadmin config` entry security
This initiates interactive mode and by following the prompts, one by one, users are guided to setup JWT, as shown in the following example:
```
$ gadmin config entry security
Security.JWT.Issuer [ ]: The Issuer for jwt token header
New: User
Security.JWT.RSA.PublicKey [ ]: Set Public key for JWT token auth
[Warning] Please use @filepath to set value of Security.JWT.RSA.PublicKey in interactive mode, or leave it empty to skip
New: @/path/to/pub.file
Security.JWT.HMAC.Secret [ ]: Set Secret for JWT token auth
[Warning] Please use @filepath to set value of Security.JWT.HMAC.Secret in interactive mode, or leave it empty to skip
New:
[  Info] no changes for Security.JWT.HMAC.Secret
```

## [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_generate_a_3rd_party_jwt_token)Generate a 3rd Party JWT Token
The JWT token is generated by a 3rd party authentication server from the customer side. For testing purposes, we recommend using a tool such as [this one](https://dinochiesa.github.io/jwt/) though any JWT token generated will also work.
[NOTE] Prior to version 4.1.2, GSQL server REST endpoints did not accept JWT tokens.
Below you can take this sample data and use it as a test payload:
```
{
"iat": 1699205547,
"exp": 1703865599,
"iss": "TigerGraph",
"aud": ["a","b"],
"sub": "tigergraph",
"graph": "graph"
}
```

Here is an example of the generated token from the payload data.
### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_use_jwt_token)Use JWT Token
Now that the JWT token is generated, its usage is the same as using a GSQL plain text token, allowing access to RESTPP endpoints.
For example, this is used to run the query {queryName} on the graph {graphName}:
```
curl -s -H "Authorization: Bearer <JWT-TOKEN>" -X GET http://127.0.0.1:14240/restpp/query/{graphName}/{queryName}
```

## [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_potential_error_messages)Potential Error Messages
When using a JWT token for authentication, please consider these scenarios and handle the corresponding errors appropriately when working with JWT tokens for authentication.
Error Type | Description  
---|---  
Expiration | If the token has expired, an error is thrown to indicate its expiration.  
User/Graph Existence | If the user specified by sub claim does not exist in the TigerGraph system, an error is thrown to indicate the user does not exist.  
Graph Scope | If the graph specified in the token is not accessible to the user due to insufficient permissions, an error is thrown to indicate permission denied.  
Issuer Match | If the issuer in the token does not match the configured issuer value set by `gadmin`, an error throws to indicate an invalid issuer.  
Audience Match | If the audience configured in the token does not match, an error throws indicating it is invalid.  
Format | If the token is in an incorrect format, contains invalid JSON or fails in base64 decoding, an error throws to indicate format or decoding failure.  
Verification | If the verification process of the JWT token fails, an error is thrown to indicate verification failure.  
Other | Any other exceptions not mentioned above, an error throws to indicate an invalid token.  
### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_ca_certificate)CA certificate
Users need to rely on a CA certificate (corresponding to the [environment variable](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters#_environment_variables) `SSL_CA_CERT`) to establish the connection with the URL being set. This env config is only needed when the URL fails with the error log recorded in the RESTPP log file:
```
I1207 11:57:25.605924 10349 sys_utility.cpp:275] Engine_RESTPP_system_utility|read URL content encountered an error in curl_easy_perform():
Problem with the SSL CA cert (path? access rights?).
```

The storage location of the CA certificate also may differ with the operating system being used.
  * In Ubuntu, by default, it is set as a single file (PEM bundle) in `/etc/ssl/certs/ca-certificates.crt`.
  * In Centos, by default, the SSL certificates on CentOS are stored in the `/etc/pki/tls/certs/` directory.


Provided is an option for users to customized their own storage location of CA certificate by setting `SSL_CA_CERT` in `RESETPP.BasicConfig.Env`.
For Example:
  1. Get the current environment variable list in TigerGraph with:
```
gadmin config get restpp.BasicConfig.Env
```

  2. Then add `SSL_CA_CERT = /path/to/cacertificate` in the `RESETPP.BasicConfig.Env` list with:
```
gadmin config set rsestpp.BasicConfig.Env ${new env variables list}
```

Here is an example
Run get:
```
gadmin config get restpp.BasicConfig.Env
```

Sample Output:
```
LSAN_OPTIONS=suppressions=/home/tigergraph/suppressions.txt;
LD_PRELOAD=/home/tigergraph/tigergraph/app/3.10.0/.syspre/usr/lib/x86_64-linux-gnu/libasan.so.5:$LD_PRELOAD;
LD_LIBRARY_PATH=$LD_LIBRARY_PATH;
ASAN_OPTIONS=detect_leaks=0:alloc_dealloc_mismatch=0;
```

Run set and apply and restart:
```
gadmin config set RESTPP.BasicConfig.Env "
LSAN_OPTIONS=suppressions=/home/tigergraph/suppressions.txt;
LD_PRELOAD=/home/tigergraph/tigergraph/app/3.10.0/.syspre/usr/lib/x86_64-linux-gnu/libasan.so.5:$LD_PRELOAD;
LD_LIBRARY_PATH=$LD_LIBRARY_PATH;
ASAN_OPTIONS=detect_leaks=0:alloc_dealloc_mismatch=0;
SSL_CA_CERT=/home/tigergraph/cacertificate/example/;
"
gadmin config apply -y
gadmin restart -y
```



Existing environment variable may have some influence on the current use of TigerGraph.  
---  
## [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_usage_of_gsql_jwt_token)Usage of GSQL JWT Token
As of version 4.1.0, token generated by TigerGraph’s REST API (e.g. `GET /gsql/v1/tokens`) are JWT tokens, and these tokens can be used with RESTPP server endpoints. As of version 4.1.2, these JWT tokens can also be used with GSQL server endpoints.  
---  
### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_create_jwt_token)create JWT Token
```
POST :14240/gsql/v1/tokens payload '{"secret":"<secret>", "graph":"<graph name>, lifetime: <number in ms>"}'
```

  * `secret`: The `secret` represents the user. If a secret is provided in the payload, user login is not required. If no secret is specified in the payload, a secret will be automatically generated.
  * `graph`: The `graph` defines the scope within which the token can be used. If no graph is specified, the token becomes a global token, applicable to all endpoints.
  * `lifetime`: The `lifetime` specifies the duration for which the token can be used, measured in milliseconds. If no lifetime is specified, the default duration is 7 days.


#### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_required_privilege)Required Privilege:
If `secret` is specified in the payload, the user does not need to login and if `graph` is specified in the payload, the user must have access to the data of the graph.
### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_drop_jwt_token)drop JWT Token
Since the JWT token cannot be deleted as it has been created, a block list is created to include JWT tokens that are restricted to access on RESTPP and GSQL server.
Clear drop list: clear current user’s block list.
```
DELETE :14240/gsql/v1/tokens?clear=true"
```

Drop specific JWT Tokens: add JWT tokens to current user’s block list.
```
DELETE :14240/gsql/v1/tokens" -d '{"tokens":"$token1, $token2, …"}'
```

#### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_required_privilege_2)Required Privilege:
No privilege is required to drop JWT tokens, as this operation is limited to the current logged-in user.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_gadmin_configuration)Gadmin Configuration
Drop Limit: set the JWT token block list limit.the default size is 20 and maximum allowed size is 50.
```
gadmin config set GSQL.Token.DropLimit <positive numbe>
```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_check_jwt_token)check JWT Token
check if a JWT token is valid and the token needs to be generated and check on the same GSQL server.
```
POST :14240/gsql/v1/tokens/check -d '{“token” : “<token>”}'
```

#### [](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/jwt-token#_required_privilege_3)Required Privilege:
No privilege is required.
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


