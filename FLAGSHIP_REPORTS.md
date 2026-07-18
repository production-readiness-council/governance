# Flagship Report Plan

Date: July 18, 2026

## Approved initial flagship set

The initial flagship report set is:

1. MCP servers for production AI integrations
2. Vector databases and retrieval infrastructure
3. API gateway and edge authorization layers for AI-facing services
4. Workflow orchestration for LLM applications

These topics were selected because they match the strategic constraints in `INTENTIONS.md`:

- production-relevant scope
- bounded evaluation questions
- feasible sandbox and evidence collection
- meaningful security, reliability, and operations tradeoffs
- enough depth to justify versioned, re-reviewable reports

## Scope and evidence expectations

### MCP servers for production AI integrations

Scope:

- server trust boundaries
- tool exposure controls
- deployment and operational patterns
- evidence of where MCP servers should and should not be used

Expected evidence:

- sandbox architecture records
- configuration and control-path evidence
- security and operational findings
- comparative notes on failure modes and guardrails

### Vector databases and retrieval infrastructure

Scope:

- retrieval reliability and operational fit
- indexing and update tradeoffs
- tenant and data-boundary concerns
- observability and maintenance expectations

Expected evidence:

- bounded retrieval scenarios
- latency and consistency observations
- operational complexity notes
- negative findings where retrieval assumptions fail

### API gateway and edge authorization layers for AI-facing services

Scope:

- policy enforcement boundaries
- authn/authz integration patterns
- rate limiting and edge control concerns
- operational and debugging tradeoffs

Expected evidence:

- policy-path sandbox scenarios
- failure and misconfiguration findings
- observability notes
- guardrail recommendations for production use

### Workflow orchestration for LLM applications

Scope:

- workflow durability and state handling
- failure recovery and operator visibility
- coupling between orchestration and model/application logic
- where orchestration adds or removes production risk

Expected evidence:

- multi-step workflow sandbox scenarios
- retry and recovery observations
- operational cost and complexity notes
- clear non-fit cases

## Working-group ownership

The intended owning Working Groups are:

- MCP servers for production AI integrations -> Agentic AI Infrastructure
- Vector databases and retrieval infrastructure -> Enterprise Adoption with support from Observability and Reliability
- API gateway and edge authorization layers for AI-facing services -> Security and Identity
- Workflow orchestration for LLM applications -> Agentic AI Infrastructure with support from Observability and Reliability

## Review-panel requirements

Each flagship report requires:

- a report-scoped review panel before publication decision
- at least one non-conflicted reviewer whose recommendation is recorded
- explicit conflict disclosure for assigned reviewers
- publication decision authority consistent with the Technical Council model

## Notes

These topics are approved as the initial flagship set. Publication remains contingent on actual evidence, draft quality, and review independence.
