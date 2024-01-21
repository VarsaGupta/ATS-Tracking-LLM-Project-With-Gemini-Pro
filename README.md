**ATS Resume Expert
ATS Resume Expert is a Streamlit web application designed to assist in analyzing resumes using Google's Generative AI, specifically the Gemini Pro model. This tool is especially useful for HR professionals and job seekers, as it helps in evaluating the alignment of a resume with a specific job description.

Features:
1. Resume Upload: Users can upload their resume in PDF format.
2. Job Description Analysis: The application allows users to input a job description.
3. Resume Evaluation: It provides an evaluation of the uploaded resume against the provided job description.
4. Matching Percentage: The tool calculates a percentage match, indicating how well the resume aligns with the job requirements.
5. Strengths and Weaknesses Analysis: Offers insights into the strengths and weaknesses of the application in relation to the specified job requirements.


How It Works:
1. Upload Resume: Users upload their resume in PDF format.
2. Input Job Description: Users enter a job description in the provided text area.
3. Analysis: Upon clicking the analysis button, the app uses Google's Gemini Pro model to analyze the resume against the job description.
4. Display Results: The app displays the analysis results, including the matching percentage and detailed feedback.


Technical Details:
1. Streamlit: This application is built using Streamlit, a powerful framework for building data applications.
2. Google Generative AI: It uses Google's Generative AI (Gemini  Pro model) for analyzing resumes.
3. PDF Processing: The app converts PDF resumes to images for processing.
4. Environment Variables: API keys and sensitive data are stored in environment variables for security.

Installation and Usage:
1. Clone the repository:
2. git clone [repository_url]
3. Install the required packages:
   pip install -r requirements.txt
4. Set your GOOGLE_API_KEY in the environment variables.
5. Run the Streamlit app:
   streamlit run app.py

Dependencies:
1. Streamlit
2. google-generativeai
3. pdf2image
4. PIL (Python Imaging Library)   

