# 🌱 Carbonapp: Transport Carbon Footprint Tracker

A Flask web app where users log their trips and see the CO₂ emissions from how they travel.

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?logo=sqlalchemy&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)

## ✨ Features

- **User accounts:** register and log in, with passwords hashed using bcrypt (Flask-Login)
- **Log trips by transport mode:** car, bus, plane, ferry, motorbike, bicycle or walking, with distance and fuel type
- **Emission calculation:** CO₂, CH₄ and total CO₂-equivalent for every entry
- **Personal dashboard:** see your emission history and delete entries
- **Methodology page:** explains how the emission factors are calculated
- **About us page**

## 🧱 Tech Stack

| Layer | Tools |
|---|---|
| Backend | Python, Flask (Blueprints), Flask-Login, Flask-WTF, bcrypt |
| Database | SQLite via Flask-SQLAlchemy (`User` and `Transport` models) |
| Frontend | Jinja2 templates, HTML, CSS |

## 📁 Project Structure

```
Capp/
├── Carbon_app/    # emission entry forms + routes
├── users/         # registration & login
├── home/          # landing page
├── Methodology/   # emission-factor explanation
├── About_us/
├── templates/     # Jinja2 HTML templates
├── static/        # CSS & icons
└── models.py      # User & Transport database models
application.py     # app entry point
```

## 🚀 Getting Started

```bash
git clone https://github.com/Petrov-Gaming/Carbonapp-3.git
cd Carbonapp-3
python3 -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate
pip install -r requirements.txt
python application.py
```

Then open http://127.0.0.1:5000 in your browser.

## 📸 Screenshots

<!-- Add screenshots here, e.g. ![Dashboard](docs/dashboard.png) -->

## 👤 Author

**Petter Mortensen**: M.Sc. Business Analytics student at NHH. See my [GitHub profile](https://github.com/Petrov-Gaming).
