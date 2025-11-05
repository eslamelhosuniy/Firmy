##  Overview  
**Firmy Platform** is an intelligent legal assistant that combines **RAG-based legal search**, **AI-powered contract analysis**, and **compliance verification**.  
It helps users search legal texts, review contracts, and verify compliance against official legal sources.

---

##  Features  

### 🔹 Phase 1 - Legal AI Search (RAG System)
- Hybrid **Retrieval-Augmented Generation** architecture.
- Uses both **internal legal repositories** and **official governmental data**.
- Validation Layer ensures reliability and citation accuracy.
- Interactive “Ask the AI” chat interface.

### 🔹 Phase 2 - Contract Upload & Compliance Checker
- Upload contracts and internal policies.
- AI generates compliance reports highlighting risks and violations.
- Clause classification (Confidentiality, Liability, Termination, etc.).

### 🔹 Phase 3 - Payment & Admin Dashboard
- Secure payment integration for subscription plans.
- Admin dashboard for managing users, contracts, and reports.

---

##  System Modules  

| Module | Description |
|--------|-------------|
| **RAG Data Source Integration** | Collect and index trusted legal content via web scraping and document parsing. |
| **Contract Feature Extraction** | Extract named entities and legal clauses from uploaded contracts. |
| **Compliance Checker** | Generate compliance and risk assessment reports. |
| **Admin Dashboard** | Manage users, payments, and document history. |

---

##  Tech Stack  

| Layer | Technologies |
|-------|---------------|
| **Frontend** | React.js / Next.js / Tailwind CSS |
| **Backend** | ASP .Net / FastAPI |
| **Database** | PostgreSQL / MySQL |
| **AI Layer** | OpenAI API / Local LLM / LangChain |
| **Vector Store** | FAISS  |
| **Deployment** | Docker |

npm run dev     # For frontend
python app.py   # Or node server.js for backend
