<h1 align="center">Jiyu Li</h1>

<p align="center"><b>OT × Cloud-Native × AI Agentic Systems</b><br/>
Industrial automation engineer turned software engineer — I build the layer where physical assets meet agents.</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.11-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/FastAPI-services-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Spring%20Boot-microservices-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/Docker-containers-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/TypeScript-strict-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/IEC%2061131--3-ST%20%7C%20LD-0A66C2?style=flat-square" alt="IEC 61131-3" />
  <img src="https://img.shields.io/badge/PLCopen-TC6%20XML-0A66C2?style=flat-square" alt="PLCopen" />
</p>

---

> **Seven years of industrial automation** — PLC and HMI engineering, LV/MV/HV drive commissioning up to 6 MW across chemical, port and heavy-manufacturing sites.
>
> **Cloud-native software engineering in Ireland** — MSc Software Design with Cloud Native Computing (TUS Athlone): polyglot microservices, API gateway and payments, containerised multi-cloud deployment.
>
> **AI agent tooling** — LLM pipelines with retrieval and structured contracts, and compilers from natural language to validated IEC 61131-3.
>
> *Measure first, then act; verify closed-loop, ship no untested assumption.* 

## Architecture & Agentic Systems

### AutoPLC-Agent — [repository](https://github.com/JreeyL/AutoPLC-Agent) · MIT

Natural-language control requirements in, validated IEC 61131-3 Structured Text / Ladder Diagram drafts out.

`requirements (NL) → SystemRequirement JSON → Gherkin features → PLC_AST → ST/LD generators → PLCopen TC6 XML → gates`

Three generation strategies (deterministic, LLM-direct, hybrid) behind a two-tier validation framework: Tier-1 deterministic schema and grounding checks, Tier-2 semantic review, then MATIEC `iec2c` compilation and OpenPLC v3 runtime simulation. Retrieval over a Siemens manual with LlamaIndex and LangChain; local-LLM backend supported. 363 tests.

### Eattoday-Architecture-Spec — [repository](https://github.com/JreeyL/Eattoday-Architecture-Spec)

Public specification, private source. Architecture for an AI-first community and commerce platform: polyglot microservices (Python/FastAPI, Spring Boot, Node), API gateway with edge security, Stripe payments, asynchronous messaging, multi-cloud container deployment (AWS EC2, Cloud Run, Vercel). Live product: [eattoday.net](https://www.eattoday.net)

### Twin OS — spec-first deterministic agent framework

Specified before implemented: a frozen capability matrix as the single fact source, deterministic gates, bounded repair loops and fail-closed pipelines. The framework specification is public; no personal data is exposed.

## Research

Edge monocular depth estimation — CNN (MiDaS) and transformer (Depth Anything) compared under deployment constraints, ONNX-optimised, 19.4 FPS on edge-class hardware. TUS MSc research, with a [live demo](https://depthnav-research.onrender.com/index.html).

## Tech Stack

| Industrial OT | Backend & Cloud | AI & Data |
| --- | --- | --- |
| Siemens TIA Portal (S7-1500, LAD/ST) | Python · FastAPI · Pydantic | LLM agent pipelines · RAG |
| HMI / SCADA design | Spring Boot · Spring Cloud · Node | LangChain · LlamaIndex |
| LV / MV / HV VFD and servo commissioning | Next.js · TypeScript · React | PyTorch · ONNX · edge inference |
| ATEX control panels · safety interlocks | Docker · Compose · Kubernetes | Weaviate · PostgreSQL · Redis · MySQL |
| IEC 61131-3 · PLCopen TC6 XML | GitHub Actions · Jenkins · Cloud Run · Vercel | OpenCV video analysis |

## Links

<p align="center">
  <a href="https://jiyu-automation-portfolio.vercel.app/">Portfolio</a> ·
  <a href="https://linkedin.com/in/jiyu-li-software">LinkedIn</a> ·
  <a href="https://github.com/JreeyL/AutoPLC-Agent">AutoPLC-Agent</a> ·
  <a href="mailto:jreeylee92@outlook.com">jreeylee92@outlook.com</a>
</p>
