# Sales Prediction Using Python



### **Problem**



Every business wants to know one thing: How much can we expect to sell?



Advertising plays a big role in sales, but deciding where to invest the marketing budget isn't always straightforward. Should more money go into TV advertising? Is Radio still effective? Does Newspaper advertising make a noticeable difference?



In this project, I built a Linear Regression model to predict product sales using advertising expenditure data. Along the way, I explored how spending across different advertising channels relates to sales and how well those relationships can be used to make predictions.



### **The Challenge**



Companies spend money on different advertising platforms, but each one affects sales differently. Without analyzing the data, it's difficult to know which channels are worth investing in.



This project answers questions like:



* Which advertising channels have the strongest relationship with sales?
* Can advertising spending be used to predict future sales?
* How well does a Linear Regression model perform on this dataset?



### **Project Goal**



The objective was to build a machine learning model that predicts sales using advertising data and to examine how TV, Radio, and Newspaper advertising influence the results.



Besides making predictions, the project also focuses on understanding the relationships within the data rather than treating the model as a black box.



#### **Dataset**



The dataset contains advertising budgets for three marketing channels along with their corresponding sales figures.



#### **Features**



* TV
* Radio
* Newspaper



#### **Target**



* Sales



Before starting the analysis, the Unnamed: 0 column was removed because it only contained row numbers and wasn't useful for the model.



### **Project Workflow**



The project follows these steps:



* Loaded and explored the dataset.
* Cleaned the data and checked for missing values.
* Visualized relationships using pairplots and a correlation heatmap.
* Split the data into training and testing sets.
* Trained a Linear Regression model.
* Evaluated the model using regression metrics.



### **Results**



The model performed well on the test dataset.



* MAE: 1.4608 
* MSE: 3.1741 
* RMSE: 1.7816 
* R² Score: 0.8994 



An R² score of approximately 0.90 means the model explains a large portion of the variation in sales, making it a strong baseline model for this dataset.



### **What I Learned**



Working on this project helped me understand more than just building a regression model.



I learned how to:



* prepare raw data before training a model
* explore relationships between variables through visualizations
* interpret regression metrics instead of relying on accuracy alone 
* understand how feature importance can support business decisions 



One interesting finding was that TV and Radio advertising showed a stronger relationship with sales than Newspaper advertising.



### **Future Improvements**



There are several ways this project could be expanded.



Try other regression models and compare their performance.

Use cross-validation to evaluate the model more thoroughly.

Build a simple Streamlit app where users can enter advertising budgets and predict sales.

Test the model on larger datasets.



### **Author**



[Syeda Eshaal Ali](https://www.linkedin.com/in/syedaeshaal-ali/)



