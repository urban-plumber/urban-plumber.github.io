# US-WestPhoenix: K-UCMv1

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](K-UCMv1_US-WestPhoenix_baseline_attrs.md)
- [Detailed](K-UCMv1_US-WestPhoenix_detailed_attrs.md)

### Error metrics

| flux     | experiment   |      MAE |         MBE |        nSD |          R |       5th |      95th |     RMSE |      cRMSE |        AMBE |       1-nSD |         1-R |   nSkewness |   nKurtosis |     Overlap |
|:---------|:-------------|---------:|------------:|-----------:|-----------:|----------:|----------:|---------:|-----------:|------------:|------------:|------------:|------------:|------------:|------------:|
| SWup     | baseline     | nan      | nan         | nan        | nan        | nan       | nan       | nan      | nan        | nan         | nan         | nan         |  nan        |  nan        | nan         |
| SWup     | detailed     |  25.7994 | -25.471     |   0.864889 |   0.96199  |   3.678   |  23.4992  |  29.5073 |   0.289834 |  25.471     |   0.135111  |   0.0380099 |    6.02375  |    0.370576 |   0.215398  |
| LWup     | baseline     | nan      | nan         | nan        | nan        | nan       | nan       | nan      | nan        | nan         | nan         | nan         |  nan        |  nan        | nan         |
| LWup     | detailed     |  11.2187 |  -3.05256   |   0.936065 |   0.973037 |   8.67369 |   9.49009 |  18.4246 |   0.233594 |   3.05256   |   0.0639335 |   0.0269632 |    1.62031  |   23.5815   |   0.0824005 |
| Qle      | baseline     | nan      | nan         | nan        | nan        | nan       | nan       | nan      | nan        | nan         | nan         | nan         |  nan        |  nan        | nan         |
| Qle      | detailed     |  11.8812 |   0.0281982 |   0.582911 |   0.665761 |   6.76557 |  17.7277  |  20.4089 |   0.750751 |   0.0281982 |   0.417088  |   0.334239  |    0.343135 |    0.78279  |   0.330645  |
| Qh       | baseline     | nan      | nan         | nan        | nan        | nan       | nan       | nan      | nan        | nan         | nan         | nan         |  nan        |  nan        | nan         |
| Qh       | detailed     |  28.3686 |  -8.6693    |   0.907834 |   0.901899 |   9.03268 |  16.6013  |  40.2747 |   0.431988 |   8.6693    |   0.0921646 |   0.0981009 |    0.178181 |    1.28447  |   0.242474  |
| Qtau     | baseline     | nan      | nan         | nan        | nan        | nan       | nan       | nan      | nan        | nan         | nan         | nan         |  nan        |  nan        | nan         |
| Qtau     | detailed     | nan      | nan         | nan        | nan        | nan       | nan       | nan      | nan        | nan         | nan         | nan         |  nan        |  nan        | nan         |
| SoilTemp | baseline     | nan      | nan         | nan        | nan        | nan       | nan       | nan      | nan        | nan         | nan         | nan         |  nan        |  nan        | nan         |
| SoilTemp | detailed     | nan      | nan         | nan        | nan        | nan       | nan       | nan      | nan        | nan         | nan         | nan         |  nan        |  nan        | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![K-UCMv1_US-WestPhoenix_subset_SWup_v0-9.png](K-UCMv1_US-WestPhoenix_subset_SWup_v0-9.png)](K-UCMv1_US-WestPhoenix_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed

 - K-UCMv1 Qstor min value of -4543.5586 is less than expected -800.0 [W/m2]
 - K-UCMv1 Qh max value of 1937.4335 is greater than expected 600.0 [W/m2]
 - K-UCMv1 LWnet min value of -1694.5096 is less than expected -500.0 [W/m2]
 - K-UCMv1 SWnet min value of -3.9546 is less than expected 0.0 [W/m2]
 - K-UCMv1 LWup max value of 2075.6096 is greater than expected 1000.0 [W/m2]
 - K-UCMv1 Qle max value of 1023.7006 is greater than expected 700.0 [W/m2]
 - K-UCMv1 Qstar min value of -1583.8870 is less than expected -500.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

