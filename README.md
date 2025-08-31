<h1 align="center">🤖 LangChain RAG Agent</h1>

<p align="center">
  <strong>Your AI-powered Document & Web Knowledge Assistant </strong><br>
  Query PDF files or web pages with natural language – powered by LangChain, FAISS, and Ollama.
</p>

<hr>

<h2>📌 Project Overview</h2>

<p>
LangChain RAG Agent is an intelligent Retrieval-Augmented Generation (RAG) system.  
It allows you to <strong>load documents or web pages</strong>, split them into chunks, generate embeddings, and query them in natural language with LLM responses.
</p>

<ul>
  <li>📄 <strong>PDF & Text Loader</strong>: Import local files</li>
  <li>🌐 <strong>Web Loader</strong>: Scrape content from websites</li>
  <li>🔎 <strong>FAISS Vector Store</strong>: Store & retrieve embeddings</li>
  <li>💬 <strong>RetrievalQA</strong>: Ask natural questions and get structured answers</li>
</ul>

<hr>

<h2>🚀 Features</h2>

<ul>
  <li>📚 Document loading from PDF, Text, and Web</li>
  <li>✂️ Automatic chunking & overlap for better context</li>
  <li>🧠 Embeddings with <code>Ollama</code> & <code>all-minilm</code></li>
  <li>🔎 Vector search with <code>FAISS</code></li>
  <li>🤖 LLM responses powered by <code>Ollama</code> (gemma3)</li>
  <li>⚡ End-to-end RAG pipeline</li>
</ul>

<hr>

<h2>🧠 How It Works</h2>

<ol>
  <li>Load a document or web page</li>
  <li>Split content into chunks</li>
  <li>Generate embeddings using Ollama</li>
  <li>Store them in FAISS vector database</li>
  <li>Query via RetrievalQA → get answers + relevant chunks</li>
</ol>

<hr>

<h2>📂 Folder Structure</h2>

<pre>
langchain-rag-agent/
├── RAG chatbot.ipynb        ← Main Colab Notebook
├── requirements.txt          ← Dependencies
└── README.md                 ← Project Documentation
</pre>

<hr>

<h2>⚙️ Setup Instructions</h2>

<ol>
  <li>Clone the repository</li>
  
  <pre><code>git clone https://github.com/yourusername/langchain-rag-agent</code></pre>

  <li>Install dependencies</li>

  <pre><code>pip install -r requirements.txt</code></pre>

  <li>Run the notebook in Google Colab or locally</li>

  <pre><code>jupyter notebook RAG chatbot.ipynb</code></pre>
</ol>

<hr>

<h2>🧪 Sample Queries</h2>

<ul>
  <li><code>What is PydanticAI and why was it created?</code></li>
  <li><code>How is PydanticAI similar to FastAPI?</code></li>
  <li><code>What makes PydanticAI type-safe?</code></li>
  <li><code>Explain streaming and debugging in PydanticAI</code></li>
</ul>

<hr>

<h2>🙌 Credits</h2>

<p>
Created by <strong>Mehadi Hassan</strong> using Python, LangChain, Ollama, and FAISS.
</p>

<hr>

<p align="center">⭐ Star this repo if you find it useful for building RAG applications!</p>
