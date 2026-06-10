# Key-Person Risk Assessment

## Purpose

Identify areas where technology operations, architecture, security, vendor relationships, or delivery depend too heavily on one person.

## When to Use It

- Founder-led or small engineering organizations
- Pre-investment or acquisition diligence
- CTO transition or leadership change
- Incident review, operational scaling, or succession planning

## Key Questions

- Which systems or processes stop if one person is unavailable?
- Who has privileged access or undocumented operational knowledge?
- What architectural history is not captured anywhere?
- Which vendor or customer relationships are concentrated in one person?
- What mitigation plan reduces dependency without disrupting the business?

## Template or Framework

| Risk Area | Assessment Questions | Mitigation |
| --- | --- | --- |
| Systems Owned by One Person | Which services have one practical owner? | Assign secondary owner, document system, rotate support |
| Undocumented Processes | Which operational tasks lack written steps? | Create runbooks and validate them through another operator |
| Single-Person Deployment Knowledge | Who can deploy, rollback, or troubleshoot production? | Automate deployment, train backup, document release process |
| Vendor Relationships | Which vendors depend on one relationship owner? | Add executive sponsor, document contract and escalation paths |
| Security Access | Who has privileged access without backup or review? | Review access, add break-glass process, enforce least privilege |
| Architectural History | Which decisions live only in memory? | Create architecture decision records and system narratives |
| Founder Dependency | Which product, architecture, customer, or production decisions require the founder? | Define decision rights and transfer operational ownership |
| Mitigation Plan | What must happen in 30, 60, and 90 days? | Assign owners, deadlines, and evidence of transfer |

## Expected Outcome

A prioritized mitigation plan that reduces operational fragility, improves succession readiness, and gives investors or executives confidence that the company can scale beyond individual dependency.
