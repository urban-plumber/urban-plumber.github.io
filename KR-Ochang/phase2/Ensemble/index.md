# KR-Ochang: Ensemble

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](Ensemble_KR-Ochang_baseline_attrs.md)
- [Detailed](Ensemble_KR-Ochang_detailed_attrs.md)

### Error metrics

| flux   | experiment   |      MAE |      MBE |      nSD |        R |      5th |     95th |    RMSE |    cRMSE |     AMBE |     1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|---------:|---------:|---------:|---------:|---------:|---------:|--------:|---------:|---------:|----------:|-----------:|------------:|------------:|----------:|
| SWup   | baseline     |  7.63669 | -5.88753 | 0.822206 | 0.946592 |  1.65449 | 17.6122  | 17.6512 | 0.345595 |  5.88753 | 0.177795  | 0.0534084  |   0.580523  |    1.23765  | 0.0953876 |
| SWup   | detailed     |  7.01916 | -4.50994 | 0.845918 | 0.947    |  1.58214 | 13.6898  | 16.8306 | 0.336763 |  4.50994 | 0.154083  | 0.0530005  |   0.570701  |    1.23077  | 0.0896839 |
| LWup   | baseline     | 14.0059  | 13.7598  | 1.14192  | 0.990484 |  6.03615 | 39.0715  | 18.9171 | 0.204635 | 13.7598  | 0.141919  | 0.00951647 |   3.83525   |    0.250174 | 0.0833718 |
| LWup   | detailed     | 11.2998  | 10.3255  | 1.12627  | 0.990199 |  5.0166  | 34.3694  | 16.1132 | 0.194991 | 10.3255  | 0.126269  | 0.00980113 |   3.88033   |    0.23401  | 0.0704357 |
| Qle    | baseline     | 20.8636  |  1.99218 | 0.900467 | 0.768522 |  4.16659 |  9.68445 | 36.2022 | 0.653286 |  1.99218 | 0.099534  | 0.231478   |   0.302584  |    0.741872 | 0.150416  |
| Qle    | detailed     | 20.3407  | -2.60223 | 0.830726 | 0.761547 |  3.70705 | 23.0939  | 36.1584 | 0.651791 |  2.60223 | 0.169275  | 0.238453   |   0.260033  |    0.665361 | 0.18891   |
| Qh     | baseline     | 23.8966  | 16.1769  | 0.935049 | 0.911933 | 21.5464  |  7.00768 | 31.9737 | 0.41099  | 16.1769  | 0.0649508 | 0.0880673  |   0.0854261 |    0.269512 | 0.499714  |
| Qh     | detailed     | 19.2796  |  7.60103 | 0.878099 | 0.913123 | 16.7633  |  9.78695 | 28.491  | 0.409186 |  7.60103 | 0.1219    | 0.0868771  |   0.0729728 |    0.250987 | 0.369315  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### out of range: baseline


### out of range: detailed



[Link to variable definitions](../modelattrs/variable_definitions.md)

