<div align="center">

# Samir Pravin Nimgade

### Mechanical Engineering @ IIT (ISM) Dhanbad · ML/AI · Systems · Robotics

Building intelligent systems at the intersection of **engineering, machine learning,
and software** — from NLP and local LLMs to computer vision for lunar radar data
and Linux systems built from first principles.

<br>

[![GitHub](https://img.shields.io/badge/GitHub-blackirron-181717?style=flat-square&logo=github)](https://github.com/blackirron)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Samir%20Pravin%20Nimgade-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/)

</div>

---

## About

I'm a second-year B.Tech. student in **Mechanical Engineering at IIT (ISM) Dhanbad**,
but much of my work happens outside the boundaries of my formal coursework.

I started exploring machine learning and software independently and gradually moved
from small experiments to building complete systems — learning by implementing,
breaking things, investigating why they broke, and rebuilding them properly.

My interests currently sit around:

- **Machine Learning & NLP**
- **LLMs, RAG and intelligent agents**
- **Systems programming and Linux internals**
- **Robotics and human–robot interaction**
- **AI applied to physical and engineering systems**
- **Building and shipping useful products**

I'm particularly interested in the space between **intelligent software and physical
systems** — how models can reason, retrieve information, understand language, and
ultimately interact with real engineering systems.

---

## Selected Work

###  Lunar Ice Detection

**Detecting and characterizing subsurface ice in lunar south-polar craters using
Chandrayaan-2 DFSAR radar data.**

[Repository](https://github.com/blackirron/Lunar-ice-detection-on-the-subsurfaces-of-south-pole-craters)

A U-Net based computer-vision pipeline developed for the **Bharatiya Antariksh
Hackathon** using real Chandrayaan-2 radar data.

The most important part of the project wasn't getting a high score.

During evaluation, I found that an apparently strong IoU (~0.90) was misleading because
the evaluation labels were algebraically derived from input features. I traced the
problem to its root cause, separated the circular evaluation from the actual model
assessment, and documented what the supplied radar product could and could not
rigorously support.

The project became as much about **scientific validation and avoiding misleading
results** as it was about training a neural network.

**Focus:** PyTorch · U-Net · ResNet-34 · SAR/DFSAR · Remote Sensing · Scientific ML

---

###  Minimal Container Runtime

**A Linux container runtime built from the underlying primitives rather than Docker.**

[Repository](https://github.com/blackirron/Minimal-container-runtime)

A from-scratch educational container runtime written in Python that explores how
Linux containers actually work underneath the abstractions.

Implemented using:

- Linux namespaces
- `unshare(2)`
- cgroup v2
- OverlayFS
- `pivot_root(2)`
- virtual Ethernet pairs
- Linux bridges
- NAT / iptables
- isolated filesystems and processes

The project was an attempt to understand containers by reconstructing the important
pieces myself rather than simply learning Docker commands.

**Focus:** Python · Linux internals · namespaces · cgroups · networking · filesystems

---

###  Local LLM / RAG Stack

**Exploring what useful AI systems look like when the model runs locally.**

I have built local LLM workflows around **Ollama, FAISS and LangChain**, including
retrieval-augmented generation and a ReAct-style agent.

The work focuses on the engineering around language models:

`documents → retrieval → context → reasoning → response`

rather than treating an LLM as a black-box API.

**Focus:** Ollama · LLMs · RAG · FAISS · LangChain · agents

---

###  Hindi Sentence Completion — CS224N

**A hands-on NLP project exploring language modelling for Hindi.**

[Repository](https://github.com/blackirron/Hindi-Sentence-Completer-CS224N-project)

An NLP project developed while working through Stanford's **CS224N** material,
focused on sentence completion and the practical challenges involved in applying
language-modeling ideas to Hindi.

I used the project to move beyond simply using NLP libraries and understand the
modelling pipeline more deeply.

**Focus:** NLP · language modelling · Hindi · PyTorch · CS224N

---

###  Sentence Parser

**Exploring the structure of language through dependency and constituency parsing.**

[Repository](https://github.com/blackirron/Sentence-Parser-NLP)

A hands-on NLP project covering:

- Dependency parsing
- Constituency parsing
- Dependency visualization
- Transition-based parsing
- SHIFT / LEFT-ARC / RIGHT-ARC operations

The repository combines pretrained NLP tooling with a small transition-based parser
implementation to understand how syntactic structures can be represented and
constructed.

**Focus:** NLP · syntax · parsing · spaCy · Benepar

---

###  AI × Robotics

I'm increasingly interested in the interface between **language models and physical
systems**.

One direction I'm exploring is using language or multimodal models for **high-level
task specification and human–robot interaction**, while leaving motion planning,
force control, compliance, and safety-critical execution to the underlying robotic
system.

This is an area I am currently exploring through my engineering background and work
in AI, rather than treating LLMs as a replacement for conventional robot control.

---

###  IsThisAI

**A deployed LLM-based application for examining AI-generated text.**

[Repository](https://github.com/blackirron/isThisAI-non-KISS)

IsThisAI takes text and uses an LLM to produce a structured assessment of whether the
writing appears AI-generated or human-written.

The application includes a FastAPI backend, provider-switchable LLM integration,
structured JSON parsing, authentication and a payment flow.

A deliberate part of the project is acknowledging its limitation: **LLM-based
AI detection is probabilistic and should not be treated as forensic proof.**

**Focus:** FastAPI · LLM APIs · SQLAlchemy · authentication · deployment

---

## Product & Systems Building

Alongside research-oriented projects, I enjoy taking ideas all the way from a rough
concept to something people can actually use.

Some of my larger product/system work includes:

### PM Network

[Repository](https://github.com/blackirron/product-hub)

A full-stack platform built around the idea of a **"GitHub for Product Managers."**

**TypeScript · React · Express · PostgreSQL · Drizzle · OpenAPI**

###  GoodAI

Experiments around making AI systems more useful as actual products rather than
just model demos.

### Shipped Products

[View the shipping log](https://blackirron.github.io/shipped-products/)

A collection of smaller products and experiments that I have built and shipped,
covering AI applications, productivity tools, consumer software and other ideas.

I keep this separate from my research work because **shipping a product and doing
research are different skills**, and I value both.


---

## Technical Interests

```text
Machine Learning
├── NLP
│   ├── Language Models
│   ├── Multilingual NLP
│   ├── Parsing
│   └── Retrieval
│
├── LLM Systems
│   ├── RAG
│   ├── Agents
│   └── Local Inference
│
├── Systems
│   ├── Linux
│   ├── Containers
│   ├── Networking
│   └── Operating-System Primitives
│
└── Engineering AI
    ├── Robotics
    ├── Human–Robot Interaction
    ├── Industrial Systems
    └── Scientific ML
