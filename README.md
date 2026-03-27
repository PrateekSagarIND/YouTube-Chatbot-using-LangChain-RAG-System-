# 🎬 YouTube Chatbot using LangChain (RAG System)

This project implements a Retrieval-Augmented Generation (RAG) chatbot that answers user questions based on a YouTube video transcript.

---

## 🚀 Features

- Extract transcript from YouTube videos  
- Split text into chunks for processing  
- Generate embeddings using OpenAI  
- Store embeddings in FAISS vector database  
- Retrieve relevant context for user queries  
- Generate answers using GPT-4.1-mini  

---

## 🧠 How It Works

1. Fetch the YouTube transcript  
2. Split the transcript into chunks  
3. Convert chunks into embeddings  
4. Store embeddings in FAISS  
5. Retrieve relevant chunks based on user query  
6. Generate answers using LLM  

---

## 📂 Project Structure

youtube-rag-chatbot/
│
├── notebook/
│   └── youtube_rag_chatbot.ipynb
│
├── README.md
├── requirements.txt
├── .gitignore
└── .env

---

## ⚙️ Installation

Clone the repository:

git clone https://github.com/your-username/youtube-rag-chatbot.git  
cd youtube-rag-chatbot  

Install dependencies:

pip install -r requirements.txt  

---

## 🔑 Setup API Key

Create a `.env` file in the root directory:

OPENAI_API_KEY=your_openai_api_key_here  

OR directly set in the notebook:

import os  
os.environ["OPENAI_API_KEY"] = "your_key"  

---

## ▶️ Run the Notebook

Open the notebook:

notebook/youtube_rag_chatbot.ipynb  

Run all cells step-by-step.

---

## 💡 Example Queries

- What is this video about?  
- Explain transformers in simple terms  
- What is the role of attention in LLMs?  

---

## 🛠️ Tech Stack

- LangChain  
- OpenAI API  
- FAISS  
- YouTube Transcript API  

---

## 📌 Notes

- Ensure the video has captions enabled  
- First run may take longer due to embeddings  
- Subsequent queries are faster  

---

## 👨‍💻 Author

Prateek Sagar  
M.Tech CSE (AI Specialization), IIIT Delhi  

---

## 📄 License

MIT License
