# Air-Quality-Predictor

Air pollution is the presence of some toxic substances in the atmosphere that have deleterious effects on human health and the quality of air is deteriorating day by day. So, with the help of some functionalities of python and machine learning algorithms we try to predict the quality of air.

This project requires Python 3.6 and above and includes the following libraries:

1. [Numpy](https://numpy.org/)
2. [Pandas](https://pandas.pydata.org/)
3. [Matplotlib](https://matplotlib.org/)
4. [Scikit-learn](https://scikit-learn.org/stable/)

You'll also need a software to write and run the code such as Jupyter Notebook.

## About  Dataset

The dataset contains 5 features on which the quality of air depends and the 6th feature is the target feature/output after processing all features. Each feature has 1600 data points on which we train our model.

## Model Used

I've built the Gradient Descent Algorithm to predict the values and also used the pre-defined model of Linear Regression provided by the the sklearn library of python.
The accuracy of both the models is nearly equal.

![Screenshot (44)](https://user-images.githubusercontent.com/84842113/125256489-1c657c80-e31a-11eb-83e2-6f678105da3f.png)

The above graph shows the reduction in error after each epoch.
