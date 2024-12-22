# Surya Wedhana Data Analysis Project's 📊

Welcome to my Data Analysis repository! This repository contains data analysis projects that explore datasets, uncover insights, and answer key questions through structured analysis and visualization. All projects are implemented in Python, leveraging powerful data analysis libraries.

---

## [Project 1: Analyzing Electronic Device User Behavior 📱](https://github.com/ngrlearningjourney/surya-wedhana-data-analysis-portofolio/blob/main/user_behavior_analysis.ipynb)

This project analyzes a dataset that provides insights into mobile device usage patterns and user behavior classification. The dataset, sourced from [Kaggle](<insert-dataset-link>), includes **700 samples** of user data, with key metrics such as app usage time, screen-on time, battery drain, and data consumption.

## Data Wrangling & Preprocessing

### Steps:
1. **Data Gathering**: The dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/valakhorasani/mobile-device-usage-and-user-behavior-dataset).
2. **Data Wrangling**:
   - Checked for **missing values**, **data format issues**, and **duplicate entries**.
   - Resolved issues with missing values and corrected data types to ensure accurate analysis.
3. **Exploratory Data Analysis (EDA)**:
   - Examined various aspects such as device usage patterns, app installation habits, and user demographics to understand mobile behavior across different user groups.

## Key Insights

1. **Device Usage by Age Group**:
   - Among adults, **OnePlus 9** users spend the least amount of time on mobile applications, averaging **30 minutes per day**.
   - For youths, **iPhone 12** and **Samsung Galaxy S21** users spend the least time on mobile apps, averaging **32 minutes per day**.

2. **Installed Applications**:
   - **Youth users** of the **Samsung Galaxy S21** have the **highest minimum number of installed applications**, with at least **19 apps** on their phones.
   - Both **youths and adults** using the **Google Pixel 5** have the same **minimum and maximum number of installed applications**.

3. **Gender Differences**:
   - **Female users** spend more time on mobile applications compared to male users, with a minimum daily usage of **31 minutes**.
   - **Male users** have the highest maximum daily screen time, spending up to **9 hours** on mobile applications.
   - Both **male and female users** have the same range for the number of installed applications, from **10 to 99 apps**.

4. **Operating System Usage**:
   - Based on the dataset, **Android** is the most used operating system, followed by **iOS**.
     
---

## [Project 2: Employee Analysis for a Company 🏢](https://github.com/ngrlearningjourney/surya-wedhana-data-analysis-portofolio/blob/main/employee_data_analysis.ipynb)

### Dataset Overview
This dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/tawfikelmetwally/employee-dataset) and formatted as a CSV file. It provides valuable insights into employee demographics, education, work history, and other employment-related factors within a company. The data includes 9 columns, capturing information such as education level, work tenure, age, gender, and other critical aspects.

### Data Wrangling and EDA
The first step in the analysis was to perform data wrangling, ensuring the dataset was clean and ready for analysis. This process involved:
- Checking for missing values and handling them appropriately.
- Ensuring correct data formats.
- Identifying and removing duplicated entries.

After the wrangling phase, I conducted Exploratory Data Analysis (EDA) to uncover trends and relationships within the data. Some key highlights from the analysis are:

### Key Insights:
- **1,232 employees** with a **Bachelor's degree** have not left the company.
- **328 employees** with a **Master's degree** have not left the company.
- **116 employees** with a **PhD** have not left the company.
- The highest number of employees were hired in **2017**, including:  
   - **367 Bachelor's degree holders**  
   - **227 Master's degree holders**  
   - **28 PhD holders**  
- The highest number of **Bachelor's** and **Master's** degree holders were hired in **2017**, with **367** and **227 individuals**, respectively.  
- The highest number of **PhD holders** were hired in **2013**, with **33 individuals**.
- The youngest **Bachelor's** degree holder is **22 years old**, and the oldest is **41 years old**.
- The youngest **Master's** degree holder is **23 years old**, and the oldest is **41 years old**.
- The youngest **PhD** holder is **22 years old**, and the oldest is **41 years old**.

### Classification Model
To predict whether an employee would leave the company, I built classification machine learning models using two algorithms:
1. **Logistic Regression**: Achieved an accuracy of **66.7%**.
2. **K-Nearest Neighbors (KNN)**: Achieved an accuracy of **71.8%**.

