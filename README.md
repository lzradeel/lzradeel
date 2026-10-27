<p align="center">
  <img src="./assets/banner.svg" width="100%" alt="Lazar Adeel, AI Engineer and Python Backend Engineer">
</p>

<p align="center">
  <a href="mailto:lzradeel@gmail.com"><img src="https://img.shields.io/badge/Email-lzradeel%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Based%20in-Troy%2C%20NY-131C3A?style=flat-square" alt="Based in Troy, NY">
  <img src="https://img.shields.io/badge/Python-7%2B%20years-3776AB?style=flat-square&logo=python&logoColor=white" alt="7+ years of Python">
</p>

### 👋 About me

I'm an AI engineer with 7+ years of Python. I lead an AI team at **Live Chat Global**, where we build a multi-tenant customer support platform that answers across chat, email and other channels with Claude, OpenAI and Pinecone. Before moving into AI I spent years building backend systems in FastAPI and Django, and I still write most of the hard code myself. I've worked with clients in the US, Canada and the EU.

### 🧠 What I work on

- **AI Autopilot** across 4 support channels, grounded in 11 knowledge-base integrations (Python 3.12, FastAPI, the Claude and OpenAI APIs, Pinecone)
- **Multi-model consensus answering**: Claude and OpenAI responses are cross-checked before delivery to reduce hallucinations, built without LangChain or LlamaIndex
- **Multi-tenant RAG** with Pinecone namespaces, org-scoped retrieval and JWT auth for strict tenant isolation
- **A resilient LLM service layer** with provider failover, response validation and token optimization, so cost per conversation stays predictable
- **Computer-vision damage inspection**: a YOLO detection microservice on FastAPI and a three-phase training pipeline, with GPT-4o and Pinecone RAG turning detected damage into itemized repair estimates

### 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/lzradeel/llmgater"><img src="https://raw.githubusercontent.com/lzradeel/llmgater/main/docs/banner.svg" alt="llmgater"></a>

**[llmgater](https://github.com/lzradeel/llmgater)**: an async Python LLM gateway in front of OpenAI, Anthropic and any OpenAI-compatible server.

- Provider failover with jittered backoff, `Retry-After` support and per-attempt or per-chunk deadlines
- A similarity cache scoped per account and conversation, plus per-account token quotas
- PII redaction, prompt-injection blocking and Pydantic-validated outputs with automatic repair
- 2 runtime dependencies, 161 offline tests, `mypy --strict`, CI on Python 3.11 to 3.14

[![CI](https://github.com/lzradeel/llmgater/actions/workflows/ci.yml/badge.svg)](https://github.com/lzradeel/llmgater/actions/workflows/ci.yml)

</td>
<td width="50%" valign="top">

<a href="https://github.com/lzradeel/answerpg"><img src="https://raw.githubusercontent.com/lzradeel/answerpg/main/docs/banner.svg" alt="answerpg"></a>

**[answerpg](https://github.com/lzradeel/answerpg)**: a RAG service that answers questions over your docs with citations, from a single PostgreSQL + pgvector database.

- Hybrid search: BM25 in SQL and pgvector HNSW, fused by reciprocal rank
- Cross-encoder reranking and `[n]` citations, with extractive or Anthropic-written answers
- A CI quality gate on 40 questions and 5 metrics: recall@5 **0.963**, MRR **0.872**
- A FastAPI service that logs timings, tokens and cost per request in Postgres, with a Docker demo

[![checks](https://github.com/lzradeel/answerpg/actions/workflows/checks.yml/badge.svg)](https://github.com/lzradeel/answerpg/actions/workflows/checks.yml)

</td>
</tr>
</table>

### 🛠️ Tech stack

**AI and LLMs**

<img src="https://skillicons.dev/icons?i=py,pytorch,opencv" alt="Python, PyTorch, OpenCV">

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square) ![Anthropic Claude](https://img.shields.io/badge/Anthropic%20Claude-191919?style=flat-square&logo=anthropic&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square) ![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![RAG](https://img.shields.io/badge/RAG%20%26%20evaluation-6366F1?style=flat-square) ![YOLO](https://img.shields.io/badge/YOLO-111F68?style=flat-square&logo=ultralytics&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white)

**Backend and APIs**

<img src="https://skillicons.dev/icons?i=fastapi,django,flask" alt="FastAPI, Django, Flask">

![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white) ![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white) ![JWT / OAuth 2.0](https://img.shields.io/badge/JWT%20%2F%20OAuth%202.0-000000?style=flat-square&logo=jsonwebtokens&logoColor=white) ![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black)

**Data, cloud and testing**

<img src="https://skillicons.dev/icons?i=postgres,redis,mongodb,mysql,aws,gcp,docker,githubactions,git,postman,jest" alt="PostgreSQL, Redis, MongoDB, MySQL, AWS, GCP, Docker, GitHub Actions, Git, Postman, Jest">

![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

### 📫 Get in touch

The best way to reach me is [lzradeel@gmail.com](mailto:lzradeel@gmail.com). I'm always happy to talk about LLM systems, RAG and Python backends.
