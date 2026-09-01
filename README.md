
# ✈️ AI Travel Agent

An AI-powered travel planning application built using Python, Streamlit, and the Gemini API.

The application takes a user's travel requirements such as destination, number of days, travelers, budget, and interests, and generates a personalized itinerary with budget estimation and plan validation.

## 🚀 Features

- 🗺️ Destination recommendations
- 📅 Day-by-day itinerary generation
- 💰 Budget estimation
- 🔍 Travel plan validation and review
- 🧠 AI-powered travel planning using Gemini API
- 💾 Travel memory/history
- 🌐 Simple Streamlit web interface

## 🛠️ Technologies Used

- Python
- Google Gemini API
- Streamlit
- JSON
- Pytest

## 📋 Requirements

- Python 3.10 or later
- Git
- Internet connection
- Google Gemini API key

## ⚙️ Installation

### 1. Clone the repository

git clone https://github.com/YOUR_USERNAME/AI-Travel-Agent.git
cd AI-Travel-Agent

Create a virtual environment

Windows:
python -m venv venv
venv\Scripts\activate

Install dependencies
pip install -r requirements.txt

Configure the Gemini API key

Create a .env file in the project root:
GEMINI_API_KEY=your_gemini_api_key_here

Run the application
streamlit run app.py

The application will open in your browser at:
http://localhost:8501

Example Input
Plan a 5-day trip to Bengaluru and Mysuru for 2 people
with a budget of ₹25,000.
I want to visit famous tourist attractions,
gardens, palaces, and markets.
