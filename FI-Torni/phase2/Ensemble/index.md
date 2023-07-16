# FI-Torni: Ensemble

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](Ensemble_FI-Torni_baseline_attrs.md)
- [Detailed](Ensemble_FI-Torni_detailed_attrs.md)

### Error metrics

| flux   | experiment   |      MAE |        MBE |      nSD |        R |      5th |    95th |    RMSE |    cRMSE |      AMBE |    1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|---------:|-----------:|---------:|---------:|---------:|--------:|--------:|---------:|----------:|---------:|-----------:|------------:|------------:|----------:|
| SWup   | baseline     | 17.2774  |  17.107    | 1.6201   | 0.886242 |  2.75997 | 49.8323 | 29.2808 | 0.867831 | 17.107    | 0.620106 | 0.113758   |  1.27485    |    2.02353  |  0.198852 |
| SWup   | detailed     |  9.04936 |   7.58618  | 1.34116  | 0.864757 |  2.19831 | 26.1308 | 20.4165 | 0.692211 |  7.58618  | 0.341163 | 0.135243   |  1.65849    |    2.87335  |  0.1366   |
| LWup   | baseline     |  9.90089 |  -1.72409  | 1.21082  | 0.988301 | 13.2982  | 25.0415 | 13.327  | 0.269772 |  1.72409  | 0.210821 | 0.0116991  |  0.864493   |    0.647266 |  0.119154 |
| LWup   | detailed     |  8.57502 |  -0.836693 | 1.18046  | 0.990155 |  8.21647 | 22.1382 | 11.6027 | 0.236242 |  0.836693 | 0.180461 | 0.00984504 |  0.896488   |    0.507519 |  0.111572 |
| Qle    | baseline     | 15.8203  |  -8.31052  | 0.556365 | 0.524218 |  6.24641 | 29.8207 | 28.2052 | 0.852191 |  8.31052  | 0.443635 | 0.475782   |  0.00468013 |    0.078179 |  0.352809 |
| Qle    | detailed     | 15.4006  |  -6.83322  | 0.580372 | 0.526322 |  6.65353 | 25.4833 | 27.8    | 0.852001 |  6.83322  | 0.419628 | 0.473678   |  0.148345   |    0.415035 |  0.314054 |
| Qh     | baseline     | 35.4873  | -22.3236   | 0.8388   | 0.776673 |  4.74345 | 31.6262 | 49.9809 | 0.63296  | 22.3236   | 0.161202 | 0.223327   |  0.340699   |    0.441829 |  0.337555 |
| Qh     | detailed     | 33.3185  | -19.5349   | 0.850407 | 0.795864 |  4.30993 | 26.4227 | 47.1838 | 0.607927 | 19.5349   | 0.149594 | 0.204136   |  0.305912   |    0.377661 |  0.288162 |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### out of range: baseline


### out of range: detailed

 - Ensemble Qanth max value of 1397.0539 is greater than expected 1000.0 [W/m2]
 - Ensemble Qanth min value of -253.3498 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

