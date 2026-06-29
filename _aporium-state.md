---
slug: _aporium
name: Aporium
category: knowledge-base
domain: ai-psychology
description: >
  Personal knowledge base at the intersection of AI, human psychology,
  and meaning-making. Built on the Karpathy LLM Wiki pattern.
location: ~/Library/Mobile Documents/iCloud~md~obsidian/Documents/Aporium
location_note: iCloud vault — agent dev-state at workspace/_aporium/
primary_language: markdown
languages: []
primary_framework: obsidian
frameworks: []
platform: cross-platform
repo_url: https://github.com/aporium-index/aporium-vault
repo_type: bare
default_branch: master
sensitivity: internal
has_agents_md: true
has_gitignore: true
phase: survey
status: null
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
file_version: "1.1"
---

# Aporium

## Current Focus

sisko → ADAMA rename and phase model consolidation. Branch cleanup complete. Compilation pipeline stable.

## Full Backlog

- [ ] OKF frontmatter retrofit on all 845 wiki pages
- [ ] Resolve .opencode/node_modules pollution in vault
- [ ] Ontological preface test protocol
- [ ] Decide Obsidian plugin trial sequence
- [ ] Raw provenance repair wave for Author/Source gaps
- [ ] Decide first deep research packet topic

## Blockers

None.

## Compliance Gaps

- **Wiki files not OKF conformant** — 845 files need frontmatter retrofit
- **No CI pipeline** — no automated validation for wiki files

## Long-Term Direction

Phase 1: OKF frontmatter retrofit across all wiki pages.
Phase 2: Compilation pipeline stabilization and agent-driven synthesis.
Phase 3: Public knowledge graph export.

Threshold: if the compilation pipeline can reliably produce publication-ready syntheses, promote to `outpost` phase with P0 priority for a production release sprint.

## Open Decisions

- Obsidian plugin trial sequence: Omnisearch → Recent Files → Homepage → Style Settings?
- First deep research packet: AI companionship off-ramps vs local AI infrastructure vs creative infrastructure?

## Decisions

| Date | Decision | Rationale |
|------|----------|-----------|
| 2026-06-28 | Bare git repo for dev-state | iCloud sync conflicts with full git repos |
| 2026-06-28 | ADAMA as control plane name | Distinctive, won't collide with project naming |

## Repo Notes

Aporium lives outside `workspace/` due to iCloud constraints.
Wikilinks resolve within Aporium's vault context, not ADAMA's.
Dev-state has its own git repo (`.git`) separate from the vault's bare git database (`Aporium.git/`).

## Links

- AGENTS.md
- [[Aporium Wiki|wiki/index.md]]
- [[Aporium Hot|wiki/hot.md]]
