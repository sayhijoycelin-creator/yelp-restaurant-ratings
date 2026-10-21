# Yelp Restaurant Ratings: Prediction & Exploration

Explore how restaurant attributes and review counts relate to Yelp ratings in Las Vegas. The notebook compares linear regression, logistic regression, decision trees, and a random forest to predict star ratings and identify restaurants rated 4 stars or above.

An interactive Dash dashboard lets users compare restaurant groups and explore predicted probabilities for different restaurant profiles. Results show associations, not causal effects.

**Result:** random forest achieved **68.0% test accuracy**, versus **55.1%** for the majority-class baseline, on 2,688 test restaurants.

## Run

Place `yelp_train.csv` and `yelp_test.csv` beside `Yelp_Restaurant_Ratings.ipynb`.

```bash
pip install numpy pandas matplotlib scikit-learn plotly dash jupyter
```

Run notebook cells in order. The final code cell launches the dashboard locally. Random forest tuning may take several minutes.
