# Resume Parser and Job Recommender

A machine learning-powered Flask web application that parses resumes, extracts key information, categorizes resume fields, and recommends relevant jobs based on the user's profile.

---

## 🚀 Features

- 📄 **Resume Parsing**  
  Upload a PDF resume and extract structured information such as name, skills, education, experience, and more.

- 🧠 **Resume Categorization**  
  Automatically categorizes resumes into predefined job domains (e.g., Data Science, Web Development, Android Development) using a trained ML model.

- 💼 **Job Recommendation Engine**  
  Recommends suitable job roles based on extracted keywords, experience, and domain using another trained ML model.

- 🛠️ **Tech Stack**
  - Python
  - Flask (Web Framework)
  - Scikit-learn (ML Models)
  - PyPDF2 (Resume Text Extraction)
  - HTML/CSS (Frontend)
  - Jinja2 (Templating)

---

## 📂 Project Structure

resume-job-recommender/
│
├── static/ # CSS/JS files
├── templates/ # HTML templates
│ ├── index.html
│ └── result.html
│
├── models/
│ ├── resume_categorizer.pkl
│ └── job_recommender.pkl
│
├── utils/
│ ├── resume_parser.py # Resume text extractor
│ └── recommender.py # Logic for categorization and recommendation
│
├── app.py # Flask server
├── requirements.txt # Project dependencies
└── README.md # Project documentation


Live Link : https://resume-scanner-kf3w.onrender.com
