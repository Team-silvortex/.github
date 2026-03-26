# Silvortex

Silvortex is a collection of system-oriented experimental projects,
focused on building observable, controllable, and programmable systems.

These projects explore different aspects of:

* network observability
* distributed orchestration
* programmable computation
* simulation systems

They are developed independently, with varying levels of maturity.

Some are functional prototypes.
Some are still forming.
Some exist as early-stage implementations.

There is no enforced unification between them at this stage.

---

## Projects

### Observability & Network Systems

* **cyanrex-lab (cy)**
  Browser-based eBPF experimentation platform with isolation and observability.

* **gewyvern (ge)**
  DSL-driven eBPF engine for protocol-agnostic network flow modeling, designed for dynamic analysis and debugging.

* **leserpent (le)**
  Orchestration layer for managing distributed gewyvern agents and coordinating execution workflows.

* **etragon (et)**
  ML-driven network flow simulation and mock generation system for controlled experimentation.

---

### Compute & Language Systems

* **nuislang**
  AOT-first system language for unified heterogeneous computation via YIR.

* **yalivia**
  Lightweight JIT runtime for executing and optimizing YIR with adaptive behavior.

* **vulpoya**
  Static analyzer and verifier for the nuis/YIR ecosystem, focused on correctness and constraints.

---

### Simulation Systems

* **kyuubiki**
  Distributed FEM computation platform with a web-based interface and orchestration layer.

---

## Notes

This is not a product suite.

Each project evolves under its own constraints and direction.
Cross-project integration may happen in the future, but is not a current goal.

The focus is on building working systems, not presenting a unified framework.
Practical correctness and system behavior are prioritized over presentation.
