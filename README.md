<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B132B,50:1C2541,100:3A506B&height=220&section=header&text=Sana%20Saki&fontSize=56&fontColor=FFFFFF&animation=fadeIn&fontAlignY=38&desc=Software%20Engineering%20%7C%20Computer%20Engineering%20at%20Lorestan%20University&descSize=18&descAlignY=58&descColor=E2E8F0" width="100%"/>

<h3 align="center">Backend Developer + AI</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&duration=3200&pause=900&color=3A506B&center=true&vCenter=true&width=720&lines=Python+%7C+FastAPI+%7C+PostgreSQL+%7C+Redis;Building+scalable%2C+production-ready+APIs;Clean+architecture.+Reliable+services.;Learning+by+building%2C+breaking+and+fixing." alt="Typing animation" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-0B132B?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-1C2541?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Django-3A506B?style=flat-square&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/Machine%20Learning-0B132B?style=flat-square&logoColor=white" />
</p>

---

## 👩‍💻 About Me

Backend Developer focused on **Python** and **FastAPI**, building **production-ready** APIs and **scalable** server-side systems. My core work is designing RESTful APIs, implementing authentication and RBAC, managing asynchronous workflows with **Celery**, and working with **PostgreSQL**, **Redis** and **Docker**, with an emphasis on clean architecture and maintainable code.

Alongside backend development I work with **Django** and **Machine Learning**. I build **intelligent backend systems** with FastAPI and ML, where **ML systems** are trained, served and integrated as reliable backend services.

🎓 Computer Engineering student at **Lorestan University**

> I believe in learning by building, breaking things, and fixing them better than before ✨

---

## 🎯 Focus Areas

| | Area | Details |
|---|---|---|
| 🐍 | **Python Backend Development** | Clean, maintainable Python with layered architecture and clear separation of concerns |
| ⚡ | **FastAPI & REST APIs** | Typed, validated, well-documented APIs with authentication and role-based access control |
| 🗄️ | **Databases** | Relational schema design, SQL, migrations and query work with PostgreSQL and SQLite |
| 🚀 | **Async, Caching & Deployment** | Celery background tasks, Redis caching, Docker containers behind Nginx on Linux |
| 🌿 | **Django** | Web applications and APIs with Django |
| 🤖 | **Machine Learning** | Data analysis, model training and evaluation with the Python data stack |

---

## 🏗️ Backend Architecture

```mermaid
flowchart TB
    C([Client]) -->|HTTPS| N[Nginx<br/>Reverse Proxy]

    subgraph API[FastAPI Service]
        RT[Routers<br/>Auth and RBAC]
        SV[Service Layer<br/>Business Logic]
        RP[Repository Layer<br/>SQLAlchemy]
        ML[ML Inference<br/>scikit-learn]
        RT --> SV
        SV --> RP
        SV --> ML
    end

    subgraph INFRA[Data and Async Layer]
        RD[(Redis<br/>Cache and Broker)]
        W[Celery Workers]
        DB[(PostgreSQL)]
        RD -->|consume tasks| W
    end

    N --> RT
    SV -->|cache / enqueue| RD
    RP --> DB
    W --> DB

    classDef core fill:#1C2541,stroke:#3A506B,color:#fff;
    classDef data fill:#0B132B,stroke:#3A506B,color:#fff;
    class RT,SV,RP,ML,W core;
    class RD,DB data;
```

<p align="center"><sub>Containerized with Docker · Served behind Nginx</sub></p>

---

## 🛠️ Tech Stack

<h4 align="center">Languages</h4>
<p align="center">
  <img src="https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" />
</p>

<h4 align="center">Backend & API Development</h4>
<p align="center">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/REST%20API%20Design-0B132B?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/Authentication%20%26%20RBAC-3A506B?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white" />
</p>

<h4 align="center">Databases & Data Layer</h4>
<p align="center">
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLite-07405e?style=flat-square&logo=sqlite&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white" />
  <img src="https://img.shields.io/badge/Alembic-3B5FC0?style=flat-square&logoColor=white" />
</p>

<h4 align="center">Async Processing & Caching</h4>
<p align="center">
  <img src="https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis%20(Broker%20%26%20Cache)-DC382D?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Background%20Tasks-1C2541?style=flat-square&logoColor=white" />
</p>

<h4 align="center">Architecture & Engineering Concepts</h4>
<p align="center">
  <img src="https://img.shields.io/badge/Clean%20Architecture-0B132B?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/Layered%20Architecture-1C2541?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/Separation%20of%20Concerns-3A506B?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/Database%20Design%20%26%20Migrations-0B132B?style=flat-square&logoColor=white" />
</p>

<h4 align="center">DevOps & Deployment</h4>
<p align="center">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />
</p>

<h4 align="center">AI & Machine Learning</h4>
<p align="center">
  <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=matplotlib&logoColor=white" />
</p>

<h4 align="center">Tools & Workflow</h4>
<p align="center">
  <img src="https://img.shields.io/badge/Git-F05033?style=flat-square&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-121011?style=flat-square&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white" />
  <img src="https://img.shields.io/badge/Insomnia-4000BF?style=flat-square&logo=insomnia&logoColor=white" />
  <img src="https://img.shields.io/badge/VSCode-0078D4?style=flat-square&logo=visual-studio-code&logoColor=white" />
</p>

---

## 🚀 Currently Focused On

- ⚡ Deepening my FastAPI skills: project structure, testing and deployment
- 🌿 Building more with Django
- 🤖 Applying Machine Learning in backend projects

<!--
## 📌 Featured Projects
- **[project-name](https://github.com/ISanaSaki/project-name)**: one line on what it does, the stack (FastAPI, PostgreSQL, Redis, Docker) and the key result.
-->

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://raw.githubusercontent.com/iSanaSaki/iSanaSaki/main/profile-summary-card-output/2077/0-profile-details.svg" alt="Profile Details" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/iSanaSaki/iSanaSaki/main/profile-summary-card-output/2077/1-repos-per-language.svg" alt="Top Languages by Repo" />
  <img src="https://raw.githubusercontent.com/iSanaSaki/iSanaSaki/main/profile-summary-card-output/2077/2-most-commit-language.svg" alt="Top Languages by Commit" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/iSanaSaki/iSanaSaki/main/profile-summary-card-output/2077/3-stats.svg" alt="GitHub Stats" />
  <img src="https://raw.githubusercontent.com/iSanaSaki/iSanaSaki/main/profile-summary-card-output/2077/4-productive-time.svg" alt="Productive Time" />
</p>

---

## 📈 Contributions

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=iSanaSaki&theme=react-dark&hide_border=true&area=true" alt="Contribution Graph" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/iSanaSaki/iSanaSaki/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/iSanaSaki/iSanaSaki/output/github-contribution-grid-snake.svg">
    <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/iSanaSaki/iSanaSaki/output/github-contribution-grid-snake.svg">
  </picture>
</p>

---

## 📫 Let's Connect

<p align="center">
  <a href="mailto:sanasaki85@gmail.com"><img src="https://img.shields.io/badge/Email-0B132B?style=flat-square&logo=gmail&logoColor=white" /></a>
  <a href="https://t.me/sana_saki"><img src="https://img.shields.io/badge/Telegram-1C2541?style=flat-square&logo=telegram&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/sana-saki"><img src="https://img.shields.io/badge/LinkedIn-3A506B?style=flat-square&logo=linkedin&logoColor=white" /></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B132B,50:1C2541,100:3A506B&height=120&section=footer" width="100%"/>
