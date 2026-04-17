# Request for Proposal
## Reimagining the Enterprise Travel Management System with AI at the Core

**RFP Reference:** PSL-TMS-2026-001  
**Issued By:** Persistent Systems Limited  
**Version:** Recommended Draft  
**Issue Date:** April 17, 2026  
**Proposal Due Date:** April 19, 2026, 11:00 AM India Time

---

## 1. Executive Summary

Persistent Systems Limited invites proposals from qualified vendors, partners, and internal solution teams to redesign its enterprise Travel Management System (TMS) as an AI-first, brownfield-ready platform aligned to the **3Cs architecture**:

- **Core:** secure, governed, observable AI and integration foundation
- **Context:** enterprise travel knowledge, semantics, memory, and decision intelligence
- **Coordination:** end-to-end orchestration across people, agents, applications, and external travel partners

The current TMS is homegrown, operationally important, and deeply integrated with email approvals, travel agency workflows, HR systems, finance platforms, policy engines, and reporting tools. It is not being replaced because it is failing. It is being reimagined because the current design is not sufficient for an AI-native operating model.

Persistent is seeking a partner that can:

- preserve what works in the current ecosystem
- modernize without disrupting active travel operations
- demonstrate a credible brownfield migration path
- embed AI safely into request, approval, booking, servicing, expense, and reporting workflows
- establish a reusable platform pattern for future enterprise workflows beyond travel

This RFP prioritizes practical transformation over conceptual vision alone. Respondents must show how their solution will deliver measurable business value while respecting current contracts, operational realities, governance requirements, and user adoption constraints.

---

## 2. Purpose of This RFP

The purpose of this RFP is to identify the solution approach, delivery model, and implementation partner best suited to design and deliver a next-generation Travel Management System that:

- improves traveler and approver experience
- reduces manual effort and turnaround time
- increases policy compliance and auditability
- improves visibility across the trip lifecycle
- supports AI-driven decision-making and automation
- operates safely within enterprise governance, privacy, and security expectations

Persistent expects respondents to submit both a strategic and an executable proposal. The winning response will combine architecture quality, business value, realism of transition, and strength of delivery.

---

## 3. Background and Current State

### 3.1 Current Environment

The existing TMS is a homegrown platform developed incrementally over time. It contains technical debt, but it also encodes real business rules, organizational practices, and integration patterns that remain essential to daily operations.

The current environment includes the following touchpoints:

- **Email-based approvals:** manager and policy approvals occur through familiar email workflows
- **External travel agency:** ticketing and booking fulfillment are handled by a contracted agency
- **HR/employee master systems:** employee grade, designation, cost center, and eligibility data
- **Finance/ERP systems:** advances, reimbursements, budget controls, and financial tracking
- **Policy engine or policy repositories:** travel entitlement and compliance rules
- **Reporting and BI tools:** spend analytics, compliance reports, and leadership dashboards
- **Calendar and scheduling systems:** meetings and project schedules that influence travel planning

### 3.2 What Must Be Preserved

Respondents should assume the following current-state strengths must be preserved or improved:

- familiar approval experience for managers and employees
- continuity of the travel agency operating model during transition
- policy enforcement and auditability
- finance traceability and budget linkage
- operational reliability for active travel requests

### 3.3 Current Pain Points

The future solution should address the following limitations:

- high manual effort in trip request creation and itinerary assembly
- limited use of historical travel patterns and traveler preferences
- slow asynchronous agency coordination
- fragmented user experience across request, booking, and reimbursement
- weak end-to-end visibility across the travel lifecycle
- approval delays and routing ambiguity
- reactive rather than proactive policy enforcement

---

## 4. Vision for the Future-State TMS

Persistent seeks a **Travel Management System of Tomorrow** that is:

- AI-first, but not AI-only
- brownfield-ready, not greenfield-dependent
- modular, governed, and observable
- centered on human-agent collaboration
- extensible beyond travel to other enterprise workflow domains

The target experience should support:

- conversational trip creation from natural language intent
- intelligent itinerary recommendations based on policy, cost, schedule, and traveler preferences
- proactive compliance checks with clear rationale and alternatives
- smart approval routing and low-risk auto-approval where appropriate
- real-time coordination with the travel agency and booking providers
- seamless handoffs between employees, approvers, travel desk, finance teams, and AI agents
- continuous learning from booking patterns, exceptions, traveler feedback, and operational outcomes

---

## 5. Architectural Foundation: The 3Cs

Respondents must explicitly map their solution to the 3Cs framework.

### 5.1 Core

The **Core** is the enterprise AI and integration foundation that must provide:

