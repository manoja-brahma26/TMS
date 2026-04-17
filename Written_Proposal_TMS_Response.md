# Written Proposal
## Reimagining the Enterprise Travel Management System with AI at the Core

**Proposal Reference:** Response to PSL-TMS-2026-001  
**Client:** Persistent Systems Limited  
**Document Type:** Written Proposal  
**Version:** Draft 1  
**Date:** April 17, 2026

---

## 1. Executive Summary

This proposal presents a practical, AI-first, brownfield-ready approach to reimagining Persistent Systems Limited's Travel Management System (TMS) as a modern enterprise workflow platform built on the **3Cs architecture**:

- **Core:** secure, governed, observable, cost-aware AI and integration foundation
- **Context:** enterprise travel intelligence through ontology, memory, policy semantics, and context graph
- **Coordination:** end-to-end orchestration across employees, approvers, travel desk, finance, agency partners, and AI agents

Our approach is designed around one central principle: **transform the travel experience without disrupting the operating backbone that exists today**. The current TMS contains critical institutional knowledge and supports a live ecosystem of email approvals, HR entitlements, finance dependencies, agency workflows, and reporting requirements. This proposal does not treat the problem as a greenfield rebuild. It treats it as a business-critical modernization program.

We propose a phased transformation that begins with assisted intelligence and controlled orchestration, then progressively scales into AI-supported automation with strong human oversight, policy control, and measurable business outcomes. The future-state platform will simplify travel request creation, reduce approval delays, improve policy compliance, coordinate bookings more effectively, and create end-to-end lifecycle visibility from trip intent through reimbursement.

Our recommended solution is not just a better travel system. It is a reusable enterprise pattern for AI-enabled workflow modernization.

---

## 2. Understanding of the Business Problem

Persistent's current travel environment works, but it was built for an earlier operating model. The business challenge is not simply that tasks are manual. The larger issue is that the current system does not natively support context-aware AI decisioning, coordinated agentic workflows, real-time orchestration across systems, or continuous learning from travel operations.

The present state introduces several challenges:

- trip requests often begin with fragmented manual inputs
- itinerary planning is time-consuming and reactive
- approval routing depends heavily on email chains and human availability
- agency coordination is asynchronous and can slow execution
- policy enforcement is not always proactive or explainable
- travel data is fragmented across systems and channels
- users experience the travel lifecycle as disconnected steps rather than one guided journey

At the same time, the current state has strengths that must be respected:

- users are familiar with approval through email
- the external travel agency remains an important operational partner
- HR and finance integrations already anchor entitlement and budget discipline
- the legacy system contains embedded business logic and institutional knowledge

The right answer is therefore not to discard the current ecosystem, but to introduce an intelligent layer that can improve decision quality, automate routine work, and coordinate actions across systems and stakeholders in a controlled way.

---

## 3. Proposed Business Solution

We propose a next-generation TMS that delivers a guided, AI-assisted, policy-aware travel journey across the following core processes:

- trip request and intent capture
- itinerary recommendation and trip planning
- approval routing and exception handling
- agency coordination and booking tracking
- traveler support during trip execution
- expense readiness and reimbursement follow-through
- reporting, compliance, and operational insights

### 3.1 Future-State User Experience

The future solution will allow an employee to initiate travel using natural language, structured forms, or context derived from meeting schedules and project needs. The platform will pre-populate likely details using employee profile, travel history, frequent routes, policy entitlements, and schedule context.

Approvers will receive clearer, faster decisions. In-policy, low-risk travel can be automatically pre-screened and, where allowed, auto-approved. Higher-risk, exception-based, or ambiguous travel will be routed with context, rationale, and alternatives so that managers can make fast, informed decisions.

The travel agency remains a partner in the workflow, but its interaction becomes structured, tracked, and visible. Instead of opaque back-and-forth email threads, the system coordinates requests, fulfillment status, changes, and escalations through a governed orchestration layer.

Finance and reporting teams gain visibility into the entire travel lifecycle, from request through booking and reimbursement, enabling better compliance, savings analysis, and operational control.

### 3.2 Business Outcomes

The proposed business solution is expected to deliver:

- reduced effort for employees creating travel requests
- reduced approval cycle time
- improved policy compliance at the point of request
- better visibility into travel status and exception trends
- improved employee experience across the full journey
- stronger auditability and control
- a scalable foundation for extending AI-enabled workflow modernization into adjacent functions

---

## 4. Technical Architecture

Our technical solution is structured explicitly around the 3Cs.

### 4.1 Core: Enterprise AI and Integration Foundation

The Core provides the secure and governed foundation for all AI-supported travel workflows. It includes:

- enterprise identity integration for travelers, approvers, admins, travel desk, and finance users
- role-based and policy-based access controls
- API and connector framework for HR, finance, reporting, calendar, email, policy repositories, and agency channels
- model access layer with routing, logging, evaluation, and policy enforcement
- agent runtime with monitoring, traceability, and operational controls
- observability stack for requests, workflows, exceptions, agent actions, and integration performance
- cost transparency and AI usage controls
- responsible AI guardrails, audit trails, and fallback mechanisms

