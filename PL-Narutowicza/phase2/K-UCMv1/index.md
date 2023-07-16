# PL-Narutowicza: K-UCMv1

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](K-UCMv1_PL-Narutowicza_baseline_attrs.md)
- [Detailed](K-UCMv1_PL-Narutowicza_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |       MBE |        nSD |          R |      5th |     95th |     RMSE |      cRMSE |      AMBE |       1-nSD |         1-R |   nSkewness |   nKurtosis |     Overlap |
|:-------|:-------------|----------:|----------:|-----------:|-----------:|---------:|---------:|---------:|-----------:|----------:|------------:|------------:|------------:|------------:|------------:|
| SWup   | baseline     | nan       | nan       | nan        | nan        | nan      | nan      | nan      | nan        | nan       | nan         | nan         |  nan        |  nan        | nan         |
| SWup   | detailed     |   8.05997 |  -7.07373 |   0.806726 |   0.863844 |   0.1473 |   8.5425 |  13.0365 |   0.506988 |   7.07373 |   0.193274  |   0.136156  |    0.448801 |    0.322211 |   0.158203  |
| LWup   | baseline     | nan       | nan       | nan        | nan        | nan      | nan      | nan      | nan        | nan       | nan         | nan         |  nan        |  nan        | nan         |
| LWup   | detailed     |  15.6165  |  10.0099  |   1.00488  |   0.94377  |  10.0366 |   2.1722 |  21.9682 |   0.336205 |  10.0099  |   0.0048855 |   0.0562303 |    3.3659   |  224.228    |   0.0880149 |
| Qle    | baseline     | nan       | nan       | nan        | nan        | nan      | nan      | nan      | nan        | nan       | nan         | nan         |  nan        |  nan        | nan         |
| Qle    | detailed     |  24.9062  | -10.9907  |   0.819907 |   0.43673  |  15.5236 |  35.3538 |  43.524  |   0.9778   |  10.9907  |   0.180095  |   0.56327   |   29.0737   | 1151.92     |   0.281824  |
| Qh     | baseline     | nan       | nan       | nan        | nan        | nan      | nan      | nan      | nan        | nan       | nan         | nan         |  nan        |  nan        | nan         |
| Qh     | detailed     |  34.1995  |   6.35079 |   0.989501 |   0.682333 |   8.132  |  20.9696 |  58.2228 |   0.792953 |   6.35079 |   0.0105014 |   0.317667  |    7.99922  |  322.889    |   0.181524  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![K-UCMv1_PL-Narutowicza_subset_SWup_v0-9.png](K-UCMv1_PL-Narutowicza_subset_SWup_v0-9.png)](K-UCMv1_PL-Narutowicza_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed

 - K-UCMv1 Qstor min value of -8634.2692 is less than expected -800.0 [W/m2]
 - K-UCMv1 LWnet min value of -2405.2788 is less than expected -500.0 [W/m2]
 - K-UCMv1 Qh max value of 4747.9898 is greater than expected 600.0 [W/m2]
 - K-UCMv1 SWnet min value of -1.6174 is less than expected 0.0 [W/m2]
 - K-UCMv1 LWup max value of 2636.6587 is greater than expected 1000.0 [W/m2]
 - K-UCMv1 Qle max value of 2902.8905 is greater than expected 700.0 [W/m2]
 - K-UCMv1 Qstar min value of -2205.5241 is less than expected -500.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

