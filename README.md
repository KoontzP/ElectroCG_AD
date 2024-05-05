This is a anomaly detection pipeline to detect anomalies in electro cardiograms with the use of deep learning with tensorflow. The pipeline uses the dataset ECG5000 that consists of ECG's that are normal and unnormal.
The neural networks learn features of how a normal ECG looks like and detects deviances by deconstructing and reconstructing ECG's. 
The network decides if a ECG has a anomaly when the error size is bigger then a certain threshold that it learns from training on normal ECG's.
This can be usefull in healthcare to alarm or notify the staff when a heartrate behaves abnormal.
