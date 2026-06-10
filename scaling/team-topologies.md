# Team Topologies Guide

## Purpose

Provide a practical guide for structuring engineering teams so ownership, delivery, security, data, AI, infrastructure, and platform responsibilities are clear.

## When to Use It

- Scaling engineering beyond a small founder-led team
- Reorganizing teams around products, platforms, or domains
- Reducing unclear ownership, slow delivery, or overloaded central teams
- Preparing for growth, investment, or post-close integration

## Key Questions

- Which teams own customer-facing outcomes?
- Which capabilities should be centralized for leverage or governance?
- Where does platform ownership improve speed rather than create dependency?
- Who owns security, data, AI, and infrastructure decisions?
- What structure best supports business priorities?

## Template or Framework

### Product Teams

Own customer-facing product outcomes, roadmap delivery, quality, and product-specific technical decisions.

### Platform Teams

Own shared infrastructure, developer experience, deployment systems, observability, Kubernetes, cloud foundations, and common tooling.

### Security Ownership

Security should have clear governance ownership, but execution often requires shared responsibility across product, platform, infrastructure, and leadership.

### Data/AI Ownership

Data and AI ownership should clarify data quality, model selection, governance, privacy, evaluation, cost, and human review responsibilities.

### Infrastructure Ownership

Infrastructure ownership should make cloud accounts, Kubernetes clusters, networking, reliability, cost, and incident response explicit.

### When to Centralize

Centralize when:

- specialized expertise is scarce
- consistency is critical
- risk is high
- platform investment can accelerate many teams
- governance or security requires standardization

### When to Decentralize

Decentralize when:

- product speed matters more than uniformity
- teams have enough capability to own decisions safely
- central queues create bottlenecks
- domain context is essential

### Warning Signs of Poor Structure

- No one owns production outcomes
- Platform team becomes a ticket queue
- Security appears only at the end of work
- Data and AI decisions happen without governance
- Every technical decision escalates to the CTO
- Teams optimize local delivery while breaking shared systems
- Product and engineering disagree on priorities without a decision process

## Expected Outcome

A team structure that improves ownership, speed, governance, and accountability while reducing bottlenecks and unclear decision rights.
