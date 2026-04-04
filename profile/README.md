<p align="center">
  <img src="https://recif-platform.github.io/logo.png" alt="Récif" width="80" />
</p>

<h2 align="center">Récif Platform</h2>

<p align="center">
  <strong>The open-source control tower for autonomous AI agents.</strong><br/>
  Deploy, evaluate, and govern AI agents at scale — any framework, any cloud.
</p>

<p align="center">
  <a href="https://recif-platform.github.io">Website</a> •
  <a href="https://recif-platform.github.io/docs/introduction">Documentation</a> •
  <a href="https://recif-platform.github.io/docs/quickstart">Quickstart</a> •
  <a href="https://discord.gg/P279TT4ZCp">Discord</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-alpha-orange?style=flat-square" alt="Alpha" />
  <img src="https://img.shields.io/badge/license-Apache_2.0-blue?style=flat-square" alt="License" />
  <a href="https://discord.gg/P279TT4ZCp"><img src="https://img.shields.io/badge/Discord-Join-5865F2?style=flat-square&logo=discord&logoColor=white" alt="Discord" /></a>
</p>

> **🚀 Just launched!** Récif is in alpha — functional but evolving fast. We're looking for contributors passionate about AI agents, Kubernetes, Go, Python, or React. Come build the future of agent operations with us.

---

### Repositories

| Repo | Description |
|------|-------------|
| [**corail**](https://github.com/recif-platform/corail) | Autonomous agent runtime — Python, 7 LLM providers, multi-channel, evaluation |
| [**recif**](https://github.com/recif-platform/recif) | Control tower API (Go) + Dashboard (Next.js) — governance, releases, monitoring |
| [**recif-operator**](https://github.com/recif-platform/recif-operator) | Kubernetes operator — Agent CRDs → Deployments, Services, ConfigMaps |
| [**helm-charts**](https://github.com/recif-platform/helm-charts) | Helm charts + deployment scripts — one-command install |

### Quick Install

```bash
helm install recif oci://ghcr.io/recif-platform/helm-charts/recif:0.1.0 \
  --namespace recif-system --create-namespace
```

### What Makes Récif Different

- **Eval-gated releases** — no agent ships without passing quality scores
- **Canary deployments** — champion/challenger with auto-rollback
- **Framework agnostic** — ADK, LangChain, CrewAI, or custom
- **Two access paths** — direct API + platform governance, simultaneously
- **Kubernetes-native** — CRDs, operators, Istio mesh, Helm

### Contributing

We welcome contributions of all sizes. Check out the [documentation](https://recif-platform.github.io/docs/introduction) and join our [Discord](https://discord.gg/P279TT4ZCp) to get started.

### License

Apache 2.0
