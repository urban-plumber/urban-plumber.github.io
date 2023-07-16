# PL-Lipowa: Ensemble

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](Ensemble_PL-Lipowa_baseline_attrs.md)
- [Detailed](Ensemble_PL-Lipowa_detailed_attrs.md)

### Error metrics

| flux   | experiment   |      MAE |       MBE |      nSD |        R |       5th |    95th |     RMSE |    cRMSE |     AMBE |     1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|---------:|----------:|---------:|---------:|----------:|--------:|---------:|---------:|---------:|----------:|-----------:|------------:|------------:|----------:|
| SWup   | baseline     | 13.0739  |  11.8164  | 1.65012  | 0.95502  |  0.706097 | 43.1253 | 19.4133  | 0.755709 | 11.8164  | 0.650113  | 0.0449804  |   0.0406575 |    1.38715  |  0.225051 |
| SWup   | detailed     |  6.21872 |   3.54158 | 1.25549  | 0.957563 |  0.834675 | 18.2181 |  9.16126 | 0.414532 |  3.54158 | 0.255491  | 0.0424374  |   0.0395701 |    1.34493  |  0.167112 |
| LWup   | baseline     | 20.0636  | -20.0264  | 1.02294  | 0.994656 | 19.3052   | 13.4755 | 21.0152  | 0.107052 | 20.0264  | 0.0229332 | 0.00534447 |   0.263984  |    0.795527 |  0.154177 |
| LWup   | detailed     | 20.8858  | -20.8536  | 1.0203   | 0.995235 | 19.0954   | 14.7321 | 21.6971  | 0.100675 | 20.8536  | 0.0203001 | 0.0047649  |   0.296865  |    0.635253 |  0.167217 |
| Qle    | baseline     | 15.7598  |  -5.47358 | 0.619515 | 0.641733 | 12.527    | 26.043  | 25.5452  | 0.76725  |  5.47358 | 0.380485  | 0.358267   |   0.448617  |    0.163208 |  0.27953  |
| Qle    | detailed     | 15.0947  |  -3.70031 | 0.669879 | 0.661343 | 13.0219   | 20.0915 | 24.6742  | 0.750132 |  3.70031 | 0.330121  | 0.338657   |   0.353262  |    0.168087 |  0.268363 |
| Qh     | baseline     | 33.6444  |  30.0381  | 1.0301   | 0.900718 | 30.9611   | 37.5759 | 42.7421  | 0.453261 | 30.0381  | 0.0300995 | 0.0992815  |   0.131248  |    0.432466 |  0.413958 |
| Qh     | detailed     | 34.0863  |  31.127   | 1.04495  | 0.907133 | 31.205    | 41.2985 | 43.0285  | 0.442837 | 31.127   | 0.0449532 | 0.0928671  |   0.13926   |    0.451727 |  0.421788 |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### out of range: baseline


### out of range: detailed

 - Ensemble Qanth min value of -173.4017 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

