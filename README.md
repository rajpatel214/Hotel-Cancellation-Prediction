# Hotel-Cancellation-Prediction


Hotels face frequent booking cancellations, leading to revenue loss and inefficient resource planning. This project aims to predict whether a booking will be canceled based on customer details, booking preferences, and external factors. By using data analysis and machine learning, hotels can improve decision-making and reduce cancellations.

**Understanding the Data**
Before building the model, it was important to explore and clean the dataset:

Checked dataset structure to understand the number of rows, columns, and data types.
Identified missing values and handled them properly to ensure clean data.
Analyzed customer behavior by looking at features like country, agent details, and number of children.
Explored correlations between different features to understand cancellation patterns.

**Data Visualization & Insights**
To better understand cancellation trends, several graphs and charts were used:

Bar charts showed cancellation trends by country.
Pie charts helped analyze the percentage of canceled vs. confirmed bookings.
Heatmaps revealed how different features are related to cancellations.

**Machine Learning Model Performance**
To predict cancellations, multiple machine learning models were tested:
Random Forest Classifier performed well but showed signs of overfitting.
Ridge Classifier achieved the highest accuracy, balancing performance and generalization.
Logistic Regression provided a simpler approach with good accuracy.

**Key Findings**
The Ridge model performed best with **96% accuracy.**
Random Forest overfitted to training data, making it less reliable for new data.
Logistic Regression was simpler and still gave a decent **84% accuracy**.
The dataset needed careful feature selection to improve predictions further.

**Final Thoughts**
This project highlights how data science can help hotels reduce cancellations, improve revenue, and make better business decisions. By analyzing patterns and applying machine learning, hotels can develop strategies to minimize booking cancellations and optimize operations.
