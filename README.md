# 📊 Finance Agent

A powerful AI agent built using the **[Phi](https://phi.works/)** framework that provides real-time financial insights using **Groq's LLaMA 3 model** and data from **Yahoo Finance**.

---

## 📌 Project Description

This project uses a custom AI agent called **Finance Agent** to retrieve and summarize financial information such as:

- ✅ Current stock prices  
- ✅ Analyst recommendations  
- ✅ Company profiles  
- ✅ Latest financial news  

**Technologies Used:**
- 🔍 **Groq LLaMA 3.3 70B Versatile** model for intelligent response generation  
- 📉 **YFinanceTools** for live financial data  
- 🧾 Markdown tables for clean, structured responses  

---

## 🛠️ Setup Instructions

Follow the steps below to set up the virtual environment and install the required packages:

```powershell
cd "your-project-path"            # Navigate to your project directory
python -m venv demo               # Create a virtual environment named 'demo'
.\demo\Scripts\Activate           # Activate the virtual environment (Windows)
pip install -r requirements.txt  # Install all dependencies


🔐 Environment Variables
Make sure to create a .env file with the necessary API keys or environment variables if required by phi or Groq.
GROQ_API_KEY=your_groq_api_key

### 🖼️ Sample Output

[![Analyst Recommendations]([Project/images/analyst_recommendations.png)](https://github.com/Tannuv95/Financial_agent/blob/main/Project/images/analyst_recommendations.png)

