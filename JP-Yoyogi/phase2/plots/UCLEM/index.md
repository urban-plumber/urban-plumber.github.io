# JP-Yoyogi: UCLEM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](UCLEM_JP-Yoyogi_baseline_attrs.md)
- [Detailed](UCLEM_JP-Yoyogi_detailed_attrs.md)

### Error metrics

| flux   | experiment   |      MAE |       MBE |      nSD |        R |       5th |    95th |    RMSE |    cRMSE |     AMBE |     1-nSD |       1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|---------:|----------:|---------:|---------:|----------:|--------:|--------:|---------:|---------:|----------:|----------:|------------:|------------:|----------:|
| SWup   | baseline     |  8.8937  |   6.25368 | 1.23089  | 0.957393 |  1.15463  | 22.1248 | 14.6525 | 0.397739 |  6.25368 | 0.230884  | 0.0426069 |    0.200544 |    0.4943   | 0.118572  |
| SWup   | detailed     |  6.22051 |  -1.07531 | 1.06174  | 0.956944 |  1.39163  |  4.6912 | 10.3377 | 0.308611 |  1.07531 | 0.0617427 | 0.0430559 |    0.208878 |    0.29605  | 0.0816529 |
| LWup   | baseline     | 22.0908  |  21.0607  | 1.37789  | 0.964439 |  1.06201  | 68.6237 | 32.579  | 0.490715 | 21.0607  | 0.377892  | 0.0355607 |    1.99903  |    1.47373  | 0.103463  |
| LWup   | detailed     | 15.8723  |  14.4293  | 1.25299  | 0.97973  |  0.950792 | 45.7176 | 22.4223 | 0.338824 | 14.4293  | 0.252991  | 0.0202701 |    1.24997  |    0.974364 | 0.094486  |
| Qle    | baseline     | 24.5316  | -16.5894  | 0.768826 | 0.491642 |  0.399808 | 34.6744 | 38.6063 | 0.913849 | 16.5894  | 0.231174  | 0.508358  |    0.359918 |    1.24974  | 0.398781  |
| Qle    | detailed     | 25.396   | -18.1693  | 0.726749 | 0.445142 |  0.629208 | 41.591  | 40.154  | 0.938696 | 18.1693  | 0.273251  | 0.554858  |    0.540313 |    2.08813  | 0.439634  |
| Qh     | baseline     | 25.4378  |   1.89332 | 0.874348 | 0.828243 | 19.792    | 11.8493 | 37.1835 | 0.562263 |  1.89332 | 0.125653  | 0.171757  |    0.352107 |    1.12186  | 0.221116  |
| Qh     | detailed     | 36.4499  |  25.4455  | 0.932275 | 0.831127 | 33.2404   | 16.8303 | 45.1772 | 0.565207 | 25.4455  | 0.0677263 | 0.168873  |    0.23833  |    0.863648 | 0.379945  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![UCLEM_JP-Yoyogi_subset_SWup_v0-9.png](UCLEM_JP-Yoyogi_subset_SWup_v0-9.png)](UCLEM_JP-Yoyogi_subset_SWup_v0-9.png)

### out of range: baseline

 - UCLEM Qle min value of -916.8510 is less than expected -700.0 [W/m2]

### out of range: detailed

 - UCLEM Qle min value of -910.4510 is less than expected -700.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

