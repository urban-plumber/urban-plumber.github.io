# JP-Yoyogi: TEB-READING

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](TEB-READING_JP-Yoyogi_baseline_attrs.md)
- [Detailed](TEB-READING_JP-Yoyogi_detailed_attrs.md)

### Error metrics

| flux   | experiment   |      MAE |       MBE |      nSD |        R |       5th |    95th |    RMSE |    cRMSE |     AMBE |    1-nSD |       1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|---------:|----------:|---------:|---------:|----------:|--------:|--------:|---------:|---------:|---------:|----------:|------------:|------------:|----------:|
| SWup   | baseline     |  9.35066 |  -7.17963 | 0.882055 | 0.934507 |  1.06385  | 15.9366 | 13.9724 | 0.359789 |  7.17963 | 0.117946 | 0.0654931 |    0.839475 |    4.52199  | 0.104268  |
| SWup   | detailed     | 15.3231  | -14.291   | 0.728859 | 0.924676 |  1.39022  | 28.928  | 20.1917 | 0.428158 | 14.291   | 0.271142 | 0.0753244 |    1.21594  |    5.72249  | 0.196766  |
| LWup   | baseline     | 18.5973  |  15.7344  | 1.42503  | 0.942894 |  4.90672  | 74.8712 | 33.5956 | 0.586006 | 15.7344  | 0.425026 | 0.0571058 |    2.78475  |    2.21952  | 0.075352  |
| LWup   | detailed     | 19.2345  |  17.7702  | 1.40165  | 0.949115 |  1.94023  | 73.579  | 33.1012 | 0.551332 | 17.7702  | 0.401648 | 0.0508847 |    2.59366  |    2.02487  | 0.0764321 |
| Qle    | baseline     | 25.632   | -16.1898  | 0.79198  | 0.43042  |  0.449808 | 32.901  | 40.4712 | 0.972349 | 16.1898  | 0.20802  | 0.56958   |    0.52814  |    1.16783  | 0.402469  |
| Qle    | detailed     | 23.5998  | -13.769   | 0.762656 | 0.461362 |  0.449808 | 31.7779 | 38.3029 | 0.936976 | 13.769   | 0.237344 | 0.538638  |    0.39845  |    0.88377  | 0.294344  |
| Qh     | baseline     | 37.1496  |  31.3237  | 1.38789  | 0.890957 | 17.3277   | 91.7528 | 54.3856 | 0.673155 | 31.3237  | 0.387888 | 0.109043  |    0.129751 |    0.240441 | 0.177055  |
| Qh     | detailed     | 28.3117  |  18.3513  | 1.2691   | 0.890207 | 11.7756   | 61.9753 | 43.2233 | 0.592528 | 18.3513  | 0.269097 | 0.109793  |    0.172816 |    0.387095 | 0.106471  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![TEB-READING_JP-Yoyogi_subset_SWup_v0-9.png](TEB-READING_JP-Yoyogi_subset_SWup_v0-9.png)](TEB-READING_JP-Yoyogi_subset_SWup_v0-9.png)

### out of range: baseline

 - TEB-READING Qanth min value of -7.0370 is less than expected 0.0 [W/m2]

### out of range: detailed

 - TEB-READING Qanth min value of -21.8175 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

