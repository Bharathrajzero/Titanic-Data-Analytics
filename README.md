# 🚢 Titanic Analytics Dashboard

A production‑ready interactive analytics dashboard built using the Titanic dataset.  
This project demonstrates **data visualization, exploratory analysis, and survival prediction** using modern React tools.

---
## Screenshots


## 📊 Features
- Interactive multi‑tab dashboard  
- KPI metrics (Passengers, Survival Rate, Average Age, Fare)  
- Data visualization using charts  
- Live survival predictor  
- Searchable dataset table with pagination  
- Responsive dark theme UI  
- CSV‑based data loading  
- Modular React component architecture  

---
## 🧰 Tech Stack

### Frontend
- React (Vite)  
- Recharts (Charts & Visualization)  
- PapaParse (CSV Parsing)  

### Languages
- JavaScript (ES6+)  
- HTML5  
- CSS3  

---

## 📁 Project Structure
```text
titanic-dashboard/

├── public/
│   ├── index.html
│   └── titanic.csv      ← Dataset file

├── src/
│   ├── components/
│   │   ├── OverviewTab.jsx
│   │   ├── ModelTab.jsx
│   │   ├── PredictorTab.jsx
│   │   ├── DataTab.jsx
│   │   ├── AboutTab.jsx
│   │   └── StatCard.jsx
│   │
│   ├── utils/
│   │   └── titanicUtils.js
│   │
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
│
├── package.json
├── README.md
└── .gitignore
```

---

## ⚙️ Installation

Clone the repository:
```bash
git clone https://github.com/bharathraj152004/titanic-dashboard.git
cd titanic-dashboard
```

Install dependencies:
```bash
npm install
```

Install required libraries:
```bash
npm install recharts papaparse
```

Run development server:
```bash
npm run dev
```

Open in browser:
```
http://localhost:5174
```

---

## 📂 Dataset Setup
Download the Titanic dataset (`train.csv`).  
Rename it:
```
titanic.csv
```
Place it inside:
```
public/titanic.csv
```

Required columns:
- PassengerId  
- Survived  
- Pclass  
- Name  
- Sex  
- Age  
- Fare  

---

## 📈 Dashboard Modules

### 📊 Overview Tab
- Passenger count  
- Survival rate  
- Gender distribution  
- Survival by class  
- Age distribution  
- Fare distribution  

### 📉 Model Tab
- Model performance metrics  
- Radar chart visualization  
- Prediction summary  

### 🔮 Predictor Tab
- Interactive survival estimator (Sex, Class, Age, Fare)  
- Outputs survival probability & risk category  

### 📋 Data Tab
- Search functionality  
- Pagination  
- Scrollable table  
- Live filtering  

### 📖 About Tab
- Data pipeline  
- Model logic  
- Tech stack  
- Feature explanation  

---

## 🧠 Prediction Logic
The dashboard uses a lightweight **rule‑based model** that simulates logistic‑style survival estimation using:
- Passenger Sex  
- Passenger Class  
- Age  
- Fare  

This demonstrates machine learning‑style prediction without requiring a backend model.

---

## 🎯 Future Improvements
- Real machine learning model integration  
- Confusion matrix visualization  
- Model comparison charts  
- Export filtered dataset  
- Dark/light theme toggle  
- API‑based dataset loading  
- Performance optimization  

---

## 🌐 Deployment Options
- Vercel ⭐ Recommended  
- Netlify  
- GitHub Pages  
- AWS Amplify  

---

## 📜 License
This project is licensed under the **MIT License © 2026 Bharath Raj, AlphaGroup**.  

---

## 👨‍💻 Author
**Bharath Raj**  
GitHub: [Bharathrajzero](https://github.com/Bharathrajzero)

---
