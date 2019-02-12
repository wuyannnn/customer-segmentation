# customer-segmentation
 applied unsupervised learning techniques to identify segments of the population that form the core customer base for a mail-order sales company in Germany.
 
 ## Project Background
This project is a part of Udacity <strong>Data Scientist Nanodegree</strong>.In this project,unsupervised learning techniques to identify segments of the population that form the core customer base for _a mail-order sales company in Germany_ is needed. These segments can then be used to _direct marketing campaigns towards audiences_ that will have the highest expected rate of returns. The data has been provided by Udacity's partners at _Bertelsmann Arvato Analytics_, and represents a <strong>real-life data science task</strong>.

The dataset presented in this project is untidy and requires a number of assessment and cleaning steps before it can be used for machine learning methods. The ability to perform data wrangling and the ability to make decisions are both valuable skills.
 
 ## Data Descriptions
 * `Udacity_AZDIAS_Subset.csv`: Demographics data for the general population of Germany; 891211 persons (rows) x 85 features (columns).
 * `Udacity_CUSTOMERS_Subset.csv`: Demographics data for customers of a mail-order company; 191652 persons (rows) x 85 features (columns).
 * `Data_Dictionary.md`: Detailed information file about the features in the provided datasets.
 * `AZDIAS_Feature_Summary.csv`: Summary of feature attributes for demographics data; 85 features (rows) x 4 columns
 
 ## Tools Used
 This project requires <strong>Python 3</strong> and the following Python libraries installed:
 * [Numpy](http://www.numpy.org/)
 * [Pandas](http://pandas.pydata.org/)
 * [Matplotlib](https://matplotlib.org/)
 * [Scikit-learn](https://scikit-learn.org/stable/)
 * [Seaborn](https://seaborn.pydata.org/)
 
 ## Analysis Steps
 1. <strong>_Data Processing_</strong>: 
 
 Before starting an analysis, it's necessory to do data exploration and data understanding. Such as:
* How many records and features? What's the percentage of missing data? 
* What do those features mean? Are there certain features should be droped from the analysis because of missing data? 
* Are there features that need to be re-encoded (_One-Hot Encoding_) before they can be used? 
* Need feature engineering to create some useful columns?
* Is feature scaling needed? Normalization or Standardization?

2. <strong>_Feature Transformation_</strong>: 

Once the data is cleaned and ready, dimensionality reduction techniques is to use to identify relationships between variables in the dataset. Principal component analysis (PCA) is commonly used to find the vectors of maximal variability.The following points in this stage will be tackled:
* How much variability in the data does each principal component capture? 
* Can you interpret associations between original features in your dataset based on the weights given on the strongest components? 
* How many components will you keep as part of the dimensionality reduction process? 

3. <strong>_Clustering_</strong>: 

Apply clustering techniques to identify groups in the general demographic data, then apply the same clustering model to the customers dataset to see how market segments differ between the general population and the mail-order sales company._How should you make a decision on how many clusters(k) to use?_

Apply the techniques and models that you fit on the demographic data to the customers data: data cleaning, feature scaling, PCA, and k-means clustering. Compare the distribution of people by cluster for the customer data to that of the general population._Can you say anything about which types of people are likely consumers for the mail-order sales company?_
 
 ## Remark
 We are not allowed to publish the data provided by Arvato Financial Services due to the terms and conditions. In the notebook you can find the code and the analysis that I perfomed on the datasets.
 