This layer ensures that every agentic action has a clear identity, scope, audit footprint, and approval boundary.

### 4.2 Context: Enterprise Travel Intelligence Layer

The Context layer makes AI useful and reliable by grounding it in enterprise reality. It includes:

- a travel ontology covering travelers, trips, approvals, policies, entitlements, projects, itineraries, bookings, vendors, expenses, and exceptions
- a context graph linking employees, travel history, cost centers, schedules, approvals, destinations, and financial artifacts
- traveler memory that captures historical preferences, common routes, visa status, special needs, prior exceptions, and booking behaviors
- policy semantics that define what terms such as domestic, emergency, exception, class eligibility, and per-diem mean in a consistent way
- traceable retrieval of context from enterprise systems and prior interactions

This layer reduces hallucination risk and improves consistency in recommendations, routing, and policy decisions.

### 4.3 Coordination: Enterprise Workflow Orchestration

The Coordination layer manages the work itself. It orchestrates tasks across humans, AI agents, enterprise systems, and external partners. It includes:

- end-to-end workflow engine for travel request through reimbursement
- intelligent task routing and status tracking
- human-in-the-loop approvals and override flows
- cross-channel orchestration across email, chat, portals, and agency communication channels
- exception handling and fallback routing
- reusable agent patterns for task specialization

### 4.4 Deterministic Controls

AI should accelerate travel operations, not introduce ambiguity. We therefore apply deterministic controls at critical points:

- policy checks before submission and booking
- approval gates based on risk, trip type, and financial thresholds
- exception workflows for out-of-policy or urgent travel
- confidence thresholds for AI recommendations and automated actions
- full audit trails for user actions, agent actions, and policy outcomes
- explicit human fallback when confidence or context completeness is insufficient

---

## 5. AI and Agent Design

The proposed solution uses a modular agent framework rather than one monolithic assistant. Each agent has a bounded responsibility, clear inputs, and measurable output.

### 5.1 Proposed Agent Set

- **Travel Request Assistant:** captures trip intent and builds a structured request
- **Itinerary Planning Agent:** recommends travel options based on policy, cost, timing, and preferences
- **Policy Compliance Agent:** checks eligibility, restrictions, and exception conditions
- **Approval Routing Agent:** determines approver path, reminders, delegations, and escalations
- **Agency Coordination Agent:** communicates booking requests and status updates with the travel agency
- **Traveler Support Agent:** supports changes, disruptions, and trip-related inquiries
- **Expense Readiness Agent:** helps ensure post-trip documentation and finance readiness
- **Insight and Anomaly Agent:** detects patterns, bottlenecks, unusual claims, and compliance issues

### 5.2 Human-Agent Collaboration Model

Our design keeps humans in control where business accountability matters most. AI agents support speed, consistency, and context assembly, but approval authority, policy exceptions, and ambiguous edge cases remain governed by human decision-makers unless explicitly approved for automation.

This creates a safe progression path:

- AI assists first
- AI recommends next
- AI automates selected low-risk actions only after controls are proven

---

## 6. Data and Integration Design

The solution will unify travel-related data across the existing ecosystem without requiring an all-at-once data migration on day one.

### 6.1 Primary Integration Points

- HR and employee master systems
- finance and ERP systems
- policy repositories or policy services
- email and messaging channels
- calendar and scheduling tools
- reporting and BI systems
- legacy TMS components and historical data stores
- travel agency interfaces and external booking-related channels

### 6.2 Integration Approach

We recommend an integration strategy that is API-first where available, but pragmatic where enterprise realities require hybrid patterns. This includes:

- direct APIs for modern internal systems
- event-based integrations where workflow responsiveness matters
- structured file or batch patterns where needed for finance or legacy interoperability
- managed email ingestion and action tracking during brownfield coexistence

### 6.3 Data Principles

- single logical view of the travel lifecycle
- traceable source attribution for decisions and recommendations
- data quality validation for key entitlement and policy inputs
- reusable travel context model rather than point-to-point mapping logic
- phased enrichment of context graph and memory over time

---

## 7. Delivery Plan

We recommend a phased delivery approach that reduces risk and builds organizational trust.

### Phase 1: Discover and Blueprint

- assess current-state workflows, systems, dependencies, and pain points
- validate high-value use cases and prioritize rollout scope
- define target architecture, 3Cs mapping, data model, agent model, and control framework
- establish delivery roadmap, business case, and success metrics

### Phase 2: Assisted Intelligence Foundation

- implement foundational integrations
- deploy request assistance, policy interpretation, and approval support capabilities
- preserve existing approval channels while improving decision visibility
- begin operational telemetry and quality measurement

### Phase 3: Coordinated Workflow Modernization

- introduce orchestration across request, approval, and agency coordination
- enable structured booking status tracking
- improve exception management and traveler support
- run new workflows in parallel with existing operating patterns

### Phase 4: Controlled Automation and Scale

- enable selected low-risk auto-approval and automation paths
- expand business-unit adoption
- enrich reporting, anomaly detection, and operational intelligence
- tune models, agents, and policies using real operating feedback

### Phase 5: Stabilize and Expand

