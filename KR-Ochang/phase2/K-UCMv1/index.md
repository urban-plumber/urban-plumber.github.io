# KR-Ochang: K-UCMv1

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](K-UCMv1_KR-Ochang_baseline_attrs.md)
- [Detailed](K-UCMv1_KR-Ochang_detailed_attrs.md)

### Error metrics

| flux   | experiment   |      MAE |       MBE |        nSD |          R |        5th |     95th |     RMSE |      cRMSE |      AMBE |       1-nSD |         1-R |   nSkewness |   nKurtosis |    Overlap |
|:-------|:-------------|---------:|----------:|-----------:|-----------:|-----------:|---------:|---------:|-----------:|----------:|------------:|------------:|------------:|------------:|-----------:|
| SWup   | baseline     | nan      | nan       | nan        | nan        | nan        | nan      | nan      | nan        | nan       | nan         | nan         |  nan        | nan         | nan        |
| SWup   | detailed     |  16.0463 | -14.3307  |   0.745252 |   0.915779 |   1.37699  |  25.1746 |  25.4337 |   0.436381 |  14.3307  |   0.254749  |   0.084221  |    0.302342 |   1.02305   |   0.127266 |
| LWup   | baseline     | nan      | nan       | nan        | nan        | nan        | nan      | nan      | nan        | nan       | nan         | nan         |  nan        | nan         | nan        |
| LWup   | detailed     |  20.3293 |  19.7476  |   1.0975   |   0.98443  |  15.4717   |  32.4663 |  23.7859 |   0.209006 |  19.7476  |   0.0974987 |   0.0155704 |    2.03705  |   0.0766478 |   0.147227 |
| Qle    | baseline     | nan      | nan       | nan        | nan        | nan        | nan      | nan      | nan        | nan       | nan         | nan         |  nan        | nan         | nan        |
| Qle    | detailed     |  27.946  |  11.1072  |   1.07885  |   0.663692 |   5.41974  |  24.8827 |  48.6185 |   0.855492 |  11.1072  |   0.0788471 |   0.336308  |    0.444344 |   6.30659   |   0.170058 |
| Qh     | baseline     | nan      | nan       | nan        | nan        | nan        | nan      | nan      | nan        | nan       | nan         | nan         |  nan        | nan         | nan        |
| Qh     | detailed     |  27.796  |  -9.03819 |   0.626693 |   0.792798 |   0.943193 |  69.0215 |  43.3445 |   0.631713 |   9.03819 |   0.373306  |   0.207202  |    0.110991 |   0.482344  |   0.299984 |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![K-UCMv1_KR-Ochang_subset_SWup_v0-9.png](K-UCMv1_KR-Ochang_subset_SWup_v0-9.png)](K-UCMv1_KR-Ochang_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed

 - K-UCMv1 Qstor min value of -2656.2139 is less than expected -800.0 [W/m2]
 - K-UCMv1 Qh max value of 671.4017 is greater than expected 600.0 [W/m2]
 - K-UCMv1 SWnet min value of -3.5336 is less than expected 0.0 [W/m2]
 - K-UCMv1 Qle max value of 1613.1257 is greater than expected 700.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

