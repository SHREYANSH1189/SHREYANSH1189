<img src="https://capsule-render.vercel.app/api?type=waving&color=0:141414,100:E8481C&height=190&section=header&text=Shreyansh%20Tiwari&fontColor=ffffff&fontSize=48&fontAlignY=34&desc=AI%20Engineer%20%C2%B7%20Voice%20Agents%20%C2%B7%20RAG%20%C2%B7%20Agent%20Orchestration&descAlignY=54&descSize=16" width="100%" alt="Shreyansh Tiwari, AI Engineer">

<p align="center">
  <a href="https://kallix.in"><img src="https://img.shields.io/badge/Live%20product-kallix.in-E8481C?style=for-the-badge" alt="Kallix AI"></a>
  <a href="UPWORK_PROFILE_URL"><img src="https://img.shields.io/badge/Hire%20on-Upwork-14A800?style=for-the-badge&logo=upwork&logoColor=white" alt="Upwork"></a>
  <a href="mailto:t.shreyansh2002@gmail.com"><img src="https://img.shields.io/badge/Email-Get%20in%20touch-141414?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="LINKEDIN_URL"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/5%20years-in%20software-5C5A57?style=flat-square" alt="">
  <img src="https://img.shields.io/badge/focus-applied%20AI-E8481C?style=flat-square" alt="">
  <img src="https://img.shields.io/badge/based%20in-Delhi,%20India-5C5A57?style=flat-square" alt="">
  <img src="https://img.shields.io/badge/status-open%20to%20freelance-2E7D32?style=flat-square" alt="">
</p>

<br>

> **Most AI work fails somewhere between the demo and the invoice.**

I work on the part after the demo. Getting a voice agent to answer inside a second. Proving a retrieval pipeline returns the right passage rather than a plausible one. Keeping an agent from committing to something it shouldn't. Keeping token cost from quietly tripling in month two.

<br>

---

<h2>Where I go deep</h2>

<table>
<tr>
<td width="50%" valign="top">

### Voice agents

Streaming ASR with voice activity detection and barge-in. Continuous language identification across multilingual calls. LLM reasoning with function calling, low latency TTS.

The full loop budgeted **under one second**, because past that a caller reads the pause as a dropped line.

`ASR` `LLM` `TTS` `Telephony` `Barge-in`

</td>
<td width="50%" valign="top">

### RAG

Chunking strategy tested rather than guessed. Retrieval accuracy measured before and after, not eyeballed.

Citations enforced, and **refusal preferred over invention** when the corpus doesn't contain the answer.

`Embeddings` `Reranking` `Evals` `Citations`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Agents and orchestration

Tool use, state, retries and guardrails. Multi-agent workflows that run unattended without a human restarting them every morning.

Frameworks where they fit, **custom orchestration where they don't**.

`Agno` `LangGraph` `CrewAI` `MCP`

</td>
<td width="50%" valign="top">

### Fine-tuning and serving

LoRA and QLoRA on open weight models. Dataset preparation, evaluation against a held-out set.

Served in production with **cost and latency tracked**, not assumed.

`LoRA` `QLoRA` `vLLM` `Ollama`

</td>
</tr>
</table>

---

<h2>Selected work</h2>

<table>
<thead>
<tr>
<th width="22%">Project</th>
<th width="56%">What it is</th>
<th width="22%">Link</th>
</tr>
</thead>
<tbody>
<tr>
<td><b>Kallix AI</b><br><sub>Voice agent</sub></td>
<td>Fully managed multilingual voice agent. Answers and places calls in 10 languages, qualifies the caller, follows up on WhatsApp, and writes the booking into CRM and calendar. The loop closes on itself, so a missed booking re-enters the queue as an outbound call.</td>
<td><a href="https://kallix.in"><b>kallix.in</b></a><br><sub>Live in production</sub></td>
</tr>
<tr>
<td><b>Document intelligence</b><br><sub>Extraction pipeline</sub></td>
<td>Vision model extraction over scanned certificates. Unit conversion, null handling where a value is genuinely absent rather than invented, and structured output feeding a downstream engineering calculation.</td>
<td><a href="CASE_STUDY_URL">Case study</a><br><sub>Client work</sub></td>
</tr>
<tr>
<td><b>On-premise LLM</b><br><sub>Regulated data</sub></td>
<td>Privacy first architecture for health data across five clinic locations. De-identification before egress, provider abstraction as a single compliance choke point, pgvector instead of external vector services.</td>
<td><a href="CASE_STUDY_URL">Case study</a><br><sub>Client work</sub></td>
</tr>
<tr>
<td><b>Content engine</b><br><sub>Multi-agent</sub></td>
<td>Autonomous generation and scheduled publishing. Runs without a human trigger, with guardrails that stop anything questionable going out.</td>
<td><a href="CASE_STUDY_URL">Case study</a><br><sub>Internal</sub></td>
</tr>
</tbody>
</table>

---

