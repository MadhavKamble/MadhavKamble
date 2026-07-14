<h1 align="center">Hi, I'm Madhav Kamble 👋</h1>
<h3 align="center">Data Engineer in training · MTech @ IIIT Allahabad · GenAI & Applied Research</h3>

<br>

```java
/**
 * MTech Data Engineering, IIIT Allahabad (2025-27)
 * Placement Coordinator, Batch 2025
 */
public class MadhavKamble implements DataEngineer, ResearchAssistant {

    private final String location   = "Prayagraj, India";
    private final String[] focus    = {"Data Engineering", "GenAI/Agentic AI", "SDE"};
    private final String thesis     = "XAI-driven Genetic Algorithms for Last-Mile Routing (VRP)";
    private final String currently  = "Placement prep — DSA, System Design, Core CS";

    @Override
    public Pipeline build(String source) {
        return new Pipeline(source, "production");
    }

    @Override
    public String toString() {
        return "Turning messy data into reliable pipelines, one commit at a time.";
    }
}
```

<br>

## 🏗️ System Architecture

```mermaid
flowchart LR
    A[("🎓 Education\nBTech · 9.31 CGPA\nMTech @ IIIT-A · 8.46 CGPA")] --> B{{"⚙️ Core Skills"}}
    B --> C["🐍 Python · SQL · Java"]
    B --> D["📦 Kafka · Airflow · dbt · Delta Lake"]
    B --> E["🤖 LLM Agents · RAG"]

    C & D & E --> F[["🚀 Projects"]]
    F --> G["Autonomous Data-Analyst Agent\nNL→SQL multi-agent system"]
    F --> H["Ride-Sharing Analytics Platform\nKafka→PySpark→Delta Lake streaming"]
    F --> P["NewsGlobe\n12-phase geospatial pipeline"]

    G & H & P --> I[("🔬 Research")]
    I --> J["XAI-Enhanced GA\nfor Last-Mile Routing"]
    I --> Q["MIGA\nGA-based Missing Data Imputation"]

    J & Q --> K{{"📡 Output"}}
    K --> L["GitHub"]
    K --> M["LinkedIn"]
    K --> R["Portfolio"]
    K --> N["Open to DE / SDE / GenAI roles"]
```

<br>

## 🔬 Research

**XAI-Enhanced Genetic Algorithm for Last-Mile Routing** *(MTech Thesis)*
An audit and extension of a published GA-based approach for last-mile delivery routing (Kim, Khir & Lee, IEEE TEVC). Found a normalization bug in the released code that inflated the reported baseline, showed the paper's SHAP-based weighting scheme was redundant against a simpler closed-form decomposition weight, and identified zone-order error as the dominant error source over intra-zone error. A memetic 2-opt refinement beat the original paper's result, and a follow-up exact-DP substitution pushed performance below 3rd place on the Amazon LMRRC leaderboard.

**MIGA — Genetic-Algorithm-Based Missing Data Imputation**
First open-source Python implementation of MIGA (Figueroa-García et al., *Information Sciences*, 2023). Benchmarked against MICE, KNN, and mean imputation across 7 UCI datasets with Wilcoxon significance testing. Extended the original method with Ledoit-Wolf shrinkage covariance, adaptive mutation scheduling, MNAR evaluation, and a kurtosis-augmented fitness function — surfacing an Fr→RMSE orthogonality result along the way. Ongoing research at IIIT Allahabad.

<br>

## 🚀 Featured Projects

