# 📺📊 Netflix Viewership Analytics Dashboard

[![Python](https://img.shields.io/badge/python-v3.8%2B-blue.svg)](https://www.python.org/downloads/)
[![Flask](https://img.shields.io/badge/flask-v2.3%2B-black.svg)](https://flask.palletsprojects.com/)
[![Pandas](https://img.shields.io/badge/pandas-Data%20Wrangling-150458.svg)](https://pandas.pydata.org/)
[![Plotly](https://img.shields.io/badge/plotly-Interactive%20Charts-blue.svg)](https://plotly.com/python/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> A complete Flask-based analytics dashboard that visualizes Netflix content viewership trends by content type, language, release month, and day of the week to uncover audience preferences. Built with Python, Flask, Pandas, and Plotly.

<img width="962" height="559" alt="Screenshot 2025-09-07 005828" src="https://github.com/user-attachments/assets/c6c0bc0f-a09c-4ee2-8cce-6c81a90a555b" />
<img width="1006" height="591" alt="Screenshot 2025-09-07 005849" src="https://github.com/user-attachments/assets/c9c374f8-ac3f-45fa-9b62-a825b5676848" />
<img width="1045" height="596" alt="Screenshot 2025-09-07 005857" src="https://github.com/user-attachments/assets/55a5881e-4551-487f-a967-56c331693885" />

---

## ✨ Features

- 🔐 **Upload & Manage Data**  
  Upload CSV files containing Netflix content viewership data.

- 🔎 **Viewership Overview**  
  View total viewership hours by content type, language, release month, and release season.

- 📈 **Trends Visualization**  
  Interactive line and bar charts showing monthly trends, seasonal trends, and weekday performance.

- 🧱 **Top Content Insights**  
  View top 5 most viewed Netflix titles with metadata.

- 📊 **Combined Metrics**  
  Overlay number of releases vs viewership hours by month and day of the week.

---

## 🚀 Quick Start

```bash
# Clone and setup

git clone https://github.com/your-username/netflix-viewership-dashboard.git
cd netflix-viewership-dashboard

python -m venv venv

# Linux/Mac:
source venv/bin/activate

# Windows (PowerShell):
# .\\venv\\Scripts\\Activate.ps1

# Install dependencies
pip install -r requirements.txt

# (Optional) Set environment variables

# Linux/Mac:
export FLASK_APP=app.py
export FLASK_ENV=development

# Windows (PowerShell):
# $env:FLASK_APP="app.py"
# $env:FLASK_ENV="development"

# Run the app
flask run

# Open http://127.0.0.1:5000

```

## 📂 Dataset

The dataset includes viewership data of Netflix content (movies & shows) in 2023.
Typical Columns
⦁	**Content Metadata**: Title, Content Type, Language Indicator, Release Date

⦁	**Viewership**: Hours Viewed

⦁	**Release Time Data**: Release Month, Release Day of Week, Release Season

Place your CSV inside data/ (e.g., data/ad_users.csv) or upload via the web UI.


## 📊 Features Used

⦁	Content Type & Language

⦁	Release Month, Release Season

⦁	Number of Releases

⦁	Hours Viewed (in billions)

⦁	Top Content Titles

## 🔍 Techniques Applied

⦁	Data Cleaning & Transformation

⦁	Time-based Aggregation (Release Month/Season/Weekday)

⦁	Interactive Plotly Visualizations (Bar & Line Charts)

⦁	User-friendly Dashboard with Netflix Theme

## 📌 Example Insights

⦁	**Content Type Distribution** — Movies vs TV Shows total viewership.

⦁	**Language Impact** — Top languages by viewership hours.

⦁	**Release Month Trends** — When does viewership peak?

⦁	**Seasonal Preferences** — Summer vs Winter viewership patterns.

⦁	**Release Day Impact** — Does release day affect viewership?

## 📈 Output

⦁	Interactive bar charts showing total viewership by content type, language, and season.

⦁	Line charts for trends by release month and content type.

⦁	Combined plots showing release counts vs total viewership.

⦁	Top 5 most viewed Netflix titles table with details.

## 🛠️ Tech Stack

⦁	**Backend**: Python, Google Colab

⦁	**Data Processing**: Pandas, NumPy

⦁	**Visualization**: Plotly

⦁	**Utilities**: joblib (optional for persistence), python-dotenv (env vars management)

💡 Contributions, issues, and feature requests are welcome!


---
