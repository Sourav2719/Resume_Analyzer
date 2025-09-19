# 📄 Resume Analyzer  

![Python](https://img.shields.io/badge/Python-3.7%2B-blue)  
![License](https://img.shields.io/badge/License-MIT-green)  
![Contributions](https://img.shields.io/badge/Contributions-Welcome-orange)  

An **AI-powered Resume Analyzer** that extracts and evaluates key details from resumes, providing **structured insights** on skills, education, and experience. This tool helps candidates **optimize their resumes** and recruiters **screen resumes faster**.  

---

## ✨ Features  

✅ **Multi-format Support** – Upload resumes in `.pdf`, `.docx`, or `.txt`  
✅ **Skill Extraction** – Detects both technical and soft skills from the resume  
✅ **Experience Parsing** – Identifies job roles, years of experience, and industries  
✅ **Education Analysis** – Extracts degree, college, and graduation year  
✅ **Keyword Matching** – Matches resume keywords with job description keywords  
✅ **Scoring System** – Gives a percentage match score with the desired role  
✅ **Visualization** – Summarizes results in an easy-to-read format (JSON/Text)  

---

## 🚀 Getting Started  

### 1️⃣ Prerequisites  
- Python 3.7+  
- `pip` for dependency management  

### 2️⃣ Installation  

Clone this repo:  
```bash
git clone https://github.com/Sourav2719/Resume_Analyzer.git
cd Resume_Analyzer
```
Create and activate virtual environment
``` bash
python -m venv venv
# Windows
venv\Scripts\activate
# Mac/Linux
source venv/bin/activate
```
Install dependencies:
```bash
pip install -r requirements.txt
```
Usage:
```bash
python analyze.py --input resume.pdf --jobdesc jd.txt --output result.json
```
Example:
```bash
python analyze.py --input samples/resume1.pdf --jobdesc samples/jobdesc.txt
```
Output(JSON):
```bash
{
  "Name": "John Doe",
  "Email": "john.doe@example.com",
  "Skills": ["Python", "Machine Learning", "Data Analysis"],
  "Experience": "3 years",
  "Education": "B.Tech in Computer Science, 2021",
  "Match Score": "82%"
}
```
### Project Structure:
```bash
Resume_Analyzer/
├── App/                  # Main application code (UI + logic)
├── pyresparser/          # Resume parsing engine
├── AI-Resume-Analyzer/   # Supporting scripts
├── samples/              # Sample resumes and job descriptions
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```



