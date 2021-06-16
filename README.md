# Classification

# Logistic Regression

For classification, the target variable has categories. For example, Cold, Warm and Hot are the categories of the target variable 'Temperature'.These categories are called the class label.

An instance is mapped to one of many available labels 
● Labels are the fixed number of values taken by the target variable
● The machine learns the pattern from train data where the labels are known for all instances. Then the learning can be used on new data where labels need to be predicted

Consider the example where we have inventory data for an online retailer which includes the number of orders, type and demand area for each item. The aim is to classify the items based on if they have a high or low demand. This process can be automated using machine learning algorithms for classification.

Here we use the "German Credit" Dataset for Logistic Regression where we classify creditability given credit amount and duration of credit in months.

# K-Nearest-Neighbors

KNN falls in the supervised learning family of algorithms. Informally, this means that we are given a labelled dataset consiting of training observations (x,y) and would like to capture the relationship between x and y. More formally, our goal is to learn a function h:X→Y so that given an unseen observation x, h(x) can confidently predict the corresponding output y. 

It classifes the data based on similarity measures. A similarity measure for two objects, will return the value 0 if the objects are unlike, and the value 1 if the objects are alike. K specifies the number of nearest neighbours to be considered

KNN is considered to be:
● Instance based learning algorithm: uses training instances to make predictions
● Lazy learning algorithm: does not required a model to be trained
● Non-Parametric algorithm: no assumptions are made about the functional form of the the problem being solved

We will explore the inner workings of KNN, choosing the optimal K values and using KNN from scikit-learn.
The data set we’ll be using is the Iris Flower Dataset which was first introduced in 1936 by the famous statistician Ronald Fisher and consists of 50 observations from each of three species of Iris (Iris setosa, Iris virginica and Iris versicolor). Four features were measured from each sample: the length and the width of the sepals and petals.
We train the KNN algorithm to be able to distinguish the species from one another given the measurements of the 4 features.
Source: https://archive.ics.uci.edu/ml/datasets/Iris

# Ensemble

● Ensemble learning algorithms combine multiple models into one predictive model 
● Decisions from several weak learners are combined to increase the model performance

Parkinson’s Disease (PD) is a degenerative neurological disorder marked by decreased dopamine levels in the brain. It manifests itself through a deterioration of movement, including the presence of tremors and stiffness. There is commonly a marked effect on speech, including dysarthria (difficulty articulating sounds), hypophonia (lowered volume), and monotone (reduced pitch range). Additionally, cognitive impairments and changes in mood can occur, and risk of dementia is increased.

Traditional diagnosis of Parkinson’s Disease involves a clinician taking a neurological history of the patient and observing motor skills in various situations. Since there is no definitive laboratory test to diagnose PD, diagnosis is often difficult, particularly in the early stages when motor effects are not yet severe. Monitoring progression of the disease over time requires repeated clinic visits by the patient. An effective screening process, particularly one that doesn’t require a clinic visit, would be beneficial. Since PD patients exhibit characteristic vocal features, voice recordings are a useful and non-invasive tool for diagnosis. If machine learning algorithms could be applied to a voice recording dataset to accurately diagnosis PD, this would be an effective screening step prior to an appointment with a clinician.
