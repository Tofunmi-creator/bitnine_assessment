# bitnine_assessment
bitnine_assessment

This file contains solutions to question 3 & 4 of the "Bitnine Apache Internship Program - 2023" assessment in Nigeria.

Question 3

Please find in this directory a file named "question 3" containing solution to the third question for this assessment.

Solution Steps

1. Create_engine and text modules are imported from the sqlalchemy library to establish connection to the Postgres database.
2. A get_json function is created to implement an algorithm  that appends data objects extracted from the database to a dictionary in the required format.
3. The function returns the results in a json string format using the json.dumps method.




Question 4

Please find in this directory a file named "question 4" containing a dash program that displays network graphs and figures showing car model price data from the files contained in the "backend/test-data" folder in the AGE Viewer repository.

Solution Steps

1. Several libraries including the dash, plotly, networkx, pandas are imported to build the different components of this dash application.
2. A callback decorator and get_nx_info function are used to retrieve input from a dropdown menu containing car producers and to create network graghs linking car-producers to their respective models.
3. Another callback decorator and get_model_price function are used to also retrieve input(s) from a multi-select dropdown menu containing car producers and to create bar plots showing model price information for the different car producers.
