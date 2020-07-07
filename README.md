<b> *Notes:</b>

Q) For which models we MUST use Feature Scaling?

A) Up until now, we do not have to use it for "Simple/Multiple/Polynomial Regression." We also DO NOT use it for "Decision Tree / Random Forest Regression" because it doesn't make any sense since these models are based on merely splitting the data over and over and are not based on a particular mathematical equation. We also do not have to 'necessarily use it for "Logistic Regression Classification," but employing it will improve the performance of the model (So I used it in my code, 16). The "KNN classification" and "SVM (SVC) Classification" and "Kernel SVM (SVC) Classification" and "Decision Tree / Random Forest Classification" are the same, too.

But, we HAVE TO use it for "SVR Regression."

Yet, Feature Scaling is COMPULSORY for Deep Learning! So, we have to do it in ANN problems. (as I did in "36_ANN_bank churn modeling") And it is so essential that we apply it to all the columns!

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
  
  <b> *36_ANN_bank churn modeling.ipynb:</b>
  
   The dataset is "Churn_Modelling.csv". This ANN code decides which 
