AI-Powered Resume Coach is an interactive GenAI application that analyzes a user’s resume and provides personalized, structured career guidance, including:

Skill improvement suggestions

Relevant certifications to pursue

Tailored project ideas

Role-specific recommendations

Strengths and gaps based on resume content

The goal of this project is to help job seekers instantly understand how to strengthen their profile for the roles they want.

🎯 Features
✅ Resume Parsing

Uses PdfPlumber (or similar libraries) to extract text content from PDF resumes.

✅ Generative AI Career Coaching

Leverages a Gemini LLM prompt to generate AI-driven insights converted into clean JSON output, including:

Suggested improvements

Certifications to obtain

Projects to build

Job titles aligned with the user’s resume

✅ User Customization (Interactive Widgets)

Built-in ipywidgets allow users to specify:

Job title they are targeting

Additional context about their experience
— which is then injected into the AI prompt for tailored results.

✅ Data Visualization

AI suggestions are parsed and displayed using Pandas DataFrames for clean, readable output.

🛠️ Tech Stack
Component	Technology
Programming Language	Python
Notebook Environment	Jupyter Notebook
Resume Text Extraction	PdfPlumber
Generative AI Model	Google Gemini API
UI Components	ipywidgets
Data Handling / Display	Pandas
📘 How It Works

Upload your resume PDF

Enter job role or context via input widgets

The notebook extracts resume text with PdfPlumber

A carefully designed Gemini prompt analyzes the resume

The model returns structured JSON with improvement tips

Results are converted into clean DataFrame tables for easy viewing

🔐 API Key Setup

To run the notebook, store your Gemini API key as an environment variable:

export GOOGLE_API_KEY="your_api_key_here"


Or add it manually in the notebook cell (only for demo use).

📈 Sample Outputs

Recommended certifications

Project ideas tailored to your resume

Skill gap analysis

Suggested job roles

Strengths summary

ATS-based resume improvement advice
