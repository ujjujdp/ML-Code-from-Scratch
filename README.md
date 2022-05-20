# ML-Code-from-Scratch
## 1. K - Nearest Neighbor

Implemented KNN from scratch using basic python libraries. Applied KNN in iris dataset which has 150 samples and 3 class (50 samples from each class). 

**Result:** Achieved an accuracy of 100% with k = 3( and some other values of k)
Also, plotted curve to observe accuracy vs k - value, and accuracy vs p(distance metric). The below is the result what I got,
- Accuracy degrades with increase in value of k; It is observed that for k>60 for this particular dataset, the accuracy of the KNN drops significantly.
- Accuracy remains almost the same for p >= 2. For p = 1, the accuracy is very bad, but for other p, it is similar to using euclidean distance. Hence, we use euclidean distance as it gives best accuracy with lesser mathematical complexity.

## 2. Logistic Regression

Implemented Logistic Regression from scratch using basic python libraries. Stochastic Gradient Descent was used to update the value of parameters. Applied Logistic Regression in Sentiment Analysis DataSet(Movie Reviews) which has 1000 samples and 2 class (500 samples from each class. Used TF-IDF representation to convert the text data into feature vector. Then applied PCA to reduce the dimension to 20.

**Result:** Achieved an accuracy of 62%.

Plotted loss curves for different values of Batch_Size in Stochastic Gradient Descent, Learning Rate and Regularization Coefficient.

## 3. PCA + LDA

Implemented PCA and LDA from scratch using basic python libraries. DataSet used contains image of people with happy or sad emotion, the task was to classify the test images as happy or sad. Used PCA to reduce the dimension from 10000 to 16. Further used LDA to project the data points in 1-D real line on which the separation between two classes were easily visible. 

**Result:** Achieved an accuracy of 100%.

## 3. K-Means Clustering

Implemented K-Means Clustering Algorithm from scratch using basic python libraries. Random 2-D DataSet was generated using make_blobs inbuilt function from sklearn library. Plotted the scatter plot of points belonging to different clusters by color coding them.

**Result:** Scatter Plot of data points with k = 3

