# GR-HECKOR: K-UCMv1

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](K-UCMv1_GR-HECKOR_baseline_attrs.md)
- [Detailed](K-UCMv1_GR-HECKOR_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |       MBE |        nSD |          R |       5th |      95th |      RMSE |      cRMSE |      AMBE |       1-nSD |         1-R |   nSkewness |   nKurtosis |    Overlap |
|:-------|:-------------|----------:|----------:|-----------:|-----------:|----------:|----------:|----------:|-----------:|----------:|------------:|------------:|------------:|------------:|-----------:|
| SWup   | baseline     | nan       | nan       | nan        | nan        | nan       | nan       | nan       | nan        | nan       | nan         | nan         |  nan        | nan         | nan        |
| SWup   | detailed     |  23.0298  | -22.8951  |   0.873611 |   0.978885 |   2.17664 |  24.6944  |  26.8933  |   0.229929 |  22.8951  |   0.12639   |   0.0211154 |    1.35191  |   0.221361  |   0.141311 |
| LWup   | baseline     | nan       | nan       | nan        | nan        | nan       | nan       | nan       | nan        | nan       | nan         | nan         |  nan        | nan         | nan        |
| LWup   | detailed     |   7.59486 |  -4.52935 |   1.08086  |   0.98895  |   5.98609 |   6.88389 |   8.85879 |   0.174433 |   4.52935 |   0.0808629 |   0.0110503 |    0.573807 |   0.720251  |   0.11993  |
| Qle    | baseline     | nan       | nan       | nan        | nan        | nan       | nan       | nan       | nan        | nan       | nan         | nan         |  nan        | nan         | nan        |
| Qle    | detailed     |  22.8899  | -19.415   |   0.172597 |   0.458564 |   4.48403 |  68.8861  |  38.3454  |   0.93354  |  19.415   |   0.827403  |   0.541436  |    0.283232 |   0.0747396 |   0.468996 |
| Qh     | baseline     | nan       | nan       | nan        | nan        | nan       | nan       | nan       | nan        | nan       | nan         | nan         |  nan        | nan         | nan        |
| Qh     | detailed     |  37.4795  |  11.3826  |   1.31856  |   0.923297 |  12.8964  |  96.3484  |  59.4457  |   0.551142 |  11.3826  |   0.318563  |   0.0767027 |    0.12277  |   2.90557   |   0.212535 |
| Qtau   | baseline     | nan       | nan       | nan        | nan        | nan       | nan       | nan       | nan        | nan       | nan         | nan         |  nan        | nan         | nan        |
| Qtau   | detailed     | nan       | nan       | nan        | nan        | nan       | nan       | nan       | nan        | nan       | nan         | nan         |  nan        | nan         | nan        |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![K-UCMv1_GR-HECKOR_subset_SWup_v0-9.png](K-UCMv1_GR-HECKOR_subset_SWup_v0-9.png)](K-UCMv1_GR-HECKOR_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed

 - K-UCMv1 Qstor min value of -2389.5923 is less than expected -800.0 [W/m2]
 - K-UCMv1 Qh max value of 2007.9720 is greater than expected 600.0 [W/m2]
 - K-UCMv1 SWnet min value of -2.4145 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

