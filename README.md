# SyriaTel Customer Churn Prediction
<img src="C:\Users\Administrator\Documents\Flatiron\Phase_3\project\Customer-Churn.png" width="1200" height="100" />

This project aims to analyze customer churn behavior for SyriaTel, a telecommunications company, using machine learning techniques. By understanding the factors contributing to customer churn, we can provide actionable insights to reduce customer attrition and improve customer retention strategies.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Dataset Description](#dataset-description)
3. [Methodology](#methodology)
4. [Technologies Used](#technologies-used)
5. [Results and Insights](#results-and-insights)
7. [Contributing](#contributing)

---

## Project Overview
Customer churn refers to the loss of customers over a given period. For telecommunications companies like SyriaTel, minimizing churn is critical for maintaining profitability. This project:

- Uses machine learning models to predict churn probability for customers.
- Identifies key factors influencing customer churn.
- Provides recommendations to reduce churn.
## Dataset Description

The dataset used in this project contains information about SyriaTel's customers, including:

- Demographics: Age, gender, etc.
- Service usage: Internet service, streaming services, etc.
- Churn label: Indicator of whether the customer has churned (binary).

### Key Features:
- `customerID`: Unique identifier for each customer.
- `MonthlyCharges`: The amount charged to the customer monthly.
- `Churn`: Target variable indicating whether the customer churned.

## Methodology

1. **Data Cleaning and Preprocessing:**
   - Handle missing values.
   - Convert categorical variables into numerical representations.
   - Standardize numerical features.

2. **Exploratory Data Analysis (EDA):**
   - Visualize distributions and relationships between features.
   - Identify patterns and trends influencing churn.
3. **Model Training:**
   - Comparison of multiple models including Decision Trees, Random Forests, and Logistic Regression.
   - ### Logistic Regression
   -    Accuracy: 0.82 Precision: 0.72 Recall: 0.65 F1-score: 0.52 AUC-ROC Score: 0.83 Summary: Logistic Regression achieves moderate accuracy and precision but lower recall compared 
         to other models. The AUC-ROC score indicates good overall performance.
   - ### Decision Trees
   -    Accuracy: 0.87 Precision: 0.56 Recall: 0.74 F1-score: 0.62 AUC-ROC Score: 0.82 Summary: Decision Tree exhibits lower accuracy and precision than Random Forest. However, it also 
        has lower recall and a slightly lower AUC-ROC score, indicating suboptimal performance
     ### Random Forest
        Accuracy: 0.92 Precision: 0.71 Recall: 0.791 AUC-ROC Score: 0.91 Summary: Random Forest improves accuracy, precision, and recall compared to Decision Tree. Its AUC-ROC score is 
        the highest
   - Use hyperparameter tuning (e.g., Grid Search) to optimize models.
   -    Random Forest with tuned hyperparameters is the model with the best performance. The model has the highest recall score. The accuracy and precision scores are also high. 
        However, the recall score achieved is below the set score of at least 85%
4. **Evaluation Metrics:**
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - ROC Curve and AUC
   - Random Forest had metrics of :
   -   train score  0.9358581436077058
       test score  0.9190404797601199
       Random Forest Classification Report:
       Accuracy:  0.9190404797601199
       Precision:  0.7079646017699115
       Recall:  0.7920792079207921
       F1 Score:  0.7476635514018691

5. **Insights and Recommendations:**
   - Analyze feature importance to understand churn drivers.
   - Propose strategies for customer retention.

## Technologies Used

- **Programming Language:** Python
- **Libraries:**
  - Pandas, NumPy: Data manipulation
  - Matplotlib, Seaborn: Visualization
  - Scikit-learn: Machine learning

## Results and Insights

- **Best Model:** Random Forest with an accuracy of 92%.
- **Key Factors Influencing Churn:**
  total day minutes
  total evening minutes
  customer service calls
  total international minutes


### Recommendations:
 Service Improvement Initiatives
 Enhanced Communication Channels
 Data-Driven Decision Making
 Customer Retention Strategies e.g personalized offers, loyalty programs, and targeted marketing campaigns


## Contributing

Contributions are welcome! If you want to improve this project:

1. Fork the repository.
2. Create a new branch.
3. Submit a pull request.

## For More Information
See the full analysis in the Jupyter Notebook ipynb_checkpoints or review this presentation . For additional information, contact Sharleen Liz at lizsharleen381@gmail.com


