# Team Silvortex

**Tools for scientific computing, software development, and human–AI collaboration.**

Team Silvortex builds programmable systems that turn ideas into executable,
inspectable, and reproducible work. Our projects span finite-element research,
network debugging, application design, collaborative execution, and heterogeneous
computing.

We are developing a connected ecosystem, not a single monolithic application.
Each project has its own responsibilities, implementation, and release lifecycle;
integration grows through explicit contracts and real workloads.

## Projects

### [Kyuubiki](https://github.com/Team-silvortex/kyuubiki)

**A FEM workstation, workflow system, and distributed simulation runtime.**

Kyuubiki combines modeling, operator workflows, execution, and result review.
Its Rust, Python, and Elixir Headless SDKs let research systems and AI agents
use backend capabilities without requiring GUI automation. Human inspection,
authorization, numerical validation, and reproducible evidence remain part of
the research process.

The direction is a Blender-like environment for finite-element research:
visual when that helps, headless when automation matters, and extensible through
portable contracts. Current work prioritizes complete, recoverable research
journeys and workload-specific reliability.

### [Gewyvern](https://github.com/Team-silvortex/gewyvern) and [Leserpent](https://github.com/Team-silvortex/gewyvern/blob/main/LESERPENT.md)

**Protocol-aware network debugging and multi-instance control.**

Gewyvern is a Linux-first, eBPF-based debugger for bounded observation sessions,
protocol-flow reconstruction, deterministic reasoning, and replayable reports.
Leserpent provides cross-platform control of multiple independent authorities
and their Gewyvern runtimes.

The repository also contains Gewylang protocol tooling and Leselang semantic
automation. GUI, Web, CLI, and code-driven control share protocol operations
rather than maintaining separate meanings for the same action. Etragon remains
an optional, incubating advisory-learning component.

### [Viento Studio](https://github.com/Team-silvortex/viento-studio)

**The future official IDE for user-space applications in the Nuis ecosystem.**

Viento is evolving into a design-first application development environment:
define worlds, objects, environments, and resources; inspect a build plan;
then build, run, and inspect the resulting program. Human interaction and AI
automation are intended to operate through the same semantic commands.

Today, its working foundation is document and original-character/worldbuilding
authoring, object-property editing, and recoverable batch changes. These are
practical starting points, not the limit of its intended role. The full
application IDE and Nuis integration are being developed incrementally, while
preserving existing projects and the distinction between design, build, and
runtime state.

### [Cyanrex](https://github.com/Team-silvortex/cyanrex-lab)

**A collaborative work environment in development for people, AI agents, and compute.**

Cyanrex currently provides a browser-based eBPF experimentation and teaching
system. Its next-generation architecture expands that foundation into
workspaces, artifacts, tasks, runs, reviews, and explicit authorization.

The aim is to coordinate collaborative work without confusing an AI planner
with an execution node, or a proposed task with permission to execute it.
Teaching remains a concrete domain for this work. New collaboration capabilities
are introduced through staged migration, not assumed to be live merely because
their architecture has been documented.

### [NuisLang](https://github.com/Team-silvortex/nuislang)

**An AOT-first heterogeneous systems language and software-production toolchain.**

Nuis organizes CPU, shader, kernel, data, network, and C-compatibility domains
around NIR, YIR, registered Nustar backends, and shared execution contracts.
Its scope extends from language semantics and compilation to linking, resource
management, artifacts, and runtime coordination.

Current development is application-led, using ns-nova workloads to expose
foundation gaps while advancing staged compiler self-hosting. The wider effort
includes ns-nova's interactive application and engine work, yalivia's dynamic
execution direction, and Vulpoya's analysis and verification work. These have
their own milestones; they are not all finished or independently released
products.

## How the ecosystem fits together

The intended division of responsibility is straightforward: **Viento designs
applications; Nuis provides their production toolchain; Cyanrex coordinates
collaborative work; Kyuubiki supplies a scientific research environment; and
Gewyvern with Leserpent supports network diagnosis and control.** This describes
the direction of integration, not an already-complete end-to-end stack.

Shared identity and hosted distribution are developed separately from the
public runtimes. Each project's local-use, self-hosting, licensing, and
compatibility contracts remain explicit. Existing applications do not need to
wait for a future operating system or a wholesale rewrite to be useful.

[Sirius](https://github.com/Team-silvortex/sirius) is reserved for longer-term
kernel work. The broader direction includes Nuis OS and spatial computing;
these are future system goals, not currently available products.

## How we build

- **Scientific practice.** Form hypotheses, build working systems, test them,
  and revise claims when the evidence changes.
- **Explicit contracts.** Keep interfaces, ownership, authorization, and
  lifecycle boundaries clear across languages, processes, and devices.
- **Human control.** Make automation inspectable and constrained; an AI-generated
  plan is not its own authorization or proof of correctness.
- **Evidence-backed delivery.** Distinguish source implementation, tested scope,
  installed artifacts, and public releases. Open development does not remove
  the need for compatibility, recovery, and security work.

## Explore and contribute

Start with the repository closest to your task. Its README, architecture notes,
release records, and validation evidence describe what is available and what
remains in development. Each repository's license and contribution guidelines
apply independently.

Reproducible bug reports, real workloads, tests, documentation, and focused
contributions help turn the broader direction into useful tools. For security
issues, follow the affected project's published reporting process.
