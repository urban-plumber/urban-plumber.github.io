# FI-Kumpula: NOAH-SLUCM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](NOAH-SLUCM_FI-Kumpula_baseline_attrs.md)
- [Detailed](NOAH-SLUCM_FI-Kumpula_detailed_attrs.md)

### Error metrics

| flux   | experiment   |      MAE |        MBE |      nSD |        R |       5th |      95th |    RMSE |    cRMSE |      AMBE |     1-nSD |       1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|---------:|-----------:|---------:|---------:|----------:|----------:|--------:|---------:|----------:|----------:|----------:|------------:|------------:|----------:|
| SWup   | baseline     |  8.85669 |   5.49684  | 1.15068  | 0.976204 | 0.211892  | 18.5145   | 13.9452 | 0.278327 |  5.49684  | 0.150664  | 0.0237957 |   0.0496597 |    0.150138 | 0.12005   |
| SWup   | detailed     |  5.74138 |  -0.377057 | 1.04716  | 0.978146 | 0.0150959 |  0.784355 | 10.0948 | 0.219074 |  0.377057 | 0.0471506 | 0.0218538 |   0.0794645 |    0.180247 | 0.103897  |
| LWup   | baseline     |  9.50011 |   5.92131  | 1.15069  | 0.986395 | 2.80652   | 29.381    | 13.609  | 0.232417 |  5.92131  | 0.150687  | 0.0136049 |   1.90926   |    0.476393 | 0.0816103 |
| LWup   | detailed     | 12.4564  |   9.32164  | 1.22035  | 0.977053 | 1.21219   | 45.0834   | 19.43   | 0.32336  |  9.32164  | 0.220347  | 0.0229473 |   3.25869   |    1.00455  | 0.0907444 |
| Qle    | baseline     | 14.4355  |  -9.19282  | 0.634457 | 0.780002 | 3.54455   | 37.3984   | 25.9921 | 0.642479 |  9.19282  | 0.365542  | 0.219998  |   0.116715  |    0.137567 | 0.213121  |
| Qle    | detailed     | 14.4349  |  -9.1831   | 0.634846 | 0.779751 | 3.54455   | 37.1649   | 25.9943 | 0.64264  |  9.1831   | 0.365153  | 0.220249  |   0.117848  |    0.142219 | 0.21364   |
| Qh     | baseline     | 26.2324  | -17.5943   | 0.739917 | 0.792688 | 2.95702   | 57.089    | 40.2107 | 0.611908 | 17.5943   | 0.260084  | 0.207312  |   0.150718  |    0.309726 | 0.247917  |
| Qh     | detailed     | 26.2152  | -18.1033   | 0.744664 | 0.801181 | 5.23347   | 56.663    | 39.8652 | 0.601085 | 18.1033   | 0.255336  | 0.198819  |   0.0929691 |    0.206363 | 0.24092   |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![NOAH-SLUCM_FI-Kumpula_subset_SWup_v0-9.png](NOAH-SLUCM_FI-Kumpula_subset_SWup_v0-9.png)](NOAH-SLUCM_FI-Kumpula_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed

 - NOAH-SLUCM Qle max value of 860.6373 is greater than expected 700.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

