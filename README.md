# Machine Learning Project : Iris-flower-classification
This program applies basic machine learning (classification) concepts on *Fisher's Iris Data* to predict the species of a new sample of Iris flowe
- Python 3.6.0
- Anaconda 4.3.0 (32 bit)
- scikit-learn 0.18.1

**Introduction**
The dataset for this project originates from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Iris). The Iris flower data set or Fisher's Iris data set is a multivariate data set introduced by the British statistician and biologist Ronald Fisher in his 1936 paper The use of multiple measurements in taxonomic problems as an example of linear discriminant analysis.
- The data set consists of 50 samples from each of three species of Iris (Iris setosa, Iris virginica and Iris versicolor).
- Four features were measured from each sample (in centimetres): 
    the length of the sepals
    the width of the sepals
    the length of the petals 
    the width of the petals

**Working of the program**
- The program takes data from the `load_iris()` function available in `sklearn` module.
- The program then creates a decision tree based on the dataset for classification.
- The user is then asked to enter the four parameters of his sample and prediction about the species of the flower is printed to the user.
