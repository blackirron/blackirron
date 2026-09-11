<div align="center">

<h1>Samir Pravin Nimgade</h1>

<p><em>Sophomore @ IIT (ISM) Dhanbad · building ML, systems, and products</em></p>

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=15&pause=1000&color=9745F5&center=true&width=600&lines=B.Tech+%40+Mechanical+Department,+IIT+ISM+Dhanbad;Building+ML%2C+systems%2C+and+products;PM+Club+%C2%B7+WorldQuant+BRAIN+%C2%B7+competitive+programming;Ship+first%2C+refine+after.)

[![GitHub](https://img.shields.io/badge/GitHub-blackirron-181717?style=flat-square&logo=github)](https://github.com/blackirron)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Samir%20Pravin%20Nimgade-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/samir-pravin)

</div>

---

## 👋 About

I'm a second-year B.Tech student in Mechanical Engineering at IIT (ISM) Dhanbad, but most of my work happens outside formal coursework. I taught myself ML/DL and systems programming by building complete things end to end, from a U-Net trained on satellite radar data to a container runtime built from raw namespaces and cgroups, then breaking them, figuring out why, and rebuilding properly.

I run models locally (Ollama, RAG pipelines with FAISS and LangChain) and wire up hosted model APIs for production use. Outside of code, I'm active in product management through IIT ISM's PM Club and in quant research through WorldQuant BRAIN.

My interests currently sit around:

- Machine learning and NLP
- LLMs, RAG, and intelligent agents
- Systems programming and Linux internals
- Robotics and human-robot interaction
- AI applied to physical and engineering systems
- Building and shipping useful products

I'm particularly interested in the space between intelligent software and physical systems, where models reason, retrieve, understand language, and ultimately interact with real engineering systems.

## 🎓 Certifications & Coursework

<div align="center">

| Certification / Course | Provider | Coverage |
|:---|:---:|:---|
| **CS50x: Introduction to Computer Science** | Harvard (edX) | Full course |
| **Machine Learning Specialization** | DeepLearning.AI | Full specialization |
| **Deep Learning Specialization** | DeepLearning.AI | Course 1 · Course 2 · Course 4 |
| **CS224N: NLP with Deep Learning** | Stanford (self-study) | Full Course |

</div>

## 🚀 Selected Work

### Lunar Ice Detection
[Repository](https://github.com/blackirron/Lunar-ice-detection-on-the-subsurfaces-of-south-pole-craters)

A U-Net based computer vision pipeline detecting subsurface ice in lunar south-polar craters, built for the Bharatiya Antariksh Hackathon using real Chandrayaan-2 DFSAR radar data. The most important part wasn't the score. An apparently strong IoU (~0.90) turned out to be misleading because the evaluation labels were algebraically derived from the input features. I traced the problem to its root, separated the circular evaluation from the real model assessment, and documented what the radar product could and couldn't rigorously support, turning a near-zero genuine ice signal into a legitimate scientific finding rather than a failed model.

**Focus:** PyTorch · U-Net · ResNet-34 · SAR/DFSAR · remote sensing · scientific ML

### Minimal Container Runtime
[Repository](https://github.com/blackirron/Minimal-container-runtime)

A Linux container runtime built from the underlying primitives instead of Docker: namespaces, `unshare(2)`, cgroup v2, OverlayFS, `pivot_root(2)`, veth pairs, Linux bridges, and NAT/iptables. An attempt to understand containers by reconstructing the important pieces rather than just learning Docker commands.

**Focus:** Python · Linux internals · namespaces · cgroups · networking · filesystems

### Local LLM / RAG Stack
[Shipping log](https://blackirron.github.io/shipped-products/)

Local LLM workflows built around Ollama, FAISS, and LangChain, including retrieval-augmented generation and a ReAct-style agent. Focused on the engineering around language models (documents, retrieval, context, reasoning, response) rather than treating an LLM as a black-box API.

**Focus:** Ollama · LLMs · RAG · FAISS · LangChain · agents

### PM Network
[Repository](https://github.com/blackirron/product-hub)

A full pnpm monorepo built around the idea of a "GitHub for Product Managers": Express API, React frontend, Postgres + Drizzle, OpenAPI-driven codegen.

**Focus:** TypeScript · Express · PostgreSQL · Drizzle · React

### IsThisAI
[Repository](https://github.com/blackirron/isThisAI-non-KISS)

An LLM-based application that assesses whether text appears AI-generated or human-written, with a FastAPI backend, provider-switchable LLM integration, structured JSON parsing, real authentication, a Pro tier, and a server-side-verified Razorpay payment flow (not just a client callback). A deliberate part of the project is acknowledging its limitation: LLM-based AI detection is probabilistic, not forensic proof.

**Focus:** FastAPI · SQLAlchemy · LLM vision · authentication · payments · deployment

### Hindi Sentence Completion (CS224N)
[Repository](https://github.com/blackirron/Hindi-Sentence-Completer-CS224N-project)

An NLP project built while working through Stanford's CS224N material, exploring sentence completion and the practical challenges of applying language-modeling ideas to Hindi. Used to move past NLP libraries and understand the modeling pipeline directly.

**Focus:** NLP · language modeling · Hindi · PyTorch

### Sentence Parser
[Repository](https://github.com/blackirron/Sentence-Parser-NLP)

Dependency and constituency parsing, dependency visualization, and a small transition-based parser (SHIFT / LEFT-ARC / RIGHT-ARC) built alongside pretrained NLP tooling to understand how syntactic structure is represented and constructed.

**Focus:** NLP · syntax · parsing · spaCy · Benepar

### AI × Robotics

An ongoing interest: using language or multimodal models for high-level task specification and human-robot interaction, while leaving motion planning, force control, compliance, and safety-critical execution to the underlying robotic system. LLMs as a layer on top of conventional robot control, not a replacement for it.

## 🧱 Product & Systems Building

Alongside research-oriented work, I like taking ideas from a rough concept to something people can actually use.

- **PM Network** (above): full-stack "GitHub for PMs" platform
- **GoodAI / Lumen**: experiments in making AI systems useful as actual products rather than model demos
- **Shipped Products**: a running [shipping log](https://blackirron.github.io/shipped-products/) of smaller products and experiments across AI applications, productivity tools, and consumer software

I keep this separate from research work because shipping a product and doing research are different skills, and I value both.

## 🗺️ Technical Interests

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
    ├── Human-Robot Interaction
    ├── Industrial Systems
    └── Scientific ML
```

<div align="">

**Also into:**  Product Management (PM Club, IIT ISM) and Competitive Programming

</div>

## 🛠️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-004482?style=for-the-badge&logo=cplusplus&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

</div>

