# 🌍 Language Translator using Ollama + Streamlit

This is a simple **AI-powered Language Translator** built with [Streamlit](https://streamlit.io/) and [LangChain](https://www.langchain.com/).  
It uses the **Ollama LLaMA 3.1 (8B)** model to translate text into different languages.  

---

## 🚀 Features
- Translate text or sentences into any target language  
- Built using **LangChain** with a prompt chain (Prompt → Model → Output Parser)  
- Simple and interactive **Streamlit UI**  
- Runs locally with Ollama  

---

## 🛠 Tech Stack
- **Python 3.10+**  
- **Streamlit** – for the user interface  
- **LangChain** – for prompt management and chaining  
- **LangChain Community** – for LLM integrations like Ollama  
- **Ollama** – to run LLaMA models locally  

---

## 📦 Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/your-username/ai-translator.git
cd ai
```

### 2. Create and activate a virtual environment
```bash
python -m venv .venv
.venv\Scripts\activate   # On Windows
source .venv/bin/activate   # On Mac/Linux
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Install and run Ollama
Download Ollama from 👉 https://ollama.ai
Pull the LLaMA 3.1 8B model:
```bash
ollama pull llama3.1:8b
```

### 5. Run the Streamlit app
```bash
streamlit run app.py
```

