---
title: 'Basic statistics'
output:
  bookdown::tufte_html2
---



# (PART) Analysis {-}


# Basic inferential statistics


R has simple functions for common inferential statistics like Chi^2^, t-tests, correlations and many more. This section is by no means exhaustive, but covers [statistics for crosstabulations](#crosstabs), [differences in means](#t-tests), and [linear correlation](#correlations).

For non-parametric statistics [this page on the statmethods site](http://www.statmethods.net/stats/nonparametric.html) is a useful guide.

The [`coin::` package](http://finzi.psych.upenn.edu/R/library/coin/doc/coin.pdf) implements many resampling tests, which can be useful when assumptions of parametric tests are not valid. [See this intro to resampling statistics](http://www.statmethods.net/stats/resampling.html). 
