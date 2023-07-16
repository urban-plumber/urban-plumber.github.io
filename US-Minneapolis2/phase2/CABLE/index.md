# US-Minneapolis2: CABLE

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](CABLE_US-Minneapolis2_baseline_attrs.md)
- [Detailed](CABLE_US-Minneapolis2_detailed_attrs.md)

### Error metrics

| flux     | experiment   |       MAE |       MBE |        nSD |          R |       5th |      95th |      RMSE |      cRMSE |      AMBE |        1-nSD |         1-R |   nSkewness |   nKurtosis |     Overlap |
|:---------|:-------------|----------:|----------:|-----------:|-----------:|----------:|----------:|----------:|-----------:|----------:|-------------:|------------:|------------:|------------:|------------:|
| SWup     | baseline     | nan       | nan       | nan        | nan        | nan       | nan       | nan       | nan        | nan       | nan          | nan         |  nan        | nan         | nan         |
| SWup     | detailed     |  46.1873  | -45.8298  |   0.500374 |   0.771743 |   1.73701 | 154.75    |  81.1386  |   0.691414 |  45.8298  |   0.499627   |   0.228257  |    0.374581 |   0.667618  |   0.226035  |
| LWup     | baseline     | nan       | nan       | nan        | nan        | nan       | nan       | nan       | nan        | nan       | nan          | nan         |  nan        | nan         | nan         |
| LWup     | detailed     |   9.72863 |   6.65628 |   0.995476 |   0.987646 |  11.4979  |   9.12569 |  13.1798  |   0.156896 |   6.65628 |   0.00452514 |   0.0123538 |    0.334029 |   0.0014841 |   0.0904102 |
| Qle      | baseline     | nan       | nan       | nan        | nan        | nan       | nan       | nan       | nan        | nan       | nan          | nan         |  nan        | nan         | nan         |
| Qle      | detailed     |  38.7035  |   6.39441 |   1.06092  |   0.628491 |   3.28064 |   7.15631 |  68.9055  |   0.889943 |   6.39441 |   0.0609239  |   0.371509  |    0.26102  |   0.614969  |   0.17355   |
| Qh       | baseline     | nan       | nan       | nan        | nan        | nan       | nan       | nan       | nan        | nan       | nan          | nan         |  nan        | nan         | nan         |
| Qh       | detailed     |  44.1162  |   6.49701 |   1.56275  |   0.71907  |  25.2469  | 100.049   |  69.6014  |   1.09304  |   6.49701 |   0.562751   |   0.28093   |    0.453843 |   0.206818  |   0.181786  |
| Qg       | baseline     | nan       | nan       | nan        | nan        | nan       | nan       | nan       | nan        | nan       | nan          | nan         |  nan        | nan         | nan         |
| Qg       | detailed     |  50.6925  |   1.10451 |   2.03329  |   0.490227 |  56.6765  |  55.7437  |  79.1376  |   1.77221  |   1.10451 |   1.03327    |   0.509773  |    0.413886 |   0.750662  |   0.300678  |
| Qtau     | baseline     | nan       | nan       | nan        | nan        | nan       | nan       | nan       | nan        | nan       | nan          | nan         |  nan        | nan         | nan         |
| Qtau     | detailed     | nan       | nan       | nan        | nan        | nan       | nan       | nan       | nan        | nan       | nan          | nan         |  nan        | nan         | nan         |
| SoilTemp | baseline     | nan       | nan       | nan        | nan        | nan       | nan       | nan       | nan        | nan       | nan          | nan         |  nan        | nan         | nan         |
| SoilTemp | detailed     |   5.03207 |  -2.94169 |   1.3281   |   0.92601  |  11.8321  |   3.0531  |   6.52322 |   0.551529 |   2.94169 |   0.328106   |   0.0739903 |    4.92111  |   0.514555  |   0.267118  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![CABLE_US-Minneapolis2_subset_SWup_v0-9.png](CABLE_US-Minneapolis2_subset_SWup_v0-9.png)](CABLE_US-Minneapolis2_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed

 - CABLE Qstor min value of -840.8791 is less than expected -800.0 [W/m2]
 - CABLE Qg max value of 771.5851 is greater than expected 500.0 [W/m2]
 - CABLE Qg min value of -840.8791 is less than expected -500.0 [W/m2]
 - CABLE Qle max value of 800.0970 is greater than expected 700.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

