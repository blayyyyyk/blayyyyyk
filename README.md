# Blake Moody

I build **web-native machine learning systems** and **research tooling** for **spatial reasoning**, **embodied agents**, and **geometric representations** — with a bias toward **fast, reproducible experiments** and **clean system design**.

- 🌐 Portfolio: **https://moody.mx**
- 🔬 Focus: web-scale RL/GA environments, high-dimensional geometry, GPU pipelines, representation learning
- 🧰 Tooling-first: I like projects that ship as *usable frameworks*, not just one-off demos

---

## What I work on

**Core themes**
- **Web ML & GPU systems**: WebGL / Three.js / GLSL pipelines that make training + visualization practical in-browser
- **Embodied / interactive learning**: Gym-style environments, instrumentation, evaluation harnesses, reproducible benchmarks
- **Geometry & representations**: rotations/projections in high dimensions, structured latent spaces, geometric primitives
- **Gradient-free optimization**: genetic algorithms, hybrid search, and alternatives/adjuncts to backprop in certain regimes

---

## Flagship projects

### 🐍 Snake-ML — N-Dimensional Reasoning on the Web
A framework for **high-dimensional Snake** where agents operate in continuous space with geometric action parameterizations (directional + angular components). Designed to run and visualize efficiently in the browser.

**Highlights**
- Web-first training/visualization pipeline (Three.js + WebGL)
- Experiments with **GA / gradientless optimization** and augmentation strategies
- Work on **rotation-plane actions** and signed-angle computations in high-D spaces

Repo: `https://github.com/blayyyyyk/snake-ml` 

---

### 🏎️ MarI/O Kart — Mario Kart DS as a Gym Environment
A **Gymnasium-registered** environment for Mario Kart DS with emulator-backed state extraction and agent evaluation.

**Highlights**
- Emulator instrumentation + structured observation/action interfaces
- Emphasis on making a *real* environment others can plug into (training scripts, eval, docs)

Repo: `https://github.com/blayyyyyk/gym-mkds`
Repo: `https://github.com/blayyyyyk/marIOkart`
Repo: `https://github.com/blayyyyyk/py-desmume-mkds`

---

### ⚡ Unified WebGL Context (UWC) + Web Visualization Acceleration
Systems work to reduce GPU/CPU sync overhead and improve throughput for interactive ML visualizations on the web.

**Highlights**
- Practical performance engineering in WebGL pipelines
- Resource lifecycle, texture transport, and minimizing stalls

Repo: `https://github.com/blayyyyyk/snake-ml`

---

## Other research-y builds

### 🧠 Alternative optimization experiments
Explorations around **fractional differentiation / “fractional gradients”**, Fourier-domain operators, and optimization variants for neural nets (prototype-heavy, theory-curious).

---

### 🧩 LEGO as a Directed Acyclic Graph (DAG)
A representation system for modeling LEGO constructions as a **piece-graph** with explicit connection semantics and robustness over connection types.

---

### 🧵 “BPE for vision” — contour tokenization
A tokenizer-inspired algorithm that mimics **Byte Pair Encoding**, but for **encoding contours of image segments** rather than text — exploring more meaningful object-level representations.

---

## Selected engineering / tooling

- **C/C++ ⇄ Python bindings**: clang-based header-to-ctypes workflows, memory mapping + structured state extraction
- **TensorFlow.js training loops**: scope/lifetime management, GPU memory behavior, stable in-browser trainers
- **Three.js internals**: textures, uniforms, WebGL resource binding, performance pitfalls
- **Dataset utilities**: memmap pipelines, synthetic DB generation, and reproducible data builds

If you’re browsing my repos, check:
- pinned projects (curated “mainline” work)

---

## Technical stack

**Languages**
- Python, TypeScript/JavaScript, C/C++, GLSL, (plus occasional Racket for theory coursework)

**ML / RL**
- PyTorch, TensorFlow.js, Gymnasium, custom GA harnesses

**Graphics / Web**
- WebGL, Three.js, React/Next.js, shader tooling

**Infra / dev**
- WSL/Linux tooling, performance profiling, reproducible scripts

---

## Papers / writing

- **Snake-ML**: manuscript + revisions in progress (web-native ML for N-D reasoning tasks)
- **MarI/O Kart**: paper-track framing in progress (environment + agent evaluation)

---

## Contact

- Website: **https://www.moody.mx/**
- GitHub: `@blayyyyyk`
- Email: `blake@mpsych.org`

---

## Collaboration

I’m most interested in collaborations around:
- web-deployable ML systems
- embodied agent benchmarks + environments
- geometric representations / structured priors
- performance engineering for interactive ML
