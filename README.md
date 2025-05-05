# Stock Normality Testing
This project analyzes historical stock/crypto/index price data on a user defined timeframe calculating the daily percentage change and performs the three most common normality tests to see if the data folows the normal distribution curve or not. (p.s. is most likely doesn't but your are still able to see the distribution from the histogram) 

The `Shapiro-Wilk` test checks overall normality, and the `Kolmogorov-Smirnov` test (K-S Test) checks on how the data matches normal distribution using its mean and standard deviation. A `Q-Q plot` (the last normality test) provides a visual confirmation of how well the data fits the normal distribution.
