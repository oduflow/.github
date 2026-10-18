# Oduflow

AI-first Odoo development, CI and hosting, built by Oduist.

Oduflow gives every git branch its own isolated, ephemeral Odoo environment on Docker,
cloned from reusable database templates, and exposes it to AI coding agents over
[MCP](https://modelcontextprotocol.io/). Agents write code, install modules, run tests and read
tracebacks in a closed feedback loop, so a written spec becomes a working module without a human
copy-pasting errors back.

## Repositories

| Repository | What it is |
|---|---|
| [oduflow](https://github.com/oduflow/oduflow) | The Oduflow server: per-branch Odoo environments, database templates, MCP tools for agents, web dashboard, production deploys and backups. `pip install oduflow` |
| [oduflow-stacks](https://github.com/oduflow/oduflow-stacks) | Ready-to-apply Declarative Stacks: an `oduflow.yaml` manifest per stack, applied with `oduflow stack apply` |
| [oduflow-client-addons](https://github.com/oduflow/oduflow-client-addons) | Odoo 19 addons: Odubook (in-app documentation), Oduscale (employee VPN through Headscale), OduPilot (AI conversations in Odoo), OduMCP (MCP access with Odoo-side policy, approvals and audit) |
| [oduflow-platform-docs](https://github.com/oduflow/oduflow-platform-docs) | Documentation for Oduflow Platform, managed Odoo infrastructure with a dedicated environment per client |

## Links

- Website and pricing: [oduflow.dev](https://oduflow.dev)
- Oduflow documentation: [docs.oduflow.dev](https://docs.oduflow.dev)
- Platform documentation: [docs.oduflow.sh](https://docs.oduflow.sh)
- Packages: [PyPI](https://pypi.org/project/oduflow/) · [Docker Hub](https://hub.docker.com/r/oduist/oduflow)

## About Oduist

Oduflow is built by [Oduist](https://oduist.com) (Oduist OÜ, Estonia). The team has more than
twenty years in IP telephony and has been wiring phone systems into Odoo since its first Asterisk
modules on the Odoo Apps store. Oduist's mission is to connect Odoo to everything. Its other
products:

- [Oduist Connect](https://oduist.com): communication and voice AI inside Odoo. Calls, messages,
  recordings, transcripts and AI voice agents land on the right contact, lead or ticket, over
  interchangeable providers such as Twilio, Telnyx, FreeSWITCH, Asterisk and 3CX.
- [OduSphere](https://odusphere.dev): an AI-native enterprise platform, in early access, that builds
  software tailored to a business from semantic primitives, with documentation that stays current.

Source code: [github.com/oduist](https://github.com/oduist) · Contact:
[team@oduist.com](mailto:team@oduist.com)

## Licensing

Oduflow is source-available under the
[PolyForm Noncommercial License 1.0.0](https://github.com/oduflow/oduflow/blob/main/LICENSE), with
[commercial licenses](https://oduflow.dev/pricing) for business use. Addons declare their licenses
per module.

Contact: [request@oduflow.dev](mailto:request@oduflow.dev)
