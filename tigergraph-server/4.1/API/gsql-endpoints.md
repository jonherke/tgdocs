![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints)[Next](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints)
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
  * [GSQL Endpoints](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/4.1/modules/API/pages/gsql-endpoints.adoc)
### Contents
  * [Schema](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_schema)
  * [show vertices](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_show_vertices)
  * [show a vertex](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_show_a_vertex)
  * [create vertex using gsql command](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_vertex_using_gsql_command)
  * [add global vertices to a local graph](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_add_global_vertices_to_a_local_graph)
  * [create vertices (create vertices in global level)](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_vertices_create_vertices_in_global_level)
  * [drop vertices](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_vertices)
  * [drop a vertex](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_a_vertex)
  * [update a vertex attribute](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_update_a_vertex_attribute)
  * [show all indexes](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_show_all_indexes)
  * [show an index](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_show_an_index)
  * [create indexes](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_indexes)
  * [drop an index](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_an_index)
  * [drop indexes](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_indexes)
  * [get all edges](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_all_edges)
  * [retrieve a specific edge type info](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_retrieve_a_specific_edge_type_info)
  * [create edges using gsql command statement](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_edges_using_gsql_command_statement)
  * [add global edges to graph using json format](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_add_global_edges_to_graph_using_json_format)
  * [create global edges using json format](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_global_edges_using_json_format)
  * [drop edges from graph](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_edges_from_graph)
  * [drop an edge](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_an_edge)
  * [update attribute in edge](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_update_attribute_in_edge)
  * [show all graphs info that only contains the name of vertices and edges](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_show_all_graphs_info_that_only_contains_the_name_of_vertices_and_edges)
  * [show one graph detailed info with given graph name](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_show_one_graph_detailed_info_with_given_graph_name)
  * [create one graph using gsql command](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_one_graph_using_gsql_command)
  * [create one graph using JSON format](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_one_graph_using_json_format)
  * [drop one graph](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_one_graph)
  * [drop graphs with given names](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_graphs_with_given_names)
  * [drop local/global schema change jobs](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_localglobal_schema_change_jobs)
  * [create local/global schema change job using gsql command](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_localglobal_schema_change_job_using_gsql_command)
  * [create global schema change job using json](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_global_schema_change_job_using_json)
  * [create local schema change job using json](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_local_schema_change_job_using_json)
  * [get a specific local/global schema change job](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_a_specific_localglobal_schema_change_job)
  * [run global schema change job directly](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_run_global_schema_change_job_directly)
  * [run the schema change job directly](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_run_the_schema_change_job_directly)
  * [run an existing schema change job](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_run_an_existing_schema_change_job)
  * [get schema change jobs](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_schema_change_jobs)
  * [Loading Jobs](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_loading_jobs)
  * [Get loading job names](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_loading_job_names)
  * [Get loading job information](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_loading_job_information)
  * [Create a loading job](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_a_loading_job)
  * [Update a loading job](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_update_a_loading_job)
  * [Drop a loading job](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_a_loading_job)
  * [Run a loading job](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_run_a_loading_job)
  * [Get loading job run statuses (multiple jobs)](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_loading_job_run_statuses_multiple_jobs)
  * [Get loading job run status (one job)](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_loading_job_run_status_one_job)
  * [Abort loading job(s)](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_abort_loading_jobs)
  * [Abort one loading job](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_abort_one_loading_job)
  * [Resume loading job](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_resume_loading_job)
  * [Data source](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_data_source)
  * [get a data source](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_a_data_source)
  * [get all data sources](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_all_data_sources)
  * [update a data source](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_update_a_data_source)
  * [create data source](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_data_source)
  * [drop one data source](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_one_data_source)
  * [grant one data source](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_grant_one_data_source)
  * [revoke datasource](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_revoke_datasource)
  * [drop all data source](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_all_data_source)
  * [get the sample data of S3 file.uris or local files](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_the_sample_data_of_s3_file_uris_or_local_files)
  * [get all buckets of given S3 data source](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_all_buckets_of_given_s3_data_source)
  * [get all files and directories under given S3 bucket path](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_all_files_and_directories_under_given_s3_bucket_path)
  * [Query](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_query)
  * [install queries](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_install_queries)
  * [check query install status](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_check_query_install_status)
  * [list query names](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_list_query_names)
  * [create query](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_query)
  * [drop query](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_query)
  * [get query content](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_query_content)
  * [run query](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_run_query)
  * [drop one query](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_one_query)
  * [interpret query](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_interpret_query)
  * [get query info](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_query_info)
  * [get query signature](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_query_signature)
  * [query semantic check](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_query_semantic_check)
  * [Template query](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_template_query)
  * [get all package names](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_all_package_names)
  * [get package content](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_package_content)
  * [create package](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_package)
  * [drop package](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_package)
  * [create function](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_function)
  * [delete function](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_delete_function)
  * [create template query](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_template_query)
  * [drop template query](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_template_query)
  * [import package](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_import_package)
  * [call template query](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_call_template_query)
  * [get template query info](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_template_query_info)
  * [Database Utilities](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_database_utilities)
  * [generic endpoint to execute any GSQL command](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_generic_endpoint_to_execute_any_gsql_command)
  * [check status of asynchronous request with requestId](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_check_status_of_asynchronous_request_with_requestid)
  * [cancel an asynchronous request with requestId](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_cancel_an_asynchronous_request_with_requestid)
  * [recover gdict catalog](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_recover_gdict_catalog)
  * [validate graph schema](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_validate_graph_schema)
  * [clear graph store](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_clear_graph_store)
  * [get gsql version](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_gsql_version)
  * [drop all](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_all)
  * [graph export](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_graph_export)
  * [graph import](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_graph_import)
  * [Security](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_security)
  * [create new JWT token](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_new_jwt_token)
  * [drop JWT tokens](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_jwt_tokens)
  * [check JWT token](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_check_jwt_token)
  * [create secret](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_secret)
  * [show secrets](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_show_secrets)
  * [delete secrets](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_delete_secrets)
  * [get secret by alias](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_secret_by_alias)
  * [drop secret by alias](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_secret_by_alias)
  * [retrieve a group by id using gsql format](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_retrieve_a_group_by_id_using_gsql_format)
  * [retrieve groups using gsql format](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_retrieve_groups_using_gsql_format)
  * [create a group using gsql format](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_a_group_using_gsql_format)
  * [update a group using gsql format](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_update_a_group_using_gsql_format)
  * [drop one group by name using gsql format](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_one_group_by_name_using_gsql_format)
  * [drop groups using gsql format](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_groups_using_gsql_format)
  * [retrieve a user by id using gsql format](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_retrieve_a_user_by_id_using_gsql_format)
  * [update an user using gsql format](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_update_an_user_using_gsql_format)
  * [drop users for gsql format](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_users_for_gsql_format)
  * [drop a user using gsql format](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_a_user_using_gsql_format)
  * [create a user using gsql format](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_a_user_using_gsql_format)
  * [retrieve users using gsql format](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_retrieve_users_using_gsql_format)
  * [show all privileges](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_show_all_privileges)
  * [grant privilege(s) to role(s)](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_grant_privileges_to_roles)
  * [revoke privilege(s) from role(s)](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_revoke_privileges_from_roles)
  * [show all roles](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_show_all_roles)
  * [Create roles](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_roles)
  * [Delete roles](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_delete_roles)
  * [show one role](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_show_one_role)
  * [delete one role](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_delete_one_role)
  * [grant role(s) to user(s)](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_grant_roles_to_users)
  * [revoke role(s) from user(s)](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_revoke_roles_from_users)
  * [SCIM APIs for users/groups](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_scim_apis_for_usersgroups)
  * [retrieve a group by id using scim format](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_retrieve_a_group_by_id_using_scim_format)
  * [retrieve groups using scim format](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_retrieve_groups_using_scim_format)
  * [create a group using scim format](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_a_group_using_scim_format)
  * [update a group using scim format](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_update_a_group_using_scim_format)
  * [drop one group by name using scim format](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_one_group_by_name_using_scim_format)
  * [drop groups using scim format](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_groups_using_scim_format)
  * [retrieve a user by id using scim format](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_retrieve_a_user_by_id_using_scim_format)
  * [update a user using scim format](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_update_a_user_using_scim_format)
  * [drop users using scim format](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_users_using_scim_format)
  * [drop a user using scim format](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_a_user_using_scim_format)
  * [create a user using scim format](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_a_user_using_scim_format)
  * [retrieve users using scim format](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_retrieve_users_using_scim_format)
  * [Statistics](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_statistics)
  * [get cardinality statistics](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_cardinality_statistics)
  * [post cardinality statistics](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_post_cardinality_statistics)
  * [delete cardinality statistics](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_delete_cardinality_statistics)
  * [get histogram statistics](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_histogram_statistics)
  * [post histogram statistics](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_post_histogram_statistics)
  * [delete histogram statistics](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_delete_histogram_statistics)
  * [User Defined Objects](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_user_defined_objects)
  * [list all tuples](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_list_all_tuples)
  * [list one tuple](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_list_one_tuple)
  * [create tuple](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_tuple)
  * [delete multiple tuples](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_delete_multiple_tuples)
  * [delete one tuple](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_delete_one_tuple)
  * [list all accumulators](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_list_all_accumulators)
  * [list one accumulator](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_list_one_accumulator)
  * [create accumulators](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_accumulators)
  * [delete mulitple accumulators](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_delete_mulitple_accumulators)
  * [delete one accumulator](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_delete_one_accumulator)
  * [download expr files](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_download_expr_files)
  * [download all files](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_download_all_files)
  * [upload one file](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_upload_one_file)
  * [upload file](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_upload_file)
  * [get token bank functions](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_token_bank_functions)
  * [get all token bank functions](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_all_token_bank_functions)


# GSQL Endpoints
Table of Contents
  * [Schema](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_schema)
  * [Loading Jobs](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_loading_jobs)
  * [Data source](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_data_source)
  * [Query](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_query)
  * [Template query](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_template_query)
  * [Database Utilities](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_database_utilities)
  * [Security](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_security)
  * [SCIM APIs for users/groups](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_scim_apis_for_usersgroups)
  * [Statistics](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_statistics)
  * [User Defined Objects](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_user_defined_objects)


This page describes the REST API endpoints accessible on a TigerGraph server. Assume all the sample requests and sample response are based on this sample schema (graph name is "financialGraph"):
In 4.0, the paths for most endpoints were revised to follow a more standard convention. Some functions were moved from the RESTPP server to the GSQL server for consistency. You can refer to the [REST endpoints for TigerGraph 3.x](https://docs.tigergraph.com/tigergraph-server/4.1/API/built-in-endpoints) for comparison.  
---  
As of version 4.1.2, JWT tokens can be used for authentication with GSQL server REST endpoints.   
---  
![financialGraph schema](https://docs.tigergraph.com/tigergraph-server/4.1/API/_images/financialGraph_schema.png)
Figure 1. Sample schema
## [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_schema)Schema
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_show_vertices)show vertices
`GET /gsql/v1/schema/vertices`
Show all the local vertices on a graph or show all the global vertices
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters)Parameters:
Name | Required | Description  
---|---|---  
`graph` | no | Specifies the graph for which vertices should be displayed. If not provided, it indicates that all global vertices should be shown.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example)Example 

Sample Request
    
```
curl -X GET -H 'Content-Type: application/json' -u tigergraph:tigergraph "http://localhost:14240/gsql/v1/schema/vertices?graph=financialGraph"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":[{"Config":{"STATS":"OUTDEGREE_BY_EDGETYPE"},"Attributes":[{"IsUsingNewSyntax":true,"AttributeType":{"Name":"STRING"},"AttributeName":"name","IsPrimaryKey":true},{"AttributeType":{"Name":"BOOL"},"AttributeName":"isBlocked"}],"PrimaryId":{"IsUsingNewSyntax":true,"AttributeType":{"Name":"STRING"},"AttributeName":"name","IsPrimaryKey":true},"Name":"Account"},{"Config":{"STATS":"OUTDEGREE_BY_EDGETYPE"},"Attributes":[{"IsUsingNewSyntax":true,"AttributeType":{"Name":"STRING"},"AttributeName":"name","IsPrimaryKey":true}],"PrimaryId":{"IsUsingNewSyntax":true,"AttributeType":{"Name":"STRING"},"AttributeName":"name","IsPrimaryKey":true},"Name":"City"},{"Config":{"STATS":"OUTDEGREE_BY_EDGETYPE"},"Attributes":[{"IsUsingNewSyntax":true,"AttributeType":{"Name":"STRING"},"AttributeName":"name","IsPrimaryKey":true},{"AttributeType":{"Name":"BOOL"},"AttributeName":"isBlocked"}],"PrimaryId":{"IsUsingNewSyntax":true,"AttributeType":{"Name":"STRING"},"AttributeName":"name","IsPrimaryKey":true},"Name":"Phone"}]}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_show_a_vertex)show a vertex
`GET /gsql/v1/schema/vertices/{vertexName}`
Show a local/global vertex.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_2)Parameters:
Name | Required | Description  
---|---|---  
`graph` | no | Specifies the graph for which the vertex should be displayed. If not provided, it indicates that the global vertex should be shown.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_2)Example 

Sample Request
    
```
curl -X GET -H 'Content-Type: application/json' -u tigergraph:tigergraph "http://localhost:14240/gsql/v1/schema/vertices/Account?graph=financialGraph"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":{"Config":{"STATS":"OUTDEGREE_BY_EDGETYPE"},"Attributes":[{"IsUsingNewSyntax":true,"AttributeType":{"Name":"STRING"},"AttributeName":"name","IsPrimaryKey":true},{"AttributeType":{"Name":"BOOL"},"AttributeName":"isBlocked"}],"PrimaryId":{"IsUsingNewSyntax":true,"AttributeType":{"Name":"STRING"},"AttributeName":"name","IsPrimaryKey":true},"Name":"Account"}}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_vertex_using_gsql_command)create vertex using gsql command
`POST /gsql/v1/schema/vertices`
Create global vertices using json contains gsql command
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_3)Parameters:
Name | Required | Description  
---|---|---  
`gsql` | no | Indicates whether to use the GSQL command for creation. Here must be set to true. The request body should contain the GSQL command within the JSON object.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_3)Example 

Sample Request
    
```
curl -X POST -H 'Content-Type: application/json' -u tigergraph:tigergraph "http://localhost:14240/gsql/v1/schema/vertices?gsql=true" -d '{"gsql":["CREATE VERTEX UserA (PRIMARY_ID user_id UINT, name STRING)", "CREATE VERTEX UserB (PRIMARY_ID user_id UINT, name STRING)"]}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully create vertices: [UserA, UserB]"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_add_global_vertices_to_a_local_graph)add global vertices to a local graph
`POST /gsql/v1/schema/vertices`
Add existing global vertices to a local graph
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_4)Parameters:
Name | Required | Description  
---|---|---  
`graph` | no | Specifies the graph to which the global vertices should be added. Here must provide.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_4)Example 

Sample Request
    
```
curl -X POST -H 'Content-Type: application/json' -u tigergraph:tigergraph "http://localhost:14240/gsql/v1/schema/vertices?graph=financialGraph" -d '{"addVertices":["UserA","UserB"]}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully add vertices: [UserA, UserB] on graph financialGraph"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_vertices_create_vertices_in_global_level)create vertices (create vertices in global level)
`POST /gsql/v1/schema/vertices`
This api is used to create global vertices using json
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_5)Parameters:
None
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_5)Example 

Sample Request
    
