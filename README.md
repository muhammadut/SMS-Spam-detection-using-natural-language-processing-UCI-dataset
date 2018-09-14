# SMS-Spam-detection-using-natural-language-processing-UCI-dataset
https://archive.ics.uci.edu/ml/datasets/sms+spam+collection


## About the dataset: 
Collection of 425 SMS spam messages was manually extracted from the Grumbletext Web site. This is a UK forum in which cell phone users make public claims about SMS spam messages, most of them without reporting the very spam message received. The identification of the text of spam messages in the claims is a very hard and time-consuming task, and it involved carefully scanning hundreds of web pages.

A subset of 3,375 SMS randomly chosen ham messages of the NUS SMS Corpus (NSC), which is a dataset of about 10,000 legitimate messages collected for research at the Department of Computer Science at the National University of Singapore. The messages largely originate from Singaporeans and mostly from students attending the University. These messages were collected from volunteers who were made aware that their contributions were going to be made publicly available. 

A list of 450 SMS ham messages collected from Caroline Tag's PhD Thesis

Finally, we have incorporated the SMS Spam Corpus v.0.1 Big. It has 1,002 SMS ham messages and 322 spam messages and it is public

### About the notebook: 

Introduction:
SMS Spam Collection Data Set
https://archive.ics.uci.edu/ml/datasets/sms+spam+collection
The motivation behind this notebook:
1. Is to explore natural language processing on "text/SMS" type dataset. This data has a lot of spelling errors, uses slang & shorthand form. 

2. Apply simple feature engineering and feature validation to improve model performance

3. Create a bigger corpus for stopwords using external resources for better data pre-processing 

4. Use Xtreme Gradient Boosting algorithm for class imbalanced classification problem.

5. Hypertune the XGboost model to optimize for f1 score. (higher precision & higher recall) Although I skipped this step but computational time. I have still written the code as to how one would go about doing it.
