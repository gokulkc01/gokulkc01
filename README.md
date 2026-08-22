<!-- Header -->
<div align="center">

```
╔══════════════════════════════════════════════════════════╗
║  GOKUL K.C  ·  CSE (Cybersecurity) ·  MSRIT  ║
╚══════════════════════════════════════════════════════════╝
```

[![Portfolio](https://img.shields.io/badge/Portfolio-gokulkc.dev-c8f06e?style=flat-square&labelColor=0a0a0a)](https://gokulkc01.github.io/gokulkc.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-gokulkc01-c8f06e?style=flat-square&labelColor=0a0a0a&logo=linkedin&logoColor=c8f06e)](https://linkedin.com/in/gokulkc001)
[![Email](https://img.shields.io/badge/Email-kcgokul001@gmail.com-c8f06e?style=flat-square&labelColor=0a0a0a)](mailto:kcgokul001@gmail.com)
[![LeetCode](https://img.shields.io/badge/LeetCode-gokulkc01-c8f06e?style=flat-square&labelColor=0a0a0a)](https://leetcode.com/gokulkc01)

</div>

---

I build at the intersection of **cloud systems**, **IoT security**, and **intelligent agents** — focused on correctness, efficiency, and systems that hold up under real-world constraints.

Final-year undergraduate @ Ramaiah Institute of Technology · Graduating 2027

---

## 💼 Experience

**Software Intern**, SISA Information Security Pvt. Ltd. — *May 2026 – Present*
> Built a Retrieval-Augmented Generation (RAG) system to assist and streamline document review. Now relied on by the team for day-to-day review, improving accuracy and turnaround time.

---

## 🔧 Active Projects

**SentryNet** — Trust-Aware Multi-Agent RL Drone Surveillance
> 3-agent cooperative MARL system for drone-based intruder tracking in a 20×20×10m PyBullet airspace. EMA-based trust scoring under adversarial packet drops (Bernoulli + Gaussian spoofing). **>60% capture rate** at 30% comms loss — vs <40% baseline. Full MAPPO pipeline with WandB + ONNX export, reproducible via pytest.
>
> `PyTorch` `PyBullet` `PettingZoo` `MAPPO` `WandB` `ONNX` `pytest`

**[FarmAssist](https://github.com/gokulkc01)** — Edge-Cloud Smart Agriculture Platform
> Edge–cloud agriculture system (ESP32 + LoRa + Raspberry Pi) for real-time monitoring in low-connectivity environments. **90%+ on-device classification**, **<50ms inference**, **35% water reduction** via data-driven irrigation. Multilingual (EN/HI/KN/TA) AI advisory system with JWT auth, real-time dashboards, and remote irrigation control; edge-first design cut cloud bandwidth **70%** via quantized INT8 models (2.1MB → 180KB).
>
> `TF Lite` `ESP32` `LoRa` `Raspberry Pi` `React` `Node.js` `Express` `MongoDB`

**CyberShield** — ML-Based C2 Traffic Detection and Robustness Platform
> Transformer-based behavioral C2 detection on fixed-length network-flow sessions — **96.36% recall**, **0.9887 AUC**, **1.08% FPR** in zero-shot evaluation against Conficker malware. Cross-family generalization validated on strict family-separated CTU-13 splits (trained on Neris/Kraken, tested on unseen Conficker, no leakage). Domain-adaptive, host-aware Transformer variants with calibration layers, plus a defensive Red-Agent framework mutating timing/flow/TLS/composite features to stress-test detector fragility and evasion risk.
>
> `PyTorch` `scikit-learn` `FastAPI` `Next.js` `TypeScript` `Tailwind CSS` `pytest` `Jest`

---

## 🧪 Currently Building

*Early-stage — design and research, not shipped yet.*

**Betamusic** — Natural-Language-to-Melody Generation Pipeline *(architecture phase)*
> A prompt-to-MIDI composition API designed around explainable, replayable generation constraints and iterative regeneration, with rule-based generation planned as a permanent production layer rather than ML scaffolding. Core schemas and interfaces are done; next up is the scale/mood constants library, followed by a structure-first (motif → phrase → form) generator — informed by MeloForm (ISMIR 2022) — in place of a note-level random walk.
>
> `Python` `FastAPI` `Pydantic` `pretty_midi`

**BhoomiTwin** — Farm Digital Twin for Indian Smallholders *(research phase)*
> Evidence-first feasibility research for a living digital twin of smallholder farmland — soil, satellite (Sentinel-1/2, SAR for monsoon cloud cover), and crop models (DSSAT/AquaCrop) — scoped against real constraints: sub-₹-per-acre cost, patchy connectivity, low literacy, zero-technician maintenance. Running spikes on satellite resolution, sensor calibration, and nutrient strategy; explicitly not the product repo yet.
>
> `Python` `Sentinel-1/2` `STAC` `LoRaWAN`

---

## 🛠 Stack

```
Languages   →  Python · JavaScript / TypeScript · Java · C / C++ · SQL
Backend     →  FastAPI · Node.js · Express · REST APIs · Redis · PostgreSQL · MongoDB
Frontend    →  React · Next.js · Vite · Tailwind · Zustand · Framer Motion
ML / AI     →  PyTorch · TensorFlow · scikit-learn · NumPy · pandas · MAPPO · PPO · PyBullet · PettingZoo · ONNX
IoT / Edge  →  ESP32 · Raspberry Pi · LoRa · TinyML · TF Lite · MQTT
Systems     →  Docker · Linux · Git · Uvicorn · WebSockets · GCP
Security    →  Burp Suite · Metasploit · Wireshark · Nmap · Cryptography
Testing     →  pytest · Jest · httpx
```

---

## 📝 Writing

I document architecture decisions, tradeoffs, and lessons from building real systems.

- [**Real-Time IoT Digital Twins: VirtuNode's Redis Pub/Sub Architecture**](https://gokulkc01.github.io/gokulkc.github.io/blog/virtunode-redis-architecture.html) — Async deadlocks, multi-worker state, container lifecycle
- [**Edge vs Cloud: Building a Real-Time Agricultural IoT System**](https://gokulkc01.github.io/gokulkc.github.io/blog/edge-vs-cloud.html) — 70% bandwidth cut via TinyML on ESP32
- [**Detecting Ransomware Patterns: Inside My File Integrity Monitor**](https://gokulkc01.github.io/gokulkc.github.io/blog/file-integrity-monitor.html) — 96.3% detection accuracy
- [**TinyML in Practice: Neural Networks on Microcontrollers**](https://gokulkc01.github.io/gokulkc.github.io/blog/tinyml-edge-inference.html) — Quantization, pruning, 512KB RAM
- [**Designing a URL Shortener from Scratch**](https://gokulkc01.github.io/gokulkc.github.io/blog/url-shortener-design.html) — System design walkthrough

---

## 🎓 Background

| | |
|---|---|
| **B.E. CSE (Cybersecurity)** | Ramaiah Institute of Technology · 2023–2027 · CGPA 8.76/10 |
| **Jr. Penetration Tester** | TryHackMe · 2026 |
| **Database Management Systems** | NPTEL — IIT/IISc · 2024 |
| **Introduction to Security Principles in Cloud Computing** | Google Cloud Career Launchpad |
| **Artificial Intelligence A-Z** | Udemy · 2026 |

**Highlights:** 300+ DSA problems solved (LeetCode + GeeksforGeeks) · Top 4% TryHackMe user

---

<div align="center">
<sub>Open to internships, full-time roles & research collaborations · Cyber Security · Software Engineering · Distributed Systems · AI & ML</sub>
</div>
