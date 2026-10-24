# AI Resume Analyzer 📄

A Python and Flask-based web application that analyzes resumes against job requirements and helps users identify relevant skills and keywords.

## 🚀 Features

- Upload resumes in PDF and DOCX formats.
- Extract text from uploaded resumes.
- Analyze resume keywords against job requirements.
- Calculate a resume match score based on keyword matching.
- Display analysis results through a simple, user-friendly interface.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Web Framework:** Flask
- **Frontend:** HTML, CSS
- **PDF Processing:** PyPDF2
- **DOCX Processing:** python-docx

## 📁 Project Structure

```text
AI-Resume-Analyzer/
├── app.py
├── requirements.txt
├── .gitignore
├── templates/
│   └── index.html
└── static/
    └── style.css
```

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/mayuri1912004/AI-Resume-Analyzer.git
cd AI-Resume-Analyzer
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
python app.py
```

Open the local URL displayed in your terminal, usually `http://127.0.0.1:5000`.

## 💡 How It Works

1. Upload your resume in PDF or DOCX format.
2. Enter the job description or required skills.
3. Submit the details for analysis.
4. Review the resume match score and relevant keywords.

## 🎯 Project Objective

The goal of this project is to help job seekers compare their resumes with job requirements and identify skills or keywords they may need to improve.

## 👩‍💻 Author

**Mayuri Kamble**

GitHub: [mayuri1912004](https://github.com/mayuri1912004)

---

*Note: The analysis score is based on the matching logic implemented in the application. It is not a guarantee of ATS selection or job placement.*
