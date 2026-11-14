<!-- ===================== HEADER ===================== -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=220&section=header&text=Adel%20Muhammad%20Haiba&fontSize=46&fontColor=ffffff&fontAlignY=38&desc=AI%20Engineer%20%C2%B7%20Data%20Engineer&descSize=20&descAlignY=60&animation=fadeIn" alt="Adel Muhammad Haiba - AI Engineer and Data Engineer" />
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&duration=3200&pause=900&color=3FA9F5&center=true&vCenter=true&width=760&height=45&lines=Fine-tuning+LLMs+with+LoRA+%26+building+RAG+pipelines;Designing+ETL+pipelines+%26+data+warehouses;Shipping+containerized+ML+services+with+Docker;Turning+theory+into+real%2C+deployable+applications" alt="Typing animation" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/adel-muhammad"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:adeldevj@gmail.com"><img src="https://img.shields.io/badge/Email-adeldevj%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/adel-dev11?tab=repositories"><img src="https://img.shields.io/badge/GitHub-Repositories-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Open%20to-AI%20%2F%20ML%20%26%20Data%20Engineering%20roles-2ea44f?style=flat-square" alt="Open to opportunities" />
  <img src="https://img.shields.io/badge/Based%20in-Cairo%2C%20Egypt-0f2027?style=flat-square&logo=googlemaps&logoColor=white" alt="Cairo, Egypt" />
  <img src="https://komarev.com/ghpvc/?username=adel-dev11&label=Profile%20views&color=2c5364&style=flat-square" alt="Profile views" />
</p>

---

## 👨‍💻 About Me

I'm an **AI Engineer and Data Engineer** and a **Computer Science graduate of Tanta University (2026)**. I build practical, well-structured systems: from **LLM-powered applications** and **machine learning models** to **ETL pipelines**, **data warehouses**, and **scalable REST services**.

I like turning theory into real applications that are understandable, maintainable, and easy to deploy, and every project below ships as a working, containerized service rather than just a notebook.

