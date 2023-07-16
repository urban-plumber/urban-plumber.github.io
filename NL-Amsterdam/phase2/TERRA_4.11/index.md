# NL-Amsterdam: TERRA_4.11

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](TERRA_4.11_NL-Amsterdam_baseline_attrs.md)
- [Detailed](TERRA_4.11_NL-Amsterdam_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |       MBE |        nSD |          R |        5th |      95th |      RMSE |      cRMSE |      AMBE |       1-nSD |         1-R |   nSkewness |   nKurtosis |     Overlap |
|:-------|:-------------|----------:|----------:|-----------:|-----------:|-----------:|----------:|----------:|-----------:|----------:|------------:|------------:|------------:|------------:|------------:|
| SWup   | baseline     |   3.34232 |  -2.04156 |   0.911337 |   0.984617 |   0.355085 |   5.89646 |   5.13736 |   0.18947  |   2.04156 |   0.0886635 |   0.0153829 |   0.0597711 |    0.236564 |   0.0704019 |
| SWup   | detailed     |   3.39569 |   1.40306 |   1.03104  |   0.984636 |   0.496399 |   3.45222 |   4.70947 |   0.180682 |   1.40306 |   0.0310405 |   0.0153644 |   0.0600052 |    0.237183 |   0.0652075 |
| LWup   | baseline     |  37.7412  | -37.6268  |   0.925778 |   0.782597 |  47.2305   |  54.6939  |  45.1452  |   0.638782 |  37.6268  |   0.0742235 |   0.217403  |   1.19554   |    1.39381  |   0.321707  |
| LWup   | detailed     |   7.36358 |   3.94493 |   1.16318  |   0.988068 |   5.01891  |  17.565   |   9.92492 |   0.233205 |   3.94493 |   0.163174  |   0.0119321 |   0.0460034 |    0.095557 |   0.0752053 |
| Qle    | baseline     |  21.974   | -18.4401  |   0.64703  |   0.638593 |   3.58638  |  35.1088  |  32.7109  |   0.769591 |  18.4401  |   0.352971  |   0.361407  |   0.273583  |    0.506831 |   0.470183  |
| Qle    | detailed     |  23.2356  | -19.9604  |   0.635066 |   0.625691 |   3.64767  |  36.439   |  33.8896  |   0.780127 |  19.9604  |   0.364935  |   0.374309  |   0.222986  |    0.566873 |   0.519098  |
| Qh     | baseline     |  81.3232  |  79.1052  |   1.22892  |   0.857995 |  59.8041   | 141.821   |  98.7063  |   0.633585 |  79.1052  |   0.228918  |   0.142005  |   0.514132  |    0.807217 |   0.448945  |
| Qh     | detailed     |  54.7112  |  49.632   |   1.02744  |   0.858929 |  45.1498   |  64.9935  |  70.6165  |   0.539106 |  49.632   |   0.0274371 |   0.141071  |   0.429244  |    0.836918 |   0.339028  |
| Qtau   | baseline     | nan       | nan       | nan        | nan        | nan        | nan       | nan       | nan        | nan       | nan         | nan         | nan         |  nan        | nan         |
| Qtau   | detailed     | nan       | nan       | nan        | nan        | nan        | nan       | nan       | nan        | nan       | nan         | nan         | nan         |  nan        | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![TERRA_4.11_NL-Amsterdam_subset_SWup_v0-9.png](TERRA_4.11_NL-Amsterdam_subset_SWup_v0-9.png)](TERRA_4.11_NL-Amsterdam_subset_SWup_v0-9.png)

### out of range: baseline

 - TERRA_4.11 SWup min value of -0.0021 is less than expected 0.0 [W/m2]
 - TERRA_4.11 Albedo min value of -0.0835 is less than expected 0.0 [1]

### out of range: detailed

 - TERRA_4.11 SWup min value of -0.0017 is less than expected 0.0 [W/m2]
 - TERRA_4.11 Albedo min value of -0.0688 is less than expected 0.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

