# US-WestPhoenix: TEB-CNRM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](TEB-CNRM_US-WestPhoenix_baseline_attrs.md)
- [Detailed](TEB-CNRM_US-WestPhoenix_detailed_attrs.md)

### Error metrics

| flux     | experiment   |        MAE |         MBE |      nSD |        R |         5th |        95th |       RMSE |    cRMSE |       AMBE |     1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:---------|:-------------|-----------:|------------:|---------:|---------:|------------:|------------:|-----------:|---------:|-----------:|----------:|-----------:|------------:|------------:|----------:|
| SWup     | baseline     | 23.2232    | -23.2201    | 0.752606 | 0.995415 |  4.63654    |  43.2623    | 26.8157    | 0.26097  | 23.2201    | 0.247394  | 0.00458495 |  0.0470873  |  0.00869543 | 0.13309   |
| SWup     | detailed     |  9.67024   |  -9.55417   | 0.929227 | 0.995452 |  4.30924    |  15.1851    | 11.2623    | 0.11602  |  9.55417   | 0.0707729 | 0.00454779 |  0.0732715  |  0.00382368 | 0.10534   |
| LWup     | baseline     | 11.911     |   7.13671   | 1.13111  | 0.988935 |  0.704816   |  36.3584    | 17.5047    | 0.20548  |  7.13671   | 0.131114  | 0.0110647  |  0.442819   |  0.458724   | 0.0426846 |
| LWup     | detailed     |  9.22598   |   5.09484   | 0.946516 | 0.994011 | 11.886      |   2.15353   | 10.5768    | 0.119156 |  5.09484   | 0.0534848 | 0.00598909 |  0.00720351 |  0.00857715 | 0.0800608 |
| Qle      | baseline     | 18.2402    | -14.2528    | 0.546492 | 0.273493 |  3.47363    |  53.0946    | 30.6906    | 0.999865 | 14.2528    | 0.453508  | 0.726507   |  3.91754    | 19.763      | 0.460028  |
| Qle      | detailed     | 16.5363    | -11.8284    | 0.594569 | 0.386431 |  3.69757    |  44.7338    | 28.2939    | 0.945512 | 11.8284    | 0.405431  | 0.613569   |  3.11389    | 13.7639     | 0.342982  |
| Qh       | baseline     | 54.2065    |  53.5791    | 1.51738  | 0.958792 | 22.9281     | 164.364     | 78.2696    | 0.626685 | 53.5791    | 0.51738   | 0.0412081  |  0.0396359  |  0.361853   | 0.484288  |
| Qh       | detailed     | 34.7589    |  30.5429    | 1.23723  | 0.946249 | 15.9161     |  90.1029    | 50.0183    | 0.435065 | 30.5429    | 0.237229  | 0.0537514  |  0.0443656  |  0.150836   | 0.359519  |
| Qtau     | baseline     |  0.0513991 |   0.0202307 | 1.20446  | 0.83616  |  0.00559967 |   0.0718357 |  0.0752638 | 0.660666 |  0.0202307 | 0.204455  | 0.16384    |  0.222854   |  0.393969   | 0.183907  |
| Qtau     | detailed     |  0.0630849 |   0.0387593 | 1.39187  | 0.837666 |  0.00486341 |   0.135658  |  0.0937664 | 0.77811  |  0.0387593 | 0.391865  | 0.162334   |  0.164038   |  0.263982   | 0.175922  |
| SoilTemp | baseline     |  3.02833   |  -2.1323    | 0.836097 | 0.976032 |  0.981299   |   5.89833   |  4.02889   | 0.258735 |  2.1323    | 0.163904  | 0.0239683  |  0.278359   |  0.106369   | 0.114895  |
| SoilTemp | detailed     |  3.3688    |  -2.83765   | 0.812127 | 0.977355 |  0.554035   |   7.3361    |  4.54243   | 0.268473 |  2.83765   | 0.187873  | 0.0226452  |  1.11866    |  0.151942   | 0.118547  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![TEB-CNRM_US-WestPhoenix_subset_SWup_v0-9.png](TEB-CNRM_US-WestPhoenix_subset_SWup_v0-9.png)](TEB-CNRM_US-WestPhoenix_subset_SWup_v0-9.png)

### out of range: baseline

 - TEB-CNRM Qh max value of 622.2573 is greater than expected 600.0 [W/m2]

### out of range: detailed



[Link to variable definitions](../modelattrs/variable_definitions.md)

