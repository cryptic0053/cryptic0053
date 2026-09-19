<h1 align="center">Anirban Argha</h1>

<p align="center">
  <b>Backend &amp; DevOps Engineer</b> · Computer Science &amp; Engineering, KUET
</p>

<p align="center">
  I build backend systems and the infrastructure that runs them — Django and FastAPI services,<br/>
  containerised and deployed on Kubernetes, with CI/CD and observability wired in from the start.<br/>
  My undergraduate thesis is on efficient <b>durable reverse top-k queries</b> over temporal recommendation data.
</p>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anirban-argha-4a20b7278/)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-cryptic0053s-projects.vercel.app)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:anirbanargha0053@gmail.com)
[![Profile Views](https://komarev.com/ghpvc/?username=cryptic0053&label=Views&color=0e75b6&style=for-the-badge)](https://github.com/cryptic0053)

</div>

---

## Research

**[Durable Reverse Top-*k* Queries](https://github.com/cryptic0053/Thesis-Reverse-Top-K-Query-)** — undergraduate thesis

A hybrid *filter–verify* framework for finding which users durably rank a given item in their top *k* over time. A cheap approximate filter prunes >96% of users; an exact verifier runs only on the survivors.

Along the way I found that the published baselines had **inverted score conventions** — the filters were systematically selecting the *worst* candidates while appearing to work. Correcting it took recall from **0.00 to 1.00** on MovieLens and produced **20–69× speedups** on Amazon Video Games.

---

## Selected projects

| Project | Domain | Stack | What it does |
| :--- | :--- | :--- | :--- |
| **[Finch-EC](https://github.com/cryptic0053/Finch-EC)** | E-Commerce + POS | `Vue 3` `Django REST` `PostgreSQL` `K8s` | Storefront and point-of-sale sharing one catalogue — Stripe checkout, JWT auth, Prometheus/Grafana/Loki observability |
| **[Learning Management System](https://github.com/cryptic0053/Learning-Management-System)** | EdTech | `React` `Django REST` `PostgreSQL` | Role-based access control and JWT auth over a React frontend |
| **[zero-downtime-app](https://github.com/cryptic0053/zero-downtime-app)** | DevOps | `Kubernetes` `Docker` `Django` | Blue-green and rolling deployments with readiness/liveness probes — no dropped requests during upgrades |
| **[fastapi_lambda](https://github.com/cryptic0053/fastapi_lambda)** | Serverless | `FastAPI` `AWS Lambda` `Mangum` | Template for running FastAPI on Lambda behind API Gateway |
| **[Hybrid Prime (FPGA)](https://github.com/cryptic0053/Hybrid_Prime_Project)** | Hardware | `Verilog` `Basys 3` `Vivado` | Primality testing in structural Verilog — sieve lookup vs. trial division, a space/time tradeoff in silicon |
| **[Dog Disease Detection](https://github.com/cryptic0053/DG)** | Deep Learning | `TensorFlow` `Keras` `EfficientNet` | Skin-disease classifier with TFLite export, served as a web app |

---

## Tech

**Backend**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/DRF-A30000?style=flat-square&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)

**Frontend**
![Vue](https://img.shields.io/badge/Vue_3-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)

**Infrastructure**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

**Data & ML**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)

**Systems**
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Verilog](https://img.shields.io/badge/Verilog-1A73E8?style=flat-square&logo=v&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## Coursework

Laboratory work from the CSE programme at KUET, one repository per course — [browse all](https://github.com/cryptic0053?tab=repositories&q=CSE-).

`Computer Graphics` · `Image Processing & Computer Vision` · `Machine Learning` · `Artificial Intelligence` · `Computer Networks` · `Digital System Design` · `Compiler Design` · `Operating Systems` · `Mobile Computing` · `Database Systems` · `Software Engineering` · `Web Programming` · `Peripherals & Interfacing` · `Technical Writing`

---

<div align="center">

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=cryptic0053&show_icons=true&theme=tokyonight&count_private=true&hide_border=true)](https://github.com/cryptic0053)
[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=cryptic0053&layout=compact&theme=tokyonight&hide_border=true)](https://github.com/cryptic0053)

[![GitHub Streak](https://streak-stats.demolab.com?user=cryptic0053&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

</div>
