# YugabyteDB (yugabytedb)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

YugabyteDB is a distributed PostgreSQL-compatible SQL database for cloud-native and mission-critical applications. It is delivered as open-source YugabyteDB Core, the fully managed YugabyteDB Aeon DBaaS, and the self-managed YugabyteDB Anywhere control plane, with REST APIs for programmatic management of accounts, projects, clusters, universes, backups, restores, read replicas, allow lists, and maintenance windows.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/yugabytedb/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/yugabytedb/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Cloud Database
- Database
- DBaaS
- Distributed SQL
- PostgreSQL

## Timestamps

- **Created:** 2026-05-03
- **Modified:** 2026-05-19

## APIs

### YugabyteDB Aeon REST API

The YugabyteDB Aeon REST API provides programmatic access to the fully managed YugabyteDB cloud database service. It is used to deploy and manage clusters and read replicas, schedule and run on-demand backups and restores, manage IP allow lists, configure maintenance windows, and set up monitoring and alerts. All paths are scoped to an account and project, and authentication uses API keys passed as bearer tokens in the Authorization header.

- **Human URL:** [https://docs.yugabyte.com/stable/yugabyte-cloud/managed-automation/managed-api/](https://docs.yugabyte.com/stable/yugabyte-cloud/managed-automation/managed-api/)
- **Base URL:** `https://cloud.yugabyte.com/api/public/v1`

#### Tags

- Aeon
- Backups
- Clusters
- DBaaS
- Distributed SQL
- Read Replicas

#### Properties

- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/yugabytedb/refs/heads/main/openapi/yugabytedb-aeon-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://docs.yugabyte.com/stable/yugabyte-cloud/managed-automation/managed-api/)
- [API Reference](https://api-docs.yugabyte.com/docs/managed-apis/)
- [Quickstart](https://docs.yugabyte.com/stable/yugabyte-cloud/managed-automation/managed-api/managed-apikeys/)
- [Authentication](https://docs.yugabyte.com/stable/yugabyte-cloud/managed-automation/managed-api/managed-apikeys/)
- [C L I](https://github.com/yugabyte/ybm-cli)
- [Integrations](https://github.com/yugabyte/terraform-provider-ybm)
- [Terms of Service](https://www.yugabyte.com/yugabytedb-managed-service-terms/)
- [Postman Collection](collections/yugabytedb-aeon.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/yugabytedb-aeon.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### YugabyteDB Anywhere REST API

The YugabyteDB Anywhere REST API enables programmatic management of self-managed YugabyteDB deployments through the YugabyteDB Anywhere (YBA) control plane. It supports creating and managing cloud provider configurations, deploying and managing universes (database clusters), pausing and resuming universes, performing software upgrades, executing backups and restores, and resizing nodes. Authentication is performed via the X-AUTH-YW-API-TOKEN HTTP header.

- **Human URL:** [https://docs.yugabyte.com/stable/yugabyte-platform/anywhere-automation/anywhere-api/](https://docs.yugabyte.com/stable/yugabyte-platform/anywhere-automation/anywhere-api/)
- **Base URL:** `http://{ybaHost}/api/v1`

#### Tags

- Anywhere
- Backups
- Distributed SQL
- Self-Managed
- Universes

#### Properties

- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/yugabytedb/refs/heads/main/openapi/yugabytedb-anywhere-v1-universes.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/yugabytedb/refs/heads/main/openapi/yugabytedb-anywhere-v1-backups-restore.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/yugabytedb/refs/heads/main/openapi/yugabytedb-anywhere-v1-providers-infra.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/yugabytedb/refs/heads/main/openapi/yugabytedb-anywhere-v1-alerts-monitoring.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/yugabytedb/refs/heads/main/openapi/yugabytedb-anywhere-v1-users-rbac.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/yugabytedb/refs/heads/main/openapi/yugabytedb-anywhere-v1-releases-maintenance.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/yugabytedb/refs/heads/main/openapi/yugabytedb-anywhere-v1-high-availability.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/yugabytedb/refs/heads/main/openapi/yugabytedb-anywhere-v2-openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/yugabytedb/refs/heads/main/openapi/yugabytedb-anywhere-v1-full.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://docs.yugabyte.com/stable/yugabyte-platform/anywhere-automation/anywhere-api/)
- [API Reference](https://api-docs.yugabyte.com/docs/yugabyte-platform/)
- [Quickstart](https://docs.yugabyte.com/stable/yugabyte-platform/anywhere-automation/anywhere-api/)
- [Authentication](https://docs.yugabyte.com/stable/yugabyte-platform/anywhere-automation/anywhere-api/)
- [SDK](https://github.com/yugabyte/platform-go-client)
- [Integrations](https://github.com/yugabyte/terraform-provider-yba)
- [Integrations](https://github.com/yugabyte/yugabyte-k8s-operator)
- [Kubernetes C R D](crd/yugabytedb-ybuniverse.yaml)
- [Kubernetes C R D](crd/yugabytedb-backup.yaml)
- [Kubernetes C R D](crd/yugabytedb-backup-schedule.yaml)
- [Kubernetes C R D](crd/yugabytedb-restore-job.yaml)
- [Kubernetes C R D](crd/yugabytedb-storage-config.yaml)
- [Kubernetes C R D](crd/yugabytedb-dr-config.yaml)
- [Kubernetes C R D](crd/yugabytedb-pitr-config.yaml)
- [Kubernetes C R D](crd/yugabytedb-release.yaml)
- [Kubernetes C R D](crd/yugabytedb-support-bundle.yaml)
- [Kubernetes C R D](crd/yugabytedb-ybcertificate.yaml)
- [Kubernetes C R D](crd/yugabytedb-ybprovider.yaml)
- [Kubernetes C R D](crd/yugabytedb-ybplatform.yaml)
- [Terms of Service](https://www.yugabyte.com/yugabytedb-managed-service-terms/)
- [Postman Collection](collections/yugabytedb-aeon.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/yugabytedb-aeon.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [LinkedIn](https://www.linkedin.com/company/yugabyte)
- [Website](https://www.yugabyte.com/)
- [Documentation](https://docs.yugabyte.com/)
- [API Reference](https://api-docs.yugabyte.com/)
- [Quickstart](https://docs.yugabyte.com/stable/quick-start-yugabytedb-managed/)
- [Getting Started](https://docs.yugabyte.com/stable/develop/)
- [Console](https://cloud.yugabyte.com/)
- [Sign Up](https://cloud.yugabyte.com/signup)
- [Login](https://cloud.yugabyte.com/login)
- [Pricing](https://www.yugabyte.com/pricing/)
- [Integrations](https://docs.yugabyte.com/stable/integrations/)
- [Blog](https://www.yugabyte.com/blog/)
- [Terms of Service](https://www.yugabyte.com/yugabytedb-managed-service-terms/)
- [Privacy Policy](https://www.yugabyte.com/privacy-policy/)
- [Status Page](https://status.yugabyte.com/)
- [Support](https://support.yugabyte.com/)
- [Support](https://forum.yugabyte.com/)
- [Release Notes](https://docs.yugabyte.com/stable/releases/)
- [Academy](https://university.yugabyte.com/)
- [GitHub Organization](https://github.com/yugabyte)
- [GitHub Repository](https://github.com/yugabyte/yugabyte-db)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/yugabytedb)
- [YouTube](https://www.youtube.com/c/yugabyte)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/yugabytedb/refs/heads/main/json-schema/yugabytedb-cluster-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/yugabytedb/refs/heads/main/json-ld/yugabytedb-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [SDK](https://github.com/yugabyte/yugabytedb-mcp-server)
- [SDK](https://github.com/yugabyte/yugabytedb-skills)
- [SDK](https://search.maven.org/artifact/com.yugabyte/jdbc-yugabytedb)
- [SDK](https://github.com/yugabyte/pgx)
- [SDK](https://pypi.org/project/django-yugabytedb/)
- [SDK](https://github.com/yugabyte/sqlalchemy-yugabytedb)
- [SDK](https://rubygems.org/gems/activerecord-yugabytedb-adapter)
- [SDK](https://www.npmjs.com/package/sequelize-yugabytedb)
- [SDK](https://github.com/yugabyte/gorm-yugabytedb)
- [SDK](https://github.com/yugabyte/r2dbc-yugabytedb)
- [SDK](https://pypi.org/project/langchain-yugabytedb/)
- [SDK](https://github.com/yugabyte/cassandra-cpp-driver)
- [SDK](https://github.com/yugabyte/cassandra-java-driver)
- [SDK](https://github.com/yugabyte/cassandra-python-driver)
- [SDK](https://github.com/yugabyte/cassandra-nodejs-driver)
- [SDK](https://github.com/yugabyte/cassandra-csharp-driver)
- [SDK](https://github.com/yugabyte/gocql)
- [SDK](https://github.com/yugabyte/spring-data-yugabytedb)
- [C L I](https://github.com/yugabyte/yb-voyager)
- [C L I](https://github.com/yugabyte/cqlsh)
- [Compliance](https://github.com/yugabyte/yuga-bench)
- [GitHub Repository](https://github.com/yugabyte/yugabytedb-pgcompare)
- [GitHub Repository](https://github.com/yugabyte/yugabyte-prometheus-sizing-calculator)
- [GitHub Repository](https://github.com/yugabyte/yb-log-analyzer-py)
- [GitHub Repository](https://github.com/yugabyte/cbo_stat_dump)
- [GitHub Repository](https://github.com/yugabyte/yb-tools)
- [GitHub Repository](https://github.com/yugabyte/yugabyte-db-action)
- [Code Examples](https://github.com/yugabyte/yb-sample-apps)
- [Code Examples](https://github.com/yugabyte/blog-examples)
- [Code Examples](https://github.com/yugabyte/cdc-examples)
- [Code Examples](https://github.com/yugabyte/spring-boot-sample-apps)
- [Code Examples](https://github.com/yugabyte/spring-data-yugabytedb-example)
- [Code Examples](https://github.com/yugabyte/microservices-demo)
- [Code Examples](https://github.com/yugabyte/yugastore)
- [Code Examples](https://github.com/yugabyte/yb-iot-fleet-management)
- [Code Examples](https://github.com/YugabyteDB-Samples/orm-examples)
- [Code Examples](https://github.com/YugabyteDB-Samples/yb-workload-simulator)
- [Tutorials](https://github.com/yugabyte/learn-yugabyte)
- [Tutorials](https://github.com/yugabyte/codelabs)
- [Integrations](https://github.com/yugabyte/debezium-connector-yugabytedb)
- [SDK](https://github.com/yugabyte/charts)
- [SDK](https://github.com/yugabyte/terraform-aws-yugabyte)
- [SDK](https://github.com/yugabyte/terraform-azure-yugabyte)
- [SDK](https://github.com/yugabyte/terraform-gcp-yugabyte)
- [SDK](https://github.com/yugabyte/aws-cloudformation)
- [SDK](https://github.com/yugabyte/azure-resource-manager)
- [SDK](https://github.com/yugabyte/gcp-deployment-manager)
- [SDK](https://github.com/yugabyte/flyway-tests)
- [SDK](https://github.com/yugabyte/hashicorp-vault-ysql-plugin)
- [Integrations](https://github.com/yugabyte/homebrew-tap)
- [GitHub Repository](https://github.com/yugabyte/cloud-resource-cleanup)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)
- [M C P Server](https://github.com/yugabyte/yugabytedb-mcp-server)
- [Agent Skill](https://github.com/yugabyte/yugabytedb-skills)
- [L L Ms Txt](https://docs.yugabyte.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
