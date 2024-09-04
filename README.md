**Coded Project - Predictive Modeling**  
**Course:** Predictive Modeling  
**Date:** January 2024  

**Overview:**  
This project is designed to apply and demonstrate predictive modeling techniques through two distinct but related analyses. It focuses on developing and implementing models to predict outcomes based on various attributes, using both linear and classification methodologies.

### Part A: Computer-activ Project

**Objective:**  
To predict the percentage of time the computer remains in user mode ('usr') using linear regression. The aim is to understand how different system attributes affect the CPU's time in user mode.

**Data Description:**  
The dataset includes system performance metrics collected from a Sun Sparcstation 20/712. Key attributes include:
- **Memory Transfers:** lread, lwrite
- **System Calls:** scall, sread, swrite, fork, exec
- **Page Management:** pgout, ppgout, pgfree, pgscan, atch, pgin, ppgin
- **Page Faults:** pflt, vflt
- **Queue and Memory:** runqsz, freemem, freeswap

**Methodology:**  
1. **Data Exploration:** Analyze data distribution and correlation between 'usr' and other attributes.
2. **Preprocessing:** Handle missing values and standardize attributes.
3. **Feature Selection:** Identify significant features influencing 'usr'.
4. **Model Building:** Develop a linear regression model to predict 'usr'.
5. **Evaluation:** Assess model performance using metrics like R-squared, MAE, and MSE.

### Part B: Women's Contraceptive Project

**Objective:**  
To classify whether married women use a contraceptive method based on their demographic and socio-economic attributes using classification techniques.

**Data Description:**  
The dataset consists of information from 1,473 married women, including:
- **Demographics:** Wife's age, education, number of children
- **Socio-Economic Factors:** Husband's education, occupation, standard-of-living index
- **Binary Variables:** Religion, employment status, media exposure

**Methodology:**  
1. **Data Exploration:** Examine the distribution of attributes and the target variable (contraceptive use).
2. **Preprocessing:** Address missing values, encode categorical variables, and normalize data.
3. **Feature Engineering:** Create and select relevant features to improve model accuracy.
4. **Model Building:** Apply classification algorithms (e.g., Logistic Regression) to predict contraceptive use.
5. **Evaluation:** Use metrics such as Accuracy, Precision, Recall, F1-score, and ROC-AUC to evaluate model performance.

### Skills & Tools Covered:
- **Linear Regression:** For predicting continuous outcomes.
- **Logistic Regression:** For binary classification tasks.
- **Data Preprocessing:** Handling missing data, encoding categorical variables.
- **Feature Engineering:** Creating and selecting relevant features.
- **Model Evaluation:** Assessing model performance with various metrics.

This project showcases the application of predictive modeling techniques to real-world problems, demonstrating proficiency in data analysis, model development, and performance evaluation.

---
