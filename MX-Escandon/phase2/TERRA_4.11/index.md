# MX-Escandon: TERRA_4.11

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](TERRA_4.11_MX-Escandon_baseline_attrs.md)
- [Detailed](TERRA_4.11_MX-Escandon_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |       MBE |        nSD |          R |       5th |     95th |      RMSE |      cRMSE |      AMBE |       1-nSD |         1-R |   nSkewness |   nKurtosis |    Overlap |
|:-------|:-------------|----------:|----------:|-----------:|-----------:|----------:|---------:|----------:|-----------:|----------:|------------:|------------:|------------:|------------:|-----------:|
| SWup   | baseline     |  10.3843  | -10.3795  |   0.877873 |   0.98208  |   2.89181 |  13.3197 |  12.2615  |   0.215354 |  10.3795  |   0.122127  |   0.0179196 |    0.737184 |   0.0247158 |   0.155424 |
| SWup   | detailed     |   5.14466 |  -3.29274 |   1.06203  |   0.98208  |   2.83555 |   3.29   |   7.02476 |   0.204718 |   3.29274 |   0.0620259 |   0.0179196 |    0.737185 |   0.024716  |   0.145945 |
| LWup   | baseline     | nan       | nan       | nan        | nan        | nan       | nan      | nan       | nan        | nan       | nan         | nan         |  nan        | nan         | nan        |
| LWup   | detailed     | nan       | nan       | nan        | nan        | nan       | nan      | nan       | nan        | nan       | nan         | nan         |  nan        | nan         | nan        |
| Qle    | baseline     |  25.8533  | -20.787   |   0.489539 |   0.37729  |   2.91933 |  59.2566 |  39.8316  |   0.932873 |  20.787   |   0.510461  |   0.62271   |    1.09685  |   1.88099   |   0.51405  |
| Qle    | detailed     |  25.244   | -21.1057  |   0.526601 |   0.45231  |   2.91198 |  54.8404 |  38.8324  |   0.89495  |  21.1057  |   0.473399  |   0.54769   |    1.09918  |   1.63325   |   0.575768 |
| Qh     | baseline     |  93.9805  |  87.416   |   1.33053  |   0.696086 |  53.2288  | 141.635  | 114.844   |   0.958117 |  87.416   |   0.330535  |   0.303914  |    0.149723 |   1.17036   |   0.572482 |
| Qh     | detailed     |  35.5537  |  12.1278  |   1.20489  |   0.808546 |  10.0644  |  50.2867 |  56.4697  |   0.709466 |  12.1278  |   0.204891  |   0.191454  |    0.145581 |   0.581035  |   0.331474 |
| Qtau   | baseline     | nan       | nan       | nan        | nan        | nan       | nan      | nan       | nan        | nan       | nan         | nan         |  nan        | nan         | nan        |
| Qtau   | detailed     | nan       | nan       | nan        | nan        | nan       | nan      | nan       | nan        | nan       | nan         | nan         |  nan        | nan         | nan        |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![TERRA_4.11_MX-Escandon_subset_SWup_v0-9.png](TERRA_4.11_MX-Escandon_subset_SWup_v0-9.png)](TERRA_4.11_MX-Escandon_subset_SWup_v0-9.png)

### out of range: baseline

 - TERRA_4.11 SWup min value of -0.0020 is less than expected 0.0 [W/m2]
 - TERRA_4.11 Albedo min value of -0.0803 is less than expected 0.0 [1]
 - TERRA_4.11 Qh max value of 677.6229 is greater than expected 600.0 [W/m2]

### out of range: detailed

 - TERRA_4.11 SWup min value of -0.0015 is less than expected 0.0 [W/m2]
 - TERRA_4.11 Albedo min value of -0.0592 is less than expected 0.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

