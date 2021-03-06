<b> *Notes:</b>

Q) For which models we MUST use Feature Scaling?

A) Up until now, we do not have to use it for "Simple/Multiple/Polynomial Regression." We also DO NOT use it for "Decision Tree / Random Forest Regression" because it doesn't make any sense since these models are based on merely splitting the data over and over and are not based on a particular mathematical equation. We also do not have to 'necessarily use it for "Logistic Regression Classification," but employing it will improve the performance of the model (So I used it in my code, 16). The "KNN classification" and "SVM (SVC) Classification" and "Kernel SVM (SVC) Classification" and "Decision Tree / Random Forest Classification" are the same, too.

But, we HAVE TO use it for "SVR Regression."

Yet, Feature Scaling is COMPULSORY for Deep Learning! So, we have to do it in ANN problems. (as I did in "36_ANN_bank churn modeling") And it is so essential that we apply it to all the columns! We also do feature scaling for "Self Organizing Maps".


<b> *Notes:</b>

The general machine learning methodology:
<ol>
  <li>Importing the libraries</li>
  <li>Importing the dataset {df + x&y}</li>
  <li>Data Engineeing {missing values + one-hot-encoding&|labelencoding}</li>
  <li>Data Splitting</li>
  <li>Feature Scaling</li>
  <li>Model</li>
  <li>Evaluating the model</li>
</ol>

# Machine_Learning
In this section, I will put and update my machine learning related codes:


<b>* dog_cat_images_CNN_classification_project.ipynb:</b>

you can either email me to send you my own dataset of cats and dogs images, or you can use anyyyy other dataset of your own with binary classification, such as a dangrous/benighn tumor. The code will work fine regardless of what kind of imag data you feed it, but you probably need to add slight changes in my code where I have mentioned the "size" of my own dataset, and substitute your dataset's size.


<b> *03_Data Preprocessing_costumers.ipynb:</b>

The dataset is "Data.csv", but the goal in here was the "Data Preprecessing" process, not the dataset.

<b> *06_Regression_Simple Linear Regression.ipynb:</b>

The dataset is "Salary_Data.csv".

<b> *07_Regression_Multiple Linear Regression.ipynb:</b>

The dataset is "50_Startups.csv".

<b> *08_Regression_Polynomial Regression.ipynb:</b>

The dataset is "Position_Salaries.csv".

<b> *09_Regression_SVR.ipynb:</b>

The dataset is "Position_Salaries.csv".

<b> *10_Regression_Decision Tree Regression.ipynb:</b>
  
  The dataset is "Position_Salaries.csv".
  
  <b> *11_Regression_Random Forest Regression.ipynb:</b>
  
  The dataset is "Position_Salaries.csv".
  
  <b> *All the codes in part 13:</b>
  
  The dataset is "Data.csv".
  
  <b> *16_Classification_Logistic Regression_Social Nework Ads.ipynb:</b>
  
  The dataset is "Social_Network_Ads.csv". The features are "Age" and "Salary" and based on these two indepandant variables, we ant to see if a user purchsed the product or not, according to label "Purchased".
  
  <b> *16_Logistic Regression Classification_Breast Cancer.ipynb:</b>
  
  The dataset is from <a href="https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Original%29">UCI breast cancer dataset</a>, that I have uploaded here as breast_cancer.csv.
  
  <b> *17_Classification_KNN.ipynb:</b>
  
  The dataset is "Social_Network_Ads.csv"
  
  
  <b> *18_Classification_SVM (SVC) Classification.ipynb:</b>
  
  The dataset is "Social_Network_Ads.csv"
  
  <b> *19_Classification_Kernel SVM.ipynb:</b>
  
  The dataset is "Social_Network_Ads.csv"
  
  <b> *20_Classification_Naive Bayes.ipynb:</b>
  
  The dataset is "Social_Network_Ads.csv", and this code predicts if costumers will buy a prodcut.
  
  <b> *21_Classification_Decision Tree Classification.ipynb:</b>
  
  The dataset is "Social_Network_Ads.csv", and this code predicts if costumers will buy a prodcut.
  
  <b> *22_Classification_Random Forest Classification.ipynb:</b>
  
  The dataset is "Social_Network_Ads.csv"
  
  <b> *23_Classification_Model Selection_....ipynb:</b>
  
  The highest accuracy occored with "Decision Tree Classifucation" algorithm for the breast cancer dataset "Data.csv"! But for a sales dataset "Social_Network_Ads.csv", the best algorithm became "Kernel SVM (SVC) Classification". Therefore the winner of the which-algorithm-is-the-best-so-far-in-accuracy for this breast cancer dataset "Data.csv" is "Decision Tree Classification"! Hats off! Buuuut ofcourse it is NOT always the same case! the best chosen algorithm differes for different datasets and applications.


