# AI Resume Evaluator

A Flask-based AI resume analysis tool that evaluates resumes against job descriptions, detects missing skills, and provides ATS-style scoring and insights.

## Features

- AI-powered resume analysis using Google Gemini
- Text extraction from PDF and DOCX (with optional OCR)
- ATS-style scoring and keyword matching
- Detection of missing skills and gaps
- Timeline and fraud-risk heuristics
- Simple web interface built with Flask templates

---

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/AbhayKishore/AI-Resume-Evaluator/blob/main/LICENSE)

An intelligent, web-based **Resume Evaluation System** built with Flask that helps candidates and reviewers understand how well a resume matches a target role, what is missing, and where improvements can be made.

---

## 🎯 Project Overview

AI Resume Evaluator is designed to make resume screening and optimization more transparent and structured.  
By combining traditional text processing with large-language-model reasoning, it analyzes resumes, compares them to a job description, and surfaces ATS-style scores, missing keywords, soft skills, AI-generated text indicators, and potential timeline inconsistencies.

---

## 🚀 Features

- **Resume Upload**: Upload resumes in PDF or DOCX format.
- **OCR Support**: Extracts text from scanned PDFs using OCR (when available).
- **ATS Scoring**: Generates an ATS-style compatibility score (0–100).
- **Skill & Keyword Matching**: Highlights missing skills and job-specific keywords.
- **Soft Skills Detection**: Identifies key soft skills mentioned in the resume.
- **AI-Content & Fraud Checks**: Heuristics and model-based detection of AI-generated or suspicious content.
- **Report Preview**: Displays a structured analysis page with summaries and breakdowns.
- **Resume Generation**: Creates an improved DOCX resume based on extracted data.

---

## 🛠️ Technology Stack

- **Backend:** Flask (Python)
- **AI Model:** Google Gemini (via `google-generativeai`)
- **Parsing & Documents:** `pdfplumber`, `python-docx`, optional `pytesseract`
- **Frontend:** HTML templates (Jinja2)
- **Sessions:** `Flask-Session`
- **Deployment:** Any WSGI-compatible Python environment

---

## 📁 Installation & Setup

To run this project locally:

1. **Clone the repository:**
   
   ```bash
   git clone https://github.com/AbhayKishore/AI-Resume-Evaluator.git
   ```
   
2. **Navigate into the directory:**
   
   ```bash
    cd AI-Resume-Evaluator
    ```

 3. **Create and activate a virtual environment:**
    
     ```bash
    python -m venv venv
    source venv/bin/activate   # Linux/Mac
    venv\Scripts\activate      # Windows
    ```

4. **Set up environment variables:**
   
 * Copy `.env.example` to `.env` in your project root:

     ```bash
     cp .env.example .env
     ```

   * Open `.env` and paste your actual API keys, database credentials, and other sensitive info.
     
    ```text
    GOOGLE_API_KEY=your_gemini_api_key
    FLASK_SECRET_KEY=your_flask_secret_key
    ```

5. **Install dependencies:**
   
   ```bash
    pip install -r requirements.txt
    ```

6. **Run the Flask application:**
   
   ```bash
    python app.py
    ```

7. **Open your browser:**

Go to http://127.0.0.1:5000 to access the app.

8. **Stop the server (when finished):**

* Press CTRL + C in the terminal to stop the development server and, if desired, deactivate the virtual environment with:
  
   ```bash
  deactivate
  ```

## 📄 License

This project is licensed under the MIT License.

For full details, see the LICENSE file.

---

© 2025 Abhay Kishore
All rights reserved.

Please give proper credit to **Abhay Kishore** when using or referencing this project in any form.

```python
# Copyright (c) 2025 Abhay Kishore
# Licensed under the MIT License
```

---

## 🤝 Contributions
Contributions and suggestions are welcome! Feel free to open issues or submit pull requests to improve the app.
---

## 📞 Contact
For any queries or support, reach out via email:
**Abhay Kishore** – [abhaykishore2004@gmail.com](mailto:abhaykishore2004@gmail.com)
