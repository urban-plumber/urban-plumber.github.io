# CA-Sunset: ASLUMv2.0

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](ASLUMv2.0_CA-Sunset_baseline_attrs.md)
- [Detailed](ASLUMv2.0_CA-Sunset_detailed_attrs.md)

### Error metrics

| flux     | experiment   |      MAE |        MBE |        nSD |          R |        5th |      95th |      RMSE |      cRMSE |       AMBE |      1-nSD |         1-R |   nSkewness |    nKurtosis |     Overlap |
|:---------|:-------------|---------:|-----------:|-----------:|-----------:|-----------:|----------:|----------:|-----------:|-----------:|-----------:|------------:|------------:|-------------:|------------:|
| SWup     | baseline     |  13.9572 |  12.5155   |   1.51835  |   0.975735 |   0.674149 |  43.9192  |  20.6547  |   0.585128 |  12.5155   |   0.518354 |   0.0242653 |   0.0433792 |   0.00297137 |   0.173393  |
| SWup     | detailed     |   4.7069 |  -0.202814 |   1.07927  |   0.973786 |   0.791057 |   5.51479 |   7.04383 |   0.250734 |   0.202814 |   0.079275 |   0.0262137 |   0.0587083 |   0.0824239  |   0.0895071 |
| LWup     | baseline     |  20.3044 |  18.7645   |   1.37768  |   0.963324 |   0.919739 |  50.3228  |  27.9229  |   0.493662 |  18.7645   |   0.377685 |   0.0366761 |   0.0214946 |   0.755954   |   0.164537  |
| LWup     | detailed     |  20.0379 |  16.8163   |   1.47301  |   0.96157  |   2.5603   |  61.171   |  29.5633  |   0.580479 |  16.8163   |   0.473011 |   0.0384303 |   0.197866  |   0.0393738  |   0.148093  |
| Qle      | baseline     |  24.4018 |   6.66983  |   0.757969 |   0.633708 |  13.7002   |   3.08174 |  36.3258  |   0.783489 |   6.66983  |   0.242033 |   0.366292  |   0.0419285 |   0.436277   |   0.321194  |
| Qle      | detailed     |  21.5739 |  -6.05039  |   0.865004 |   0.618863 |   8.0299   |  13.7342  |  38.0011  |   0.823161 |   6.05039  |   0.134998 |   0.381137  |   0.563749  |   1.76243    |   0.21585   |
| Qh       | baseline     |  36.1674 |  18.5917   |   0.782004 |   0.923165 |  22.3982   |  37.9639  |  46.2633  |   0.409504 |  18.5917   |   0.217999 |   0.0768355 |   0.176234  |   0.424845   |   0.391033  |
| Qh       | detailed     |  30.2373 |   7.92043  |   0.767443 |   0.931342 |  18.7255   |  48.4112  |  42.0632  |   0.39933  |   7.92043  |   0.23256  |   0.0686576 |   0.127584  |   0.337401   |   0.31894   |
| Qtau     | baseline     | nan      | nan        | nan        | nan        | nan        | nan       | nan       | nan        | nan        | nan        | nan         | nan         | nan          | nan         |
| Qtau     | detailed     | nan      | nan        | nan        | nan        | nan        | nan       | nan       | nan        | nan        | nan        | nan         | nan         | nan          | nan         |
| SoilTemp | baseline     | nan      | nan        | nan        | nan        | nan        | nan       | nan       | nan        | nan        | nan        | nan         | nan         | nan          | nan         |
| SoilTemp | detailed     | nan      | nan        | nan        | nan        | nan        | nan       | nan       | nan        | nan        | nan        | nan         | nan         | nan          | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![ASLUMv2.0_CA-Sunset_subset_SWup_v0-9.png](ASLUMv2.0_CA-Sunset_subset_SWup_v0-9.png)](ASLUMv2.0_CA-Sunset_subset_SWup_v0-9.png)

### out of range: baseline

 - ASLUMv2.0 SWup min value of -3.9804 is less than expected 0.0 [W/m2]

### out of range: detailed

 - ASLUMv2.0 SWup min value of -5.1168 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