```
curl -X POST -H 'Content-Type: application/json' -u tigergraph:tigergraph "http://localhost:14240/gsql/v1/schema/vertices" -d '{
  "createVertices": [
    {
      "Config": {
        "STATS": "OUTDEGREE_BY_EDGETYPE"
      },
      "Attributes": [
        {
          "AttributeType": {
            "Name": "STRING"
          },
          "AttributeName": "name"
        }
      ],
      "PrimaryId": {
        "AttributeType": {
          "Name": "UINT"
        },
        "AttributeName": "user_id"
      },
      "Name": "User5"
    },
    {
      "Config": {
        "STATS": "OUTDEGREE_BY_EDGETYPE"
      },
      "Attributes": [
        {
          "AttributeType": {
            "Name": "STRING"
          },
          "AttributeName": "name"
        }
      ],
      "PrimaryId": {
        "AttributeType": {
          "Name": "UINT"
        },
        "AttributeName": "user_id"
      },
      "Name": "User4"
    }
  ]
}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully create vertices: [User5, User4]"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_vertices)drop vertices
`DELETE /gsql/v1/schema/vertices`
Drop local vertices on specific graph or drop global vertices.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_6)Parameters:
Name | Required | Description  
---|---|---  
`vertex` | yes | Specifies the vertex types to be deleted. If there are multiple vertex types, separate them with commas. Use "all" to delete all vertices.  
`graph` | no | Specifies the graph from which vertices should be deleted. If not provided, it indicates that global vertices should be dropped.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_6)Example 

Sample Request
    
```
curl -X DELETE -H "content-type: text/plain" -u tigergraph:tigergraph "http://localhost:14240/gsql/v1/schema/vertices?vertex=user5,user4"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Vertices [user5, user4] deleted successfully."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_a_vertex)drop a vertex
`DELETE /gsql/v1/schema/vertices/{vertexName}`
Drop a local/global vertex.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_7)Parameters:
Name | Required | Description  
---|---|---  
`graph` | no | Specifies the graph from which the vertex should be deleted. If not provided, it indicates that a global vertex should be dropped.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_7)Example 

Sample Request
    
```
curl -X DELETE -H "content-type: text/plain" -u tigergraph:tigergraph "http://localhost:14240/gsql/v1/schema/vertices/userB?graph=financialGraph"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Vertices [userB] deleted successfully."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_update_a_vertex_attribute)update a vertex attribute
`PUT /gsql/v1/schema/vertices/{vertexName}`
Update a vertex attributes.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_8)Parameters:
Name | Required | Description  
---|---|---  
`graph` | no | Specifies the graph in which the vertex attributes should be updated. If not provided, it indicates that the attributes of a global vertex should be updated.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_8)Example 

Sample Request
    
```
curl -X PUT -H "content-type: application/json" -u tigergraph:tigergraph "http://localhost:14240/gsql/v1/schema/vertices/Account?graph=financialGraph" -d '{"dropAttributes":["isBlocked"],"addAttributes":[{"AttributeType":{"Name":"STRING"},"AttributeName":"attr1"}]}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully update vertex: Account"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_show_all_indexes)show all indexes
`GET /gsql/v1/schema/indexes`
Display all indexes within a specific graph or across all global vertices.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_9)Parameters:
Name | Required | Description  
---|---|---  
`graph` | no | Specifies the graph for which to display indexes. If not provided, all indexes on global vertices will be shown.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_9)Example 

Sample Request
    
```
curl -X GET -H "content-type: text/plain" -u tigergraph:tigergraph "http://localhost:14240/gsql/v1/schema/indexes?graph=financialGraph"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":[{"Account":[{"index":"index_type_name","attribute":"name"}]}]}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_show_an_index)show an index
`GET /gsql/v1/schema/indexes/{indexName}`
This endpoint endpoint is used to retrieve information about a specific index.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_10)Parameters:
Name | Required | Description  
---|---|---  
`graph` | no | Specifies the graph in which the index is located.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_10)Example 

Sample Request
    
```
curl -X GET -H "content-type: text/plain" -u tigergraph:tigergraph "http://localhost:14240/gsql/v1/schema/indexes/index_type_name?graph=financialGraph"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":{"index":"index_type_name","attribute":"name"}}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_indexes)create indexes
`POST /gsql/v1/schema/indexes`
Create indexes.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_11)Parameters:
Name | Required | Description  
---|---|---  
`graph` | no | Specifies the graph where the indexes should be created. If not provided, the indexes will be created in the default graph.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_11)Example: 

Sample Request
    
```
curl -X POST -H "content-type: text/plain" -u tigergraph:tigergraph "http://localhost:14240/gsql/v1/schema/indexes?graph=financialGraph" -d '{"vertex":"Account","addIndexAttributes":[{"indexName":"nameIndex","attributeName":"name"}]}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully add index nameIndex on attribute name\n"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_an_index)drop an index
`DELETE /gsql/v1/schema/indexes/{indexName}`
Drop an index.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_12)Parameters:
Name | Required | Description  
---|---|---  
`vertex` | yes | Specifies the vertex from which to drop the index  
`graph` | no | Specifies the graph from which the index should be dropped. If not specified, the index will be dropped from the global vertex.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_12)Example: 

Sample Request
    
```
curl -X DELETE -H "content-type: text/plain" -u tigergraph:tigergraph "http://localhost:14240/gsql/v1/schema/indexes/nameIndex"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully drop index"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_indexes)drop indexes
`DELETE /gsql/v1/schema/indexes`
Drop indexes.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_13)Parameters:
Name | Required | Description  
---|---|---  
`vertex` | yes | Specifies the vertex on which to drop the indexes.  
`index` | yes | Specifies the indexes to drop (separated by commas)  
`graph` | no | Specifies the graph from which the indexes should be dropped.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_13)Example: 

Sample Request
    
```
curl -X DELETE -H "content-type: text/plain" -u tigergraph:tigergraph "http://localhost:14240/gsql/v1/schema/indexes?graph=financialGraph&vertex=Account&index=nameIndex"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully drop index"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_all_edges)get all edges
`GET /gsql/v1/schema/edges`
Retrieve all local edges within a specific graph or retrieve all global edges.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_14)Parameters:
Name | Required | Description  
---|---|---  
`graph` | no | Specifies the graph from which to retrieve the edges. If not provided, means to get all global edges.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_14)Example: 

Sample Request
    
```
curl -X GET -H 'Content-Type: application/json' -u tigergraph:tigergraph "http://localhost:14240/gsql/v1/schema/edges?graph=financialGraph"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":[{"IsDirected":true,"ToVertexTypeName":"Account","Config":{"REVERSE_EDGE":"Transfer_Reverse"},"DiscriminatorCount":1,"Attributes":[{"AttributeType":{"Name":"DATETIME"},"IsDiscriminator":true,"AttributeName":"date"},{"AttributeType":{"Name":"UINT"},"AttributeName":"amount"}],"FromVertexTypeName":"Account","CompositeDiscriminator":["date"],"Name":"Transfer"},{"IsDirected":false,"ToVertexTypeName":"Phone","Config":{},"Attributes":[],"FromVertexTypeName":"Account","Name":"hasPhone"},{"IsDirected":true,"ToVertexTypeName":"City","Config":{},"Attributes":[],"FromVertexTypeName":"Account","Name":"isLocatedIn"}]}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_retrieve_a_specific_edge_type_info)retrieve a specific edge type info
`GET /gsql/v1/schema/edges/{edgeName}`
Retrieve information about a specific edge type within a local graph, or retrieve information about a specific global edge type.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_15)Parameters:
Name | Required | Description  
---|---|---  
`graph` | no | Specifies the graph in which the edge type is located. If not provided, it retrieves the global edge type information.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_15)Example: 

Sample Request
    
```
curl -X GET -H 'Content-Type: application/json' -u tigergraph:tigergraph "http://localhost:14240/gsql/v1/schema/edges/isLocatedIn?graph=financialGraph"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":{"IsDirected":true,"ToVertexTypeName":"City","Config":{},"Attributes":[],"FromVertexTypeName":"Account","Name":"isLocatedIn"}}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_edges_using_gsql_command_statement)create edges using gsql command statement
`POST /gsql/v1/schema/edges`
Create global edges using gsql command statement.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_16)Parameters:
Name | Required | Description  
---|---|---  
`gsql` | no | Indicates whether to use the GSQL command for creating edges. Here must set to true. The request body should contain the GSQL command within the JSON object.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_16)Example: 

Sample Request
    
```
curl -X POST -H 'Content-Type: application/json' -u tigergraph:tigergraph "http://localhost:14240/gsql/v1/schema/edges?gsql=true" -d '{"gsql":["CREATE UNDIRECTED EDGE edge1 (from Account, to City, attr1 float)", "CREATE UNDIRECTED EDGE edge2 (from Account, to Phone, attr2 float)"]}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully create edges: [edge1, edge2]"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_add_global_edges_to_graph_using_json_format)add global edges to graph using json format
`POST /gsql/v1/schema/edges`
Add global edges to graph using json format.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_17)Parameters:
Name | Required | Description  
---|---|---  
`graph` | no | Specifies the graph to which the global edges will be added. Here must provide.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_17)Example: 

Sample Request
    
```
curl -X POST -H "content-type: application/json" -H 'Content-Type: application/json' -u tigergraph:tigergraph "http://localhost:14240/gsql/v1/schema/edges?graph=financialGraph" -d '{"addEdges":["has_account"]}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully added edges [has_account] to graph financialGraph."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_global_edges_using_json_format)create global edges using json format
`POST /gsql/v1/schema/edges`
Create global edges using json format.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_18)Parameters:
None
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_18)Example: 

Sample Request
    
```
curl -X POST -H 'Content-Type: application/json' -u tigergraph:tigergraph "http://localhost:14240/gsql/v1/schema/edges" -d ' {"createEdges":["IsDirected":true,"ToVertexTypeName":"City","Config":{},"Attributes":[],"FromVertexTypeName":"Account","Name":"isLocatedIn"},"IsDirected":true,"ToVertexTypeName":"Phone","Config":{},"Attributes":[],"FromVertexTypeName":"Account","Name":"hasPhone"}]}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully create edges: [isLocatedIn, hasPhone]"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_edges_from_graph)drop edges from graph
`DELETE /gsql/v1/schema/edges`
Drop edges from a graph or drop global edges.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_19)Parameters:
Name | Required | Description  
---|---|---  
`edge` | yes | Specifies the edge types to be deleted. If there are multiple edge types, separate them with a comma. Use 'all' to drop all edges.  
`graph` | no | Specifies the graph from which the edges will be deleted. If not provided, it means the operation will drop global edges.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_19)Example: 

Sample Request
    
```
curl -X DELETE -H 'Content-Type: application/json' -u tigergraph:tigergraph "http://localhost:14240/gsql/v1/schema/edges?edge=hasPhone&graph=financialGraph"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Edges [hasPhone] deleted successfully."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_an_edge)drop an edge
`DELETE /gsql/v1/schema/edges/{edgeName}`
Drop a local/global edge.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_20)Parameters:
Name | Required | Description  
---|---|---  
`graph` | no | Specifies the graph from which the edge will be deleted. If not provided, it means the operation will drop a global edge.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_20)Example: 

Sample Request
    
```
curl -X DELETE -H "content-type: text/plain" -u tigergraph:tigergraph "http://localhost:14240/gsql/v1/schema/edges/hasPhone?graph=financialGraph"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Edges [hasPhone] deleted successfully."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_update_attribute_in_edge)update attribute in edge
`PUT /gsql/v1/schema/edges/{edgeName}`
Update attributes in edge.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_21)Parameters:
Name | Required | Description  
---|---|---  
`graph` | no | Specifies the graph in which the edge’s attributes will be updated. If not provided, it means the operation will update attributes on the global level.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_21)Example: 

Sample Request
    
```
curl -X PUT -H 'Content-Type: application/json' -u tigergraph:tigergraph "http://localhost:14240/gsql/v1/schema/edges/Transfer?graph=financialGraph" -d '{"dropAttributes":["date"],"addAttributes":[{"AttributeType":{"Name":"STRING"},"AttributeName":"attr"}]}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully update edge: Transfer"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_show_all_graphs_info_that_only_contains_the_name_of_vertices_and_edges)show all graphs info that only contains the name of vertices and edges
`GET /gsql/v1/schema/graphs`
Show all graphs info only containing names of vertices and edges.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_22)Parameters:
None
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_22)Example: 

Sample Request
    
```
curl -X GET -H 'Content-Type: application/json' -u tigergraph:tigergraph "http://localhost:14240/gsql/v1/schema/graphs"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"graphs":[{"graphName":"financialGraph","vertices":["Account","City","Phone"],"edges":["Transfer","Transfer_Reverse","hasPhone","isLocatedIn"]}],"error":false,"message":""}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_show_one_graph_detailed_info_with_given_graph_name)show one graph detailed info with given graph name
`GET /gsql/v1/schema/graphs/{graph}`
Show one graph detailed info with given graph name.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_23)Parameters:
None
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_23)Example: 

Sample Request
    
```
curl -X GET -H "content-type: application/json" -u tigergraph:tigergraph "http://localhost:14240/gsql/v1/schema/graphs/financialGraph"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":{"GraphName":"financialGraph","VertexTypes":[{"Config":{"STATS":"OUTDEGREE_BY_EDGETYPE"},"Attributes":[{"AttributeType":{"Name":"BOOL"},"AttributeName":"isBlocked"},{"AttributeType":{"Name":"STRING"},"AttributeName":"name"}],"PrimaryId":{"AttributeType":{"Name":"UINT"},"AttributeName":"id"},"Name":"Account"},{"Config":{"STATS":"OUTDEGREE_BY_EDGETYPE"},"Attributes":[{"AttributeType":{"Name":"STRING"},"AttributeName":"name"}],"PrimaryId":{"AttributeType":{"Name":"UINT"},"AttributeName":"id"},"Name":"City"},{"Config":{"STATS":"OUTDEGREE_BY_EDGETYPE"},"Attributes":[{"AttributeType":{"Name":"BOOL"},"AttributeName":"isBlocked"},{"AttributeType":{"Name":"STRING"},"AttributeName":"number"}],"PrimaryId":{"AttributeType":{"Name":"UINT"},"AttributeName":"id"},"Name":"Phone"}],"EdgeTypes":[{"IsDirected":true,"ToVertexTypeName":"City","Config":{},"Attributes":[],"FromVertexTypeName":"Account","Name":"isLocatedIn"},{"IsDirected":true,"ToVertexTypeName":"Phone","Config":{},"Attributes":[],"FromVertexTypeName":"Account","Name":"hasPhone"}, {"IsDirected":false,"ToVertexTypeName":"Account","Config":{"REVERSE_EDGE":"Transfer_Reverse"},"Attributes":[{"AttributeType":{"Name":"UINT"},"AttributeName":"amount"},{"AttributeType":{"Name":"DATETIME"},"AttributeName":"date"}],"FromVertexTypeName":"Account","Name":"Transfer"}]}}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_one_graph_using_gsql_command)create one graph using gsql command
`POST /gsql/v1/schema/graphs`
Create one graph using gsql command.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_24)Parameters:
Name | Required | Description  
---|---|---  
`gsql` | no | default: false. Indicates whether to use the GSQL command for creation. Here must be set to true. The request body should contain the GSQL command within the JSON object.  
`graphName` | yes | Specifies the name of the graph to be created.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_24)Example: 

Sample Request
    
```
curl -X POST -H "content-type: application/json" "http://localhost:14240/gsql/v1/schema/graphs?gsql=true" -d '{"gsql": "create graph g(*)"}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully created graph: [g]."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_one_graph_using_json_format)create one graph using JSON format
`POST /gsql/v1/schema/graphs`
Create one graph using JSON format.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_25)Parameters:
Name | Required | Description  
---|---|---  
`gsql` | no | default: false. Indicates whether to use a GSQL command for graph creation. Here must set to false to use JSON format.  
`graphName` | yes | Specifies the name of the graph to be created.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_25)Example: 

Sample Request
    
```
curl -X POST -H "content-type: application/json" "http://localhost:14240/gsql/v1/schema/graphs?graphName=gtest&gsql=false
" -d '{"VertexTypes":["Account","Phone"], "EdgeTypes":["hasPhone"]}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully created graph: [gtest]."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_one_graph)drop one graph
`DELETE /gsql/v1/schema/graphs/{graphName}`
Drop one graph.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_26)Parameters:
Name | Required | Description  
---|---|---  
`cascade` | no | default: `false`. If set to `true`, it will automatically drop the queries and loading jobs associated with this graph. If set to `false`, the operation will fail if there are any existing queries or loading jobs related to the graph.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_26)Example: 

Sample Request
    
```
curl -X DELETE -H "content-type: text/plain" "http://localhost:14240/gsql/v1/schema/graphs/financialGraph?cascade=true"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully dropped graph: financialGraph."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_graphs_with_given_names)drop graphs with given names
`DELETE /gsql/v1/schema/graphs`
Drop graphs with given names.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_27)Parameters:
Name | Required | Description  
---|---|---  
`graphNames` | yes | Specifies the names of the graphs to be dropped, separated by commas. Use 'all' to drop all graphs.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_27)Example: 

Sample Request
    
