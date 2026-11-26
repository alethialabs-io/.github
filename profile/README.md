# Alethia Labs

Alethia runs Kubernetes in your own cloud account. It turns a repository into proposed
infrastructure, plans it with OpenTofu, checks the plan with a deterministic gate, applies it in
your account and hands you a signed receipt of what changed.

```sh
brew install alethialabs-io/tap/alethia
```

AWS, Google Cloud and Azure connect without stored cloud keys, through short-lived federated
identity. Hetzner uses a scoped API token, because Hetzner has no federation. The core is open
source under AGPL-3.0 and self-hostable.

## Repositories

| Repository | What it is |
| --- | --- |
| [`alethialabs`](https://github.com/alethialabs-io/alethialabs) | The main repository: console, CLI, runner, docs and self-host stacks. Issues and PRs go here |
| [`alethia-examples`](https://github.com/alethialabs-io/alethia-examples) | Online Boutique across environments, and bring-your-own OpenTofu modules |
| [`alethia-starter-ai`](https://github.com/alethialabs-io/alethia-starter-ai) | Template: RAG, a vector database and model serving |
| [`alethia-starter-apps`](https://github.com/alethialabs-io/alethia-starter-apps) | Template: an ArgoCD apps destination |
| [`alethia-starter-chart`](https://github.com/alethialabs-io/alethia-starter-chart) | Template: bring your own Helm chart |
| [`alethia-cli`](https://github.com/alethialabs-io/alethia-cli) | Read-only mirror of the CLI, published by CI |
| [`homebrew-tap`](https://github.com/alethialabs-io/homebrew-tap) · [`scoop-bucket`](https://github.com/alethialabs-io/scoop-bucket) | Install the CLI on macOS, Linux and Windows |

## Links

- Docs: https://alethialabs.io/docs
- Website: https://alethialabs.io
- Security reports: security@alethialabs.io (see [SECURITY.md](https://github.com/alethialabs-io/.github/blob/main/SECURITY.md))
