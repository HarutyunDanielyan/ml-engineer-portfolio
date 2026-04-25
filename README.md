# ML Engineer Portfolio — Harutyun Danielyan

[![LinkedIn](https://img.shields.io/badge/LinkedIn-harutyundanielyan-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/harutyundanielyan)
[![GitHub](https://img.shields.io/badge/GitHub-HarutyunDanielyan-181717?style=flat&logo=github)](https://github.com/HarutyunDanielyan)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## Բովանդակություն / Table of Contents

- [Կուրսի կառուցվածք / Course Structure](#կուրսի-կառուցվածք--course-structure)
- [Ռեպոյի կառուցվածք / Repository Structure](#ռեպոյի-կառուցվածք--repository-structure)
- [Ֆայլերի անվանում / Naming Convention](#ֆայլերի-անվանում--naming-convention)
- [Գործիքներ / Tools & Workflow](#գործիքներ--tools--workflow)

---

## Կուրսի կառուցվածք / Course Structure

Այս ռեպոն ներառում է Armenian Code Academy-ի (ACA) 10-ամսյա Machine Learning Engineer ծրագրի ամբողջ նյութը՝ տնային առաջադրանքների լուծումներ, projects և կառուցվածքային նոտեր։

This repository contains all materials from the 10-month Machine Learning Engineer program at Armenian Code Academy (ACA) — homework solutions, hands-on projects, and structured notes across all four sections.

---

### S01 — Math & Programming Foundations

| Թեմա / Topic | Բաժին / Category |
|---|---|
| Python Fundamentals | Programming |
| Intermediate Python | Programming |
| Linear Algebra I | Math |
| Linear Algebra II | Math |
| Calculus I | Math |
| Calculus II | Math |
| Probability Theory | Math |
| Statistics | Math |
| Data Wrangling with Pandas | Programming |
| Exploratory Data Analysis (EDA) | Programming |
| Machine Learning Math in Practice | Math |
| Optimization Techniques | Math |
| Time Series Math I | Math |
| Time Series Math II | Math |
| NLP Math | Math |
| Neural Network Math | Math |

---

### S02 — Machine Learning & Time Series

| Թեմա / Topic | Բաժին / Category |
|---|---|
| Supervised Learning: Regression | Classical ML |
| Supervised Learning: Classification | Classical ML |
| Ensemble Methods | Classical ML |
| Unsupervised Learning | Classical ML |
| Time Series Forecasting I | Time Series |
| Time Series Forecasting II | Time Series |
| Deep Learning I | Deep Learning |
| Deep Learning II | Deep Learning |
| Time Series Forecasting III | Time Series |
| Time Series Forecasting IV | Time Series |
| Unsupervised Deep Learning | Deep Learning |
| Recommender Systems | Classical ML |
| Advanced Supervised Learning | Classical ML |
| Advanced Model Evaluation | Classical ML |
| ML Project End-to-End I | Project |
| ML Project End-to-End II | Project |

---

### S03 — NLP & LLMs

| Թեմա / Topic | Բաժին / Category |
|---|---|
| NLP Fundamentals | NLP |
| Word Embeddings | NLP |
| Sequence Models | NLP |
| Attention & Transformers | NLP |
| Introduction to BERT | NLP |
| Fine-Tuning BERT for Classification | NLP |
| LLM Fundamentals | LLMs |
| Prompt Engineering | LLMs |
| Advanced LLM Concepts | LLMs |
| Building with LLMs | LLMs |
| Computer Vision with Transformers | Computer Vision |
| Multimodal AI | Computer Vision |
| Ethics & Bias in AI | Ethics |
| Project Ideation & Scoping | Project |
| Capstone Project Work I | Project |
| Capstone Project Work II | Project |

---

### S04 — MLOps & Career Prep

| Թեմա / Topic | Բաժին / Category |
|---|---|
| Introduction to MLOps | MLOps |
| Versioning & Experiment Tracking | MLOps |
| Containerization | MLOps |
| Model Deployment | MLOps |
| Cloud Deployment I | MLOps |
| Cloud Deployment II | MLOps |
| Advanced MLOps | MLOps |
| Serverless ML | MLOps |
| Capstone Project Work III | Project |
| Capstone Project Work IV | Project |
| Project Presentation Practice | Career |
| Portfolio Building | Career |
| Resume & LinkedIn Optimization | Career |
| Behavioral Interview Prep | Career |
| Technical Interview Prep | Career |
| Graduation & Final Presentations | Career |

---

## Ռեպոյի կառուցվածք / Repository Structure

```
ml-engineer-portfolio/
│
├── s01_math_programming/
│   ├── lectures/          # Դասախոսությունների նոտեր / Lecture notes
│   ├── homeworks/         # Տնային առաջադրանքներ / Homework solutions
│   ├── notes/             # Անձնական նոտեր / Personal concept notes
│   └── resources/         # Լրացուցիչ նյութեր / Additional materials
│
├── s02_machine_learning/
│   ├── lectures/
│   ├── homeworks/
│   ├── notes/
│   └── resources/
│
├── s03_nlp_llms/
│   ├── lectures/
│   ├── homeworks/
│   ├── notes/
│   └── resources/
│
├── s04_mlops_career/
│   ├── lectures/
│   ├── homeworks/
│   ├── notes/
│   └── resources/
│
├── projects/
│   ├── capstone/          # Capstone project (S03–S04)
│   └── ml_end_to_end/     # End-to-end ML project (S02)
│
├── career/
│   ├── resume/
│   ├── portfolio/
│   └── interview_prep/
│
├── _templates/            # Obsidian templates
├── .gitignore
├── LICENSE
└── README.md
```

---

## Ֆայլերի անվանում / Naming Convention

Բոլոր ֆայլերն ունեն միասնական անվանման ձևաչափ, որը հեշտացնում է նավիգացիան և որոնումը։

All files follow a consistent naming format for easy navigation and searchability.

```
prefix_s##_l##_topic_name.extension
```

| Prefix | Տեսակ / Type | Օրինակ / Example |
|---|---|---|
| `hw` | Homework solution | `hw_s01_l03_linear_algebra_i.ipynb` |
| `lec` | Lecture note | `lec_s01_l01_python_fundamentals.md` |
| `note` | Concept note | `note_gradient_descent.md` |
| `proj` | Project file | `proj_capstone_eda_v1.ipynb` |

- Բոլոր անունները փոքրատառ են, բաժանված `_`-ով / All lowercase, separated by underscores
- Ամսաթիվը Git history-ն է պահում, ոչ ֆայլի անունը / Date is tracked by Git history, not the filename
- Versions-ները նշվում են `_v1`, `_v2` suffix-ով projects-ի համար / Versions marked with `_v1`, `_v2` for projects

---

## Գործիքներ / Tools & Workflow

| Գործիք / Tool | Նպատակ / Purpose |
|---|---|
| [Obsidian](https://obsidian.md) | Note-taking, knowledge management |
| [Git](https://git-scm.com) | Version control |
| [GitHub](https://github.com) | Remote repository, portfolio |
| [Python](https://python.org) | Primary programming language |
| [Jupyter Notebook](https://jupyter.org) | Interactive code & analysis |
| [PyTorch](https://pytorch.org) | Deep Learning framework |
| [scikit-learn](https://scikit-learn.org) | Classical ML |

**Լեզու / Language**

Նոտերը գրվում են հայերեն՝ նյութի ավելի խորը յուրացման համար, անգլերեն թարգմանությամբ՝ միջազգային հասանելիության համար։

Notes are written in Armenian for deeper retention, with English translation for international accessibility.

**Git Workflow**

```bash
# Daily work on dev branch
git checkout dev
git add .
git commit -m "feat(s01): complete hw linear algebra i — eigenvalues & matrix ops"
git push origin dev

# Weekly — merge to main after review
git checkout main
git merge dev --no-ff -m "merge: s01 week 2 — linear algebra complete"
git push origin main
```

**Commit message convention**

| Type | Երբ / When |
|---|---|
| `feat(s##)` | New homework solution or note added |
| `fix(s##)` | Bug fix in code or correction in notes |
| `docs` | README or comments updated |
| `refactor` | Structure changed, content unchanged |
| `wip(s##)` | Work in progress, not yet complete |

---

*Started: April 2026 · Expected completion: January 2027*
