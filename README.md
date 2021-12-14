# applied-machine-learning-project
This is a repository for CS5785 Applied Machine Learning course at Cornell Tech. 

# Content
## HW0-Visualization-of-Iris-Dataset
* Built visualization of the Iris dataset.

## HW1-Kaggle-Housing-Price-Titanic-Disaster
* Completed [the House Prices - Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques) competition on Kaggle.
    * Pre-processed data: steps include one-hot encoding, dealing with missing values, normalizing numerical values, dealing with categorical values etc.
    * Built ordinary least squares (OLS) from scratch to predict house prices on this dataset.
    * The result is MSE of 0.013690668658049349 and R-square of 0.9141384048093214.
* Completed [the Titanic: Machine Learning From Disaster](https://www.kaggle.com/c/titanic) competition on Kaggle.
    *  Pre-processed data: steps include one-hot encoding, dealing with missing values, normalizing numerical values, dealing with categorical values etc.
    *  Used logistic regression to predict whether a passenger survived the disaster.
* The math excersie explores topics on Maximum Likelihood and KL Divergence, Gradient and log-likelihood for logistic regression, and Linear regression and OLS.

## HW2-Binary-Classiﬁcation-on-Text-Data
* Worked on [the NLP with Disaster Tweets](https://www.kaggle.com/c/nlp-getting-started) Kaggle competition, where the task is to predict whether or not a tweet is about a real disaster.
    * Pre-processed data: 1.Convert all the words to lowercase 2.Lemmatize all the words 3.Lemmatize all the words 4.Strip the stop words 5.Strip the stop words 6.Strip the HTML tags 7.Strip the urls.
    * Built bag of words model.
    * Performed classiﬁcation on text data with Logistic regression (without regularization terms/L1/L2), Bernoulli Naive Bayes classiﬁer, N-gram model; then compared models.
* The math excersie explores topics on Naive Bayes with Binary Features and Categorical Naive Bayes.

## HW3-Eigenface-Implement-EM
* Implemented the Eigenface method for recognizing human faces, using face images from The Yale Face Database B, where there are 64 images under different lighting conditions per each of 10 distinct subjects, 640 face images in total.
* Implemented a bimodal GMM model ﬁt using the EM algorithm from scratch.
* The math excersie explores topics on SVD and eigendecomposition.

## HW4-Convolutional-Neural-Networks-Random-Forest
* Convolutional Neural Networks
    * Worked with the MNIST dataset. This dataset contains 60,000 images of handwritten numbers from 0 to 9.
    * Recognized the handwritten numbers by building a CNN model.
* Random Forests for Image Approximation
    * use random forest regression to approximate an image by learning a function, f : R^2 → R , that takes image (x, y) coordinates as input and outputs pixel brightness. This way, the function learns to approximate areas of the image that it has not seen before.
* The math excersie explores topics on Maximum Margin Classiﬁers and Neural Networks as Function Approximators.
