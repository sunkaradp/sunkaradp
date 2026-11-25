# Durgaprasad Sunkara

**DevOps Engineer | Platform Engineering | Kubernetes | Cloud Infrastructure**

I build and operate cloud-native infrastructure, Kubernetes platforms and automated delivery workflows. My focus is reliable deployments, practical automation, observability, secure operations and clear engineering documentation.

Hamburg, Germany · Open to DevOps, Platform and Cloud Engineering roles across Germany and Europe · Open to relocation

**Core stack:** Kubernetes · Docker · Terraform · AWS · Hetzner Cloud · Python · GitHub Actions · Prometheus · Grafana · TypeScript

## Featured engineering work

### [AlertScope — Kubernetes alert investigation](https://github.com/sunkaradp/alertscope)
An Alertmanager webhook service that gathers Prometheus metrics, Loki logs and Kubernetes pod context, then produces an evidence-based first-pass diagnosis and sends findings to Slack. Supports Bedrock and Vertex AI, with a deterministic local stub for development. Includes a browser console, Helm deployment, Terraform examples and CI workflows. The public Pages site is a frontend; the FastAPI service and telemetry stack must be deployed separately.

### [Deployment Dash Intelligence — Kubernetes manifest risk analysis](https://github.com/sunkaradp/deployment-dash-intelligence)
A read-only analyzer for Kubernetes YAML that reports explainable configuration and security findings, evidence paths and remediation guidance. Includes browser-side analysis, a CLI and a composite GitHub Action. The optional FastAPI API is intended for private/local use and must not be exposed publicly without adding authentication, authorization and rate limiting.
[Public demo](https://sunkaradp.github.io/deployment-dash-intelligence/)

### [Kubernetes Incident Remediation for k3s](https://github.com/sunkaradp/k3s-ai-remediation)
A policy-controlled incident response prototype connecting alert context, diagnosis and predefined Kubernetes runbooks. Defaults to observe and dry-run modes; medium-risk actions require approval, and the model cannot execute arbitrary shell or Kubernetes commands. End-to-end cluster deployment and chaos-test measurements remain on the roadmap.

### [Kubernetes Platform Intelligence](https://github.com/sunkaradp/k8s-platform-intelligence)
An observe-only Kubernetes operator experiment that estimates node memory pressure from Prometheus time-series data and emits native Kubernetes Warning Events. Tested on Minikube; predictions are investigation signals, not automated remediation or production guarantees.

### [EV Charging Sessions](https://github.com/sunkaradp/ev-charging-sessions)
A collaborative data-engineering project using Kafka, Airflow and analytics. My documented contributions include producer reliability improvements, reusable batch transformation tests, Python CI coverage and repository hygiene.

## Technical focus

- **Containers & orchestration:** Kubernetes (k3s), Docker, Helm, Kustomize
- **Cloud & infrastructure:** Hetzner Cloud, AWS, Terraform, IAM, GCP project work
- **CI/CD & GitOps:** GitHub Actions, self-hosted runners, GHCR, Argo CD
- **Observability & operations:** Prometheus, Grafana, Loki, Promtail, incident troubleshooting, backup and recovery
- **Application & data infrastructure:** Linux, Python, FastAPI, PostgreSQL, Kafka, Airflow, TypeScript

## Experience

**MLOps / DevOps Intern — AIcoo GmbH, Hamburg** · April 2026 – September 2026

- Built and maintained Kubernetes configuration for a FastAPI, frontend and PostgreSQL platform on k3s hosted by Hetzner Cloud.
- Created 28 Kubernetes manifests with Kustomize, including development and staging overlays, Deployments and a PostgreSQL StatefulSet.
- Implemented GitHub Actions CI/CD with a self-hosted runner to build images, publish to GHCR, run database migrations and deploy to development and staging.
- Worked on secrets management, observability, operational runbooks and disaster-recovery procedures.

**Master's Thesis — AIcoo GmbH / SRH University** · October 2026 – Present

Building a Docker-based pipeline for LLM-assisted extraction and analysis of emails from the Enron corpus, with a focus on data processing, evaluation and reproducibility.

**Previous experience**
- DevOps Engineer — Skillmine Technology Consulting · April 2023 – August 2024
- Junior DevOps Engineer — Test Yantra · November 2021 – February 2023
- Software Associate — Tech Mahindra · March 2020 – September 2021

## Education

**MSc Applied Data Science and Analytics — SRH University of Applied Sciences Hamburg** · Expected March 2027

## Engineering principles

- Prefer repeatable infrastructure and reviewable delivery workflows.
- Make systems observable and operationally understandable.
- Keep automation bounded by explicit policy and least-privilege access.
- Document trade-offs, setup steps and known limitations.
- Distinguish verified outcomes from planned work.

## Contact

[Portfolio](https://sunkaradp.github.io) · [LinkedIn](https://www.linkedin.com/in/dpcloud) · [GitHub](https://github.com/sunkaradp)

---

*Project descriptions link to their repositories, where implementation details, tests and limitations are documented.*
