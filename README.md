
</p>
<h1 align="center"> Cardiovascular Risk Prediction </h1>
<h3 align="center"> AlmaBetter Verfied Project - <a href="https://www.almabetter.com/"> AlmaBetter School </a> </h5>


   ![ijcc-4-103-003](https://user-images.githubusercontent.com/109129303/178421226-f434306d-d081-4e1c-8df3-3c4fc109322a.gif)



<p>Built scalable machine learning model that alarms patient with 10 year risk of coronary heart disease and enables timely treatment to prevent it</p>

<h2> :floppy_disk: Project Files Description</h2>

<p>This Project includes 2 executable files, 1 text files , 1 directories as follows:</p>
<h4>Executable Files:</h4>
<ul>
  
  <li><b>Cardiovascular_Risk_Prediction.ipynb</b> - Includes all information on imputing missing values, outlier detection and Feature engineering process and Exploratory data analysis.</li>
  <li><b>Model_performance_cardiovascular (1).ipynb</b> -  Contains information on model performance of the classification algorithms on unseen data and model performance after hyperparameter tuning using random search cv</li>
</ul>

<h4>Output Files:</h4>
<ul>
  <li><b>result.txt</b> - Contains information about Accuracy and Recall scores from respected models.</li>
  
  </ul>

<h4>Source Directories:</h4>
<ul>
  <li><b>Dataset</b> - Includes all dataset  for the training phase  and testing phase of the model in the csv format.</li>
  
</ul>


</ul>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :book: Random Forest Regression </h2>

<p> Classification in random forests employs an ensemble methodology to attain the outcome. The training data is fed to train various decision trees. This dataset consists of observations and features that will be selected randomly during the splitting of nodes.

A rain forest system relies on various decision trees. Every decision tree consists of decision nodes, leaf nodes, and a root node. The leaf node of each tree is the final output produced by that specific decision tree. The selection of the final output follows the majority-voting system. In this case, the output chosen by the majority of the decision trees becomes the final output of the rain forest system. The diagram below shows a simple random forest classifier.
  
  ![24015Random+Forest](https://user-images.githubusercontent.com/109129303/178424318-1155742e-c4b3-43e2-b87f-4021025d28ca.jpg)

<h2> :book: Logistic Regression </h2>

<p>  Logistic regression estimates the probability of an event occurring, such as voted or didn’t vote, based on a given dataset of independent variables. Since the outcome is a probability, the dependent variable is bounded between 0 and 1. In logistic regression, a logit transformation is applied on the odds—that is, the probability of success divided by the probability of failure. This is also commonly known as the log odds, or the natural logarithm of odds, and this logistic function is represented by the following formulas:

Logit(pi) = 1/(1+ exp(-pi))

ln(pi/(1-pi)) = Beta_0 + Beta_1*X_1 + … + B_k*K_k

In this logistic regression equation, logit(pi) is the dependent or response variable and x is the independent variable. The beta parameter, or coefficient, in this model is commonly estimated via maximum likelihood estimation (MLE). This method tests different values of beta through multiple iterations to optimize for the best fit of log odds. All of these iterations produce the log likelihood function, and logistic regression seeks to maximize this function to find the best parameter estimate. Once the optimal coefficient (or coefficients if there is more than one independent variable) is found, the conditional probabilities for each observation can be calculated, logged, and summed together to yield a predicted probability. For binary classification, a probability less than .5 will predict 0 while a probability greater than 0 will predict 1.  After the model has been computed, it’s best practice to evaluate the how well the model predicts the dependent variable, which is called goodness of fit.
  
  ![LogReg_1](https://user-images.githubusercontent.com/109129303/178425033-25cd5a4e-673f-4409-a55d-98b2ffd6ecf6.png)

  <h2> :book: KNN </h2>

<p> 
The k-nearest neighbors algorithm, also known as KNN or k-NN, is a non-parametric, supervised learning classifier, which uses proximity to make classifications or predictions about the grouping of an individual data point. While it can be used for either regression or classification problems, it is typically used as a classification algorithm, working off the assumption that similar points can be found near one another.


For classification problems, a class label is assigned on the basis of a majority vote—i.e. the label that is most frequently represented around a given data point is used. While this is technically considered “plurality voting”, the term, “majority vote” is more commonly used in literature. The distinction between these terminologies is that “majority voting” technically requires a majority of greater than 50%, which primarily works when there are only two categories. When you have multiple classes—e.g. four categories, you don’t necessarily need 50% of the vote to make a conclusion about a class; you could assign a class label with a vote of greater than 25%
  
  
![download](https://user-images.githubusercontent.com/109129303/178426275-0ed98170-d325-40af-9d5d-60b99cd34c77.png)

  
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
  
  <h2> :clipboard: Execution Instruction</h2>
<p>The order of execution of the program files is as follows:</p>


<p><b>1) Model_performance_cardiovascular (1).ipynb</b></p>
<p> This file must be executed, to define all the functions and variables required for classification operations which leads to the evaluation of the model performance on unseen data
  
  ![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
  
  <!-- CREDITS -->
<h2 id="credits"> :scroll: Credits</h2>

< Manoj Korukonda > | Avid Learner | Data Scientist | Machine Learning Engineer | Deep Learning enthusiast

<p> <i> Contact me for Data Science Project Collaborations</i></p>


[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/manoj-korukonda/)
[![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Manoj-Korukonda)


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :books: References</h2>
<ul>
  <li><p>'Machine Learning with a Heart: Predicting Heart Disease'. [Online].</p>
      <p>Available: https://medium.com/@dskswu/machine-learning-with-a-heart-predicting-heart-disease-b2e9f24fee84
  </li>
  
  <li><p>'Random Forest Classification '. [Online].</p>
      <p>Available: https://www.section.io/engineering-education/introduction-to-random-forest-in-machine-learning/ /</p>
  </li>
  <li><p>'Logistic Regression '. [Online].</p>
      <p>Available:https://www.ibm.com/in-en/topics/logistic-regression#:~:text=Logistic%20regression%20estimates%20the%20probability,bounded%20between%200%20and%201. /</p>
  </li>
  <li><p>'KNN '. [Online].</p>
      <p>Available:https://www.javatpoint.com/k-nearest-neighbor-algorithm-for-machine-learning /</p>
  </li>
    </li>
  <li><p>Case Study: Bike-sharing demand prediction'. [Online].</p>
      <p>Available:  </li>
  <li><p>End to end Case Study: Machine learning prediction in cardiovascular diseases'. [Online].</p>
      <p>Available:https://towardsdatascience.com/end-to-end-case-study-bike-sharing-demand-dataset-53201926c8db</p>
  </li>
  
</ul>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
</p>
  </li>
  
</ul>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)



