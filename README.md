# WakaTime (wakatime)

WakaTime is an automated time-tracking and productivity analytics service for software developers. IDE plugins (VS Code, JetBrains, Vim, Emacs, Sublime, Xcode, Visual Studio, Eclipse, and many more) send heartbeats describing the file, project, language, branch, and editor a developer is working in, and the WakaTime API v1 aggregates that data into dashboards, summaries, stats, goals, leaderboards, and team/organization dashboards. WakaTime also offers private leaderboards, code-time-on-commit enrichment for GitHub/GitLab/Bitbucket, embeddable charts, and a full data export.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/wakatime/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/wakatime/refs/heads/main/apis.yml)

## Tags

- Developer Productivity
- Developer Tools
- Time Tracking
- Coding Analytics
- Leaderboards
- IDE Plugins
- Open Source
- Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## APIs

### WakaTime API v1

The WakaTime API v1 is a REST API for sending coding heartbeats and reading coding-activity analytics derived from those heartbeats. The API exposes user profiles, heartbeats (single, bulk, and bulk-delete), durations, summaries, stats (last_7_days, last_30_days, last_6_months, last_year, all_time), insights (by language, project, editor, OS, weekday, day, AI day), projects, per-project commits, goals, custom rules (personal and org-level), editor and machine inventories, programming languages, leaders (public and private), status bar summaries, data dumps, external durations (for non-IDE activity), org dashboards and member-level dashboards, and infrastructure meta information. Authentication is via OAuth 2.0 (authorize / token / revoke) with scopes such as read_summaries, read_stats, read_goals, read_heartbeats, write_heartbeats, read_orgs, write_orgs, and email, or via API Key (HTTP Basic auth or ?api_key=) for personal use. The default rate limit is fewer than 10 requests per second on average over any 5-minute window.

