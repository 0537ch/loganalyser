# 🧠 Capstone Project: HTTP Log Classification with LLM

This project explores how large language models (LLMs), specifically IBM Granite 8B via Replicate, can classify HTTP request logs as **Benign** or **Malicious**.

### 🔍 Objective
Use LLMs to analyze web traffic logs and detect potentially harmful patterns such as SQL injection, XSS, or unauthorized access attempts.

### 📦 Dataset
- **Source**: CSIC 2010 HTTP Web Log Dataset
- **Format**: Combined HTTP method, URL, and content for each log
- **Labels**: Normal (Benign) vs Attack (Malicious)

### ⚙️ Method
- Prompt-based classification using few-shot learning
- Deployed via Google Colab and LangChain
- Evaluated with precision, recall, F1-score, and confusion matrix

### 📊 Result (Best)
- **Accuracy**: 82%
- **F1-Score (Malicious)**: 74%
- LLM shows promise for flexible, human-like reasoning in security logs

### 🤖 AI Used
- **Model**: `ibm-granite/granite-3.3-8b-instruct`
- **API**: Replicate
- **Support**: LangChain for pipeline integration

---

