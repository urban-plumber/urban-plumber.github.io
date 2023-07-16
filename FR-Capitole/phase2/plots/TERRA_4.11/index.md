# FR-Capitole: TERRA_4.11

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](TERRA_4.11_FR-Capitole_baseline_attrs.md)
- [Detailed](TERRA_4.11_FR-Capitole_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |       MBE |        nSD |          R |       5th |      95th |      RMSE |      cRMSE |      AMBE |       1-nSD |          1-R |   nSkewness |   nKurtosis |     Overlap |
|:-------|:-------------|----------:|----------:|-----------:|-----------:|----------:|----------:|----------:|-----------:|----------:|------------:|-------------:|------------:|------------:|------------:|
| SWup   | baseline     |  14.9078  | -14.9077  |   0.696712 |   0.9903   |   2.81922 |  32.8735  |  18.4497  |   0.324809 |  14.9077  |   0.303288  |   0.00970049 |   0.138353  |    0.239236 |   0.178295  |
| SWup   | detailed     |   4.20878 |  -2.84246 |   1.02486  |   0.990299 |   2.71696 |   1.01648 |   5.57126 |   0.143182 |   2.84246 |   0.0248557 |   0.00970052 |   0.138357  |    0.239239 |   0.140165  |
| LWup   | baseline     |  56.2868  | -56.2861  |   0.855223 |   0.770286 |  68.9732  |  92.6853  |  65.6833  |   0.64333  |  56.2861  |   0.144777  |   0.229714   |   1.43067   |    2.47671  |   0.337269  |
| LWup   | detailed     |   7.10436 |   1.37236 |   1.14726  |   0.995581 |   8.55753 |  17.8203  |   9.48784 |   0.178396 |   1.37236 |   0.147257  |   0.0044194  |   0.0161113 |    0.235335 |   0.0821365 |
| Qle    | baseline     |  13.1705  |  -8.19286 |   0.771893 |   0.620371 |   5.46502 |  17.7569  |  18.417   |   0.798811 |   8.19286 |   0.228108  |   0.379629   |   1.30415   |    1.79882  |   0.429475  |
| Qle    | detailed     |  13.886   |  -9.42088 |   0.752164 |   0.60945  |   5.36321 |  16.7103  |  19.1164  |   0.805567 |   9.42088 |   0.247837  |   0.39055    |   1.10337   |    1.19914  |   0.482145  |
| Qh     | baseline     |  66.1241  |  61.0138  |   1.33595  |   0.879854 |  43.0591  | 131.593   |  81.571   |   0.658693 |  61.0138  |   0.335947  |   0.120146   |   0.0332515 |    0.112488 |   0.414681  |
| Qh     | detailed     |  40.6655  |  34.158   |   1.02268  |   0.909661 |  36.2461  |  38.6083  |  49.1786  |   0.430454 |  34.158   |   0.0226834 |   0.0903389  |   0.111459  |    0.45805  |   0.337479  |
| Qtau   | baseline     | nan       | nan       | nan        | nan        | nan       | nan       | nan       | nan        | nan       | nan         | nan          | nan         |  nan        | nan         |
| Qtau   | detailed     | nan       | nan       | nan        | nan        | nan       | nan       | nan       | nan        | nan       | nan         | nan          | nan         |  nan        | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![TERRA_4.11_FR-Capitole_subset_SWup_v0-9.png](TERRA_4.11_FR-Capitole_subset_SWup_v0-9.png)](TERRA_4.11_FR-Capitole_subset_SWup_v0-9.png)

### out of range: baseline

 - TERRA_4.11 SWup min value of -0.0032 is less than expected 0.0 [W/m2]
 - TERRA_4.11 Albedo min value of -0.2161 is less than expected 0.0 [1]

### out of range: detailed

 - TERRA_4.11 SWup min value of -0.0024 is less than expected 0.0 [W/m2]
 - TERRA_4.11 Albedo min value of -0.1609 is less than expected 0.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

