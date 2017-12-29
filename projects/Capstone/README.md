# Machine Learning Engineer Nanodegree - Build a Digit Recognition Program

This project requires **Python 2.7** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [SciPy](https://www.scipy.org/)
- [scikit-learn](http://scikit-learn.org/0.17/install.html) (v0.17)
- [TensorFlow](http://tensorflow.org)
- [keras](https://keras.io/#installation)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html).

### Code
The code is stored in four Jupyter Notebooks.
- digit_recognition_MNIST.ipynb
This notebook contains all the code related to my analysis of the MNIST dataset.

- hp5ytopickle.ipynb
This notebook loads the data from the SVHN hp5y files and saves it as a pickle file to be accessed by other notebooks. The code in this notebook must be run before running the following two notebooks!

- Data_Exploration.ipynb
This notebook contains a preliminary exploration of the SVHN data.

- digit_recognition_SVHN.ipynb
This notebook contains the code that builds, trains and analyzes the results of the CNN I used to classify 

### Data
You will need to download the [Street View House Numbers (SVHN) dataset](http://ufldl.stanford.edu/housenumbers/).  The model was trained on the train and extra datasets and tested on the test dataset.

The digit_recognition_MNIST.ipynb contains a script to download the MNIST dataset otherwise it can be downloaded from (http://yann.lecun.com/exdb/mnist/).
