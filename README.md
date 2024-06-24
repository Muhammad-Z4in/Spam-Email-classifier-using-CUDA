# Spam-Email-classifier-using-CUDA
This project features a spam email classifier that leverages logistic regression with CUDA acceleration provided by [CuPy](https://cupy.dev/). For feature extraction, the model is trained using [scikit-learn](https://scikit-learn.org/stable/). It includes functionality to assess the model's accuracy using an 80/20 testing split and can classify new emails.

## Features
- Applies logistic regression to classify emails.
- Employs CUDA acceleration via CuPy for expedited computation.
- Utilizes scikit-learn's CountVectorizer for feature extraction.
- Includes functionality to assess model accuracy using an 80/20 testing split.
- Allows classification of new emails.

## Requirements
- Python 3.x
- CuPy
- NumPy
- pandas
- scikit-learn
