# GR-HECKOR: Ensemble

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](Ensemble_GR-HECKOR_baseline_attrs.md)
- [Detailed](Ensemble_GR-HECKOR_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |        MBE |      nSD |        R |         5th |      95th |      RMSE |    cRMSE |      AMBE |     1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|----------:|-----------:|---------:|---------:|------------:|----------:|----------:|---------:|----------:|----------:|-----------:|------------:|------------:|----------:|
| SWup   | baseline     | 25.0177   | -25.0158   | 0.76308  | 0.993282 |  3.05141    | 50.8582   | 29.5931   | 0.25765  | 25.0158   | 0.236921  | 0.00671788 |  0.0357277  |   0.112264  | 0.106975  |
| SWup   | detailed     | 15.01     | -14.995    | 0.90025  | 0.993433 |  2.8198     | 24.3515   | 17.5167   | 0.147557 | 14.995    | 0.0997502 | 0.00656657 |  0.208392   |   0.0594509 | 0.0996355 |
| LWup   | baseline     | 20.8412   |  18.5295   | 1.4634   | 0.96436  |  1.13513    | 67.3028   | 30.8403   | 0.564848 | 18.5295   | 0.463399  | 0.03564    |  0.870254   |   0.650295  | 0.104738  |
| LWup   | detailed     | 19.2341   |  17.6962   | 1.4128   | 0.968617 |  2.82209    | 61.4489   | 28.4025   | 0.509004 | 17.6962   | 0.412802  | 0.0313835  |  0.816125   |   0.581079  | 0.0978552 |
| Qle    | baseline     | 23.3126   | -17.0728   | 0.534328 | 0.233027 |  3.91638    | 62.2689   | 39.8975   | 1.01808  | 17.0728   | 0.465672  | 0.766973   |  2.61571    |   7.94169   | 0.435688  |
| Qle    | detailed     | 21.4934   | -15.0436   | 0.472969 | 0.306536 |  4.11607    | 58.2181   | 37.3864   | 0.9663   | 15.0436   | 0.527031  | 0.693464   |  1.7398     |   4.82153   | 0.350696  |
| Qh     | baseline     | 30.5097   |  21.6467   | 1.1983   | 0.947617 | 12.3737     | 79.5494   | 48.1267   | 0.406034 | 21.6467   | 0.198298  | 0.0523835  |  0.00551827 |   0.376679  | 0.174034  |
| Qh     | detailed     | 29.2111   |  13.5865   | 1.20694  | 0.944027 |  3.89786    | 71.8151   | 46.6765   | 0.421826 | 13.5865   | 0.206943  | 0.0559728  |  0.0177114  |   0.476899  | 0.146645  |
| Qtau   | baseline     |  0.226105 |  -0.223731 | 0.448205 | 0.925683 |  0.0118677  |  0.669162 |  0.343341 | 0.609176 |  0.223731 | 0.551795  | 0.0743171  |  0.0490144  |   0.130634  | 0.241597  |
| Qtau   | detailed     |  0.204452 |  -0.19744  | 0.476357 | 0.933493 |  0.00475928 |  0.627    |  0.317303 | 0.581003 |  0.19744  | 0.523643  | 0.066507   |  0.0277417  |   0.051109  | 0.221495  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### out of range: baseline


### out of range: detailed



[Link to variable definitions](../modelattrs/variable_definitions.md)

