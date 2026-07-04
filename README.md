# 🤖 Poornima Chandrashekhar Balagondar — AI & ML Engineer Portfolio

> Personal portfolio website of an AI & Machine Learning Engineer specialising in LLM integration, prompt engineering, RAG pipelines, and production-grade ML systems.

🔗 **Live Portfolio:** [View Here](https://cbpoornima0511.github.io/portfolio)  
📧 **Email:** poornimabalagondar@gmail.com  
💼 **LinkedIn:** [linkedin.com/in/poornima-chandrashekhar-balagondar](https://linkedin.com/in/poornima-chandrashekhar-balagondar)  
☁️ **Google Cloud Badges:** [cloudskillsboost.google/profile/badges](https://www.cloudskillsboost.google/profile/badges)

---

## 📋 About This Portfolio

A fully responsive, single-file HTML portfolio built with vanilla HTML, CSS, and JavaScript — no frameworks, no dependencies, no build step. Features an animated particle constellation background, glassmorphism cards, scroll-triggered reveal animations, and interactive system architecture diagrams for each project.

---

## 🗂️ Portfolio Sections

| Section | Content |
|---|---|
| **Hero** | Name, title, CTA buttons, skill badges, animated avatar |
| **About Me** | Bio, contact info, 4 stat cards |
| **Skills & Stack** | 4 categorised skill cards: GenAI, ML, NLP, Dev Tools |
| **Experience & Education** | Vertical timeline: Internship + 3 education entries |
| **Projects** | 3 full project cards with architecture diagrams |
| **Certifications** | Google Cloud, NPTEL, Data Science with GenAI |
| **Contact** | Clickable email, GitHub, LinkedIn links |

---

## 🚀 Featured Projects

### 1. Intelligent NHIS Insurance Claim Fraud Detection Using LLM
> **Dec 2025 – Feb 2026**

An end-to-end intelligent fraud detection system combining XGBoost classification with Meta's Llama 3.1 8B for natural-language explainability.

- **Dataset:** 20,388 NHIS insurance claims · 4 fraud classes (No Fraud, Phantom Billing, Ghost Enrollee, Wrong Diagnosis)
- **ML Pipeline:** Sklearn ColumnTransformer → XGBoost (class_weight=balanced) → model.pkl
- **LLM Layer:** 4 distinct prompt templates (Explanation / Q&A / Investigation Report / Decision Recommendation)
- **Interface:** 4-tab Streamlit dashboard with animated CSS cards and cross-tab session state
- **Tech:** `XGBoost` `Scikit-learn` `Llama 3.1 8B` `HuggingFace Router` `Streamlit` `Python`

🔗 [View Repository](https://github.com/cbpoornima0511/Intelligent-NHIS-Insurance-Claim-Fraud-Detection-Using-LLM)

---

### 2. Medical Query Classification & AI-Generated Guidance System
> **Stroke Risk Assessment**

AI-powered stroke risk assessment assistant combining Logistic Regression classification with Llama 3.1 8B conversational guidance.

- **ML Pipeline:** Sklearn ColumnTransformer → Logistic Regression (class_weight=balanced) → stroke_model.pkl
- **LLM Layer:** INST-format system prompt with medical AI role + explicit safety guardrails (never diagnose)
- **Features:** Risk scoring (LOW/MEDIUM/HIGH), personalised health guidance, Llama chat interface, batch CSV screening, emergency FAST sidebar
- **Interface:** Glassmorphism Streamlit app with animated gradient cards
- **Tech:** `Logistic Regression` `Sklearn Pipeline` `Llama 3.1 8B` `HuggingFace Router` `Streamlit` `Python`

🔗 [View Repository](https://github.com/cbpoornima0511/Medical-Query-Classification-and-AI-Generated-Guidance-System)

---

### 3. Financial Causality Detection
> **Sep 2024 – Jan 2025**

Two-model NLP pipeline for detecting and explaining causal relationships in financial news text.

- **Pipeline:** Fine-tuned RoBERTa (causality classification) → GPT-2 (causal narrative generation)
- **Approach:** RoBERTa detects cause-effect pairs in financial text; GPT-2 generates plain-English explanations
- **Tech:** `RoBERTa` `GPT-2` `HuggingFace Transformers` `XGBoost` `Python`

---

## 🛠️ Tech Stack Used in Portfolio

| Category | Technologies |
|---|---|
| **Frontend** | HTML5, CSS3 (custom properties, animations), Vanilla JavaScript |
| **Background** | Animated mesh-gradient (radial auroras + scan lines) via CSS pseudo-elements |
| **Particles** | Canvas API — 140-particle constellation with connecting lines |
| **Animations** | CSS keyframes, IntersectionObserver scroll reveals, animated distribution bars |
| **Fonts** | Inter, system-ui (no external font dependency) |
| **Deployment** | GitHub Pages (single `index.html`) |

---

## 💡 Skills Showcased

```
Generative AI    →  Llama 3.1 8B · GPT-2 · Prompt Engineering · RAG · LangChain · HuggingFace · Agents · Pydantic
Machine Learning →  XGBoost · Logistic Regression · Sklearn Pipeline · ColumnTransformer · GridSearchCV · AUC-ROC
NLP              →  RoBERTa · Transformers · Fine-tuning · NER · POS · TF-IDF · Word Embeddings
Dev & Tools      →  Python · SQL · Streamlit · Pandas · NumPy · Matplotlib · Seaborn · Power BI · Git
```

---

## 🎓 Education

| Degree | Institution | Year | Score |
|---|---|---|---|
| B.E. Computer Engineering (AI & ML) | Presidency University, Bengaluru | 2021–2025 | CGPA 7.88 |
| PUC – Science | Anmol Science PU College, Davanagere | 2019–2021 | 86.5% |
| SSLC | Roshni High School, Hangal, Haveri | 2019 | 84.32% |

---

## 📜 Certifications

- ☁️ **Generative AI Solutions** — Google Cloud Skills Boost
- 🎓 **Fundamentals of Artificial Intelligence** — NPTEL
- 🤖 **Data Science with Generative AI** — AI/ML Professional Development

---

## 💼 Experience

**Machine Learning Intern — InternPe** *(Jul 2024 – Aug 2024)*
- Built end-to-end ML pipelines using scikit-learn (preprocessing, feature engineering, model evaluation)
- Applied cross-validation and GridSearchCV, improving baseline accuracy by ~12%
- Delivered model performance reports with actionable stakeholder insights

---

## 🚀 How to Use

### Run Locally
```bash
# Clone the repository
git clone https://github.com/cbpoornima0511/portfolio.git
cd portfolio

# Open directly in browser — no build step needed
open index.html
# or just double-click index.html
```

### Deploy to GitHub Pages
```bash
# 1. Rename the HTML file to index.html
mv poornima_portfolio.html index.html

# 2. Push to GitHub
git add index.html
git commit -m "Add portfolio"
git push origin main

# 3. Go to repo Settings → Pages → Source: main branch → Save
# Your portfolio will be live at: https://cbpoornima0511.github.io/portfolio
```

---

## 📁 Repository Structure

```
portfolio/
└── index.html          # Complete portfolio — single self-contained file
                        # Includes all CSS, JavaScript, and content inline
                        # No external dependencies · No build step required
```

---

## 🎨 Design Features

- **Color Palette:** Deep emerald-obsidian (`#07120F`) with emerald, sky-blue, copper-gold and coral accents
- **Background:** Animated 4-layer radial aurora mesh with diagonal scan-line texture (CSS-only, 26s drift)
- **Glassmorphism:** Frosted-glass cards with border glow on hover
- **Starfield:** Canvas-based 140-particle constellation with dynamic connecting lines
- **Scroll Animations:** IntersectionObserver-powered reveal transitions on every section
- **Architecture Diagrams:** Inline HTML flow diagrams for all 3 projects — no external libraries
- **Fully Responsive:** Mobile-first, collapses gracefully at 768px

---

## 📬 Contact

| Channel | Details |
|---|---|
| 📧 Email | poornimabalagondar@gmail.com |
| 📞 Phone | +91 8310704458 |
| 💼 LinkedIn | [linkedin.com/in/poornima-chandrashekhar-balagondar](https://linkedin.com/in/poornima-chandrashekhar-balagondar) |
| 🐙 GitHub | [github.com/cbpoornima0511](https://github.com/cbpoornima0511) |
| ☁️ Cloud Badges | [cloudskillsboost.google/profile/badges](https://www.cloudskillsboost.google/profile/badges) |

---

<div align="center">

**Open to AI/ML · Generative AI · Prompt Engineering · NLP · Data Science opportunities**

*Built with ❤️ by Poornima Chandrashekhar Balagondar · Bengaluru, India*

</div>
