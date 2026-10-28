### Hi there 👋

I'm an SRE & Platform Engineer with roots in Linux system administration. I build tools in **Go**, **Python**, **TypeScript**, and **Bash** to solve infrastructure problems — from infrastructure providers and network intelligence to secure, cloud-native applications.

#### Currently working on
- 🛜 [terraform-provider-unifi](https://github.com/BadgerOps/terraform-provider-unifi) — Terraform provider for UniFi Network using the official Integration API (Go)
- 🧳 [travel-hq](https://github.com/BadgerOps/travel-hq) — Trips-first family travel dashboard running on Cloudflare Workers, D1, and Workers AI (TypeScript)
- 🌐 [CloudPAM](https://github.com/BadgerOps/cloudpam) — A lightweight, cloud-native IP Address Management solution for AWS/GCP (Go + TypeScript)
- 🕸️ [grapheon](https://github.com/BadgerOps/grapheon) — Network intelligence platform that aggregates scan data (nmap, netstat, arp) into graph visualizations (Python/FastAPI + React)

#### Popular & Featured Projects
- ⭐ [salt-workspace](https://github.com/BadgerOps/salt-workspace) — Salt configuration management workspace (16 stars)
- 📦 [epel-offline-sync](https://github.com/BadgerOps/epel-offline-sync) — Sync EPEL repos for disconnected environments (Python)
- 🔄 [ocpsync](https://github.com/BadgerOps/ocpsync) — Sync artifacts for OpenShift in air-gapped environments (Go)
- 📥 [dlserver](https://github.com/BadgerOps/dlserver) — Download server written in Go
- 🎤 [bsides-if-2022](https://github.com/BadgerOps/bsides-if-2022) — BSides Idaho Falls 2022 conference talk materials

#### Security Research

Discovered hardcoded secrets vulnerabilities in Red Hat's Mirror Registry, resulting in 4 CVEs:
- [CVE-2024-3622](https://nvd.nist.gov/vuln/detail/CVE-2024-3622) — Plaintext CSRF secret key
- [CVE-2024-3623](https://nvd.nist.gov/vuln/detail/CVE-2024-3623) — Default database secret key in plain-text
- [CVE-2024-3624](https://nvd.nist.gov/vuln/detail/CVE-2024-3624) — Database user and password stored in plain-text
- [CVE-2024-3625](https://nvd.nist.gov/vuln/detail/CVE-2024-3625) — Redis password stored in plain-text

Read more: [CVE disclosure process writeup](https://blog.badgerops.net/cves/)

#### Upstream Contributions

- **[quay/mirror-registry](https://github.com/quay/mirror-registry)** — 4 merged PRs fixing secrets handling and security issues
- **[keycloak/keycloak](https://github.com/keycloak/keycloak)** — Operator documentation and TLS configuration fixes
- **[openshift/oc-mirror](https://github.com/openshift/oc-mirror)** — Code cleanup contributions

#### Last 180 Days

From May 1 through October 28, 2026: **281 commits** across seven public repositories, **123 pull requests**, **53 issues**, and **6 code reviews**, plus **34 private contributions**.

- **[travel-hq](https://github.com/BadgerOps/travel-hq)** — 139 commits and 53 PRs building secure email, calendar, PDF, and on-device document ingestion; a mobile PWA; push notifications; trip collaboration; and production observability on Cloudflare
- **[terraform-provider-unifi](https://github.com/BadgerOps/terraform-provider-unifi)** — 58 commits and 10 PRs expanding UniFi resources, updating the OpenAPI snapshot, fixing configuration drift, adding plan-time validation, and hardening contribution and release workflows
- **[CloudPAM](https://github.com/BadgerOps/cloudpam)** — 52 commits and 50 PRs spanning discovery and import workflows, a Terraform provider, OpenTelemetry tracing, responsive UI work, security fixes, and an increase in Go test coverage to 85%
- **[grapheon](https://github.com/BadgerOps/grapheon)** — 26 commits and 9 PRs delivering passive-agent lifecycle management, topology evidence and provenance, on-demand collection, and map-layer improvements
- **Maintenance and learning** — dependency and security updates for [network-trainer](https://github.com/BadgerOps/network-trainer), ongoing [Rust exercises](https://github.com/BadgerOps/rust-learning), and a [salt-workspace](https://github.com/BadgerOps/salt-workspace) update

#### Ask me about
- Observability (metrics, logs, traces)
- Salt, Ansible, and configuration management at scale
- Disconnected/air-gapped environment challenges
- OpenShift & container orchestration

#### Connect
- 📝 [blog.badgerops.net](https://blog.badgerops.net)
- 🐘 [mastodon.social/@badgerops](https://mastodon.social/@badgerops)
- 🐦 [@badgerops](https://twitter.com/badgerops)

#### GitHub Stats

<p>
  <img src="stats/github-stats.svg" alt="GitHub Stats" />
  <img src="stats/top-langs.svg" alt="Top Languages" />
</p>

> Stats are refreshed weekly via [GitHub Actions](.github/workflows/update-stats.yml) using [lowlighter/metrics](https://github.com/lowlighter/metrics). Languages are measured by lines of code.

#### Tech Stack

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnu-bash&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![OpenShift](https://img.shields.io/badge/OpenShift-EE0000?style=flat&logo=red-hat-open-shift&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat&logo=google-cloud&logoColor=white)
