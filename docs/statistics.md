---
authors:
    - Adnan Haideri
    - Tom Gregory
date: 2020-09-29
---

# Statistics

You should be familiar with basic statistical concepts like measures of central tendency (mean, median, mode), dispersion (standard deviation, variance), and linear regression.

## During the MSIS program
A basic understanding of statistics will be helpful in a number of courses in the MSIS program. These concepts will serve as building blocks for more advanced analytics which can be used to make strategic recommendations.

!!! note "Nice to have"
    All of these examples can be completed using Excel. Being able to use statistical tools like SPSS, MatLab, or R is a bonus.

    Once you have completed the prerequisites for [the Computer Programming module](/programming/), you are encouraged to apply these concepts in Python.

## Major concepts

You should be able to do the following:

1. Compare and contrast important measures of central tendency and dispersion.
2. For a given population sample, calculate mean, median, mode, standard deviation, and variance.
3. Define linear regression and its uses and limitations.
4. Calculate a regression line showing the relationship between two variables.

!!! note "Nice to have"
    * Be able to build regression equations given multiple independent variables.
    * Correctly apply polynomial (second-order) and logistic regression.

## Resources

1. It is important to understand _**central tendency**_ in data. [This article by Laerd Statistics][laerd statistics] is a good read for a formal definition of central tendency and its measures. It also compares these measures by application.


2. [This introductory Statistics][data statistics] course module from Khan Academy has simple examples of _**mean**_, _**median**_ and _**mode**_. _(~15 mins)_

3. [This video on Standard Deviation][standard deviation] explains central tendency with an example. Watch [this video on standard deviation][sd calculation] to learn how _**standard deviation**_ is calculated.

4. _**Dispersion**_ is a measure of how wide or narrow a bell curve is. [This Variance & Standard Deviation][dispersion] course module from Khan Academy teaches measures of dispersion in statistics. _(~25 minutes)_

5. This book provides a remarkably fun way to learn the basics of statistics:

    _Head First Statistics: A Brain-Friendly Guide, 1st Ed._, Dawn Griffiths, O'Reilly Media (2018), ISBN-13: 978-0596527587 [[Amazon]](https://www.amazon.com/Head-First-Statistics-Brain-Friendly-Guide-ebook-dp-B00B797ELQ/dp/B00B797ELQ/ref=mt_other?_encoding=UTF8&me=&qid=)

[data statistics]:https://www.khanacademy.org/math/cc-sixth-grade-math/cc-6th-data-statistics
[standard deviation]:https://www.youtube.com/watch?v=MRqtXL2WX2M
[sd calculation]:https://www.youtube.com/watch?v=WVx3MYd-Q9w
[laerd statistics]:https://statistics.laerd.com/statistical-guides/measures-central-tendency-mean-mode-median.php
[dispersion]:https://www.khanacademy.org/math/statistics-probability/summarizing-quantitative-data/variance-standard-deviation-population/v/variance-of-a-population

## Linear regression

1. _**Linear Regression**_ is a statistical method for data analysis that models a relationship between a dependent variable and one or more independent variables. It is used to either predict an unknown value (dependent variable) given a set of features (independent variables). For example, let's say we have a dataset of three variables: height (`Y`), weight (`x1`) & gender (`x2`). We can also try and predict the height of a person depending on their weight and gender.

2. Nuts & bolts of linear regression -
    * **Dependent variable (`Y`):** The unknown variable we are trying to predict the value of. It is always continuous and numerical.
    * **Independent variable (`x`):** Known variable(s) used to predict Y.
    * **Regression equation**: The mathematical equation that represents the regression model. `Y = mx + c`
    * **Simple linear regression**: Regression using a single independent variable.
    * **Multiple linear regression**: Regression using two or more independent variables.

3. It's important you to be able to do linear regression. <iframe width="560" height="315" src="https://www.youtube.com/embed/zPG4NjIkCjc" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

4. Linear regression should only be used when the use case is appropriate. [This article by Eric Benjamin Seufert][linear regression candidates] nicely explains good and bad candidates for linear regression.

5. The article ["A Refresher on Regression Analysis"][HBR] from _Harvard Business Review_ is another good read. It explains how companies use regression, and the common mistakes people make when using it.

<!-- #3 [This introduction to linear regression video][linear regression intro] is quite good. -->
[linear regression intro]:https://www.youtube.com/watch?v=zPG4NjIkCjc
[linear regression candidates]:https://mobiledevmemo.com/when-why-and-how-you-should-use-linear-regression/
[HBR]:https://hbr.org/2015/11/a-refresher-on-regression-analysis

## Practice

There are many free data sets suitable for use in learning statistics. The "Data and Story Library" has good sets for practicing [confidence intervals][data-ci] and [regression][data-slr]. If you're practicing in R, [this collection of sample datasets][data-r] originally distributed with R may prove useful.

[data-ci]:https://dasl.datadescription.com/datafiles/?_sfm_methods=Confidence%20Intervals%20for%20Means&_sfm_cases=4+59943
[data-slr]:https://dasl.datadescription.com/datafiles/?_sfm_methods=Regression&_sfm_cases=4+59943
[data-r]:https://vincentarelbundock.github.io/Rdatasets/

 If you want more interesting data sets (with no guarantee of suitability for practice), Jeremy Singer-Vine at _Data Is Plural_ publishes a [weekly newsletter](https://tinyletter.com/data-is-plural) of interesting data sets ([archive](https://docs.google.com/spreadsheets/d/1wZhPLMCHKJvwOkP4juclhjFgqIY8fQFMemwKL2c64vk/edit#gid=0)).

### Exercises

1. Use this ["Body Fat" dataset][body-fat-data]. Use "weight" as the dependent variable.

    1. Describe mean, median, and mode.
    2. Describe the standard deviation and variance. Explain what they mean.
    3. Using words, describe the bell curve for weight. Graph the bell curve; evaluate your description.
    4. Regress weight by height. What is the coefficient and y-intercept? Does the equation make sense?
    5. Regress weight by multiple variables? Which variables best predict weight? How do you decide?

[body-fat-data]:https://dasl.datadescription.com/datafile/bodyfat/?_sfm_methods=Confidence+Intervals+for+Means-+-Regression&_sfm_cases=4+59943
