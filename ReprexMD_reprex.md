---
author: trinhdhk
date: 2021-07-05
knit: "reprex::reprex_render"
output:
  reprex::reprex_document:
    advertise: no
    session_info: yes
    tidyverse_quiet: yes
title: My manuscript
---

## What reprex provide

Describe your issue very briefly here. Then show it with a minimal, self-contained example in the following R chunk.

``` r
x <- 1
y <- "2"
x + y
#> Error in x + y: non-numeric argument to binary operator
```

Inline code is working? 2
Plot will be automatically uploaded to imgur. Don’t know whether it is good or bad thing?

``` r
plot(density(rnorm(1000, 0, 1)))
```

![](https://i.imgur.com/q725DF8.png)

<details style="margin-bottom:10px;">
<summary>
Session info
</summary>

``` r
sessionInfo()
#> R version 4.1.0 (2021-05-18)
#> Platform: x86_64-apple-darwin17.0 (64-bit)
#> Running under: macOS Big Sur 10.16
#> 
#> Matrix products: default
#> BLAS:   /Library/Frameworks/R.framework/Versions/4.1/Resources/lib/libRblas.dylib
#> LAPACK: /Library/Frameworks/R.framework/Versions/4.1/Resources/lib/libRlapack.dylib
#> 
#> locale:
#> [1] en_US.UTF-8/en_US.UTF-8/en_US.UTF-8/C/en_US.UTF-8/en_US.UTF-8
#> 
#> attached base packages:
#> [1] stats     graphics  grDevices utils     datasets  methods   base     
#> 
#> loaded via a namespace (and not attached):
#>  [1] xml2_1.3.2        knitr_1.33        magrittr_2.0.1    R6_2.5.0         
#>  [5] rlang_0.4.11      fansi_0.5.0       stringr_1.4.0     styler_1.4.1     
#>  [9] highr_0.9         httr_1.4.2        tools_4.1.0       xfun_0.23        
#> [13] utf8_1.2.1        withr_2.4.2       htmltools_0.5.1.1 ellipsis_0.3.2   
#> [17] yaml_2.2.1        digest_0.6.27     tibble_3.1.2      lifecycle_1.0.0  
#> [21] crayon_1.4.1      purrr_0.3.4       vctrs_0.3.8       fs_1.5.0         
#> [25] curl_4.3.1        mime_0.10         glue_1.4.2        evaluate_0.14    
#> [29] rmarkdown_2.8     reprex_2.0.0      stringi_1.6.2     compiler_4.1.0   
#> [33] pillar_1.6.1      backports_1.2.1   pkgconfig_2.0.3
```

</details>
