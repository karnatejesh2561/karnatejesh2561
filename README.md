from pathlib import Path
import pypandoc

md = r"""# 👋 Karna Tejesh Kumar

<div align="center">

# Frontend Software Engineer

### React.js • Next.js • TypeScript • JavaScript • React Native • Node.js

<img src="Assets/output.gif" width="100%" alt="Hero"/>

<p>
<a href="https://github.com/karnatejesh2561"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github"/></a>
<a href="https://tejesh-karna-portfolio.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel"/></a>
<a href="mailto:tejeshkarna96@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail"/></a>
</p>

<img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=700&size=28&duration=3000&pause=1000&center=true&width=900&lines=Frontend+Engineer;React.js+%7C+Next.js;AI+Powered+Web+Apps;Always+Learning"/>

</div>

---

## 🚀 About Me

- 💼 Frontend Software Engineer
- ⚛️ React.js, Next.js, TypeScript, React Native
- 🤖 AI integrations (OpenAI, Gemini, Claude)
- 🌱 Learning Python, Django, FastAPI, AWS, Docker, PostgreSQL, MongoDB, Redis, LLMs, Prompt Engineering, Vector DBs, System Design
- 📫 tejeshkarna96@gmail.com

## 🛠 Tech Stack

### Frontend
<img src="https://skillicons.dev/icons?i=react,nextjs,ts,js,html,css,tailwind,redux,vite"/>

### Backend
<img src="https://skillicons.dev/icons?i=nodejs,express,python,django,fastapi"/>

### Cloud & DevOps
<img src="https://skillicons.dev/icons?i=aws,docker,vercel,githubactions"/>

### Databases
<img src="https://skillicons.dev/icons?i=postgres,mongodb,redis,supabase"/>

### Tools
<img src="https://skillicons.dev/icons?i=git,github,vscode,figma,postman"/>

---

## 📊 GitHub Analytics

<p align="center">
<img height="170" src="https://github-readme-stats.vercel.app/api?username=karnatejesh2561&theme=github_dark&show_icons=true&hide_border=true"/>
<img height="170" src="https://streak-stats.demolab.com?user=karnatejesh2561&theme=github-dark&hide_border=true"/>
</p>

<p align="center">
<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=karnatejesh2561&theme=github_dark"/>
</p>

<p align="center">
<img src="https://github-profile-trophy.vercel.app/?username=karnatejesh2561&theme=darkhub&no-frame=true&column=4"/>
</p>

---

## 🌟 Featured Projects

- 🚀 PalAsk AI
- 🛒 Together Buying
- 🌞 Sun & Tan

---

> "Code. Build. Learn. Repeat."
"""
out="/mnt/data/README.md"
Path(out).write_text(md,encoding="utf-8")
print(out)
