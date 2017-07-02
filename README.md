# TidyDataC3assigment
create tidy data.frame after getting and cleaning

In this document the following topics will be explained:

 1 - golbal information concerning the object/target of the data
 2 - the source / authors of the data
 3 - the variables measured 
 4 - the target of the assingment (from Coursera)
 5 - Description of the proces/script:
 
 
    1 Object / Target (original)
		
Human Activity Recognition database built from the recordings of  activities of 
daily living (ADL) while carrying a waist-mounted smartphone with embedded inertial sensors.

 http://www.insideactivitytracking.com/data-science-activity-tracking-and-the-battle-for-the-worlds-top-sports-brand/
 
		2 source

 Jorge L. Reyes-Ortiz(1,2), Davide Anguita(1), Alessandro Ghio(1), Luca Oneto(1) and Xavier Parra(2)
 1 - Smartlab - Non-Linear Complex Systems Laboratory
 DITEN - UniversitÃ  degli Studi di Genova, Genoa (I-16145), Italy. 
 2 - CETpD - Technical Research Centre for Dependency Care and Autonomous Living
 Universitat PolitÃ¨cnica de Catalunya (BarcelonaTech). Vilanova i la GeltrÃº (08800), Spain
 activityrecognition '@' smartlab.ws


		3 Variables and the method of measuring

 The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. 
 Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING)
 wearing a smartphone (Samsung Galaxy S II) on the waist. 
 Using its embedded accelerometer and gyroscope, 
 captured in 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. 

 The experiments have been video-recorded to label the data manually. 
 The obtained dataset has been randomly partitioned into two sets:
 - 70% of the volunteers was selected for generating the training data  
 - 30% for test data.
 
		4 the target of the assingment (from Coursera)

 Create from the data-files, available from the folowwing site:
 http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
 
 I    one data.frame table, of which 
 
 II   information can be obtained about:
      - the average recorded amounts (mean) and the standard deviation (std)-
      - for each activity and / or each persoon, and
 
 III  Cleaning the data from non-relevant data and adjust labels (if required) in descriptive labels
 
 IV   Create a second tidy data.frame with relevant data of all calculated means
