![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-template)[Next](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-template)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-template)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-template)
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
  * [Load from <data type>](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-template)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/4.1/modules/data-loading/pages/load-template.adoc)
### Contents
  * [Example Schema](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-template#_example_schema)
  * [Create Data Source Object](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-template#_create_data_source_object)
  * [Create a loading job](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-template#_create_a_loading_job)
  * [Define filenames](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-template#_define_filenames)
  * [Specify the data mapping](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-template#_specify_the_data_mapping)
  * [Run the loading job](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-template#_run_the_loading_job)
  * [Manage and monitor your loading job](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-template#_manage_and_monitor_your_loading_job)
  * [Manage loading job concurrency](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-template#_manage_loading_job_concurrency)
  * [Known Issues with Loading](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-template#_known_issues_with_loading)


# Load from <data type>
Table of Contents
  * [Example Schema](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-template#_example_schema)
  * [Create Data Source Object](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-template#_create_data_source_object)
    * [String Literals](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-template#_string_literals)
  * [Create a loading job](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-template#_create_a_loading_job)
    * [Define filenames](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-template#_define_filenames)
    * [Specify the data mapping](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-template#_specify_the_data_mapping)
  * [Run the loading job](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-template#_run_the_loading_job)
  * [Manage and monitor your loading job](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-template#_manage_and_monitor_your_loading_job)
  * [Manage loading job concurrency](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-template#_manage_loading_job_concurrency)
  * [Known Issues with Loading](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-template#_known_issues_with_loading)


After you have [defined a graph schema](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/defining-a-graph-schema), you can create a loading job, specify your data sources, and run the job to load data.
The steps for loading from local files, cloud storage, or any other supported sources are similar. We will call out whether a particular step is common for all loading or specific to a data source or loading mode.
## [](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-template#_example_schema)Example Schema
Example schema taken from LDBC_SNB
```
//Vertex Types:
CREATE VERTEX Person(PRIMARY_ID id UINT, firstName STRING, lastName STRING,
 gender STRING, birthday DATETIME, creationDate DATETIME, locationIP STRING,
 browserUsed STRING, speaks SET<STRING>, email SET<STRING>)
 WITH STATS="OUTDEGREE_BY_EDGETYPE", PRIMARY_ID_AS_ATTRIBUTE="true"
CREATE VERTEX Comment(PRIMARY_ID id UINT, creationDate DATETIME,
 locationIP STRING, browserUsed STRING, content STRING, length UINT)
 WITH STATS="OUTDEGREE_BY_EDGETYPE", PRIMARY_ID_AS_ATTRIBUTE="true"
//Edge Types:
CREATE DIRECTED EDGE HAS_CREATOR(FROM Comment, TO Person)
 WITH REVERSE_EDGE="HAS_CREATOR_REVERSE"
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-template#_create_data_source_object)Create Data Source Object
A data source object provides a standard interface for all supported data source types, so that loading jobs can be written without regard for the data source.
When you create the object, you specify its details (type, access credentials, etc.) in the form of a JSON object. The JSON object can either be read in from a file or provided inline.
Inline mode is required when creating data sources for TigerGraph Cloud instances.  
---  
In the following example, we create a data source named `s1`, and read its configuration information from a file called `ds_config.json`.
```
USE GRAPH ldbc_snb
CREATE DATA_SOURCE s1 = "ds_config.json" FOR GRAPH ldbc_snb
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Older versions of TigerGraph required a keyword after `DATA_SOURCE` such as `STREAM` or `KAFKA`.  
---  
Inline JSON data format when creating a data source
```
CREATE DATA_SOURCE s1 = "{
 type: <type>,
 key: <value>
}" FOR GRAPH ldbc_snb
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-template#_string_literals)String Literals
String literals can be represented according to the following options:
  * Enclosed with double quote `"`.
  * Enclosed with triple double quotes `"""`.
  * Enclosed with triple single quotes `'''`.


In the case of JSON that does not contain a colon `:` or a comma `,` the double quotes `"` can be omitted.
Alternate quote syntax for inline JSON data
```
CREATE DATA_SOURCE s1 = """{
 "type": "<type>",
 "key": "<value>"
}""" FOR GRAPH ldbc_snb
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Either a period `.` or `_` can be used for separation in the specified key name. Example: `first.second` or `first_second`.
## [](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-template#_create_a_loading_job)Create a loading job
A loading job tells the database how to construct vertices and edges from data sources. The loading job body has two parts:
  1. DEFINE statements create variables to refer to data sources. These can refer to actual files or be placeholder names. The actual data sources can be given when running the loading job.
  2. LOAD statements specify how to take the data fields from files to construct vertices or edges.


### [](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-template#_define_filenames)Define filenames
First we define _filenames_ , which are local variables referring to data files (or data objects).
The terms `FILENAME` and `filevar` are used for legacy reasons, but a `filevar` can also be an object in a data object store.   
---  
DEFINE FILENAME syntax
```
DEFINE FILENAME filevar ["=" file_descriptor ];
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The file descriptor can be specified at compile-time or at runtime. Runtime settings override compile-time settings:
Specifying file descriptor at runtime
```
RUN LOADING JOB job_name USING filevar=file_descriptor_override
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-template#_specify_the_data_mapping)Specify the data mapping
Next, we use LOAD statements to describe how the incoming data will be loaded to attributes of vertices and edges. Each LOAD statement handles the data mapping, and optional data transformation and filtering, from one filename to one or more vertex and edge types.
LOAD statement syntax
```
LOAD [ source_object|filevar|TEMP_TABLE table_name ]
 destination_clause [, destination_clause ]*
 [ TAGS clause ] **(1)**
 [ USING clause ];
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**1** | As of v3.9.3, TAGS are deprecated.  
---|---  
Let’s break down one of the LOAD statements in our example:
Example loading job for local files
```
LOAD file_Person TO VERTEX Person
  VALUES($1, $2, $3, $4, $5, $0, $6, $7,
    SPLIT($8, ";"), SPLIT($9, ";"))
  USING SEPARATOR="|", HEADER="true", EOL="\n";
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  * `$0`, `$1`,…​ refer to the first, second, …​ columns in each line a data file.
  * `SEPARATOR="|"` says the column separator character is the pipe (`|`). The default is comma (`,`).
  * `HEADER="true"` says that the first line in the source contains column header names instead of data. These names can be used instead of the columnn numbers.
  * `SPLIT` is one of GSQL’s ETL functions. It says that there is a multi-valued column, which has a separator character to mark the subfields in that column.


Refer to [Creating a Loading Job](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/creating-a-loading-job) in the GSQL Language Reference for descriptions of all the options for loading jobs.
## [](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-template#_run_the_loading_job)Run the loading job
Use the command `RUN LOADING JOB` to run the loading job.
RUN LOADING JOB basic syntax (some options omitted)
```
RUN LOADING JOB [-noprint] job_name [
 USING filevar [="file_descriptor"][, filevar [="file_descriptor"]]*
 [,EOF="eof_mode"]
]
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

**-noprint**
By default, the loading job will run in the foreground and print the loading status and statistics after you submit the job. If the `-noprint` option is specified, the job will run in the background after displaying the job ID and the location of the log file.
**filevar list**
The optional `USING` clause may contain a list of file variables. Each file variable may optionally be assigned a `file_descriptor`, obeying the same format as in `CREATE LOADING JOB`. This list of file variables determines which parts of a loading job are run and what data files are used.
When a loading job is compiled, it generates one RESTPP endpoint for each `filevar` and source_object. As a consequence, a loading job can be run in parts. When `RUN LOADING JOB` is executed, only those endpoints whose filevar or file identifier (`_GSQL_FILENAME_n_`) is mentioned in the`USING` clause will be used. However, if the `USING` clause is omitted, then the entire loading job will be run.
If a `file_descriptor` is given, it overrides the `file_descriptor` defined in the loading job. If a particular `filevar` is not assigned a `file_descriptor` either in the loading job or in the `RUN LOADING JOB` statement, an error is reported and the job exits.
## [](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-template#_manage_and_monitor_your_loading_job)Manage and monitor your loading job
When a loading job starts, the GSQL server assigns it a job ID and displays it for the user to see. There are four key commands to monitor and manage loading jobs:
```
SHOW LOADING STATUS job_id|ALL
ABORT LOADING JOB job_id|ALL
RESUME LOADING JOB job_id
SHOW LOADING ERROR job_id
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

`SHOW LOADING STATUS` shows the current status of either a specified loading job or all current jobs, this command should be within the scope of a graph:
```
GSQL > USE GRAPH graph_name
GSQL > SHOW LOADING STATUS ALL
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

For each loading job, the above command reports the following information:
  * Loading status
  * Loaded lines/Loaded objects/Error lines
  * Average loading speed
  * Size of loaded data
  * Duration When inspecting all current jobs with `SHOW LOADING STATUS ALL`, the jobs in the `FINISHED` state will be omitted as they are considered to have successfully finished. You can use `SHOW LOADING STATUS job_id` to check the historical information of finished jobs. If the report for this job contains error data, you can use `SHOW LOADING ERROR job_id` to see the original data that caused the error.


See [Managing and Inspecting a Loading Job](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/managing-loading-job) for more details.
## [](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-template#_manage_loading_job_concurrency)Manage loading job concurrency
See [Loading Job Concurrency](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/loading-concurrency) for how to manage the concurrency of loading jobs.
## [](https://docs.tigergraph.com/tigergraph-server/4.1/data-loading/load-template#_known_issues_with_loading)Known Issues with Loading
TigerGraph does not store NULL values. Therefore, your input data should not contain any NULLs.   
---  
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


