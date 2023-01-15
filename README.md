Descriptions of Projetcs ----


-----------------------
Abalone Age Estimation
-----------------------
abalone Problem Statement -
The age of an abalone can be found by cutting its shell and counting the number of rings on the shell. 
In the Abalone Dataset, you can find the age measurements of a large number of abalones along with a lot of other physical measurements.

The goal of the project is to develop a model that can predict the age of an abalone based purely on the other physical measurements. T
his would allow researchers to estimate the abalone’s age without having to cut its shell and count the rings.

ML Algorithm implemented - kNN <br>
Fine Tuning of HyperParameters done using GridSearchCV 

Data taken from uci repository.

---------------------------------------------------------

-------------------------
Predicting CO2 emissions 
-------------------------
Here we have taken the data for a list of cars of the Government of Canada that produce some amount of emissions. From this data we can 
predict the CO2 emissions of the vehicle. Basically used both Simple Linear Regression and Multiple Linear Regresssion for the data 
to analyse the change in various evaluation parameters like Mean Absolute Deviation, Root Mean Squared Error and found a considerable 
decrease in these values on switching from Simple to Multiple Linear Regression as expected. Changes of the ealuation metrics when parameters
were changed in Linear Regression was much more observable than that of Multiple Linear Regression.

ML algorithms implemented - Simple Linear Regression, Multiple Linear Regression

Data taken from Canadian government archives.

-------------------------------------------------------------------------------------------------------------------

-------------------------
Predicting the Chinese GDP 
-------------------------
We have the data for the chinese gdp over the years starting from 1960 to 2015. Looking at the data curve, lower, highly steep in the middle and then a bit decrease
we observe that it shows a trend that can be easily fitted with a non-linear regression curve. The best beta1 and beta2 for the sigmoid function (beta 1 for the 
curve steepness and beta 2 to slide the curve on the axis) are found using the curve_fit function using the scipy.optimize library. We get a very good fit with 
almost best possible evaluation metrics(r2_score, MSE,MAD).

ML algorithm implemented - Non-Linear Regression

Data taken from IBM skills network database.

-------------------------------------------------------------------------------------------------------------------

-------------------------
Service Provider
-------------------------
A Telecommunications provider has segmented its customer base by service usage patterns, categorizing the customers into four groups. If demographic data can be used to predict group membership, the company can customize offers for individual prospective customers. It is a classification problem. That is, given the dataset, with predefined labels, we need to build a model to be used to predict class of a new or unknown case.
This uses various data parameters like demographic data,region, age etc. to predict usage patterns.

The target field, called custcat, has four possible values that correspond to the four customer groups, as follows: 1- Basic Service 2- E-Service 3- Plus Service 4- Total Service We will build a classifier, to predict the class of unknown cases.

ML algorithm implemented - K Nearest Neighbors

Data taken from IBM skills network database.
