# Resume Expert

## Overview
Resume Expert is a web application built to assist users in analyzing and improving resumes with the help of GEMINI AI (LLM). It allows users to upload their resumes in PDF format and provides various features for analyzing the resume content, comparing it with a job description, and obtaining feedback on how to improve it.

## Features
- **JobFit Analyzer:** Users can input a job description and analyze their resume against it to determine how well it fits the job requirements.
- **Skill Enhancement Suggestions:** Users can receive suggestions on how to improve their skills based on the job description and their resume content.
- **Keyword Analysis:** Users can identify missing keywords in their resume compared to the job description.
- **Percentage Match:** Users can find out the percentage match of their resume with the job description.

## Technologies Used
- **Python**
- **Streamlit**
- **Pillow (PIL)**
- **pdf2image**
- **google-generativeai**

## How to Run
To run the application locally, follow these steps:
1. Clone the repository: `git clone https://github.com/JensenJose/Applicant-Tracking-System.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Set up your Google API key and add it to a `.env` file.
4. Run the Streamlit app: `streamlit run app.py`
5. Access the application in your web browser at `http://localhost:8501`.

## Usage
1. Enter a job description in the input field provided.
2. Upload your resume in PDF format.
3. Choose the desired analysis option:
   - JobFit Analyzer
   - Skill Enhancement Suggestions
   - Keyword Analysis
   - Percentage Match
4. Click the corresponding button to view the analysis results.

## License
This project is licensed under the [MIT License](LICENSE).
