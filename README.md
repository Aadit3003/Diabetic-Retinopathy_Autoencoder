# Autoencoder-based Feature Selection for Diabetic Retinopathy Risk Factors
This project was done under the guidance of Dr. Sundaresan Raman, BITS Pilani, as part of the course CS F376 (Design Oriented Project) in the Second Semester of AY 21-22.

## Brief Description
We explored three methods to identify certain Risk factors for Diabetic Retinopathy (DR) of Primary or Secondary Importance. Of these 3 approaches, we found most success with the Autoencoder using the SN-DREAMS dataset for DR.

## Dataset
The SN-DREAMS dataset ([Dataset Link](https://github.com/Aadit3003/Diabetic-Retinopathy_Autoencoder/blob/2006d6796ba2008d573f280a57f0b5a523eb46f5/Modified.csv)) contains 13 risk factors (columns) and the 14th column as an indicator of DR. Of these 13, 4 factors are categorical, while 9 are continuous. This data is available for 1555 patients (rows). However, the data is imablanced, since rows with DR = 1 are sparse. To combat this SMOTE-ENN and standardization are used.

Furthermore, we use Expert-Labeled Primary/Secondary clusters ([File Link](https://github.com/Aadit3003/Diabetic-Retinopathy_Autoencoder/blob/2006d6796ba2008d573f280a57f0b5a523eb46f5/Actual.xlsx)) as the 'Gold-Truth' to evaluate the results from each approach.

## Attempt 1: Classification
Diagram, Result
<p float="left">
  <img src="https://github.com/Aadit3003/Diabetic-Retinopathy_Autoencoder/blob/2006d6796ba2008d573f280a57f0b5a523eb46f5/Assets/Clustering.png" width="480" />
  <img src="https://github.com/Aadit3003/Diabetic-Retinopathy_Autoencoder/blob/b58fc6765adc889079e409f70c35c8855847e601/Assets/1_Results.png" width="480" /> 
</p>
<em><b>K-Means Clustering and the resulting Confusion Matrix</b></em>

## Attempt 2: Classification
<p float="left">
  <img src="https://github.com/Aadit3003/Diabetic-Retinopathy_Autoencoder/blob/2006d6796ba2008d573f280a57f0b5a523eb46f5/Assets/KNN%20Classification%20ROC.png" width="400" />
  <img src="https://github.com/Aadit3003/Diabetic-Retinopathy_Autoencoder/blob/b58fc6765adc889079e409f70c35c8855847e601/Assets/2_Results.png" width="480" /> 
</p>
<em><b>KNN Classification and the resulting Confusion Matrix</b></em>

## Attempt 3: Autoencoder

<p float="left">
  <img src="https://github.com/Aadit3003/Diabetic-Retinopathy_Autoencoder/blob/b58fc6765adc889079e409f70c35c8855847e601/Assets/3_Autoencoder%20Parameters.png" width="480" /> 
  <img src="https://github.com/Aadit3003/Diabetic-Retinopathy_Autoencoder/blob/b58fc6765adc889079e409f70c35c8855847e601/Assets/3_Autoencoder%20Structure.png" width="200" />
</p><br>
<em><b>Autoencoder Structure and Parameters</b></em><br>




<p float="left">
  <img src="https://github.com/Aadit3003/Diabetic-Retinopathy_Autoencoder/blob/6e1e0aa60309dc71de149cdae4fb1471a39befd5/Assets/3_Autoencoder.png" width="560" />
  <img src="https://github.com/Aadit3003/Diabetic-Retinopathy_Autoencoder/blob/b58fc6765adc889079e409f70c35c8855847e601/Assets/3_Results.png" width="440" /> 
</p><br>
<em><b>Autoencoder Approach and the resulting Confusion Matrix</b></em>




## Installation and Use

Comparison Table
CSV Files
Different Dataset: What to change

<img src="" width = "512"><br>
<em><b>Positive Tweet</b></em><br>

<img src="" width = "512"><br>
<em><b>Negative Tweet</b></em>

## References
- <em>Khalid, S., Prieto-Alhambra, D. Machine Learning for Feature Selection and Cluster Analysis in Drug Utilisation Research. Curr Epidemiol Rep 6, 364–372 (2019).</em> ([Paper Link](https://rdcu.be/cQnva))
- Please refer to the PPTs for a more detailed analysis of the three Feature Selection methods and their results.
  - ([PPT 1: Feature Selection (3 methods)](https://github.com/Aadit3003/Diabetic-Retinopathy_Autoencoder/blob/8fd10b7258584e88716d1c40f8f6009797779586/Assets/PPT%20I%20Feature%20Selection.pdf))
  - ([PPT 2: Autoencoder for Feature Selection](https://github.com/Aadit3003/Diabetic-Retinopathy_Autoencoder/blob/8fd10b7258584e88716d1c40f8f6009797779586/Assets/PPT%20II%20Autoencoder.pdf))
