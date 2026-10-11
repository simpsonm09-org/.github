# simpsonm09-org

Personal projects and developer tooling by [Max Simpson](https://github.com/simpsonm09).

This organization holds the original repositories. Development happens in personal forks under [@simpsonm09](https://github.com/simpsonm09), with pull requests back to the originals.

## Repository standards

- [repo-standard](https://github.com/simpsonm09-org/simpsonm09-repo-standard) owns reusable CI, linting, security scanning, conformance checks, and branch governance.
- [repo-template](https://github.com/simpsonm09-org/simpsonm09-repo-template) is the starting point for new projects: a layered Kotlin and Spring Boot service wired to the standard.
- [repo-catalog](https://github.com/simpsonm09-org/simpsonm09-repo-catalog) records fleet membership, adoption policy, and agent access intent.

## AI development

- [maxstack](https://github.com/simpsonm09-org/simpsonm09-maxstack) composes and installs the workspace AI layers for OpenCode, Claude Code, GitHub Copilot CLI, and Pi, used through T3 Code. The model is selected in the harness.
- The base layer comes from the [pstack-claude fork](https://github.com/simpsonm09/pstack-claude). The layer order is PStack, then the org layer, then the personal layer.
- [org-ai-plugin](https://github.com/simpsonm09-org/simpsonm09-org-ai-plugin) supplies portable skills, integration guidance, and the shared agent-access gate.
- [personal-ai-plugin](https://github.com/simpsonm09-org/simpsonm09-personal-ai-plugin) supplies personal preferences, skills, and integration guidance for services such as Discord and email.

The current org and personal plugins use CLI integrations and contribute no MCP server.

## Personal integrations and homelab

- [OpenClaw homelab](https://github.com/simpsonm09-org/simpsonm09-openclaw-homelab) holds configuration, validation, and deployment runbooks for a self-hosted AI gateway. It is currently a scaffold; it does not install or run OpenClaw.

## Workstation and machines

- [dev-setup](https://github.com/simpsonm09-org/simpsonm09-dev-setup) owns workstation tools, machine setup, local services, secrets loaders, and Agent Vault wrappers.
- [machine-inventory](https://github.com/simpsonm09-org/simpsonm09-machine-inventory) records machine classes, counts, and capabilities without identifying devices or people.

## API and test tooling

- [Postman test utilities](https://github.com/simpsonm09-org/simpsonm09-postman-test-utils) run collections with newman, resolve secrets, and provide shared response validation.
- [Playwright API wrapper](https://github.com/simpsonm09-org/simpsonm09-playwright-api-wrapper) exposes declarative browser scenarios through an HTTP API for Postman, newman, and CI.

## Examples and conformance

- [Browser calculator](https://github.com/simpsonm09-org/simpsonm09-browser-calculator) is a Fastify application with an arithmetic evaluator and a stateless contact form.
- [PokeAPI wrapper](https://github.com/simpsonm09-org/simpsonm09-pokeapi-wrapper) is a FastAPI service and reference implementation for generated OpenAPI contracts.
- Item CRUD fixtures in [Go](https://github.com/simpsonm09-org/simpsonm09-fixture-go), [Rust](https://github.com/simpsonm09-org/simpsonm09-fixture-rust), [.NET](https://github.com/simpsonm09-org/simpsonm09-fixture-dotnet), and [NestJS](https://github.com/simpsonm09-org/simpsonm09-fixture-nest) validate the fleet framework and its agent-access levels.

## Earlier and archived work

- [Steam wishlist cleanup](https://github.com/simpsonm09-org/steam_wishlist_cleanup) compares wishlists with games available through friends or family.
- [Acrobat PDF field automation](https://github.com/simpsonm09-org/pdf_field_automation_acrobat) adds fields through Acrobat's JavaScript API.
- [The Gaming Index](https://github.com/simpsonm09-org/The_Gaming_Index_Video_Game_Database_Final_Capstone) is the archived capstone project.
- [pstack-opencode-plugin](https://github.com/simpsonm09-org/pstack-opencode-plugin) is the archived adapter, superseded by the pstack-claude base layer.

## Profile and community

[.github](https://github.com/simpsonm09-org/.github) holds this overview and the organization's default contribution guidance, support guidance, and issue and pull request templates. Repository-specific files take precedence. CI and governance remain in repo-standard.

[Browse all repositories](https://github.com/orgs/simpsonm09-org/repositories) · [Personal profile](https://github.com/simpsonm09) · [LinkedIn](https://www.linkedin.com/in/maxwellsimpson/)