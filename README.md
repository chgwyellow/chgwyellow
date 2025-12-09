# 👋 Hi, I'm Arthur (chgwyellow)

I enjoy immersing myself in the world of programming —  
exploring data, building systems, and creating things that actually work.  
My goal is to grow into someone who can turn ideas into scalable and reliable data solutions.

---

## 🌟 About Me

- 🚀 Passionate about **Data Engineering**, **Data Science**, **Machine Learning**, and **Deep Learning**
- 🔧 Strengthening skills in Python, SQL, data pipelines, databases, and cloud-native tools
- 🧠 Exploring **LLM workflows**, especially **RAG**, vector databases, and prompt engineering
- 🌱 Learning by building real projects and experimenting with real-world datasets
- 💼 Open to opportunities in **DE / DS / ML Engineering**

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://raw.githubusercontent.com/chgwyellow/chgwyellow/main/profile-summary-card-output/solarized/0-profile-details.svg" alt="Profile Details" />
  <br/>

  <img src="https://raw.githubusercontent.com/chgwyellow/chgwyellow/main/profile-summary-card-output/solarized/1-repos-per-language.svg" height="170" alt="Repos per Language" />
  <img src="https://raw.githubusercontent.com/chgwyellow/chgwyellow/main/profile-summary-card-output/solarized/2-most-commit-language.svg" height="170" alt="Most Commit Language" />
  <br/>

  <img src="https://raw.githubusercontent.com/chgwyellow/chgwyellow/main/profile-summary-card-output/solarized/3-stats.svg" height="170" alt="Stats" />
  <img src="https://raw.githubusercontent.com/chgwyellow/chgwyellow/main/profile-summary-card-output/solarized/4-productive-time.svg" height="170" alt="Productive Time" />
</div>

<div align="center">
  <br>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/chgwyellow/chgwyellow/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/chgwyellow/chgwyellow/output/github-contribution-grid-snake.svg">
    <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/chgwyellow/chgwyellow/output/github-contribution-grid-snake.svg">
  </picture>
</div>

---

## 🛠️ Tech Stack

| Category | Skills |
| :--- | :--- |
| **Languages** | <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/SQL-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white"/> |
| **Data Engineering** | <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/> <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/> |
| **Data Science & ML** | <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/> <img src="https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/> <img src="https://img.shields.io/badge/LightGBM-3A433A?style=for-the-badge&logo=lightgbm&logoColor=white"/> | <img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white"/> |

---

## 📂 Featured Project

### 🔹 **Air Quality Prediction System (End-to-End ML Pipeline)**

📌 **A comprehensive machine learning project predicting AQI using real-world environmental data.**
* **Pipeline:** Designed a robust workflow including Data Cleaning, Feature Engineering, and Model Evaluation.
* **Model Selection:** Conducted comparative analysis between **Deep Learning (LSTM)** and **Gradient Boosting (LightGBM)**.
* **Result:** **LightGBM** achieved superior performance (higher R²) and efficiency compared to LSTM for this tabular dataset.
* **Deployment:** Containerized the solution using Docker and deployed a user interface via Streamlit.

🔗 Repo: https://github.com/chgwyellow/air_pollution

### 🏗️ Workflow Architecture

```mermaid
graph LR
    classDef data fill:#16161e,stroke:#89ddff,stroke-width:2px,color:#fff
    classDef model fill:#16161e,stroke:#f5bde6,stroke-width:3px,color:#fff
    classDef deploy fill:#16161e,stroke:#a6e3a1,stroke-width:2px,color:#fff,stroke-dasharray: 8 5
    
    subgraph Pipeline [🐳 **Dockerized ML Pipeline**]
        direction LR
        Raw[**📂 Raw Data**]:::data --> Clean(**🧹 Cleaning**):::data
        Clean --> Feat(**⚙️ Feature Eng.**):::data
        Feat --> Train{**🤖 Model Building**}:::model
        
        Train --> Eval[**📉 Eval & SHAP**]:::model
        Train -.-> App[**🚀 Streamlit App**]:::deploy
    end

    linkStyle default stroke:#9aa5ce,stroke-width:3px;
```

---

## 📫 Contact Me
📧 **dinnis1107@gmail.com**
