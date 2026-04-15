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

<img width="1518" height="868" alt="Screenshot 2026-04-15 184031" src="https://github.com/user-attachments/assets/4848f1d1-716a-451f-8f8e-c4866d375448" />
<img width="985" height="820" alt="Screenshot 2026-04-15 184326" src="https://github.com/user-attachments/assets/72962064-0f89-4254-9dca-074d05bed49a" />
<img width="1393" height="809" alt="Screenshot 2026-04-15 184507" src="https://github.com/user-attachments/assets/c62f2240-b0ec-4b9c-a015-90a5c4b9e429" />
<img width="1028" height="816" alt="Screenshot 2026-04-15 184743" src="https://github.com/user-attachments/assets/202197e2-1546-4837-b0b4-77cc003b401c" />



##  Output Example

```python
{
 'Score': 85,
 'Explanation': 'Candidate has strong matching skills including Python, Machine Learning, and SQL with relevant experience.'
}
