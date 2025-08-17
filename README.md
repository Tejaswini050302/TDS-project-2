# TDS Project 2

This project implements a Data Analyst Agent API that uses large language models (LLMs) to source, prepare, analyze, and visualize data based on user-provided questions and optional file attachments.
---
Available at : [https://tds-project-2-plhk.onrender.com](https://tds-project-2-plhk.onrender.com)

##  Features
- Accepts POST requests at `/api/` endpoint  
- Handles a mandatory `questions.txt` file containing data analysis questions  
- Supports multiple optional file attachments (e.g., CSV, images)  
- Ready to integrate with LLMs or data analysis pipelines  
- Dockerized for consistent environment and deployment
- Ready for Heroku deployment with `Procfile` and `runtime.txt`
- Extensible for adding APIs, data analysis features, or ML models

---

## 🛠️ Tech Stack
- **Python**
- **HTML** for the UI
- **Docker** for containerization
- **Heroku** deployment support

---

## 📁 Project Structure
.
├── app.py # Main Flask application code
├── index.html # Frontend HTML template
├── requirements.txt # Python dependencies
├── Dockerfile # Docker configuration file
├── entrypoint.sh # Startup script for Docker container
├── Procfile # Heroku process file
├── runtime.txt # Python runtime version for Heroku
├── README.md # Project documentation
└── LICENSE # MIT License file

---

##  License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

##  Author

Developed by [Tejaswini](https://github.com/Tejaswini050302)

---

