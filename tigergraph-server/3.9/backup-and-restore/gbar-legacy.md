![TigerGraph Logo](https://www.tigergraph.com/wp-content/uploads/2020/05/TG_LOGO.svg) [Docs](https://docs.tigergraph.com/home)
Page 1[Prev](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy)[Next](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy)
Search by [Algolia](https://www.algolia.com/docsearch)
[Products](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy)
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
[Resources](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy)
[Developer Site](https://dev.tigergraph.com/) [Community Forum](https://community.tigergraph.com/) [Knowledge Base](https://tigergraph.freshdesk.com/support/solutions)
[Download](https://dl.tigergraph.com)
[ TG Savanna](https://savanna.tgcloud.io)
### [TigerGraph DB](https://docs.tigergraph.com/tigergraph-server/3.9/intro/)
  *     * [Release Notes](https://docs.tigergraph.com/tigergraph-server/3.9/release-notes/)
  *     * [Overview](https://docs.tigergraph.com/tigergraph-server/3.9/intro/)
    * [Get Started](https://docs.tigergraph.com/tigergraph-server/3.9/getting-started/)
      * Installation
        * [On Docker](https://docs.tigergraph.com/tigergraph-server/3.9/getting-started/docker)
        * [On Cloud Marketplace](https://docs.tigergraph.com/tigergraph-server/3.9/getting-started/cloud-images/)
          * [AWS](https://docs.tigergraph.com/tigergraph-server/3.9/getting-started/cloud-images/aws)
          * [Azure](https://docs.tigergraph.com/tigergraph-server/3.9/getting-started/cloud-images/azure)
          * [GCP](https://docs.tigergraph.com/tigergraph-server/3.9/getting-started/cloud-images/gcp)
        * [On Linux](https://docs.tigergraph.com/tigergraph-server/3.9/getting-started/linux)
          * [System Requirements](https://docs.tigergraph.com/tigergraph-server/3.9/installation/hw-and-sw-requirements)
          * [Linux On Bare Metal](https://docs.tigergraph.com/tigergraph-server/3.9/installation/bare-metal-install)
          * [Post Install Checks](https://docs.tigergraph.com/tigergraph-server/3.9/installation/post-install-check)
        * [Advanced License Issues](https://docs.tigergraph.com/tigergraph-server/3.9/installation/license)
        * [Changing Ports](https://docs.tigergraph.com/tigergraph-server/3.9/installation/change-port)
        * [Upgrade](https://docs.tigergraph.com/tigergraph-server/3.9/installation/upgrade)
        * [Uninstallation](https://docs.tigergraph.com/tigergraph-server/3.9/installation/uninstallation)
      * [The GSQL Shell](https://docs.tigergraph.com/tigergraph-server/3.9/gsql-shell/)
        * [GSQL Shell Sessions](https://docs.tigergraph.com/tigergraph-server/3.9/gsql-shell/gsql-sessions)
        * [Using a Remote GSQL Client](https://docs.tigergraph.com/tigergraph-server/3.9/gsql-shell/using-a-remote-gsql-client)
        * [GSQL Shell (Web)](https://docs.tigergraph.com/tigergraph-server/3.9/gsql-shell/web)
    * [Create Database](https://docs.tigergraph.com/tigergraph-server/3.9/getting-started/database-definition)
      * [MultiGraph Overview](https://docs.tigergraph.com/tigergraph-server/3.9/intro/multigraph-overview)
  *     * [Load Data](https://docs.tigergraph.com/tigergraph-server/3.9/data-loading/)
      * [Overview](https://docs.tigergraph.com/tigergraph-server/3.9/data-loading/data-loading-overview)
      * [Load from Local Files](https://docs.tigergraph.com/tigergraph-server/3.9/data-loading/load-local-files)
      * [Load from Cloud Storage](https://docs.tigergraph.com/tigergraph-server/3.9/data-loading/load-from-cloud)
      * [Load from Data Warehouse](https://docs.tigergraph.com/tigergraph-server/3.9/data-loading/load-from-warehouse)
      * [Load from External Kafka](https://docs.tigergraph.com/tigergraph-server/3.9/data-loading/load-from-kafka)
      * [Load DataFrames from Spark](https://docs.tigergraph.com/tigergraph-server/3.9/data-loading/spark-connection-via-jdbc-driver)
      * [Manage Data Sources](https://docs.tigergraph.com/tigergraph-server/3.9/data-loading/manage-data-source)
      * [Stream from External Kafka (Deprecated)](https://docs.tigergraph.com/tigergraph-server/3.9/data-loading/data-streaming-connector/kafka)
  *     * Advanced Topics
      * [System Management](https://docs.tigergraph.com/tigergraph-server/3.9/system-management/management-with-gadmin)
        * [Memory management](https://docs.tigergraph.com/tigergraph-server/3.9/system-management/memory-management)
        * [Manage TigerGraph services](https://docs.tigergraph.com/tigergraph-server/3.9/system-management/manage-services)
        * [Workload Management](https://docs.tigergraph.com/tigergraph-server/3.9/system-management/workload-management)
        * [Metrics Reporting](https://docs.tigergraph.com/tigergraph-server/3.9/system-management/system-metrics)
        * [Command Glossary](https://docs.tigergraph.com/tigergraph-server/3.9/system-management/management-commands)
      * [Access Management](https://docs.tigergraph.com/tigergraph-server/3.9/user-access/)
        * Authentication
          * [Enabling User Authentication](https://docs.tigergraph.com/tigergraph-server/3.9/user-access/enabling-user-authentication)
          * [User Credentials](https://docs.tigergraph.com/tigergraph-server/3.9/user-access/user-credentials)
          * [Single Sign-On](https://docs.tigergraph.com/tigergraph-server/3.9/user-access/sso)
          * [Lightweight Directory Access Protocol (LDAP)](https://docs.tigergraph.com/tigergraph-server/3.9/user-access/ldap)
        * Authorization
          * [User Management](https://docs.tigergraph.com/tigergraph-server/3.9/user-access/user-management)
          * [Role Management](https://docs.tigergraph.com/tigergraph-server/3.9/user-access/role-management)
          * [Access Control Model](https://docs.tigergraph.com/tigergraph-server/3.9/user-access/access-control-model)
          * [Access Control Lists (ACLs)](https://docs.tigergraph.com/tigergraph-server/3.9/user-access/acl-management)
          * [Vertex-Level Access Control (Deprecated)](https://docs.tigergraph.com/tigergraph-server/3.9/user-access/vlac)
      * [Backup and Restore](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/)
        * [Backup and Restore Configurations](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/configurations)
        * [Back up a Database Cluster](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/backup-cluster)
        * [Restore a Database Backup from the Same Cluster](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/restore-backup-same)
        * [Restore a Database Backup from Another Cluster](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/cross-cluster-backup)
        * [Database Import/Export](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/database-import-export)
        * [Legacy Backup and Restore](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy)
      * Cluster and HA Management
        * Cluster Resizing
          * [Cluster Expansion](https://docs.tigergraph.com/tigergraph-server/3.9/cluster-and-ha-management/expand-a-cluster)
          * [Cluster Shrinking](https://docs.tigergraph.com/tigergraph-server/3.9/cluster-and-ha-management/shrink-a-cluster)
          * [Cluster Repartition](https://docs.tigergraph.com/tigergraph-server/3.9/cluster-and-ha-management/repartition-a-cluster)
          * [Cluster Replace](https://docs.tigergraph.com/tigergraph-server/3.9/cluster-and-ha-management/how_to-replace-a-node-in-a-cluster)
        * [Cross-Region Replication (CRR)](https://docs.tigergraph.com/tigergraph-server/3.9/cluster-and-ha-management/crr-index)
          * [Set up CRR](https://docs.tigergraph.com/tigergraph-server/3.9/cluster-and-ha-management/set-up-crr)
          * [Fail over to the DR cluster](https://docs.tigergraph.com/tigergraph-server/3.9/cluster-and-ha-management/fail-over)
          * [Troubleshooting CRR](https://docs.tigergraph.com/tigergraph-server/3.9/cluster-and-ha-management/troubleshooting)
          * [CRR FAQ](https://docs.tigergraph.com/tigergraph-server/3.9/cluster-and-ha-management/crr-faq)
        * [High Availability (HA)](https://docs.tigergraph.com/tigergraph-server/3.9/cluster-and-ha-management/ha-overview)
          * [Cluster Configuration](https://docs.tigergraph.com/tigergraph-server/3.9/cluster-and-ha-management/ha-cluster)
          * [GSQL Server Support](https://docs.tigergraph.com/tigergraph-server/3.9/cluster-and-ha-management/ha-for-gsql-server)
          * [Application Server Support](https://docs.tigergraph.com/tigergraph-server/3.9/cluster-and-ha-management/ha-for-application-server)
          * [Cluster Commands](https://docs.tigergraph.com/tigergraph-server/3.9/cluster-and-ha-management/cluster-commands)
          * [Removal of Failed Nodes](https://docs.tigergraph.com/tigergraph-server/3.9/cluster-and-ha-management/remove-failed-node)
      * [Architecture](https://docs.tigergraph.com/tigergraph-server/3.9/intro/internal-architecture)
        * [MultiGraph Overview](https://docs.tigergraph.com/tigergraph-server/3.9/intro/multigraph-overview)
        * [Transaction Processing and ACID Support](https://docs.tigergraph.com/tigergraph-server/3.9/intro/transaction-and-acid)
        * [Continuous Availability Overview](https://docs.tigergraph.com/tigergraph-server/3.9/intro/continuous-availability-overview)
      * [Kubernetes (Preview)](https://docs.tigergraph.com/tigergraph-server/3.9/kubernetes/)
        * [Kubernetes Operator (Preview)](https://docs.tigergraph.com/tigergraph-server/3.9/kubernetes/k8s-operator/)
  *     * [Security](https://docs.tigergraph.com/tigergraph-server/3.9/security/)
      * [Auditing Privileged User Actions](https://docs.tigergraph.com/tigergraph-server/3.9/security/audit-privileged-actions)
      * [Encrypting Connections](https://docs.tigergraph.com/tigergraph-server/3.9/security/encrypting-connections)
      * [Encrypting Data At Rest](https://docs.tigergraph.com/tigergraph-server/3.9/security/encrypting-data-at-rest)
      * [File Output Policy](https://docs.tigergraph.com/tigergraph-server/3.9/security/file-output-policy)
      * [Configuring Login Protection](https://docs.tigergraph.com/tigergraph-server/3.9/security/login-protection)
  *     * [REST API Reference](https://docs.tigergraph.com/tigergraph-server/3.9/API/)
      * [Authentication](https://docs.tigergraph.com/tigergraph-server/3.9/API/authentication)
      * [Built-in Endpoints](https://docs.tigergraph.com/tigergraph-server/3.9/API/built-in-endpoints)
      * [Built-in Endpoints JSON Catalog](https://docs.tigergraph.com/tigergraph-server/3.9/API/json-catalog)
      * [Upsert data to graph](https://docs.tigergraph.com/tigergraph-server/3.9/API/upsert-rest)
  *     * Additional Resources
      * Troubleshooting and FAQs
        * [Knowledge base and FAQs](https://kb.tigergraph.com/)
        * [System Administration FAQs](https://docs.tigergraph.com/tigergraph-server/3.9/troubleshooting/system-administration-faqs)
        * [Log Files](https://docs.tigergraph.com/tigergraph-server/3.9/troubleshooting/log-files)
          * [Gathering Log Information with gcollect](https://docs.tigergraph.com/tigergraph-server/3.9/troubleshooting/gcollect)
          * [Audit Logs](https://docs.tigergraph.com/tigergraph-server/3.9/troubleshooting/audit-logs)
          * [Set up Log Viewing with Elasticsearch, Kibana and Filebeat](https://docs.tigergraph.com/tigergraph-server/3.9/troubleshooting/elk-filebeat)
        * [Troubleshooting Guide](https://docs.tigergraph.com/tigergraph-server/3.9/troubleshooting/troubleshooting-guide)
      * References
        * [Configuration Parameters](https://docs.tigergraph.com/tigergraph-server/3.9/reference/configuration-parameters)
        * [Return codes](https://docs.tigergraph.com/tigergraph-server/3.9/reference/return-codes)
        * [List of Privileges](https://docs.tigergraph.com/tigergraph-server/3.9/reference/list-of-privileges)
        * [List of Ports](https://docs.tigergraph.com/tigergraph-server/3.9/reference/ports)
        * [Glossary](https://docs.tigergraph.com/tigergraph-server/3.9/reference/glossary)
        * [Patents and Third Party Software](https://docs.tigergraph.com/tigergraph-server/3.9/reference/patents-and-third-party-software)
        * [Legacy Version Documentation](https://docs.tigergraph.com/tigergraph-server/3.9/additional-resources/legacy-tg-versions)
        * [Comparing TigerGraph Editions](https://docs.tigergraph.com/tigergraph-server/3.9/intro/comparison-of-editions)
        * [Release and Patch Process](https://docs.tigergraph.com/tigergraph-server/3.9/intro/release-process)


TigerGraph DB 3.9
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
  * [TigerGraph DB 3.9](https://docs.tigergraph.com/tigergraph-server/3.9/intro/)
  * Advanced Topics
  * [Backup and Restore](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/)
  * [Legacy Backup and Restore](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy)


[Edit this Page](https://github.com/tigergraph/server-docs/edit/3.9/modules/backup-and-restore/pages/gbar-legacy.adoc)
### Contents
  * [Synopsis](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy#_synopsis)
  * [Configure GBAR](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy#_configure_gbar)
  * [Perform a backup](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy#_perform_a_backup)
  * [List Backup Files](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy#_list_backup_files)
  * [Restore from a backup archive](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy#_restore_from_a_backup_archive)
  * [Restore process](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy#_restore_process)
  * [Remove a backup](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy#_remove_a_backup)
  * [Clean up temporary files](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy#_clean_up_temporary_files)
  * [GBAR Detailed Example](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy#_gbar_detailed_example)
  * [GBAR Backup Operational Details](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy#_gbar_backup_operational_details)
  * [GBAR Restore Operational Details](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy#_gbar_restore_operational_details)
  * [Performance Summary of Example](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy#_performance_summary_of_example)


# Legacy Backup and Restore
### Contents
  * [Synopsis](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy#_synopsis)
  * [Configure GBAR](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy#_configure_gbar)
  * [Perform a backup](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy#_perform_a_backup)
  * [List Backup Files](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy#_list_backup_files)
  * [Restore from a backup archive](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy#_restore_from_a_backup_archive)
  * [Restore process](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy#_restore_process)
  * [Remove a backup](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy#_remove_a_backup)
  * [Clean up temporary files](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy#_clean_up_temporary_files)
  * [GBAR Detailed Example](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy#_gbar_detailed_example)
  * [GBAR Backup Operational Details](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy#_gbar_backup_operational_details)
  * [GBAR Restore Operational Details](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy#_gbar_restore_operational_details)
  * [Performance Summary of Example](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy#_performance_summary_of_example)


Graph Backup And Restore (GBAR), is an integrated tool for backing up and restoring the data and data dictionary (schema, loading jobs, and queries) of a TigerGraph instance or cluster.
The backup feature packs TigerGraph data and configuration information into a directory on the local disk or a remote AWS S3 bucket. Multiple backup files can be archived. Later, you can use the restore feature to roll back the system to any backup point. This tool can also be integrated easily with Linux cron to perform periodic backup jobs.
The current version of GBAR is intended for restoring the same machine that was backed up. For help with cloning a database (i.e., backing up machine A and restoring the database to machine B), please [open a support ticket](https://tigergraph.zendesk.com/hc/en-us/).  
---  
## [](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy#_synopsis)Synopsis
```
Usage: gbar backup [options] -t <backup_tag>
		   gbar restore [options] <backup_tag>
		   gbar list [backup_tag] [-j]
		   gbar remove|rm <backup_tag>
		   gbar cleanup
		   gbar expand [-a] <new_nodes>
		      New nodes must be written in <name>:<host> pairs separated by comma
		      Example:
		        m1:192.168.1.2,m2:192.168.1.3,m3:192.168.1.4
		Options:
		 -h, --help   	Show this help message and exit
		 -v       	Run with debug info dumped
		 -vv      	Run with verbose debug info dumped
		 -y       	Run without prompt
		 -j      		Print gbar list as JSON
		 -t BACKUP_TAG 	Tag for backup file, required on backup
		 -a, --advanced  Enable advanced mode for node expansion
text![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The `-y` option forces GBAR to skip interactive prompt questions by selecting the default answer. There is currently one interactive question:
  * At the start of the restore process, GBAR always asks if it is okay to stop and reset the TigerGraph services. The default answer is yes.


## [](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy#_configure_gbar)Configure GBAR
Before using the backup or the restore feature, GBAR must be configured.
  1. Run `gadmin config entry system.backup`. At each prompt, enter the appropriate values for each config parameter.
```
$ gadmin config entry system.backup
System.Backup.TimeoutSec [ 18000 ]: The backup timeout in seconds
New: 18000
System.Backup.CompressProcessNumber [ 0 ]: The number of concurrent process for compression during backup
New: 0
System.Backup.Local.Enable [ true ]: Backup data to local path
New: true
System.Backup.Local.Path [ /tmp/backup ]: The path to store the backup files
New: /data/backup
System.Backup.S3.Enable [ false ]: Backup data to S3 path
New: false
System.Backup.S3.AWSAccessKeyID [ <masked> ]: The path to store the backup files
New:
System.Backup.S3.AWSSecretAccessKey [ <masked> ]: The path to store the backup files
New:
System.Backup.S3.BucketName [ ]: The path to store the backup files
New:
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

  2. After entering the configuration values, run the following command to apply the new configurations
```
gadmin config apply -y
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```



  * You can specify the number of parallel processes for backup and restore.
  * You must provide the username and password using `GSQL_USERNAME` and `GSQL_PASSWORD` environment variables. ```
$ GSQL_USERNAME=tigergraph GSQL_PASSWORD=tigergraph gbar backup -t daily![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!
```


  
---  
## [](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy#_perform_a_backup)Perform a backup
Before performing a backup, ensure that there is enough free disk space for the backup files.
To perform a backup, run the following command as the TigerGraph Linux user:
```
gbar backup -t <backup_tag>
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

Depending on your configuration settings, your backup archive is output to your local backup path and/or your AWS S3 bucket. If you are running a cluster, there will be a backup archive on every node in the same path.
A backup archive is stored as several files in a folder, rather than as a single file. The backup tag acts like a filename prefix for the archive filename. The full name of the backup archive will be `<backup_tag>-<timestamp>`, which is a subfolder of the backup repository.
  * If `System.Backup.Local.Enable` is set to `true`, the folder is a local folder on every node in a cluster, to avoid massive data moving across nodes in a cluster.
  * If `System.Backup.S3.Enable` is set to `true`, every node will upload data located on the node to the s3 repository. Therefore, every node in a cluster needs access to Amazon S3.


GBAR Backup performs a live backup, meaning that normal operations may continue while the backup is in progress. When GBAR backup starts, GBAR checks if there are running loading jobs. If there are, it pauses loading for 1 minute to generate a snapshot and then continue the backup process. You can specify the loading pausing interval by the environment variable `PAUSE_LOADING`.
GBAR then sends a request to the admin server, which then requests the GPE and GSE to create snapshots of their data. Per the request, the GPE and GSE store their data under GBAR’s own working directory. GBAR also directly contacts the Dictionary and obtains a dump of its system configuration information. In addition, GBAR gathers the TigerGraph system version and customized information including user-defined functions, token functions, schema layouts and user-uploaded icons. Then, GBAR compresses each of these data and configuration information files in tgz format and stores them in the `<backup_tag>-<timestamp>` subfolder on each node. As the last step, GBAR copies that file to local storage or AWS S3, according to the Config settings, and removes all temporary files generated during backup.
The current version of GBAR Backup takes snapshots quickly to make it very likely that all the components (GPE, GSE, and Dictionary) are in a consistent state, but it does not fully guarantee consistency.
Backup does not save input message queues for REST++ or Kafka. Make sure all messages are consumed before performing a backup.  
---  
## [](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy#_list_backup_files)List Backup Files
```
gbar list
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

This command lists all generated backup files in the storage place configured by the user. For each file, it shows the file’s full tag, its size in human-readable format, and its creation time.
## [](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy#_restore_from_a_backup_archive)Restore from a backup archive
Before restoring a backup, ensure that the backup you are restoring from is in the **same exact version** as your current version of TigerGraph. Also make sure you have enough free disk space to accommodate both the old graph store and the graph store to be restored.
To restore a backup, run the following command:
```
gbar restore <archive_name>
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

If GBAR can verify that the backup archive exists and that the backup’s system version is compatible with the current system version, GBAR shuts down the TigerGraph servers temporarily as it restores the backup. After completing the restore, GBAR restarts the TigerGraph servers. If you are running a cluster, and you have copied the backup files to each individual node in the cluster, running `gbar restore` on any node restores the entire cluster.
Restore is an offline operation, requiring the data services to be temporarily shut down. The user must specify the full archive name ( `<backup_tag>-<timestamp>` ) to be restored.
### [](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy#_restore_process)Restore process
When GBAR restore begins, it first searches for a backup archive exactly matching the archive name supplied in the command line. Then it decompresses the backup files to a working directory. Next, GBAR compares the TigerGraph system version in the backup archive with the current system’s version, to make sure that the backup archive is compatible with that current system. It will then shut down the TigerGraph servers (GSE, RESTPP, etc.) temporarily.
GBAR then makes a copy of the current graph data, as a precaution. Next, GBAR copies the backup graph data into the GPE and GSE and notifies the Dictionary to load the configuration data. GBAR also notifies the GST to load backup user data and copy the backup user-defined token/functions to the right location. When these actions are all done, GBAR restarts the TigerGraph servers.
## [](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy#_remove_a_backup)Remove a backup
To remove a backup, run the `gbar remove` command:
```
$ gbar remove <backup_tag>-<timestamp>
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The command removes a backup from the backup storage path. To retrieve the full tag of a backup with the timestamp, use the `gbar list` command.
Please note that the backup tag entered when you create a backup automatically includes a timestamp that is shown in the results of `gbar list`. The `gbar remove` command must use the full tag, including the timestamp.
## [](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy#_clean_up_temporary_files)Clean up temporary files
Run `gbar cleanup` to delete the temporary files created during backup or restore operations:
```
$ gbar cleanup
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

## [](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy#_gbar_detailed_example)GBAR Detailed Example
The following example describes a real example, to show the actual commands, the expected output, and the amount of time and disk space used, for a given set of graph data. For this example, an Amazon EC2 instance was used, with the following specifications:
Single instance with 32 vCPU + 244GB memory + 2TB HDD.
Naturally, backup and restore time will vary depending on the hardware used.
### [](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy#_gbar_backup_operational_details)GBAR Backup Operational Details
To run a daily backup, we tell GBAR to backup with the tag name _daily_.
```
$ gbar backup -t daily
[23:21:46] Retrieve TigerGraph system configuration
[23:21:51] Start workgroup
[23:21:59] Snapshot GPE/GSE data
[23:33:50] Snapshot DICT data
[23:33:50] Calc checksum
[23:37:19] Compress backup data
[23:46:43] Pack backup data
[23:53:18] Put archive daily-20180607232159 to repo-local
[23:53:19] Terminate workgroup
Backup to daily-20180607232159 finished in 31m33s.
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

The total backup process took about 31 minutes, and the generated archive is about 49 GB. Dumping the GPE + GSE data to disk took 12 minutes. Compressing the files took another 20 minutes.
### [](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy#_gbar_restore_operational_details)GBAR Restore Operational Details
To restore from a backup archive, a full archive name needs to be provided, such as _daily-20180607232159_. By default, restore will ask the user to approve to continue. If you want to pre-approve these actions, use the "-y" option. GBAR will make the default choice for you.
```
$ gbar restore daily-20180607232159
[23:57:06] Retrieve TigerGraph system configuration
GBAR restore needs to reset TigerGraph system.
Do you want to continue?(y/N):y
[23:57:13] Start workgroup
[23:57:22] Pull archive daily-20180607232159, round #1
[23:57:57] Pull archive daily-20180607232159, round #2
[00:01:00] Pull archive daily-20180607232159, round #3
[00:01:00] Unpack cluster data
[00:06:39] Decompress backup data
[00:17:32] Verify checksum
[00:18:30] gadmin stop gpe gse
[00:18:36] Snapshot DICT data
[00:18:36] Restore cluster data
[00:18:36] Restore DICT data
[00:18:36] gadmin reset
[00:19:16] gadmin start
[00:19:41] reinstall GSQL queries
[00:19:42] recompiling loading jobs
[00:20:01] Terminate workgroup
Restore from daily-20180607232159 finished in 22m55s.
Old gstore data saved under /home/tigergraph/tigergraph/gstore with suffix -20180608001836, you need to remove them manually.
![copy icon](https://docs.tigergraph.com/_/img/octicons-16.svg#view-clippy)Copied!

```

For our test, GBAR restore took about 23 minutes. Most of the time (20 minutes) was spent decompressing the backup archive.
Note that after the restore is done, GBAR informs you were the pre-restore graph data has been saved. After you have verified that the restore was successful, you may want to delete the old graph data files to free up disk space.
### [](https://docs.tigergraph.com/tigergraph-server/3.9/backup-and-restore/gbar-legacy#_performance_summary_of_example)Performance Summary of Example
GStore size | Backup file size | Backup time | Restore time  
---|---|---|---  
219GB | 49GB | 31 mins | 23 mins  
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


