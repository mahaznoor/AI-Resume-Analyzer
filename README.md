# AI Resume Analyzer 🤖

An AI-powered Resume Analyzer built with Python, Flask, and Groq LLM to help users analyze their resumes and get AI-generated insights.

## 🚀 Overview

AI Resume Analyzer is a web-based application that uses Artificial Intelligence and Natural Language Processing (NLP) to analyze resumes and provide useful feedback.

The application allows users to upload their resumes and receive AI-powered analysis to better understand their skills, experience, and professional profile.

## ✨ Features

- 📄 Resume Upload – Upload resumes in PDF and DOCX formats.
- 🤖 AI-Powered Analysis – Analyze resume content using Groq LLM.
- 🧠 NLP-Based Processing – Extract and process relevant resume information.
- 📊 Resume Insights – Generate useful feedback from resume content.
- 🌐 Web Interface – Simple and user-friendly frontend.
- ⚡ Python Flask Backend – Handles resume processing and AI integration.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Backend development |
| Flask | Web framework |
| Groq API | AI-powered analysis |
| NLP | Text processing |
| HTML5 | Frontend structure |
| CSS3 | Styling |
| JavaScript | Frontend functionality |
| PyPDF / DOCX libraries | Resume file processing |

## 📂 Project Structure

```text
AI-Resume-Analyzer/
│
├── backend/
│   ├── app.py
│   ├── requirements.txt
│   └── installRequirements.txt
│
├── frontend/
│   ├── index.html
│   ├── styles.css
│   ├── script.js
│   └── favicon.ico
│
├── tests/
│   └── test_parsing.py
│
├── .gitignore
├── README.md
├── Dockerfile
└── pyproject.toml
```

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/mahaznoor/AI-Resume-Analyzer.git
```

### 2. Open the Project Folder

```bash
cd AI-Resume-Analyzer
```

### 3. Create a Virtual Environment

```bash
python -m venv .venv
```

### 4. Activate Virtual Environment

**Windows PowerShell:**

```powershell
.venv\Scripts\Activate
```

### 5. Install Dependencies

```bash
pip install -r backend/requirements.txt
```

### 6. Configure Groq API

Create a `.env` file inside the `backend` folder.

Add your Groq API credentials:

```env
GROQ_API_KEY=your_groq_api_key
GROQ_MODEL=openai/gpt-oss-120b
```

Get your API key from [Groq Console](https://console.groq.com/).

**Important:** Never upload your `.env` file or API key to GitHub.

### 7. Run the Application

```bash
python backend/app.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000
```

## 📸 Screenshots

Add your application screenshots here to showcase the user interface and resume analysis results.

## 🔮 Future Improvements

- Resume scoring system
- Job description matching
- Skill gap analysis
- ATS compatibility checking
- Personalized career recommendations
- Downloadable AI-generated reports

## 👨‍💻 Developer

**Mahaz Noor**

Computer Science Graduate | Python | AI/ML | NLP | Web Development

- GitHub: [@mahaznoor](https://github.com/mahaznoor)
- Project: [AI Resume Analyzer](https://github.com/mahaznoor/AI-Resume-Analyzer)

---

⭐ If you find this project useful, consider giving it a star!

**Built with Python, AI, and passion for technology.**