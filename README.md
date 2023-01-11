# The Survivability of Passengers in Titanic Demise - A Machine Learning Approach in Python

Background and context

The Titanic, the largest British luxury passenger liner that is famous worldwide perished in the North Atlantic Ocean after striking with an iceberg on her inaugural journey from Southampton to New York City in the early hours of April 15, 1912. The tragic tragedy resulted in 1,500 deaths out of the 2,224 passengers and personnel on board the ship. Despite the passage of time, curiosity in the Titanic is now as high as it was then. Many people search tirelessly for facts about this disaster and hopefully it is very interesting on exactly what happened in that terrible, freezing cold April night? According to the historical facts, attempts were made to reach the neighboring vessels, and the life boats were instructed to rescue the passengers, giving priority to women and children. The Titanic sank with over a thousand passengers and staff members aboard. The unfortunate disaster startled the whole world and caused significant frustration due to lack of life boats, inadequate laws, and the unequal treatment of third class passengers during the evacuation. The study will intend to perform a statistical analysis on the Titanic Dataset available in Kaggle to determine unsinkable facts about the tragedy of Titanic.

Data Description

The data contains data of the passengers; Passenger name, age, sex, passenger class and whether they survived or not, port of entry, etc. It includes 12 variables and 891 passenger details with some missing values.

The data available in the Titanic dataset and its characteristics are given below.
•	Passenger ID – Unique number assigned to each passenger
•	Survived – Indicates whether the passenger is survived or not (survived – 0, died- 1)
•	Pclass – Passenger class (First class -1, Second class – 2, Third class - 3)
•	Name – Name of the passenger
•	Sex – Sex of the passenger (Male, Female)
•	Age – Age of the passenger
•	Sibsp – Number of siblings/spouses aboard
•	Parch – Number of parent/ children aboard
•	Ticket – Ticket number of the passenger
•	Fare – The price of the ticket
•	Cabin – The cabin category of the passenger
•	Embarked – The port of entry (Cherbourg – C, Q – Queenstown, S- Southampton)

Machine Learning models

The goal of the project was to predict which passengers survived in the Titanic disaster. Since the survivability was given in the dataset as survived-1 and not-survived - 0, 3 supervised machine learning models were trained.

•	Random Forest Classifier
•	Support Vector Machine 
•	Logistic Regression Model