```
curl -X DELETE -H "content-type: text/plain" "http://localhost:14240/gsql/v1/schema/graphs?graphNames=financialGraph,recommend"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully dropped graphs: [financialGraph, recommend]."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_localglobal_schema_change_jobs)drop local/global schema change jobs
`DELETE /gsql/v1/schema/jobs`
Drop local/global schema change jobs.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_28)Parameters:
Name | Required | Description  
---|---|---  
`jobName` | yes | Specifies the schema jobs to drop, separated by commas.  
`graph` | no | Specifies the graph whose jobs are to be dropped. If not provided, means drop the global schema change jobs.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_28)Example: 

Sample Request
    
```
curl -X DELETE -H "content-type: text/plain" "http://localhost:14240/gsql/v1/schema/jobs?jobName=test1,test2&graph=financialGraph"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully dropped schema change jobs: [test1, test2]."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_localglobal_schema_change_job_using_gsql_command)create local/global schema change job using gsql command
`POST /gsql/v1/schema/jobs/{jobName}`
Create local/global schema change job using gsql command.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_29)Parameters:
Name | Required | Description  
---|---|---  
`gsql` | no | Indicates whether to use the GSQL command for creation. Here must be set to true. The request body should contain the GSQL command within the JSON object.  
`graph` | no | Which graph to create schema change. Global schema change doesn’t need provide.  
`type` | no | When creating a global schema change job, provide `global`. This is not required for local schema change jobs.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_29)Example: 

Sample Request
    
```
curl -X POST -H "content-type: text/plain" "http://localhost:14240/gsql/v1/schema/jobs/test3?gsql=true&type=global" -d ' {"gsql" : "create global schema_change job test3 {add vertex website to graph financialGraph;}"}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully created global schema change job: [test3]."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_global_schema_change_job_using_json)create global schema change job using json
`POST /gsql/v1/schema/jobs/{jobName}`
Create global schema change job using json.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_30)Parameters:
None
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_30)Example: 

Sample Request
    
```
curl -X POST -H "content-type: application/json" "http://localhost:14240/gsql/v1/schema/jobs/test4" -d '{"graphs": [{"graphName":"financialGraph","addVertexTypes":["user","website"],"dropVertexTypes":[], "dropEdgeTypes":[],"addEdgeTypes":[]}]}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully created global schema change job: [test4]."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_local_schema_change_job_using_json)create local schema change job using json
`POST /gsql/v1/schema/jobs/{jobName}`
Create local schema change job using json.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_31)Parameters:
Name | Required | Description  
---|---|---  
`graph` | no | The graph whose schema change job is to be created. Here should provide.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_31)Example:
Assuming we already have the following vertices and edges in the local graph financialGraph:
```
VERTEX LocalAccount (
  name STRING PRIMARY KEY,
  isBlocked BOOL
)
VERTEX LocalCity (
  name STRING PRIMARY KEY
)
VERTEX LocalPhone (
  name STRING PRIMARY KEY,
  isBlocked BOOL
)
DIRECTED EDGE LocalTransfer (
  FROM Account,
  TO Account,
  DISCRIMINATOR(date DATETIME),
  amount UINT
) WITH REVERSE_EDGE="LocalTransfer_Reverse"
UNDIRECTED EDGE LocalhasPhone (
  FROM Account,
  TO Phone
)
DIRECTED EDGE LocalisLocatedIn (
  FROM Account,
  TO City
)
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Request
    
```
curl -X POST -H "content-type: application/json" -u tigergraph:tigergraph "http://localhost:14240/gsql/v1/schema/jobs/test5?graph=financialGraph" -d '
{
  "dropVertexTypes": [
    "LocalPhone"
  ],
  "alterVertexTypes": [
    {
      "name": "LocalAccount",
      "addAttributes": [
        {
          "DefaultValue": "defaultValue1",
          "AttributeType": {
            "Name": "STRING"
          },
          "AttributeName": "attr2"
        }
      ],
      "addIndexAttributes": [
        {
          "indexName": "ppIndex",
          "attributeName": "name"
        }
      ]
    }
  ],
  "addVertexTypes": [
    {
      "Config": {
        "STATS": "OUTDEGREE_BY_EDGETYPE"
      },
      "Attributes": [
        {
          "AttributeType": {
            "Name": "STRING"
          },
          "AttributeName": "name"
        }
      ],
      "PrimaryId": {
        "AttributeType": {
          "Name": "UINT"
        },
        "AttributeName": "user_id"
      },
      "Name": "User5"
    },
    {
      "Config": {
        "STATS": "OUTDEGREE_BY_EDGETYPE"
      },
      "Attributes": [
        {
          "AttributeType": {
            "Name": "STRING"
          },
          "AttributeName": "name"
        }
      ],
      "PrimaryId": {
        "AttributeType": {
          "Name": "UINT"
        },
        "AttributeName": "user_id"
      },
      "Name": "User4"
    }
  ],
  "addEdgeTypes": [
    {
      "IsDirected": true,
      "ToVertexTypeName": "User4",
      "Config": {
      },
      "IsLocal": true,
      "Attributes": [
        {
          "AttributeType": {
            "Name": "DATETIME"
          },
          "AttributeName": "live_date"
        }
      ],
      "FromVertexTypeName": "User5",
      "Name": "edge1"
    }
  ],
  "dropEdgeTypes": [
    "LocalhasPhone"
  ],
  "alterEdgeTypes": [
    {
      "dropAttributes": [
        "amount"
      ],
      "addAttributes": [
        {
          "DefaultValue": "defaultValue1",
          "AttributeType": {
            "Name": "STRING"
          },
          "AttributeName": "attr2"
        }
      ],
      "name": "LocalTransfer"
    }
  ]
}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully created schema change job: [test5]."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_a_specific_localglobal_schema_change_job)get a specific local/global schema change job
`GET /gsql/v1/schema/jobs/{jobName}`
Retrieve a specific local/global schema change job.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_32)Parameters:
Name | Required | Description  
---|---|---  
`graph` | no | the graph whose schema change job to show. don’t provide this if get a global schema change job.  
`json` | yes | Set to `true` to receive the response in JSON format; otherwise, the response will be in text format.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_32)Example: 

Sample Request
    
```
curl -X GET -H "content-type: application/json" "http://localhost:14240/gsql/v1/schema/jobs/job12?json=true&graph=financialGraph"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":{"job12":{"dropVertexTypes":[],"addTags":[],"name":"job12","alterVertexTypes":[],"addVertexTypes":[{"Config":{"STATS":"OUTDEGREE_BY_EDGETYPE"},"Attributes":[{"IsUsingNewSyntax":true,"AttributeType":{"Name":"STRING"},"AttributeName":"name","IsPrimaryKey":true},{"AttributeType":{"Name":"BOOL"},"AttributeName":"isBlocked"}],"PrimaryId":{"IsUsingNewSyntax":true,"AttributeType":{"Name":"STRING"},"AttributeName":"name","IsPrimaryKey":true},"Name":"LocalAccount"},{"Config":{"STATS":"OUTDEGREE_BY_EDGETYPE"},"Attributes":[{"IsUsingNewSyntax":true,"AttributeType":{"Name":"STRING"},"AttributeName":"name","IsPrimaryKey":true}],"PrimaryId":{"IsUsingNewSyntax":true,"AttributeType":{"Name":"STRING"},"AttributeName":"name","IsPrimaryKey":true},"Name":"LocalCity"},{"Config":{"STATS":"OUTDEGREE_BY_EDGETYPE"},"Attributes":[{"IsUsingNewSyntax":true,"AttributeType":{"Name":"STRING"},"AttributeName":"name","IsPrimaryKey":true},{"AttributeType":{"Name":"BOOL"},"AttributeName":"isBlocked"}],"PrimaryId":{"IsUsingNewSyntax":true,"AttributeType":{"Name":"STRING"},"AttributeName":"name","IsPrimaryKey":true},"Name":"LocalPhone"}],"addEdgeTypes":[{"IsDirected":true,"ToVertexTypeName":"Account","Config":{"REVERSE_EDGE":"LocalTransfer_Reverse"},"DiscriminatorCount":1,"Attributes":[{"AttributeType":{"Name":"DATETIME"},"IsDiscriminator":true,"AttributeName":"date"},{"AttributeType":{"Name":"UINT"},"AttributeName":"amount"}],"FromVertexTypeName":"Account","Name":"LocalTransfer"},{"IsDirected":false,"ToVertexTypeName":"Phone","Config":{},"Attributes":[],"FromVertexTypeName":"Account","Name":"LocalhasPhone"},{"IsDirected":true,"ToVertexTypeName":"City","Config":{},"Attributes":[],"FromVertexTypeName":"Account","Name":"LocalisLocatedIn"}],"dropEdgeTypes":[],"graph":"financialGraph","alterEdgeTypes":[],"dropTags":[]}}}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_run_global_schema_change_job_directly)run global schema change job directly
`POST /gsql/v1/schema/change`
Run global schema change job directly.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_33)Parameters:
None
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_33)Example: 

Sample Request
    
```
curl -X POST -H "content-type: application/json" -u tigergraph:tigergraph "http://localhost:14240/gsql/v1/schema/change" -d '
 {"addVertexTypes":[{"Config":{"STATS":"OUTDEGREE_BY_EDGETYPE"},"Attributes":[{"AttributeType":{"Name":"STRING"},"AttributeName":"name"}],"PrimaryId":{"AttributeType":{"Name":"UINT"},"AttributeName":"user_id"},"Name":"User5"},
{"Config":{"STATS":"OUTDEGREE_BY_EDGETYPE"},"Attributes":[{"AttributeType":{"Name":"STRING"},"AttributeName":"name"}],"PrimaryId":{"AttributeType":{"Name":"UINT"},"AttributeName":"user_id"},"Name":"User4"}
]}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Global schema change runs successfully"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_run_the_schema_change_job_directly)run the schema change job directly
`POST /gsql/v1/schema/change`
Run the schema change job directly.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_34)Parameters:
Name | Required | Description  
---|---|---  
`graph` | no | which graph to run the local schema change job on, run local schema change need provide this. If not provided, means running global schema change job.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_34)Example: 

Sample Request
    
```
curl -X POST -H "content-type: application/json" "http://localhost:14240/gsql/v1/schema/change?graph=financialGraph" -d '
{
  "dropVertexTypes": [],
  "alterVertexTypes": [
    {
      "name": "LocalAccount",
      "dropAttributes": [],
      "addAttributes": [
        {
          "DefaultValue": "defaultValue1",
          "AttributeType": {
            "Name": "STRING"
          },
          "AttributeName": "attr2"
        }
      ],
      "dropIndexAttributes": [],
      "addIndexAttributes": [
        {
          "indexName": "xIndex",
          "attributeName": "name"
        },
        {
          "indexName": "yIndex",
          "attributeName": "isBlocked"
        }
      ]
    }
  ],
  "addVertexTypes": [
    {
      "Config": {
        "STATS": "OUTDEGREE_BY_EDGETYPE"
      },
      "Attributes": [
        {
          "AttributeType": {
            "Name": "STRING"
          },
          "AttributeName": "name"
        }
      ],
      "PrimaryId": {
        "AttributeType": {
          "Name": "UINT"
        },
        "AttributeName": "user_id"
      },
      "Name": "User5"
    },
    {
      "Config": {
        "STATS": "OUTDEGREE_BY_EDGETYPE"
      },
      "Attributes": [
        {
          "AttributeType": {
            "Name": "STRING"
          },
          "AttributeName": "name"
        }
      ],
      "PrimaryId": {
        "AttributeType": {
          "Name": "UINT"
        },
        "AttributeName": "user_id"
      },
      "Name": "User4"
    }
  ],
  "addEdgeTypes": [
    {
      "IsDirected": true,
      "ToVertexTypeName": "User4",
      "Config": {},
      "IsLocal": true,
      "Attributes": [
        {
          "AttributeType": {
            "Name": "DATETIME"
          },
          "AttributeName": "live_date"
        }
      ],
      "FromVertexTypeName": "User5",
      "Name": "edge1"
    }
  ],
  "dropEdgeTypes": [],
  "alterEdgeTypes": [
    {
      "dropAttributes": ["isBlocked"],
      "addAttributes": [
        {
          "DefaultValue": "defaultValue1",
          "AttributeType": {
            "Name": "STRING"
          },
          "AttributeName": "attr2"
        }
      ],
      "name": "LocalPhone"
    }
  ]
}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Schema change job runs successfully"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_run_an_existing_schema_change_job)run an existing schema change job
`POST /gsql/v1/schema/jobs/{jobName}`
Run an existing schema change job.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_35)Parameters:
Name | Required | Description  
---|---|---  
`graph` | no | which graph to run the schema change job on. If not provided, means run the global schema change job.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_35)Example: 

Sample Request
    
```
curl -X POST -H "content-type: application/json" "http://localhost:14240/gsql/v1/schema/jobs/test5?graph=financialGraph"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Schema change job run successfully!"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_schema_change_jobs)get schema change jobs
`GET /gsql/v1/schema/jobs`
Get all local/global schema change jobs.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_36)Parameters:
Name | Required | Description  
---|---|---  
`graph` | no | The graph whose schema change job to show. If not provided, means to get all the global schema change job.  
`json` | yes | Set to `true` means response in JSON format; otherwise, the response will be in text format.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_36)Example: 

Sample Request
    
```
curl -X GET -H "content-type: application/json" -u tigergraph:tigergraph "http://localhost:14240/gsql/v1/schema/jobs?graph=financialGraph"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":[{"job12":"CREATE SCHEMA_CHANGE JOB job12 FOR GRAPH financialGraph {\n   ADD VERTEX LocalAccount(name STRING primary key, isBlocked BOOL) WITH STATS=\"OUTDEGREE_BY_EDGETYPE\";\n   ADD VERTEX LocalCity(name STRING primary key) WITH STATS=\"OUTDEGREE_BY_EDGETYPE\";\n   ADD VERTEX LocalPhone(name STRING primary key, isBlocked BOOL) WITH STATS=\"OUTDEGREE_BY_EDGETYPE\";\n   ADD DIRECTED EDGE LocalTransfer(FROM Account, TO Account, DISCRIMINATOR( date DATETIME), amount UINT) WITH REVERSE_EDGE=\"LocalTransfer_Reverse\";\n   ADD UNDIRECTED EDGE LocalhasPhone(FROM Account, TO Phone);\n   ADD DIRECTED EDGE LocalisLocatedIn(FROM Account, TO City);\n  }\n"},{"test5":"CREATE SCHEMA_CHANGE JOB test5 {\n   ADD VERTEX User5(PRIMARY_ID user_id UINT, name STRING) WITH STATS=\"OUTDEGREE_BY_EDGETYPE\";\n   ADD VERTEX User4(PRIMARY_ID user_id UINT, name STRING) WITH STATS=\"OUTDEGREE_BY_EDGETYPE\";\n   ADD DIRECTED EDGE edge1(FROM User5, TO User4, live_date DATETIME);\n   DROP VERTEX LocalPhone;\n   DROP EDGE LocalhasPhone;\n   ALTER VERTEX LocalAccount ADD ATTRIBUTE (attr2 STRING DEFAULT \"defaultValue1\");\n   ALTER VERTEX LocalAccount ADD INDEX ppIndex ON (name);\n   ALTER EDGE LocalTransfer ADD ATTRIBUTE (attr2 STRING DEFAULT \"defaultValue1\");\n   ALTER EDGE LocalTransfer DROP ATTRIBUTE (amount);\n  }\n"}]}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_loading_jobs)Loading Jobs
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_loading_job_names)Get loading job names
`GET /gsql/v1/loading-jobs`
Get the names of all loading jobs in the given graph.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_37)Parameters:
Name | Required | Description  
---|---|---  
`graph` | yes | name of the graph that these jobs belong to  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_37)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X GET
'http://localhost:14240/gsql/v1/loading-jobs?graph=financialGraph'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","jobNames":["incidents_fraud_report_company_csv"]}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_loading_job_information)Get loading job information
`GET /gsql/v1/loading-jobs/{jobName}`
Get information about a specific loading job.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_38)Parameters:
Name | Required | Description  
---|---|---  
`graph` | yes | name of the graph that this job belongs to  
`verbose` | no | If `true`: show more details. If `false` (default): show fewer details.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_38)Example 

Sample Request
    
```
curl -H 'Content-Type: applicaiton/json' -X GET
'http://localhost:14240/gsql/v1/loading-jobs/incidents_fraud_report_company_csv?graph=financialGraph&json=[true/false]'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
json=false:
```
{"error":false,"message":"","results":{"jobName":"incidents_fraud_report_company_csv","jobContent":"this is jobContent"}}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

json=true:
```
{"error":false,"message":"","results":{"Filters":[],"GraphName":"g","Headers":{"f1_header":["report_id","report_updated_at","report_status","report_type","report_source","report_data_source","fraud_type","tax_id"],"f1_header_company":["tax_id","report_updated_at","tax_status"]},"JobName":"incidents_fraud_report_company_csv","FileNames":{"f1":""},"LoadingStatements":[{"Type":"Vertex","UsingClauses":{"QUOTE":"double","EOL":"\\n","SEPARATOR":",","HEADER":"true","USER_DEFINED_HEADER":"f1_header"},"Mappings":[{"Type":"SrcColName","Value":"report_id"},{"Type":"SrcColName","Value":"report_updated_at"},{"Type":"SrcColName","Value":"report_status"},{"Type":"SrcColName","Value":"report_type"},{"Type":"SrcColName","Value":"report_source"},{"Type":"SrcColName","Value":"report_data_source"},{"Type":"SrcColName","Value":"fraud_type"}],"TargetName":"FraudReport","DataSource":{"Type":"FileVar","Value":"f1"}},{"Type":"Vertex","UsingClauses":{"QUOTE":"double","EOL":"\\n","SEPARATOR":",","HEADER":"true","USER_DEFINED_HEADER":"f1_header_company"},"Mappings":[{"Type":"SrcColName","Value":"tax_id"},{"Type":"SrcColName","Value":"report_updated_at"},{"Type":"SrcColName","Value":"tax_status"}],"TargetName":"Company","DataSource":{"Type":"FileVar","Value":"f1"}},{"Type":"Edge","UsingClauses":{"QUOTE":"double","EOL":"\\n","SEPARATOR":",","HEADER":"true","USER_DEFINED_HEADER":"f1_header"},"Mappings":[{"Type":"SrcColName","Value":"report_id"},{"Type":"SrcColName","Value":"tax_id"}],"TargetName":"HasIncident","FromVertexType":"FraudReport","ToVertexType":"Company","DataSource":{"Type":"FileVar","Value":"f1"}}]}}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_a_loading_job)Create a loading job
`POST /gsql/v1/loading-jobs`
Create a new loading job, equivalent to GSQL [CREATE LOADING JOB](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/creating-a-loading-job#_create_loading_job).
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_39)Parameters:
Name | Required | Description  
---|---|---  
`graph` | yes | name of the graph that this job will belong to  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_39)Example 

