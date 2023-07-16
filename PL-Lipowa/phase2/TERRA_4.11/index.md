# PL-Lipowa: TERRA_4.11

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](TERRA_4.11_PL-Lipowa_baseline_attrs.md)
- [Detailed](TERRA_4.11_PL-Lipowa_detailed_attrs.md)

### Error metrics

| flux   | experiment   |      MAE |        MBE |      nSD |        R |       5th |     95th |    RMSE |    cRMSE |      AMBE |     1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|---------:|-----------:|---------:|---------:|----------:|---------:|--------:|---------:|----------:|----------:|-----------:|------------:|------------:|----------:|
| SWup   | baseline     |  5.59155 |   0.977007 | 1.26209  | 0.897156 |  0.933906 |  11.1041 | 11.719  | 0.572966 |  0.977007 | 0.262089  | 0.102844   |    1.41239  |  17.4746    |  0.141131 |
| SWup   | detailed     |  5.8941  |   1.6621   | 1.28232  | 0.907397 |  0.926833 |  13.1658 | 11.5989 | 0.563201 |  1.6621   | 0.282314  | 0.092603   |    1.21515  |  14.3838    |  0.14741  |
| LWup   | baseline     | 42.4208  | -42.4185   | 0.841923 | 0.886537 | 42.3029   |  71.0757 | 50.6399 | 0.464803 | 42.4185   | 0.15808   | 0.113463   |    1.39058  |   0.628239  |  0.233523 |
| LWup   | detailed     | 17.9683  | -17.7848   | 1.03265  | 0.994867 | 19.0362   |  11.7825 | 18.9107 | 0.108016 | 17.7848   | 0.0326471 | 0.00513313 |    0.222845 |   0.734639  |  0.138752 |
| Qle    | baseline     | 16.6057  |  -7.37061  | 0.668499 | 0.650248 | 12.1501   |  22.7052 | 25.7898 | 0.759941 |  7.37061  | 0.331501  | 0.349752   |    0.547106 |   0.128331  |  0.382799 |
| Qle    | detailed     | 16.6991  |  -7.83193  | 0.663916 | 0.655208 | 12.1347   |  22.2116 | 25.7878 | 0.755499 |  7.83193  | 0.336084  | 0.344792   |    0.476374 |   0.0785276 |  0.403236 |
| Qh     | baseline     | 70.8445  |  69.6962   | 1.37304  | 0.871684 | 43.7054   | 125.602  | 84.0811 | 0.701088 | 69.6962   | 0.373038  | 0.128316   |    0.214957 |   0.574691  |  0.547669 |
| Qh     | detailed     | 42.8514  |  40.4391   | 1.16903  | 0.894924 | 29.8634   |  64.671  | 53.5682 | 0.523684 | 40.4391   | 0.169027  | 0.105076   |    0.201573 |   0.556726  |  0.416363 |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![TERRA_4.11_PL-Lipowa_subset_SWup_v0-9.png](TERRA_4.11_PL-Lipowa_subset_SWup_v0-9.png)](TERRA_4.11_PL-Lipowa_subset_SWup_v0-9.png)

### out of range: baseline

 - TERRA_4.11 SWup min value of -0.0013 is less than expected 0.0 [W/m2]
 - TERRA_4.11 Albedo min value of -0.0753 is less than expected 0.0 [1]

### out of range: detailed

 - TERRA_4.11 SWup min value of -0.0012 is less than expected 0.0 [W/m2]
 - TERRA_4.11 Albedo min value of -0.0717 is less than expected 0.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

