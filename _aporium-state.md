---
type: project
slug: _aporium
name: Aporium
category: knowledge-base
domain: ai-psychology
description: >
  Agent-maintained Obsidian knowledge base connecting algorithmic systems,
  human psychology, and meaning-making, with source ingestion, graph
  compilation, public-artifact testing, and research workflows.
location: /Users/josh/Library/Mobile Documents/iCloud~md~obsidian/Documents/Aporium
location_note: >
  iCloud-synced vault with external Git object storage and ADAMA state under
  /Users/josh/workspace/_aporium/.
primary_language: markdown
languages: [javascript, python, shell]
primary_framework: obsidian
frameworks: [dataview, quickadd]
runtimes: [obsidian, node.js, python-3]
local_models: []
interfaces: [documentation, cli]
platform: [macos, ios]
stack_categories:
  knowledge_runtime: [obsidian, markdown, wikilinks, yaml-frontmatter]
  automation: [node.js, python-3, shell]
  obsidian_plugins: [dataview, quickadd]
  test: [node-test]
repo_url: https://github.com/aporium-index/aporium-vault
repo_type: bare
default_branch: master
repo_layout: external-gitdir
submodule_count: 0
test_command: "node --test scripts/quickadd/*.test.js && node scripts/quickadd/vault-status-report.js && node scripts/quickadd/control-plane-drift-report.js"
ci: false
hardware_requirements: null
evidence_as_of: 2026-06-29
verification_scope: >
  All 34 Node tests passed; vault structure, manifests, links, project evidence
  thresholds, raw-quality flags, and control-plane count drift were checked.
  Obsidian mobile behavior, external-model workflows, browser/publication flows,
  and the full Python/PDF toolchain were not exercised.
sensitivity: internal
has_agents_md: false
has_gitignore: false
phase: survey
maturity: null
status: null
condition: condition-green
priority: P1
criticality: tier-1
owner: josh
owner_type: human
last_active: 2026-06-29
last_code_activity: 2026-06-27
last_push: 2026-06-29
last_checkin: 2026-06-29
timestamp: 2026-06-29
stale_threshold_days: 14
depends_on: []
depended_on_by: []
tags: [knowledge-base, obsidian, llm-wiki, research, publishing]
file_version: "1.3"
---

# Aporium

## Current Focus

Turn a structurally stable compiled graph into evidence-backed public tests while closing ADAMA compliance, provenance, and quote-audit debt after the 2026-06-27 branch cleanup and partial synthesis merge.

## Full Backlog

- [ ] **Top 1:** Bring the outpost interface into ADAMA compliance: add OKF metadata and state-file/commit-push shutdown guidance to root `AGENTS.md`, add `.tmp/` to `.gitignore`, and resolve the external state-file exception.
- [ ] **Top 2:** Run the controlled ontological-preface prompt-test protocol before treating SOUL, GENESIS, ETHOS, THROWN, or ATTUNEMENT scaffolds as supported interventions.
- [ ] **Top 3:** Advance the first public feedback loop: review current subreddit rules, post only the approved question-led proof-of-thinking seed, and harvest responses back into the graph.

---

- [ ] Build the first two infrastructure-legitimacy case studies with dated external evidence before making public claims.
- [ ] Continue explicit `public_status` assignment and exact-claim/quote audits, prioritizing active syntheses in the public corridor.
- [ ] Backfill local compile-decision evidence for 215 `compile_complete` manifests.
- [ ] Repair the next high-priority raw-provenance wave; 716 of 827 raw Markdown files currently trigger at least one quality flag.
- [ ] Normalize the 11 machine-like wikilinks currently missing human-readable display labels.
- [ ] Continue the book-lint production queue with Huizinga or Wittgenstein.
- [ ] Resolve the `.obsidian/community-plugins.json` versus `.obsidian/plugins.bak/` mismatch, then choose whether to trial Omnisearch, Recent Files, Homepage, and Style Settings.
- [ ] Remove the ignored 61 MB `.opencode/node_modules/` tree from the synced vault after confirming it is reproducible from `.opencode/package-lock.json`.
- [ ] Choose and validate the next deep-research packet: AI companionship off-ramps, local AI infrastructure legitimacy, creative-infrastructure keepers, or friendship infrastructure.
- [ ] Define an Aporium-specific OKF compatibility profile before attempting a repository-wide frontmatter migration.

