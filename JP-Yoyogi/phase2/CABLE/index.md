# JP-Yoyogi: CABLE

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](CABLE_JP-Yoyogi_baseline_attrs.md)
- [Detailed](CABLE_JP-Yoyogi_detailed_attrs.md)

### Error metrics

| flux   | experiment   |      MAE |       MBE |        nSD |          R |       5th |     95th |     RMSE |      cRMSE |      AMBE |      1-nSD |         1-R |   nSkewness |   nKurtosis |    Overlap |
|:-------|:-------------|---------:|----------:|-----------:|-----------:|----------:|---------:|---------:|-----------:|----------:|-----------:|------------:|------------:|------------:|-----------:|
| SWup   | baseline     | nan      | nan       | nan        | nan        | nan       | nan      | nan      | nan        | nan       | nan        | nan         | nan         |  nan        | nan        |
| SWup   | detailed     |  10.2595 |  -9.40444 |   0.825435 |   0.964184 |   1.5073  |  16.6818 |  13.7075 |   0.299333 |   9.40444 |   0.174566 |   0.0358157 |   0.296439  |    0.746548 |   0.134497 |
| LWup   | baseline     | nan      | nan       | nan        | nan        | nan       | nan      | nan      | nan        | nan       | nan        | nan         | nan         |  nan        | nan        |
| LWup   | detailed     |  14.9674 |   5.22402 |   1.28336  |   0.942338 |  13.2951  |  36.4062 |  24.7596 |   0.4778   |   5.22402 |   0.283356 |   0.0576619 |   2.29212   |    2.42952  |   0.103415 |
| Qle    | baseline     | nan      | nan       | nan        | nan        | nan       | nan      | nan      | nan        | nan       | nan        | nan         | nan         |  nan        | nan        |
| Qle    | detailed     |  59.3315 |  46.3896  |   2.96984  |   0.502407 |   1.45278 | 220.58   | 109.997  |   2.61454  |  46.3896  |   1.96984  |   0.497593  |   0.0370747 |    0.175216 |   0.165755 |
| Qh     | baseline     | nan      | nan       | nan        | nan        | nan       | nan      | nan      | nan        | nan       | nan        | nan         | nan         |  nan        | nan        |
| Qh     | detailed     |  38.6289 | -33.602   |   0.480602 |   0.729132 |   0.19829 | 114.303  |  58.665  |   0.728103 |  33.602   |   0.519398 |   0.270868  |   0.701697  |    4.10904  |   0.291694 |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![CABLE_JP-Yoyogi_subset_SWup_v0-9.png](CABLE_JP-Yoyogi_subset_SWup_v0-9.png)](CABLE_JP-Yoyogi_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed

 - CABLE Qstor min value of -821.8669 is less than expected -800.0 [W/m2]
 - CABLE Qle max value of 905.7581 is greater than expected 700.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

