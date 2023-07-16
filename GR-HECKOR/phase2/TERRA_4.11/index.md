# GR-HECKOR: TERRA_4.11

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](TERRA_4.11_GR-HECKOR_baseline_attrs.md)
- [Detailed](TERRA_4.11_GR-HECKOR_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |       MBE |        nSD |          R |       5th |      95th |      RMSE |      cRMSE |      AMBE |       1-nSD |          1-R |   nSkewness |   nKurtosis |     Overlap |
|:-------|:-------------|----------:|----------:|-----------:|-----------:|----------:|----------:|----------:|-----------:|----------:|------------:|-------------:|------------:|------------:|------------:|
| SWup   | baseline     |  51.1343  | -51.1342  |   0.454474 |   0.993118 |   3.64201 | 106.572   |  61.3094  |   0.55123  |  51.1342  |   0.545527  |   0.00688165 |   0.217846  |   0.0606369 |   0.122499  |
| SWup   | detailed     |   6.46208 |  -3.51314 |   1.048    |   0.993152 |   2.73657 |   2.34849 |   8.66427 |   0.129069 |   3.51314 |   0.0480043 |   0.00684846 |   0.213717  |   0.0613402 |   0.0994074 |
| LWup   | baseline     |  53.8845  | -53.8711  |   0.762241 |   0.857159 |  48.0366  |  80.7923  |  58.5201  |   0.523725 |  53.8711  |   0.23776   |   0.142841   |   1.09165   |   0.105208  |   0.391158  |
| LWup   | detailed     |  20.0178  |  16.6043  |   1.44434  |   0.960914 |   1.01151 |  64.6433  |  29.443   |   0.557084 |  16.6043  |   0.444334  |   0.0390863  |   0.941266  |   0.761807  |   0.108788  |
| Qle    | baseline     |  25.1986  | -19.7259  |   0.453061 |   0.181912 |   3.35799 |  61.9373  |  41.163   |   1.02001  |  19.7259  |   0.546939  |   0.818088   |   1.68551   |   3.64159   |   0.562531  |
| Qle    | detailed     |  24.8687  | -20.3296  |   0.381451 |   0.201519 |   3.36589 |  63.2689  |  40.7127  |   0.995874 |  20.3296  |   0.618549  |   0.798481   |   1.20854   |   1.99072   |   0.580906  |
| Qh     | baseline     | 116.214   | 116.084   |   1.61787  |   0.945205 |  55.3913  | 262.725   | 140.502   |   0.747706 | 116.084   |   0.617871  |   0.0547948  |   0.0896033 |   0.752302  |   0.509722  |
| Qh     | detailed     |  42.4219  |  36.6082  |   1.31077  |   0.943271 |  15.7304  | 114.647   |  63.9465  |   0.495274 |  36.6082  |   0.310772  |   0.0567292  |   0.0679922 |   0.735737  |   0.269977  |
| Qtau   | baseline     | nan       | nan       | nan        | nan        | nan       | nan       | nan       | nan        | nan       | nan         | nan          | nan         | nan         | nan         |
| Qtau   | detailed     | nan       | nan       | nan        | nan        | nan       | nan       | nan       | nan        | nan       | nan         | nan          | nan         | nan         | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![TERRA_4.11_GR-HECKOR_subset_SWup_v0-9.png](TERRA_4.11_GR-HECKOR_subset_SWup_v0-9.png)](TERRA_4.11_GR-HECKOR_subset_SWup_v0-9.png)

### out of range: baseline

 - TERRA_4.11 Qh max value of 714.9194 is greater than expected 600.0 [W/m2]
 - TERRA_4.11 SWup min value of -0.0027 is less than expected 0.0 [W/m2]
 - TERRA_4.11 Albedo min value of -0.1729 is less than expected 0.0 [1]

### out of range: detailed

 - TERRA_4.11 SWup min value of -0.0004 is less than expected 0.0 [W/m2]
 - TERRA_4.11 Albedo min value of -0.0280 is less than expected 0.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

