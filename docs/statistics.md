---
authors:
    - Adnan Haideri
    - Tom Gregory
date: 2020-09-29
updated: 2021-02-02
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
2. For a given population sample, calculate mean ($\bar{x}$), median, mode, standard deviation ($s$), and variance ($v$).
3. Define linear regression. Describe its uses and limitations.
4. Calculate a regression line showing the relationship between two variables.

!!! note "Nice to have"
    * Be able to build regression equations given multiple independent variables.
    * Correctly apply polynomial (second-order) and logistic regression.

## Resources

1. It is important to understand _**central tendency**_ in data. [This article by Laerd Statistics][laerd statistics] is a good read for a formal definition of central tendency and its measures. It also compares these measures by application.

2. [This introductory Statistics][data statistics] course module from Khan Academy has simple examples of _**mean**_, _**median**_ and _**mode**_. _(~15 mins)_

3. [This video on Standard Deviation][standard deviation] explains central tendency with an example. Watch [this video on standard deviation][sd calculation] to learn how _**standard deviation**_ is calculated.

4. _**Dispersion**_ is a measure of how wide or narrow a bell curve is, and is communicated using _**variance*_ or _**standard deviation**_. [This Variance & Standard Deviation][dispersion] course module from Khan Academy teaches measures of dispersion in statistics. _(~25 minutes)_

5. The free online course ["Introduction to Statistics"][intro-stats] is an excellent resource.

6. This book provides a remarkably fun way to learn the basics of statistics:

    _Head First Statistics: A Brain-Friendly Guide, 1st Ed._, Dawn Griffiths, O'Reilly Media (2018), ISBN-13: 978-0596527587 [[Amazon]](https://www.amazon.com/Head-First-Statistics-Brain-Friendly-Guide-ebook-dp-B00B797ELQ/dp/B00B797ELQ/ref=mt_other?_encoding=UTF8&me=&qid=)

[data statistics]:https://www.khanacademy.org/math/cc-sixth-grade-math/cc-6th-data-statistics
[standard deviation]:https://www.youtube.com/watch?v=MRqtXL2WX2M
[sd calculation]:https://www.youtube.com/watch?v=WVx3MYd-Q9w
[laerd statistics]:https://statistics.laerd.com/statistical-guides/measures-central-tendency-mean-mode-median.php
[dispersion]:https://www.khanacademy.org/math/statistics-probability/summarizing-quantitative-data/variance-standard-deviation-population/v/variance-of-a-population
[intro-stats]:https://courses.lumenlearning.com/suny-fmcc-introstats1/

## Linear regression

1. _**Linear Regression**_ is a statistical method for data analysis that models a relationship between a dependent variable and one or more independent variables. It is used to either predict an unknown value (dependent variable) given a set of features (independent variables).

For example, let's say we have a dataset of three variables: height, weight, and gender. We could try to predict weight based on height and gender, or we could try to predict height based on the remaining variables.

2. Nuts & bolts of linear regression -
    * **Dependent variable ($\hat{y}$):** The unknown variable we are trying to predict the value of. It is always _continuous_ and numerical.
    * **Independent variable ($x$):** Known variable(s) used to predict $\hat{y}$.
    * **Regression equation**: The mathematical equation that represents the regression model $\hat{y} = a + bx$ (for simple linear regression), where $a$ is the y-intercept and $b$ is the slope (also call "correlation coefficient").
    * **Simple linear regression**: Regression using a single independent variable.
    * **Multiple linear regression**: Regression using two or more independent variables.

3. It's important you to be able to do linear regression. <iframe width="560" height="315" src="https://www.youtube.com/embed/zPG4NjIkCjc" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

4. Linear regression should only be used when the use case is appropriate. [This article by Eric Benjamin Seufert][linear regression candidates] nicely explains good and bad candidates for linear regression.

5. The article ["A Refresher on Regression Analysis"][HBR] from _Harvard Business Review_ is another good read. It explains how companies use regression, and the common mistakes people make when using it.

[linear regression candidates]:https://mobiledevmemo.com/when-why-and-how-you-should-use-linear-regression/
[HBR]:https://hbr.org/2015/11/a-refresher-on-regression-analysis

## Practice

There are many free data sets suitable for use in learning statistics. The "Data and Story Library" has good sets for practicing [confidence intervals][data-ci] and [regression][data-slr]. If you're practicing in R, [this collection of sample datasets][data-r] originally distributed with R may prove useful.

