# AU-Preston: SUEWS

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |       MAE |        MBE |        nSD |          R |        5th |       95th |     RMSE |       cRMSE |       AMBE |        1-nSD |          1-R |   nSkewness |   nKurtosis |     Overlap |
|:-------|:-------------|----------:|-----------:|-----------:|-----------:|-----------:|-----------:|---------:|------------:|-----------:|-------------:|-------------:|------------:|------------:|------------:|
| SWup   | baseline     |   7.57898 |  -7.32084  |   0.87303  |   0.994398 |   0.347449 |  18.5349   |  10.4791 |   0.160942  |   7.32084  |   0.12697    |   0.00560182 |   0.0482667 |   0.131055  |   0.0767264 |
| SWup   | detailed     |   3.12426 |  -0.275027 |   0.994333 |   0.995643 |   0.138    |   0.314875 |   4.3531 |   0.0932537 |   0.275027 |   0.00566695 |   0.00435676 |   0.010901  |   0.0392741 |   0.0579545 |
| LWup   | baseline     |   8.93627 |   7.34618  |   0.969908 |   0.982787 |  10.1476   |   5.29073  |  10.7003 |   0.185193  |   7.34618  |   0.0300924  |   0.0172134  |   0.091314  |   0.193961  |   0.133405  |
| LWup   | detailed     |   9.21888 |   7.76577  |   0.965552 |   0.982697 |  10.8586   |   5.21513  |  11.017  |   0.186014  |   7.76577  |   0.0344475  |   0.0173034  |   0.0951193 |   0.208442  |   0.139802  |
| Qle    | baseline     |  30.9433  | -10.3766   |   0.773747 |   0.392739 |  12.1719   |  30.7045   |  52.8671 |   0.995452  |  10.3766   |   0.226253   |   0.607261   |   0.724755  |   1.06377   |   0.310379  |
| Qle    | detailed     |  27.7079  | -10.5402   |   0.76017  |   0.508864 |  12.1145   |  29.1276   |  47.875  |   0.896779  |  10.5402   |   0.23983    |   0.491136   |   0.556158  |   0.579476  |   0.373367  |
| Qh     | baseline     |  76.6672  |  73.2048   |   1.2756   |   0.869867 |  42.4174   | 127.262    |  93.8687 |   0.638713  |  73.2048   |   0.275604   |   0.130133   |   0.230045  |   0.514469  |   0.477007  |
| Qh     | detailed     |  31.2034  |  -3.63201  |   0.891691 |   0.860071 |   6.40123  |  21.9452   |  47.1625 |   0.511154  |   3.63201  |   0.108309   |   0.139929   |   0.0802937 |   0.209702  |   0.202637  |
| Qtau   | baseline     | nan       | nan        | nan        | nan        | nan        | nan        | nan      | nan         | nan        | nan          | nan          | nan         | nan         | nan         |
| Qtau   | detailed     | nan       | nan        | nan        | nan        | nan        | nan        | nan      | nan         | nan        | nan          | nan          | nan         | nan         | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="datasheet"></a>Datasheet
[![SUEWS_AU-Preston_Datasheet.png](SUEWS_AU-Preston_Datasheet.png)](SUEWS_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![SUEWS_AU-Preston_Distributions.png](SUEWS_AU-Preston_Distributions.png)](SUEWS_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![SUEWS_AU-Preston_closure_baseline.png](SUEWS_AU-Preston_closure_baseline.png)](SUEWS_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![SUEWS_AU-Preston_closure_detailed.png](SUEWS_AU-Preston_closure_detailed.png)](SUEWS_AU-Preston_closure_detailed.png)

### <a name="subset_lwup"></a>subset_LWup
[![SUEWS_AU-Preston_subset_LWup.png](SUEWS_AU-Preston_subset_LWup.png)](SUEWS_AU-Preston_subset_LWup.png)

### <a name="subset_qh"></a>subset_Qh
[![SUEWS_AU-Preston_subset_Qh.png](SUEWS_AU-Preston_subset_Qh.png)](SUEWS_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![SUEWS_AU-Preston_subset_Qle.png](SUEWS_AU-Preston_subset_Qle.png)](SUEWS_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![SUEWS_AU-Preston_subset_SWup.png](SUEWS_AU-Preston_subset_SWup.png)](SUEWS_AU-Preston_subset_SWup.png)

### out of range: baseline

 - SUEWS EvapF max value of 2.0126 is greater than expected 1.0 [1]

### out of range: detailed

 - SUEWS EvapF max value of 27.5169 is greater than expected 1.0 [1]
 - SUEWS EvapF min value of -11.1926 is less than expected 0.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

