# Devin Solutions

> **Devin-Powered** — Integrations, automations, SDKs, and agent patterns where Devin is a runtime participant.

This catalog indexes solutions in the `Devin-Samples` org where Devin is integral to the runtime — the software interacts with Devin's APIs, triggers Devin sessions, uses Devin as a worker agent, or provides tooling that extends Devin's capabilities.

> **Disclaimer:** Devin Samples are example code that demonstrates practical implementations of Devin for specific use cases and scenarios. These application solutions are not supported products in their own right, but educational examples to help our customers and partners use our products for their applications. Any applications you integrate these examples into should be thoroughly tested, secured, and optimized according to your business's security standards & policies before deploying to production or handling production workloads.

## Standalone Solutions

| Solution | Description | Tech Stack | Status |
|----------|-------------|------------|--------|
| [ACU-budgets](https://github.com/Devin-Samples/ACU-budgets) | Budget enforcement and ACU management using the Devin API | TypeScript, React, AWS | Available |
| [cognizant-devin-bulk-manager](https://github.com/Devin-Samples/cognizant-devin-bulk-manager) | Bulk user provisioning via Devin v3 API using CSV | Python | Available |
| [deepwiki-api](https://github.com/Devin-Samples/deepwiki-api) | API and frontend for DeepWiki and AskDevin | JavaScript | Available |
| [devin-bulk-manager](https://github.com/Devin-Samples/devin-bulk-manager) | Bulk user permission management via Devin API | Python | Available |
| [devin-sdk](https://github.com/Devin-Samples/devin-sdk) | Lightweight reference SDK wrapping Devin's APIs | TypeScript | Available |
| [prompt-library](https://github.com/Devin-Samples/prompt-library) | Reference system prompts to improve Devin behavior | Markdown | Available |
| [user-management](https://github.com/Devin-Samples/user-management) | User, org, and GitHub team management for Devin enterprises | Python | Available |

## Aggregate Collections

| Collection | Description | Scope | Status |
|------------|-------------|-------|--------|
| [automations-and-integrations](https://github.com/Devin-Samples/automations-and-integrations) | CI/CD triggers, network connectivity, webhook receivers | GitHub Actions, Azure DevOps, AWS SSM | Available |
| [reference-solution-architectures](https://github.com/Devin-Samples/reference-solution-architectures) | Solution designs where Devin provides quality, efficiency, reliability, and/or scale | Architecture patterns | Available |

## What Makes a Repo "Devin-Powered"?

A repo belongs in this catalog when:
- It calls the **Devin API or SDK** at runtime
- It **triggers or orchestrates** Devin sessions (webhooks, CI/CD, scheduled)
- It provides **MCP servers, playbooks, prompts, or knowledge** for Devin
- It wraps **Devin as a worker agent** in a larger pipeline
- It **manages Devin resources** (users, budgets, permissions)

## Looking for Devin-Built Solutions?

For standalone applications authored entirely by Devin that run independently, see **[devin-showcase](https://github.com/Devin-Samples/devin-showcase)**.

## Adding a New Entry

See [CONTRIBUTING.md](CONTRIBUTING.md) for how to register your solution in this catalog.

## License

This project is licensed under the Apache License 2.0 — see the [LICENSE](LICENSE) file for details.
