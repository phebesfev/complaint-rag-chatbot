# Intelligent-Complaint-Analysis-for-Financial-Services

CrediTrust Complaint-Answering Chatbot
A Retrieval-Augmented Generation (RAG) system that transforms unstructured customer complaints into actionable insights for internal teams at CrediTrust Financial.

🚀 Project Overview
CrediTrust serves 500,000+ users across East Africa with products like credit cards, personal loans, BNPL, savings accounts, and money transfers. With thousands of monthly complaints, teams need a fast way to understand pain points.

This tool enables users to ask natural-language questions and get evidence-backed answers using semantic search and LLMs.

🎯 Objectives
Identify complaint trends in minutes, not days

Enable non-technical teams to extract insights

Shift from reactive to proactive problem-solving

🔧 Tech Stack
Embeddings: all-MiniLM-L6-v2 (Sentence Transformers)

Vector DB: FAISS / ChromaDB

LLM: Mistral / LLaMA / Hugging Face

UI: Streamlit or Gradio

Data: CFPB Complaint Dataset

📁 Project Structure
bash
Copy
Edit
├── data/                  # Raw & cleaned datasets
├── notebooks/             # EDA & preprocessing
├── src/                   # Chunking, embedding, RAG pipeline
├── vector_store/          # FAISS/ChromaDB index
├── app.py                 # Gradio/Streamlit UI
├── report/                # Evaluation & screenshots
├── requirements.txt
└── README.md
⚙️ Setup Instructions
Clone repo & install dependencies

bash
Copy
Edit
git clone <repo_url>
cd project-folder
pip install -r requirements.txt
Run the app

bash
Copy
Edit
python app.py
📌 Key Features
Ask plain-English questions about complaints

Get short, evidence-based answers with source excerpts

Filter by product: Credit Cards, Loans, BNPL, etc.

Clean, user-friendly interface for non-technical users

📝 Deliverables
Cleaned dataset (filtered_complaints.csv)

Vector index with metadata

Core RAG logic & evaluation

Functional chatbot UI

Final report with results & analysis

