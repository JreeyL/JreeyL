<p align="center">
  <img src="[https://capsule-render.vercel.app/api?type=waving&color=0:1b2a47,100:2b6cb0&height=180&section=header&text=Jiyu%20Li&fontSize=42&fontColor=ffffff&desc=OT%20%C3%97%20Cloud%20%C3%97%20AI&descAlignY=65&descSize=18](https://capsule-render.vercel.app/api?type=waving&color=0:1b2a47,100:2b6cb0&height=180&section=header&text=Jiyu%20Li&fontSize=42&fontColor=ffffff&desc=OT%20%C3%97%20Cloud%20%C3%97%20AI&descAlignY=65&descSize=18)" width="100%" />
</p>

<p align="center">
  <img src="[https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1500&color=0969DA&center=true&vCenter=true&width=600&lines=Natural+language+%E2%86%92+validated+IEC+61131-3;Cloud-native+microservices+%26+LLM+agents;Measure+first.+Verify+before+shipping](https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1500&color=0969DA&center=true&vCenter=true&width=600&lines=Natural+language+%E2%86%92+validated+IEC+61131-3;Cloud-native+microservices+%26+LLM+agents;Measure+first.+Verify+before+shipping)." />
</p>

```bash
$ whoami
Jiyu Li — Systems crossing OT, Cloud & AI

$ cat focus.txt
7 years in industrial automation (PLC, HMI, MV/HV drives, commissioning).
Currently building cloud-native backends and LLM agent pipelines.
Core focus: Translating natural-language intent into validated engineering systems.
```

### Architecture & Agentic Systems

* **AutoPLC-Agent** — Natural language to validated IEC 61131-3 / PLCopen TC6 XML.
```text
Requirements (NL)
   └─ req_parser ──▶ SystemRequirement JSON
        └─ gherkin_gen ──▶ .feature scenarios
             └─ ast_gen A/B/C ──▶ PLC_AST
                  └─ st_gen | ld_ir_gen (deterministic · LLM-direct · hybrid)
                       └─ plcopen_xml_exporter ──▶ PLCopen TC6 XML
                            └─ GATES: AST Syntax + MATIEC Compile + OpenPLC Simulation
```

* **Eattoday-Architecture-Spec** — Polyglot microservices platform specification (Python/FastAPI, Spring Boot, API gateway, Stripe, multi-cloud deployment). *(Spec public / Source private)*
* **Twin OS** — Spec-first deterministic agent runtime framework.

### Research

* **Edge Monocular Depth Estimation** — Benchmarking CNN (MiDaS) vs Transformer (Depth Anything) under edge compute constraints; ONNX runtime optimization (19.4 FPS).

### Tech Stack

```text
Backend:     Python (FastAPI, Pydantic), Java (Spring Boot), TypeScript, Node.js
Industrial:  Siemens TIA Portal (S7-1500 LAD/ST), IEC 61131-3, PLCopen XML, MV/HV VFDs
Data & AI:   LLM Agents, RAG (LangChain, LlamaIndex), PyTorch, ONNX, PostgreSQL, Redis
Cloud & Ops: Docker, Kubernetes, Google Cloud Run, AWS EC2, GitHub Actions, CI/CD
```

<br/>

<p align="center">
  <a href="[https://jiyu-automation-portfolio.vercel.app/](https://jiyu-automation-portfolio.vercel.app/)"><b>Portfolio</b></a> ·
  <a href="[https://linkedin.com/in/jiyu-li-software](https://linkedin.com/in/jiyu-li-software)"><b>LinkedIn</b></a> ·
  <a href="[https://github.com/JreeyL/AutoPLC-Agent](https://github.com/JreeyL/AutoPLC-Agent)"><b>AutoPLC-Agent</b></a> ·
  <a href="mailto:jreeylee92@outlook.com"><b>Email</b></a>
</p>
