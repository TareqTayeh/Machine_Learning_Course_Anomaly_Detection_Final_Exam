# ECE9309 Machine Learning Course Anomaly Detection Final Exam

This is my final exam work for ECE9309B Machine Learning course offered at Western University in Winter 2020 by Dr. Abdallah Shami.

### Questions:
#### 1) Indicate the ratio of the normal and anomaly examples in the dataset. Make a bar chart to visualize the ratios.
<p align="center">
  <img src="https://github.com/TareqTayeh/Machine_Learning_Course_Anomaly_Detection_Final_Exam/blob/master/figures/Bar-Chart-Ratios.png" width="600">
</p>

#### 2) Plot the probability density function (PDF) of each feature, and make your observations of the pdf of each feature (i.e., normal distribution, left-skewed distribution, right-skewed distribution, ...) 
Lets take a feature example
<p align="center">
  <img src="https://github.com/TareqTayeh/Machine_Learning_Course_Anomaly_Detection_Final_Exam/blob/master/figures/Requests-Feature-Analysis.png" width="700">
</p>

#### 3) Find the correlation between the features. Indicate the highly correlated features and the independent features.
<p align="center">
  <img src="https://github.com/TareqTayeh/Machine_Learning_Course_Anomaly_Detection_Final_Exam/blob/master/figures/Correlation.png" width="600">
</p>
<p align="center">
  <img src="https://github.com/TareqTayeh/Machine_Learning_Course_Anomaly_Detection_Final_Exam/blob/master/figures/Correlation-Analysis.png" width="700">
</p>

#### 4) Apply any significance test to rank the significance of each feature as being a distinctive feature of anomalies.
<p align="center">
  <img src="https://github.com/TareqTayeh/Machine_Learning_Course_Anomaly_Detection_Final_Exam/blob/master/figures/Ridge-Regression.png" width="700">
</p>

#### 5) Apply a suitable transformation to make better suit the Gaussian shape. Plot the normal probability plot and the pdf of each feature before and after the transformation. Also, indicate the formula that is used to transform each feature (i.e., yi = log (xi)).
<p align="center">
  <img src="https://github.com/TareqTayeh/Machine_Learning_Course_Anomaly_Detection_Final_Exam/blob/master/figures/Yeo-Johnson.png" width="700">
</p>
Lets take a feature example
<p align="center">
  <img src="https://github.com/TareqTayeh/Machine_Learning_Course_Anomaly_Detection_Final_Exam/blob/master/figures/Requests-Feature-Post-Yeo-Johnson.png" width="700">
</p>
<p align="center">
  <img src="https://github.com/TareqTayeh/Machine_Learning_Course_Anomaly_Detection_Final_Exam/blob/master/figures/Requests-Feature-Post-Yeo-Johnson-Problot.png" width="700">
</p>


#### 6) Split the data randomly into 70 training and 30 testing datasets. Make sure that the training dataset contains 70 of the total anomalies and the testing dataset contains 30 of the total anomalies. Indicate the ratio of the normal and anomaly examples for both datasets.
<p align="center">
  <img src="https://github.com/TareqTayeh/Machine_Learning_Course_Anomaly_Detection_Final_Exam/blob/master/figures/Train-Test-Split.png" width="700">
</p>

#### 7) Model the features in the training dataset (all features, columns A, B, ..., H) using the multivariate Gaussian distribution. Please write down the expression of the multivariate Gaussian distribution and show the mean vector and the connivance matrix
<p align="center">
  <img src="https://github.com/TareqTayeh/Machine_Learning_Course_Anomaly_Detection_Final_Exam/blob/master/figures/multivariate_gaussian3.png" width="700">
</p>
<p align="center">
  <img src="https://github.com/TareqTayeh/Machine_Learning_Course_Anomaly_Detection_Final_Exam/blob/master/figures/multivariate_gaussian_probabilities.png" width="700">
</p>


#### 8) Develop an anomaly alarm by adjusting a threshold e to your Gaussian models obtained in Questions 7, and accordingly, generate the anomaly alarm. Evaluate its performance using relative metrics (use the label column as a benchmark for the true anomalies).