| | |
|---|---|
| 🎓 **Education** | B.Sc. Computer Science, Faculty of Computer Science & IT, Tanta University (2026) |
| 🧠 **Currently** | AI & Machine Learning Training at the National Telecommunication Institute (NTI) |
| 🎯 **Preparing for** | Huawei International Certification Exam (AI Track) |
| 🗣️ **Languages** | Arabic (Native) · English (Conversational) |
| 📫 **Reach me** | [adeldevj@gmail.com](mailto:adeldevj@gmail.com) · [LinkedIn](https://www.linkedin.com/in/adel-muhammad) |

---

## 🔭 What I'm Focused On

- 🤖 **Generative AI:** fine-tuning LLMs with **LoRA** and building **RAG** pipelines that ground answers in trusted knowledge
- 🏗️ **Data Engineering:** ETL pipelines, data warehousing (**Medallion Architecture**, **Star Schema**), and data modeling
- ⚙️ **Backend & Deployment:** scalable REST APIs documented with Swagger and deployed with **Docker**
- 👁️ **Computer Vision & Deep Learning:** CNN, transfer learning (VGG, ResNet), object detection with YOLO

---

## 🚀 Featured Projects

| Project | What it does & impact | Stack |
|:--|:--|:--|
| 🩺 **[Medical Chatbot](https://github.com/adel-dev11/medchatbot-live-demo)** | Domain-specific medical Q&A. A **Qwen** LLM fine-tuned with **LoRA**, plus a **RAG** pipeline that grounds answers in a medical knowledge base, with security mechanisms for safer responses. Deployed as a containerized REST API. | `Python` `Flask` `Qwen` `LoRA` `RAG` `MongoDB` `Docker` |
| 🛡️ **[LicenseGuard Pro](https://github.com/adel-dev11/live-demo-AI-licenses)** | Analyzes a project's `package.json`, enriches every dependency through **live npm registry calls**, and uses an ML classifier to flag risky licenses (GPL / LGPL / MIT) with replacement recommendations. Documented REST API with **Swagger UI**, deployed on Railway. | `Python` `Flask` `Scikit-learn` `REST API` `Docker` `Railway` |
| 🏦 **[SQL Data Warehouse & Analytics](https://github.com/adel-dev11/SQL-data-warehouse-project)** | Data warehouse built on **Medallion Architecture** (Bronze / Silver / Gold) with a **Star Schema**. ETL pipelines process **300 GB+ of monthly ERP and CRM data** and **cut data duplication by 30%**. | `SQL Server` `T-SQL` `ETL` `Data Modeling` |
| 📈 **[Risk Assessment AI Tool](https://github.com/adel-dev11/Risk-Assessment)** | Green Bonds financial risk analysis with automated preprocessing and data-quality validation, **ARIMA time-series forecasting**, ML classifiers, and interactive dashboards. | `Python` `Flask` `Pandas` `ARIMA` `Chart.js` |
| 📧 **[Spam Email Detector](https://github.com/adel-dev11/spam-detector)** | **Bilingual (Arabic / English)** spam detection using **Isolation Forest** anomaly detection and a TF-IDF text pipeline, with **no labeled data required**. | `Python` `Flask` `NLP` `Scikit-learn` `TF-IDF` |

<details>
<summary><b>🧩 See how two of these systems are designed</b></summary>

<br/>

**Medical Chatbot: RAG + LoRA fine-tuned LLM**

```mermaid
flowchart LR
    U([User question]) --> A[Flask REST API]
    A --> R[RAG retrieval]
    R <--> K[(MongoDB<br/>medical knowledge base)]
    R --> L[Qwen LLM<br/>fine-tuned with LoRA]
    L --> O([Grounded medical answer])
```

**SQL Data Warehouse: Medallion Architecture**

```mermaid
flowchart LR
    E[(ERP data)] --> B[🥉 Bronze<br/>raw ingestion]
    C[(CRM data)] --> B
    B --> S[🥈 Silver<br/>cleaned and standardized]
    S --> G[🥇 Gold<br/>Star Schema]
    G --> X([Analytics and ML])
```

</details>

---

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL%20%2F%20T--SQL-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=csharp&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**AI / Machine Learning**

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![LoRA](https://img.shields.io/badge/LLM%20Fine--Tuning-LoRA-7B2FF7?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-Pipelines-0A9396?style=flat-square)
![NLP](https://img.shields.io/badge/NLP-TF--IDF-2C5364?style=flat-square)
![CNN](https://img.shields.io/badge/CNN%20%7C%20Transfer%20Learning-VGG%20%2F%20ResNet-8E44AD?style=flat-square)
![YOLO](https://img.shields.io/badge/Object%20Detection-YOLO-00B4D8?style=flat-square)
![Time Series](https://img.shields.io/badge/Time%20Series-ARIMA-1D3557?style=flat-square)
![Anomaly Detection](https://img.shields.io/badge/Anomaly%20Detection-Isolation%20Forest-6A994E?style=flat-square)

**Data Engineering & Databases**

![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![ETL](https://img.shields.io/badge/ETL-Pipelines-203A43?style=flat-square)
![Data Warehouse](https://img.shields.io/badge/Data%20Warehouse-Medallion%20%7C%20Star%20Schema-0F2027?style=flat-square)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chartdotjs&logoColor=white)

**Backend & DevOps**

![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![REST API](https://img.shields.io/badge/REST%20API-Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=white)

---

## 💼 Experience & Training

| Period | Role | Highlights |
|:--|:--|:--|
| **Sep 2025 – Present** | **AI & Machine Learning Training**<br/>National Telecommunication Institute (NTI) | Intensive deep learning training with **TensorFlow / Keras**: ANN, CNN, and **transfer learning (VGG, ResNet)** applied to real image-classification projects. |
| **Jun 2025 – Aug 2025** | **Data Science Intern**<br/>CIB (Commercial International Bank) | Exploratory data analysis and predictive analytics on **real banking datasets**, supporting risk assessment and sustainable-finance decisions. |
| **Nov 2024 – Jun 2025** | **Families Committee President**<br/>Students' Union Council, Tanta University | Organized **5+ workshops** and a **job fair connecting 200+ students** with employers. |

---

## 📊 GitHub Activity

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=adel-dev11&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=adel-dev11&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=adel-dev11&theme=tokyonight&hide_border=true" alt="GitHub streak" />
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=adel-dev11&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=10" alt="GitHub trophies" />
</p>

---

## 🤝 Let's Connect

I'm open to **AI Engineer, Machine Learning Engineer, and Data Engineer** opportunities, and always happy to talk about LLMs, data platforms, or collaborating on something useful. Feedback on my repositories is very welcome.

<p align="center">
  <a href="https://www.linkedin.com/in/adel-muhammad"><img src="https://img.shields.io/badge/Message%20me%20on-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:adeldevj@gmail.com"><img src="https://img.shields.io/badge/Send%20me%20an-Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=110&section=footer" alt="footer" />
</p>
