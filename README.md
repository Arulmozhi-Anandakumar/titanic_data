**🧹 Titanic Data Cleaning & EDA Project**📌 
**Project Overview**

This project is part of my data science learning journey. I worked on the classic Titanic dataset to practice data cleaning and exploratory data analysis (EDA) using Python.
The main goal was to clean the raw data, handle missing values, explore important features, and prepare it for future machine learning tasks.

**📊 Dataset Information**

The Titanic dataset contains details about passengers aboard the Titanic, including whether they survived the disaster.
Key columns include:

PassengerId – Unique ID for each passenger

Survived – Survival status (0 = No, 1 = Yes)

Pclass – Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd)

Name, Sex, Age – Personal details

SibSp, Parch – Family aboard

Ticket, Fare, Cabin, Embarked – Travel details

**🛠️ Tools & Libraries Used**

🐍 Python

📦 Pandas

📊 Matplotlib

🎨 Seaborn

☁️ Google Colab

**🧹 Data Cleaning Steps**

Here’s what I did in the data cleaning phase:

✅ Handled missing values in Age and Embarked

🗑️ Dropped the Cabin column due to excessive null values

🔁 Removed duplicate rows

🧼 Standardized categorical values (e.g., Sex)

🔄 Converted columns like Survived and Pclass to categorical

✏️ Renamed columns for better clarity

💾 Saved the cleaned dataset as cleaned_titanic.csv

**📊 Exploratory Data Analysis (EDA)**

To understand the data better, I explored:

📉 Survival distribution overall

👩‍🦱 Survival rates by gender and passenger class

📈 Age distribution of passengers

🔥 Correlation between key numerical features (Age, Fare, Survived)

**📁 Project Structure** 
titanic_data/
│
├── train.csv                # Original dataset
├── cleaned_titanic.csv      # Cleaned dataset
├── titanic_cleaning.ipynb   # Data cleaning notebook
├── titanic_eda.ipynb        # EDA notebook
└── README.md                # Project documentation

**🚀 Next Step**

The next phase of this project will involve building a machine learning model to predict passenger survival based on the cleaned dataset.

**🧠 What I Learned**

How to clean and preprocess real-world data

Handling missing values and duplicates

Performing basic exploratory data analysis

Creating visualizations to uncover patterns and insights

**📌 Dataset Source**

Kaggle – Titanic: Machine Learning from Disaster

✨ This project helped me build a strong foundation in data cleaning and EDA, which are essential skills for every aspiring data scientist.