## Blockers

None.

## Health Risks

- Public-facing pages still carry trust debt: 91 source quote placeholders, 215 compile-complete manifests without local decision evidence, and many pages that require explicit public-status or quote review before external use.
- Raw provenance remains uneven: 716 of 827 raw Markdown files trigger at least one quality flag, including 560 missing Author lines and 554 missing Source Provenance sections.
- Local checks are healthy but there is no CI; validation depends on agents running the documented commands before push.
- The ignored `.opencode/node_modules/` tree occupies roughly 61 MB inside the iCloud vault, contrary to the synced-vault/dev-state boundary, and `.tmp/` is currently untracked rather than ignored.
- State, Git objects, and content live across two repositories/locations, creating freshness and atomic-commit ambiguity for ADAMA.

## Compliance Gaps

- **Root `AGENTS.md` is only partially compliant** — `standards/okf.md` sections “Required Fields” and “Implementation” require OKF frontmatter on `AGENTS.md`; `standards/agents.md` sections “Agent Startup Protocol,” “Agent Shutdown Protocol,” and “Git: Always Commit + Push” require agents to read/update the state file and commit/push each session. Add those rules without weakening the Aporium-specific operating contract; until then `has_agents_md` remains `false`.
- **Root `.gitignore` misses `.tmp/`** — `standards/git.md` section “Repo Structure” and `standards/agents.md` section “Every Outpost Must Have” require explicit coverage of `.DS_Store`, `node_modules/`, `.venv/`, `__pycache__/`, and `.tmp/`. Add `.tmp/`; until then `has_gitignore` remains `false`.
- **The canonical state file is outside the vault repo root** — `standards/agents.md` section “Every Outpost Must Have” requires `<slug>-state.md` in the outpost root, but `_aporium-state.md` lives in `/Users/josh/workspace/_aporium/`. Either define this split-state exception in the standard or add a safe root-level pointer/canonical copy with an explicit ownership rule.
- **Aporium Markdown does not implement OKF literally** — `standards/okf.md` sections “Required Fields” and “Implementation” require `type`, `tags`, and `timestamp`. Of 3,012 tracked Markdown files, none has all required fields because Aporium uses `last_updated` and a richer type taxonomy. Define a compatibility mapping and migration scope before bulk edits.

## Long-Term Direction

Over the next 0–3 months, close the ADAMA contract gaps, remove synced dev-state, finish the controlled ontological-preface test, and reduce quote/provenance/compile-evidence debt without destabilizing the graph.

Over 3–6 months, make the compile and public-readiness gates reproducible: automated validation on push, explicit evidence for compile decisions, repeatable quote-audit packets, and at least one full public-test-to-comment-harvest loop.

Over 6–12 months, turn Aporium from an internally coherent vault into a selective public knowledge and artifact system: publish tested syntheses, build the strongest project briefs into usable tools or formats, and preserve a feedback route from audience contact back into sources and concepts.

Ask ADAMA to reassess `phase`, `maturity`, and priority when the outpost has a compliant interface, automated checks, repeatable publication evidence, and at least two public artifacts whose feedback has been routed back into the graph.

## Open Decisions

- Should ADAMA support an external state repository for iCloud outposts, or should Aporium carry a root state file/pointer?
- Should Aporium adopt literal OKF `timestamp` and type enums, or should ADAMA define an `aporium-v1` compatibility profile mapping `last_updated` and the existing page taxonomy?
- After synced dev-state cleanup, should the next Obsidian step be plugin trialing or mobile workspace tuning?
- Which deep-research packet should be validated first?

## Decisions

| Date | Decision | Rationale |
|---|---|---|
| 2026-06-29 | Keep lifecycle, priority, dependency, and ownership fields unchanged during the outpost review | These fields are ADAMA-assigned; the review found health and compliance debt but no hard blocker. |
| 2026-06-29 | Treat the external `_aporium-state.md` as canonical for this review while flagging its standards conflict | Moving the interface across repositories would be a structural decision beyond an accuracy audit. |
| 2026-06-29 | Record the existing Node test suite plus structural reports as the verification command | All 34 tests pass and the reports cover the current knowledge-graph failure modes more accurately than a build command would. |
| 2026-06-28 | Keep Git object storage and agent dev-state outside the iCloud vault | Heavy Git and generated state cause iCloud conflict and mobile reliability problems. |
| 2026-06-28 | Use ADAMA as the workspace control-plane name | The name is distinctive and avoids project-name collisions. |

