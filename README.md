# Big Bytes Challenge 2019
Submission for Cognizant's hackathon. Details of the challenge can be found at: http://bigbytes.sg/the-mission/  <br/>
Dataset can be found at: https://www.dropbox.com/s/fiugsupsw12tnda/Credit%20Card%20Dataset%20for%20Students.zip?dl=0

## Objective
The proposed solution to improving fraud recovery through the early identification and proactive management of suspicious transactions by a Neural Network trained on the provided dataset. 

## Methodology

### Data preparation
* Random Oversampling on minority class 0 for training data set
* 80% Training and 20% Testing split
* Standardizing of features
   
### NN Architecture
* Hidden layer 1: 2048 nodes 
* Hidden layer 2: 1024 nodes 
* Hidden layer 3: 512 nodes 

## Performance

### Trained Model Performance

<img src='https://lh3.googleusercontent.com/e21Pybyxm8H5iLMfjN_p5S-VpsdRG0MZaIQIGQWWDGcYadfTfbP2w4kyLL9XZWeIgEyXNKQfW2p2DdHGiGqMtFr-HdKa24w-GXC5H9uOmRMR3qjb0EYWjqLquCfeRvTrTwO7RHHjHLattVh5KidR1vz3x00Adi9Y0EF3i6T93EC-VpAZhNOhlTcsFT5_Ypza9ESfni388usWHeWl6AHcJqsJativ0fuYn-0sFKuk2DX5kVyPW_lGaFUcCvQPDrGtP35GwM9q9J_B1foyPvOQN2uhM00KVydhx-PjfPl-SniWd9XOmMiLmuixK1LDziz1KCmL6LF2R4zE8eGQzKspTBfMvSjf5qkPvBFne4fQ9cVjg6LO7UYaD3_VodH8R0zX2ncY1byj2Oas3mRRDqiq6k64eq_5-lxEw9EMdw1WGSBITyysCw-x17C2b1caQ6F93pZeCostiiXKa-i_ie0P8Fi_QChqIYM9X15RvQCxaOA8Ss4urHtS6CXZkBzFtMK3dOr44umGOjCHtaM3OUX9kLXkLYkuHKyK6R6YyTQVP1Wo-epFVxj9-ArSOZ8qTOXKkowebVF61YDmTidHYUzSDoK1VcGjtmLxBOVd8FIR6yGH7zPIuXQmhF1q2M1y9slMBjvBxVu8Gzci-VPGd3-06NJrBRejr5A=w395-h278-no'>

Loss Curve for training and validation set

<img src='https://lh3.googleusercontent.com/lmDL4W9ztGXTatXNJT31Kr-cOUUAdMxjXdXrskGqWzTPWIgApcI4OtX62oJ0vTMZFhxpkowgkH0lWO3_VaiIZldNWtHd_xKyqhBLBeyfjZS4HdhU9ivbtKnzICnM9Jtk4jXatKhtF2ChSzxAIV_x9ASDOAtBvEh4l-UpleZDlVew32OkKNNBQN5jmu-RkBGBTDBVbR1P0bOmbY6oS8eQAbtIHjEouArClbu79kpbE1GM0LtnQrmxxGXzMCLA5LSZwhSOecTPcbi1g-7MzAjYeyqv4qkQ7dKNsYzEWWms2VP46M4K9ERT2mlJlRRyLrj-wb5iYAMQIdAGpZPv2gOSuT9gwKwFFFSlO-zZdSXTfFMk1Me1pzO6DRXKcYXhuovVk2AQ6pljgU1riIOUWrffis0_CbwvzIsvTmnMbw15QNzZxFg0x5gXyXTWPYWFkPSvk0TYLDZosT7iev7yBZ-rGaVJm66Sl8w2QxQ8Pqz1wMSemNk65QPhKCpw2Gcz52et29i7vHVkAVuRPopViBnNTPBCy7EGsbNd_BKz-vrJ1VoCZrdaAOiO9Qt8NKQ3362-jxDFSKiJtg9_iEhEH8v71bBbul2NFU9KJzvRvoc9oVjogb3CAdW7yhGvRRDHbhU24lcSYmWXvYm4XxOmCVM2XBtuf6snlvs=w394-h278-no'>
 
 Area under ROC
 

* Precision for Model : 0.79
* Sensitivity/Recall for Model : 0.89
* F1 Score for Model : 0.83
* F-Beta Score for Model : 0.87
 
### Cross validation Performance
6-fold cross validation summary metrics (Average)

* Precision for Model : 0.75
* Sensitivity/Recall for Model : 0.89
* F1 Score for Model : 0.8
* F-Beta Score for Model : 0.85
* AUC for Model : 0.94
 
