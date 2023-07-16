# PL-Lipowa: K-UCMv1

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](K-UCMv1_PL-Lipowa_baseline_attrs.md)
- [Detailed](K-UCMv1_PL-Lipowa_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |       MBE |        nSD |          R |      5th |       95th |     RMSE |      cRMSE |      AMBE |       1-nSD |         1-R |   nSkewness |   nKurtosis |    Overlap |
|:-------|:-------------|----------:|----------:|-----------:|-----------:|---------:|-----------:|---------:|-----------:|----------:|------------:|------------:|------------:|------------:|-----------:|
| SWup   | baseline     | nan       | nan       | nan        | nan        | nan      | nan        | nan      | nan        | nan       | nan         | nan         |  nan        |  nan        | nan        |
| SWup   | detailed     |   5.97371 |  -4.27668 |   0.923622 |   0.884415 |   0.8783 |   0.815201 |  10.4601 |   0.468345 |   4.27668 |   0.0763794 |   0.115585  |    0.340926 |    0.182561 |   0.14528  |
| LWup   | baseline     | nan       | nan       | nan        | nan        | nan      | nan        | nan      | nan        | nan       | nan         | nan         |  nan        |  nan        | nan        |
| LWup   | detailed     |  16.9397  | -16.7041  |   0.950675 |   0.98792  |  14.5136 |  27.6949   |  19.2089 |   0.159378 |  16.7041  |   0.0493266 |   0.0120801 |    0.336592 |    0.785582 |   0.127003 |
| Qle    | baseline     | nan       | nan       | nan        | nan        | nan      | nan        | nan      | nan        | nan       | nan         | nan         |  nan        |  nan        | nan        |
| Qle    | detailed     |  16.232   |  -5.67662 |   0.559573 |   0.619098 |  12.9076 |  27.5236   |  26.2344 |   0.787566 |   5.67662 |   0.440427  |   0.380902  |    0.293776 |    0.279325 |   0.277412 |
| Qh     | baseline     | nan       | nan       | nan        | nan        | nan      | nan        | nan      | nan        | nan       | nan         | nan         |  nan        |  nan        | nan        |
| Qh     | detailed     |  38.5307  |  29.7495  |   1.04376  |   0.822921 |  18.667  |  33.7539   |  50.5694 |   0.609565 |  29.7495  |   0.0437538 |   0.177079  |    0.173493 |    0.293715 |   0.341263 |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![K-UCMv1_PL-Lipowa_subset_SWup_v0-9.png](K-UCMv1_PL-Lipowa_subset_SWup_v0-9.png)](K-UCMv1_PL-Lipowa_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed

 - K-UCMv1 Qstor min value of -951.6917 is less than expected -800.0 [W/m2]
 - K-UCMv1 Qh max value of 725.7769 is greater than expected 600.0 [W/m2]
 - K-UCMv1 SWnet min value of -1.6245 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

