# 👋 Hi, I'm Emmanuel Ajala

### ML Systems Engineer | Distributed Training | LLM Inference | ML Research

I build and investigate machine learning systems with a focus on **performance, efficiency, and reproducibility**.

My work starts with a technical question, not a technology:

> **What is the bottleneck, what changes when I alter it, and what does the evidence show?**

I use controlled experiments to study trade-offs across **compute, memory, communication, latency, throughput, and model quality**.

---

## 🔬 What I Work On

* **ML Systems** — distributed training, multi-GPU workloads, communication/computation trade-offs, and performance bottlenecks
* **LLM Systems** — inference, KV caching, retrieval-augmented generation, and serving
* **Efficient ML** — PEFT, quantization, memory efficiency, and model optimization
* **Deep Learning** — PyTorch implementations and reproductions of research papers from first principles
* **Experimentation** — controlled benchmarks, profiling, reproducibility, and failure analysis

---

## 🧪 How I Approach Engineering

I try to make every investigation answer five questions:

1. **What is the hypothesis?**
2. **What variables need to be controlled?**
3. **What should be measured?**
4. **What actually happened?**
5. **What engineering conclusion follows from the evidence?**

I'm particularly interested in situations where improving one dimension makes another worse:

**latency ↔ throughput**
**memory ↔ compute**
**communication ↔ scaling**
**model quality ↔ efficiency**

---

## 🚀 Selected Work

### [PEFT Benchmark](https://github.com/manofvalour/PEFT_benchmark)

Controlled experiments comparing **LoRA, AdaLoRA, IA³, DoRA, and Prefix Tuning**.

I measure the trade-offs between:

* Model quality
* Trainable parameters
* GPU memory
* Training performance

The goal is to understand the **Pareto frontier of parameter-efficient adaptation**, rather than simply identify a single "best" method.

### Model Replication

From-scratch implementations of architectures and techniques from research papers, including:

* Transformer
* GPT-2
* Mixture-of-Experts
* KV caching

The focus is on understanding the implementation details behind the papers, validating assumptions, and investigating discrepancies between expected and observed behavior.

### Multi-Agent RAG System

A production-oriented RAG system built with **FastAPI, Qdrant, Redis, and multiple LLM providers**.

The system includes retrieval, reranking, query expansion, claim verification, confidence scoring, semantic caching, evaluation, and observability.

---

## 📚 Current Research Direction

I'm currently focused on **ML systems research**, particularly:

* Distributed training under constrained network conditions
* Communication-efficient training
* LLM inference efficiency
* Quantization and memory trade-offs
* GPU performance analysis
* Reproducible ML systems benchmarks

---

## 🛠️ Technologies

**Languages:** Python, SQL

**ML:** PyTorch, Scikit-learn

**LLM / Retrieval:** Qdrant, FAISS, RAG

**Systems:** FastAPI, Docker, Redis

**Observability:** OpenTelemetry, Prometheus, Grafana

**Experimentation:** Benchmarking, profiling, controlled experiments

---

## 📫 Connect

* [LinkedIn](https://www.linkedin.com/in/emmanuelajala)
* [Portfolio](https://emmanuelajala.netlify.app)
* Email: [ajalae2@gmail.com](mailto:ajalae2@gmail.com)

---

> **Evidence over intuition.**
>
> Build the experiment. Measure the system. Understand the trade-off.
