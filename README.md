# Sabry Zammit

**Fullstack developer, TypeScript & PHP, with lead dev experience.** Based in Paris, open to freelance missions. I work in French and English.

I build complete products from a blank page: architecture and stack choices under real constraints, delivery, and the team practices that keep them healthy, such as code reviews, onboarding and CI.

- **NestJS + React + TypeScript**, for scale-ups and larger organizations
- **Laravel + Inertia + React + TypeScript**, for SaaS startups and product teams

## Featured projects

### [mcp-project-context](https://github.com/sabrysty/mcp-project-context)

An MCP server that gives AI coding agents (Claude Code, Copilot, Cursor) a project's context: overview, conventions, security rules and features, plus a `check_code` tool that checks generated code against the team's rules.

During real-client tests, an agent wrote an authorization flaw that no rule could catch. The cause was a gap in the documentation, not the agent: once it was documented, the same request produced correct code. The project is built around that lesson, with security by design (read-only, defense in depth against path traversal), 369 tests, CI on Linux and Windows, and one issue and one pull request per step.

### [ovh-deploy-kit](https://github.com/sabrysty/ovh-deploy-kit)

Deploys a Laravel app to OVH shared hosting with FTP only: no SSH, no phpMyAdmin, no Composer on the server. One command builds a zip, uploads it over FTPS and runs short-lived server scripts, which are protected by a single-use token and removed automatically at the end. PHP with no dependencies.

## How I work

- **Measure before fixing, prove with tests.** A bug fix comes with the test that would have caught it.
- **Write decisions down**, with the alternatives and trade-offs, in issues, pull requests and commit messages.
- **Treat security as a design constraint**, not a final check.
- **Be honest about limits**: what was tested, and what was not.

## Contact

[LinkedIn](https://www.linkedin.com/in/sabry-zammit-859596123/)
