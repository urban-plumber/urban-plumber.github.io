# FR-Capitole: Ensemble

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](Ensemble_FR-Capitole_baseline_attrs.md)
- [Detailed](Ensemble_FR-Capitole_detailed_attrs.md)

### Error metrics

| flux   | experiment   |        MAE |         MBE |      nSD |        R |          5th |       95th |       RMSE |    cRMSE |       AMBE |      1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|-----------:|------------:|---------:|---------:|-------------:|-----------:|-----------:|---------:|-----------:|-----------:|-----------:|------------:|------------:|----------:|
| SWup   | baseline     |  4.35526   |   0.558475  | 1.10341  | 0.990941 |  2.65433     |  8.77513   |  5.88883   | 0.175176 |  0.558475  | 0.103413   | 0.00905937 |   0.0857921 |    0.148516 | 0.15864   |
| SWup   | detailed     |  4.37609   |  -3.38412   | 0.99861  | 0.989152 |  2.57132     |  1.31036   |  5.97655   | 0.147202 |  3.38412   | 0.00138917 | 0.0108484  |   0.12947   |    0.228913 | 0.135641  |
| LWup   | baseline     |  8.86327   |  -2.22167   | 1.17819  | 0.995052 | 13.9296      | 18.3376    | 11.1872    | 0.208351 |  2.22167   | 0.178189   | 0.00494772 |   0.0332859 |    0.263441 | 0.109788  |
| LWup   | detailed     |  8.82309   |  -1.55686   | 1.17197  | 0.994149 | 12.0558      | 18.9507    | 11.0589    | 0.208054 |  1.55686   | 0.171968   | 0.00585056 |   0.0841117 |    0.487942 | 0.105816  |
| Qle    | baseline     | 13.1145    |  -8.56529   | 0.700176 | 0.632792 |  5.21307     | 21.9605    | 18.1917    | 0.777248 |  8.56529   | 0.299825   | 0.367208   |   1.17729   |    2.0808   | 0.410595  |
| Qle    | detailed     | 11.8962    |  -6.31944   | 0.739953 | 0.664405 |  5.81619     | 12.7705    | 16.7488    | 0.751182 |  6.31944   | 0.260048   | 0.335595   |   0.563218  |    0.353788 | 0.362762  |
| Qh     | baseline     | 28.3675    | -19.3844    | 0.943428 | 0.903057 |  0.588657    | 16.8803    | 40.4117    | 0.431414 | 19.3844    | 0.0565725  | 0.0969429  |   0.201937  |    0.373858 | 0.265812  |
| Qh     | detailed     | 24.1823    | -13.8413    | 0.974709 | 0.919152 |  4.65961     |  6.4041    | 35.5055    | 0.397801 | 13.8413    | 0.0252913  | 0.0808477  |   0.163717  |    0.222436 | 0.24949   |
| Qtau   | baseline     |  0.0510464 |   0.0100723 | 1.04399  | 0.901943 |  0.000698592 |  0.0312803 |  0.0824904 | 0.454615 |  0.0100723 | 0.0439878  | 0.0980566  |   0.060248  |    0.178781 | 0.0329691 |
| Qtau   | detailed     |  0.0683303 |   0.0527061 | 1.26682  | 0.910614 |  0.00789883  |  0.150336  |  0.1115    | 0.545584 |  0.0527061 | 0.266815   | 0.0893859  |   0.0632619 |    0.183631 | 0.0968291 |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### out of range: baseline


### out of range: detailed

 - Ensemble SWnet min value of -0.0000 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

