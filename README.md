# Durgaprasad Sunkara

**DevOps / Platform Engineer | Kubernetes | Cloud Infrastructure | CI/CD**

Hamburg, Germany · Open to relocation

DevOps / Platform Engineer with over 3 years of hands-on experience across Skillmine Technology Consulting, Test Yantra and AIcoo GmbH. At AIcoo in Hamburg, I own the DevOps environment for an LLM-based coordinator platform: k3s on Hetzner Cloud, Kubernetes configuration with Kustomize, CI/CD with GitHub Actions and self-hosted runners, secrets management, observability and disaster recovery.

I built the platform from its initial manifests through development and staging deployments. I am completing an MSc in Applied Data Science and Analytics at SRH Hochschule Hamburg (expected March 2027) and writing my master's thesis at AIcoo.

## Engineering focus

- **Containers & orchestration:** Kubernetes (k3s), Docker, Helm, Kustomize, OpenShift
- **Cloud & infrastructure:** AWS, Azure, GCP, Hetzner Cloud, Terraform, IAM
- **CI/CD & GitOps:** GitHub Actions, Jenkins, Argo CD
- **Observability:** Prometheus, Grafana, Loki, Promtail
- **Data & ML infrastructure:** PostgreSQL, pgvector, RAG pipelines
- **Tools:** PowerShell, Jira

## Professional experience

- **DevOps / Platform Engineer — AIcoo GmbH, Hamburg** (April 2026–present)
  - Own the DevOps environment for a coordinator platform with a FastAPI backend, frontend and PostgreSQL on k3s hosted by Hetzner Cloud.
  - Built 28 Kubernetes manifests with Kustomize, including development and staging overlays, Deployments and a PostgreSQL StatefulSet.
  - Built GitHub Actions CI/CD with a self-hosted runner to build images, publish to GHCR, run database migrations and deploy to development and staging.
  - Introduced Sealed Secrets, deployed Prometheus/Grafana/Loki/Promtail, and wrote and tested disaster-recovery procedures.
  - Troubleshoot workload, image-pull, database credential, migration and deployment workflow issues; maintain runbooks and resource conventions.
  - Master's thesis work (since October 2026): a Docker-based MLOps-style pipeline for LLM-based extraction of project emails from the Enron corpus.

- **DevOps Engineer — Skillmine Technology Consulting, Bengaluru** (April 2023–August 2024)
- **Junior DevOps Engineer — Test Yantra, Bengaluru** (November 2021–February 2023; project assignment from June 2022)
- **Software Associate — Tech Mahindra** (March 2020–September 2021)

## Education

**MSc Applied Data Science and Analytics — SRH Hochschule Hamburg**  
Expected completion: March 2027

## Selected projects

### [Kubernetes Incident Remediation for k3s](https://github.com/sunkaradp/k3s-ai-remediation)
Policy-controlled incident diagnosis and remediation using alert context, a local LLM and predefined runbooks. The model recommends an action; policy checks control whether it is observed, requires approval or is eligible to run.

**Focus:** Kubernetes · Prometheus · Alertmanager · Loki · Ollama · FastAPI · RBAC

### [Kubernetes Platform Intelligence](https://github.com/sunkaradp/k8s-platform-intelligence)
A Kubernetes operator experiment that estimates node memory pressure from Prometheus time-series data and emits native Kubernetes warning events. The current implementation is observe-only.

**Focus:** Kubernetes Operators · Prometheus · Python · Custom Resources

### [k3s DevOps Reference](https://github.com/sunkaradp/k3s-devops-reference)
A practical reference covering containerization, k3s deployment, CI/CD, secret handling, observability, database migrations and resource configuration.

**Focus:** Docker · k3s · GitHub Actions · Sealed Secrets · Prometheus · Grafana · Loki · Terraform

### [EV Charging Sessions](https://github.com/sunkaradp/ev-charging-sessions)
A data engineering project exploring ingestion and analytics for EV charging session data.

**Focus:** Kafka · Airflow · BigQuery · Python

## How I approach engineering

- Prefer observable systems with clear operational signals.
- Keep automation bounded by explicit policies and least-privilege access.
- Make infrastructure repeatable and configuration reviewable.
- Document setup steps, trade-offs and known limitations.
- Distinguish tested behavior from planned work and assumptions.

## Current direction

Building deeper practical capability in cloud infrastructure, Kubernetes platforms, GitOps, reliability engineering and cloud-native operations.

## Find me

- GitHub: [@sunkaradp](https://github.com/sunkaradp)
- Portfolio: [sunkaradp.github.io](https://sunkaradp.github.io)

---

*This profile highlights selected personal and learning projects. Project scope and implementation status are documented in each repository.*
