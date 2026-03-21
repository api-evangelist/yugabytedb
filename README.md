# YugabyteDB (yugabytedb)
YugabyteDB is an open-source, high-performance distributed SQL database built for cloud-native applications. It offers full PostgreSQL compatibility through its YSQL API and Cassandra-compatible access through its YCQL API, with support for horizontal scalability, distributed ACID transactions, and multi-region deployments. The developer platform provides REST APIs for managing both the fully managed Aeon cloud service and self-hosted deployments via YugabyteDB Anywhere.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/yugabytedb/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Database, Distributed SQL, Cloud, PostgreSQL, Cassandra, NoSQL, REST

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-03-21

## APIs

### YugabyteDB Aeon REST API
The YugabyteDB Aeon REST API provides programmatic access to YugabyteDB's fully managed cloud database service. Developers and operators can use it to deploy and manage database clusters, configure read replicas, schedule and execute on-demand backups and restores, and set up monitoring and alerts. The API supports automation workflows alongside the Terraform Provider and ybm CLI, enabling infrastructure-as-code patterns for managing cloud database deployments. Authentication is performed using API keys passed as bearer tokens in request headers.

**Human URL:** [https://docs.yugabyte.com/stable/yugabyte-cloud/managed-automation/managed-api/](https://docs.yugabyte.com/stable/yugabyte-cloud/managed-automation/managed-api/)


#### Tags:

 - Database, Cloud, Distributed SQL, Cluster Management, REST

#### Properties

- [Documentation](https://docs.yugabyte.com/stable/yugabyte-cloud/managed-automation/managed-api/)
- [Documentation](https://api-docs.yugabyte.com/docs/managed-apis/9u5yqnccbe8lk-yugabyte-db-aeon-rest-api)
- [OpenAPI](openapi/yugabytedb-aeon-openapi.yml)

### YugabyteDB Anywhere REST API
The YugabyteDB Anywhere REST API enables programmatic management of self-managed YugabyteDB deployments through the YugabyteDB Anywhere (formerly Yugabyte Platform) control plane. It supports creating and managing provider configurations, deploying and managing universes, pausing and resuming universes, performing software upgrades, executing backups and restores, and resizing nodes. The API base URL follows the pattern http://<yba_host>/api/v1/ and requires authentication via the X-AUTH-YW-API-TOKEN HTTP header. This API is intended for teams running YugabyteDB on their own cloud or on-premises infrastructure who need automation beyond what the UI provides.

**Human URL:** [https://docs.yugabyte.com/stable/yugabyte-platform/anywhere-automation/anywhere-api/](https://docs.yugabyte.com/stable/yugabyte-platform/anywhere-automation/anywhere-api/)


#### Tags:

 - Database, Self-Managed, Distributed SQL, Universe Management, REST

#### Properties

- [Documentation](https://docs.yugabyte.com/stable/yugabyte-platform/anywhere-automation/anywhere-api/)
- [Documentation](https://api-docs.yugabyte.com/docs/yugabyte-platform/6e6672ea4b926-yugabyte-db-anywhere-ap-is)
- [OpenAPI](openapi/yugabytedb-anywhere-openapi.yml)

### YugabyteDB YSQL API
YSQL (Yugabyte Structured Query Language) is YugabyteDB's fully relational SQL API that is wire-compatible with PostgreSQL. It is designed for RDBMS workloads that require horizontal write scalability and globally distributed ACID transactions while retaining relational features such as JOINs, foreign keys, and secondary indexes. Applications connect to YSQL using standard PostgreSQL client libraries and drivers over port 5433. The API supports the broad PostgreSQL syntax and semantics, making it straightforward to migrate existing PostgreSQL workloads to a distributed database environment.

**Human URL:** [https://docs.yugabyte.com/stable/api/ysql/](https://docs.yugabyte.com/stable/api/ysql/)


#### Tags:

 - Database, SQL, PostgreSQL, Distributed SQL, Query Language

#### Properties

- [Documentation](https://docs.yugabyte.com/stable/api/ysql/)

### YugabyteDB YCQL API
YCQL (Yugabyte Cloud Query Language) is YugabyteDB's semi-relational SQL API with roots in Apache Cassandra Query Language. It is designed for internet-scale OLTP and HTAP applications that demand rapid data ingestion, multi-shard distributed transactions, and low-latency reads. YCQL includes native JSON column support and connects over port 9042 using CQL-compatible drivers. Applications previously built on Apache Cassandra can migrate to YCQL to benefit from YugabyteDB's distributed transaction semantics and consistent replication model while retaining familiar query patterns.

**Human URL:** [https://docs.yugabyte.com/stable/api/ycql/](https://docs.yugabyte.com/stable/api/ycql/)


#### Tags:

 - Database, Cassandra, NoSQL, Distributed SQL, Query Language

#### Properties

- [Documentation](https://docs.yugabyte.com/stable/api/ycql/)

## Common Properties

- [Portal](https://docs.yugabyte.com/)
- [Documentation](https://docs.yugabyte.com/)
- [Website](https://www.yugabyte.com/)
- [PrivacyPolicy](https://www.yugabyte.com/privacy-policy/)
- [TermsOfService](https://www.yugabyte.com/terms-of-service/)
- [Support](https://support.yugabyte.com/)
- [Blog](https://www.yugabyte.com/blog/)
- [Login](https://cloud.yugabyte.com/login)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
