# NL-Amsterdam: UCLEM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](UCLEM_NL-Amsterdam_baseline_attrs.md)
- [Detailed](UCLEM_NL-Amsterdam_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |        MBE |      nSD |        R |        5th |      95th |      RMSE |    cRMSE |      AMBE |      1-nSD |       1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|----------:|-----------:|---------:|---------:|-----------:|----------:|----------:|---------:|----------:|-----------:|----------:|------------:|------------:|----------:|
| SWup   | baseline     | 16.1658   |  16.126    | 1.53284  | 0.988412 |  1.04637   | 41.4007   | 21.3965   | 0.565193 | 16.126    | 0.532839   | 0.0115878 |   0.0234927 |   0.0408173 | 0.0996415 |
| SWup   | detailed     |  2.52942  |   0.370871 | 0.99359  | 0.986539 |  0.389067  |  0.648999 |  4.08942  | 0.16368  |  0.370871 | 0.00641071 | 0.0134612 |   0.0445915 |   0.183107  | 0.0610664 |
| LWup   | baseline     | 12.9463   |  10.7657   | 1.28185  | 0.980089 |  2.61089   | 35.3468   | 17.7456   | 0.361228 | 10.7657   | 0.281849   | 0.0199112 |   0.0496801 |   0.249314  | 0.117141  |
| LWup   | detailed     |  9.35761  |   5.90412  | 1.19901  | 0.982676 |  4.88869   | 23.4279   | 12.5942   | 0.284861 |  5.90412  | 0.199004   | 0.0173238 |   0.054727  |   0.116859  | 0.0869115 |
| Qle    | baseline     | 21.6461   | -14.2846   | 0.937458 | 0.632485 |  4.56958   | 13.3965   | 32.5288   | 0.832448 | 14.2846   | 0.0625429  | 0.367515  |   0.0804467 |   0.11452   | 0.417986  |
| Qle    | detailed     | 22.75     | -15.5719   | 0.955389 | 0.587115 |  4.52828   | 18.272    | 34.8896   | 0.889337 | 15.5719   | 0.0446116  | 0.412885  |   0.734538  |   1.50077   | 0.425344  |
| Qh     | baseline     | 32.7054   | -15.7766   | 0.791904 | 0.859012 |  6.1969    | 41.5273   | 50.632    | 0.516335 | 15.7766   | 0.208096   | 0.140988  |   0.743639  |   0.59191   | 0.14562   |
| Qh     | detailed     | 40.4889   |  28.5242   | 1.00895  | 0.864608 | 28.4374    | 48.9824   | 56.448    | 0.52277  | 28.5242   | 0.00895188 | 0.135392  |   0.746717  |   0.586027  | 0.247187  |
| Qtau   | baseline     |  0.299901 |  -0.273504 | 0.463068 | 0.736822 |  0.0218099 |  0.90648  |  0.520338 | 0.729407 |  0.273504 | 0.536932   | 0.263178  |   0.293046  |   0.646354  | 0.219501  |
| Qtau   | detailed     |  0.242319 |  -0.197456 | 0.58162  | 0.76083  |  0.0261099 |  0.68368  |  0.453786 | 0.673242 |  0.197456 | 0.41838    | 0.23917   |   0.285585  |   0.641595  | 0.145381  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![UCLEM_NL-Amsterdam_subset_SWup_v0-9.png](UCLEM_NL-Amsterdam_subset_SWup_v0-9.png)](UCLEM_NL-Amsterdam_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed

 - UCLEM Qle max value of 715.5164 is greater than expected 700.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