- complete transition for approved scope
- optimize support model and governance
- identify adjacent workflow candidates using the same platform pattern

### 7.1 Delivery Governance

The program should be governed through:

- executive sponsor alignment
- architecture and security review gates
- product and process ownership checkpoints
- measurable acceptance criteria per phase
- readiness review before each production expansion

---

## 8. Commercials

We recommend a phased commercial model to align investment with delivery confidence and value realization.

### 8.1 Recommended Commercial Structure

- **Phase 1:** fixed-price discovery and blueprinting
- **Phases 2 to 4:** milestone-based implementation with defined deliverables and acceptance criteria
- **Phase 5 and beyond:** managed support and optimization model

### 8.2 Commercial Principles

- transparent separation of one-time implementation costs and recurring platform costs
- clear accounting of infrastructure, model usage, licensing, and support components
- explicit assumptions around agency integration complexity, legacy system readiness, and data quality
- use of reusable accelerators where they reduce effort without forcing unnecessary lock-in

### 8.3 Cost Categories to Be Estimated

- solution design and architecture
- integration development
- workflow and agent development
- data and context model implementation
- testing and environment setup
- change management and training
- production deployment and hypercare
- ongoing support and optimization

Final pricing should be confirmed after detailed discovery because brownfield complexity, legacy dependencies, and transition choices materially affect cost and schedule.

---

## 9. Risks and Mitigation

This transformation is achievable, but several risks must be actively managed.

### 9.1 Key Risks

- incomplete understanding of legacy dependencies
- inconsistent policy interpretation across systems or business teams
- low-quality or fragmented source data
- over-automation before confidence and controls are established
- resistance to change from users comfortable with current workflows
- agency integration limitations or variable response models
- unclear ownership of business rules and exception handling

### 9.2 Mitigation Approach

- begin with structured discovery and dependency mapping
- define policy semantics explicitly and validate with business stakeholders
- introduce context quality checks and source-level validation
- phase automation with clear approval boundaries
- preserve familiar channels while improving the user experience gradually
- create joint operating mechanisms with agency and internal stakeholders
- establish governance for rules, prompts, and agent behavior

---

## 10. Team Structure

The delivery team should combine business, architecture, engineering, and change leadership.

### 10.1 Proposed Core Team

- **Engagement Sponsor:** executive alignment and escalation support
- **Program Manager:** overall delivery governance, planning, and stakeholder management
- **Business Process Lead:** travel workflow redesign and value realization
- **Enterprise Architect:** end-to-end architecture and 3Cs alignment
- **AI / Agent Architect:** agent model, orchestration patterns, and controls
- **Data Architect:** ontology, context graph, semantics, and data integration design
- **Integration Lead:** internal and external system interfaces
- **Security and Governance Lead:** privacy, access, observability, and responsible AI
- **UX Lead:** employee, approver, and operations experience design
- **Engineering Team:** platform, workflow, integration, and UI implementation
- **QA and Test Lead:** test strategy, validation, and release quality
- **Change Management Lead:** training, adoption, communications, and rollout support

### 10.2 Delivery Model

The delivery model should be cross-functional, with business and technical workstreams operating together rather than sequentially. This is especially important because policy interpretation, workflow design, agent design, and integration behavior are tightly coupled in a brownfield modernization.

---

## 11. Future Vision

While the immediate scope is travel, the long-term value of this program is broader. The proposed platform establishes a repeatable enterprise pattern for AI-enabled workflow modernization using Core, Context, and Coordination as reusable layers.

Over the next 24 to 36 months, the same architectural foundation can support expansion into:

- mobility and visitor management
- employee service workflows
- procurement and approvals
- field service coordination
- internal operations with policy-heavy routing and exception handling

In this model, travel becomes the first production-grade workflow on a broader enterprise AI orchestration platform. The result is not just process automation, but a governed operating model in which people, systems, and AI agents work together with transparency and accountability.

---

## 12. Why This Proposal Is Strong

This proposal stands out because it balances ambition with operational realism.

It does not assume travel can be reimagined by replacing one UI with another. It recognizes that travel is a cross-functional process tied to identity, policy, approvals, agency fulfillment, financial controls, and user behavior. It therefore proposes a platform and transition model that can improve outcomes quickly while reducing adoption and operational risk.

The proposal is strong because it:

- treats the engagement as a true brownfield modernization
- uses the 3Cs as an implementation model, not just a framework label
- places strong emphasis on context and deterministic controls
- introduces AI through specialized, governed agents
- preserves business continuity while building toward a more intelligent operating model
- creates value beyond travel through reusable architecture

---

## 13. Conclusion

Persistent has the opportunity to turn its Travel Management System into the first AI-native workflow on a scalable enterprise architecture. The right response is one that improves the travel experience, respects the realities of the current environment, and builds a long-term platform for future workflow transformation.

Our proposed approach does exactly that. It combines business redesign, enterprise architecture, AI orchestration, data grounding, governance, and phased delivery into one practical modernization program.

The outcome is a Travel Management System that is more intelligent, more adaptive, more auditable, and better aligned to how enterprise workflows will operate in the years ahead.
