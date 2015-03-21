---
title       : Regression Model Analyser
subtitle    : An app to help you build linear regression models
author      : Fabio M. R. Amaral
job         : Developing Data Products (Johns Hopkins - Coursera)
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Regression Model Analyser

</br>
#### An app to help you build linear regression models
 
* Developed to automate the process of creating linear regression models.
* Analysis is done in R language without having to know any programming.
* Each step in the regression modelling can be accessed by simple tab toggles.
</br>

#### App Features in Tabs

* Selection of data sets (including data set uploaded by user)
* The Correlation Matrix Plot
* Model Summary
* Diagnostic Plots
* Visualization of the raw data

http://fredus.shinyapps.io/RegApp


--- &twocol w1:30% w2:70%

## Correlation Matrix Plot

</br>

*** =left
</br>
* Uses package ``PerformanceAnalytics``.
* Helps identify the most relevant variables.
* Scatter plots of all variable combinations.
* Distribution histograms of all variables.
* Correlation coefficients with respective significance indicator (font size and stars).
* Help the identification collinearity of regressors/predictors.
</br>
</br>
</br>
http://fredus.shinyapps.io/RegApp

*** =right
![Scatter plot correlation matrix.](assets/fig/unnamed-chunk-1-1.png) 


--- &twocol w1:20% w2:80%

## Model Summary

</br>
</br>
</br>

*** =left

- Select the data set
- Select the desired outcome variable 
- Select the desired predictor variables
- Toggle to the ``Model Summary`` tab to see details such as residuals and coefficients summaries.

</br>
</br>
</br>
http://fredus.shinyapps.io/RegApp


*** =right
<img src="images/summary.png" align="middle" width=490>


--- &twocol w1:20% w2:80%

## Diagnostic Plots


*** =left

</br>
</br>

- Toggle to ``Diagnostic Plots`` tab.
- These plots help to assess the fit of the model generated as well as the patern of residuals (normality, scedastcity, influential points, etc). 

</br>
</br>
``Thank you`` for assessing the app. 
</br>
Hope it will be as useful as was fun to make it!

</br>
http://fredus.shinyapps.io/RegApp




*** =right

![Residual Plot Analysis and Diagnostics](assets/fig/unnamed-chunk-2-1.png) 



