# 📄📦 Resume ZIP to CSV Analyzer

## 📌 Overview
Resume ZIP to CSV Analyzer is a **Streamlit-based application** that extracts resumes from a **ZIP file**, processes them using **AI/NLP**, and converts the information into a **structured CSV format** for easy analysis.

The system supports resumes in **PDF and DOCX formats** and helps automate resume screening and data extraction.

---

## 🎯 Key Features
- Upload ZIP file containing multiple resumes
- Supports PDF and DOCX resumes
- Automated resume text extraction
- Converts resumes into structured CSV
- Resume data analysis and summarization
- Simple and interactive Streamlit UI

---

## 🧠 How It Works
1. User uploads a ZIP file of resumes
2. Resumes are extracted automatically
3. Text is parsed from PDF/DOCX files
4. Key details are extracted (skills, experience, etc.)
5. All resume data is saved into a CSV file
6. User can download the generated CSV

---

## 🏗️ Tech Stack
- **Frontend:** Streamlit  
- **Language:** Python  
- **Resume Parsing:** pdfplumber, python-docx  
- **Data Handling:** Pandas  
- **AI/NLP (Optional):** LangChain / LLM  

---

## 📁 Project Structure
```
resume-to-csv/
├── app.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Setup & Run Locally
```bash
pip install -r requirements.txt
streamlit run app.py
```

---

## ☁️ Deploy on Streamlit Cloud
1. Push the code to GitHub
2. Create a Streamlit Cloud app
3. Select `app.py` as the main file
4. Deploy the app

---

## 📥 Output
- Downloadable CSV file
- Each row represents one resume
- Useful for:
  - Resume screening
  - Candidate comparison
  - HR analytics
  - Recruitment automation

---

## 🎓 Learning Outcomes
- Handling ZIP file uploads in Streamlit
- Resume text extraction from PDF/DOCX
- Data transformation using Pandas
- Building real-world HR automation tools
- End-to-end Streamlit app deployment

---

## 👩‍💻 Author
**Pavani Reddy**
