# Technology Risk Scoring Model

## Purpose

Define a consistent model for rating technology diligence findings by risk level, confidence, evidence strength, and business impact.

## When to Use

- Technology due diligence reports
- Portfolio company quarterly reviews
- Board technology briefings
- Post-close remediation planning
- CTO or operating partner risk registers

## Red / Yellow / Green Definitions

| Rating | Definition | Typical Interpretation |
| --- | --- | --- |
| Red | Material issue with clear operational, security, integration, scalability, financial, or business impact | Requires executive ownership, near-term action, and board visibility |
| Yellow | Moderate issue, incomplete control, unclear ownership, or improvement area | Requires management attention, timeline, and operating cadence |
| Green | No major issue found, adequate control exists, or risk is actively managed | Monitor through normal governance |

### Red Examples

- Founder or VP Engineering is the only person who can deploy, troubleshoot, or explain critical architecture.
- Production access is broad, unmanaged, or not reviewed.
- Backups exist but have not been tested.
- Manual deployments create release risk or integration fragility.
- Security logging, vulnerability management, or privileged access controls are materially incomplete.

### Yellow Examples

- Documentation exists but is incomplete or not current.
- Cloud cost visibility exists but lacks ownership or forecast discipline.
- CI/CD is partially automated but still relies on manual approval or tribal knowledge.
- AI use cases exist but governance, evaluation, or data classification is incomplete.
- Product and engineering alignment depends on informal communication rather than operating cadence.

### Green Examples

- Critical systems have documented ownership and backup operators.
- Access reviews, monitoring, incident response, and backup tests are performed on a defined cadence.
- Architecture decisions are recorded and reviewed.
- AI use cases have documented data boundaries, human oversight, and success measures.

## Confidence Levels

| Confidence | Definition | Evidence Standard |
| --- | --- | --- |
| High | Finding is strongly supported and unlikely to change with additional diligence | Three or more relevant citations, or strong evidence across two or more documents or interviews |
| Medium | Finding is supported by direct evidence but scope or impact may need validation | One to two relevant citations with direct evidence |
| Low | Finding is plausible but evidence is weak, indirect, inferred, or incomplete | Limited documentation, inconsistent interviews, or absence of evidence |

## Evidence Count Guidance

- 0 evidence items: do not present as fact; frame as open question or limitation.
- 1 evidence item: medium confidence only if direct and specific; otherwise low confidence.
- 2 evidence items: medium confidence when consistent and relevant.
- 3 or more evidence items: high confidence when evidence is direct and not duplicative.
- Multiple documents are stronger than multiple references from the same artifact.

## Business Impact Scoring

Use business impact to decide whether a technical issue matters at executive level.

| Impact Area | Business Question |
| --- | --- |
| Revenue | Could this affect sales, renewals, expansion, customer commitments, or product launch timing? |
| Customer Trust | Could this affect reliability, security perception, enterprise readiness, or customer confidence? |
| Compliance | Could this affect regulatory obligations, audit readiness, contractual commitments, or data handling? |
| Margin | Could this materially increase cloud, vendor, support, or engineering cost? |
| Integration | Could this slow or complicate acquisition integration or platform consolidation? |
| Execution | Could this reduce delivery predictability, leadership capacity, or roadmap credibility? |
| Resilience | Could this increase outage, incident, recovery, or support risk? |

## Example Findings

| Finding | Risk | Confidence | Business Impact | Rationale |
| --- | --- | --- | --- | --- |
| Critical deployment knowledge sits with one VP Engineering and is not documented | Red | High | Execution, resilience, integration | Creates operational dependency and post-close continuity risk |
| AI pilots use confidential data but no formal use case register exists | Yellow | Medium | Compliance, customer trust, AI governance | Governance gap is real, but impact depends on data scope and usage |
| Kubernetes platform has monitoring and documented escalation paths | Green | Medium | Resilience | Controls appear adequate, but should remain part of normal operating review |
| Cloud spend is rising but ownership and unit economics are unclear | Yellow | Medium | Margin | Cost risk is manageable if ownership and reporting cadence are established |
| Backups are configured but restore tests are not evidenced | Red | Medium | Resilience, customer trust | Missing restore proof creates material recovery uncertainty |

## Expected Outcome

A consistent scoring model that makes technology findings comparable, evidence-backed, and suitable for management prioritization or board review.
