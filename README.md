# PROJECT-Mobile_Health_Human_Behavior_Prediction
Introduction:
       Mobile health human behavior,is a term that describes the fastly developing field of digital health providing care and treatment for the population via mobile technology such as smart devices.Human behavior is diverse and complex,this nature has posed a great challenge on learning,and most importantly,predicting the human behavior from daily activities.
Data source:
       https://www.kaggle.com/datasets/gaurav2022/mobile-health
Data Description:       
      This dataset consist of 14 columns and a collection of data from 2 sensors placed on different body parts of 10 volunteers.The two sensors used are the accelerometer and gyroscope.
The of the gyroscope is to measure the rate of rotation of an object,while the accelerometer measures the change acceleration of a free falling object or vertically moving object.The sensors are placed on the right and left ankle and wrist.
Activity Set(class labels):
  The activity set is listed in the following:
  
L1: Standing still (1 min)

L2: Sitting and relaxing (1 min)

L3: Lying down (1 min)

L4: Walking (1 min)

L5: Climbing stairs (1 min)
L6: Waist bends forward (20x)
L7: Frontal elevation of arms (20x)
L8: Knees bending (crouching) (20x)
L9: Cycling (1 min)
L10: Jogging (1 min)

L11: Running (1 min)

L12: Jump front & back (20x)

NOTE: In brackets are the number of repetitions (Nx) or the duration of the exercises (min)

Abstract:
     The aim of this project was to accurately classify sensor input data from the MHealth_human_behavior dataset into one of a number of physical activity classes.After performing exploratory data analysis,creating relevant visualizations,and preprocessing the data,i proceeded to train and tune a range of classification models on the data in order to achieve the best results.I utilized the models are Logistic Regression,Random Forest Classifier,K-Nearest Neighbors(KNN),Decision Tree Classifier and Naive Bayes.I compare the performance of these models based on classification report,confusion metrics and have gotten best model via hyperparameter tuning.Most of the model were able to achieve my goal of over 95% accuracy,with the Random Forest acheiving the best performance overall,followed by Decision Tree and KNN.Further model validations and implementing proven strategies on time series data would likely benefit this analysis in the future. 






