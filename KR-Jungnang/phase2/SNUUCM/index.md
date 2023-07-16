# KR-Jungnang: SNUUCM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](SNUUCM_KR-Jungnang_baseline_attrs.md)
- [Detailed](SNUUCM_KR-Jungnang_detailed_attrs.md)

### Error metrics

| flux   | experiment   |     MAE |       MBE |      nSD |        R |      5th |    95th |    RMSE |    cRMSE |     AMBE |     1-nSD |       1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|--------:|----------:|---------:|---------:|---------:|--------:|--------:|---------:|---------:|----------:|----------:|------------:|------------:|----------:|
| SWup   | baseline     | 10.4711 |  -8.72209 | 0.720327 | 0.982254 |  3.52631 | 23.9553 | 13.707  | 0.322154 |  8.72209 | 0.279674  | 0.0177462 |  0.00165969 |   0.0445669 |  0.163154 |
| SWup   | detailed     | 12.1718 |  11.9298  | 1.11676  | 0.97774  |  6.78557 | 19.7695 | 14.5109 | 0.251694 | 11.9298  | 0.116754  | 0.02226   |  0.0180962  |   0.0619929 |  0.148298 |
| LWup   | baseline     | 20.0883 |  -2.92496 | 1.28344  | 0.977549 | 22.973   | 47.2427 | 25.342  | 0.371438 |  2.92496 | 0.283436  | 0.0224513 |  1.54753    |   0.868784  |  0.133319 |
| LWup   | detailed     | 20.377  | -12.7009  | 1.19017  | 0.983504 | 24.3705  | 22.7752 | 22.5334 | 0.274645 | 12.7009  | 0.190164  | 0.0164964 |  1.17534    |   0.549012  |  0.143748 |
| Qle    | baseline     | 20.3336 | -11.5773  | 0.965885 | 0.339654 |  6.66702 | 50.6449 | 34.1925 | 1.12996  | 11.5773  | 0.0341167 | 0.660346  |  2.56498    |   4.35078   |  0.523405 |
| Qle    | detailed     | 26.8607 |  13.7492  | 1.8021   | 0.522838 |  7.2066  | 74.477  | 45.8785 | 1.53726  | 13.7492  | 0.802101  | 0.477162  |  0.101788   |   0.499961  |  0.459616 |
| Qh     | baseline     | 43.9338 | -11.4441  | 1.24509  | 0.762065 |  1.95572 | 48.5036 | 62.9612 | 0.807817 | 11.4441  | 0.245086  | 0.237935  |  0.346008   |   0.95848   |  0.357273 |
| Qh     | detailed     | 38.879  | -29.3614  | 0.95022  | 0.801263 |  3.79852 | 23.4876 | 55.6343 | 0.616576 | 29.3614  | 0.0497824 | 0.198737  |  0.404598   |   1.45603   |  0.377227 |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![SNUUCM_KR-Jungnang_subset_SWup_v0-9.png](SNUUCM_KR-Jungnang_subset_SWup_v0-9.png)](SNUUCM_KR-Jungnang_subset_SWup_v0-9.png)

### out of range: baseline

 - SNUUCM TairSurf max value of 336.5936 is greater than expected 333.0 [K]

### out of range: detailed



[Link to variable definitions](../modelattrs/variable_definitions.md)

