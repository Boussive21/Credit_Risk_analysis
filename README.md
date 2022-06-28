# Credit_Risk_analysis
#Overview of project
In this project we are doing supervised machine learning with the to run through Loans Status and to classify them as low risk or high risk. We first are employ oversampling, under sampling, and then a logistical regression. These are done under two files one called resample and ensemple.  After that we compared the accuracy, precision, and recall of the model. 
#Results
Naive Oversample
With the Naive oversample size we got a balance score of 65 percent. 
The high risk precision of 1 percent is in line 62 percent sensitivity. While low risk is almost 100 percent with 68 percent sensitivity.  
![Oversample 2](https://user-images.githubusercontent.com/99147715/176085651-a8e9da82-cf0b-4090-8f18-cd0a675cdc1e.PNG)

The Smote Oversample model 
The balance score for the Smote 62 percent 
With High risk precision being 1 percent 59 percent. Low Risk precision nearly 100 percent with sensitivity of 66 percent.
![Overbalance](https://user-images.githubusercontent.com/99147715/176085849-0dde77bb-0d16-441d-a103-b4843004a679.PNG)

Clusteredroid Under sampling
In our Clusteredriod model we received a 62 percent balance score.
Our high-risk precision was 1 percent and our sensitivity was .61 percent. Low risk though was nearly 100 percent and the sensitivity was 45 percent. 

![Undersample](https://user-images.githubusercontent.com/99147715/176085915-f390b47a-2893-44cb-8f4e-eaa28e7bee76.PNG)

Smoteenn Combined Sampling 
In the Smoteenn model we got a balance score of .52 
With our high risk precision being 1 percent with a sensitivity of 70 percent. Our low risk being close to 100 percent and the sensitivity of  58 percent. 
![CombinedSample](https://user-images.githubusercontent.com/99147715/176085953-51c7711d-751d-4258-a226-bcfb3e09bc4c.PNG)

Balance Random Forest
In Balanced Random Forest Classifier we got a balance score .78.  
With our high risk precision being 3 percent and sensitivity 70 percent. With our low risk precision being close to 100 percent and sensitivity 87 percent. 

Easy Ensemble Classifier
In the Easy Ensemble Classifier we got a balance score of .93 
With our high risk precision being 9 percent with a sensitivity of 92 percent. Low Risk precision being nearly 100 percent and sensitivity 94 percent. 

#Summary 
From the test we ran used to perform to the credit risk analysis shows a weak precision on high risk credit. The easy ensembler showed more precision on of 7 percent. With low risk a lot of the them would be labeled as false positive. Which could cause the bank to lose a large amount of revenue due to the falsely detecting as them as high risk. Which is why I would not recommend the bank to implement it right now.   
