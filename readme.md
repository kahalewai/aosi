<div align="center">

# AOSI Reference Model for Artificial Intelligence

Welcome to the **AOSI** (AI Open Systems Interconnection) Reference Landing

![aosi2](https://github.com/user-attachments/assets/2910ea5d-e638-4354-b1d8-aa0712565ef4)

</div>


## Intro

AOSI (AI Open Systems Interconnection) is inspired by the same principles that drove the OSI (Open Systems Interconnection) reference model for Network Infrastructure. The artificial intelligence landscape is evolving rapidly; AI, LLMs, and autonomous agents are growing in complexity, with multiple layers of computation, data processing, orchestration, and interaction. Along with this comes a range of ambiguous terminology. The industry lacks a shared, commonly agreed upon technical reference model to describe these systems from the ground up. That’s where AOSI comes in.

AOSI provides a 7-layer technical reference model for AI systems, starting from the infrastructure that powers AI all the way to the applications that deliver intelligence to humans or other systems. Each layer has a clear technical responsibility, making it easy to analyze, design, and discuss AI systems.

The goal of AOSI is simple: create a common vocabulary, common terminology, and functional roadmap for AI systems, so that developers, researchers, and organizations can communicate more clearly, design more reliably, and innovate faster; just like OSI did for networking.



<br>

## AOSI Model

AOSI provides a **layered reference model for AI, LLMs, and autonomous agents**, describing the **technical functions required for AI systems to operate reliably, interoperably, and end-to-end**. Each layer provides services to the layer above, forming a **progressive stack from infrastructure to application**.

For a detailed breakdown of the 7-layer AOSI model, including technical responsibilities and how each layer builds upon the next, see the full reference document here: [aosi_model.md](./aosi_model.md)

<br>


| Layer | Name           | Function                       | Provides to Layer Above                            |
| ----- | -------------- | ------------------------------ | -------------------------------------------------- |
| 1     | Infrastructure | Runtime environment            | Stable, reproducible compute for models            |
| 2     | Model          | Core intelligence              | Predictive outputs for data and agents             |
| 3     | Data           | Input/output and training data | Clean, validated data for agents and communication |
| 4     | Orchestration  | Autonomous agent control       | Safe, coordinated agent behavior                   |
| 5     | Communication  | Messaging & protocols          | Reliable interaction for interfaces                |
| 6     | Interface      | Human/system interaction       | Mechanisms for applications to consume AI          |
| 7     | Application    | End-user AI functionality      | Actionable intelligence and services               |

<br>

This reference model is **implementation-agnostic**, applicable to LLMs, multi-agent systems, federated AI, or hybrid architectures. Security, reliability, and safety are **cross-cutting considerations applied per layer**.

<br>

## Contribute

AOSI is a **working-draft**; we believe the best standards are built **collaboratively**. This reference model is intended as a **shared artifact for the entire AI industry**, where researchers, developers, and vendors can **work together to define, refine, and evolve the reference model**.

We invite **all AI vendors, AI tool developers, and AI organizations** to participate in shaping AOSI. The idea is to create a **working group-style collaboration** directly on GitHub, where:

* Each organization or vendor can become a **contributor**.
* Updates and improvements are submitted via **Pull Requests (PRs)**.
* Discussions, reviews, and proposals are **transparent and open to the community**.
* Changes are tracked using **versioning and clear documentation**, ensuring the reference model evolves safely and consistently.

**Why contribute?**

* Influence a **shared industry reference** for AI technical systems.
* Help create a **common vocabulary** for AI architecture, orchestration, and deployment.
* Enable **better interoperability, collaboration, and understanding** across vendors and projects.
* Be part of a **living, evolving standard** that grows with AI technology.

**How to get started:**

1. Fork the repository.
2. Review the current AOSI layers and documentation.
3. Open a PR to suggest edits, additions, or clarifications.
4. Participate in discussions to refine the model collaboratively.

<br>

By working together, we can ensure AOSI becomes a **practical, widely-adopted reference** that benefits the whole AI community.

