<<<<<<< HEAD
# LLM_ChatBot
=======
<<<<<<< HEAD
# LLM_ChatBot
=======


# 🚀 **Chatbot using RAG, LangChain, and Streamlit** 🤖  

This repository contains a **chatbot application** built using **Retrieval-Augmented Generation (RAG)** concepts, **LangChain** libraries, and a touch of **prompt engineering**. The chatbot leverages the **Cohere API** to enhance its generative capabilities and features a user-friendly **Streamlit interface**.

---

## 🎯 **Features**

✅ **Document Upload Support**: Users can upload **PDF** or **Word files** etc. The chatbot extracts relevant information from the documents.  
✅ **Query Answering**: Intelligent answers to user queries using the **RAG** approach.  
✅ **LangChain Integration**: Document processing, chunking, and retrieval.  
✅ **Prompt Engineering**: Fine-tuned prompts for accurate responses.  
✅ **Streamlit UI**: Simple and intuitive **web-based interface**.  
✅ **Cohere API**: Enhanced natural language understanding and response generation.  

---

## 🛠️ **Technologies Used**

- 🐍 **Python**  
- 🧠 **LangChain**  
- 🌐 **Streamlit**  
- ✨ **Cohere API**  
- 📄 **PyPDF**  

---

## ⚙️ **Setup Instructions**

Follow these steps to set up and run the chatbot locally:

### **1️⃣ Clone the Repository**

```bash
git clone <repository-url>
cd <repository-folder>
```

---

### **2️⃣ Install Dependencies**

Install all required libraries from the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

---

### **3️⃣ Get the Cohere API Key 🔑**

1. Visit [Cohere's website](https://cohere.ai/) to create an account and get an API key.  
2. Save the API key securely into a `.env` file in the main directory like below — it will be required to run the chatbot.
```bash
COHERE_API_KEY=YOUR-API-KEY
```

---

### **4️⃣ Run the Chatbot 💻**

Launch the Streamlit interface using the following command:

```bash
streamlit run rag/app.py
```

✅ This will open the chatbot interface in your **default web browser**.

---

## ⚡ **How It Works**

1. **📥 Upload Documents**:  
   - Users upload PDFs or Word files through the Streamlit interface.  
   - Files are processed, and content is split into chunks using **LangChain** tools.

2. **💡 Query Processing**:  
   - Queries are matched to the most relevant document chunks (**retrieval** step).  
   - The retrieved content is passed to the **Cohere API** for final response generation (**generation** step).

3. **📝 Response**:  
   - The chatbot provides intelligent and **context-aware answers** based on the uploaded documents.

---

## 📂 **Folder Structure**

```plaintext
.
├── rag/app.py             # 🚀 Main Streamlit application
├── requirements.txt       # 📋 Required dependencies
├── README.md              # 📖 Project documentation

```






---

Enjoy exploring the chatbot! 🚀✨
>>>>>>> 581c395 (commit)
>>>>>>> 561f544 (intial commit)
