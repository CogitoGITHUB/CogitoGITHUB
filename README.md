### Hi, I'm Cogito
( outdated.. brb ) 

I build systems — not software as product, but the scaffolding that makes thought itself reproducible.

Self-taught. Keyboard-first. Obsessed with the geometry of knowledge. Perpetually dissecting the machinery until the machinery becomes the map.

This is not a portfolio. It is a cartography of a single, ongoing experiment: what happens when you treat every layer of a computing environment as a deliberate coordinate in a higher-dimensional manifold of meaning, constraint, and execution.

---

## The Position

Most people treat tools as appliances. I treat them as architecture.

Every config file is a decision about what is allowed to exist. Every abstraction is a claim about causality. Every layer either earns its place by enforcing structure or it slowly poisons everything beneath it. I build environments where the structure of the tooling and the structure of thought are forced to converge — where opening a file, capturing an idea, reshaping a system, and materializing a container are all expressions of the same underlying model.

This is not productivity theater. It is epistemology made executable.

The method remains constant: **build deliberately, break systematically, understand completely.** Most of what I know was extracted by destroying working systems to discover the exact points at which they held together. The failures are the only honest documentation.

---

## The Cartography

What you are looking at is a full cartographic system for personal operating reality.

It maps:

- the physical substrate (hardware, kernel, packages)
- the cognitive substrate (knowledge graph, capture schemas, spatial hierarchy)
- the intentional substrate (architect-defined shapes, forms, and projections)
- the temporal substrate (history as material, not sacred text)

Everything is coordinates. Everything has topology. Everything is forced to declare its place in the manifold or be rejected by the structure.

---

## Interface Layer — Emacs + Org-mode as Living Atlas

Emacs is not a text editor. It is a programmable interface to structured thought.

Org-mode is the sole source of truth. Planning, research, system documentation, literate configuration, capture, export — all of it lives as structured records, not files. The knowledge base is a queryable, navigable, schema-enforced graph.

- **vulpea** — property-based querying and filtering across the entire knowledge base. Notes are structured data. Metadata becomes first-class graph edges.
- **doct** — declarative capture templates. Even the act of capturing a thought is schema-constrained at the point of entry.
- **tempel + yasnippet** — layered templating from lightweight structural snippets to full expansion macros.
- **modaled** — fully custom modal editing framework. No inherited Vi conventions. States, substates, cursor shapes, lighters, and keybindings defined from scratch in Elisp. The modal flow is authored, not borrowed.

The knowledge system is three-edge spatial: hierarchy, properties, and ordered geometry (float ORDER_KEY). Capture is schema-enforced. Specialized dictionary and rules paths exist. Planned AI agents will operate *inside* the manifold — placement-aware, schema-respecting, contradiction-aware — rather than floating over unstructured documents.

---

## Input Layer — Keyboard, Pen, and the End of Lateral Travel

Everything is keyboard-driven as a deliberate constraint that enforces intentionality. Dvorak reduces friction at the physical layer. Keybindings eliminate the context switch between thinking and doing. When the hands never leave the home row, thought and execution stop feeling separate.

The deliberate exception is the **Wacom Intuos Pro (2025)** with Pro Pen 3 (8192 pressure levels, ±60° tilt, 5080 lpi, battery-free EMR). The tablet is 4 mm thin, Bluetooth 5.3, dual-machine pairing, remappable ExpressKeys and mechanical dials that map directly into Emacs.

The pen is not a mouse substitute. It is a categorically different input mode: continuous physical intent for annotation, spatial reasoning, atlas-style documentation, handwritten capture into the knowledge graph, and sketching at the speed of thought. Capabilities outside the keyboard’s discrete symbolic domain.

Dials and ExpressKeys keep the tablet inside the keyboard-first model even when the hand holding the pen is not.

