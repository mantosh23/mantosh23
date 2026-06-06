<div align="center">

# 👋 Hi there, I'm Mantosh Kumar

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mantosh23)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mantosh23)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/u/mantosh23)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mantoshkumar4382@gmail.com)

🎓 **Computer Science & Engineering (AIML)** at **SRM Institute of Science and Technology** (`CGPA: 9.12 / 10.0`, 2023–2027)  
📍 Based in **Chennai, India**

> *"Building intuitive, high-performance software, explainable ML models, and production AI systems."*

</div>

---

### 🚀 About Me

- 💻 **Software & Applied ML Engineer** with experience spanning production web applications, high-throughput backend APIs, deep learning sequence modeling, and native iOS development.
- 📱 Shipped **[Everlore](https://apps.apple.com/in/app/everlore/id6761700355)** on the **Apple App Store** (500+ downloads).
- 🧠 Strong technical foundation in **Data Structures & Algorithms**, **Deep Learning (BiGRU / NLP)**, **Explainable AI (SHAP / Tree Ensembles)**, and **Distributed Cloud Backends**.
- 🏆 **Top 100 Nationally** in Atal Innovation Mission (NITI Aayog) National Innovation Challenge.
- 🎭 Outside of engineering, I enjoy acting & monologue performance (2nd Place at VIT Vellore & VIT Chennai) and public speaking.

---

### 💼 Work Experience

- **Frontend Engineering Intern** @ **Zudoc** *(Sep 2026 – Present | Remote)*
  - Building responsive healthcare web applications using React.js and REST APIs.
  - Reduced registration form abandonment by **25%** through client-side state caching and regex input validation across 500+ patient records.

- **Developer Trainee** @ **Madras Mindworks** *(Jun 2026 – Sep 2026 | Chennai, India)*
  - Resolved 15 staging API routing and webhook defects with backend engineering teams.
  - Slashed recurring monthly cloud hosting expenses from **INR 30,000 to under INR 100** by configuring Cloudflare CDN caching rules.
  - Documented REST API specifications and developed Swift interaction modules for 6 visionOS prototypes.

- **iOS Developer Intern (Agile Lead)** @ **Infosys** *(Mar 2026 – Apr 2026 | Mysore, India)*
  - Led sprint planning and backlog reviews for a 10-person intern team as Agile Lead in Jira.
  - Excluded invalid GPS telemetry points in PostgreSQL using `ST_MakeEnvelope` spatial queries.
  - Integrated Mapbox SDK into a Swift mobile application to render active routes across 50 driver trips.

- **iOS Developer Trainee** @ **SRM iOS Development Centre** *(Aug 2025 – May 2026 | Chennai, India)*
  - Completed rigorous product engineering curriculum (selected among Top 100 of 1,000+ applicants).
  - Shipped **Everlore** on the Apple App Store, synchronizing 15 SwiftUI views across 8 Supabase tables.

---

### 🛠️ Tech Stack & Skills

```
Languages:              Python · Java · SQL · JavaScript (ES6+) · TypeScript · Swift
AI, ML & NLP:           XGBoost · SHAP · TensorFlow · Keras · scikit-learn · BiGRU · RNN · RAG · LangChain · ChromaDB · Whisper
Backend & Cloud:        FastAPI · Pydantic v2 · Node.js · Express.js · REST APIs · Webhooks · Supabase · AWS · Cloudflare CDN
Databases:              PostgreSQL · MongoDB · SQLite · ChromaDB (Vector DB)
Mobile & Frontend:      SwiftUI · React.js · HTML5 · CSS3 · Tailwind CSS · Figma
Tools & Methodologies:  Git · GitHub · Postman · Linux CLI · Jira · Agile Scrum · TestFlight · Render · unittest
```

---

### 🌟 Featured Projects

#### 🧠 Machine Learning & Explainable AI (XAI)
- 💳 **[LoanLens – Explainable Credit Risk Assessment Platform](https://github.com/mantosh23/LoanLens)**
  - End-to-end default prediction pipeline trained on 32,581 credit records using leak-free `ColumnTransformer` preprocessing.
  - Tuned XGBoost via RandomizedSearchCV (750 fits) $\to$ **0.94 CV ROC-AUC**, **0.90 PR-AUC**, **0.92 test accuracy**, and **0.81 F1**.
  - Calibrated default probabilities via 5-fold sigmoid Platt scaling (`CalibratedClassifierCV`) and generated per-applicant SHAP waterfall plots.
  - *Tech:* Python, XGBoost, SHAP, scikit-learn, FastAPI, Pydantic, Render

- 🎭 **[Moodline+ – Real-Time Emotion Classification & BiGRU NLP Engine](https://github.com/mantosh23/Emotion-Prediction)**
  - 6-class NLP emotion classification engine trained on 18,000 text samples (`dair-ai/emotion`), achieving **92.10% test accuracy** (outperforming LSTM and RNN baselines).
  - Stacked Bidirectional GRU (300D embeddings, 128/64 recurrent units, Dropout 0.5) with balanced class weights.
  - Vectorized FastAPI batch inference service (`POST /predict/batch` up to 50 lines) with diagnostic `/health` endpoints and responsive dark web studio.
  - *Tech:* Python, TensorFlow, Keras, FastAPI, Pydantic v2, NumPy, HTML/CSS/JS

- 🏙️ **[NYC Stay Classifier – Multi-Class Rental ML Pipeline](https://github.com/mantosh23/NYC-Stay-Classifier)**
  - Multi-class classification pipeline on 48,895 NYC Airbnb listings across 10 spatial and pricing features.
  - Tuned Random Forest reaching **85.59% accuracy** and **0.741 macro-F1** with 99th-percentile outlier clipping.
  - Validated FastAPI REST service with Pydantic range constraints and animated NYC skyline frontend visualization.
  - *Tech:* Python, scikit-learn, FastAPI, Pydantic, Joblib, pandas, NumPy

- 📊 **[Student Wellness Analytics – Predictive ML & APIs](https://github.com/mantosh23/Mental-Heath-Score)**
  - Preprocessed 1,000 student survey responses and trained regression models achieving an **$0.878\ R^2$** score predicting academic burnout.
  - Deployed real-time inference endpoints via FastAPI returning predictions in **<100ms**.
  - *Tech:* Python, scikit-learn, pandas, NumPy, FastAPI, Pydantic

---

#### 🎙️ Generative AI & Real-Time Engineering
- 🎙️ **[AI Video Assistant – Meeting Intelligence Platform](https://github.com/mantosh23/AI-Video-Assistance)**
  - Audio transcription and semantic search pipeline accepting YouTube URLs or local video files.
  - Dual transcription via OpenAI Whisper and Sarvam AI, with a RAG vector retrieval chatbot in ChromaDB across 500 transcript chunks.
  - *Tech:* Python, Whisper, Mistral AI, LangChain, ChromaDB, Sentence Transformers, Streamlit

- 📱 **[Everlore – Native iOS Memory Platform](https://apps.apple.com/in/app/everlore/id6761700355)**
  - Production iOS application published on the Apple App Store (**500+ downloads**).
  - Cloudinary media upload pipelines paired with Supabase authentication and real-time state synchronization.
  - *Tech:* Swift, SwiftUI, Supabase, Cloudinary, AWS Cloud Storage, TestFlight

- 📡 **[PeerSync – Real-Time Peer-to-Peer Communication Engine](https://github.com/mantosh23/Apna-Video-Call)**
  - Low-latency video conferencing platform utilizing WebRTC and Socket.io signaling (**<100ms latency**).
  - Custom signaling server in Node.js managing multi-client states and network disconnect recoveries.
  - *Tech:* WebRTC, Socket.io, Node.js, Express, React, MongoDB

- 📚 **[Vocably – AI Vocabulary Learning Platform](https://github.com/mantosh23/Vocably)** ([Live Demo](https://vocablyy.vercel.app/))
  - Full-stack learning platform leveraging Google Gemini AI for contextual definitions and practice exercises.
  - *Tech:* React, Node.js, Express, MongoDB, Google Gemini AI, Google OAuth

- ⚡ **[StyleHive – Event-Driven Automation Platform](https://github.com/mantosh23/Xeno)** ([Live Demo](https://stylehive-xeno.vercel.app/))
  - 11-table PostgreSQL relational schema with database triggers and 35 REST APIs in Express.
  - *Tech:* React, Node.js, Express, PostgreSQL, Supabase, REST APIs

---

### 📈 GitHub & Coding Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=mantosh23&show_icons=true&theme=radical&hide_border=true&count_private=true" alt="Mantosh's GitHub Stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mantosh23&layout=compact&theme=radical&hide_border=true" alt="Top Languages" />

</div>

---

### 📫 Connect With Me

- 💼 **LinkedIn:** [linkedin.com/in/mantosh23](https://linkedin.com/in/mantosh23)
- 🧩 **LeetCode:** [leetcode.com/u/mantosh23](https://leetcode.com/u/mantosh23)
- 📬 **Email:** [mantoshkumar4382@gmail.com](mailto:mantoshkumar4382@gmail.com)
- 🌐 **Portfolio:** [mantoshkumar.com](https://mantoshkumar.com)
