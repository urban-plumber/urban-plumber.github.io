# GR-HECKOR: TEB-READING

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](TEB-READING_GR-HECKOR_baseline_attrs.md)
- [Detailed](TEB-READING_GR-HECKOR_detailed_attrs.md)

### Error metrics

| flux   | experiment   |      MAE |       MBE |        nSD |          R |       5th |     95th |     RMSE |      cRMSE |      AMBE |      1-nSD |         1-R |   nSkewness |   nKurtosis |     Overlap |
|:-------|:-------------|---------:|----------:|-----------:|-----------:|----------:|---------:|---------:|-----------:|----------:|-----------:|------------:|------------:|------------:|------------:|
| SWup   | baseline     |  41.6734 | -41.672   |   0.549058 |   0.989558 |   3.2879  |  90.9094 |  50.4522 |   0.463482 |  41.672   |   0.450942 |   0.010442  |   0.290487  |   0.16545   |   0.125734  |
| SWup   | detailed     |  16.3069 | -16.2677  |   0.904951 |   0.98942  |   2.73432 |  22.6213 |  19.2551 |   0.167879 |  16.2677  |   0.09505  |   0.0105801 |   0.474332  |   0.0101841 |   0.100417  |
| LWup   | baseline     |  29.607  |  28.9013  |   1.68648  |   0.935619 |   4.43834 |  99.8655 |  46.3321 |   0.8297   |  28.9013  |   0.686472 |   0.0643807 |   1.2186    |   0.960949  |   0.0992281 |
| LWup   | detailed     |  31.0194 |  28.1674  |   1.76649  |   0.925473 |   1.27997 | 106.18   |  49.1341 |   0.922392 |  28.1674  |   0.766485 |   0.0745265 |   1.26728   |   0.955083  |   0.106474  |
| Qle    | baseline     |  23.6478 | -14.7787  |   0.761562 |   0.273164 |   3.30373 |  48.286  |  40.9709 |   1.07885  |  14.7787  |   0.238438 |   0.726836  |   2.17601   |   6.22388   |   0.422928  |
| Qle    | detailed     |  22.1926 |  -9.50871 |   0.857498 |   0.310478 |   3.30373 |  39.457  |  39.9931 |   1.09674  |   9.50871 |   0.142502 |   0.689522  |   1.52727   |   3.87318   |   0.27173   |
| Qh     | baseline     |  43.4203 |  37.3792  |   1.3476   |   0.93644  |  13.2589  | 130.755  |  68.3455 |   0.540495 |  37.3792  |   0.347603 |   0.0635604 |   0.0109022 |   0.330725  |   0.163556  |
| Qh     | detailed     |  35.0413 |  11.6347  |   1.25403  |   0.930283 |   3.94276 |  77.8581 |  53.0859 |   0.48927  |  11.6347  |   0.254031 |   0.0697166 |   0.0485926 |   0.579622  |   0.228223  |
| Qtau   | baseline     | nan      | nan       | nan        | nan        | nan       | nan      | nan      | nan        | nan       | nan        | nan         | nan         | nan         | nan         |
| Qtau   | detailed     | nan      | nan       | nan        | nan        | nan       | nan      | nan      | nan        | nan       | nan        | nan         | nan         | nan         | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![TEB-READING_GR-HECKOR_subset_SWup_v0-9.png](TEB-READING_GR-HECKOR_subset_SWup_v0-9.png)](TEB-READING_GR-HECKOR_subset_SWup_v0-9.png)

### out of range: baseline

 - TEB-READING Qanth min value of -51.0930 is less than expected 0.0 [W/m2]

### out of range: detailed

 - TEB-READING Qanth min value of -66.1370 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