Next coordinate: the **Svalboard** — per-finger cluster device where each finger actuates keys in five directions without leaving its resting position. No lateral travel. No repositioning. The logical conclusion of keyboard-first: not a better keyboard, but a redefinition of what a keyboard is allowed to be.

---

## System Layer — Guix as Declarative Reality Engine

Source-based. Declarative. Literate. Built and rebuilt from first principles because trust in any system requires understanding what lives beneath the abstractions.

Guix is the execution backend. Org-mode remains the source of truth. Emacs is the composition surface.

USE flags and package definitions are treated as a design language. A system configuration is a statement of intent, not a collection of preferences.

---

## Automation Layer — Nushell as Structured Pipeline Substrate

Nushell replaces the Unix text-stream model with structured, typed pipelines. Data is natively tables, records, and lists. The old parsing tax (`awk`, `sed`, `grep`) is largely eliminated because structured data does not need to be parsed back into structure.

The shell becomes programmable infrastructure rather than a command runner. `fzf`, `bat`, `fd` are integrated as native Nushell commands and piped directly into Emacs where useful.

---

## Language Surface Area

Not a skills matrix. A map of working literacy — languages I can read, modify, and reason about without claiming unearned depth.

| Language   | Mode of Engagement          | Primary Context                                      |
|------------|-----------------------------|------------------------------------------------------|
| Elisp      | Operational                 | Emacs configuration and extension — the interface language |
| Guile      | Operational / Reading       | Scheme dialect — Guix system definitions, literate exposure |
| Nushell    | Operational                 | Primary shell and automation layer                   |
| Bash       | Functional / Legacy         | POSIX glue, portability layer                        |
| Lisp       | Conceptual foundation       | Informs thinking about Elisp and Guile               |
| Python     | Reading / modification      | Tooling scripts, one-off automation                  |
| Lua        | Reading                     | Configuration exposure (Neovim ecosystem, embedded)  |
| SQL        | Reading / querying          | Structured data retrieval                            |
| HTML/CSS   | Reading / modification      | Document structure and layout comprehension          |
| JavaScript | Reading                     | Browser-side awareness                               |

The distinction that matters is mode of engagement: languages written deliberately, languages read and modified confidently, languages navigated without disorientation. All of the above clear the third bar. Elisp, Guile, and Nushell are operational environments.

---

## Version Control — Git.
---

## Research Workflow — Structured Knowledge Pipeline

The knowledge system is not a note-taking app. It is a structured environment for building, connecting, and querying understanding across time.

All research lives in Org-mode, captured through `doct` templates that enforce structure at entry. Every note carries metadata. Every metadata field is queryable. `vulpea` turns the knowledge base into a filtered, navigable graph — find by project, domain, status, date, or arbitrary property combinations.

Pipeline:

```
capture (doct) → structure (org + vulpea) → connect (links + properties)
    → query (vulpea) → export (LaTeX / HTML / plain)
```

LaTeX integration is in progress. The goal is a single authoring environment where research notes, technical documentation, and publication-ready output share one source of truth.

---

## ManifoldOS — The Shape-Shifter’s Manifold

ManifoldOS is a declarative operating system composition model built on GNU Guix, structured as a layered system of definition, transformation, and materialization.

It is not a configuration dump. It is not a dotfiles collection. It is a reproducible system defined as a **semantic architecture**. Every component exists as a deliberate layer in a controlled dependency flow. The structure is fixed. Only the system *within* it grows.

### The Architect

The Architect is the only source of intentionality. The Architect does not “configure” in the traditional sense. The Architect defines:

- the **base system** (substrate)
- the **valid system categories** (shapes)
- the **construction rules** (forms)
- the **allowed runtime projections** (containers, VMs, ISOs)

Nothing else in the system is permitted to define architecture upward. Org-mode is the source of truth. Guix is the execution backend. Emacs is the interface for composition, inspection, and transformation.

### The Fixed Stack

