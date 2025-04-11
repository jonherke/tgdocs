![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe)[Next](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe)
[Developer Site](https://dev.tigergraph.com/) [Community Forum](https://community.tigergraph.com/) [Knowledge Base](https://tigergraph.freshdesk.com/support/solutions)
[Download](https://dl.tigergraph.com)
[ TG Savanna](https://savanna.tgcloud.io)
### [TigerGraph DB](https://docs.tigergraph.com/tigergraph-server/4.2/intro/)
  *     * [TigerGraph DB Release Notes](https://docs.tigergraph.com/tigergraph-server/4.2/release-notes/)
  *     * [Architecture](https://docs.tigergraph.com/tigergraph-server/4.2/intro/internal-architecture)
      * [Transaction Processing and ACID Support](https://docs.tigergraph.com/tigergraph-server/4.2/intro/transaction-and-acid)
      * [Continuous Availability Overview](https://docs.tigergraph.com/tigergraph-server/4.2/intro/continuous-availability-overview)
  *     * Get Started
      * [Installation](https://docs.tigergraph.com/tigergraph-server/4.2/getting-started/)
        * [On Docker](https://docs.tigergraph.com/tigergraph-server/4.2/getting-started/docker)
        * [On Linux](https://docs.tigergraph.com/tigergraph-server/4.2/getting-started/linux)
          * [Hardware and Software Requirements](https://docs.tigergraph.com/tigergraph-server/4.2/installation/hw-and-sw-requirements)
          * [Linux On Bare Metal](https://docs.tigergraph.com/tigergraph-server/4.2/installation/bare-metal-install)
          * [Post Install Checks](https://docs.tigergraph.com/tigergraph-server/4.2/installation/post-install-check)
        * [On Kubernetes](https://docs.tigergraph.com/tigergraph-server/4.2/getting-started/kubernetes)
        * [On Cloud Marketplace](https://docs.tigergraph.com/tigergraph-server/4.2/getting-started/cloud-images/)
          * [AWS](https://docs.tigergraph.com/tigergraph-server/4.2/getting-started/cloud-images/aws)
          * [Azure](https://docs.tigergraph.com/tigergraph-server/4.2/getting-started/cloud-images/azure)
          * [GCP](https://docs.tigergraph.com/tigergraph-server/4.2/getting-started/cloud-images/gcp)
        * [Advanced License Issues](https://docs.tigergraph.com/tigergraph-server/4.2/installation/license)
        * [Changing Ports](https://docs.tigergraph.com/tigergraph-server/4.2/installation/change-port)
        * [Change IP or Hostname](https://docs.tigergraph.com/tigergraph-server/4.2/installation/change-ip-or-hostname)
        * [Upgrade](https://docs.tigergraph.com/tigergraph-server/4.2/installation/upgrade)
        * [Uninstallation](https://docs.tigergraph.com/tigergraph-server/4.2/installation/uninstallation)
      * [The GSQL Shell](https://docs.tigergraph.com/tigergraph-server/4.2/gsql-shell/)
        * [GSQL Shell Sessions](https://docs.tigergraph.com/tigergraph-server/4.2/gsql-shell/gsql-sessions)
        * [Using a Remote GSQL Client](https://docs.tigergraph.com/tigergraph-server/4.2/gsql-shell/using-a-remote-gsql-client)
        * [The GSQL Shell](https://docs.tigergraph.com/tigergraph-server/4.2/gsql-shell/)
  *     * [Clustering](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/)
      * Cluster Resizing
        * [Cluster Expansion](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/expand-a-cluster)
        * [Cluster Shrinking](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/shrink-a-cluster)
        * [Cluster Repartition](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/repartition-a-cluster)
        * [Removal of Failed Nodes](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/remove-failed-node)
        * [Replace a Node](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/how_to-replace-a-node-in-a-cluster)
      * [Cross-Region Replication](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/crr-index)
        * [Set Up Cross-Region Replication](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/set-up-crr)
        * [Fail over to the DR cluster](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/fail-over)
        * [Troubleshooting CRR](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/troubleshooting)
        * [Cross-Region Replication FAQ](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/crr-faq)
      * [High Availability](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-overview)
        * [High Availability Cluster Configuration](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-cluster)
        * [Region Aware Cluster Configuration](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/region-aware)
        * [GSQL Server HA](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-gsql-server)
        * [Application Server HA](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/ha-for-application-server)
      * [Cluster Commands](https://docs.tigergraph.com/tigergraph-server/4.2/cluster-and-ha-management/cluster-commands)
  *     * [Set Up Data Connectors](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/)
      * [Overview](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/data-loading-overview)
      * [Load from Local Files](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/load-local-files)
      * [from Cloud Storage](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/load-from-cloud)
      * [from Data Warehouse](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/load-from-warehouse)
      * [from External Kafka](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/load-from-kafka)
        * [Avro Data Validation](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/avro-validation-with-kafka)
        * [Kafka SSL Security Guide](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/kafka-ssl-security-guide)
      * [from Spark](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/load-from-spark-dataframe)
      * [to Spark](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe)
      * [Externalize Kafka Configs](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/externalizing-kafka-configs)
      * [Manage Data Sources](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/manage-data-source)
      * [Data Loading V2 (Beta)](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/data-loading-v2)
  *     * [Querying](https://docs.tigergraph.com/tigergraph-server/4.2/data-querying/README)
      * [Define a Graph Schema](https://docs.tigergraph.com/tigergraph-server/4.2/getting-started/database-definition)
  *     * [Manage Your Database](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/)
      * [GADMIN Utility](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/management-commands)
      * [Access Management](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/)
        * Authentication
          * [Enabling User Authentication](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/enabling-user-authentication)
          * [User Credentials](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-credentials)
          * [Single Sign-On](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/sso)
          * [Lightweight Directory Access Protocol (LDAP)](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/ldap)
          * [OIDC JWT Authentication](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/jwt-token)
        * Authorization
          * [User Management](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/user-management)
          * [Access Control Model](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/access-control-model)
          * [Fine-Grained Query Privileges](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/fine-grained-query-privileges)
            * [Migrate Query Privileges from 3.x to 4.1](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/query-privilege-migration)
          * [Role Management](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/role-management)
          * [Row Policies](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/row-policy-overview)
            * [Key Concepts](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/rbac-row-policy)
            * [Set Up Row Policy](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/setup-row-policy)
          * [Access Control Lists (ACLs) (Deprecated)](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/acl-management)
      * [Backup and Export](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/)
        * [Backup and Restore Configurations](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/configurations)
        * [Back up a Database Cluster](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/backup-cluster)
        * [Incremental Backup](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/incremental-backup)
        * [Online Backup](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/online-backup)
        * Restore
          * [Restore](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/restore-backup-same)
          * [Restore to a Different Cluster](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/restore-cross-cluster)
          * [Point-in-Time Restore](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/point-in-time-restore)
        * Export/Import
          * [Database Import/Export All Graphs](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/database-import-export)
          * [Import/Export Individual Graphs](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/single-graph-import-export)
        * [Legacy Backup and Restore](https://docs.tigergraph.com/tigergraph-server/4.2/backup-and-restore/gbar-legacy)
        * [Change Data Capture (CDC)](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/change-data-capture/cdc-overview)
          * [CDC Setup](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/change-data-capture/cdc-setup)
          * [CDC Message Examples](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/change-data-capture/cdc-message-example)
          * [CDC Monitoring and Reset](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/change-data-capture/cdc-state-monitoring)
      * [Kubernetes](https://docs.tigergraph.com/tigergraph-server/4.2/kubernetes/)
        * [Kubernetes Operator](https://docs.tigergraph.com/tigergraph-server/4.2/kubernetes/k8s-operator/)
      * [Logs](https://docs.tigergraph.com/tigergraph-server/4.2/troubleshooting/log-files)
      * [Resources and Processes](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/resource-and-process-mgmt)
        * [Memory Management](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/memory-management)
        * [Service Management](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/manage-services)
        * [Workload Management](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/workload-management)
        * [Using gadmin](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/management-with-gadmin)
        * [Metrics Reports](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/system-metrics)
      * [Security](https://docs.tigergraph.com/tigergraph-server/4.2/security/)
        * [Auditing Privileged User Actions](https://docs.tigergraph.com/tigergraph-server/4.2/security/audit-privileged-actions)
        * [Encrypting Connections](https://docs.tigergraph.com/tigergraph-server/4.2/security/encrypting-connections)
        * [Encrypting Data At Rest](https://docs.tigergraph.com/tigergraph-server/4.2/security/encrypting-data-at-rest)
        * [File Input Policy](https://docs.tigergraph.com/tigergraph-server/4.2/security/gsql-file-input-policy)
        * [File Output Policy](https://docs.tigergraph.com/tigergraph-server/4.2/security/file-output-policy)
        * [Login Policy](https://docs.tigergraph.com/tigergraph-server/4.2/security/login-protection)
        * [Password Policy](https://docs.tigergraph.com/tigergraph-server/4.2/security/password-policy)
  *     * References
      * [Best Practices](https://docs.tigergraph.com/tigergraph-server/4.2/additional-resources/best-practice-guides/best-practices-overview)
      * [Configuration Parameters](https://docs.tigergraph.com/tigergraph-server/4.2/reference/configuration-parameters)
      * [gadmin Commands](https://docs.tigergraph.com/tigergraph-server/4.2/system-management/management-commands)
      * [REST Endpoints](https://docs.tigergraph.com/tigergraph-server/4.2/API/)
        * [GSQL Endpoints](https://docs.tigergraph.com/tigergraph-server/4.2/API/gsql-endpoints)
        * [RESTPP & Infra Endpoints](https://docs.tigergraph.com/tigergraph-server/4.2/API/built-in-endpoints)
        * [Upsert Data](https://docs.tigergraph.com/tigergraph-server/4.2/API/upsert-rest)
      * [RBAC Object-Based Privileges](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/row-policy-privileges-table)
        * [RBAC Row Policy EBNF](https://docs.tigergraph.com/tigergraph-server/4.2/user-access/rbac-row-policy/row-policy-ebnf)
        * [List of Legacy Privilege Syntax](https://docs.tigergraph.com/tigergraph-server/4.2/reference/list-of-privileges)
      * [List of Ports](https://docs.tigergraph.com/tigergraph-server/4.2/reference/ports)
      * [Return codes](https://docs.tigergraph.com/tigergraph-server/4.2/reference/return-codes)
      * [Troubleshooting and FAQs](https://docs.tigergraph.com/tigergraph-server/4.2/troubleshooting/troubleshooting-guide)
      * More References
        * [Compare TigerGraph Editions](https://docs.tigergraph.com/tigergraph-server/4.2/intro/comparison-of-editions)
        * [Documentation for Legacy Versions](https://docs.tigergraph.com/tigergraph-server/4.2/additional-resources/legacy-tg-versions)
        * [Patents and Third Party Software](https://docs.tigergraph.com/tigergraph-server/4.2/reference/patents-and-third-party-software)
        * [TigerGraph Glossary](https://docs.tigergraph.com/tigergraph-server/4.2/reference/glossary)
        * [TigerGraph Release And Patch Process](https://docs.tigergraph.com/tigergraph-server/4.2/intro/release-process)


TigerGraph DB 4.2 Pre
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
  * [TigerGraph DB 4.2 Pre](https://docs.tigergraph.com/tigergraph-server/4.2/intro/)
  * [Set Up Data Connectors](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/)
  * [to Spark](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/4.2/modules/data-loading/pages/read-to-spark-dataframe.adoc)
### Contents
  * [Prerequisite](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_prerequisite)
  * [Download the TigerGraph Spark Connector](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_download_the_tigergraph_spark_connector)
  * [Configure Logging](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_configure_logging)
  * [Overview](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_overview)
  * [Database Connection](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_database_connection)
  * [Read Vertices](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_read_vertices)
  * [Read all vertices by type](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_read_all_vertices_by_type)
  * [Partitioned Vertex Query](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_partitioned_vertex_query)
  * [Read a vertex by primary ID](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_read_a_vertex_by_primary_id)
  * [Read Edges](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_read_edges)
  * [Read all edges of a vertex](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_read_all_edges_of_a_vertex)
  * [Read edges of a vertex by edge type](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_read_edges_of_a_vertex_by_edge_type)
  * [Read edges of a vertex by edge type and target vertex type](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_read_edges_of_a_vertex_by_edge_type_and_target_vertex_type)
  * [Read an edge by source vertex, target vertex, and edge type](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_read_an_edge_by_source_vertex_target_vertex_and_edge_type)
  * [Query Operators](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_query_operators)
  * [Run a GSQL Query](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_run_a_gsql_query)
  * [Run a Pre-installed Query](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_run_a_pre_installed_query)
  * [Run an Interpreted Query](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_run_an_interpreted_query)
  * [DataFrame Schema](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_dataframe_schema)
  * [Connector Options](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_connector_options)
  * [Common Options](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_common_options)
  * [Query Options](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_query_options)


# Read to Spark Dataframe
### Contents
  * [Prerequisite](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_prerequisite)
  * [Download the TigerGraph Spark Connector](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_download_the_tigergraph_spark_connector)
  * [Configure Logging](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_configure_logging)
  * [Overview](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_overview)
  * [Database Connection](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_database_connection)
  * [Read Vertices](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_read_vertices)
  * [Read all vertices by type](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_read_all_vertices_by_type)
  * [Partitioned Vertex Query](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_partitioned_vertex_query)
  * [Read a vertex by primary ID](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_read_a_vertex_by_primary_id)
  * [Read Edges](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_read_edges)
  * [Read all edges of a vertex](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_read_all_edges_of_a_vertex)
  * [Read edges of a vertex by edge type](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_read_edges_of_a_vertex_by_edge_type)
  * [Read edges of a vertex by edge type and target vertex type](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_read_edges_of_a_vertex_by_edge_type_and_target_vertex_type)
  * [Read an edge by source vertex, target vertex, and edge type](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_read_an_edge_by_source_vertex_target_vertex_and_edge_type)
  * [Query Operators](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_query_operators)
  * [Run a GSQL Query](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_run_a_gsql_query)
  * [Run a Pre-installed Query](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_run_a_pre_installed_query)
  * [Run an Interpreted Query](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_run_an_interpreted_query)
  * [DataFrame Schema](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_dataframe_schema)
  * [Connector Options](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_connector_options)
  * [Common Options](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_common_options)
  * [Query Options](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_query_options)


The TigerGraph Spark Connector employs [Apache Spark](https://spark.apache.org) to read data from TigerGraph.
Supported reader types:
  * Read Vertices
  * Read Edges
  * Run Pre-installed Query
  * Run Interpreted Query


The same connector can be used as an intermediary to read data from a variety of sources and then [stream data from Spark to TigerGraph.](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/load-from-spark-dataframe)
The legacy [Spark Connection Via JDBC Driver](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/spark-connection-via-jdbc-driver) is deprecated. Please migrate to this new connector.  
---  
## [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_prerequisite)Prerequisite
  * TigerGraph 3.6.0 or higher. Job-level loading statistics are available in v3.10+.
  * Spark 3.2 or higher with Scala 2.12 and Scala 2.13.
  * JAVA 8 or higher.


### [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_download_the_tigergraph_spark_connector)Download the TigerGraph Spark Connector
This connector can be downloaded from the Maven central repository: [Maven Central](https://central.sonatype.com/artifact/com.tigergraph/tigergraph-spark-connector/overview). The connector is available in three formats:
  * `tigergraph-spark-connector-<version>.jar`: The `JAR` file containing only the compiled classes of the connector, which does not include any dependencies.
  * `tigergraph-spark-connector-<version>-jar-with-dependencies.jar`: The `JAR` file that includes compiled classes, as well as all the dependencies.
  * `tigergraph-spark-connector-<version>.tar.gz`: The compressed `TAR` archive that includes `tigergraph-spark-connector-<version>.jar` and dependencies in separate `JAR` files.


To use the TigerGraph Spark connector in a Spark shell:
use the `--jars` option:
```
spark-shell --jars tigergraph-spark-connector-<version>-jar-with-dependencies.jar
```

If you want to include the TigerGraph Spark Connector in your Spark installation, add the `JAR` with dependencies to Spark’s `jars` folder.  
---  
### [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_configure_logging)Configure Logging
We highly recommend setting the log level to `info` to monitor the execution. There are two methods to enable logging for the connector.
#### [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_connector_default_logger)Connector Default Logger
The connector has a built-in logger based on _java.util.logging_. To activate it, set the option `log.level` to 2, which enables info-level logging.
Please refer to [Common Options](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_common_options) to learn more about `log.level` and `log.file` options.
#### [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_spark_logger)Spark Logger
Configure Spark Log4j by `$SPARK_HOME/conf/log4j2.properties` as follows, or other SLF4j bindings if any:
```
logger.tg.name = com.tigergraph
logger.tg.level = info
```

## [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_overview)Overview
TigerGraph Spark connector provides 4 kinds of reader options to read data from TigerGraph:
Option | Description  
---|---  
`query.vertex` | Read vertex/vertices with the attributes.  
`query.edge` | Read edge(s) with the attributes.  
`query.installed` | Run a pre-installed query and read the outputs of `PRINT` statement.  
`query.interpreted` | Run a query in interpreted mode and read the outputs of `PRINT` statement.  
Please refer to the following sections for detailed usage and examples. Prior to that, ensure that the connection options are defined in advance.
### [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_database_connection)Database Connection
Predefined connection options:
```
val tgOptions = Map(
  "url" -> "http(s)://<tg_node_host>:<tg_nginx_port>",
  "version" -> "<tg_version>",
  "graph" -> "<graph_name>",
  "username" -> "<username>",
  "password" -> "<password>"
)
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_some_helpful_tips)Some Helpful tips
  * **Connection options object**


You may find it convenient to bundle the options related to making a database connection in a data object (e.g., `tgOptions`) and then use `.options(tgOptions)` when running the connector. Moreover, placing the user credentials in a data object keeps them separate from the connection commands.
  * **Authentication methods**


Using username/password has the advantage that this authentication method will automatically refresh an access token as needed.If you choose to use a token, please make sure the lifetime of the token is long enough for the loading job.
  * **High Availabilty**


To support fault tolerance and failover, please provide the URL of all nodes in the option `url`, e.g., "url" → "https://m1:14240,https://m2:14240,https://m3:14240,https://m4:14240",
## [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_read_vertices)Read Vertices
### [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_read_all_vertices_by_type)Read all vertices by type
Option | Value  
---|---  
`query.vertex` | <vertex_type>  
Example: read all vertices of type `Person`
```
val df = spark.read
  .format("tigergraph")
  .options(tgOptions)
  .option("query.vertex", "Person")
  .load()
df.show()
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results
```
+--------+--------+---+------+-----+
|  v_id|  name|age|gender|state|
+--------+--------+---+------+-----+
|person42|person42| 42|female|  ny|
|person12|person12| 12| male|  ny|
+--------+--------+---+------+-----+
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_partitioned_vertex_query)Partitioned Vertex Query
To fully utilize the parallel and distributed processing capabilities of Spark and TigerGraph, it is recommended to use partitioned queries. This approach involves splitting a query into multiple range queries that are executed in parallel.
Option | Value  
---|---  
`query.partition.key` | The name of the attribute that has been indexed.  
`query.partition.num` | The expected partition number.  
`query.partition.upper.bound` | The upper bound used to calculate the partition stride.  
`query.partition.lower.bound` | The lower bound used to calculate the partition stride.  
Notice that `query.partition.upper.bound` and `query.partition.lower.bound` are just used to decide the partition stride, not for filtering the vertices.  
---  
Example
```
val df = spark.read
  .format("tigergraph")
  .options(tgOptions)
  .option("query.vertex", "Person")
  .option("query.partition.key", "age")
  .option("query.partition.num", "5")
  .option("query.partition.upper.bound", "50")
  .option("query.partition.lower.bound", "20")
  .load()
df.show()
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This query will generate 5 separate range queries:
  * age < 20
  * 20 ≤ age < 30
  * 30 ≤ age < 40
  * 40 ≤ age < 50
  * 50 ≤ age


### [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_read_a_vertex_by_primary_id)Read a vertex by primary ID
Option | Value  
---|---  
`query.vertex` | <vertex_type>.<vertex_id>  
Example: read a vertex of type `Person` and primary ID `person2`
```
val df = spark.read
  .format("tigergraph")
  .options(tgOptions)
  .option("query.vertex", "Person.person2")
  .load()
df.show()
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results
```
+--------+--------+---+------+-----+
|  v_id|  name|age|gender|state|
+--------+--------+---+------+-----+
| person2| person2| 3| male|  tx|
+--------+--------+---+------+-----+
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_read_edges)Read Edges
### [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_read_all_edges_of_a_vertex)Read all edges of a vertex
Option | Value  
---|---  
`query.edge` | <src_vertex_type>.<src_vertex_id>  
Example: read all edges of vertex type `Person`, ID `person1`
```
val df = spark.read
  .format("tigergraph")
  .options(tgOptions)
  .option("query.edge", "Person.person1")
  .load()
df.show()
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results
```
+---------+-------+-------+-------+-------+--------------------+
|from_type|from_id|to_type| to_id| e_type|     attributes|
+---------+-------+-------+-------+-------+--------------------+
|  Person|person1| Photo|photo16| Likes|{"click_time":"20...|
|  Person|person1| Short| short1| Likes|{"click_time":"20...|
|  Person|person1| Short| short1|Watches|   {"share":true}|
|  Person|person1| Short|short19|Watches|   {"share":true}|
+---------+-------+-------+-------+-------+--------------------+
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The results can contain different types of edges, so the edge attributes won’t be flattened.
### [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_read_edges_of_a_vertex_by_edge_type)Read edges of a vertex by edge type
Option | Value  
---|---  
`query.edge` | <src_vertex_type>.<src_vertex_id>.<edge_type>  
Example: read all edges of type `Likes` from vertex type `Person`, ID `person1`
```
val df = spark.read
  .format("tigergraph")
  .options(tgOptions)
  .option("query.edge", "Person.person1.Likes")
  .load()
df.show()
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results
```
+---------+-------+-------+-------+-------------------+
|from_type|from_id|to_type| to_id|     click_time|
+---------+-------+-------+-------+-------------------+
|  Person|person1| Photo|photo16|2024-01-22 03:16:45|
|  Person|person1| Short| short1|2019-07-15 09:23:41|
+---------+-------+-------+-------+-------------------+
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_read_edges_of_a_vertex_by_edge_type_and_target_vertex_type)Read edges of a vertex by edge type and target vertex type
Option | Value  
---|---  
`query.edge` | <src_vertex_type>.<src_vertex_id>.<edge_type>.<tgt_vertex_type>  
Example: read all edges of type `Likes` from vertex type `Person`, ID `person1` to vertex type `Photo`
```
val df = spark.read
  .format("tigergraph")
  .options(tgOptions)
  .option("query.edge", "Person.person1.Likes.Photo")
  .load()
df.show()
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results
```
+---------+-------+-------+-------+-------------------+
|from_type|from_id|to_type| to_id|     click_time|
+---------+-------+-------+-------+-------------------+
|  Person|person1| Photo|photo16|2024-01-22 03:16:45|
|  Person|person1| Photo| photo7|2021-05-09 17:58:00|
+---------+-------+-------+-------+-------------------+
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_read_an_edge_by_source_vertex_target_vertex_and_edge_type)Read an edge by source vertex, target vertex, and edge type
Option | Value  
---|---  
`query.edge` | <src_vertex_type>.<src_vertex_id>.<edge_type>.<tgt_vertex_type>.<tgt_vertex_id>  
Example: read an edge of type `Likes` from vertex type `Person` and ID `person1`, to vertex type `Photo` and ID `photo7`
```
val df = spark.read
  .format("tigergraph")
  .options(tgOptions)
  .option("query.edge", "Person.person1.Likes.Photo.photo7")
  .load()
df.show()
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Results
```
+---------+-------+-------+------+-------------------+
|from_type|from_id|to_type| to_id|     click_time|
+---------+-------+-------+------+-------------------+
|  Person|person1| Photo|photo7|2021-05-09 17:58:00|
+---------+-------+-------+------+-------------------+
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

By default, we use "." to split the query fields. If the vertex ID contains ".", you can set a different separator to avoid the conflict: ```
.option("query.edge", "Person|jack.smith|Likes|Photo")
.option("query.field.separator", "|")scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!
```
  
---  
## [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_query_operators)Query Operators
For the built-in vertex and edge queries mentioned above, there are several available query operators that can be used in combination.:
Option | Value | Example  
---|---|---  
`query.op.select` | Attributes of the selected vertices/edges to return separated by comma. | `name,age`  
`query.op.filter` | Conditions used to filter the vertices/edges to return. The parameter takes a list of conditions, which is a string of comma-separated values. | `age>20,gender=male`  
`query.op.limit` | An integer value that specifies the maximum limit of the total number of vertices/edges to return. NOTE: When used with partitioned queries, the limit applies to each partition. | `50`  
`query.op.sort` | Attributes to sort the results by. The parameter takes a list, which is a string of comma-separated values, and will sort all the vertices/edges based on the attributes provided in the list in order. NOTE: When used with partitioned queries, the sort applies within each partition. | `age,-salary`  
Example: read top 10 vertices of type Person, sorted by age(ASC) and last_name(DESC)
```
val df = spark.read
  .format("tigergraph")
  .options(tgOptions)
  .option("query.vertex", "Person")
  .option("query.op.limit", "10")
  .option("query.op.sort", "age,-last_name")
  .load()
df.show()
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Example: read edges of type `Invest`, whose `ratio` attribute should be greater than 0.1, and select only the `timestamp` attribute:
```
val df = spark.read
  .format("tigergraph")
  .options(tgOptions)
  .option("query.edge", "Person.person1.Invest")
  .option("query.op.filter", "ratio>0.1")
  .option("query.op.select", "timestamp")
  .load()
df.show()
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_run_a_gsql_query)Run a GSQL Query
### [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_run_a_pre_installed_query)Run a Pre-installed Query
Option | Value  
---|---  
`query.installed` | Name of the pre-installed query.  
`query.params` | The query parameters in JSON format. Please refer to [Formatting data in JSON](https://docs.tigergraph.com/tigergraph-server/4.2/API/#_formatting_data_in_json).  
Example: run the query `topK` with k=10
GSQL Query `topK`
```
CREATE QUERY topK (INT k) {
  vSet = SELECT p FROM Person:p ORDER BY p.age LIMIT k;
  PRINT vSet;
}
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Reader Options
```
val df = spark.read
  .format("tigergraph")
  .options(tgOptions)
  .option("query.installed", "topK")
  .option("query.params", "{\"k\": 10}")
  .load()
df.show()
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_run_an_interpreted_query)Run an Interpreted Query
Option | Value  
---|---  
`query.interpreted` | Query body of an anonymous query.  
Example: run the anonymous `topK` query in interpreted mode with k=10. Because no parameter is allowed, the parameter k is set within the query.
Define the interpreted query body
```
val queryBody = """
  INTERPRET QUERY () FOR GRAPH gsql_demo {
    INT k=10;
    vSet = SELECT p FROM Person:p ORDER BY p.age LIMIT k;
    PRINT vSet;
  }
"""
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Reader Options
```
val df = spark.read
  .format("tigergraph")
  .options(tgOptions)
  .option("query.interpreted", queryBody)
  .load()
df.show()
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

### [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_dataframe_schema)DataFrame Schema
#### [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_schema_inference)Schema Inference
The output format of a GSQL query is flexible, as you can include multiple `PRINT` statements within a single query, with each `PRINT` statement capable of printing multiple objects.
By default, the output of each `PRINT` statement is converted into a row of a DataFrame:
A portion of a GSQL query with multiple PRINT statements
```
...
ListAccum<INT> @@list_accum = [1,3,5];
PRINT @@list_accum, @@list_accum.size();
PRINT @@list_accum.get(0);
...
gsql![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The resulting DataFrame includes two rows corresponding to the outputs of two PRINT statements.
```
+------------------------------------------------+
|results                     |
+------------------------------------------------+
|{"@@list_accum":[1,3,5],"@@list_accum.size()":3}|
|{"@@list_accum.get(0)":1}            |
+------------------------------------------------+
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

However, sometimes we want to convert a vertex expression set or an accumulator into a Spark DataFrame, like `@@list_accum`, with each element being transformed into a row of the DataFrame.
The connector can automatically expand the vertex set or accumulator to Spark DataFrame under the following conditions:
  * It is an installed query instead of an interpreted query;
  * It contains only one PRINT statement, which only print a single object;
  * The printed object must either be a vertex expression set, or an accumulator.


You can also explicitly extract an object from multiple PRINT statements by option `query.results.extract`:
Option | Value  
---|---  
`query.results.extract` | The row index and the object key concatenated with colon. E.g.: `1:vSet`, which extracts `vSet` from the output of the 2nd PRINT statement.  
Example: The above list accumulator is extracted and expanded by setting "query.results.extract" to "0:@@list_accum".
```
+-------+
|results|
+-------+
|1   |
|3   |
|5   |
+-------+
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

#### [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_custom_schema)Custom Schema
For interpreted queries and some installed queries, the schema cannot be inferred accurately, so it’s required to manually provide the schema by `.schema(DDLString)`, whose column names should be the same as the corresponding JSON keys. Please check the example below:
Define the topK query in interpreted mode
```
val queryBody = """
  INTERPRET QUERY () FOR GRAPH gsql_demo {
    INT k=3;
    vSet = SELECT p FROM Person:p ORDER BY p.age LIMIT k;
    PRINT vSet;
  }
"""
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

1. without user given schema
```
val df = spark.read
  .format("tigergraph")
  .options(tgOptions)
  .option("query.interpreted", queryBody)
  .option("query.results.extract","0:vSet") // explicitly expand the vertex set
  .load()
df.show()
+-----------------------------------------------------------------------------------------------------------+
|results                                                  |
+-----------------------------------------------------------------------------------------------------------+
|{"v_id":"person1","attributes":{"gender":"male","name":"person1","state":"fl","age":1},"v_type":"Person"} |
|{"v_id":"person2","attributes":{"gender":"female","name":"person2","state":"ca","age":2},"v_type":"Person"}|
|{"v_id":"person3","attributes":{"gender":"male","name":"person3","state":"ny","age":3},"v_type":"Person"} |
+-----------------------------------------------------------------------------------------------------------+
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

2. with user given schema
```
val df = spark.read
  .format("tigergraph")
  .schema("v_id STRING, gender STRING, name STRING, state STRING, age INT") // user given schema
  .options(tgOptions)
  .option("query.interpreted", queryBody)
  .option("query.results.extract","0:vSet") // explicitly expand the vertex set
  .load()
df.show()
+-------+------+-------+-----+---+
|v_id  |gender|name  |state|age|
+-------+------+-------+-----+---+
|person1|male |person1|fl  |1 |
|person2|female|person2|ca  |2 |
|person3|male |person3|ny  |3 |
+-------+------+-------+-----+---+
scala![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_connector_options)Connector Options
### [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_common_options)Common Options
Beginning with version 0.2.0 of the connector, the following [connector options](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/load-from-spark-dataframe#_connector_options) are required: `version`, `log.level`, and `log.file`.  
---  
Key | Default Value | Description | Group  
---|---|---|---  
`url` | (none) | The connection URL to TigerGraph cluster. It can be a list of URLs separated by comma for load balancing. The port number can be retrieved by `gadmin config get Nginx.Port`. For TGCloud users, the default port number is 443. Example: http(s)://192.168.1.1:14240, http(s)://192.168.1.2:14240, http(s)://192.168.1.3:14240 | General  
`version` | (none) | TigerGraph version, e.g., "3.10.1", "4.1.0". | General  
`graph` | (none) | The graph name. | General  
`username` | (none) | The GSQL username. | Authentication (The username/password pair or secret based authentication is more preferred than a fixed token, as it can generate and refresh token automatically.)  
`password` | (none) | The GSQL password. | Authentication  
`secret` | (none) | The GSQL secret, which is recommended for TGCloud users. | Authentication  
`token` | (none) | The classic Bearer token or JWT(since 3.10.1) for RESTPP authentication. | Authentication  
`ssl.mode` | basic | The SSL mode. Supported values: `basic`, `verifyCA` and `verifyHostname`. When setting it to `verifyCA` or `verifyHostname`, the truststore file should be given. | SSL  
`ssl.truststore` | (none) | Filename of the truststore which stores the SSL certificate chains. Add `--files /path/to/trust.jks` when submitting the Spark job. | SSL  
`ssl.truststore.type` | JKS | Truststore type, e.g., JKS, PKCS12 | SSL  
`ssl.truststore.password` | (none) | Password of the truststore. | SSL  
`io.connect.timeout.ms` | 30000 | Connect timeout in ms. | Transport Timeout  
`io.read.timeout.ms` | 60000 | Socket read timeout in ms. | Transport Timeout  
`io.retry.interval.ms` | 5000 | The initial retry interval for transport timeout. | Transport Timeout  
`io.max.retry.interval.ms` | 10000 | The maximum retry interval for transport timeout. | Transport Timeout  
`io.max.retry.attempts` | 5 | The maximum retry attempts for transport timeout. | Transport Timeout  
`log.level` | (none) | The log level of the default logger. Available values: "0", "1", "2" and "3", which represent "ERROR", "WARN", "INFO" and "DEBUG". The Spark logging configurations(log4j) will be omitted if this option is set. The log will be printed to stderr unless `log.file` is set. | Logging  
`log.file` | (none) | The log file name pattern, e.g., "/tmp/tigergraph-spark-connector.log". It requires setting `log.level` first. | Logging  
### [](https://docs.tigergraph.com/tigergraph-server/4.2/data-loading/read-to-spark-dataframe#_query_options)Query Options
Key | Default Value | Description | Group  
---|---|---|---  
`query.timeout.ms` | 16000 | By default, an HTTP request in the TigerGraph system times out after 16 seconds. You can customize this timeout limit for a particular query instance by this option. Equivalent to RESTPP request header `GSQL-TIMEOUT`. | Query  
`query.max.response.bytes` | (none) | Specify the response size limit of a query request. Equivalent to RESTPP request header `RESPONSE-LIMIT`. | Query  
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


