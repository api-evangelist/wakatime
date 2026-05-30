# WakaTime (wakatime)

WakaTime is an automated time-tracking and productivity analytics service for software developers. IDE plugins (VS Code, JetBrains, Vim, Emacs, Sublime, Xcode, Visual Studio, Eclipse, and many more) send heartbeats describing the file, project, language, branch, and editor a developer is working in, and the WakaTime API v1 aggregates that data into dashboards, summaries, stats, goals, leaderboards, and team/organization dashboards. WakaTime also offers private leaderboards, code-time-on-commit enrichment for GitHub/GitLab/Bitbucket, embeddable charts, and a full data export.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/wakatime/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

Developer Productivity, Developer Tools, Time Tracking, Coding Analytics, Leaderboards, IDE Plugins, Open Source, Public APIs

## Type

- **x-type:** company
- **x-tier:** 2 (full-pipeline enrichment)
- **source:** [public-apis/public-apis](https://github.com/public-apis/public-apis) — category: Developer Productivity

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## APIs

### WakaTime API v1

The WakaTime API v1 is a REST API for sending coding heartbeats and reading coding-activity analytics derived from those heartbeats. The API exposes user profiles, heartbeats (single, bulk, bulk-delete), durations, summaries, stats (last_7_days, last_30_days, last_6_months, last_year, all_time), insights, projects, per-project commits, goals, custom rules (personal and org-level), editor and machine inventories, programming languages, leaders (public and private), status bar summaries, data dumps, external durations, org dashboards, and infrastructure meta information.

**Human URL:** [https://wakatime.com/developers](https://wakatime.com/developers)
**Base URL:** `https://wakatime.com/api/v1/`
**Version:** v1
**Authentication:** OAuth 2.0 (authorize / token / revoke) with scopes (`read_summaries`, `read_stats`, `read_goals`, `read_heartbeats`, `write_heartbeats`, `read_orgs`, `write_orgs`, `email`) or API Key (HTTP Basic / `?api_key=`)

#### Tags

Time Tracking, Coding Analytics, Heartbeats, Summaries, Stats, Goals, Leaderboards, Org Dashboards, OAuth 2.0

#### Properties

- [OpenAPI](openapi/wakatime-api-v1-openapi.yml)
- [Documentation](https://wakatime.com/developers)
- [Sign Up](https://wakatime.com/signup)
- [Authentication](https://wakatime.com/developers#authentication)
- [OAuth](https://wakatime.com/developers#authentication)
- [API Keys](https://wakatime.com/api-key)
- [Rate Limits](https://wakatime.com/developers#rate_limits)
- [Changelog](https://wakatime.com/changelog)
- [Status](https://wakatime.com/status)
- [Embeddable](https://wakatime.com/share)
- [Data Export](https://wakatime.com/settings/account)
- [Webhooks](https://wakatime.com/settings/webhooks)
- [WakaTime CLI (Go)](https://github.com/wakatime/wakatime-cli)
- [Integrations](https://wakatime.com/integrations)

## Common Properties

- [Plans](plans/wakatime-plans-pricing.yml)
- [Rate Limits](rate-limits/wakatime-rate-limits.yml)
- [FinOps](finops/wakatime-finops.yml)
- [Vocabulary](vocabulary/wakatime-vocabulary.yml)
- [Spectral Rules](rules/wakatime-rules.yml)
- [JSON-LD Context](json-ld/wakatime-context.jsonld)
- [Examples](examples/)
- [Website](https://wakatime.com)
- [Documentation](https://wakatime.com/developers)
- [Pricing](https://wakatime.com/pricing)
- [Blog](https://wakatime.com/blog)
- [Status](https://wakatime.com/status)
- [Changelog](https://wakatime.com/changelog)
- [Support](https://wakatime.com/help)
- [Terms of Service](https://wakatime.com/terms)
- [Privacy Policy](https://wakatime.com/privacy)
- [GitHub Organization](https://github.com/wakatime)
- [Twitter](https://twitter.com/wakatime)
- [Leaderboards](https://wakatime.com/leaders)
- [Embeddable Charts](https://wakatime.com/share)
- [CLI (wakatime-cli, Go)](https://github.com/wakatime/wakatime-cli)
- [CLI (wakatime PyPI wrapper)](https://pypi.org/project/wakatime/)
- [wakadump (data dump converter)](https://github.com/wakatime/wakadump)
- [WakaQ (Python background task queue)](https://github.com/wakatime/wakaq)
- [WakaQ-TS (TypeScript port)](https://github.com/wakatime/wakaq-ts)
- [Crackboard.dev (productivity leaderboard)](https://github.com/wakatime/crackboard.dev)
- [Public APIs Listing](https://github.com/public-apis/public-apis)

## IDE & App Plugins (selected)

| Editor / App | Repo |
|---|---|
| VS Code | [vscode-wakatime](https://github.com/wakatime/vscode-wakatime) |
| JetBrains (IntelliJ, PyCharm, RubyMine, PhpStorm, GoLand, Rider, WebStorm, AppCode, AndroidStudio) | [jetbrains-wakatime](https://github.com/wakatime/jetbrains-wakatime) |
| Vim / Neovim | [vim-wakatime](https://github.com/wakatime/vim-wakatime) |
| Emacs | [wakatime-mode](https://github.com/wakatime/wakatime-mode) |
| Sublime Text | [sublime-wakatime](https://github.com/wakatime/sublime-wakatime) |
| Atom | [atom-wakatime](https://github.com/wakatime/atom-wakatime) |
| Xcode | [xcode-wakatime](https://github.com/wakatime/xcode-wakatime) |
| Visual Studio | [visualstudio-wakatime](https://github.com/wakatime/visualstudio-wakatime) |
| Eclipse | [eclipse-wakatime](https://github.com/wakatime/eclipse-wakatime) |
| NetBeans | [netbeans-wakatime](https://github.com/wakatime/netbeans-wakatime) |
| Zed | [zed-wakatime](https://github.com/wakatime/zed-wakatime) |
| Notepad++ | [notepadpp-wakatime](https://github.com/wakatime/notepadpp-wakatime) |
| macOS system tray (tracks Xcode, Figma, Postman, ...) | [macos-wakatime](https://github.com/wakatime/macos-wakatime) |
| Windows & Linux system tray | [desktop-wakatime](https://github.com/wakatime/desktop-wakatime) |
| Browser (Chrome / Firefox / Edge) | [browser-wakatime](https://github.com/wakatime/browser-wakatime) |
| Figma | [figma-wakatime](https://github.com/wakatime/figma-wakatime) |
| Sketch | [sketch-wakatime](https://github.com/wakatime/sketch-wakatime) |
| Adobe XD | [adobe-xd-wakatime](https://github.com/wakatime/adobe-xd-wakatime) |
| Blender | [blender-wakatime](https://github.com/wakatime/blender-wakatime) |
| Godot | [godot-wakatime](https://github.com/wakatime/godot-wakatime) |
| Unity | [wakatime-unity](https://github.com/wakatime/wakatime-unity) |
| Roblox Studio | [roblox-studio-wakatime](https://github.com/wakatime/roblox-studio-wakatime) |
| Obsidian | [obsidian-wakatime](https://github.com/wakatime/obsidian-wakatime) |
| JupyterLab | [jupyterlab-wakatime](https://github.com/wakatime/jupyterlab-wakatime) |
| Zotero | [zotero-wakatime](https://github.com/wakatime/zotero-wakatime) |
| Discord (Vencord / BetterDiscord) | [vencord-wakatime](https://github.com/wakatime/vencord-wakatime) / [discord-wakatime](https://github.com/wakatime/discord-wakatime) |
| Claude Code (track AI coding time) | [claude-code-wakatime](https://github.com/wakatime/claude-code-wakatime) |
| Codex | [codex-wakatime](https://github.com/wakatime/codex-wakatime) |
| Camunda Modeler | [camunda-modeler-wakatime-plugin](https://github.com/wakatime/camunda-modeler-wakatime-plugin) |

(See `apis.yml` for the full list — 50+ plugins total.)

## MCP Servers

No official WakaTime MCP server is published. Third-party community implementations exist:

- [geeknees/wakatime-mcp](https://github.com/geeknees/wakatime-mcp) — Node.js, exposes WakaTime summaries over stdio
- [geeknees/wakatime-mcp-rb](https://github.com/geeknees/wakatime-mcp-rb) — Ruby implementation of the same
- [dpshde/wakatime-mcp](https://github.com/dpshde/wakatime-mcp) — MCP server for WakaTime coding statistics
- [pipeworx-io/mcp-wakatime](https://github.com/pipeworx-io/mcp-wakatime) — Another community MCP server

## Self-Hosted Alternative

- [muety/wakapi](https://github.com/muety/wakapi) — Minimalist, self-hosted, WakaTime-compatible backend for coding statistics (Go).

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [WakaTime API v1](openapi/wakatime-api-v1-openapi.yml) — 43 paths, 51 operations, 21 schemas

### JSON Schema

- [Heartbeat](json-schema/wakatime-heartbeat-schema.json) — atomic coding event sent by editor plugins
- [Summary (day)](json-schema/wakatime-summary-schema.json) — daily aggregated coding-activity summary
- [User](json-schema/wakatime-user-schema.json) — WakaTime user profile

### JSON Structure

- [Heartbeat](json-structure/wakatime-heartbeat-structure.json)

### JSON-LD

- [WakaTime Context](json-ld/wakatime-context.jsonld) — maps WakaTime entities to schema.org, FOAF, PROV, and Dublin Core

### Examples

- [Create Heartbeat](examples/wakatime-create-heartbeat-example.json)
- [List Summaries](examples/wakatime-list-summaries-example.json)
- [Get Stats (last_7_days)](examples/wakatime-get-stats-last-7-days-example.json)
- [List Leaders](examples/wakatime-list-leaders-example.json)

## Naftiko Capabilities

20 self-contained Naftiko alpha2 capability files — one per OpenAPI tag — each exposing both a REST adapter (port 8080) and an MCP adapter (port 9090) that route inline through the file's own consumes block.

### WakaTime API v1

| File | Operations | Surface |
|---|---|---|
| [users](capabilities/wakatime-api-v1-users.yaml) | 2 | Authenticated user profile + public user lookup |
| [heartbeats](capabilities/wakatime-api-v1-heartbeats.yaml) | 4 | List / create / bulk-create / bulk-delete heartbeats |
| [durations](capabilities/wakatime-api-v1-durations.yaml) | 1 | List per-day durations |
| [external-durations](capabilities/wakatime-api-v1-external-durations.yaml) | 4 | List / create / bulk-create / bulk-delete non-IDE durations |
| [summaries](capabilities/wakatime-api-v1-summaries.yaml) | 1 | Daily activity summaries between two dates |
| [stats](capabilities/wakatime-api-v1-stats.yaml) | 4 | Stats by range + named ranges + aggregated + all-time-since-today |
| [insights](capabilities/wakatime-api-v1-insights.yaml) | 1 | Curated insight slices |
| [projects](capabilities/wakatime-api-v1-projects.yaml) | 2 | List / get projects |
| [commits](capabilities/wakatime-api-v1-commits.yaml) | 2 | Per-project commit history with coding time |
| [goals](capabilities/wakatime-api-v1-goals.yaml) | 2 | List / get goals |
| [custom-rules](capabilities/wakatime-api-v1-custom-rules.yaml) | 5 | List / put / delete custom rules + progress + abort |
| [data-dumps](capabilities/wakatime-api-v1-data-dumps.yaml) | 2 | List / create data exports |
| [editors](capabilities/wakatime-api-v1-editors.yaml) | 1 | List available editor plugins |
| [languages](capabilities/wakatime-api-v1-languages.yaml) | 3 | List languages, program languages, user languages |
| [machines](capabilities/wakatime-api-v1-machines.yaml) | 1 | List user machines |
| [user-agents](capabilities/wakatime-api-v1-user-agents.yaml) | 1 | List user agents |
| [leaderboards](capabilities/wakatime-api-v1-leaderboards.yaml) | 3 | Public + private leaderboards |
| [status-bar](capabilities/wakatime-api-v1-status-bar.yaml) | 1 | Cached today stats |
| [organizations](capabilities/wakatime-api-v1-organizations.yaml) | 9 | Orgs, dashboards, members, custom rules, durations, summaries |
| [meta](capabilities/wakatime-api-v1-meta.yaml) | 1 | WakaTime infrastructure metadata |

## Plans & Pricing

[wakatime-plans-pricing.yml](plans/wakatime-plans-pricing.yml) — API Commons Plans 0.1, 5 plans:

| Plan | Monthly | Annual (per mo) | Dashboard History | Goals | Private LB |
|---|---|---|---|---|---|
| Free | $0 | $0 | 1 week | 1 | — |
| Basic | $9 | $8.25 | 2 weeks | 3 | 5 |
| Premium | $14 | $12.83 | Unlimited | Unlimited | 50 |
| Team (per developer, up to 100) | $21 | $19.25 | Unlimited | Unlimited | 100 |
| Business (per developer, 100-1,000) | $24 | $22 | Unlimited | Unlimited | 1,000 |

## Rate Limits

[wakatime-rate-limits.yml](rate-limits/wakatime-rate-limits.yml) — API Commons Rate Limits 0.1.

| Scope | Limit |
|---|---|
| Global per-user request budget | < 10 rps averaged over any 5-minute window |
| Heartbeats bulk batch size | 25 per request (POST /heartbeats.bulk) |
| External durations bulk batch size | 1,000 per request (POST /external_durations.bulk) |
| OAuth token issuance | 10 per user per hour |
| Active OAuth tokens | 8 per user |

## FinOps

[wakatime-finops.yml](finops/wakatime-finops.yml) — FOCUS 1.3 / FinOps Framework 1.0. Subscription billing per seat-month; 7 documented meters covering individual / team seats, entitlements (goals, history, leaderboard size), data dumps, and observability of API requests against the shared rate budget.

## Vocabulary

- [WakaTime Vocabulary](vocabulary/wakatime-vocabulary.yml) — 20 entities, 16 activity categories, 5 plans, 10 OAuth scopes, 6 capability axes

## Rules

- [WakaTime Spectral Ruleset](rules/wakatime-rules.yml) — 51 rules across 13 categories (info, openapi-version, servers, paths, operations, tags, parameters, request bodies, responses, schemas, security, HTTP method conventions, general quality) enforcing WakaTime API conventions: snake_case paths and properties, camelCase operationIds with verb prefixes, Title Case tags, OAuth 2.0 + API Key security schemes, `data` envelope on successful responses, and `x-microcks-operation` extensions.

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
