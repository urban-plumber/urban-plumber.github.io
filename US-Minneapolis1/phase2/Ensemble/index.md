# US-Minneapolis1: Ensemble

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](Ensemble_US-Minneapolis1_baseline_attrs.md)
- [Detailed](Ensemble_US-Minneapolis1_detailed_attrs.md)

### Error metrics

| flux     | experiment   |        MAE |         MBE |      nSD |        R |        5th |       95th |      RMSE |    cRMSE |       AMBE |      1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:---------|:-------------|-----------:|------------:|---------:|---------:|-----------:|-----------:|----------:|---------:|-----------:|-----------:|-----------:|------------:|------------:|----------:|
| SWup     | baseline     | 42.8779    | -42.3758    | 0.488562 | 0.872407 |  1.55483   | 164.992    | 73.6059   | 0.621485 | 42.3758    | 0.511439   | 0.127593   |   0.590715  |   1.0357    | 0.179425  |
| SWup     | detailed     | 33.6854    | -32.5743    | 0.57036  | 0.853429 |  1.1598    | 139.573    | 66.0309   | 0.593116 | 32.5743    | 0.429641   | 0.146571   |   0.623092  |   1.09017   | 0.112953  |
| LWup     | baseline     |  8.95163   |   6.85473   | 1.0139   | 0.991751 |  8.62592   |   9.143    | 11.6589   | 0.130077 |  6.85473   | 0.0139003  | 0.00824866 |   0.100617  |   0.362444  | 0.0727449 |
| LWup     | detailed     |  7.32882   |   2.07479   | 1.0071   | 0.991362 |  4.68069   |   2.23294  |  9.79947  | 0.132095 |  2.07479   | 0.00710004 | 0.00863796 |   0.151199  |   0.439216  | 0.0561388 |
| Qle      | baseline     | 16.6918    |   7.7525    | 1.00766  | 0.862775 |  5.59824   |  23.6289   | 30.2221   | 0.525938 |  7.7525    | 0.00765702 | 0.137225   |   0.173874  |   0.524025  | 0.183441  |
| Qle      | detailed     | 16.731     |   6.17475   | 0.937893 | 0.854712 |  5.43217   |  10.5722   | 29.8448   | 0.525725 |  6.17475   | 0.0621068  | 0.145288   |   0.204608  |   0.555393  | 0.206967  |
| Qh       | baseline     | 28.6173    |  19.267     | 0.908074 | 0.930223 | 30.0989    |   5.02548  | 36.4055   | 0.367663 | 19.267     | 0.0919272  | 0.0697774  |   0.0465897 |   0.0251321 | 0.307275  |
| Qh       | detailed     | 22.1253    |   3.89701   | 0.839653 | 0.930017 | 23.6422    |  20.6673   | 32.0344   | 0.378462 |  3.89701   | 0.160348   | 0.0699826  |   0.108575  |   0.165019  | 0.242556  |
| Qg       | baseline     | 23.428     |   1.08982   | 1.266    | 0.799103 | 12.5339    |  14.8621   | 34.0056   | 0.761203 |  1.08982   | 0.265994   | 0.200897   |   0.374623  |   0.811123  | 0.231808  |
| Qg       | detailed     | 23.8527    |   0.874811  | 1.17047  | 0.765756 |  9.27863   |   4.45963  | 33.9403   | 0.759879 |  0.874811  | 0.170466   | 0.234244   |   0.404366  |   0.840282  | 0.216271  |
| Qtau     | baseline     |  0.0780561 |  -0.0430053 | 0.71834  | 0.891457 |  0.0265693 |   0.163271 |  0.120394 | 0.48505  |  0.0430053 | 0.281661   | 0.108543   |   0.0416177 |   0.230199  | 0.193528  |
| Qtau     | detailed     |  0.0974074 |  -0.0859457 | 0.607969 | 0.905615 |  0.0104837 |   0.257701 |  0.1477   | 0.518126 |  0.0859457 | 0.392032   | 0.0943847  |   0.0610493 |   0.282741  | 0.213073  |
| SoilTemp | baseline     |  2.46903   |  -2.04957   | 1.09769  | 0.982196 |  4.84177   |   0.731883 |  3.10164  | 0.220522 |  2.04957   | 0.0976914  | 0.0178042  |   2.90168   |   0.0911524 | 0.180246  |
| SoilTemp | detailed     |  2.60834   |  -2.14156   | 1.10396  | 0.981264 |  4.84381   |   0.487357 |  3.22505  | 0.228422 |  2.14156   | 0.103967   | 0.0187361  |   2.19189   |   0.0891802 | 0.177458  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### out of range: baseline


### out of range: detailed

 - Ensemble Qanth min value of -54.9949 is less than expected 0.0 [W/m2]
 - Ensemble SWnet min value of -1.1496 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

