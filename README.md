# Surya Wedhana Data Analysis Project's 📊

Welcome to my Data Analysis repository! This repository contains data analysis projects that explore datasets, uncover insights, and answer key questions through structured analysis and visualization. All projects are implemented in Python, leveraging powerful data analysis libraries.

---

## Project 1: Analyzing Electronic Device User Behavior 📱

This project explores the behavior of electronic device users to identify patterns and trends.  

### Steps:
1. **Data Gathering**: Dataset from [Kaggle](https://www.kaggle.com/datasets/valakhorasani/mobile-device-usage-and-user-behavior-dataset).
2. **Data Wrangling**  
3. **Exploratory Data Analysis (EDA)**  
4. **Data Visualization**  
5. **Answering Key Questions**

### Dataset Columns:
- **User ID**: Unique identifier for each user.  
- **Device Model**: Model of the user's smartphone.  
- **Operating System**: The OS of the device (iOS or Android). 
- **App Usage Time**: Daily time spent on mobile applications, measured in minutes.  
- **Screen On Time**: Average hours per day the screen is active.  
- **Battery Drain**: Daily battery consumption in mAh. 
- **Number of Apps Installed**: Total apps available on the device.  
- **Data Usage**: Daily mobile data consumption in megabytes. 
- **Age**: Age of the user.
- **Gender**: Gender of the user (Male or Female).
- **User Behavior Class**: Classification of user behavior based on usage patterns (1 to 5).

### Key Questions:
1. How much time does each device model in different age groups spend on apps, and how many apps are installed?  
2. How much time do users of each gender spend on apps, and how many apps are installed?  
3. Is there a correlation between screen time and battery drain?  
4. Is there a correlation between the number of installed apps and battery drain?  
5. What operating system is used the most?  
6. Is there a correlation between gender and data usage?  

### Tools:
- Python, NumPy, Pandas, Matplotlib, Seaborn  

---

## Project 2: Employee Analysis for a Company 🏢

This project analyzes employee data to uncover workforce trends and insights.  

### Steps:
1. **Data Gathering**: Dataset from [Kaggle](https://www.kaggle.com/datasets/tawfikelmetwally/employee-dataset).
2. **Data Wrangling**  
3. **Exploratory Data Analysis (EDA)**  
4. **Data Visualization**  
5. **Answering Key Questions**  

### Dataset Columns:
- **Education**: Employee qualifications.  
- **Joining Year**: Year of recruitment.  
- **City**: Employee location.  
- **Payment Tier**: Salary category.  
- **Age**: Employee age.  
- **Gender**: Gender identity.  
- **Ever Benched**: Work assignment status.  
- **Experience in Current Domain**: Years of experience in the current field.  
- **Leave or Not**: Target column.  

### Key Questions:
1. How many employees with each degree have left versus stayed?  
2. How many employees were recruited each year?  
3. What is the average age of employees by degree?

### Machine Learning Classification

In this project, two machine learning classification models were applied to predict employee attrition (whether employees leave the company). The models used were **Logistic Regression** and **K-Nearest Neighbors (KNN)**.

1. **Logistic Regression**:  
   The Logistic Regression model achieved an accuracy of **63.5%**. This model helps to predict the probability of an employee leaving the company based on various features such as education, experience, and payment tier.

2. **K-Nearest Neighbors (KNN)**:  
   The KNN model outperformed the Logistic Regression model with an accuracy of **73.6%**. KNN is a non-parametric method that predicts the target variable based on the closest training examples in the feature space.

Both models were evaluated based on their accuracy and provided insights into factors influencing employee attrition.

### Tools:
- Python, NumPy, Pandas, Matplotlib, Seaborn  

---

Feel free to explore the notebooks, clone the repository, and share feedback or suggestions. Stay tuned for more projects! 🎉
