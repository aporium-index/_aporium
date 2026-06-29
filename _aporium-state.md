---
slug: _aporium
name: Aporium
category: knowledge-base
domain: ai-psychology
sensitivity: internal
primary_language: markdown
languages: []
primary_framework: obsidian
frameworks: []
platform: cross-platform
repo_url: local
repo_type: bare
default_branch: main
has_agents_md: true
has_gitignore: true
state: operational
condition: condition-green
priority: P1
criticality: tier-1
owner: josh
owner_type: human
last_active: 2026-06-28
last_checkin: 2026-06-28
timestamp: 2026-06-28
stale_threshold_days: 14
depends_on: []
depended_on_by: []
tags: [knowledge-base, obsidian, wiki, llm]
file_version: "1.0"
---

# Aporium

Personal knowledge base at the intersection of AI, human psychology, and meaning-making. Built on the Karpathy LLM Wiki pattern. Obsidian vault synced via iCloud.

## Location

`~/Library/Mobile Documents/iCloud~md~obsidian/Documents/Aporium`

Dev-state bare repo at `workspace/_aporium/`.

## Current Focus

sisko bootstrap — defining control plane standards. Branch cleanup + partial merge complete. OKF frontmatter applied to sisko files, Aporium wiki pending.

## Next Actions

- [ ] OKF frontmatter retrofit on Aporium wiki pages
- [ ] Resolve `.opencode/node_modules` pollution in vault
- [ ] Decide Obsidian plugin trial sequence

## Blockers

None.

## Open Decisions

- Obsidian plugin trial sequence: Omnisearch → Recent Files → Homepage → Style Settings?
- First deep research packet: AI companionship off-ramps vs local AI infrastructure vs creative infrastructure?

## Decisions

| Date | Decision | Rationale |
|------|----------|-----------|
| 2026-06-28 | Bare git repo for dev-state | iCloud sync conflicts with full git repos in vault |
| 2026-06-28 | Dev-state dir renamed to _aporium | Single underscore avoids markdown italic, matches sisko convention |

## Notes

Wikilinks in this file resolve within Aporium's vault context, not sisko's.

## Links

- AGENTS.md
- [[Aporium Wiki|wiki/index.md]]
- [[Aporium Hot|wiki/hot.md]]
