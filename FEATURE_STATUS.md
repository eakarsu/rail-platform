# Feature status — Rail operations & safety

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 67 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 0 | 0 | Native records/view |
| Work items & projects | records | 0 | 0 | Native records/view |
| Contacts & parties | records | 0 | 0 | Native records/view |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 0 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 0 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 0 | 0 | Native records/view |
| Reports & analytics | report | 3 | 0 | Native records/view |
| Activity & audit trail | audit | 2 | 0 | Native records/view |
| Provider connections | integration | 0 | 0 | Provider request records only |
| Crossing Program | records | 1 | 0 | Native records/view |
| Rail Crossing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Crossing Owner | records | 1 | 0 | Native records/view |
| Warning Device | records | 1 | 0 | Native records/view |
| Crossing Inspection | records | 1 | 0 | Native records/view |
| Traffic Observation | records | 1 | 0 | Native records/view |
| Crossing Project | records | 1 | 0 | Native records/view |
| Inventory Change | records | 1 | 0 | Native records/view |
| Crossing Submission | records | 1 | 0 | Native records/view |
| Operational Task | records | 1 | 0 | Native records/view |
| Rule Version | records | 1 | 0 | Native records/view |
| Document Requirement | records | 1 | 0 | Native records/view |
| Inspection change extraction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Owner responsibility review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Device record reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Project coordination brief | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Inventory discrepancy packet | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Agency submission narrative | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Evidence completeness review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Operations handoff draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rail tariff and contract library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Railcar and equipment registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Waybill ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Event and interchange timeline | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Actual placement calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Constructive placement calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Free-time calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Demurrage recalculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Storage and switching audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Empty-return rule validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bunching and carrier-delay analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Closure and force-majeure evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoice validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rail dispute package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carrier credit tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dwell alerts and lane analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Lease agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Railcar mark registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Interchange event ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Loaded empty mileage | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Daily rent calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Mileage allowance calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Utilization threshold control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bad-order day exclusion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Maintenance responsibility | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Repair invoice audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AAR rule validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Owner lessee settlement | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cash credit reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fleet counterparty analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rules & Jobs | records | 1 | 0 | Native records/view |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 67 feature pages were visited in the browser; 65 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 43 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

43 original AI entries are now grouped into **5 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
