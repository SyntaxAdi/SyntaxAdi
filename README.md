<img src="1.png" alt="SyntaxAdi Banner" width="30%">

# Hi there!  👋 I'm SyntaxAdi

I design and build automation-driven software using Python — Telegram bot infrastructures, backend services, and AI-powered tools. My focus is creating practical systems that solve real problems without unnecessary complexity.

## About Me

I build automation systems and backend services using Python.  
My work focuses on Telegram bot infrastructure, API-driven services, and automation tools.  
Interested in building practical systems that solve real-world problems.

Technically, I work across:
- Python automation and bot frameworks (Telethon)
- Backend service development with FastAPI
- API integrations and workflow orchestration
- ML model deployment with Hugging Face and Gradio
- DevOps and Linux-based deployment environments 

## Technical Stack

![Languages](https://img.shields.io/badge/LANGUAGES-0d1117?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

![Backend](https://img.shields.io/badge/BACKEND-0d1117?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![aiohttp](https://img.shields.io/badge/aiohttp-2C5BB4?style=flat-square&logo=aiohttp&logoColor=white)

![Bots & Automation](https://img.shields.io/badge/BOTS%20%26%20AUTOMATION-0d1117?style=flat-square)
![Telethon](https://img.shields.io/badge/Telethon-2CA5E0?style=flat-square&logo=telegram&logoColor=white)
![Pyrogram](https://img.shields.io/badge/Pyrogram-2CA5E0?style=flat-square&logo=telegram&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![BeautifulSoup4](https://img.shields.io/badge/BeautifulSoup4-59666C?style=flat-square&logo=python&logoColor=white)
![yt-dlp](https://img.shields.io/badge/yt--dlp-FF0000?style=flat-square&logo=youtube&logoColor=white)

![Databases](https://img.shields.io/badge/DATABASES-0d1117?style=flat-square)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

![DevOps](https://img.shields.io/badge/DEVOPS-0d1117?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

![Frontend](https://img.shields.io/badge/FRONTEND-0d1117?style=flat-square)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

## Featured Projects

### [Media-Downloader](https://github.com/SyntaxAdi/Media-Downloader)
*Async Telegram bot downloading media from 20+ platforms via modular per-site handlers*

**Stack:** Python, Telethon, asyncio, yt-dlp, gallery-dl, cloudscraper, pymongo, aiohttp, httpx, Pillow, BeautifulSoup4

- Modular async architecture with per-platform handlers for 20+ media sources including Instagram, TikTok, YouTube, Reddit, and Threads
- Media pipeline includes direct song downloads, Shazam-based music recognition, and CDN-side image compression for Telegram delivery limits
- Production bot controls include anti-spam protection, force-subscribe gating, and admin tools for remote update, restart, and log access

---

### [Udemy-Auto-Enroller](https://github.com/SyntaxAdi/Udemy-Auto-Enroller)
*Telegram bot that scrapes five course aggregators in parallel and auto-enrolls users in free Udemy courses*

**Stack:** Python, Telethon, asyncio, aiohttp, motor (async MongoDB), BeautifulSoup4, lxml, cloudscraper, python-dotenv

- Async parallel scraping across: Discudemy, Udemy Freebies, Real Discount, Tutorial Bar, Course Vania
- Course expiry validated before enrollment — filters dead deals before hitting the Udemy API
- Real-time enrollment progress updates sent in Telegram; per-user savings and stats tracking
- Daily rate limits, channel subscription gate, and admin usage reporting

---

### [ArthSaathi](https://github.com/SyntaxAdi/ArthSaathi)
*AI-powered personal finance web app for Indian youth — hackathon build, deployed on Vercel*

**Stack:** React 18, Vite 5, Tailwind CSS, Framer Motion, Supabase (PostgreSQL + Auth + RLS), Groq API (LLaMA 3.3 70B), React Router DOM v7

- Financial health score algorithm factoring savings rate, EMI ratio, and spending patterns
- LLM coach powered by LLaMA 3.3 70B via Groq; receives the user's full exported report as prompt context
- AI-suggested goals importable directly into the tracker with one click
- Full multilingual UI: English, Hindi, Tamil, Marathi — with per-user currency and number system settings

---

### [Word-Grid-Solver-Web](https://github.com/SyntaxAdi/Word-Grid-Solver-Web)
*Flask web app that solves word-search puzzles from uploaded images*

**Stack:** Python 3.9, Flask 3.0, Werkzeug, Requests, Vanilla JS/CSS, Docker (port 7860)

- Drag-and-drop image upload; grid extracted via remote Lambda-hosted OCR API (base64-encoded)
- 8-directional grid search (all 4 axes + diagonals) with jagged array handling
- Clue-based constraint solving — parses `A---- (5)` into start character + length pairs
- Dockerized deployment with a decoupled solver core that can also run as a standalone CLI tool

---

### [Kali-Portfolio](https://github.com/SyntaxAdi/Kali-Portfolio)
*Personal portfolio built as a Kali Linux desktop simulation*

**Stack:** React 19, Vite 7, Tailwind CSS, Framer Motion, shadcn/ui, Lucide React

- Desktop-style interface with a finite-state flow for boot, login, workspace, and shutdown transitions
- Window manager system handles app focus, stacking order, and multi-window interactions
- Visual polish includes boot logs, CRT effects, wallpaper cycling, and animated restart or shutdown sequences

---

### [Personal-Portfolio](https://github.com/SyntaxAdi/Personal-Portfolio)
*Minimal static portfolio — no framework, no build step*

**Stack:** HTML5, CSS3, Vanilla JS, Vercel

- Entire site self-contained in a single 43KB `index.html` with embedded CSS and JS
- Rotating anime/motivational quotes; `vercel.json` with SPA-style routing

## 📈 GitHub Stats

![SyntaxAdi's GitHub stats](https://github-readme-stats.vercel.app/api?username=SyntaxAdi&show_icons=true&theme=dark&hide_border=true&count_private=true) ![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=SyntaxAdi&layout=compact&theme=dark&hide_border=true&langs_count=8)

## Current Work

**LLM Applications**  
Experimenting with Gemini and Groq APIs to build AI-assisted tools and workflow automation.

**Telegram Bot Systems**  
Developing modular Telegram bot architectures using async Python frameworks and MTProto libraries.

**Automation Tools**  
Creating scripts and utilities that automate repetitive workflows and integrate multiple APIs.

**Backend Development**  
Building lightweight backend services with FastAPI and asynchronous Python.

**ML Experiments**  
Testing model hosting setups using Hugging Face, Gradio interfaces, and free GPU environments such as Colab.

## 🤝 Let's Connect! 
Open to collaborating on interesting technical projects, discussing engineering ideas, or exploring new opportunities.
- **💼 LinkedIn:** [aaditya-pawar2004](https://www.linkedin.com/in/aaditya-pawar2004)
- **📧 Email:** [aadityapawar00001@gmail.com](mailto:aadityapawar00001@gmail.com)
- **💬 Telegram:** [@ItzAditya_xD](https://t.me/ItzAditya_xD)
- **🌐 Portfolio:** [akenochan.my.id](https://akenochan.my.id)
