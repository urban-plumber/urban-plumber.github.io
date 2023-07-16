# UK-Swindon: ASLUMv2.0

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](ASLUMv2.0_UK-Swindon_baseline_attrs.md)
- [Detailed](ASLUMv2.0_UK-Swindon_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |       MBE |        nSD |          R |        5th |      95th |      RMSE |      cRMSE |      AMBE |       1-nSD |          1-R |   nSkewness |   nKurtosis |     Overlap |
|:-------|:-------------|----------:|----------:|-----------:|-----------:|-----------:|----------:|----------:|-----------:|----------:|------------:|-------------:|------------:|------------:|------------:|
| SWup   | baseline     |   5.03534 |   4.02343 |   1.14778  |   0.990094 |   0.805065 |  12.6025  |   7.49264 |   0.211136 |   4.02343 |   0.147778  |   0.00990618 |   0.0362955 |   0.156815  |   0.0966888 |
| SWup   | detailed     |   2.66497 |  -1.48851 |   0.967677 |   0.990018 |   0.903143 |   4.23263 |   4.52398 |   0.142704 |   1.48851 |   0.0323232 |   0.00998245 |   0.0457855 |   0.22578   |   0.0745867 |
| LWup   | baseline     |  14.4549  |  13.0323  |   1.27937  |   0.974505 |   4.80958  |  33.6098  |  18.4865  |   0.378526 |  13.0323  |   0.279368  |   0.0254948  |   0.420652  |   0.5745    |   0.149065  |
| LWup   | detailed     |  11.1566  |   9.52837 |   1.35026  |   0.970497 |   0.807337 |  40.9664  |  18.2641  |   0.449841 |   9.52837 |   0.35026   |   0.029503   |   1.23204   |   8.99668   |   0.0809624 |
| Qle    | baseline     |  20.9372  |  14.8936  |   1.15035  |   0.840531 |   6.90601  |  32.7687  |  29.2557  |   0.624094 |  14.8936  |   0.150346  |   0.159469   |   0.0329329 |   0.0165674 |   0.2769    |
| Qle    | detailed     |  24.7954  |  21.7709  |   1.28775  |   0.857828 |   9.12215  |  48.3109  |  34.7111  |   0.670047 |  21.7709  |   0.28775   |   0.142172   |   0.0614088 |   0.0937356 |   0.34293   |
| Qh     | baseline     |  25.3073  |  16.3732  |   0.784813 |   0.901058 |  25.3994   |  17.7581  |  31.9346  |   0.449008 |  16.3732  |   0.215187  |   0.0989423  |   0.199344  |   0.460401  |   0.3594    |
| Qh     | detailed     |  21.6565  |  15.4393  |   0.883009 |   0.925115 |  18.7481   |   5.85704 |  27.9737  |   0.382016 |  15.4393  |   0.116991  |   0.0748855  |   0.150099  |   0.346997  |   0.297851  |
| Qtau   | baseline     | nan       | nan       | nan        | nan        | nan        | nan       | nan       | nan        | nan       | nan         | nan          | nan         | nan         | nan         |
| Qtau   | detailed     | nan       | nan       | nan        | nan        | nan        | nan       | nan       | nan        | nan       | nan         | nan          | nan         | nan         | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![ASLUMv2.0_UK-Swindon_subset_SWup_v0-9.png](ASLUMv2.0_UK-Swindon_subset_SWup_v0-9.png)](ASLUMv2.0_UK-Swindon_subset_SWup_v0-9.png)

### out of range: baseline

 - ASLUMv2.0 SWup min value of -11.5294 is less than expected 0.0 [W/m2]
 - ASLUMv2.0 alb min value of -0.0251 is less than expected 0.0 [1]
 - ASLUMv2.0 Albedo min value of -0.0251 is less than expected 0.0 [1]

### out of range: detailed

 - ASLUMv2.0 SWup min value of -27.0959 is less than expected 0.0 [W/m2]
 - ASLUMv2.0 alb min value of -0.0589 is less than expected 0.0 [1]
 - ASLUMv2.0 Albedo min value of -0.0589 is less than expected 0.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

