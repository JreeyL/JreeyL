<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,100:58A6FF&height=180&section=header&text=Jiyu%20Li&fontSize=44&fontColor=E6EDF3&desc=OT%20%C3%97%20Cloud%20%C3%97%20AI&descAlignY=64&descSize=18" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&pause=1200&color=58A6FF&center=true&vCenter=true&width=640&lines=Natural+language+%E2%86%92+validated+IEC+61131-3;Cloud-native+microservices+%26+LLM+agent+pipelines;Measure+first.+Verify+before+shipping." />
</p>

---

```console
$ whoami
Jiyu Li — systems that cross OT / cloud / AI

$ cat focus.txt
Seven years of industrial automation (PLC, HMI, LV–MV–HV drives, commissioning),
now building cloud-native services and LLM agent pipelines.
I work on the layer between them: natural language in, validated engineering artefacts out.
```

### Architecture & Agentic Systems

**AutoPLC-Agent** — natural language to validated IEC 61131-3 / PLCopen TC6 XML (MIT)

```text
requirements (NL)
   └─ req_parser ──▶ SystemRequirement JSON
        └─ gherkin_gen ──▶ .feature scenarios
             └─ ast_gen A/B/C ──▶ PLC_AST
                  └─ st_gen | ld_ir_gen  (deterministic · LLM-direct · hybrid)
                       └─ plcopen_xml_exporter ──▶ PLCopen TC6 XML 2.01
                            └─ GATES: Tier-1 schema/grounding + Tier-2 semantic review
                                      + MATIEC iec2c compile + OpenPLC v3 simulation
```

**Eattoday-Architecture-Spec** — polyglot microservices platform specification
(Python/FastAPI · Spring Boot · API gateway & edge security · Stripe · multi-cloud)

**Twin OS** — spec-first agent framework: frozen capability matrix as the fact source,
deterministic gates, fail-closed pipelines (framework spec public, no personal data)

### Research

**Edge monocular depth estimation** — CNN (MiDaS) vs transformer (Depth Anything) under edge
constraints; ONNX optimisation, 19.4 FPS on constrained hardware

### Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,fastapi,spring,docker,kubernetes,ts,nextjs,react,pytorch,git&theme=dark" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/IEC%2061131--3-ST%20%7C%20LD-0A66C2?style=for-the-badge" />
  <img src="https://img.shields.io/badge/PLCopen-TC6%20XML-0A66C2?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Siemens-TIA%20Portal-009999?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Stripe-payments-635BFF?style=for-the-badge&logo=stripe&logoColor=white" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=JreeyL&theme=github-dark-blue&hide_border=true&background=0D1117" height="150" />
</p>

---

<p align="center">
  <a href="https://jiyu-automation-portfolio.vercel.app/">Portfolio</a> ·
  <a href="https://linkedin.com/in/jiyu-li-software">LinkedIn</a> ·
  <a href="https://github.com/JreeyL/AutoPLC-Agent">AutoPLC-Agent</a> ·
  <a href="mailto:jreeylee92@outlook.com">jreeylee92@outlook.com</a>
</p>
