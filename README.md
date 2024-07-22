# AnomalyQuest-Exploring-Novel-Approaches-for-Anomaly-Detection-in-Diverse-Domains
Here we have done outlier detection on 4 dataset.
1. Credit Card
   Based on different features which are already dimensionality reduced we classify whether the data is from fraud or normal
   Source: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
2. Network Intrusion Dataset
   Taken from the famous kdd cup 99 dataset here we took normal data and labelled all other types of attacks as simply fraud/attack
   Source: https://www.kaggle.com/code/aravindnaidu/anomaly-detection-on-kdd-99-intrusion-detection
3. Thyroid
   The original thyroid disease (ann-thyroid) dataset from UCI machine learning repository is a classification dataset. For outlier detection, 3772 training instances are used, with only 6 real attributes. The hyperfunction class is treated as outlier class and other two classes are inliers, because hyperfunction is a clear minority class.
   Source: https://archive.ics.uci.edu/dataset/102/thyroid+disease
4. Forest Cover
   The original ForestCover/Covertype dataset from UCI machine learning repository is a multiclass classification dataset. It is used in predicting forest cover type from cartographic variables only.. Here, outlier detection dataset is created using only 10 quantitative attributes. Instances from class 2 are considered as normal points and instances from class 4 are anomalies. The anomalies ratio is 0.9%. Instances from the other classes are omitted.
   Source: https://archive.ics.uci.edu/dataset/31/covertype


Also we have calculated and ploted the time and space complexity of each algorithm on a seperate note(TimeAndSpaceComplexity.ipynb). This is to view how increasing number and attributes and attribute of input increases the space-time complexity.
