# FI-Torni: UCLEM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](UCLEM_FI-Torni_baseline_attrs.md)
- [Detailed](UCLEM_FI-Torni_detailed_attrs.md)

### Error metrics

| flux   | experiment   |      MAE |       MBE |      nSD |        R |      5th |    95th |    RMSE |    cRMSE |     AMBE |    1-nSD |       1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|---------:|----------:|---------:|---------:|---------:|--------:|--------:|---------:|---------:|---------:|----------:|------------:|------------:|----------:|
| SWup   | baseline     | 16.948   |  16.697   | 1.52759  | 0.939312 |  2.7304  | 38.4399 | 25.0307 | 0.681007 | 16.697   | 0.527596 | 0.0606883 |   0.677966  |   1.18909   |  0.226361 |
| SWup   | detailed     |  5.59844 |   2.70064 | 1.11694  | 0.931545 |  1.8021  |  4.9511 | 11.4983 | 0.40816  |  2.70064 | 0.116937 | 0.0684552 |   0.803251  |   1.32726   |  0.126361 |
| LWup   | baseline     | 15.1256  |  10.3156  | 1.31393  | 0.975137 |  6.04328 | 46.5436 | 22.3536 | 0.404833 | 10.3156  | 0.313931 | 0.0248628 |   1.11484   |   0.63433   |  0.113741 |
| LWup   | detailed     | 10.9758  |   7.59013 | 1.19892  | 0.983094 |  3.47548 | 30.1289 | 15.8061 | 0.283029 |  7.59013 | 0.198917 | 0.0169055 |   0.729179  |   0.357935  |  0.096864 |
| Qle    | baseline     | 19.4975  | -12.9897  | 0.74986  | 0.404631 |  2.2109  | 33.6879 | 33.5336 | 0.977475 | 12.9897  | 0.25014  | 0.595369  |   0.457467  |   1.1629    |  0.410399 |
| Qle    | detailed     | 19.761   | -14.118   | 0.690323 | 0.348545 |  2.973   | 45.8085 | 34.5684 | 0.997662 | 14.118   | 0.309677 | 0.651455  |   0.392555  |   2.33869   |  0.399064 |
| Qh     | baseline     | 38.0305  | -24.7309  | 0.731664 | 0.73223  |  5.3293  | 57.1151 | 54.1002 | 0.681058 | 24.7309  | 0.268337 | 0.26777   |   0.254819  |   0.303694  |  0.310178 |
| Qh     | detailed     | 36.1614  |   5.09823 | 0.794516 | 0.720262 | 17.7555  | 21.2537 | 49.5529 | 0.697665 |  5.09823 | 0.205485 | 0.279738  |   0.0547589 |   0.0469565 |  0.223062 |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![UCLEM_FI-Torni_subset_SWup_v0-9.png](UCLEM_FI-Torni_subset_SWup_v0-9.png)](UCLEM_FI-Torni_subset_SWup_v0-9.png)

### out of range: baseline

 - UCLEM Qle max value of 867.0872 is greater than expected 700.0 [W/m2]

### out of range: detailed

 - UCLEM Qle max value of 702.8712 is greater than expected 700.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

