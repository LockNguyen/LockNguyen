<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/bento-dark.svg" />
  <img src="./assets/bento-light.svg" alt="Loc Nguyen: Software Engineer" width="100%" />
</picture>

## ✦ About

I build production systems by sitting with non-technical stakeholders—product owners, business analysts, biology researchers—listening to their workflow complaints, and translating them into working software. Over **2+ years** I've shipped features across an enterprise Vue / C# .NET / SQL Server platform used in **100+ countries**, plus custom integrations, data migrations, and deployed AI tools. I've delivered measurable impact: **20x** faster dashboards, **93%** fewer database reads, and AI services with **99.9%** uptime during provider outages.

## ✦ Selected work

| Project | What it does | Impact | Stack |
|---------|-------------|--------|-------|
| VietCorner PWA | Production PWA for **20+ users** with live chat, push notifications, and RAG-based Voice AI answering Vietnamese questions from English PDFs with citations | Cut pgvector search from **1.2s to 0.25s** using connection pools; **99.9% uptime** during LLM outages via multi-provider failover | TypeScript, Python, Postgres, pgvector, Docker, Oracle Cloud, LLM APIs |
| AI Follicle Detector | Cell-imaging tool for a university biology lab; fine-tuned Mask R-CNN (Detectron2) | Detected **112 of 126 follicles** (F1 **0.89**) on held-out test set; prevented data leakage by splitting **29 animals** across train/val/test within **0.5 points** of 60/20/20 target | Python, Detectron2, PyTorch, CVAT SDK, FastAPI, Docker |
| Planning Dashboard Optimization | Made the Planning dashboard load its data faster and cut chart database reads | Load time **10s → 0.5s** (**20x faster**); chart reads down **93%** | C#, .NET, SQL Server |
| Bynder Migration Recovery | Python ETL pipeline on the Bynder API | Restored **150,000 relationships** for **22,666 assets**; saved research and marketing teams an estimated **200+ hours** of manual re-linking | Python, Bynder API |
| Developer Tracer Tool | Request tracer (OpenTelemetry, Jaeger) shipped across **14 .NET repos** | **3 teammates** used it to cut load times **50–70%** on **3 pages** | C#, .NET, OpenTelemetry, Jaeger |
| Security Vulnerability Remediation | Optimized O(n²) algorithms to O(n) and added request throttling to prevent CPU exhaustion attacks | Remediated a **critical security vulnerability** | C#, .NET |

<details>
<summary>VietCorner PWA, in depth</summary>

**The approach**: Built a production PWA with RAG-based Voice AI and a resilient AI microservice with multi-provider failover and exponential backoff on Oracle Cloud using Docker. Ran user acceptance interviews with congregation members, translated their feedback into a prioritized backlog, and documented expected behavior per feature.

**The result**: Cut pgvector search from **1.2s to 0.25s** using connection pools and achieved **99.9% uptime** during LLM outages via multi-provider failover.

</details>

<details>
<summary>AI Follicle Detector, in depth</summary>

**The approach**: Led a **6-person team** delivering a cell-imaging tool for a university biology lab, gathering requirements from the researchers and fine-tuning Mask R-CNN (Detectron2). Scored the model against a held-out test set of **126 follicles** and prevented data leakage with a splitter keeping each of **29 animals** in one split within **0.5 points** of a 60/20/20 split target (50/17/17 images).

**The result**: Detected **112 of 126 follicles** (F1 **0.89**) on the held-out test set.

</details>

## ✦ Experience

| Period | Role | Company | Highlights |
|--------|------|---------|------------|
| *Sep 2026 – Present* | AI Software Engineer (Volunteer) | Vietnamese Baptist Church | Built and deployed a production PWA for **20+ users** with RAG-based Voice AI; cut pgvector search from **1.2s to 0.25s** and achieved **99.9% uptime** during LLM outages. |
| *Jan 2025 – Sep 2026* | Junior Software Engineer (Full Stack) | OneHope | Shipped internal developer tooling across **14 .NET repos** that **3 teammates** used to cut load times **50–70%** on **3 pages**; made Planning dashboard **20x faster** (10s → 0.5s) and cut chart reads **93%**; remediated a **critical security vulnerability**; delivered **40+ production features and fixes**. |
| *May 2024 – Aug 2024* | Software Engineer Intern | OneHope | Executed a data migration recovery with a Python ETL pipeline on the Bynder API, restoring **150,000 asset relationships** for **22,666 assets** and saving an estimated **200+ hours**; delivered **15+ production features and fixes**. |

## ✦ Credentials

- **B.S. Computer Science: Software Engineering**, Liberty University, *Aug 2022 – Aug 2026*

## ✦ Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=cs,py,ts,js,cpp,java,vue,html,dotnet,fastapi,pytorch,react,nextjs,postgres,docker,supabase&theme=dark&perline=8" alt="cs, py, ts, js, cpp, java, vue, html, dotnet, fastapi, pytorch, react, nextjs, postgres, docker, supabase" />
</p>

<p align="center"><a href="mailto:loc.software.dev@gmail.com"><b>Email</b></a> &nbsp;·&nbsp; <a href="https://linkedin.com/in/lock-nguyen"><b>LinkedIn</b></a> &nbsp;·&nbsp; <a href="https://loc-nguyen.netlify.app/"><b>Website</b></a> &nbsp;·&nbsp; <a href="https://github.com/LockNguyen"><b>GitHub</b></a></p>

## ✦ Projects

- [vuln-priority-engine](https://github.com/LockNguyen/vuln-priority-engine) — Turn a scanner's flat CVE dump into a risk-ranked, SLA-bucketed remediation queue using EPSS exploit-probability + CISA KEV + asset criticality.
- [supply-chain-optimizer](https://github.com/LockNguyen/supply-chain-optimizer) — AI-powered inventory management system that predicts demand 8 weeks ahead, optimizes stock levels, and reduces carrying costs by 40%.
- [advanced-rag-llm-app](https://github.com/LockNguyen/advanced-rag-llm-app) — This project is a self-contained summer-internship-level implementation of an advanced AI application that combines Retrieval-Augmented Generation (RAG)…
- [fraud-detection-system](https://github.com/LockNguyen/fraud-detection-system) — Protecting $20B+ in annual e-commerce transactions with ML-powered fraud detection
- [elt-pipeline-dbt-snowflake-airflow](https://github.com/LockNguyen/elt-pipeline-dbt-snowflake-airflow) — A production-grade ELT pipeline that extracts data from multiple public APIs (Reddit, OpenWeather, and a SaaS PostgreSQL database), loads raw data into…