Both models helped identify patterns and factors contributing to employee retention and turnover.


---

# [Project 3: Student Performance Analysis 📚](https://github.com/ngrlearningjourney/surya-wedhana-data-analysis-portofolio/blob/main/student_performance_analysis.ipynb)

This project analyzes a dataset to identify key factors that influence student performance in exams. The dataset, sourced from [Kaggle](https://www.kaggle.com/datasets/lainguyn123/student-performance-factors), includes a comprehensive overview of various factors affecting students' academic success, such as study habits, attendance, parental involvement, and more.

## Data Wrangling & Preprocessing

### Steps:
1. **Data Gathering**: The dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/lainguyn123/student-performance-factors).
2. **Data Wrangling**:
   - Checked for **missing values**, **data format issues**, and **duplicate entries**.
   - Resolved issues with missing values and corrected data types to ensure accurate analysis.
3. **Exploratory Data Analysis (EDA)**:
   - Examined various aspects such as student motivational levels, availability of educational resources, and parental involvement to gain insights into factors influencing academic performance.

## Key Insights

1. **Spearman Correlation Analysis**:
   - The **Percentage of Classes Attended** shows the **highest correlation** with exam scores, with a correlation coefficient of **0.672366**.
   - The **Number of Hours Spent Studying per Week** has the **second highest correlation**, with a coefficient of **0.480956**.
   - These findings highlight the **moderate positive relationship** between attendance, study habits, and exam performance, while suggesting that other factors may also influence outcomes.

2. **Study Hours by School Type**:
   - There is no significant difference in the **maximum number of hours spent studying per week** between private and public school students: **44 hours** for private school students vs. **43 hours** for public school students.
   - The **minimum study time** reported is **1 hour** per week for both school types.

3. **Teacher Quality and Exam Scores**:
   - Students with **high and medium teacher quality** achieved similar maximum exam scores (100), with average exam scores ranging between **66** and **67** across all teacher quality categories.
   
4. **Extracurricular Activities and Performance**:
   - **87 students** who scored above **75** participate in **extracurricular activities**, indicating a higher proportion of high performers among this group.
   - However, **37 students** who do not participate in extracurricular activities also scored above **75**, suggesting that extracurricular involvement may be associated with better performance, but it's not a definitive factor for all high performers.

5. **Tutoring and High Exam Scores**:
   - The majority of students with **high exam scores** (above 90) attend **tutoring sessions once a month**, making this frequency the most common among top performers.

---
# [Project 4: Supermarket Purchase Analysis 🛒](https://github.com/ngrlearningjourney/surya-wedhana-data-analysis-portofolio/blob/main/supermarket_analysis.ipynb)

This project analyzes supermarket purchase data to identify key trends and insights. The dataset, sourced from [Kaggle](https://www.kaggle.com/datasets/arunjangir245/super-market-sales), contains several columns such as **branch**, **city**, **product line**, **gross income**, **rating**, **unit price**, **COGS (Cost of Goods Sold)**, **date**, **time**, and **payment method**. 

## Data Wrangling & Preprocessing

### Steps:
1. **Data Gathering**: The dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/arunjangir245/super-market-sales).
2. **Data Wrangling**:
   - Checked for **missing values**, **data format issues**, and **duplicate entries**.
   - Resolved issues by handling missing values and correcting data formats to ensure the dataset is ready for analysis.
3. **Exploratory Data Analysis (EDA)**:
   - Performed a comprehensive EDA to uncover key trends, relationships, and patterns in the data. Analyzed key metrics such as gross income, COGS, product ratings, and transaction times.

## Key Insights

1. **Gross Income**:
   - The **highest gross income** was recorded in **January**, totaling **$5,537 USD**.

2. **Customer Ratings**:
   - Both **female** and **male customers** gave an **average rating of 6.9**.
   - The **lowest rating** given by both genders is **4 out of 10**.

3. **Cost of Goods Sold (COGS)**:
   - The **highest COGS** for **Electronic Accessories** is recorded in **Mandalay City**, amounting to **897 USD**.
   - The **highest COGS** for **Fashion Accessories** is recorded in **Yangon City**, amounting to **989 USD**.
   - **Naypyitaw City** has the highest COGS in **Food and Beverages**, **Health and Beauty**, **Home and Lifestyle**, and **Sports and Travel** product lines.

