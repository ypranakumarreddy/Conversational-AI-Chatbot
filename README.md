# Conversational-AI-Chatbot
# 🤖 JSOM Conversational AI Chatbot

A category-aware Conversational AI assistant developed for the **Jindal School of Management (JSOM)** at the **University of Texas at Dallas**. This chatbot allows users to ask natural language questions and receive accurate, structured responses from JSOM's official website content.

---

## 📘 Project Overview

Developed as part of the **BUAN 6390 – Analytics Practicum (Spring 2025)**, this project focuses on simplifying access to academic information using advanced natural language processing techniques. The chatbot integrates:

- Sentence-BERT for semantic understanding  
- FAISS for fast similarity-based search  
- Chainlit for an intuitive user interface  
- Rasa for intelligent dialogue handling  
- Feedback logging to support continuous improvement  

---

## 🧰 Tech Stack

- **Programming Language**: Python  
- **Web Scraping**: BeautifulSoup, Trafilatura  
- **Embeddings**: Sentence-BERT (`all-MiniLM-L6-v2`) via Hugging Face  
- **Similarity Search**: FAISS (Facebook AI)  
- **Conversational Engine**: Rasa SDK  
- **Frontend UI**: Chainlit  
- **Feedback Tracking**: CSV file logging  

---

## 🔄 System Workflow

1. **Scrape & Clean**: Extract content from the JSOM website  
2. **Chunk & Embed**: Split content into chunks and generate embeddings  
3. **Store**: Save embeddings in a FAISS vector database with metadata  
4. **User Query**: 
   - User selects a category and asks a question  
   - Rasa processes the query and retrieves the most relevant information from FAISS  
5. **Feedback**: Optionally collected and saved for further enhancement  

---

## 📚 References

- [Sentence-BERT – Hugging Face](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2)  
- [FAISS – Facebook AI Similarity Search](https://github.com/facebookresearch/faiss)  
- [Rasa](https://rasa.com/)  
- [Chainlit](https://www.chainlit.io/)  
- [Jindal School of Management Website](https://jindal.utdallas.edu)  