```
constitution
    ├── substrate                         (base OS reality)
    │   ├── kernel-space
    │   │   ├── kernel, bootloader, drivers, filesystems, locale, hostname
    │   ├── user-space/root
    │   │   ├── loaders/                  (aggregate domain modules)
    │   │   └── container-system/
    │   │       ├── podman.scm            (rootless podman)
    │   │       └── substrate-containerized.scm  (OCI image pipeline → manifoldos-image)
    │   ├── user-space/home
    │   └── substrate.scm                 (assembles + exports os + manifoldos-image)
    └── shapes                            (taxonomy of possible systems)
        ├── containers/substrate-adapter  (placeholder)
        ├── isos/                         (planned)
        └── vms/                          (planned)
```

| Layer              | Role                                                                 |
|--------------------|----------------------------------------------------------------------|
| constitution.scm   | Bootstrap — single entry point, no domain logic                      |
| Substrate          | Reality — complete base OS, self-contained, declarative              |
| Shapes             | Taxonomy — categories of systems that can exist                      |
| Forms *(planned)*  | Construction — how shapes are built from the substrate               |
| Execution *(planned)* | Materialization — containers, VMs, ISOs                           |
| Outputs *(planned)*| Artifacts — built images, snapshots, exported states                 |

**Execution flow:**

```
constitution → substrate → shapes → forms → (substrate + forms) → containers / VMs / ISOs → outputs
```

**Dependency invariants (non-negotiable):**

- substrate depends only on kernel-space and user-space
- shapes may read substrate; they contain no execution logic
- constitution wires substrate and shapes
- no circular dependencies
- no upstream influence from outputs
- no layer may define what it is not

### Currently Operational

- Full Guix system (166+ packages, local packages only — channel logic removed)
- Rootless podman with subuid/subgid configuration
- ManifoldOS OCI image built automatically on every system reconfigure via `oci-service-type`
- Distrobox integration
- Cuirass CI under development
- `ManifoldOS-Reshaping-History` — full `jj`+git push pipeline with conflict detection, divergence handling, large-file guards, SSH management, and GitHub/GitLab API bootstrapping from a single keypress

ManifoldOS is a **closed architectural model undergoing expansion in breadth, not depth**. No new layers will be introduced. All future work lives inside the existing coordinates: substrate expansion, shapes expansion, forms expansion, executor expansion, output refinement.

---

## Currently Building

| Project                                      | Status      |
|----------------------------------------------|-------------|
| ManifoldOS — Guix-based shape-shifter system | Active      |
| Personal knowledge graph (vulpea + org)      | Active      |
| LaTeX integration into documentation pipeline| In progress |
| Literate system config publishing            | In progress |
| Spatial 3D mind-map geometry (ORDER_KEY)     | Active      |
| Schema-enforced capture + agent interfaces   | Active      |

---

## Open To

```
→ Freelance: automation pipelines, reproducible system setups, knowledge system architecture, declarative infrastructure
→ Collaboration: open source tooling, Unix-philosophy-aligned projects, literate systems
→ Conversation: cognitive workflows, cartographic knowledge systems, constraint-driven design, the geometry of thought
```

Find me where the configs are public. If something here resonates — open an issue, send a PR, or reach out directly.

---

## Profile Index

This is the **Technical / IT profile** — one projection node in a larger profile system built on the same underlying model.

```
→ Technical / IT        ← you are here [WIP]
→ Social Media          [coming]
→ Business              [coming]
→ ...                   [more to come]
```

Each profile is a different export target of the same architectural source. Same manifold. Different coordinate projection.

---

> *Structure is not decoration — it is constraint.  
> Constraint is what makes systems reproducible.  
> Reproducibility is what makes systems real.  
>  
> Meaning is encoded in separation.  
> Separation is what prevents collapse.  
>  
> A system is stable when every layer knows what it is not allowed to be.  
>  
> A map of reality, built one config file, one schema, one deliberate coordinate at a time.*