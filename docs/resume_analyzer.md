# Resume Analyzer

An intelligent tool to parse, extract, and analyze resumes for automated screening and shortlisting of candidates.

---

## ✨ Project Overview

The Resume Analyzer is an end-to-end system that:
- Parses resumes (PDF/DOCX)
- Extracts structured information using NLP
- Classifies or ranks candidates based on job-fit
- Exposes results via web interface or API

---

## 📁 Features (Planned & In Progress)

### ✅ Resume Parsing
- [ ] Support for PDF, DOCX, and TXT
- [ ] Convert documents to raw text
- [ ] Extract sections like "Education", "Experience", "Skills"

### ✅ Named Entity Recognition (NER)
- [ ] Use spaCy / custom NER model to extract:
  - Name, Email, Phone
  - Degrees, Skills, Universities
  - Job Titles, Companies, Duration

### ✅ Skill Matching
- [ ] Keyword/skill matching against job description
- [ ] Custom weightage for preferred skills

### ✅ Candidate Ranking
- [ ] Scoring algorithm based on:
  - Education relevance
  - Experience match
  - Skill overlap
- [ ] Use ML model (XGBoost / Logistic Regression / BERT scoring)

### ✅ Output Format
- [ ] Structured JSON
- [ ] CSV export for bulk analysis
- [ ] Streamlit or Flask dashboard

### ✅ UI / API Integration
- [ ] Web interface with file upload
- [ ] REST API to return parsed resume data

---

## ⚙️ Tech Stack

- Python (NLP, Text Parsing)
- spaCy / BERT / Custom NER
- Streamlit / Flask
- MySQL or MongoDB for storage
- GitHub Actions for CI/CD (planned)

---

## 🚀 Future Enhancements

- Support multilingual resumes
- Add feedback loop to improve model
- Integrate with ATS (Applicant Tracking Systems)
