長庚大學 大數據分析方法 作業二
================

數值變數運算
------------

``` r
num1<-3561;
num2<-5815;

num1+num2;
```

    ## [1] 9376

``` r
num1-num2;
```

    ## [1] -2254

``` r
num1*num2;
```

    ## [1] 20707215

``` r
round(num1/num2, digits=2);
```

    ## [1] 0.61

檢查總覽資料
------------

``` r
?iris;
```

    ## starting httpd help server ...

    ##  done

輸出系統現在日期
----------------

``` r
Sys.Date();
```

    ## [1] "2017-03-10"

字串比大小
----------

``` r
"A">"a";
```

    ## [1] TRUE

``` r
"b">"A";
```

    ## [1] TRUE

運作環境資訊擷取
----------------

``` r
sessionInfo();
```

    ## R version 3.3.2 (2016-10-31)
    ## Platform: x86_64-w64-mingw32/x64 (64-bit)
    ## Running under: Windows 10 x64 (build 14393)
    ## 
    ## locale:
    ## [1] LC_COLLATE=English_United States.1252 
    ## [2] LC_CTYPE=English_United States.1252   
    ## [3] LC_MONETARY=English_United States.1252
    ## [4] LC_NUMERIC=C                          
    ## [5] LC_TIME=English_United States.1252    
    ## 
    ## attached base packages:
    ## [1] stats     graphics  grDevices utils     datasets  methods   base     
    ## 
    ## loaded via a namespace (and not attached):
    ##  [1] backports_1.0.5 magrittr_1.5    rprojroot_1.2   tools_3.3.2    
    ##  [5] htmltools_0.3.5 yaml_2.1.14     Rcpp_0.12.9     stringi_1.1.2  
    ##  [9] rmarkdown_1.3   knitr_1.15.1    stringr_1.2.0   digest_0.6.12  
    ## [13] evaluate_0.10
