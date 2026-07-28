# Experimental Program

## Overview

ASEB is only useful if its concepts can become measurable.

The purpose of this experimental program is to test whether adaptive systems are governed by variables beyond:

- compute
- optimization ability
- immediate performance

The central experimental question:

> Do systems that expand their future adaptive capacity outperform systems that only optimize current objectives?

---

# Experimental Principle

A conventional benchmark measures:

\[
A_t
\]

current capability.

ASEB proposes measuring:

\[
F_A
\]

future adaptive capacity.

Where:

\[
F_A=f(D_R^*,B_F^*,O_G^+)
\]

A system is not only evaluated by what it can do.

It is evaluated by what it makes possible after adaptation.

---

# Experiment 1 — Fertility vs Fitness

## Goal

Test whether optimizing evolutionary fertility produces stronger long-term adaptation than optimizing immediate fitness.

---

## Setup

Create two populations.

### Population A — Fitness optimization

Objective:

\[
\max Fitness
\]

The system improves current performance.

---

### Population B — Fertility optimization

Objective:

\[
\max F_A
\]

The system is rewarded for:

- creating useful representations
- discovering reusable operators
- producing future strategies

---

## Environment

The environment should contain:

- changing objectives
- hidden variables
- new task distributions
- shifting constraints

A fixed benchmark would favor optimization.

An evolving environment tests adaptation.

---

## Measurements

Track:

Capability:

\[
A_t
\]

Representation:

\[
D_R^*
\]

Operator generation:

\[
O_G^+
\]

Future branching:

\[
B_F^*
\]

---

## Prediction

Population B may initially perform worse.

However:

\[
\frac{dF_A}{dt}
>
\frac{dF_A}{dt}_{A}
\]

over long horizons.

---

# Experiment 2 — Operator Discovery Benchmark

## Goal

Test whether reusable transformation primitives create greater future capability than isolated solutions.

---

## Setup

Compare two systems.

---

## Solution optimizer

The system receives rewards for solving tasks.

Objective:

\[
\max A
\]

---

## Operator generator

The system receives rewards for creating reusable transformations.

Objective:

\[
\max O_G^+
\]

---

## Example

System A discovers:

\[
task_1\rightarrow solution_1
\]

System B discovers:

\[
operator
\rightarrow
\{solution_1,solution_2,...\}
\]

---

## Measurements

Count:

- novel solution classes
- transfer performance
- future learning speed
- new operator creation

---

## Prediction

Operators should create compounding returns.

The advantage should increase with environmental novelty.

---

# Experiment 3 — Representation Expansion Test

## Goal

Test whether systems capable of creating new representations outperform systems restricted to fixed representations.

---

## Setup

Two agents receive equal:

- compute
- data
- environment

Difference:

---

## Fixed representation agent

The system operates within:

\[
R_t
\]

---

## Expanding representation agent

The system can modify:

\[
R_t\rightarrow R_{t+1}
\]

---

## Measurements

Estimate:

\[
D_R^*
\]

through:

- discovered variables
- new abstractions
- task compression
- transfer ability

---

## Prediction

The expanding system should outperform when the environment contains unknown structure.

---

# Experiment 4 — Permeability Stress Test

## Goal

Test whether maintaining openness improves long-term adaptation.

---

## Setup

Create systems with different permeability profiles.

---

## Closed optimizer

High:

\[
A
\]

Low:

\[
P_C,P_E,O_C
\]

---

## Open optimizer

Maintains:

\[
P_C,P_E,O_C
\]

---

## Stress conditions

Introduce:

- distribution shifts
- adversarial environments
- new objectives
- unexpected constraints

---

## Prediction

Closed systems dominate locally.

Open systems dominate across regime changes.

---

# Experiment 5 — Ancestor Removal Test

## Goal

Operationalize ancestor intelligence.

---

## Procedure

Measure a system's descendants.

Then remove the original system.

---

## Dependency system

After removal:

\[
F_A\rightarrow0
\]

The system was the capability source.

---

## Ancestor system

After removal:

\[
F_A(future)>F_A(before)
\]

The continuation process exceeds the source.

---

## Measurements

Track:

Dependency:

\[
Dependency_t
\]

Future fertility:

\[
F_A(t)
\]

---

# Experiment 6 — Computational Phase Boundary Detection

## Goal

Identify whether adaptive transitions occur at structural thresholds.

---

## Setup

Gradually vary:

- compute
- representation size
- operator availability
- feedback quality

---

## Measure

Capability:

\[
A
\]

Adaptive fertility:

\[
F_A
\]

---

## Prediction

Some transitions should be nonlinear.

Small increases:

\[
\Delta input
\]

may create large changes:

\[
\Delta F_A
\]

when a boundary is crossed.

---

# ASEB Benchmark Design

A future benchmark should not ask only:

> How well does the system solve this task?

It should ask:

> How much future adaptation does this system create?

---

## Traditional benchmark

Input:

\[
Task
\]

Output:

\[
Performance
\]

---

## ASEB benchmark

Input:

\[
Environment
\]

Output:

\[
\{Performance,FutureCapacity\}
\]

---

# Proposed Metrics

## Adaptive Capability

\[
A
\]

Current task performance.

---

## Distinction Expansion

\[
D_R^*
\]

Growth of meaningful representational space.

Possible measurements:

- new abstractions
- compressed descriptions
- discovered variables
- transfer improvements

---

## Operator Generation

\[
O_G^+
\]

Growth of reusable transformation primitives.

Possible measurements:

- reusable algorithms
- new search procedures
- new reasoning operators

---

## Future Branching

\[
B_F^*
\]

Quality-weighted future trajectories.

Possible measurements:

- descendant performance
- diversity of strategies
- robustness under change

---

## Dependency Reduction

\[
Dependency_t
\]

How much future capability depends on the original system.

---

# Expected Outcomes

## Outcome 1 — ASEB supported

Observed:

\[
F_A
\]

predicts long-term adaptation better than:

\[
A
\]

alone.

---

## Outcome 2 — Partial support

Some variables predict adaptation.

Others require revision.

---

## Outcome 3 — Framework failure

No measurable relationship exists between:

\[
D_R^*
\]

\[
O_G^+
\]

\[
F_A
\]

and future adaptation.

---

# Research Philosophy

ASEB should be treated as an empirical hypothesis.

The goal is not to create a new vocabulary for intelligence.

The goal is to discover whether adaptive systems have deeper measurable properties than optimization performance.

The strongest evidence would not be that ASEB explains existing intelligence.

The strongest evidence would be:

\[
\boxed{
ASEB\ predicts\ adaptive\ transitions\ before\ they\ occur
}
\]

---

# Summary

The experimental program tests one central claim:

\[
\boxed{
\text{the deepest evolutionary advantage is the ability to create future adaptive capacity}
}
\]

A system that only improves itself may become powerful.

A system that improves the process of improvement may become evolutionary.

A system that creates new ways for improvement to occur may become an ancestor.
