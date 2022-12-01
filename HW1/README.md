The data is in the data.npz file (attached). This data was generated based on the following relationship:

$$ y = 4x_2^2x_1 + 2x_2^2 + 3x_1 + 1 $$

Therefore, the samples are [x2,x1] and their corresponding output is y. There are six one-dimensional arrays in the npz.data file, x2test, x1test, ytest, x2, x1, y. An example of accessing the y file array is as follows:

a = np.load('data.npz')
print(a['y'])
