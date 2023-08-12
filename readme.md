The problem here is to predict whether a share price will show an
exceptional rise after quarterly announcement of the Earning Per
Share based on the price movement of that share price on the
proceeding 60 days?

The data was formatted by Vlad Pazenuks as part of his third year
project. Daily price data on NASDAQ 100 companies was extracted
from a Kaggle data set. Reporting dates of these companies were
obtained from NASDAQ.com. Each data is the percentage change of the
close price from the day before. Each case is a series of 60 day
data.

The target class is is defined as

0 = price did not increase after company report release by more
than 5 percent

1 = price increased after company report release by
more than 5 percent

There are 1931 cases, 1326 class 0 and 605 class 1.
