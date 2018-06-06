
# Project Timeline

1. April 12,2018 - Met Prof Scalzo and gave inputs to solve the problem. He sent an introductory mail to Dr. Yannan Yu to get more information. We are planning to first analyse raw images without any image transformation. We then plan to use CNN and other feature extraction techniques.

2. April 13, 2018 - Formed group

3. April 15, 2018 - Started developing website for timeline and preliminary results

4. April 19, 2018 - Met Dr. Yannan Yu to know more about the project details

5. April 22, 2018 - Recieved Data from Dr. Scalzo

6. April 25, 2018 - Made a simple Decision Tree Classifier without any data transformation and got an accuracy of 95.8%.

7. April 27, 2018 - Used Standard Scaler to see if it makes any improvement. No good improvement seen. 

8. April 28, 2018 - Made Train and test models have different patient IDs and then tested the same model. Pretty bad performance. 

9. May 5, 2018 - Used Boosting Model (XGboost) to improve the performance. Observed a higher accuracy.

10. May 7, 2018 - Made an LSTM model only on the time seris features. Improvement over the baseline model observed

11. May 12, 2018 - Made Multi input model.

12. May 20, 2018 - Used ROC and AUC as metrics

13. May 29, 2018 - Made Heatmaps on test images

# Dependencies used for the code

1. Numpy
2. Pandas
3. Scikit-Learn
4. Xgboost
5. Keras
6. Matplotlib
7. pylab
8. scipy
9. tensorflow
10. os

# Procedure for running the code

1. It is very simple to run the code. Simply install all the above mentioned libraries and run the jupyter notebooks cell by cell in order.

2. Make sure you change the folder directories as they are local to mine.
