# visualization-of-App-usage-metrics
**🎯 Objective:**
The aim of this project is to analyze and visualize how users interact with various mobile apps. It focuses on understanding patterns in screen time, frequency of app usage, and peak usage periods using visual analytics and machine learning algorithms.

**🧾 Step-by-Step Explanation:**
**1. Importing Libraries**
The project starts by importing Python libraries used for data manipulation and visualization such as:
Pandas for handling data,
Matplotlib and Seaborn for visualizing patterns
These tools are essential for turning raw data into understandable charts and graphs.

**2. Loading the Dataset**
App usage data is collected in a CSV file and loaded into the environment. The dataset includes information such as:

Date               
App                
Usage (minutes)    
Notifications      
Times Opened 
This data gives a full picture of how the user interacts with different apps.

**3. Initial Data Exploration**
The data is first explored to check its structure and quality. This includes:

Viewing sample rows
Checking data types
Identifying missing or duplicate records

This helps understand what kind of data we’re working with and what needs to be cleaned.

**4. Data Cleaning**
Unnecessary or duplicate records are removed

Date and time fields are formatted correctly

Categorical values (like app names) are handled appropriately

Cleaning ensures the dataset is accurate and ready for analysis.

**5. Feature Engineering**
Additional columns are derived from the existing data to help with analysis, such as:

Day of the week (e.g., Monday, Tuesday)
Hour of the day
Total screen time

These new features help break down usage into useful segments for better visualization.

**6. Data Visualization**
This is the core part of the project. Several charts and plots are created to display:

Total screen time per day: to spot trends in usage over time.

Most used apps: to identify which apps are opened most often.

Apps with longest usage time: to show which apps engage users the most.

Usage by hour and day: to detect patterns in daily and weekly usage behavior.

These visuals make the data easy to interpret and reveal clear usage trends.

**7. Algorithms Used (Machine Learning Models)**
This project also integrates machine learning algorithms to analyze and predict user behavior:

**🔹 Support Vector Machine (SVM)**
Used to classify user behavior patterns based on app usage.

It finds the optimal boundary (hyperplane) to separate different usage categories (like light, moderate, and heavy users).

**🔹 K-Nearest Neighbors (KNN)**
Used to classify a user’s usage level based on the similarity to other users.

It checks how similar a user's current behavior is to others in the dataset and assigns a label accordingly.

**🔹 Logistic Regression**
Used to predict the likelihood of certain behavior, like whether a user is likely to overuse an app or not.

It’s a statistical model used for binary classification (yes/no, high/low, etc.).

These algorithms were evaluated and compared to find which model best fits the app usage data. Their performance was measured using accuracy and confusion matrix values.

**8. Model Evaluation**
Each algorithm is tested using part of the dataset (test set). Their predictions are compared to the actual results to measure:

Accuracy (how often the model was correct)
Precision and Recall (how well it distinguishes between usage types)
F1 Score (balance between precision and recall)

The model with the highest accuracy and balanced metrics is considered best for predicting user behavior.

**✅ Conclusion:**
This project effectively combines data visualization and machine learning to understand and predict user interaction with mobile apps. It provides:

Insightful charts on usage patterns
Predictive models that classify or forecast usage behavior
A full cycle from data preprocessing to intelligent insights

**Result:**
K-Nearest algorithm have the best accuracy of 0.88