- identity, authentication, authorization, and role-based access control
- model management and runtime controls
- observability, logging, audit trails, and traceability
- token and infrastructure cost controls
- integration connectivity to enterprise systems and external providers
- data protection controls for PII and sensitive travel documents
- responsible AI controls including guardrails, evaluation, and fallback mechanisms

### 5.2 Context

The **Context** layer is the travel intelligence plane that makes AI reliable and enterprise-aware. It should include:

- a travel ontology covering trips, legs, travelers, entitlements, policies, vendors, approvals, and exceptions
- a context graph linking employees, travel history, preferences, projects, destinations, approvals, and financial data
- traveler and system memory for repeatable preferences, common routes, visa status, and prior exceptions
- shared business semantics for policy interpretation and consistent decisioning
- mechanisms for data quality, lineage, freshness, and traceable context retrieval

### 5.3 Coordination

The **Coordination** layer is where work is executed across humans, agents, systems, and external partners. It should include:

- workflow orchestration from request to reimbursement
- atomic agents for itinerary planning, policy checks, approval routing, agency communication, expense support, and risk alerts
- human-in-the-loop approvals, overrides, and escalation handling
- cross-platform orchestration across email, chat, agency systems, HR, ERP, and reporting tools
- fallback paths and deterministic checkpoints for high-impact decisions

### 5.4 Deterministic Glue

Respondents must explain where and how deterministic controls are applied, including:

- policy rules and thresholds
- approval gates
- exception workflows
- audit and compliance checkpoints
- business-rule enforcement
- confidence thresholds and fallbacks to human review

---

## 6. Scope of Work

The selected respondent will be expected to cover the following scope areas.

### 6.1 Discovery and Blueprinting

- assess current-state business processes, integrations, data, and constraints
- validate future-state use cases and business priorities
- define target architecture, transition roadmap, and delivery plan
- identify dependencies, assumptions, and critical risks

### 6.2 Solution Design

- design the target TMS aligned to the 3Cs
- define the AI architecture, agent roles, orchestration model, and control points
- define the travel data model, ontology, context graph, and integration contracts
- design user journeys across traveler, approver, travel desk, finance, and admin personas

### 6.3 Build and Integration

- implement or configure the target platform and supporting services
- integrate with legacy TMS components as needed during transition
- integrate HR, finance, policy, reporting, calendar, email, and agency touchpoints
- implement observability, security, governance, and operational controls

### 6.4 Migration and Transition

- define a phased migration strategy
- support coexistence between old and new processes during transition
- propose a parallel-run and cutover strategy with clear entry and exit criteria
- migrate relevant data and validate business continuity

### 6.5 Adoption and Change Management

- enable adoption across employees, managers, travel desk, finance, and leadership
- preserve familiar workflows where appropriate while introducing better interaction models
- define training, communications, support, and governance changes required for agentic operations

### 6.6 Post-Go-Live Support

- support stabilization and hypercare
- define operating model, SLAs, and support responsibilities
- propose roadmap options for continuous optimization and expansion

---

## 7. Functional Requirements

At a minimum, respondents must address how the solution will support the following capabilities.

### 7.1 Travel Request and Planning

- conversational and form-based trip request creation
- trip creation using purpose, schedule, location, budget, and traveler preferences
- itinerary generation with ranked options
- support for domestic and international travel scenarios
- support for multi-leg and multi-city travel

### 7.2 Policy and Compliance

- policy validation before submission and before booking
- explanation of policy violations in business language
- recommendation of compliant alternatives
- support for exceptions, waivers, and emergency travel
- auditable storage of approval rationale and policy decisions

### 7.3 Approvals

- smart routing to the correct approver based on org hierarchy, cost center, policy, and trip type
- support for email-based approvals during transition
- support for auto-approval of low-risk, in-policy scenarios
- escalations, delegations, reminders, and SLA monitoring

### 7.4 Agency and Booking Coordination

- structured communication with external travel agency channels
- booking status tracking and updates
- support for changes, cancellations, and rebooking
- management of traveler, agency, and approver interactions in one workflow

### 7.5 Expense and Reimbursement Support

- connection with finance and expense systems
- receipt and documentation support
- anomaly detection and missing-document reminders
- visibility from trip approval through reimbursement completion

### 7.6 Risk, Advisory, and Traveler Support

- destination risk and travel advisory alerts
- visa and document-awareness support
- disruption alerts for delays, cancellations, or major travel events
- traveler assistance workflows and escalation support

### 7.7 Reporting and Insights

- operational dashboards for request, approval, booking, and reimbursement flows
- compliance reporting and audit traceability
- spend analytics, savings insights, and exception trends
- adoption and agent performance metrics

