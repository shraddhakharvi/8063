# Bank Term Deposit Prediction Project

This project focuses on predicting whether clients will subscribe to a term deposit using machine learning models. The dataset provided contains information on customer demographics, past interactions, and campaign outcomes. This repository includes the analysis, modeling, and insights obtained from the dataset.

## Dataset Information

### Columns:
- **age**: Age of the client.
- **job**: Job type (e.g., admin., technician, etc.).
- **marital**: Marital status (e.g., married, single).
- **education**: Level of education.
- **default**: Has credit in default? (yes/no).
- **balance**: Average yearly balance in euros.
- **housing**: Has a housing loan? (yes/no).
- **loan**: Has a personal loan? (yes/no).
- **contact**: Communication type (e.g., cellular, telephone).
- **day**: Last contact day of the month.
- **month**: Last contact month of the year.
- **duration**: Last contact duration in seconds.
- **campaign**: Number of contacts performed during this campaign.
- **pdays**: Days since the client was last contacted.
- **previous**: Number of contacts performed before this campaign.
- **poutcome**: Outcome of the previous marketing campaign.
- **y**: Target variable (yes/no).

## Project Workflow

### 1. Data Preprocessing:
- Handled missing values and encoded categorical variables.
- Scaled numerical features for model compatibility.

### 2. Exploratory Data Analysis (EDA):
- **Key Insights:**
  1. Overall subscription rate.
  2. Subscription rates by age group, job type, and education level.
  3. Impact of previous campaign outcomes on subscriptions.
  4. Relationships between balance, loan status, and subscriptions.
  5. Monthly trends in subscriptions.

- **Visualization Tools:**
  - Power BI was used for dashboards.
  - Key visualizations include bar charts, scatter plots, and line charts.

### 3. Model Selection and Training:
- Logistic Regression was selected for its simplicity and interpretability.
- The dataset was split into training and test sets (80:20).
- Model evaluation metrics included accuracy, precision, recall, and F1-score.

### 4. Key Insights:
- Age groups and education levels significantly influence subscription likelihood.
- Longer call durations correlate positively with subscriptions.
- Successful outcomes in previous campaigns increase current subscription chances.

## Files in the Repository

1. **`train.csv`**: Original dataset used for training the model.
2. **`Hackhaton.pbix`**: Power BI dashboard file.
3. **`8063.csv`**: Contains predictions with an additional column `y` (predicted outcome).
4. **`8063.ipynb`**: Jupyter Notebook with data preprocessing, EDA, and modeling.
5. **`theme.json`**: Custom Power BI theme for the dashboard.
6. **`README.md`**: Project overview and detailed description.

## Instructions to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/bank-term-deposit-prediction.git
   cd bank-term-deposit-prediction
   ```

2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook 8063.ipynb
   ```

4. Visualize insights in Power BI using the `Hackhaton.pbix` file.

5. Submit the `8063.csv` file for evaluation.

## Future Improvements
- Implement advanced models like Random Forest or XGBoost for better accuracy.
- Add hyperparameter tuning and cross-validation steps.
- Explore SHAP values for better interpretability of model predictions.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

If you have any questions or suggestions, feel free to open an issue or contact the project maintainer.

here is the presentation vedio of our team
" https://drive.google.com/file/d/171p74CVmKfr6uyVDh4bnz2IdoGQFrqVU/view?usp=sharing "

