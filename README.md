# 🎓 Life After Graduation – EDA Project

[![Open in Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Kannadossramadoss/Life_After_Graduation_EDA/HEAD)

This project explores post-graduation outcomes such as earnings, employment rate, and student debt across different majors and degree levels using **exploratory data analysis (EDA)** and **visualizations**.

---

## 📌 Project Overview

The goal of this analysis is to uncover trends and insights that help understand:

- Which majors lead to better employment?
- How earnings vary with degree level?
- What kind of debt students typically graduate with?

The findings are presented through clear charts and grouped statistics, using a cleaned dataset derived from the original source.

---
```
Life_After_Graduation_EDA/
├── data/                         # Raw dataset
│   └── life_after_graduation.csv
├── notebooks/                    # Main EDA notebook
│   └── Life_After_Graduation_EDA.ipynb
├── outputs/                      # Cleaned data and visualizations
│   ├── life_after_graduation_cleaned.csv
│   └── employment_vs_major.png
├── README.md                     # Project documentation
└── requirements.txt              # Python dependencies
```
---

## 📊 Key Insights

- 🎓 Graduates with a **PhD** degree have the **highest median earnings**, averaging around **\$79,710**.
- 💼 **Political Science** majors show the **highest median employment rate**, reaching approximately **89.0%**.
- 💸 Students majoring in **Marketing** incur the **highest median student debt**, around **\$24,694**.
- 📈 The **overall average median earnings** across all graduates is around **\$75,426**, with an **average employment rate of 83.0%**, and a **median debt of \$22,249**.

---

## 🛠️ Technologies Used

- Python 🐍
- Jupyter Notebook 📓
- pandas, matplotlib, seaborn
- Binder (for online notebook execution)

---

## ▶️ How to Run

1. Clone this repository:
   git clone https://github.com/Kannadossramadoss/Life_After_Graduation_EDA.git
   cd Life_After_Graduation_EDA

2. Create and activate a virtual environment:
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate

3. Install required packages:
   pip install -r requirements.txt

4. Launch Jupyter Notebook:
   jupyter notebook

---

## 🌐 Try It Online
Click the Binder badge at the top of this README to open the notebook online without any setup.

---

## 📬 Contact
For questions, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/kannadoss-ramadoss/) or raise an issue on this repo.

---

## ⭐ Acknowledgements
Inspired by real-world graduation and employment datasets. Project built to demonstrate real-world EDA skills for data science portfolios.
