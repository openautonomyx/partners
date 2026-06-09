# Enforcement Policy

## Principle

Checks without enforcement are guidance.

Autonomyx standards become enforceable only when repository controls prevent bypassing the review process.

## Required branch protection

The default branch must enable:

- Require pull requests before merge
- Require approval reviews
- Require review from CODEOWNERS
- Require status checks to pass
- Dismiss stale approvals on new commits
- Require conversation resolution
- Restrict force pushes
- Restrict branch deletion

## Required workflow gates

The following checks must pass before merge:

- Markdown validation
- YAML validation
- Registry validation
- Metadata validation
- Documentation validation
- Certification validation
- Conformance validation

## RFC enforcement

Draft proposals must not be merged directly as standards.

Required path:

Draft RFC
→ Community Review
→ Technical Review
→ Governance Review
→ Approval
→ Published Standard

## Certification enforcement

A partner may not claim certification unless:

- Evidence exists
- Review completed
- Status published in registry
- Certification status equals certified

## Marketplace enforcement

Marketplace assets may be delisted when:

- Security risk exists
- Required metadata is missing
- Publisher identity cannot be verified
- Certification is suspended
- Governance violations occur

## Trust enforcement

Trust is earned through evidence.

Trust may be reduced or revoked when:

- False claims are made
- Delivery evidence is fabricated
- Security obligations are ignored
- Customers are abandoned
- Governance requirements are bypassed

## Merge policy

No direct commits to main.

All standards, certifications, governance changes, registry changes, marketplace policies, and review procedures must enter through pull requests.
