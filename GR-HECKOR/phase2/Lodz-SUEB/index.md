# GR-HECKOR: Lodz-SUEB

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](Lodz-SUEB_GR-HECKOR_baseline_attrs.md)
- [Detailed](Lodz-SUEB_GR-HECKOR_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |        MBE |      nSD |        R |         5th |      95th |      RMSE |    cRMSE |      AMBE |      1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|----------:|-----------:|---------:|---------:|------------:|----------:|----------:|---------:|----------:|-----------:|-----------:|------------:|------------:|----------:|
| SWup   | baseline     | 24.3007   | -24.2993   | 0.788639 | 0.993175 |  3.12954    | 45.2847   | 28.2702   | 0.235453 | 24.2993   | 0.211362   | 0.00682469 |   0.210954  |   0.0617628 | 0.107622  |
| SWup   | detailed     |  6.41843  |  -3.20814  | 1.05152  | 0.993175 |  2.72824    |  2.9486   |  8.62143  | 0.13041  |  3.20814  | 0.0515173  | 0.00682469 |   0.210954  |   0.0617628 | 0.100468  |
| LWup   | baseline     | 26.7673   |  25.8094   | 1.60245  | 0.957031 |  2.45541    | 90.3416   | 40.2474   | 0.70757  | 25.8094   | 0.602444   | 0.0429693  |   1.03506   |   0.835556  | 0.0996101 |
| LWup   | detailed     | 27.4834   |  27.3634   | 1.51616  | 0.962469 |  7.63431    | 83.496    | 38.3806   | 0.616625 | 27.3634   | 0.516156   | 0.0375308  |   0.993379  |   0.819807  | 0.126922  |
| Qle    | baseline     | 22.0342   |  -6.78468  | 0.920883 | 0.309027 |  3.46753    | 28.8442   | 40.6258   | 1.13087  |  6.78468  | 0.0791175  | 0.690973   |   2.09545   |   7.68658   | 0.40492   |
| Qle    | detailed     | 22.2742   |  -6.47678  | 0.933448 | 0.29835  |  3.53813    | 29.4693   | 41.1202   | 1.14645  |  6.47678  | 0.0665524  | 0.70165    |   1.97091   |   6.91286   | 0.396864  |
| Qh     | baseline     | 21.8412   |   1.65782  | 1.00754  | 0.946011 |  9.74328    | 12.1219   | 34.9656   | 0.329922 |  1.65782  | 0.00754489 | 0.0539885  |   0.0299287 |   0.537493  | 0.136064  |
| Qh     | detailed     | 22.3672   |   5.35602  | 0.962335 | 0.944821 | 12.8785     |  2.49549  | 35.1392   | 0.328055 |  5.35602  | 0.037664   | 0.0551791  |   0.0653712 |   0.638296  | 0.128049  |
| Qtau   | baseline     |  0.263403 |  -0.26258  | 0.351893 | 0.915441 |  0.018419   |  0.78011  |  0.395726 | 0.692498 |  0.26258  | 0.648107   | 0.084559   |   0.125802  |   0.287356  | 0.289329  |
| Qtau   | detailed     |  0.141545 |  -0.113273 | 0.68553  | 0.931098 |  0.00106995 |  0.379802 |  0.219482 | 0.439728 |  0.113273 | 0.314471   | 0.0689024  |   0.0626706 |   0.155599  | 0.138424  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![Lodz-SUEB_GR-HECKOR_subset_SWup_v0-9.png](Lodz-SUEB_GR-HECKOR_subset_SWup_v0-9.png)](Lodz-SUEB_GR-HECKOR_subset_SWup_v0-9.png)

### out of range: baseline

 - Lodz-SUEB Qle max value of 831.1957 is greater than expected 700.0 [W/m2]

### out of range: detailed

 - Lodz-SUEB Qle max value of 829.2733 is greater than expected 700.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

