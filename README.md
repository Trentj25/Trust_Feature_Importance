# Trust_Feature_Importance
Feature Importance Trust and Adherence to Public Health Measures

Based on the multi-jurisdictional trust and adherence data collect across 11 countries during the COVID-19 pandemic, this code to determine which X features are best able to predict: 

1.	Instances where the respondent reported to have either always or mostly adhered to pandemic related public health measures (PHMs)?
2.	Instances where the respondent anticipates adhering to PHMs in the event of a future public health crisis?  
3.	A decline in adherence to PHMs?  Respondent indicated they either always or mostly followed PHMs in the past but would likely either not or only rarely follow PHMs in the future .
4.	Increased adherence to PHMs? Respondent indicated they never or rarely adhered to PHMs but anticipate following most or all future public health crisis related PHMs.
5.	Trusting in community, healthcare providers (HCP) and political communications? 
6.	Not trusting communications from traditional media, government, HCPs or health related NGOs (such as WHO) in the event of a future public health crisis? 
7.	Relatively low trust in one of either community, HCPs or political communications?  Instances where the respondents indicated they either mostly or implicitly trust two of the areas surveyed but either mistrust or distrust the other.  

X Features: include device and location meta-data (primarily sub-national region); collection phase (Waves I and II),  self-reported data on age, level of trust in community, health care providers (HCP), political communications, past and future adherence to public health measures, language selection, COVID-19 information source (past and future) and education level.

Uses Catboost's classifier and get_feature_importance function

Seperate models are built for each country within the survey (11 countries total).  Accuracy scores also included. 

y variables converted to binary, previous scale value versions had limited fit and uneven distribution of errors. 



