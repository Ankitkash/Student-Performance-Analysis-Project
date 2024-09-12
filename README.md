# Student-Performance-Analysis-Project
This project analyzes student test scores from a fictional public school, aiming to identify potential interaction effects of various personal and socio-economic factors on student performance. The dataset includes three test scores (Math, Reading, Writing) and features such as gender, ethnicity, parental education, lunch type, test preparation, and other demographic variables.

## Key Features:
- **Data Analysis**: Exploration and visualization of the relationships between student performance and socio-economic factors.
- **Machine Learning**: Predictive modeling to identify key factors influencing test scores.
- **Python Libraries**: Utilized pandas, numpy, matplotlib, seaborn, and scikit-learn for data manipulation, visualization, and modeling.

## Dataset Overview
The dataset includes the following columns:
- **Gender**: Male/Female
- **EthnicGroup**: Group A to E
- **ParentEduc**: Parental education level (ranging from some high school to master's degree)
- **LunchType**: Standard or free/reduced lunch
- **TestPrep**: Completion of test preparation course (yes/no)
- **ParentMaritalStatus**: Married, single, widowed, or divorced
- **PracticeSport**: Frequency of practicing sports (never, sometimes, regularly)
- **IsFirstChild**: Whether the student is the first child (yes/no)
- **NrSiblings**: Number of siblings (0 to 7)
- **TransportMeans**: Means of transport to school (school bus/private)
- **WklyStudyHours**: Weekly study hours (<5, 5-10, >10 hours)
- **MathScore, ReadingScore, WritingScore**: Scores (0-100) in each subject

## Objectives
- **Data Exploration**: Investigate relationships between socio-economic factors and student performance using visualizations and statistical analysis.
- **Feature Importance**: Identify the most significant factors affecting student scores.
- **Predictive Modeling**: Use machine learning algorithms to predict student performance based on personal and socio-economic factors.
- **Insights and Recommendations**: Provide insights into how schools or parents can improve student outcomes.

## Tools & Libraries
- **Python**: Programming language used for data manipulation and analysis.
- **Pandas, NumPy**: For data cleaning, manipulation, and statistical analysis.
- **Matplotlib, Seaborn**: For creating insightful visualizations.

## Methodology
1. **Data Cleaning**: Handled missing or incorrect values, converted categorical features to numerical ones, and scaled continuous data.
2. **Exploratory Data Analysis (EDA)**: Visualized distributions, correlations, and patterns among student demographics and test scores.
3. **Feature Engineering**: Derived additional features from the dataset to improve model performance.
4. **Insights**: Analyzed how factors like parental education, test preparation, and weekly study hours impact performance in different subjects.

## Results & Findings
- **Test Preparation Impact**: Students who completed test preparation performed significantly better in all subjects.
- **Parental Education**: Higher parental education correlated with better performance in Reading and Writing.
- **Study Hours**: Students studying more than 10 hours weekly scored higher across all subjects.
- **Sports Practice**: Regular sports practice was positively associated with improved scores in Math and Writing.

## Conclusion
This project provides a detailed understanding of the factors that contribute to student success, offering actionable insights for educators and parents to improve academic outcomes.
