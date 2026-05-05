# YugabyteDB (yugabytedb)
YugabyteDB is a distributed PostgreSQL-compatible SQL database for cloud-native and mission-critical applications. It is delivered as open-source YugabyteDB Core, the fully managed YugabyteDB Aeon DBaaS, and the self-managed YugabyteDB Anywhere control plane, with REST APIs for programmatic management of accounts, projects, clusters, universes, backups, restores, read replicas, allow lists, and maintenance windows.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/yugabytedb/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Cloud Database, Database, DBaaS, Distributed SQL, PostgreSQL

## Timestamps

- **Created:** 2026-05-03
- **Modified:** 2026-05-03

## APIs

### YugabyteDB Aeon REST API
The YugabyteDB Aeon REST API provides programmatic access to the fully managed YugabyteDB cloud database service. It is used to deploy and manage clusters and read replicas, schedule and run on-demand backups and restores, manage IP allow lists, configure maintenance windows, and set up monitoring and alerts. All paths are scoped to an account and project, and authentication uses API keys passed as bearer tokens in the Authorization header.

**Human URL:** [https://docs.yugabyte.com/stable/yugabyte-cloud/managed-automation/managed-api/](https://docs.yugabyte.com/stable/yugabyte-cloud/managed-automation/managed-api/)

#### Tags:

 - Aeon, Backups, Clusters, DBaaS, Distributed SQL, Read Replicas

#### Properties

- [OpenAPI](openapi/yugabytedb-aeon-openapi.yml)
- [Documentation](https://docs.yugabyte.com/stable/yugabyte-cloud/managed-automation/managed-api/)
- [APIReference](https://api-docs.yugabyte.com/docs/managed-apis/)
- [Quickstart](https://docs.yugabyte.com/stable/yugabyte-cloud/managed-automation/managed-api/managed-apikeys/)
- [Authentication](https://docs.yugabyte.com/stable/yugabyte-cloud/managed-automation/managed-api/managed-apikeys/)
- [CLI — YugabyteDB Aeon CLI (ybm)](https://github.com/yugabyte/ybm-cli)
- [Integrations — Terraform Provider for YugabyteDB Aeon](https://github.com/yugabyte/terraform-provider-ybm)
- [TermsOfService](https://www.yugabyte.com/yugabytedb-managed-service-terms/)

### YugabyteDB Anywhere REST API
The YugabyteDB Anywhere REST API enables programmatic management of self-managed YugabyteDB deployments through the YugabyteDB Anywhere (YBA) control plane. It supports creating and managing cloud provider configurations, deploying and managing universes (database clusters), pausing and resuming universes, performing software upgrades, executing backups and restores, and resizing nodes. Authentication is performed via the X-AUTH-YW-API-TOKEN HTTP header.

**Human URL:** [https://docs.yugabyte.com/stable/yugabyte-platform/anywhere-automation/anywhere-api/](https://docs.yugabyte.com/stable/yugabyte-platform/anywhere-automation/anywhere-api/)

#### Tags:

 - Anywhere, Backups, Distributed SQL, Self-Managed, Universes

#### Properties

- [OpenAPI — Anywhere v1 — Universe Management](openapi/yugabytedb-anywhere-v1-universes.yaml)
- [OpenAPI — Anywhere v1 — Backups, Restores, and Replication](openapi/yugabytedb-anywhere-v1-backups-restore.yaml)
- [OpenAPI — Anywhere v1 — Providers and Infrastructure](openapi/yugabytedb-anywhere-v1-providers-infra.yaml)
- [OpenAPI — Anywhere v1 — Alerts and Monitoring](openapi/yugabytedb-anywhere-v1-alerts-monitoring.yaml)
- [OpenAPI — Anywhere v1 — Users, Sessions, and RBAC](openapi/yugabytedb-anywhere-v1-users-rbac.yaml)
- [OpenAPI — Anywhere v1 — Releases and Maintenance](openapi/yugabytedb-anywhere-v1-releases-maintenance.yaml)
- [OpenAPI — Anywhere v1 — High Availability](openapi/yugabytedb-anywhere-v1-high-availability.yaml)
- [OpenAPI — Anywhere v2 — Improved API](openapi/yugabytedb-anywhere-v2-openapi.yaml)
- [OpenAPI — Anywhere v1 — Full Monolithic Spec (reference)](openapi/yugabytedb-anywhere-v1-full.yaml)
- [Documentation](https://docs.yugabyte.com/stable/yugabyte-platform/anywhere-automation/anywhere-api/)
- [APIReference](https://api-docs.yugabyte.com/docs/yugabyte-platform/)
- [Quickstart](https://docs.yugabyte.com/stable/yugabyte-platform/anywhere-automation/anywhere-api/)
- [Authentication](https://docs.yugabyte.com/stable/yugabyte-platform/anywhere-automation/anywhere-api/)
- [SDK — YugabyteDB Anywhere Go API Client](https://github.com/yugabyte/platform-go-client)
- [Integrations — Terraform Provider for YugabyteDB Anywhere](https://github.com/yugabyte/terraform-provider-yba)
- [Integrations — YugabyteDB Kubernetes Operator](https://github.com/yugabyte/yugabyte-k8s-operator)
- [KubernetesCRD — YBUniverse CRD](crd/yugabytedb-ybuniverse.yaml)
- [KubernetesCRD — Backup CRD](crd/yugabytedb-backup.yaml)
- [KubernetesCRD — BackupSchedule CRD](crd/yugabytedb-backup-schedule.yaml)
- [KubernetesCRD — RestoreJob CRD](crd/yugabytedb-restore-job.yaml)
- [KubernetesCRD — StorageConfig CRD](crd/yugabytedb-storage-config.yaml)
- [KubernetesCRD — DrConfig CRD](crd/yugabytedb-dr-config.yaml)
- [KubernetesCRD — PitrConfig CRD](crd/yugabytedb-pitr-config.yaml)
- [KubernetesCRD — Release CRD](crd/yugabytedb-release.yaml)
- [KubernetesCRD — SupportBundle CRD](crd/yugabytedb-support-bundle.yaml)
- [KubernetesCRD — YBCertificate CRD](crd/yugabytedb-ybcertificate.yaml)
- [KubernetesCRD — YBProvider CRD](crd/yugabytedb-ybprovider.yaml)
- [KubernetesCRD — YBPlatform CRD](crd/yugabytedb-ybplatform.yaml)
- [TermsOfService](https://www.yugabyte.com/yugabytedb-managed-service-terms/)

## Common Properties

- [Website](https://www.yugabyte.com/)
- [Documentation](https://docs.yugabyte.com/)
- [APIReference](https://api-docs.yugabyte.com/)
- [Quickstart](https://docs.yugabyte.com/stable/quick-start-yugabytedb-managed/)
- [GettingStarted](https://docs.yugabyte.com/stable/develop/)
- [Console](https://cloud.yugabyte.com/)
- [SignUp](https://cloud.yugabyte.com/signup)
- [Login](https://cloud.yugabyte.com/login)
- [Pricing](https://www.yugabyte.com/pricing/)
- [Integrations](https://docs.yugabyte.com/stable/integrations/)
- [Blog](https://www.yugabyte.com/blog/)
- [TermsOfService](https://www.yugabyte.com/yugabytedb-managed-service-terms/)
- [PrivacyPolicy](https://www.yugabyte.com/privacy-policy/)
- [StatusPage](https://status.yugabyte.com/)
- [Support](https://support.yugabyte.com/)
- [Support](https://forum.yugabyte.com/)
- [ReleaseNotes](https://docs.yugabyte.com/stable/releases/)
- [Academy](https://university.yugabyte.com/)
- [GitHubOrganization](https://github.com/yugabyte)
- [GitHubRepository](https://github.com/yugabyte/yugabyte-db)
- [StackOverflow](https://stackoverflow.com/questions/tagged/yugabytedb)
- [YouTube](https://www.youtube.com/c/yugabyte)
- [JSONSchema](json-schema/yugabytedb-cluster-schema.json)
- [JSON-LD](json-ld/yugabytedb-context.jsonld)
- [SDK — MCP Server](https://github.com/yugabyte/yugabytedb-mcp-server)
- [SDK — AI Agent Skills](https://github.com/yugabyte/yugabytedb-skills)
- [SDK — Java YSQL Smart Driver](https://search.maven.org/artifact/com.yugabyte/jdbc-yugabytedb)
- [SDK — Go YSQL Smart Driver](https://github.com/yugabyte/pgx)
- [SDK — Python Django Backend](https://pypi.org/project/django-yugabytedb/)
- [SDK — Python SQLAlchemy Dialect](https://github.com/yugabyte/sqlalchemy-yugabytedb)
- [SDK — Ruby ActiveRecord Adapter](https://rubygems.org/gems/activerecord-yugabytedb-adapter)
- [SDK — Node.js Sequelize Package](https://www.npmjs.com/package/sequelize-yugabytedb)
- [SDK — Go GORM Driver](https://github.com/yugabyte/gorm-yugabytedb)
- [SDK — Java R2DBC YSQL Driver](https://github.com/yugabyte/r2dbc-yugabytedb)
- [SDK — Python LangChain Integration](https://pypi.org/project/langchain-yugabytedb/)
- [SDK — C++ YCQL Driver](https://github.com/yugabyte/cassandra-cpp-driver)
- [SDK — Java YCQL Driver](https://github.com/yugabyte/cassandra-java-driver)
- [SDK — Python YCQL Driver](https://github.com/yugabyte/cassandra-python-driver)
- [SDK — Node.js YCQL Driver](https://github.com/yugabyte/cassandra-nodejs-driver)
- [SDK — C# YCQL Driver](https://github.com/yugabyte/cassandra-csharp-driver)
- [SDK — Go YCQL Driver](https://github.com/yugabyte/gocql)
- [SDK — Java Spring Data Module](https://github.com/yugabyte/spring-data-yugabytedb)
- [CLI — Database Migration Tool (yb-voyager)](https://github.com/yugabyte/yb-voyager)
- [CLI — YCQL Shell (cqlsh)](https://github.com/yugabyte/cqlsh)
- [Compliance](https://github.com/yugabyte/yuga-bench)
- [GitHubRepository](https://github.com/yugabyte/yugabytedb-pgcompare)
- [GitHubRepository](https://github.com/yugabyte/yugabyte-prometheus-sizing-calculator)
- [GitHubRepository](https://github.com/yugabyte/yb-log-analyzer-py)
- [GitHubRepository](https://github.com/yugabyte/cbo_stat_dump)
- [GitHubRepository](https://github.com/yugabyte/yb-tools)
- [GitHubRepository](https://github.com/yugabyte/yugabyte-db-action)
- [CodeExamples — Workload Generator (Java)](https://github.com/yugabyte/yb-sample-apps)
- [CodeExamples — Blog Demonstrations](https://github.com/yugabyte/blog-examples)
- [CodeExamples — CDC Connector Examples](https://github.com/yugabyte/cdc-examples)
- [CodeExamples — Spring Boot Samples](https://github.com/yugabyte/spring-boot-sample-apps)
- [CodeExamples — Spring Data Sample](https://github.com/yugabyte/spring-data-yugabytedb-example)
- [CodeExamples — Microservices Demo (Hipster Shop fork)](https://github.com/yugabyte/microservices-demo)
- [CodeExamples — Yugastore E-Commerce App](https://github.com/yugabyte/yugastore)
- [CodeExamples — IoT Fleet Management Sample](https://github.com/yugabyte/yb-iot-fleet-management)
- [CodeExamples — ORM Examples](https://github.com/YugabyteDB-Samples/orm-examples)
- [CodeExamples — Workload Simulator](https://github.com/YugabyteDB-Samples/yb-workload-simulator)
- [Tutorials — Distributed SQL Lessons](https://github.com/yugabyte/learn-yugabyte)
- [Tutorials — Code Labs](https://github.com/yugabyte/codelabs)
- [Integrations — Debezium CDC Connector](https://github.com/yugabyte/debezium-connector-yugabytedb)
- [Integrations — Helm Charts](https://github.com/yugabyte/charts)
- [Integrations — Terraform AWS Module](https://github.com/yugabyte/terraform-aws-yugabyte)
- [Integrations — Terraform Azure Module](https://github.com/yugabyte/terraform-azure-yugabyte)
- [Integrations — Terraform GCP Module](https://github.com/yugabyte/terraform-gcp-yugabyte)
- [Integrations — AWS CloudFormation Template](https://github.com/yugabyte/aws-cloudformation)
- [Integrations — Azure Resource Manager Template](https://github.com/yugabyte/azure-resource-manager)
- [Integrations — GCP Deployment Manager](https://github.com/yugabyte/gcp-deployment-manager)
- [Integrations — Flyway Plugin](https://github.com/yugabyte/flyway-tests)
- [Integrations — HashiCorp Vault Plugin](https://github.com/yugabyte/hashicorp-vault-ysql-plugin)
- [Integrations — Homebrew Tap](https://github.com/yugabyte/homebrew-tap)
- [GitHubRepository](https://github.com/yugabyte/cloud-resource-cleanup)

## Features

| Name | Description |
|------|-------------|
| PostgreSQL Compatibility | Wire-compatible YSQL API supporting PostgreSQL drivers, ORMs, stored procedures, triggers, and extensions. |
| Distributed SQL | ACID transactions, automatic sharding, and horizontal scaling across nodes, zones, and regions. |
| Multi-Region Deployments | Geo-distributed clusters with synchronous and asynchronous replication for disaster recovery and data residency. |
| Cloud Database as a Service | Fully managed YugabyteDB Aeon clusters across AWS, Azure, and Google Cloud regions. |
| Self-Managed Control Plane | YugabyteDB Anywhere for deploying and operating universes on customer infrastructure and Kubernetes. |
| Backups and Restores | On-demand and scheduled backups, point-in-time recovery, and cross-region restore. |
| Read Replicas | Asynchronous read replicas for low-latency reads in additional regions. |
| Vector Indexing | Vector search capabilities for retrieval-augmented generation (RAG) and GenAI workloads. |
| YCQL API | Cassandra-compatible API for wide-column workloads alongside the PostgreSQL-compatible YSQL API. |
| Connection Management | Built-in connection pooling and load balancing for distributed workloads. |

## Use Cases

| Name | Description |
|------|-------------|
| Database Modernization | Replace legacy monolithic RDBMS systems with a horizontally scalable, PostgreSQL-compatible alternative. |
| Cloud-Native Applications | Power Kubernetes-deployed and microservices applications with a resilient distributed SQL backend. |
| Multi-Region SaaS | Operate global SaaS platforms with low-latency reads and disaster-recovery-ready writes. |
| Financial Services | Run mission-critical transaction systems requiring strong consistency and high availability. |
| Retail and eCommerce | Handle high-throughput product catalogs, inventory, and orders across regions. |
| Telecommunications | Support subscriber, billing, and session data at carrier scale. |
| GenAI and RAG | Store embeddings and metadata for retrieval-augmented generation pipelines. |
| Edge and Streaming | Provide a durable distributed SQL store for edge and streaming application data. |

## Integrations

| Name | Description |
|------|-------------|
| Kubernetes | Helm charts and a Kubernetes Operator for deploying YugabyteDB on Kubernetes clusters. |
| Terraform | Terraform Provider for YugabyteDB Anywhere for infrastructure-as-code management of universes. |
| YugabyteDB Voyager | Open-source migration tool for moving schema and data from PostgreSQL, Oracle, and MySQL to YugabyteDB. |
| AWS, Azure, and Google Cloud | Native deployment targets for YugabyteDB Aeon and Anywhere across major public clouds. |
| PostgreSQL Drivers and ORMs | Compatibility with standard PostgreSQL drivers, ORMs, and tooling via the YSQL API. |
| REST API | Bearer-token authenticated REST APIs for both Aeon and Anywhere control planes. |

## Solutions

| Name | Description |
|------|-------------|
| YugabyteDB Core | Open-source distributed SQL database available under the Apache 2.0 license. |
| YugabyteDB Aeon | Fully managed cloud database service operated by Yugabyte. |
| YugabyteDB Anywhere | Self-managed control plane for operating YugabyteDB universes on customer infrastructure. |
| YugabyteDB Voyager | Database migration service and tooling for moving to YugabyteDB. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [YugabyteDB Aeon REST API](openapi/yugabytedb-aeon-openapi.yml)
- [YugabyteDB Anywhere v1 — Universe Management](openapi/yugabytedb-anywhere-v1-universes.yaml)
- [YugabyteDB Anywhere v1 — Backups, Restores, and Replication](openapi/yugabytedb-anywhere-v1-backups-restore.yaml)
- [YugabyteDB Anywhere v1 — Providers and Infrastructure](openapi/yugabytedb-anywhere-v1-providers-infra.yaml)
- [YugabyteDB Anywhere v1 — Alerts and Monitoring](openapi/yugabytedb-anywhere-v1-alerts-monitoring.yaml)
- [YugabyteDB Anywhere v1 — Users, Sessions, and RBAC](openapi/yugabytedb-anywhere-v1-users-rbac.yaml)
- [YugabyteDB Anywhere v1 — Releases and Maintenance](openapi/yugabytedb-anywhere-v1-releases-maintenance.yaml)
- [YugabyteDB Anywhere v1 — High Availability](openapi/yugabytedb-anywhere-v1-high-availability.yaml)
- [YugabyteDB Anywhere v2 — Improved API](openapi/yugabytedb-anywhere-v2-openapi.yaml)
- [YugabyteDB Anywhere v1 — Full Monolithic Spec (reference)](openapi/yugabytedb-anywhere-v1-full.yaml)

### JSON Schema

- [YugabyteDB Cluster Schema](json-schema/yugabytedb-cluster-schema.json)

### JSON-LD

- [YugabyteDB Context](json-ld/yugabytedb-context.jsonld)

## Kubernetes CRDs

Kubernetes Custom Resource Definitions defining the declarative API surface.

| Kind | Group | Version | Scope | File |
|------|-------|---------|-------|------|
| YBUniverse | operator.yugabyte.io | v1alpha1 | Namespaced | [yugabytedb-ybuniverse.yaml](crd/yugabytedb-ybuniverse.yaml) |
| Backup | operator.yugabyte.io | v1alpha1 | Namespaced | [yugabytedb-backup.yaml](crd/yugabytedb-backup.yaml) |
| BackupSchedule | operator.yugabyte.io | v1alpha1 | Namespaced | [yugabytedb-backup-schedule.yaml](crd/yugabytedb-backup-schedule.yaml) |
| RestoreJob | operator.yugabyte.io | v1alpha1 | Namespaced | [yugabytedb-restore-job.yaml](crd/yugabytedb-restore-job.yaml) |
| StorageConfig | operator.yugabyte.io | v1alpha1 | Namespaced | [yugabytedb-storage-config.yaml](crd/yugabytedb-storage-config.yaml) |
| DrConfig | operator.yugabyte.io | v1alpha1 | Namespaced | [yugabytedb-dr-config.yaml](crd/yugabytedb-dr-config.yaml) |
| PitrConfig | operator.yugabyte.io | v1alpha1 | Namespaced | [yugabytedb-pitr-config.yaml](crd/yugabytedb-pitr-config.yaml) |
| Release | operator.yugabyte.io | v1alpha1 | Namespaced | [yugabytedb-release.yaml](crd/yugabytedb-release.yaml) |
| SupportBundle | operator.yugabyte.io | v1alpha1 | Namespaced | [yugabytedb-support-bundle.yaml](crd/yugabytedb-support-bundle.yaml) |
| YBCertificate | operator.yugabyte.io | v1alpha1 | Namespaced | [yugabytedb-ybcertificate.yaml](crd/yugabytedb-ybcertificate.yaml) |
| YBProvider | operator.yugabyte.io | v1alpha1 | Namespaced | [yugabytedb-ybprovider.yaml](crd/yugabytedb-ybprovider.yaml) |
| YBPlatform | yugabyte.com | v1alpha1 | Namespaced | [yugabytedb-ybplatform.yaml](crd/yugabytedb-ybplatform.yaml) |

## Rules

- [YugabyteDB Spectral Rules](rules/yugabytedb-spectral-rules.yml) — 67 rules across 13 categories enforcing YugabyteDB Aeon and Anywhere API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
