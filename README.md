# 🧠 AI Document Embedding Workflow with Pinecone

This workflow automates the process of loading documents from Google Drive, splitting them, generating embeddings using OpenAI, and storing them in Pinecone for semantic search or retrieval-augmented generation (RAG).

---

## 📌 Use Cases

- RAG applications (question-answering over uploaded files)
- Semantic search in enterprise document databases
- AI-powered document understanding and summarization
- Knowledge base construction

---

## ⚙️ Workflow Overview

1. **Trigger**: Manual start (`When clicking 'Test workflow'`)
2. **Google Drive**: Downloads a file
3. **Default Data Loader**: Parses the file
4. **Recursive Text Splitter**: Splits long text into chunks
5. **OpenAI Embeddings**: Generates embeddings
6. **Pinecone Vector Store**: Stores the vectorized content

---

## 🛠 Built With

- [n8n](https://n8n.io) – visual workflow automation
- [Google Drive API](https://developers.google.com/drive)
- [OpenAI API](https://platform.openai.com/)
- [Pinecone](https://www.pinecone.io/) – vector database

---

## 🧩 Screenshot

![AI Embedding Workflow](assets/n8n-vector-flow.png)

---

## 🗂 Folder Structure

/your-repo
│
├── assets/
│   └── n8n-vector-flow.png
│
└── vector-ingest-flow.json



---

## 🚀 Getting Started

1. Clone this repo  
2. Import `vector-ingest-flow.json` into n8n  
3. Add your API credentials for Google, OpenAI, and Pinecone  
4. Click **Test Workflow**

---

## 📝 License

MIT


