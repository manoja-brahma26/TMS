# Brownfield Transition Plan for the Travel Management System

## 1. Transition Objective

The transition objective is to move from the current homegrown, email-driven, agency-supported TMS to an AI-first orchestration model without interrupting active travel operations, breaking system dependencies, or forcing abrupt user behavior change.

The transition must preserve business continuity while gradually introducing better intelligence, visibility, and automation.

## 2. Brownfield Principles

- preserve what already works operationally
- avoid big-bang replacement
- integrate before replacing
- keep email approvals alive during the transition period
- maintain continuity with the travel agency
- phase automation only after controls and trust are established
- run old and new workflows in parallel where required

## 3. Current-State Dependencies to Preserve

- legacy TMS data and business logic
- email-based approval habits
- travel agency ticketing and fulfillment processes
- HR entitlement and employee master integration
- finance and ERP dependencies
- policy interpretation and compliance checkpoints
- reporting and audit requirements

## 4. Coexistence Strategy

### 4.1 Legacy TMS Coexistence

The legacy TMS should remain active during early phases as:

- system of reference for historical travel records
- fallback path for unsupported scenarios
- source of selected business rules and integration behavior
- bridge for phased process replacement

New workflows should be introduced around the legacy system first, then progressively absorb responsibilities as confidence grows.

### 4.2 Email Approval Coexistence

Email-based approvals should continue during the transition. The new system should:

- ingest email approvals and map them into workflow state
- enrich approval emails with policy and trip context
- provide structured approvals through links or embedded actions where possible
- preserve audit trails across both email and platform channels

This avoids forcing immediate user behavior change while improving decision clarity.

### 4.3 Travel Agency Coexistence

The travel agency remains an operational partner throughout transition. The new system should:

- send structured booking requests to the agency
- track agency responses and service states
- support exception handling and rebooking coordination
- maintain human escalation for complex or time-sensitive cases

The goal is to improve visibility and coordination before changing the fulfillment model itself.

### 4.4 HR, Finance, and Policy Coexistence

The target solution should integrate with existing enterprise systems rather than duplicate their authority:

- HR remains the source of employee identity, grade, and entitlements
- finance and ERP remain the source for budgets, advances, and reimbursements
- policy repositories remain the authoritative source for travel rules until policy services are modernized

## 5. Transition Phases

### Phase 1: Discovery and Dependency Mapping

- identify all current travel process variants
- map integration dependencies and hidden manual steps
- document approval rules, policy exceptions, and agency touchpoints
- classify what must be preserved, improved, replaced, or deferred

### Phase 2: Assisted Overlay

- introduce AI-assisted request creation
- introduce policy explanation and approval support
- maintain existing approval and booking channels
- capture workflow telemetry and user feedback

### Phase 3: Coordinated Parallel Run

- run new orchestration layer in parallel with legacy execution
- track both system outcomes for selected use cases
- integrate structured agency coordination
- validate business rules, exceptions, and operational readiness

### Phase 4: Controlled Cutover by Process Slice

- cut over low-risk and high-volume travel scenarios first
- maintain fallback to legacy handling for exceptions
- expand to more business units and trip categories
- retire legacy functions only after acceptance criteria are met

### Phase 5: Stabilization and Decommission Planning

- stabilize operations
- confirm audit, finance, and reporting continuity
- identify residual legacy functions
- plan selective retirement of replaced capabilities

## 6. Migration Strategy

### 6.1 Data Migration

The migration should be phased, not all-at-once.

- migrate master data references first
- expose historical trip data through read access where possible
- selectively migrate high-value history used for traveler memory and reporting
- validate data quality before using it in AI-supported decisions

### 6.2 Process Migration

Processes should be migrated in slices such as:

- request creation
- policy evaluation
- approval routing
- agency coordination
- post-trip expense follow-through

This reduces operational risk compared with replacing the entire lifecycle at once.

## 7. Parallel Run Approach

Parallel run is required for confidence and operational safety.

### Parallel Run Design

- use selected business units or travel categories for pilot scope
- execute the new orchestration layer while retaining legacy fallback
- compare cycle time, compliance, approval quality, and exception handling outcomes
- capture production issues before wider rollout

### Parallel Run Exit Criteria

- workflow completion rate meets agreed target
- approval decisions are accurate and auditable
- no critical finance or policy regressions
- agency coordination is stable
- support teams are trained and ready

## 8. Cutover Approach

Cutover should be gradual and criteria-based.

### Recommended Cutover Sequence

- domestic, in-policy employee travel
- manager approvals with clear routing logic
- structured agency fulfillment tracking
- expense and reimbursement follow-through
- higher-complexity international or exception-driven cases

### Cutover Conditions

- process stability demonstrated in pilot
- business sign-off from travel, HR, finance, and compliance stakeholders
- support model active
- fallback procedures documented and tested

## 9. Testing Strategy

- system integration testing across all enterprise touchpoints
- workflow validation for normal, exception, and emergency scenarios
- policy and approval rule testing
- agent behavior validation with traceability checks
- user acceptance testing by persona
- parallel run validation using live or near-live scenarios

## 10. Support and Change Management

### Support Model

- hypercare during pilot and initial rollout
- operational monitoring for workflow and integration failures
- dedicated support path for agency and finance issues
- governance forum for policy and agent behavior tuning

### Change Management

- preserve familiar user patterns where possible
- train employees, approvers, travel desk, and finance separately
- communicate what changes, what stays the same, and when
- use pilot champions and business feedback loops

## 11. Why This Brownfield Plan Is Strong

This transition plan is strong because it accepts enterprise reality. It does not assume users, policies, agency contracts, or downstream systems can be replaced overnight.

Instead, it creates a practical modernization path that:

- improves travel operations early
- reduces disruption risk
- builds trust in AI-supported workflows
- gives Persistent control over the pace of transformation
