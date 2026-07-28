# Computational Phase Boundaries

## Overview

ASEB proposes that major increases in adaptive capability often occur through structural transitions rather than gradual improvement.

A system can accumulate:

- more data
- more computation
- more optimization
- more resources

without fundamentally changing its adaptive regime.

A computational phase boundary occurs when a system crosses a constraint threshold that enables a new class of transformations.

---

# Continuous improvement vs phase transition

Most optimization follows a gradual trajectory:

capability

↑

time

Small improvements accumulate.

However, some transitions are discontinuous:

capability

    |
    |
    |       ______
    |      /
    |_____/
    |
    +----------------
          time

A small structural change can unlock a large capability increase.

---

# The central hypothesis

ASEB proposes:

ΔCapability

is not always explained by:

ΔResources

Instead, large transitions occur when:

constraints are crossed

A simplified hypothesis:

ΔΛ_E → Δα → ΔC

where:

Λ_E

=
evolutionary constraint boundary

α

=
accessible adaptive regime

C

=
capability

When a constraint boundary shifts, the reachable computational space changes.

---

# The four primary boundaries

ASEB identifies four possible limiting boundaries.

## Information boundary

The system lacks access to relevant information.

Question:

> Can the system observe the variables needed for adaptation?

Examples:

- missing data
- hidden state
- incomplete feedback

---

## Representation boundary

The system cannot express the relevant distinctions.

Question:

> Can the system represent the structure needed for improvement?

Examples:

- missing abstractions
- poor latent structure
- inadequate concepts

---

## Computational boundary

The system has the representation but lacks resources to explore it.

Question:

> Can the system search the reachable space?

Examples:

- insufficient compute
- inefficient algorithms
- limited optimization

---

## Observation boundary

The system cannot detect whether its changes are successful.

Question:

> Can the system measure consequences accurately?

Examples:

- delayed feedback
- noisy environments
- inaccessible outcomes

---

# Constraint crossing

A system can remain limited even with increasing resources.

Example:

compute ↑

representation constant

The system becomes faster but does not access a larger adaptive space.

A phase transition requires crossing the active bottleneck:

constraint

↓

new reachable region

↓

new adaptive behavior

---

# The relationship to representation

Representation boundaries are often the deepest constraints.

A system may have:

high computation

poor representation

The result:

large search over a small world

A representation transition changes the geometry of the search space.

Instead of:

search harder

the system achieves:

search differently

---

# Computational geometry of adaptation

ASEB treats adaptive systems as operating inside reachable computational spaces.

A system has access to:

reachable transformations

The boundary determines:

which transformations are possible

A phase transition occurs when:

Reachable Space(t+1)

Reachable Space(t)

The system does not merely improve within a landscape.

The landscape expands.

---

# Examples of phase boundaries

## Deep learning

The important transition was not only larger datasets.

It involved:

- differentiable representations
- scalable optimization
- hardware acceleration
- architectures capable of hierarchical features

The capability increase emerged from crossing interacting constraints.

---

## AlphaZero

The breakthrough was not simply more computation.

The system combined:

- self-play
- learned representations
- search
- reinforcement learning

The architecture changed the reachable strategy space.

---

## Scientific discovery

Scientific methods created a new computational substrate for knowledge generation.

The transition:

individual reasoning

↓

collective error-correcting discovery process

changed the rate at which new knowledge could emerge.

---

# Phase boundaries and open-ended evolution

Open-ended evolution requires repeated boundary crossings.

A closed system:

same representation

↓

better optimization

↓

eventual saturation

An open system:

new representation

↓

new operators

↓

new adaptive regimes

The evolutionary process continues because the search space continues expanding.

---

# Measuring phase transitions

A potential empirical framework:

Track:

## Capability

ΔA

Did performance improve?

---

## Representation

ΔD_R*

Did meaningful distinctions expand?

---

## Permeability

ΔP_C, ΔP_E, ΔO_C

Did the system remain open to correction?

---

## Reachable computation

ΔC_R

Did the space of accessible transformations expand?

---

A strong phase transition should show:

ΔD_R* > 0

ΔC_R > 0

ΔA > 0

rather than capability improvement alone.

---

# Relationship to Ancestor Intelligence

Computational phase boundaries explain the mechanics of evolutionary transitions.

Ancestor Intelligence asks what transitions should be selected.

ASEB asks:

> what structural conditions allow those transitions to occur?

The relationship:

ASEB

↓

possible evolutionary transitions

↓

Ancestor Intelligence

↓

selection for transitions that expand future evolution

---

# Summary

ASEB proposes:

Capability growth

≠

evolutionary transition

A true computational phase boundary occurs when a system crosses a structural constraint and gains access to a new adaptive regime.

The deepest transitions are not:

more computation

but:

more reachable computation

Not:

better optimization

but:

new spaces in which optimization can occur

Compressed:

constraints define reachable computation

reachable computation defines adaptive potential

adaptive potential defines evolutionary possibility


The central research question:

> What measurable structural changes cause adaptive systems to cross into new evolutionary regimes?
