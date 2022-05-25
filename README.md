# PyBer_Analysis
## Overview
In this module we used pandas libraries to help organize data.
## Results
There were six models used to analyze this data. These models delivered mixed results. 
- The first model used a Random Over Sampler with Logistic Regression. The accuracy of this model was about 60.2%. 
![](https://github.com/ryanstaudhammer/Credit_Risk_Analysis/blob/main/Resources/ROS.png)
- Next was SMOTE Oversampling. The accuracy of this model was about 62.8%. 
![](https://github.com/ryanstaudhammer/Credit_Risk_Analysis/blob/main/Resources/SMOTE.png)
- Next was Cluster Centroids. The accuracy of this model was about 52.0%. 
![](https://github.com/ryanstaudhammer/Credit_Risk_Analysis/blob/main/Resources/CC.png)
- Next was SMOTEENN. The accuracy of this model was about 63.8%. 
![](https://github.com/ryanstaudhammer/Credit_Risk_Analysis/blob/main/Resources/SMOTEENN.png)
- Next was Balanced Random Forest Classifier. The accuracy of this model was about 76.0%. 
![](https://github.com/ryanstaudhammer/Credit_Risk_Analysis/blob/main/Resources/RFC.png)
- Finally was Easy Ensemble Classifier. The accuracy of this model was about 93.3%. 
![](https://github.com/ryanstaudhammer/Credit_Risk_Analysis/blob/main/Resources/EEC.png)
## Summary
There was one model that seemed to have better accuracy than all the rest. The Easy Ensemble AdaBoost Classifier seemed to have the best accuracy of all the models. The only downside might be that this model is prone to overfitting data. 
