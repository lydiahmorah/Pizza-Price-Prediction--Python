# A Comprehensive Analysis of Pizza Pricing Factors and Predictive Modeling
- This project aims to develop a machine learning model capable of accurately predicting pizza prices based on various factors such as size, toppings, and company. 

- By analyzing a dataset of pizza orders, we explore the relationships between these variables and the price of the pizza.

- The primary objective is to create a reliable model that can assist businesses in pricing their pizza offerings competitively and profitably. 

- This model can also provide valuable insights into consumer preferences and market trends.

- The project follows a structured methodology, including data exploration, preprocessing, feature engineering, model selection, training, evaluation, and deployment. 
- Through this process, I aim to build a robust and effective machine learning solution for pizza price prediction.

# Task Guideline
- A.Import Libraries and data screening
    1.First 5 Rows

    2.Shape of the Data Set

    3.Get Information About Our Dataset Like Total Number Rows, Total Number of Columns, Datatypes of Each Column And Memory Requirement bold text
    
- B.Data cleaning
    - 5.Check Null Values In The Dataset bold text
6. Data Preprocessing
   -○	Rename the column price_rupiah to KES price (TO the currency of your choice).
    ○	Remove 'Rp' and commas from the price column and converted it to integers.
    ○	Converted the price column from Indonesian Rupiah to Kes.
    ○	Removed 'inch' from the diameter column and converted it to floats.
    ○	Displayed the first five rows after preprocessing using pizza_df.head().
7. Conduct Univariate Analysis for the columns:Company,Price,Diameter,Topping,Variant,Size,Extra Sauce & Extra Cheese
9. Conduct Bivariate Analysis:
Price by Company
Price by topping
Price by size
10. Find the most expensive pizza
11.Find diameters of jumbo size pizza
12. Find diameters of XL size pizza
13.Remove outliers in the jumbo size pizzas
14. Label Encoding
15. Create the Feature Matrix X and Response(Target) Vector y
16.Split the data into Train and Test sets
17.Building the Models
18. Training the models
19. Prediction on Test Data
20. Model Evaluation
21. Feature Importance
21.a. Random Forest
21.b.Gradient Boosting Regressor
21.c. XGBRegressor
22. Saving The Best Model