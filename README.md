# RAG_GROQ_APP
A Streamlit-based RAG chatbot that uses Groq's LLaMA 3 model to answer user questions by retrieving and summarizing content from the website.
# 💬 ChatGroq RAG Demo (Any Website)
🚀 Features

- ✅ Retrieval-Augmented Generation (RAG) pipeline using FAISS vector search  
- ✅ Embedding generation using **OllamaEmbeddings**  
- ✅ Fast and accurate responses using **Groq’s LLaMA3-70B** model  
- ✅ Source-aware answers with document similarity preview  
- ✅ Clean, interactive UI built with **Streamlit**  
- ✅ Automatically scrapes and processes website content on first run

🧠 How It Works

1. Web Scraping: Loads content from a specified website  
2. Text Chunking: Splits long pages into smaller readable chunks  
3. Vectorizatio: Embeds each chunk using semantic embeddings  
4. Retrieval: When a question is asked, it finds the most relevant chunks  
5. LLM Generation: Sends retrieved chunks and question to Groq’s LLM  
6. Response: Displays an accurate answer with supporting context

🛠️ Tech Stack

| Tool             | Purpose                                |
|------------------|----------------------------------------|
| Streamlit        | Frontend / UI                          |
| Groq             | Fast LLM API (LLaMA 3)                 |
| FAISS            | Vector store for document retrieval    |
| OllamaEmbeddings | Converts text into semantic vectors    |
| LangChain        | Orchestrates RAG pipeline              |
| Python           | Backend logic                          |

 🧪 Setup Instructions


1. Clone the Repo
git clone https://github.com/your-username/chatgroq-rag.git
cd chatgroq-rag

3. Install Dependencies
pip install -r requirements.txt

5. Add Your Environment Variable
GROQ_API_KEY=your_groq_api_key_here
(Get your API key at: https://console.groq.com/)

▶️ Run the App
streamlit run app.py

