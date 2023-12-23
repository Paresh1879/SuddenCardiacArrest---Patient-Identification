# Sudden Cardiac Arrest - Patient Identification

## 1. About the problem statement​

## 2. Data Overview​

## 3. Exploratory Data Analysis​

## 4. Data PreProcessing and Wrangling​

## 5. Models building and evaluations


### 1. About the problem statement​

* We've been tasked with developing various prediction models to pinpoint individuals who are at the risk of SCA by collecting data from patient histories.

### 2. Data Overview​

* Contains demographic details including the patient's name, age, and gender.​
* And the metrics is based on patient's resting electrocardiogram, ST segment slope, resting blood pressure, and maximum heart rate achieved during a stress test.​
* Includes factors such as chest pain type, cholesterol levels, fasting blood sugar, exercise-induced angina, and ST depression induced by exercise relative to rest​.

### 3. Exploratory Data Analysis​

* This detailed summary provides insights into patient age, resting blood pressure (including zero values), cholesterol levels (including zero values), and maximum heart rate.​
* The correlation matrix also suggests that age is a significant factor in blood pressure, heart rate, and cholesterol levels.
*  As people age, their blood pressure tends to increase, while their maximum heart rate and cholesterol levels tend to decrease.​

### 4. Data PreProcessing and Wrangling​ 

* Handling Missing Values​
* Removing Duplicate Data​
* Outlier Detection and Removal​
* Feature Engineering - Introducing 'HeartRisk'
* Categorical Data Encoding​
* Feature Scaling​

### 5. Models building and evaluations 

* Decision Tree Model
* Random Forest Model
* Support Vector Machine
* K - Nearest Neighbors
* Gradient Boost

# Random Forest appears to be the winner 

* It has the highest accuracy and precision among the models, employs an ensemble of decision trees for enhanced predictive power.​
* Notable strengths include its ensemble nature, providing insights into feature importance, robustness to outliers, and a track record of high predictive accuracy. ​
* Overall, the Random Forest emerges as a compelling choice, excelling in both interpretability and performance.​
​
