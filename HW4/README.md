# HW4
## Instructor : Dr.babaali

### The first question

The data of two classes in two-dimensional space is given as follows:
$$ \set((0,-1),(1,0),(2,1),(1,1),(-1,1),(-1,-1),(-1,-1)) $$
1. Obtain the main components.
2. Map the data on the first component.
3. Reconstruct the original values using the mapped values.
4. Show the initial values and the reconstructed values in the picture.
The process should be done descriptively.

### The second question
Two files named npy.set_train and npy.set_test are provided with the exercises, which is the data set of the second exercise.

1. First, display the training and test data in two-dimensional space.
2. Using LDA, map the data to a one-dimensional space and train the model using perceptron or linear regression, report the error on the training and test data. visualize the incorrectly classified data.
3. Using PCA, map the data to one-dimensional space and perform other steps similar to the previous part.
4. Between the results of LDA and PCA, conclude which one is better and why.

Note: Test data should only be used for final evaluation and should not be used in any training phase.
It is suggested to standardize the data first

### The third question
We have a collection of face pictures of 40 different people (10 pictures from each person) (attached). In fact, the dataset contains 400 64 x 64 dimensional images, where each pixel of the image has a value between 0 and 255 (gray images), the data is stored in the mat.faces file. Divide the training and evaluation data with a ratio of 70 to 30. Consider the first 70% of the data for training.
1. Implement the PCA algorithm, in this step, keep the first 45 main components and display the image in a state where only these 45 components are used in image reconstruction and display it graphically (on any image from the set of tested images); And also get the RMSE error between the reconstructed images and the original images on the training and test data.
2. Find out how many components you should keep so that the shape of the image, in your opinion, does not differ from its original shape (without PCA).
With this component value, select an arbitrary image from the test data and run the PCA algorithm on it, and then reconstruct the result and compare the original image; And also get the RMSE error between the reconstructed images and the original images on the training and test data.
