# Intrusion-Detection
Build a predictive model (i.e. a machine learning classifier) capable of distinguishing between “intrusive” traffic, called threats/intrusions or attacks, and “good” normal traffic 

 1. Datataset 
 The first row of each dataset gives variable numbers (this may need to be removed). The original dataset has 154 input variables and 1 target variable however two of the input variables numbered 4 and 7 (frame.time_epoch and frame.time_relative) have been removed from both datasets as they provide temporal information which may cause unfair prediction. The training set has 97044 observations while testing set has 40158 observations.  
 
 2. Constructing and Selecting Features
 - Create additional features using a representation learner (Autoencoder). The latent space representation, simply a representation of compressed data by a representation leaner, may contain important information needed to represent original data point. 
 - Combine the additional features with original dataset. Thecombined dataset should have 154 (original features) + additional features. 
 - Apply feature selection techniques(e.g.filter,wrapperandembedded) and see if any of the additional features created by a representation learner are selected.  
 
 3. Building ML algorithms.  
 
 4. Evaluating model and analysing the results.
