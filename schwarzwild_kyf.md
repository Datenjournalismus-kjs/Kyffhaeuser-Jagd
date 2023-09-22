Schwarzwild KYF
================

    ##   Bezeichnung Jagdstrecke
    ## 1      Keiler         128
    ## 2      Bachen          72
    ## 3  Überläufer         899
    ## 4 Frischlinge         683

$$
\sum Jagdstrecke
$$

    ## Gesamtstrecke

    ## [1] 1782

``` r
library(ggplot2)
ggplot(d7, aes(Bezeichnung, Jagdstrecke)) +
  geom_point(shape = 21, size = 3, fill = "lightgreen") 
```

![](schwarzwild_kyf_files/figure-gfm/unnamed-chunk-3-1.png)<!-- -->

``` r
boxplot(d7$Jagdstrecke, col="lightgreen")
```

![](schwarzwild_kyf_files/figure-gfm/unnamed-chunk-4-1.png)<!-- -->
