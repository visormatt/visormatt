<picture>
 <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/visormatt/visormatt/contributions/contributions-dark.svg">
 <img alt="snake!" src="https://raw.githubusercontent.com/visormatt/visormatt/contributions/contributions.svg">
</picture>

# Hi, I'm Matthew Scholta 👋

Setting **technical direction** across the org. Turning legacy systems into **modern architectures**. Building the platforms and AI-native tooling that let **teams ship faster**.

## 👨‍💻 Current Role

**Principal Engineer** at [Shiftsmart](https://shiftsmart.com)

- Setting architecture direction and engineering standards across teams
- Leading the move from a legacy monolith to services on NestJS, GraphQL, BullMQ, and TypeScript
- Building the platform layer: observability, developer tooling, and automation
- Bringing AI-assisted, agent-driven engineering into everyday team workflows

## 🧩 In Progress

### [OpenThrottle](https://openthrottle.ai)

[OpenThrottle](https://github.com/OpenThrottle/monorepo) is an open-core (Apache-2.0), AI-native platform for planning and shipping software. At its core is a Postgres knowledge base of **plans and tasks** with semantic search. Editors and coding agents reach it over **MCP**. **Ralph**, its agent runner, executes those plans, and a developer dashboard shows what's in flight and what shipped.

I build OpenThrottle with OpenThrottle: more than 1,000 plans have gone from idea to merged PR through it. It is also where I prove out patterns, like Nx generators, shared packages, and agent workflows, before they land in Shiftsmart's monorepos.

**Highlights**:

- MCP server that makes plans and tasks the shared source of truth for every agent and editor
- Ralph: plan-driven agent runs in isolated git worktrees, one task at a time, ending in a PR
- One agent config synced to Claude Code, Cursor, Codex, OpenCode, and Antigravity, with a CI check for drift
- Token usage and skill telemetry per account and per agent, on a built-in usage dashboard
- OpenThrottle CMS, a schema-driven content editor (more below)
- Nx + pnpm monorepo: NestJS GraphQL, React Router, BullMQ, Postgres, Redis, custom Nx generators

### OpenThrottle CMS _(in progress)_

Formerly [RocketCMS](https://rocketcms.org), now being rebuilt inside OpenThrottle. Most CMS platforms make you define content models up front. This one takes a Server Driven UI approach: the components you design define the content model. Their schemas drive a fragment editor with nested layouts, drag-to-reorder children, and a live preview.

## 🔥 On the Back Burner

- **BarGuide**: a search guide to San Francisco's 700+ bars, built around the details that matter when you pick a spot. Offline for now.

## 🤝 Let's Connect

- [LinkedIn](https://www.linkedin.com/in/MatthewScholta)
- [Portfolio](https://mattscholta.com)
- [Email](mailto:matthew.scholta@gmail.com)

<!--
## 📊 GitHub Stats

![GitHub stats](https://github-readme-stats.vercel.app/api?username=visormatt&show_icons=true&theme=dark)

![GitHub contributions](https://raw.githubusercontent.com/visormatt/visormatt/contributions/contributions-dark.svg)
-->
