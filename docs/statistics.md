---
authors:
    - Adnan Haideri
    - Tom Gregory
date: 2020-09-29
---

# Statistics

You should be familiar with basic statistical concepts like measures of central tendency (mean, median, mode), dispersion (standard deviation, variance), and linear regression.

## During the MSIS program
A basic understanding of statistics will be helpful in a number of courses in the MSIS program. In the Data Analytics module, these concepts will serve as building blocks for you to drive analytics on raw data and glean powerful insights which can in turn be used to make strategic recommendations in business presentations.

!!! note "Nice to have"
    All of these examples can be completed using Excel. Being able to use statistical tools like SPSS, MatLab, or R is a bonus.

    Once you have completed the prerequisites for [Computer Programming](/programming/), you are encouraged to apply these concepts in Python.

## Major concepts

Before entering the MSIS program, you should be able to do the following:

1. Compare and contrast important measures of central tendency and dispersion.
2. For a given population sample, calculate mean, median, mode, standard deviation, and variance.
3. Define linear regression and its uses and limitations
4. Calculate a regression line showing the relationship between two variables.

!!! note "Nice to have"
    * Be able to build regression equations given multiple independent variables.
    * Correctly apply polynomial (second-order) and logistic regression.

## Resources

1. A nice way to get started would be to understand the idea of central tendency in data. [This article by Laerd Statistics][laerd statistics] is a good read for a formal definition of central tendency and its measures. It also compares these measures by application.

2. [This Data Statistics Intro][data statistics] course module from Khan Academy has simple examples on mean, median and mode. _(~15 mins)_

3. Next, you can watch [this Standard Deviation video][standard deviation] that explains the concept with an example. You can also watch [this video][sd calculation] to learn how it is calculated.

4. Lastly,  [this Variance & Standard Deviation][dispersion] course module on Khan Academy teaches measures of dispersion in statistics. _(~25 minutes)_

5. This book provides a remarkably fun way to learn the basics of statistics:

    _Head First Statistics: A Brain-Friendly Guide, 1st Ed._, Dawn Griffiths, O'Reilly Media (2018), ISBN-13: 978-0596527587 [[Amazon]](https://www.amazon.com/Head-First-Statistics-Brain-Friendly-Guide-ebook-dp-B00B797ELQ/dp/B00B797ELQ/ref=mt_other?_encoding=UTF8&me=&qid=)

[data statistics]:https://www.khanacademy.org/math/cc-sixth-grade-math/cc-6th-data-statistics
[standard deviation]:https://www.youtube.com/watch?v=MRqtXL2WX2M
[sd calculation]:https://www.youtube.com/watch?v=WVx3MYd-Q9w
[laerd statistics]:https://statistics.laerd.com/statistical-guides/measures-central-tendency-mean-mode-median.php
[dispersion]:https://www.khanacademy.org/math/statistics-probability/summarizing-quantitative-data/variance-standard-deviation-population/v/variance-of-a-population

## Linear regression

1. Linear Regression is a statistical method for data analysis that models a relationship between a dependent variable and one or more independent variables. It is used to either predict an unknown value (dependent variable) given a set of features (independent variables). For example, let's say we have a dataset of three variables: height (`Y`), weight (`x1`) & gender (`x2`). We can also try and predict the height of a person depending on their weight and gender.

2. Nuts & bolts of linear regression -
    * **Dependent variable (`Y`)** - unknown variable we are trying to predict the value of. It is always continuous and numerical.
    * **Independent variable (`x`)** - known variable/feature that will be used to predict Y.
    * **Regression equation** - mathematical equation that represents the regression model. (`Y = mx + c`)
    * **Simple linear regression** - regression between a dependent variable and a single independent variable.
    * **Multiple linear regression** - regression between a dependent variable and two or more independent variables.

3. If the explanation in above is not clear enough, watch [this introduction to linear regression video][linear regression intro].

4. Linear regression should only be used when the use case is appropriate. [This article by Eric Benjamin Seufert][linear regression candidates] nicely explains good and bad candidates for linear regression.

5. The article ["A Refresher on Regression Analysis"][HBR] from _Harvard Business Review_ is another good read on regression analysis. It also talks about how companies use regression and common mistakes people make when using it.
[jupyter notebook]:https://jupyter.org/
[python]:https://www.python.org/about/
[linear regression intro]:https://www.youtube.com/watch?v=zPG4NjIkCjc
[linear regression candidates]:https://mobiledevmemo.com/when-why-and-how-you-should-use-linear-regression/
[HBR]:https://hbr.org/2015/11/a-refresher-on-regression-analysis

## Practice

There are many free data sets suitable for use in learning statistics the Data and Story Library has good sets for practicing [confidence intervals][data-ci] and [regression][data-slr]. If you're practicing in R, [this collection of sample datasets][data-r] originally distributed with R may prove useful.

[data-ci]:https://dasl.datadescription.com/datafiles/?_sfm_methods=Confidence%20Intervals%20for%20Means&_sfm_cases=4+59943
[data-slr]:https://dasl.datadescription.com/datafiles/?_sfm_methods=Regression&_sfm_cases=4+59943
[data-r]:https://vincentarelbundock.github.io/Rdatasets/

 If you want more interesting data sets (with no guarantee of suitability for practice), Jeremy Singer-Vine at _Data Is Plural_ publishes a [weekly newsletter](https://tinyletter.com/data-is-plural) of interesting data sets ([archive](https://docs.google.com/spreadsheets/d/1wZhPLMCHKJvwOkP4juclhjFgqIY8fQFMemwKL2c64vk/edit#gid=0)).
