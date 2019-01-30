# NLP_Project

## Summary

The goal of this project is to build a profit warning dectection model that performs textual analysis to classify profit warning companies from non profit warning companies. This is to favor the analyts in financial sector who loose resource doing such tedious work. With this model it is expected to get more deep insights.

## Files

data.json: contain the transcript data with time series and text.  
data_new_var.json: The features extracted while modelling are stored along with data.json. This is to import the data and features for further analysis reducing the time for the finding the features.  
LM.csv: contains the Loughran and McDonald Dictionary downloaded from their official website.  
ML_Models: Feature generation, Standalone model testing.  
Ensemble_Models: Ensembling the standalone models to minimize the generalization error and log loss error.  


## CODE

The following modules are required to run the system:

Python 2.7
NumPy
Pandas
Scipy
scikit-learn
nltk
Matplotlib
textstat
pySentiment
LM Dictionary
WordCloud
Xgboost
re
JSON

## References

Xiao Ding, Yue Zhang, Ting Liu, and Junwen Duan. 2014. Using structured events to predict stock price movement: An empirical investigation. In EMNLP. 

Heeyoung Lee, Mihai Surdeanu, Bill Maccartney, and Dan Jurafsky. On the importance of text analysis for stock price prediction.

Robert Remus. 2011. Improving sentence-level subjectivity classification through readability measurement. In Proceedings of the 18th Nordic Conference of Computational Linguistics (NODALIDA 2011), pages 168–174. Northern European Association for
Language Technology (NEALT).

Muhammad et al Waqar. 2017. Prediction of stock market by principal component analysis. 13th International Conference on Computational Intelligence and Security (CIS), arXiv:1503.06733. 599-602.
