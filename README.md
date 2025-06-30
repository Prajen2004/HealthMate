# 🩺 HealthMate – Your AI-Powered Virtual Doctor

> A blazing-fast virtual doctor powered by LLaMA 3 (via Groq), built with Streamlit.  
> Diagnose symptoms, book doctors, set medication reminders, and get daily health tips — all in one intelligent platform.

![HealthMate Banner](https://your-image-url.com/banner.png) <!-- Optional -->

---

## 💡 Problem Statement

Billions lack access to timely, reliable, and affordable healthcare. From missed medications to undiagnosed symptoms, the world faces a silent crisis — especially in remote and underserved areas.

**HealthMate** tackles this problem with a smart, AI-driven virtual assistant that empowers users to:
- Self-assess their health instantly
- Book nearby doctors
- Get medication alerts
- Receive personalized advice — all without waiting rooms or phone calls.

---

## 🚀 Features

| Module | Description |
|--------|-------------|
| 🧠 **AI Symptom Checker** | Enter symptoms & receive LLM-powered diagnosis and remedies |
| 🗓️ **Book a DOC** | Discover nearby doctors using geolocation and request appointments |
| ⏰ **Medication Reminder** | Set daily medication reminders with audio alerts |
| ⚖️ **BMI Calculator** | Get personalized health insights based on BMI |
| 📞 **Emergency Contact Info** | Auto-display key emergency numbers by state |
| 📥 **Chat Export** | Download your full medical chat history as a Word document |
| 💡 **Daily Health Tips** | Auto-refreshing well-being tips every session |

---

## 🧠 Tech Stack

| Category | Tools Used |
|----------|------------|
| 💬 AI/LLM | [Groq](https://groq.com/) + [LLaMA 3](https://huggingface.co/meta-llama) |
| 🧠 Prompt Orchestration | [LangChain](https://www.langchain.com/) |
| 🌐 Frontend | [Streamlit](https://streamlit.io/) |
| 🗺️ Geolocation | [Folium](https://python-visualization.github.io/folium/) + [Geopy](https://geopy.readthedocs.io/) |
| 📦 Exporting Docs | [python-docx](https://python-docx.readthedocs.io/) |
| 🔔 Alerts | Custom alarm with HTML5 Audio |
| 🧠 Backgrounds | Dynamic CSS via Streamlit injection |

---

## 🖼️ Screenshots

| Diagnosis View | Map View | Reminders |
|----------------|----------|-----------|
| ![Diagnosis](https://your-link.com/diag.png) | ![Map](https://your-link.com/map.png) | ![Reminder](https://your-link.com/reminder.png) |

---

## 🎬 Demo Video

> ⏯️ [Watch Demo (3 minutes)](https://youtu.be/your-demo-link)

---

## 🛠️ How to Run Locally

```bash
# Clone the repo
git clone https://github.com/yourusername/HealthMate.git
cd HealthMate

# (Optional) Set up a virtual environment
python -m venv venv
source venv/bin/activate  # or .\venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Set your Groq API key
export GROQ_API_KEY=your_groq_key  # or set in .env

# Run the app
streamlit run app.py
