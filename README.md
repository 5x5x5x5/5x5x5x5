# Daniel Siegle

**Applied ML engineer · Durham, NC**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![JAX](https://img.shields.io/badge/JAX-9cf?logo=google&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![uv](https://img.shields.io/badge/uv-Astral-261230?logo=astral&logoColor=white)
![Vim](https://img.shields.io/badge/Vim-019733?logo=vim&logoColor=white)

I build ML systems, and I keep coming back to where they meet biology and drug manufacturing; my master's thesis was on predicting cytochrome P450 inhibition. The rest of what's here is **evals and training pipelines**, **market mechanisms**, and **teaching material**. A few things exist purely because they were fun to build.

---

## 🧬 Life sciences and manufacturing

**[batchlens](https://github.com/5x5x5x5/batchlens)** — Batch analytics for monoclonal antibody manufacturing, on synthetic data. It follows product mass from cell culture through the purification train and says where a batch left the reference, what that cost in grams, and which records the statement rests on. Built as an app for the open [PlantCraft](https://plantcraft.io) suite.

**[taihls](https://taihls.com)** 🚧 — An interactive textbook on AI for health and life sciences, with in-browser runnable code. Landing chapter by chapter.

**[applied-ml-portfolio](https://danielsiegle.com/applied-ml-portfolio/)** 🚧 — Applied ML and pharma projects: AWS MLOps, RAG, CNNs, drug discovery.

**[CYP-thesis-edits](https://github.com/5x5x5x5/CYP-thesis-edits)** — My 2015 master's thesis, classifying cytochrome P450 inhibitors with statistical learning, with notebooks that re-run the models. Currently being revised with Claude.

## 🔧 Evals, training and generative pipelines

**[dear-reader-bench](https://github.com/5x5x5x5/dear-reader-bench)** — An LLM benchmark for translating comedic narration (à la *Wizard People, Dear Reader*): does the humor, voice, and running gags survive the trip into another language?

**[grpo-countdown-modal](https://github.com/5x5x5x5/grpo-countdown-modal)** — GRPO fine-tuning on Modal GPUs: LoRA-tunes small Qwen models on Countdown arithmetic and MBPP code generation with verifiable, sandboxed rewards.

**[celery-man](https://github.com/5x5x5x5/celery-man)** — A music-video pipeline with no theme built in: give it a song and it times the beats, writes a brief and a shot list, generates stills and clips (FLUX + LTX on Modal), and cuts on the beat. Each creative decision is made by you or by a model.

**[commentary-track](https://github.com/5x5x5x5/commentary-track)** — AI director's commentary for films: give it a subtitle file and a persona, get a timed commentary track (and optional audio) that never talks over the dialogue.

**[ai-vocabulary](https://danielsiegle.com/ai-vocabulary/)** — Fourteen years of what the field called itself: 78 terms tracked across 625,000 arXiv AI papers, 2012–2026, as an animated word cloud, streamgraph, and sparklines.

## ⚖️ Markets and mechanisms

**[marketplace](https://github.com/5x5x5x5/marketplace)** — Two-sided marketplace API where the platform sets buyer price and seller payout independently and keeps the spread. FastAPI + Pydantic v2, runtime-tunable pricing and matching. Companion: [auction](https://github.com/5x5x5x5/auction), a minimal sealed-bid call auction.

**[quant-lessons](https://danielsiegle.com/quant-lessons/)** — An eight-unit curriculum from first principles to trading primitives: options, Greeks, vol surfaces, backtesting, ML for finance. Also available as [malick-money](https://danielsiegle.com/malick-money/), the same material in Terrence Malick voiceover.

## 📚 Teaching and curricula

**[learn-jax](https://github.com/5x5x5x5/learn-jax)** — Notes on JAX and XLA — jit, vmap, grad, pytrees, sharding — plus 100 hands-on puzzles.

**[ghidra-journey](https://danielsiegle.com/ghidra-journey/)** — A self-paced 14-module reverse-engineering curriculum for Ghidra on Linux x86-64.

**[schemer](https://danielsiegle.com/schemer/)** 🚧 — An in-browser CS tutor in the question-and-answer style of *The Little Schemer*.

**[APL, out loud](https://danielsiegle.com/apl/)** — A beginner APL tutorial with a live interpreter on the page: say the symbol names out loud and run them, up to Conway's Game of Life in one line.

## 🎲 Tools and toys

**[gutenberg-typist](https://github.com/5x5x5x5/gutenberg-typist)** — Vim plugin for touch-typing practice by transcribing Project Gutenberg books, with per-character feedback and WPM stats. [Plugin site](https://danielsiegle.com/gutenberg-typist/) · [leaderboard](https://danielsiegle.com/typist-guild/)

**[phantom-architecture](https://danielsiegle.com/phantom-architecture/)** — Twenty-five architectural designs that never left the page, rendered as deterministic SVG blueprints. Vibe-coded by dictation.

**[deploy-pony](https://danielsiegle.com/deploy-pony/)** — Java deployment hell as an interactive site, in two aesthetics: neon-lit dark or pastel and bouncy. May your heap never overflow.

**[arcade](https://danielsiegle.com/arcade/)** — Vibe-coded browser games, each a single static HTML file: a diner-themed match-3 and a 3D cat-chases-dogs romp.

**[craps](https://danielsiegle.com/craps/)** — A craps simulator with built-in tutorial, in plain JavaScript.

**[ELIZA](https://danielsiegle.com/eliza/)** — Weizenbaum's 1966 DOCTOR script, compiled to WebAssembly and printed on teletype paper.

## 🗺️ Elsewhere

I founded and run **[Deep Learning RTP](https://www.meetup.com/deep-learning-rtp/)** — a Research Triangle meetup for people building with neural networks. The [group site](https://deeplearningrtp.org) runs its ML demos entirely in-browser; [dlrtp-build-and-learn](https://github.com/DeepLearningRTP/dlrtp-build-and-learn) archives 82 topics across 120 sessions.

More at [danielsiegle.com](https://danielsiegle.com). Consulting through [Possible Futures](https://possiblefutures.bio).
