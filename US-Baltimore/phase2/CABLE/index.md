# US-Baltimore: CABLE

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](CABLE_US-Baltimore_baseline_attrs.md)
- [Detailed](CABLE_US-Baltimore_detailed_attrs.md)

### Error metrics

| flux     | experiment   |       MAE |        MBE |       nSD |          R |       5th |      95th |      RMSE |      cRMSE |       AMBE |      1-nSD |         1-R |   nSkewness |   nKurtosis |     Overlap |
|:---------|:-------------|----------:|-----------:|----------:|-----------:|----------:|----------:|----------:|-----------:|-----------:|-----------:|------------:|------------:|------------:|------------:|
| SWup     | baseline     | nan       | nan        | nan       | nan        | nan       | nan       | nan       | nan        | nan        | nan        | nan         | nan         |  nan        | nan         |
| SWup     | detailed     |   7.02174 |  -0.897321 |   1.12155 |   0.962909 |   0.36632 |  12.385   |  10.5344  |   0.313005 |   0.897321 |   0.121547 |   0.037091  |   0.691742  |    1.03747  |   0.0934128 |
| LWup     | baseline     | nan       | nan        | nan       | nan        | nan       | nan       | nan       | nan        | nan        | nan        | nan         | nan         |  nan        | nan         |
| LWup     | detailed     |  10.6202  |   2.89827  |   1.17489 |   0.971604 |   4.28828 |  31.647   |  17.4816  |   0.311951 |   2.89827  |   0.174892 |   0.0283964 |  11.3705    |    0.885056 |   0.102264  |
| Qle      | baseline     | nan       | nan        | nan       | nan        | nan       | nan       | nan       | nan        | nan        | nan        | nan         | nan         |  nan        | nan         |
| Qle      | detailed     |  46.1951  |  28.407    |   1.25413 |   0.68802  |  16.6776  |  62.0042  |  72.3859  |   0.920388 |  28.407    |   0.254134 |   0.31198   |   0.0243839 |    0.061407 |   0.226681  |
| Qh       | baseline     | nan       | nan        | nan       | nan        | nan       | nan       | nan       | nan        | nan        | nan        | nan         | nan         |  nan        | nan         |
| Qh       | detailed     |  44.9682  | -20.4878   |   0.87355 |   0.70695  |  25.2747  |  59.3046  |  67.6135  |   0.72662  |  20.4878   |   0.126451 |   0.29305   |   0.143158  |    0.419072 |   0.17437   |
| SoilTemp | baseline     | nan       | nan        | nan       | nan        | nan       | nan       | nan       | nan        | nan        | nan        | nan         | nan         |  nan        | nan         |
| SoilTemp | detailed     |   3.10396 |  -1.13151  |   1.19741 |   0.948245 |   2.30429 |   2.93179 |   3.94083 |   0.403629 |   1.13151  |   0.197411 |   0.0517548 |   1.76179   |    0.396839 |   0.162442  |
| Qtau     | baseline     | nan       | nan        | nan       | nan        | nan       | nan       | nan       | nan        | nan        | nan        | nan         | nan         |  nan        | nan         |
| Qtau     | detailed     | nan       | nan        | nan       | nan        | nan       | nan       | nan       | nan        | nan        | nan        | nan         | nan         |  nan        | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![CABLE_US-Baltimore_subset_SWup_v0-9.png](CABLE_US-Baltimore_subset_SWup_v0-9.png)](CABLE_US-Baltimore_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed

 - CABLE Qstor max value of 1039.5103 is greater than expected 800.0 [W/m2]
 - CABLE Qstor min value of -937.5334 is less than expected -800.0 [W/m2]
 - CABLE Qh max value of 619.3665 is greater than expected 600.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

