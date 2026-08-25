# AI Job Application Analyzer

An AI-powered web application that analyzes a candidate's resume against a job description and provides job-fit insights, skill matching, text similarity, and AI-generated recommendations.

## Features

- Upload a resume in PDF format
- Paste a job description
- Extract resume text automatically
- Calculate text similarity between resume and job description
- Identify matched and missing skills
- Generate AI-powered analysis using Google Gemini
- Provide personalized improvement suggestions
- View extracted resume text
- Professional Streamlit-based user interface

## Technologies Used

- Python
- Streamlit
- PyMuPDF
- Scikit-learn
- TF-IDF
- Cosine Similarity
- Google Gemini API
- Pandas
- NumPy

## Project Structure

AI Job Application Analyzer/
│
├── notebooks/
│   └── AI Job Analyzer Application.ipynb
│
├── app.py
├── requirements.txt
├── .gitignore
└── README.md

## How It Works

Resume PDF
     ↓
PDF Text Extraction
     ↓
Resume Text
     ↓
Text Similarity Analysis
     ↓
Skill Matching
     ↓
Gemini AI Analysis
     ↓
Job Match Results
     ↓
Personalized Recommendations

## Analysis

### Text Similarity Score

The application uses TF-IDF vectorization and cosine similarity to measure how closely the resume content matches the job description.

### Skill Match Score

The application identifies skills found in both the resume and job description and highlights missing skills.

### Gemini AI Analysis

Google Gemini provides an additional analysis covering:

- Candidate strengths
- Missing or weak areas
- Improvement suggestions
- Relevant technical interview questions

## Installation

Clone the repository:

git clone <your-github-repository-url>

cd "AI Job Application Analyzer"

Install the required dependencies:

pip install -r requirements.txt

## Gemini API Key

The application requires a Google Gemini API key.

Set your API key as an environment variable.

### Windows

set GEMINI_API_KEY=your_api_key

### Linux / macOS

export GEMINI_API_KEY="your_api_key"

Important: Never upload your Gemini API key to GitHub.

## Run the Application

Start the Streamlit application:

streamlit run app.py

The application will open in your browser.

## Future Improvements

- Add overall job-fit recommendations
- Add resume improvement suggestions
- Add downloadable analysis reports
- Add multiple job comparison
- Add resume keyword optimization
- Add job application tracking
- Improve skill detection using NLP/LLM-based extraction

## Author

K. Abhinav Akash

## License

This project is intended for educational and portfolio purposes.