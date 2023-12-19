# Overview
The "Pima Indians Diabetes Analysis" project is a comprehensive data science endeavor focused on exploring the prevalence and characteristics of diabetes within the Pima Indian community. This community has been noted for its high incidence of diabetes, particularly among women.

# Objective
The primary goal of this project is to conduct an Exploratory Data Analysis (EDA) to uncover patterns, correlations, and insights related to diabetes within the Pima Indian tribe. The analysis focuses on various factors that might contribute to the prevalence of diabetes, such as genetic and environmental factors.

# Data Source
The dataset used in this project includes medical records of female patients from the Pima Indian community, aged 21 years or older. It provides a range of variables that are potentially linked to diabetes, including:

  Pregnancies: Number of times pregnant \
  Glucose: Plasma glucose concentration (2-hour oral glucose tolerance test) \
  BloodPressure: Diastolic blood pressure (mm Hg) \
  SkinThickness: Triceps skin fold thickness (mm) \
  Insulin: 2-hour serum insulin (mu U/ml) \
  BMI: Body mass index (weight in kg/(height in m)^2) \
  DiabetesPedigreeFunction: Score indicating likelihood of diabetes based on family history \
  Age: Age in years \
  Outcome: Indicator variable (0: non-diabetic, 1: diabetic) 

# Methodology
The analysis begins with importing essential Python packages for data manipulation and visualization, including Numpy, Pandas, Seaborn, and Matplotlib. A detailed examination of the dataset is performed, including assessing data quality, exploring distributions of various variables, and identifying potential correlations. The project also includes visualizations such as graphs and charts to aid in the interpretation of data.

# Key Findings and Insights
Age v/s Pregnancies show the most positive correlation of 0.54 indicating that they show the strongest positive relationship out of all other variables in the dataset. At glucose concentration greater than and equal to almost 60 units but lesser than and equal to 180 units, there seems to be a data point corresponding to same insulin level for each glucose concentration value. Skinthickness variable and DiabetesPedigreeFunction variable seem to be rightly skewed for both women who have diabetes as well as who donot have diabetes. The Glucose variable seems to be more rightly skewed for women who donot have diabetes as compared to the women who have diabetes. Refer to the code for rest of the insights.

**To replicate this analysis or to explore the dataset further, one should have a Python environment set up with necessary libraries installed. The Jupyter Notebook provides a step-by-step guide to the analysis, making it easy to follow and modify for further exploration.**

# Conclusion
This project contributes to the understanding of diabetes within a specific community and demonstrates the power of data science in uncovering health-related insights. It serves as a valuable resource for students, researchers, and healthcare professionals interested in the intersection of data science and healthcare.

# Acknowledgments
This project was completed as a part of the MIT - Applied Data Science Program. Special thanks to MIT Professional Education for providing the dataset and the opportunity to work on this insightful analysis. Their support and resources were invaluable in the successful completion of this project.
