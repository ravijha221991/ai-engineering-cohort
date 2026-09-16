# AI Engineering Cohort

A hands-on journey to learn modern AI Engineering from first principles by building real applications using open-source tools.

## Why This Repository Exists

As a backend engineer, I want to learn AI Engineering the same way I learned distributed systems: by understanding fundamentals, building projects, evaluating trade-offs, and gradually moving toward production-grade systems.

This repository documents that journey from LLM fundamentals to production-ready AI applications.

---

# Learning Principles

- Learn concepts before frameworks
- Understand why a solution exists before using it
- Build everything locally whenever possible
- Prefer open-source tools over paid services
- Document learnings publicly
- Focus on engineering depth rather than tutorial completion

---

# Technology Stack

### Models

- Ollama
- Qwen
- Llama
- Gemma

### AI Frameworks

- LangChain
- LangGraph

### Vector Databases

- ChromaDB
- Qdrant

### Evaluation

- DeepEval
- RAGAS

### Observability

- Langfuse
- OpenTelemetry

### Backend & Infrastructure

- FastAPI
- Docker
- PostgreSQL
- Redis

---

# 12-Week Roadmap

## Week 0 - AI Foundations

### Goal

Build intuition about how LLMs actually work.

### Topics

- What is an LLM?
- Tokens
- Context Windows
- Temperature
- Embeddings
- Vector Search
- Hallucinations
- Why RAG Exists

### Deliverables

- AI Fundamentals Notes
- Architecture Diagrams
- Mental Models

### Milestone

✅ Explain how ChatGPT-style systems work without using LangChain.

---

## Week 1 - Local LLMs & Prompting

### Goal

Build a local ChatGPT-style application.

### Topics

- Ollama
- Chat Models
- Prompt Templates
- Structured Prompts
- Output Parsing

### Project

Local Chat Assistant

### Milestone

✅ First AI application running locally.

---

## Week 2 - LangChain & LCEL

### Goal

Understand how LangChain composes AI workflows.

### Topics

- LangChain Fundamentals
- Runnables
- LCEL
- invoke()
- batch()
- stream()

### Project

Code Explainer Assistant

### Milestone

✅ Build and understand your first LangChain pipeline.

---

## Week 3 - RAG Fundamentals

### Goal

Understand how AI systems learn from your own data.

### Topics

- Document Loaders
- Text Splitters
- Embeddings
- ChromaDB
- Retrieval

### Project

Chat with PDF

### Milestone

✅ Build your first Retrieval-Augmented Generation system.

---

## Week 4 - Advanced Retrieval

### Goal

Improve retrieval quality.

### Topics

- Similarity Search
- MMR
- Multi Query Retrieval
- Hybrid Search
- Parent Documents
- Context Compression

### Project

Knowledge Assistant

### Milestone

✅ Understand why advanced retrieval techniques exist and when to use them.

---

## Week 5 - Evaluation

### Goal

Learn how AI systems are tested.

### Topics

- Relevance
- Faithfulness
- Context Relevance
- Retrieval Metrics
- DeepEval
- RAGAS

### Project

AI Evaluation Framework

### Milestone

✅ Build automated tests for AI applications.

---

## Week 6 - Memory

### Goal

Build conversational systems that remember.

### Topics

- Conversation History
- Session Memory
- Long-Term Memory
- Memory Optimization

### Project

Personal AI Assistant

### Milestone

✅ Build an assistant that remembers previous conversations.

---

## Week 7 - Tools

### Goal

Allow AI systems to interact with the outside world.

### Topics

- Custom Tools
- File Tools
- Search Tools
- API Integrations
- Structured Tool Calling

### Project

Developer Assistant

### Milestone

✅ Build an AI that can perform actions instead of only generating text.

---

## Week 8 - Agents

### Goal

Understand autonomous decision-making.

### Topics

- ReAct Pattern
- Agent Executors
- Tool Selection
- Planning
- Reasoning

### Project

Research Agent

### Milestone

✅ Build an AI agent that decides what actions to take.

---

## Week 9 - LangGraph

### Goal

Build stateful and controllable AI workflows.

### Topics

- State
- Nodes
- Edges
- Conditional Routing
- Checkpoints
- Human-in-the-Loop

### Project

Multi-Step Agent Workflow

### Milestone

✅ Build a stateful AI workflow using LangGraph.

---

## Week 10 - APIs & Serving

### Goal

Expose AI applications through APIs.

### Topics

- FastAPI
- LangServe
- Streaming APIs
- Authentication
- Rate Limiting

### Project

AI Backend Service

### Milestone

✅ Serve AI applications through production-style APIs.

---

## Week 11 - Observability

### Goal

Understand what happens inside AI systems.

### Topics

- Langfuse
- Tracing
- Monitoring
- Prompt Tracking
- Error Analysis
- OpenTelemetry

### Project

Observable AI System

### Milestone

✅ Trace and debug AI applications like production systems.

---

## Week 12 - Production AI

### Goal

Bring everything together.

### Topics

- Docker
- Redis
- PostgreSQL
- Qdrant
- Caching
- Security
- Cost Optimization
- Production Patterns

### Project

Production-Ready AI Application

### Milestone

✅ Build and deploy a complete AI system locally.

---

# Final Outcomes

By the end of this cohort, I should be able to:

- Explain modern AI systems from first principles
- Build RAG applications
- Evaluate AI systems
- Build tool-enabled agents
- Design LangGraph workflows
- Serve AI applications through APIs
- Observe and debug AI systems
- Build production-ready AI applications

---

# Repository Structure

```text
ai-engineering-cohort/

docs/
├── week-00
├── week-01
├── week-02
├── week-03
├── week-04
├── week-05
├── week-06
├── week-07
├── week-08
├── week-09
├── week-10
├── week-11
└── week-12

notes/

projects/
├── local-chat
├── code-explainer
├── pdf-chat
├── knowledge-assistant
├── evaluation
├── memory-assistant
├── developer-assistant
├── research-agent
├── langgraph-workflow
└── production-app

assets/

README.md
```

---

# Progress

| Week | Topic | Status |
|--------|--------|--------|
| 0 | Foundations | ⬜ |
| 1 | Local LLMs & Prompting | ⬜ |
| 2 | LangChain & LCEL | ⬜ |
| 3 | RAG Fundamentals | ⬜ |
| 4 | Advanced Retrieval | ⬜ |
| 5 | Evaluation | ⬜ |
| 6 | Memory | ⬜ |
| 7 | Tools | ⬜ |
| 8 | Agents | ⬜ |
| 9 | LangGraph | ⬜ |
| 10 | APIs & Serving | ⬜ |
| 11 | Observability | ⬜ |
| 12 | Production AI | ⬜ |

---

> Learn deeply. Build consistently. Document everything. Think like an AI Engineer.
One change I'd make before we start
Add a "Weekly Output Checklist" section:
## Weekly Output Checklist

Every week must produce:

- Notes
- Architecture Diagram
- Working Code
- README Update
- Lessons Learned
- Git Commit History
