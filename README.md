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

output
<img width="1518" height="868" alt="Screenshot 2026-04-15 184031" src="https://github.com/user-attachments/assets/5332fe35-8cff-4028-bcad-82d11957b854" />
<img width="985" height="820" alt="Screenshot 2026-04-15 184326" src="https://github.com/user-attachments/assets/e2fbe241-c1b8-4785-9317-d613130f923c" />
<img width="1393" height="809" alt="Screenshot 2026-04-15 184507" src="https://github.com/user-attachments/assets/ec6665f3-34af-4f53-b0d2-7c3b5c9aa058" />
<img width="1028" height="816" alt="Screenshot 2026-04-15 184743" src="https://github.com/user-attachments/assets/5a9a6f86-8dcf-428d-9cb5-ad5457383a87" />

