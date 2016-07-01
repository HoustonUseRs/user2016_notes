# user2016_notes

Combined notes of user2016, from HRUG. This really a unorganized draft with typos, at this point.



# five thirty eight data analysis model

> ‏@andrewflowers
I'm giving a #useR2016 talk @ 2:12pm PT/5:12pm ET.



# broom:  Drob variance explained


![](https://pbs.twimg.com/media/CmI33TqUsAAmUPb.jpg:large)

[Slides from the talk](http://varianceexplained.org/files/DavidRobinsonBroomUseR2016.pdf)

# visual studio for R
![](https://pbs.twimg.com/media/CmJS-fQUYAApbXE.jpg)

# Hadley

1. tibble pkg
  - `instead of df$x use df[["x"]]`

![](https://pbs.twimg.com/media/CmIhsO5UgAA667F.jpg:large)

![](https://pbs.twimg.com/media/CmIgoWUVYAEwABO.jpg:large)

- Using bioC s4 classes in dplyr
-  different object oriented system
- Q: which system best suited for tidyverse
> S3, fits best. Because its the simplest


![](https://pbs.twimg.com/media/CmIgvzCUsAEq8ce.jpg:large)

> Being a utopian vs conservative
> little bit of short term pain is going to help you in the long run..



# superheatmap

![](https://pbs.twimg.com/media/CmOAlMWUsAAaLCg.jpg)

Rebecca Barter's new superheat #rstats package. Heatmaps on steroids! https://github.com/rlbarter/superheat/blob/master/vignettes/Vignette.Rmd



    datacamp/tutorial::go_interactive

# ggduo

> Barrett Schloerke's ggduo has function for plotting marginal dists of covariates in a linear regression

![](https://pbs.twimg.com/media/CmODXPqUgAAj4FY.jpg)
![](https://pbs.twimg.com/media/CmODdqLUsAAYCNg.jpg:large)

rbokeh


# Bookdown

[slides from Yihue Xie](https://dl.dropboxusercontent.com/u/15335397/slides/2016-useR-bookdown-Yihui-Xie.html)

# @jo_hardin47 DynamicData

> Data analysis examples for the classroom

[DynamicData](https://github.com/hardin47/DynamicData)

# @groundwalkergmb Data Science struggles

![](https://pbs.twimg.com/media/CmN-OjYVYAA7mrk.jpg)

# Deborah Nolan

> Problem with stats education: impression that "EDA is for babies, theory is for grownups" -Deborah Nolan


> "Randomize, Repeat, Reject"- Deborah Nolan suggests teaching permutation+bootstrap rather than normal theory #useR2016

> Now Deb Nolan is calling out this paper by Hesterberg on resampling. One of my favorites!

[What Teachers Should Know About the Bootstrap: Resampling in the Undergraduate Statistics Curriculum](http://www.tandfonline.com/doi/pdf/10.1080/00031305.2015.1089789)

[Nolan referencing this upsetting research on gender and TA ratings](https://www.math.upenn.edu/~pemantle/active-papers/Evals/stark2016.pdf)

> a great way to teach visualization is to show a plot and ask how can it be better?

# Daniela Witten

Not use Random Forest!

FLAM and CART.

Boosting, Random Forest and neural networks, are not interpretable.

> crisp, for more than two features

> Interpretability and cross validation.

Cross validated mean sq. errored.

> piece-wise constant.

PSA is above this, use this.


![](https://pbs.twimg.com/media/CmNh42-VEAAyeRb.jpg)

# Size of Data and its implications @szilard

[slides](https://speakerdeck.com/player/b4cad6ac716a425d93d3d1b64a7d042e?#)

- 743 for 128GB of RAM
- Data growing at 20% every year @kdnuggets

> It takes a big man to admit, his dataset is small @jcheng

## [benchm-databases](https://github.com/szilard/benchm-databases)

> sqldf, extremely FAST!
> R DT with key extremely FAST

https://github.com/szilard/benchm-R-mysql

Action                     |  RMySQL | RMySQL-dev | mysql CL | RJDBC | RODBC | dplyr
---------------------------|---------|------------|----------|-------|-------|------
Insert 1M rows [s]         |   12    |    800*    |    6     | 900*  |  800* | 10
Read 1M rows [s]           |   2.4   |     1      |    2.5   |  3.4  |  2.7  | 2.2
Insert 1 row [ms]          |    5    |     4      |          |  12** |   6   | 13**
Read 1 row [ms]            |   0.4   |    0.4     |          |   3.5 |   0.5 | 0.6

![](https://github.com/szilard/benchm-ml/raw/master/1-linear/x-plot-time.png)

![](https://github.com/szilard/benchm-ml/raw/master/1-linear/x-plot-auc.png)

![](https://github.com/szilard/benchm-ml/raw/master/1-linear/z-auc-lin-rf.png)


## Random Forest

![](https://github.com/szilard/benchm-ml/raw/master/2-rf/x-plot-time.png)

> The H2O implementation is fast, memory efficient and uses all cores. It deals with categorical variables automatically. It is also more accurate than the studied R/Python packages, which may be because of dealing properly with the categorical variables, i.e. internally in the algo rather than working from a previously 1-hot encoded dataset (where the link between the dummies belonging to the same original variable is lost).


![](https://github.com/szilard/benchm-databases/raw/master/plot.png)

## R version 3.0 to 3.1

- data.frame is much faster!

## Benchmarking

![](https://speakerdeck.com/szilard/benchmarking-machine-learning-tools-h2o-world-conference-nov-2015)

# FDA

Putting this to rest once and for all.. SAS is not required for FDA approval /cc @rdpeng #useR2016 #TheMoreYouKnow

![](https://pbs.twimg.com/media/CmJe091VEAARlQl.jpg:large)

# Shiny

The differences between Shiny apps and Shiny gadgets #UseR2016

![](https://pbs.twimg.com/media/CmN04LUUkAAGjFo.jpg)

# Daniela Witten

> Daniela Witten: # of non-zero LASSO coefs is unbiased estimate of df's used by model. Today I learned! #useR2016

![](https://pbs.twimg.com/media/CmJ1tI_VAAEMfyc.jpg)




> END
