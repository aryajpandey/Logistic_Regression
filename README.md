# Logistic_Regression

This project aims at predicting heart_attack using various parameters.

This project uses data from heart attack prediction at kaggle. Download the dataset here : https://www.kaggle.com/imnikhilanand/heart-attack-prediction


# About the data


The authors of the databases have requested that any publications resulting from the use of the data include the names of the principal investigator responsible for the data collection at each institution.  
															
															They would be:    
               1. Hungarian Institute of Cardiology. Budapest: Andras Janosi, M.D.
               2. University Hospital, Zurich, Switzerland: William Steinbrunn, M.D.
               3. University Hospital, Basel, Switzerland: Matthias Pfisterer, M.D.
               4. V.A. Medical Center, Long Beach and Cleveland Clinic Foundation:Robert Detrano, M.D., Ph.D.
 


This database contains 76 attributes, but all published experiments refer to using a subset of 14 of them. In particular, the Cleveland database is the only one that has been used by ML researchers to this date. The "goal" field refers to the presence of heart disease in the patient. It is integer valued from 0 (no presence) to 4. Experiments with the Cleveland database have concentrated on simply attempting to distinguish presence (values 1,2,3,4) from absence (value 0).

Number of Instances: Database: # of instances: Cleveland: 303 Hungarian: 294 Switzerland: 123 Long Beach VA: 200
Number of Attributes: 76 (including the predicted attribute)

# Attribute Information
    
				
				Only 14 used    1. #3 (age) 
                    2. #4 (sex) 
                    3. #9 (cp) 
                    4. #10 (trestbps) 
                    5. #12 (chol) 
                    6. #16 (fbs) 
                    7. #19 (restecg) 
                    8. #32 (thalach) 
                    9. #38 (exang) 
                    10. #40 (oldpeak) 
                    11. #41 (slope) 
                    12. #44 (ca) 
                    13. #51 (thal) 
                    14. #58 (num) (the predicted attribute)

# Class Distribution: 
		
		
		#--Database: 0 1 2 3 4 
		#--Total Cleveland: 164 55 36 35 13 303 
		#--Hungarian: 188 37 26 28 15 294 
		#--Switzerland: 8 48 32 30 5 123 
		#--Long Beach VA: 51 56 41 42 10 200