<b> *26_Clustering_Kmeans.ipynb:</b>

The dataset is "Mall_Customers.csv", which clusters the customers of a mall, based on their annual income and their spending score, as careful, careless or best target for the mall! 5 clusters were generated and the according policy for each customer is written at the end of the code, in a sepearte cell, within 5 command lines.

<b> *29_Association Rule_Apriori.ipynb:</b>

The dataset is "Market_Basket_Optimisation.csv". And since we do NOT have a special method in Python Sklearn for "Apriori" algorithm, we should first install "apyori.py" package in our notebook. This is a really exciting implementation!! It wants to tell us that for a French supermarket what kind of policy should we employ in order to sell the most! And the policy is as follows:

**What products should we sell and what according products should we give for free, as a result!! For instance, the strongest association products are "formage blanc" and "honey". Therefore, we sell "formage blanc" and if someone buys it, we will give them "honey" for free in order to maximize our sells!!
  
  <b> *30_Association Rule_Eclat.ipynb:</b>
  
  The dataset is "Market_Basket_Optimisation.csv". It is trained just like "Apriori" algorithm, because both are exactly the same, and the difference is that in "Eclat" we ONLY use the "support" metric (but in "Apriori" we use "support", "confidence", and "lift" metrics). That is why it is recommended usually to use "Apriori" algorithm, rather than "Eclat".
  
  <b> *32_Reinforcement Learning_UCB (upper confidence bound).ipynb:</b>
  
  The dataset is "Ads_CTR_Optimisation.csv".
  
  <b> *34_NLP.ipynb:</b>
  
   The dataset is "Restaurant_Reviews.tsv". In this code in Natural Language Processing, I did a text classification on restaurant reviews, and the accuracy became 73% 😎!
   This section can be regarded as "sentimental Analysis" as well. The more complex applications of NLP (Natural Language Processing) are DNLP (Deep Natural Language Processing) and "seq2seq" in chat bots. We can also increase the accuracy even more by using Some of these great models to train our data for "NLP" applications:
   <ol>
      <li>CART</li>
      <li>C5.0</li>
      <li>Maximum Entropy</li>
  </ol>
  
  <b> *36_ANN_Classification_bank churn modeling.ipynb:</b> 
  
  The dataset is "Churn_Modelling.csv". This ANN code decides based on the costumers information, which costumers will stay and which of them withdraw from the bank, which is called a "Churn Model"! Very useful code for banking applications!! In addition, I have uploaded a picture that shows the summary of an ANN with Stocastic Gradient Descent algorithm as "Stochastic_Gradient_Descent.png" for the reference.
  
  
<b> *36_ANN_Regression power plant energy dataset.ipynb:</b>

The dataset is "Folds5x2_pp.xlsx" from <a href="https://archive.ics.uci.edu/ml/datasets/Combined+Cycle+Power+Plant" target="_blank">UCI's Combined Cycle Power Plant dataset</a>. The goal was to perform a Regression task in ANN and see the differences from a Classification task in ANN. The main difference (Codewise ofcourse!!) was the output layer's "activation" function that we do NOT assign a function to, and also the the compiling "loss" that we choose "mean_squared_error" (as we usually do in all other Regression tasks). Then I predicted the output energy of this power plant for different test set's environmental features "Air Temperature, Vacuum, Air Pressure, and Humidity".
  
<b> *37_CNN_cat dog detection.ipynb:</b>

The dataset is "dataset.rar" which contains dog and cat images for both the training set and the test set. The final accuracy was 90% through 25 epochs! The data set file is too huge that it would take one to two hours to clone. So, feel free to contact me if you need the dataset. (<a href="https://www.earthdatascience.org/workshops/intro-version-control-git/basic-git-commands/#:~:text=From%20your%20repository%20page%20on,like%20to%20clone%20your%20repository." target="_blank">How to Clone files on GitHub</a>)

<b> *39_PCA_recommender system.ipynb:</b>

The dataset is "Wine.csv". This code employs "PCA" technique to reduce the dimensiality of a wine dataset of many columns, so that to make a recommender system.

<b> *40_LDA.ipynb:</b>

The dataset is "Wine.csv". This code does "Linear Discriminant Analysis", and acts as a perfect dimensiality reducer and also a recommender system.

<b> *41_Kernel PCA_version 1.ipynb:</b>

