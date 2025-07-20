````markdown
# Resume Parser Web App

A simple Flask app that extracts structured JSON (name, contact, education, experience, skills) from PDF/DOCX resumes using OpenAI.

## 🚀 Quick Start

1. Clone & install:
   ```bash
   git clone https://github.com/yourusername/resume-parser-webapp.git
   cd resume-parser-webapp
   pip install -r requirements.txt
````

2. Set API key:

   ```bash
   export OPENAI_API_KEY="your_key_here"
   ```
3. Run:

   ```bash
   flask run --port=8000
   ```
4. Open `http://localhost:8000`, upload a resume, and view the JSON output.

## 📂 Structure

* `app.py` – Flask routes & upload handling
* `resumeparser.py` – PDF/DOCX text extraction & OpenAI parsing
* `templates/index.html` – upload form & results


