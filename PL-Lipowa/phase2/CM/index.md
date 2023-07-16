# PL-Lipowa: CM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](CM_PL-Lipowa_baseline_attrs.md)
- [Detailed](CM_PL-Lipowa_detailed_attrs.md)

### Error metrics

| flux   | experiment   |      MAE |       MBE |        nSD |          R |     5th |      95th |     RMSE |      cRMSE |      AMBE |        1-nSD |         1-R |   nSkewness |   nKurtosis |    Overlap |
|:-------|:-------------|---------:|----------:|-----------:|-----------:|--------:|----------:|---------:|-----------:|----------:|-------------:|------------:|------------:|------------:|-----------:|
| SWup   | baseline     | nan      | nan       | nan        | nan        | nan     | nan       | nan      | nan        | nan       | nan          | nan         | nan         |   nan       | nan        |
| SWup   | detailed     |   9.2341 |  -9.21435 |   0.681882 |   0.906152 |   1.09  |  17.51    |  13.4207 |   0.478734 |   9.21435 |   0.318119   |   0.0938483 |   0.120828  |     1.16015 |   0.171048 |
| LWup   | baseline     | nan      | nan       | nan        | nan        | nan     | nan       | nan      | nan        | nan       | nan          | nan         | nan         |   nan       | nan        |
| LWup   | detailed     |  25.4518 | -24.0851  |   1.07692  |   0.979373 |  21.73  |   3.40001 |  27.5386 |   0.224375 |  24.0851  |   0.0769194  |   0.0206268 |   0.988294  |     2.79619 |   0.203854 |
| Qle    | baseline     | nan      | nan       | nan        | nan        | nan     | nan       | nan      | nan        | nan       | nan          | nan         | nan         |   nan       | nan        |
| Qle    | detailed     |  18.5735 |  -5.99483 |   0.773933 |   0.432357 |  12.207 |  21.64    |  31.9258 |   0.964231 |   5.99483 |   0.226067   |   0.567643  |   7.0485    |   141.172   |   0.20376  |
| Qh     | baseline     | nan      | nan       | nan        | nan        | nan     | nan       | nan      | nan        | nan       | nan          | nan         | nan         |   nan       | nan        |
| Qh     | detailed     |  33.9739 |  29.128   |   1.00411  |   0.889576 |  32.718 |  32.844   |  42.9711 |   0.470928 |  29.128   |   0.00411153 |   0.110424  |   0.0819667 |     0.28991 |   0.430267 |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![CM_PL-Lipowa_subset_SWup_v0-9.png](CM_PL-Lipowa_subset_SWup_v0-9.png)](CM_PL-Lipowa_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed

 - CM Qstor max value of 1393.4600 is greater than expected 800.0 [W/m2]
 - CM Qstor min value of -1172.0100 is less than expected -800.0 [W/m2]
 - CM Qh max value of 709.7500 is greater than expected 600.0 [W/m2]
 - CM Qle min value of -1731.9800 is less than expected -700.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

