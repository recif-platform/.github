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

---

### Repositories

| Repo | Description |
|------|-------------|
| [**corail**](https://github.com/recif-platform/corail) | Autonomous agent runtime — Python, 7 LLM providers, multi-channel, evaluation |
| [**recif**](https://github.com/recif-platform/recif) | Control tower API (Go) + Dashboard (Next.js) — governance, releases, monitoring |
| [**recif-operator**](https://github.com/recif-platform/recif-operator) | Kubernetes operator — Agent CRDs → Deployments, Services, ConfigMaps |
| [**helm-charts**](https://github.com/recif-platform/helm-charts) | Helm charts + deployment scripts — one-command install |
| [**docs**](https://github.com/recif-platform/docs) | Documentation site — guides, references, architecture |

### Quick Install

```bash
helm install recif oci://ghcr.io/recif-platform/helm-charts/recif
```

### License

Apache 2.0
