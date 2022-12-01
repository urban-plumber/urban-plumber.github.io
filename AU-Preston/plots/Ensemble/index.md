# AU-Preston: Ensemble

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](Ensemble_AU-Preston_baseline_attrs.md)
- [Detailed](Ensemble_AU-Preston_detailed_attrs.md)

### Error metrics

| flux   | experiment   |        MAE |          MBE |      nSD |        R |         5th |       95th |      RMSE |     cRMSE |         AMBE |      1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|-----------:|-------------:|---------:|---------:|------------:|-----------:|----------:|----------:|-------------:|-----------:|-----------:|------------:|------------:|----------:|
| SWup   | G11          |  2.69536   |  0.777       | 1.00402  | 0.997057 |  0.16186    |  0.355818  |  3.66725  | 0.0769727 |  0.777       | 0.00401693 | 0.00294251 |   0.0521763 |  0.112553   | 0.0603192 |
| SWup   | baseline     |  3.5339    | -2.79074     | 0.949834 | 0.996603 |  0.497298   |  7.45883   |  5.22127  | 0.0947136 |  2.79074     | 0.0501665  | 0.00339743 |   0.0195043 |  0.0405558  | 0.0640075 |
| SWup   | detailed     |  2.8407    | -1.42788     | 0.981519 | 0.996711 |  0.471392   |  2.18819   |  4.09839  | 0.0824525 |  1.42788     | 0.0184813  | 0.00328922 |   0.0198489 |  0.0459544  | 0.0625164 |
| LWup   | G11          |  9.07561   |  4.38296     | 1.14483  | 0.977686 |  1.3135     | 20.2813    | 12.1      | 0.268455  |  4.38296     | 0.144832   | 0.0223141  |   0.079746  |  0.101279   | 0.0639132 |
| LWup   | baseline     |  7.14485   |  2.95796     | 1.15168  | 0.987004 |  3.42707    | 19.7077    | 10.1135   | 0.230089  |  2.95796     | 0.151677   | 0.0129963  |   0.0523464 |  0.00397612 | 0.0654557 |
| LWup   | detailed     |  8.00134   |  4.25238     | 1.17518  | 0.985182 |  2.62965    | 23.3983    | 11.5685   | 0.255959  |  4.25238     | 0.175179   | 0.0148179  |   0.0669957 |  0.0173024  | 0.0658329 |
| Qle    | G11          | 19.4237    | -8.21046     | 0.601402 | 0.748537 | 10.1928     | 38.4281    | 34.1919   | 0.679221  |  8.21046     | 0.398598   | 0.251463   |   0.134972  |  0.678911   | 0.238347  |
| Qle    | baseline     | 18.997     | -5.3214      | 0.66279  | 0.739657 | 11.1798     | 31.1694    | 33.517    | 0.677359  |  5.3214      | 0.33721    | 0.260343   |   0.0110716 |  0.436957   | 0.203481  |
| Qle    | detailed     | 18.2955    | -4.05424     | 0.699249 | 0.754593 | 10.89       | 24.5469    | 32.4261   | 0.658523  |  4.05424     | 0.300751   | 0.245407   |   0.0730115 |  0.5901     | 0.211646  |
| Qh     | G11          | 23.1383    | 12.1201      | 1.23468  | 0.955595 |  1.28207    | 74.3635    | 39.1248   | 0.405868  | 12.1201      | 0.234683   | 0.0444053  |   0.0106264 |  0.148186   | 0.131152  |
| Qh     | baseline     | 20.1946    | 11.8669      | 1.03823  | 0.95274  | 11.749      | 23.7829    | 31.2564   | 0.315587  | 11.8669      | 0.0382268  | 0.0472603  |   0.0319757 |  0.00612681 | 0.187615  |
| Qh     | detailed     | 16.9239    |  5.20992     | 0.996472 | 0.955478 |  8.08228    |  7.7002    | 27.7878   | 0.297895  |  5.20992     | 0.00352786 | 0.0445216  |   0.0318827 |  0.00726646 | 0.108564  |
| Qtau   | G11          |  0.0922373 |  0.000292506 | 0.877365 | 0.878506 |  0.00448539 |  0.0938522 |  0.148146 | 0.477733  |  0.000292506 | 0.122635   | 0.121494   |   0.209037  |  0.410262   | 0.0742814 |
| Qtau   | baseline     |  0.189964  |  0.167627    | 1.19643  | 0.866428 |  0.0444555  |  0.262392  |  0.249925 | 0.598501  |  0.167627    | 0.196428   | 0.133572   |   0.244849  |  0.416408   | 0.253097  |
| Qtau   | detailed     |  0.161628  |  0.133617    | 1.14469  | 0.870378 |  0.0324262  |  0.195688  |  0.219842 | 0.563639  |  0.133617    | 0.144689   | 0.129622   |   0.240738  |  0.41403    | 0.209635  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="albedo"></a>Albedo
[![Ensemble_AU-Preston_Albedo.png](Ensemble_AU-Preston_Albedo.png)](Ensemble_AU-Preston_Albedo.png)

### out of range: baseline

 - Ensemble SWup min value of -0.0110 is less than expected 0.0 [W/m2]

### out of range: detailed

 - Ensemble SWup min value of -0.0112 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