The dataset is "Wine.csv".This code does "Kernel Principal Component Analysis"and acts as a perfect dimensiality reducer and also a recommender system.

<b> *41_Kernel PCA_version 2.ipynb:</b>

The dataset is "Social_Network_Ads.csv".This code does "Kernel Principal Component Analysis"and acts as a dimensiality reducer and also a recommender system.

<b> *43_Model Selection_ kfold cross validation.ipynb:</b>

The dataset is "Social_Network_Ads.csv". And the objective in this section is to use "K-fold cross validation" technique to turn the "X_train" into "k" different folds. Then we calculate all these "k" according accuracies and get their mean. The answere is a better estimator of the real accuracy of our model! Since when we calculate the accuracy by the typical "accuracy_score" method on the "X_test", the code might have chosen "X_test" perfectly, in the begining. Meaning that we got lucky and thus we think this perfect accuracy is always true :( . But if we re-reun the program, the program will choose another random set for "X_test" from "X_train", and this new test set may yield a worse accuracy! Therefore, we use "K-fold" method to check if we got lucky on the accuracy for the "X_test"! 

<b> *43_Model Selection_Grid Search.ipynb:</b>

The dataset is "Social_Network_Ads.csv". This code implements a "grid search" right after a "k-fold" section, using different parameters and kernels, and then finds the best accuracy and the best parameter!

<b> *44_Boosting_XGBoost_bank churn modeling.ipynb</b>

The dataset is "Churn_Modelling.csv". I implemented this code to measure the churning rate of a bank's costumers like in "36_ANN_Classification_bank churn modeling.ipynb". But this time, I did it using "XGBoost" model.


<b> *44_Boosting_XGBoost_breast cancer detection.ipynb:</b>

The dataset is "Data.csv". I did the breast cancer detection project that I did before in "23_Classification_Model Selection_Decision Tree Classification.ipynb", now with xgboost library "XGBClassifier" class, and it beat the best accuracy I reached before for breast cancer project (the best algorithm before was "Decision Tree Classifier" and the accuracy was 95.9%). But with "XGBClassifier" the accuracy became 97.8%! So to check whether we got lucky by choosing a very good "X_test" set, I implemented a "K-fold" algorithm and the accuracy became 96.5%, which still beats the former best "Decision Tree Classifier"!!

Thus, the best algorithms among all the classification algorithms that I have implemented so far for the breast cancer deection are:
<ol>
  <li><strong> XGBoost Classifier ("XGBClassifier") 🌟</strong></li> 
  <li> Decision Tree Classifier</li> 
  <li> Kernel SVM (SVC)</li> 
</ol>

<b> *44_Boosting_CATBoost:</b>

The dataset is "Data.csv". The "CATBoost" technique is a gradient-based model that is bound to beat out the power that LightGBM (a gradient-based model that uses tree-based learning algorithms) has to offer on specific problems. CatBoost is a great self-tuning model to have in the toolkit whenever you want to get the highest accuracy on datasets that have many categorical features, which is usually the case with on-the-job problems. In this code, I implemented CatBoost on the breast cancer dataset (the same dataset we used for XGBoost = UCI's data "Data.csv"). The benefits of "CATBoost" model are as follow:

<ol>
  <li> Great quality without parameter tuning: Reduce time spent on parameter tuning, because CatBoost provides great results with default parameters</li>
  <li> Categorical features support: Improve your training results with CatBoost that allows you to use non-numeric factors, instead of having to pre-process your data or spend time and effort turning it to numbers.</li>
  <li> Fast and scalable GPU version: Train your model on a fast implementation of gradient-boosting algorithm for GPU. Use a multi-card configuration for large datasets.</li>
  <li> Improved accuracy: Reduce overfitting when constructing your models with a novel gradient-boosting scheme.</li>
  <li> Fast prediction: Apply your trained model quickly and efficiently even to latency-critical tasks using CatBoost's model applier</li>
</ol>  


So The result: 
CatBoost has beat "XGBoost"!!!
After implementing a "K-fold" algorithm on "XGBoost", the accuracy became "96%" but in "CATBoost" the accuracy after a "k-fold" became "97.08"!!
Thus, the best algorithms among all the classification algorithms that I have implemented so far for the breast cancer deection are:
<ol>
  <li><strong> CATBoost Classifier ("CatBoostClassifier") 🌟🌟</strong></li>
  <li> XGBoost Classifier ("XGBClassifier")</li> 
  <li> Decision Tree Classifier</li> 
  <li> Kernel SVM (SVC)</li> 
</ol>

