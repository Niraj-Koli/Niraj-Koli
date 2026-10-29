<h1 align="center">Hi, I'm Niraj Koli 👋</h1>

<p align="center">
  <b>Software Engineer · Backend & AI/ML</b><br>
  I build high-volume, event-driven systems for the National Stock Exchange of India, and AI systems that detect, reason and act.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/niraj-koli/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:nirajkoli1012@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://leetcode.com/u/KaiZer-/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"></a>
</p>

---

## 🚀 About me

- 💼 **Software Engineer at IESoft Technologies**, working on production systems for the **National Stock Exchange of India (NSE)** since Aug 2024
- ⚡ Build event-driven data replication on **Solace PubSub+** that moves **10M+ messages (3.4 TB) a day** between the data center and disaster recovery site
- 📈 Develop **Node.js, Express and TypeScript** microservices for NSE's **Offer for Sale (OFS)** and **order book** workflows
- 🏎️ Cut API response times from **150–200 ms to 10–20 ms** by rebuilding legacy microservices
- 🤖 Trained **YOLOv8** models for intrusion detection and surveillance products, and build **multi-agent LLM** systems
- 🎓 B.E. in Computer Engineering, University of Mumbai · CGPA 9.25 / 10

---

## 🛠️ Featured projects

### [Gauntlet](https://github.com/Niraj-Koli/Gauntlet) · Multi-Agent LLM Trading Platform
A paper-trading arena where up to **6 AI agents on six LLM providers** trade on live market data with simulated money. Agents research markets, follow database-enforced limits and refine their strategies from past results.

- **Per-run tracing and cost tracking** to compare how each model performs
- Signed MCP tokens, row-level locking and a leader-elected scheduler so agents run safely in parallel
- Deployed on Kubernetes with Helm, Argo CD (GitOps) and Sealed Secrets · **250 tests, 95% coverage**

`Python` `FastAPI` `PostgreSQL` `OpenAI Agents SDK` `LiteLLM` `MCP` `Next.js` `Supabase` `Kubernetes`

### [Secureye](https://github.com/Niraj-Koli/Secureye) · AI Threat Detection Platform
A full-stack app with custom-trained **YOLOv8** models that detect intruders and weapons across **12 classes** in photos, videos and live camera feeds, with **~85–90% accuracy**.

- Background video pipeline with Celery and ByteTrack, streaming labeled frames in real time over Server-Sent Events
- Live webcam detection over WebSockets at ~4 frames/sec on CPU
- Auth built from scratch: Argon2id hashing, rotating JWT refresh tokens and rate limiting
- **340+ automated tests** with a GitHub Actions CI pipeline for type checks, dependency audits and image scans

`Python` `FastAPI` `YOLOv8` `Celery` `Redis` `PostgreSQL` `React` `TypeScript` `Docker`

---

## 🧰 Tech stack

**Languages**
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL">
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" alt="Bash">
</p>

**Backend & Messaging**
<p>
  <img src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white" alt="Express.js">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white" alt="GraphQL">
  <img src="https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white" alt="Celery">
  <img src="https://img.shields.io/badge/Solace_PubSub%2B-00C895?style=flat-square" alt="Solace PubSub+">
</p>

**Frontend**
<p>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js">
  <img src="https://img.shields.io/badge/Redux_Toolkit-764ABC?style=flat-square&logo=redux&logoColor=white" alt="Redux Toolkit">
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite">
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/Material_UI-007FFF?style=flat-square&logo=mui&logoColor=white" alt="Material UI">
</p>

**AI / ML & LLMs**
<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/YOLOv8-111F68?style=flat-square" alt="YOLOv8">
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV">
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face">
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain">
  <img src="https://img.shields.io/badge/OpenAI_Agents_SDK-412991?style=flat-square" alt="OpenAI Agents SDK">
  <img src="https://img.shields.io/badge/MCP-555555?style=flat-square" alt="Model Context Protocol">
</p>

**Databases**
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis">
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB">
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase">
</p>

**DevOps & Tools**
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes">
  <img src="https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white" alt="Helm">
  <img src="https://img.shields.io/badge/Argo_CD-EF7B4D?style=flat-square&logo=argo&logoColor=white" alt="Argo CD">
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions">
  <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" alt="Nginx">
  <img src="https://img.shields.io/badge/RHEL_Linux-EE0000?style=flat-square&logo=redhat&logoColor=white" alt="RHEL Linux">
  <img src="https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=claude&logoColor=white" alt="Claude Code">
</p>

---

<p align="center">
  💬 Open to <b>Software Engineering</b> and <b>AI Engineering</b> roles · Reach me at <a href="mailto:nirajkoli1012@gmail.com">nirajkoli1012@gmail.com</a>
</p>
