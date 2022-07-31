# AU-Preston: JULES_2T

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |       MAE |         MBE |      nSD |        R |          5th |      95th |      RMSE |    cRMSE |       AMBE |     1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|----------:|------------:|---------:|---------:|-------------:|----------:|----------:|---------:|-----------:|----------:|-----------:|------------:|------------:|----------:|
| SWup   | baseline     | 12.7726   |  12.5085    | 1.24456  | 0.996707 |  0.250629    | 35.9891   | 17.4373   | 0.260782 | 12.5085    | 0.244562  | 0.00329283 |   0.011806  |  0.0199241  | 0.104541  |
| SWup   | detailed     |  6.14903  |   5.60673   | 1.11664  | 0.996707 |  0.400626    | 17.283    |  8.77069  | 0.144775 |  5.60673   | 0.116644  | 0.00329283 |   0.011806  |  0.0199241  | 0.0869166 |
| LWup   | baseline     | 10.8704   |   9.63563   | 1.14188  | 0.980989 |  3.886       | 24.5896   | 14.318    | 0.252085 |  9.63563   | 0.141878  | 0.0190114  |   0.0400601 |  0.00138273 | 0.0930473 |
| LWup   | detailed     | 14.8817   |  10.4069    | 1.32218  | 0.964906 |  2.01742     | 44.8288   | 21.3378   | 0.443394 | 10.4069    | 0.322177  | 0.0350936  |   0.111143  |  0.096554   | 0.0867249 |
| Qle    | baseline     | 23.7482   | -11.2661    | 0.533141 | 0.660549 | 12.08        | 51.9296   | 41.2257   | 0.761517 | 11.2661    | 0.466859  | 0.339451   |   0.0148997 |  0.440156   | 0.250742  |
| Qle    | detailed     | 22.1794   |   2.07855   | 0.866015 | 0.694112 | 11.4912      |  2.25706  | 38.5975   | 0.740107 |  2.07855   | 0.133985  | 0.305888   |   0.158473  |  0.740526   | 0.177345  |
| Qh     | baseline     | 23.1381   |   1.95697   | 1.0867   | 0.926099 | 10.2021      | 18.6321   | 37.7714   | 0.41004  |  1.95697   | 0.0867019 | 0.0739005  |   0.0207622 |  0.069782   | 0.0713628 |
| Qh     | detailed     | 21.3324   |  -7.40508   | 1.01269  | 0.93603  | 16.4968      |  7.35162  | 33.9507   | 0.360173 |  7.40508   | 0.0126859 | 0.0639704  |   0.0199453 |  0.0116485  | 0.096422  |
| Qtau   | baseline     |  0.179025 |   0.148254  | 1.30328  | 0.870971 |  0.0094988   |  0.308661 |  0.260941 | 0.654445 |  0.148254  | 0.303279  | 0.129029   |   0.142677  |  0.180424   | 0.18081   |
| Qtau   | detailed     |  0.115546 |   0.0507882 | 1.06168  | 0.873524 |  0.000273709 |  0.055002 |  0.17861  | 0.52188  |  0.0507882 | 0.0616797 | 0.126476   |   0.137217  |  0.176877   | 0.0913294 |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="datasheet"></a>Datasheet
[![JULES_2T_AU-Preston_Datasheet.png](JULES_2T_AU-Preston_Datasheet.png)](JULES_2T_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![JULES_2T_AU-Preston_Distributions.png](JULES_2T_AU-Preston_Distributions.png)](JULES_2T_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![JULES_2T_AU-Preston_closure_baseline.png](JULES_2T_AU-Preston_closure_baseline.png)](JULES_2T_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![JULES_2T_AU-Preston_closure_detailed.png](JULES_2T_AU-Preston_closure_detailed.png)](JULES_2T_AU-Preston_closure_detailed.png)

### <a name="subset_lwup"></a>subset_LWup
[![JULES_2T_AU-Preston_subset_LWup.png](JULES_2T_AU-Preston_subset_LWup.png)](JULES_2T_AU-Preston_subset_LWup.png)

### <a name="subset_qh"></a>subset_Qh
[![JULES_2T_AU-Preston_subset_Qh.png](JULES_2T_AU-Preston_subset_Qh.png)](JULES_2T_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![JULES_2T_AU-Preston_subset_Qle.png](JULES_2T_AU-Preston_subset_Qle.png)](JULES_2T_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![JULES_2T_AU-Preston_subset_SWup.png](JULES_2T_AU-Preston_subset_SWup.png)](JULES_2T_AU-Preston_subset_SWup.png)

### out of range: baseline

 - JULES_2T SWE min value of -0.0000 is less than expected 0.0 [kg/m2]
 - JULES_2T EvapF max value of 54.0354 is greater than expected 1.0 [1]
 - JULES_2T EvapF min value of -28.4239 is less than expected 0.0 [1]

### out of range: detailed

 - JULES_2T SWE min value of -0.0000 is less than expected 0.0 [kg/m2]
 - JULES_2T EvapF max value of 51.2599 is greater than expected 1.0 [1]
 - JULES_2T EvapF min value of -16.3861 is less than expected 0.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

