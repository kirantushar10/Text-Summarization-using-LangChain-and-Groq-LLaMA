<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Text Summarization using LangChain and Groq LLaMA 3.1 — README</title>
  <style>
    :root{
      --bg:#ffffff;
      --muted:#6b7280;
      --accent:#0ea5a4;
      --divider:#e6e6e6;
      --container-width:900px;
      --mono: "SFMono-Regular", Menlo, Monaco, "Roboto Mono", "Courier New", monospace;
    }
    html,body{height:100%;margin:0;background:var(--bg);color:#111827;font-family:Inter,system-ui,-apple-system,"Segoe UI",Roboto,"Helvetica Neue",Arial;}
    .wrap{max-width:var(--container-width);margin:28px auto;padding:28px;background:#fff;border-radius:10px;box-shadow:0 6px 18px rgba(15,23,42,0.06);}
    header h1{font-size:1.8rem;margin:0 0 8px;display:flex;align-items:center;gap:.6rem}
    header .subtitle{color:var(--muted);margin:4px 0 18px;font-size:0.98rem}
    .badges img{height:22px;margin-right:8px;margin-bottom:8px}
    a.repo{display:inline-block;color:#0b63ff;text-decoration:none;margin-top:10px}
    .section{margin:22px 0;padding:18px;border-radius:8px}
    .divider{display:flex;align-items:center;gap:12px;justify-content:center;color:var(--muted);font-weight:600}
    .big-divider{border-top:4px solid var(--divider);margin:26px 0;padding-top:18px}
    pre{background:#0f1724;color:#e6eef8;padding:12px;border-radius:8px;overflow:auto;font-family:var(--mono);font-size:0.95rem}
    table{width:100%;border-collapse:collapse;margin-top:12px}
    table th, table td{padding:10px;border:1px solid #e9eef2;text-align:left}
    table th{background:#f3f4f6}
    ul{margin:8px 0 0 20px}
    .center{text-align:center}
    .footer{font-size:0.9rem;color:var(--muted);margin-top:18px}
    code.inline{background:#f3f4f6;padding:2px 6px;border-radius:6px;font-family:var(--mono);font-size:0.92em}
    .hero-badges{display:flex;flex-wrap:wrap;gap:8px;align-items:center}
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <h1>⚡️ Text Summarization using LangChain and Groq LLaMA 3.1</h1>
      <div class="subtitle">An end-to-end project demonstrating powerful text summarization techniques using LangChain and Groq LLMs.</div>
    </header>

    <section class="section center">
      <div class="hero-badges">
        <strong>🚀 LangChain</strong> • <strong>⚡ Groq LLaMA 3.1</strong> • <strong>📄 PDF Loader</strong> • <strong>🧩 Summarization Chains</strong> • <strong>🔡 Token Counting</strong> • <strong>📊 Chunking &amp; Optimization</strong>
      </div>
      <div style="margin-top:12px" class="badges">
        <img src="https://img.shields.io/badge/Python-3.10+-blue" alt="Python 3.10+">
        <img src="https://img.shields.io/badge/LangChain-Framework-orange" alt="LangChain Framework">
        <img src="https://img.shields.io/badge/Groq-LLaMA_3.1_8B-green" alt="Groq LLaMA 3.1 8B">
        <img src="https://img.shields.io/badge/Text_Summarization-purple" alt="Text Summarization">
        <img src="https://img.shields.io/badge/Status-Active-brightgreen" alt="Status Active">
        <img src="https://img.shields.io/badge/Jupyter-Notebook-red" alt="Jupyter Notebook">
      </div>

      <div style="margin-top:12px">
        <a class="repo" href="https://github.com/kirantushar10/Text-Summarization-using-LangChain-and-Groq-LLaMA" target="_blank" rel="noopener noreferrer">
          🔗 GitHub Repository: https://github.com/kirantushar10/Text-Summarization-using-LangChain-and-Groq-LLaMA
        </a>
      </div>
    </section>

    <div class="big-divider"></div>

    <div class="section">
      <div class="divider">━ 🛠️ TECHNOLOGY STACK ━</div>
      <ul>
        <li>⚡ <strong>Groq</strong> — High-speed inference</li>
        <li>🧩 <strong>LangChain</strong> — LLM orchestration</li>
        <li>🐍 <strong>Python 3.10</strong> — Backend language</li>
        <li>🧠 <strong>LLaMA 3.1 8B</strong> — Fast, optimized LLM</li>
      </ul>
      <p style="margin-top:12px">This project demonstrates multiple <strong>text summarization techniques</strong> inside the interactive <code class="inline">TextSummarization.ipynb</code> notebook.</p>
    </div>

    <div class="big-divider"></div>

    <div class="section">
      <div class="divider">━ ✨ KEY CAPABILITIES ━</div>

      <h3>🧠 Ultra-Fast LLM Summaries</h3>
      <p>Powered by <strong>Groq’s LLaMA-3.1-8B</strong>.</p>

      <h3>🧩 Summarization Architectures</h3>
      <ul>
        <li>Direct Prompt Summaries</li>
        <li>Prompt Template Summaries</li>
        <li>Stuff</li>
        <li>Map-Reduce</li>
        <li>Refine</li>
      </ul>

      <h3>📄 PDF Document Summarization</h3>
      <p>Extract & summarize long PDFs using <strong>PyPDFLoader</strong>.</p>

      <h3>🌐 Multilingual Support</h3>
      <p>Translate summaries into Hindi, French, and more.</p>

      <h3>⚙️ Token Counting Tools</h3>
      <p>Monitor and optimize LLM usage.</p>

      <h3>🔍 Smart Chunk Splitting</h3>
      <p>Handle large texts via <strong>RecursiveCharacterTextSplitter</strong>.</p>

      <h3>🧪 Clean Experiment Notebook</h3>
      <p>Fully reproducible & beginner-friendly.</p>
    </div>

    <div class="big-divider"></div>

    <div class="section">
      <div class="divider">━ ⚙️ GETTING STARTED ━</div>
      <h4>📋 Prerequisites</h4>
      <ul>
        <li>Python 3.10</li>
        <li>Jupyter Notebook / JupyterLab</li>
      </ul>
    </div>

    <div class="big-divider"></div>

    <div class="section">
      <div class="divider">━ 📦 INSTALLATION ━</div>

      <h4>1️⃣ Clone the Repository</h4>
      <pre><code>git clone https://github.com/kirantushar10/Text-Summarization-using-LangChain-and-Groq-LLaMA.git
cd Text-Summarization-using-LangChain-and-Groq-LLaMA</code></pre>

      <h4>2️⃣ Install Dependencies</h4>
      <pre><code>pip install -r requirements.txt</code></pre>
    </div>

    <div class="big-divider"></div>

    <div class="section">
      <div class="divider">━ 🔑 API KEY SETUP ━</div>
      <ol>
        <li>Get your <strong>Groq API Key</strong></li>
        <li>Create a <code class="inline">.env</code> file</li>
        <li>Insert:
          <pre><code>GROQ_API_KEY="YOUR_API_KEY_GOES_HERE"</code></pre>
        </li>
      </ol>
    </div>

    <div class="big-divider"></div>

    <div class="section">
      <div class="divider">━ ▶️ RUNNING THE NOTEBOOK ━</div>

      <p>Start Jupyter:</p>
      <pre><code>jupyter notebook</code></pre>

      <p>Open <code class="inline">TextSummarization.ipynb</code> and explore:</p>
      <ul>
        <li>Simple prompts</li>
        <li>Prompt templates</li>
        <li>Map-Reduce</li>
        <li>Refine pipeline</li>
        <li>Chunking</li>
        <li>PDF workflows</li>
      </ul>
    </div>

    <div class="big-divider"></div>

    <div class="section">
      <div class="divider">━ 🧠 SUMMARIZATION CHAINS EXPLAINED ━</div>

      <table>
        <thead>
          <tr>
            <th>Chain Type</th>
            <th>Use Case</th>
            <th>Pros</th>
            <th>Cons</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td><strong>Stuff</strong> ✏️</td>
            <td>Short documents</td>
            <td>Fastest, simplest</td>
            <td>Fails on long docs</td>
          </tr>
          <tr>
            <td><strong>Map-Reduce</strong> 📚➡️📌</td>
            <td>Large documents</td>
            <td>Scalable, parallel</td>
            <td>May lose cohesion</td>
          </tr>
          <tr>
            <td><strong>Refine</strong> 🎯</td>
            <td>High-quality summaries</td>
            <td>Sequentially detailed</td>
            <td>Slowest</td>
          </tr>
        </tbody>
      </table>
    </div>

    <div class="big-divider"></div>

    <div class="section">
      <div class="divider">━ 📜 LICENSE ━</div>
      <p>Licensed under the <strong>MIT License</strong>.</p>
    </div>

    <div class="big-divider"></div>

    <div class="section">
      <div class="divider">━ 🤝 CONTRIBUTION &amp; FEEDBACK ━</div>
      <p>We welcome:</p>
      <ul>
        <li>💡 Ideas</li>
        <li>🛠️ Enhancements</li>
        <li>🔄 Pull requests</li>
        <li>🐛 Issues</li>
      </ul>
      <p class="center" style="margin-top:12px;font-weight:600">🎉 <span style="font-size:1.05em">Happy Summarizing!</span> 📚✨</p>
    </div>

    <div class="footer center">
      <p>Generated from the README content — converted to HTML. Repository: <a href="https://github.com/kirantushar10/Text-Summarization-using-LangChain-and-Groq-LLaMA" target="_blank" rel="noopener noreferrer">github.com/kirantushar10/Text-Summarization-using-LangChain-and-Groq-LLaMA</a></p>
    </div>
  </div>
</body>
</html>
