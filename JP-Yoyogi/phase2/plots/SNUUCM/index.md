# JP-Yoyogi: SNUUCM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](SNUUCM_JP-Yoyogi_baseline_attrs.md)
- [Detailed](SNUUCM_JP-Yoyogi_detailed_attrs.md)

### Error metrics

| flux   | experiment   |      MAE |        MBE |      nSD |        R |       5th |     95th |    RMSE |    cRMSE |      AMBE |     1-nSD |       1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|---------:|-----------:|---------:|---------:|----------:|---------:|--------:|---------:|----------:|----------:|----------:|------------:|------------:|----------:|
| SWup   | baseline     | 10.1382  |  -9.38247  | 0.81729  | 0.967234 |  1.48939  | 17.4028  | 13.5842 | 0.294858 |  9.38247  | 0.182711  | 0.0327658 |    0.176082 |    0.245493 |  0.114873 |
| SWup   | detailed     |  7.92364 |   5.28425  | 1.19999  | 0.968786 |  1.06614  | 21.272   | 12.4686 | 0.338985 |  5.28425  | 0.199992  | 0.0312141 |    0.178519 |    0.248071 |  0.110049 |
| LWup   | baseline     | 20.6218  |  -0.821783 | 1.43447  | 0.953841 | 24.8107   | 57.7966  | 28.7191 | 0.56674  |  0.821783 | 0.434471  | 0.0461589 |    2.40481  |    1.91551  |  0.144091 |
| LWup   | detailed     | 21.6027  |  -9.5032   | 1.34456  | 0.963296 | 29.4853   | 37.0597  | 25.459  | 0.466284 |  9.5032   | 0.344556  | 0.036704  |    1.85525  |    1.40883  |  0.169208 |
| Qle    | baseline     | 26.6982  | -14.8045   | 1.01725  | 0.428288 |  0.634399 | 24.9177  | 43.7285 | 1.07863  | 14.8045   | 0.0172477 | 0.571712  |    0.901234 |    2.0705   |  0.437598 |
| Qle    | detailed     | 26.3782  |   6.95015  | 1.45661  | 0.612725 |  0.330194 | 49.6677  | 44.6482 | 1.15617  |  6.95015  | 0.456614  | 0.387275  |    0.050219 |    0.232334 |  0.300798 |
| Qh     | baseline     | 29.6786  |   3.57184  | 1.30344  | 0.846646 |  6.07285  | 60.3603  | 46.4568 | 0.701319 |  3.57184  | 0.303436  | 0.153354  |    0.336404 |    0.7576   |  0.227411 |
| Qh     | detailed     | 24.21    | -11.4526   | 0.978753 | 0.864646 |  1.30124  |  4.94513 | 35.9012 | 0.515178 | 11.4526   | 0.0212477 | 0.135354  |    0.308961 |    0.755056 |  0.205674 |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![SNUUCM_JP-Yoyogi_subset_SWup_v0-9.png](SNUUCM_JP-Yoyogi_subset_SWup_v0-9.png)](SNUUCM_JP-Yoyogi_subset_SWup_v0-9.png)

### out of range: baseline

 - SNUUCM TairSurf max value of 334.4068 is greater than expected 333.0 [K]
 - SNUUCM Qh max value of 823.0309 is greater than expected 600.0 [W/m2]

### out of range: detailed



[Link to variable definitions](../modelattrs/variable_definitions.md)