| Project | Description | Stack |
|---|---|---|
| **[Autonomous Data-Analyst Agent](https://github.com/MadhavKamble/autonomous-data-analyst-agent)** | Multi-agent system (Planner → RAG → SQL Generator → Executor → Critic → Summarizer) converting NL questions into verified SQL, with a bounded self-correction loop and 67 passing pytest tests. [Live demo →](https://autonomous-data-analyst-agent-adaa.vercel.app/) | FastAPI, React, PostgreSQL, Groq (Llama 3.3 70B), RAG, pgvector |
| **[Real-Time Ride-Sharing Analytics Platform](https://github.com/MadhavKamble/realtime-rideshare-pipeline)** | End-to-end streaming platform simulating Uber/Ola internals — Kafka ingestion through PySpark Structured Streaming into a Delta Lake medallion (Bronze→Silver→Gold) architecture, with an ML-powered surge pricing model and a live dashboard. Redis caching cut dashboard read latency from ~10s to <1ms; 4 production Airflow DAGs orchestrate refresh, retraining, data quality, and cache warmup across 10 Docker services | Python, Kafka, PySpark, Delta Lake, Airflow, XGBoost, MLflow, Redis, Streamlit, Docker |
| **NewsGlobe** | 12-phase geospatial data pipeline with orchestration and testing at scale | dbt, Airflow, PostGIS, 102 pytest + 22 dbt tests |

<br>

## 🧰 Core Skills

**Languages**
<p align="left">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black" />
  <img src="https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white" />
</p>

**Frameworks**
<p align="left">
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white" />
</p>

**Databases**
<p align="left">
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/pgvector-336791?style=flat&logo=postgresql&logoColor=white" />
</p>

**Data Engineering**
<p align="left">
  <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=flat&logo=apachekafka&logoColor=white" />
  <img src="https://img.shields.io/badge/Apache_Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white" />
  <img src="https://img.shields.io/badge/PySpark-E25A1C?style=flat&logo=apachespark&logoColor=white" />
  <img src="https://img.shields.io/badge/Delta_Lake-00ADD8?style=flat&logo=databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/dbt-FF694B?style=flat&logo=dbt&logoColor=white" />
  <img src="https://img.shields.io/badge/PostGIS-336791?style=flat&logo=postgresql&logoColor=white" />
</p>

**GenAI & ML Engineering**
<p align="left">
  <img src="https://img.shields.io/badge/Groq-F55036?style=flat&logo=groq&logoColor=white" />
  <img src="https://img.shields.io/badge/Llama_3.3-0467DF?style=flat&logo=meta&logoColor=white" />
  <img src="https://img.shields.io/badge/RAG-4B8BBE?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/XGBoost-EC0000?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white" />
</p>

**Research & Optimization**
<p align="left">
  <img src="https://img.shields.io/badge/Genetic_Algorithms-6A1B9A?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/NSGA--II-6A1B9A?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/SHAP-8E44AD?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Wilcoxon_Testing-8E44AD?style=flat&logo=python&logoColor=white" />
</p>

**Data & ML**
<p align="left">
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Seaborn-3776AB?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/Hadoop-66CCFF?style=flat&logo=apachehadoop&logoColor=black" />
</p>

**Tools**
<p align="left">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=flat&logo=visualstudiocode&logoColor=white" />
  <img src="https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white" />
</p>

**Relevant Coursework:** Big Data Analytics · Data Visualisation · Machine Learning · Operating Systems · Computer Networks · DBMS

<br>

## 🏆 Achievements

- LeetCode Rating: **1669**
- CodeChef Rating: **1441**
- Runner-Up — Sinhgad Hackathon 2k23
- Runner-Up — Sinhgad Hackathon 2k22

<br>

## 📜 Certifications & Licenses

- **0 to 100 Full-Stack Cohort** — 100xDevs (2024)
- **Cyber Threat Intelligence 101** — arcX (2024)
- **Getting Started with Enterprise Data Science** — IBM (2024)

<br>

## 🐍 Contribution Snake

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/MadhavKamble/MadhavKamble/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/MadhavKamble/MadhavKamble/output/github-contribution-grid-snake.svg" />
    <img alt="contribution snake" src="https://raw.githubusercontent.com/MadhavKamble/MadhavKamble/output/github-contribution-grid-snake.svg" />
  </picture>
</p>

<br>

## 📊 GitHub Stats

<p align="left">
  <img src="https://github-readme-stats-sigma-five.vercel.app/api?username=MadhavKamble&show_icons=true&theme=default&hide_border=true" height="165"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=MadhavKamble&hide_border=true" height="165"/>
</p>

<br>

## 🎲 Beyond the Code

```bash
$ whoami
madhav — mostly caffeine and constant integration, occasionally sleep

$ cat /etc/interests
🏎️  F1 — will debate strategy calls at 1am
🏏  Cricket — silent during a chase, unbearable after
🤖  Serial Claude consumer — if it can be asked, I've asked it
🥦  Vegetarian — don't ask about the mess food

$ ./run_forever.sh
[perpetually] compiling code, watching qualifying, arguing with an LLM until it agrees with me
```

<br>

## 📫 Connect

<p align="left">
  <a href="https://www.linkedin.com/in/madhav-kamble-64710a221/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white"/></a>
  <a href="https://github.com/MadhavKamble"><img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white"/></a>
  <a href="https://madhav-kamble.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=flat&logo=vercel&logoColor=white"/></a>
  <a href="mailto:madhavukamble@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white"/></a>
</p>

<br>

<p align="center"><i>compiled with 0 errors, 12 existential crises.</i></p>
