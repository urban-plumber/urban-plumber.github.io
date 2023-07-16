# KR-Jungnang: UCLEM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](UCLEM_KR-Jungnang_baseline_attrs.md)
- [Detailed](UCLEM_KR-Jungnang_detailed_attrs.md)

### Error metrics

| flux   | experiment   |     MAE |      MBE |      nSD |        R |      5th |     95th |    RMSE |    cRMSE |    AMBE |     1-nSD |       1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|--------:|---------:|---------:|---------:|---------:|---------:|--------:|---------:|--------:|----------:|----------:|------------:|------------:|----------:|
| SWup   | baseline     | 15.7266 |  15.6555 | 1.21307  | 0.907532 |  7.09274 |  22.6688 | 23.145  | 0.519368 | 15.6555 | 0.213073  | 0.0924683 |    0.53817  |    1.32015  | 0.166951  |
| SWup   | detailed     | 11.3376 |  10.197  | 1.13164  | 0.88425  |  5.90004 |  10.917  | 20.1214 | 0.528489 | 10.197  | 0.131634  | 0.11575   |    0.646636 |    1.38563  | 0.132893  |
| LWup   | baseline     | 22.6449 |  21.03   | 1.25706  | 0.980927 |  1.18312 |  61.8529 | 31.0802 | 0.33768  | 21.03   | 0.257054  | 0.0190725 |    1.04715  |    0.604678 | 0.0989788 |
| LWup   | detailed     | 16.3937 |  11.8921 | 1.23118  | 0.98171  |  5.74888 |  51.1656 | 24.3669 | 0.31382  | 11.8921 | 0.231182  | 0.0182904 |    1.18787  |    0.697863 | 0.0786045 |
| Qle    | baseline     | 19.0146 | -12.038  | 0.743074 | 0.367426 |  7.32476 |  38.3324 | 30.9928 | 1.00305  | 12.038  | 0.256927  | 0.632574  |    1.72431  |    3.48441  | 0.475045  |
| Qle    | detailed     | 20.7239 | -13.003  | 0.903762 | 0.297327 |  7.00386 |  44.3882 | 34.731  | 1.13109  | 13.003  | 0.0962396 | 0.702673  |    3.62346  |   13.1464   | 0.587524  |
| Qh     | baseline     | 39.5459 | -20.1118 | 0.803139 | 0.691557 |  5.84973 |  40.6615 | 59.5176 | 0.730889 | 20.1118 | 0.196863  | 0.308443  |    0.399094 |    1.69946  | 0.213535  |
| Qh     | detailed     | 61.6478 |  50.3603 | 1.2387   | 0.795653 | 42.8125  | 102.219  | 76.4493 | 0.750482 | 50.3603 | 0.238693  | 0.204347  |    0.185034 |    0.329789 | 0.427632  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![UCLEM_KR-Jungnang_subset_SWup_v0-9.png](UCLEM_KR-Jungnang_subset_SWup_v0-9.png)](UCLEM_KR-Jungnang_subset_SWup_v0-9.png)

### out of range: baseline

 - UCLEM Qstor min value of -1042.8740 is less than expected -800.0 [W/m2]
 - UCLEM Qle max value of 993.0044 is greater than expected 700.0 [W/m2]

### out of range: detailed

 - UCLEM Qle max value of 922.2186 is greater than expected 700.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

