---
layout: post
title:  "Explor Regression Report: 2020 Vote Republican"
date:   2021-09-13 15:58:51 -0400
categories: jekyll update
---
Determine which explanatory variables may act as consistent predictors for the 2024
US Presidential Election percentage Democrat vote.

This is a partial print out of the Exploratory Regression report generated using ArcGIS.  
Exploratory regression is a spatial statistics tool that evaluates all possible combinations
of the input candidate explanatory variables.  

It looks for Ordinary Least Squares (OLS) models that can best explain the dependent variable
within the context of user-specified criteria.

Exploratory Regression was Run with the following parameters:

Input features: CountyData_EnrichLayer
Dependent Variable: PCT_DEM
Candidate Explanatory Variables:
2016 Ave HH Income
2016 Diversity Index
2016 Population Density
Percent Seniors (Age 65+)
Percent Republican
Percent Blue Collar Workers
Percent Never Married
Percent College Degree
CDC SVI Index
Percent Vaccinations

<br>
<img src="/assets/ER_2020_PCT_Republican.png">
<br>

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
