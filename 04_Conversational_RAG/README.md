# 🧠 ConversaRAG – Intelligent Conversational RAG Chatbot

An AI-powered **Conversational Retrieval-Augmented Generation (RAG) Chatbot** that answers user queries based on uploaded documents while maintaining conversation memory.

---

## 🚀 Project Overview

ConversaRAG is designed to:

- Answer questions using your uploaded documents  
- Maintain conversation history  
- Improve response relevance using context-aware retrieval  
- Combine LLM + Vector Search (FAISS)  

---

## 📂 Project Structure

```
04_Conversational_RAG/
│
├── Data/
│   ├── Fundamental of Data Science.pdf
│   ├── Introduction to Outlier.docx.pdf
│   ├── NIST-CSF-NOTES.pdf
│   └── NIST-CyberSecurityFramework.pdf
│
├── Notebooks/
│   ├── Conversational_rag.ipynb   # Main chatbot notebook
│   └── faiss_index/               # Temporary index storage
│
├── Vectore_DB/
│   ├── index.faiss                # Vector index
│   └── index.pkl                  # Metadata
│
├── requirements.txt
└── README.md
```

---

## ⚙️ How It Works

1. Documents are loaded from the **Data folder**  
2. Text is split into chunks  
3. Embeddings are generated using an LLM model  
4. Stored in **FAISS vector database**  

### During Chat:
- User query + conversation history is processed  
- Relevant chunks are retrieved  
- LLM generates contextual answer  

---

## 🛠️ Installation

### 1. Clone the Repository
```bash
git clone <your-repo-link>
cd 04_Conversational_RAG
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Set Environment Variables
```bash
set OPENAI_API_KEY=your_api_key   # Windows
export OPENAI_API_KEY=your_api_key   # Linux/Mac
```

---

## ▶️ How to Use

### Step 1: Add Your Documents
Place all PDFs inside:
```
Data/
```

### Step 2: Run the Notebook

Open:
```
Notebooks/Conversational_rag.ipynb
```

Run all cells step by step.

---

### Step 3: Start Chatbot

```
🤖 Chatbot Started (type 'exit' to stop)

🧑 You: What is AI?
🤖 Bot: ...
```

---

## 💡 Features

- ✅ Document-based Q&A  
- ✅ Conversational memory  
- ✅ Context-aware responses  
- ✅ FAISS fast retrieval  
- ✅ Multi-document support  
- ❌ Personal memory is short-term (session-based)  

---

## 🔧 Future Improvements

- Add persistent memory (database)  
- Build UI (Streamlit / React)  
- Optimize retrieval (hybrid search)  
- Add user authentication  
- Deploy as API  

---

## 📦 Requirements

```
langchain
langchain-community
langchain-openai
faiss-cpu
openai
tqdm
```

---

## 🧪 Example Use Cases

- Study assistant from PDFs  
- Cybersecurity document Q&A  
- Research summarization  
- Personal knowledge base  

---

## 📌 Important Note

This system:

- Does NOT know everything  
- Only answers based on:
  - Uploaded documents  
  - Limited conversation memory  

If information is missing → output may be incomplete or incorrect.

---

## 👨‍💻 Author

**Karan Mistry**  
AI / GenAI Developer (Learning Phase)

---

## ⚡ Reality Check

This is a **learning project**, not production-grade.

- No real understanding  
- No long-term memory  
- Just retrieval + LLM response generation  

To improve:
- Focus on retrieval quality  
- Improve prompt design  
- Build better memory systems  