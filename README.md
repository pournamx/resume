# AI Resume Analyzer & Career Coach

A production-quality AI-powered resume analyzer, ATS scorer, and career development planner built with Python, Streamlit, and Google Gemini AI.

## Demo

[![Watch the demo video](https://img.shields.io/badge/Watch-Demo%20Video-blue?style=for-the-badge)](./videos/Screen%20Recording%202026-06-18%20220638.mp4)

## Quickstart (Windows PowerShell)

```powershell
# Enter the project folder
cd "C:/Users/pourn/OneDrive/Desktop/VS Code/Study AI/studybuddy-ai"

# Activate virtual environment
.\venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
```

## Features
- **File Parsing**: Auto-extract text from PDF and DOCX files.
- **ATS Compatbility Scorer**: 0–100 score breakdown across formatting, keywords, experience, projects, and education.
- **Missing Skills Detection**: Compares your resume to target roles or descriptions.
- **ATS Resume Rewriter**: Generates optimized summaries, categorized skills, and impact-driven experience bullets.
- **Career Coach Roadmap**: Suggested roles, learning paths, and an interactive 30-day week-by-week timeline checklist.
- **Mock Interview Prep**: Custom technical and HR questions tailored to your profile.
- **SQLite History Log**: Track scores and comparisons across resume revisions.

## Configuration
Add your Gemini API key inside the local `.env` file as `GEMINI_API_KEY`, or input it directly in the Streamlit sidebar when running the app.
