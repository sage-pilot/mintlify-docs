# Sagepilot documentation instructions

This is the Mintlify documentation site for Sagepilot and should become the source of truth for product documentation. Use this file as the local writing guide for AI tools and contributors.

## Source of truth

- Product behavior should be verified against `../agi-admin-portal` before writing detailed instructions.
- If documentation conflicts with the app, investigate the current app behavior before changing the docs.
- Navigation lives in `docs.json`.
- Pages are MDX files with YAML frontmatter.
- Use `mint dev` from this directory to preview locally.
- Use `mint broken-links` before publishing large changes.
- Follow a simple `Guides`, `API Reference`, and `Changelog` top-level structure unless there is a strong reason to add a new tab.

## Writing standards

- Write for workspace admins, support managers, support agents, and operators.
- Use active voice and second person.
- Keep headings in sentence case.
- Bold UI labels, for example: Click **Settings**.
- Use backticks for commands, paths, API fields, route names, and exact values.
- Prefer short procedural pages with clear prerequisites, steps, and expected outcomes.

## Content policy

- Do not invent product behavior. Leave a `TODO:` note when behavior needs owner confirmation.
- Do not document internal-only routes, scripts, database tables, or implementation details unless the page is explicitly for internal operators.
- Avoid exposing model names, provider internals, prompt details, hidden tools, or private integration contracts.
- Use customer-facing names: support inbox, tickets, customers, calls, AI agents, voice agents, knowledge base, Engage, journeys, templates, channels, integrations, analytics, settings.

## Mintlify setup

- Mintlify documentation index: `https://www.mintlify.com/docs/llms.txt`
- Mintlify docs MCP: `https://mintlify.com/docs/mcp`
- Mintlify authenticated MCP: `https://mcp.mintlify.com`
