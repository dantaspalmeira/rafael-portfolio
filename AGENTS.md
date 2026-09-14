# Prototype Instructions

Run the local server yourself and open the preview in the browser available to this environment. Do not give the user server-start instructions when you can run it.

Before making substantial visual changes, use the Product Design plugin's `get-context` skill when the visual source is unclear or no longer matches the current goal. When the user gives durable prototype-specific design feedback, preferences, or decisions, record them in `AGENTS.md`.

## Portfolio direction

Use Bright TSA as the interaction and layout reference, with special attention to the supplied mobile screenshots. Preserve Rafael Palmeira's own identity, Portuguese copy, project imagery, professional history, and contact links. The intended structure is a split introduction and project deck on desktop, a stacked project stream on mobile, filterable work, an editorial about page, and a persistent compact navigation dock.

Position the copy for Lead Product Designer and Design Lead opportunities while preserving Rafael's multidisciplinary profile. Use concise, confident language grounded in strategy, hands-on craft, systems thinking, collaboration, and delivery. Use the exact user-supplied illustrated avatar for compact identity moments and keep the photographic portrait on the About page.

When implementing from a selected generated mock, treat that image as the source of truth for layout, component anatomy, density, spacing, color, typography, visible content, and hierarchy.

Build app UI in `src/`. Keep `.openai/hosting.json`, `worker/index.js`, `scripts/prepare-sites-build.mjs`, and `tests/sites-worker.test.mjs` intact so the same local prototype can be handed to Sites. Before a Sites handoff, run `npm run build` and `npm run test:sites`; the build must leave `dist/client/index.html`, `dist/server/index.js`, and `dist/.openai/hosting.json`.
