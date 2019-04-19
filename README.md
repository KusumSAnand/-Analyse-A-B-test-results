
## Project:  A/B Test result analysis
### Overview

This project analyses the A/B test results,comparing the new and old versions of the web page from an e-commerce company. The new page has been designed to improve the conversion rate, ie increase the number of users who pay for the product.  The goal of the analysis is to decide on the implementation of the new page or to continue further testing for a longer duration before deciding on its implementation.

The analysis has been performed in terms of Probablity,Hypothesis testing and Logistic regression  to determine the implementation of the new web page.

### Software Requirements

This project requires **Python 3.x** and the following Python libraries installed:

- [numPy](http://www.numpy.org/)
- [pandas](http://pandas.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [matplotlib](http://matplotlib.org/)
- [patsy](https://pypi.org/project/patsy/)
- [statsmodels](https://www.statsmodels.org/stable/index.html)

### Data

The dataset used for analysis - 'ab_data.csv' has 4 features and 294478 data points
Interaction term,country is introduced via countries.csv.

**Features**
- `user_id`: unique id associated with each of the users.
- `timestamp`: timestamp of the landing page accessed.
- `group`: User who is part of Control or Treatment group.
- `landing_page`: User accessing either old landing page vs new landing page.
- `country`: country the user lives.


**Target variable**
- `converted` :whether the user converted or not

