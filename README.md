# AI-Resume-Analyzer-Real-Time-Job-Finder
AI Resume Analyzer + Real-Time Job Finder is an AI automation workflow that analyzes a candidate’s resume, identifies suitable job roles, searches for relevant job vacancies, ranks jobs based on resume compatibility, and sends personalized job recommendations through Gmail.

## 🚀 Project Overview

The workflow automates the job-search process using AI and n8n.

Automates: resume upload → AI resume analysis → real-time job search → AI job ranking → Gmail notification of matches.

Instead of manually reading a resume and searching for jobs, the system:

1. Collects the candidate's information and resume.
2. Extracts text from the uploaded PDF.
3. Uses Google Gemini to analyze the resume.
4. Identifies suitable job roles.
5. Searches for relevant job vacancies.
6. Uses AI to compare jobs with the candidate's profile.
7. Calculates and ranks job matches.
8. Creates an HTML job recommendation report.
9. Sends the results to the candidate through Gmail.

## 🏗️ Workflow Architecture

```text
Form Submission
       ↓
Extract Resume PDF
       ↓
AI Resume Analyzer
       ↓
Resume Profile
       ↓
Job Search API
       ↓
Split Jobs
       ↓
AI Job Ranker
       ↓
Match Job + Ranking
       ↓
Sort by Match Score
       ↓
Top Job Recommendations
       ↓
HTML Report
       ↓
Gmail
