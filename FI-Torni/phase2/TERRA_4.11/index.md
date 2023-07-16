# FI-Torni: TERRA_4.11

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](TERRA_4.11_FI-Torni_baseline_attrs.md)
- [Detailed](TERRA_4.11_FI-Torni_detailed_attrs.md)

### Error metrics

| flux   | experiment   |     MAE |        MBE |      nSD |        R |      5th |     95th |    RMSE |    cRMSE |      AMBE |     1-nSD |       1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|--------:|-----------:|---------:|---------:|---------:|---------:|--------:|---------:|----------:|----------:|----------:|------------:|------------:|----------:|
| SWup   | baseline     | 21.2067 |  14.3738   | 2.19491  | 0.60341  |  2.01774 |  85.3773 | 50.8194 | 1.7801   | 14.3738   | 1.19491   | 0.39659   |    4.96714  |  10.97      |  0.148927 |
| SWup   | detailed     | 23.4636 |  22.553    | 2.51386  | 0.622572 |  2.43293 | 134.36   | 60.4146 | 2.04679  | 22.553    | 1.51386   | 0.377428  |    4.46848  |   9.0513    |  0.135576 |
| LWup   | baseline     | 30.1612 | -30.135    | 0.987926 | 0.90197  | 43.3748  |  41.3871 | 37.0575 | 0.44027  | 30.135    | 0.0120754 | 0.0980298 |    2.01358  |   0.193209  |  0.194412 |
| LWup   | detailed     | 10.2295 |  -0.629856 | 1.23172  | 0.985869 | 17.1503  |  23.1551 | 14.5869 | 0.2975   |  0.629856 | 0.23172   | 0.0141311 |    0.3868   |   0.157623  |  0.138869 |
| Qle    | baseline     | 17.2479 |  -8.31149  | 0.581301 | 0.491596 |  5.9106  |  25.3233 | 28.9087 | 0.875431 |  8.31149  | 0.418699  | 0.508404  |    0.178857 |   0.527519  |  0.321767 |
| Qle    | detailed     | 17.1009 | -10.1216   | 0.568413 | 0.513581 |  5.06316 |  26.8053 | 29.016  | 0.859791 | 10.1216   | 0.431587  | 0.486419  |    0.184856 |   0.570408  |  0.385509 |
| Qh     | baseline     | 43.2708 |  17.9548   | 1.15432  | 0.712935 | 22.855   |  65.6665 | 61.2307 | 0.828581 | 17.9548   | 0.154321  | 0.287065  |    0.181355 |   0.0812587 |  0.242648 |
| Qh     | detailed     | 33.8746 | -14.4151   | 0.871136 | 0.735838 |  6.16819 |  16.6454 | 50.8717 | 0.690541 | 14.4151   | 0.128866  | 0.264162  |    0.268979 |   0.294797  |  0.271395 |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![TERRA_4.11_FI-Torni_subset_SWup_v0-9.png](TERRA_4.11_FI-Torni_subset_SWup_v0-9.png)](TERRA_4.11_FI-Torni_subset_SWup_v0-9.png)

### out of range: baseline

 - TERRA_4.11 SWup min value of -0.0014 is less than expected 0.0 [W/m2]
 - TERRA_4.11 Albedo min value of -0.0822 is less than expected 0.0 [1]

### out of range: detailed

 - TERRA_4.11 SWup min value of -0.0009 is less than expected 0.0 [W/m2]
 - TERRA_4.11 Albedo min value of -0.0552 is less than expected 0.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

