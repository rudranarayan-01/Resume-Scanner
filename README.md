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

## 🧪 How it Works

1. **User uploads resume (PDF)**
2. **Resume is parsed and cleaned using `PyPDF2`**
3. **Extracted text is passed through the categorizer model**
4. **Relevant job recommendations are fetched from the recommender model**
5. **Results are displayed in a user-friendly format**

---

## 💻 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/Resume-Scanner.git
   cd Resume-Scanner
```


Live Link : https://resume-scanner-kf3w.onrender.com
