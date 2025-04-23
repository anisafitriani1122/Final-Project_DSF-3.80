# Final-Project_DSF-3.80
## Project Data Science - Anisa Fitriani

### Titanic Data Investigation
The tragic sinking of the Titanic in 1912 is one of the most infamous maritime incidents in history, with over 1,500 fatalities out of a total of over 2,200 passengers and crew. In this project, I analysed datasets curated from Frank Harrell's Hmisc Titanic Dataset to uncover patterns behind who survived and who did not. The main focus of the analysis included exploratory data analysis (EDA), data preprocessing, as well as testing several machine learning algorithms.

The dataset contains important information about Titanic passengers, such as name, gender, age, and safety status. Of the total 500 data rows and 4 main columns (name, sex, age, survived), only the age column contains missing values, which is 9.82%. The data cleaning process includes removing duplicates and imputing missing values using the median for numeric features. Meanwhile, categorical features such as sex were converted into numerical format using Label Encoding, and the AgeGroup feature was added to support analysis based on age categories.

The EDA results show duplicate data and missing values in the age column. From the visualisation, it can be seen that women and children have a higher probability of survival than adult men. The age distribution of passengers is mostly in the age range of 20-40 years, and the number of male passengers is recorded higher than that of females.

### Version Libraries (opsional)
pandas v1.5.3
numpy v1.22.4
seaborn v0.12.2
matplotlib v3.7.1
scikit-learn v1.2.2

### Insights
The insights I gained from this project include
1. Duplicate entries and missing values—particularly in the age column—were identified and addressed through a thorough data cleaning process.
2. Female passengers had a higher survival rate compared to male passengers, as evidenced by the results of data exploration and visualization.
3. Among the various machine learning models tested, the Support Vector Machine (SVM) demonstrated the best performance, achieving the highest scores.

### Advice
1. Perform more advanced data visualizations to uncover deeper insights.
2. Explore additional machine learning models beyond the three that have already been implemented.
