# Experimental Design Statistics Basics

This project contains notes (in notebooks) for a module I took that is based on Experimental Design Statistics.

The codes is in [R language](https://en.wikipedia.org/wiki/R_(programming_language)) ([install guide here](https://courses.edx.org/courses/UTAustinX/UT.7.01x/3T2014/56c5437b88fa43cf828bff5371c6a924/)).

To setup R language in Jupyter notebook, [read here](https://developers.refinitiv.com/en/article-catalog/article/setup-jupyter-notebook-r).

### Interpreting the plots

1. For the **Residuals vs Fitted**, the straighter the line, the lesser errors, we can question the linearly or the constant of variance or independence.
2. For the **Scale-Location**, if there is a more linear trend decreasing or increasing, there can be errors same as Residuals vs Fitted.
3. For the **Normal Q-Q**, the more outliers the more errors, we can question the normality.
4. For the **Constant Leverage**, if there are more than `1` or `-1`, there are more outliers that are inferential can cause problems.
5. For the **Cook's distance**, if it is larger than `0.25`, there are inferential problem (same as Constant Leverage).
6. For the **Histogram**, if the histogram isn't shaped as a bell-curve or  symmetric about the mean, its normality can be questioned.
7. If the interaction graphs are not parallel or crosses each other, there are interactions.
