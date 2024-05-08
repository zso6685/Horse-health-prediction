# Horse-health-prediction
https://www.kaggle.com/competitions/playground-series-s3e22/data?select=train.csv
# Project Title
This respiratory holds an attempt to predict horse health outcome given different variables.

# Overview
I went over the training train and test csv files, sample_submission file had no need to be used. I first downloaded and uploaded the files, looked at the data types, looked for missing values and duplicates, dropped the duplicates and removed the missing values.
My model predicts that the age of the horse does predict its health outcome, in that more adult horses made it to hospitals tan the young ones.
I as well had a chance to look at the pulse, temperature extreemities and the rate of respiration of the horses to predict their health.
My challenge was having to go back and forth between the two files, "test and train"



![image](https://github.com/zso6685/Horse-health-prediction/assets/123700251/6c39a404-16ef-4019-a82f-00d50327e1a9)


# Summary of work done
I was able to look into the data , mostly focussed on the train_csv file, I was able to do a clean up, where I dropped duplicates and removed missing values.
I had a chance to do a pair plot on certain columns since I kept running into a pair plot with the titles jumbled up if i used the whole data set and it did not look neat. Thus my choice of using only certain columns.


![image](https://github.com/zso6685/Horse-health-prediction/assets/123700251/1197ce30-230c-4e40-b5b8-2af53e7b98ff)



# Data Visualization
Through ploting data I could see the trend of the older horses having the need of surgery thus the older the horse, the poor the health outcome.


![image](https://github.com/zso6685/Horse-health-prediction/assets/123700251/06f7d5b7-b769-43f8-bc9b-ef9f3111ccc2)




The correlation heatmap was used to show the respiratory_rate, the temperature extremities and the pulse as well.



![image](https://github.com/zso6685/Horse-health-prediction/assets/123700251/6c2d5ada-5757-43ad-8c73-d7b8e528608f)



# Problem function
Working through to see the outcome of horse health
# Training

![image](https://github.com/zso6685/Horse-health-prediction/assets/123700251/fe6ef6ab-c938-4552-a914-52043fa33e3d)

Classification report from splitiing the data 80% training and 20% test.


# performance comparison

![image](https://github.com/zso6685/Horse-health-prediction/assets/123700251/c5956d80-8be2-47a6-a07d-09dd837c3b57)

I encountered a problem with not outputting the ROC curve correctly, I would assume is because of the data I chose to work with.

# Conclusion
I could tell from the distribution that of the data that the older the horse and the mucousal membrane the more likely to live or die
# Future work
Work with more datasets practice deep learning and be able to test and train data sets and use different models as well. 
