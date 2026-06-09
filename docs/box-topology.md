# Box Topology

## Purpose

Box Topology defines how Boxes connect, compose, federate, and exchange streams without breaking identity fabric, data fabric, governance, or trust.

A Box is a contained fabric.

A topology is the map of how Boxes relate.

## Core thesis

```text
Box = Contained Fabric
Topology = Governed Relationship Between Boxes
Stream = Controlled Movement Between and Inside Boxes
Boundary = Trust Edge
Policy = Crossing Rule
Evidence = Proof of Crossing
```

## Why topology matters

A single Box can contain work.

A network of Boxes can contain an ecosystem.

At scale, Autonomyx must support:

- partner Boxes
- customer Boxes
- sandbox Boxes
- marketplace Boxes
- regional Boxes
- industry Boxes
- agent Boxes
- deployment Boxes
- evidence Boxes
- compliance Boxes

The topology defines how they connect.

## Box relationship types

### Parent Box

A Box that governs or contains child Boxes.

Examples:

- Autonomyx ecosystem Box
- Partner organization Box
- Enterprise customer Box

### Child Box

A Box governed within a parent boundary.

Examples:

- project Box
- tenant Box
- sandbox Box
- deployment Box

### Peer Box

A Box that relates to another Box without containment.

Examples:

- partner-to-partner collaboration
- customer-to-partner engagement
- marketplace-to-customer delivery

### Edge Box

A Box close to runtime, device, region, or customer boundary.

Examples:

- branch office Box
- factory Box
- edge cluster Box
- private-cloud Box

### Marketplace Box

A Box that publishes trusted work surfaces.

Examples:

- certified solution listing
- connector listing
- training offer
- managed service offer

## Boundary crossing rule

No stream crosses a Box boundary without:

- source identity
- target identity
- purpose
- policy
- consent or authorization where required
- audit event
- evidence link
- reconciliation path

## Stream crossing model

```text
Source Box
  ↓
Boundary Policy
  ↓
Stream Contract
  ↓
Evidence Capture
  ↓
Target Box
  ↓
Observation
  ↓
Reconciliation
```

## Box graph

Boxes form a graph, not a flat hierarchy.

```text
Autonomyx Ecosystem Box
  ├── Partner Network Box
  │     ├── Partner A Box
  │     └── Partner B Box
  ├── Marketplace Box
  │     ├── Solution Box
  │     └── Connector Box
  └── Customer Box
        ├── Sandbox Box
        ├── Production Box
        └── Evidence Box
```

But Boxes may also form peer relations:

```text
Partner Box ↔ Customer Box
Solution Box ↔ Deployment Box
Compliance Box ↔ Evidence Box
Marketplace Box ↔ Partner Box
```

## Topology constraints

A Box relation must define:

```yaml
relation:
  source_box:
  target_box:
  relation_type:
  allowed_streams:
  blocked_streams:
  policy:
  evidence_required:
  owner:
  review_required:
  expiry:
```

## Identity topology

Identity does not automatically flow across Boxes.

Identity must be mapped, delegated, federated, or scoped.

Examples:

- partner identity mapped to customer project role
- agent identity scoped to sandbox Box
- reviewer identity scoped to certification Box
- operator identity scoped to Juju model Box

## Data topology

Data does not automatically flow across Boxes.

Data crossing requires:

- classification
- purpose
- access policy
- retention rule
- lineage
- audit
- destination scope

## Governance topology

Governance loops can be local, parent-level, or federated.

```text
Local loop reconciles local Box state.
Parent loop reconciles child Box trust.
Federated loop exchanges evidence between Boxes.
```

## Runtime topology

Runtime Boxes may map to:

- Juju model
- Kubernetes namespace
- VM
- bare-metal node
- edge site
- customer tenant
- sandbox

## Marketplace topology

A marketplace listing is not just a page.

It is a Box that exposes controlled streams:

- discovery stream
- version stream
- certification stream
- support stream
- pricing stream
- installation stream
- security advisory stream

## Drift across Boxes

Cross-Box drift occurs when:

- source Box claims trust but target Box lacks evidence
- partner certification expires but marketplace listing remains active
- customer deployment runs unsupported version
- connector permission scope changes
- support owner changes without registry update

Cross-Box drift must create an issue, alert, PR, or suspension workflow.

## Final axiom

```text
A Box contains fabric.
A topology connects Boxes.
A stream moves state.
A boundary protects trust.
A policy governs crossing.
Evidence proves crossing.
```
