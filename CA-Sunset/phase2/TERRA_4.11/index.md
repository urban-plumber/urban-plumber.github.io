# CA-Sunset: TERRA_4.11

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](TERRA_4.11_CA-Sunset_baseline_attrs.md)
- [Detailed](TERRA_4.11_CA-Sunset_detailed_attrs.md)

### Error metrics

| flux     | experiment   |       MAE |        MBE |        nSD |          R |        5th |        95th |      RMSE |      cRMSE |       AMBE |        1-nSD |         1-R |     nSkewness |   nKurtosis |     Overlap |
|:---------|:-------------|----------:|-----------:|-----------:|-----------:|-----------:|------------:|----------:|-----------:|-----------:|-------------:|------------:|--------------:|------------:|------------:|
| SWup     | baseline     |   4.74251 |  -3.78265  |   0.916784 |   0.976825 |   0.768405 |   8.40474   |   7.29912 |   0.222303 |   3.78265  |   0.0832138  |   0.0231755 |   0.000549134 |   0.48831   |   0.0810005 |
| SWup     | detailed     |   4.31498 |   0.620998 |   1.07399  |   0.97686  |   0.740117 |   5.135     |   6.62547 |   0.234901 |   0.620998 |   0.0739887  |   0.0231402 |   0.000557385 |   0.48791   |   0.0775543 |
| LWup     | baseline     |  25.4274  | -24.9206   |   0.913281 |   0.865394 |  34.6376   |  46.1626    |  32.6437  |   0.503375 |  24.9206   |   0.0867193  |   0.134606  |   0.929502    |   0.0410758 |   0.199648  |
| LWup     | detailed     |  10.6897  |   3.0798   |   1.24943  |   0.963772 |   6.89542  |  29.5854    |  16.6578  |   0.390825 |   3.0798   |   0.249432   |   0.0362275 |   0.253373    |   0.651304  |   0.0808287 |
| Qle      | baseline     |  20.3817  | -11.7843   |   0.647198 |   0.686339 |   7.91761  |  33.919     |  35.2242  |   0.728334 |  11.7843   |   0.352804   |   0.313661  |   0.0303724   |   0.517788  |   0.32788   |
| Qle      | detailed     |  21.1237  | -13.4197   |   0.634731 |   0.681304 |   6.75908  |  37.8189    |  36.0221  |   0.733481 |  13.4197   |   0.365271   |   0.318696  |   0.0271044   |   0.508205  |   0.340961  |
| Qh       | baseline     |  41.9651  |  34.4276   |   0.931804 |   0.933999 |  27.8329   |  20.0878    |  50.511   |   0.357282 |  34.4276   |   0.0681996  |   0.0660008 |   0.130553    |   0.364202  |   0.431366  |
| Qh       | detailed     |  29.9608  |  19.0699   |   0.933304 |   0.940431 |  22.6477   |   6.18033   |  40.0154  |   0.340059 |  19.0699   |   0.0666993  |   0.059569  |   0.0993556   |   0.325978  |   0.363054  |
| Qtau     | baseline     | nan       | nan        | nan        | nan        | nan        | nan         | nan       | nan        | nan        | nan          | nan         | nan           | nan         | nan         |
| Qtau     | detailed     | nan       | nan        | nan        | nan        | nan        | nan         | nan       | nan        | nan        | nan          | nan         | nan           | nan         | nan         |
| SoilTemp | baseline     |   2.54179 |   0.115908 |   1.12127  |   0.892949 |   0.808289 |   3.07452   |   3.35742 |   0.504748 |   0.115908 |   0.121273   |   0.107051  |   0.894566    |   0.840977  |   0.126485  |
| SoilTemp | detailed     |   2.26713 |  -0.889515 |   0.99575  |   0.915794 |   0.789001 |   0.0422974 |   2.86405 |   0.409529 |   0.889515 |   0.00424328 |   0.0842058 |   0.189921    |   0.796929  |   0.1183    |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![TERRA_4.11_CA-Sunset_subset_SWup_v0-9.png](TERRA_4.11_CA-Sunset_subset_SWup_v0-9.png)](TERRA_4.11_CA-Sunset_subset_SWup_v0-9.png)

### out of range: baseline

 - TERRA_4.11 SWup min value of -0.0019 is less than expected 0.0 [W/m2]
 - TERRA_4.11 Albedo min value of -0.0763 is less than expected 0.0 [1]

### out of range: detailed

 - TERRA_4.11 SWup min value of -0.0014 is less than expected 0.0 [W/m2]
 - TERRA_4.11 Albedo min value of -0.0551 is less than expected 0.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

