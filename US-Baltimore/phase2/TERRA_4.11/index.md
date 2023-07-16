# US-Baltimore: TERRA_4.11

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](TERRA_4.11_US-Baltimore_baseline_attrs.md)
- [Detailed](TERRA_4.11_US-Baltimore_detailed_attrs.md)

### Error metrics

| flux     | experiment   |       MAE |        MBE |        nSD |          R |         5th |      95th |      RMSE |      cRMSE |       AMBE |       1-nSD |         1-R |   nSkewness |   nKurtosis |     Overlap |
|:---------|:-------------|----------:|-----------:|-----------:|-----------:|------------:|----------:|----------:|-----------:|-----------:|------------:|------------:|------------:|------------:|------------:|
| SWup     | baseline     |  77.105   |   1.63778  |   3.59588  |   0.756735 | 143.191     | 154.085   |  97.7115  |   2.91344  |   1.63778  |   2.59588   |   0.243265  |   0.472799  |   0.529067  |   0.540222  |
| SWup     | detailed     |   8.4451  |   4.60144  |   1.32128  |   0.92051  |   0.0991584 |  17.4724  |  19.3249  |   0.55971  |   4.60144  |   0.321278  |   0.0794898 |   3.07383   |  17.1401    |   0.0919451 |
| LWup     | baseline     |  17.6916  | -16.2519   |   1.04754  |   0.970977 |  24.5176    |  12.3849  |  21.3713  |   0.251128 |  16.2519   |   0.0475351 |   0.0290231 |   0.978806  |   0.189411  |   0.117376  |
| LWup     | detailed     |   8.35975 |   0.779342 |   1.12185  |   0.983996 |   5.72699   |  23.1036  |  12.4749  |   0.225291 |   0.779342 |   0.121848  |   0.0160043 |   5.84291   |   0.475941  |   0.0687614 |
| Qle      | baseline     |  25.7264  |  -3.17835  |   0.930605 |   0.8168   |  14.728     |  13.0413  |  42.6561  |   0.588038 |   3.17835  |   0.0693951 |   0.1832    |   0.061018  |   0.0224348 |   0.251111  |
| Qle      | detailed     |  26.8922  |  -3.9955   |   0.98406  |   0.801769 |  14.6101    |   7.98882 |  45.3742  |   0.624817 |   3.9955   |   0.0159408 |   0.198231  |   0.138559  |   0.203921  |   0.274353  |
| Qh       | baseline     |  49.286   |  25.286    |   0.780356 |   0.759588 |  48.3535    |  23.7308  |  63.0025  |   0.650736 |  25.286    |   0.219645  |   0.240412  |   0.0233682 |   0.234782  |   0.49661   |
| Qh       | detailed     |  33.0833  |  11.4115   |   1.02907  |   0.854199 |   9.90758   |  13.1614  |  49.9661  |   0.548567 |  11.4115   |   0.0290732 |   0.145801  |   0.0243334 |   0.245274  |   0.14139   |
| SoilTemp | baseline     |   3.60758 |  -1.44074  |   1.1542   |   0.924485 |   4.53928   |   1.97882 |   4.40484 |   0.445079 |   1.44074  |   0.154192  |   0.0755153 |   0.85817   |   0.373959  |   0.161576  |
| SoilTemp | detailed     |   3.28712 |  -1.949    |   1.08715  |   0.937722 |   4.12473   |   0.21283 |   4.0382  |   0.378162 |   1.949    |   0.0871493 |   0.0622778 |   1.69742   |   0.308666  |   0.144156  |
| Qtau     | baseline     | nan       | nan        | nan        | nan        | nan         | nan       | nan       | nan        | nan        | nan         | nan         | nan         | nan         | nan         |
| Qtau     | detailed     | nan       | nan        | nan        | nan        | nan         | nan       | nan       | nan        | nan        | nan         | nan         | nan         | nan         | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![TERRA_4.11_US-Baltimore_subset_SWup_v0-9.png](TERRA_4.11_US-Baltimore_subset_SWup_v0-9.png)](TERRA_4.11_US-Baltimore_subset_SWup_v0-9.png)

### out of range: baseline

 - TERRA_4.11 SWup min value of -270.0607 is less than expected 0.0 [W/m2]
 - TERRA_4.11 alb min value of -0.9991 is less than expected 0.0 [1]
 - TERRA_4.11 Albedo min value of -7182.1952 is less than expected 0.0 [1]

### out of range: detailed

 - TERRA_4.11 SWup min value of -0.0000 is less than expected 0.0 [W/m2]
 - TERRA_4.11 Albedo min value of -0.0011 is less than expected 0.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

