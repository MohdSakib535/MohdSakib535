<p align="center">
  <img src="./assets/banner.svg" width="100%" alt="Mohd Sakib — Senior Consultant, GenAI &amp; Agentic AI at StatusNeo" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/mohdsakibb/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://d1dhudon9u2vfb.cloudfront.net/"><img src="https://img.shields.io/badge/Portfolio-111827?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/></a>
  <a href="mailto:mohdsakib9398@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://statusneo.com"><img src="https://img.shields.io/badge/Now-Senior%20Consultant%20%40%20StatusNeo-7C3AED?style=for-the-badge" alt="Senior Consultant at StatusNeo"/></a>
</p>

## About me

I'm a **Senior Consultant at [StatusNeo](https://statusneo.com)**, working on **Generative AI and Agentic AI**. I design LLM agents that plan, call tools, retrieve and check evidence, and I ship them as secure, observable, production-grade systems.

Underneath is **5+ years of backend engineering** (Python, FastAPI, Django, Kafka, AWS, Azure), so the agents I build come with real software around them: typed APIs, async workers, event streams, tests and guardrails.

- **Agentic AI** — LangGraph multi-agent workflows: routing, tool calling, self-correction loops, human-in-the-loop review, durable Postgres checkpoints
- **RAG → GraphRAG** — hybrid vector + knowledge-graph retrieval (Neo4j, Elasticsearch, ChromaDB), evidence grading, answers with citations
- **Trustworthy AI** — prompt-injection defence, validated structured outputs, guardrails, and agents that abstain when the evidence is weak
- **AI-native backends** — event-driven systems serving **1,000+ concurrent submissions at sub-200 ms**; **~35% less DB connection overhead** with PgBouncer pooling

## More GenAI work

<table>
  <tr>
    <td colspan="2" valign="top">
      <h3><a href="https://github.com/MohdSakib535/Agentic-GraphRAG-Intelligent-Knowledge-Graph-Assistant">Agentic GraphRAG — Intelligent Knowledge Graph Assistant</a></h3>
      <p>Enterprise knowledge assistant that turns PDF, DOCX, TXT and Markdown into a <b>Neo4j knowledge graph + vector index</b>. A <b>LangGraph agent</b> routes each question to vector, multi-hop graph or hybrid retrieval, grades the evidence, rewrites weak queries, and verifies that every answer is grounded and cited — or abstains when the evidence isn't there.</p>
      <sub>LangGraph · LangChain · Neo4j · FastAPI · Celery · PostgreSQL · Redis · Streamlit · Docker</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/MohdSakib535/SkillProof-AI">SkillProof-AI</a></h3>
      <p>Multi-agent resume ↔ job-description verifier. A 4-node <b>LangGraph</b> pipeline (extract → match → quiz → evaluate) scores fit, quizzes the skills the job needs, and separates <i>verified</i> skills from merely claimed ones.</p>
      <sub>LangGraph · FastAPI · Celery · Kafka + Debezium CDC · Elasticsearch · 8 Docker services</sub>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/MohdSakib535/data-quality-agent">data-quality-agent</a></h3>
      <p>AI data-cleaning agent with a human in the loop: deterministic cleaning first, ambiguous text to a <b>local LLM</b> with Pydantic-validated output; low-confidence fixes go to a review queue and every decision is audit-logged.</p>
      <sub>FastAPI · LangChain · Ollama · Pydantic · Pandas</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/MohdSakib535/rag-fastApi-project">rag-fastApi-project</a></h3>
      <p>Source-grounded <b>RAG Q&amp;A</b> over PDF, DOCX, TXT and YouTube transcripts: chunking + embeddings in ChromaDB, prompt-injection hardening, decoupled FastAPI + Streamlit.</p>
      <sub>LangChain · LlamaIndex · ChromaDB · FastAPI · Streamlit</sub>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/MohdSakib535/FastApi_WebRTC">FastApi_WebRTC</a></h3>
      <p>AI meeting assistant: WebRTC video rooms stream live speech-to-text into Postgres, then an LLM (OpenAI or Hugging Face) turns the transcript into a downloadable <b>PDF summary</b>.</p>
      <sub>FastAPI · WebRTC · PostgreSQL · OpenAI · Hugging Face</sub>
    </td>
  </tr>
</table>

<sub>[All repositories →](https://github.com/MohdSakib535?tab=repositories)</sub>

## Toolbox

**Agentic AI & LLMs**

<p>
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=white" alt="LangGraph"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain"/>
  <img src="https://img.shields.io/badge/LlamaIndex-8A2BE2?style=for-the-badge&logoColor=white" alt="LlamaIndex"/>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI"/>
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" alt="Ollama"/>
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face"/>
  <img src="https://img.shields.io/badge/LangSmith-1C3C3C?style=for-the-badge&logoColor=white" alt="LangSmith"/>
  <img src="https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white" alt="Pydantic"/>
  <img src="https://img.shields.io/badge/Neo4j-4581C3?style=for-the-badge&logo=neo4j&logoColor=white" alt="Neo4j"/>
  <img src="https://img.shields.io/badge/ChromaDB-FFB000?style=for-the-badge&logoColor=black" alt="ChromaDB"/>
</p>

**Engineering & Cloud**

<p>
  <img src="https://skillicons.dev/icons?i=py,fastapi,django,flask,graphql,postgres,mongodb,redis,elasticsearch,kafka,rabbitmq,docker,kubernetes,aws,azure,jenkins,git,gitlab&perline=9" alt="Python, FastAPI, Django, Flask, GraphQL, PostgreSQL, MongoDB, Redis, Elasticsearch, Kafka, RabbitMQ, Docker, Kubernetes, AWS, Azure, Jenkins, Git, GitLab"/>
</p>

<sub>Also: Celery · Debezium (CDC) · DuckDB · MySQL · SQLite · Go · JavaScript · Pytest · CloudWatch · Postman · Swagger</sub>

## Experience

| Role | Company | Period |
| :-- | :-- | :-- |
| **Senior Consultant** — GenAI & Agentic AI | [StatusNeo](https://statusneo.com) | Sep 2026 – Present |
| **Software Engineer** — Python Backend & GenAI | Kellton | Jun 2025 – Sep 2026 |
| **Backend Developer** | Spacepe | May 2024 – Jun 2025 |
| **Associate Consultant** — Development | Oodles Technologies | Dec 2023 – Apr 2024 |
| **Full Stack Software Developer** | Seo Digital India | Jan 2022 – Nov 2023 |

**B.Tech, Computer Science & Engineering** — Jawaharlal Nehru Technological University, Hyderabad

## GitHub activity

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=MohdSakib535&theme=tokyonight" alt="GitHub profile summary"/>
</p>

## Let's talk

Always happy to compare notes on **agentic architectures, GraphRAG, LLM evaluation and production GenAI**. Find me on [LinkedIn](https://www.linkedin.com/in/mohdsakibb/) or at **mohdsakib9398@gmail.com**.

<p align="center"><sub>Building AI agents that plan, retrieve and verify — and know when to say “I don't know.”</sub></p>
