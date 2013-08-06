---
title       : 
subtitle    : 
author      : 
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
---

## Read-And-Delete

1. Edit YAML front matter
2. Write using R Markdown
3. Use an empty line followed by three dashes to separate slides!

--- .class #id 

## Slide 2

- test
  - indent
  
[hyperlink](www.google.com)

  
---

some r code 

```r
str(Theoph)
```

```
## Classes 'nfnGroupedData', 'nfGroupedData', 'groupedData' and 'data.frame':	132 obs. of  5 variables:
##  $ Subject: Ord.factor w/ 12 levels "6"<"7"<"8"<"11"<..: 11 11 11 11 11 11 11 11 11 11 ...
##  $ Wt     : num  79.6 79.6 79.6 79.6 79.6 79.6 79.6 79.6 79.6 79.6 ...
##  $ Dose   : num  4.02 4.02 4.02 4.02 4.02 4.02 4.02 4.02 4.02 4.02 ...
##  $ Time   : num  0 0.25 0.57 1.12 2.02 ...
##  $ conc   : num  0.74 2.84 6.57 10.5 9.66 8.58 8.36 7.47 6.89 5.94 ...
##  - attr(*, "formula")=Class 'formula' length 3 conc ~ Time | Subject
##   .. ..- attr(*, ".Environment")=<environment: R_EmptyEnv> 
##  - attr(*, "labels")=List of 2
##   ..$ x: chr "Time since drug administration"
##   ..$ y: chr "Theophylline concentration in serum"
##  - attr(*, "units")=List of 2
##   ..$ x: chr "(hr)"
##   ..$ y: chr "(mg/l)"
```





