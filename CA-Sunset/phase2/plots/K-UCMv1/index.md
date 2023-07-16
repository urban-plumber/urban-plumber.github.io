# CA-Sunset: K-UCMv1

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](K-UCMv1_CA-Sunset_baseline_attrs.md)
- [Detailed](K-UCMv1_CA-Sunset_detailed_attrs.md)

### Error metrics

| flux     | experiment   |       MAE |       MBE |        nSD |          R |        5th |       95th |      RMSE |      cRMSE |      AMBE |       1-nSD |         1-R |   nSkewness |   nKurtosis |     Overlap |
|:---------|:-------------|----------:|----------:|-----------:|-----------:|-----------:|-----------:|----------:|-----------:|----------:|------------:|------------:|------------:|------------:|------------:|
| SWup     | baseline     | nan       | nan       | nan        | nan        | nan        | nan        | nan       | nan        | nan       | nan         | nan         | nan         |  nan        | nan         |
| SWup     | detailed     |   5.71374 |  -1.98071 |   1.00192  |   0.956035 |   0.668433 |   0.193798 |   8.56717 |   0.29682  |   1.98071 |   0.0019195 |   0.0439649 |   0.103288  |    0.66687  |   0.0633752 |
| LWup     | baseline     | nan       | nan       | nan        | nan        | nan        | nan        | nan       | nan        | nan       | nan         | nan         | nan         |  nan        | nan         |
| LWup     | detailed     |  15.3397  |  -8.12447 |   1.21825  |   0.959357 |  15.7196   |  14.6514   |  17.9812  |   0.382963 |   8.12447 |   0.218251  |   0.0406426 |   0.17661   |    0.171535 |   0.173806  |
| Qle      | baseline     | nan       | nan       | nan        | nan        | nan        | nan        | nan       | nan        | nan       | nan         | nan         | nan         |  nan        | nan         |
| Qle      | detailed     |  20.7719  |  -9.28692 |   0.610457 |   0.642586 |   8.4476   |  34.184    |  36.1644  |   0.766887 |   9.28692 |   0.389544  |   0.357414  |   0.0600436 |    0.522382 |   0.255205  |
| Qh       | baseline     | nan       | nan       | nan        | nan        | nan        | nan        | nan       | nan        | nan       | nan         | nan         | nan         |  nan        | nan         |
| Qh       | detailed     |  28.9958  |  -4.03667 |   0.76361  |   0.919118 |   4.6509   |  59.8646   |  44.0032  |   0.423563 |   4.03667 |   0.236393  |   0.0808824 |   0.0700023 |    0.170111 |   0.23908   |
| Qtau     | baseline     | nan       | nan       | nan        | nan        | nan        | nan        | nan       | nan        | nan       | nan         | nan         | nan         |  nan        | nan         |
| Qtau     | detailed     | nan       | nan       | nan        | nan        | nan        | nan        | nan       | nan        | nan       | nan         | nan         | nan         |  nan        | nan         |
| SoilTemp | baseline     | nan       | nan       | nan        | nan        | nan        | nan        | nan       | nan        | nan       | nan         | nan         | nan         |  nan        | nan         |
| SoilTemp | detailed     | nan       | nan       | nan        | nan        | nan        | nan        | nan       | nan        | nan       | nan         | nan         | nan         |  nan        | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![K-UCMv1_CA-Sunset_subset_SWup_v0-9.png](K-UCMv1_CA-Sunset_subset_SWup_v0-9.png)](K-UCMv1_CA-Sunset_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed

 - K-UCMv1 Qstor min value of -955.4192 is less than expected -800.0 [W/m2]
 - K-UCMv1 SWnet min value of -3.1626 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