---

## 8. Non-Functional Requirements

Respondents must clearly address the following non-functional requirements.

### 8.1 Security and Privacy

- protection of personally identifiable information and sensitive travel documents
- encryption in transit and at rest
- role-based and attribute-based access controls as appropriate
- data retention and deletion controls
- auditability of user and agent actions

### 8.2 Responsible AI and Governance

- explainability for recommendations and decisions
- controls against hallucination and unsupported actions
- approval thresholds for autonomous or semi-autonomous actions
- prompt, model, and policy governance
- evaluation frameworks for model quality and agent behavior

### 8.3 Reliability and Performance

- high availability and graceful degradation
- monitoring and alerting
- transaction traceability across systems and agents
- response-time expectations for key workflows
- operational support model and incident management

### 8.4 Integration and Extensibility

- API-first where feasible, with pragmatic support for event-driven, file-based, and email-based patterns where required
- modular design that can extend to other workflow domains
- portability and avoidance of unnecessary lock-in

### 8.5 Data and Context Quality

- data lineage and provenance
- freshness and synchronization strategy
- conflict resolution for inconsistent data
- versioning of ontology, policy semantics, and business rules

---

## 9. Brownfield and Transition Requirements

This is a brownfield modernization. Proposals that assume a clean-slate replacement without coexistence planning will be scored poorly.

Respondents must explain:

- how they will preserve continuity of current travel operations
- how email-based approvals will coexist with future digital workflows
- how the current travel agency model will be retained, integrated, or evolved
- how legacy data will be migrated or referenced during transition
- how old and new systems will run in parallel when needed
- how confidence will be built through pilots, checkpoints, and phased rollout

The preferred response will present a **phased transition roadmap** such as:

- Phase 1: discovery, architecture, and experience blueprint
- Phase 2: assisted AI workflows with human control
- Phase 3: limited-scope deployment and parallel run
- Phase 4: scaled rollout across business units and geographies
- Phase 5: optimization and expansion into adjacent workflows

---

## 10. Expected Deliverables

Respondents should propose deliverables at each stage. At minimum, Persistent expects:

- current-state assessment and gap analysis
- target-state architecture and 3Cs mapping
- business process redesign and future-state workflows
- integration and data architecture specifications
- ontology, context, and agent design approach
- phased implementation plan and migration strategy
- testing, quality, and acceptance approach
- change management and training plan
- support model and operating model proposal
- value realization framework with KPIs and measurement approach

If respondents recommend accelerators, reusable IP, or prebuilt components, they must identify:

- what is reusable versus custom-built
- ownership and licensing implications
- limits of reuse and any required adaptation

---

## 11. Vendor Response Instructions

Respondents must structure their proposal using the sections below.

### Section A: Executive Summary

- understanding of the business problem
- summary of recommended solution
- why the respondent is best positioned to deliver
- expected business outcomes

### Section B: Business and Operating Model

- current-state understanding and key pain points
- future-state operating model
- process redesign across request, approval, booking, servicing, and expense
- user experience by persona
- value realization and KPI assumptions

### Section C: Technical Architecture

- overall architecture and component model
- explicit mapping to Core, Context, Coordination, and deterministic glue
- AI architecture including model choices, orchestration approach, and agent design
- integration architecture across internal and external systems
- data, ontology, graph, and memory design
- security, privacy, governance, observability, and FinOps approach

### Section D: Brownfield Transition and Delivery Plan

- phased roadmap and rollout strategy
- coexistence model with legacy workflows and agency operations
- migration approach and cutover criteria
- testing, release, and environment strategy
- change management and adoption plan

### Section E: Team, Credentials, and Accelerators

- relevant experience
- proposed team and roles
- comparable programs or case studies
- frameworks, accelerators, or assets that improve delivery speed or quality

### Section F: Commercial Proposal

- pricing model and commercial assumptions
- effort estimate by phase
- schedule and milestone view
- licensing, platform, infrastructure, and third-party cost implications
- dependencies and exclusions

### Section G: Risks and Assumptions

- top program risks
- mitigation actions
- assumptions requiring Persistent validation

### Section H: Innovation and Future Vision

- differentiators of the proposed solution
- roadmap for the next 24 to 36 months
- how the platform pattern extends beyond travel

---

## 12. Demonstration Requirements

Respondents must identify **4 to 5 priority use cases** from their proposed solution and provide demonstrable flows or prototypes for the most important scenarios.

Recommended demo scenarios include:

