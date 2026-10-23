# 👋 Nathan Douglas

## Software engineer moving into AI safety research, starting with the collective behavior of interacting AI systems.

I want to help make interacting AI systems safer by understanding the collective behavior that single-agent evaluations can miss. I'm exploring when established models of group behavior, and populations of simple agents, predict how LLM populations respond to changes in communication, information access and oversight, and I'm building reproducible experiments to find out where those models hold and where they break.

I come to this from fourteen years of building and operating production software, most recently as engineer of record for the VA.gov Check-In platform, plus earlier work in nuclear power engineering and healthcare and undergraduate study in philosophy, sociology and psychology. I'd like to bring that engineering discipline to research, alongside people who can tell me where I'm wrong.

📄 [Résumé](https://ndouglas.github.io/resume/resume.pdf) · 🧫 [BottomUpLab](https://ndouglas.github.io/BottomUpLab/) · 🌐 [darkdell.net](https://darkdell.net)

---

### 🔭 Now

- **First research question (November 2026):** do LLMs tell independent supporting evidence apart from repeated reports of a single source? Compare simple-model predictions with LLM behavior across no-peer, independent-evidence and repeated-source conditions, then test whether exposing provenance changes the outcome. A single model reading controlled reports is only a baseline; showing a *collective* failure needs interacting agents relaying and reusing reports.
- **Learning:** completed BlueDot Impact's AGI Strategy course (October 2026) and taking its Technical AI Safety course, October 26–31; working through PyTorch and interpretability fundamentals.
- **Open to:** research engineering, evaluation and infrastructure work alongside researchers; collaboration on multi-agent and collective-behavior questions; and senior platform engineering. Remote from northeast Ohio.

---

### 🧪 Selected Work

**🧫 [BottomUpLab](https://github.com/ndouglas/BottomUpLab)** ([live](https://ndouglas.github.io/BottomUpLab/)): agent-based models of societies, markets, games and minds, each reproduced from its source paper and measured against it. Rust compiled to WebAssembly, with seeded experiments, parameter sweeps, replayable sessions and regression tests. Every ambiguity in a paper becomes a named switch, and a reproducibility register records where published findings don't reproduce: Sugarscape's VI-2 crash and V-2 endemic disease among them.

**🏔️ [Hornvale](https://github.com/hornvale)**: a large Rust world simulation whose guardrails are the point: architecture rules and documentation invariants enforced as tests, byte-identical deterministic output verified across CPU architectures, and mutation tooling written after false-green results. Decisions, retrospectives and the running chronicle are published as a [book](https://hornvale.github.io/book/).

**🦷 [Goldentooth](https://github.com/goldentooth)**: a 17-node Talos Kubernetes cluster on Raspberry Pis, run entirely through Flux GitOps, used to learn how infrastructure behaves when it's allowed to break. Observability end to end, chaos engineering, internal PKI, and a 100-plus-entry [journal](https://github.com/goldentooth/clog) of what broke and why.

**🕴️ [resume](https://github.com/ndouglas/resume)**: my résumé as a content database where every line carries an evidence pointer, rendered per profile to LaTeX and PDF.

---

### 🏗️ Engineering Background

- **Production ownership:** engineer of record for four VA.gov patient check-in services handling nearly two million requests a day: application code, infrastructure, delivery pipelines and on-call; led the migration to a new AWS account.
- **Testing and reproducibility:** a developer platform of 40-plus reusable infrastructure modules integration-tested against real AWS, and 200-plus end-to-end tests of health-record appointment flows that link failing assertions to execution traces.
- **Failure investigation:** traced an error rate below 0.01% to a longstanding silent authorization defect and shipped the fix overnight; introduced the team's first postmortem and a 24-hour postmortem policy.

---

<details>
<summary><b>🗂️ Everything else</b></summary>

#### 🌀 [ndouglas](https://github.com/ndouglas)

- 👋 [ndouglas](https://github.com/ndouglas/ndouglas): My README
- 🕴️ [resume](https://github.com/ndouglas/resume): My résumé, written in LaTeX, with continuous delivery or something.
- 🎮 [greenstone](https://github.com/ndouglas/greenstone): A basic NES emulator written in Rust with an emphasis on debugging and game development.
- 🧁 [BottomUpLab](https://github.com/ndouglas/BottomUpLab): Agent-based models reproduced from their source papers, in the browser
- 🎲 [longtable](https://github.com/ndouglas/longtable): LISP + ECS + Rule Engine
- 🧭 [clork](https://github.com/ndouglas/clork): A faithful port of _Zork_ to Clojure
- 🔢 [mips-sudoku-solver](https://github.com/ndouglas/mips-sudoku-solver): A Sudoku solver, written in MIPS R4K assembly.
- 🧊 [unity-hashing-grid](https://github.com/ndouglas/unity-hashing-grid): Hashing Grid implementation in Unity
- 🗣️ [whispers](https://github.com/ndouglas/whispers): Whispers is a self-organizing, belief-driven mesh where nodes propose, verify, and evolve solutions through dynamic, decentralized consensus.
- 💻 [blackpool](https://github.com/ndouglas/blackpool): An implementation of the Lox Virtual Machine, written in Rust
- 📈 [linear-regression](https://github.com/ndouglas/linear-regression): Simple implementation of linear regression in Rust as a learning project.
- ☕️ [distillation](https://github.com/ndouglas/distillation): An experiment with distillation using various combinations of naïve implementations, adversarial training, Jacobian penalties, and approximate Hessian penalties.
- 🪾 [arborhedron](https://github.com/ndouglas/arborhedron): An exploration of Platonic symmetry, emergent structures, symbolic recursion, and ideal-vs-real tension.


#### 🦷 [Goldentooth](https://github.com/goldentooth): Kubernetes laboratory

- 🚜 [terraform](https://github.com/goldentooth/terraform): General Terraform Infrastructure-as-Code for Goldentooth
- 👋 [.github](https://github.com/goldentooth/.github): My ✨special ✨ repository
- 🚜 [gitops](https://github.com/goldentooth/gitops): GitOps repository for Goldentooth Talos cluster
- 🧱 [clog](https://github.com/goldentooth/clog): The changelog formerly known as "Kubernetes, the _Excruciating_ Way".
- 🏗️ [cluster](https://github.com/goldentooth/cluster): Declarative definition for Goldentooth.
- ❓ [mcp](https://github.com/goldentooth/mcp): MCP server for the Goldentooth Bramble
- 🛡️ [asoiaf-noble-house-images](https://github.com/goldentooth/asoiaf-noble-house-images): Images derived from arms from noble houses of ASoIaF.


#### 🌉 [Bitterbridge](https://github.com/bitterbridge): systems experiments

- 👋 [.github](https://github.com/bitterbridge/.github): Special Repository
- 🚜 [terraform](https://github.com/bitterbridge/terraform): General Terraform Infrastructure-as-Code for Bitterbridge
- 🧩 [terraform-modules](https://github.com/bitterbridge/terraform-modules): Reusable Terraform modules for various projects
- ⚙️ [github-actions](https://github.com/bitterbridge/github-actions): GHA reusable Actions and Workflows for use in my various repositories
- ❓ [goldengrove](https://github.com/bitterbridge/goldengrove): A tool for creating and exploring fantastic planets.
- ❓ [snakewood](https://github.com/bitterbridge/snakewood): An experimental MUD
- 📉 [p5js-sketches](https://github.com/bitterbridge/p5js-sketches): p5.js sketches for fun and to show off silly ideas
- ❓ [crows-nest](https://github.com/bitterbridge/crows-nest): A thunk-based agentic system.
- 🕵️‍ [rills](https://github.com/bitterbridge/rills): A little experiment with LLMs playing _Mafia_, basically.


#### ️‍🔥 [Hellholt](https://github.com/hellholt): dotfiles and personal infrastructure

</details>

---

## 🎈 Outside the Terminal

Relearning French, building LEGO with [my kid](https://github.com/JomoDuggins), painting miniatures, lifting, cycling and rowing, and cooking (bread, cheese, pasta). Films on [Letterboxd](https://letterboxd.com/supertempt768/), music on [RateYourMusic](https://rateyourmusic.com/~NathanDouglas).

!["I try to make everyone's life a little more surreal."](https://github.com/user-attachments/assets/6784e08b-88b1-4760-a856-ed1d6e17c0df)

---

( <span style="display:inline-block; min-width: 2em;">🌀</span>[ndouglas](https://github.com/ndouglas/) | <span style="display:inline-block; min-width: 2em;">🌉</span>[bitterbridge](https://github.com/bitterbridge/) | <span style="display:inline-block; min-width: 2em;">️‍🔥</span>[hellholt](https://github.com/hellholt/) | <span style="display:inline-block; min-width: 2em;">🦷</span>[goldentooth](https://github.com/goldentooth/) )
