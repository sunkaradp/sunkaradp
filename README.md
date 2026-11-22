# Durgaprasad Sunkara

**DevOps / Platform Engineer | Kubernetes | Cloud Infrastructure | CI/CD**

Hamburg, Germany · Open to relocation across Germany and Europe

DevOps / Platform Engineer with 3+ years of experience across cloud infrastructure, automation and application delivery. My recent hands-on work includes building and operating Kubernetes-based environments on Hetzner Cloud, implementing CI/CD with GitHub Actions and self-hosted runners, managing application configuration and secrets, and establishing monitoring and recovery procedures.

I completed an MLOps / DevOps internship at AIcoo GmbH in Hamburg (April–September 2026). Since October 2026, I have been working on my MSc thesis with AIcoo while completing an MSc in Applied Data Science and Analytics at SRH Hochschule Hamburg (expected March 2027).

## Engineering focus

- **Containers & orchestration:** Kubernetes (k3s), Docker, Helm, Kustomize, OpenShift
- **Cloud & infrastructure:** AWS, Azure, GCP, Hetzner Cloud, Terraform, IAM
- **CI/CD & GitOps:** GitHub Actions, Jenkins, Argo CD, GHCR
- **Observability & reliability:** Prometheus, Grafana, Loki, Promtail, disaster recovery
- **Data & ML infrastructure:** PostgreSQL, pgvector, Python, RAG pipelines
- **Operating practices:** Linux, troubleshooting, runbooks, least-privilege access

## Professional experience

### MLOps / DevOps Intern — AIcoo GmbH, Hamburg
**April 2026 – September 2026**

- Built and maintained Kubernetes configuration for a coordinator platform with a FastAPI backend, frontend and PostgreSQL on k3s hosted by Hetzner Cloud.
- Created 28 Kubernetes manifests with Kustomize, including development and staging overlays, Deployments and a PostgreSQL StatefulSet.
- Implemented GitHub Actions CI/CD with a self-hosted runner to build container images, publish to GHCR, run database migrations and deploy to development and staging.
- Worked on secrets management, Prometheus/Grafana/Loki/Promtail observability, operational runbooks and disaster-recovery procedures.
- Investigated workload, image-pull, database credential, migration and deployment workflow issues.

### Master's Thesis — AIcoo GmbH / SRH Hochschule Hamburg
**October 2026 – Present**

Research and implementation of a Docker-based pipeline for LLM-assisted extraction and analysis of project-related emails from the Enron corpus. The work includes data processing, evaluation and reproducibility; thesis materials and implementation details are maintained separately.

### Previous experience

- **DevOps Engineer — Skillmine Technology Consulting, Bengaluru** (April 2023 – August 2024)
- **Junior DevOps Engineer — Test Yantra, Bengaluru** (November 2021 – February 2023; project assignment from June 2022)
- **Software Associate — Tech Mahindra** (March 2020 – September 2021)

## Education

**MSc Applied Data Science and Analytics — SRH Hochschule Hamburg**  
Expected completion: March 2027

## Selected engineering projects

### [Kubernetes Incident Remediation for k3s](https://github.com/sunkaradp/k3s-ai-remediation)
A policy-controlled Kubernetes incident response prototype connecting alert context, diagnosis and predefined runbooks. Recommendations are constrained by explicit policy modes, risk levels and safe defaults.

**Technologies:** Kubernetes, Prometheus, Alertmanager, Loki, FastAPI, Python, RBAC, Argo CD, Terraform

### [Kubernetes Platform Intelligence](https://github.com/sunkaradp/k8s-platform-intelligence)
An observe-only Kubernetes operator experiment that estimates node memory pressure from Prometheus time-series data and emits native Kubernetes Warning Events.

**Technologies:** Kubernetes Operators, Custom Resources, Prometheus, Python, Helm

### [k3s DevOps Reference](https://github.com/sunkaradp/k3s-devops-reference)
A practical implementation reference covering containerization, k3s deployment, CI/CD, secret handling, observability, database migrations and resource configuration.

**Technologies:** Docker, k3s, GitHub Actions, Sealed Secrets, Prometheus, Grafana, Loki, Terraform

### [EV Charging Sessions](https://github.com/sunkaradp/ev-charging-sessions)
A data engineering project exploring event ingestion, orchestration and analytics for EV charging sessions.

**Technologies:** Kafka, Airflow, Python, BigQuery

## Engineering principles

- Build repeatable infrastructure and reviewable deployment workflows.
- Prefer observable systems with clear operational signals.
- Keep automation bounded by explicit policy and least-privilege access.
- Document setup, operational procedures, trade-offs and known limitations.
- Separate verified results from assumptions and planned work.

## Links

- GitHub: [@sunkaradp](https://github.com/sunkaradp)
- Portfolio: [sunkaradp.github.io](https://sunkaradp.github.io)
- LinkedIn: [linkedin.com/in/dpcloud](https://www.linkedin.com/in/dpcloud)

---

*This profile highlights selected work. Each project README describes its implementation scope, verification status and limitations.*
