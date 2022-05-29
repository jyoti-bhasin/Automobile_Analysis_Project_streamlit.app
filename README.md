# Automobile Data Analysis :

## Data Analysis
- It is the process of systematically applying statistical and/or logical techniques to describe and illustrate, condense and recap, and evaluate data.

## Dataset used 
[https://github.com/jyoti-bhasin/Automobile_Analysis_Project_streamlit.app/blob/main/Book2.csv
](url)

## Technologies used :
### Language 
- *Python*- for programming and writing logic.
- *CSS* - for adding some UI/UX.
### Python libraries 
- api, beautifulsoup4, matplotlib, numpy, pandas, pickle_mixin, plotly, requests, scikit_learn.
### Algorithms 
- Machine Learning Algorithms such as Linear Regression and SVM Regression.
### APIs
- NewsAPI.
### Framework for deployment
- Streamlit.
### Hosted on 
- Streamlit share.

## Working of the app :
### Import libraries and dataset.
- First of all,import all the required modules and libraries of python.
- Then, the csv file is loaded to obtain dataset.
- Since our file does not have a lot of null values, or severe issues, we will just replace extra space by null values in the dataset, and it will be ready to use.
- The basic design and menu options are created. The navigation bar, home screen and about section details are added.

### Adding functionality : 1- feature
- Next, for the visual representation feature, a select menu is created for selecting features of cars, and to choose types of graphs. 
- The different types of graphs such as bar, line, area, scatter, pie, donut chart are visualised using the plost library of streamlit.
> - **Plost**- *is a deceptively simple plotting library for Streamlit, used for depicting data in the form of beautiful charts and graphs.*
- The dataset data is worked on and processed by several computations using the NumPy and Pandas library of Python.
> - **NumPy**- *It is  a Python package used for performing the various numerical computations and processing of the multidimensional and single-dimensional array elements.*
> - **Pandas**- *It is an open source Python package that is used for data science/data analysis and machine learning tasks.*
### 2- feature
- For the Dependency and analysis, similar menu , along with few conditions are applied, and feature to select type of graph is created. 
- Again, plost library of streamlit is used for visualization.
### 3- feature
- For the Price prediction feature, two models of Machine learning- Linear Regression and SVM Regression are made, and their pickle files are used in the app, for the prediction of price of cars, by taking input of features of the car. 
- These models are imported from sklearn library of Python.
> - **Sklearn**- *The sklearn library contains a lot of efficient tools for machine learning and statistical modeling including classification, regression, clustering and dimensionality reduction.*
> - **Linear Regression**- *It is a Machine Learning is used to predict the value of a variable based on the value of another variable.*
> - **SVM Regression**- *It is a supervised learning algorithm that is used to predict discrete values.*
### 4- feature 
- For the Automobile News generation, the news is shown on the app using the NewsAPI. It is extracted in a JSON format, hence converted to the readable text and all the details such as news headline, author, source, description, etc are displayed on the web page.
> NewsAPI link - [https://newsapi.org/docs/endpoints/everything](url)
### 5- feature
- Next, for the resolve queries section, three queries related to automobiles are chosen and a selection menu is created, to allow the user to choose a query to resolve. 
- Specific logic is written, utilizing the dataset to solve these queries to display the maximum or minimum values of a car feature, etc. 
- For the 'Grouping and Segmentation' query, K-Clustering Algorithm to form different groups which could depict best combinations of two features which most of the automobiles uses. A scatter graph is displayed to view these groups and segmentation.
> **K-Clustering Algorithm** -*It is an Unsupervised Learning algorithm, which groups the unlabeled dataset into different clusters. It allows us to cluster the data into different groups and a convenient way to discover the categories of groups in the unlabeled dataset on its own without the need for any training.*
### 6- feature
- For adding the functionality of last feature, web scraping, we will use the requests and BeautifulSoup library of Python.
> - **BeautifulSoup** - *It is a Python library for pulling data out of HTML and XML files.*
> - **Requests**- *It is a library for constructing and sending HTTP requests.*
- The data from a cars website is extracted, and all important details such as mileage, dealer name, rating, review count and price of few cars is stored in an excel sheet. 
- Now, data from this file is displayed on the app, along with a graph between rating and name of car. Besides, a selection menu is created for the user to choose a car, and the details related to that specific car will be displayed.

### Deployment
- After all the code is written, it is deployed on Streamlit framework, with a few changes to the code for errorfree deployment.
> **Streamlit** - *It is an open source app framework in Python language, which helps us create beautiful web apps for data science and machine learning.*
 
### UI/UX
- Although Streamlit provides a decent UI/UX design, some custom CSS is added in the code to improve the look of the app, and give some colours and design to the headings and text.

### Hosting 
- After all the code is ready and the app is all deployed, it is hosted on streamlit share.

## Functionality & features :
### 1. Visual Representation :
- You can visually represent the different features of cars such as engine size, length, width, horsepower, etc in the form of various *charts and graphs* such as bar, line, area, scatter, pie, donut chart. The charts and graphs are **interactive**; you can choose or select one or more features, and also the type of graphs.

### 2. Dependency & Analysis :
- You can check out the dependency and **variation** of one feature of an automobile with other features such as engine size, length, width, horsepower, etc , in the form of line and area graph. The charts and graphs are interactive; you can choose or select one or more features, and also the type of graphs.

### 3. Price Prediction :
- You can predict the price of a car by inputting several parameters such as width, horsepower, engine size etc. You can also choose the prediction model to predict the price - **Linear Regression or SVM Regression.**

### 4. Resolve Queries :
You can resolve various queries related to automobiles such as-
- find the cars with specific value of features , for example find the car names whose engine size is greater than 200, etc.
- find the highest/lowest values of the features, for example find the highest value of length or width of car, and the car names which possess these values,etc.
- find and view grouping and segmentation of two features ie to show best combinations of two specific features which are availabel.

### 5. Automobile News :
- News extracted using the NewsAPI can be shown here.You can **search a keyword** related to automobiles and get access to news related to it.

### 6. Web Scraping :
- You can access and analyse data such as car name, mileage, rating, price etc , from an online car website, by scraping data from web. Also, you can *view the graph* of rating of various cars, and get details of a specific car model.

## Application of Data Analysis in Automobile Industry
- In automobile industry, analyzed data is used to improve the customer experience, where data grouping and segmentation can lead to more *effective marketing and improved customer engagement , more targeted one‑to‑one offers* and can help the automobile industry to correctly manage the features and price of cars. 
-The analyzed data can be used for changing the **auto business, support mechanization, and boost automation.**
