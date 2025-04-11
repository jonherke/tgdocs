![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest)[Next](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest)
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
  * [Upsert Data](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/4.1/modules/API/pages/upsert-rest.adoc)
### Contents
  * [Endpoint URL](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_endpoint_url)
  * [Parameters](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_parameters)
  * [Response](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_response)
  * [Request body](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_request_body)
  * [Examples](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_examples)
  * [Operation codes](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_operation_codes)
  * [Upserting vertices with composite keys](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_upserting_vertices_with_composite_keys)
  * [Upserting regular edges](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_upserting_regular_edges)
  * [Examples](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_examples_2)
  * [Upserting edges with discriminators](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_upserting_edges_with_discriminators)
  * [Rules for upserting edges with discriminators](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_rules_for_upserting_edges_with_discriminators)
  * [Example: Edge type definition](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_example_edge_type_definition)
  * [General rules for JSON formatting](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_general_rules_for_json_formatting)
  * [Valid data types](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_valid_data_types)
  * [Example](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_example)
  * [Atomic upsert transaction](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_atomic_upsert_transaction)


# Upsert data to graph
### Contents
  * [Endpoint URL](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_endpoint_url)
  * [Parameters](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_parameters)
  * [Response](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_response)
  * [Request body](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_request_body)
  * [Examples](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_examples)
  * [Operation codes](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_operation_codes)
  * [Upserting vertices with composite keys](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_upserting_vertices_with_composite_keys)
  * [Upserting regular edges](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_upserting_regular_edges)
  * [Examples](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_examples_2)
  * [Upserting edges with discriminators](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_upserting_edges_with_discriminators)
  * [Rules for upserting edges with discriminators](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_rules_for_upserting_edges_with_discriminators)
  * [Example: Edge type definition](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_example_edge_type_definition)
  * [General rules for JSON formatting](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_general_rules_for_json_formatting)
  * [Valid data types](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_valid_data_types)
  * [Example](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_example)
  * [Atomic upsert transaction](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_atomic_upsert_transaction)


