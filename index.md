---
title       : Tooth growth and Vitamin C
subtitle    : Supplementing Vitamin C for tooth growth in guinea pigs
author      : Hl
job         : Dev
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## What?
Let's talk about

- Why? Is there a demand for this application?
- How? How we developed our model.
- When?

---

## Why?

- Guinea pigs use their teeth a lot
- Teeth gets worn out
- Therefor a healthy teeth growth is necessary to sustain their teeth usage

---

## Slide The model

Building a linear model, showing correlation between Vitamin C and teeth growth




```r
model <- lm(len ~ ., data=ToothGrowth)
print(model)
```

```
## 
## Call:
## lm(formula = len ~ ., data = ToothGrowth)
## 
## Coefficients:
## (Intercept)       suppVC         dose  
##       9.272       -3.700        9.764
```

---

## Slide Available today!

Simple to use web application

[https://lohmander.shinyapps.io/Tooth_Growth_Prediction](https://lohmander.shinyapps.io/Tooth_Growth_Prediction)