- conversational trip creation from a meeting or business intent
- in-policy itinerary recommendation with explanation
- approval routing with auto-approval for low-risk cases
- agency coordination for booking status and changes
- expense follow-through from completed trip to reimbursement readiness

Each demo should make clear:

- the user persona
- the AI role
- where human control exists
- what enterprise systems are involved
- how policy, audit, and fallback controls are applied

---

## 13. Evaluation Criteria

Persistent will evaluate responses using the following weighted criteria.

| Evaluation Area | Weight | What Strong Responses Demonstrate |
|---|---:|---|
| Business Understanding and Value | 15% | Clear grasp of travel pain points, measurable value thesis, realistic benefits |
| Technical Architecture | 25% | Strong 3Cs mapping, sound integration design, secure and scalable AI architecture |
| Context and Intelligence Design | 15% | Credible travel ontology, context graph, memory, semantics, and decision support approach |
| Coordination and Workflow Design | 15% | Practical end-to-end orchestration with agent and human handoffs, exception handling, and controls |
| Brownfield Transition Strategy | 15% | Realistic coexistence, migration, agency integration, and phased rollout strategy |
| Team, Credentials, and Delivery Confidence | 10% | Relevant experience, strong team composition, delivery rigor |
| Commercials and Delivery Realism | 5% | Transparent pricing, reasonable assumptions, no hidden complexity |

Persistent may also consider the following cross-cutting factors:

- quality of written proposal
- credibility of assumptions
- strength of demonstrations
- clarity of differentiation

---

## 14. Proposal Presentation Format

Shortlisted respondents will be invited to present their proposal and demonstrations.

Recommended finalist session format:

- **Total time:** 15 minutes
- **Executive summary presentation:** 3 minutes
- **Solution demos:** 7 to 8 minutes
- **Q&A:** 4 to 5 minutes

Each finalist should submit:

- the full written proposal
- supporting architecture diagrams
- 3 summary slides for presentation
- demo materials for selected use cases

The 3 summary slides should cover:

- business value proposition and outcome commitment
- solution differentiation and why this approach will win
- the single most important architectural or transformation point the team wants the jury to remember

---

## 15. Submission Guidelines

- **Submission format:** PDF or PPTX, with supporting diagrams and demo references
- **Recommended page limit:** 40 pages excluding appendices
- **Submission deadline:** April 19, 2026, 11:00 AM India Time
- **Submission method:** email, shared drive, or submission portal as communicated separately

All proposals should be concise, evidence-based, and explicitly tied to the requirements in this RFP.

---

## 16. Commercial Response Expectations

Commercial responses should include:

- phase-wise effort estimate
- delivery timeline with key milestones
- staffing plan by role
- licensing and platform costs
- assumptions around infrastructure and environments
- support and hypercare assumptions
- risks that materially affect cost or timeline

Persistent prefers commercial transparency over artificially low initial estimates. Responses should distinguish clearly between:

- one-time implementation costs
- recurring platform or license costs
- third-party costs
- change requests or optional future enhancements

---

## 17. Terms and Conditions

- This RFP may be used for evaluation, training, or controlled internal selection purposes.
- Persistent reserves the right to amend timelines, scope, requirements, or evaluation criteria.
- Persistent reserves the right to accept or reject any proposal in whole or in part.
- Submission of a proposal does not guarantee selection for implementation.
- Respondents are responsible for validating assumptions called out in their submission.
- All confidential information shared during the process must be handled according to Persistent's information security policies and any applicable NDA terms.

---

## 18. Appendix A: 3Cs Quick Reference

| Layer | Role in TMS | Illustrative Components |
|---|---|---|
| Core | Secure and governed AI and integration foundation | identity, model runtime, observability, token controls, connectors, security controls |
| Context | Enterprise travel intelligence and memory | ontology, context graph, semantics, traveler memory, policy knowledge |
| Coordination | Orchestration of work across humans, agents, and systems | workflow engine, approval routing, agency coordination, exception handling, human handoffs |
| Deterministic Glue | Predictability, safety, and business control | policy rules, audit, thresholds, approval gates, fallback paths |

---

## 19. Appendix B: What Excellent Responses Will Show

The strongest responses will not just describe an AI-enabled travel platform. They will show:

- a clear understanding of why this is a brownfield transformation
- a practical path from today's email-and-agency-driven model to tomorrow's AI-coordinated workflow
- disciplined control of where AI acts autonomously and where humans remain accountable
- a strong travel context model that reduces hallucination and improves decision quality
- a solution that is valuable on day one and extensible on day one plus one

Persistent is not only selecting a TMS solution. It is selecting a partner and a pattern for how enterprise workflows will be modernized in the AI era.
