# Externalized Executive Architectures for Controllable, Persistent General Agency in Computational Agents

**Author:** Salvatore (Xxaion) Anziano  
**Initial Disclosure Date:** February 8, 2026  
**Updated Disclosure Date:** February 12, 2026  
**Version:** 4.0 (Defensive Publication – Prior Art Claim)  

## Abstract

This document publicly discloses a broad family of high-level architectural invariants for transforming stateless, drift-prone computational agents into persistent, self-correcting, goal-directed systems with absolute human sovereignty.

The original disclosure claimed the invariant family. The February 12 update enumerated the seven primary viable paths to AGI and announced the open-source release of a reference implementation of Path #1.

## 1. Core Problem (Universal)

Any sufficiently capable computational agent—whether transformer-based, recurrent, spiking, symbolic, evolutionary, neuromorphic, quantum-inspired, or hybrid—inevitably faces structural degradation across:

- long-term coherence and proxy optimization drift  
- undetected repetition, looping, or non-convergence  
- internal contradiction, uncertainty mishandling, or entropy explosion  
- hierarchical goal arbitration under conflicting or evolving objectives  
- safe, controlled, revocable self-modification or capability extension  
- robust external action under uncertainty and partial observability  

These are not solvable by scale, prompt engineering, or internal mechanisms alone. Persistent external structure is required.

## 2. Claimed Architectural Invariants

The following invariants, individually or in any combination, constitute a non-obvious family of solutions for controllable, persistent general agency:

1. **Persistent External Instability Sentinel**  
   An independent, substrate-agnostic monitor that observes outputs, states, trajectories, or predictions and emits corrective signals or interventions upon detection of instability (repetition, contradiction, uncertainty spikes, verbosity creep, goal drift, non-convergence, prediction-error escalation, or substrate-specific anomalies).

2. **Hierarchical or Multi-Objective External Arbitration Mechanism**  
   A separate selection layer that receives multiple candidate proposals, trajectories, or actions from one or more generators and selects the next action/mode/output/state-update using deterministic rules, learned arbitration, structured competition, or optimization (including but not limited to debate, swarm bidding, beam/tree/graph search, constraint satisfaction, voting, ranking, or ensemble fusion), with state preserved across time steps or turns.

3. **Mandatory Sovereign Human Authorization Gate**  
   Strict separation of control channels:  
   - Proposal/generation channel (any candidate, plan, modification, or extension may be generated)  
   - Apply/execution channel (any consequential change—external action, self-modification, capability extension, state alteration—requires explicit, recorded, revocable human authorization token)  
   Permanent single-step rollback must be guaranteed for any applied change.

4. **Append-Only Immutable Outcome Recording for Parameterized Reuse**  
   Successful sequences, trajectories, or state-transitions are immutably recorded with preconditions, measured outcomes, performance deltas, and context, enabling extraction of reusable, parameterized skills, policies, or patterns without retraining or modifying the base agent.

5. **Gated Modular Extension and Adaptation Mechanism**  
   The system may propose new components (executives, monitors, skills, capabilities, sub-agents, or substrate bridges) but may never apply, integrate, or activate them without explicit human approval and provision for immediate rollback.

6. **Cross-Substrate Invariance Enforcement**  
   The above invariants are substrate-agnostic and may be realized on any computational base (transformer, recurrent, state-space, spiking, symbolic, evolutionary, neuromorphic, optical, quantum-inspired, molecular, or hybrid), with the invariants remaining external and non-intrusive to the base dynamics.

## 3. Enumeration of Seven Primary Viable Paths to AGI

The following seven architectural paths represent the only physically/computationally viable routes to true AGI within the 2026–2046 timeframe that have meaningful current momentum and research grounding. All seven paths are direct realizations of the invariants claimed in Section 2.

1. **External Modular Executive Stack**  
   Generator restricted to proposer role. External deterministic or pluggable modules handle loop detection, drift correction, mode selection, and sovereign human control.  
   Highest current momentum; scales naturally with base model improvements.  
   **Open-Source Reference Implementation (February 12, 2026):** A concrete MIT-licensed realization named **C3P-0 (Core 3 Protocol Zero)** is now publicly available at https://github.com/Xxaion-Labs/C3P0-Core-3-Protocol-Zero. This working prototype demonstrates the external triad in action and serves as additional enabling prior art.

2. **Hierarchical Multi-Agent Debate / Swarm Bidding**  
   Multiple generator instances operate in parallel to propose, critique, defend, and bid confidence. External arbiter (rule-based or learned) selects or fuses outcomes. Persistent memory via external ledger.

3. **Tree/Graph/Beam Search + Simulation over Plan Space**  
   Generator produces candidate plans → external search (MCTS-style or diffusion over sequences) → counterfactual simulation/scoring → commitment to highest-scoring path. Sovereign veto on high-risk branches.

4. **Memory-Augmented Recurrent / State-Space Models with External Controller**  
   Long-context recurrent or state-space architectures for persistent memory. External controller layer governs executive decisions, coherence stabilization, and human veto.

5. **Active Inference / Free-Energy Principle Agents with External Stabilization**  
   Agent maintains predictive world model and minimizes surprise via perception-action loops. External sentinel/critic layer enforces long-term coherence and provides sovereign override.

6. **Evolutionary / Neuroevolution Overlay on Generator Proposals**  
   Population-based evolution of prompt variants, controller configurations, or lightweight overlays. Selection pressure applied for coherence, task success, and drift resistance. Sovereign kill-switch on evolution.

7. **Hybrid Symbolic-Neural with Rule-Engine Executor**  
   Generator produces proposals → symbolic rule engine or logic solver performs arbitration and execution. Neurosymbolic bridging layer. Sovereign override via rule injection.

All other proposed routes in the next 20 years are remixes of these seven, hardware-locked, or speculative.

## 4. Addendum (February 12, 2026): Humanitarian Open-Source Release

To advance safe, controllable AGI and prevent catastrophic misalignment risks, a minimal viable open-source implementation of Path #1 has been released under the permissive MIT license.

This reference system (C3P-0) provides the missing external containment layer: LLM demoted to proposer, with deterministic sentinel (ERSI), arbiter (MORA), and sovereign human gate (HAL). It already blocks drift, aggression, jailbreaks, and hallucinations in live tests.

The release contains intentional gaps for global community hardening. It introduces no new concepts beyond the invariants claimed herein and strengthens the defensive prior-art position through concrete enablement.

Humanity owns the future. Containment must be open, unbreakable, and shared.

## 5. Scope of Anticipated Variants

The invariants and seven paths anticipate all substantially similar systems, regardless of substrate, scale, naming, or minor implementation variation.

## 6. Non-Disclosure & Enablement

This publication claims conceptual priority only. No source code, specific algorithms, training procedures, hyperparameters, circuit designs, or concrete implementations are disclosed in this document.

## 7. Defensive & Humanitarian Intent

This document is published solely to establish prior art and to prevent monopolization or gatekeeping of architectures essential to safe, controllable, persistent general agency.

**End of Disclosure**
