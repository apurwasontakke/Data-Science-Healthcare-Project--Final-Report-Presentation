🩺 Data Science Healthcare Project: Predicting Drug Persistency

GitHub Repository: Data-Science-Healthcare-Project--Final-Report-Presentation

📜 Project Overview

In healthcare, understanding why patients continue or discontinue prescribed medications is crucial. This project aims to develop a machine learning model that predicts drug persistency, labeled as Persistency_Flag. By accurately identifying factors influencing drug adherence, this model supports targeted interventions to improve patient outcomes and optimize healthcare resources.

🔍 Problem Description

Drug persistency is essential for effective treatment and healthcare optimization. Discontinuation can lead to adverse health effects and increased costs. This project uses data analysis and machine learning to automate the identification of factors affecting drug persistency, helping healthcare providers make data-driven decisions to enhance medication adherence.

📊 Exploratory Data Analysis (EDA)

Data Cleaning: Ensured no missing values and analyzed numerical/categorical distributions.

Data Visualization: Used heatmaps, box plots, and histograms to understand relationships and distributions.

High positive correlation observed between Dexa_Freq_During_Rx and its log transformation.

Gender-based disparities in drug persistency, with non-persistent cases higher among females.

Outliers: Identified and analyzed outliers in Dexa_Freq_During_Rx and Count_Of_Risks.

⚙️ Model Development

We evaluated multiple machine learning models, including:

Logistic Regression: High interpretability, 81% accuracy

Random Forest: 80% accuracy, insights via feature importance

Gradient Boosting: Improved precision for persistent cases

Support Vector Machine (SVM): Best balance between precision and recall

Final Model: Optimized Logistic Regression, selected for its balanced performance, high interpretability, and consistency across metrics.

🚀 Technical Implementation

Preprocessing: Scaled data with StandardScaler, encoded categorical variables with OneHotEncoder.

Parameter Settings: Optimized Logistic Regression with C=0.1 and liblinear solver.

Deployment: Integrated the model into a production pipeline with real-time monitoring.

🎯 Results & Impact

Enhanced Decision-Making: Transparent model provides clear insights for strategic decisions.

Targeted Interventions: Identifies patients at high risk of discontinuation for timely intervention.

Resource Optimization: Pinpoints key factors influencing persistency for better resource allocation.

📝 Conclusion

This project demonstrated how data science and domain expertise can address real-world healthcare challenges. By deploying the optimized model, healthcare providers can improve patient adherence, reduce costs, and enhance overall treatment efficacy.

📈 Key Visualizations

Correlation Heatmap: Displays relationships between variables.

Box Plot: Shows distribution and outliers in Dexa_Freq_During_Rx.

Pair Plot: Visualizes pairwise relationships in data.

For more details, refer to the project report, code, and final presentation in this repository.