Sample Request
    
```
curl -H 'Content-Type: text/plain' -X POST 'http://localhost:14240/gsql/v1/loading-jobs?graph=financialGraph'
-d 'CREATE LOADING JOB load_kafka {
 DEFINE FILENAME f1 = "$ka:/tmp/kafka_topic.json";
 LOAD f1
  TO VERTEX company VALUES($0, $1, "2")
  USING SEPARATOR=",";
}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully created loading job: load_kafka"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_update_a_loading_job)Update a loading job
`PUT /gsql/v1/loading-jobs`
Update an existing loading job.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_40)Parameters:
Name | Required | Description  
---|---|---  
`graph` | yes | name of the graph that this job belongs to  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_40)Example 

Sample Request
    
```
curl -H 'Content-Type: text/plain' -X PUT 'http://localhost:14240/gsql/v1/loading-jobs?graph=financialGraph'
-d 'CREATE LOADING JOB load_kafka {
 DEFINE FILENAME f1 = "$ka:/tmp/kafka_topic.json";
 LOAD f1
  TO VERTEX company VALUES($0, $1, "3")
  USING SEPARATOR=",";
}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully created loading job: load_kafka"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_a_loading_job)Drop a loading job
`DELETE /gsql/v1/loading-jobs/{jobName}`
Drop a loading job, equivalent to GSQL [DROP JOB](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/creating-a-loading-job#_drop_job_statement).
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_41)Parameters:
Name | Required | Description  
---|---|---  
`graph` | yes | name of the graph that this job belongs to  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_41)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X DELETE
'http://localhost:14240/gsql/v1/loading-jobs/load_kafka?graph=financialGraph'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error": false,"message":"Successfully drop loading job 'load_kafka'."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_run_a_loading_job)Run a loading job
`POST /gsql/v1/loading-jobs/run`
Run a loading job, equivalent to GSQL [RUN LOADING JOB](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/running-a-loading-job#_run_loading_job).
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_42)Parameters:
Name | Required | Description  
---|---|---  
`graph` | yes | name of the graph that this job belongs to  
The details of the loading job should be specified in the payload. They include the job name, the path to the data sources, and any desired options for running the loading job. There may also be parameters specify to the data source. Below are some examples:
  * **Kafka** : `[{"name":"load_kafka", "streaming":false}, "dataSources":[{"filename":"f1","name":"k1","path":"","config":{"topic":"regress7715","partition_list":[{"start_offset":-2,"partition":0}]}}]]`
  * **S3** : `[{"name":"load_comment","streaming":true,"dataSources":[{"filename":"file_Comment","name":"s1","path":"s3-loading-test/tg_ldbc_snb/sf0.1_csv/dynamic/Comment"}]}]`
  * **Local files** : `[{"name":"load_job","sys.data_root":"/tmp","dataSources":[{"filename":"f","path":"./data","name":"file"}]}]`


#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_42)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X POST -d @header.json
'http://localhost:14240/gsql/v1/loading-jobs/run?graph=financialGraph'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

where the file `header.json` contains
`[{"name":"load_job","sys.data_root":"/tmp","verbose":true,"dryrun":true,"interval":1,"maxNumError":1,"maxPercentError":1 "dataSources":[{"filename":"f","path":"./data","name":"file"}]}]` 

Sample Response
    
```
{"error": false,"message":"Successfully ran loading job(s): [jobName]", "jobIds": ["jobId"]}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_loading_job_run_statuses_multiple_jobs)Get loading job run statuses (multiple jobs)
`GET /gsql/v1/loading-jobs/status`
Get the status of one or more loading jobs that have been started, equivalent to GSQL [SHOW LOADING STATUS](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/managing-loading-job#_show_loading_status).
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_43)Parameters:
Name | Required | Description  
---|---|---  
`jobIds` | yes | ID of the loading job  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_43)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X GET
'http://localhost:14240/gsql/v1/loading-jobs/status/jobIds=financialGraph.load_ldbc_snb.jdbc.all.1111111111121'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":[{"overall":{"averageSpeed":66666,"currentSpeed":55555,"duration":12345,"endTime":1111111123456,"id":"financialGraph.load_ldbc_snb.jdbc.all.1111111111121","progress":0,"size":1236,"startTime":1111111111111,"statistics":{"fileLevel":{"validLine":8},"objectLevel":{"vertex":[{"invalidAttribute":1,"noIdFound":1,"typeName":"Post","validObject":6}]}}},"workers":[{"tasks":[{"filename":"f1"}]}]}]}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_loading_job_run_status_one_job)Get loading job run status (one job)
`GET /gsql/v1/loading-jobs/status/{jobId}`
Get the status of one loading job that has been started. The behavior of this endpoint is the same as that of `GET /gsql/v1/loading-jobs/status/` when only one `jobIds` parameter is used.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_44)Parameters:
Name | Required | Description  
---|---|---  
`jobId` | yes | ID of the loading job  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_44)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X GET
'http://localhost:14240/gsql/v1/loading-jobs/status/financialGraph.load_ldbc_snb.jdbc.all.1111111111121'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":[{"overall":{"averageSpeed":66666,"currentSpeed":55555,"duration":12345,"endTime":1111111123456,"id":"financialGraph.load_ldbc_snb.jdbc.all.1111111111121","progress":0,"size":1236,"startTime":1111111111111,"statistics":{"fileLevel":{"validLine":8},"objectLevel":{"vertex":[{"invalidAttribute":1,"noIdFound":1,"typeName":"Post","validObject":6}]}}},"workers":[{"tasks":[{"filename":"f1"}]}]}]}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_abort_loading_jobs)Abort loading job(s)
`GET /gsql/v1/loading-jobs/abort`
Abort one or more loading jobs, equivalent to GSQL [ABORT LOADING JOB](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/managing-loading-job#_abort_loading_job).
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_45)Parameters:
Name | Required | Description  
---|---|---  
`graph` | yes | name of the graph that this job belongs to  
`jobIds` | yes | ID of one of the loading jobs  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_45)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X GET
'http://localhost:14240/gsql/v1/loading-jobs/abort?graph=financialGraph&jobIds=jobId1'
curl -H 'Content-Type: application/json' -X GET
'http://localhost:14240/gsql/v1/loading-jobs/abort?graph=financialGraph&jobIds=jobId2&isPause=true'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error": false,"message":"Successfully aborted loading job(s): [jobId1]."}
{"error": false,"message":"Successfully paused loading job(s): [jobId2]."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_abort_one_loading_job)Abort one loading job
`GET /gsql/v1/loading-jobs/abort/{jobId}`
Abort one loading job, equivalent to GSQL [ABORT LOADING JOB](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/managing-loading-job#_abort_loading_job). The behavior of this endpoint is the same as that of `GET /gsql/v1/loading-jobs/abort/` when only one `jobIds` parameter is used.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_46)Parameters:
Name | Required | Description  
---|---|---  
`graph` | yes | name of the graph that this job belongs to  
`jobId` | yes | ID of the loading job  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_46)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X GET 'http://localhost:14240/gsql/v1/loading-jobs/jobId1?graph=financialGraph'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error": false,"message":"Successfully aborted loading job(s): [jobId1]."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_resume_loading_job)Resume loading job
`GET /gsql/v1/loading-jobs/resume/{jobId}`
Resume a paused/aborted loading job, equivalent to GSQL [RESUME LOADING JOB](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/managing-loading-job#_resume_loading_job).
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_47)Parameters:
Name | Required | Description  
---|---|---  
`jobId` | yes | ID of the loading job  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_47)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X GET 'http://localhost:14240/gsql/v1/loading-jobs/resume/jobId1'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error": false,"message":"Successfully resumed loading job(s): [jobId1]."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_data_source)Data source
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_a_data_source)get a data source
`GET /gsql/v1/data-sources/{dsName}`
Get a data source.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_48)Parameters:
None
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_48)Example: 

Sample Request
    
```
curl -X GET "http://localhost:14240/gsql/v1/data-sources/k1"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":{"name":"k1","type":"KAFKA","content":{"broker":"kafka-0.tigergraph.com","kafka_config":{"security.protocol":"SSL"}}}}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_all_data_sources)get all data sources
`GET /gsql/v1/data-sources`
Get all data sources.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_49)Parameters:
None
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_49)Example: 

Sample Request
    
```
curl -X GET "http://localhost:14240/gsql/v1/data-sources"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":[{"name":"s1","belongTo":"empty_graph","type":"S3","content":{"access.key":"AKIA6B6T6R52UU7XJ2NL","secret.key":"","type":"s3"},"isLocal":true},{"name":"s2","belongTo":"person_movie","type":"S3","content":{"access.key":"AKIA6B6T6R52UU7XJ2NL","secret.key":"","type":"s3"},"isLocal":true},{"name":"k1","type":"KAFKA","content":{"broker":"kafka-0.tigergraph.com","kafka_config":{"security.protocol":"SSL"}},"isLocal":false}]}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_update_a_data_source)update a data source
`PUT /gsql/v1/data-sources`
Update a data source .
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_50)Parameters:
Name | Required | Description  
---|---|---  
`graph` | no | the graph whose data source to update. If not provided, means to update a global data source.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_50)Example: 

Sample Request
    
```
curl -X PUT 'Content-type: application/json' "http://localhost:14240/gsql/v1/data-sources/s5?graph=financialGraph" -d '{"name":"s5","config":{"type":"s3","access.key":"AKIA6B6T6R52UU7XJ2NL","secret.key":""}}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Data source s5 is created"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_data_source)create data source
`POST /gsql/v1/data-sources`
Create a data source.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_51)Parameters:
Name | Required | Description  
---|---|---  
`graph` | no | the graph whose data source to create. If not provided, means to create a global data source.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_51)Example: 

Sample Request
    
```
curl -X POST 'Content-type: application/json' "http://localhost:14240/gsql/v1/data-sources?graph=financialGraph" -d '{"name":"s4","config":{"type":"s3","access.key":"AKIA6B6T6R52UU7XJ2NL","secret.key":""}}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Data source s4 is created"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_one_data_source)drop one data source
`DELETE /gsql/v1/data-sources/{dsName}`
Drop one data source.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_52)Parameters:
Name | Required | Description  
---|---|---  
`graph` | no | the graph whose data source to delete. If not provided, means to delete a global data source.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_52)Example: 

Sample Request
    
```
curl -X DELETE 'Content-type: application/json' "http://localhost:14240/gsql/v1/data-sources/k1?graph=financialGraph" -d '{"error":false,"message":"Data source k1 is dropped."}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Data source k1 is dropped."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_grant_one_data_source)grant one data source
`POST /gsql/v1/data-sources/grant`
Grant one data source.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_53)Parameters:
None
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_53)Example: 

Sample Request
    
```
curl -X POST 'Content-type: application/json' "http://localhost:14240/gsql/v1/data-sources/grant" -d '{"graphs":["empty_graph","person_movie"],"datasource":"k1"}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully grant datasource k1 to the graph(s) [empty_graph, person_movie]"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_revoke_datasource)revoke datasource
`POST /gsql/v1/data-sources/revoke`
Revoke data source.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_54)Parameters:
None
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_54)Example: 

Sample Request
    
```
curl -X POST 'Content-type: text/plain' "http://localhost:14240/gsql/v1/data-sources/revoke" -d '{"graphs":["empty_graph","person_movie"],"datasource":"k1"}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully revoke datasource k1 from graph(s) [empty_graph, person_movie]"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_all_data_source)drop all data source
`DELETE /gsql/v1/data-sources/dropAll`
Drop all data source.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_55)Parameters:
Name | Required | Description  
---|---|---  
`graph` | no | If given, will delete all the data sources used by this graph. otherwise will delete all the global data sources.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_55)Example: 

Sample Request
    
```
curl -X DELETE 'Content-type: text/plain' "http://localhost:14240/gsql/v1/data-sources/dropAll"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"All data sources is dropped successfully."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_the_sample_data_of_s3_file_uris_or_local_files)get the sample data of S3 file.uris or local files
`POST /gsql/v1/sample-data`
Get the sample data of S3 file.uris or local files.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_56)Parameters:
None
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_56)Example: 

Sample Request
    
```
curl -X POST 'Content-type: application/json' "http://localhost:14240/gsql/v1/sample-data" -d '
 {
 "graphName": "ldbc_snb",
 "dataSource": "adsafsfsfsfds",
 "type": "s3",
 "path": "s3a://gsql-sample-data/test-json/test.json",
 "dataFormat": "json",
 "parsing": {
  "fileFormat": "none",
  "eol": "\\n"
 },
 "filling": "N/A",
 "size": 10
}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{
  "error": false,
  "message": "",
  "results": {
    "data": [
      {
        "age": 40,
        "gender": "male",
        "name": "Tom",
        "state": "ca"
      },
      {
        "age": 34,
        "gender": "male",
        "name": "Dan",
        "state": "ny"
      },
      {
        "age": 25,
        "gender": "female",
        "name": "Jenny",
        "state": "tx"
      },
      [
        {
          "age": 28,
          "gender": "male",
          "name": "Kevin",
          "state": "az"
        },
        {
          "age": 22,
          "gender": "female",
          "name": "Amily",
          "state": "ca"
        },
        {
          "age": 20,
          "gender": "female",
          "name": "Nancy",
          "state": "ky"
        }
      ],
      {
        "age": 26,
        "gender": "male",
        "name": "Jack",
        "state": "fl"
      },
      {
        "age": 8,
        "gender": "male",
        "name": "a",
        "state": "OR"
      },
      {
        "age": 57,
        "gender": "male",
        "name": "aa",
        "state": "MA"
      },
      {
        "age": 25,
        "gender": "male",
        "name": "aaa",
        "state": "MI"
      },
      {
        "age": 71,
        "gender": "female",
        "name": "ab",
        "state": "WY"
      },
      {
        "age": 71,
        "gender": "female",
        "name": "abandoned",
        "state": "KS"
      }
    ],
    "header": [],
    "json": true
  }
}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_all_buckets_of_given_s3_data_source)get all buckets of given S3 data source
`GET /gsql/v1/list-buckets/{s3Name}`
Get all buckets of given S3 data source.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_57)Parameters:
None
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_57)Example: 

