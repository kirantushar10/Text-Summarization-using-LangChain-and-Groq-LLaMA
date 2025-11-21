# **⚡️ Text Summarization using LangChain and Groq LLaMA 3.1**

### **🛠️ Technology Stack**

**Groq** (⚡️ High-Speed Inference)  •  **LangChain** (🧩 Framework)  •  **Python 3.10** (🐍 Language)  •  **Llama 3.1 8B** (🧠 LLM)

An end-to-end project demonstrating powerful text summarization techniques using the **LangChain** framework, accelerated by the ultra-fast inference of **Groq**'s Large Language Models (LLMs).

This repository's core is the **TextSummarization.ipynb** Jupyter Notebook, where you can explore and experiment with multiple distinct summarization strategies.

\--- ✨🧠 \---

## **✨ Key Capabilities**

This project offers a comprehensive suite of features for high-performance text summarization:

* **🧠 LLM-Driven Summary Generation:** Powered by Groq’s low-latency **LLaMA-3.1-8B** for extremely fast summaries.  
* **🧩 Multiple Summarization Architectures:** Exploration of diverse strategies, including:  
  * **Direct Prompt Summaries** (Simple Invocation)  
  * **Prompt Template Summaries** (Structured & Custom Output)  
  * **Stuff** (Basic Combine)  
  * **Map-Reduce** (Scalable for Large Docs)  
  * **Refine Pipeline** (Iterative Enhancement)  
* **📄 PDF Document Summarization:** Integration with PyPDFLoader for seamless processing of long-form documents.  
* **🌐 Multilingual Summary Output:** Demonstrated capability to translate the final summary (e.g., to Hindi, French).  
* **⚙️ Token Counting \+ Optimization:** Functions to monitor and manage token usage for efficiency.  
* **🔍 Recursive Chunk Splitting:** Uses RecursiveCharacterTextSplitter to handle texts exceeding the LLM's context window.  
* **🧪 Clean Experimentation:** A fully-reproducible Jupyter Notebook for easy learning and testing.

\--- ⚙️🚀 \---

## **⚙️ Getting Started**

Follow these steps to set up and run the interactive notebook locally.

### **📋 Prerequisites**

* Python (3.10)  
* Jupyter environment (Lab or Notebook)

### **📦 Installation**

1. **Clone the repository:**  
   git clone https://github.com/kirantushar10/Text-Summarization-using-LangChain-and-Groq-LLaMA.git
   cd Text-Summarization-using-LangChain-and-Groq-LLaMA

2. Install dependencies:  
   The required packages are listed in the requirements.txt file.  
   \# Install the necessary libraries  
   pip install \-r requirements.txt

### **🔑 API Key Setup**

1. **Obtain a Key:** Get your free API key from the [Groq Console](https://console.groq.com/).  
2. **Create .env:** In the root directory of this project, create a file named **.env**.  
3. **Add Key:** Paste your API key into the file:  
   GROQ\_API\_KEY="YOUR\_API\_KEY\_GOES\_HERE"

### **▶️ Running the Notebook**

1. **Start Jupyter:**  
   jupyter notebook

2. **Open TextSummarization.ipynb** and execute the cells sequentially to observe the various summarization techniques (simple invocation, prompt templating, and advanced chains).

\--- 📚 \---

## **🧠 Summarization Chains Explained**

The notebook provides practical examples of how to choose the right chain for the job:

| Chain Type | Use Case | Pros | Cons |
| :---- | :---- | :---- | :---- |
| **Stuff** | Short documents, simple tasks. | Simplest, fastest, maintains full context. | Fails on long documents due to token limits. |
| **Map-Reduce** | Very large documents, need bullet points/structure. | Handles huge inputs, summaries are independent and easily parallelized. | Requires two LLM calls (Map \+ Reduce), may lose overall flow/cohesion. |
| **Refine** | Large documents where high accuracy/cohesion is needed. | Maintains full document context sequentially, high-quality final output. | Slowest method, relies heavily on the quality of the refinement prompt. |

\--- 📜 \---

## **📜 License**

This project is licensed under the MIT License \- see the [LICENSE.md](http://docs.google.com/LICENSE.md) file for details.

\--- 🤝 \---

## **🤝 Contribution & Feedback**

Got ideas for another chain or a cleaner prompt structure? We welcome pull requests and issues\!

Fork the repository and share your improvements. Happy summarizing\! 🎉
