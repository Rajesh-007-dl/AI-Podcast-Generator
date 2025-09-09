# 🔊 Narrify  
### *“Give your writings a voice.”*

Turn blogs into engaging podcasts in just one click.  
This app scrapes blog content and generates natural-sounding audio — giving your written words a voice.  

---

## ✨ Features
- 🔍 **Blog Scraping** – Extracts clean text content from blogs using Firecrawl.  
- 📝 **Smart transcript** – Generates concise, conversational transcript.  
- 🎧 **Podcast Generation** – Converts text to high-quality audio using ElevenLabs.  
- ⚡ **One-Click Workflow** – Input a URL, get a downloadable podcast.  

---

## 🛠️ Tech Stack
- **Frontend**: [Streamlit](https://streamlit.io/)  
- **LLMs**: OpenAI (GPT-4o)  
- **Audio Generation**: ElevenLabs API  
- **Scraping**: Firecrawl API  
- **Orchestration**: [Agno Agents](https://pypi.org/project/agno/)  

---

## 🚀 Getting Started

### 1️⃣ Clone the Repo
```bash
git clone https://github.com/Rajesh-007-dl/AI-Podcast-Generator.git
cd AI-Podcast-Generator
```

### 2️⃣ Create Virtual Environment
```bash

```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Setup Environment Variables
Create a `.env` file in the root directory:

```
OPENAI_API_KEY=your_openai_key_here
ELEVEN_LABS_API_KEY=your_elevenlabs_key_here
FIRECRAWL_API_KEY=your_firecrawl_key_here
```

### 5️⃣ Run the App
```bash
streamlit run app.py
```

---

## 📂 Project Structure
```
├── app.py             # Streamlit frontend
├── requirements.txt    # Dependencies
├── .env.example        # Example environment file
└── audio_generations/  # Generated podcasts
```

---

## 📸 Demo
<img width="996" height="547" alt="Screenshot" src="https://github.com/user-attachments/assets/5c1de091-4dea-4aae-bbfa-c7560d63d657" />

🎧 [Listen to Sample Podcast](https://github.com/Rajesh-007-dl/AI-Podcast-Generator/blob/main/sample_podcast.mp3)

🎧 [Listen to Sample Podcast](https://github.com/Rajesh-007-dl/AI-Podcast-Generator/blob/main/generated_podcast.mp3)


---

## 🔮 Future Enhancements
- Multi-voice & language support  
- Direct RSS feed podcast publishing  
- User accounts & history tracking  
- Mobile-friendly UI  

---

## 📜 License
MIT License. Free to use and modify.  

---

## 💡 Inspiration
We built **Narrify** to transform **static blogs into dynamic audio experiences** — making content accessible to busy readers, commuters, and auditory learners.  

---
