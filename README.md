# ECE9309 Machine Learning Course Anomaly Detection Final Exam

This is my final exam work for ECE9309B Machine Learning course offered at Western University in Winter 2020 by Dr. Abdallah Shami. Full work available in ECE9309_TareqTayeh_FinalExam.ipynb.

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
<p align="center">
  <img src="https://github.com/TareqTayeh/Machine_Learning_Course_Anomaly_Detection_Final_Exam/blob/master/figures/arbitrary_threshold_anomaly.png" width="700">
</p>
<p align="center">
  <img src="https://github.com/TareqTayeh/Machine_Learning_Course_Anomaly_Detection_Final_Exam/blob/master/figures/arbitrary_threshold_anomaly_results.png" width="700">
</p>


#### 9) Plot the generated alarm, true anomaly labels (given in label column from the dataset), and the feature of the most important feature obtained from the ranking test in Question 4.
<p align="center">
  <img src="https://github.com/TareqTayeh/Machine_Learning_Course_Anomaly_Detection_Final_Exam/blob/master/figures/generated_alarm_plotted.png" width="700">
</p>

#### 10) Apply one supervised learning approach, using all features (columns A, B, ..., H), for classifying the events to normal and anomalies. Use relative performance metrics to evaluate its performance.
<p align="center">
  <img src="https://github.com/TareqTayeh/Machine_Learning_Course_Anomaly_Detection_Final_Exam/blob/master/figures/SVM_results.png" width="700">
</p>

#### 11) Apply any clustering based algorithm, using all features (columns A, B, ..., H), to separate the anomaly data from the normal ones.
<p align="center">
  <img src="https://github.com/TareqTayeh/Machine_Learning_Course_Anomaly_Detection_Final_Exam/blob/master/figures/K-NN_results.png" width="700">
</p>

#### 12) Compare the Gaussian-based anomaly detection algorithm, the supervised learning approach you picked, and the clustering approach.
<p align="center">
  <img src="https://github.com/TareqTayeh/Machine_Learning_Course_Anomaly_Detection_Final_Exam/blob/master/figures/algorithm-evaluations.png" width="700">
</p>
<p align="center">
  <img src="https://github.com/TareqTayeh/Machine_Learning_Course_Anomaly_Detection_Final_Exam/blob/master/figures/algorithm-evaluations-visualizations.png" width="700">
</p>
<p align="center">
  <img src="https://github.com/TareqTayeh/Machine_Learning_Course_Anomaly_Detection_Final_Exam/blob/master/figures/algorithm-evaluations-visualizations2.png" width="700">
</p>
<p align="center">
  <img src="https://github.com/TareqTayeh/Machine_Learning_Course_Anomaly_Detection_Final_Exam/blob/master/figures/algorithm-evaluations-visualizations3.png" width="700">
</p>
<p align="center">
  <img src="https://github.com/TareqTayeh/Machine_Learning_Course_Anomaly_Detection_Final_Exam/blob/master/figures/algorithm-evaluations2.png" width="700">
</p>
<p align="center">
  <img src="https://github.com/TareqTayeh/Machine_Learning_Course_Anomaly_Detection_Final_Exam/blob/master/figures/algorithm-evaluations3.png" width="700">
</p>

#### 13) Optimize the parameter e from Question 8 to maximize the detection rate and minimizing the false alarm rate (multi-objective optimization).
<p align="center">
  <img src="https://github.com/TareqTayeh/Machine_Learning_Course_Anomaly_Detection_Final_Exam/blob/master/figures/optimized_threshold_results.png" width="700">
</p>
<p align="center">
  <img src="https://github.com/TareqTayeh/Machine_Learning_Course_Anomaly_Detection_Final_Exam/blob/master/figures/optimized_threshold_results2.png" width="700">
</p>