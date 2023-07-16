# NL-Amsterdam: K-UCMv1

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](K-UCMv1_NL-Amsterdam_baseline_attrs.md)
- [Detailed](K-UCMv1_NL-Amsterdam_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |       MBE |        nSD |          R |        5th |      95th |      RMSE |      cRMSE |      AMBE |       1-nSD |         1-R |   nSkewness |   nKurtosis |     Overlap |
|:-------|:-------------|----------:|----------:|-----------:|-----------:|-----------:|----------:|----------:|-----------:|----------:|------------:|------------:|------------:|------------:|------------:|
| SWup   | baseline     | nan       | nan       | nan        | nan        | nan        | nan       | nan       | nan        | nan       | nan         | nan         |  nan        |  nan        | nan         |
| SWup   | detailed     |   4.29715 |  -1.97135 |   0.906419 |   0.971034 |   0.596633 |   4.98003 |   6.4667  |   0.247526 |   1.97135 |   0.093581  |   0.0289664 |    0.22169  |    1.01622  |   0.0933841 |
| LWup   | baseline     | nan       | nan       | nan        | nan        | nan        | nan       | nan       | nan        | nan       | nan         | nan         |  nan        |  nan        | nan         |
| LWup   | detailed     |   6.97814 |   2.56306 |   0.952679 |   0.973684 |   3.30801  |   5.19055 |   9.29833 |   0.228868 |   2.56306 |   0.047322  |   0.0263159 |    0.318824 |    0.260253 |   0.0880737 |
| Qle    | baseline     | nan       | nan       | nan        | nan        | nan        | nan       | nan       | nan        | nan       | nan         | nan         |  nan        |  nan        | nan         |
| Qle    | detailed     |  27.282   | -25.3674  |   0.334196 |   0.437479 |   2.76238  |  65.1822  |  40.6613  |   0.90514  |  25.3674  |   0.665804  |   0.562521  |    2.77132  |   12.5438   |   0.575716  |
| Qh     | baseline     | nan       | nan       | nan        | nan        | nan        | nan       | nan       | nan        | nan       | nan         | nan         |  nan        |  nan        | nan         |
| Qh     | detailed     |  37.6391  |   5.90382 |   1.06826  |   0.835626 |   5.8789   |  30.5023  |  55.898   |   0.596531 |   5.90382 |   0.0682628 |   0.164374  |    0.571653 |    0.481561 |   0.0960004 |
| Qtau   | baseline     | nan       | nan       | nan        | nan        | nan        | nan       | nan       | nan        | nan       | nan         | nan         |  nan        |  nan        | nan         |
| Qtau   | detailed     | nan       | nan       | nan        | nan        | nan        | nan       | nan       | nan        | nan       | nan         | nan         |  nan        |  nan        | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![K-UCMv1_NL-Amsterdam_subset_SWup_v0-9.png](K-UCMv1_NL-Amsterdam_subset_SWup_v0-9.png)](K-UCMv1_NL-Amsterdam_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed

 - K-UCMv1 Qstor min value of -2207.5574 is less than expected -800.0 [W/m2]
 - K-UCMv1 Qh max value of 1460.4344 is greater than expected 600.0 [W/m2]
 - K-UCMv1 SWnet min value of -0.6053 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

