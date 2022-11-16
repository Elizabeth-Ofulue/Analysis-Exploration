# Diamonds Data Exploration

## Dataset

The data consists of information regarding 54,000 round-cut diamonds, including
price, carat, and other diamond qualities. The dataset can be found in the
repository for R's ggplot2 library [here](https://github.com/tidyverse/ggplot2/blob/master/data-raw/diamonds.csv),
with feature documentation available [here](http://ggplot2.tidyverse.org/reference/diamonds.html).


## Summary of Findings

There was a strong relationship between the price of a diamond and its carat weight, with modifying effects from the cut, color, and clarity grades given to the diamond. This relationship is approximately linear between price and carat when price is transformed to be on a logarithmic scale and carat transformed to be on a cube-root scale. 

Based on the marginal trend for the cut, color, and clarity, higher diamond quality were associated with lower prices. However, they were also associated with smaller diamonds. After isolating diamonds of a single carat weight, there was a clear positive relationship between higher diamond quality and higher diamond price.

Besides the main variables of interest, I verified the relationship between diamond carat weight and its x, y, and z dimensions. For the dataset given, there was an interesting interaction in the categorical diamond quality features. The lower clarity grades looked like they had slightly better distribution of cut and color grades than diamonds with the higher clarity grades.


## Key Insights

For this project, the focus is on the influence of the four Cs of diamonds, leaving out most of the intermediate derivations. I start by introducing the price variable, followed by the pattern in carat distribution, then plot the transformed scatterplot. Afterwards, the categorical variables are introduced one after the other. 

The violin plots of price and carat across clarity is the clearest example of how the categorical quality grades affect diamond pricing. The other two categorical variables, cut and color, are covered afterwards, using point plots. Different color palettes are used for each quality variable to ensure it a distinction between plots.
