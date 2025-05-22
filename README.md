# LLM Drift Observatory 🛰️

A hands-on framework for detecting and visualizing **behavioral drift** in Large Language Models (LLMs) across versions and providers.

## 🧠 Why this matters

Model updates often happen silently. Prompt behavior subtly shifts. Outputs change tone, verbosity, or factuality — without a version bump or changelog.

If you're building real-world systems on top of LLMs, this is not an edge case. It's your **prod environment**.

This repo helps you:

- Track **instruction-following degradation**
- Compare **hallucination control** across models
- Evaluate **tone and verbosity drift**
- Visualize changes over time or across vendors

---

## 🧩 What's inside

### `drift-tests/`
Prompt suites organized by category:
- `instruction-following`
- `tone-style-consistency`
- `hallucination-control`

### `scoring/`
Define your metrics: factuality, clarity, verbosity, alignment, etc.

### `outputs/`
Raw completions from models like GPT-4, GPT-4.1, Claude, Mistral

### `notebooks/`
Includes `drift_analysis.ipynb` — for analyzing and visualizing drift across versions

---

## 📊 Use cases

✅ Choosing between models for product integration  
✅ Verifying that model upgrades don’t silently break UX  
✅ Building trust in AI-powered systems through stability  
✅ Equipping PMs and engineers with repeatable drift detection

---

## 💡 Planned

- Session-based behavioral fingerprinting  
- Streaming output drift (for GPT-4o)  
- Regression alerts via GitHub Actions

---

## 🧭 Get Started

1. Drop your prompts into `drift-tests/`
2. Run completions via API or platform
3. Save raw outputs in `outputs/`
4. Analyze drift in `notebooks/`

---

## 📣 Why this matters

Evaluation isn't just about "score".  
It's about **knowing when your model has changed** — before your users tell you.

---
