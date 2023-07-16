# US-Minneapolis2: CHTESSEL_U

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](CHTESSEL_U_US-Minneapolis2_baseline_attrs.md)
- [Detailed](CHTESSEL_U_US-Minneapolis2_detailed_attrs.md)

### Error metrics

| flux     | experiment   |      MAE |        MBE |      nSD |          R |         5th |       95th |      RMSE |      cRMSE |      AMBE |     1-nSD |         1-R |   nSkewness |   nKurtosis |   Overlap |
|:---------|:-------------|---------:|-----------:|---------:|-----------:|------------:|-----------:|----------:|-----------:|----------:|----------:|------------:|------------:|------------:|----------:|
| SWup     | baseline     | 36.8561  | -33.6459   | 0.671858 |   0.92736  |  1.55079    | 109.369    | 55.2917   |   0.453083 | 33.6459   | 0.328144  |   0.0726397 |    0.055638 |   0.126521  | 0.183311  |
| SWup     | detailed     | 36.8561  | -33.6459   | 0.671858 |   0.92736  |  1.55079    | 109.369    | 55.2917   |   0.453083 | 33.6459   | 0.328144  |   0.0726397 |    0.055638 |   0.126521  | 0.183311  |
| LWup     | baseline     |  9.04615 |  -1.78195  | 0.968815 |   0.985025 |  0.0865326  |   9.78918  | 12.6813   |   0.173171 |  1.78195  | 0.0311863 |   0.0149748 |    0.629868 |   0.429349  | 0.0593825 |
| LWup     | detailed     |  9.04615 |  -1.78195  | 0.968815 |   0.985025 |  0.0865326  |   9.78918  | 12.6813   |   0.173171 |  1.78195  | 0.0311863 |   0.0149748 |    0.629868 |   0.429349  | 0.0593825 |
| Qle      | baseline     | 23.4138  |  -0.926338 | 0.938683 |   0.8411   |  0.916018   |  12.4802   | 42.3812   |   0.549612 |  0.926338 | 0.0613175 |   0.1589    |    0.114141 |   0.354042  | 0.0615963 |
| Qle      | detailed     | 23.4138  |  -0.926338 | 0.938683 |   0.8411   |  0.916018   |  12.4802   | 42.3812   |   0.549612 |  0.926338 | 0.0613175 |   0.1589    |    0.114141 |   0.354042  | 0.0615963 |
| Qh       | baseline     | 36.0406  |  19.4416   | 1.60308  |   0.862865 | 15.2233     | 116.314    | 60.059    |   0.896313 | 19.4416   | 0.603077  |   0.137135  |    0.30074  |   0.204608  | 0.197754  |
| Qh       | detailed     | 36.0406  |  19.4416   | 1.60308  |   0.862865 | 15.2233     | 116.314    | 60.059    |   0.896313 | 19.4416   | 0.603077  |   0.137135  |    0.30074  |   0.204608  | 0.197754  |
| Qg       | baseline     | 18.174   |  -0.892796 | 0.932053 |   0.796479 |  6.93496    |  20.2021   | 27.6835   |   0.619678 |  0.892796 | 0.0679532 |   0.203521  |    0.476228 |   0.718405  | 0.127211  |
| Qg       | detailed     | 18.174   |  -0.892796 | 0.932053 |   0.796479 |  6.93496    |  20.2021   | 27.6835   |   0.619678 |  0.892796 | 0.0679532 |   0.203521  |    0.476228 |   0.718405  | 0.127211  |
| Qtau     | baseline     |  0.2303  |  -0.2303   | 0        | nan        |  0.00724557 |   0.771555 |  0.354792 | nan        |  0.2303   | 1         | nan         |    1        |   1         | 0.922931  |
| Qtau     | detailed     |  0.2303  |  -0.2303   | 0        | nan        |  0.00724557 |   0.771555 |  0.354792 | nan        |  0.2303   | 1         | nan         |    1        |   1         | 0.922931  |
| SoilTemp | baseline     |  2.65345 |  -2.09881  | 1.01349  |   0.975204 |  0.909363   |   0.44635  |  3.16645  |   0.224595 |  2.09881  | 0.0134974 |   0.0247957 |    3.78528  |   0.0937878 | 0.196756  |
| SoilTemp | detailed     |  2.65345 |  -2.09881  | 1.01349  |   0.975204 |  0.909363   |   0.44635  |  3.16645  |   0.224595 |  2.09881  | 0.0134974 |   0.0247957 |    3.78528  |   0.0937878 | 0.196756  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![CHTESSEL_U_US-Minneapolis2_subset_SWup_v0-9.png](CHTESSEL_U_US-Minneapolis2_subset_SWup_v0-9.png)](CHTESSEL_U_US-Minneapolis2_subset_SWup_v0-9.png)

### out of range: baseline

 - CHTESSEL_U Qh min value of -1007.5397 is less than expected -600.0 [W/m2]
 - CHTESSEL_U Qg max value of 533.9344 is greater than expected 500.0 [W/m2]
 - CHTESSEL_U Qle max value of 1036.8640 is greater than expected 700.0 [W/m2]

### out of range: detailed

 - CHTESSEL_U Qh min value of -1007.5397 is less than expected -600.0 [W/m2]
 - CHTESSEL_U Qg max value of 533.9344 is greater than expected 500.0 [W/m2]
 - CHTESSEL_U Qle max value of 1036.8640 is greater than expected 700.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

