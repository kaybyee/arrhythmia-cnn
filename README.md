# arrhythmia-cnn
CNN-based ECG Arrhythmia Classification: Deep learning model to classify heartbeats into 5 arrhythmia categories

The five categories of heartbeats identified in the study are:
1. Normal (N): Represents normal sinus rhythm heartbeats.
2. Supraventricular Ectopic (S): Includes atrial premature contractions and other supraventricular ectopic beats.
3. Ventricular Ectopic (V): Comprises premature ventricular contractions and other ventricular ectopic beats.
4. Fusion (F): Occurs when a normal heartbeat coincides with an ectopic beat, resulting in a fusion beat.
5. Unknown (Q): Heartbeats that cannot be classified into the above categories due to noise or other factors.

DATASET:
The model was trained and evaluated using the MIT-BIH Arrhythmia Database, a widely used dataset in ECG research. This dataset contains 48 half-hour excerpts of two-channel ambulatory ECG recordings, with annotations for various types of arrhythmic events. The data was preprocessed to remove high-frequency noise and artificially augmented to balance the number of instances across the five classes.






## References
This project is an implementation based on the paper:  
U. Rajendra Acharya, Shu Lih Oh, Yuki Hagiwara, Jen Hong Tan, Muhammad Adam, Arkadiusz Gertych, Ru San Tan (2017)
"A deep convolutional neural network model to classify heartbeats"

