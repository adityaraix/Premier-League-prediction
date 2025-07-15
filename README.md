# Football Match Outcome Prediction

This repository contains a data science project that explores historical football match data and builds a predictive model to forecast match outcomes.  
The project includes data exploration, preprocessing, visualization, and predictive modeling steps, all written in Python within a Jupyter Notebook.

## 📂 Project Structure

├── matches.csv # Dataset containing football match statistics
├── Prediction.ipynb # Jupyter Notebook with data analysis and prediction code
└── README.md # Project documentation

## 🧰 Technologies Used

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn (if used in modeling)

## 📊 Dataset

The dataset `matches.csv` includes data from 1389 football matches.  
Key columns:
- `date`, `time`: Match timing
- `comp`, `round`, `day`, `venue`: Competition and match context
- `result`: Match result (W/L/D)
- `gf`, `ga`: Goals scored and conceded
- `xg`, `xga`: Expected goals and expected goals against
- `poss`: Possession percentage
- `attendance`: Match attendance
- `captain`, `formation`, `referee`
- `opponent`, `team`: Teams involved
- Shooting and penalty stats: `sh`, `sot`, `fk`, `pk`, `pkatt`

## ​:contentReference[oaicite:0]{index=0}​
