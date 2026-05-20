# Teacher Feedback Agent

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

An AI-powered, multi-agent pedagogical evaluation system that simulates diverse student personas to provide structured, evidence-based feedback on teaching quality. 

Unlike traditional transcription summarizers, this agent evaluates the teaching experience from the perspective of different learner profiles (e.g., ESL students, low-attention students, high performers) and provides actionable pedagogical feedback grounded in established learning science frameworks.

## 🎯 Core Objectives

The system evaluates raw transcripts, audio, video, or lesson plans to answer critical pedagogical questions:
- Would a real student understand this lesson?
- Which parts were confusing and where would students lose attention?
- Which concepts lacked scaffolding or assumed prior knowledge?
- Was cognitive load too high or pacing too fast?
- Were misconceptions predicted and addressed?

## 🏗 Architecture

This project is designed as a **Multi-Agent System** consisting of three distinct clusters, built to run independently or compose together as skills:

1. **Ingest Agent Cluster:** Normalizes multi-modal inputs (YouTube, audio, PDF, live stream) into structured `LessonContent`.
2. **Evaluation Agent Cluster (LangGraph):** Orchestrates parallel simulated student personas, detects conceptual scaffolding, and applies pedagogical rubrics to generate a `TeacherReport`.
3. **Coach Agent Cluster:** A stateful, long-lived dialogue agent that tracks teacher improvement goals across longitudinal sessions.

> **Read the full architecture design:** [Multi-Agent Architecture Documentation](./docs/architecture/multi_agent_architecture.md)

## 📚 Documentation & Research

Our evaluation rubrics are rigorously grounded in cognitive science and learning theory. 

- [Implementation Plan](./docs/architecture/implementation_plan.md)
- [ClassMind Paper Analysis (MIT 2025)](./docs/research/classmind_paper_analysis.md)
- [Pedagogical Practices & Learning Science Reference](./docs/research/pedagogical_practices_reference.md)

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details on how to get started, set up your environment, and submit pull requests.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
