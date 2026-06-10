# Architecture Review Template

## Purpose

Create an executive-readable architecture review that connects system design to scalability, security, operational risk, modernization needs, and business impact.

## When to Use It

- During due diligence, platform modernization, or strategic planning
- Before major integration, migration, or cloud-native transformation work
- When leadership lacks a clear picture of current-state architecture

## Key Questions

- What are the major systems and how do they interact?
- Where are the data flows, security boundaries, and integration points?
- What limits scale, resilience, delivery speed, or integration readiness?
- Which modernization opportunities create business value or reduce risk?

## Template or Framework

### Current-State Architecture

Summarize the platform in business terms: what it does, who uses it, and what outcomes it supports.

### Major Systems

| System | Purpose | Owner | Criticality | Notes |
| --- | --- | --- | --- | --- |
|  |  |  | High / Medium / Low |  |

### Data Flows

Describe major data sources, transformations, storage locations, and downstream consumers.

### Integrations

List internal and external integrations, API dependencies, data sharing, and failure handling.

### Hosting Model

Describe cloud provider, Kubernetes usage, regions, environments, networking, CI/CD, and operational ownership.

### Scalability Limits

Identify constraints in architecture, database, queueing, compute, team operations, vendor limits, or cost model.

### Security Boundaries

Describe authentication, authorization, network boundaries, encryption, secrets, logging, and privileged access.

### Operational Risks

Identify fragile processes, manual deployments, missing runbooks, poor observability, backup gaps, or incident risks.

### Modernization Opportunities

List opportunities by business value, risk reduction, cost, complexity, and reversibility.

### Business Impact

Translate architecture findings into impact on growth, customer experience, margins, compliance, integration, or valuation.

## Expected Outcome

A concise architecture review that helps executives understand how current system design supports or constrains the business.
