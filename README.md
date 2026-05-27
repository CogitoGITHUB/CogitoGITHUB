![Emacs](https://img.shields.io/badge/Emacs-7F5AB6?style=flat-square&logo=gnuemacs&logoColor=white)
![Org-mode](https://img.shields.io/badge/Org--mode-77AA99?style=flat-square&logo=org&logoColor=white)
![Gentoo](https://img.shields.io/badge/Gentoo-54487A?style=flat-square&logo=gentoo&logoColor=white)
![NixOS](https://img.shields.io/badge/NixOS-5277C3?style=flat-square&logo=nixos&logoColor=white)
![Nushell](https://img.shields.io/badge/Nushell-4E9A06?style=flat-square&logo=gnu-bash&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white)
![Dvorak](https://img.shields.io/badge/Keyboard-Dvorak-black?style=flat-square)
![Profile](https://img.shields.io/badge/Profile-Technical%20%2F%20IT-informational?style=flat-square)
![Status](https://img.shields.io/badge/Status-WIP-yellow?style=flat-square)
---
### Hi, I'm Cogito
I build systems — not just software, but the scaffolding around thinking itself.
Self-taught. Keyboard-first. Perpetually configuring something.
---
## The Position
Most people treat their tools as appliances. I treat mine as architecture.
Every config file is a decision. Every abstraction is a claim about what matters. Every layer in a system either earns its place or corrupts everything beneath it. I build toward environments where the structure of the tooling and the structure of thought converge — where opening a file, capturing an idea, and deploying a system are all expressions of the same underlying model.
This is not productivity. It is epistemology made executable.
The method: **build deliberately, break systematically, understand completely.** Most of what I know came from destroying working systems to find out why they held together. The failures are the documentation.
---
## The Stack
### Interface Layer — Emacs + Org-mode
Emacs is not a text editor. It is a programmable interface to structured thought.
Org-mode is the source of truth for everything: planning, research, system documentation, literate configs, capture, export. The knowledge base is not a folder of notes — it is a queryable, navigable graph of structured records.
- `vulpea` v2 — property-based querying, filtering and selection across the entire knowledge base; notes as structured data, not flat text
- `doct` — declarative capture templates; even the act of capturing a thought has a schema
- `tempel` + `yasnippet` — layered templating from lightweight structural snippets to full expansion macros
- `modaled` — fully customizable modal editing framework; no predefined states, no inherited keybindings, no Vi emulation. States and substates are defined from scratch in Elisp using `modaled-define-state` and `modaled-define-keys`. The modal flow is entirely owned — every state transition, cursor shape, lighter, and keybinding is a deliberate authoring decision, not a borrowed convention
### Input Layer — Keyboard, Pen, and What Comes Next
Everything is keyboard-driven. Not as an aesthetic — as a constraint that enforces intentionality. Dvorak reduces friction at the physical layer. Keybindings eliminate the context switch between thinking and doing. When the hands never leave the home row, thought and execution stop feeling separate.

The one deliberate exception is the **[Wacom Intuos Pro (2025)](https://www.wacom.com/en-us/products/pen-tablets/wacom-intuos-pro)**. The **Pro Pen 3** delivers 8,192 pressure levels, ±60° tilt, and 5080 lpi resolution via battery-free electromagnetic resonance. The tablet is 4mm thin, Bluetooth 5.3, 16h battery, dual-machine pairing, with fully remappable ExpressKeys and mechanical dials that map directly to Emacs commands.

The pen earns its place not by imitating a mouse but by being a categorically different input mode. Where the keyboard encodes discrete symbolic intent, the pen encodes continuous physical intent — annotation, spatial reasoning, atlas-style documentation, handwritten capture into the knowledge graph, and sketching at the speed of thought. These are not mouse tasks done differently; they are capabilities outside the keyboard's domain entirely.

The dials and ExpressKeys keep the tablet inside the keyboard-first model even when the hand holding the pen isn't. It is an extension of the system, not a break from it.

The next step is the **[Svalboard](https://svalboard.com/)** — a per-finger cluster device where each finger actuates keys in five directions without leaving its resting position. No lateral travel. No repositioning. The logical conclusion of keyboard-first: not a better keyboard, but a redefinition of what a keyboard is allowed to be.
### System Layer — Gentoo / NixOS / Guix
Source-based. Declarative. Literate. Built from scratch — LFS multiple times — because understanding what lives beneath the abstractions is not optional; it is the foundation of trust in any system you operate.
USE flags are a design language. A kernel config is a statement of intent.
### Automation Layer — Nushell
Nushell replaces the Unix text-stream model with structured, typed pipelines. Data is natively tables, records and lists. `awk`, `sed`, `grep` are gone — not because they are wrong, but because structured data does not need parsing.
The shell is programmable infrastructure, not a command runner.
- `fzf` + `bat` + `fd` integrated as native Nushell commands, piped directly into Emacs
- `ManifoldOS` — see below
### Language Surface Area
Not a skills matrix. A map of working literacy — languages I can read, modify, and reason about, without claiming depth I haven't earned.

| Language | Awareness | Primary Context |
|---|---|---|
| Elisp | Functional | Emacs configuration and extension — the language the interface is written in |
| Nushell | Functional | Primary shell and automation layer — structured pipelines, system scripting |
| Bash | Functional | Legacy scripts, POSIX glue, portability layer beneath Nushell |
| Guile | Reading | Scheme dialect — Guix system definitions, literate config exposure |
| Lisp | Reading | Conceptual foundation; informs how I think about Elisp and Guile |
| Python | Reading / modification | Tooling scripts, one-off automation; not a primary environment |
| Lua | Reading | Configuration exposure (Neovim ecosystem, embedded scripting) |
| SQL | Reading / querying | Structured data retrieval; not a primary authoring language |
| HTML | Reading / modification | Document structure layer; understood, not authored from scratch |
| CSS | Reading / modification | Styling and layout comprehension; modified more than written |
| JavaScript | Reading | Browser-side awareness; not a working language |

The distinction that matters here is not proficiency level — it is **mode of engagement**: languages I write deliberately, languages I read and modify confidently, and languages I can navigate without being lost. All of the above clear the third bar. Several clear the second. Elisp and Nushell are operational environments.

### Version Control — Jujutsu (`jj`)
Colocated with git. Bookmark-based. Operation log with full undo. History is not sacred — it is material to be shaped. `jj` makes composable, conflict-aware history rewriting the default, not the exception.
---
## Research Workflow
The knowledge system is not a note-taking app. It is a structured environment for building, connecting and querying understanding over time.
All research lives in Org-mode, captured through `doct` templates that enforce structure at the point of entry. Every note has metadata. Every metadata field is queryable. `vulpea` turns the knowledge base into a filtered, navigable graph — find by project, domain, status, date, or arbitrary property combinations.
The pipeline:
```
capture (doct) → structure (org + vulpea) → connect (links + properties)
    → query (vulpea) → export (LaTeX / HTML / plain)
```
LaTeX integration is in progress — the goal is a single authoring environment where research notes, technical documentation and publication-ready output share one source.
---
## ManifoldOS — The Shape-Shifter's Manifold
ManifoldOS is a literate operating system composition model built on Gentoo and Nushell, structured as a layered system of definition, transformation, and materialization.
It is not a configuration dump. It is not a dotfiles collection. It is a reproducible system defined as a **semantic architecture**. Every component exists as a deliberate layer in a controlled dependency flow.
The Architect — the only source of intentionality in the system — does not "configure" in the traditional sense. Instead, the Architect defines:
- the **base system** (substrate)
- the **valid system categories** (shapes)
- the **construction rules** (forms)
- the **allowed runtime projections** (containers, VMs, ISOs)
Nothing else in the system is allowed to define architecture upward. Org-mode is the source of truth. Nushell is the execution layer. Emacs is the interface for composition, inspection, and transformation.
### The Stack
```
constitution
    ├── substrate                         (base OS reality)
    │   ├── kernel-space
    │   │   ├── kernel.nu                 (kernel config + build pipeline)
    │   │   └── portage.nu                (USE flags, package sets, world)
    │   ├── user-space/root
    │   │   ├── loaders/                  (aggregate domain modules)
    │   │   └── container-system/
    │   │       ├── podman.nu             (rootless podman setup)
    │   │       └── substrate-containerized.nu  (OCI image pipeline)
    │   ├── user-space/home
    │   └── substrate.nu                 (assembles + exports system state)
    └── shapes                            (future system type extensions)
        ├── containers/substrate-adapter  (placeholder)
        ├── isos/                         (planned)
        └── vms/                          (planned)
```
| Layer | Role |
|---|---|
| `constitution.nu` | Bootstrap — single entry point, no domain logic |
| Substrate | Reality — complete base OS, literate Gentoo + Nushell |
| Shapes | Taxonomy — categories of systems that can exist |
| Forms *(planned)* | Construction — how shapes are built from the substrate |
| Execution *(planned)* | Materialization — containers, VMs, ISOs |
| Outputs *(planned)* | Artifacts — built images, snapshots, exported states |
**Execution flow:**
```
constitution → substrate → shapes → forms → (substrate + forms) → containers / VMs / ISOs → outputs
```
**Dependency invariants:**
- `substrate` → kernel-space, user-space only
- `shapes` → may read substrate; no execution logic
- `constitution` → substrate, shapes
- No circular dependencies. No upstream influence from outputs. No layer may define what it is not.
### Currently operational
- Full Gentoo system — source-built, USE-flag controlled, fully owned
- Rootless podman with subuid/subgid configuration
- ManifoldOS OCI image built via Nushell pipeline on every system update
- Distrobox integration
- `ManifoldOS-Reshaping-History` — a full `jj`+git push pipeline with conflict detection, divergence handling, large-file guards, SSH management, and GitHub/GitLab API bootstrapping — all from a single keypress
> ManifoldOS is not a finished system. It is a **closed architectural model undergoing expansion in breadth, not depth**. No new layers will be introduced. All future work lives inside: substrate expansion, shapes expansion, forms expansion, executor expansion, output refinement.
---
## Currently Building
| Project | Status |
|---|---|
| ManifoldOS — Gentoo + Nushell migration | Active |
| Personal knowledge graph (vulpea + org) | Active |
| LaTeX integration into documentation pipeline | In progress |
| Literate system config publishing | In progress |

---
## Open To
```
→ Freelance: automation pipelines, reproducible system setups, knowledge system architecture
→ Collaboration: open source tooling, Unix-philosophy-aligned projects
→ Conversation: cognitive workflows, literate systems, declarative infrastructure
```
Find me where the configs are public. If something here resonates — open an issue, send a PR, or reach out directly.
---
## Profile Index
This is the **Technical / IT profile** — one node in a larger profile system built on the same underlying model.

```
→ Technical / IT        ← you are here [WIP]
→ Social Media          [coming]
→ Business              [coming]
→ ...                   [more to come]
```

Each profile is a projection of the same architecture onto a different context. Same source. Different export target.

---
> *"Structure is not decoration — it is constraint. Constraint is what makes systems reproducible. Reproducibility is what makes systems real.*
>
> *Meaning is encoded in separation. Separation is what prevents collapse.*
>
> *A map of reality, built one config file at a time."*