# ⚡️ Text Summarization using LangChain and Groq LLaMA 3.1

<div align="center">

<i>✨ Ultra-fast text summarization with Groq LLaMA + LangChain — PDFs, chunking, and multilingual summaries made easy ✨</i>

---
  
### 🚀 **PDF Loader** • 🧩 **Summarization Chains** • ⚡ **Groq LLaMA 3.1** • 🔡 **Token Counting** • 📊 **Chunking & Optimization** • 🌐 **Multilingual Output**


  <img src="https://img.shields.io/badge/Python-3.10+-blue" />
  <img src="https://img.shields.io/badge/LangChain-Framework-orange" />
  <img src="https://img.shields.io/badge/Groq-LLaMA_3.1_8B-green" />
  <img src="https://img.shields.io/badge/Text_Summarization-purple" />
  <img src="https://img.shields.io/badge/Status-Active-brightgreen" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-red" />


  🔗 <strong>GitHub Repository:</strong><br>
  <a href="https://github.com/kirantushar10/Text-Summarization-using-LangChain-and-Groq-LLaMA">
    https://github.com/kirantushar10/Text-Summarization-using-LangChain-and-Groq-LLaMA
  </a>
</div>

---

<!-- OVERVIEW - CSS STYLED CARD WITH ITALIC PARAGRAPHS -->
<div>
  <h3 style="
    margin: 0 0 10px 0;
    color: #0ea5e9;
    font-size: 18px;
    font-weight: 700;
    display: flex;
    align-items: center;
    gap: 8px;
  ">📘 Overview</h3>
  <i> 
  <p style="margin: 8px 0; font-size: 14.5px; line-height: 1.65; font-style: italic;">
      ⚡ Ultra-fast text summarization powered by Groq LLaMA 3.1, supporting multiple LangChain pipelines such as Stuff, Map-Reduce, and Refine.
  </p>

  <p style="margin: 8px 0; font-size: 14.5px; line-height: 1.65; font-style: italic;">
      📄 Handles PDF document summarization with PyPDFLoader and uses recursive chunk splitting for long documents.
  </p>

  <p style="margin: 8px 0; font-size: 14.5px; line-height: 1.65; font-style: italic;">
      🌍 Generates multilingual summaries (Hindi, French, and more) and includes token usage tracking for optimization.
  </p>

  <p style="margin: 8px 0 0 0; font-size: 14.5px; line-height: 1.65; font-style: italic;">
      📓 Designed for clean, reproducible Jupyter Notebook workflows and ideal for developers or researchers exploring LLM-based summarization.
  </p>
  </i>

</div>

---
<div> 

  <h3 style="
    margin: 0 0 10px 0;
    color: #0ea5e9;
    font-size: 18px;
    font-weight: 700;
    display: flex;
    align-items: center;
    gap: 8px;
  ">🛠️ Setup Instructions</h3>

  To get started with this project, follow the steps below.

  <h4>1️⃣ Clone the Repository</h4>

  ```
    git clone https://github.com/kirantushar10/Text-Summarization-using-LangChain-and-Groq-LLaMA.git
    cd Text-Summarization-using-LangChain-and-Groq-LLaMA
  ```

 <h4>2️⃣ Create & Activate a Virtual Environment</h4>


It is highly recommended to use a virtual environment to manage dependencies.
```
python -m venv venv
```

For Mac/Linux:
```
source venv/bin/activate
```
For Windows (Command Prompt):
```
venv\Scripts\activate
```
 <h4>3️⃣ Install Dependencies</h4>


Install all necessary libraries using the provided requirements.txt file.
```
pip install -r requirements.txt
```
 <h4>4️⃣ Set up Environment Variables</h4>

Create a file named .env in the project root and add your Groq API key:
```
GROQ_API_KEY = "your_api_key_here"
```

(You must register for the Groq API and obtain a key from their console.)

 <h4>5️⃣ Run the Notebook</h4>


Launch the Jupyter environment and open the notebook.

<div class="code-block">
<span class="command">jupyter notebook TextSummarization.ipynb</span>
</div>

Execute the cells step-by-step to reproduce the entire summarization workflow.


</div>
