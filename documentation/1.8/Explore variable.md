---
layout: documentation
title:  "Explore variable"
section_id: get_help
---
{% include_relative toc.md %}

# Explore variable
From the `Analysis` menu choose `Explore variable`, and choose the variable(s) you want to analyze, then hit OK.

* Optionally, uncheck the Frequencies, if you want to skip that analysis.
* Optionally, change the central tendency value, if your hypothesis is a different value.

The following values and graphs will be displayed (see also the [common elements of the results](Common-elements-of-the-analysis-results)):

## Raw data
* Number of valid and missing cases
* Raw data on a [dot plot](https://en.wikipedia.org/wiki/Dot_plot_(statistics))

## Sample properties
Extended and reorganized in v1.7

|For interval data|For ordinal data|For nominal data
|-----|------|-----
|Frequencies<br>Table of all values in the variable with the following details:<br>* Value<br>* Frequency<br>* Relative frequency (percentage of that value of all cases)<br>* Cumulative frequency<br>* Cumulative relative frequency|Frequencies<br>Table of all values in the variable with the following details:<br>* Value<br>* Frequency<br>* Relative frequency (percentage of that value of all cases)<br>* Cumulative frequency<br>* Cumulative relative frequency|Frequencies<br>Table of all values in the variable with the following details:<br>* Value<br>* Frequency<br>* Relative frequency (percentage of that value of all cases)
|Descriptive statistics:<br>Mean<br>[Standard deviation](Differences-in-calculations-between-CogStat-and-other-programs#standard-deviation-of-the-sample)<br>[Skewness](https://en.wikipedia.org/wiki/Skewness)<br>[Kurtosis](https://en.wikipedia.org/wiki/Kurtosis)<br>[Range](https://en.wikipedia.org/wiki/Range_(statistics))<br>Maximum<br>[Upper quartile](https://en.wikipedia.org/wiki/Quartile)<br>[Median](https://en.wikipedia.org/wiki/Median)<br>Lower quartile<br>Minimum|Descriptive statistics:<br>Maximum<br>[Upper quartile](https://en.wikipedia.org/wiki/Quartile)<br>[Median](https://en.wikipedia.org/wiki/Median)<br>Lower quartile<br>Minimum|
Combined graph of histogram, individual data on x axes and [box plot](Box-plots)|Combined graph of histogram, individual data on x axes and [box plot](Box-plots) of [the order of the values](Displaying-ordinal-and-nominal-data)|[Histogram](https://en.wikipedia.org/wiki/Histogram)

## Population properties
### Normality
Only for interval variables.
* [Shapiro-Wilk test](https://en.wikipedia.org/wiki/Shapiro%E2%80%93Wilk_test)
* Histogram with normal distribution (normal distribution has the same average and standard deviation as the data)
* [Q-Q plot](https://en.wikipedia.org/wiki/Q%E2%80%93Q_plot)

### Testing [central tendency](https://en.wikipedia.org/wiki/Central_tendency)
Only for interval and ordinal variables.

For normal interval data|For ordinal data and for non-normal interval data
-----|------
[One-sample t-test](https://en.wikipedia.org/wiki/Student%27s_t-test#One-sample_t-test)|[Wilcoxon signed-rank test](https://en.wikipedia.org/wiki/Wilcoxon_signed-rank_test) (see [CogStat specific](Differences-in-calculations-between-CogStat-and-other-programs#wilcoxon-signed-rank-test) details)
Mean and confidence interval|Median
Graph with mean and confidence interval|Graph with median
