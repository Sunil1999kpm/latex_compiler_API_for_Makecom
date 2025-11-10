# 📄 LaTeX Compiler API

A lightweight Flask-based microservice that compiles LaTeX code into PDF files.  
This API accepts raw LaTeX input or JSON payloads and returns the generated PDF.  
Deployed on **Render** and easily usable by any frontend, AI model, or automation script.

---

## 🚀 Features

- Accepts both `GET` (test endpoint) and `POST` (compilation request)
- Converts LaTeX code into a downloadable PDF
- Built with Flask and integrated with a Hugging Face model for compilation
- Supports JSON or raw LaTeX payloads
- Deployed on [Render.com](https://render.com) for public access

---

## 🧩 API Endpoints

### **GET /**
Returns a basic message confirming the API is live.

```bash
curl https://latex-bridge.onrender.com/