Sample Request
    
```
curl -X GET 'Content-type: text/plain' "http://localhost:14240/gsql/v1/list-buckets/abcd"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
"error":false,"message":"","results":["acxiom2019","antifraudtg","aws-cloudtrail-logs-966275272565-4bde22f6","aws-glue-assets-966275272565-us-east-1","aws-logs-966275272565-us-east-1","bofa-louvain","ces-bucket-2","ces-neptune-bucket","ces-new-bucket","cf-templates-58ygac5qoly7-us-east-1","cloud-gbar-test","config-bucket-966275272565","databricks-workspace-stack-aa423-lambdazipsbucket-xjxhu6ikq892","databricks-workspace-stack-f31e4-bucket","databricks-workspace-stack-f31e4-lambdazipsbucket-ucd8ilhr3buv","databricks-workspace-stack-lambdazipsbucket-1qcpzmo9f4qzv","databricks-workspace-stack-lambdazipsbucket-1tycaofagn975","db-0cb8f9da9d4e67f9345947c4c54a5c3e-s3-root-bucket","db-81dc2edb4436079cea7c8c522f2ca24c-s3-root-bucket","db-ed2852b62420a6b838035944365a583a-s3-root-bucket","docker-image-store","docker-registry-backup","faerskit","faq.graphtiger.com","fareshealthcare","files.graphtiger.com","finfraud-demo-files","gbar-test","graphsql","graphsql-ctrip","graphsql-download","graphsql-elb-log","graphsql-eric-elb-log","graphsql-s3download","graphsql-test","graphsql-testdrive","graphsql-web","graphsql-xyz","graphsql-yeepay","graphstudio-customerportal","graphstudio-s3-e2e-test","graphstudio-sample-data-e2e-test","gsql-sample-data","kafka-connector-experiment","ldbc1","like-elb-test","litong","loading-test","merklescience","movie-rec-demo","pmitigergraph","presalesdocs","presalestg","racsftp","release-download-access-log","release-package-stats","release.graphtiger.com","renmaitong","rhfraud1","rik-bucket1","robb-tg-finfraud","robb-tgload-data","s3-import-test","s3-loading-test","se.training.deepdive","stevefuller-db","tango-test","test-gbar","test-graphstudio-bucket","test-s3import-el","test-website.graphtiger.com","tg-app-team","tg-isgs","tg-it-resource","tigergraph-aws-usage","tigergraph-benchmark-dataset","tigergraph-build-artifacts","tigergraph-cloudphysics","tigergraph-customer-support","tigergraph-development-artifects","tigergraph-download-hk","tigergraph-engineering-development-packages","tigergraph-fs-data","tigergraph-gle-prebuild","tigergraph-gui-prebuild-package","tigergraph-kafka-prebuild-package","tigergraph-mcafee-dlp","tigergraph-misc","tigergraph-release-download","tigergraph-release-prebuild","tigergraph-release-replica","tigergraph-temporary-files","tigergraph-test-dataset","tigergraph-testdrive-testdata","tigergraph-training","traininggsql","twitter-graph-benchmark","urbana-docker-ws","vladsynthea","xandrlog"]}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_all_files_and_directories_under_given_s3_bucket_path)get all files and directories under given S3 bucket path
`GET /gsql/v1/list-files/{s3Name}`
Get all files and directories under given S3 bucket path.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_58)Parameters:
Name | Required | Description  
---|---|---  
`path` | no | Uri of the data source. If not provide, list files under `/`  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_58)Example: 

Sample Request
    
```
curl -X GET 'Content-type: text/plain' "http://localhost:14240/gsql/v1/list-files/fl2323?path=s3a://import-test"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"results":{"folders":["test-folder"],"files":["chinese.csv","movies.csv","ratings.csv","ratings.tar","ratings.tar.gz","ratings.zip","中文®初めまして.csv"]}}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_query)Query
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_install_queries)install queries
`GET /gsql/v1/queries/install`
This api is used for installing queries
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_59)Parameters:
Name | Required | Description  
---|---|---  
`graph` | yes | which graph to install queries  
`queries` | yes | query names(join with `,` separated); value `*` or `all` mean all the queries.  
`flag` | no | Possible values: `-single`: Install the query in single gpr mode. `-force`: Force the installation of the query. `-legacy`: Install the query in UDF mode. `-debug`: Present results contains debug info. `-cost`: Present results contains performance consumption. `-single` and `-legacy` cannot be used together. The other options can be combined.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_59)Example: 

Sample Request
    
```
curl -X GET -H "Content-type: text/plain" "http://localhost:14240/gsql/v1/queries/install?graph=financialGraph1&queries=q1,q2&flag=-single"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{
"requestId": ": "121212121331",
"message": "Successfully submitted request",
"startTime": "2024-07-07T23:17:06.831474Z"
}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_check_query_install_status)check query install status
`GET /gsql/v1/queries/install/{requestId}`
This api is used for checking query install status
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_60)Example: 

Sample Request
    
```
curl -X GET -H "Content-type: text/plain" "http://localhost:14240/gsql/v1/queries/install/121212121331"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{
"error":false,
"message":"Request 121212121331 is running",
"requestId" : "121212121331",
"startTime": "2024-07-07T23:17:06.831474Z"
}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_list_query_names)list query names
`GET /gsql/v1/queries`
Get all query names of a graph.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_61)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X GET 'http://localhost:14240/gsql/v1/quries?graph=financialGraph'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":["query1","query2"]}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_query)create query
`POST /gsql/v1/queries`
Create a query.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_60)Parameters:
Name | Required | Description  
---|---|---  
`graph` | yes | the query created under which graph  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_62)Example 

Sample Request
    
```
curl -H 'Content-Type: text/plain' -X POST 'http://localhost:14240/gsql/v1/queries?graph=financialGraph' -d 'create query q1 {...}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully created queries: [q1].\n"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_query)drop query
`DELETE /gsql/v1/queries`
Drop quries.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_61)Parameters:
Name | Required | Description  
---|---|---  
`query` | yes | the queries to be dropped  
`graph` | yes | the queries dropped under which graph  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_63)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X DELETE 'http://localhost:14240/gsql/v1/queries?query=q1&graph=financialGraph'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"failedToDrop":[],"dropped":["q1"],"error":false,"message":""}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_query_content)get query content
`GET /gsql/v1/queries/{queryName}`
This endpoint is to get the content of a query by its name. Please note that calling this endpoint needs to set 'Content-Type: application/json' in header.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_62)Parameters:
Name | Required | Description  
---|---|---  
`queryName` | yes | the content of which query  
`graph` | yes | the query under which graph  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_64)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X GET 'http://localhost:14240/gsql/v1/queries/q1?graph=financialGraph
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"queryContent":"CREATE QUERY q1() { print 1;}","name":"test","syntax":"GSQL v2","error":false,"message":"","status":"VALID"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_run_query)run query
`POST /gsql/v1/queries/{queryName}`
The endpoint is used to run a query by its name.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_endpoint_parameters)Endpoint Parameters:
Name | Required | Description  
---|---|---  
`queryName` | yes | the query to run  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_format_for_parameters_of_query_being_run)Format for Parameters of Query Being Run
To pass the input parameter values to the query being run, include a JSON name-value pair in the payload (body) of the endpoint with the name `"parameters"`.
The value of `"parameters"` is a JSON object containing a name-value pair for each parameter.
Table 1. Format for query parameter values Value Type | Value Format | Example of Name:Value Pair  
---|---|---  
Primitive (e.g., string, numeric, Boolean) | _value_ | `"age": 25`  
Vertex, type specified in query definition | _vertex_id_ | `"v_source": "v34261"`  
Vertex, type not specified in query definition | [_vertex_id_ , _vertex_type_] | `"vset_target": ["v5933", "Person"]`  
If the parameter type is a set, list, then use JSON array syntax `[item1, item2, …​, itemN]` for the parameter value, where each item follows the rules in the table.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_65)Example
Sample Query:
```
CREATE QUERY paramEx(STRING name, INT age, SET<VERTEX> neighbors)
{ PRINT name, age, neighbors; }
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Request
    
```
curl -H 'Content-Type: application/json' -X POST 'http://localhost:14240/gsql/v1/queries/paramEx?graph=financialGraph
-d '{"diagnose":false,"denseMode":false,"allvertex":false,"asyncRun":false,
"parameters":{"name":"Fred", "age":35,
"neighbors":[["Mr. McFeely","Person"],["Daniel Tiger","Puppet"]]}}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":{"error":false,"message":"","version":{"schema":1,"edition":"enterprise","api":"v2"},"results":
["name":"Fred", "age":35,
"neighbors":["Mr. McFeely","Daniel Tiger"]]}}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_one_query)drop one query
`DELETE /gsql/v1/queries/{queryName}`
Drop a query by its name.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_63)Parameters:
Name | Required | Description  
---|---|---  
`queryName` | yes | the query to drop  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_66)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X DELETE 'http://localhost:14240/gsql/v1/queries/q1?graph=financialGraph
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"failedToDrop":[],"dropped":["q1"],"error":false,"message":""}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_interpret_query)interpret query
`POST /gsql/v1/queries/interpret`
Intepret query. Please note that calling this endpont need to set 'Content-Type: text/plain' in header.
For interpret query, we can declare workload queue in 2 ways:
  * In the request header
  * In the GSQL query definition


#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_64)Parameters:
Name | Required | Description  
---|---|---  
`graph` | yes | the query interpreted under which graph  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_headers)Headers:
Name | Required | Description  
---|---|---  
`workload_queue_name` | optional | the workload queue name  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_67)Example 

Sample Request
    
```
curl -H 'Content-Type: text/plain' -X POST 'localhost:14240/gsql/v1/queries/interpret?p1=hello&p1=world' -d 'INTERPRET QUERY (SET<STRING> p1) FOR GRAPH financialGraph syntax v1 { print p1; }'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","version":{"schema":1,"edition":"enterprise","api":"v2"},"results":[{"p1":["hello","world"]}]}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Request For Interpreting Anonymous Query Using Request Header
    
```
curl -X POST -H 'Workload-Queue: <workload_queue_name>' 'localhost:14240/gsql/v1/queries/interpret?p1=hello&p1=world' -d 'INTERPRET QUERY (SET<STRING> p1) FOR GRAPH financialGraph syntax v1 { print p1; }'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Request For Interpreting Anonymous Query Using GSQL Command
    
```
curl -X POST 'localhost:14240/gsql/v1/queries/interpret?p1=hello&p1=world' -d 'INTERPRET QUERY -QUEUE <workload_queue_name> (SET<STRING> p1) FOR GRAPH financialGraph syntax v1 { print p1; }'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_query_info)get query info
`GET /gsql/v1/queries/info`
Get the query’s information.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_65)Parameters:
Name | Required | Description  
---|---|---  
`graph` | yes | the query under which graph  
`query` | no | the query name  
`status` | no | the query status  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_68)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X GET 'localhost:14240/gsql/v1/queries/info?graph=financialGraph'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":[{"graphUpdate":false,"installed":true,"endpoint":{"query":{"financialGraph":{"q1":{"GET/POST":{"graphUpdate":false,"summary":"This is query entrance","readDataList":{},"alternative_endpoint":"/query/q1","graph_name":"financialGraph","needReadRole":false,"executeGranted":false,"updateDataList":{},"enabled":true,"target":"GPE","deleteDataList":{},"libudf":"libudf-financialGraph-1","payload":[{"rule":"AS_JSON"},{"rule":"AS_QUERY_STRING"}],"function":"queryDispatcher","needCurrentRoles":false,"createDataList":{},"action":"query","executorList":[],"parameters":{"query":{"default":"q1","type":"STRING"}}}}}}},"code":"create query q1(){ print 1;}","callerQueries":[],"isACLSpecified":false,"name":"q1","syntax":"GSQL v2","installing":false,"enabled":true,"isHidden":false,"status":"VALID"}]}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_query_signature)get query signature
`GET /gsql/v1/queries/signature`
Get query’s signature by its name.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_66)Parameters:
Name | Required | Description  
---|---|---  
`graph` | yes | the query under which graph  
`queryName` | no | the query name to get query signature  
`interpret` | no | default: false, false means the query in compiled mode and true means the query in interpret mode  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_69)Example 

Sample Request
    
```
curl -H 'Content-Type: text/plain' -X GET 'localhost:14240/gsql/v1/queries/signature?queryName=q1&graph=financialGraph'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"output":[{"1":"int"}],"input":[],"queryname":"q1","error":false,"message":"","version":{"schema":0,"edition":"ENTERPRISE_EDITION","api":"V2"}}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_query_semantic_check)query semantic check
`POST /gsql/v1/internal/check/query`
Perform a semantic check of a query.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_70)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X POST 'localhost:14240/gsql/v1/internal/check/query' -d ' {"code":""}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"warnings":[],"errors":[]}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_template_query)Template query
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_all_package_names)get all package names
`GET /gsql/v1/packages`
Get all package names.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_71)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X GET 'localhost:14240/gsql/v1/packages
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":["gds","gds.community"]}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_package_content)get package content
`GET /gsql/v1/package/{packageName}`
Get package by its name.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_72)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X GET 'localhost:14240/gsql/v1/packages/gds.community
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":{"fullPackageName":"gds.community","functions":[],"templateQueries":["printVertex"],"subpackageNames":[]}}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_package)create package
`POST /gsql/v1/package/{packageName}`
Create package.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_73)Example 

Sample Request
    
```
curl -H 'Content-Type: text/plain' -X POST 'localhost:14240/gsql/v1/packages/gds.commumity1
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully created package: [gds.community1]."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_package)drop package
`DELETE /gsql/v1/package/{packageName}`
Drop package by its name.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_74)Example 

Sample Request
    
```
curl -X DELETE 'localhost:14240/gsql/v1/packages/gds.commumity1
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully dropped package: [gds.community1]."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_function)create function
`POST /gsql/v1/package/function`
Create function
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_75)Example 

Sample Request
    
```
curl -H 'Content-Type: text/plain' -X POST 'localhost:14240/gsql/v1/packages/function -d 'create function gds.community.func1 {<content>}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully created function: [gds.community.func1]."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_delete_function)delete function
`DELETE /gsql/v1/package/{functionName}`
Delete function by its name.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_76)Example 

Sample Request
    
```
curl -X DELETE 'localhost:14240/gsql/v1/packages/function/gds.community.func1'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully dropped function: [gds.community.func1]."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_template_query)create template query
`POST /gsql/v1/package/template`
Create template query.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_77)Example 

Sample Request
    
```
curl -H 'Content-Type: text/plain' -X POST 'localhost:14240/gsql/v1/packages/template' -d 'create template query gds.community.templateQuery1 {<content>}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully created template query: [gds.community.templateQuery1]."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_template_query)drop template query
`DELETE /gsql/v1/package/template/{queryName}`
Drop template query.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_78)Example 

Sample Request
    
```
curl -X DELETE 'localhost:14240/gsql/v1/packages/template/gds.community.templateQuery1'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully dropped template query: [gds.community.templateQuery1]."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_import_package)import package
`POST /gsql/v1/package/import/{packageName}`
Import package.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_79)Example 

Sample Request
    
```
curl -X POST 'localhost:14240/gsql/v1/packages/import/pkg'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully import package pkg."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_call_template_query)call template query
`POST /gsql/v1/library/{functionName}`
Call template query.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_67)Parameters:
Name | Required | Description  
---|---|---  
`graph` | yes | the function under which graph  
`functionName` | yes | the function name to call  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_80)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X POST 'localhost:14240/gsql/v1/library/gds_community_printVertex_0000000000?graph=financialGraph' -d '{parameters: {"vertex": ""}}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"generatedQueryName":"gds_community_printVertex_0000000000","error":false,"message":"","results":{"error":false,"message":"","version":{"schema":1,"edition":"enterprise","api":"v2"},"results":[{"a":"3"}]}}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_template_query_info)get template query info
`GET /gsql/v1/library/{functionName}`
Get template query’s information.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_68)Parameters:
Name | Required | Description  
---|---|---  
`functionName` | yes | the function name of the tempalte query  
`isRegularExpression` | no | deafult: false, true means using the regex pattern to match function name  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_81)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X GET 'localhost:14240/gsql/v1/library/printVertex'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":[{"query":"CREATE template QUERY gds.community.printVertex(vertex a) SYNTAX V1 {\n print a;\n}","name":"printVertex","params":{"a":{"id_type":"$a.type","type":"STRING","is_id":"true","min_count":0},"a.type":{"type":"STRING","min_count":0}}}]}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_database_utilities)Database Utilities
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_generic_endpoint_to_execute_any_gsql_command)generic endpoint to execute any GSQL command
`POST /gsql/v1/statements`
Execute any GSQL command asynchronously or synchronously.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_69)Parameters:
Name | Required | Description  
---|---|---  
`async` | no | default: false; run the request asynchronously if true, otherwise run the request synchronously.  
`timeout` | no | default: 0; the request will be aborted if not finished in timeout seconds. A value of 0 means the request will never time out.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_82)Example: 

