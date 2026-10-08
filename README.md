\# Home Credit - Loan Against Property (LAP) AI Voice Agent



An outbound Voice AI qualification agent designed for \*\*Home Credit\*\* using \*\*Retell AI\*\* for the AI Intern (Prompt Engineer) technical evaluation.



\## 🔗 Live Call Log \& Audio Recording

\- \*\*Retell AI Public Session\*\*: \[View Call Transcript \& Audio Recording](https://dashboard.retellai.com/org\_DCkDRYccoz8viKmu/call-history?history=call\_0295fa9065ee34b5cbb20135b73)



\---



\## 📋 Architectural Highlights

1\. \*\*7-Point Sequential Qualification Checklist\*\*:

&#x20;  - Property Type (Residential, Commercial, Industrial vs. Agricultural disqualification)

&#x20;  - Ownership Status (Sole vs Joint)

&#x20;  - Original Property Documents Availability

&#x20;  - Desired Loan Amount (<= 75 Lakhs cap enforcement)

&#x20;  - Occupation \& Income Credit Mode (Bank Transfer vs. Cash disqualification)

&#x20;  - Estimated Market Valuation

&#x20;  - Repayment Tenure (3 to 15 years)



2\. \*\*Deterministic Priority Overrides \& Safety Guards\*\*:

&#x20;  - \*\*Immediate Disqualifications\*\*: Automatically detects and terminates calls if property is agricultural, documents are unavailable, or income is received in cash.

&#x20;  - \*\*Balance Transfer Routing\*\*: Routes existing loan balance transfers and EMI refinancing inquiries directly to a specialized human transfer desk.

&#x20;  - \*\*Unavailable / Callback Logic\*\*: Gracefully handles busy customers and logs callbacks.



3\. \*\*Natural Conversational Dynamics\*\*:

&#x20;  - Spoken turns capped at 1-2 conversational sentences to avoid voice monologues.

&#x20;  - Proactive slot-filling ensures customers who provide unprompted or out-of-order details are never asked redundant questions.



\---



\## 🛠️ Tech Stack \& Platform

\- \*\*Voice Platform\*\*: Retell AI

\- \*\*LLM Engine\*\*: GPT-4o / Claude 3.5 Sonnet

\- \*\*Prompt Architecture\*\*: State-aware markdown with conditional branching and fallback safety bounds.

