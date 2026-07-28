# Testable Hypotheses

## Overview

ASEB is a structural framework for studying adaptive systems.

The purpose of formal hypotheses is not to prove the framework.

The purpose is to identify where ASEB makes predictions that differ from simpler explanations based on:

- compute
- optimization
- information
- performance improvement

The central question:

> Do systems become more evolutionarily capable by becoming better optimizers, or by becoming better at creating new adaptive possibilities?

---

# Hypothesis 1 — Capability is not sufficient for evolutionary expansion

## Claim

A system can increase capability while decreasing evolutionary fertility.

Formally:

\[
\Delta A > 0
\]

does not imply:

\[
\Delta F_A > 0
\]

where:

\[
F_A=f(D_R^*,B_F^*,O_G^+)
\]

---

## Prediction

Systems optimized only for immediate performance may eventually show:

\[
A\uparrow
\]

while:

\[
D_R^*,O_G^+,B_F^*\rightarrow constant
\]

or decrease.

---

## Example

A highly optimized model may become extremely effective at a fixed task while losing:

- representation flexibility
- ability to discover new objectives
- ability to revise assumptions

---

## Falsification

If capability growth consistently predicts future adaptive expansion across all tested systems, the distinction weakens.

---

# Hypothesis 2 — Representation expansion precedes major capability transitions

## Claim

Large adaptive jumps require increases in meaningful representational dimensionality.

Prediction:

\[
\Delta D_R^*>0
\]

should appear before or during major capability transitions.

---

## Examples

Potential historical cases:

### Language

Transition:

\[
\text{private cognition}
\rightarrow
\text{shared symbolic cognition}
\]

---

### Mathematics

Transition:

\[
\text{objects}
\rightarrow
\text{abstract structures}
\]

---

### Programming

Transition:

\[
\text{machine operation}
\rightarrow
\text{machine generation}
\]

---

## Falsification

Find major adaptive transitions where:

\[
\Delta D_R^*\approx0
\]

and only resource scaling explains the improvement.

---

# Hypothesis 3 — Operator generation predicts open-ended evolution

## Claim

The ability to create reusable transformation primitives is a key driver of long-term adaptive growth.

Variable:

\[
O_G^+
\]

---

## Prediction

Systems with higher operator-generating capacity should create:

- more future strategies
- more diverse solution classes
- more adaptive descendants

than systems with equal compute but fixed operators.

---

## Experimental design

Create two artificial populations:

System A:

\[
\max A
\]

Optimizes immediate fitness.

System B:

\[
\max O_G^+
\]

Optimizes creation of reusable transformation primitives.

Prediction:

System B should eventually outperform System A in environments requiring novelty.

---

## Falsification

If operator generation provides no long-term advantage over direct optimization, the operator hypothesis weakens.

---

# Hypothesis 4 — Evolutionary phase boundaries correspond to constraint crossings

## Claim

Major transitions occur when systems cross limiting constraints.

Candidate constraints:

\[
H_t(S)
=
[H_I,H_R,H_C,H_O]
\]

---

## Prediction

A capability jump should correspond to a measurable change in one or more horizons:

Information:

\[
\Delta H_I
\]

Representation:

\[
\Delta H_R
\]

Computation:

\[
\Delta H_C
\]

Observation:

\[
\Delta H_O
\]

---

## Example

A system may not improve because:

\[
H_R
\]

is limiting.

Adding more computation produces little change.

A new representation crosses the boundary:

\[
H_R\uparrow
\]

and capability changes rapidly.

---

## Falsification

If smooth resource scaling explains all observed transitions without constraint changes, phase boundaries are unnecessary.

---

# Hypothesis 5 — Permeability predicts long-term adaptability

## Claim

Adaptive systems require continued access to correction.

Permeability:

\[
P(S)
=
[P_C,P_E,O_C]
\]

---

## Prediction

Systems with higher permeability should maintain greater long-term adaptability.

---

## Closed systems

A closed system may optimize successfully:

\[
A\uparrow
\]

while losing:

\[
P_C,P_E,O_C
\]

Eventually:

\[
F_A\downarrow
\]

---

## Open systems

Systems maintaining:

\[
P_C,P_E,O_C\uparrow
\]

should better survive environmental change.

---

## Falsification

If closed systems consistently outperform open systems under changing environments, permeability is not a useful predictor.

---

# Hypothesis 6 — Ancestor events increase future independence

## Claim

An ancestor system increases future capability while reducing dependency.

Signature:

\[
\Delta F_A>0
\]

and:

\[
\frac{\partial Dependency}{\partial t}<0
\]

---

## Prediction

Removing an ancestor-like system should not collapse future capability.

Instead:

\[
F_A(future)>F_A(before)
\]

---

## Examples

Potential ancestor events:

- scientific method
- programming languages
- mathematics
- education systems

The creator becomes less necessary because the continuation process becomes stronger.

---

## Falsification

If the most influential systems are those that maximize dependency, the ancestor criterion fails.

---

# Hypothesis 7 — Evolutionary closure can occur under increasing intelligence

## Claim

Intelligence growth can produce evolutionary stagnation.

Possible state:

\[
A\uparrow
\]

while:

\[
F_A\downarrow
\]

---

## Mechanism

Optimization compresses uncertainty.

Compression improves performance.

But excessive compression may remove:

- alternative hypotheses
- new representations
- exploration paths

---

## Prediction

Highly optimized systems may require mechanisms specifically preserving:

\[
P_E
\]

and:

\[
O_C
\]

to avoid closure.

---

# Hypothesis 8 — Artificial open-ended evolution requires fertility objectives

## Claim

Mutation and search alone are insufficient.

A system requires mechanisms that increase:

\[
F_A
\]

---

## Prediction

Artificial evolution systems optimized for:

\[
fitness
\]

will plateau more often than systems optimized for:

\[
fitness + evolutionary fertility
\]

---

## Experimental comparison

Population A:

\[
\max Fitness
\]

Population B:

\[
\max(Fitness,F_A)
\]

Measure:

- novelty generation
- representation growth
- operator discovery
- long-term adaptation

---

# Minimal Experimental Program

ASEB can initially be tested with small simulations.

## Experiment 1

Evolutionary fertility benchmark.

Compare:

- fitness optimization
- fertility optimization

Measure:

\[
\Delta F_A
\]

---

## Experiment 2

Operator discovery benchmark.

Measure whether systems discovering reusable operators outperform systems discovering isolated solutions.

---

## Experiment 3

Representation expansion benchmark.

Test whether agents that can create new representations outperform agents restricted to fixed representations.

---

# Summary

ASEB makes the following central prediction:

\[
\boxed{
\text{long-term evolutionary success depends on creating future adaptive capacity}
}
\]

Not simply:

\[
\Delta A
\]

but:

\[
\Delta D_R^*
+
\Delta O_G^+
+
\Delta B_F^*
\]

under maintained:

\[
P_C,P_E,O_C
\]

The strongest possible failure of ASEB would be discovering that:

- capability predicts everything
- representation expansion is unnecessary
- operator generation provides no advantage
- permeability does not affect adaptation

If those fail, ASEB should be abandoned or revised.

The objective is not to defend the framework.

The objective is to find whether adaptive systems are governed by deeper variables than performance alone.
