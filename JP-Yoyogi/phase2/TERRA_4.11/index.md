# JP-Yoyogi: TERRA_4.11

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](TERRA_4.11_JP-Yoyogi_baseline_attrs.md)
- [Detailed](TERRA_4.11_JP-Yoyogi_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |        MBE |      nSD |        R |        5th |      95th |      RMSE |    cRMSE |       AMBE |     1-nSD |       1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|----------:|-----------:|---------:|---------:|-----------:|----------:|----------:|---------:|-----------:|----------:|----------:|------------:|------------:|----------:|
| SWup   | baseline     |  15.0484  | -14.8114   | 0.680736 | 0.965569 |   1.6549   |  31.4828  |  19.6098  | 0.385754 |  14.8114   | 0.319265  | 0.0344307 |   0.212154  |    0.309667 | 0.144758  |
| SWup   | detailed     |   5.69008 |  -0.414431 | 1.05657  | 0.965593 |   1.25628  |   7.87068 |   9.18834 | 0.275515 |   0.414431 | 0.0565735 | 0.0344073 |   0.216126  |    0.322375 | 0.0972411 |
| LWup   | baseline     |  39.6603  | -39.6554   | 1.16411  | 0.903359 |  61.8915   |  37.4283  |  47.1058  | 0.501929 |  39.6554   | 0.164106  | 0.0966415 |   1.49739   |    0.384862 | 0.255084  |
| LWup   | detailed     |  12.9767  |  12.2649   | 1.23427  | 0.983111 |   0.104753 |  42.4276  |  19.9552  | 0.310762 |  12.2649   | 0.234269  | 0.0168889 |   1.46428   |    1.08588  | 0.0711579 |
| Qle    | baseline     |  21.8912  | -17.2522   | 0.600394 | 0.560961 |   0.351438 |  48.4938  |  36.0161  | 0.828781 |  17.2522   | 0.399606  | 0.439039  |   0.277733  |    0.437096 | 0.368222  |
| Qle    | detailed     |  21.2171  | -17.5795   | 0.558457 | 0.586504 |   0.311905 |  51.0429  |  35.564   | 0.810432 |  17.5795   | 0.441543  | 0.413496  |   0.145683  |    0.117913 | 0.368951  |
| Qh     | baseline     | 163.404   | 163.32     | 1.74672  | 0.860292 | 110.192    | 262.1     | 176.733   | 1.02257  | 163.32     | 0.746713  | 0.139708  |   0.174703  |    0.536603 | 0.755354  |
| Qh     | detailed     |  40.6123  |  36.2764   | 1.06868  | 0.887932 |  32.7493   |  44.8787  |  48.7996  | 0.494215 |  36.2764   | 0.0686823 | 0.112068  |   0.0256545 |    0.113596 | 0.36373   |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![TERRA_4.11_JP-Yoyogi_subset_SWup_v0-9.png](TERRA_4.11_JP-Yoyogi_subset_SWup_v0-9.png)](TERRA_4.11_JP-Yoyogi_subset_SWup_v0-9.png)

### out of range: baseline

 - TERRA_4.11 Qh max value of 693.7244 is greater than expected 600.0 [W/m2]

### out of range: detailed



[Link to variable definitions](../modelattrs/variable_definitions.md)

