# AU-Preston: SNUUCM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](SNUUCM_AU-Preston_baseline_attrs.md)
- [Detailed](SNUUCM_AU-Preston_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |       MBE |        nSD |          R |        5th |      95th |      RMSE |       cRMSE |      AMBE |       1-nSD |          1-R |   nSkewness |   nKurtosis |     Overlap |
|:-------|:-------------|----------:|----------:|-----------:|-----------:|-----------:|----------:|----------:|------------:|----------:|------------:|-------------:|------------:|------------:|------------:|
| SWup   | baseline     |   3.32737 |  -2.48368 |   0.974947 |   0.996452 |   0.60861  |   3.28783 |   4.74861 |   0.0868673 |   2.48368 |   0.0250531 |   0.00354801 |   0.0431448 |   0.0750377 |   0.0618501 |
| SWup   | detailed     |   3.64857 |   2.24227 |   1.06388  |   0.996499 |   0.507586 |   9.70564 |   5.48227 |   0.107374  |   2.24227 |   0.0638766 |   0.00350088 |   0.0458423 |   0.081369  |   0.0742636 |
| LWup   | baseline     |  15.1528  |  -8.56024 |   1.26337  |   0.975654 |  18.2472   |  20.9688  |  17.4483  |   0.36177   |   8.56024 |   0.263366  |   0.0243456  |   0.165642  |   0.305905  |   0.207556  |
| LWup   | detailed     |  17.0338  |  -5.75808 |   1.36702  |   0.967904 |  18.3924   |  35.3229  |  20.6415  |   0.471653  |   5.75808 |   0.367021  |   0.0320955  |   0.213899  |   0.395989  |   0.220958  |
| Qle    | baseline     |  24.4764  | -10.6973  |   0.696184 |   0.56991  |   7.78626  |  39.0264  |  41.9735  |   0.831353  |  10.6973  |   0.303817  |   0.43009    |   0.533337  |   0.71861   |   0.239608  |
| Qle    | detailed     |  24.9974  | -10.2859  |   0.740521 |   0.539081 |   7.73264  |  39.0778  |  43.5126  |   0.866008  |  10.2859  |   0.25948   |   0.460919   |   0.97794   |   3.04412   |   0.236993  |
| Qh     | baseline     |  22.2343  |   7.53063 |   1.21579  |   0.94442  |   1.31957  |  67.1629  |  39.8389  |   0.426277  |   7.53063 |   0.215788  |   0.0555804  |   0.121604  |   0.181598  |   0.100184  |
| Qh     | detailed     |  22.1466  |   6.0464  |   1.19551  |   0.944475 |   1.0461   |  60.2857  |  38.4272  |   0.413504  |   6.0464  |   0.195513  |   0.0555247  |   0.0893538 |   0.105028  |   0.119116  |
| Qtau   | baseline     | nan       | nan       | nan        | nan        | nan        | nan       | nan       | nan         | nan       | nan         | nan          | nan         | nan         | nan         |
| Qtau   | detailed     | nan       | nan       | nan        | nan        | nan        | nan       | nan       | nan         | nan       | nan         | nan          | nan         | nan         | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![SNUUCM_AU-Preston_subset_SWup_v0-9.png](SNUUCM_AU-Preston_subset_SWup_v0-9.png)](SNUUCM_AU-Preston_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed

 - SNUUCM Qstor max value of 2524.4658 is greater than expected 800.0 [W/m2]
 - SNUUCM Qstor min value of -2116338.7500 is less than expected -800.0 [W/m2]
 - SNUUCM Qh max value of 727.7576 is greater than expected 600.0 [W/m2]
 - SNUUCM Qle max value of 2116519.0000 is greater than expected 700.0 [W/m2]
 - SNUUCM Qle min value of -2358.2024 is less than expected -700.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

