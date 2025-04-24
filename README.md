# Student Engagement Churn (Data Analysis)

## 📊 Project Overview
This project aims to analyze student engagement and predict churn (dropout) for the Excelerate AI Data Analyst Internship program. The analysis spans four weeks of data-driven exploration, cleaning, and modeling to identify factors contributing to student engagement and disengagement. By leveraging data science techniques, the project provides actionable insights to enhance student retention and engagement strategies.

## 🗂 Repository Structure
```plaintext
├── Week 1 - Data Cleaning and Validation
│   ├── Cleaned_Preprocessed_Dataset_Week1.csv
│   ├── excelerate_Student_Engagement_and_Churn_Analysis.ipynb
│   ├── Week1_Feature_Engineering_Report_Shahid Khan.pdf
├── Week 2 - Exploratory Data Analysis
│   ├── Dataset_Week2.csv
│   ├── EDA_Week2.ipynb
│   ├── Week2 Report.pdf
├── Week 3 - Churn Analysis and Predictive Modeling
│   ├── Week 3 Module 1.ipynb
│   ├── Week 3 Module 2.ipynb
│   ├── Dataset_Week2.csv
│   ├── final_dataset.csv
│   ├── Week 3 Report.pdf
├── Week 4 - Recommendations & Presentation
│   ├── AI DRIVEN DATA ANALYSIS.pptx
└── README.md
```
## 👥 Team Members
-Shahid Khan
-Mangesh Pawar
-Janak Adhikari
-Md Aijaz Ahmad
-Rishika Nirala
-Harsh Bajpay
-Muhammad Sohaib


## 📈 Week 1: Data Cleaning and Feature Engineering
### Overview
In the first week, we focused on cleaning the raw dataset to ensure it was suitable for further analysis. Key tasks included handling missing values, removing duplicates, correcting formatting issues, and standardizing data types. Feature engineering techniques were also applied to extract meaningful insights from existing data columns.

### Key Steps
- **Data Cleaning**:
  - Addressed missing values using imputation techniques.
  - Removed unnecessary columns and standardized data types.
  - Validated entries for accuracy, including dates, numerical fields, and categorical data.
- **Feature Engineering**:
  - Created new features such as "Age of Learner," "Engagement Duration," and "Time Since Last Engagement."
  - Normalized engagement-related metrics to prepare for modeling.

### Tools & Libraries
- Python (Pandas, NumPy, Seaborn)
- Jupyter Notebook


## 🔍 Week 2: Exploratory Data Analysis (EDA)
### Overview
In the second week, we conducted an in-depth Exploratory Data Analysis (EDA) to uncover patterns and insights within the cleaned dataset. This phase laid the foundation for hypothesis generation and feature selection for predictive modeling.

### Key Analyses
- **Demographic Insights**:
  - Analyzed learner demographics like age, gender, and engagement patterns.
  - Identified high engagement among specific age groups (18-28 years).
- **Temporal Trends**:
  - Seasonal analysis of engagement scores, sign-up trends, and engagement duration.
  - Observed peak engagement in specific months (e.g., July) and days (e.g., Thursday).
- **Advanced Visualizations**:
  - Generated correlation heatmaps, PCA plots, and clustering (K-Means) to identify underlying data structures.
  - Conducted cohort analysis to track engagement over time.

### Tools & Libraries
- Python (NumPy, Pandas, Seaborn, Matplotlib, Scikit-learn)


## 📊 Week 3: Churn Analysis & Predictive Modeling
### Overview
The focus of week three was to develop a robust predictive model for identifying students at risk of churn. The analysis aimed to uncover factors contributing to student drop-offs and to build a model capable of predicting churn with high accuracy.

### Key Steps
- **Data Preparation**:
  - Created new engagement metrics and defined churn indicators based on engagement duration, frequency, and inactivity.
  - Labeled students as "churned" or "non-churned" based on thresholds derived from EDA insights.
- **Model Training**:
  - Trained multiple models: Logistic Regression, Decision Tree, Random Forest, SVM.
  - In the trial method, before implementation, we achieved the best results with an ensemble Voting Classifier, yielding 98% accuracy.
- **Model Evaluation**:
  - Evaluated models using metrics such as Precision, Recall, F1 Score, and Confusion Matrix.

### Tools & Libraries
- Python (Scikit-learn, TensorFlow, Keras)
- Juypter Notebook


## 📝 Week 4: Recommendations & Strategic Engagement

### Overview
In the final week of our analysis, we developed targeted strategies to boost student engagement and reduce churn. By leveraging insights from previous analyses, we implemented a recommendation system that focuses on personalized re-engagement, course suggestions, and incentives for participation. These strategies are designed to enhance user retention on the platform by delivering tailored interventions.

### Key Strategies Implemented

1. **Personalized Re-Engagement Alerts**
   - **Objective**: To re-engage inactive or low-engagement students.
   - **Approach**: Students with low engagement scores or more than 30 days of inactivity receive automated re-engagement notifications. These alerts are designed to remind them of the value of the platform and encourage them to resume their activities.
   - **Example Recommendation**: "Send re-engagement email"

2. **Targeted Course Suggestions**
   - **Objective**: To increase student engagement by suggesting relevant learning opportunities.
   - **Approach**: For students showing signs of churn or low participation in courses, we recommend popular courses tailored to their interests and past activities. This personalized approach helps in aligning course offerings with student preferences, thereby enhancing their engagement.
   - **Example Recommendation**: "Recommend popular courses based on interests"

3. **Incentivize Participation**
   - **Objective**: To encourage first-time or increased participation in learning opportunities.
   - **Approach**: Students with zero course participation receive incentives like reward points or badges to motivate them to join their first course or activity. This strategy is aimed at fostering initial engagement and encouraging continued participation.
   - **Example Recommendation**: "Offer incentives for first-time participation"


By implementing these personalized strategies, the platform can proactively address student churn, enhance engagement, and foster a more interactive learning environment. The recommendation system serves as a scalable approach to optimize student interactions based on real-time engagement data.

---

## 📊 Key Findings
1. **Top Factors for Churn**:
   - Low Engagement Score
   - Extended inactivity (Days Since Last Engagement > 126 days)
   - Limited Opportunity Participation (< 2 opportunities)
2. **Demographic Trends**:
   - Highest engagement among learners aged 18-28.
   - Significant interest from users in India, Nigeria, and the United States.
3. **Actionable Insights**:
   - Focus outreach on peak sign-up months to maximize engagement.
   - Address gaps in opportunity completion rates to reduce churn.


## 📌 Conclusion
This project successfully utilized data analysis and machine learning techniques to analyze student engagement and predict churn within an educational platform. The insights derived can be used to optimize retention strategies and enhance user experience.