4. **Monthly Trends**:
   - **January** was the busiest month with **352 transactions**, followed by **March** with **345 transactions**. **February** recorded the lowest number of transactions at **303**.

5. **Highest Gross Income by Branch**:
   - **Branch C** recorded the highest gross income, amounting to **$5,265 USD**, while **Branch A** and **Branch B** showed similar performance.

6. **Transactions by Membership**:
   - **Members** made the highest total purchases in **January**, amounting to **57,914 USD**.
   - **Normal customers** also recorded their highest purchases in **January**, totaling **58,377 USD**.

7. **Peak Times by Branch**:
   - **Branch A** and **Branch C** have the busiest times at **10 AM**, while **Branch B** peaks at **7 PM**.

8. **Product Ratings by Branch**:
   - **Branch A**: The **Health and Beauty** product had the highest rating of **10/10**, while **Food and Beverage** had the lowest at **4/10**.
   - **Branch B**: Both **Electronic Accessories** and **Sports and Travel** had the highest rating of **10/10**, while the lowest rating was given to **Food and Beverage** and **Health and Beauty**.
   - **Branch C**: The **Sports and Travel** product received the highest rating of **10/10**, while **Fashion Accessories** and **Food and Beverage** had the lowest at **4/10**.
---

# [Project 5: Hotel Reservation Data Analysis 🏨](https://github.com/ngrlearningjourney/surya-wedhana-data-analysis-portofolio/blob/main/hotel_reservation_analysis.ipynb)

This project analyzes hotel reservation data to uncover insights about booking trends, customer preferences, room types, and cancellations. The dataset, sourced from [Kaggle](https://www.kaggle.com/datasets/ahsan81/hotel-reservations-classification-dataset), contains details such as the number of adults and children in each booking, booking time, arrival time, meal preferences, room type preferences, and special requests.

## Data Wrangling & Preprocessing

### Steps:
1. **Data Gathering**: The dataset was sourced from [Kaggle](https://www.kaggle.com/datasets/ahsan81/hotel-reservations-classification-dataset).
2. **Data Wrangling**:
   - Checked for **missing values**, **data format issues**, and **duplicate entries**.
   - Corrected **data formats** to make the dataset easier to analyze.
   - Cleaned and processed the data to ensure that it was in a readable and usable form for further analysis.

3. **Exploratory Data Analysis (EDA)**:
   - Conducted a deep analysis to understand the distribution of bookings, room preferences, customer demographics, and special requests.
   - Generated insights based on patterns observed in the dataset using visualizations and statistical analysis.

---

## Key Insights

1. **Room Type Preferences**:
   - The most reserved room type by customers bringing children is **Room Type 1**, accounting for **54.6%** of all bookings.
   - The second most reserved room type is **Room Type 6**, accounting for **29.1%** of all bookings.

2. **Group Size**:
   - The most common group size for hotel reservations is **2 people**.
   - **15,573 reservations** were made for **2 people in a single room**.

3. **Monthly Booking Trends**:
   - **October** recorded the highest number of bookings with **3,423 bookings**.
   - **September** followed with **3,067 bookings**, and **December** recorded **2,603 bookings**.

4. **Repeated Guests**:
   - **Repeated guests** most commonly reserve **Room Type 1**, accounting for **86.8%** of all bookings by repeat customers.
   - The second most reserved room type by repeated guests is **Room Type 4**, which accounts for **7.3%** of the booking data.

5. **Room Type Cancellations**:
   - **Room Type 1** has the highest number of cancellations, with **9,072 bookings cancelled**.
   - At the same time, **Room Type 1** also has the highest number of non-cancelled bookings, totaling **19,058 bookings not cancelled**.

6. **Special Requests**:
   - **Room Type 1** has the highest number of special requests, with **15,691 special requests**.
   - **Room Type 3** has the lowest number of special requests among all room types.

7. **Spearman Correlation**:
   - The **number of special requests** has the **highest correlation** with **booking status**, with a **correlation coefficient of 0.256**.
   - This indicates a **weak to moderate positive relationship**, suggesting that special requests may influence the booking status but are not the most significant factor.

## Tools & Libraries Used:
- **Python**, **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**, **Sklearn**
- **Spearman Correlation** for identifying relationships between variables

---

Feel free to explore the notebooks, clone the repository, and provide feedback or suggestions for further analysis!

