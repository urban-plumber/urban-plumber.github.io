# PL-Narutowicza: Ensemble

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](Ensemble_PL-Narutowicza_baseline_attrs.md)
- [Detailed](Ensemble_PL-Narutowicza_detailed_attrs.md)

### Error metrics

| flux   | experiment   |     MAE |       MBE |      nSD |        R |       5th |     95th |    RMSE |    cRMSE |     AMBE |     1-nSD |       1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|--------:|----------:|---------:|---------:|----------:|---------:|--------:|---------:|---------:|----------:|----------:|------------:|------------:|----------:|
| SWup   | baseline     | 15.0944 |  14.0702  | 1.64171  | 0.951316 |  0.491887 | 45.9956  | 21.5557 | 0.756071 | 14.0702  | 0.641711  | 0.0486838 |   0.0422095 |   1.47599   | 0.205448  |
| SWup   | detailed     |  9.3125 |   7.21173 | 1.34997  | 0.951471 |  0.263122 | 26.426   | 13.0489 | 0.503494 |  7.21173 | 0.349972  | 0.0485288 |   0.025356  |   1.53342   | 0.14422   |
| LWup   | baseline     | 10.4427 |  -1.95513 | 1.06139  | 0.979384 |  3.57745  |  8.79583 | 12.8307 | 0.21802  |  1.95513 | 0.0613957 | 0.0206161 |   0.402242  |   0.71694   | 0.0683678 |
| LWup   | detailed     |  9.8782 |  -3.34955 | 1.0274   | 0.980031 |  2.00314  |  2.96545 | 12.3521 | 0.20441  |  3.34955 | 0.0274008 | 0.0199693 |   0.355879  |   0.454967  | 0.0667278 |
| Qle    | baseline     | 23.8685 | -13.9533  | 0.628594 | 0.650281 | 14.6669   | 39.1177  | 35.583  | 0.760003 | 13.9533  | 0.371408  | 0.349719  |   0.777661  |   0.852491  | 0.351323  |
| Qle    | detailed     | 23.371  | -13.2995  | 0.618604 | 0.656763 | 15.427    | 40.1416  | 35.1346 | 0.755062 | 13.2995  | 0.381398  | 0.343237  |   0.792059  |   0.812821  | 0.342952  |
| Qh     | baseline     | 24.6055 |  11.3665  | 0.880195 | 0.897252 | 27.4815   |  2.23499 | 34.1938 | 0.441848 | 11.3665  | 0.119807  | 0.102748  |   0.0872797 |   0.0801769 | 0.262563  |
| Qh     | detailed     | 26.2134 |  16.1699  | 0.912482 | 0.902623 | 28.5223   |  6.87573 | 35.3405 | 0.430544 | 16.1699  | 0.0875204 | 0.0973766 |   0.0710173 |   0.0596628 | 0.282843  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### out of range: baseline


### out of range: detailed

 - Ensemble Qanth min value of -318.2911 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

