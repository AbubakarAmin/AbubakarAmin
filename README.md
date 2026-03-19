# Abubakar Amin

<p align="left">
  <a href="mailto:abubakarmain100@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/developer-abubakar-amin/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</p>

Backend & AI systems developer. I build production APIs, payment infrastructure, multi-tenant platforms, and autonomous AI pipelines. I work primarily on the backend but am comfortable owning the full stack when a project needs it — React, Tailwind, Alpine, the works.

Open to **freelance projects** and **remote opportunities**.

---

## 🛠️ What I Work With

**Backend & APIs**
<p>
  <img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" />
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/REST_APIs-FF6B35?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Laravel_Passport-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" />
</p>

**AI & Automation**
<p>
  <img src="https://img.shields.io/badge/LangGraph-000000?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Google_Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white" />
  <img src="https://img.shields.io/badge/FAISS-FF6B35?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Multi--Agent_Systems-6B4FBB?style=for-the-badge" />
</p>

**Frontend**
<p>
  <img src="https://img.shields.io/badge/React.js-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
  <img src="https://img.shields.io/badge/Alpine.js-8BC0D0?style=for-the-badge&logo=alpine.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" />
</p>

**Infrastructure & Tools**
<p>
  <img src="https://img.shields.io/badge/Linux_VPS-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" />
  <img src="https://img.shields.io/badge/Pusher-300D4F?style=for-the-badge&logo=pusher&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
</p>

---

## 🚀 Featured Projects

### [EasyTopup — Mobile Recharge & Payment Platform](https://github.com/abubakaramin/easytopup-backend)

<p>
  <a href="https://play.google.com/store/apps/details?id=easytopup.easytopupapp.EasyTopup">
    <img src="https://img.shields.io/badge/Google_Play-414141?style=flat-square&logo=google-play&logoColor=white" />
  </a>
  <a href="https://apps.apple.com/ng/app/easy-topup-mobile-recharge/id6633411365">
    <img src="https://img.shields.io/badge/App_Store-000000?style=flat-square&logo=apple&logoColor=white" />
  </a>
  <a href="https://easytopup.pk">
    <img src="https://img.shields.io/badge/Website-0052FF?style=flat-square&logo=google-chrome&logoColor=white" />
  </a>
</p>

Live production platform for mobile recharges and utility top-ups — available on iOS, Android, and web. Built and deployed the entire backend solo in **3.5 months**, from first line of code to VPS deployment.
Actively serving **10,000+ users** across iOS and Android.
- Unified 5 payment gateways (JazzCash, EasyPaisa, MyPay, Bank Alfalah, Tap) using the Strategy pattern into a single transaction flow
- Integrated Ding API and Swich API for real-time telecom catalog queries and recharges
- Built automated fulfillment queues with fail-safe reconciliation — handles edge cases where payment succeeds but telecom delivery fails
- Full admin panel with CRUD management across users, transactions, orders, and platform config
- Real-time customer support chat via Laravel Reverb + Pusher
- OAuth2 authentication + custom device binding service for fraud prevention

`Laravel 10` `PHP` `MySQL` `Laravel Passport` `Firebase` `Pusher` `REST API` `VPS`

---

### [ReserveroHub — Multi-Tenant Booking Platform](https://github.com/abubakaramin/reserverohub)
<p>
  <a href="https://reserverohub.com">
    <img src="https://img.shields.io/badge/Live_Site-0052FF?style=flat-square&logo=google-chrome&logoColor=white" />
  </a>
</p>
A live booking and business directory platform for service-based businesses. Each owner gets an isolated workspace — services, staff, operating hours — while admins manage the full platform from a central dashboard.

- Three-role architecture (Admin / Owner / User) with separate routing files and custom middleware per role
- Multi-tenant design with fully isolated business workspaces
- Dynamic service and employee management with real-time availability toggling
- Domain-driven folder structure separating Admin, Owner, and Front logic across controllers and models
- Integrated Alpine.js + Tailwind CSS frontend via Vite for a reactive UI without a heavy JS framework
- Testing foundation configured with Pest PHP

`Laravel 11` `PHP 8.2` `MySQL` `Alpine.js` `Tailwind CSS` `Vite` `Pest`

---

### [ScholarGraph — Autonomous Multi-Agent Research Engine](https://github.com/abubakaramin/scholargraph)

A personal project. A fully autonomous AI system that takes a research domain as input and outputs a publication-ready LaTeX paper — no human in the loop. Eight specialized agents collaborate, debate, write code, run experiments, validate quality, and assemble the final document.

- Adversarial debate system (Proposer + Challenger + Moderator agents) with a hard 7.5/10 quality gate before research begins
- Engineer Agent generates *and executes* Python simulations — results and graphs feed directly into the paper
- Supervisor Agent enforces an 8.5/10 threshold using hallucination detection, SymPy math validation, and peer review simulation
- Meta Agent monitors the full pipeline for stuck loops and triggers resets automatically
- FAISS vector memory for persistent knowledge shared across all agents
- Sources live academic data from arXiv, OpenAlex, and CrossRef

`Python` `LangGraph` `Google Gemini` `FAISS` `arXiv API` `OpenAlex` `PyLaTeX` `SymPy`

---

## 📊 GitHub Stats

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=abubakaramin&layout=compact&theme=default&hide_border=true&title_color=000000&text_color=444444" />
</p>

---

## 📫 Let's Work Together

If you need backend development, API integrations, payment systems, or AI automation — feel free to reach out.

- **Email:** [abubakarmain100@gmail.com](mailto:abubakarmain100@gmail.com)
- **LinkedIn:** [developer-abubakar-amin](https://www.linkedin.com/in/developer-abubakar-amin/)
- **Phone:** +92 329 5596618
