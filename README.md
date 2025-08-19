# 🚀 RAG-CHATBOT-FOR-NATURAL-LANGUAGE-DATABASE-INTERACTION  

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue)](https://www.python.org/)  
[![Stars](https://img.shields.io/github/stars/MausamRakse/RAG-Chatbot-for-Natural-Language-Database-Interaction?style=social)](https://github.com/MausamRakse/RAG-Chatbot-for-Natural-Language-Database-Interaction/stargazers)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mousam%20Rakse-blue?logo=linkedin)](https://www.linkedin.com/in/mousam-rakse)  
[![Email](https://img.shields.io/badge/Email-Contact%20Me-red?logo=gmail)](mailto:mousamrakse@gmail.com)  

---

## 🧠 About the Project  
A **Retrieval-Augmented Generation (RAG) based chatbot** that allows users to query structured **databases** using **natural language**.  
It leverages **LangChain, LangGraph, and LlamaIndex** to:  
- 🔹 Convert plain English into **SQL queries**  
- 🔹 Fetch relevant database results  
- 🔹 Generate **human-like responses** via LLM  

👉 Making **database access easy, interactive, and conversational** for everyone!  

---

## 🎥 Demo Video  
📺 Watch the demo here → [Demo Video Link](https://drive.google.com/file/d/17ZfOg3d0bUnlLJItj7aNxRNjyTRRzsTj/view?usp=sharing)  

---
✨ Features

🗣️ Natural Language to SQL conversion

🔐 Secure database connection

⚡ Real-time query execution

🌐 Works with multiple SQL databases

🎨 Simple Streamlit UI

👩‍💻 Author

Mousam Rakse
🔗 LinkedIn

📧 Email 
## ⚡ Quick Start  

### ✅ Step 1: Install Requirements  
```bash
pip install -r requirements.txt
✅ Step 2: Configure API Key

Open app.py → Line 12 → Paste your API Key:

genai.configure(api_key="your_API_KEY")

✅ Step 3: Run the Application
streamlit run app.py

✅ Step 4: Enter Database Credentials

Fill in the following:

Host → e.g., localhost

Port → e.g., 3306

Username → your DB username

Password → your DB password

Database Name → target database

✅ Step 5: Connect

Click on “Connect Database” ✅

✅ Step 6: Ask Questions in Plain English

Example:

User: Provide me the total number of students  
Bot: You have 320 students in the database.  

