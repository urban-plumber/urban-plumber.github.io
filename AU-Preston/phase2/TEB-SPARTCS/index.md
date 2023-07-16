# AU-Preston: TEB-SPARTCS

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](TEB-SPARTCS_AU-Preston_baseline_attrs.md)
- [Detailed](TEB-SPARTCS_AU-Preston_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |       MBE |      nSD |        R |        5th |       95th |      RMSE |    cRMSE |      AMBE |     1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|----------:|----------:|---------:|---------:|-----------:|-----------:|----------:|---------:|----------:|----------:|-----------:|------------:|------------:|----------:|
| SWup   | baseline     |  9.11177  | -9.03713  | 0.843735 | 0.995369 |  1.24082   |  22.7889   | 12.3142   | 0.179535 |  9.03713  | 0.156264  | 0.00463066 | 0.000348123 |   0.0199314 | 0.0880492 |
| SWup   | detailed     |  3.56364  | -0.783722 | 0.97734  | 0.994815 |  1.12197   |   3.53818  |  4.87138  | 0.103193 |  0.783722 | 0.02266   | 0.0051851  | 0.0625728   |   0.0927068 | 0.0787525 |
| LWup   | baseline     | 18.7361   | 12.0559   | 1.49298  | 0.965108 |  8.67511   |  63.2796   | 27.5429   | 0.589246 | 12.0559   | 0.492973  | 0.0348921  | 0.139646    |   0.140722  | 0.122051  |
| LWup   | detailed     | 13.4875   | 13.4295   | 1.08753  | 0.990488 |  8.43034   |  21.5302   | 15.1798   | 0.168378 | 13.4295   | 0.0875327 | 0.0095119  | 0.0082362   |   0.0847308 | 0.142015  |
| Qle    | baseline     | 26.1987   | -9.92881  | 0.724857 | 0.484181 |  9.72236   |  36.5518   | 45.4023   | 0.907465 |  9.92881  | 0.275144  | 0.515819   | 0.759094    |   1.29945   | 0.267733  |
| Qle    | detailed     | 24.73     | -1.31702  | 0.851922 | 0.593936 |  5.55242   |  13.5949   | 41.2681   | 0.844865 |  1.31702  | 0.148079  | 0.406064   | 0.280375    |   0.160978  | 0.0811201 |
| Qh     | baseline     | 37.8213   | 33.8019   | 1.34388  | 0.94627  | 21.0887    | 122.235    | 57.921    | 0.512512 | 33.8019   | 0.343883  | 0.0537299  | 0.0411401   |   0.0325104 | 0.289252  |
| Qh     | detailed     | 22.7532   |  6.74892  | 1.0675   | 0.936093 |  1.91456   |  25.4882   | 35.1149   | 0.375494 |  6.74892  | 0.0674958 | 0.0639068  | 0.0754295   |   0.169251  | 0.148263  |
| Qtau   | baseline     |  0.198855 |  0.174408 | 1.31026  | 0.870675 |  0.0296658 |   0.35012  |  0.26853  | 0.659669 |  0.174408 | 0.310266  | 0.129325   | 0.196961    |   0.347501  | 0.231811  |
| Qtau   | detailed     |  0.379482 |  0.367825 | 1.97537  | 0.835512 |  0.0192404 |   0.955909 |  0.537303 | 1.26538  |  0.367825 | 0.975372  | 0.164488   | 0.261487    |   0.488975  | 0.317509  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![TEB-SPARTCS_AU-Preston_subset_SWup_v0-9.png](TEB-SPARTCS_AU-Preston_subset_SWup_v0-9.png)](TEB-SPARTCS_AU-Preston_subset_SWup_v0-9.png)

### out of range: baseline

 - TEB-SPARTCS Qh max value of 604.0351 is greater than expected 600.0 [W/m2]

### out of range: detailed



[Link to variable definitions](../modelattrs/variable_definitions.md)

