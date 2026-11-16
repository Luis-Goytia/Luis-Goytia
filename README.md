<div align="center">

<img src="./assets/header.svg" alt="Luis Goytia — AI Engineer &amp; Backend Developer" width="100%" />

<a href="https://luiscabezas.vercel.app/">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=2800&pause=900&color=22D3EE&center=true&vCenter=true&width=720&lines=I+ship+AI+agents+to+production;Multi-agent+systems+%C2%B7+MCP+servers+%C2%B7+RAG;Low-latency+voice+agents;Self-hosted+LLMs+with+Terraform;Spec-driven+development+with+BMAD" alt="What I do" />
</a>

<p>
  <a href="https://luiscabezas.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-luiscabezas.vercel.app-06b6d4?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/luis-goytia/"><img src="https://img.shields.io/badge/LinkedIn-luis--goytia-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:luisgoytia.dev@gmail.com"><img src="https://img.shields.io/badge/Email-Let's%20talk-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<img src="https://img.shields.io/badge/📍-Argentina%20(UTC--3)-1e293b?style=flat-square" alt="Argentina (UTC-3)" />
<img src="https://img.shields.io/badge/🌎-Remote-1e293b?style=flat-square" alt="Remote" />
<img src="https://img.shields.io/badge/🟢-Open%20to%20opportunities-16a34a?style=flat-square" alt="Open to opportunities" />

</div>

<br />

## 👋 About me

I'm an **AI Engineer & Backend Developer** who takes AI out of the notebook and into production: autonomous agents, multi-agent systems, MCP servers, RAG and real-time voice agents.

I cover the whole path, from the use case and the spec to orchestration, tools and infrastructure, with **Python**, **Node.js / NestJS** and **Go**.

## 🚀 What I'm building

<table>
<tr>
<td width="50%" valign="top">

### 🧠 Company brain · Facephi
<sub>Digital identity & fraud prevention · clients in 30+ countries</sub>

- Internal AI platform that puts agents and use cases at the service of every team
- Agents that resolve customer tickets on their own, integrated with **Zoho** and **Atlassian**
- **Self-hosted LLMs (Qwen)** on company servers, provisioned with **Terraform**, alongside OpenAI and Claude
- **MCP servers**, tools and multi-agent RAG flows on **Mastra + Bun** and **LangGraph**
- Spec-driven development with **BMAD**

</td>
<td width="50%" valign="top">

### 🏢 AI for smart buildings · Keedian
<sub>Building management for multi-site operators · 12,000+ monitored sites</sub>

- Brought AI into a platform serving JCPenney, 7-Eleven, Crate & Barrel and Banco Santander
- Agents that automate **~90% of support processes**
- Autonomous agents + RAG that detect energy anomalies and trigger alerts, calls and technician dispatch
- Low-latency **voice agents** with Twilio, ElevenLabs and Deepgram
- Orchestration with **LangGraph** on NestJS and Redis

</td>
</tr>
</table>

## 🧩 How I build agents

```mermaid
flowchart LR
    A[Use case] --> B[Spec · BMAD]
    B --> C{Orchestrator<br/>LangGraph · Mastra}
    C --> D[MCP servers & tools]
    C --> E[RAG · vector memory]
    C --> F[Voice pipeline]
    D --> G[(APIs · Zoho · Atlassian · Meta)]
    E --> H[(pgvector · Redis · Pinecone)]
    C --> I[LLMs<br/>OpenAI · Claude · self-hosted Qwen]
    I --> J[Evals & observability · Langfuse]
    J --> K([Production])
```

## 🛠️ Tech stack

<table>
<tr>
<td valign="top" width="50%">

**🤖 Agents & orchestration**

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Mastra](https://img.shields.io/badge/Mastra-000000?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-servers%20%26%20tools-6366f1?style=flat-square)
![Semantic Kernel](https://img.shields.io/badge/Semantic%20Kernel-5C2D91?style=flat-square)
![A2A](https://img.shields.io/badge/A2A-6366f1?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-6366f1?style=flat-square)

**🧠 Models**

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=claude&logoColor=white)
![Qwen](https://img.shields.io/badge/Qwen-self--hosted-615CED?style=flat-square)
![DeepSeek](https://img.shields.io/badge/DeepSeek-4D6BFE?style=flat-square)
![Llama](https://img.shields.io/badge/Llama-0467DF?style=flat-square&logo=meta&logoColor=white)

**🎙️ Voice agents**

![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=flat-square&logo=twilio&logoColor=white)
![ElevenLabs](https://img.shields.io/badge/ElevenLabs-000000?style=flat-square&logo=elevenlabs&logoColor=white)
![Deepgram](https://img.shields.io/badge/Deepgram-13EF93?style=flat-square&logoColor=black)
![LiveKit](https://img.shields.io/badge/LiveKit-1F2937?style=flat-square)
![Pipecat](https://img.shields.io/badge/Pipecat-1F2937?style=flat-square)
![OpenAI Realtime](https://img.shields.io/badge/OpenAI%20Realtime-412991?style=flat-square)

</td>
<td valign="top" width="50%">

**⚙️ Backend**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Bun](https://img.shields.io/badge/Bun-000000?style=flat-square&logo=bun&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)

**🗄️ Data & vector memory**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL%20%2F%20pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square)

**☁️ Infrastructure & quality**

![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square)
![Langfuse](https://img.shields.io/badge/Langfuse-evals%20%26%20observability-0A0A0A?style=flat-square)
![BMAD](https://img.shields.io/badge/BMAD-spec--driven-0A0A0A?style=flat-square)

</td>
</tr>
</table>

## 📊 GitHub activity

<div align="center">
  <img src="https://streak-stats.demolab.com?user=Luis-Goytia&hide_border=true&background=0f172a&ring=22d3ee&fire=22d3ee&currStreakLabel=22d3ee&sideLabels=e2e8f0&currStreakNum=e2e8f0&sideNums=e2e8f0&dates=94a3b8" alt="GitHub streak" />
</div>

<details>
<summary><b>🇪🇸 Versión en español</b></summary>

<br />

Soy **AI Engineer y Backend Developer**. Llevo la IA a producción: agentes autónomos, sistemas multiagente, servidores MCP, RAG y voice agents en tiempo real.

- **Facephi:** construyo el company brain, la plataforma interna de IA de una compañía de identidad digital con clientes en más de 30 países. Agentes que atienden tickets (Zoho, Atlassian), modelos locales (Qwen) en servidores propios con Terraform, servidores MCP y flujos multiagente con Mastra y LangGraph, con metodología spec-driven (BMAD).
- **Keedian:** introduje la IA en una plataforma de gestión de edificios con más de 12.000 sitios monitoreados. Agentes que automatizan cerca del 90 % de los procesos de soporte, detección de anomalías energéticas con despacho de técnicos y voice agents de baja latencia.

Trabajo en remoto desde Argentina (UTC-3). Escribime a **luisgoytia.dev@gmail.com** o por [LinkedIn](https://www.linkedin.com/in/luis-goytia/).

</details>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=110&color=0:06b6d4,50:1e3a8a,100:0f172a&section=footer" alt="" width="100%" />

</div>
