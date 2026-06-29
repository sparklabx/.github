# SparkLabX

**One platform for the entire data lifecycle — on your own infrastructure.**

A unified, self-hosted data platform built on Apache Spark and open lakehouse
standards: ingest, process, orchestrate, query, govern, and secure your data
from a single workspace — no SaaS dependency, no vendor lock-in.

![SparkLabX platform](https://raw.githubusercontent.com/sparklabx/.github/main/profile/platform.png)

## The platform

A running, production-grade workspace covering the full data lifecycle:

- **Data Ingestion** — land raw data from any source
- **Workflows & Data Processing** — medallion pipelines (bronze → silver →
  gold) with scheduling, backfill, and run history
- **Notebooks & Query Engine** — interactive PySpark + Scala, ad-hoc SQL
- **Data Catalog & Governance** — discover, document, and control your data
- **Monitoring & Security Center** — observability and access control across everything

## Open source

We're open-sourcing the platform progressively. Available today:

- **[sparklabx](https://github.com/sparklabx/sparklabx)** — Self-hosted,
  multi-user Spark notebooks. Per-user kernel pods, MinIO IAM storage, OAuth.
  One Helm install. Apache-2.0.

The remaining modules run in the platform today; their source is being prepared
for release.

## Principles

- **Self-hosted first** — your data never leaves your infrastructure.
- **Open by default** — Apache Spark, open lakehouse formats, no lock-in.
- **Production-ready** — multi-tenant, per-user isolation, built for real workloads.

🌐 [sparklabx.com](https://sparklabx.com)