[data-ci]:https://dasl.datadescription.com/datafiles/?_sfm_methods=Confidence%20Intervals%20for%20Means&_sfm_cases=4+59943
[data-slr]:https://dasl.datadescription.com/datafiles/?_sfm_methods=Regression&_sfm_cases=4+59943
[data-r]:https://vincentarelbundock.github.io/Rdatasets/

 If you want more interesting data sets (with no guarantee of suitability for practice), Jeremy Singer-Vine at _Data Is Plural_ publishes a [weekly newsletter](https://tinyletter.com/data-is-plural) of interesting data sets ([archive](https://docs.google.com/spreadsheets/d/1wZhPLMCHKJvwOkP4juclhjFgqIY8fQFMemwKL2c64vk/edit#gid=0)).

 First, try the exercises below using Excel. Then try the same exercises using some other statistical or programming tool, like SPSS, R or Python.

### Exercises

1. In a normal distribution, what percent of the sample population is within one standard deviation of the mean? What percent is within two standard deviations? Three?
  <details class="example">
  <summary>Answer</summary>
    <p>For data having a <strong>symmetric</strong>, <strong>normal</strong> distribution:
    <ul>
      <li>Approximately 68% of the data is within one standard deviation of the mean</li>
      <li>Approximately 95% of the data is within two standard deviations of the mean</li>
      <li>More than 99% of the data is within three standard deviations of the mean</li>
    </ul>
    </p>
    <p>For skewed data, the percentages are different, but are still within boundaries described by <em>Chebyshev's Rule</em></p>
  </details>

2. Use [this "Body Fat" dataset][body-fat-data]. Use _weight_ as the dependent variable.

    1. Describe the mean, median, and mode for _weight_.
       <details class="example">
       <summary>Answer</summary>
       <p>**Hint:** Use the [Analysis ToolPak Add-in](https://www.excel-easy.com/data-analysis/analysis-toolpak.html) to quickly get descriptive statistics in Excel.</p>
       <div class="md-typeset__scrollwrap"><div class="md-typeset__table"><table>
       <thead>
         <tr>
           <th>Statistic</th>
           <th align="right">Value</th>
         </tr>
       </thead>
       <tbody>
         <tr>
           <td>Mean</td>
           <td align="right">178.1</td>
         </tr>
         <tr>
           <td>Median</td>
           <td align="right">176.1 </td>
         </tr>
         <tr>
           <td>Mode</td>
           <td align="right">184.25</td>
         </tr>
         <tr>
           <td>Std Dev</td>
           <td align="right">27.1</td>
         </tr>
         <tr>
           <td>Std Variance</td>
           <td align="right">730.9</td>
         </tr>
         <tr>
           <td>Count</td>
           <td align="right">250 </td>
         </tr>
       </tbody>
       </table></div></div>
       </details>
    2. Describe the standard deviation ($s$) and variance ($v$) of _weight_. Explain what they mean. What is the relationship between standard deviation and variance?
    3. What are the Excel functions to calculate population standard deviation ($\sigma$) and sample standard deviation ($s$)?
    3. Using words, describe the bell curve for _weight_. Graph the bell curve; evaluate your description.
    <details class="example">
    <summary>Answer</summary>
    ![alt text](/images/histogram1.png "Histogram of weight")
    </details>
    4. Regress _weight_ by _height_. What is the coefficient and y-intercept? Does the equation make sense?
    <details class="example">
    <summary>Answer</summary>
    ![alt text](/images/regression1.png "Graph of the regression between height and weight")
    <p>**Coefficient of height:** 5.3 _(In other words, every inch of height typically adds about 5.3 pounds.)_<br>
      **Intercept:** -194.4861343<br>
      **Full equation:** $predicted\ weight = 5.3*height - 194.5$<br>
      **$R^2$:** 0.263 _(This equation explains only about 26% of the variance in weight.)_</p>
    </details>
    5. **OPTIONAL:** Regress _weight_ by multiple variables. Which variables best predict weight? How do you decide?

[body-fat-data]:https://dasl.datadescription.com/datafile/bodyfat/?_sfm_methods=Confidence+Intervals+for+Means-+-Regression&_sfm_cases=4+59943

<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-chtml.js"></script>
