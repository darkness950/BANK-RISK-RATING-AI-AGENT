# Autonomous AI Risk Officer for Banking Risk Assessment

An end-to-end autonomous AI system designed for comprehensive banking risk assessment, regulatory compliance analysis, and professional report generation.

## 🚀 Overview

This project is an autonomous AI agent that analyzes bank risk rating datasets using advanced machine learning, regulatory intelligence, and professional reporting capabilities. It automatically trains models, evaluates performance, explains key risk drivers, and generates comprehensive reports enriched with regulatory context from Basel III frameworks.

## ✨ Key Features

- **🤖 AutoML Pipeline**: Automated model selection and training using AutoGluon
- **📚 Regulatory Intelligence**: RAG system with Basel III document processing
- **🧠 Knowledge Graph**: Graph RAG for regulatory concept mapping
- **📊 Professional Reporting**: PDF generation with banking-grade formatting
- **🛡️ Resilience**: Checkpointing and recovery system
- **🌐 Web Interface**: Streamlit dashboard for interactive analysis
- **📈 Visualization**: Comprehensive model performance and feature analysis

🚀🚀 Guide to Test the Program
Step 1 – Open the Project

Import the project into your IDE (PyCharm, VS Code, etc.).

Set the Python interpreter to Python 3.11 to avoid any compatibility issues.

Step 2 – Configure the Groq API Key

For security reasons, the default Groq API key will expire.

You need to create your own API key at this site: 👉 https://console.groq.com/keys

Once the key is generated, open the .env file and replace the value of GROQ_API_KEY with your own key.

Step 3 – Install Dependencies

Open a terminal in the project environment.

Run the following command to install all required dependencies:

pip install -r requirements.txt

Step 4 – Launch the Application

Once installation is complete, start the application with:

streamlit run app.py


A browser window will automatically open at http://localhost:8501
.

Step 5 – Use the Application

In the left sidebar of the interface:

Upload the CSV dataset of your choice.

Click the Run Full Analysis button to start the complete analysis.

ℹ️ Important Note

⏳ The execution time may vary between 45 and 90 minutes, depending on the dataset size.

You can leave the program running in the background until the analysis finishes.
