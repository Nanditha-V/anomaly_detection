# anomaly_detection
Anomaly detection using Machine learning and Deep learning model.

Anomaly detection is a technique used to identify abnormal patterns or events in data that deviate significantly from the normal. These anomalies can represent either rare occurrences or errors in the data. The goal of anomaly detection is to separate these abnormal instances from the regular or expected patterns present in the data.

Anomaly Detection have wide applications in various industries like cybersecurity, Fraud detection, IOT, health care etc

In any Anomaly Detection problem, the various steps(generalized:)
1. define the anomaly for the problem statement (for supervised model)
2. preprocossing includes fill missing date,removal of duplicates, normalization and handling categorical data 
3. feature engineering includes all the features required for the model as input variales
4. modelling (various models are used to solve AD model like ML,DL, clustering and time series)
5. Post processing: includes defining the thresholds
there are two kinds of thresholds, dynamic and static
Static Threshold:
A static threshold is a fixed value that remains constant throughout the anomaly detection process. It is predefined based on domain knowledge or statistical analysis of the data. The basic idea is that any data point or observation that crosses this fixed threshold is considered an anomaly.
Dynamic Threshold:
A dynamic threshold, on the other hand, is a threshold that changes or adapts over time based on the characteristics of the data. Instead of using a fixed value, the threshold is updated dynamically, allowing the anomaly detection system to adapt to changing patterns in the data.
Threshold = Mean + 2 * Standard Deviation
It's important to note that this static threshold is appropriate when dealing with data that follows a roughly normal distribution. In real-world scenarios, data may follow different distributions or have varying levels of noise, so it's essential to analyze the data's characteristics and possibly consider more sophisticated dynamic thresholds for anomaly detection.
