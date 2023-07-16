# GR-HECKOR: SNUUCM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](SNUUCM_GR-HECKOR_baseline_attrs.md)
- [Detailed](SNUUCM_GR-HECKOR_detailed_attrs.md)

### Error metrics

| flux   | experiment   |      MAE |       MBE |        nSD |          R |       5th |     95th |     RMSE |      cRMSE |      AMBE |      1-nSD |          1-R |   nSkewness |   nKurtosis |    Overlap |
|:-------|:-------------|---------:|----------:|-----------:|-----------:|----------:|---------:|---------:|-----------:|----------:|-----------:|-------------:|------------:|------------:|-----------:|
| SWup   | baseline     |  43.2651 | -43.265   |   0.546754 |   0.993378 |   3.47397 |  89.8494 |  51.6979 |   0.461165 |  43.265   |   0.453246 |   0.00662244 |   0.100391  |   0.0825037 |   0.117841 |
| SWup   | detailed     |  46.281  | -46.2809  |   0.509122 |   0.993201 |   3.53589 |  97.117  |  55.4555 |   0.49788  |  46.2809  |   0.490878 |   0.00679944 |   0.0737386 |   0.0942556 |   0.122151 |
| LWup   | baseline     |  27.9241 |  10.2869  |   1.73398  |   0.9467   |  17.9407  |  87.2528 |  38.525  |   0.850625 |  10.2869  |   0.733971 |   0.0533002  |   1.1564    |   0.94217   |   0.20709  |
| LWup   | detailed     |  10.8255 |  -3.91059 |   1.16983  |   0.979632 |  10.0728  |  12.9485 |  12.6893 |   0.276582 |   3.91059 |   0.16983  |   0.0203682  |   0.35564   |   0.237419  |   0.134593 |
| Qle    | baseline     |  26.6689 | -18.4532  |   0.889445 |   0.168971 |   2.50707 |  66.8057 |  47.0158 |   1.22087  |  18.4532  |   0.110555 |   0.831029   |   3.14993   |   9.42833   |   0.534277 |
| Qle    | detailed     |  26.027  | -18.5986  |   0.825481 |   0.186638 |   1.01106 |  66.3385 |  45.4839 |   1.17187  |  18.5986  |   0.174519 |   0.813362   |   3.18631   |   9.7225    |   0.486302 |
| Qh     | baseline     |  37.221  |  19.5424  |   1.37183  |   0.937522 |   1.36546 | 125.235  |  62.0672 |   0.556481 |  19.5424  |   0.371826 |   0.062478   |   0.0642466 |   0.084657  |   0.23862  |
| Qh     | detailed     |  59.4103 |  46.1894  |   1.7139   |   0.940663 |  12.8594  | 228.645  | 100.62   |   0.844418 |  46.1894  |   0.713897 |   0.059337   |   0.0237346 |   0.244589  |   0.180141 |
| Qtau   | baseline     | nan      | nan       | nan        | nan        | nan       | nan      | nan      | nan        | nan       | nan        | nan          | nan         | nan         | nan        |
| Qtau   | detailed     | nan      | nan       | nan        | nan        | nan       | nan      | nan      | nan        | nan       | nan        | nan          | nan         | nan         | nan        |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![SNUUCM_GR-HECKOR_subset_SWup_v0-9.png](SNUUCM_GR-HECKOR_subset_SWup_v0-9.png)](SNUUCM_GR-HECKOR_subset_SWup_v0-9.png)

### out of range: baseline

 - SNUUCM Qle max value of 788.8508 is greater than expected 700.0 [W/m2]

### out of range: detailed

 - SNUUCM Qh max value of 728.6589 is greater than expected 600.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

