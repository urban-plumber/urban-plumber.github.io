# JP-Yoyogi: K-UCMv1

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](K-UCMv1_JP-Yoyogi_baseline_attrs.md)
- [Detailed](K-UCMv1_JP-Yoyogi_detailed_attrs.md)

### Error metrics

| flux   | experiment   |      MAE |      MBE |        nSD |          R |        5th |     95th |     RMSE |      cRMSE |     AMBE |      1-nSD |         1-R |   nSkewness |   nKurtosis |    Overlap |
|:-------|:-------------|---------:|---------:|-----------:|-----------:|-----------:|---------:|---------:|-----------:|---------:|-----------:|------------:|------------:|------------:|-----------:|
| SWup   | baseline     | nan      | nan      | nan        | nan        | nan        | nan      | nan      | nan        | nan      | nan        | nan         |   nan       |   nan       | nan        |
| SWup   | detailed     |  13.6068 | -12.8978 |   0.750922 |   0.934557 |   1.35173  |  22.5482 |  18.5555 |   0.400407 |  12.8978 |   0.249079 |   0.0654434 |     0.86484 |     2.19779 |   0.196539 |
| LWup   | baseline     | nan      | nan      | nan        | nan        | nan        | nan      | nan      | nan        | nan      | nan        | nan         |   nan       |   nan       | nan        |
| LWup   | detailed     |  16.2492 |  15.8572 |   6.98054  |   0.150832 |   9.05511  |  21.3436 | 349.914  |   6.90088  |  15.8572 |   5.98054  |   0.849168  |   470.669   | 18826.5     |   0.101817 |
| Qle    | baseline     | nan      | nan      | nan        | nan        | nan        | nan      | nan      | nan        | nan      | nan        | nan         |   nan       |   nan       | nan        |
| Qle    | detailed     |  29.0542 | -27.2864 |   0.525901 |   0.129154 |   0.469692 |  92.1534 |  49.0357 |   1.06805  |  27.2864 |   0.474099 |   0.870846  |    33.7091  |   881.231   |   0.631177 |
| Qh     | baseline     | nan      | nan      | nan        | nan        | nan        | nan      | nan      | nan        | nan      | nan        | nan         |   nan       |   nan       | nan        |
| Qh     | detailed     |  37.0438 |  23.8963 |   3.50381  |   0.255327 |   5.6559   |  32.1941 | 225.126  |   3.38932  |  23.8963 |   2.50381  |   0.744673  |    63.1654  |  5140.67    |   0.216221 |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![K-UCMv1_JP-Yoyogi_subset_SWup_v0-9.png](K-UCMv1_JP-Yoyogi_subset_SWup_v0-9.png)](K-UCMv1_JP-Yoyogi_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed

 - K-UCMv1 Qstor min value of -61873.1431 is less than expected -800.0 [W/m2]
 - K-UCMv1 LWnet min value of -47820.6328 is less than expected -500.0 [W/m2]
 - K-UCMv1 Qh max value of 27425.2597 is greater than expected 600.0 [W/m2]
 - K-UCMv1 SWnet min value of -2.2976 is less than expected 0.0 [W/m2]
 - K-UCMv1 LWup max value of 48140.0312 is greater than expected 1000.0 [W/m2]
 - K-UCMv1 Qle max value of 1931.4351 is greater than expected 700.0 [W/m2]
 - K-UCMv1 Qstar min value of -47719.0764 is less than expected -500.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