Sample Request
    
```
curl -X POST -H "content-type: text/plain" "http://localhost:14240/gsql/v1/statements" -d 'ls'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
---- Global vertices, edges, and all graphs
Vertex Types:
Edge Types:
Graphs:
Jobs:

JSON API version: v2
Syntax version: v2
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_check_status_of_asynchronous_request_with_requestid)check status of asynchronous request with requestId
`GET /gsql/v1/statements/{requestId}`
Check status of asynchronous request with requestId.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_70)Parameters:
None
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_83)Example: 

Sample Request
    
```
curl -X GET -H "content-type: application/json" "http://localhost:14240/gsql/v1/statements/00000000006.317280417"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{
"endTime":"2024-08-08T13:16:10.038174Z",
"error":false,
"message":"Request 00000000006.317280417 is finished with status SUCCESS",
"results":"---- Global vertices, edges, and all graphs\nVertex Types: \nEdge Types: \n\n\nGraphs: \nJobs: \n\n\n\n\nJSON API version: v2 \nSyntax version: v2\n"
}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_cancel_an_asynchronous_request_with_requestid)cancel an asynchronous request with requestId
`PUT /gsql/v1/statements/{requestId}/cancel`
Cancel an asynchronous request with requestId.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_71)Parameters:
None
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_84)Example: 

Sample Request
    
```
curl -X PUT -H "content-type: application/json" "http://localhost:14240/gsql/v1/statements/00000000006.317280417/cancel"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{
"error":false,
"message":"Successfully aborted request 00000000006.317280417",
}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_recover_gdict_catalog)recover gdict catalog
`POST /gsql/v1/schema/recover`
Recover catalog.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_72)Parameters:
None
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_85)Example: 

Sample Request
    
```
curl -X POST -H "content-type: text/plain" "http://localhost:14240/gsql/v1/schema/recover"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Recover schema succeed!"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_validate_graph_schema)validate graph schema
`POST /gsql/v1/schema/check`
Check that a schema is valid.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_73)Parameters:
None
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_86)Example: 

Sample Request
    
```
curl -X POST -H "content-type: text/plain" "http://localhost:14240/gsql/v1/schema/check"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Schema Check succeeded."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_clear_graph_store)clear graph store
`GET /gsql/v1/clear-store`
This endpoint permanently deletes all the data out of the graph store (database), for all graphs. It does not delete the database schema, nor does it delete queries or loading jobs. It is equivalent to the GSQL command [CLEAR GRAPH STORE](https://docs.tigergraph.com/gsql-ref/4.1/ddl-and-loading/running-a-loading-job#_clear_graph_store).
This operation is not reversible. The deleted data cannot be recovered.  
---  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_87)Example: 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X GET 'http://localhost:14240/gsql/v1/clear-store'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully cleared graph store."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_gsql_version)get gsql version
`GET /gsql/v1/version`
This endpoint used for get the gsql version infomation.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_74)Parameters:
Name | Required | Description  
---|---|---  
`verbose` | no | `bool` type, `true` will print detail info.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_88)Example: 

Sample Request
    
```
curl -H 'Content-Type: text/plain' -X GET 'http://localhost:14240/gsql/v1/version?verbose=true'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
GSQL version: GLE-7162
GSQL commit number: 3f46585895039eb41a460e87e6b8f15eef224800
GSQL commit date: 2024-07-26 08:56:11 +0800
Copyright (c) 2014-2024 TigerGraph. All rights reserved.
This product is protected by U.S. and international copyright and intellectual property laws.
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_all)drop all
`GET /gsql/v1/drop-all`
Drop all.
This operation is not reversible. The deleted data cannot be recovered.  
---  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_89)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X GET 'localhost:14240/gsql/v1/drop-all'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully dropped all."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_graph_export)graph export
`POST /gsql/v1/db-export`
Export database.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_90)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X POST 'localhost:14240/gsql/v1/db-export' -d '{"path":"pass","graphNames":["*"],"schema":false,"template":false,"data":false,"users":false,"password":"password","separator":"\u001d","eol":"\u001c"}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully exported database."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_graph_import)graph import
`POST /gsql/v1/db-import`
Import database.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_91)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X POST 'localhost:14240/gsql/v1/db-import' -d '{"path":"pass","graphNames":["*"],"keepUsers":false,"password":"password"}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully imported database."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_security)Security
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_new_jwt_token)create new JWT token
`POST /gsql/v1/tokens`
Create a new JWT token.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_payload)Payload:
Name | Required | Description  
---|---|---  
`secret` | no | the secret denotes the user  
`graph` | no | the graph the token created for  
`lifetime` | no | default: one week, the duration time of the token  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_92)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X POST 'localhost:14240/gsql/v1/tokens' -d "{\"secret\": \"j2qho3smncbk4g5cg4airige8up5bqn2\"}"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"expiration":"Fri Dec 20 09:07:39 UTC 2024","error":false,"message":"Generate new JWT token successfully.","token":"eyJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ0aWdlcmdyYXBoIiwiaWF0IjoxNzM0MDgwODU0LCJleHAiOjE3MzQ2ODU2NTksImlzcyI6IlRpZ2VyR3JhcGgifQ.1Qrgj2I90WL4Xo8cMaXrmyOQmqhgNz1rES0hJu7H3mg"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_jwt_tokens)drop JWT tokens
`DELETE /gsql/v1/tokens`
Drop specific a list of tokens.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_75)Parameters:
Name | Required | Description  
---|---|---  
`clear` | no | default: false, true means clear out the current block list.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_93)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X DELETE 'localhost:14240/gsql/v1/tokens' -d '{"tokens": "eyJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ0aWdlcmdyYXBoIiwiaWF0IjoxNzM0MDgwODU0LCJleHAiOjE3MzQ2ODU2NTksImlzcyI6IlRpZ2VyR3JhcGgifQ.1Qrgj2I90WL4Xo8cMaXrmyOQmqhgNz1rES0hJu7H3mg"}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error": false, "message": "Successfully dropped the specified JWT tokens"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_check_jwt_token)check JWT token
`POST /gsql/v1/tokens/check`
Check JWT token is valid or not.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_94)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X POST 'localhost:14240/gsql/v1/tokens/check' -d '{"token": "eyJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ0aWdlcmdyYXBoIiwiaWF0IjoxNzM0MDgwODU0LCJleHAiOjE3MzQ2ODU2NTksImlzcyI6IlRpZ2VyR3JhcGgifQ.1Qrgj2I90WL4Xo8cMaXrmyOQmqhgNz1rES0hJu7H3mg"}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"The token eyJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ0aWdlcmdyYXBoIiwiaWF0IjoxNzM0MDgwODU0LCJleHAiOjE3MzQ2ODU2NTksImlzcyI6IlRpZ2VyR3JhcGgifQ.1Qrgj2I90WL4Xo8cMaXrmyOQmqhgNz1rES0hJu7H3mg verification succeed."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_secret)create secret
`POST /gsql/v1/secrets`
Create a secret.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_76)Parameters:
Name | Required | Description  
---|---|---  
`userName` | no | the user the secret created for. The default user is the logged-in user if not specified.  
`alias` | no | the alias of the secret created.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_95)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X POST 'localhost:14240/gsql/v1/secrets?alias=s1'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":{"alias":"s1","value":"59ccqdlqmkfcqjl99u2jv4qt2telmeoj"}}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_show_secrets)show secrets
`GET /gsql/v1/secrets`
Show secrets for the user.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_77)Parameters:
Name | Required | Description  
---|---|---  
`userName` | no | the user who wants to show the secrets. The default user is the logged-in user if not specified.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_96)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X GET 'localhost:14240/gsql/v1/secrets'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":{"alias":"s1","value":"59ccqdlqmkfcqjl99u2jv4qt2telmeoj"}}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_delete_secrets)delete secrets
`DELETE /gsql/v1/secrets`
Delete the secrets of the user.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_78)Parameters:
Name | Required | Description  
---|---|---  
`userName` | no | the user who wants to delete the secrets. The default user is the logged-in user if not specified.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_97)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X DELETE 'localhost:14240/gsql/v1/secrets' -d '{"secrets":[$secret1,$secret2]}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully removed the secrets for user tigergraph."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_secret_by_alias)get secret by alias
`GET /gsql/v1/secrets/{alias}`
Get the secrets by its alias name.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_79)Parameters:
Name | Required | Description  
---|---|---  
`userName` | no | the user who wants to get the secret. The default user is the logged-in user if not specified.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_98)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X GET 'localhost:14240/gsql/v1/secrets/s2'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":{"alias":"s2","value":"g2ea27q79tes6nsark3k3ecp718rp4ej"}}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_secret_by_alias)drop secret by alias
`DELETE /gsql/v1/secrets/{alias}`
Delete the secret of the user by its alias name.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_80)Parameters:
Name | Required | Description  
---|---|---  
`userName` | no | the user who wants to delete the secret. The default user is the logged-in user if not specified.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_99)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X DELETE 'localhost:14240/gsql/v1/secrets/s2'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully removed the secrets for user tigergraph."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_retrieve_a_group_by_id_using_gsql_format)retrieve a group by id using gsql format
`GET /gsql/v1/groups/{id}`
Retrieve a group by id response scim format or gsql format JSON.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_81)Parameters:
None
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_100)Example: 

Sample Request
    
```
curl -X GET "http://localhost:14240/gsql/v1/groups/g1"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":{"lastSuccessLogin":"Thu Aug 08 16:31:56 HKT 2024","privileges":{},"nextValidLogin":"Thu Aug 08 16:31:56 HKT 2024","roles":{},"failedAttempts":0,"members":[],"name":"g1","rule":"group=th-department","disabled":false,"isSuperUser":false,"showAlterPasswordWarning":false,"secrets":[]}}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_retrieve_groups_using_gsql_format)retrieve groups using gsql format
`GET /gsql/v1/groups`
Retrieve groups response gsql format JSON.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_82)Parameters:
Name | Required | Description  
---|---|---  
`graph` | no | If the graph is not specified and the current user has global READ_PROXYGROUP privilege, they can see all proxy groups. Otherwise, no proxy group information can be accessed. If the graph is specified and the current user has local READ_PROXYGROUP privilege for this graph, they can only view the proxy groups on this specific graph.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_101)Example: 

Sample Request
    
```
curl -X GET "Content-type: text/plain" "http://localhost:14240/gsql/v1/groups"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"results":[{"lastSuccessLogin":"Tue Jul 02 17:07:50 HKT 2024","privileges":{},"nextValidLogin":"Tue Jul 02 17:07:50 HKT 2024","roles":{},"failedAttempts":0,"members":[],"name":"g1","rule":"group=tech-department","disabled":false,"isSuperUser":false,"showAlterPasswordWarning":false,"secrets":[]},{"lastSuccessLogin":"Tue Jul 02 17:07:50 HKT 2024","privileges":{},"nextValidLogin":"Tue Jul 02 17:07:50 HKT 2024","roles":{},"failedAttempts":0,"members":[],"name":"g2","rule":"group=tech-department","disabled":false,"isSuperUser":false,"showAlterPasswordWarning":false,"secrets":[]}]}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_a_group_using_gsql_format)create a group using gsql format
`POST /gsql/v1/groups`
Create a group using gsql format.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_83)Parameters:
None
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_102)Example: 

Sample Request
    
```
curl -X POST "Content-type: application/json" "http://localhost:14240/gsql/v1/groups" -d '{"groupName":"g4","proxyRule":"group=tech-department"}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully created group g4","results":{"lastSuccessLogin":"Tue Jul 02 17:32:40 HKT 2024","privileges":{},"nextValidLogin":"Tue Jul 02 17:32:40 HKT 2024","roles":{},"failedAttempts":0,"members":[],"name":"g4","rule":"group=tech-department","disabled":false,"isSuperUser":false,"showAlterPasswordWarning":false,"secrets":[]}}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_update_a_group_using_gsql_format)update a group using gsql format
`PUT /gsql/v1/groups`
Update a group.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_84)Parameters:
None
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_103)Example: 

Sample Request
    
```
curl -X PUT "Content-type: application/json" "http://localhost:14240/gsql/v1/groups" -d '{"name": "g1", "rule": ""group=tech-department""}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error": true, "message": "Successfully change the proxy rule for group g1"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_one_group_by_name_using_gsql_format)drop one group by name using gsql format
`DELETE /gsql/v1/groups/{id}`
Drop one group by name.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_85)Parameters:
None
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_104)Example: 

Sample Request
    
```
curl -X DELETE "Content-type: application/json" "http://localhost:14240/gsql/v1/groups/g1"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully dropped group g1"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_groups_using_gsql_format)drop groups using gsql format
`POST /gsql/v1/groups`
Drop groups.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_86)Parameters:
Name | Required | Description  
---|---|---  
`action` | no | The default value is `create`. Possible values are `create` and `delete`. `Delete` indicates dropping groups, while `create` indicates creating groups.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_105)Example: 

Sample Request
    
```
curl -X POST "Content-type: application/json" "http://localhost:14240/gsql/v1/groups?action=delete" -d '{"groupNames":["g1"]}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully dropped groups: [g1]"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_retrieve_a_user_by_id_using_gsql_format)retrieve a user by id using gsql format
`GET /gsql/v1/users/{id}`
Retrieve a user by id respond gsql format.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_87)Parameters:
None
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_106)Example: 

Sample Request
    
```
curl -X GET "http://localhost:14240/gsql/v1/users/u1"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":{"lastSuccessLogin":"Thu Aug 08 16:51:23 HKT 2024","privileges":{"recommend":{"privileges":[]}},"nextValidLogin":"Thu Aug 08 16:51:23 HKT 2024","roles":{"recommend":["r1"]},"failedAttempts":0,"name":"u1","disabled":false,"isSuperUser":false,"showAlterPasswordWarning":false,"secrets":[]}}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_update_an_user_using_gsql_format)update an user using gsql format
`PUT /gsql/v1/users`
Update a user.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_88)Parameters:
None
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_107)Example: 

Sample Request
    
```
curl -X PUT -H "Content-type: application/json" "http://localhost:14240/gsql/v1/users" -d '{"name": "tigergraph", "password": "123"}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error": false, "message": "Successfully updated user tigergraph"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_users_for_gsql_format)drop users for gsql format
`POST /gsql/v1/users`
Drop users.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_89)Parameters:
Name | Required | Description  
---|---|---  
`action` | no | default: `create`. Possible values: `create`, `delete`. `delete` indicates to drop users; `create` indicates to create users. Here set the value `delete`.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_108)Example: 

Sample Request
    
```
curl -X POST -H "Content-type: application/json" "http://localhost:14240/gsql/v1/users?action=delete" -d ' {"userNames":["u1"]}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully dropped users: [u1]"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_a_user_using_gsql_format)drop a user using gsql format
`DELETE /gsql/v1/users/{id}`
Drop a user.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_90)Parameters:
None
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_109)Example: 

Sample Request
    
```
curl -X DELETE -H "Content-type: application/json" "http://localhost:14240/gsql/v1/users/u1"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully dropped user u1"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_a_user_using_gsql_format)create a user using gsql format
`POST /gsql/v1/users`
Create a user using gsql format.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_91)Parameters:
None
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_110)Example: 

Sample Request
    
