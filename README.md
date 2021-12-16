# Yelp-Cuisine-Analysis
UMass CS490A Final Project -- Nisarga Patil, Apurv Shah, Anand Murali

# How to Run
To run the code, perform the following steps:
1. Clone the repository to your machine using the command `git clone git@github.com:anand-s-murali/Yelp-Cuisine-Analysis.git`
2. `cd (change directory)` into the project.
3. Install the dependencies using the command `pip install -r requirements.txt`
4. `cd` into `Code/`
5. Run the main python file using the command `python3 main.py`

All intermediate results can be reproduced by running the respective python file. For example, if you wanted to visualize the cross-validation/hypertuning process for our Naive Bayes model, simply perform steps 1-4 listed above, and then run `python3 naive_bayes.py`; similarly for Logistic Regression, run `python3 logisitc_regression.py`. As of now the code for BERT is fully functional, however, we have no results, as it would take an infeasible amount of time to train the model.
