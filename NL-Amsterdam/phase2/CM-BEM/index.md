# NL-Amsterdam: CM-BEM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](CM-BEM_NL-Amsterdam_baseline_attrs.md)
- [Detailed](CM-BEM_NL-Amsterdam_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |        MBE |        nSD |          R |        5th |      95th |      RMSE |      cRMSE |       AMBE |       1-nSD |         1-R |   nSkewness |   nKurtosis |     Overlap |
|:-------|:-------------|----------:|-----------:|-----------:|-----------:|-----------:|----------:|----------:|-----------:|-----------:|------------:|------------:|------------:|------------:|------------:|
| SWup   | baseline     | nan       | nan        | nan        | nan        | nan        | nan       | nan       | nan        | nan        | nan         | nan         | nan         | nan         | nan         |
| SWup   | detailed     |   5.24831 |  -0.791466 |   0.922418 |   0.947402 |   0.321233 |   6.47133 |   8.02755 |   0.32102  |   0.791466 |   0.0775821 |   0.052598  |   0.0636186 |   0.0141764 |   0.0773175 |
| LWup   | baseline     | nan       | nan        | nan        | nan        | nan        | nan       | nan       | nan        | nan        | nan         | nan         | nan         | nan         | nan         |
| LWup   | detailed     |  13.1659  |  -8.08335  |   1.20144  |   0.973607 |  14.7533   |  14.0385  |  14.9656  |   0.322483 |   8.08335  |   0.201435  |   0.0263928 |   0.303111  |   0.291949  |   0.164469  |
| Qle    | baseline     | nan       | nan        | nan        | nan        | nan        | nan       | nan       | nan        | nan        | nan         | nan         | nan         | nan         | nan         |
| Qle    | detailed     |  20.6099  |  -9.79554  |   0.797878 |   0.512312 |   4.38058  |  14.0158  |  33.2536  |   0.905033 |   9.79554  |   0.202122  |   0.487688  |   0.127038  |   0.583042  |   0.218873  |
| Qh     | baseline     | nan       | nan        | nan        | nan        | nan        | nan       | nan       | nan        | nan        | nan         | nan         | nan         | nan         | nan         |
| Qh     | detailed     |  46.7215  |  37.5599   |   1.2057   |   0.857857 |  17.8801   |  91.6282  |  68.955   |   0.620544 |  37.5599   |   0.205701  |   0.142143  |   0.49313   |   0.810246  |   0.143569  |
| Qtau   | baseline     | nan       | nan        | nan        | nan        | nan        | nan       | nan       | nan        | nan        | nan         | nan         | nan         | nan         | nan         |
| Qtau   | detailed     | nan       | nan        | nan        | nan        | nan        | nan       | nan       | nan        | nan        | nan         | nan         | nan         | nan         | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![CM-BEM_NL-Amsterdam_subset_SWup_v0-9.png](CM-BEM_NL-Amsterdam_subset_SWup_v0-9.png)](CM-BEM_NL-Amsterdam_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed

 - CM-BEM SWnet min value of -10.9792 is less than expected 0.0 [W/m2]
 - CM-BEM SWup min value of -2.7146 is less than expected 0.0 [W/m2]
 - CM-BEM Albedo min value of -0.0250 is less than expected 0.0 [1]
 - CM-BEM alb min value of -0.0248 is less than expected 0.0 [1]
 - CM-BEM Qanth max value of 54867.5300 is greater than expected 1000.0 [W/m2]
 - CM-BEM Qanth min value of -6132.4500 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