```
curl -X POST -H "Content-type: application/json" "http://localhost:14240/gsql/v1/users" -d ' {"password":"tiger123","username":"user2"}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully created user user2"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_retrieve_users_using_gsql_format)retrieve users using gsql format
`GET /gsql/v1/users`
Retrieve users response gsql format JSON.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_92)Parameters:
Name | Required | Description  
---|---|---  
`graph` | no | If the graph is not provided and the current user has global READ_USER privilege, they can view all users. Otherwise, no user information can be accessed. If the graph is provided, users with global READ_USER privilege can view all users. If the current user holds local READ_USER privilege for this graph, they can only see users with access to this specific graph. Otherwise, they can only view their own information if they have access to the graph.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_111)Example: 

Sample Request
    
```
curl -X GET -H "Content-type: application/json" "http://localhost:14240/gsql/v1/users"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"results":[{"lastSuccessLogin":"Wed Jul 03 15:26:33 HKT 2024","privileges":{"1":{"privileges":["READ_SCHEMA","WRITE_SCHEMA","READ_LOADINGJOB","EXECUTE_LOADINGJOB","WRITE_LOADINGJOB","CREATE_QUERY","WRITE_DATASOURCE","READ_ROLE","WRITE_ROLE","READ_USER","WRITE_USER","READ_PROXYGROUP","WRITE_PROXYGROUP","READ_FILE","WRITE_FILE","DROP_GRAPH","EXPORT_GRAPH","CLEAR_GRAPHSTORE","DROP_ALL","READ_DATA","CREATE_DATA","UPDATE_DATA","DELETE_DATA","APP_ACCESS_DATA","READ_POLICY","WRITE_POLICY","USE_FUNCTION","WRITE_FUNCTION","READ_WORKLOAD_QUEUE","WRITE_WORKLOAD_QUEUE"]},"recommend":{"privileges":[]}},"nextValidLogin":"Wed Jul 03 15:26:33 HKT 2024","roles":{"1":["superuser"],"recommend":["superuser"]},"failedAttempts":0,"name":"tigergraph","disabled":false,"isSuperUser":true,"showAlterPasswordWarning":false,"secrets":[]},{"lastSuccessLogin":"Wed Jul 03 15:26:33 HKT 2024","privileges":{"recommend":{"privileges":[]}},"nextValidLogin":"Wed Jul 03 15:26:33 HKT 2024","roles":{"recommend":["r1"]},"failedAttempts":0,"name":"u1","disabled":false,"isSuperUser":false,"showAlterPasswordWarning":false,"secrets":[]}]}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_show_all_privileges)show all privileges
`GET /gsql/v1/privileges`
List all built-in privileges.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_112)Example: 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X GET "http://localhost:14240/gsql/v1/privileges"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":[{"privilegeType":"GRAPH","privilege":"READ_SCHEMA"},{"privilegeType":"GRAPH","privilege":"WRITE_SCHEMA"},{"privilegeType":"GRAPH","privilege":"READ_LOADINGJOB"},{"privilegeType":"GRAPH","privilege":"EXECUTE_LOADINGJOB"},{"privilegeType":"GRAPH","privilege":"WRITE_LOADINGJOB"},{"privilegeType":"QUERY","privilege":"READ_QUERY"},{"privilegeType":"GRAPH","privilege":"CREATE_QUERY"},{"privilegeType":"QUERY","privilege":"UPDATE_QUERY"},{"privilegeType":"QUERY","privilege":"DROP_QUERY"},{"privilegeType":"QUERY","privilege":"INSTALL_QUERY"},{"privilegeType":"QUERY","privilege":"EXECUTE_QUERY"},{"privilegeType":"QUERY","privilege":"OWNER"},{"privilegeType":"GRAPH","privilege":"WRITE_DATASOURCE"},{"privilegeType":"GRAPH","privilege":"READ_ROLE"},{"privilegeType":"GRAPH","privilege":"WRITE_ROLE"},{"privilegeType":"GRAPH","privilege":"READ_USER"},{"privilegeType":"GLOBAL","privilege":"WRITE_USER"},{"privilegeType":"GRAPH","privilege":"READ_PROXYGROUP"},{"privilegeType":"GLOBAL","privilege":"WRITE_PROXYGROUP"},{"privilegeType":"GLOBAL","privilege":"READ_FILE"},{"privilegeType":"GLOBAL","privilege":"WRITE_FILE"},{"privilegeType":"GLOBAL","privilege":"DROP_GRAPH"},{"privilegeType":"GLOBAL","privilege":"EXPORT_GRAPH"},{"privilegeType":"GLOBAL","privilege":"CLEAR_GRAPHSTORE"},{"privilegeType":"GLOBAL","privilege":"DROP_ALL"},{"privilegeType":"GRAPH","privilege":"READ_DATA"},{"privilegeType":"GRAPH","privilege":"CREATE_DATA"},{"privilegeType":"GRAPH","privilege":"UPDATE_DATA"},{"privilegeType":"GRAPH","privilege":"DELETE_DATA"},{"privilegeType":"GRAPH","privilege":"APP_ACCESS_DATA"},{"privilegeType":"GRAPH","privilege":"READ_POLICY"},{"privilegeType":"GRAPH","privilege":"WRITE_POLICY"},{"privilegeType":"PACKAGE","privilege":"USE_FUNCTION"},{"privilegeType":"PACKAGE","privilege":"WRITE_FUNCTION"},{"privilegeType":"GLOBAL","privilege":"READ_WORKLOAD_QUEUE"},{"privilegeType":"GLOBAL","privilege":"WRITE_WORKLOAD_QUEUE"}]}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_grant_privileges_to_roles)grant privilege(s) to role(s)
`POST /gsql/v1/privileges/grant`
Grant RABC privileges to specific roles.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_93)Parameters:
Name | Required | Description  
---|---|---  
`graph` | no | in which graph the privilege(s) should be granted, or grant privilege(s) on global level if the parameter is missing  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_113)Example: 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X POST "http://localhost:14240/gsql/v1/privileges/grant?graph=financialGraph" -d "{"privileges":["READ_DATA", "CREATE_DATA", "UPDATE_DATA"], "vertexName": "Account", "roles":["r1", "r2"]}"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"The privileges \"CREATE, READ, UPDATE\" are successfully granted on \"VERTEX Account\" IN GRAPH recommend to role: r2\nThe privileges \"CREATE, READ, UPDATE\" are successfully granted on \"VERTEX Account\" IN GRAPH recommend to role: r1\n","results":[{"privileges":{"1":{"privileges":[]},"recommend":{"privileges":[],"childPermissions":{"user":{"privileges":["READ_DATA","CREATE_DATA","UPDATE_DATA"]}}}},"role":"r1"},{"privileges":{"recommend":{"privileges":[],"childPermissions":{"user":{"privileges":["READ_DATA","CREATE_DATA","UPDATE_DATA"]}}}},"role":"r2"}]}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_revoke_privileges_from_roles)revoke privilege(s) from role(s)
`POST /gsql/v1/privileges/revoke`
Revoke RABC privileges from specific roles
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_94)Parameters:
Name | Required | Description  
---|---|---  
`graph` | no | in which graph the privilege(s) should be revoked, or revoke privilege(s) on global level if the parameter is missing  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_114)Example: 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X POST "http://localhost:14240/gsql/v1/privileges/revoke?graph=financialGraph" -d "{"privileges":["READ_DATA", "CREATE_DATA", "UPDATE_DATA"], "vertexName": "Account", "roles":["r1", "r2"]}"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"The privileges \"CREATE, READ, UPDATE\" are successfully revoked on \"VERTEX Account\" IN GRAPH recommend from role: r2\nThe privileges \"CREATE, READ, UPDATE\" are successfully revoked on \"VERTEX Account\" IN GRAPH recommend from role: r1\n","results":[{"privileges":{"1":{"privileges":[]}},"role":"r1"},{"privileges":{},"role":"r2"}]}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_show_all_roles)show all roles
`GET /gsql/v1/roles`
Call this endpoint to show all roles, including built-in roles and user defined roles.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_115)Example: 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X GET "http://localhost:14240/gsql/v1/roles"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":{"builtIn":{"global":["globalobserver","globaldesigner","superuser"],"local":["observer","queryreader","querywriter","designer","admin"]},"userDefinedRoles":{"1":["r1","r2","r3"],"recommend":["r4"]}}}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_roles)Create roles
`POST /gsql/v1/roles`
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_95)Parameters:
Name | Required | Description  
---|---|---  
`graph` | no | in which graph to create local roles, or create global roles if the parameter is missing  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_116)Example: 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X POST "http://localhost:14240/gsql/v1/roles?graph=financialGraph" -d "{"roles":["r1", "r2"]}"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":"Successfully created local roles on graph 'financialGraph': [r1, r2]."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_delete_roles)Delete roles
`DELETE /gsql/v1/roles`
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_96)Parameters:
Name | Required | Description  
---|---|---  
`graph` | no | in which graph to delete local roles, or delete global roles if the parameter is missing  
`roles` | yes | roles to delete  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_117)Example: 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X DELETE "http://localhost:14240/gsql/v1/roles?graph=financialGraph&role=r1,r2"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":"Successfully dropped roles: [r1, r2]."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_show_one_role)show one role
`GET /gsql/v1/roles/{roleName}`
Call this endpoint to show the info of a specific role.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_118)Example: 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X GET "http://localhost:14240/gsql/v1/roles/r1"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":{"Graph":"financialGraph","roleName":"r1","isGlobal":false,"rolePrivileges":{"financialGraph":{"privileges":["READ_DATA","CREATE_DATA"]}}}}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_delete_one_role)delete one role
`DELETE /gsql/v1/roles/{roleName}`
Call this endpoint to delete a specific role.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_119)Example: 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X DELETE "http://localhost:14240/gsql/v1/roles/r1"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":"Successfully dropped roles: [r1]."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_grant_roles_to_users)grant role(s) to user(s)
`POST /gsql/v1/roles/grant`
Grant roles to specific users
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_97)Parameters:
Name | Required | Description  
---|---|---  
`graph` | no | in which graph the role(s) should be granted, or grant role(s) on global level if the parameter is missing  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_120)Example: 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X POST 'http://localhost:14240/gsql/v1/roles/grant?graph=financialGraph' -d '{"roles":["observer", "r1"], "users":["user1", "user2"]}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":"Successfully granted roles [observer, r1] on graph 'financialGraph' to users [user1, user2]."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_revoke_roles_from_users)revoke role(s) from user(s)
`POST /gsql/v1/roles/revoke`
Revoke roles from specific users
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_98)Parameters:
Name | Required | Description  
---|---|---  
`graph` | no | in which graph the role(s) should be revoked, or revoke role(s) on global level if the parameter is missing  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_121)Example: 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X POST 'http://localhost:14240/gsql/v1/roles/revoke?graph=financialGraph' -d '{"roles":["observer", "r1"], "users":["user1", "user2"]}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":"Successfully revoked roles [observer, r1] on graph 'financialGraph' from users [user1, user2]."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_scim_apis_for_usersgroups)SCIM APIs for users/groups
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_retrieve_a_group_by_id_using_scim_format)retrieve a group by id using scim format
`GET /gsql/scim/v2/Groups/{id}`
Retrieve a group by id response scim format.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_99)Parameters:
None
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_122)Example: 

Sample Request
    
```
curl -X GET "http://localhost:14240/gsql/scim/v2/Groups/g2"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"displayName":"g2","meta":{"location":"/scim/v2/Groups/54ba8a0f-693c-4cf3-9c53-5caaa244049a","resourceType":"Group"},"members":[],"id":"54ba8a0f-693c-4cf3-9c53-5caaa244049a"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_retrieve_groups_using_scim_format)retrieve groups using scim format
`GET /gsql/scim/v2/Groups`
Retrieve groups response scim format.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_100)Parameters:
Name | Required | Description  
---|---|---  
`filter` | no | The filter format should follow this structure: `displayName op {value} op2 displayName op {value}`. Here, `op` can be one of `eq`, `ne`, `co`, `sw`, `ew`, and `op2` can be either `and` or `or`.  
`excludedAttributes` | no | Specifies attributes to be excluded. Currently supports only `members`.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_123)Example: 

Sample Request
    
```
curl -X GET -H "Content-type: text/plain" "http://localhost:14240/gsql/scim/v2/Groups?excludedAttributes=members&filter=displayName%ne%20'g2'%20and%20displayName%20sw%20'g1'"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"totalResults":1,"startIndex":1,"itemsPerPage":100,"schemas":true,"Resources":[{"displayName":"g1","meta":{"location":"/scim/v2/Groups/0570fc42-79ea-427e-aa2e-2b53a0470163","resourceType":"Group"},"id":"0570fc42-79ea-427e-aa2e-2b53a0470163"}]}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_a_group_using_scim_format)create a group using scim format
`POST /gsql/scim/v2/Groups`
Create a group using scim format.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_101)Parameters:
None
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_124)Example: 

Sample Request
    
```
curl -X POST "Content-type: application/json" "http://localhost:14240/gsql/scim/v2/Groups" -d '{"displayName":"scimG3","schemas":"[\"urn:ietf:params:scim:schemas:core:2.0:Group\"]","members":[{"display":"user3"},{"value":"user4"}]}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"displayName":"scimG3","meta":{"location":"/scim/v2/Groups/706d0ad6-2165-4190-8512-de5abfd06988","resourceType":"Group"},"members":[{"display":"user3","type":"User","value":"16c1e6cc-3b2a-4d57-9a2e-fb55a5d14804"},{"display":"user4","type":"User","value":"457b9982-d5fb-4ad6-b50a-266919bf0c16"}],"id":"706d0ad6-2165-4190-8512-de5abfd06988"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_update_a_group_using_scim_format)update a group using scim format
`PATCH /gsql/scim/v2/Groups/{id}`
Update a group.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_102)Parameters:
None
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_125)Example: 

Sample Request
    
```
curl -X PATCH "Content-type: application/json" "http://localhost:14240/gsql/scim/v2/Groups/g1" -d '
{"schemas":"[\"urn:ietf:params:scim:api:messages:2.0:PatchOp\"]","Operations":[{"op":"remove","path":"members"},{"op":"replace","path":"members","value":[{"display":"user4"}]},{"op":"add","value":[{"display":"user3"}]}]}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"displayName":"g1","meta":{"location":"/scim/v2/Groups/0b181bc8-d055-4fcb-af52-20c560324c6f","resourceType":"Group"},"members":[{"display":"user3","type":"User","value":"5cdad092-af32-435e-9865-c2ad06b9d6f8"},{"display":"user4","type":"User","value":"c14765de-ea78-422a-bd87-88f3f7d3ceda"}],"id":"0b181bc8-d055-4fcb-af52-20c560324c6f"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_one_group_by_name_using_scim_format)drop one group by name using scim format
`DELETE /gsql/scim/v2/Groups/{id}`
Drop one group by name.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_103)Parameters:
None
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_126)Example: 

Sample Request
    
```
curl -X DELETE "Content-type: application/json" "http://localhost:14240/gsql/scim/v2/Groups/g1" -d '
{"schemas":"[\"urn:ietf:params:scim:api:messages:2.0:PatchOp\"]","Operations":[{"op":"remove","path":"members"},{"op":"replace","path":"members","value":[{"display":"user4"}]},{"op":"add","value":[{"display":"user3"}]}]}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully dropped group g1"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_groups_using_scim_format)drop groups using scim format
`POST /gsql/scim/v2/Groups`
Drop groups.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_104)Parameters:
Name | Required | Description  
---|---|---  
`action` | no | The default value is `create`. Possible values are `create` and `delete`. `Delete` indicates dropping groups, while `create` indicates creating groups.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_127)Example: 

Sample Request
    
```
curl -X POST "Content-type: application/json" "http://localhost:14240/gsql/scim/v2/Groups?action=delete" -d '{"groupNames":["g1"]}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully dropped groups: [g1]"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_retrieve_a_user_by_id_using_scim_format)retrieve a user by id using scim format
`GET /gsql/scim/v2/Users/{id}`
Retrieve a user by id respond with scim format.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_105)Parameters:
None
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_128)Example: 

Sample Request
    
