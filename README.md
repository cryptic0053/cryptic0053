<h1 align="center">Anirban Ghosh Argha</h1>

<p align="center">
  <b>Database Systems &amp; Query Processing</b> · Computer Science &amp; Engineering, KUET
</p>

<p align="center">
  <a href="https://portfolio-cryptic0053s-projects.vercel.app">
    <img src="https://img.shields.io/badge/%F0%9F%8C%90%20VIEW%20MY%20PORTFOLIO-0e75b6?style=for-the-badge&labelColor=0e75b6" height="42" alt="View my portfolio" />
  </a>
</p>

<p align="center">
  <a href="https://portfolio-cryptic0053s-projects.vercel.app/Anirban_Ghosh_Argha_Research_CV.pdf"><img src="https://img.shields.io/badge/Research%20CV-14395C?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="Research CV" /></a>
  <a href="https://portfolio-cryptic0053s-projects.vercel.app/Anirban_Ghosh_Argha_CV.pdf"><img src="https://img.shields.io/badge/Software%20CV-4A5560?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="Software CV" /></a>
  <a href="https://www.linkedin.com/in/anirban-argha-4a20b7278/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:anirbanargha0053@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<p align="center">
  I work on database systems, query processing and ranking queries.<br/>
  Alongside that I build backend services with Django, FastAPI, Docker and Kubernetes.
</p>

---

## Research

**HyDART-RQ: A Hybrid Framework for Durable Reverse Top-*k* Query over Time Varying Preferences**
Submitted to the 29th International Conference on Computer and Information Technology (ICCIT 2026) — *under review*.
Undergraduate thesis, graded A+. Supervisor: Dr. K. M. Azharul Hasan, Professor, Department of CSE, KUET.

A durable reverse top-*k* query asks which users keep a given item in their top-*k* list for at least a
fraction of a time interval. Answering it exactly means scoring every user–item pair in every window,
which does not scale.

The framework introduces the **Durable Quantile Rank (DQR)**, an order-statistic formulation that reduces
the durability predicate to a single threshold test across temporal windows, and pairs rank-table-based
candidate filtering with exact verification. Because DQR is monotone, thresholding per-window rank lower
bounds cannot discard a durable user; where sampled rank tables give estimates rather than bounds,
conformal risk control calibrates the selection.

Evaluated on MovieLens, a Netflix subset and Amazon Video Games. Across 200 held-out test queries, exact
configurations verified approximately **10–15 candidates** from populations of up to **5,000 users**, a
measured **15–20× wall-clock speed-up** over exhaustive verification under the same scoring implementation.

> Implementation available on request while the manuscript is under review.

---

## Selected projects

| Project | Domain | Stack | What it does |
| :--- | :--- | :--- | :--- |
| **[Finch-EC](https://github.com/cryptic0053/Finch-EC)** | E-Commerce + POS | `Vue 3` `Django REST` `PostgreSQL` `K8s` | Storefront and point-of-sale sharing one catalogue — Stripe checkout, JWT auth, Prometheus/Grafana observability |
| **[Learning Management System](https://github.com/cryptic0053/Learning-Management-System)** | EdTech | `React` `Django REST` `PostgreSQL` | Role-based access control and JWT auth over a React frontend |
| **[zero-downtime-app](https://github.com/cryptic0053/zero-downtime-app)** | DevOps | `Kubernetes` `Docker` `Django` | Rolling deployments with readiness/liveness probes — no dropped requests during upgrades |
| **[fastapi_lambda](https://github.com/cryptic0053/fastapi_lambda)** | Serverless | `FastAPI` `AWS Lambda` `Mangum` | Deployment template running FastAPI on Lambda, container images or zip bundles |
| **[Movie Recommender System](https://github.com/cryptic0053/Movie-Recommender-System)** | Recommendation | `Python` `scikit-learn` `Streamlit` | Content-based recommender over a 5,000-title catalogue, ranked by cosine similarity |

---

## Toolbox

`Python` · `C++` · `SQL` · `Java` · `JavaScript/TypeScript`
`PostgreSQL` · `MySQL` · `MongoDB` · `SQLite`
`Django` · `Django REST Framework` · `FastAPI` · `React` · `Next.js`
`Docker` · `Kubernetes` · `GitHub Actions` · `AWS Lambda` · `Prometheus` · `Grafana` · `Linux`

---

<p align="center">
  <i>Fundamental IT Engineer (FE), ITEE Level 2 — Bangladesh Computer Council, April 2026</i>
</p>
