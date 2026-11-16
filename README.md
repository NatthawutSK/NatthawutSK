<div align="center">

# Hi, I'm Natthawut Sornkhiew 👋

### Full-Stack Developer · Go · TypeScript · Flutter

I build products end to end — from the API and database to the web and mobile app people actually use.

📍 Bangkok, Thailand &nbsp;·&nbsp; 🎓 IT, KMITL

[![Email](https://img.shields.io/badge/Email-natthawut.sk.work%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:natthawut.sk.work@gmail.com)
![Open to opportunities](https://img.shields.io/badge/Open_to-new_opportunities-2ea44f?style=flat-square)

</div>

---

## 🧑‍💻 About me

- Working full-stack developer, open to new opportunities.
- Comfortable across the stack: **Go** services on **PostgreSQL**, **Next.js / React / Vue** front ends, and **Flutter / React Native** mobile apps.
- Have shipped to **AWS** (EC2, S3, RDS) and **Google Cloud** (Compute Engine, Cloud Run, Cloud SQL, Cloud Storage) with **Docker**, and automated deploys with **Jenkins** CI/CD pipelines.
- I care about clean architecture (hexagonal / ports & adapters), clear docs and decisions written down as ADRs.

## 🛠️ Tech stack

| | |
|---|---|
| **Languages** | <img src="https://skillicons.dev/icons?i=go,ts,js,java,dart" height="36"/> |
| **Frontend** | <img src="https://skillicons.dev/icons?i=react,nextjs,vue,tailwind,redux" height="36"/> |
| **Mobile** | <img src="https://skillicons.dev/icons?i=flutter,react,androidstudio" height="36"/> |
| **Backend** | <img src="https://skillicons.dev/icons?i=nodejs,express,spring,graphql,rabbitmq" height="36"/> |
| **Databases** | <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,firebase" height="36"/> |
| **Cloud & DevOps** | <img src="https://skillicons.dev/icons?i=aws,gcp,docker,jenkins,git,github" height="36"/> |

## 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

### 🐶 [Dog-Jod (ด็อกจด)](https://github.com/NatthawutSK/dog-jod-releases)
**AI expense tracker for Android.** Snap or share a Thai bank transfer slip — Gemini reads it and logs the expense to the user's own Google Sheet automatically.

- Watches a slip folder and records new slips in the background
- Offline queue that syncs when back online
- De-duplicates by reference number; imports password-protected credit-card statements (PDF)
- No backend: talks to Google APIs directly with least-privilege `drive.file` scope
- Self-updating releases via GitHub Releases

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google_Sheets-34A853?style=flat-square&logo=googlesheets&logoColor=white)

</td>
<td width="50%" valign="top">

### 📋 [NoTeams](https://github.com/NatthawutSK/NoTeams-Backend)
**Team project-management platform.** Create teams, run tasks on a drag-and-drop Kanban board, share files and manage members.

- Role-based access control (Owner / Member)
- Deployed on two clouds: [AWS](https://github.com/NatthawutSK/NoTeams-Backend) (EC2, S3, RDS) and [Google Cloud](https://github.com/NatthawutSK/NoTeams-Backend-Devtool) (Compute Engine, Cloud Storage, Cloud SQL)
- **CI/CD with Jenkins:** builds the Docker image, pushes it to Docker Hub, then triggers a deploy job that rolls the new container out to Compute Engine over SSH
- Team project — I built the Go backend and the deployment pipeline

![Go](https://img.shields.io/badge/Go_Fiber-00ADD8?style=flat-square&logo=go&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛒 [Ri-Shop API](https://github.com/NatthawutSK/ri-shop-api)
**E-commerce REST API built with hexagonal architecture.** Users, products, categories and orders.

- JWT auth with access & refresh tokens
- Image uploads to Google Cloud Storage
- Containerised and deployed on Cloud Run + Cloud SQL

![Go](https://img.shields.io/badge/Go_Fiber-00ADD8?style=flat-square&logo=go&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)

</td>
<td width="50%" valign="top">

### 💬 [Real-Time Chat](https://github.com/NatthawutSK/real-time-chat-go-next)
**Chat rooms with instant messaging over WebSockets.**

- Sign up / sign in / logout, user accounts in PostgreSQL
- Multiple rooms, messages pushed live to every member
- Go backend + Next.js front end

![Go](https://img.shields.io/badge/Go_Fiber-00ADD8?style=flat-square&logo=go&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=flat-square&logo=socketdotio&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ♻️ [Trash2Cash](https://github.com/NatthawutSK/Trash2Cash)
**Mobile app that makes recycling pay.** Find nearby recycling centres, check prices for each kind of waste and confirm sales by QR code.

- Google Maps integration for nearby centres
- QR-code transactions and a ranking of top-selling waste

![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Google Maps](https://img.shields.io/badge/Google_Maps-4285F4?style=flat-square&logo=googlemaps&logoColor=white)

</td>
<td width="50%" valign="top">

### 🧩 More projects

- **[EMVALAI](https://github.com/NatthawutSK/EMVALAI)** — service-oriented web app, TypeScript front end + [Java backend](https://github.com/NatthawutSK/EMVALAI-backend)
- **[StackUnderflow](https://github.com/NatthawutSK/StackUnderflow)** — Q&A forum with guest / member / admin roles (Vue)
- **Gym Tracker** — personal Telegram bot + Android app that logs workouts to Google Sheets via Apps Script

</td>
</tr>
</table>

---

<div align="center">

💌 Interested in working together? **[natthawut.sk.work@gmail.com](mailto:natthawut.sk.work@gmail.com)**

</div>
