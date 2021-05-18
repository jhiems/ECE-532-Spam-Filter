# ECE-532-Spam-Filter
Attempts at building an email spam filter for ECE 532



The folder enron1 contains the dataset used.

The folder images contains all images that were generated during the project.

The folder Results text files contains all text files with results that were generated during the project.

The folder Writeup contains the Tex files as well as the PDF of the final writeup for this project.

The code in this project should be run using the latest version of Python 3. Various packages may be necessary, including but not limited to numpy, scikitlearn, and io.

Within each section below, code should be run in the order presented unless otherwise stated. It is necessary to run the Data Preprocessing section before any following section. Preprocessed data could not be included on GitHub due to size limitations.

#######################################################
Data Preprocessing
#######################################################
Dictionary.py -- make a dictionary from the data
Vectors.py -- implement Bag of Words model by making word vectors for each email
## Change DataMatrix.txt to DataMatrix.csv
labels.py -- Generate labels from the emails

#######################################################
Least-Squares
#######################################################
Erase Duplicates.py -- Get rid of duplicate emails
Least_squares.py -- find the weights
LS Error Computation.py -- find misclassifications and other useful data.


#######################################################
SVMs
#######################################################
Kernelized SVM.py -- train and run kernelized SVMs using the function defined in this program.


#######################################################
Neural Networks
#######################################################
NNet Function.py -- Train and run neural networks using the function defined in this program.

#######################################################
Naive Bayes
#######################################################
Naive Bayes.py -- Runs the Naive Bayes classifier without cross-validation. Does not need to be run before the next program
Naive Bayes with cross validation.py -- Runs the Naive Bayes classifier with cross validation.
