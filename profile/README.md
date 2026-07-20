# Alethia Labs

Alethia Labs builds an open-core control plane for multi-cloud infrastructure.

Teams use Alethia to design infrastructure as a Project, plan the change, run it
through controlled provisioning jobs, and hand the resulting Kubernetes estate to
GitOps reconciliation. The product is built for platform teams that need a
practical way to manage cloud infrastructure across AWS, GCP, Azure, and other
environments without spreading long-lived cloud credentials through tools and
pipelines.

## What we build

- **Alethia Console** - a web control plane for projects, environments, jobs,
  runners, alerts, and governance.
- **`alethia` CLI** - a command-line interface for authentication, project
  operations, planning, deployment, and runner workflows.
- **Provisioning runners** - isolated workers that claim jobs, execute
  OpenTofu/Terraform, and stream logs and status back to the control plane.
- **Infrastructure templates** - versioned modules for cloud networks,
  Kubernetes clusters, databases, caches, DNS, secrets, registries, and
  supporting services.
- **GitOps integration** - ArgoCD-based reconciliation after provisioning, so
  deployed clusters stay aligned with source-controlled state.

## Principles

- **No stored cloud keys by default.** Cloud access is designed around
  short-lived federated identity wherever the provider supports it.
- **Self-hostable core.** The core platform is open source under AGPL-3.0 and
  can run on your own infrastructure.
- **Operational visibility.** Plans, applies, runner activity, logs, alerts,
  and infrastructure state are visible from one place.
- **Open core, clear boundaries.** Core infrastructure workflows are open
  source; enterprise features add organization governance, SSO, custom roles,
  and audit controls.

## Repositories

- [`alethialabs`](https://github.com/alethialabs-io/alethialabs) - main
  monorepo for the console, CLI, runners, docs, infrastructure, and shared
  packages.

## Links

- Website: https://alethialabs.io
- Documentation: https://alethialabs.io/docs
- Main repository: https://github.com/alethialabs-io/alethialabs
