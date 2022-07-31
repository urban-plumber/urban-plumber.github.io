# AU-Preston: JULES_MORUS

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](JULES_MORUS_AU-Preston_baseline_attrs.md)
- [Detailed](JULES_MORUS_AU-Preston_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |         MBE |      nSD |        R |         5th |      95th |      RMSE |     cRMSE |       AMBE |     1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|----------:|------------:|---------:|---------:|------------:|----------:|----------:|----------:|-----------:|----------:|-----------:|------------:|------------:|----------:|
| SWup   | baseline     |  3.48093  |  -2.04671   | 0.935671 | 0.996548 |  0.371565   |  9.32476  |  5.21424  | 0.102942  |  2.04671   | 0.0643286 | 0.0034515  |   0.107257  |    0.194466 | 0.0767645 |
| SWup   | detailed     |  3.1353   |   2.03729   | 1.03445  | 0.996902 |  0.409089   |  5.15425  |  4.54266  | 0.0871532 |  2.03729   | 0.0344484 | 0.00309778 |   0.0339758 |    0.065507 | 0.0693705 |
| LWup   | baseline     |  6.92928  |   4.59412   | 0.928003 | 0.989162 |  6.27662    |  1.8384   |  8.10914  | 0.159055  |  4.59412   | 0.0719966 | 0.0108378  |   0.074699  |    0.128205 | 0.108016  |
| LWup   | detailed     |  7.04585  |  -0.717451  | 0.955869 | 0.978671 |  3.23895    |  6.51046  |  8.71319  | 0.206693  |  0.717451  | 0.0441312 | 0.0213285  |   0.173936  |    0.317695 | 0.0716116 |
| Qle    | baseline     | 24.7331   | -11.6806    | 0.530717 | 0.625895 | 12.0878     | 53.2349   | 42.5501   | 0.785694  | 11.6806    | 0.469283  | 0.374105   |   0.0859896 |    0.24537  | 0.228583  |
| Qle    | detailed     | 22.4336   |   2.28338   | 0.881025 | 0.690107 | 11.7394     |  4.45742  | 39.0437   | 0.748467  |  2.28338   | 0.118975  | 0.309893   |   0.144724  |    0.724131 | 0.195036  |
| Qh     | baseline     | 28.1842   |  12.4321    | 1.21117  | 0.922128 |  8.77428    | 56.7359   | 46.1333   | 0.482937  | 12.4321    | 0.211173  | 0.0778725  |   0.0712406 |    0.208579 | 0.17354   |
| Qh     | detailed     | 23.7707   |   2.95147   | 1.18021  | 0.938808 | 16.0665     | 43.696    | 38.8058   | 0.420614  |  2.95147   | 0.180214  | 0.061192   |   0.019524  |    0.022411 | 0.133494  |
| Qtau   | baseline     |  0.14899  |   0.105852  | 1.156    | 0.864494 |  0.0175277  |  0.174305 |  0.218069 | 0.581058  |  0.105852  | 0.156004  | 0.135506   |   0.144869  |    0.192277 | 0.147259  |
| Qtau   | detailed     |  0.108162 |  -0.0544813 | 0.754842 | 0.861448 |  0.00191222 |  0.247003 |  0.178769 | 0.518915  |  0.0544813 | 0.245158  | 0.138552   |   0.119222  |    0.160216 | 0.0608589 |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="datasheet"></a>Datasheet
[![JULES_MORUS_AU-Preston_Datasheet.png](JULES_MORUS_AU-Preston_Datasheet.png)](JULES_MORUS_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![JULES_MORUS_AU-Preston_Distributions.png](JULES_MORUS_AU-Preston_Distributions.png)](JULES_MORUS_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![JULES_MORUS_AU-Preston_closure_baseline.png](JULES_MORUS_AU-Preston_closure_baseline.png)](JULES_MORUS_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![JULES_MORUS_AU-Preston_closure_detailed.png](JULES_MORUS_AU-Preston_closure_detailed.png)](JULES_MORUS_AU-Preston_closure_detailed.png)

### <a name="subset_lwup"></a>subset_LWup
[![JULES_MORUS_AU-Preston_subset_LWup.png](JULES_MORUS_AU-Preston_subset_LWup.png)](JULES_MORUS_AU-Preston_subset_LWup.png)

### <a name="subset_qh"></a>subset_Qh
[![JULES_MORUS_AU-Preston_subset_Qh.png](JULES_MORUS_AU-Preston_subset_Qh.png)](JULES_MORUS_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![JULES_MORUS_AU-Preston_subset_Qle.png](JULES_MORUS_AU-Preston_subset_Qle.png)](JULES_MORUS_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![JULES_MORUS_AU-Preston_subset_SWup.png](JULES_MORUS_AU-Preston_subset_SWup.png)](JULES_MORUS_AU-Preston_subset_SWup.png)

### out of range: baseline

 - JULES_MORUS Qh max value of 699.7561 is greater than expected 600.0 [W/m2]
 - JULES_MORUS SWE min value of -0.0000 is less than expected 0.0 [kg/m2]
 - JULES_MORUS Qsm min value of -0.0000 is less than expected 0.0 [kg/m2/s]
 - JULES_MORUS EvapF max value of 63.4013 is greater than expected 1.0 [1]
 - JULES_MORUS EvapF min value of -118.2092 is less than expected 0.0 [1]

### out of range: detailed

 - JULES_MORUS SWE min value of -0.0000 is less than expected 0.0 [kg/m2]
 - JULES_MORUS EvapF max value of 94.7447 is greater than expected 1.0 [1]
 - JULES_MORUS EvapF min value of -77.2919 is less than expected 0.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

