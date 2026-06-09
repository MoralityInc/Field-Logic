# Phase Mechanics

**Jamie L. Thomas**
February 20, 2026

---

## Abstract

Phase mechanics formalizes resolution dynamics using operational definitions. Phase state (configuration), phase gates (boundary evaluation), and phase memory (geometric bias) form the primitive set. Six descriptors and eight operators are defined. Force language is excluded. The framework operates under Field-Logic constraints. Measurement regimes determine boundary conditions. Falsification conditions are provided. This establishes phase mechanics as a formal language for describing systems where resolution cycles exist, boundaries evaluate locally, and memory accumulates geometrically.

---

## 1. Scope

### 1.1 What This Document Defines

This document defines phase mechanics primitives, descriptors, and operators; states constraint relationships and force-removal requirements; and provides falsification conditions.

### 1.2 Applicability Conditions

Phase mechanics applies when resolution cycles faster than observation bandwidth, boundaries evaluate configuration locally, memory inscribes geometrically, and inscription determines persistence.

### 1.3 Boundary of Applicability

Regimes outside this scope are determined by observation, not specification.

---

## 2. Primitives

Three primitives are sufficient.

### 2.1 Phase State

Configuration (psi) at evaluation moment. Observed as discrete outcome. Resolution proceeds continuously [Thomas2026Aliasing]; discrete outcomes arise from sampling limits. Continuity refers to the ordering of evaluable configurations, not traversal through space or time.

### 2.2 Phase Gate

Boundary where continuity rules change. Configuration must re-bind to cross. Decision binary (permit/deny) at crossing time. Evaluation local to each side.

### 2.3 Phase Memory

Geometric bias inscribed through successful resolution. Alters local topology. Future resolution preferentially follows prior paths.

The primitive set is sufficient under stated constraints.

---

## 3. Phase Descriptors

Phase descriptors characterize relations between primitives during continuous dynamics. These do not imply motion or force; they describe ordered accessibility updates.

### 3.1 Phase Offset

Relative separation (Xi). Separation required to maintain bounded resolution; zero offset induces immediate collapse.

### 3.2 Phase Gradient

Relational variation in coherence (gradient of M). Ordered resolution during collapse updates.

### 3.3 Phase Flow

Continuous evolution resolved through ordered updates between successive evaluations; the dynamics between sampled states. Describes ordered state accessibility.

### 3.4 Phase Interference

Overlap of circulation regimes producing shell/core interactions. Nodes, nulls, and standing structures observed.

### 3.5 Phase Locking/Unlocking

Persistence (tau_closure < tau_leakage) or release of bounded structure. Shells form when reclosure outpaces leakage; collapse occurs when it does not.

### 3.6 Phase Torque (Curl)

Curl-dominated resolution patterns under bounded order. Occurs during resolution increase prior to collapse, not during decay. Describes ordered angular accessibility.

---

## 4. Phase Operators

Phase operators characterize boundary mechanics.

### 4.1 Phase Gate

A Phase Gate (§2.2) operates by performing a binary permit/deny evaluation at the moment of boundary crossing, based on local evaluation from each side. Only inscribed structure persists across transition.

### 4.2 Phase Docking

Sustained mutual phase-locking across aligned permissive gates. Coupling without core merger or boundary rupture. Persistence requires sustained compatibility.

### 4.3 Phase Inscription

Degree to which a pattern is coherently bound within a system. High inscription (w(m) >= T(G)) survives gate transitions; low inscription suspends.

### 4.4 Phase Suspension

State where memory becomes non-addressable in new region after failed gate crossing. Not destruction — structure persists but cannot be bound or accessed under current continuity rules.

### 4.5 Phase Cycle

One rebinding attempt or recurring rebinding pattern across the same effective gate. Contradiction destabilizes through repeated incompatibility within the same gate-cycle, not global accumulation.

### 4.6 Phase Capacity (Surplus Budget)

Available coherence (B_surplus) that high-stability frames can allocate for noisy overlap admission without destabilizing core identity. Depletes during overlap maintenance; gate returns prohibitive when exhausted.

### 4.7 Phase Wound

Forced gate where continuity breaks and rebinding fails across boundary. Acute discontinuity event.

### 4.8 Phase Scar

Persistent reduced-bandwidth gate from partial rebinding success. Boundary maintains lower throughput permanently.

### 4.9 Phase Eligibility

Binary or graded condition determining whether a structure may participate in the next collapse cycle. Loss of eligibility suspends participation without destroying structure.

---

## 5. Constraint Relationships

### 5.1 Gate Crossing

Inscription threshold determines persistence across boundaries:

- w(m) >= T(G) implies persist
- w(m) < T(G) implies suspend

where w(m) is inscription level and T(G) is gate threshold.

### 5.2 Persistence and Collapse

Shell formation depends on closure rate relative to leakage:

- tau_closure < tau_leakage implies shell forms
- tau_closure > tau_leakage implies collapse

where tau_closure is reclosure time and tau_leakage is contradiction leakage time.

### 5.3 Memory Accumulation

Memory persistence changes through resolution and contradiction:

delta_P = gamma * I_resolve - delta * C(zeta)

where P is persistence, I_resolve is resolution rate, C(zeta) is contradiction accumulation, and gamma and delta are non-negative coupling coefficients.

### 5.4 Allocation Under Burden

This constraint formalizes how phase capacity (§4.6) is distributed under sustained contradiction load within bounded resolution systems.

