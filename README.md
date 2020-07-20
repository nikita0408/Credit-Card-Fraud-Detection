# Credit-Card-Fraud-Detection

ABSTRACT<br>
Fraud is one of the major ethical issues in the credit card industry.
The main aims are, firstly, to identify the different types of credit card fraud.
Depending on the type of fraud faced by banks or credit card companies, various measures can be adopted and implemented.
The significance of the application of the techniques reviewed here is in the minimization of credit card fraud.
Yet there are still ethical issues when genuine credit card customers are misclassified as fraudulent.
Enormous Data is processed every day and the model build must be fast enough to respond to the scam in time.
Imbalanced Data i.e most of the transactions (99.8%) are not fraudulent which makes it really hard for detecting the fraudulent ones
Our goal in this project is to construct models to predict whether a credit card transaction is fraudulent.
<br>

PROBLEM STATEMENT<br>
To recognize fraudulent credit card transactions so that the customers of credit card companies are not charged for items that they did not purchase.
<br>

DATASET<br>

In this project we analyze a dataset of credit card transactions made over a two-day period in September 2013 by European cardholders. The dataset contains 284,807 transactions, of which 492 (0.17%) are fraudulent.<br>
Each transaction has 30 features, all of which are numerical. The features V1, V2, ..., V28 are the result of a PCA transformation. To protect confidentiality, background information on these features is not available. The Time feature contains the time elapsed since the first transaction, and the Amount feature contains the transaction amount. The response variable, Class, is 1 in the case of fraud, and 0 otherwise.
<br>

SOFTWARE AND LIBRARIES<br>
This project uses the following software and Python libraries:<br>

Python 3.7<br>
NumPy<br>
pandas<br>
seaborn<br>
sklearn<br>
matplotlib<br>
iPython Notebook<br>

MODEL IMPLEMENTED<br>
Logistic Regression<br>

WORKFLOW<br>

Preprocessing phase<br>
Not much preproccesing was needed as the data was already clean but we divided the data set in two classes one fraud and other not fraud.<br>

Visualizations<br>
Made some data visualizations to reveal patterns and structure in the data.<br>

Training and Testing<br>
Splitting the dataset in 70 and 30 ratio.<br>

Model making using Logstic regression classifier<br>

Evaluation
<br>
For a financial institution dealing with identifying fraud, Sensitivity and F1 - Score might be more important metrics. F1- Score reprsents a more balanced result as it is the harmonic mean between Precision and Recall. Sensitivity is more important in the sense that we are more interested in identifying fraud than than identifying legitimate customers. 
<br>

RESULT<br>

Sensitivity/Recall for Logistic Regression Model  : 0.57<br>
F1 Score for Logistic Regression Model  : 0.68<br>
