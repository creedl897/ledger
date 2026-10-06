# FinOps ledger

What the AI work cost you, and what you changed because of it.

This ledger lives in the repository and is committed. It is never kept in a spreadsheet, a
chat thread, or anywhere else. It is checked as **present and current** — it is not scored
on how accurate the numbers are. An honest rough figure beats a precise invented one.

The FinOps Lead keeps it. Every member supplies their own rows.

## The plan — written in Phase 2

*Which assistant or model you use for which kind of work, and what your limit is. Three or
four lines. Revisit it in Phase 4 and say whether it held.*

| Kind of work | What we use | Why |
|---|---|---|
| High-level planning, persona definition, epics, user stories, acceptance criteria | Gemini Enterprise (Browser) | Free, no code involved, wide reasoning capacity, incurs no IDE token costs. |
| Coding, schema creation, implementation, and running tests | Antigravity IDE Agent | Direct access to workspace context, capable of editing files directly and executing tests. |
| **Tactics to keep runs narrow** | Explicit file targeting & upfront "done" criteria | Pointing to specific named files instead of entire folders and defining strict acceptance criteria beforehand to prevent agent wandering. |
| **Visibility & Monitoring** | Antigravity limits vs. Gemini Enterprise | Watch Antigravity remaining usage limits (~5-hour refresh cycle); Gemini Enterprise dashboard is administrator-only with zero end-user metrics. |
| **Quota exhaustion fallback** | 4-step hierarchy | 1. Narrow ask. 2. Move thinking to browser. 3. Use personal API key (AI Studio / OpenRouter). 4. Do it by hand and wait for refresh. |

Our limit: Antigravity free tier limits (~5-hour refresh cycles). If we hit it, we narrow the ask, switch thinking to the browser, use personal API key fallback, or complete work by hand and inform the team.

## Phase 2

| Story | Assistant used | What it used (tokens, requests, or your own estimate) | What we gave it (files, story, schema) | What we would do differently |
|---|---|---|---|---|
| US-01: Database Schema Setup | Antigravity IDE Agent | ~25,000 tokens | `config/contract_specs.yaml`, user story #1, acceptance criteria | Target single schema file directly rather than general project structure. |

## Phase 3

| Story | Assistant used | What it used (tokens, requests, or your own estimate) | What we gave it (files, story, schema) | What we would do differently |
|---|---|---|---|---|
|  |  |  |  |  |

## Phase 4

| Story | Assistant used | What it used (tokens, requests, or your own estimate) | What we gave it (files, story, schema) | What we would do differently |
|---|---|---|---|---|
|  |  |  |  |  |

## Phase 5

| Story | Assistant used | What it used (tokens, requests, or your own estimate) | What we gave it (files, story, schema) | What we would do differently |
|---|---|---|---|---|
|  |  |  |  |  |

## Phase 6

| Story | Assistant used | What it used (tokens, requests, or your own estimate) | What we gave it (files, story, schema) | What we would do differently |
|---|---|---|---|---|
|  |  |  |  |  |
