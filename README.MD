<!-- HEADER -->
<div align="center">

# 👋 Hi, I'm Amit

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=14B8A6&center=true&vCenter=true&width=800&lines=AI+Solutions+Architect+%26+Technical+Product+Manager;AI+Infrastructure+%26+Agentic+Platforms;Open-Source+Models%3A+Training+to+Production" alt="Typing SVG" />
</a>

<br/><br/>

[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-amitgambhir.com-0d9488?style=for-the-badge)](https://amitgambhir.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/amitgambhir)
[![Hugging Face](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/amitgambhir)
[![Twitter](https://img.shields.io/badge/Twitter-000000?style=for-the-badge&logo=x&logoColor=white)](https://twitter.com/gambhir_amit)

</div>

---

## 🧭 About Me

I'm a builder who has spent 15+ years in the gap between "this works in a demo" and "this works in production." I started on product and platform teams, led an enterprise RAG/LLM platform from first prototype to something the business trusted in live, high-stakes workflows, and now work as an AI Solutions Architect.

What I care about most are the decisions that look technical but are really business decisions: which model is good enough, shared API or dedicated GPUs, how much latency and cost a product can take. Get them wrong and you pay for GPUs you don't need, or ship something nobody will wait for.

The lesson I keep coming back to: **AI products rarely fail because of the model. They fail on everything around it.**

This GitHub is where I build to learn. Most of what's here started as a question I couldn't answer from docs or vendor benchmarks, so I built something and measured it.

---

## 🛰️ How I Approach a Problem

1. **Start with the workload.** What does "good" mean here: quality, latency, throughput, cost? Write it down first.
2. **Make the trade-offs on purpose.** API vs. dedicated, vLLM vs. SGLang vs. TRT-LLM, which GPU, which quantization. Say what you rejected and why.
3. **Prove it on real traffic.** Load tests and concurrency sweeps, and report what missed, too.
4. **Plan for day two.** Cold starts, autoscaling, observability, and the bill.

---

## 🛠️ What I'm Into Right Now

- **Inference serving:** vLLM, SGLang, TensorRT-LLM · batching, KV cache, quantization, speculative decoding
- **Performance & sizing:** TTFT / TPOT under concurrency · GPU selection · cost per token
- **Evaluating AI systems:** RAG evaluation (RAGAS, LLM-as-judge) and behavioral evals for agents
- **Agents with guardrails:** multi-agent setups where a human still approves what matters

---

## 🧪 Things I've Built

| | Project | What It Is |
|:---:|---|---|
| ⚡ | [**LLM Inference Bench**](https://github.com/amitgambhir/llm-inference-bench) | Llama 3.1 8B FP8 on an NVIDIA L4 with vLLM: concurrent load tests, quality evals, and a deployment advisor built on measured data |
| 🔍 | [**RAG Auditor**](https://github.com/amitgambhir/rag-auditor) | Open-source RAG evaluation: scores faithfulness, relevancy, and hallucination risk |
| 🧪 | [**agent-eval-kit**](https://github.com/amitgambhir/agent-eval-kit) | Tests whether agents honor their spec (role, scope, escalation, handoff) with Claude-as-judge and PR-gated CI |
| 🖼️ | [**Multimodal Agentic RAG**](https://github.com/amitgambhir/multimodal-agentic-rag) | Multimodal RAG with runtime Claude↔Gemini switching, caption-then-embed for images, and a 3D embedding-space visualizer |
| 🤖 | [**Multi-LLM RAG Agent Chat**](https://github.com/amitgambhir/multi-llm-rag-agent-chat) | Containerized RAG chatbot that routes queries between GPT-4o and Gemini by complexity |
| 🏛️ | [**Inner Circle AI**](https://github.com/amitgambhir/inner-circle-ai) | Five AI agents, one team, and you're the CEO: a file-based multi-agent framework with approval governance |
| 🌐 | [**amitgambhir.com**](https://amitgambhir.com) | My portfolio, with `@amit-ai`, a RAG chatbot on Claude + Voyage + pgvector that RAG Auditor grades |

---

## ✍️ Writing

I write about inference, RAG, agents, and whatever I'm building at the moment → [amitgambhir.com/blog](https://amitgambhir.com/blog)

---

## 🤝 Say Hi

I'm always up for a conversation about running open-source models in production, how to choose between APIs and dedicated GPUs, or RAG and agent systems that hold up under real traffic.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/amitgambhir)
[![Twitter](https://img.shields.io/badge/Twitter-000000?style=for-the-badge&logo=x&logoColor=white)](https://twitter.com/gambhir_amit)

<br/>

</div>
