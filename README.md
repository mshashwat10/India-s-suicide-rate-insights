# TimeSeries-Forecasting - Case studies

# 1. Paperback vs Hardcover

The data set used here is Books, it has Sales data of the paperback and hardcover books. In general hardcover books are 
published first so as part of the data analysis I am building a linear regression model to identify the effect of hardcover book
sales on paperback book sales.This is useful in terms of estimating the sales for paperback books and the information can be 
used for identifying the optimal no of books to be published.


![Paperback vs Hardcover](https://user-images.githubusercontent.com/38140470/82738326-65b0d200-9cfc-11ea-9f9f-242126961db3.png)

Call:
lm(formula = Paperback ~ Hardcover, data = books)

Residuals:
    Min      1Q  Median      3Q     Max 
-70.121 -23.933   0.559  23.202  58.633 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept) 147.2852    32.8786   4.480 0.000115 ***
Hardcover     0.1967     0.1622   1.213 0.235240    
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

