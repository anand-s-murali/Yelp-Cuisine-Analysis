# Yelp-Cuisine-Analysis
UMass CS490A Final Project -- Nisarga Patil, Apurv Shah, Anand Murali

# Requirements
In order to successfully run this project, you will need to install the following packages:
```
pandas==1.1.3
numpy==1.18.4
tabulate==0.8.3
sklearn==0.0
nltk==3.6.5
matplotlib==3.5.0
torch==1.9.1
transformers==4.13.0
datasets==1.16.1
```

# How to Run
1. Clone the repository to your machine.
2. Change directory so that you are now in `Code/`
3. Run the main python file `python3 main.py`

All intermediate results can be reproduced by running the respective python file. For example, if you wanted to visualize the cross-validation/hypertuning process for our Naive Bayes model, simply perform the first two steps listed above, and then run `python3 naive_bayes.py`. Similarly for `logistic_regression.py` and `bert.py`.
