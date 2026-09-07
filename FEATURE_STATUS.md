# Feature status — Lending, mortgage & credit operations

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 209 pages |
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
| Documents | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 0 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 3 | 0 | Native records/view |
| Reports & analytics | report | 9 | 0 | Native records/view |
| Activity & audit trail | audit | 8 | 0 | Native records/view |
| Provider connections | integration | 2 | 0 | Provider request records only |
| Product agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fee schedule versioning | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Account transaction ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Late fee validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| NSF fee sequence analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Convenience fee review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Add-on product consent | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Military status protections | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| State cap validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Duplicate fee detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Refund amount calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Consumer notice generation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Complaint linkage | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Remediation payment tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Product fee analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Facility tranche registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Borrowing repayment ledger | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Base rate spread calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Interest day-count validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| SOFR floor fallback control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Leverage grid pricing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Unused commitment fee | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Letter-of-credit fee audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Default interest validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Agent lender fee reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Compliance certificate linkage | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Lender statement audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Correction workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Facility cost analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Investor guide library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Default loan registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Milestone deadline control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Property preservation expense | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Attorney fee validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tax insurance advances | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Conveyance condition tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claimable expense classification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Interest curtailment calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim form preparation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Investor exception remediation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supplemental claim workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reimbursement matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Unrecovered advance ledger | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Investor vendor analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Loan and investor registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Escrow transaction ledger | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tax disbursement matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Insurance disbursement matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Escrow analysis recalculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cushion-limit validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Shortage and surplus calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Force-placed insurance review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Corporate advance classification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recoverability and aging analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Suspense-account reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Servicing-transfer reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Investor claim preparation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Borrower notice evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Advance recovery ledger | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Portfolio and vendor analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Applicants | records | 2 | 0 | Native records/view |
| Risk Assessments | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Portfolio | records | 2 | 0 | Native records/view |
| Fraud Detection | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Early Warnings | records | 1 | 0 | Native records/view |
| Covenant Risk | records | 1 | 0 | Native records/view |
| Collateral | records | 1 | 0 | Native records/view |
| Compliance | records | 4 | 0 | Native records/view |
| AI Assistant | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit Bureaus | integration | 1 | 0 | Provider request records only |
| Cash Flow | records | 1 | 0 | Native records/view |
| Document OCR | records | 1 | 0 | Native records/view |
| Rules Engine | records | 1 | 0 | Native records/view |
| Approval Workflow | records | 1 | 0 | Native records/view |
| Loan Origination | records | 1 | 0 | Native records/view |
| Adverse Action | records | 1 | 0 | Native records/view |
| Model Monitoring | records | 1 | 0 | Native records/view |
| Decision Audit | records | 1 | 0 | Native records/view |
| Customer Portal | records | 1 | 0 | Native records/view |
| Loan Officer Mobile | records | 1 | 0 | Native records/view |
| Rate Sheets | records | 1 | 0 | Native records/view |
| Stress Testing | records | 1 | 0 | Native records/view |
| Examiner Reports | records | 1 | 0 | Native records/view |
| Peer Comparison Scoring | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Auto-Tier Assignment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Applicant Similarity | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Risk Mitigation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Scenario Simulation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Adverse Action Letter | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Market Rate Benchmark | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Macro Economic Impact | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predict Approval Likelihood | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Regulatory Narrative | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predictive default modeling | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Collateral aware pricing | records | 1 | 0 | Native records/view |
| Portfolio concentration analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Regulatory scenario modeling | records | 1 | 0 | Native records/view |
| Customer lifetime value modeling | records | 1 | 0 | Native records/view |
| Applicants lacks predict approval likelihood | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Export lacks generate regulatory narrative | records | 1 | 0 | Native records/view |
| Assessments lacks ai driven underwriting copilot | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| No credit bureau integrations equifax experian transunion | integration | 1 | 0 | Provider request records only |
| No workflow automation auto approval for low risk auto escal | records | 1 | 0 | Native records/view |
| Limited third party integrations no salesforce servicenow co | integration | 1 | 0 | Provider request records only |
| No loan officer mobile app | records | 1 | 0 | Native records/view |
| No webhooks | integration | 3 | 0 | Provider request records only |
| Debtor Accounts | records | 1 | 0 | Native records/view |
| Collection Campaigns | records | 1 | 0 | Native records/view |
| Payment Plans | records | 1 | 0 | Native records/view |
| Compliance Monitor | records | 1 | 0 | Native records/view |
| Risk Assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dispute Resolution | records | 1 | 0 | Native records/view |
| Payment Tracking | records | 1 | 0 | Native records/view |
| Agent Performance | records | 1 | 0 | Native records/view |
| Debt Portfolios | records | 1 | 0 | Native records/view |
| Settlement Offers | records | 1 | 0 | Native records/view |
| Contact Schedules | records | 1 | 0 | Native records/view |
| Recovery Predictions | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Score Debtor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predict Payment Likelihood | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Optimize Settlement Offer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Detect Fraud | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Analyze Payment Pattern | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Schedule Optimal Contact | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Calculator | records | 1 | 0 | Native records/view |
| Features | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| New | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Hardship program fit | records | 1 | 0 | Native records/view |
| Predictive contact strategy | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dynamic settlement optimization | records | 1 | 0 | Native records/view |
| Predictive compliance risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Debtor segmentation targeting | records | 1 | 0 | Native records/view |
| Critical only 1 ai endpoint for 30 routes missing score debt | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| No phone system integration for automated outreach sms email | integration | 1 | 0 | Provider request records only |
| Limited credit bureau integration | integration | 1 | 0 | Provider request records only |
| No automated fdcpa tcpa compliance validation engine | records | 1 | 0 | Native records/view |
| No mobile api surface | records | 1 | 0 | Native records/view |
| Regulatory alert scan | records | 1 | 0 | Native records/view |
| Coaching leaderboard | records | 1 | 0 | Native records/view |
| Results | records | 1 | 0 | Native records/view |
| Credit Risk Assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Income Verification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| DTI Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Borrower Profile Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Loan Eligibility | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Loan Product Advisor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Property Valuation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Market Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Appraisal Review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Comparable Sales Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Insurance Requirements | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Underwriting Decision | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Document Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Compliance Review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Risk Scoring | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Condition Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rate Lock Advisory | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fee Estimator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pipeline Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Workload Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rule Suggestions | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Audit Anomaly Detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Smart Notifications | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Portfolio Risk Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Title Risk Assessment | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Closing Readiness | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Loan Applications | records | 1 | 0 | Native records/view |
| Borrowers | records | 1 | 0 | Native records/view |
| Properties | records | 1 | 0 | Native records/view |
| Loan Products | records | 1 | 0 | Native records/view |
| Credit Reports | records | 1 | 0 | Native records/view |
| Income Records | records | 1 | 0 | Native records/view |
| Appraisals | records | 1 | 0 | Native records/view |
| Fee Schedules | records | 1 | 0 | Native records/view |
| Conditions | records | 1 | 0 | Native records/view |
| Pipeline | records | 1 | 0 | Native records/view |
| Underwriting Rules | records | 2 | 0 | Native records/view |
| User Management | records | 1 | 0 | Native records/view |
| Compensating factor matrix | records | 1 | 0 | Native records/view |
| Appraisal | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Asset verification | records | 1 | 0 | Native records/view |
| Borrower | records | 1 | 0 | Native records/view |
| Employment verification | records | 1 | 0 | Native records/view |
| E signature | integration | 1 | 0 | Provider request records only |
| Pricing | records | 1 | 0 | Native records/view |
| Third party | records | 1 | 0 | Native records/view |
| Title | records | 1 | 0 | Native records/view |
| Agentic | records | 1 | 0 | Native records/view |
| Autonomous | records | 1 | 0 | Native records/view |
| Realtime | records | 1 | 0 | Native records/view |
| Vision | records | 1 | 0 | Native records/view |
| Missing features | records | 1 | 0 | Native records/view |
| Production readiness | records | 1 | 0 | Native records/view |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 209 feature pages were visited in the browser; 207 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 121 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

121 original AI entries are now grouped into **7 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

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
