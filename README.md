# Automatic Classification of Solos and Kicks in Gaelic Football Using Accelerometer Data<br>

## **Project Overview**<br>
This research aimed to classify Gaelic football actions (solos, kicks, and shots) using accelerometer data from wearable devices. <br>
Signal processing and machine learning methods, including Support Vector Machines (SVM) and Random Forests, were applied to detect these actions automatically.<br>

---

## **Key Objectives**<br>
1. Identify and categorise solos, kicks, and shots in Gaelic football.  <br>
2. Build machine learning models (SVM and Random Forest) to classify these actions.  <br>
3. Evaluate model accuracy using metrics such as sensitivity, precision, and recall.  <br>

---

## **Methodology**<br>
1. **Data Collection**:  <br>
   - Gather accelerometer data from four players during various activities.<br>  
   - Use a Playertek device to record data at 100 Hz on three axes (X, Y, Z).<br>

2. **Signal Processing**:  <br>
   - Use sliding windows, Butterworth filters, and peak detection to identify potential action windows. <br> 
   - Extract features (e.g., standard deviation, skewness, kurtosis) for training.<br>

3. **Model Building**:  <br>
   - Train SVM models with kernel tricks for non-linear separable data.  <br>
   - Train Random Forest models for robust classification of solos, kicks, and shots.<br>

4. **Validation**:  <br>
   - Evaluate models using test data from unseen subjects.  <br>
   - Compare sensitivity, precision, and accuracy across models.<br>

---

## **Key Findings**<br>
1. **Kicks and Shots**:  <br>
   - Models achieved high precision and sensitivity (~93% to 100%).  <br>
   - Both SVM and Random Forest were highly effective for kick classification.<br>

2. **Solos**:  <br>
   - Model performance was lower due to variability in solo duration and similarity to running data.  <br>
   - Random Forest outperformed SVM with higher precision for solos.  <br>

---

## **Challenges**<br>
1. Variability in Solos: Duration differences and noise from running actions affected accuracy.  <br>
2. Limited Data: Results could improve with more extensive datasets and diverse subjects.  <br>

---

## **Recommendations**<br>
1. Incorporate gyroscope data to enhance solo detection.  <br>
2. Expand data collection to include more players, different conditions, and match settings.  <br>
3. Adapt the methodology for other sports and movements.<br>

---

## **Conclusion**<br>
This study demonstrated that wearable accelerometers can effectively classify Gaelic football actions, particularly kicks and shots, with high accuracy. <br>
While challenges remain for detecting solos, this research establishes a foundation for using machine learning in Gaelic football performance analysis and opens avenues for further advancements in sports analytics.




