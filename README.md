# Kosmik

**Status: sunset — the product reached end of life on 31 May 2026.**

Kosmik was an infinite-canvas visual workspace and AI moodboarding app for macOS and Windows,
published by Lithium Media SAS in Paris and backed by Creandum. It organized work into spatial
"universes" grouped in shared workspaces, and combined that canvas with a built-in web browser,
web clipper, PDF reader, drawing and frames, real-time multiplayer collaboration, and AI features
including auto-tagging, AI search and AI-assisted asset discovery.

Kosmik was an early mover on local-first storage — it shipped an on-device IPFS node with
multiplayer collaboration in 2018 and a multiplayer web browser in 2022 — before consolidating
that work into Kosmik 3 in 2025.

## API surface

None. Kosmik published no API, OpenAPI/AsyncAPI definition, SDK, CLI, webhook surface or
developer portal at any point, and no `/.well-known/` discovery documents are served. The
pricing page listed "MCP integrations" as a coming-soon feature of an unreleased "Ambassador"
plan, but it never shipped.

## Wind-down

Users export data in-app rather than through an API: universes and workspaces export as ZIP
archives of their underlying files. See https://www.kosmik.app/0-wind-down-export.

## Artifacts

- `lifecycle/kosmik-lifecycle.yml` — end-of-life record, wind-down policy, product timeline
- `security/kosmik-domain-security.yml` — TLS/HSTS/DNS probe of kosmik.app
- `well-known/kosmik-well-known.yml` — `/.well-known/` probe (nothing published)
- `llms/kosmik-llms.txt` — llms.txt summary of the public surface

Backed by: creandum — https://www.kosmik.app/
