# CA-Sunset: ASLUMv3.1

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](ASLUMv3.1_CA-Sunset_baseline_attrs.md)
- [Detailed](ASLUMv3.1_CA-Sunset_detailed_attrs.md)

### Error metrics

| flux     | experiment   |       MAE |       MBE |        nSD |          R |        5th |      95th |      RMSE |      cRMSE |      AMBE |      1-nSD |         1-R |    nSkewness |   nKurtosis |     Overlap |
|:---------|:-------------|----------:|----------:|-----------:|-----------:|-----------:|----------:|----------:|-----------:|----------:|-----------:|------------:|-------------:|------------:|------------:|
| SWup     | baseline     |  10.9829  |   9.57215 |   1.38037  |   0.977058 |   0.343567 |  31.967   |  15.9894  |   0.45609  |   9.57215 |   0.380374 |   0.0229417 |   0.00196016 |    0.487617 |   0.128038  |
| SWup     | detailed     |   5.67021 |  -5.08877 |   0.868978 |   0.974574 |   0.397    |  12.0469  |   8.61847 |   0.247703 |   5.08877 |   0.131021 |   0.0254264 |   0.0311728  |    0.21876  |   0.0757006 |
| LWup     | baseline     |  17.3826  |  15.5446  |   1.31135  |   0.964624 |   0.156194 |  41.0397  |  23.9688  |   0.435567 |  15.5446  |   0.311349 |   0.0353758 |   0.062985   |    0.814521 |   0.152231  |
| LWup     | detailed     |  15.3482  |  11.632   |   1.37539  |   0.963902 |   4.2059   |  48.7469  |  23.5961  |   0.49012  |  11.632   |   0.375394 |   0.0360977 |   0.246347   |    0.444783 |   0.113708  |
| Qle      | baseline     |  24.5295  |   7.73837 |   0.825329 |   0.640399 |  12.2166   |   1.92957 |  36.8269  |   0.789992 |   7.73837 |   0.174672 |   0.359601  |   0.119413   |    0.564057 |   0.268833  |
| Qle      | detailed     |  24.1293  | -10.1392  |   0.843423 |   0.519771 |   7.99588  |  43.3112  |  42.853   |   0.913558 |  10.1392  |   0.156579 |   0.480229  |   1.68519    |    6.9605   |   0.236144  |
| Qh       | baseline     |  34.7856  |  11.6221  |   0.728441 |   0.921976 |  20.5101   |  56.9144  |  46.2687  |   0.432916 |  11.6221  |   0.271561 |   0.0780245 |   0.176878   |    0.421092 |   0.371667  |
| Qh       | detailed     |  29.1894  |   2.95967 |   0.739601 |   0.93426  |  17.8286   |  57.7412  |  42.1321  |   0.406263 |   2.95967 |   0.260402 |   0.0657397 |   0.0823864  |    0.233973 |   0.306151  |
| Qtau     | baseline     | nan       | nan       | nan        | nan        | nan        | nan       | nan       | nan        | nan       | nan        | nan         | nan          |  nan        | nan         |
| Qtau     | detailed     | nan       | nan       | nan        | nan        | nan        | nan       | nan       | nan        | nan       | nan        | nan         | nan          |  nan        | nan         |
| SoilTemp | baseline     | nan       | nan       | nan        | nan        | nan        | nan       | nan       | nan        | nan       | nan        | nan         | nan          |  nan        | nan         |
| SoilTemp | detailed     | nan       | nan       | nan        | nan        | nan        | nan       | nan       | nan        | nan       | nan        | nan         | nan          |  nan        | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![ASLUMv3.1_CA-Sunset_subset_SWup_v0-9.png](ASLUMv3.1_CA-Sunset_subset_SWup_v0-9.png)](ASLUMv3.1_CA-Sunset_subset_SWup_v0-9.png)

### out of range: baseline

 - ASLUMv3.1 SWup min value of -4.0419 is less than expected 0.0 [W/m2]

### out of range: detailed

 - ASLUMv3.1 SWup min value of -5.2524 is less than expected 0.0 [W/m2]
 - ASLUMv3.1 Qle max value of 848.6750 is greater than expected 700.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

