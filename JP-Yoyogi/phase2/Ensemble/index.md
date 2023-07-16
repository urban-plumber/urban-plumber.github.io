# JP-Yoyogi: Ensemble

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](Ensemble_JP-Yoyogi_baseline_attrs.md)
- [Detailed](Ensemble_JP-Yoyogi_detailed_attrs.md)

### Error metrics

| flux   | experiment   |      MAE |       MBE |      nSD |        R |       5th |     95th |     RMSE |    cRMSE |     AMBE |     1-nSD |       1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|---------:|----------:|---------:|---------:|----------:|---------:|---------:|---------:|---------:|----------:|----------:|------------:|------------:|----------:|
| SWup   | baseline     |  5.61036 |   1.01254 | 1.08175  | 0.967705 |  1.07219  |  9.91951 |  9.27338 | 0.276684 |  1.01254 | 0.0817533 | 0.0322949 |    0.177744 |    0.287482 | 0.0845528 |
| SWup   | detailed     |  6.894   |   3.8034  | 1.15381  | 0.967372 |  0.680537 | 17.7825  | 11.1488  | 0.314565 |  3.8034  | 0.153808  | 0.0326284 |    0.186704 |    0.249209 | 0.0983871 |
| LWup   | baseline     | 13.4133  |   8.79218 | 1.30002  | 0.974174 |  8.12719  | 48.9759  | 21.9211  | 0.396432 |  8.79218 | 0.300017  | 0.0258257 |    1.70911  |    1.30522  | 0.0819825 |
| LWup   | detailed     |  9.51106 |   6.59715 | 1.1844   | 0.963123 |  1.29624  | 31.3923  | 18.8386  | 0.348361 |  6.59715 | 0.184394  | 0.0368768 |    4.39847  |   24.2235   | 0.0540894 |
| Qle    | baseline     | 21.712   | -17.3801  | 0.52519  | 0.581218 |  0.484953 | 54.6675  | 35.6403  | 0.815674 | 17.3801  | 0.47481   | 0.418782  |    0.257927 |    0.721481 | 0.340223  |
| Qle    | detailed     | 17.514   | -12.2821  | 0.572459 | 0.670943 |  1.38443  | 42.6774  | 31.0656  | 0.74802  | 12.2821  | 0.427541  | 0.329057  |    0.209051 |    0.447645 | 0.226721  |
| Qh     | baseline     | 27.7151  |  19.5031  | 1.15283  | 0.891453 | 20.1147   | 46.2945  | 39.6733  | 0.523097 | 19.5031  | 0.152831  | 0.108547  |    0.141508 |    0.247923 | 0.209122  |
| Qh     | detailed     | 24.2825  |  14.4447  | 1.02577  | 0.890853 | 21.5887   | 21.6838  | 34.4717  | 0.473902 | 14.4447  | 0.0257665 | 0.109147  |    0.202931 |    0.88718  | 0.2296    |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### out of range: baseline

 - Ensemble TairSurf max value of 345.8474 is greater than expected 333.0 [K]

### out of range: detailed

 - Ensemble Qstor min value of -2030.2701 is less than expected -800.0 [W/m2]
 - Ensemble LWnet min value of -1585.5298 is less than expected -500.0 [W/m2]
 - Ensemble TairSurf max value of 341.8933 is greater than expected 333.0 [K]
 - Ensemble Qh max value of 918.6583 is greater than expected 600.0 [W/m2]
 - Ensemble LWup max value of 2002.2604 is greater than expected 1000.0 [W/m2]
 - Ensemble Qstar min value of -1494.1964 is less than expected -500.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

