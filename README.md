<div align="center">

# Runhao Li

### LLMs · Reliable Agents · ML Systems

M.S. Computer Science (AI) at **USC** · Graduating **May 2027** · Los Angeles

[Website](https://runhao-li.runhaolee136.chatgpt.site) · [Google Scholar](https://scholar.google.com/citations?user=HkEIcZ0AAAAJ&hl=en) · [LinkedIn](https://www.linkedin.com/in/runhao-li-lee021004) · [Email](mailto:runhaoli@usc.edu)

**Seeking 2027 opportunities in Software Engineering (AI/ML) and Machine Learning Engineering.**

</div>

---

I build and evaluate LLM systems, from model post-training and agent orchestration to inference services and evaluation tooling. My experience spans ML engineering internships at **TikTok**, **General Motors**, and **Shanghai AI Laboratory**, and research at **Princeton** and **UC Berkeley**.

[Industry experience](#industry-experience) · [Featured research & code](#featured-research--code) · [Research](#research) · [Toolkit](#toolkit)

## Industry experience

**TikTok · Machine Learning Engineer Intern**  
Bellevue, WA · Jun–Sep 2026

- Post-trained a router–expert moderation cascade with SFT and KTO, improving production precision and recall by approximately **13.5 percentage points** while routing **15% of traffic** to the expert.
- Fine-tuned a multimodal moderation model, raising AUC from **0.75 to 0.93**; built CaseBank Agent for case replay, human review, and hard-example collection.

**General Motors · Machine Learning Engineer Intern**  
Detroit, MI · Jan–Apr 2026

- Co-developed **PreDiff-LM**, adapting pretrained autoregressive models to masked diffusion through hybrid attention.
- Under matched initialization and training, improved WikiText-103 perplexity from **34.1 to 28.7** over uniform bidirectional attention; studied confidence-aware parallel decoding and self-conditioning.

**Shanghai AI Laboratory · Machine Learning Engineer Intern**  
Shanghai, China · Jun–Sep 2025

- Built a LangGraph agent workflow that improved task success from **61% to 83%**, and hybrid retrieval that raised Recall@5 from **71% to 89%**.
- Fine-tuned and served vision-language models with QLoRA, vLLM, FastAPI, and Redis, achieving **p95 latency below 500 ms**.

## Featured research & code

### DMAPO — Less Data, Better Alignment

**Data-Centric Multi-Evaluator Agreement for Preference Optimization**

A model-alignment pipeline that generates on-policy responses, scores them with specialized evaluators, and uses agreement and confidence filtering to select preference-training data. The paper studies a curated set of **1,871 examples from 54,236 candidates**, with KTO training and controlled comparisons against other preference-optimization methods.

**Engineering:** candidate generation · multi-evaluator scoring · LoRA training · evaluation pipelines  
[Paper](https://arxiv.org/abs/2607.25136) · [Code](https://github.com/runhaoli-creator/dmapo) · [Training implementation](https://github.com/runhaoli-creator/dmapo/blob/main/src/dmapo/training/train.py)

### PreDiff-LM — Hybrid Attention for Diffusion Language Models

**Pretrained Discrete Masked Diffusion Language Modeling with Hybrid Attention**

Adapts pretrained autoregressive transformers to masked diffusion while retaining causal attention in the observed prompt and bidirectional attention in the target. Under matched initialization and training, hybrid attention improves WikiText-103 perplexity from **34.1 to 28.7** and MAUVE from **0.71 to 0.78** over uniform bidirectional attention.

**Research:** attention adaptation · discrete diffusion · confidence-aware decoding · controlled evaluation  
[Paper](https://arxiv.org/abs/2607.25157) · [OpenReview](https://openreview.net/forum?id=zl9y14yJuN)

<details>
<summary><strong>Other open-source projects</strong></summary>

- [ACM-ICL](https://github.com/runhaoli-creator/acm-icl) — Agent reliability, calibrated reasoning, and vLLM multi-LoRA serving.
- [paper_read](https://github.com/runhaoli-creator/paper_read) — Research workflows and citation-verification tools.
- [latent-agent-team](https://github.com/runhaoli-creator/latent-agent-team) — Budgeted latent communication between agents.
- [RAMTL](https://github.com/runhaoli-creator/RAMTL) — Shared-backbone, multi-role tool use.
- [updr-reasoning](https://github.com/runhaoli-creator/updr-reasoning) — Uncertainty-guided debate and self-repair.
- [DEAMS](https://github.com/runhaoli-creator/DEAMS) — Alignment across heterogeneous vision-language agents.
- [PAGC](https://github.com/runhaoli-creator/PAGC) — Grounded communication in cooperative multi-agent learning.
- [KTM-WM](https://github.com/runhaoli-creator/KTM-WM) — Kernel-based world models for agent planning.

</details>

## Research

| Experience | Work |
| :--- | :--- |
| **Princeton University** · Research Assistant<br>May–Sep 2026 | **Insurance Credit:** causal evaluation of preventive agent actions; fault-injection experiments across 50,000+ episodes and five agents. |
| **UC Berkeley** · Research Assistant<br>Sep–Dec 2025 | **Data-centric alignment:** multi-evaluator agreement, confidence filtering, and preference optimization; asynchronous judge services with FastAPI, Redis, Docker, and CI. |

My research interests include agent reliability, diffusion language models, model alignment, and physical reasoning.

[Publications & project details](https://runhao-li.runhaolee136.chatgpt.site/#publications) · [Google Scholar](https://scholar.google.com/citations?user=HkEIcZ0AAAAJ&hl=en) · [OpenReview](https://openreview.net/profile?id=~Runhao_Li3)

## Toolkit

| Area | Technologies |
| :--- | :--- |
| **Software & services** | Python · C++ · SQL · FastAPI · Docker · Kubernetes · AWS · Redis |
| **Training & alignment** | PyTorch · Transformers · TRL · PEFT · LoRA/QLoRA · DeepSpeed · FSDP |
| **Agents, retrieval & inference** | LangGraph · vLLM · FAISS · BM25 · Reranking |
| **Evaluation & delivery** | MLflow · Weights & Biases · GitHub Actions |

**Education:** USC M.S. Computer Science, AI track (2025–2027, GPA 4.0/4.0) · Hong Kong Baptist University B.S. Computer Science, Honors (2021–2025, GPA 3.96/4.0).

---

Interested in LLMs, agents, or ML infrastructure? [Get in touch](mailto:runhaoli@usc.edu).
