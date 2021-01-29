# times_series_forecasting_using_fbprophet

Time series forecasting is an important area of machine learning that is often neglected.

It is important because there are so many prediction problems that involve a time component and these problems are often neglected because it is this time component that makes time series problems more difficult to handle.

Before getting started with Time Series Analysis, let’s get our basics clear on Anomaly Detection

WHAT IS TIME SERIES ANALYSIS?

Time Series is a set of observations taken at a specified time usually at equal intervals. It is used to predict future values based on previous observed values.

Considering a graph, where ‘x’ is time & if the dependent variable ‘y’ depends on time parameter then it’s called as a time series.

PROPHET:

Facebook developed an open sourcing Prophet, a forecasting tool available in both Python and R. It provides intuitive parameters which are easy to tune. Even someone who lacks deep expertise in time-series forecasting models can use this to generate meaningful predictions for a variety of problems in business scenarios.

Highlights of Facebook Prophet

Very fast, since it’s built in Stan, a programming language for statistical inference written in C++.
An additive regression model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects: 1. A piecewise linear or logistic growth curve trend. Prophet automatically detects changes in trends by selecting changepoints from the data 2. A yearly seasonal component modeled using Fourier series 3. A weekly seasonal component using dummy variables 4. A user-provided list of important holidays.
Robust to missing data and shifts in the trend, and typically handles outliers .
Easy procedure to tweak and adjust forecast while adding domain knowledge or business insights.

When fbProphet shines?

Hourly, Weekly, Daily observations with at least a few months of history.
Strong multiple “human-scale” seasonality’s
Holidays that occur at irregular intervals
Reasonable number of missing observations