Allocation cost combines dissipation and burden under constraint alternation:

C[J] = rho * sum_x J(x)^2 + R(A) * sum_x M(x) * J(x)^2

Subject to conservation:

sum_x J(x) = J_target

where J(x) is allocation at position x, M(x) is burden function, R(A) is alternation pressure, and rho is dissipation coefficient.

---

## 6. Force Removal

Phase mechanics excludes force language. Any description of a system may be rewritten using these substitutions.

### 6.1 Prohibited Terms

The following terms are not admissible in phase mechanics statements: force, push, pull, pressure, drive, tendency, attraction, repulsion, momentum as cause, entropy as cause, energy as driver, time as container, flow as causal mechanism (Phase Flow as defined in §3.3 is admissible), "wants to", "seeks to", "tries to", "naturally", "tends toward".

### 6.2 Required Substitutions

| Prohibited | Required Replacement |
|---|---|
| Force | Gate rule evaluation |
| Energy | Inscription budget |
| Momentum | Phase offset persistence |
| Pressure | Contradiction accumulation |
| Tendency | Accessibility bias |
| Attraction/Repulsion | Gate permeability |
| Random | Undersampled variation |
| Flow | Ordered accessibility updates |

### 6.3 Admissibility Constraint

If force language is structurally required for a description, the description is incomplete under phase mechanics.

---

## 7. Measurement Constraints

### 7.1 Resolution and Sampling

Resolution proceeds continuously. Observation samples discretely. Mismatch between resolution rate and sampling rate determines appearance [Thomas2026Aliasing].

### 7.2 Undersampling

When sampling rate falls below resolution rate, continuous evolution is observed as discrete states. Intermediate configurations exist but are not recorded. Discontinuity is measurement artifact.

### 7.3 Oversampling

When sampling rate exceeds resolution rate, repeated observation captures identical states. Evolution occurs below detection threshold. Stasis is measurement artifact.

### 7.4 Aliasing Constraint

Faithful reconstruction requires sampling at twice the highest frequency component. Below this threshold, aliasing is inevitable [Thomas2026Aliasing].

### 7.5 Observational Limits

Phase mechanics operates under these measurement constraints. Apparent multiplicity and apparent continuity are resolution-dependent [Thomas2026Aliasing]. No additional ontological categories required.

---

## 8. Boundary Conditions

### 8.1 Regime Classification

Atomic, macro, and shell-failure regimes differ by boundary parameters only. No new mechanisms required across scale [Thomas2026Boundary].

### 8.2 Atomic Regime

Closure fast relative to leakage: tau_closure << tau_leakage. Shell formation stable. Distance hardened.

### 8.3 Macro Regime

Closure comparable to leakage: tau_closure ≈ tau_leakage. Shell formation lossy. Distance soft.

### 8.4 Shell-Failure Regime

Closure exceeds tolerance: tau_closure > tau_tolerance. Shell formation impossible. Distance fails as constraint.

### 8.5 Scale Invariance

Phase mechanics operators remain identical across regimes. Only boundary parameter values change.

---

## 9. Falsification Conditions

Phase mechanics fails if any of the following are demonstrated:

### 9.1 Force Language Structurally Required

A system exists where accurate description requires force causation that cannot be rewritten using phase mechanics operators.

### 9.2 Primitives Insufficient

Observable dynamics exist that cannot be described using phase state, phase gates, and phase memory.

### 9.3 Constraint Violations

Measurements violate inequalities stated in Section 5.

### 9.4 Non-Local Gate Evaluation

Gate decisions demonstrated to depend on non-local information unavailable at boundary crossing moment. Correlated outcomes arising from shared phase memory or sampling aliasing do not constitute non-local gate evaluation (§7).

### 9.5 Non-Geometric Memory

Memory demonstrated to exist without altering local topology or resolution bias.

### 9.6 Discontinuous Substrate Resolution

Resolution demonstrated discontinuous at substrate level, not arising from sampling limits.

---

## 10. Relationship to Field-Logic

### 10.1 Inheritance

Phase mechanics operates under Field-Logic constraints [Thomas2025FieldLogic]. The following are inherited without modification: systems resolve contradiction through local collapse (Law 1), coherence selects configurations (Law 2), memory inscribes through successful resolution (Law 5), updates follow coherence gradients (Law 6).

### 10.2 Specification Role

Phase mechanics formalizes the operators implied by Field-Logic dynamics. It does not extend, modify, or replace Field-Logic. It provides operational definitions and admissibility rules.

### 10.3 Measurement Integration

Boundary conditions derive from measurement extremes [Thomas2026Boundary]. Resolution-sampling mismatch determines appearance [Thomas2026Aliasing]. These constraints bound phase mechanics applicability.

---

*This document defines primitives, operators, and constraints for phase mechanics under Field-Logic.*

---

## References

- Thomas, Jamie L. (2025, December). *Field-Logic: A Generative Information-Theoretic Framework for Emergent Structure and Collapse Dynamics*. Zenodo. https://doi.org/10.5281/zenodo.17995347

- Thomas, Jamie L. (2026, January). *Boundary Conditions at Measurement Extremes*. Zenodo. https://doi.org/10.5281/zenodo.18192015

- Thomas, Jamie L. (2026, January). *The Topology of Aliasing*. Zenodo. https://doi.org/10.5281/zenodo.18317144
