# Regression-Model-to-Predict-Stock-Option-Pricing
Build a model to predict European call option pricing data on the S&amp;P 500.

## Overview
For this project you will be examining European call option pricing data on the S&P 500. Recall, a European call option gives the holder the right (but not the obligation) to purchase an asset at a given time for a given price. Valuing such an option is tricky because it depends on the future value of the underlying asset.

## Data
- Value (C): Current option value
- S: Current asset value
- K: Strike price of option
- r: Annual interest rate
- tau: Time to maturity (in years)
- BS: The Black-Scholes formula was applied to this data (using some � ) to get C_pred. and If an option has C_pred – C > 0, i.e., the prediction over estimated the option value, we associate that option by (Over); otherwise, we associate that option with (Under).
