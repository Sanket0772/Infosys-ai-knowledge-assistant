# infosys-ai-knowledge-assistant-
AI Knowledge Assistant for enterprise document retrieval, grounded answers, citations, and knowledge management.

# 🔗 Project Links

- **GitHub:** https://github.com/Sanket0772/Infosys-ai-knowledge-assistant
- **Live Demo:** ADD LIVE LINK
- **Demo Video:** ADD GOOGLE DRIVE LINK

## 📌 Project Overview

The **Infosys AI Knowledge Assistant** is a Generative AI-powered enterprise knowledge management system designed to help employees quickly find reliable information from internal documents.

Instead of manually searching through multiple HR policies, technical guides, project manuals, SOPs, and business documents, users can ask questions in natural language and receive relevant, grounded answers.

The system combines:

- Retrieval-Augmented Generation (RAG)
- Document ingestion and processing
- Query classification
- Vector-based knowledge retrieval
- Grounded answer generation
- Source citations
- Answer validation
- Authentication and Role-Based Access Control (RBAC)
- Analytics and feedback
- AI workflow orchestration

The project is developed as an Applied GenAI prototype demonstrating how enterprise knowledge can be made accessible through a conversational AI interface.

---

# 🎯 Business Problem

Enterprise information is often distributed across different documents such as:

- HR policies
- Technical documentation
- Project manuals
- Standard Operating Procedures (SOPs)
- Engineering guides
- Business and sales documents

Employees may spend significant time searching through these documents to find a specific piece of information.

Traditional keyword-based document searching can also make it difficult to understand questions expressed in natural language.

The proposed solution provides a conversational knowledge assistant where employees can simply ask a question and receive an answer based on the organization's approved knowledge sources.

---

# 🎯 Product Goal

The primary goal of the system is:

> **To provide reliable, evidence-backed answers from approved enterprise documents while reducing unsupported or hallucinated responses.**

The assistant should:

1. Understand the user's question.
2. Classify the query.
3. Retrieve relevant enterprise knowledge.
4. Generate an answer using retrieved evidence.
5. Provide citations or source information.
6. Validate the generated response.
7. Avoid answering when sufficient evidence is unavailable.
8. Respect user permissions and access boundaries.

   
# 🚀 Key Features

### 🤖 AI-Powered Question Answering

Users can ask enterprise-related questions using natural language instead of manually searching through documents.

### 📚 Retrieval-Augmented Generation

The system retrieves relevant document content before generating an answer, helping ground the response in available enterprise knowledge.

### 📄 Document Ingestion

The ingestion pipeline supports processing enterprise documents and preparing them for retrieval.

Supported document formats include:

- PDF
- DOCX
- TXT

### 🔎 Query Classification

User questions are classified before the retrieval and answer-generation process.

This allows the system to determine the appropriate workflow for the incoming query.

### 🧠 Grounded Answer Generation

The answer-generation workflow uses retrieved evidence instead of relying only on the language model's general knowledge.

### 📑 Source Citations

Answers can include source information so users can understand where the information was retrieved from.

### ✅ Answer Validation

Generated answers pass through a validation stage to check whether the response is sufficiently supported by the retrieved evidence.

### 🔐 Authentication & RBAC

The application includes authentication and role-based access control mechanisms to restrict access to appropriate functionality and information.

### 📤 Knowledge Upload

Authorized users can upload documents that can be processed through the ingestion pipeline.

### 📊 Analytics

The application includes analytics functionality for understanding usage and knowledge-assistant activity.

### 🔌 Tool / MCP Integration

The project includes tool integration functionality as part of the AI workflow and enterprise knowledge architecture.

# 🛠️ Technologies Used

| Component | Technology |
|---|---|
| Frontend | Next.js, React, TypeScript |
| Backend | Python, FastAPI |
| AI | Generative AI, RAG, Embeddings |
| Retrieval | Vector-based retrieval |
| Document Processing | PDF, DOCX, TXT |
| Security | Authentication, JWT, RBAC |
| Testing | Python Testing Framework |
| Deployment | Vercel / Render |
---

## 🏗️ Architecture

The application follows a modular frontend, backend, AI workflow, and knowledge-processing architecture.

```text
                         User
                           │
                           ▼
                  ┌─────────────────┐
                  │ Next.js Frontend│
                  └────────┬────────┘
                           │
                           ▼
                  ┌─────────────────┐
                  │ FastAPI Backend │
                  └────────┬────────┘
                           │
                           ▼
                  ┌─────────────────┐
                  │   AI Workflow   │
                  └────────┬────────┘
                           │
          ┌────────────────┼────────────────┐
          ▼                ▼                ▼
   Query Classification  RAG Retrieval  Tool Selection
          │                │                │
          └────────────────┼────────────────┘
                           │
                           ▼
                  Grounded Synthesis
                           │
                           ▼
                    Citation Builder
                           │
                           ▼
                    Answer Validation
                           │
                           ▼
                    Final Response



## 👥 Team Members

- **Sanket Arun Patil**
- ** Pulkit Narang**
- **Sayan Modak**
- **Soumyakanta Mishra**
- **Subhansu Bose**
- **Chandra Akash Kiran**
- **M.S. Pavan Shankar**
- **Shruti Vishwas Deshpande**
