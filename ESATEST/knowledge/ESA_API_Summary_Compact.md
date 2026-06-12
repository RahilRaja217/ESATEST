# ESA API Summary (Learning Enablement)

## Purpose
This artifact supports fast, consistent answers for users who are learning Sage Embedded Services APIs. It is optimized for orientation and capability understanding first, with implementation depth only when explicitly requested.

## Executive overview
Sage Embedded Services APIs represent the interface layer for core finance capabilities in ESA. For learning-focused conversations, the most useful view is capability-first: what each API area covers, how they relate, and when to move into deeper technical detail.

## Full API group inventory
The current inventory in this learning source includes all API groups listed below.

| API group | Primary scope | Typical learning question |
| --- | --- | --- |
| Embedded Accounting | Core accounting structures and ledger-aligned records | How is accounting data organized in ESA? |
| Embedded Expense Management | Expense capture, processing, and workflows | What expense management workflows are supported? |
| Embedded Carbon Accounting | Carbon footprint tracking and reporting | How does ESA support carbon accounting? |
| Embedded Payroll | Payroll processing and integration | What payroll capabilities does ESA provide? |

## API capability map
| API area | What it covers | Why it matters for learning | Typical learning question |
| --- | --- | --- | --- |
| Embedded Accounting | Core accounting structures and ledger-aligned records | Helps explain the accounting backbone of ESA | How is accounting data organized in ESA? |
| Embedded Expense Management | Expense capture, processing, and workflows | Clarifies expense journeys and management responsibilities | What expense management workflows are supported? |
| Embedded Carbon Accounting | Carbon footprint tracking and reporting | Supports understanding of sustainability-oriented capability scope | How does ESA support carbon accounting? |
| Embedded Payroll | Payroll processing and integration | Enables clear explanation of payroll and HR outcomes | What payroll capabilities does ESA provide? |

## Recommended answer structure for API learning questions
1. Start with a short, plain-language overview of the API landscape.
2. Name the relevant API area and explain it in business terms.
3. Explain how that area connects to adjacent capabilities.
4. Offer one focused follow-up question.

## How to explain the API landscape for learning
- Capability-first framing: start with business outcomes, then map to API areas.
- Relationship framing: show how Embedded Accounting, Embedded Expense Management, Embedded Carbon Accounting, and Embedded Payroll connect.
- Terminology framing: define key terms before discussing detail.
- Depth-on-demand framing: provide implementation detail only when asked.

## Optional deep dive (only when requested)
### Implementation topics to cover
- Scope and fit: scenario alignment, capability fit, and availability context.
- Contract and mapping: entity mapping, required fields, and transformation needs.
- Security and access: access model and authorization boundaries.
- Reliability and operations: retries, idempotency, error handling, and observability.

## Common learning communication pitfalls
- Jumping to implementation detail before establishing capability context.
- Mixing API area definitions, which confuses users who are still learning.
- Using technical shorthand without explaining terminology.
- Treating an overview question as a delivery-design question.

## Standard response templates
### Learning overview template
Sage Embedded Services APIs are organized across four main areas: Embedded Accounting, Embedded Expense Management, Embedded Carbon Accounting, and Embedded Payroll. Together, these areas describe how ESA supports finance workflows and outcomes. If useful, I can break down one area in more detail and explain how it connects to the others.

### Learning deep-dive template
For this topic, the key API area is [API area]. In ESA terms, this area focuses on [plain-language purpose] and typically connects to [adjacent area/capability]. If you want, I can also provide implementation-level considerations for this area.

## If detail is missing
Based on available records, I can provide a clear learning overview of the API landscape, and I can add implementation detail if you specify the API area or workflow.

## Follow-up question bank
- Which API area should we focus on first for learning?
- Would you like a side-by-side comparison of the four API areas?
- Do you want a simple architecture-level view of how these API areas fit together?
- Should I stay at overview level, or go into implementation detail for one area?
- Are you preparing for learning, stakeholder briefing, or delivery planning?

## Suggested quick prompts
- Give me a learning overview of ESA APIs.
- Compare Embedded Accounting, Embedded Expense Management, Embedded Carbon Accounting, and Embedded Payroll in simple terms.
- Explain how the API areas fit together at a high level.
