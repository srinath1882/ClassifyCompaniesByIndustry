# ClassifyCompaniesByIndustry

Subject: Industry Classification of publicly listed companies based on business description


### Files Attached <b>
• Training Data
This file has publicly listed companies which are categorized by certain tags mentioned in the column C <b>
  
• Testing Data
This file has the list of publicly listed companies. It has the company name and business description.


### Analysis
The companies mentioned in the Test Data file are classified as per the Industry tags mentioned in the Training Data file. 
We are looking for a Deep Learning based classification model preferably application of some
transformer-based algorithm.
A TFBertForSequenceClassification model from Huggingface is used for the task.  

A training set, and a validation set is created, also F1 score is calculated for the Training Data file.
