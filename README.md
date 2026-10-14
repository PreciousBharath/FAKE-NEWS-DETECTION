<div align="center">
<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=800&size=40&duration=3500&pause=1500&color=36BCF7&center=true&vCenter=true&width=900&height=70&lines=%F0%9F%93%B0%20Fake%20News%20Detection" alt="Fake News Detection"/>

<b><i>Spot fake news with NLP & Machine Learning — Django</i></b>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=36BCF7&center=true&vCenter=true&width=700&lines=%F0%9F%93%B0%20Real%20or%20Fake%3F;%F0%9F%A7%A0%20NLP%20%2B%20Logistic%20Regression;%F0%9F%8C%90%20Django%20web%20application" alt="Typing SVG" />

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/> <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django"/> <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn"/> <img src="https://img.shields.io/badge/NLTK-154F5B?style=for-the-badge&logo=python&logoColor=white" alt="NLTK"/> <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/> <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite"/> <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/> <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>

<img src="https://img.shields.io/github/stars/PreciousBharath/FAKE-NEWS-DETECTION?style=social" alt="stars"/> <img src="https://img.shields.io/github/forks/PreciousBharath/FAKE-NEWS-DETECTION?style=social" alt="forks"/> <img src="https://img.shields.io/github/last-commit/PreciousBharath/FAKE-NEWS-DETECTION?style=flat-square&color=blueviolet" alt="last commit"/> <img src="https://img.shields.io/github/repo-size/PreciousBharath/FAKE-NEWS-DETECTION?style=flat-square&color=success" alt="repo size"/>
</div>

---

## 📰 About the Project

Based on the paper *“Detecting Fake News Using Machine Learning Algorithms”*, this **Django** web app classifies news articles as **REAL or FAKE** using **NLP (TF-IDF)** and **Logistic Regression** among other algorithms. Users submit news text; admins review model results and manage users.

## ✨ Key Features

- 📝 Paste any news text and get an instant **Real / Fake** verdict
- 🧹 NLP pipeline — cleaning, stop-word removal, **TF-IDF** vectorisation
- 📊 Algorithm comparison & accuracy **results page** for admins
- 👥 User registration with **admin activation**
- 📄 Abstract, base paper and full code included

## 🧠 How It Works

```mermaid
flowchart LR
N["📰 News Text"] --> P["🧹 Text Cleaning"] --> T["🔢 TF-IDF"] --> M["🧠 Logistic Regression"] --> R{"✅ Real / ❌ Fake"}
```

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Backend | Django (Python) |
| NLP / ML | NLTK · scikit-learn (TF-IDF, Logistic Regression) |
| Database | SQLite |
| Frontend | HTML5 · CSS3 · JavaScript |

## 📂 Project Structure

```text
29 Detecting Fake News/
├── ABSTRACT/     # project abstract
├── BASEPAPER/    # reference paper
└── CODE/fakenews/
    ├── admins/   # admin app
    ├── users/    # user app (prediction)
    ├── assets/   # templates + static
    └── manage.py
```

## 🚀 Getting Started

```bash
git clone https://github.com/PreciousBharath/FAKE-NEWS-DETECTION.git
cd "FAKE-NEWS-DETECTION/29 Detecting Fake News/CODE/fakenews"
pip install django pandas scikit-learn nltk
python manage.py migrate
python manage.py runserver
```

## 🤝 Contributing

Contributions, issues and feature requests are welcome! Feel free to ⭐ star the repo and open a pull request.

## 👨‍💻 Author

<div align="center">

**Bharath** — Software Developer · Project Engineer · Technical Trainer

<a href="https://github.com/PreciousBharath"><img src="https://img.shields.io/badge/GitHub-PreciousBharath-181717?style=for-the-badge&logo=github"/></a>
<a href="https://linkedin.com/in/connectbharath"><img src="https://img.shields.io/badge/LinkedIn-connectbharath-0A66C2?style=for-the-badge&logo=linkedin"/></a>

### 🍔 EAT · 😴 SLEEP · 💻 CODE · 🔁 REPEAT

⭐ **If you found this project useful, give it a star!** ⭐

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

</div>
