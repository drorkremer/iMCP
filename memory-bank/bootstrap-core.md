# iMCP — bootstrap core

Minimum context for a fresh agent session in this project.

## What this is

iMCP is a macOS app exposing iCloud / macOS-API tools (Calendar,
Contacts, Location, Maps, Messages, Reminders, Weather, etc.) as an
MCP server for Claude Desktop and other MCP clients.

Upstream: `mattt/iMCP` (Mattt Thompson). This working copy is dror's
personal fork at `drorkremer/iMCP`; `upstream` remote tracks the
original. Local changes are reliability tweaks to the MCP connection
loop, not feature work.

For everything else — capabilities, build instructions, screenshots —
see the project README (`README.md` at repo root).

## Layer chain

`global → personal → project`. Direct child of the personal portfolio;
no sub-portfolio.

## Cairn integration notes

Migrated under cairn in session
`memory-bank/sessions/2026-05-28/migrate-personal-direct-projects.*`
(authored in the cairn-source repo, not this one).

Slug is `iMCP` (CamelCase, matching repo path and the playbook's own
example in `docs/migration-playbook.md` § Step 1). The cairn parser
does not enforce kebab-case; the convention note in the playbook is
soft.
