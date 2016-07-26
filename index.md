---
title       : Next word predictor
subtitle    : Capstone Project - Coursera Data Science Specialization
author      : Pratigya Subedi
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Objective
* The main objective of this project is to build a working predictive model. For that we analyze a large      corpus data set provided by swiftkey.
* Demonstrate the model through Shiny App

---

## Process
* Random Sampling of the corpus

* datacleaning by removing numbers unnecessary words,stemming, removal of html tags, emails, punctuations     white space etc.

* N-gram tokens were created for the data sample

* The N-gram tables are used to perform predictive analysis for the user inputs


---

## Next Word Predictor app

The shiny app is avaliable at : https://pratsubedi.shinyapps.io/WordPredicting/

![Next word Predictor](Capture.JPG)
* It has a simple UI that takes user inputs for the next word prediction.



---
