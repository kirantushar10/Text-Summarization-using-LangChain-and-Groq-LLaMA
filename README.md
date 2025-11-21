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
  ">📘 <ins>Overview </ins></h3>
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
  ">🛠️ <ins>Setup Instructions</ins></h3>

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

  ```
   1. Launch the Jupyter environment and open the notebook.
   2. jupyter notebook TextSummarization.ipynb
   3. Execute the cells step-by-step to reproduce the entire summarization workflow.
  ```
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
  ">📋 <ins>Project Workflow Overview<ins></h3>
  
  
  <h4>1️⃣ Load the LLM</h4>

  ```
    llm = ChatGroq(model="llama-3.1-8b-instant", groq_api_key=groq_api_key)
  ```

  <h4>2️⃣ Simple Speech Summarisation</h4>
  
  Define a speech text, token-count it, then call the model with a simple prompt:
  
  ```
    llm.invoke(chat_message)
  ```

  <h4>3️⃣ Summarization Using Prompt Templates</h4>
  
  
  ```
    llm_chain = LLMChain(llm=llm, prompt=prompt)
    summary = llm_chain.run({'speech': speech, 'language': 'hindi'})
  ```

  <h4>4️⃣ PDF Summarization</h4>
  
  
  ```
    docs = PyPDFLoader("apjspeech.pdf").load_and_split()
  ```

  <h4>5️⃣ Stuff Chain (Small/Medium Documents)</h4>
  
  
  ```
    output_summary = load_summarize_chain(llm, chain_type='stuff').run(docs)
  ```

  <h4>6️⃣ Map-Reduce Chain (Large Documents)</h4>
  
  
  ```
    output = summary_chain.run(final_documents)
  ```

  <h4>7️⃣  Refine Chain (Iterative Improvement)</h4>
  
  
  ```
    output_summary = refine_chain.run(final_documents)
  ```

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
  ">📝<ins> Use Cases </ins></h3>

  <div>

   Summarizing political speeches, interviews, or long transcripts

  Condensing large PDF reports

  Creating structured summaries for presentations

  Generating multilingual summaries automatically
    
  </div>
  
</div>
