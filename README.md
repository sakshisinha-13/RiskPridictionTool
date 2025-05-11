Construction Risk Monitoring Dashboard
Live Demo: https://construction-risk-monitoring.vercel.app/ 

An AI-powered tool to monitor and predict risks in construction projects. The platform includes an intuitive frontend dashboard and a backend ML model that analyzes supply chain vulnerabilities, predicts potential risk levels, and suggests mitigation strategies.

Features:
Interactive and responsive frontend dashboard (Vercel-hosted)
Predictive analytics via integrated Streamlit ML tool
Real-time supply chain risk scoring
Cost/resource efficiency estimation pre- and post-mitigation
AI-generated mitigation suggestions
Seamless integration between frontend and ML dashboard

Tech Stack:
| Frontend            | Backend ML App       |
| ------------------- | -------------------- |
| HTML / Tailwind CSS | Python, Streamlit    |
| JavaScript (Vite)   | Scikit-learn, Pandas |
| Hosted on Vercel    | Hosted on Streamlit  |

Project Structure:
RiskPridictionTool/
│
├── Risk_Pridiction_Tool-main/       # ML model & Streamlit app
│   └── app.py
│   └── requirements.txt
│
├── client/ (or frontend folder)     # Vite + Tailwind UI
│   └── index.html
│   └── favicon.ico
│   └── assets/
│
├── README.md
└── ...
