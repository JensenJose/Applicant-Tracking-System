Resume Expert
Overview
Resume Expert is a web application built to assist users in analyzing and improving resumes with the help of GEMINI AI (LLM). It allows users to upload their resumes in PDF format and provides various features for analyzing the resume content, comparing it with a job description, and obtaining feedback on how to improve it.

Features
JobFit Analyzer: Users can input a job description and analyze their resume against it to determine how well it fits the job requirements.
Skill Enhancement Suggestions: Users can receive suggestions on how to improve their skills based on the job description and their resume content.
Keyword Analysis: Users can identify missing keywords in their resume compared to the job description.
Percentage Match: Users can find out the percentage match of their resume with the job description.
Technologies Used
Python: The backend logic of the application is written in Python.
Streamlit: The web application is built using Streamlit, a Python library for creating interactive web apps.
Pillow (PIL): Used for image processing, including converting PDF pages to images.
pdf2image: A Python library for converting PDF files to images.
google-generativeai: A Python library for accessing GEMINI AI (LLM) by Google for generating text.
How to Run
To run the application locally, follow these steps:

Clone the repository: git clone https://github.com/JensenJose/Applicant-Tracking-System.git
Install dependencies: pip install -r requirements.txt
Set up your Google API key and add it to a .env file.
Run the Streamlit app: streamlit run app.py
Access the application in your web browser at http://localhost:8501
