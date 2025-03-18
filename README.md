# Resume-Screening-and-Ranking
## Overview
The AI-Based Resume Screening and Candidate Ranking System is a machine learning-powered solution designed to automate the process of screening job applicants. The system analyzes resumes and ranks candidates based on their relevance to the provided job description. The goal is to help HR professionals and recruiters streamline the hiring process by quickly identifying the most qualified candidates.

## Features
Resume Screening: Automatically scans resumes to extract key skills, qualifications, and experiences.<br>
Job Description Matching: Analyzes job descriptions to extract relevant keywords and requirements.<br>
Candidate Ranking: Ranks candidates based on how closely their resumes match the job description.<br>
AI-Powered: Uses machine learning techniques to assess resumes.<br>
Customizable: The system can be easily adapted to different job descriptions, industries, and requirements.<br>
Visualization: Provides a visual ranking of candidates with their scores.<br>

## Technologies Used
Python: Programming language for backend development.<br>
Streamlit: For building a user-friendly web interface to input job descriptions and display results.<br>
Scikit-learn: For machine learning models and vectorization of resumes.<br>
Pandas: For data manipulation and handling resumes.<br>

## How It Works
Input Job Description: The recruiter or HR professional enters the job description into the provided text box on the app interface.<br>
Upload Resumes: Resumes are uploaded by candidates, or multiple resumes can be added at once.<br>
Text Processing: The system processes the text of the job description and resumes.<br>
Feature Extraction: Key features such as skills, qualifications, and experience are extracted from both the resumes and the job description.<br>
Vectorization: The system uses TF-IDF (Term Frequency-Inverse Document Frequency) or word embeddings to represent the textual content numerically.<br>
Ranking: Using machine learning models like cosine similarity, the system ranks candidates based on how closely their resume matches the job description.<br>
Output: The system displays a list of candidates ranked from the most to the least relevant to the job description.<br>
