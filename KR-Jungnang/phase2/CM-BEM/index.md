# KR-Jungnang: CM-BEM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](CM-BEM_KR-Jungnang_baseline_attrs.md)
- [Detailed](CM-BEM_KR-Jungnang_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |       MBE |        nSD |          R |        5th |     95th |     RMSE |      cRMSE |      AMBE |        1-nSD |         1-R |   nSkewness |   nKurtosis |    Overlap |
|:-------|:-------------|----------:|----------:|-----------:|-----------:|-----------:|---------:|---------:|-----------:|----------:|-------------:|------------:|------------:|------------:|-----------:|
| SWup   | baseline     | nan       | nan       | nan        | nan        | nan        | nan      | nan      | nan        | nan       | nan          | nan         | nan         |  nan        | nan        |
| SWup   | detailed     |   8.85189 |  -4.10019 |   0.994585 |   0.941663 |   1.35378  |   6.8001 |  11.9114 |   0.340694 |   4.10019 |   0.00541598 |   0.0583374 |   0.150375  |    0.416264 |   0.104307 |
| LWup   | baseline     | nan       | nan       | nan        | nan        | nan        | nan      | nan      | nan        | nan       | nan          | nan         | nan         |  nan        | nan        |
| LWup   | detailed     |  18.0023  |  -3.26542 |   1.21601  |   0.975021 |  15.7412   |  39.4902 |  22.4622 |   0.327733 |   3.26542 |   0.216006   |   0.0249791 |   1.76189   |    1.01066  |   0.112172 |
| Qle    | baseline     | nan       | nan       | nan        | nan        | nan        | nan      | nan      | nan        | nan       | nan          | nan         | nan         |  nan        | nan        |
| Qle    | detailed     |  17.187   |  -9.32187 |   0.465776 |   0.31133  |   0.970416 |  39.9103 |  28.9775 |   0.96277  |   9.32187 |   0.534224   |   0.68867   |   0.516774  |    0.472801 |   0.187481 |
| Qh     | baseline     | nan       | nan       | nan        | nan        | nan        | nan      | nan      | nan        | nan       | nan          | nan         | nan         |  nan        | nan        |
| Qh     | detailed     |  59.2677  |  42.8957  |   1.46283  |   0.779591 |  19.6928   | 124.601  |  83.0109 |   0.92685  |  42.8957  |   0.462827   |   0.220409  |   0.0425473 |    0.313381 |   0.254096 |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![CM-BEM_KR-Jungnang_subset_SWup_v0-9.png](CM-BEM_KR-Jungnang_subset_SWup_v0-9.png)](CM-BEM_KR-Jungnang_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed

 - CM-BEM SWnet min value of -9.1857 is less than expected 0.0 [W/m2]
 - CM-BEM SWup min value of -9.5545 is less than expected 0.0 [W/m2]
 - CM-BEM Albedo min value of -0.0368 is less than expected 0.0 [1]
 - CM-BEM alb min value of -0.0368 is less than expected 0.0 [1]
 - CM-BEM Qle min value of -2474.7385 is less than expected -700.0 [W/m2]
 - CM-BEM Qanth min value of -46.3700 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

