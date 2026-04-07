# AI-Powered Resume Screening and Ranking System

## Overview
This project aims to develop an AI-powered resume screening and ranking system using Natural Language Processing (NLP) and Machine Learning (ML) techniques. The system allows users to upload their resumes (in PDF or TXT format) and job descriptions (in TXT format). It then provides a ranking score based on how well the resume matches the job description.

## Features
- **Resume Upload**: Users can upload their resumes in PDF or TXT format.
- **Job Description Upload**: Users can submit job descriptions in TXT format.
- **AI Ranking**: The system uses NLP and ML models to evaluate and rank resumes based on relevance to the provided job description.
- **Frontend Interface**: Built with Streamlit for a user-friendly web interface.

## Technologies Used
- **Backend**: Python, Flask
- **Frontend**: Streamlit
- **NLP**: spaCy, NLTK, or other NLP libraries
- **Machine Learning**: Scikit-learn, TensorFlow, or PyTorch
- **Other Libraries**: pandas, numpy, matplotlib
- **Database**: SQLite (Optional for storing resumes and job descriptions)

 AI-Powered Resume Screening and Ranking System/
│
├── backend/                   
│   ├── app.py               # Flask API to handle user requests and resume processing
│   ├── model.py             # ML Model for resume ranking based on job description
│   ├── nlp_processing.py    # NLP-based feature extraction and text processing
│   ├── utils.py             # Helper functions for data processing and model usage
│   ├── requirements.txt     # List of Python dependencies for the backend
│
├── frontend/                 
│   ├── src/                 
│   │   ├── components/      # UI components for the frontend (e.g., file upload forms)
│   │   ├── pages/           # Streamlit app pages (main user interface)
│   │   ├── App.js           # Main app entry point (for frontend logic)
│   │   ├── index.js         # Initial file for frontend routing and setup
│   ├── package.json         # Frontend dependencies for the project (Streamlit)
│
├── models/                  # Folder containing trained ML models for resume ranking
│   ├── ranking_model.pkl    # Pickled model for ranking resumes based on the job description
│
├── dataset/                 # Folder to store sample resumes and job descriptions for testing
│   ├── resumes/             # Sample resume files (PDF/TXT)
│   ├── job_descriptions/    # Sample job description files (TXT)
│
├── README.md                # Project documentation and instructions
└── .gitignore               # Git ignore file for unnecessary files




