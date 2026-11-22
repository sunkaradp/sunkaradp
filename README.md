# Durgaprasad Sunkara

**DevOps / Platform Engineer | Kubernetes | Cloud Infrastructure | CI/CD**

[![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white)](https://kubernetes.io/) [![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)](https://www.docker.com/) [![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white)](https://aws.amazon.com/) [![Terraform](https://img.shields.io/badge/Terraform-844FBA?logo=terraform&logoColor=white)](https://www.terraform.io/) [![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)](https://www.python.org/) [![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)](https://github.com/features/actions)

**Live project CI:** [k3s-ai-remediation](https://github.com/sunkaradp/k3s-ai-remediation/actions/workflows/ci.yml) · [k8s-platform-intelligence](https://github.com/sunkaradp/k8s-platform-intelligence/actions/workflows/ci.yml)

## Featured platform engineering work

### [Kubernetes Incident Remediation for k3s](https://github.com/sunkaradp/k3s-ai-remediation)
Policy-gated incident response prototype: Alertmanager webhook, Kubernetes/Loki context, rules and local-LLM diagnosis, risk-based policy decisions, and predefined runbooks. Defaults to OBSERVE and dry-run; medium-risk actions require approval.

**Evidence:** automated tests, linting, Kubernetes manifest validation, Terraform validation and container image checks in CI.

### [Kubernetes Platform Intelligence](https://github.com/sunkaradp/k8s-platform-intelligence)
Observe-only Kubernetes operator experiment that estimates node memory pressure from Prometheus time-series data and emits native Kubernetes Warning Events.

**Evidence:** CRD schema, Helm chart, scoped RBAC, hardened workload configuration and automated tests.

### [EV Charging Sessions](https://github.com/sunkaradp/ev-charging-sessions)
Team data-engineering project covering Kafka event ingestion, Airflow batch transformations and analytics. My documented recent contributions include Kafka producer reliability, batch transformation tests and Python CI.


Hamburg, Germany · Open to relocation across Germany and Europe

DevOps / Platform Engineer with 3+ years of experience across cloud infrastructure, automation and application delivery. My recent hands-on work includes building and operating Kubernetes-based environments on Hetzner Cloud, implementing CI/CD with GitHub Actions and self-hosted runners, managing application configuration and secrets, and establishing monitoring and recovery procedures.

I completed an MLOps / DevOps internship at AIcoo GmbH in Hamburg (April–September 2026). Since October 2026, I have been working on my MSc thesis with AIcoo while completing an MSc in Applied Data Science and Analytics at SRH Hochschule Hamburg (expected March 2027).

## Engineering focus

- **Containers & orchestration:** Kubernetes (k3s), Docker, Helm, Kustomize
- **Cloud & infrastructure:** Hetzner Cloud, Terraform, IAM, GCP (project work)
- **CI/CD & GitOps:** GitHub Actions, Argo CD, GHCR
- **Observability & reliability:** Prometheus, Grafana, Loki, Promtail
- **Data & application infrastructure:** PostgreSQL, Kafka, Airflow, Python
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
