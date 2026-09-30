# 🗳️ Indian Election Analysis & Prediction

Exploratory data analysis of Indian Lok Sabha and Vidhan Sabha elections
covering candidate demographics, party performance, and voter turnout.

## 📌 Overview
This project analyzes Indian election data using Python. It cleans the data,
computes key election metrics, and presents them through charts to reveal
patterns across states and years.

## 📂 Project Structure
├── Indian_Election_Prediction.ipynb   # Main analysis notebook
└── README.md

## 🔍 Analysis Performed
- Handling missing values (candidate gender, constituency type)
- Unique counts of states, years, constituencies, candidates, and parties
- Candidate gender distribution (pie chart)
- Average candidates per seat per year (line plot)
- Voter turnout % by year and by state
- Top 10 parties by number of candidates (bar chart)
- Winner identification per constituency
- Gujarat party vote-share trends and seats won by top 3 parties
- Number of constituencies per state

## 🛠️ Tech Stack
Python · Pandas · NumPy · Matplotlib · Seaborn · Jupyter Notebook

## ▶️ How to Run
1. Clone the repo
2. Install dependencies:
   pip install pandas numpy matplotlib seaborn jupyter
3. Add the Lok Sabha (df_lok) and Vidhan Sabha (df_vidhan) datasets
4. Open and run the notebook:
   jupyter notebook Indian_Election_Prediction.ipynb

## 📈 Future Scope
- Build ML models (Logistic Regression, Random Forest) to predict winners
- Add feature engineering (vote margin, incumbency, party alliances)
- Create an interactive dashboard (Streamlit / Power BI)

## ⚠️ Note
The notebook currently uses small sample DataFrames as placeholders.
Replace them with the real election datasets for actual results.
