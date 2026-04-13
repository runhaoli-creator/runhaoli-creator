<div align="center">

# Runhao Li

### Building intelligent multi-agent LLM systems

LLM Agent Engineer · MS CS @ University of Southern California

[![Email](https://img.shields.io/badge/Email-runhaoli%40usc.edu-0078D4?style=flat&logo=gmail&logoColor=white)](mailto:runhaoli@usc.edu)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-runhao--li-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/runhao-li-lee021004)
[![GitHub](https://img.shields.io/badge/GitHub-runhaoli--creator-181717?style=flat&logo=github&logoColor=white)](https://github.com/runhaoli-creator)

</div>

---

## About

I design and post-train **multi-agent LLM systems** — from learned inter-agent communication protocols to data-centric alignment pipelines to production vLLM serving stacks. My focus is on agent teams that are reliable, interpretable, and cheap to deploy end-to-end.

**Current interests:** multi-agent orchestration · post-training (DPO / KTO / GRPO) · vLLM multi-LoRA serving · agent evaluation harnesses · learned latent communication protocols.

---

## Featured Projects

### [latent-agent-team](https://github.com/runhaoli-creator/latent-agent-team) &nbsp;·&nbsp; Budgeted Multi-Agent Communication

Five-agent team (Planner · Retriever · Browser · Verifier · Memory) that replaces natural-language inter-agent messages with **learned latent channels** — continuous embeddings or VQ codes with an adaptive bitrate scheduler.

**Results** · Mind2Web **81.5%** ElemAcc · WebShop **72.4%** SR · AgentBench **66.8%** SR

### [acm-icl](https://github.com/runhaoli-creator/acm-icl) &nbsp;·&nbsp; Autonomy-Calibrated Multi-Agent In-Context Learning

Four-stage inference pipeline (**Solver → Skeptic → Verifier → Calibrated Judge**) with DD-CoT structured reasoning and per-peer reliability scoring for epistemic robustness under adversarial peer pressure.

**Results** · **73.9%** average across 5 peer-pressure benchmarks · **+13.7 pp** over strongest multi-agent-debate baseline (MAD)

### [dmapo](https://github.com/runhaoli-creator/dmapo) &nbsp;·&nbsp; Data-centric Multi-Agent Preference Optimization

Six-stage data-centric alignment pipeline — prompts → on-policy generation → three-judge multi-agent scoring (Qwen3-8B) → process critic → confidence gating → KTO. Unified trainer supporting DPO / KTO / ORPO / SimPO / SFT.

**Results** · Mistral-7B on only **1,871** gated examples (3.45% accept rate) beats every baseline trained on 10–20k — MT-Bench **7.62** · AlpacaEval **96.3%** · win-rate **85.3%** vs. 68.2% best baseline

---

## More Agent Research

| Repo | Summary |
|------|---------|
| [**updr-reasoning**](https://github.com/runhaoli-creator/updr-reasoning) | Uncertainty-Prompted Debate and Repair — adaptive-compute multi-persona reasoning with uncertainty-gated self-repair |
| [**RAMTL**](https://github.com/runhaoli-creator/RAMTL) | Role-Adaptive Multi-Tool Learning — single-backbone multi-role agent framework for tool use and function calling |
| [**DEAMS**](https://github.com/runhaoli-creator/DEAMS) | Decentralized Epistemic Alignment for Multimodal Swarms — MA-GRPO across heterogeneous Qwen-VL / InternVL agents |
| [**PAGC**](https://github.com/runhaoli-creator/PAGC) | Partner-Adaptive Grounded Communication — cooperative MARL with emergent text-grounded communication |
| [**KTM-WM**](https://github.com/runhaoli-creator/KTM-WM) | Training-free kernel-trick world models for LLM agent planning (beam / MPC / CEM planners) |

---

## Tech Stack

**LLM / Agent Frameworks**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)
![TRL](https://img.shields.io/badge/TRL-FFBE0B?style=flat)
![PEFT](https://img.shields.io/badge/PEFT-FF6F61?style=flat)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat)
![Function%20Calling](https://img.shields.io/badge/Function%20Calling-6E44FF?style=flat)
![Outlines](https://img.shields.io/badge/outlines-4B32C3?style=flat)

**Models**

![Qwen](https://img.shields.io/badge/Qwen2.5-1677FF?style=flat)
![Llama](https://img.shields.io/badge/Llama%203-0867EC?style=flat)
![Mistral](https://img.shields.io/badge/Mistral-FF7000?style=flat)
![Gemma](https://img.shields.io/badge/Gemma%202-4285F4?style=flat)
![Phi](https://img.shields.io/badge/Phi--3-5E5DF0?style=flat)
![Qwen-VL](https://img.shields.io/badge/Qwen2--VL-1677FF?style=flat)

**Retrieval / RAG**

![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat)
![BGE](https://img.shields.io/badge/BGE-FFD21E?style=flat)
![BM25](https://img.shields.io/badge/BM25-8E44AD?style=flat)
![Reranker](https://img.shields.io/badge/bge--reranker--v2-FFD21E?style=flat)
![HyDE](https://img.shields.io/badge/HyDE-6A5ACD?style=flat)
![Vector%20DB](https://img.shields.io/badge/Vector%20DB-00A3E0?style=flat)

**Training / Post-Training**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![QLoRA](https://img.shields.io/badge/QLoRA-4B32C3?style=flat)
![DPO](https://img.shields.io/badge/DPO-2E8B57?style=flat)
![KTO](https://img.shields.io/badge/KTO-2E8B57?style=flat)
![GRPO](https://img.shields.io/badge/GRPO-2E8B57?style=flat)
![DeepSpeed](https://img.shields.io/badge/DeepSpeed-1E90FF?style=flat)
![Accelerate](https://img.shields.io/badge/Accelerate-FFBE0B?style=flat)
![FSDP](https://img.shields.io/badge/FSDP-EE4C2C?style=flat)

**Deployment / Serving**

![vLLM](https://img.shields.io/badge/vLLM-EE4C2C?style=flat)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![SageMaker](https://img.shields.io/badge/SageMaker-232F3E?style=flat&logo=amazon&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)

**Evaluation / MLOps**

![wandb](https://img.shields.io/badge/Weights%20%26%20Biases-FFBE00?style=flat&logo=weightsandbiases&logoColor=black)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white)
![LLM--as--Judge](https://img.shields.io/badge/LLM--as--Judge-6E44FF?style=flat)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)

**General**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Hydra](https://img.shields.io/badge/Hydra-54C7EC?style=flat)

---

## GitHub Stats

<div align="center">

![Runhao's GitHub stats](https://github-readme-stats.vercel.app/api?username=runhaoli-creator&show_icons=true&hide_border=true&count_private=true&include_all_commits=true&rank_icon=github)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=runhaoli-creator&layout=compact&hide_border=true&langs_count=8)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=runhaoli-creator&hide_border=true)

</div>

---

<div align="center">

**Open to full-time LLM Agent Engineer roles · 2026**

[runhaoli@usc.edu](mailto:runhaoli@usc.edu) &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/runhao-li-lee021004) &nbsp;·&nbsp; [GitHub](https://github.com/runhaoli-creator)

</div>
