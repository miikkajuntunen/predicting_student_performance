# Predicting Students’ Performance

## 💼 Business Task  
Develop a model to predict students’ final grades based on their performance logs, quizzes, projects, and peer reviews. The goal was to identify the most influential features affecting grades and evaluate the performance of different models.

## 📊 Dataset
The dataset consists of anonymized records from 107 students, including grades, peer reviews, and engagement logs. The data was preprocessed to reduce noise and focus on the most impactful features, simplifying 48 variables down to 13.  

## 🛠️ Tools
- **Python**: Pandas, Scikit-learn  
- **Matplotlib**: Data visualization  

## Data Preparation
The project began with cleaning and transforming the raw data to ensure accuracy and usability. Steps included removing duplicates, handling missing values, and aggregating activity logs. Correlation analysis revealed the most impactful features, such as Mini Project 3 and Peer Review scores.  

## Modeling and Results
- **Linear Regression**: Achieved an R² score of 0.92, demonstrating high accuracy. The model performed best due to the dataset’s linear characteristics.  
- **Random Forest**: Scored an R² of 0.89, performing slightly worse but providing valuable insights into feature importance.  

## Key Insights
- Peer review grades and Mini Projects were the strongest predictors of final grades.  
- Early performance (e.g., Quiz 1) showed a significant correlation with overall success.  
- Linear Regression outperformed Random Forest, highlighting the importance of selecting models suited to the data's structure.  

## Conclusion 
This project showcased the importance of data cleaning, feature analysis, and model selection. By simplifying the dataset and leveraging Linear Regression, I could create a highly accurate predictive model while gaining insights into factors that drive student success.  
