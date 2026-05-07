<p align="center">
  <img src="./assets/github-banner.png" alt="Eseosa Raymond Iyangbe GitHub profile banner" width="100%" />
</p>

# Eseosa Raymond Iyangbe

Platform and DevOps engineer focused on Kubernetes operations, observability, secrets management, GitOps direction, cloud infrastructure, and operator-ready documentation.

My GitHub is centered on one core idea: build systems that are realistic enough to operate, troubleshoot, harden, and explain like a real platform, not just demo in isolation.

## What I Am Building

I am building an **Internal Developer Platform** that brings together multiple application styles under one operational model:

- a shared observability and control-plane layer
- Kubernetes-first workload operations on local `k3s`
- Vault-backed secret delivery
- Cloudflare public ingress and protected observability surfaces
- repeatable deployment, verification, and recovery workflows
- runbooks that document both success paths and failure paths

The platform currently spans:

- `observability-stack`: the control plane and observability hub
- `swiftpay`: a fintech-style microservices system
- `foodpulse`: a resilience and failover lab
- `memflip`: a simpler application path used to prove deployment and GitOps patterns
- `opensis`: a legacy-style application with stronger secret and operational requirements

## Engineering Focus

- Kubernetes operations and environment design
- observability with metrics, logs, dashboards, probes, and alerts
- platform engineering and control-plane thinking
- secure secret delivery with Vault and External Secrets
- Docker and local platform orchestration
- ingress, DNS, and edge exposure patterns
- Bash automation and operator workflows
- incident response, verification, and recovery documentation

## Current Platform Story

The strongest work in this portfolio is no longer a single repo or one isolated stack. It is the platform story across the repos:

- a live control plane for workload health, alerts, logs, and service discovery
- multiple applications migrated onto a shared `k3s` runtime
- public demo ingress through Cloudflare Tunnel
- Cloudflare Access protection for sensitive observability surfaces
- production-style `dev` and `prod` Kubernetes overlays
- certification-style verification scripts for each workload
- documented recovery work when reality did not match the intended design

That means the portfolio is not just showing what was built. It also shows how the platform behaves under pressure, how drift is corrected, and how the operating model is tightened over time.

## Flagship Repositories

### Internal Developer Platform

The central coordination repo for the platform: roadmap, runbooks, shared bootstrap, GitOps activation path, recovery procedures, and workspace operating model.

Key areas demonstrated:

- platform architecture and phase-based roadmap
- multi-repo operating model
- shared runtime and bootstrap automation
- GitOps activation design for ArgoCD
- Cloudflare recovery and platform-level operations notes

Repository: [internal-developer-platform](https://github.com/eseosaiyangbe/internal-developer-platform)

### Observability Stack

The platform control plane and observability hub that ties the rest of the workloads together.

Key areas demonstrated:

- Next.js control plane UI
- Prometheus, Grafana, Alertmanager, Loki, Promtail, cAdvisor, node-exporter, and blackbox-exporter
- protected observability endpoints through Cloudflare Access
- platform service inventory, health views, alerts, and logs
- Kubernetes and local runtime operations

Repository: [Obervability-Stack](https://github.com/eseosaiyangbe/Obervability-Stack)

### SwiftPay

A fintech-style microservices platform used to demonstrate service decomposition, asynchronous workflows, Kubernetes overlays, and operator verification.

Key areas demonstrated:

- API gateway, auth, wallet, transaction, and notification services
- PostgreSQL, Redis, and RabbitMQ integration
- `dev` and `prod` Kubernetes overlays
- live verification workflows and production-style controls

Repository: [SwiftPay](https://github.com/eseosaiyangbe/SwiftPay)

### FoodPulse

A resilience-focused application lab used to demonstrate stateful services, failover patterns, and recovery hardening.

Key areas demonstrated:

- PostgreSQL cluster behavior
- Redis and Sentinel topology
- high-availability traffic flow
- restart and failover recovery work
- monitoring and operational drills

Repository: [FoodPulse](https://github.com/eseosaiyangbe/FoodPulse)

### OpenSIS

A legacy-style workload with stronger secret, runtime, and operational constraints than a typical greenfield app.

Key areas demonstrated:

- Vault-backed secret delivery
- Kubernetes deployment and verification
- MariaDB and session Redis operations
- exporter coverage and control-plane integration
- production-minded operational documentation

Repository: [OpenSIS](https://github.com/eseosaiyangbe/OpenSIS)

### MemFlip

A simpler application path that helps prove the platform model end to end without the same operational weight as the larger workloads.

Key areas demonstrated:

- containerization and Kubernetes overlays
- GitOps-oriented application structure
- verification workflows
- deployment-path documentation

Repository: [MemFlip](https://github.com/eseosaiyangbe/MemFlip)

## Tooling And Platform Areas

| Area | Tools and Concepts |
|---|---|
| Platform Runtime | Docker, Colima, `k3s`, Traefik |
| Kubernetes | Deployments, StatefulSets, Services, Ingress, Kustomize, HPAs, PDBs |
| GitOps Direction | ArgoCD application structure, root orchestration patterns |
| Observability | Prometheus, Grafana, Alertmanager, Loki, Promtail, cAdvisor, node-exporter, blackbox-exporter |
| Secrets and Security | Vault, External Secrets, Cloudflare Access, secret scoping, runtime secret delivery |
| Data and Messaging | PostgreSQL, MariaDB, Redis, RabbitMQ |
| Automation | Bash, verification scripts, bootstrap scripts, runbooks |
| Cloud and Edge | AWS/Azure direction, Cloudflare Tunnel, DNS and ingress exposure |

## How I Work

I care about systems that are:

- repeatable to deploy
- explicit about health and failure
- honest about what is live versus what is still directional
- secure enough to defend architectural decisions
- documented so another engineer can operate them without guesswork
- strong enough to discuss in interviews as real platform work, not only tutorials

## Current Priorities

- complete stable GitOps activation for the local `k3s` platform
- keep tightening production-style controls across the workload set
- expand the operational evidence pack with screenshots, runbooks, and recovery records
- continue improving the platform story across the multi-repo model

## Contact

- GitHub: [github.com/eseosaiyangbe](https://github.com/eseosaiyangbe)

<!-- profile-readme-render-refresh: 2026-05-07T13:35:00Z -->
