# SparkLabX

**Building one platform for the entire data lifecycle — on your own infrastructure.**

Our vision: ingestion, processing, orchestration, querying, governance, and
security as a single, coherent, self-hosted workspace — open by design, with no
vendor lock-in. We're building it one production-ready piece at a time.

## Available now

- **[Self-hosted multi-user Spark notebooks](https://github.com/sparklabx/sparklabx)**
  — interactive PySpark + Scala, per-user kernel pods, MinIO IAM storage, OAuth.
  One Helm install. Apache-2.0.

## Where we're headed

The pieces below are in active development — this is the platform we're working
toward, not a description of what ships today:

- **Data Ingestion** — land raw data from any source
- **Workflows & Data Processing** — medallion pipelines (bronze → silver →
  gold) with scheduling, backfill, and run history
- **Query Engine** — ad-hoc SQL over the lakehouse
- **Data Catalog & Governance** — discover, document, and control your data
- **Monitoring & Security Center** — observability and access control across everything

> _Preview of the platform vision (Workflows module — in development):_

![SparkLabX platform preview](https://raw.githubusercontent.com/sparklabx/.github/main/profile/platform.png)

## Principles

- **Self-hosted first** — your data never leaves your infrastructure.
- **Open by default** — Apache Spark, open lakehouse formats, no lock-in.
- **Production-ready** — multi-tenant, per-user isolation, built for real workloads.

🌐 [sparklabx.com](https://sparklabx.com)
