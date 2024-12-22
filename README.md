# K-Nearest-Neighbors-using-Iris-Dataset
**K-Nearest Neighbors Algorithm (KNN)**
**Definition**
K-Nearest Neighbors (KNN) is a simple, non-parametric, and lazy learning algorithm used for classification and regression. It works by identifying the 𝑘 closest data points (neighbors) to a given data point in a feature space and makes predictions based on the majority class (classification) or the average of the neighbors (regression).

**Equation Explanation**
The distance metric is central to KNN, commonly calculated using Euclidean distance:

𝑑(𝑖,𝑗)=∑𝑛=1𝑁(𝑥𝑖,𝑛−𝑥𝑗,𝑛)2
d(i,j)= n=1∑N (xi,n −xj,n)2
 
​Where:

d(i,j): Distance between points 𝑖 and 𝑗

x i,n : n-th feature of point i

x j,n : n-th feature of point j

N: Total number of features

The k smallest distances determine the nearest neighbors.

**Advantages**

Simplicity: Easy to understand and implement.

No Training Phase: Lazy learner; minimal computation during training.

Adaptability: Effective with non-linear data without the need for assumptions about data distribution.

**Disadvantages**

Computational Cost: High during prediction for large datasets.

Memory Intensive: Requires storing the entire dataset.

Sensitive to Noise: Outliers can significantly affect results.

Feature Scaling: Performance depends on properly scaled data.

