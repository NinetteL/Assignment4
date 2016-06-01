Chicken Weights
================
Ninette Lotter
1 June 2016

Null hypothesis: no difference in weights

Alternative hypothesis: difference in weights

![](Chick_weights_files/figure-markdown_github/unnamed-chunk-1-1.png)<!-- -->

### Statistical test

Kruskal-Wallis test for unpaired non-parametric data.

Assumption:

1.  The errors are independent (the 'error' refers to the difference between each value and the median)

2.  Data are unmatched (for unpaired data) / matching is effective (for repeated measures data)

3.  Samples are drawn from populations with the same shape distributions.

<!-- -->

    ## 
    ##  Kruskal-Wallis rank sum test
    ## 
    ## data:  weight by feed
    ## Kruskal-Wallis chi-squared = 37.343, df = 5, p-value = 5.113e-07

From the results p &lt; 0.05. The p-value indicates that there is a difference between chicken weights according to feed. Therefore we can reject the null hypothesis and accept the altenative hypothesis.
