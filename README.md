# Age-Detection-of-Indian-Actors

Age Detection of Indian actors datasets consists of about 19000 images which we have to classify into three classes
MIDDLE, YOUNG and OLD. 
The dataset is highly imbalanced so I have used label smoothing regularization and stratified K-Fold techniques for handling this imbalance.

I have trained different models like Efficientnet_B2,B3 , Resnext50 and Densenet121 and then finally combine all of them using ensembling averaging technique.

I achieved an accuracy of 92.7% and rank of 31 out of 8082 registered particpants and the rank will keep on improve as I optimise my models further.

Link to challenge : https://datahack.analyticsvidhya.com/contest/practice-problem-age-detection/#About
