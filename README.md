# 🥊 Predicting UFC Fights and Observing Fight Data Trends  
**Author:** Izak Boardman  
**Course:** DSCI 311 – Project 2  

## 📘 Overview
This project aims to analyze UFC fight data and build a predictive model to determine the outcome of a fight (Red vs Blue corner). It explores trends, evaluates fighter statistics, and applies machine learning techniques to predict fight outcomes using historical fight data.

## 📂 Data Source
- Dataset: [Ultimate UFC Dataset on Kaggle](https://www.kaggle.com/datasets/mdabbert/ultimate-ufc-dataset/data)
- The dataset includes detailed statistics for each fighter and bout, including:
  - Odds, rankings, and win/loss records
  - Strike and takedown statistics
  - Finish details (round, time, method)
  - Fighter physical attributes (height, reach, stance, etc.)

## 📊 Features
Key engineered features include:
- Win/loss streak differences
- Significant strikes per minute and accuracy
- Submission and takedown attempts
- Physical and rank comparisons between fighters
- Fight outcome and method of finish

## 🧠 Methods Used
- **Exploratory Data Analysis (EDA)**: To identify patterns and trends in fighter performance and outcomes.
- **Principal Component Analysis (PCA)**: For dimensionality reduction and visual insights.
- **Logistic Regression**: To classify the winner (Red vs Blue corner).
- **Train/Test Split & K-Fold Cross Validation**: For model evaluation.
- **StandardScaler**: For feature scaling before model training.

## 📈 Results
- Visualizations reveal trends in fighter performance across weight classes and gender.
- Logistic regression provides a baseline predictive model with metrics evaluated using accuracy and mean squared error.
- PCA components help visualize class separability between winners.

## 🛠️ Installation and Setup
1. Clone the repository or download the notebook.
2. Install the required Python packages:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Download the dataset from Kaggle and place it in the same directory or update the path in the notebook.
4. Run the notebook (`notebook.ipynb`) in Jupyter Lab/Notebook or VS Code.

## 📌 Project Structure
```
├── notebook.ipynb         # Main analysis and modeling notebook
├── README.md              # Project overview and instructions
└── ufc-master.csv         # UFC dataset (downloaded separately)
```

## ✅ Future Work
- Explore more complex models like Random Forests or XGBoost
- Use fight text commentary or video data for additional context
- Optimize hyperparameters for improved performance
- Deploy the model using a web app interface (e.g., Flask or Streamlit)

## 📬 Contact
For questions or collaboration inquiries, please reach out to Izak Boardman via your academic platform or GitHub.
