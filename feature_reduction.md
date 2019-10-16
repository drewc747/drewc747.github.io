## Feature Reduction

**Techniques Explored:** Principle Componant Analysis (PCA), Linear Discriminant Analysis (LDA), Multi-Dimensional Scaling (MDS), Locality Sensitive Hashing (LSH)

**Skills Demonstrated:** Python, Feature Reduction Techniques

**Project description:** In machine learning it is often desired to reduce the amount of features (or dimensions) of a given problem. As the number of features in a problem increases, so does the problem complexity. However, it is often the case the features are redundant and can be removed with minimal decrease in a models performance while significantly decreasing the models complexity. This project will first explore the curse of dimensionality, a simple projection example, and then implament some common techniques used for feature reduction as well as the advantages and disadvantages of each. Techniques to be explored are PCA, LDA, MDS, and LSH. 

### 1. What is feature reduction? A simple example:
As a simple example, let look at training data in a 2D space consisting of red circles and blue squares. The plot below shows these data points in xy space.

Based on this training data, we may want to create a classifier that can tell us whether a data point is a circle or square based on the xy coordinates, and in the case above there is a clear correlation with xy coordinates and whether or not a data point is a circle or a square. We could draw a line between to seperate the training data, and then use that line for the test data to make a prediction on whether or not a data point is a red circle or blue square based on where the datapoint falls relative to the line. The plot shows one line that may work for this.

Upon closer inspection, you can see that if you were to project all the data onto the x-axis, there is still seperation between the data points suggesting the the only feature that is needed to classify this data set is the x-coordinate. The plot below shows the data points projected onto the x axis and a point on the x-axis used as a threshold for classification.

Alternatively, if we try projecting the data onto the y-axis, we no longer have the ability to distinguish the red circles and blue square based on just the y value.  The plot below shows the data projected onto the y-axis.

This simple example shows that feature reduction can be performed in order to simplify a problem by removing redundant features. In this case, the y-value is redundant and unecessary for the classification of red circles and blue squares.

```python
if (isAwesome){
  return true
}
```

### 2. Why is feature reduction important? The curse of dimensionality:


### 3. Principle Componant Analysis (PCA)

<img src="images/dummy_thumbnail.jpg?raw=true"/>

### 4. Linear Discriminant Analysis (LDA)


### 5. Multi-Dimensional Scaling (MDS)


### 6. Locality Sensitive Hashing (LSH)

For all code, see [GitHub Repository](https://github.com/drewc747/machine-learning-examples/tree/master/feature_reduction)
