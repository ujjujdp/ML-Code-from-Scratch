# ML-Code-from-Scratch
1. **K - Nearest Neighbor**
Implemented KNN from scratch using basic python libraries. Applied KNN in iris dataset which has 150 samples and 3 class (50 samples from each class). Acheived an accuracy of 100% with k = 3( and some other values of k). Also, plotted curve to observe accuracy vs k - value, and accuracy vs p(distance metric). The below is the result what I got,
a. Accuracy degrades with increase in value of k; It is observed that for k>60 for this particular dataset, the accuracy of the KNN drops significantly.
b. Accuracy remains almost the same for p >= 2. For p = 1, the accuracy is very bad, but for other p, it is similar to using euclidean distance. Hence, we use euclidean distance as it gives best accuracy with lesser mathematical complexity.
