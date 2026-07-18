<h1 align="center">AI Tutor – RAG & LLM Powered Chatbot</h1>

<p align="center">
  A document-aware AI tutor built using <b>Retrieval-Augmented Generation (RAG)</b> and
  <b>Large Language Models (LLMs)</b> for accurate, context-grounded question answering.
</p>

<hr/>

<h2>📌 Project Description</h2>

<p>
This project implements an <b>AI Tutor</b> that allows users to upload PDF documents and ask
natural language questions. Instead of relying solely on an LLM’s internal knowledge,
the system retrieves relevant information from the document and generates answers
strictly grounded in that content.
</p>

<p>
The architecture significantly reduces hallucinations and makes the chatbot suitable
for educational, research, and enterprise document-based use cases.
</p>

<hr/>

<h2>✨ Key Capabilities</h2>

<ul>
  <li>PDF-based question answering</li>
  <li>Retrieval-Augmented Generation (RAG) pipeline</li>
  <li>LLM-powered reasoning and response generation</li>
  <li>Multi-tool extensible design</li>
  <li>Thread-based conversational sessions</li>
  <li>Clean and interactive Streamlit UI</li>
</ul>

<hr/>

<h2>🧠 System Workflow</h2>

<pre>
PDF Upload
   → Document Chunking
   → Embeddings Generation
   → Vector Retrieval (RAG)
   → LLM Reasoning
   → Context-Aware Answer
</pre>

<hr/>

<h2>🛠️ Technology Stack</h2>

<table>
  <tr>
    <th align="left">Layer</th>
    <th align="left">Technology</th>
  </tr>
  <tr>
    <td>Language</td>
    <td>Python</td>
  </tr>
  <tr>
    <td>Frontend</td>
    <td>Streamlit</td>
  </tr>
  <tr>
    <td>LLMs</td>
    <td>OpenAI / Gemini / Hugging Face (pluggable)</td>
  </tr>
  <tr>
    <td>Retrieval</td>
    <td>Embeddings + Vector Store</td>
  </tr>
  <tr>
    <td>Architecture</td>
    <td>Modular & Scalable</td>
  </tr>
</table>

<hr/>

<h2>📂 Project Structure</h2>

<pre>
├── backend/
│   ├── ingest_pdf.py
│   ├── retriever.py
│   ├── llm_handler.py
│   └── tools.py
├── frontend/
│   └── app.py
├── data/
├── requirements.txt
└── README.md
</pre>

<hr/>

<h2>🚀 Running the Application</h2>

<pre>
git clone https://github.com/Subham837/Rag-and-LLM-powered-AI-chatbot.git
cd Rag-and-LLM-powered-AI-chatbot

python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate

pip install -r requirements.txt
streamlit run app.py
</pre>

<hr/>

<h2>🎯 Use Cases</h2>

<ul>
  <li>AI-powered tutoring systems</li>
  <li>PDF and document-based assistants</li>
  <li>Enterprise knowledge-base chatbots</li>
  <li>Academic and research RAG experiments</li>
</ul>

<hr/>

<h2>👤 Author</h2>

<p>
<b>Subham Pradhan</b><br/>
Machine Learning & AI Enthusiast<br/>
GitHub: <a href="https://github.com/Subham837">https://github.com/Subham837</a>
</p>

<hr/>

<p align="center">
⭐ If you find this project useful, consider starring the repository.
</p>
