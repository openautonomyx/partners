# Certification Framework

## Purpose

Certification is the trust anchor of the Autonomyx Partner Delivery Network.

It proves that a partner, solution, connector, or deployment follows Autonomyx standards for open source commercial delivery, governance, security, operations, and customer accountability.

Certification is evidence-based. Claims are not enough.

## Certification types

### Autonomyx Certified Partner

A company or individual partner approved to participate in the delivery network.

Evidence required:

- Partner profile
- Legal entity or professional identity
- Public contact channel
- Service capability statement
- Open source compliance commitment
- Brand usage agreement

### Autonomyx Certified Delivery Partner

A partner approved to implement Autonomyx for customers.

Evidence required:

- Certified implementation staff
- Delivery lifecycle adoption
- Deployment evidence template
- Security baseline checklist
- Customer handoff process
- Support escalation path

### Autonomyx Certified Managed Partner

A partner approved to operate Autonomyx as a managed service.

Evidence required:

- Monitoring process
- Backup and recovery process
- Upgrade process
- Incident response process
- SLA definition
- Security patching process
- Customer reporting process

### Autonomyx Certified Solution

A packaged industry, functional, or horizontal solution built on Autonomyx.

Evidence required:

- Solution profile
- Supported Autonomyx versions
- Architecture diagram
- Installation guide
- Data handling statement
- Security notes
- Support owner
- License

### Autonomyx Certified Connector

A connector that integrates Autonomyx with an external system.

Evidence required:

- Connector profile
- Authentication model
- Permissions required
- Data access scope
- Error handling behavior
- Rate-limit behavior
- Security review
- Maintainer identity

### Autonomyx Certified Deployment

A customer deployment that passed the baseline conformance checks.

Evidence required:

- Deployment evidence file
- Architecture summary
- Identity setup
- Audit logging enabled
- Observability enabled
- Backup configured
- Human approval gates configured
- Policy controls enabled
- Handoff completed

## Certification levels

### Level 0: Registered

Basic network registration. No delivery authority.

### Level 1: Verified

Identity and profile verified. May appear in the public registry.

### Level 2: Certified

Evidence reviewed. May deliver or publish certified assets.

### Level 3: Advanced Certified

Proven production delivery or managed operation experience.

### Level 4: Strategic Certified

Joint roadmap, joint go-to-market, and executive-level accountability.

## Certification lifecycle

```text
Apply
  ↓
Submit evidence
  ↓
Review
  ↓
Remediate gaps
  ↓
Approve
  ↓
Publish registry status
  ↓
Annual renewal
```

## Required review criteria

Every certification review checks:

- Security
- Reliability
- Operational readiness
- Open source compliance
- Customer accountability
- Governance compatibility
- Version compatibility
- Support ownership
- Incident handling
- Documentation quality

## Certification status values

```yaml
certification_status:
  - draft
  - submitted
  - under_review
  - changes_requested
  - certified
  - suspended
  - expired
  - revoked
```

## Revocation conditions

Certification can be suspended or revoked for:

- False claims
- Unsupported forks sold as official
- Hidden proprietary lock-in
- Security negligence
- Data misuse
- Repeated failed deployments
- Customer abandonment
- Brand misuse
- Marketplace abuse
- Policy bypass

## Renewal

Certification must be renewed annually or after major platform changes.

Renewal evidence may include:

- Updated partner profile
- Recent deployment evidence
- Incident history
- Security updates
- Customer references
- Training completion
- Marketplace asset updates

## Principle

Certification is not a badge. Certification is operational responsibility.
