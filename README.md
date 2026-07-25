# Daniel Siegle

**Applied ML engineer · Durham, NC**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![JAX](https://img.shields.io/badge/JAX-9cf?logo=google&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![uv](https://img.shields.io/badge/uv-Astral-261230?logo=astral&logoColor=white)
![Vim](https://img.shields.io/badge/Vim-019733?logo=vim&logoColor=white)

Most of what's here falls into four buckets: **training and serving pipelines**, **evals and benchmarks**, **market mechanisms**, and **teaching material**. A few things exist purely because they were fun to build.

---

## 🔧 Selected work

**🚧[applied-ml-portfolio](https://5x5x5x5.github.io/applied-ml-portfolio/)** — A portfolio of applied ML and pharma projects: AWS MLOps, RAG, CNNs, drug discovery. Being built out constantly.

**[dear-reader-bench](https://github.com/5x5x5x5/dear-reader-bench)** — An LLM benchmark for translating comedic narration (in the spirit of *Wizard People, Dear Reader*): can a model carry humor, voice, and running gags into another language? Headline DRS score combines a performability check (does the read fit its time window?) with a Bradley-Terry-aggregated win rate over judged humor/voice/gags/fidelity.

**[grpo-countdown-modal](https://github.com/5x5x5x5/grpo-countdown-modal)** — GRPO fine-tuning ported to Modal GPUs: LoRA-tunes small Qwen models on a Countdown arithmetic puzzle and MBPP code generation using binary, verifiable rewards with sandboxed execution. Self-contained HTML training reports and a web endpoint serving the trained solver.

**[Gorganzola](https://github.com/5x5x5x5/Gorganzola)** — Generates AI director's-commentary tracks for films from a subtitle file: chapters the film, writes timed commentary in a chosen persona (director, historian, rifftrax…), stays out of the way of the actual dialogue, and optionally renders a spoken audio track. Claude-first with 10+ pluggable inference providers and 21 languages.

**[marketplace](https://github.com/5x5x5x5/marketplace)** — Two-sided marketplace API where the platform sets buyer price and seller payout independently and keeps the spread. FastAPI + Pydantic v2, runtime-tunable pricing pipelines with pluggable adjusters and matching strategies. Companion piece: [auction](https://github.com/5x5x5x5/auction), a deliberately minimal sealed-bid call auction with an honest write-up of its mechanism-design trade-offs.

**[LLM_tuning_demonstration](https://github.com/5x5x5x5/LLM_tuning_demonstration)** — End-to-end LLM fine-tuning pipeline: data prep → QLoRA SFT → DPO alignment → merge → quantization → eval harness (BLEU/ROUGE/BERTScore/LLM-judge) with regression gates → vLLM serving. Typer CLI, 74 CPU-runnable tests, CI with a `--tiny` smoke path.

**[learn-jax](https://github.com/5x5x5x5/learn-jax)** — Working notes on JAX and XLA: jit, vmap, grad, pytrees, sharding, plus 100 hands-on puzzles.

**[gutenberg-typist](https://github.com/5x5x5x5/gutenberg-typist)** — Vim plugin for touch-typing practice by transcribing Project Gutenberg books. Per-character feedback, WPM/accuracy in the statusline, idempotent cross-machine stat merging. [Plugin site](https://5x5x5x5.github.io/gutenberg-typist/) · [typist-guild leaderboard](https://5x5x5x5.github.io/typist-guild/)

## 📚 Teaching and curricula

**[quant-lessons](https://5x5x5x5.github.io/quant-lessons/)** — An eight-unit curriculum from first principles to trading primitives: options, Greeks, vol surfaces, backtesting, ML for finance. Also available as [the-way-of-grace](https://5x5x5x5.github.io/the-way-of-grace/), the same material delivered in Terrence Malick voiceover.

**[ghidra-journey](https://5x5x5x5.github.io/ghidra-journey/)** — A 14-module self-paced reverse-engineering curriculum for Ghidra on Linux x86-64.

**[taihls](https://5x5x5x5.github.io/taihls/)** 🚧 — An interactive textbook on AI for health and life sciences. MyST/Jupyter Book 2 with in-browser runnable code via JupyterLite. Toolchain and exemplar chapter are done; content is landing chapter by chapter.

## 🎲 Just for fun

**[phantom-architecture](https://5x5x5x5.github.io/phantom-architecture/)** — A catalog of twenty-five architectural designs that never left the page, each rendered as a deterministic SVG blueprint. An experiment in vibe coding by dictation.

**[deploy-pony](https://5x5x5x5.github.io/deploy-pony/)** — "Enterprise Nightmares": Java deployment hell as an interactive site, in your choice of two aesthetics — dark and neon-lit, or pastel and bouncy. Brought to you by AbstractSingletonProxyFactoryBean LLC. May your heap never overflow.

**[craps](https://github.com/5x5x5x5/craps)** — An educational craps simulator with a built-in tutorial, in plain JavaScript.

## 🌐 Live sites

Everything above with a working GitHub Pages deployment, in one place:

- [applied-ml-portfolio](https://5x5x5x5.github.io/applied-ml-portfolio/) — applied ML and pharma project portfolio
- [quant-lessons](https://5x5x5x5.github.io/quant-lessons/) — quant finance curriculum
- [the-way-of-grace](https://5x5x5x5.github.io/the-way-of-grace/) — the same curriculum, Malick voiceover
- [ghidra-journey](https://5x5x5x5.github.io/ghidra-journey/) — reverse-engineering curriculum
- [taihls](https://5x5x5x5.github.io/taihls/) — AI for health and life sciences textbook 🚧
- [gutenberg-typist](https://5x5x5x5.github.io/gutenberg-typist/) — Vim typing-practice plugin site
- [typist-guild](https://5x5x5x5.github.io/typist-guild/) — typing leaderboard
- [phantom-architecture](https://5x5x5x5.github.io/phantom-architecture/) — unbuilt buildings as SVG blueprints
- [deploy-pony](https://5x5x5x5.github.io/deploy-pony/) — Java deployment hell, two ways
- [deeplearningrtp.github.io](https://deeplearningrtp.github.io/) — Deep Learning RTP's site, with sentiment analysis, image classification, and local LLM chat running entirely in your browser

## 🗺️ Elsewhere

I founded and run **[Deep Learning RTP](https://www.meetup.com/deep-learning-rtp/)** — a Research Triangle meetup for people building with neural networks. The [group site](https://deeplearningrtp.github.io/) runs its ML demos in-browser via Transformers.js and WebLLM, and [dlrtp-build-and-learn](https://github.com/DeepLearningRTP/dlrtp-build-and-learn) archives 82 topics across 120 sessions of talks, workshops, and build nights.
