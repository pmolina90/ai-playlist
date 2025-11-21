# ai-playlist
AI-powered playlist generator that creates custom YouTube playlists based on user vibes, moods, and prompts. Full-stack SaaS demo with FastAPI backend and Next.js frontend.


# AI Playlist Generator 🎵🤖

AI-powered playlist generator that creates custom YouTube playlists based on user vibes, moods, and prompts. Full-stack SaaS demo with FastAPI backend and Next.js frontend.

---

## 🚀 Features

- Generate YouTube playlists from natural language prompts
- User authentication & account management
- Save and view previously generated playlists
- Async playlist generation using Celery + Redis
- Responsive frontend with Next.js + TypeScript
- Optional cloud storage integration (Cloudflare R2)

---

## 🛠 Tech Stack

**Backend:** FastAPI, Python, Celery, Redis  
**Frontend:** Next.js, React, TypeScript  
**Database:** PostgreSQL  
**Cloud / Storage:** Cloudflare R2 (optional)  
**DevOps:** Docker, Docker Compose  
**APIs:** YouTube Data API, OpenAI / other LLMs  

---

## 💻 Installation (Backend)

1. Clone the repo:

git clone https://github.com/PMOLINA90/ai-playlist.git

cd ai-playlist

2. Create a Python virtual environment:
   python3.11 - m venv venv
   source venv/bin/activate

3. Install dependencies: 
  pip install -r requirements.txt

4. Create a .env file with the following variables:
   YOUTUBE_API_KEY=your_youtube_api_key
   OPENAI_API_KEY=your_openai_api_key
   DATABASE_URL=postgresql://user:password@localhost:5432/dbname
   SECRET_KEY=your_secret_key

5. Start the backend server:
   uvicorn app.main:app --reload   
 
  