This endpoint upserts vertices and/or edges into a graph. To upsert means that if a vertex or edge does not exist, it is inserted, and if it does exist, it is updated.
Upserting vertices or edges require the user to have sufficient privileges. See [Access Control Model in TigerGraph](https://docs.tigergraph.com/tigergraph-server/4.1/user-access/access-control-model).
## [](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_endpoint_url)Endpoint URL
`POST /graph/{graph_name}`
## [](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_parameters)Parameters
The following table describes the URL parameters for the endpoint.
Name | Required | Description  
---|---|---  
`ack` | No |  The value of this parameter can either be `"all"` or `"none"`.
  * `"all"`: request will return after all GPE instances have acknowledged the POST request
  * `"none"`: request will return immediately after RESTPP processed the POST request.

Default value is `"all"`. `"none"` is not recommended as it could easily lead to overwhelming the system. Contact TigerGraph Support if you believe your situation requires setting this to "none".  
`new_vertex_only` | No | If `new_vertex_only` is set to true, the request will only insert new vertices and not update existing ones. Default value is `false`.  
`update_vertex_only` | No | If `update_vertex_only` is set to true, the request will only update existing vertices and not insert new vertices.  
`atomic_post` | No |  |  This parameter is deprecated. Please use the `gsql-atomic-level` header instead.   
---  
If `atomic_post` is set to true, the request becomes an atomic transaction - either all updates are successful or no updates are successful. Default value is `false`.  
`vertex_must_exist` | No | If the value is `true`, the request will only insert an **edge** if both the `FROM` and `TO` vertices of the edge already exist. If the value is false, the request will always insert new edges, and create the necessary vertices with default values for their attributes. This parameter does not affect vertices. Default value is `false`.  
`source_vertex_must_exist` | No | If the value is `true`, the request will only insert an **edge** if the `FROM` vertex of the edge already exists. If the value is `false`, the request will always insert new edges, and create the necessary vertices with default values for their attributes. This parameter does not affect vertices. For non-directed edges, the behavior of this parameter is identical to `vertex_must_exist`. Default value is `false`. This parameter is mutually exclusive with the general `vertex_must_exist` parameter and will return an error if both are used.  
`target_vertex_must_exist` | No | If the value is `true`, the request will only insert an **edge** if the `TO` vertex of the edge already exists. If the value is `false`, the request will always insert new edges, and create the necessary vertices with default values for their attributes. This parameter does not affect vertices. For non-directed edges, the behavior of this parameter is identical to `vertex_must_exist`. Default value is `false`. This parameter is mutually exclusive with the general `vertex_must_exist` parameter and will return an error if both are used.  
## [](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_response)Response
The response is the number of vertices and edges that were accepted. Additionally, if `new_vertex_only` is true, the response will include two more fields:
  * `skipped_vertices`: the number of vertices in the input data which already existed in the graph
  * `vertices_already_exist`: the id and type of the input vertices which were skipped


If `vertex_must_exist` is true, the response will include two more fields:
  * `skipped_edges`: the number of edges in the input data rejected because of missing endpoint vertices
  * `miss_vertices`: the id and type of the endpoint vertices which were missing


The example file `add_id6.json` (shown in the **Request Body** section) upserts one `User` _vertex with`id = "id6"` , one `Liked` _edge, and one `Liked_By` _edge. The`Liked` _edge is from `"id1` " to `"id6"`; the `Liked_By` __edge is from`"id6"` to _`"id1"`_.
## [](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_request_body)Request body
The payload data should be in JSON according to the schema shown below:
Request body schema
```
{
  "vertices": {
    "<vertex_type>": {
     "<vertex_id>": {
       "<attribute>": {
        "value": <value>,
        "op": <opcode>
       }
     }
    }
  },
  "edges": {
    "<source_vertex_type>": {
     "<source_vertex_id>": {
       "<edge_type>": {
        "<target_vertex_type>": {
          "<target_vertex_id>": {
           "<attribute>": {
             "value": <value>,
             "op": <opcode>
           }
          }
        }
       }
     }
    }
  }
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The fields in angle brackets (`<>`) are placeholder names or values, to be replaced with actual values. The keys in angle parentheses, such as `<vertex_type>`, can be repeated to form a list of items. The keys which are not in angle brackets are exact texts that must be used as they are. The nested hierarchy means that vertices are grouped by type. Edges, on the other hand, are first grouped by source vertex type, then vertex ID, then edge type.
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_examples)Examples
Upsert Example Data 1: Two User vertices
The first example below shows two `User` vertices having an attribute called `age`:
```
{
 "vertices": {
  "User": {
   "id6": {
    "age": {
      "value": 30
     }
   },
   "id1": {
    "age": {
      "value": 22
     }
   }
  }
 }
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Upsert Example Data 2: Adding Vertices and Edges
This example starts with one `User` vertex (`id6`). Since `id6` contains no attributes, it will remain unchanged if it already exists. If it doesn’t yet exist, the request will create a vertex with ID `id6` with default attribute values. Two edges are created:
  * A `Liked` edge from `id1` to `id6`.
  * A `Liked_By` edge from `id6` to `id1`.


```
{
 "vertices": {
  "User": {
   "id6": {
   }
  }
 },
 "edges": {
  "User":{
   "id1": {
    "Liked": {
     "User": {
      "id6" : {
       "weight" : {
        "value": 5.0
       }
      }
     }
    }
   },
   "id6": {
    "Liked_By": {
     "User": {
      "id1" : {
       "weight" : {
        "value": 1.0
       }
      }
     }
    }
   }
  }
 }
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Follow the instructions in the Introduction section to [format advanced data types](https://docs.tigergraph.com/tigergraph-server/4.1/API/#_formatting_data_in_json).
For example, the following payload is used to upsert two `User` vertices with an attribute `coordinates` of type `LIST` and an attribute `measurements` of type `MAP`:
```
{
 "vertices": {
  "User": {
   "id4": {
    "coordinates": {
      "value": [51.3345, -7.2233]
     },
    "measurements": {
      "value": {
       "keyList": ["chest", "waist", "hip"]
       "valueList": [35, 30, 35]
      }
     }
   },
   "id5": {
    "coordinates": {
      "value": [31.3245, -17.3292]
     },
    "measurements": {
      "value": {
       "keyList": ["chest", "waist", "hip"]
       "valueList": [39, 35, 41]
      }
     }
   }
  }
 }
}
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_operation_codes)Operation codes
Each attribute value may be accompanied by an operation (op) code, which provides very sophisticated schemes for data update or insertion:
Type | op | Meaning  
---|---|---  
1 | `"ignore_if_exists"` or `"~"` | If the vertex/edge does not exist, use the payload value to initialize the attribute; but if the vertex/edge already exists, do not change this attribute.  
2 | `"add"` or `"+"` | Add the payload value to the existing value.  
3 | `"and"` or `"&"` | Update to the logical AND of the payload value and the existing value.  
4 | `"or"` or `"|"` | Update to the logical OR of the payload value and the existing value.  
5 | `"max"` or `">"` | Update to the higher value between the payload value and the existing value.  
6 | `"min"` or `"<"` | Update to the lower value between the payload value and the existing value.  
If an attribute is not given in the payload, the attribute stays unchanged if the vertex/edge already exists, or if the vertex/edge does not exist, a new vertex/edge is created and assigned the default value for that data type. The default value is 0 for `int/uint`, 0.0 for `float/double`, and `""`(empty string) for string.
## [](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_upserting_vertices_with_composite_keys)Upserting vertices with composite keys
If your vertex has composite keys, separate the attributes that make up the composite key with a comma (`,`) in the same order as they are defined in the schema.
For example, suppose we have the following vertex definition:
```
CREATE VERTEX Composite_Person(id UINT, name STRING, age UINT, primary key (name, id))
CREATE VERTEX Composite_Movie (id UINT, title STRING, country STRING, year UINT, PRIMARY KEY (title,year,id))
CREATE DIRECTED EDGE Composite_Roles (from Composite_Person,to Composite_Movie, role STRING)
CREATE GRAPH Person_Movie(Composite_Person, Composite_Movie, Composite_Roles)
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The following requests upserts two vertices with the defined composite key, as well as an edge of the type `Composite_Roles` between `Bob, 123` and `Harry Potter, 1990, 1337`:
```
curl -X POST "localhost:14240/restpp/graph/Person_Movie" -d '
{
 "vertices": {
  "Composite_Person":{
   "Bob,123":{
    "name":{"value":"Bob"},
    "id":{"value":123},
    "age":{"value":25}
   },
   "Tom,456":{
    "name":{"value":"Tom"},
    "id":{"value":456},
    "age":{"value":47}
   }
  }
 },
 "edges":{
  "Composite_Person":{
   "Bob,123":{
    "Composite_Roles":{
     "Composite_Movie":{
      "Harry Potter,1990,1337":{
       "role":{
        "value":"Wizard"
       }
      }
     }
    }
   }
  }
 }
}
'
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_upserting_regular_edges)Upserting regular edges
Regular edges do not have discriminators and must be uniquely defined by their source and target vertex IDs. To upsert a regular edge, use the following JSON format:
```
{
 "edges": {
  "<source_vertex_type>": {
   "<source_vertex_id>": {
    "<edge_type>": {
     "<target_vertex_type>": {
      "<target_vertex_id>": {
       "<attribute>": {
        "value": <value>
       }
      }
     }
    }
   }
  }
 }
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_examples_2)Examples
Upserting a `Liked` edge from a `User` vertex (`id1`) to another `User` vertex (`id6`):
```
{
 "edges": {
  "User": {
   "id1": {
    "Liked": {
     "User": {
      "id6": {
       "weight": {
        "value": 5.0
       }
      }
     }
    }
   }
  }
 }
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_upserting_edges_with_discriminators)Upserting edges with discriminators
Some edge types are defined with [discriminators](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema#_discriminator), which allow multiple instances of the same edge type between two vertices.
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_rules_for_upserting_edges_with_discriminators)Rules for upserting edges with discriminators
  1. **Discriminator attributes are required:**
     * You must include all attributes defined in the discriminator when inserting an edge.
  2. **Discriminator attributes cannot be updated:**
     * Discriminator attributes are immutable and cannot be changed once the edge is created.
  3. **Support for multi-edges with JSON arrays:**
     * When upserting multiple edges with discriminators between the same source and target vertices, you can use a JSON array format..


### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_example_edge_type_definition)Example: Edge type definition
```
CREATE DIRECTED EDGE Liked (
 FROM User,
 TO User,
 DISCRIMINATOR(actionId STRING),
 weight FLOAT
);
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_json_format_for_edges_with_discriminators)JSON Format for Edges with Discriminators
To upsert edges with discriminators, use the following JSON format:
```
{
 "edges": {
  "User": {
   "id1": {
    "Liked": {
     "User": {
      "id6": {
       "actionId": {
        "value": "uuid-1"
       },
       "weight": {
        "value": 5.0
       }
      }
     }
    }
   }
  }
 }
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  1. **"actionId" is the discriminator:**
     * The `actionId` uniquely identifies each edge instance of type `Liked` between the same source (id1) and target (id6) vertices.
     * Discriminators are required when upserting edges of this type and must be included in the JSON payload.
  2. **Other attributes, like "weight":**
     * Attributes not part of the discriminator (e.g., `weight`) can be updated when upserting.
  3. **Nested Structure:**
     * The JSON groups the edge by source vertex type (User) and source vertex ID (id1).
     * Inside, the edge type (Liked) connects the source to the target vertex type (User) and target vertex ID (id6).
     * The `value` field holds the attribute value for each edge attribute.


  * This format is the only supported way to upsert edges with discriminators in the current version.
  * Discriminator attributes are required for creating edges and cannot be updated after the edge is created.
  * A future version will introduce support for upserting multiple edges with discriminators using JSON arrays.

  
---  
## [](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_general_rules_for_json_formatting)General rules for JSON formatting
  1. **Escaped quotes:**
     * If the payload is enclosed in double quotes (`"`), internal double quotes must be replaced with escaped single quotes (`\'`).
     * Example:


```
'{"edges":{"User":{"id1":{"Liked":{"User":{"id6":{"weight":{"value":5.0}}}}}}}}'
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  1. **Lists and Sets:**
     * For attributes that store lists or sets, use the following format:


```
{
 "measurements": {
  "value": {
   "keyList": ["chest", "waist", "hip"],
   "valueList": [35, 30, 35]
  }
 }
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_valid_data_types)Valid data types
The RESTPP server validates the request before updating the values. The following schema violations will cause the entire request to fail and no change will be made to a graph:
  * For vertex upsert
    * Invalid vertex type
    * Invalid attribute data type
  * For edge upsert:
    * Invalid source vertex type
    * Invalid edge type
    * Invalid target vertex type
    * Invalid attribute data type.


If an invalid attribute name is given, it is ignored.
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_example)Example
The following example submits an upsert request by using the payload data stored in `add_id6.json`.
```
curl -X POST --data-binary @add_id6.json "http://localhost:14240/restpp/graph"
{"accepted_vertices":1,"accepted_edges":2}
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

If we set the value of `vertex_must_exist` parameter to `true`, the endpoint will only insert edges whose endpoint vertices both exist. This includes the vertices being inserted in the same request. Therefore, inserting the content of `add_id6.json` to an empty graph would cause the edges to be rejected:
```
curl -X POST --data-binary @add_id6.json "http://localhost:14240/restpp/graph?vertex_must_exist=true"
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
   "accepted_vertices": 1,
   "accepted_edges": 0,
   "skipped_edges": 2,
   "edge_vertices_not_exist": [
    {
     "v_type": "User",
     "v_id": "id1"
    }
   ]
  }
 ],
 "code": "REST-0003"
}
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/4.1/API/upsert-rest#_atomic_upsert_transaction)Atomic upsert transaction
By default, the `POST /graph/{graph_name}` endpoint is not atomic. If something goes wrong during the process of the request, the request data can be partially consumed by the database.
You can append a request header `gsql-atomic-level` to the request to set the request’s atomicity level. The header parameter accepts the following values:
  * `atomic`: The request is an atomic transaction. An atomic transaction means that updates to the database contained in the request are all-or-nothing: either all changes are successful, or none is successful.
  * `nonatomic`: The request is not atomic. This is the default behavior of the endpoint.


For example, suppose we have the following request to upsert two vertices:
  * Request
  * Request body


```
curl --data-binary @vertices.json http://localhost:14240/restpp/graph/social
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Content of `vertices.json` is:
```
{
 "vertices": {
  "person": {
   "Velma": {
    "age": {
      "value": 30
     }
   },
   "Kelly": {
    "age": {
      "value": 22
     }
   }
  }
 }
}
json![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

With the request above, if the vertex `Kelly` fails to be upserted due to a machine failure, it is still possible that the vertex `Velma` is upserted to the database.
If you add the `gsql-atomic-level` header to the request URL and set its value to `atomic`, the request becomes atomic and if any part of the request body fails to be upserted, nothing will be upserted:
```
# This is an atomic request
curl -X POST -H 'gsql-atomic-level:atomic' --data-binary @vertices.json http://localhost:14240/restpp/graph/social
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


