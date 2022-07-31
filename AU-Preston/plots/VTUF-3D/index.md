# AU-Preston: VTUF-3D

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](VTUF-3D_AU-Preston_baseline_attrs.md)
- [Detailed](VTUF-3D_AU-Preston_detailed_attrs.md)

### Error metrics

| flux   | experiment   |      MAE |       MBE |        nSD |          R |       5th |     95th |     RMSE |      cRMSE |      AMBE |      1-nSD |          1-R |   nSkewness |   nKurtosis |     Overlap |
|:-------|:-------------|---------:|----------:|-----------:|-----------:|----------:|---------:|---------:|-----------:|----------:|-----------:|-------------:|------------:|------------:|------------:|
| SWup   | baseline     |  20.0412 | -20.041   |   0.623163 |   0.996093 |   0.80254 |  54.4682 |  26.8374 |   0.383244 |  20.041   |   0.376837 |   0.00390723 |   0.0125033 |   0.0392639 |   0.0942838 |
| SWup   | detailed     |  16.8719 | -16.8681  |   0.680983 |   0.996294 |   0.72756 |  45.938  |  22.721  |   0.326831 |  16.8681  |   0.319017 |   0.00370552 |   0.0112132 |   0.0425897 |   0.0858802 |
| LWup   | baseline     |  10.8393 |  -4.66627 |   0.730412 |   0.962331 |   6.88992 |  28.1583 |  15.6957 |   0.357358 |   4.66627 |   0.269588 |   0.0376685  |   0.0140891 |   0.284378  |   0.144072  |
| LWup   | detailed     |  10.9602 |  -4.82169 |   0.727159 |   0.96122  |   6.87486 |  28.611  |  15.9168 |   0.361719 |   4.82169 |   0.272841 |   0.0387799  |   0.0131197 |   0.287227  |   0.143198  |
| Qle    | baseline     |  28.3282 | -16.1573  |   0.367101 |   0.509424 |  12.19    |  80.8745 |  48.2066 |   0.872206 |  16.1573  |   0.632899 |   0.490576   |   0.0611884 |   0.260816  |   0.2898    |
| Qle    | detailed     |  28.3288 | -16.157   |   0.3671   |   0.509423 |  12.19    |  80.8745 |  48.2065 |   0.872206 |  16.157   |   0.6329   |   0.490577   |   0.0612016 |   0.260818  |   0.289893  |
| Qh     | baseline     |  24.915  |  -6.59641 |   0.808725 |   0.920752 |   4.86528 |  46.0743 |  37.9306 |   0.405913 |   6.59641 |   0.191275 |   0.0792476  |   0.0971424 |   0.256242  |   0.123983  |
| Qh     | detailed     |  25.2667 |  -7.48337 |   0.795385 |   0.919434 |   4.73593 |  50.0892 |  38.6755 |   0.412346 |   7.48337 |   0.204615 |   0.080566   |   0.0996137 |   0.256359  |   0.119365  |
| Qtau   | baseline     | nan      | nan       | nan        | nan        | nan       | nan      | nan      | nan        | nan       | nan        | nan          | nan         | nan         | nan         |
| Qtau   | detailed     | nan      | nan       | nan        | nan        | nan       | nan      | nan      | nan        | nan       | nan        | nan          | nan         | nan         | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="datasheet"></a>Datasheet
[![VTUF-3D_AU-Preston_Datasheet.png](VTUF-3D_AU-Preston_Datasheet.png)](VTUF-3D_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![VTUF-3D_AU-Preston_Distributions.png](VTUF-3D_AU-Preston_Distributions.png)](VTUF-3D_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![VTUF-3D_AU-Preston_closure_baseline.png](VTUF-3D_AU-Preston_closure_baseline.png)](VTUF-3D_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![VTUF-3D_AU-Preston_closure_detailed.png](VTUF-3D_AU-Preston_closure_detailed.png)](VTUF-3D_AU-Preston_closure_detailed.png)

### <a name="subset_lwup"></a>subset_LWup
[![VTUF-3D_AU-Preston_subset_LWup.png](VTUF-3D_AU-Preston_subset_LWup.png)](VTUF-3D_AU-Preston_subset_LWup.png)

### <a name="subset_qh"></a>subset_Qh
[![VTUF-3D_AU-Preston_subset_Qh.png](VTUF-3D_AU-Preston_subset_Qh.png)](VTUF-3D_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![VTUF-3D_AU-Preston_subset_Qle.png](VTUF-3D_AU-Preston_subset_Qle.png)](VTUF-3D_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![VTUF-3D_AU-Preston_subset_SWup.png](VTUF-3D_AU-Preston_subset_SWup.png)](VTUF-3D_AU-Preston_subset_SWup.png)

### out of range: baseline

 - VTUF-3D SWnet min value of -0.0002 is less than expected 0.0 [W/m2]
 - VTUF-3D EvapF max value of 15.0682 is greater than expected 1.0 [1]
 - VTUF-3D EvapF min value of -72.2261 is less than expected 0.0 [1]

### out of range: detailed

 - VTUF-3D SWnet min value of -0.0003 is less than expected 0.0 [W/m2]
 - VTUF-3D EvapF max value of 24.2687 is greater than expected 1.0 [1]
 - VTUF-3D EvapF min value of -17.2465 is less than expected 0.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

