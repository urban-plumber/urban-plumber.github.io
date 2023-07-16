# US-Minneapolis2: K-UCMv1

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](K-UCMv1_US-Minneapolis2_baseline_attrs.md)
- [Detailed](K-UCMv1_US-Minneapolis2_detailed_attrs.md)

### Error metrics

| flux     | experiment   |      MAE |       MBE |        nSD |          R |      5th |     95th |     RMSE |      cRMSE |      AMBE |      1-nSD |         1-R |   nSkewness |   nKurtosis |    Overlap |
|:---------|:-------------|---------:|----------:|-----------:|-----------:|---------:|---------:|---------:|-----------:|----------:|-----------:|------------:|------------:|------------:|-----------:|
| SWup     | baseline     | nan      | nan       | nan        | nan        | nan      | nan      | nan      | nan        | nan       | nan        | nan         |  nan        | nan         | nan        |
| SWup     | detailed     |  41.2009 | -34.2093  |   0.574369 |   0.616106 |   1.116  | 129.901  |  83.6956 |   0.788768 |  34.2093  |   0.425632 |   0.383894  |    0.593428 |   1.12032   |   0.136766 |
| LWup     | baseline     | nan      | nan       | nan        | nan        | nan      | nan      | nan      | nan        | nan       | nan        | nan         |  nan        | nan         | nan        |
| LWup     | detailed     |  15.7155 |  -5.32209 |   0.783373 |   0.959476 |  11.1852 |  50.3328 |  24.6734 |   0.332293 |   5.32209 |   0.216628 |   0.0405244 |    1.93061  |   0.861275  |   0.136348 |
| Qle      | baseline     | nan      | nan       | nan        | nan        | nan      | nan      | nan      | nan        | nan       | nan        | nan         |  nan        | nan         | nan        |
| Qle      | detailed     |  68.0225 |  63.711   |   2.13812  |   0.900544 |   3.3778 | 278.555  | 119.521  |   1.31172  |  63.711   |   1.13812  |   0.0994564 |    0.117107 |   0.408701  |   0.26508  |
| Qh       | baseline     | nan      | nan       | nan        | nan        | nan      | nan      | nan      | nan        | nan       | nan        | nan         |  nan        | nan         | nan        |
| Qh       | detailed     |  58.8212 | -51.2657  |   0.859297 |   0.314881 |  76.7689 |  96.8178 |  86.2576 |   1.09418  |  51.2657  |   0.140703 |   0.685119  |    1.75363  |   0.0513603 |   0.336155 |
| Qg       | baseline     | nan      | nan       | nan        | nan        | nan      | nan      | nan      | nan        | nan       | nan        | nan         |  nan        | nan         | nan        |
| Qg       | detailed     | nan      | nan       | nan        | nan        | nan      | nan      | nan      | nan        | nan       | nan        | nan         |  nan        | nan         | nan        |
| Qtau     | baseline     | nan      | nan       | nan        | nan        | nan      | nan      | nan      | nan        | nan       | nan        | nan         |  nan        | nan         | nan        |
| Qtau     | detailed     | nan      | nan       | nan        | nan        | nan      | nan      | nan      | nan        | nan       | nan        | nan         |  nan        | nan         | nan        |
| SoilTemp | baseline     | nan      | nan       | nan        | nan        | nan      | nan      | nan      | nan        | nan       | nan        | nan         |  nan        | nan         | nan        |
| SoilTemp | detailed     | nan      | nan       | nan        | nan        | nan      | nan      | nan      | nan        | nan       | nan        | nan         |  nan        | nan         | nan        |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![K-UCMv1_US-Minneapolis2_subset_SWup_v0-9.png](K-UCMv1_US-Minneapolis2_subset_SWup_v0-9.png)](K-UCMv1_US-Minneapolis2_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed

 - K-UCMv1 Qstor min value of -1370.4981 is less than expected -800.0 [W/m2]
 - K-UCMv1 SWnet min value of -227.8117 is less than expected 0.0 [W/m2]
 - K-UCMv1 Qle max value of 1107.3146 is greater than expected 700.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

