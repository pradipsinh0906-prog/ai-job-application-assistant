# AI Job Application Assistant

AI-powered job application analyzer built with n8n, Groq AI, and Google Sheets. This workflow automates resume screening and job matching to streamline the application process.

## 🚀 Features

- **Resume Extraction**: Automatically extracts text from uploaded resume PDFs
- **AI-Powered Analysis**: Uses Groq AI to analyze candidate fit against job descriptions
- **Match Scoring**: Generates a numerical match score (0-100) based on skills alignment
- **ATS Keyword Detection**: Identifies missing keywords that could affect ATS screening
- **Cover Letter Generation**: Auto-generates personalized cover letters
- **Google Sheets Integration**: Logs all results (score, strengths, gaps, keywords) for tracking

## 🛠️ Tech Stack

- **n8n** - Workflow automation platform
- **Groq AI** - LLM for application analysis and content generation
- **Google Sheets API** - Data logging and tracking

## 📋 Workflow Steps

1. **Job Application Form** - Captures job description and resume upload
2. **Extract Resume PDF** - Parses resume content from PDF
3. **Normalize Inputs** - Cleans and formats data for AI processing
4. **Analyze Application** - AI evaluates fit, generates match score, identifies gaps
5. **Save to Google Sheet** - Stores structured results for review

## 📸 Workflow Diagram

<img width="1863" height="408" alt="n8n_workflow" src="https://github.com/user-attachments/assets/c394027b-3bdd-48a2-8576-77b507e8a5f7" />

## 📂 Files

- `workflow.json` - Exportable n8n workflow configuration

## 👤 Author

Pradipsinh Jadeja
