# YugabyteDB Kubernetes CRDs

Custom Resource Definitions (CRDs) used by the YugabyteDB Kubernetes Operator and the YugabyteDB Anywhere (Platform) Operator. These CRDs are the declarative API contract for managing YugabyteDB universes, backups, restores, disaster recovery, and the Anywhere control plane on Kubernetes.

Sources:
- [yugabyte/charts](https://github.com/yugabyte/charts) — `crds/concatenated_crd.yaml` (operator.yugabyte.io group)
- [yugabyte/yugabyte-platform-operator](https://github.com/yugabyte/yugabyte-platform-operator) — `config/crd/bases/yugabyte.com_ybplatforms.yaml`

| Kind | Group | Version | Scope | Fields | File |
|------|-------|---------|-------|--------|------|
| Backup | operator.yugabyte.io | v1alpha1 | Namespaced | 8 | [yugabytedb-backup.yaml](yugabytedb-backup.yaml) |
| BackupSchedule | operator.yugabyte.io | v1alpha1 | Namespaced | 11 | [yugabytedb-backup-schedule.yaml](yugabytedb-backup-schedule.yaml) |
| DrConfig | operator.yugabyte.io | v1alpha1 | Namespaced | 5 | [yugabytedb-dr-config.yaml](yugabytedb-dr-config.yaml) |
| PitrConfig | operator.yugabyte.io | v1alpha1 | Namespaced | 6 | [yugabytedb-pitr-config.yaml](yugabytedb-pitr-config.yaml) |
| Release | operator.yugabyte.io | v1alpha1 | Namespaced | 1 | [yugabytedb-release.yaml](yugabytedb-release.yaml) |
| RestoreJob | operator.yugabyte.io | v1alpha1 | Namespaced | 4 | [yugabytedb-restore-job.yaml](yugabytedb-restore-job.yaml) |
| StorageConfig | operator.yugabyte.io | v1alpha1 | Namespaced | 6 | [yugabytedb-storage-config.yaml](yugabytedb-storage-config.yaml) |
| SupportBundle | operator.yugabyte.io | v1alpha1 | Namespaced | 3 | [yugabytedb-support-bundle.yaml](yugabytedb-support-bundle.yaml) |
| YBCertificate | operator.yugabyte.io | v1alpha1 | Namespaced | 2 | [yugabytedb-ybcertificate.yaml](yugabytedb-ybcertificate.yaml) |
| YBPlatform | yugabyte.com | v1alpha1 | Namespaced | 5 | [yugabytedb-ybplatform.yaml](yugabytedb-ybplatform.yaml) |
| YBProvider | operator.yugabyte.io | v1alpha1 | Namespaced | 2 | [yugabytedb-ybprovider.yaml](yugabytedb-ybprovider.yaml) |
| YBUniverse | operator.yugabyte.io | v1alpha1 | Namespaced | 25 | [yugabytedb-ybuniverse.yaml](yugabytedb-ybuniverse.yaml) |

## Resource Summaries

- **Backup** — On-demand backup of a YugabyteDB universe to a configured storage backend.
- **BackupSchedule** — Recurring scheduled backup policy for a universe.
- **DrConfig** — Disaster recovery (xCluster DR) configuration between universes.
- **PitrConfig** — Point-in-time-recovery configuration for a universe or namespace.
- **Release** — Definition of an installable YugabyteDB software release tracked by the operator.
- **RestoreJob** — Restore operation that materializes a Backup back into a target universe.
- **StorageConfig** — Storage backend (S3, GCS, Azure, NFS) credentials and bucket settings used by Backup/RestoreJob.
- **SupportBundle** — Diagnostic log/event capture for a universe to assist with support escalations.
- **YBCertificate** — Certificate management configuration for a universe (TLS for client/server and node-to-node).
- **YBPlatform** — Top-level Anywhere (YBA) control-plane deployment managed by the YugabyteDB Platform Operator.
- **YBProvider** — Kubernetes provider configuration registered with YBA, used as a target for universe deployment.
- **YBUniverse** — A YugabyteDB universe (database cluster). Primary, most field-rich CRD covering replication factor, node config, storage, gflags, networking, and deployment topology.

## API Group Mapping

| CRD Group | Operator | Maps To |
|---|---|---|
| `operator.yugabyte.io` | YugabyteDB Kubernetes Operator | `yugabytedb:anywhere` |
| `yugabyte.com` | YugabyteDB Platform Operator | `yugabytedb:anywhere` |

Both operators are control-plane components for YugabyteDB Anywhere — they let YBA deploy and manage universes declaratively from Kubernetes manifests rather than through the Anywhere REST API.
