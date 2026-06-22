---
title: "Call for Papers"
featured_image: "/images/utrecht-netherlands.jpg"
description: "Submit your work on alternative architectures and generative paradigms for NLG"
---

## Overview

In the past few years, autoregressive transformers have been the dominant method in Natural Language Generation (NLG). While scaling these models has brought astounding results, this approach relies on a single generative paradigm (sequential next-token prediction), a single method (neural networks), and a single architecture (the transformer decoder). This layout comes with significant limitations: quadratic computational cost, an inability to correct mid-generation, and a lack of learning during inference time. Furthermore, high-quality training data is becoming scarce.

This workshop creates a dedicated forum — the **Alternative Architectures Project (AAP)** — to expand and diversify core NLG architecture research. Our goal is to encourage the community to focus on non-traditional machine learning structures that learn, process, and generate language differently.

---

## Core Themes

We invite submissions exploring any alternative core models and non-traditional generation paradigms. Topics of interest include, but are not limited to:

- **Non-autoregressive diffusion & flow paradigms** — Models that generate text by parallel refinement across a window rather than token-by-token, enabling native text rewriting and infilling.
- **Test-Time Training (TTT) & deep neural memory** — Architectures where model weights dynamically update during inference, replacing static KV caches to handle long contexts efficiently.
- **State Space Models (SSMs) & linear hybrids** — Layouts like Mamba that process sequences with linear complexity, enabling massive context processing at a fraction of the computing cost.
- **Joint Embedding Predictive Architectures (JEPA)** — Non-generative core structures that predict abstract concepts in a latent space instead of predicting individual surface tokens.
- **Explainable & transparent generation models** — Architectures with traceable reasoning paths instead of opaque calculations, allowing humans to see exactly why a model chooses its words.
- **Any other creative approaches** to more efficient, adaptive, or interpretable language generation.

---

## Target Communities

This workshop bridges deep learning theoreticians, engineers, and NLG researchers. We particularly target:

- Machine learning engineers creating new sequence layouts (SSMs, diffusion, TTT) who need robust linguistic evaluation settings.
- NLG researchers focusing on long-form text, dialogue, low-resource languages, and real-time interaction who face computational, data, and explainability constraints from standard Transformer implementations.

---

## Submission Guidelines

### Paper Types

| Type | Length | Scope |
|---|---|---|
| **Long papers** | Up to 8 pages (excl. references & appendices) | Completed work with evaluation |
| **Short papers** | Up to 4 pages | Preliminary results, negative findings, position pieces, demos |

- One extra page will be granted for camera-ready revisions.
- Supplementary material (code, data, appendices) is optional but encouraged and must be anonymised.

### Formatting

Submissions must follow the [ACL Author Guidelines](https://www.aclweb.org/adminwiki/index.php?title=ACL_Author_Guidelines) and use ACL style files. LaTeX and Microsoft Word templates are available at [https://acl-org.github.io/ACLPUB/formatting.html](https://acl-org.github.io/ACLPUB/formatting.html).

### Review

Review is **double-blind**. Please ensure your submission is fully anonymised.

### Multiple-Submission Policy

Non-archival versions may be under review elsewhere. Please indicate any parallel submissions at submission time.

### Submission Site

Papers should be submitted through OpenReview:

**[Submit on OpenReview](https://openreview.net/)** — *link will be updated when the submission site is open*

---

## Important Dates

| Event | Date |
|---|---|
| First Call for Papers | 1 June 2026 |
| **Workshop Paper Submission Due** | **1 August 2026** |
| Paper Acceptance Notification | 1 September 2026 |
| Camera-Ready Papers Due | 16 September 2026 |
| INLG 2026 Conference | 17–21 October 2026 |
| **AAP Workshop** | **18 October 2026** (TBC) |

All deadlines are 23:59 Anywhere on Earth (AoE).

---

**Contact:** [r.j.a.kuiper@umcutrecht.nl](mailto:r.j.a.kuiper@umcutrecht.nl) · [a.bagheri@uu.nl](mailto:a.bagheri@uu.nl)
