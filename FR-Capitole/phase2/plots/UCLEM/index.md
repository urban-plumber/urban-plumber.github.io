# FR-Capitole: UCLEM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](UCLEM_FR-Capitole_baseline_attrs.md)
- [Detailed](UCLEM_FR-Capitole_detailed_attrs.md)

### Error metrics

| flux   | experiment   |        MAE |         MBE |      nSD |        R |       5th |       95th |       RMSE |    cRMSE |       AMBE |      1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|-----------:|------------:|---------:|---------:|----------:|-----------:|-----------:|---------:|-----------:|-----------:|-----------:|------------:|------------:|----------:|
| SWup   | baseline     |  6.81694   |   4.61542   | 1.20916  | 0.99318  |  2.6731   | 17.6887    |  9.42166   | 0.245441 |  4.61542   | 0.209165   | 0.00681953 |  0.00470229 |   0.0422113 | 0.177934  |
| SWup   | detailed     |  3.79106   |  -1.21192   | 1.06839  | 0.992296 |  2.7168   |  3.99317   |  5.01414   | 0.145389 |  1.21192   | 0.0683871  | 0.00770383 |  0.0644148  |   0.0370652 | 0.147196  |
| LWup   | baseline     | 14.91      |  10.2265    | 1.28697  | 0.988463 |  8.10378  | 40.4313    | 20.3684    | 0.33473  | 10.2265    | 0.286965   | 0.0115368  |  0.0087247  |   0.165196  | 0.123296  |
| LWup   | detailed     | 11.805     |   0.848079  | 1.22165  | 0.985746 | 15.9375   | 26.5901    | 15.2716    | 0.28975  |  0.848079  | 0.221649   | 0.0142539  |  0.043517   |   0.728455  | 0.102597  |
| Qle    | baseline     | 14.489     |  -7.44188   | 1.00312  | 0.56261  |  4.4853   | 14.7793    | 20.7249    | 0.936758 |  7.44188   | 0.00311413 | 0.43739    |  2.02288    |   4.45496   | 0.415555  |
| Qle    | detailed     | 16.1645    |  -8.41631   | 1.11864  | 0.468209 |  3.8588   | 14.0249    | 24.1684    | 1.0972   |  8.41631   | 0.11864    | 0.531791   |  3.19797    |  10.6512    | 0.44151   |
| Qh     | baseline     | 39.2636    | -33.4319    | 0.729448 | 0.84842  |  0.3224   | 75.3268    | 55.7328    | 0.542529 | 33.4319    | 0.270552   | 0.15158    |  0.251904   |   0.668254  | 0.303396  |
| Qh     | detailed     | 27.5989    |   4.29188   | 1.03818  | 0.895635 | 19.4797   | 27.6581    | 38.6293    | 0.467072 |  4.29188   | 0.0381761  | 0.104365   |  0.254874   |   0.56586   | 0.217912  |
| Qtau   | baseline     |  0.0621548 |   0.0156033 | 1.09007  | 0.881697 |  0.010366 |  0.0489929 |  0.0941899 | 0.515779 |  0.0156033 | 0.0900669  | 0.118303   |  0.0973245  |   0.227785  | 0.0708584 |
| Qtau   | detailed     |  0.0692247 |  -0.054083  | 0.783469 | 0.872356 |  0.011066 |  0.127907  |  0.10456   | 0.496886 |  0.054083  | 0.216531   | 0.127644   |  0.094535   |   0.244216  | 0.194686  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![UCLEM_FR-Capitole_subset_SWup_v0-9.png](UCLEM_FR-Capitole_subset_SWup_v0-9.png)](UCLEM_FR-Capitole_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed

 - UCLEM Qle max value of 928.3569 is greater than expected 700.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

