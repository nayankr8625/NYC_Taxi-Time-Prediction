<p align="center"> 
  <img src="https://cdn-images-1.medium.com/fit/t/1600/480/1*0VrGI7no8VdwehuLCp4xew.jpeg" >
  <h3 align="center"> AlmaBetter Verfied Project - <a href="https://www.almabetter.com/"> AlmaBetter School </a> </h5>
</p>
<p align="center"> 
   <img src="https://media.giphy.com/media/arZ261VdyAuXu/giphy.gif"  width="300px" height="200px">
</p>
<h1 align="center">NYC Taxi Trip Time Prediction</h1>

<p>Developed various models to predict the total ride duration of taxi trips in New York City</p>

<h2> :floppy_disk: Data Description</h2>

- **The dataset is based on the 2016 NYC Yellow Cab trip record data made available in Big Query on Google Cloud Platform. The data was originally published by the NYC Taxi and Limousine Commission (TLC). The data was sampled and cleaned for the purposes of this project. Based on individual trip attributes, you should predict the duration of each trip in the test set.**

- **NYC Taxi Data.csv - the training set (contains 1458644 trip records)**

<h2> :floppy_disk: Project Files Description</h2>

<p>This Project includes 1 executable files, 3 text files as well as 1 directories as follows:</p>
<h4>Executable Files:</h4>
<ul>
  <li><b>NYC_Taxi_Trip_Time_Prediction_Capstone_Project.ipynb</b> - Includes all functions required for Regression operations.</li>
  <li><b>Project presentation.docx</b> - Contains all the analysis which is presented after completing the analysis.</li>
  <li><b>Project report.pdf</b> - Contains whole analysis strategy and analysis methodology followed for the project.</li>
</ul>

<h4>Source Directories:</h4>
<ul>
  <li><b>NYC Taxi Data.csv</b> - Includes all the required data for the Regression task.</li>
</ul>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :book: XGBOOST (Ensemble Model) </h2>
<p>
XGBoost is an optimized distributed gradient boosting library designed to be highly efficient, flexible and portable. It implements machine learning algorithms under the Gradient Boosting framework. XGBoost provides a parallel tree boosting (also known as GBDT, GBM) that solve many data science problems in a fast and accurate way.

<img src ="https://media.geeksforgeeks.org/wp-content/uploads/20210707140912/Bagging.png" style ="max-width:100">
</p>
<p>Before beginning with mathematics about Gradient Boosting, Here’s a simple example of a CART that classifies whether someone will like a hypothetical computer game X. The example of tree is below:

The prediction scores of each individual decision tree then sum up to get  If you look at the example, an important fact is that the two trees try to complement each other. Mathematically, we can write our model in the form
<img src="https://www.geeksforgeeks.org/wp-content/ql-cache/quicklatex.com-87f26227761074a39338c48dc7e18650_l3.svg" alt="Formula 2" style="max-width:100%;"></p>

<p>where, K is the number of trees, f is the functional space of F, F is the set of possible CARTs. The objective function for the above model is given by:</p>
<img src="https://www.geeksforgeeks.org/wp-content/ql-cache/quicklatex.com-efa461b91d41d448daf09c1bbab0ab74_l3.svg" alt="Formula 3" style="max-width:100%;"></p>

<p>where, first term is the loss function and the second is the regularization parameter. Now, Instead of learning the tree all at once which makes the optimization harder, we apply the additive stretegy, minimize the loss what we have learned and add a new tree which can be summarised below:<p>

<img src="https://www.geeksforgeeks.org/wp-content/ql-cache/quicklatex.com-fee37eb06f4977678672dcf31351dbe4_l3.svg" alt="Formula 3" style="max-width:100%;"></p>

#### XGBoost minimizes a regularized (L1 and L2) objective function that combines a convex loss function (based on the difference between the predicted and target outputs) and a penalty term for model complexity (in other words, the regression tree functions). 

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :clipboard: Execution Instruction</h2>
<p>The order of execution of the program files is as follows:</p>
<p><b>1) Health_Insurance_Cross_Sell_Prediction.ipynb</b></p>
<p>The Health_Insurance_Cross_Sell_Prediction.ipynb is to be executed to access all the analysis done for classification operations.</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- Conclusions -->
<h2 id="conclusions"> :scroll: Conclusions</h2>

<p><b>1) Regression analysis was conducted to create a system that can assist taxi companies in determining the duration of cab trips, thereby improving their business models and enhancing customer availability.</b></p>
<p><b>2) The problem statement was resolved by using various regression techniques, including linear regression, decision trees and XGBOOST regressions.</b></p>
<p><b>3) Preparing the data for analysis and loading it for machine learning models involved PCA transformation, feature engineering, and forward Feature selection.</b></p>
<p><b>4) Various regression models were processed and XGBOOST performed better than other models with high R2 score and low RMSE score with 97% accuracy.</b></p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- Future Work -->
<h2 id="Future Work"> :scroll: Future work</h2>

**- As this data set is of only almost 6 months and I think there should be more data for more than a year and also some more features should be there so that we can train our models with more significant information that will help our model to learn more efficiently so that we can get more higher performance from Machine Learning Models.**

**- And also we can extract more information about this data by getting more features so that we can explore more about this kind of data**


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)


<!-- CREDITS -->
<h2 id="credits"> :scroll: Credits</h2>

Nayan Kumar | Data Scientist | Machine Learning Engineer | Deep Learning 

<p> <i> Contact me for Data Science Project Collaborations and Data Science related job roles</i></p>


[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nayan8625/)
[![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nayankr8625)

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
<h2> :books: References</h2>
<ul>
  <li><p>XGBoost has helped to understand more about XGBOOST</p>
      <p>Available: https://xgboost.readthedocs.io/en/stable/</p>
  </li>
  <li><p>Geeksforgeek helped to understand the working of xgboost more effciently and easily.</p>
      <p>Available: https://www.geeksforgeeks.org/xgboost/</p>
  </li>
  <li><p>Medium.com, 'NYC Taxi Trip Duration Prediction using Machine Learning'. [Online].</p>
      <p>Available: https://medium.com/@ShortHills_Tech/nyc-taxi-trip-duration-prediction-using-machine-learning-a92874bd761</p>
  </li>
  <li><p>Youtube.com, 'NYC taxi trip duration'. [Online].</p>
      <p>Available: https://www.youtube.com/watch?v=p1OnQfFfJeU</p>
  </li>
  <li><p>Reseachgate, 'NYC Taxi Trip and Fare Data Analytics using BigData'. [Online].</p>
      <p>Available: https://www.researchgate.net/publication/287205557_NYC_Taxi_Trip_and_Fare_Data_Analytics_using_BigData</p>
  </li>
  <li><p>lexisnexis.machinelearnigmastry, 'Regression Metrics for Machine Learning'. [Online].</p>
      <p>Available: https://machinelearningmastery.com/regression-metrics-for-machine-learning/</p>
  </li>
</ul>

# **Thank you so much for visiting :smile:**

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
