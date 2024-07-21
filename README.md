
# Credit-card fraudulent transaction check

Created various machine learning models to identify fraud transactions and analyzed the result using
PowerBI . The models used here are : Logistic Regression and Random Forest .

## 🚀 About Me
I'm a fourth-year Computer Science Engineering student with a deep passion for uncovering insights from
data. I'm on the lookout for opportunities in Data Science and Data Analysis where I can put my skills in
machine learning, statistical analysis, and data visualization to good use. I'm enthusiastic about applying
what I've learned to help drive data-driven decisions and make a real impact in the world.


## 🛠 Skills
Python , SQL , PowerBI , Tableau 


## Lessons Learned

### Challenge 1: Imbalanced Dataset

**Problem:** 
In building a credit card fraud detection model, one of the toughest issues was the imbalanced dataset, where fraudulent transactions were far fewer than legitimate ones. This imbalance made it hard for the model to accurately detect fraud.

**Solution:** 
To tackle this, I used SMOTE (Synthetic Minority Over-sampling Technique) to create synthetic examples of fraudulent transactions, ensuring a more balanced dataset. I also applied stratified sampling to maintain a fair representation of fraud cases in each training batch. Additionally, I focused on metrics like Precision, Recall, and the F1-Score, rather than just accuracy, to better evaluate the model’s effectiveness in identifying fraud.

### Challenge 2: Feature Engineering

**Problem:** 
Another challenge was identifying and creating the right features from the raw transaction data, which is essential for improving the model's performance. Raw data often needs significant preprocessing and feature extraction to be useful.

**Solution:** 
I carried out thorough exploratory data analysis (EDA) to understand the dataset and identify potential features. This included creating new features, such as the deviation of transaction amounts from a user's average, the time of transactions, and the frequency of transactions within a given period. Incorporating these engineered features into the logistic regression and random forest models substantially improved their accuracy and predictive power.

### Challenge 3: Outliers

**Problem:** 
Handling outliers was a significant challenge in the credit card fraud detection project. Outliers can distort the model’s understanding and reduce its predictive accuracy.

**Solution:** 
To manage outliers, I first identified them using statistical methods like the IQR (Interquartile Range) method and z-scores. Once identified, I tested various strategies such as capping and flooring the outliers or using robust scalers that minimize the influence of outliers. This preprocessing step helped in maintaining the integrity of the data and improved the overall performance and robustness of both the logistic regression and random forest models.


## Tech Stack
- **Python**

#### Development Environment:
- **Jupyter Notebook**

#### Libraries and Frameworks:
- **Pandas**
- **Scikit-learn**
- **Imbalanced-learn**

#### Business Intelligence:
- **Power BI**

