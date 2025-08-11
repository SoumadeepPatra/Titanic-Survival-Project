🚢 Titanic Survival Prediction

Objective:
The objective of this project is to develop a machine learning model that predicts whether a passenger aboard the Titanic survived or not, based on personal and travel-related attributes.

Dataset Description:
The dataset contains demographic and socio-economic information for individual passengers, including:

PassengerId – Unique identifier for each passenger

Pclass – Ticket class (1 = First, 2 = Second, 3 = Third)

Name – Passenger’s name

Sex – Gender of the passenger

Age – Passenger’s age in years

SibSp – Number of siblings/spouses aboard the Titanic

Parch – Number of parents/children aboard the Titanic

Ticket – Ticket number

Fare – Ticket fare

Cabin – Cabin number (if available)

Embarked – Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)

Survived – Survival status (0 = No, 1 = Yes) – Target variable

Methodology:

Data Preprocessing:

Handling missing values for variables like Age, Cabin, and Embarked

Encoding categorical variables (e.g., Sex, Embarked)

Feature scaling and selection of relevant features

Model Building:

Splitting the dataset into training and testing sets

Training classification algorithms such as Logistic Regression, Random Forest, or Decision Tree

Evaluating model performance using accuracy, precision, recall, and F1-score

Result:
The model was able to learn survival patterns based on socio-economic class, gender, and other features. For example, female passengers and those in higher classes generally had higher survival probabilities.

Conclusion:
This project demonstrates the end-to-end process of building a predictive machine learning model, including data preprocessing, feature engineering, model training, and evaluation. The Titanic dataset provides a simple yet effective platform for understanding classification problems, handling real-world data imperfections, and applying supervised learning techniques.

Tools & Libraries Used:

Python

Pandas, NumPy

Matplotlib, Seaborn (for visualization)

Scikit-learn (for machine learning models)
