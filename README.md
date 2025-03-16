# 📄 Chat with PDF - AI-Powered PDF Assistant

This project enables users to **chat with PDFs** using AI-powered **Natural Language Processing (NLP)** models. Users can upload a PDF and interact with its contents through conversational AI. The project leverages **LangChain, Unstructured, OpenAI, and Groq** to parse, process, and generate intelligent responses based on the document's content.

## 🚀 Features
- **Upload a PDF** and extract structured content (text, tables, images).
- **Conversational AI** to interact with the PDF like a chatbot.
- **Summarization, Q&A, and contextual understanding** of the document.
- **Support for text-based and scanned PDFs** (OCR-enabled).
- **Integrates OpenAI & Groq models** for fast, accurate responses.

## 🛠️ Technologies Used
- **LangChain** 🧠 - Framework for building AI-powered conversational agents.
- **Unstructured** 📄 - Extracts content from complex PDFs (tables, text, images).
- **OpenAI API** 🤖 - Provides LLM-based responses (GPT models).
- **Groq API** 🚀 - Optimized LLM inference for fast response times.
- **Tesseract OCR** 🔍 - Handles scanned PDFs (if needed).


## 🔑 API Configuration
Set up your OpenAI and Groq API keys:
```sh
export OPENAI_API_KEY='your-openai-api-key'
export GROQ_API_KEY='your-groq-api-key'
```
Or create a `.env` file:
```sh
OPENAI_API_KEY=your-openai-api-key
GROQ_API_KEY=your-groq-api-key
```

## 📜 Usage
### **1️⃣ Run the Chatbot**

### **2️⃣ Upload & Chat with a PDF**
1. Upload a PDF.
2. Ask questions like:
   - "Summarize this document."
   - "What are the key points in Section 2?"
   - "Find financial data in this report."


