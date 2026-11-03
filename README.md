<h1 align="center">Hi, I'm Harsh Vardhan Singh</h1>

<p align="center">
  Pre-final year student at VIT Vellore building scalable backend systems, real-time apps, and AI/ML products.
</p>

<p align="center">
  <a href="https://harxhe.dev">Portfolio</a> •
  <a href="https://linkedin.com/in/harxhe">LinkedIn</a> •
  <a href="https://medium.com/@harxhe">Blog</a>
</p>

---

### Featured Projects

<details>
<summary><b>Echo</b>: Discord-inspired platform, 900+ users at Gravitas | <code>TypeScript</code> <code>Socket.IO</code> <code>Redis</code> <code>PostgreSQL</code></summary>

<br>

- Co-developed the backend for real-time messaging, typing indicators, and presence, scaled across instances with the Redis adapter
- Designed a PostgreSQL schema for friend graphs, server roles, and polymorphic channels
- [Repo](https://github.com/harxhe/echo-backend-harsh) • [Details](https://harxhe.dev/project/echo)

</details>

<details>
<summary><b>Wormhole</b>: self-hosted reverse tunnel, an ngrok alternative | <code>Node.js</code> <code>TypeScript</code> <code>TLS</code></summary>

<br>

- A client opens one outbound TLS connection to a public relay server, which assigns a subdomain and forwards incoming requests through the tunnel
- Custom binary protocol multiplexes many concurrent requests over that single connection
- [Repo](https://github.com/harxhe/wormhole)

</details>

<details>
<summary><b>Real-Time Voice Assistant</b>: VAD → ASR → LLM → TTS, under 5.5s latency | <code>Python</code> <code>PyTorch</code> <code>Faster-Whisper</code></summary>

<br>

- Token-level LLM streaming and chunk-based synthesis to cut end-to-end latency
- State-machine engagement layer with filler audio and barge-in support
- [Repo](https://github.com/harxhe/real-time-voice-assistant) • [Details](https://harxhe.dev/project/real-time-voice-assistant)

</details>

<details>
<summary><b>CI/CD Failure Prediction</b>: serverless AWS system that predicts build failures mid-run | <code>Python</code> <code>AWS</code></summary>

<br>

- Predicts whether a CI build is likely to fail while it is still running
- Sends an email alert when the predicted risk is high
- [Repo](https://github.com/harxhe/cicd-failure-prediction-framework)

</details>

<details>
<summary><b>HealAgent</b>: self-healing agent framework with a learned recovery policy | <code>Python</code></summary>

<br>

- Extends the Monitor → Detect → Diagnose → Recover → Verify loop from Babu & Agrawal (2026)
- Adds a Recovery Ledger (failure signature → action → outcome) and a bandit-based selector that learns the best recovery action per failure type
- [Repo](https://github.com/harxhe/self-healing-agent-framework)

</details>

<details>
<summary><b>Kernel Module Rootkit Detector</b>: Linux tool that flags suspicious kernel module changes | <code>C</code> <code>Linux</code></summary>

<br>

- Scans loaded kernel modules and compares the current state against a trusted baseline
- Identifies suspicious changes and assigns a risk score
- [Repo](https://github.com/harxhe/kernel-module-rootkit-detector)

</details>

<details>
<summary>More projects</summary>

<br>

- **[JanSeva](https://github.com/harxhe/JanSeva)**: AI civic complaint platform with voice complaints in 21+ languages (React Native, Node.js, FastAPI, Groq)
- **[ChatWithPDF RAG](https://github.com/harxhe/chatwithpdf-rag-system)**: document Q&A using LangChain, a vector DB, and Flan-T5-Large
- **[XyraChain](https://github.com/harxhe/XyraChain)**: healthcare AI platform with CNN chest X-ray analysis, IPFS report storage, and blockchain-ready verification

</details>

---

### Tech Stack

**Languages:** Python, Go, Java, C++, TypeScript, SQL<br>
**Frameworks & Libraries:** FastAPI, Node.js, Express.js, React, LangChain, PyTorch, Hugging Face<br>
**Databases & Cloud:** PostgreSQL, Redis, MongoDB, Supabase, GCP, AWS<br>
**DevOps & Concepts:** Docker, GitHub Actions, Git, System Design, RAG

---

### Recent Writing

- [How I made my own offline voice assistant](https://medium.com/@harxhe/how-i-made-my-own-offline-voice-assistant-f45d223d64ad)
- [The era of vibe coding: how AI is changing the way we build apps](https://medium.com/techloop/the-era-of-vibe-coding-how-ai-is-changing-the-way-we-build-apps-98433507a544)