- **Human URL:** [https://wakatime.com/developers](https://wakatime.com/developers)
- **Base URL:** `https://wakatime.com/api/v1/`

#### Tags

- Time Tracking
- Coding Analytics
- Heartbeats
- Summaries
- Stats
- Goals
- Leaderboards
- Org Dashboards
- OAuth 2.0

#### Properties

- [Documentation](https://wakatime.com/developers)
- [OpenAPI](openapi/wakatime-api-v1-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wakatime-api-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wakatime-api-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Sign Up](https://wakatime.com/signup)
- [Authentication](https://wakatime.com/developers#authentication)
- [O Auth](https://wakatime.com/developers#authentication)
- [A P I Keys](https://wakatime.com/api-key)
- [Rate Limits](https://wakatime.com/developers#rate_limits)
- [Changelog](https://wakatime.com/changelog)
- [Status](https://wakatime.com/status)
- [Embeddable](https://wakatime.com/share)
- [Data Export](https://wakatime.com/settings/account)
- [Webhooks](https://wakatime.com/settings/webhooks)
- [JSON Schema](json-schema/wakatime-heartbeat-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/wakatime-summary-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/wakatime-user-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/wakatime-heartbeat-structure.json)
- [JSON-LD](json-ld/wakatime-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/wakatime-rules.yml)
- [Vocabulary](vocabulary/wakatime-vocabulary.yml)
- [Plans](plans/wakatime-plans-pricing.yml)
- [Rate Limits Policy](rate-limits/wakatime-rate-limits.yml)
- [Fin Ops](finops/wakatime-finops.yml)
- [SDK](https://github.com/wakatime/wakatime-cli)
- [C L I](https://github.com/wakatime/wakatime-cli)
- [Integrations](https://wakatime.com/integrations)
- [Embeddables](https://wakatime.com/share)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Plans](plans/wakatime-plans-pricing.yml)
- [Rate Limits](rate-limits/wakatime-rate-limits.yml)
- [Fin Ops](finops/wakatime-finops.yml)
- [Vocabulary](vocabulary/wakatime-vocabulary.yml)
- [Spectral Rules](rules/wakatime-rules.yml)
- [J S O N L D Context](json-ld/wakatime-context.jsonld)
- [Examples](examples/)
- [Website](https://wakatime.com)
- [Documentation](https://wakatime.com/developers)
- [API Reference](https://wakatime.com/developers)
- [Sign Up](https://wakatime.com/signup)
- [Login](https://wakatime.com/login)
- [Pricing](https://wakatime.com/pricing)
- [Blog](https://wakatime.com/blog)
- [Blog Content](https://github.com/wakatime/wakatime-blog)
- [Status](https://wakatime.com/status)
- [Status Repo](https://github.com/wakatime/statuspage)
- [Changelog](https://wakatime.com/changelog)
- [Support](https://wakatime.com/help)
- [Contact Support](https://wakatime.com/contact)
- [Terms of Service](https://wakatime.com/terms)
- [Privacy Policy](https://wakatime.com/privacy)
- [Legal](https://github.com/wakatime/legal)
- [GitHub Organization](https://github.com/wakatime)
- [Twitter Account](https://twitter.com/wakatime)
- [Public APIs Listing](https://github.com/public-apis/public-apis)
- [Leaderboards](https://wakatime.com/leaders)
- [Embeddable](https://wakatime.com/share)
- [Integrations](https://wakatime.com/integrations)
- [Partner Program](https://wakatime.com/partners)
- [Affiliates](https://wakatime.com/affiliates)
- [C L I](https://github.com/wakatime/wakatime-cli)
- [C L I](https://pypi.org/project/wakatime/)
- [Tools](https://github.com/wakatime/homebrew-tap)
- [Tools](https://github.com/wakatime/wakadump)
- [Tools](https://github.com/wakatime/wakaq)
- [Tools](https://github.com/wakatime/wakaq-ts)
- [Tools](https://github.com/wakatime/crackboard.dev)
- [Tools](https://github.com/wakatime/wakatime.io)
- [Plugin](https://github.com/wakatime/vscode-wakatime)
- [Plugin](https://github.com/wakatime/jetbrains-wakatime)
- [Plugin](https://github.com/wakatime/vim-wakatime)
- [Plugin](https://github.com/wakatime/vim-wakatime)
- [Plugin](https://github.com/wakatime/wakatime-mode)
- [Plugin](https://github.com/wakatime/sublime-wakatime)
- [Plugin](https://github.com/wakatime/atom-wakatime)
- [Plugin](https://github.com/wakatime/xcode-wakatime)
- [Plugin](https://github.com/wakatime/visualstudio-wakatime)
- [Plugin](https://github.com/wakatime/eclipse-wakatime)
- [Plugin](https://github.com/wakatime/netbeans-wakatime)
- [Plugin](https://github.com/wakatime/zed-wakatime)
- [Plugin](https://github.com/wakatime/notepadpp-wakatime)
- [Plugin](https://github.com/wakatime/brackets-wakatime)
- [Plugin](https://github.com/wakatime/textmate-wakatime)
- [Plugin](https://github.com/wakatime/komodo-wakatime)
- [Plugin](https://github.com/wakatime/geany-wakatime)
- [Plugin](https://github.com/wakatime/gedit-wakatime)
- [Plugin](https://github.com/wakatime/kate-wakatime)
- [Plugin](https://github.com/wakatime/WakaTime.novaextension)
- [Plugin](https://github.com/wakatime/micro-wakatime)
- [Plugin](https://github.com/wakatime/kakoune-wakatime)
- [Plugin](https://github.com/wakatime/ssms-wakatime)
- [Plugin](https://github.com/wakatime/office-wakatime)
- [Plugin](https://github.com/wakatime/delphi-wakatime)
- [Plugin](https://github.com/wakatime/coda-wakatime)
- [Plugin](https://github.com/wakatime/c9-wakatime)
- [Plugin](https://github.com/wakatime/wing-wakatime)
- [Plugin](https://github.com/wakatime/se_wakatime)
- [Plugin](https://github.com/wakatime/ida-wakatime-py)
- [Plugin](https://github.com/wakatime/eric6-wakatime)
- [Plugin](https://github.com/wakatime/macos-wakatime)
- [Plugin](https://github.com/wakatime/desktop-wakatime)
- [Plugin](https://github.com/wakatime/browser-wakatime)
- [Plugin](https://github.com/wakatime/figma-wakatime)
- [Plugin](https://github.com/wakatime/sketch-wakatime)
- [Plugin](https://github.com/wakatime/adobe-xd-wakatime)
- [Plugin](https://github.com/wakatime/blender-wakatime)
- [Plugin](https://github.com/wakatime/godot-wakatime)
- [Plugin](https://github.com/wakatime/wakatime-unity)
- [Plugin](https://github.com/wakatime/roblox-studio-wakatime)
- [Plugin](https://github.com/wakatime/obsidian-wakatime)
- [Plugin](https://github.com/wakatime/jupyterlab-wakatime)
- [Plugin](https://github.com/wakatime/zotero-wakatime)
- [Plugin](https://github.com/wakatime/discord-wakatime)
- [Plugin](https://github.com/wakatime/vencord-wakatime)
- [Plugin](https://github.com/wakatime/repl-python-wakatime)
- [Plugin](https://github.com/wakatime/processing-wakatime)
- [Plugin](https://github.com/wakatime/texstudio-wakatime)
- [Plugin](https://github.com/wakatime/reclassex-wakatime)
- [Plugin](https://github.com/wakatime/codex-wakatime)
- [Plugin](https://github.com/wakatime/claude-code-wakatime)
- [Plugin](https://github.com/wakatime/camunda-modeler-wakatime-plugin)
- [Tools](https://github.com/wakatime/wakatime-mobile)
- [Integrations](https://github.com/wakatime/slack-demo-chat)
- [Similar A P Is](https://github.com/muety/wakapi)
- [Similar A P Is](https://codestats.net/)
- [Similar A P Is](https://toggl.com/track/)
- [Tools](https://github.com/geeknees/wakatime-mcp)
- [Tools](https://github.com/geeknees/wakatime-mcp-rb)
- [Tools](https://github.com/dpshde/wakatime-mcp)
- [Tools](https://github.com/pipeworx-io/mcp-wakatime)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