## Repo Notes

- The content vault is an iCloud-synced Obsidian repository. Its `.git` is a 51-byte gitdir pointer to `/Users/josh/workspace/_aporium/Aporium.git`; do not replace it with a full `.git/` directory.
- `/Users/josh/workspace/_aporium/` is a second Git repository that tracks only this state file. It also contains untracked dev-state and the vault Git directory; stage `_aporium-state.md` explicitly rather than using `git add -A` there.
- The vault uses `master` as its only local and remote branch. `origin/master` matched `HEAD` at review time; the review/session-bridge commit was pushed on 2026-06-29.
- Markdown is the product surface. JavaScript, Python, and shell scripts provide ingestion, linting, graph reports, PDF cleanup, model-health tracking, and book-lint workflows.
- `raw/` is provenance; `wiki/` is agent-owned canon. Ingest and compile are separate passes with manifest handoff. `wiki/hot.md`, `wiki/index.md`, and `wiki/command-center.md` are the main orientation surfaces.
- Existing checks are local: `node --test scripts/quickadd/*.test.js`, `node scripts/quickadd/vault-status-report.js`, and `node scripts/quickadd/control-plane-drift-report.js`.
- The current vault worktree has an unrelated untracked `.tmp/` directory; preserve it until its ownership is known.

## Links

- [[Aporium Agent Instructions|AGENTS.md]]
- [[Aporium Repo Policy|REPO_POLICY.md]]
- [[Aporium Wiki Index|wiki/index.md]]
- [[Aporium Session Bridge|wiki/hot.md]]
- [[Aporium Command Center|wiki/command-center.md]]
- [[Aporium Pipeline|wiki/pipeline.md]]

## Template Feedback

- **Markdown-native activity is misclassified.** The prescribed `last_code_activity` command excludes every `*.md` file, but Markdown is Aporium’s primary product and most meaningful commits are Markdown-only. Add `last_content_activity` or a per-outpost configurable activity scope instead of treating “non-Markdown” as code by definition.
- **One repository record cannot represent the split topology.** Aporium has a content worktree, an external Git directory, and a separate state repository, each with its own location, remote, dirty state, and push date. Replace overloaded `repo_type`, `repo_layout`, and `location_note` fields with a `repositories`/`storage` map or add `state_location`, `git_dir`, `state_repo_url`, and separate push timestamps.
- **The state-location rule conflicts with the supplied Aporium topology.** `standards/agents.md` requires the state file in the repo root while the ADAMA template example and existing symlink intentionally place it under `workspace/_aporium/`. The standard needs an explicit external-state exception and an ownership/atomicity rule.
- **OKF needs compatibility profiles.** Aporium already has meaningful `type`, `status`, `pipeline_status`, `public_status`, source dates, and `last_updated` semantics. Literal replacement with OKF’s small type enum and universal `timestamp` would be lossy or redundant. Add schema profiles/mappings and distinguish creation time from modification time.
- **A single `test_command` is too narrow.** This outpost has unit tests, structural graph validation, provenance lint, public-readiness audits, and external/manual flows with different guarantees. Support a list of named verification commands with `kind`, `scope`, `last_run`, and result.
- **Compliance booleans hide actionable partial states.** `AGENTS.md` exists and is strong for Aporium but misses ADAMA metadata and shutdown requirements. Replace `has_agents_md`/`has_gitignore` booleans with `missing | partial | compliant`, or add machine-readable gap codes.
- **Knowledge-base health needs first-class evidence metrics.** Source count, pending manifests, quote placeholders, compile-decision evidence, unresolved links, raw-quality flags, and public-readiness counts are more informative than a generic condition. Add an optional dated `health_metrics` map or report pointer.
- **The review packet and live standard disagree on version.** This brief requires `file_version: "1.3"`, while the current `standards/outpost-state.md` template shows `1.4`. Review packets should pin the standards commit/version they target, and the validator should report version skew before edits.
- **Cross-vault links are ambiguous.** Wikilinks in this external state file are interpreted in ADAMA’s vault context, while the targets live under the Aporium vault. Define outpost-qualified link syntax or structured absolute/relative link fields so dashboard links resolve predictably.
