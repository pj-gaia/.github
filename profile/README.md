# Project Gaia

> A unified software lifecycle and compliance platform — bringing OSS tools out of their silos.

## What is Project Gaia?

Project Gaia is an open, Kubernetes-native toolsuite that connects best-in-class OSS applications into a single, coherent engineering and compliance platform.

The goal is simple: **product managers should be able to audit a release without chasing information across five different tools, and engineers should have one authoritative source of truth for their quality gates.**

---

## Who is it for?

| Role | What Gaia gives you |
|---|---|
| **Product Manager** | A consolidated release audit view — quality gates, compliance status, and risk indicators in one place |
| **Engineer** | A single entry point for SBOM reviews, policy checks, and dependency vulnerability status |
| **Security / Compliance** | Traceable artefacts from code to release, with policies version-controlled alongside the product |

---

## Platform Components

| Component | Technology | Purpose |
|---|---|---|
| Policy & Content Management | [Strapi](https://strapi.io) | Version-controlled policies, risk assessments (TARA), and compliance metadata |
| SBOM & Dependency Analysis | [Dependency-Track](https://dependencytrack.org) | Software Bill of Materials ingestion, vulnerability tracking, and licence compliance |
| _More integrations planned_ | | The platform is designed to grow — additional OSS tools will be integrated as the PoC matures |

---

## Architecture

Architecture documentation follows the [arc42](https://arc42.org) template and is maintained in the [`architecture`](https://github.com/pj-gaia/architecture) repository.

---

## Repositories

| Repository | Description |
|---|---|
| [`architecture`](https://github.com/pj-gaia/architecture) | arc42 architecture documentation (AsciiDoc) |
| [`helm`](https://github.com/pj-gaia/helm) | Helm charts for Kubernetes deployment |

---

## Status

> **Proof of Concept** — Project Gaia is under active development. APIs, integration contracts, and deployment structures are subject to change.

Contributions, issues, and discussions are welcome in the respective repositories.
