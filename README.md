# Cortex documentation

User documentation for [Cortex](https://app.oncortex.ai), published with Mintlify at
docs.oncortex.ai.

- Content is MDX; navigation and branding live in `docs.json`.
- The documentation plan (information architecture, style rules, phasing) lives in the product
  repo at `cortex/docs/mintlify-docs-plan.md`. Follow its terminology table: users read
  "filing", never "ingestion"; the analogy set (filing cabinet, librarian, tray, key) is fixed.
- No em-dashes anywhere. British English.
- Local preview: `npx mint dev` in the repo root.

Every behavioural claim (defaults, limits, formats) must be verified against the product
before publishing. Docs changes ship via PR, walked through against the live app.
