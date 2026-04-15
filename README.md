#  AI Resume Screening System using LangChain

This project is an AI-powered Resume Screening System built using LangChain.  
It evaluates candidates based on a given job description and provides a score along with a clear explanation.

---

##  Project Overview

The system simulates how recruiters screen resumes by automating:

- Skill extraction
- Resume vs Job Description matching
- Candidate scoring (0–100)
- Explanation generation

It follows a structured LLM pipeline and includes tracing using LangSmith for debugging and monitoring.

---

##  Pipeline Flow

Resume → Skill Extraction → Matching → Scoring → Explanation → Output

---

##  Technologies Used

- Python
- LangChain
- LangSmith (for tracing)
- Jupyter Notebook

---

##  Features

✔ PromptTemplate-based structured prompting  
✔ Modular pipeline design  
✔ Resume evaluation with scoring logic  
✔ Explainable AI output (reason for score)  
✔ LangSmith tracing enabled for monitoring  
✔ Clean and reusable code  

---

##  Project Structure
AI-Resume-Screening-System-LangChain/
│── AI_Resume_Screening_System_LangChain.ipynb
│── README.md

---

##  Sample Inputs

### Job Description
Data Scientist role requiring:
- Python
- Machine Learning
- SQL
- Pandas, NumPy
- Data Visualization

---

### Candidate Types

- 🟢 Strong Candidate (High match)
- 🟡 Average Candidate (Partial match)
- 🔴 Weak Candidate (Low match)

---

##  Output Example

```python
{
 'Score': 85,
 'Explanation': 'Candidate has strong matching skills including Python, Machine Learning, and SQL with relevant experience.'
}
