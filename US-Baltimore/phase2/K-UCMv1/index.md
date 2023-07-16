# US-Baltimore: K-UCMv1

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](K-UCMv1_US-Baltimore_baseline_attrs.md)
- [Detailed](K-UCMv1_US-Baltimore_detailed_attrs.md)

### Error metrics

| flux     | experiment   |      MAE |       MBE |        nSD |          R |      5th |       95th |     RMSE |      cRMSE |      AMBE |        1-nSD |         1-R |   nSkewness |   nKurtosis |     Overlap |
|:---------|:-------------|---------:|----------:|-----------:|-----------:|---------:|-----------:|---------:|-----------:|----------:|-------------:|------------:|------------:|------------:|------------:|
| SWup     | baseline     | nan      | nan       | nan        | nan        | nan      | nan        | nan      | nan        | nan       | nan          | nan         | nan         |  nan        | nan         |
| SWup     | detailed     |  10.3798 |  -4.71637 |   0.992554 |   0.906255 |   1.2914 |   0.174598 |  15.2174 |   0.431451 |   4.71637 |   0.00744547 |   0.0937452 |   0.403548  |    0.447417 |   0.0901902 |
| LWup     | baseline     | nan      | nan       | nan        | nan        | nan      | nan        | nan      | nan        | nan       | nan          | nan         | nan         |  nan        | nan         |
| LWup     | detailed     |  11.3865 |  -3.83736 |   1.09893  |   0.975073 |   8.602  |  14.5243   |  14.5583 |   0.254114 |   3.83736 |   0.0989337  |   0.0249268 |   4.91777   |    0.407924 |   0.0804673 |
| Qle      | baseline     | nan      | nan       | nan        | nan        | nan      | nan        | nan      | nan        | nan       | nan          | nan         | nan         |  nan        | nan         |
| Qle      | detailed     |  39.5116 |  26.4624  |   1.13044  |   0.765304 |  21.6404 |  44.1634   |  59.7152 |   0.740024 |  26.4624  |   0.130442   |   0.234696  |   0.213246  |    1.91625  |   0.313059  |
| Qh       | baseline     | nan      | nan       | nan        | nan        | nan      | nan        | nan      | nan        | nan       | nan          | nan         | nan         |  nan        | nan         |
| Qh       | detailed     |  40.9252 | -18.2958  |   0.683296 |   0.758011 |   8.0651 |  94.5944   |  61.0253 |   0.656507 |  18.2958  |   0.316704   |   0.241989  |   0.0567505 |    4.64325  |   0.201272  |
| SoilTemp | baseline     | nan      | nan       | nan        | nan        | nan      | nan        | nan      | nan        | nan       | nan          | nan         | nan         |  nan        | nan         |
| SoilTemp | detailed     | nan      | nan       | nan        | nan        | nan      | nan        | nan      | nan        | nan       | nan          | nan         | nan         |  nan        | nan         |
| Qtau     | baseline     | nan      | nan       | nan        | nan        | nan      | nan        | nan      | nan        | nan       | nan          | nan         | nan         |  nan        | nan         |
| Qtau     | detailed     | nan      | nan       | nan        | nan        | nan      | nan        | nan      | nan        | nan       | nan          | nan         | nan         |  nan        | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![K-UCMv1_US-Baltimore_subset_SWup_v0-9.png](K-UCMv1_US-Baltimore_subset_SWup_v0-9.png)](K-UCMv1_US-Baltimore_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed

 - K-UCMv1 Qstor min value of -5458.6460 is less than expected -800.0 [W/m2]
 - K-UCMv1 Qh max value of 1930.0768 is greater than expected 600.0 [W/m2]
 - K-UCMv1 LWnet min value of -965.7596 is less than expected -500.0 [W/m2]
 - K-UCMv1 SWnet min value of -170.3974 is less than expected 0.0 [W/m2]
 - K-UCMv1 LWup max value of 1177.0096 is greater than expected 1000.0 [W/m2]
 - K-UCMv1 Qle max value of 2394.2321 is greater than expected 700.0 [W/m2]
 - K-UCMv1 Qstar min value of -1136.1570 is less than expected -500.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

