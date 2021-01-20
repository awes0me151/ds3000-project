# Predicting the Price of an Uber or Lyft Ride

For our DS 3000 (Foundations of Data Science) final project, we decided to analyze rideshare rides such as Uber and Lyft in the Boston area. Currently, when we use an app like Uber or Lyft, we simply input our current location and a destination, resulting in a price we pay if we choose to accept the ride. However, we believed that other non-obvious factors may influence a price of a rideshare, such as the weather, time of day, or temperature. We believed that this project is important because depending on our findings, this may allow users to gain a better insight into how a price is calculated, and possibly be able to plan their ride days in advance. Our findings might also tell users the best hours to commute, or whether an Uber or Lyft might be the better option.

We used a Jupyter Notebook to execute and display our work. If you want to run this code for yourself, here are some libraries you must install to run the notebook for yourself.

- [ ] pandas
- [ ] sklearn
- [ ] scipy
- [ ] plotly.express

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install these libraries.

```bash
pip install pandas
pip install sklearn
pip install scipy
pip install plotly_express==0.4.0
```

## General Overview of the Project
1. Introduction
2. Data Wrangling
    * Removing NAN values
    * Removing unnecessary columns
    * One-hot encoding
    * Min-max scaling
    * Model-based feature selection
3. Data Exploration
    * Scatter Plot
    * Bar Graph
    * Heatmap
4. Hypothesis Testing
    * Assumption Checks
        * Levene
        * Shapiro-Wilk
    * Mann-Whitney U-test
5. Model Evaluation and Testing
    * Models Used
        * Multiple Linear Regression
        * Lasso Regression
        * Ridge Regression
    * Evaluation Metrics
        * R-squared Score
        * Mean Squared Error
    * Hyperparameter Tuning
        * GridSearchCV
6. Discussion and Next Steps

### References
* [Reference 1](https://medium.com/@malaiiyy/presenting-to-you-the-lyft-and-uber-price-predictor-known-as-the-ride-hailer-47dea6dc7a9a)
* [Reference 2](https://www.naefrontiers.org/184199/Abstract)
* [Reference 3](https://mds.marshall.edu/cgi/viewcontent.cgi?article=2263&context=etd)

[Link to Dataset](https://www.kaggle.com/brllrb/uber-and-lyft-dataset-boston-ma)

**By Justin Lau, Siddhant Dosi, and Aneesh Atri**
