# Awesome-Graph-Engineering

<div align="center">
  <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
  <a href="http://makeapullrequest.com"><img src="https://img.shields.io/badge/PRs-welcome-green.svg" alt="PRs welcome"></a>
  <a href="https://github.com/DEEP-JLU/Awesome-Graph-Engineering"><img src="https://img.shields.io/github/stars/DEEP-JLU/Awesome-Graph-Engineering?style=flat" alt="GitHub stars"></a>
</div>

A curated collection of research papers, benchmarks, and open-source projects on **Graph Engineering in the era of LLM agents**. This repository accompanies the survey *Graph Engineering in the Era of LLM Agents: From Individual Intelligence to System Intelligence* and will be continuously updated.

Graph Engineering studies how explicit, dynamic, and evolving graph structures can organize tasks, coordinate heterogeneous agents, maintain runtime state, and support system evolution. The collection follows the survey's progression from **Model Intelligence**, through **Individual Intelligence**, to **System Intelligence**.

🤗 **Contributions are welcome.** If you find a missing resource or a relevant new work, please open an issue or submit a pull request.

**📃 Please [cite our paper](#-citation)** if you find this survey or repository helpful.

---

## 🎉 News

- **[2026-08]** We release the initial resource collection for Graph Engineering in the era of LLM agents.

## Overview

Graph Engineering provides a structured path from standalone model capability to coordinated system-level intelligence:

- **Model Intelligence** builds and adapts foundation-model capabilities through parameterized training, prompt engineering, and context engineering.
- **Individual Intelligence** equips a single agent with tools, memory, skills, runtime orchestration, and persistent interaction loops.
- **System Intelligence** organizes tasks, agents, runtime state, and system evolution through explicit graph structures, with ontology engineering providing a shared semantic layer.

## Table of Contents

- [Awesome-Graph-Engineering](#awesome-graph-engineering)
  - [🎉 News](#-news)
  - [Overview](#overview)
  - [Table of Contents](#table-of-contents)
  - [📚 Related Survey Papers](#-related-survey-papers)
  - [📜 Research Papers](#-research-papers)
    - [Model Intelligence](#model-intelligence)
      - [Pre-Training](#pre-training)
      - [Post-Training](#post-training)
      - [Prompt Engineering](#prompt-engineering)
      - [Context Engineering](#context-engineering)
    - [Individual Intelligence](#individual-intelligence)
      - [Tool Integration](#tool-integration)
      - [Memory Management](#memory-management)
      - [Skill Composition](#skill-composition)
      - [Runtime Orchestration](#runtime-orchestration)
      - [Loop Structure](#loop-structure)
      - [Interaction Protocol](#interaction-protocol)
      - [Environment Feedback](#environment-feedback)
    - [System Intelligence](#system-intelligence)
      - [Task Organization](#task-organization)
      - [Agent Coordination](#agent-coordination)
      - [State Management](#state-management)
      - [System Evolution](#system-evolution)
      - [Ontology Engineering](#ontology-engineering)
  - [🏆 Benchmarks, Datasets, and Environments](#-benchmarks-datasets-and-environments)
    - [Model Intelligence](#model-intelligence-1)
    - [Individual Intelligence](#individual-intelligence-1)
    - [System Intelligence](#system-intelligence-1)
  - [💻 Open-Source Libraries](#-open-source-libraries)
    - [Model Intelligence](#model-intelligence-2)
    - [Individual Intelligence](#individual-intelligence-2)
    - [System Intelligence](#system-intelligence-2)
  - [🚀 Applications](#-applications)
    - [Software Engineering and IT Operations](#software-engineering-and-it-operations)
    - [Scientific Discovery and Laboratory Automation](#scientific-discovery-and-laboratory-automation)
    - [Healthcare and Clinical Decision Support](#healthcare-and-clinical-decision-support)
    - [Enterprise Workflows and Digital Organizations](#enterprise-workflows-and-digital-organizations)
    - [General-Purpose Digital Agents and Personal Automation](#general-purpose-digital-agents-and-personal-automation)
    - [Social and Economic Simulation](#social-and-economic-simulation)
  - [🍀 Citation](#-citation)
  - [Acknowledgments](#acknowledgments)

## 📚 Related Survey Papers

- (arXiv 2024) Graph Retrieval-Augmented Generation: A Survey [[Paper]](https://arxiv.org/abs/2408.08921)
- (arXiv 2026) Agent Harness Engineering: A Survey [[Paper]](https://openreview.net/forum?id=eONq7FdiHa)
- (arXiv 2025) Graphs Meet AI Agents: Taxonomy, Progress, and Future Opportunities [[Paper]](https://arxiv.org/abs/2506.18019)
- (arXiv 2025) Graph-Augmented Large Language Model Agents: Current Progress and Future Prospects [[Paper]](https://arxiv.org/abs/2507.21407)
- (arXiv 2026) Integrating Graphs, Large Language Models, and Agents: Reasoning and Retrieval [[Paper]](https://arxiv.org/abs/2604.15951)
- (arXiv 2024) Understanding the Planning of LLM Agents: A Survey [[Paper]](https://arxiv.org/abs/2402.02716)
- (Paper 2025) A Survey on Agent Workflow—Status and Future [[Paper]](https://arxiv.org/abs/2508.01186)
- (arXiv 2026) From Agent Loops to Structured Graphs: A Scheduler-Theoretic Framework for LLM Agent Execution [[Paper]](https://arxiv.org/abs/2604.11378)
- (Vicinagearth 2024) A Survey on LLM-Based Multi-Agent Systems: Workflow, Infrastructure, and Challenges [[Paper]](https://link.springer.com/article/10.1007/s44336-024-00009-2)
- (Frontiers of Computer Science 2026) Beyond Self-Talk: A Communication-Centric Survey of LLM-Based Multi-Agent Systems [[Paper]](https://arxiv.org/abs/2502.14321)
- (arXiv 2026) Graph-Based Agent Memory: Taxonomy, Techniques, and Applications [[Paper]](https://arxiv.org/abs/2602.05665)
- (TMLR 2026) A Survey of Self-Evolving Agents: What, When, How, and Where to Evolve on the Path to Artificial Super Intelligence [[Paper]](https://arxiv.org/abs/2507.21046)
- (OpenReview Archive 2026) Self-Improving Agents in the Era of Experience: A Survey of Self- to Meta-Evolution [[Paper]](https://openreview.net/forum?id=IUltZSgLMm)
- (arXiv 2025) Multi-Agent Collaboration Mechanisms: A Survey of LLMs [[Paper]](https://arxiv.org/abs/2501.06322)
- (arXiv 2026) Beyond Individual Intelligence: Surveying Collaboration, Failure Attribution, and Self-Evolution in LLM-based Multi-Agent Systems [[Paper]](https://arxiv.org/abs/2605.14892)

## 📜 Research Papers

> Papers are organized according to the taxonomy in the accompanying survey. Venue and year information is derived from the survey bibliography.

### Model Intelligence

#### Pre-Training

- (NeurIPS 2020) **GPT-3** — Language Models are Few-Shot Learners [[Paper]](https://scholar.google.com/scholar?q=Language+Models+are+Few-Shot+Learners)
- (arXiv 2021) **Gopher** — Scaling Language Models: Methods, Analysis & Insights from Training Gopher [[Paper]](https://arxiv.org/abs/2112.11446)
- (JMLR 2023) **PaLM** — PaLM: Scaling Language Modeling with Pathways [[Paper]](https://scholar.google.com/scholar?q=PaLM%3A+Scaling+Language+Modeling+with+Pathways)
- (arXiv 2023) **LLaMA** — LLaMA: Open and Efficient Foundation Language Models [[Paper]](https://arxiv.org/abs/2302.13971)
- (arXiv 2020) **Scaling Laws** — Scaling Laws for Neural Language Models [[Paper]](https://arxiv.org/abs/2001.08361)
- (NeurIPS 2022) **Chinchilla** — Training Compute-Optimal Large Language Models [[Paper]](https://scholar.google.com/scholar?q=Training+Compute-Optimal+Large+Language+Models)
- (JMLR 2022) **Switch Transformer** — Switch Transformers: Scaling to Trillion Parameter Models with Simple and Efficient Sparsity [[Paper]](https://scholar.google.com/scholar?q=Switch+Transformers%3A+Scaling+to+Trillion+Parameter+Models+with+Simple+and+Efficient+Sparsity)
- (arXiv 2024) **Mixtral** — Mixtral of Experts [[Paper]](https://arxiv.org/abs/2401.04088)
- (Paper 2024) **DeepSeekMoE** — DeepSeekMoE: Towards Ultimate Expert Specialization in Mixture-of-Experts Language Models [[Paper]](https://scholar.google.com/scholar?q=DeepSeekMoE%3A+Towards+Ultimate+Expert+Specialization+in+Mixture-of-Experts+Language+Models)
- (arXiv 2024) **Llama 3** — The Llama 3 Herd of Models [[Paper]](https://arxiv.org/abs/2407.21783)
- (arXiv 2024) **DeepSeek-V3** — DeepSeek-V3 Technical Report [[Paper]](https://arxiv.org/abs/2412.19437)
- (Paper 2022) **Deduplication** — Deduplicating Training Data Makes Language Models Better [[Paper]](https://scholar.google.com/scholar?q=Deduplicating+Training+Data+Makes+Language+Models+Better)
- (NeurIPS 2024) **FineWeb** — The FineWeb Datasets: Decanting the Web for the Finest Text Data at Scale [[Paper]](https://scholar.google.com/scholar?q=The+FineWeb+Datasets%3A+Decanting+the+Web+for+the+Finest+Text+Data+at+Scale)
- (NeurIPS 2024) **DataComp-LM** — DataComp-LM: In Search of the Next Generation of Training Sets for Language Models [[Paper]](https://scholar.google.com/scholar?q=DataComp-LM%3A+In+Search+of+the+Next+Generation+of+Training+Sets+for+Language+Models)
- (arXiv 2024) **Qwen2.5** — Qwen2.5 Technical Report [[Paper]](https://arxiv.org/abs/2412.15115)
- (arXiv 2025) **Qwen3** — Qwen3 Technical Report [[Paper]](https://arxiv.org/abs/2505.09388)
- (arXiv 2025) **Kimi K2** — Kimi K2: Open Agentic Intelligence [[Paper]](https://arxiv.org/abs/2507.20534)

#### Post-Training

- (ICLR 2022) **FLAN** — Finetuned Language Models Are Zero-Shot Learners [[Paper]](https://scholar.google.com/scholar?q=Finetuned+Language+Models+Are+Zero-Shot+Learners)
- (ICLR 2022) **T0** — Multitask Prompted Training Enables Zero-Shot Task Generalization [[Paper]](https://scholar.google.com/scholar?q=Multitask+Prompted+Training+Enables+Zero-Shot+Task+Generalization)
- (NeurIPS 2022) **InstructGPT** — Training Language Models to Follow Instructions with Human Feedback [[Paper]](https://scholar.google.com/scholar?q=Training+Language+Models+to+Follow+Instructions+with+Human+Feedback)
- (ICML 2023) **Flan Collection** — The Flan Collection: Designing Data and Methods for Effective Instruction Tuning [[Paper]](https://scholar.google.com/scholar?q=The+Flan+Collection%3A+Designing+Data+and+Methods+for+Effective+Instruction+Tuning)
- (arXiv 2022) **Constitutional AI** — Constitutional AI: Harmlessness from AI Feedback [[Paper]](https://arxiv.org/abs/2212.08073)
- (arXiv 2023) **RLAIF** — RLAIF vs. RLHF: Scaling Reinforcement Learning from Human Feedback with AI Feedback [[Paper]](https://arxiv.org/abs/2309.00267)
- (NeurIPS 2023) **DPO** — Direct Preference Optimization: Your Language Model is Secretly a Reward Model [[Paper]](https://scholar.google.com/scholar?q=Direct+Preference+Optimization%3A+Your+Language+Model+is+Secretly+a+Reward+Model)
- (arXiv 2024) **Tulu 3** — Tulu 3: Pushing Frontiers in Open Language Model Post-Training [[Paper]](https://arxiv.org/abs/2411.15124)
- (arXiv 2024) **DeepSeekMath** — DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open Language Models [[Paper]](https://arxiv.org/abs/2402.03300)
- (Nature 2025) **DeepSeek-R1** — DeepSeek-R1 Incentivizes Reasoning in LLMs through Reinforcement Learning [[Paper]](https://scholar.google.com/scholar?q=DeepSeek-R1+Incentivizes+Reasoning+in+LLMs+through+Reinforcement+Learning)
- (arXiv 2025) **DAPO** — DAPO: An Open-Source LLM Reinforcement Learning System at Scale [[Paper]](https://arxiv.org/abs/2503.14476)
- (ICLR 2025) **WebRL** — WebRL: Training LLM Web Agents via Self-Evolving Online Curriculum Reinforcement Learning [[Paper]](https://scholar.google.com/scholar?q=WebRL%3A+Training+LLM+Web+Agents+via+Self-Evolving+Online+Curriculum+Reinforcement+Learning)
- (arXiv 2025) **Search-R1** — Search-R1: Training LLMs to Reason and Leverage Search Engines with Reinforcement Learning [[Paper]](https://arxiv.org/abs/2503.09516)
- (arXiv 2025) **ReTool** — ReTool: Reinforcement Learning for Strategic Tool Use in LLMs [[Paper]](https://arxiv.org/abs/2504.11536)
- (arXiv 2025) **ToolRL** — ToolRL: Reward is All Tool Learning Needs [[Paper]](https://arxiv.org/abs/2504.13958)
- (arXiv 2025) **RAGEN** — RAGEN: Understanding Self-Evolution in LLM Agents via Multi-Turn Reinforcement Learning [[Paper]](https://arxiv.org/abs/2504.20073)
- (arXiv 2025) **Agent-R1** — Agent-R1: Training Powerful LLM Agents with End-to-End Reinforcement Learning [[Paper]](https://arxiv.org/abs/2511.14460)
- (arXiv 2025) **Agent Lightning** — Agent Lightning: Train ANY AI Agents with Reinforcement Learning [[Paper]](https://arxiv.org/abs/2508.03680)
- (arXiv 2026) **DynaWeb** — DynaWeb: Model-Based Reinforcement Learning of Web Agents [[Paper]](https://arxiv.org/abs/2601.22149)

#### Prompt Engineering

- (arXiv 2021) **Prompt Programming** — Prompt Programming for Large Language Models: Beyond the Few-Shot Paradigm [[Paper]](https://arxiv.org/abs/2102.07350)
- (Paper 2022) **Demonstrations** — Rethinking the Role of Demonstrations: What Makes In-Context Learning Work? [[Paper]](https://scholar.google.com/scholar?q=Rethinking+the+Role+of+Demonstrations%3A+What+Makes+In-Context+Learning+Work%3F)
- (Paper 2022) **In-Context Examples** — What Makes Good In-Context Examples for GPT-3? [[Paper]](https://scholar.google.com/scholar?q=What+Makes+Good+In-Context+Examples+for+GPT-3%3F)
- (NeurIPS 2022) **Chain-of-Thought** — Chain-of-Thought Prompting Elicits Reasoning in Large Language Models [[Paper]](https://scholar.google.com/scholar?q=Chain-of-Thought+Prompting+Elicits+Reasoning+in+Large+Language+Models)
- (ICLR 2023) **Self-Consistency** — Self-Consistency Improves Chain of Thought Reasoning in Language Models [[Paper]](https://scholar.google.com/scholar?q=Self-Consistency+Improves+Chain+of+Thought+Reasoning+in+Language+Models)
- (ICLR 2023) **Least-to-Most** — Least-to-Most Prompting Enables Complex Reasoning in Large Language Models [[Paper]](https://scholar.google.com/scholar?q=Least-to-Most+Prompting+Enables+Complex+Reasoning+in+Large+Language+Models)
- (NeurIPS 2023) **Tree of Thoughts** — Tree of Thoughts: Deliberate Problem Solving with Large Language Models [[Paper]](https://scholar.google.com/scholar?q=Tree+of+Thoughts%3A+Deliberate+Problem+Solving+with+Large+Language+Models)
- (NeurIPS 2023) **Self-Refine** — Self-Refine: Iterative Refinement with Self-Feedback [[Paper]](https://scholar.google.com/scholar?q=Self-Refine%3A+Iterative+Refinement+with+Self-Feedback)
- (AAAI 2024) **Graph of Thoughts** — Graph of Thoughts: Solving Elaborate Problems with Large Language Models [[Paper]](https://scholar.google.com/scholar?q=Graph+of+Thoughts%3A+Solving+Elaborate+Problems+with+Large+Language+Models)
- (Paper 2020) **AutoPrompt** — AutoPrompt: Eliciting Knowledge from Language Models with Automatically Generated Prompts [[Paper]](https://scholar.google.com/scholar?q=AutoPrompt%3A+Eliciting+Knowledge+from+Language+Models+with+Automatically+Generated+Prompts)
- (ICLR 2023) **APE** — Large Language Models Are Human-Level Prompt Engineers [[Paper]](https://scholar.google.com/scholar?q=Large+Language+Models+Are+Human-Level+Prompt+Engineers)
- (ICLR 2024) **OPRO** — Large Language Models as Optimizers [[Paper]](https://scholar.google.com/scholar?q=Large+Language+Models+as+Optimizers)
- (ICLR 2024) **Promptbreeder** — Promptbreeder: Self-Referential Self-Improvement via Prompt Evolution [[Paper]](https://scholar.google.com/scholar?q=Promptbreeder%3A+Self-Referential+Self-Improvement+via+Prompt+Evolution)
- (arXiv 2024) **TextGrad** — TextGrad: Automatic ``Differentiation'' via Text [[Paper]](https://arxiv.org/abs/2406.07496)

#### Context Engineering

- (Paper 2020) **DPR** — Dense Passage Retrieval for Open-Domain Question Answering [[Paper]](https://scholar.google.com/scholar?q=Dense+Passage+Retrieval+for+Open-Domain+Question+Answering)
- (NeurIPS 2020) **RAG** — Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks [[Paper]](https://scholar.google.com/scholar?q=Retrieval-Augmented+Generation+for+Knowledge-Intensive+NLP+Tasks)
- (Paper 2021) **FiD** — Leveraging Passage Retrieval with Generative Models for Open Domain Question Answering [[Paper]](https://scholar.google.com/scholar?q=Leveraging+Passage+Retrieval+with+Generative+Models+for+Open+Domain+Question+Answering)
- (Paper 2023) **HyDE** — Precise Zero-Shot Dense Retrieval without Relevance Labels [[Paper]](https://scholar.google.com/scholar?q=Precise+Zero-Shot+Dense+Retrieval+without+Relevance+Labels)
- (Paper 2023) **IRCoT** — Interleaving Retrieval with Chain-of-Thought Reasoning for Knowledge-Intensive Multi-Step Questions [[Paper]](https://scholar.google.com/scholar?q=Interleaving+Retrieval+with+Chain-of-Thought+Reasoning+for+Knowledge-Intensive+Multi-Step+Questions)
- (ICLR 2024) **Self-RAG** — Self-RAG: Learning to Retrieve, Generate, and Critique through Self-Reflection [[Paper]](https://scholar.google.com/scholar?q=Self-RAG%3A+Learning+to+Retrieve%2C+Generate%2C+and+Critique+through+Self-Reflection)
- (NeurIPS 2025) **CoRAG** — Chain-of-Retrieval Augmented Generation [[Paper]](https://scholar.google.com/scholar?q=Chain-of-Retrieval+Augmented+Generation)
- (NeurIPS 2024) **RankRAG** — RankRAG: Unifying Context Ranking with Retrieval-Augmented Generation in LLMs [[Paper]](https://scholar.google.com/scholar?q=RankRAG%3A+Unifying+Context+Ranking+with+Retrieval-Augmented+Generation+in+LLMs)
- (Paper 2023) **LLMLingua** — LLMLingua: Compressing Prompts for Accelerated Inference of Large Language Models [[Paper]](https://scholar.google.com/scholar?q=LLMLingua%3A+Compressing+Prompts+for+Accelerated+Inference+of+Large+Language+Models)
- (ICLR 2024) **RECOMP** — RECOMP: Improving Retrieval-Augmented LMs with Compression and Selective Augmentation [[Paper]](https://scholar.google.com/scholar?q=RECOMP%3A+Improving+Retrieval-Augmented+LMs+with+Compression+and+Selective+Augmentation)
- (arXiv 2024) **GraphRAG** — From Local to Global: A Graph RAG Approach to Query-Focused Summarization [[Paper]](https://arxiv.org/abs/2404.16130)
- (ICLR 2025) **Provence** — Provence: Efficient and Robust Context Pruning for Retrieval-Augmented Generation [[Paper]](https://scholar.google.com/scholar?q=Provence%3A+Efficient+and+Robust+Context+Pruning+for+Retrieval-Augmented+Generation)
- (Paper 2024) **Lost in the Middle** — Lost in the Middle: How Language Models Use Long Contexts [[Paper]](https://scholar.google.com/scholar?q=Lost+in+the+Middle%3A+How+Language+Models+Use+Long+Contexts)
- (arXiv 2023) **MemGPT** — MemGPT: Towards LLMs as Operating Systems [[Paper]](https://arxiv.org/abs/2310.08560)
- (arXiv 2024) **HiAgent** — HiAgent: Hierarchical Working Memory Management for Solving Long-Horizon Agent Tasks with Large Language Model [[Paper]](https://arxiv.org/abs/2408.09559)
- (ICML 2026) **ACON** — ACON: Optimizing Context Compression for Long-horizon LLM Agents [[Paper]](https://arxiv.org/abs/2510.00615)
- (ICLR 2026) **ACE** — Agentic Context Engineering: Evolving Contexts for Self-Improving Language Models [[Paper]](https://arxiv.org/abs/2510.04618)
- (arXiv 2026) **ContextCurator** — Escaping the Context Bottleneck: Active Context Curation for LLM Agents via Reinforcement Learning [[Paper]](https://arxiv.org/abs/2604.11462)
- (arXiv 2026) **AdaCoM** — Learning Agent-Compatible Context Management for Long-Horizon Tasks [[Paper]](https://arxiv.org/abs/2605.30785)

### Individual Intelligence

#### Tool Integration

- (arXiv 2022) **MRKL** — MRKL Systems: A Modular, Neuro-Symbolic Architecture that Combines Large Language Models, External Knowledge Sources and Discrete Reasoning [[Paper]](https://arxiv.org/abs/2205.00445)
- (arXiv 2022) **TALM** — TALM: Tool Augmented Language Models [[Paper]](https://arxiv.org/abs/2205.12255)
- (ICLR 2023) **ReAct** — ReAct: Synergizing Reasoning and Acting in Language Models [[Paper]](https://openreview.net/forum?id=WE_vluYUL-X)
- (NeurIPS 2023) **Toolformer** — Toolformer: Language Models Can Teach Themselves to Use Tools [[Paper]](https://scholar.google.com/scholar?q=Toolformer%3A+Language+Models+Can+Teach+Themselves+to+Use+Tools)
- (Paper 2023) **API-Bank** — API-Bank: A Comprehensive Benchmark for Tool-Augmented LLMs [[Paper]](https://scholar.google.com/scholar?q=API-Bank%3A+A+Comprehensive+Benchmark+for+Tool-Augmented+LLMs)
- (ICLR 2024) **ToolLLM** — ToolLLM: Facilitating Large Language Models to Master 16000+ Real-world APIs [[Paper]](https://scholar.google.com/scholar?q=ToolLLM%3A+Facilitating+Large+Language+Models+to+Master+16000%2B+Real-world+APIs)
- (NeurIPS 2024) **Gorilla** — Gorilla: Large Language Model Connected with Massive APIs [[Paper]](https://scholar.google.com/scholar?q=Gorilla%3A+Large+Language+Model+Connected+with+Massive+APIs)
- (Anthropic 2024) **MCP** — Introducing the Model Context Protocol [[Paper]](https://scholar.google.com/scholar?q=Introducing+the+Model+Context+Protocol)
- (arXiv 2024) **CodeAct** — Executable Code Actions Elicit Better LLM Agents [[Paper]](https://arxiv.org/abs/2402.01030)
- (arXiv 2024) **SWE-agent** — SWE-agent: Agent-Computer Interfaces Enable Automated Software Engineering [[Paper]](https://arxiv.org/abs/2405.15793)
- (arXiv 2024) **OpenHands** — OpenHands: An Open Platform for AI Software Developers as Generalist Agents [[Paper]](https://arxiv.org/abs/2407.16741)
- (arXiv 2025) **ToolMaker** — LLM Agents Making Agent Tools [[Paper]](https://arxiv.org/abs/2502.11705)
- (OpenAI 2025) **Codex** — Introducing Codex [[Paper]](https://scholar.google.com/scholar?q=Introducing+Codex)
- (Anthropic 2025) **Claude Code** — Claude 3.7 Sonnet and Claude Code [[Paper]](https://scholar.google.com/scholar?q=Claude+3.7+Sonnet+and+Claude+Code)
- (Google 2025) **Gemini CLI** — Gemini CLI: Your Open-Source AI Agent [[Paper]](https://scholar.google.com/scholar?q=Gemini+CLI%3A+Your+Open-Source+AI+Agent)
- (GitHub Blog 2025) **Copilot Coding Agent** — GitHub Copilot: Meet the New Coding Agent [[Paper]](https://scholar.google.com/scholar?q=GitHub+Copilot%3A+Meet+the+New+Coding+Agent)
- (OpenAI Engineering 2026) **Symphony** — An Open-Source Spec for Codex Orchestration: Symphony [[Paper]](https://scholar.google.com/scholar?q=An+Open-Source+Spec+for+Codex+Orchestration%3A+Symphony)

#### Memory Management

- (Paper 2023) **Generative Agents** — Generative Agents: Interactive Simulacra of Human Behavior [[Paper]](https://scholar.google.com/scholar?q=Generative+Agents%3A+Interactive+Simulacra+of+Human+Behavior)
- (AAAI 2024) **MemoryBank** — MemoryBank: Enhancing Large Language Models with Long-Term Memory [[Paper]](https://scholar.google.com/scholar?q=MemoryBank%3A+Enhancing+Large+Language+Models+with+Long-Term+Memory)
- (arXiv 2023) **MemGPT** — MemGPT: Towards LLMs as Operating Systems [[Paper]](https://arxiv.org/abs/2310.08560)
- (arXiv 2025) **A-MEM** — A-MEM: Agentic Memory for LLM Agents [[Paper]](https://arxiv.org/abs/2502.12110)
- (arXiv 2025) **Mem0** — Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory [[Paper]](https://arxiv.org/abs/2504.19413)
- (arXiv 2025) **Zep** — Zep: A Temporal Knowledge Graph Architecture for Agent Memory [[Paper]](https://arxiv.org/abs/2501.13956)
- (arXiv 2025) **MemoryOS** — Memory OS of AI Agent [[Paper]](https://arxiv.org/abs/2506.06326)
- (arXiv 2025) **Memoria** — Memoria: A Scalable Agentic Memory Framework for Personalized Conversational AI [[Paper]](https://arxiv.org/abs/2512.12686)
- (Paper 2026) **AgeMem** — Agentic Memory: Learning Unified Long-Term and Short-Term Memory Management for Large Language Model Agents [[Paper]](https://doi.org/10.18653/v1/2026.acl-long.981)
- (arXiv 2026) **Memori** — Memori: A Persistent Memory Layer for Efficient, Context-Aware LLM Agents [[Paper]](https://arxiv.org/abs/2603.19935)
- (arXiv 2026) **LycheeMemory V2** — LycheeMemory V2: Efficient Long-Term Memory for LLM Agents via Semantic Segment-Level Consolidation [[Paper]](https://arxiv.org/abs/2608.12990)
- (arXiv 2024) **Agent Workflow Memory** — Agent Workflow Memory [[Paper]](https://arxiv.org/abs/2409.07429)

#### Skill Composition

- (arXiv 2023) **Voyager** — Voyager: An Open-Ended Embodied Agent with Large Language Models [[Paper]](https://arxiv.org/abs/2305.16291)
- (ICLR 2024) **CRAFT** — CRAFT: Customizing LLMs by Creating and Retrieving from Specialized Toolsets [[Paper]](https://scholar.google.com/scholar?q=CRAFT%3A+Customizing+LLMs+by+Creating+and+Retrieving+from+Specialized+Toolsets)
- (Anthropic Engineering 2025) **Agent Skills** — Equipping Agents for the Real World with Agent Skills [[Paper]](https://scholar.google.com/scholar?q=Equipping+Agents+for+the+Real+World+with+Agent+Skills)
- (arXiv 2025) **SAGE** — Reinforcement Learning for Self-Improving Agent with Skill Library [[Paper]](https://arxiv.org/abs/2512.17102)
- (arXiv 2026) **HASP** — Harnessing LLM Agents with Skill Programs [[Paper]](https://arxiv.org/abs/2605.17734)
- (arXiv 2026) **SSL Skills** — From Skill Text to Skill Structure: The Scheduling-Structural-Logical Representation for Agent Skills [[Paper]](https://arxiv.org/abs/2604.24026)
- (arXiv 2026) **SkillComposer** — SkillComposer: Learning to Evolve Agent Skills for Specification and Generalization [[Paper]](https://arxiv.org/abs/2606.06079)
- (arXiv 2026) **Generative Skill Composition** — Generative Skill Composition for LLM Agents [[Paper]](https://arxiv.org/abs/2606.32025)
- (arXiv 2026) **Skill-Use** — Skill-Use: Can LLMs Actually Use Skills in Agentic Harnesses? [[Paper]](https://arxiv.org/abs/2608.04828)
- (arXiv 2026) **HDSO** — Hypothesis-Driven Skill Optimization for LLM Agents [[Paper]](https://arxiv.org/abs/2606.22330)
- (arXiv 2026) **Demystifying Agent Skills** — Demystifying Agent Skills: Why They Work—Until They Don't [[Paper]](https://arxiv.org/abs/2608.14036)

#### Runtime Orchestration

- (Anthropic Engineering 2025) **Long-Running Harness** — Effective Harnesses for Long-Running Agents [[Paper]](https://scholar.google.com/scholar?q=Effective+Harnesses+for+Long-Running+Agents)
- (arXiv 2026) **Externalization** — Externalization in LLM Agents: A Unified Review of Memory, Skills, Protocols and Harness Engineering [[Paper]](https://arxiv.org/abs/2604.08224)
- (arXiv 2026) **Harness Engineering** — AI Harness Engineering: A Runtime Substrate for Foundation-Model Software Agents [[Paper]](https://arxiv.org/abs/2605.13357)
- (arXiv 2026) **Code as Agent Harness** — Code as Agent Harness [[Paper]](https://arxiv.org/abs/2605.18747)
- (arXiv 2026) **Harness Configuration** — Configuring Agentic AI Coding Tools: An Exploratory Study [[Paper]](https://arxiv.org/abs/2602.14690)
- (arXiv 2026) **Harness-Bench** — Harness-Bench: Measuring Harness Effects across Models in Realistic Agent Workflows [[Paper]](https://arxiv.org/abs/2605.27922)
- (arXiv 2026) **Prompts to Contracts** — From Prompts to Contracts: Harness Engineering for Auditable Enterprise LLM Agents [[Paper]](https://arxiv.org/abs/2607.08028)
- (arXiv 2024) **ToolSandbox** — ToolSandbox: A Stateful, Conversational, Interactive Evaluation Benchmark for LLM Tool Use Capabilities [[Paper]](https://arxiv.org/abs/2408.04682)
- (arXiv 2023) **ToolEmu** — Identifying the Risks of LM Agents with an LM-Emulated Sandbox [[Paper]](https://arxiv.org/abs/2309.15817)
- (arXiv 2026) **RHO** — Evolving Agents in the Dark: Retrospective Harness Optimization via Self-Preference [[Paper]](https://arxiv.org/abs/2606.05922)
- (arXiv 2025) **CaMeL** — Defeating Prompt Injections by Design [[Paper]](https://arxiv.org/abs/2503.18813)
- (arXiv 2025) **MCP Security Bench** — MCP Security Bench (MSB): Benchmarking Attacks Against Model Context Protocol in LLM Agents [[Paper]](https://arxiv.org/abs/2510.15994)
- (OpenAI Engineering 2026) **OpenAI Harness Engineering** — Harness Engineering: Leveraging Codex in an Agent-First World [[Paper]](https://scholar.google.com/scholar?q=Harness+Engineering%3A+Leveraging+Codex+in+an+Agent-First+World)
- (Anthropic Engineering 2026) **Anthropic Harness Design** — Harness Design for Long-Running Application Development [[Paper]](https://scholar.google.com/scholar?q=Harness+Design+for+Long-Running+Application+Development)
- (arXiv 2026) **Meta-Harness** — Meta-Harness: End-to-End Optimization of Model Harnesses [[Paper]](https://arxiv.org/abs/2603.28052)
- (arXiv 2026) **Agentic Harness** — Agentic Harness Engineering: Observability-Driven Automatic Evolution of Coding-Agent Harnesses [[Paper]](https://arxiv.org/abs/2604.25850)
- (arXiv 2026) **Self-Harness** — Self-Harness: Harnesses That Improve Themselves [[Paper]](https://arxiv.org/abs/2606.09498)
- (arXiv 2026) **HarnessFix** — From Failed Trajectories to Reliable LLM Agents: Diagnosing and Repairing Harness Flaws [[Paper]](https://arxiv.org/abs/2606.06324)
- (arXiv 2026) **HARBOR** — HARBOR: Automated Harness Optimization [[Paper]](https://arxiv.org/abs/2604.20938)
- (arXiv 2024) **AgentDojo** — AgentDojo: A Dynamic Environment to Evaluate Prompt Injection Attacks and Defenses for LLM Agents [[Paper]](https://arxiv.org/abs/2406.13352)
- (arXiv 2026) **Harness Updating** — Harness Updating Is Not Harness Benefit: Disentangling Evolution Capabilities in Self-Evolving LLM Agents [[Paper]](https://arxiv.org/abs/2605.30621)
- (arXiv 2026) **Adaptive Auto-Harness** — Adaptive Auto-Harness: Sustained Self-Improvement for Agentic System Deployment on Open-Ended Task Streams [[Paper]](https://arxiv.org/abs/2606.01770)
- (arXiv 2026) **LongHorizon-Harness** — LongHorizon-Harness: Advancing Long-Horizon Agents for Real-World Tasks [[Paper]](https://arxiv.org/abs/2608.01964)
- (arXiv 2026) **OneDayAgent** — OneDayAgent: Towards a Long-Horizon Harness for Autonomous Agents [[Paper]](https://arxiv.org/abs/2608.05013)
- (arXiv 2026) **Evo-Harness** — Evo-Harness: Context-to-Harness Skill Compilation for Self-Evolving Agents [[Paper]](https://arxiv.org/abs/2608.15071)
- (arXiv 2026) **Harness Handbook** — Harness Handbook: Making Evolving Agent Harnesses Readable, Navigable, and Editable [[Paper]](https://arxiv.org/abs/2607.13285)
- (arXiv 2026) **HarnessOpt-Bench** — HarnessOpt-Bench: Evaluating LLMs at Harness Optimization [[Paper]](https://arxiv.org/abs/2608.06301)
- (arXiv 2026) **The Scaffold Effect** — The Scaffold Effect in Coding Agents: Harness Choice as a Hidden Variable in Coding-Agent Evaluation [[Paper]](https://arxiv.org/abs/2607.22585)
- (arXiv 2026) **Harness-IF** — Harness-IF: Evaluating Instruction Following Across Instruction Surfaces in Coding Agents [[Paper]](https://arxiv.org/abs/2608.11727)
- (arXiv 2026) **Evo-Bench** — Evo-Bench: Can Language Models Improve Agent Harness? [[Paper]](https://arxiv.org/abs/2608.09096)

#### Loop Architecture

- (arXiv 2024) **StateFlow** — StateFlow: Enhancing LLM Task-Solving through State-Driven Workflows [[Paper]](https://arxiv.org/abs/2403.11322)
- (arXiv 2024) **Magentic-One** — Magentic-one: A generalist multi-agent system for solving complex tasks [[Paper]](https://arxiv.org/abs/2411.04468)
- (arXiv 2024) **AIOS** — AIOS: LLM Agent Operating System [[Paper]](https://arxiv.org/abs/2403.16971)
- (arXiv 2024) **AgentBoard** — AgentBoard: An Analytical Evaluation Board of Multi-turn LLM Agents [[Paper]](https://arxiv.org/abs/2401.13178)
- (arXiv 2023) **AdaPlanner** — AdaPlanner: Adaptive Planning from Feedback with Language Models [[Paper]](https://arxiv.org/abs/2305.16653)
- (arXiv 2026) **When Agents Do Not Stop** — When Agents Do Not Stop: Uncovering Infinite Agentic Loops in LLM Agents [[Paper]](https://arxiv.org/abs/2607.01641)
- (arXiv 2026) **Stop Hand-Holding Your Coding Agent** — Stop Hand-Holding Your Coding Agent: Engineering the Loops That Replace Step-by-Step Prompting [[Paper]](https://arxiv.org/abs/2607.00038)
- (arXiv 2026) **ResearchLoop** — ResearchLoop: An Evidence-Gated Control Plane for AI-Assisted Research [[Paper]](https://arxiv.org/abs/2605.28282)
- (arXiv 2026) **Proof-or-Stop** — Proof-or-Stop: Don't Trust the Agent, Trust the Evidence – Loop Engineering for Verifiable Evidence-Gated Lifecycle Control [[Paper]](https://arxiv.org/abs/2607.14890)

#### Interaction Protocol

- (arXiv 2026) **Beyond Message Passing** — Beyond Message Passing: A Semantic View of Agent Communication Protocols [[Paper]](https://arxiv.org/abs/2604.02369)
- (Paper 2025) **Internet of Agents** — Internet of Agents: Fundamentals, Applications, and Challenges [[Paper]](https://arxiv.org/abs/2505.07176)
- (NeurIPS 2025) **LACP** — LLM Agent Communication Protocol (LACP) Requires Urgent Standardization: A Telecom-Inspired Protocol Is Necessary [[Paper]](https://arxiv.org/abs/2510.13821)
- (Paper 2026) **Beyond the Protocol** — Beyond the Protocol: Unveiling Attack Vectors in the Model Context Protocol (MCP) Ecosystem [[Paper]](https://doi.org/10.1109/TSE.2026.3694876)
- (arXiv 2026) **AgentRx** — AgentRx: Diagnosing AI Agent Failures from Execution Trajectories [[Paper]](https://arxiv.org/abs/2602.02475)
- (arXiv 2026) **Supervising Ralph Wiggum** — Supervising Ralph Wiggum: Exploring a Metacognitive Co-Regulation Agentic AI Loop for Engineering Design [[Paper]](https://arxiv.org/abs/2603.24768)
- (ZTE Communications 2025) **From Function Calls to MCPs** — From Function Calls to MCPs for Securing AI Agent Systems: Architecture, Challenges and Countermeasures [[Paper]](https://doi.org/10.12142/ZTECOM.202503004)
- (arXiv 2026) **Sovereign Agentic Loops** — Sovereign Agentic Loops: Decoupling AI Reasoning from Execution in Real-World Systems [[Paper]](https://arxiv.org/abs/2604.22136)
- (arXiv 2026) **The Log is the Agent** — The Log is the Agent: Event-Sourced Reactive Graphs for Auditable, Forkable Agentic Systems [[Paper]](https://arxiv.org/abs/2605.21997)

#### Environment Feedback

- (arXiv 2026) **EEurekAgent** — EurekAgent: Agent Environment Engineering is All You Need for Autonomous Scientific Discovery [[Paper]](https://arxiv.org/abs/2606.13662)
- (arXiv 2023) **LEVER** — LEVER: Learning to Verify Language-to-Code Generation with Execution [[Paper]](https://arxiv.org/abs/2302.08468)
- (arXiv 2023) **CRITIC** — CRITIC: Large Language Models Can Self-Correct with Tool-Interactive Critiquing [[Paper]](https://arxiv.org/abs/2305.11738)
- (arXiv 2024) **Executable Code Actions** — Executable Code Actions Elicit Better LLM Agents [[Paper]](https://arxiv.org/abs/2402.01030)
- (arXiv 2024) **ToolSandbox** — ToolSandbox: A Stateful, Conversational, Interactive Evaluation Benchmark for LLM Tool Use Capabilities [[Paper]](https://arxiv.org/abs/2408.04682)
- (NeurIPS 2024) **OSWorld** — OSWorld: Benchmarking Multimodal Agents for Open-Ended Tasks in Real Computer Environments [[Paper]](https://arxiv.org/abs/2404.07972)
- (arXiv 2026) **DeltaBox** — DeltaBox: Scaling Stateful AI Agents with Millisecond-Level Sandbox Checkpoint/Rollback [[Paper]](https://arxiv.org/abs/2605.22781)

### System Intelligence

#### Task Organization

- (NeurIPS 2023) **HuggingGPT** — HuggingGPT: Solving AI Tasks with ChatGPT and Its Friends in Hugging Face [[Paper]](https://arxiv.org/abs/2303.17580)
- (arXiv 2023) **ReWOO** — ReWOO: Decoupling Reasoning from Observations for Efficient Augmented Language Models [[Paper]](https://arxiv.org/abs/2305.18323)
- (ICML 2024) **LLMCompiler** — An LLM Compiler for Parallel Function Calling [[Paper]](https://arxiv.org/abs/2312.04511)
- (arXiv 2025) **Plan-over-Graph** — Plan-over-Graph: Towards Parallelable LLM Agent Schedule [[Paper]](https://arxiv.org/abs/2502.14563)
- (Neural Networks 2025) **TDAG** — TDAG: A Multi-Agent Framework Based on Dynamic Task Decomposition and Agent Generation [[Paper]](https://arxiv.org/abs/2402.10178)
- (ICLR 2025) **Flow** — Flow: Modularized Agentic Workflow Automation [[Paper]](https://proceedings.iclr.cc/paper_files/paper/2025/hash/ba84da6921f3040b74ee163aa7451f53-Abstract-Conference.html)
- (arXiv 2025) **VFlow** — VFlow: Discovering Optimal Agentic Workflows for Verilog Generation [[Paper]](https://arxiv.org/abs/2504.03723)
- (ICML 2024) **GPTSwarm** — GPTSwarm: Language Agents as Optimizable Graphs [[Paper]](https://proceedings.mlr.press/v235/zhuge24a.html)
- (ICLR 2025) **ADAS** — Automated Design of Agentic Systems [[Paper]](https://arxiv.org/abs/2408.08435)
- (arXiv 2024) **AutoFlow** — AutoFlow: Automated Workflow Generation for Large Language Model Agents [[Paper]](https://arxiv.org/abs/2407.12821)
- (ICLR 2025) **AFlow** — AFlow: Automating Agentic Workflow Generation [[Paper]](https://openreview.net/forum?id=z5uVAKwmjf)
- (arXiv 2025) **A2Flow** — A2Flow: Automating Agentic Workflow Generation via Self-Adaptive Abstraction Operators [[Paper]](https://arxiv.org/abs/2511.20693)
- (arXiv 2025) **MermaidFlow** — MermaidFlow: Redefining Agentic Workflow Generation via Safety-Constrained Evolutionary Programming [[Paper]](https://arxiv.org/abs/2505.22967)
- (Paper 2025) **DynTaskMAS** — Dyntaskmas: A dynamic task graph-driven framework for asynchronous and parallel llm-based multi-agent systems [[Paper]](https://scholar.google.com/scholar?q=Dyntaskmas%3A+A+dynamic+task+graph-driven+framework+for+asynchronous+and+parallel+llm-based+multi-agent+systems)
- (NeurIPS 2025) **DyFlow** — DyFlow: Dynamic Workflow Framework for Agentic Reasoning [[Paper]](https://arxiv.org/abs/2509.26062)
- (arXiv 2025) **EvoFlow** — EvoFlow: Evolving Diverse Agentic Workflows On The Fly [[Paper]](https://arxiv.org/abs/2502.07373)
- (arXiv 2025) **QualityFlow** — QualityFlow: An Agentic Workflow for Program Synthesis Controlled by LLM Quality Checks [[Paper]](https://arxiv.org/abs/2501.17167)
- (arXiv 2026) **FlowSteer** — FlowSteer: Prompt-Only Workflow Steering Exposes Planning-Time Vulnerabilities in Multi-Agent LLM Systems [[Paper]](https://arxiv.org/abs/2605.11514)
- (arXiv 2025) **AgenticLab** — Towards a science of scaling agent systems [[Paper]](https://arxiv.org/abs/2512.08296)
- (arXiv 2025) **ScalingAgent** — Towards a science of scaling agent systems [[Paper]](https://arxiv.org/abs/2512.08296)

#### Agent Coordination

- (COLM 2024) **DyLAN** — A dynamic LLM-powered agent network for task-oriented agent collaboration [[Paper]](https://arxiv.org/abs/2310.02170)
- (ICLR 2025) **Agent-Oriented Planning** — Agent-oriented planning in multi-agent systems [[Paper]](https://arxiv.org/abs/2410.02189)
- (ACL 2025) **MasRouter** — Masrouter: Learning to route llms for multi-agent systems [[Paper]](https://arxiv.org/abs/2502.11133)
- (IJCAI 2024) **AutoAgents** — Autoagents: A framework for automatic agent generation [[Paper]](https://arxiv.org/abs/2309.17288)
- (NAACL 2025) **EvoAgent** — Evoagent: Towards automatic multi-agent generation via evolutionary algorithms [[Paper]](https://arxiv.org/abs/2406.14228)
- (ICLR 2026) **Collaborative Gym** — Collaborative gym: A framework for enabling and evaluating human-agent collaboration [[Paper]](https://arxiv.org/abs/2412.15701)
- (ICML 2026) **AOrchestra** — Aorchestra: Automating sub-agent creation for agentic orchestration [[Paper]](https://arxiv.org/abs/2602.03786)
- (ECAI 2025) **Captain Agent** — Adaptive graph pruning for multi-agent communication [[Paper]](https://arxiv.org/abs/2506.02951)
- (ICML 2026) **MaAS** — Multi-agent architecture search via agentic supernet [[Paper]](https://arxiv.org/abs/2502.04180)
- (arXiv 2026) **SkillGraph** — SkillGraph: Self-Evolving Multi-Agent Collaboration with Multimodal Graph Topology [[Paper]](https://arxiv.org/abs/2604.17503)
- (ICLR 2024) **MetaGPT** — MetaGPT: Meta Programming for A Multi-Agent Collaborative Framework [[Paper]](https://arxiv.org/abs/2308.00352)
- (ACL 2024) **ChatDev** — ChatDev: Communicative Agents for Software Development [[Paper]](https://aclanthology.org/2024.acl-long.810/)
- (arXiv 2024) **Magentic-One** — Magentic-one: A generalist multi-agent system for solving complex tasks [[Paper]](https://arxiv.org/abs/2411.04468)
- (ICLR 2024) **AgentVerse** — Agentverse: Facilitating multi-agent collaboration and exploring emergent behaviors [[Paper]](https://arxiv.org/abs/2308.10848)
- (NeurIPS 2025) **Puppeteer** — Multi-agent collaboration via evolving orchestration [[Paper]](https://arxiv.org/abs/2505.19591)
- (NeurIPS 2025) **AgentNet** — Agentnet: Decentralized evolutionary coordination for llm-based multi-agent systems [[Paper]](https://arxiv.org/abs/2504.00587)
- (ICLR 2025) **MacNet** — Scaling large language model-based multi-agent collaboration [[Paper]](https://arxiv.org/abs/2406.07155)
- (EMNLP 2025) **SwarmAgentic** — Swarmagentic: Towards fully automated agentic system generation via swarm intelligence [[Paper]](https://arxiv.org/abs/2506.15672)
- (ICLR 2025) **Mixture-of-Agents** — Mixture-of-agents enhances large language model capabilities [[Paper]](https://arxiv.org/abs/2406.04692)
- (ICML 2025) **G-Designer** — G-designer: Architecting multi-agent communication topologies via graph neural networks [[Paper]](https://arxiv.org/abs/2410.11782)
- (EMNLP-2025) **AMAS** — Amas: Adaptively determining communication topology for llm-based multi-agent system [[Paper]](https://arxiv.org/abs/2510.01617)
- (ICLR 2025) **AgentPrune** — Cut the crap: An economical communication pipeline for llm-based multi-agent systems [[Paper]](https://arxiv.org/abs/2410.02506)
- (ACL 2025) **AgentDropout** — Agentdropout: Dynamic agent elimination for token-efficient and high-performance llm-based multi-agent collaboration [[Paper]](https://arxiv.org/abs/2503.18891)
- (arXiv 2026) **DyTopo** — Dytopo: Dynamic topology routing for multi-agent reasoning via semantic matching [[Paper]](https://arxiv.org/abs/2602.06039)
- (AAAI 2026) **Adaptive Theory of Mind** — Adaptive theory of mind for LLM-based multi-agent coordination [[Paper]](https://arxiv.org/abs/2603.16264)
- (AAAI 2026) **Assemble Your Crew** — Assemble your crew: Automatic multi-agent communication topology design via autoregressive graph generation [[Paper]](https://arxiv.org/abs/2507.18224)
- (AAAI 2026) **Learning to Generate and Extract** — Learning to Generate and Extract: A Multi-Agent Collaboration Framework For Zero-shot Document-level Event Arguments Extraction [[Paper]](https://arxiv.org/abs/2603.02909)
- (arXiv 2026) **Agent-World** — Agent-world: Scaling real-world environment synthesis for evolving general agent intelligence [[Paper]](https://arxiv.org/abs/2604.18292)
- (ICLR 2026) **Graph-of-Agents** — Graph-of-agents: A graph-based framework for multi-agent LLM collaboration [[Paper]](https://arxiv.org/abs/2604.17148)
- (ICLR 2026) **Emergent Coordination** — Emergent coordination in multi-agent language models [[Paper]](https://arxiv.org/abs/2510.05174)
- (ICLR 2026) **AgentPO** — AgentPO: Enhancing Multi-Agent Collaboration via Reinforcement Learning [[Paper]](https://openreview.net/forum?id=5L8uyzjn2l)
- (ICLR 2026) **Multi-Agent Design** — Multi-agent design: Optimizing agents with better prompts and topologies [[Paper]](https://arxiv.org/abs/2502.02533)
- (IEEE Network 2026) **Agent Discovery** — Agent Discovery in Internet of Agents: Challenges and Solutions [[Paper]](https://arxiv.org/abs/2511.19113)
- (SIGIR 2026) **LLM Agents Factory** — LLM Agents Factory: Retrieval of Domain-Specific LLM Agents [[Paper]](https://arxiv.org/abs/2608.09934)
- (arXiv 2026) **TacoMAS** — TacoMAS: Test-Time Co-Evolution of Topology and Capability in LLM-based Multi-Agent Systems [[Paper]](https://arxiv.org/abs/2605.09539)
- (arXiv 2026) **EvolveRouter** — Evolverouter: Co-evolving routing and prompt for multi-agent question answering [[Paper]](https://arxiv.org/abs/2604.05149)
- (arXiv 2026) **MoRSE** — MoRSE: Task-Oriented Multi-Agent System with Mixture of Role-Subtask Experts [[Paper]](https://arxiv.org/abs/2608.09251)
- (ICLR 2025) **Internet of Agents** — Internet of agents: Weaving a web of heterogeneous agents for collaborative intelligence [[Paper]](https://arxiv.org/abs/2407.07061)
- (arXiv 2026) **Organizational Science of Multi-Agent LLM Systems** — Toward an Organizational Science of Multi-Agent LLM Systems: Decoupling Who, How, and Which Algorithm [[Paper]](https://arxiv.org/abs/2607.25446)
- (arXiv 2026) **Multi-Agent Teams Hold Experts Back** — Multi-agent teams hold experts back [[Paper]](https://arxiv.org/abs/2602.01011)
- (arXiv 2026) **Dynamic Role Assignment** — Dynamic role assignment for multi-agent debate [[Paper]](https://arxiv.org/abs/2601.17152)
- (NAACL 2025) **WorkTeam** — WorkTeam: Constructing Workflows from Natural Language with Multi-Agents [[Paper]](https://aclanthology.org/2025.naacl-industry.3/)
- (arXiv 2026) **Meta-Team** — Evolve as a Team: Collaborative Self-Evolution for LLM-based Multi-Agent Systems [[Paper]](https://arxiv.org/abs/2605.29790)
- (arXiv 2026) **WebSwarm** — WebSwarm: Recursive Multi-Agent Orchestration for Deep-and-Wide Web Search [[Paper]](https://arxiv.org/abs/2607.08662)
- (arXiv 2025) **OWL** — Owl: Optimized workforce learning for general multi-agent assistance in real-world task automation [[Paper]](https://arxiv.org/abs/2505.23885)
- (ICLR 2025) **AgentSquare** — Agentsquare: Automatic llm agent search in modular design space [[Paper]](https://arxiv.org/abs/2410.06153)
- (arXiv 2026) **MAS-on-the-Fly** — MAS-on-the-Fly: Dynamic Adaptation of LLM-based Multi-Agent Systems at Test Time [[Paper]](https://arxiv.org/abs/2602.13671)
- (arXiv 2026) **Self-Organizing Agents** — Drop the Hierarchy and Roles: How Self-Organizing LLM Agents Outperform Designed Structures [[Paper]](https://arxiv.org/abs/2603.28990)
- (arXiv 2026) **Swarm Skills** — Swarm Skills: A Portable, Self-Evolving Multi-Agent System Specification for Coordination Engineering [[Paper]](https://arxiv.org/abs/2605.10052)
- (arXiv 2025) **ATLAS** — Atlas: Adaptive trading with llm agents through dynamic prompt optimization and multi-agent coordination [[Paper]](https://arxiv.org/abs/2510.15949)
- (EMNLP 2025) **MAgICoRe** — Magicore: Multi-agent, iterative, coarse-to-fine refinement for reasoning [[Paper]](https://aclanthology.org/2025.emnlp-main.1660/)
- (EMNLP 2025) **Information Propagation Effects** — Understanding the information propagation effects of communication topologies in llm-based multi-agent systems [[Paper]](https://aclanthology.org/2025.emnlp-main.623/)
- (arXiv 2026) **CARD** — CARD: Towards Conditional Design of Multi-agent Topological Structures [[Paper]](https://arxiv.org/abs/2603.01089)
- (arXiv 2026) **QueenBee Planner** — QueenBee Planner: Skill-Evolving Communication Topologies for Token-Efficient LLM Multi-Agent Systems [[Paper]](https://arxiv.org/abs/2606.27492)
- (arXiv 2026) **Agentic Aggregation** — Agentic aggregation for parallel scaling of long-horizon agentic tasks [[Paper]](https://arxiv.org/abs/2604.11753)

#### State Management

- (arXiv 2024) **StateFlow** — StateFlow: Enhancing LLM Task-Solving through State-Driven Workflows [[Paper]](https://arxiv.org/abs/2403.11322)
- (arXiv 2024) **AutoGRAMS** — AutoGRAMS: Autonomous Graphical Agent Modeling Software [[Paper]](https://arxiv.org/abs/2407.10049)
- (arXiv 2024) **Magentic-One** — Magentic-one: A generalist multi-agent system for solving complex tasks [[Paper]](https://arxiv.org/abs/2411.04468)
- (arXiv 2026) **Graph of States** — Graph of States: Solving Abductive Tasks with Large Language Models [[Paper]](https://arxiv.org/abs/2603.21250)
- (Paper 2026) **LangGraph** — LangGraph: Low-Level Orchestration for Stateful Agents [[Paper]](https://github.com/langchain-ai/langgraph)
- (Paper 2026) **Burr** — Apache Burr: Stateful Application and Agent Framework [[Paper]](https://github.com/apache/burr)
- (arXiv 2025) **Aegis** — Aegis: Taxonomy and Optimizations for Overcoming Agent-Environment Failures in LLM Agents [[Paper]](https://arxiv.org/abs/2508.19504)
- (Paper 2026) **LlamaIndex Workflows** — LlamaIndex Workflows: Event-Driven Agent Workflows [[Paper]](https://github.com/run-llama/workflows-py)
- (Paper 2026) **Pydantic AI** — Pydantic AI: Typed Agent Framework and Graph Runtime [[Paper]](https://github.com/pydantic/pydantic-ai)
- (arXiv 2023) **AutoGen** — AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation [[Paper]](https://arxiv.org/abs/2308.08155)
- (arXiv 2026) **Sovereign Agentic Loops** — Sovereign Agentic Loops: Decoupling AI Reasoning from Execution in Real-World Systems [[Paper]](https://arxiv.org/abs/2604.22136)
- (arXiv 2023) **LATS** — Language Agent Tree Search Unifies Reasoning, Acting, and Planning in Language Models [[Paper]](https://arxiv.org/abs/2310.04406)
- (arXiv 2026) **PatchBoard** — PatchBoard: Schema-Grounded State Mutation for Reliable and Auditable LLM Multi-Agent Collaboration [[Paper]](https://arxiv.org/abs/2605.29313)
- (arXiv 2026) **MemTX** — MemTX: Transactional Belief Commit for Stateful Agent Memory [[Paper]](https://arxiv.org/abs/2607.23929)
- (arXiv 2026) **Cordon** — Cordon: Semantic Transactions for Tool-Using LLM Agents [[Paper]](https://arxiv.org/abs/2606.17573)
- (arXiv 2026) **Atomix** — Atomix: Timely, transactional tool use for reliable agentic workflows [[Paper]](https://arxiv.org/abs/2602.14849)
- (arXiv 2025) **SagaLLM** — SagaLLM: Context Management, Validation, and Transaction Guarantees for Multi-Agent LLM Planning [[Paper]](https://arxiv.org/abs/2503.11951)
- (arXiv 2025) **ALAS** — Alas: Transactional and dynamic multi-agent llm planning [[Paper]](https://arxiv.org/abs/2511.03094)
- (CAIS 2026) **RAC** — Robust Agent Compensation (RAC): Teaching AI Agents to Compensate [[Paper]](https://dl.acm.org/doi/full/10.1145/3786335.3813141)
- (arXiv 2026) **ProPlay** — ProPlay: Procedural World Models for Self-Evolving LLM Agents [[Paper]](https://arxiv.org/abs/2606.12780)
- (arXiv 2026) **DART** — DART: Semantic Recoverability for Structured Tool Agents [[Paper]](https://arxiv.org/abs/2605.23311)
- (arXiv 2025) **AgentGit** — AgentGit: A version control framework for reliable and scalable LLM-powered multi-agent systems [[Paper]](https://arxiv.org/abs/2511.00628)
- (arXiv 2026) **Shepherd** — Shepherd: Enabling Programmable Meta-Agents via Reversible Agentic Execution Traces [[Paper]](https://arxiv.org/abs/2605.10913)
- (arXiv 2026) **The Log is the Agent** — The Log is the Agent: Event-Sourced Reactive Graphs for Auditable, Forkable Agentic Systems [[Paper]](https://arxiv.org/abs/2605.21997)
- (arXiv 2026) **Concurrency Anomaly Prevention** — Verified Detection and Prevention of Concurrency Anomalies in Multi-Agent Large Language Model Systems [[Paper]](https://arxiv.org/abs/2606.17182)
- (arXiv 2026) **CausalFlow** — CausalFlow: Causal Attribution and Counterfactual Repair for LLM Agent Failures [[Paper]](https://arxiv.org/abs/2605.25338)
- (arXiv 2025) **ReflexGrad** — ReflexGrad: Within-Episode Failure Recovery in LLM Agents via Progress-Gated Dual-Process Routing [[Paper]](https://arxiv.org/abs/2511.14584)
- (arXiv 2026) **TDAD** — TDAD: Test-Driven Agentic Development - Reducing Code Regressions in AI Coding Agents via Graph-Based Impact Analysis [[Paper]](https://arxiv.org/abs/2603.17973)
- (arXiv 2025) **Who & When** — Which Agent Causes Task Failures and When? On Automated Failure Attribution of LLM Multi-Agent Systems [[Paper]](https://arxiv.org/abs/2505.00212)
- (NeurIPS 2025) **MAST** — Why Do Multi-Agent LLM Systems Fail? [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2025/hash/b1041e52d3be19f0a9bc491657488e4a-Abstract-Datasets_and_Benchmarks_Track.html)
- (arXiv 2026) **Living-Harness** — Living-Harness Is an Interactive-Agent Evolver [[Paper]](https://arxiv.org/abs/2607.26598)
- (arXiv 2026) **APEX** — APEX: Autonomous Policy Exploration for Self-Evolving LLM Agents [[Paper]](https://arxiv.org/abs/2605.21240)

#### System Evolution

- (arXiv 2026) **QueenBee Planner** — QueenBee Planner: Skill-Evolving Communication Topologies for Token-Efficient LLM Multi-Agent Systems [[Paper]](https://arxiv.org/abs/2606.27492)
- (ACL 2026) **ReCreate** — Recreate: Reasoning and creating domain agents driven by experience [[Paper]](https://aclanthology.org/2026.acl-long.1432/)
- (arXiv 2026) **SkillGraph** — SkillGraph: Self-Evolving Multi-Agent Collaboration with Multimodal Graph Topology [[Paper]](https://arxiv.org/abs/2604.17503)
- (arXiv 2026) **Swarm Skills** — Swarm Skills: A Portable, Self-Evolving Multi-Agent System Specification for Coordination Engineering [[Paper]](https://arxiv.org/abs/2605.10052)
- (arXiv 2026) **MemTX** — MemTX: Transactional Belief Commit for Stateful Agent Memory [[Paper]](https://arxiv.org/abs/2607.23929)
- (arXiv 2026) **The Log is the Agent** — The Log is the Agent: Event-Sourced Reactive Graphs for Auditable, Forkable Agentic Systems [[Paper]](https://arxiv.org/abs/2605.21997)
- (Neural Networks 2025) **TDAG** — TDAG: A Multi-Agent Framework Based on Dynamic Task Decomposition and Agent Generation [[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S0893608025000796)
- (ICLR 2025) **Flow** — Flow: Modularized Agentic Workflow Automation [[Paper]](https://proceedings.iclr.cc/paper_files/paper/2025/hash/ba84da6921f3040b74ee163aa7451f53-Abstract-Conference.html)
- (ICAPS 2025) **DynTaskMAS** — Dyntaskmas: A dynamic task graph-driven framework for asynchronous and parallel llm-based multi-agent systems [[Paper]](https://scholar.google.com/scholar?q=Dyntaskmas%3A+A+dynamic+task+graph-driven+framework+for+asynchronous+and+parallel+llm-based+multi-agent+systems)
- (NeurIPS 2025) **DyFlow** — DyFlow: Dynamic Workflow Framework for Agentic Reasoning [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2025/hash/fe9910d2b03324faeb5371a9658277bb-Abstract-Conference.html)
- (arXiv 2025) **EvoFlow** — EvoFlow: Evolving Diverse Agentic Workflows On The Fly [[Paper]](https://arxiv.org/abs/2502.07373)
- (arXiv 2025) **QualityFlow** — QualityFlow: An Agentic Workflow for Program Synthesis Controlled by LLM Quality Checks [[Paper]](https://arxiv.org/abs/2501.17167)
- (arXiv 2026) **FlowSteer** — FlowSteer: Prompt-Only Workflow Steering Exposes Planning-Time Vulnerabilities in Multi-Agent LLM Systems [[Paper]](https://arxiv.org/abs/2605.11514)
- (EMNLP 2025) **SwarmAgentic** — Swarmagentic: Towards fully automated agentic system generation via swarm intelligence [[Paper]](https://aclanthology.org/2025.emnlp-main.93/)
- (NeurIPS 2026) **AgentNet** — Agentnet: Decentralized evolutionary coordination for llm-based multi-agent systems [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2025/hash/9a379c1b05793d1c42dc832269834515-Abstract-Conference.html)
- (arXiv 2026) **Self-Organizing Agents** — Drop the Hierarchy and Roles: How Self-Organizing LLM Agents Outperform Designed Structures [[Paper]](https://arxiv.org/abs/2603.28990)
- (arXiv 2026) **Meta-Team** — Evolve as a Team: Collaborative Self-Evolution for LLM-based Multi-Agent Systems [[Paper]](https://arxiv.org/abs/2605.29790)
- (arXiv 2026) **DyTopo** — Dytopo: Dynamic topology routing for multi-agent reasoning via semantic matching [[Paper]](https://arxiv.org/abs/2602.06039)
- (arXiv 2026) **CARD** — CARD: Towards Conditional Design of Multi-agent Topological Structures [[Paper]](https://arxiv.org/abs/2603.01089)

#### Ontology Engineering

- (arXiv 2026) **OntoExtend** — OntoExtend: A Framework for Requirement-driven and Scalable Ontology Extension with LLMs [[Paper]](https://arxiv.org/abs/2607.17963)
- (Knowledge acquisition 1993) **OntoSpecification** — A translation approach to portable ontology specifications [[Paper]](https://scholar.google.com/scholar?q=A+translation+approach+to+portable+ontology+specifications)
- (Paper 2025) **iCARE** — iCARE: Ontology-Guided Intent Routing for Multi-Agent LLM-Based Dialogue Systems [[Paper]](https://scholar.google.com/scholar?q=iCARE%3A+Ontology-Guided+Intent+Routing+for+Multi-Agent+LLM-Based+Dialogue+Systems)
- (arXiv 2026) **OG-MAR** — Toward Culturally Aligned LLMs through Ontology-Guided Multi-Agent Reasoning [[Paper]](https://arxiv.org/abs/2601.21700)
- (Paper 2026) **CAPAS** — Agentic Information Architectures for Global Climate Governance: A Multi-Agent Decision-Support System for Cross-National Policy Analytics [[Paper]](https://scholar.google.com/scholar?q=Agentic+Information+Architectures+for+Global+Climate+Governance%3A+A+Multi-Agent+Decision-Support+System+for+Cross-National+Policy+Analytics)
- (Procedia CIRP 2026) **LaMAS4PD** — LaMAS4PD-A Multi-Agent LLM Approach for Ontology-Driven Structuring of Engineering Knowledge in Industry 4.0 [[Paper]](https://scholar.google.com/scholar?q=LaMAS4PD-A+Multi-Agent+LLM+Approach+for+Ontology-Driven+Structuring+of+Engineering+Knowledge+in+Industry+4.0)
- (Available at SSRN 6919461 2026) **Agentology** — Agentology: Ontology-Driven Operational Environments for Multi-Agent Systems [[Paper]](https://scholar.google.com/scholar?q=Agentology%3A+Ontology-Driven+Operational+Environments+for+Multi-Agent+Systems)
- (npj Health Systems 2026) **OntoCodex** — OntoCodex: a multi-agent biomedical ontology enrichment framework [[Paper]](https://scholar.google.com/scholar?q=OntoCodex%3A+a+multi-agent+biomedical+ontology+enrichment+framework)
- (European Semantic Web Conference 2026) **AgentO** — AgentO: An Ontology for Modeling Agentic AI Systems [[Paper]](https://scholar.google.com/scholar?q=AgentO%3A+An+Ontology+for+Modeling+Agentic+AI+Systems)
- (arXiv 2026) **Ontology-to-Tools** — Ontology-to-tools compilation for executable semantic constraint enforcement in LLM agents [[Paper]](https://arxiv.org/abs/2602.03439)
- (Semantic Web 2026) **Ontology SLR** — Large language models for ontology engineering: a systematic literature review [[Paper]](https://scholar.google.com/scholar?q=Large+language+models+for+ontology+engineering%3A+a+systematic+literature+review)
- (arXiv 2026) **Palantir Ontology** — The Ontology System [[Paper]](https://www.palantir.com/docs/foundry/architecture-center/ontology-system)

## 🏆 Benchmarks, Datasets, and Environments

Representative evaluation resources from the survey:

### Model Intelligence

- [MMLU/MMLU-Pro](https://arxiv.org/abs/2406.01574)
- [GPQA](https://arxiv.org/abs/2311.12022)
- [NPPC](https://arxiv.org/abs/2504.11239)
- [OlymMATH](https://aclanthology.org/2026.acl-long.792/)
- [IFEval](https://arxiv.org/abs/2311.07911)
- [EvolIF](https://aclanthology.org/2026.acl-long.433/)
- [HumanEval/EvalPlus](https://arxiv.org/abs/2305.01210)
- [MMMU](https://openaccess.thecvf.com/content/CVPR2024/html/Yue_MMMU_A_Massive_Multi-discipline_Multimodal_Understanding_and_Reasoning_Benchmark_for_CVPR_2024_paper.html)
- [OMHBench](https://aclanthology.org/2026.findings-acl.911/)
- [LiveBench](https://arxiv.org/abs/2406.19314)
- [GraphRAG-Bench](https://proceedings.iclr.cc/paper_files/paper/2026/hash/6c9e01d6cefbbf4cdd265032550e767f-Abstract-Conference.html)

### Individual Intelligence

- [AgentBench](https://arxiv.org/abs/2308.03688)
- [GAIA](https://arxiv.org/abs/2311.12983)
- [AgencyBench](https://aclanthology.org/2026.acl-long.337/)
- [WebArena](https://arxiv.org/abs/2307.13854)
- [OSWorld](https://arxiv.org/abs/2404.07972)
- [SWE-bench](https://arxiv.org/abs/2310.06770)
- [AppWorld](https://appworld.dev/)
- [$$-bench](https://arxiv.org/abs/2406.12045)
- [ToolSandbox](https://github.com/apple/ToolSandbox)
- [AgentDojo](https://github.com/ethz-spylab/agentdojo)
- [Harness-Bench](https://arxiv.org/abs/2605.27922)
- [Skill-Use](https://arxiv.org/abs/2608.04828)
- [LongMemEval](https://arxiv.org/abs/2410.10813)
- [MemoryAgentBench](https://github.com/HUST-AI-HYZ/MemoryAgentBench)
- [MemoryArena](https://arxiv.org/abs/2602.16313)
- [GateMem](https://rzhub.github.io/GateMem/project.html)
- [MemSyco-Bench](https://arxiv.org/abs/2607.01071)
- [Mem2ActBench](https://github.com/Cantaloupe-M/Mem2ActBench)
- [LongDS-Bench](https://arxiv.org/abs/2605.30434)
- [EvoMemBench](https://github.com/DSAIL-Memory/EvoMemBench)
- [Trainee-Bench](https://arxiv.org/abs/2601.08173)
- [SEA-Eval](https://arxiv.org/abs/2604.08988)
- [Evo-Bench](https://arxiv.org/abs/2608.09096)
- [OpenClawBench](https://arxiv.org/abs/2605.29253)
- [BenchTrace](https://arxiv.org/abs/2605.29225)
- [TheAgentCompany](https://arxiv.org/abs/2412.14161)

### System Intelligence

- [TaskBench](https://arxiv.org/abs/2311.18760)
- [WorFBench](https://arxiv.org/abs/2410.07869)
- [FlowBench](https://aclanthology.org/2024.findings-emnlp.638/)
- [ComfyBench](https://openaccess.thecvf.com/content/CVPR2025/html/Xue_ComfyBench_Benchmarking_LLM-based_Agents_in_ComfyUI_for_Autonomously_Designing_Collaborative_CVPR_2025_paper.html)
- [TPS-Bench](https://aclanthology.org/2026.acl-long.1614/)
- [JourneyBench](https://aclanthology.org/2026.eacl-industry.15/)
- [ETOM](https://aclanthology.org/2026.findings-eacl.75/)
- [LLM-Coordination](https://aclanthology.org/2025.findings-naacl.448/)
- [VillagerBench](https://aclanthology.org/2024.findings-acl.964/)
- [MultiAgentBench](https://aclanthology.org/2025.acl-long.421/)
- [AgentsNet](https://arxiv.org/abs/2507.08616)
- [DBS](https://ojs.aaai.org/index.php/AAAI/article/view/39812)
- [SILO-BENCH](https://aclanthology.org/2026.acl-long.1354/)
- [CoLLAB](https://openreview.net/forum?id=372FjQy1cF)
- [Collab-Overcooked](https://aclanthology.org/2025.emnlp-main.249/)
- [MAS-BENCH](https://aclanthology.org/2026.findings-acl.1698/)
- [DPBench](https://github.com/najmulhasan-code/dpbench)
- [CalBench](https://arxiv.org/abs/2605.09823)
- [TAMAS](https://aclanthology.org/2026.acl-long.1442/)
- [SyncBench](https://proceedings.mlr.press/v267/guo25l.html)
- [MAST](https://arxiv.org/abs/2503.13657)
- [TraceElephant](https://aclanthology.org/2026.acl-long.912/)
- [MP-Bench](https://arxiv.org/abs/2603.25001)
- [R2Act](https://arxiv.org/abs/2607.04623)
- [MAFBench](https://arxiv.org/abs/2602.03128)
- [MASEval](https://aclanthology.org/2026.acl-demo.34/)
- [MAS-PromptBench](https://arxiv.org/abs/2606.23664)
- [BenchAgent](https://arxiv.org/abs/2606.05670)

## 💻 Open-Source Libraries

Reusable projects grouped by their primary engineering target:

### Model Intelligence

- [Transformers](https://github.com/huggingface/transformers)
- [Megatron Core](https://github.com/NVIDIA/Megatron-LM)
- [LLaMA-Factory](https://github.com/hiyouga/LlamaFactory)
- [verl](https://github.com/verl-project/verl)
- [slime](https://github.com/THUDM/slime)
- [vLLM](https://github.com/vllm-project/vllm)
- [SGLang](https://github.com/sgl-project/sglang)

### Individual Intelligence

- [LangChain](https://github.com/langchain-ai/langchain)
- [OpenAI Agents SDK](https://github.com/openai/openai-agents-python)
- [Claude Agent SDK](https://github.com/anthropics/claude-agent-sdk-python)
- [Pydantic AI](https://github.com/pydantic/pydantic-ai)
- [LlamaIndex Workflows](https://github.com/run-llama/workflows-py)
- [Haystack](https://github.com/deepset-ai/haystack)
- [Apache Burr](https://github.com/apache/burr)
- [Letta Agent SDK](https://github.com/letta-ai/letta-agent-sdk)
- [Graphiti](https://github.com/getzep/graphiti)
- [MCP Python SDK](https://github.com/modelcontextprotocol/python-sdk)
- [Langflow](https://github.com/langflow-ai/langflow)
- [Dify](https://github.com/langgenius/dify)

### System Intelligence

- [LangGraph](https://github.com/langchain-ai/langgraph)
- [Microsoft Agent Framework](https://github.com/microsoft/agent-framework)
- [Google ADK](https://github.com/google/adk-python)
- [AutoGen/GraphFlow](https://github.com/microsoft/autogen)
- [AG2](https://github.com/ag2ai/ag2)
- [CrewAI](https://github.com/crewAIInc/crewAI)
- [CAMEL](https://github.com/camel-ai/camel)
- [Mastra](https://github.com/mastra-ai/mastra)
- [GPTSwarm](https://github.com/metauto-ai/GPTSwarm)

## 🚀 Applications

Representative systems and application domains covered by the survey:

### Software Engineering and IT Operations

- [MetaGPT](https://proceedings.iclr.cc/paper_files/paper/2024/hash/6507b115562bb0a305f1958ccc87355a-Abstract-Conference.html)
- [SWE-agent](https://proceedings.neurips.cc/paper_files/paper/2024/hash/5a7c947568c1b1328ccc5230172e1e7c-Abstract-Conference.html)
- [OpenHands](https://openreview.net/forum?id=OJd3ayDDoF)
- [Codex](https://openai.com/index/introducing-the-codex-app/)
- [Claude Code](https://www.anthropic.com/product/claude-code)
- [OpenCode](https://opencode.ai/docs/agents/)
- [Cline](https://docs.cline.bot/sdk/guides/multi-agent-teams)
- [Project ALICE](https://research.ibm.com/blog/project-alice-software-bugs-agents)

### Scientific Discovery and Laboratory Automation

- [SciAgents](https://doi.org/10.1002/adma.202413523)
- [The AI Scientist](https://github.com/SakanaAI/AI-Scientist)
- [Virtual Lab](https://doi.org/10.1038/s41586-025-09442-9)
- [Co-Scientist](https://doi.org/10.1038/s41586-026-10644-y)
- [Robin](https://doi.org/10.1038/s41586-026-10652-y)

### Healthcare and Clinical Decision Support

- [DeepRare](https://doi.org/10.1038/s41586-025-10097-9)
- [AMIE](https://doi.org/10.1038/s41586-026-10764-5)
- [CARE-AD](https://doi.org/10.1038/s41746-025-01940-4)
- [MAP](https://doi.org/10.1038/s44401-026-00085-0)

### Enterprise Workflows and Digital Organizations

- [WorkTeam](https://aclanthology.org/2025.naacl-industry.3/)
- [SOAN](https://arxiv.org/abs/2508.13732)
- [FinRobot-ERP](https://arxiv.org/abs/2506.01423)
- [Agent-Ops](https://aclanthology.org/2026.acl-industry.29/)
- [Gemini Enterprise Agentic RAG](https://research.google/blog/unlocking-dependable-responses-with-gemini-enterprise-agent-platforms-agentic-rag/)

### General-Purpose Digital Agents and Personal Automation

- [OpenClaw](https://github.com/openclaw/openclaw)
- [Hermes Agent](https://github.com/NousResearch/hermes-agent)

### Social and Economic Simulation

- [AgentSociety](https://aclanthology.org/2025.acl-industry.94/)
- [EconAgent](https://aclanthology.org/2024.acl-long.829/)
- [SRAP-Agent](https://aclanthology.org/2024.findings-emnlp.15/)
- [TwinMarket](https://proceedings.neurips.cc/paper_files/paper/2025/hash/5bf234ecf83cd77bc5b77a24ba9338b0-Abstract-Conference.html)

## 🍀 Citation

If you find this repository useful, please cite the accompanying survey:

```bibtex
@article{graphengineering2026,
  title   = {Graph Engineering in the Era of LLM Agents: From Individual Intelligence to System Intelligence},
  author  = {Anonymous Authors},
  journal = {arXiv preprint},
  year    = {2026}
}
```

> The citation metadata will be updated when the public arXiv record is available.

## Acknowledgments

This list is maintained by the authors and community contributors. We thank the authors of all referenced works and open-source projects.
