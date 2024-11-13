# PROJECT-Mobile_Health_Human_Behavior_Predection
Introduction:
     Mobile health human behavior,is a term that describes the fastly developing field of digital health providing care and treatment for the population via mobile technology such as smart devices.Human behavior is diverse and complex,this nature has posed a great challenge on learning,and most importantly,predicting the human behavior from daily activities.

Abstract:
    The aim of this project was to accurately classify sensor input data from the MHealth_human_behavior dataset into one of a number of physical activity classes.After performing exploratory data analysis,creating relevant visualizations,and preprocessing the data,i proceeded to train and tune a range of classification models on the data in order to achieve the best results.I utilized the models are Logistic Regression,Random Forest Classifier,K-Nearest Neighbors(KNN),Decision Tree Classifier and Naive Bayes.I compare the performance of these models based on classification report,confusion metrics and have gotten best model via hyperparameter tuning.Most of the model were able to achieve my goal of over 95% accuracy,with the Random Forest acheiving the best performance overall,followed by Decision Tree and KNN.Further model validations and implementing proven strategies on time series data would likely benefit this analysis in the future. 
           
Data source:
        http://archive.ics.uci.edu/ml/datasets/mhealth+dataset
       
Data Description:       
      This dataset consist of 14 columns and a collection of data from 2 sensors placed on different body parts of 10 volunteers.The two sensors used are the accelerometer and gyroscope.
The of the gyroscope is to measure the rate of rotation of an object,while the accelerometer measures the change acceleration of a free falling object or vertically moving object.The sensors are placed on the right and left ankle and wrist.

Note:

The Mbl_Hlth_Hmn_bhvr.pynb file ran in Google Colab GPU environment in order to obtain better performance and training the model.







