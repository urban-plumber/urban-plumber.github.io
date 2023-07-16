# JP-Yoyogi: NOAH-SLUCM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](NOAH-SLUCM_JP-Yoyogi_baseline_attrs.md)
- [Detailed](NOAH-SLUCM_JP-Yoyogi_detailed_attrs.md)

### Error metrics

| flux   | experiment   |      MAE |       MBE |      nSD |        R |       5th |    95th |    RMSE |    cRMSE |     AMBE |     1-nSD |       1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|---------:|----------:|---------:|---------:|----------:|--------:|--------:|---------:|---------:|----------:|----------:|------------:|------------:|----------:|
| SWup   | baseline     | 11.6078  |   9.93319 | 1.32462  | 0.966551 |  0.965878 | 35.5604 | 17.7196 | 0.440443 |  9.93319 | 0.324614  | 0.0334495 |   0.202505  |   0.290086  | 0.143866  |
| SWup   | detailed     |  8.42021 |  -7.21023 | 0.877666 | 0.9671   |  1.44116  | 11.0547 | 11.5195 | 0.269659 |  7.21023 | 0.122335  | 0.0328999 |   0.198473  |   0.281451  | 0.106563  |
| LWup   | baseline     | 28.9916  |  28.2997  | 1.44557  | 0.950125 |  1.06598  | 87.5254 | 40.9907 | 0.585432 | 28.2997  | 0.445572  | 0.0498746 |   2.11491   |   1.66006   | 0.129792  |
| LWup   | detailed     | 33.7073  |  33.6871  | 1.39477  | 0.963165 | 10.0262   | 85.363  | 42.4066 | 0.508525 | 33.6871  | 0.394772  | 0.0368347 |   1.85685   |   1.40965   | 0.160906  |
| Qle    | baseline     | 27.9489  | -26.7372  | 0.240218 | 0.614754 |  0.373481 | 84.6064 | 42.7111 | 0.873129 | 26.7372  | 0.759782  | 0.385246  |   1.64512   |  14.6877    | 0.586161  |
| Qle    | detailed     | 27.9442  | -26.7311  | 0.23849  | 0.61923  |  0.373481 | 84.5784 | 42.693  | 0.87265  | 26.7311  | 0.76151   | 0.38077   |   1.36224   |  11.2272    | 0.583986  |
| Qh     | baseline     | 22.3974  |  -1.48645 | 1.13086  | 0.894708 |  1.02591  | 23.3253 | 33.402  | 0.505237 |  1.48645 | 0.130858  | 0.105292  |   0.104178  |   0.0864849 | 0.162746  |
| Qh     | detailed     | 20.8298  |   1.00124 | 1.05553  | 0.894954 |  3.28309  | 13.9674 | 31.3333 | 0.474175 |  1.00124 | 0.0555252 | 0.105046  |   0.0776207 |   0.0715587 | 0.0674335 |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![NOAH-SLUCM_JP-Yoyogi_subset_SWup_v0-9.png](NOAH-SLUCM_JP-Yoyogi_subset_SWup_v0-9.png)](NOAH-SLUCM_JP-Yoyogi_subset_SWup_v0-9.png)

### out of range: baseline

 - NOAH-SLUCM TairSurf max value of 855.3789 is greater than expected 333.0 [K]

### out of range: detailed

 - NOAH-SLUCM TairSurf max value of 998.3037 is greater than expected 333.0 [K]


[Link to variable definitions](../modelattrs/variable_definitions.md)

