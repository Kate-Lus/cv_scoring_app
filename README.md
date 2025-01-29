## AI Scoring Tool for HR

# 📌 Overview
This service helps HR specialists quickly assess candidate resumes against specific job openings using the OpenAI API. Simply upload a resume link and job description, and the neural network will analyze the data and generate an objective scoring.

# 🔹 Key Features
🚀 Automated candidate assessment based on job requirements
🎯 Numerical relevance scoring (from 1 to 10)
🛠 Utilization of OpenAI API for analysis
🔍 Parsing job descriptions and resumes
📊 Generation of a brief analytical report

# 🛠 Technologies Used
Python – core development language
Streamlit – for the web interface
requests – parsing job postings from hh.ru
OpenAI API – analyzing resumes and job descriptions
GitHub Actions (optional) – for CI/CD

# 📖 How to Run the Project?
1️⃣ Install dependencies:
bash
Copy
Edit
pip install -r requirements.txt
2️⃣ Run the local Streamlit server:
bash
Copy
Edit
streamlit run streamlit_app.py
3️⃣ Connect API keys via secrets.toml

# 💡 What I Learned
Developing prompts for GPT and working with system prompts
Integrating OpenAI API into HR processes
Building a web application with Streamlit
Parsing data from hh.ru
Optimizing AI-based candidate evaluation
