# simpsonm09-projects

Personal projects and developer tooling by [Max Simpson](https://github.com/simpsonm09).

This organization holds the repositories. Development happens on branches in these repositories, and pull requests merge into `main` here; work does not go through personal forks.

## Repository standards

- [repo-standard](https://github.com/simpsonm09-projects/simpsonm09-repo-standard): owns reusable CI, linting, security scanning, conformance checks, and branch governance.
- [repo-template](https://github.com/simpsonm09-projects/simpsonm09-repo-template): is the starting point for new projects: a layered Kotlin and Spring Boot service wired to the standard.
- [repo-catalog](https://github.com/simpsonm09-projects/simpsonm09-repo-catalog): records fleet membership, adoption policy, and agent access intent.

## AI development

- [maxstack](https://github.com/simpsonm09-projects/simpsonm09-maxstack): composes and installs the workspace AI layers for OpenCode, Claude Code, GitHub Copilot CLI, and Pi, used through T3 Code. The model is selected in the harness.
- [simpsonm09/pstack-claude](https://github.com/simpsonm09/pstack-claude): fork of michael-denyer/pstack-claude that supplies the PStack base layer. The layer order is PStack, then the org layer, then the personal layer.
- [org-ai-plugin](https://github.com/simpsonm09-projects/simpsonm09-org-ai-plugin): supplies portable skills, integration guidance, and the shared agent-access gate.
- [personal-ai-plugin](https://github.com/simpsonm09-projects/simpsonm09-personal-ai-plugin): supplies personal preferences, skills, and integration guidance for services such as Discord and email.

The current org and personal plugins use CLI integrations and contribute no MCP server.

## Personal integrations and homelab

- [openclaw-homelab](https://github.com/simpsonm09-projects/simpsonm09-openclaw-homelab): holds configuration, validation, and deployment runbooks for a self-hosted AI gateway. It is currently a scaffold; it does not install or run OpenClaw.

## Workstation and machines

- [dev-setup](https://github.com/simpsonm09-projects/simpsonm09-dev-setup): owns workstation tools, machine setup, local services, secrets loaders, and Agent Vault wrappers.
- [machine-inventory](https://github.com/simpsonm09-projects/simpsonm09-machine-inventory): records machine classes, counts, and capabilities without identifying devices or people.

## API and test tooling

- [postman-test-utils](https://github.com/simpsonm09-projects/simpsonm09-postman-test-utils): run collections with newman, resolve secrets, and provide shared response validation.
- [playwright-api-wrapper](https://github.com/simpsonm09-projects/simpsonm09-playwright-api-wrapper): exposes declarative browser scenarios through an HTTP API for Postman, newman, and CI.

## Examples and conformance

- [browser-calculator](https://github.com/simpsonm09-projects/simpsonm09-browser-calculator): is a Fastify application with an arithmetic evaluator and a stateless contact form.
- [pokeapi-wrapper](https://github.com/simpsonm09-projects/simpsonm09-pokeapi-wrapper): is a FastAPI service and reference implementation for generated OpenAPI contracts.
- [fixture-go](https://github.com/simpsonm09-projects/simpsonm09-fixture-go): Go item CRUD fixture that validates the fleet framework and its agent-access levels.
- [fixture-rust](https://github.com/simpsonm09-projects/simpsonm09-fixture-rust): Rust item CRUD fixture that validates the fleet framework and its agent-access levels.
- [fixture-dotnet](https://github.com/simpsonm09-projects/simpsonm09-fixture-dotnet): .NET item CRUD fixture that validates the fleet framework and its agent-access levels.
- [fixture-nest](https://github.com/simpsonm09-projects/simpsonm09-fixture-nest): NestJS item CRUD fixture that validates the fleet framework and its agent-access levels.

## Earlier and archived work

- [steam-wishlist-cleanup](https://github.com/simpsonm09-projects/steam-wishlist-cleanup): compares wishlists with games available through friends or family.
- [pdf-field-automation-acrobat](https://github.com/simpsonm09-projects/pdf-field-automation-acrobat): adds fields through Acrobat's JavaScript API.
- [the-gaming-index-video-game-database-final-capstone](https://github.com/simpsonm09-projects/the-gaming-index-video-game-database-final-capstone): is the archived capstone project.
- [pstack-opencode-plugin](https://github.com/simpsonm09-projects/pstack-opencode-plugin): is the archived adapter, superseded by the pstack-claude base layer.

## Profile and community

- [.github](https://github.com/simpsonm09-projects/.github): holds this overview and the organization's default contribution guidance, support guidance, and issue and pull request templates. Repository-specific files take precedence. CI and governance remain in repo-standard.

[Browse all repositories](https://github.com/orgs/simpsonm09-projects/repositories) · [Personal profile](https://github.com/simpsonm09) · [LinkedIn](https://www.linkedin.com/in/maxwellsimpson/)