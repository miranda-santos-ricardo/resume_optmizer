# ResumeGPT – AI-Powered Resume Optimizer

ResumeGPT is a smart resume optimizer built with OpenAI GPT-4, Streamlit, and Python. It helps job seekers rewrite their resumes to match job descriptions using LLM-based text generation. The final version can be downloaded to manual updates.
## Architecture

<img width="665" alt="image" src="https://github.com/user-attachments/assets/3a9feb49-71e7-4526-9eb6-f8f3624bcba1" />

## 🔥 Features
- Upload your resume (PDF/DOCX)
- Upload a job description (PDF/TXT/DOC)
- Automatically rewrite your resume for a better job match
- Give you a score from 0 to 100 how much your resume match with the job description
- Download optimized resume as TXT or DOCX
- Powered by OpenAI's GPT-4 + custom prompts

## 📦 Tech Stack
- Python, Streamlit
- OpenAI GPT-4 API
- PyPDF2, docx2txt, python-docx
- Optional: Pinecone/FAISS for RAG (future feature)

## 🚀 Getting Started

```bash
git clone https://github.com/rikardoms/resume_optmizer.git
cd resume_optmizer
pip install -r requirements.txt (need to include your OPENAPI KEY in the .env file)
streamlit run app.py
