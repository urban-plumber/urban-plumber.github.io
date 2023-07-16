# PL-Narutowicza: UCLEM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](UCLEM_PL-Narutowicza_baseline_attrs.md)
- [Detailed](UCLEM_PL-Narutowicza_detailed_attrs.md)

### Error metrics

| flux   | experiment   |      MAE |       MBE |      nSD |        R |      5th |    95th |     RMSE |    cRMSE |     AMBE |     1-nSD |       1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|---------:|----------:|---------:|---------:|---------:|--------:|---------:|---------:|---------:|----------:|----------:|------------:|------------:|----------:|
| SWup   | baseline     | 18.4876  |  17.792   | 1.82566  | 0.939424 |  0.4643  | 54.1484 | 27.162   | 0.950212 | 17.792   | 0.825662  | 0.0605762 |  0.194805   |   0.0387495 | 0.234841  |
| SWup   | detailed     |  5.18397 |   1.63611 | 1.16005  | 0.927814 |  0.069   |  8.0074 |  9.63113 | 0.439426 |  1.63611 | 0.16005   | 0.0721862 |  0.43458    |   2.47971   | 0.0850786 |
| LWup   | baseline     | 14.0427  |   8.13726 | 1.13337  | 0.975111 |  0.54031 | 25.3332 | 17.8116  | 0.272406 |  8.13726 | 0.133376  | 0.0248888 |  0.307235   |   0.221382  | 0.0780744 |
| LWup   | detailed     | 12.6139  |   6.09479 | 1.07763  | 0.975271 |  2.50821 | 15.7802 | 15.4222  | 0.243566 |  6.09479 | 0.0776356 | 0.0247289 |  0.201299   |   0.0453905 | 0.0699416 |
| Qle    | baseline     | 27.6931  | -17.391   | 0.8485   | 0.519855 |  9.4279  | 32.2509 | 43.0869  | 0.915292 | 17.391   | 0.151502  | 0.480145  |  0.730118   |  10.3671    | 0.379416  |
| Qle    | detailed     | 29.1635  | -20.4156  | 0.762111 | 0.470377 | 10.2012  | 48.8729 | 44.9359  | 0.929438 | 20.4156  | 0.237891  | 0.529623  |  0.719587   |  22.1254    | 0.388119  |
| Qh     | baseline     | 28.131   |   4.73311 | 0.711579 | 0.848875 | 27.5209  | 41.1217 | 40.1408  | 0.546133 |  4.73311 | 0.288423  | 0.151125  |  0.0313721  |   0.0858659 | 0.288559  |
| Qh     | detailed     | 40.8169  |  28.4433  | 0.78295  | 0.820502 | 41.2902  |  7.927  | 50.57    | 0.572876 | 28.4433  | 0.217052  | 0.179498  |  0.00707449 |   0.214797  | 0.447009  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![UCLEM_PL-Narutowicza_subset_SWup_v0-9.png](UCLEM_PL-Narutowicza_subset_SWup_v0-9.png)](UCLEM_PL-Narutowicza_subset_SWup_v0-9.png)

### out of range: baseline

 - UCLEM Qle max value of 763.4641 is greater than expected 700.0 [W/m2]

### out of range: detailed

 - UCLEM Qle max value of 931.6539 is greater than expected 700.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

