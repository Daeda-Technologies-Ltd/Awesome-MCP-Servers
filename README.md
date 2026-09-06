# Awesome MCP Servers for RevOps
> A curated list of MCP servers for RevOps, HubSpot admins, and CRM teams — tested and vouched for by Daeda Technologies.

Most "awesome MCP" lists are sprawling dumps of every server anyone has ever pushed to GitHub. This one is different: a short, opinionated list of **MCP servers for RevOps** — the tools we actually use day-to-day to connect AI assistants to HubSpot, CRM data, revenue systems, and the rest of the ops stack. Every entry is **well-documented, actively maintained, and useful in real workflows**, so you don't have to wade through hundreds of entries to find the good ones.

Curated by [Daeda Technologies](https://daeda.tech?utm_source=github), makers of [Daeda MCP](https://www.npmjs.com/package/daeda-mcp) — the free HubSpot MCP — and other [HubSpot marketplace apps](https://daeda.tech/app-categories/hubspot?utm_source=github). For the full write-up of why each of these made the cut, read [Awesome MCP Servers for RevOps](https://daeda.tech/blogs/awesome-mcp-servers-for-revops?utm_source=github) on daeda.tech.

---

## Contents

- [CRM & Sales](#crm--sales)
- [Automation](#automation)
- [Communication](#communication)
- [Project Management](#project-management)
- [Analytics](#analytics)
- [Knowledge & Documentation](#knowledge--documentation)
- [Revenue & Payments](#revenue--payments)
- [Contributing](#contributing)

---

## Our Quality Bar

Every server on this list meets these criteria:

**Documented** - Clear setup instructions and usage examples  
**Maintained** - Active development or stable with recent commits  
**Functional** - We've tested it and it works as described  
**Useful** - Solves a real problem, not just a proof of concept  

Servers built by Daeda are marked with a 🔶

---


## CRM & Sales

| Server | Description | Links |
|--------|-------------|-------|
| 🔶 **Daeda HubSpot MCP** | Query and interact with your HubSpot CRM — contacts, companies, deals, associations, and more. Free npm package gives any AI assistant a local, encrypted, read-only sync of your portal. The full [Daeda AI](https://daeda.tech/projects/daeda-ai/?utm_source=github) app on the HubSpot Marketplace adds Write Plans, multi-portal support, and creates HubSpot Workflow Actions. | [npm (free)](https://www.npmjs.com/package/daeda-mcp) · [Daeda AI (Marketplace)](https://daeda.tech/projects/daeda-ai/?utm_source=github) |
| **Crawdar Business Research** | Discover companies from a business brief, review criterion-level evidence and unknowns, then export CSV or JSON before a CRM import. Hosted Streamable HTTP MCP with a free, rate-limited tier and fictional sandbox. Does not write to your CRM or send outreach. | [Setup](https://crawdar.com/agents) · [API contract](https://crawdar.com/openapi.json) |

## Automation

| Server | Description | Links |
|--------|-------------|-------|
| **Zapier** | Official MCP server to connect your AI to 8,000+ apps and 30,000+ actions | [Docs](https://zapier.com/mcp) |

## Communication

| Server | Description | Links |
|--------|-------------|-------|
| **Slack** | Official MCP server. Search messages, access channels, and send notifications from AI workflows. Useful for ops automation that pings the right team when a deal closes or a ticket escalates. | [Docs](https://docs.slack.dev/ai/slack-mcp-server/) |

## Project Management

| Server | Description | Links |
|--------|-------------|-------|
| **ClickUp** | Official MCP server allowing AI agents to interact with ClickUp Workspace data - like tasks, lists, folders, and docs using natural language. | [ClickUp Docs](https://developer.clickup.com/docs/connect-an-ai-assistant-to-clickups-mcp-server) |
| **Linear** | Official Linear MCP server. Create, update, and search issues, projects, and initiatives from AI chat. Popular with ops and engineering teams running sprints who want agents keeping work in sync. | [Docs](https://linear.app/docs/mcp) |

## Analytics

| Server | Description | Links |
|--------|-------------|-------|
| **PostHog** | Official PostHog MCP server. Query analytics, manage feature flags, track errors, and run SQL insights through natural language. | [GitHub](https://github.com/PostHog/mcp) · [Docs](https://posthog.com/docs/model-context-protocol) |

## Knowledge & Documentation

| Server | Description | Links |
|--------|-------------|-------|
| **Notion** | Official Notion MCP server. Read and write Notion pages, databases, and wikis. Ideal for RevOps teams storing playbooks, deal rooms, or campaign briefs in Notion — agents can reference and update docs directly. | [Docs](https://developers.notion.com/docs/mcp) |

## Revenue & Payments

| Server | Description | Links |
|--------|-------------|-------|
| **Stripe** | Official Stripe MCP server. Query customers, subscriptions, invoices, and payment events directly from AI chat. Core for RevOps teams measuring MRR, churn, and billing health. | [Docs](https://docs.stripe.com/mcp) |


> *Know a great MCP we're missing? [Open a PR!](#contributing)*

---

## Other Awesome Lists

If you're looking for a longer, more comprehensive list, these are pretty good:

- [wong2/awesome-mcp-servers](https://github.com/wong2/awesome-mcp-servers) - Large community-maintained list
- [punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) - Another comprehensive collection
- [appcypher/awesome-mcp-servers](https://github.com/appcypher/awesome-mcp-servers) - Categorised with security notes

---

## Contributing

If you find an MCP server that you think deserves to be on this list, we'd love your help!

### How to submit

1. Fork this repository
2. Add the server to the appropriate category in this README
3. Make sure it meets our [quality bar](#our-quality-bar)
4. Open a Pull Request with a brief note on why it belongs here

### What we're looking for

- Servers you've **personally used** and found valuable
- Clear documentation and setup instructions
- Active maintenance (commits within the last 6 months)
- Solves a real workflow problem

### What we'll decline

- Abandoned projects with no recent activity
- Servers with no documentation
- Proof-of-concepts that aren't functional
- Duplicate functionality where a better option already exists on the list

---

## About

This list is maintained by [Daeda Technologies](https://daeda.tech?utm_source=github), builders of AI-powered HubSpot apps on the [HubSpot Marketplace](https://daeda.tech/app-categories/hubspot?utm_source=github). We work with MCP servers daily and keep this list because these are the ones that 10x our RevOps workflows — sharing what's useful so HubSpot admins and CRM teams don't have to find them the hard way.

For the deeper walkthrough of why each of these made the cut, read our blog post: [Awesome MCP Servers for RevOps](https://daeda.tech/blogs/awesome-mcp-servers-for-revops?utm_source=github).

If you find this useful, a ⭐ helps other RevOps folks discover it too.
