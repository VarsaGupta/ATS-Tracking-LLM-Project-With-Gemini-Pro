                                                                             ATS Resume Expert

ATS Resume Expert is a Streamlit web application designed to assist in analyzing resumes using Google's Generative AI, specifically the Gemini Pro model. This tool is especially useful for HR professionals and job seekers, as it helps in evaluating the alignment of a resume with a specific job description.

**Features:**
-  Resume Upload: Users can upload their resume in PDF format.
-  Job Description Analysis: The application allows users to input a job description.
-  Resume Evaluation: It provides an evaluation of the uploaded resume against the provided job description.
-  Matching Percentage: The tool calculates a percentage match, indicating how well the resume aligns with the job requirements.
-  Strengths and Weaknesses Analysis: Offers insights into the strengths and weaknesses of the application in relation to the specified job requirements.


**Image:**
<img width="747" alt="Screenshot 2024-01-21 152319" src="https://github.com/VarsaGupta/ATS-Tracking-LLM-Project-With-Gemini-Pro/assets/125072517/2e797d35-83ae-4e64-95af-1e13d5d8bdfa">


**How It Works:**
-  Upload Resume: Users upload their resume in PDF format.
- Input Job Description: Users enter a job description in the provided text area.
-  Analysis: Upon clicking the analysis button, the app uses Google's Gemini Pro model to analyze the resume against the job description.
- Display Results: The app displays the analysis results, including the matching percentage and detailed feedback.


**Technical Details:**
-  Streamlit: This application is built using Streamlit, a powerful framework for building data applications.
- Google Generative AI: It uses Google's Generative AI (Gemini  Pro model) for analyzing resumes.
- PDF Processing: The app converts PDF resumes to images for processing.
- Environment Variables: API keys and sensitive data are stored in environment variables for security.

**Installation and Usage:**

- Clone the repository:
   git clone [repository_url]
- Install the required packages:
   pip install -r requirements.txt
- Set your GOOGLE_API_KEY in the environment variables.
-  Run the Streamlit app:
   streamlit run app.py

**Dependencies:**
1. Streamlit
2. google-generativeai
3. pdf2image
4. PIL (Python Imaging Library)   