```
curl -X GET "http://localhost:14240/gsql/scim/v2/Users/u1"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"meta":{"location":"/scim/v2/Users/1e224fd0-54eb-43c3-84d6-455ca3b6339d","resourceType":"User"},"schemas":["urn:ietf:params:scim:schemas:core:2.0:User"],"name":{},"active":true,"id":"1e224fd0-54eb-43c3-84d6-455ca3b6339d","userName":"u1"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_update_a_user_using_scim_format)update a user using scim format
`PUT /gsql/scim/v2/Users/{id}`
Update a user.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_106)Parameters:
None
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_129)Example: 

Sample Request
    
```
curl -X PUT -H "Content-type: application/json" "http://localhost:14240/gsql/scim/v2/Users/u1" -d '{"schemas":"[\"urn:ietf:params:scim:api:messages:2.0:PatchOp\"]","Operations":[{"op":"replace","path":"password","value":"newPassword"}]}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"meta":{"location":"/scim/v2/Users/1e224fd0-54eb-43c3-84d6-455ca3b6339d","resourceType":"User"},"schemas":["urn:ietf:params:scim:schemas:core:2.0:User"],"name":{},"active":true,"id":"1e224fd0-54eb-43c3-84d6-455ca3b6339d","userName":"u1"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_users_using_scim_format)drop users using scim format
`POST /gsql/scim/v2/Users`
Drop users.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_107)Parameters:
Name | Required | Description  
---|---|---  
`action` | no | default: `create`. Possible values: `create`, `delete`. `delete` indicates to drop users; `create` indicates to create users. Here set the value `delete`.  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_130)Example: 

Sample Request
    
```
curl -X POST -H "Content-type: application/json" "http://localhost:14240/gsql/scim/v2/Users?action=delete" -d ' {"userNames":["u1"]}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully dropped users: [u1]"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_drop_a_user_using_scim_format)drop a user using scim format
`DELETE /gsql/scim/v2/Users/{id}`
Drop a user.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_108)Parameters:
None
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_131)Example: 

Sample Request
    
```
curl -X DELETE -H "Content-type: application/json" "http://localhost:14240/gsql/scim/v2/Users/u1"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully dropped user u1"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_a_user_using_scim_format)create a user using scim format
`POST /gsql/scim/v2/Users`
Create a user using scim format.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_109)Parameters:
None
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_132)Example: 

Sample Request
    
```
curl -X POST -H "Content-type: application/json" "http://localhost:14240/gsql/scim/v2/Users" -d '
{"password":"12345678","schemas":"[\"urn:ietf:params:scim:schemas:core:2.0:User\"]","name":{"familyName":"f","givenName":"g"},"externalId":"externalId123","active":false,"userName":"scimUser2"}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"meta":{"location":"/scim/v2/Users/d838c224-d1d6-4a07-b6b5-5c0aab43f0a6","resourceType":"User"},"schemas":["urn:ietf:params:scim:schemas:core:2.0:User"],"active":true,"id":"d838c224-d1d6-4a07-b6b5-5c0aab43f0a6","userName":"scimUser2"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_retrieve_users_using_scim_format)retrieve users using scim format
`GET /gsql/scim/v2/Users`
Retrieve users response scim format.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_110)Parameters:
Name | Required | Description  
---|---|---  
`excludedAttributes` | no | `names`, currently only support this value.  
`filter` | no | The format should follow this pattern: `userName op {value} op2 displayName op {value}`. Here, `op` can be one of `eq`, `ne`, `co`, `sw`, `ew`, and `op2` can be either `and` or `or`. Example: 1. userName eq "user1" 2. userName sw "u" and userName ne "u1"  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_133)Example: 

Sample Request
    
```
curl -X GET -H "Content-type: application/json" "http://localhost:14240/gsql/scim/v2/Users?filter=userName%20ne%20%22tigergraph%22%20and%20userName%20sw%20%22u%22&excludedAttributes=names"
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"totalResults":2,"startIndex":1,"itemsPerPage":100,"schemas":true,"Resources":[{"meta":{"location":"/scim/v2/Users/7a004538-8d41-4f85-b5e7-2a26358f0173","resourceType":"User"},"schemas":["urn:ietf:params:scim:schemas:core:2.0:User"],"name":{},"active":true,"id":"7a004538-8d41-4f85-b5e7-2a26358f0173","userName":"tigergraph"},{"meta":{"location":"/scim/v2/Users/0a71523d-9623-4b04-908d-395096e288f4","resourceType":"User"},"schemas":["urn:ietf:params:scim:schemas:core:2.0:User"],"name":{},"active":true,"id":"0a71523d-9623-4b04-908d-395096e288f4","userName":"u1"}]}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_statistics)Statistics
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_cardinality_statistics)get cardinality statistics
`GET /gsql/v1/stats/cardinality`
Fetch cardinality statistics.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_111)Parameters:
Name | Required | Description  
---|---|---  
`graph` | yes | Get the cardinality stats of which graph  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_134)Example: 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X GET 'http://localhost:14240/gsql/v1/stats/cardinality?graph=financialGraph'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":{"vertex_counts":[{"count":5,"type":"Account"}],"edge_counts":[{"count":5,"type":"isLocatedIn"},{"count":10,"from":"Account","to":"City","type":"isLocatedIn"}]}}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_post_cardinality_statistics)post cardinality statistics
`POST /gsql/v1/stats/cardinality`
This endpoint has to usage: 1) Fetch fresh up-to-date cardinality statistics and persist it to storage. 2) Persist user defined cardinality statistics to storage.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_1_fetch_fresh_up_to_date_cardinality_statistics_and_persist_it_to_storage)1) Fetch fresh up-to-date cardinality statistics and persist it to storage
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_112)Parameters:
Name | Required | Description  
---|---|---  
`graph` | yes | Persist the cardinality stats to which graph  
`vertex` | no | Fetch fresh up-to-date cardinality stats for specific vertex types and persist them to storage  
`edge` | no | Fetch fresh up-to-date cardinality stats for specific edge types and persist them to storage, if `vertex` is not empty, this parameter will be ignored  
`from` | no | Fetch fresh up-to-date cardinality stats for not only specific edge types but also from specific vertex, if `edge` is not empty, this parameter will be ignored, this parameter usually used together with `to`.  
`to` | no | Fetch fresh up-to-date cardinality stats for not only specific edge types but also to specific vertex, if `edge` is not empty, this parameter will be ignored, this parameter usually used together with `from`.  
##### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_135)Example: 

Sample Request 1
    
```
curl -H 'Content-Type: application/json' -X POST 'http://localhost:14240/gsql/v1/stats/cardinality?graph=financialGraph&vertex=Account'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response 1
    
```
{"error": false,"message": "successfully persisted statistics"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Request 2
    
```
curl -H 'Content-Type: application/json' -X POST 'http://localhost:14240/gsql/v1/stats/cardinality?graph=financialGraph&edge=isLocatedIn&from=Account&to=City'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response 2
    
```
{"error": false,"message": "successfully persisted statistics"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_2_persist_user_defined_cardinality_statistics_to_storage)2) Persist user defined cardinality statistics to storage.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_113)Parameters:
Name | Required | Description  
---|---|---  
`graph` | yes | Persist the cardinality stats to which graph  
##### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_136)Example: 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X POST 'http://localhost:14240/gsql/v1/stats/cardinality?graph=financialGraph' -d '{"vertex_counts":[{"type": "Account","count": 5}], "edge_counts":[{"type":"hasPhone","count":5},{"type":"isLocatedIn","from":"Account","to":"City","count":10}]}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":{"vertex_counts":[{"count":5,"type":"Account"}],"edge_counts":[{"count":5,"type":"hasPhone"},{"count":10,"from":"Account","to":"City","type":"isLocatedIn"}]}}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_delete_cardinality_statistics)delete cardinality statistics
`DELETE /gsql/v1/stats/cardinality`
Remove cardinality statistics from storage.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_114)Parameters:
Name | Required | Description  
---|---|---  
`graph` | yes | Delete the cardinality stats of indicated graph from storage  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_137)Example: 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X DELETE 'http://localhost:14240/gsql/v1/stats/cardinality?graph=financialGraph'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"successfully deleted statistics"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_histogram_statistics)get histogram statistics
`GET /gsql/v1/stats/histogram`
Fetch histogram statistics.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_138)Example: 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X GET 'http://localhost:14240/gsql/v1/stats/histogram' -d ' {"graph":"financialGraph", "edge":"isLocatedIn", "from":"Account", "to":"City", "attribute":"name", "bucket":10}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
[{"histogram": [{"rowsTotal": 104,"rowsUpper": 1,"upperBound": "2010-05-05 10:44:41"},{"rowsTotal": 12599,"rowsUpper": 1,"upperBound": "2012-06-09 21:24:20"},{"rowsTotal": 15986,"rowsUpper": 1,"upperBound": "2012-09-13 09:27:04"},{"rowsTotal": 1995,"rowsUpper": 1,"upperBound": "2010-11-14 17:07:00"},{"rowsTotal": 3570,"rowsUpper": 1,"upperBound": "2011-02-18 09:33:18"},{"rowsTotal": 4193,"rowsUpper": 1,"upperBound": "2011-05-24 21:54:24"},{"rowsTotal": 5481,"rowsUpper": 1,"upperBound": "2011-08-28 09:45:29"},{"rowsTotal": 752,"rowsUpper": 1,"upperBound": "2010-08-11 07:41:03"},{"rowsTotal": 8665,"rowsUpper": 1,"upperBound": "2012-03-06 08:31:44"},{"rowsTotal": 8880,"rowsUpper": 1,"upperBound": "2011-12-01 21:13:33"}]}]
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_post_histogram_statistics)post histogram statistics
`POST /gsql/v1/stats/histogram`
Persist new histogram statistics to storage.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_139)Example: 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X POST 'http://localhost:14240/gsql/v1/stats/histogram' -d '{"graph":"financialGraph", "edge":"isLocatedIn", "from":"Account", "to":"City", "attribute":"name"}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"0": {"rowsTotal": 151037,"rowsUpper": 90,"upperBound": 183},"1": {"rowsTotal": 0,"rowsUpper": 0,"upperBound": 399},"2": {"rowsTotal": 0,"rowsUpper": 0,"upperBound": 598},"3": {"rowsTotal": 1,"rowsUpper": 1,"upperBound": 710},"4": {"rowsTotal": 1,"rowsUpper": 1,"upperBound": 908},"5": {"rowsTotal": 1,"rowsUpper": 1,"upperBound": 1119},"6": {"rowsTotal": 1,"rowsUpper": 1,"upperBound": 1211},"7": {"rowsTotal": 1,"rowsUpper": 1,"upperBound": 1402},"8": {"rowsTotal": 0,"rowsUpper": 0,"upperBound": 1789},"9": {"rowsTotal": 1,"rowsUpper": 1,"upperBound": 1988}}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_delete_histogram_statistics)delete histogram statistics
`DELETE /gsql/v1/stats/histogram`
Remove histogram statistics from storage.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_140)Example: 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X DELETE 'http://localhost:14240/gsql/v1/stats/histogram' -d ' {"graph":"financialGraph", "edge":"isLocatedIn", "from":"Account", "to":"City", "attribute":"name"}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error": false,"message": "","results": "Deleting any histogram(s) for G.E1.a"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_user_defined_objects)User Defined Objects
### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_list_all_tuples)list all tuples
`GET /gsql/v1/udt/tuples`
Get all tuples.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_141)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X GET 'localhost:14240/gsql/v1/udt/tuples'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":[{"name":"TestTup","fields":[{"fieldName":"da","length":8,"fieldType":"UINT"},{"fieldName":"flow","length":8,"fieldType":"STRING"}]}]}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_list_one_tuple)list one tuple
`GET /gsql/v1/udt/tuples/{tupleName}`
Get tuple by its name.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_115)Parameters:
Name | Required | Description  
---|---|---  
`tupleName` | yes | the tuple name to get information  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_142)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X GET 'localhost:14240/gsql/v1/udt/tuples/TestTup'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":[{"name":"TestTup","fields":[{"fieldName":"da","length":8,"fieldType":"UINT"},{"fieldName":"flow","length":8,"fieldType":"STRING"}]}]}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_tuple)create tuple
`POST /gsql/udt/tuples`
Create a tuple.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_143)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X POST 'localhost:14240/gsql/v1/udt/tuples?gsql=true' -d '{"gsql":"create tuple commands"}'
or
curl -H 'Content-Type: application/json' -X POST 'localhost:14240/gsql/v1/udt/tuples' -d '{"tuples":[{"Name":"tuple1","TupleElements":[{"name":"attr1","AttributeType":"int"}]}]}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully create tuples: TestTup."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_delete_multiple_tuples)delete multiple tuples
`DELETE /gsql/v1/udt/tuples`
Delte multiple tuples.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_116)Parameters:
Name | Required | Description  
---|---|---  
`tupleName` | yes | the tuple names to be dropped  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_144)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X DELETE 'localhost:14240/gsql/v1/udt/tuples?tupleName=TestTuple'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully dropped userDefinedTuple: [TestTup]."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_delete_one_tuple)delete one tuple
`DELETE /gsql/v1/udt/tuples/{tupleName}`
Delete one tuple by its name.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_145)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X DELETE 'localhost:14240/gsql/v1/udt/tuples/TestTuple'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully dropped userDefinedTuple: [TestTup]."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_list_all_accumulators)list all accumulators
`GET /gsql/v1/udt/accum`
Get all accumulators.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_146)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X GET 'localhost:14240/gsql/v1/udt/accum'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":[{"myGroup":"GroupByAccum<int a, SumAccum<int> b> myGroup\n"}]}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_list_one_accumulator)list one accumulator
`GET /gsql/v1/udt/accum/{accumName}`
Get one accumulator by its name.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_147)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X GET 'localhost:14240/gsql/v1/udt/accum/myGroup'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":[{"myGroup":"GroupByAccum<int a, SumAccum<int> b> myGroup\n"}]}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_create_accumulators)create accumulators
`POST /gsql/v1/udt/accum`
Create one accumulator.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_148)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X POST 'localhost:14240/gsql/v1/udt/accum' -d '{"AccumString":"typedef GroupByAccum or typedef HeapAccum"}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully create accumulator."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_delete_mulitple_accumulators)delete mulitple accumulators
`DELETE /gsql/v1/udt/accum`
Delete multiple accumulators.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_parameters_117)Parameters:
Name | Required | Description  
---|---|---  
`accumName` | yes | the accumulator names to drop  
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_149)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X DELETE 'localhost:14240/gsql/v1/udt/accum?accumName=myGroup'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully dropped accumulator: [myGroup]."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_delete_one_accumulator)delete one accumulator
`DELETE /gsql/v1/udt/accum/{accumName}`
Delete one accumulator.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_150)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X DELETE 'localhost:14240/gsql/v1/udt/accum/myGroup'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"Successfully dropped accumulator: [myGroup]."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_download_expr_files)download expr files
`GET /gsql/v1/udt/files/{fileName}`
Download one file by its name, {fileName} can be one of: [tg_]ExprFunctions, [tg_]ExprUtil, TokenBank.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_151)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X GET 'localhost:14240/gsql/v1/udt/files/TokenBank'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"results": {"TokenBank": "<TokenBank File Content>"}}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_download_all_files)download all files
`GET /gsql/v1/udt/files`
Get all files.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_152)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X GET 'localhost:14240/gsql/v1/udt/files'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"results": {"TokenBank": "TokenBank File Content", "ExprFunctions": "ExprFunctions file content", "ExprUtil": "", "tg_ExprFunctions": "", "tg_ExprUtil": ""}}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_upload_one_file)upload one file
`PUT /gsql/v1/udt/files/{fileName}`
Upload file.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_153)Example 

Sample Request
    
```
curl -H 'Content-Type: text/plain' -X PUT 'localhost:14240/gsql/v1/udt/files/TokenBank' -d '<Token Bank file content>'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message": "Successfully update file: TokenBank"}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_upload_file)upload file
`PUT /gsql/v1/udt/files`
Upload all files.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_154)Example 

Sample Request
    
```
curl -H 'Content-Type: application/json' -X PUT 'localhost:14240/gsql/v1/udt/files' -d '{"files":[{"Name":"ExprUtil","Content":"<file content>"}]}'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message": "All files get updated: [TokenBank, ExprFunctions]."}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_token_bank_functions)get token bank functions
`GET /gsql/v1/udt/token-functions/{functionName}`
Get function content by its name.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_155)Example 

Sample Request
    
```
curl -X GET 'localhost:14240/gsql/v1/udt/token-functions/_Concat'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":{"code":"token bank function code","name":"_Concat","returnType":"string"}}
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_get_all_token_bank_functions)get all token bank functions
`GET /gsql/v1/udt/token-functions`
Get all token bank functions.
#### [](https://docs.tigergraph.com/tigergraph-server/4.1/API/gsql-endpoints#_example_156)Example 

Sample Request
    
```
curl -X GET 'localhost:14240/gsql/v1/udt/token-functions'
bash![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```


Sample Response
    
```
{"error":false,"message":"","results":[{"code":"token bank function code","name":"_Concat","returnType":"string"}]}
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


