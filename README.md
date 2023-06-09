# SpaceX Falcon9 First Stage Landing Prediction

In this project, we will predict if the <font color='green'>SpaceX Falcon 9 first stage</font> will land successfully.<br />
SpaceX advertises Falcon 9 rocket launches on its website, with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage.<br />
Therefore, if we can determine if the first stage will land, we can determine the cost of a launch.<br />
This information can be used if an alternate company wants to bid against SpaceX for a rocket launch.<br />

<b>Part 1M</b>: Data Collection using Web Scraping<br />
In this part, web scraping is done using Python BeautifulSoup package, to collect Falcon 9 historical launch records from a Wikipedia page titled 'List of Falcon 9 and Falcon Heavy launches'<br />
https://en.wikipedia.org/wiki/List_of_Falcon\_9\_and_Falcon_Heavy_launches

<b>Part 2</b>: Data Collection using SpaceX API<br />
In this part, data is collected from the SpaceX API. Basic data wrangling and formatting is done.

<b>Part 3</b>: Data Wrangling<br />
In this part, Exploratory Data Analysis (EDA) is performed to find some patterns in the data and determine what would be the labels for training supervised models.

<b>Part 4</b>: Exploratory Data Analysis with Oracle or SQL<br />
In this part, the Spacex Dataset is loaded into a corresponding table in a oracle database and SQL queries are executed to better understand the data.

<b>Part 5</b>: Exploratory Data Analysis with Visualization<br />
In this part, exploratory data analysis and Feature Engineering is performed using Pandas and Matplotlib.

<b>Part 6</b>: Data Visualization using Folium<br />
In this part, more interactive visual analytics are performed using Python Folium package.

<b>Part 7</b>: Plotly Dashboard<br />
In this part, an interactive dashboard app is created based on the SpaceX dataset, using Python Dash and Plotly packages.

<b>Part 8</b>: SpaceX Machine Learning Prediction<br />
In this part, data is analysed, split into training and testing sets and 4 supervised models- Support Vector Machine, Decision Tree, K-Nearest Neighbours and Logistic Regression, are trained on the dataset.
The accuracy of each of the models is calculated to find the best prediction model.
