# 🚀 Arun’s Generative AI Playground  
### *From Hugging Face Transformers to Interactive Chatbots*  

Welcome 👋 This repository contains my work on **Generative AI** using Hugging Face and Gradio.  
It demonstrates how to use **Transformers pipelines** for multiple NLP tasks, and how to build simple AI applications with **Gradio**.  

---

## 🔐 Hugging Face Authentication  

At the start, we connect to Hugging Face using a **secret access token**:  
1. Create a token at 👉 [https://huggingface.co/settings/tokens](https://huggingface.co/settings/tokens)  
2. Copy and paste the token when prompted in the notebook.  
⚠️ **Important:** This token gives access to your account. Keep it private and remove it after use.  

---

## 🧩 Transformers and Pipelines  

Hugging Face `transformers` library provides **pipelines** — high-level APIs to perform NLP tasks easily.  
In this notebook, we use several pipelines:  

### 1. Sentiment Analysis  
- Input: `"I love this movie!"`  
- Output: **POSITIVE**, score = 0.999  

### 2. Text Classification  
- Categorizes text into predefined classes.  

### 3. Summarization  
- Input: Long text  
- Output: Short summary of main points.  

### 4. Translation (English → Hindi)  
- Input: `"How are you?"`  
- Output: `"आप कैसे हैं?"`  

### 5. Question Answering  
- Input: Context + Question  
- Output: The best possible answer from the text.  

---

## 🎨 Gradio Applications  

We also create interactive apps using **Gradio**:  
- **Sentiment Analysis App** – Detects positive/negative text.  
- **Summarizer App** – Summarizes long passages.  
- **Translator App** – English → Hindi.  
- **Q&A App** – Answers based on a passage.  

---

## 💬 Chatbot  

Finally, we build a **chatbot** using Hugging Face + Gradio:  
- Responds to user messages.  
- Uses pipelines like text generation & Q&A.  
- Example of how to make interactive AI systems.  

---

## ⚙️ Tools & Technologies Used  
- **Python** 🐍  
- **Hugging Face Transformers** 🤗  
- **Gradio** 🎨  
- **Jupyter Notebook** 📓  

---

## 📂 File  
- `generative_ai_with_huggingface.ipynb` – Main notebook  

---

## 🎯 Outcome  

By the end, you will:  
- Authenticate & use Hugging Face models  
- Run sentiment analysis, summarization, translation, and Q&A  
- Build NLP apps with Gradio  
- Create a simple chatbot  

---

