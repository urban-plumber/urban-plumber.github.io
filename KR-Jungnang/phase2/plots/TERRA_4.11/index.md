# KR-Jungnang: TERRA_4.11

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](TERRA_4.11_KR-Jungnang_baseline_attrs.md)
- [Detailed](TERRA_4.11_KR-Jungnang_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |        MBE |      nSD |        R |       5th |      95th |      RMSE |    cRMSE |       AMBE |     1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|----------:|-----------:|---------:|---------:|----------:|----------:|----------:|---------:|-----------:|----------:|-----------:|------------:|------------:|----------:|
| SWup   | baseline     |  15.4422  | -14.5152   | 0.615283 | 0.982469 |   2.51931 |  35.6145  |  19.8339  | 0.411802 |  14.5152   | 0.384718  | 0.0175312  |   0.0651511 |  0.0045711  | 0.186554  |
| SWup   | detailed     |   5.38306 |  -0.246049 | 0.889796 | 0.982568 |   4.83887 |   4.92468 |   6.82384 | 0.207766 |   0.246049 | 0.110205  | 0.017432   |   0.0631022 |  0.00560474 | 0.114984  |
| LWup   | baseline     |  51.2073  | -51.1316   | 1.05332  | 0.926491 |  62.6895  |  53.5666  |  57.7818  | 0.397113 |  51.1316   | 0.0533167 | 0.0735088  |   0.72657   |  0.247757   | 0.248776  |
| LWup   | detailed     |  10.4556  |   7.47909  | 1.1672   | 0.991756 |   3.8802  |  36.2335  |  16.5144  | 0.217258 |   7.47909  | 0.167197  | 0.00824446 |   1.01295   |  0.546859   | 0.0646883 |
| Qle    | baseline     |  18.1267  | -12.2983   | 0.543853 | 0.407355 |   7.31988 |  38.1747  |  29.0262  | 0.923414 |  12.2983   | 0.456148  | 0.592645   |   1.24204   |  1.17396    | 0.48987   |
| Qle    | detailed     |  18.1536  | -12.5828   | 0.522901 | 0.412521 |   7.3179  |  38.6739  |  28.9989  | 0.917611 |  12.5828   | 0.4771    | 0.587479   |   1.20478   |  1.05764    | 0.521756  |
| Qh     | baseline     | 182.286   | 181.93     | 1.73347  | 0.766121 | 119.413   | 303.411   | 202.537   | 1.16139  | 181.93     | 0.733462  | 0.233879   |   0.0934787 |  0.585266   | 0.700339  |
| Qh     | detailed     | 105.065   | 103.105    | 1.42569  | 0.805504 |  73.2818  | 170.113   | 122.281   | 0.857787 | 103.105    | 0.42569   | 0.194496   |   0.158315  |  0.897062   | 0.595509  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![TERRA_4.11_KR-Jungnang_subset_SWup_v0-9.png](TERRA_4.11_KR-Jungnang_subset_SWup_v0-9.png)](TERRA_4.11_KR-Jungnang_subset_SWup_v0-9.png)

### out of range: baseline

 - TERRA_4.11 Qh max value of 791.7789 is greater than expected 600.0 [W/m2]
 - TERRA_4.11 SWup min value of -0.0015 is less than expected 0.0 [W/m2]
 - TERRA_4.11 Albedo min value of -0.0881 is less than expected 0.0 [1]

### out of range: detailed

 - TERRA_4.11 Qh max value of 611.9849 is greater than expected 600.0 [W/m2]
 - TERRA_4.11 SWup min value of -0.0007 is less than expected 0.0 [W/m2]
 - TERRA_4.11 Albedo min value of -0.0434 is less than expected 0.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

