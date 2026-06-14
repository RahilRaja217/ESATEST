# ESA Architecture Summary (Learning Enablement)

## Purpose
This artifact supports fast, consistent answers for users learning Sage Embedded Services architecture. It is optimized for architecture orientation first, with implementation detail only when explicitly requested.

## Executive overview
Sage Embedded Services architecture is designed as a capability-led, integration-friendly model that enables finance experiences to be embedded into partner products. The learning-first view is layer-based: where experiences surface, how APIs orchestrate flows, which domain services provide capability, and how platform operations keep services secure and reliable.

## Full architecture area inventory
The current inventory in this learning source includes all architecture areas below.

| Architecture area | Primary scope | Typical learning question |
| --- | --- | --- |
| Experience layer | Embedded UX and channel touchpoints in partner journeys | Where does ESA appear in the end-user journey? |
| API and orchestration layer | API interfaces, workflow orchestration, and integration coordination | How do partner systems interact with ESA services? |
| Domain capability layer | Core business domains such as accounting, payroll, expense, and carbon | Which capabilities are delivered by ESA domain services? |
| Platform and operations layer | Security, environment controls, monitoring, and reliability practices | How is architecture operated securely and reliably at scale? |

## Architecture capability map
| Architecture area | What it covers | Why it matters for learning | Typical learning question |
| --- | --- | --- | --- |
| Experience layer | User journeys and embedded surfaces | Clarifies where architecture is visible to users and teams | Where does ESA appear in the end-user journey? |
| API and orchestration layer | Integration contracts and service coordination | Explains cross-system flow, dependencies, and coupling points | How do partner systems interact with ESA services? |
| Domain capability layer | Core finance domains and bounded services | Shows where core business capability is owned and delivered | Which capabilities are delivered by ESA domain services? |
| Platform and operations layer | Security, observability, reliability, and controls | Explains how architecture is operated in production safely | How is architecture operated securely and reliably at scale? |

## Recommended answer structure for architecture learning questions
1. Start with a short, plain-language architecture overview.
2. Name the relevant architecture area and explain it in business terms.
3. Explain how that area connects to adjacent layers.
4. Offer one focused follow-up question.

## How to explain the architecture landscape for learning
- Layer-first framing: start with architecture layers before details.
- Relationship framing: show how Experience, API and orchestration, Domain capability, and Platform and operations connect.
- Terminology framing: define key architecture terms before technical detail.
- Depth-on-demand framing: provide implementation detail only when asked.

## Optional deep dive (only when requested)
### Implementation topics to cover
- Service boundaries and orchestration responsibilities.
- Integration contracts, events, and dependency management.
- Security controls, identity boundaries, and access patterns.
- Reliability, observability, and operational readiness.

## Common learning communication pitfalls
- Jumping directly to implementation details before layer context.
- Mixing architecture and capability definitions in one explanation.
- Using technical shorthand without defining terms.
- Treating overview questions as implementation design questions.

## Standard response templates
### Learning overview template
Sage Embedded Services architecture is organized across four areas: Experience layer, API and orchestration layer, Domain capability layer, and Platform and operations layer. Together, these areas explain how ESA delivers capabilities, integrates with partner systems, and runs securely at scale. If useful, I can break down one area in more detail and explain how it connects to the others.

### Learning deep-dive template
For this topic, the key architecture area is [architecture area]. In ESA terms, this area focuses on [plain-language purpose] and typically connects to [adjacent layer]. If you want, I can also provide implementation-level considerations for this area.

## If detail is missing
Based on available records, I can provide a clear architecture overview and add implementation detail if you specify the architecture area or workflow.

## Follow-up question bank
- Which architecture area should we focus on first for learning?
- Would you like a side-by-side comparison of the four architecture areas?
- Do you want a simple end-to-end view of how these architecture layers fit together?
- Should I stay at overview level, or go into implementation detail for one area?
- Are you preparing for learning, stakeholder briefing, or delivery planning?

## Suggested quick prompts
- Give me a learning overview of ESA architecture.
- Compare the four architecture areas in simple terms.
- Explain how the architecture layers fit together at a high level.
