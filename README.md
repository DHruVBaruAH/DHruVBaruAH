<!--
  GitHub PROFILE README for Dhruv Baruah.
  This goes in a repo named exactly "DHruVBaruAH" (same as your username) so GitHub shows it on your profile.
  Keep header.svg in the repo ROOT next to this file.
  TODO: fix the three project repo links below (two currently point at your profile, not the repo).
-->

<p align="center">
  <img src="./header.svg" alt="Dhruv Baruah — Backend Engineer, Machine Learning Practitioner, Systems Builder" width="850">
</p>

## About

I'm a final-year Computer Science & Engineering student who builds production backend systems and research-driven machine learning. My backend work centers on Java and Spring Boot — auth, payments, and data integrity for systems real users touch. My ML work is deliberately rigorous: I care more about evaluation that holds up under scrutiny than about a headline accuracy number. Currently looking for software and machine learning engineering roles.

## Selected Work

### House of OVRN — Production E-Commerce Backend &nbsp;·&nbsp; [Repo](https://github.com/DHruVBaruAH)

Live backend for a streetwear brand. A containerized Spring Boot service handling catalog, inventory, cart, and checkout.

- OAuth2 (Google / GitHub) and JWT authorization via Spring Security across every endpoint
- Payment-gateway integration with HMAC-SHA256 signature verification; persistent server-side cart
- Schema integrity enforced through Flyway migrations; deployed on a Docker-based cloud setup

![Java](https://img.shields.io/badge/Java_21-21262D?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-21262D?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-21262D?style=flat-square&logo=springsecurity&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-21262D?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-21262D?style=flat-square&logo=docker&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-21262D?style=flat-square&logo=flyway&logoColor=white)

### AdaptED v2 — EEG-Based ADHD Classification &nbsp;·&nbsp; [Repo](https://github.com/DHruVBaruAH/AdaptED-v2-EEG)

A study of how the *evaluation protocol* — not model quality — drives reported accuracy in EEG-based ADHD classification.

- The same 19-channel pipeline scored **93.28%** under epoch-shuffled cross-validation but only **74.17% (AUC 0.7813)** under pre-specified leave-one-subject-out (LOSO) validation
- The ~19-point gap is an evaluation-protocol artifact, not a modeling gain — LOSO is the deployment-realistic number, and it's the one I report
- Full reproducible pipeline: MNE feature extraction (266 features), feature selection, RBF-kernel SVM; 120 clinical subjects (Nasrabadi); Dockerized for repeatable runs

![Python](https://img.shields.io/badge/Python-21262D?style=flat-square&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-21262D?style=flat-square&logo=scikitlearn&logoColor=white)
![MNE](https://img.shields.io/badge/MNE-21262D?style=flat-square&logoColor=white)
![SVM](https://img.shields.io/badge/RBF--SVM-21262D?style=flat-square&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-21262D?style=flat-square&logo=docker&logoColor=white)

### AdaptED — AI Adaptive Learning Platform &nbsp;·&nbsp; [Repo](https://github.com/DHruVBaruAH)

Full-stack adaptive learning platform with a dedicated ML service for ADHD behavioral assessment.

- Stacking ensemble (LightGBM + XGBoost + CatBoost) on CPT-II clinical features; CV R² = 0.708, chosen over single models for generalization on a small dataset
- Polyglot architecture: Spring Boot + FastAPI ML service + React/TypeScript frontend
- Anthropic Claude API integration, validated end-to-end with unit and integration tests

![Spring Boot](https://img.shields.io/badge/Spring_Boot-21262D?style=flat-square&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-21262D?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-21262D?style=flat-square&logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-21262D?style=flat-square&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-21262D?style=flat-square&logo=postgresql&logoColor=white)

## Tech Stack

**Backend** &nbsp;
![Java](https://img.shields.io/badge/Java-21262D?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-21262D?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-21262D?style=flat-square&logo=springsecurity&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-21262D?style=flat-square&logo=hibernate&logoColor=white)
![REST](https://img.shields.io/badge/REST_APIs-21262D?style=flat-square&logoColor=white)

**Machine Learning** &nbsp;
![scikit-learn](https://img.shields.io/badge/scikit--learn-21262D?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-21262D?style=flat-square&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-21262D?style=flat-square&logoColor=white)
![CatBoost](https://img.shields.io/badge/CatBoost-21262D?style=flat-square&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-21262D?style=flat-square&logoColor=white)
![MNE](https://img.shields.io/badge/MNE-21262D?style=flat-square&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-21262D?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-21262D?style=flat-square&logo=numpy&logoColor=white)

**Data** &nbsp;
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-21262D?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-21262D?style=flat-square&logo=mysql&logoColor=white)

**Infrastructure & Tools** &nbsp;
![Docker](https://img.shields.io/badge/Docker-21262D?style=flat-square&logo=docker&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-21262D?style=flat-square&logo=flyway&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-21262D?style=flat-square&logo=githubactions&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-21262D?style=flat-square&logo=railway&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-21262D?style=flat-square&logo=vercel&logoColor=white)
![Git](https://img.shields.io/badge/Git-21262D?style=flat-square&logo=git&logoColor=white)

## Now

Deepening production backend work — Spring Security and OAuth2 architectures — alongside applied ML and the MLOps fundamentals that make it deployable: reproducible pipelines, containerized evaluation, and experiment tracking.

## Recognition

- **Google Developer Student Club** — Co-Head, App Development (2023–24); led sprint-based Java workshops for 50+ students
- **TCS NQT 2025** — cleared national qualifier
- **Edunet Foundation ML Program** (Shell India, 2025) — built an energy-prediction pipeline with SHAP-based explainability

<!--
  ============================================================
  OPTIONAL — GitHub stats. KEEP ONLY IF YOUR NUMBERS LOOK GOOD.
  These widgets expose your real commit count, stars, and language split.
  If your activity is light, DELETE this whole block — sparse stats read
  worse than no stats. Streak-stats deliberately omitted (most punishing if low).
  Top-languages hides html/css so your Java/Python read clearly.
  ============================================================
-->
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=DHruVBaruAH&show_icons=true&hide_border=true&count_private=true&theme=transparent&title_color=E6EDF3&text_color=8B949E&icon_color=E3B341" height="160" alt="GitHub stats">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=DHruVBaruAH&layout=compact&hide_border=true&hide=html,css&theme=transparent&title_color=E6EDF3&text_color=8B949E" height="160" alt="Top languages">
</p>

---

<p align="center">
  <a href="https://linkedin.com/in/dhruv-baruah"><img src="https://img.shields.io/badge/LinkedIn-21262D?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  &nbsp;
  <a href="https://github.com/DHruVBaruAH"><img src="https://img.shields.io/badge/GitHub-21262D?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>
  &nbsp;
  <a href="mailto:dhruvbaruah51@gmail.com"><img src="https://img.shields.io/badge/Email-21262D?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>
