# Credit_Risk_Analysis
## Overview

The purpose of this project is to evaluate our loan prediction risk analysis machine learning algorithms.  We are evaluating different algorithms to determine whether any of these models should be used to predict credit risk.

## Results

The balanced accuracy, precision and recall scores of each 6 machine learning models are included in my table below.  




![image_name](https://github.com/jessicameyer23/Credit_Risk_Analysis/blob/main/Annotation%202022-04-10%20172950.png)



# Summary

Based on the results of the analysis, I would definitely recommend not using any of the oversampling models.  There was some improvement in the results using the BalancedRandomeForestClassifer and the EasyEnsembleClassifier however. 

Based on the results, I would recommend that we consider using the last algorith, the EasyEnsembleClassifer, as the balanced accuracy score was by far the highest at .9254.  The precision high risk was 0.07 and the precision low risk was almost 1.0.  The recall high risk was 0.91 and the recall low risk was 0.94.  

Overall, it really depends on exactly what we would use this information for. Some key data points and analysis are included below:

1.  For example, if we are going to use the information to target our data for people who we think are low risk, we have very good odds that they will actually be low risk, almost at 1.0 .  

2.  We did say that 979 were higher risk, but in actuality, only 79 were, so we could miss out on offering them some loans.  

3.   We had 79 people that we said were high risk but there were 87 that were really high risk, which is 91%, so we missed out on a few people who were high risk, however, its a pretty small number that would potentially default.  

4.  However, we would potentially lose out on some low risk who are really low risk but classified them as high risk, about 10%.

## Conclusion:

Overall, I recommend we refine the EasyEnsembleClassifer a bit more and then use that to predict credit risk.








