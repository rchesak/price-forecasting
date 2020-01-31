# price-forecasting
Price forecasting data science challenge, which I hacked together in a strict 3.5 day time limit.

## Quick Results Summary
The linear regression model captures 84% of the variance in regional average avocado prices across the USA (**R-squared = 0.8372**). 

On average, the selected model forecasts avocado prices within 11 cents of the true value (**mean absolute error = 0.113**, unit = USD, forecasting one week ahead).

### One-week ahead forecasts

![predicted vs. actuals, linegraph](https://i.imgur.com/h9QbABw.png)
![predicted vs. actuals, scatterplot](https://i.imgur.com/snxqMPO.png)
![error distribution](https://i.imgur.com/NdHPRvy.png)

## Presentation
See the presentation [powerpoint](https://github.com/rchesak/price-forecasting/blob/master/chesak_avocado_case_study.pptx) or [pdf](https://github.com/rchesak/price-forecasting/blob/master/chesak_avocado_case_study.pdf) for an executive overview, followed by a technical overview.

## Code
See the [exploratory data analysis](https://github.com/rchesak/price-forecasting/blob/master/exploratory-analysis.ipynb) and [modelling](https://github.com/rchesak/price-forecasting/blob/master/modelling_averageprice.ipynb) Jupyter Notebooks for hacked code. Please forgive some of the code neatness, as this was a hackathon-style project done in 3.5 days.

## Data
All data used in the challenge is located in the [/data](https://github.com/rchesak/price-forecasting/tree/master/data) directory.

The data for this challenge comes originally from the [Hass Avocado Board](https://hassavocadoboard.com/), and the sample used in this analysis was pulled from [Kaggle](https://www.kaggle.com/neuromusic/avocado-prices). 

Also included, for fun, was a sample of avocado search term data from Google Trends. See an example [here](https://trends.google.com/trends/explore?q=avocado&geo=US).