# COVID19 Country-by-Country Metric Comparison

This Mathematica code will read COVID-19 time series data from Johns Hopkins University Center for Systems Science and Engineering's GitHub page and generate an mp4 movie file that animates how each country's trajectory in the *number of cases* vs. *number of deaths* metric space evolves over time. The numbers are normalized per 100,000 people.

Examples can be seen in the following:

* Last 200 days: https://twitter.com/HirokiSayama/status/1479809946476810243
* Entire pandemic since early 2020: https://twitter.com/HirokiSayama/status/1477007655508094980

Data was smoothed using seven-day moving averages and B-spline smoothing functions.
