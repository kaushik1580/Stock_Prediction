# Stock_Prediction

The productive market theory (EMH) declares that money related markets are "enlightening proficient", or that costs on exchanged resources (e.g., stocks, securities, or property) as of now mirror all known data, and in a split second change to reflect new data. In this manner, as indicated by hypothesis, it is difficult to reliably beat the market by utilizing any data that the market definitely knows. Data or news in the EMH is characterized as whatever may influence costs that is mysterious in the present and hence shows up arbitrarily later on. Securities exchange forecast carries with it the test of demonstrating whether the money related market is unsurprising or not since there has been no agreement on the legitimacy of Efficient Market Hypothesis (EMH).
The EMH (Effective market hypothesis) states that the stock prices for tomorrow cannot be predicted. Trying to go against the EMH aiming to predict stock prices using SVR (support vector regression).

##### SVM classifier:
- SVM classifier is a type of discriminative classifier. The SVM uses supervised learning i.e. a labeled training data. The output is hyperplanes which categorizes the new dataset. They are supervised learning models that use associated learning algorithms for classification and as well as regression. Parameters The tuning parameters of SVM classifier are kernel parameter, gamma parameter and regularization parameter.         

- Kernels can be categorized as linear and rbf kernels calculates the prediction line. In linear kernels prediction for a new input is calculated by the dot product between the input and the support vector.
C parameter is known as the regularization parameter; it determines whether the accuracy of model is increases or decreases. The default value of c=10.Lower regularization value leads to misclassification.  

- Gamma parameter measures the influence of a single training on the model. Low values signifies far from the plausible margin and high values signifies closeness from the plausible margin

#### PROBLEM STATEMENT:

The recent stock prediction algorithm doesn’t give the proper accurate result and the time complexity is high. The problem which I am attempting to solve is an NP-hard problem because the stock market prediction cannot be made in a deterministic manner and also cannot be done in polynomial time. The existing prediction systems also not consider the outlier situations (the situation of out of bound or extreme changes, like the Great Depression of US (1931)). I used SVR (Support Vector Regression) to solve the current problem. 

Using Grid Serach I find the best parameter and used linear kernel with C=100.
      - Mean Absolute Error: 1.0789042003701774
      - Mean Square Error: 8.08707384303651
                   
I compared through changing the kernel, using rbf(Radial Based Function) kernel having 
      - Mean Absolute Error: 1.1792203284126659
      - Mean Square Error: 17.41510645580223
### Conclusion:

Linear Kernel is better than rbf kernel from the above result.





