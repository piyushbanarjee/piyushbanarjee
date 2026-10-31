<!-- Animated waving header -->
<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=230&section=header&text=Piyush%20Banarjee&fontSize=58&fontColor=ffffff&fontAlignY=38&animation=fadeIn&desc=ML%20%2F%20AI%20Engineer%20%C2%B7%20Building%20from%20first%20principles&descSize=18&descAlignY=60&descColor=9be7ff" alt="header"/>
</p>

<!-- Typing animation -->
<p align="center">
  <a href="https://github.com/piyushbanarjee">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1200&color=00D9FF&center=true&vCenter=true&width=760&height=45&lines=Transformers+written+in+raw+JAX;GraphRAG+that+runs+fully+air-gapped;Multi-node+MPI+clusters+built+by+hand;Local+LLMs+%2B+strict+Pydantic+schemas;Open+to+ML%2FAI+internships+and+junior+roles" alt="Typing SVG"/>
  </a>
</p>

<p align="center">
  <a href="https://linkedin.com/in/piyushbanarjee"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:dev.piyush195@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://komarev.com/ghpvc/?username=piyushbanarjee&style=for-the-badge&color=0e75b6&label=PROFILE+VIEWS" alt="Profile views"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/📍_Pune,_India-1f2937?style=flat-square" alt="Location"/>
  <img src="https://img.shields.io/badge/🎓_Final--year_B.Tech_CSE-1f2937?style=flat-square" alt="Education"/>
  <img src="https://img.shields.io/badge/🟢_Open_to_work-16a34a?style=flat-square" alt="Open to work"/>
</p>

---

## 🧭 About Me

> I like understanding how things work underneath the framework.

I've written a Transformer in raw JAX, wired up a multi-node MPI cluster by hand, and built a GraphRAG platform that runs air-gapped on local models.

| | |
|---|---|
| 🔭 **Focus** | LLM systems, RAG, attention, accelerated compute |
| 🛠️ **Style** | First-principles builds, strict schemas, reproducible infra |
| 🌱 **Looking for** | Internships and junior roles with real AI/ML work, ideally at early-stage startups |
| 🐧 **Daily driver** | Linux + VS Code |

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🕵️ S.P.A.R.K.
**Air-gapped investigative intelligence platform**

Offline GraphRAG over unstructured legal and investigative dossiers. Entities live in NetworkX graphs beside ChromaDB vector indices, with strict Pydantic schemas over local Ollama output.

`FastAPI` `PostgreSQL` `ChromaDB` `Ollama` `NetworkX`

</td>
<td width="50%" valign="top">

### 🧠 Transformer from Scratch
**Custom attention engine in JAX**

Seq2seq Transformer from math, with no prebuilt model layers. Custom multi-head attention, positional encodings and causal masks, compiled with `jit` and `vmap`.

`JAX` `Flax` `XLA` `Python`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🖧 Distributed HPC Cluster
**Multi-node compute on Rocky Linux**

Static private routing, passwordless SSH and shared NFS. Parallel matrix multiplication in C with OpenMPI and latency profiling.

`Rocky Linux` `OpenMPI` `C` `Bash`

</td>
<td width="50%" valign="top">

### 🛡️ AirSCA
**Dependency vulnerability analysis API**

Parses SBOM data and maps the blast radius of vulnerable transitive dependencies with recursive SQL CTEs.

`FastAPI` `PostgreSQL` `Asyncio`

</td>
</tr>
</table>

<details>
<summary><b>🔍 How S.P.A.R.K. works (click to expand)</b></summary>

<br/>

```mermaid
flowchart LR
    A[📄 Dossiers<br/>legal + investigative] --> B[🧩 Entity extraction<br/>local Ollama SLM]
    B --> C{Pydantic<br/>schema gate}
    C -->|valid JSON| D[🕸️ NetworkX<br/>entity graph]
    C -->|valid JSON| E[🔎 ChromaDB<br/>vector index]
    D --> F[⚡ FastAPI<br/>hybrid retrieval]
    E --> F
    F --> G[💬 Grounded answer]
    C -.->|invalid| B
```

- **Problem:** manual cross-referencing of dossiers meant multi-hour lookups.
- **Resilience:** strict Pydantic schemas over Ollama streams block non-deterministic JSON failures.
- **Constraint:** everything runs offline, with no external API calls.

</details>

<details>
<summary><b>⚙️ How the JAX Transformer is built (click to expand)</b></summary>

<br/>

```mermaid
flowchart TB
    T[Tokens] --> E[Embedding + sinusoidal positions]
    E --> M[Multi-Head Attention<br/>causal mask]
    M --> N[Add & Norm]
    N --> FF[Feed-forward]
    FF --> O[Output logits]
    subgraph XLA["Compiled with jit · batched with vmap · trained with grad"]
    M
    N
    FF
    end
```

</details>

---

## 🧰 Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,cpp,c,bash,pytorch,fastapi,postgres,docker,linux,aws,firebase,git,githubactions,vscode&perline=7" alt="Tech stack icons"/>
</p>

| Area | Tools |
|---|---|
| **Languages** | Python (Asyncio, Pydantic), C++17/20, C, SQL, Bash |
| **AI / ML** | JAX/Flax, PyTorch, scikit-learn, PEFT (LoRA), Ollama, ChromaDB, pgvector |
| **Backend & Data** | FastAPI, REST, PostgreSQL (B-Tree indexing, CTEs), Firebase Functions |
| **Infra** | Linux (Rocky, Ubuntu), Docker, OpenMPI, AWS (EC2), OCI, Git |

---

## 💼 Experience

**Freelance Software Engineer, Orange Elixirs** · *Dec 2023 – Mar 2024*

- Owned cloud and backend delivery for a subscription video-streaming mobile app, from client requirements to a serverless MVP.
- Built idempotent Firebase Cloud Functions to validate Google Play billing webhooks without race conditions.
- Secured media delivery with token-authenticated Bunny.net CDN endpoints.

---

## 🎓 Education & Certifications

**B.Tech, Computer Science & Engineering (Software Engineering)** · Ajeenkya DY Patil University, Pune · 2023 – 2027

<p>
  <img src="https://img.shields.io/badge/Oracle-OCI_AI_Foundations_Associate-F80000?style=flat-square&logo=oracle&logoColor=white" alt="Oracle"/>
  <img src="https://img.shields.io/badge/Stanford_%2B_DeepLearning.AI-ML_Specialization-8C1515?style=flat-square" alt="Stanford"/>
  <img src="https://img.shields.io/badge/IBM-GenAI_Language_Modeling_with_Transformers-052FAD?style=flat-square&logo=ibm&logoColor=white" alt="IBM"/>
  <img src="https://img.shields.io/badge/Google_Cloud-Attention_%C2%B7_Transformers_%26_BERT_%C2%B7_LLMs-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="Google Cloud"/>
</p>

---

## 🤝 Let's Connect

> [!TIP]
> I'm open to internships and junior ML/AI engineering roles. If you're building something where the models, the retrieval and the infrastructure all matter, let's talk.

📫 **dev.piyush195@gmail.com** · [LinkedIn](https://linkedin.com/in/piyushbanarjee)

<p align="center"><i>"If I can't build it from scratch, I don't understand it yet."</i></p>

<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer" alt="footer"/>
</p>
