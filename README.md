Automobile Data Analysis :

Data Analysis is the process of systematically applying statistical and/or logical techniques to describe and illustrate, condense and recap, and evaluate data.

Technologies used :
Language - Python.
Python libraries - api, beautifulsoup4, matplotlib, numpy, pandas, pickle_mixin, plotly, requests, scikit_learn, seaborn.
Machine Learning algorithms such as Linear Regression and SVM Regression.
Framework for deployment - Streamlit.
Hosted on - Streamlit share.

Working of the app :
First of all,import all the required modules and libraries of python.
Then, the csv file is loaded to obtain dataset.
Since our file does not have a lot of null values, or severe issues, we will just replace extra space by null values in the dataset, and it will be ready to use.
The basic design and menu options are created.
Next, in the visual representation option, a select menu is created for selecting features of cars, and to choose types of graphs. The different types of graphs such as bar, line, area, scatter, pie, donut chart are visualised using the plost library of streamlit.
For the Dependency and analysis, similar menu , along with few conditions are applied, and feature to select type of graph is created. Again, plost library of streamlit is used for visualization.
For the Price prediction feature, two models of Machine learning- Linear Regression and SVM Regression are made, and their pickle files are used in the app, for the prediction of price of cars, by taking input of features of the car.



Features :
1. Visual Representation :
You can visually represent the different features of cars such as engine size, length, width, horsepower, etc in the form of various charts and graphs such as bar, line, area, scatter, pie, donut chart. The charts and graphs are interactive; you can choose or select one or more features, and also the type of graphs.

2. Dependency & Analysis :
You can check out the dependency and variation of one feature of an automobile with other features such as engine size, length, width, horsepower, etc , in the form of line and area graph. The charts and graphs are interactive; you can choose or select one or more features, and also the type of graphs.

3. Price Prediction :
You can predict the price of a car by inputting several parameters such as width, horsepower, engine size etc. You can also choose the prediction model to predict the price - Linear Regression or SVM Regression.

4. Resolve Queries :
You can resolve various queries related to automobiles such as-
find the cars with specific value of features , for example find the car names whose engine size is greater than 200, etc.
find the highest/lowest values of the features, for example find the highest value of length or width of car, and the car names which possess these values,etc.
find and view grouping and segmentation of two features ie to show best combinations of two specific features which are availabel.

5. Automobile News :
News extracted using the NewsAPI can be shown here.You can search a keyword related to automobiles and get access to news related to it.

6. Web Scraping :
You can access and analyse data such as car name, mileage, rating, price etc , from an online car website, by scraping data from web. Also, you can view the graph of rating of various cars, and get details of a specific car model.
