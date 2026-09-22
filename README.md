# Satyam Agnihotri

### DevOps & Cloud Engineering · Kubernetes · Azure · GitOps

I work on Kubernetes-based delivery, infrastructure automation, cloud
observability, and software supply chain security. My backend engineering
background helps me connect application behavior with infrastructure and
operational troubleshooting.

**CKA | Certified Kubernetes Administrator · AZ-104 | Microsoft Certified: Azure Administrator Associate**

[LinkedIn](https://www.linkedin.com/in/swe1-satyam/) ·
[Azure AKS project](https://github.com/devSatym/azure-aks-gitops-observability) ·
[GCP security reference](https://github.com/devSatym/gcp-supply-chain-security/tree/656741e02a526341dd6b98d1ab9ab059aed3fb20)

## Selected engineering work

### Azure AKS — GitOps Delivery & OpenTelemetry Observability

A Terraform-managed AKS reference environment with Argo CD workload
reconciliation and Azure-native telemetry backends.

- **Infrastructure and delivery:** AKS, ACR, Terraform, Helm, Argo CD, and
  GitHub Actions. CI promotes an internal canary image through Git rather
  than acting as a second Kubernetes deployment controller.
- **Observability:** OpenTelemetry, Azure Monitor, Log Analytics,
  Managed Prometheus, and Container Insights.
- **Recorded validation:** 17 ready demo deployments in the main release;
  a checkout trace across 12 services in a separate temporary capture.

[Source and architecture](https://github.com/devSatym/azure-aks-gitops-observability) ·
[Validation evidence](https://github.com/devSatym/azure-aks-gitops-observability#live-evidence-index) ·
[Scope and limitations](https://github.com/devSatym/azure-aks-gitops-observability#scope-and-limitations)

The upstream OpenTelemetry Demo supplies the application workload. My work
focuses on platform integration, deployment, configuration, and validation.

### GCP / GKE — Software Supply Chain & Runtime Security

A preserved GCP reference implementation connecting artifact identity,
reviewed deployment state, admission enforcement, and runtime detection.

- **Artifact trust:** GitHub OIDC / GCP Workload Identity Federation,
  Cosign keyless signing, SPDX SBOM, and SLSA provenance attestations.
- **Deployment and admission:** digest-pinned GitOps delivery through Argo CD
  with Kyverno checks against the configured trust contract.
- **Recorded validation:** trusted-image admission; rejection of unsigned
  images and initContainers in the protected scope; rejection under incorrect
  trust expectations; Falco detection of controlled shell execution.

[Preserved GCP source](https://github.com/devSatym/gcp-supply-chain-security/tree/656741e02a526341dd6b98d1ab9ab059aed3fb20) ·
[Validation record](https://github.com/devSatym/gcp-supply-chain-security/blob/656741e02a526341dd6b98d1ab9ab059aed3fb20/docs/my-validation/README.md) ·
[Threat model and boundaries](https://github.com/devSatym/gcp-supply-chain-security/tree/656741e02a526341dd6b98d1ab9ab059aed3fb20#threat-model-and-boundaries)

This work integrates and extends credited upstream components. The links
above deliberately target the GCP snapshot: current `main` contains an Azure
implementation, and the GCP evidence does not validate that newer code path.

### Kubernetes Playbook

My Kubernetes reference notes, organized around concepts, failure patterns,
troubleshooting, and security considerations developed during CKA/CKS study.

[Explore the playbook](https://github.com/devSatym/Kubernetes-Playbook)

## Technical focus

| Area | Tools and concepts |
| --- | --- |
| Infrastructure | Azure, AKS, GCP, GKE, Terraform, Linux, networking |
| Delivery | Kubernetes, Docker, Helm, Argo CD, GitHub Actions, GitOps |
| Observability | OpenTelemetry, Azure Monitor, Log Analytics, Managed Prometheus, Container Insights |
| Security | OIDC, workload identity, Cosign, SBOM/provenance, Kyverno, Falco, Trivy, Semgrep |
| Backend foundation | Node.js, TypeScript, Fastify, PostgreSQL, Redis, BullMQ, Sequelize |

## How I approach the work

I keep infrastructure ownership separate from workload reconciliation, test
negative security cases instead of showing only successful deployments, and
record what the evidence does—and does not—prove.

My repositories describe recorded validation runs, not an always-on service,
a production SLA, or an unqualified security guarantee.

## Background and opportunities

Software engineering internship experience at **Easyhyre**, spanning backend
systems, containerized delivery, and troubleshooting. **BCA, CSJMU, Kanpur.**

Seeking **DevOps and Cloud Engineer** opportunities focused on Kubernetes,
infrastructure as code, delivery automation, observability, and security.

[Connect on LinkedIn](https://www.linkedin.com/in/swe1-satyam/)
