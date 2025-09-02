# 🎥 Agentic AI Video Summarizer  

An AI-powered **multimodal agent** that summarizes and analyzes videos with the help of **Gemini 2.0 Flash Exp**, **Phidata Agents**, and **DuckDuckGo search integration**.  
This app allows users to upload videos, ask context-specific questions, and receive **detailed, user-friendly, and actionable insights** from the video content — enhanced with external web research.  

---

## 🚀 Features  
- 📂 **Upload video files** (`.mp4`, `.mov`, `.avi`) for AI analysis.  
- 🎤 **Ask queries** about the video (e.g., "Summarize key moments", "What are the main discussion points?").  
- 🧠 **Powered by Gemini 2.0 Flash Exp** for multimodal understanding.  
- 🌐 **Enhanced with DuckDuckGo search** for supplementary context.  
- ⚡ **Agentic workflow with Phidata** for reasoning and structured responses.  
- 🎬 **Instant video playback** in the Streamlit interface.  

---

## 🛠️ Tech Stack  
- [Streamlit](https://streamlit.io/) – Frontend framework for interactive UI.  
- [Phidata Agents](https://github.com/phidatahq/phidata) – Agent framework for LLM workflows.  
- [Google Gemini](https://deepmind.google/technologies/gemini/) – Multimodal AI model for video + text analysis.  
- [DuckDuckGo Tool](https://duckduckgo.com/) – For real-time web search and insights.  
- [Python-dotenv](https://pypi.org/project/python-dotenv/) – To manage environment variables.  

---

## ⚙️ Installation & Setup  

### 1. Clone the repository  

git clone https://github.com/your-username/agentic_ai_vid_summarizer.git

cd agentic_ai_vid_summarizer

### 2. Create a virtual environment
python -m venv venv
source venv/bin/activate   # On Mac/Linux
venv\Scripts\activate      # On Windows

### 3. Install dependencies
pip install -r requirements.txt

### 4. Set up environment variables

Create a .env file in the project root and add your Google API key:

GOOGLE_API_KEY=your_api_key_here

### 5. Run the Streamlit app
streamlit run app.py



## 👤 Author
**Siddharth Bhimpure**  
- 🎓 B.Tech in AI & Data Science  
