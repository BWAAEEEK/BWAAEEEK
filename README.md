# JooHo Lee

AI engineer and researcher working on LLM systems, agent architecture, reasoning structures, and workflow optimization.

I focus on systems where model capability is only one part of the problem. The harder work is often in defining the task clearly, designing the right system boundary, evaluating behavior under realistic conditions, and making failures visible enough to improve.

My work sits between research prototypes and production-minded engineering: turning uncertain model behavior into workflows that can be inspected, measured, corrected, and maintained.

## What I Work On

- LLM systems that require reliability, observability, and clear evaluation criteria
- Agent architectures with explicit state, tool use, failure handling, and feedback loops
- Reasoning structures for decomposition, verification, planning, and recovery
- Workflow optimization where AI supports decision-making without hiding uncertainty
- Evaluation pipelines that test behavior beyond ideal examples
- Research-to-implementation loops that preserve both experimental flexibility and engineering discipline

## How I Think

I prefer to start with the shape of the problem rather than the choice of model.

Before optimizing a system, I try to understand what must be true for it to be trusted: what the system is allowed to assume, where it can fail, how those failures are detected, and what evidence would show that the design is improving.

I care about implementation, but I care just as much about the reason behind an implementation. A design that works once is not enough; it should be possible to explain, evaluate, debug, and extend it without relying on intuition alone.

## Current Interests

- Reasoning design for multi-step LLM workflows
- Agent planning and execution loops
- Tool-use reliability and recovery strategies
- Evaluation design for reasoning-heavy systems
- Context, memory, and retrieval architectures
- Human-in-the-loop workflows
- System-level reliability for LLM applications
- Long-lived architecture for AI systems

## Selected Repositories

- [`Transformer-Implementation-Pytorch`](https://github.com/BWAAEEEK/Transformer-Implementation-Pytorch): educational PyTorch implementation of the Transformer architecture
- [`BERT_pytorch`](https://github.com/BWAAEEEK/BERT_pytorch): minimal PyTorch implementation and experiments with BERT-style language modeling
- [`NeuroMarketing-with-GNN`](https://github.com/BWAAEEEK/NeuroMarketing-with-GNN): graph neural network experiments for neuromarketing and behavior prediction
- [`Neural_Collaborative_Filtering`](https://github.com/BWAAEEEK/Neural_Collaborative_Filtering): PyTorch implementation of neural collaborative filtering for recommendation tasks
- [`FontRecSys`](https://github.com/BWAAEEEK/FontRecSys): font recommendation experiments using machine learning and representation learning
- [`Blog_post_embedding`](https://github.com/BWAAEEEK/Blog_post_embedding): data collection and semantic embedding experiments for blog post representation

## Selected Principles

- Measure behavior before trusting capability.
- Treat prompts, tools, memory, and orchestration as system components.
- Prefer explicit assumptions over hidden heuristics.
- Design evaluation loops before scaling a workflow.
- Make failures legible enough to debug.
- Optimize for correctness, maintainability, and evidence, not only speed.
- Keep architectures simple until complexity is justified.
- Build systems that can improve through inspection and iteration.

## Contact

- GitHub: [@BWAAEEEK](https://github.com/BWAAEEEK)
