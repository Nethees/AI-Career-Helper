# 🧠 AI Career Coach – Resume Analyzer & QA System

This is a Flask-based web application that uses **LangChain**, **OpenAI's GPT-3.5**, and **FAISS** to:
- Extract and summarize key aspects from a user's resume PDF
- Let users ask career-related questions based on their resume contents

---

## 🚀 Features

- ✅ Upload your resume (PDF)
- ✅ Extract and summarize:
  - Career Objective
  - Skills and Expertise
  - Work Experience
  - Education
  - Notable Achievements
- ✅ Ask career-related questions using Retrieval-based QA
- ✅ FAISS-based vector search on resume content
- ✅ Built with OpenAI, HuggingFace, and LangChain

---

## 🏗️ Tech Stack

- `Flask` (Web App Framework)
- `PyPDF2` (PDF Text Extraction)
- `LangChain` (Prompting & Retrieval Chain)
- `FAISS` (Vector Search for QA)
- `HuggingFace Embeddings` (Document Embeddings)
- `OpenAI` (LLM for summary and QA)
- `dotenv` (for managing API keys)

---