<h2>Stack</h2>

<table>
<tr>
<td width="14%"><b>Models</b></td>
<td>
<a href="https://docs.anthropic.com"><img src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Claude"></a>
<a href="https://platform.openai.com/docs"><img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white" alt="OpenAI"></a>
<a href="https://ai.google.dev"><img src="https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini"></a>
<img src="https://img.shields.io/badge/Llama-0866FF?style=flat-square&logo=meta&logoColor=white" alt="Llama">
<img src="https://img.shields.io/badge/Mistral-FF7000?style=flat-square&logo=mistralai&logoColor=white" alt="Mistral">
<img src="https://img.shields.io/badge/Qwen-615CED?style=flat-square" alt="Qwen">
</td>
</tr>
<tr>
<td><b>Agents</b></td>
<td>
<a href="https://docs.agno.com"><img src="https://img.shields.io/badge/Agno-1B1B1B?style=flat-square" alt="Agno"></a>
<a href="https://langchain-ai.github.io/langgraph/"><img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangGraph"></a>
<a href="https://python.langchain.com"><img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain"></a>
<a href="https://docs.crewai.com"><img src="https://img.shields.io/badge/CrewAI-FF5A50?style=flat-square" alt="CrewAI"></a>
<a href="https://modelcontextprotocol.io"><img src="https://img.shields.io/badge/MCP-000000?style=flat-square" alt="MCP"></a>
</td>
</tr>
<tr>
<td><b>Retrieval</b></td>
<td>
<a href="https://github.com/pgvector/pgvector"><img src="https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="pgvector"></a>
<a href="https://docs.pinecone.io"><img src="https://img.shields.io/badge/Pinecone-000000?style=flat-square" alt="Pinecone"></a>
<a href="https://qdrant.tech/documentation/"><img src="https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white" alt="Qdrant"></a>
<a href="https://docs.llamaindex.ai"><img src="https://img.shields.io/badge/LlamaIndex-2B2B2B?style=flat-square" alt="LlamaIndex"></a>
</td>
</tr>
<tr>
<td><b>Backend</b></td>
<td>
<a href="https://docs.python.org/3/"><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"></a>
<a href="https://fastapi.tiangolo.com"><img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"></a>
<a href="https://nodejs.org/docs/latest/api/"><img src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js"></a>
<a href="https://www.postgresql.org/docs/"><img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"></a>
<img src="https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white" alt="Redis">
</td>
</tr>
<tr>
<td><b>Frontend</b></td>
<td>
<a href="https://nextjs.org/docs"><img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js"></a>
<a href="https://react.dev"><img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React"></a>
<a href="https://reactnative.dev"><img src="https://img.shields.io/badge/React%20Native-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React Native"></a>
<a href="https://www.typescriptlang.org/docs/"><img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"></a>
</td>
</tr>
<tr>
<td><b>Infra</b></td>
<td>
<img src="https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS">
<img src="https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="GCP">
<a href="https://docs.docker.com"><img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"></a>
<a href="https://docs.vllm.ai"><img src="https://img.shields.io/badge/vLLM-1B1B1B?style=flat-square" alt="vLLM"></a>
<a href="https://ollama.com"><img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white" alt="Ollama"></a>
</td>
</tr>
</table>

---

<h2>How I work</h2>

<details open>
<summary><b>&nbsp;Scope before code</b></summary>
<br>
You get a written breakdown of approach, risks and cost before anything starts, including an honest read on what a model cannot do for your use case. I would rather kill a feature in week one than bill for it in week six.
<br><br>
</details>

<details>
<summary><b>&nbsp;Evaluation is not optional</b></summary>
<br>
If a system can't be measured, it can't be improved, and you have no way of knowing whether my last change made it worse. Retrieval accuracy, latency percentiles and cost per interaction get tracked from the first week rather than retrofitted after launch.
<br><br>
</details>

<details>
<summary><b>&nbsp;I stay on it</b></summary>
<br>
Models drift, providers change pricing, and edge cases surface in month three. Handing over a working demo and disappearing is not delivery. Kallix has been running since launch and I still tune it weekly from real transcripts.
<br><br>
</details>

---

<h2>Open to work</h2>

Voice agents, RAG systems, agentic workflows and LLM integration.

Send me the problem rather than the spec, and I'll tell you whether AI is the right answer before quoting anything.

<p align="left">
  <a href="mailto:t.shreyansh2002@gmail.com"><img src="https://img.shields.io/badge/t.shreyansh2002@gmail.com-E8481C?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="UPWORK_PROFILE_URL"><img src="https://img.shields.io/badge/Upwork%20profile-14A800?style=for-the-badge&logo=upwork&logoColor=white" alt="Upwork"></a>
  <a href="https://kallix.in"><img src="https://img.shields.io/badge/kallix.in-141414?style=for-the-badge" alt="Kallix"></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:E8481C,100:141414&height=110&section=footer" width="100%" alt="">
