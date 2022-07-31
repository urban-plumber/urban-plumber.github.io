# AU-Preston: CLMU5

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](CLMU5_AU-Preston_baseline_attrs.md)
- [Detailed](CLMU5_AU-Preston_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |        MBE |      nSD |        R |         5th |      95th |      RMSE |     cRMSE |       AMBE |      1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|----------:|-----------:|---------:|---------:|------------:|----------:|----------:|----------:|-----------:|-----------:|-----------:|------------:|------------:|----------:|
| SWup   | baseline     |  2.99026  |  0.89095   | 1.00554  | 0.995959 |  0.470946   |  0.18087  |  4.30083  | 0.0903159 |  0.89095   | 0.00554264 | 0.00404072 |   0.0871605 |   0.189221  | 0.0685738 |
| SWup   | detailed     |  2.73361  | -0.188556  | 1.01284  | 0.996715 |  0.532768   |  2.2551   |  3.85181  | 0.082581  |  0.188556  | 0.0128369  | 0.00328525 |   0.0250366 |   0.0471835 | 0.0624285 |
| LWup   | baseline     | 12.172    | 10.008     | 1.19355  | 0.971512 |  5.3455     | 34.0293   | 16.9205   | 0.324751  | 10.008     | 0.193546   | 0.0284878  |   0.167571  |   0.192316  | 0.098693  |
| LWup   | detailed     | 12.7798   | 10.7358    | 1.22183  | 0.970171 |  4.53547    | 38.0317   | 18.187    | 0.349431  | 10.7358    | 0.221833   | 0.029829   |   0.161996  |   0.168077  | 0.096566  |
| Qle    | baseline     | 25.2527   | -4.76405   | 0.895137 | 0.656707 | 11.815      |  3.06915  | 41.4632   | 0.790939  |  4.76405   | 0.104863   | 0.343293   |   0.191735  |   0.294414  | 0.280862  |
| Qle    | detailed     | 25.0075   | -5.83928   | 0.858279 | 0.653812 | 11.3771     |  1.36574  | 41.2322   | 0.783796  |  5.83928   | 0.141721   | 0.346188   |   0.151742  |   0.356128  | 0.271583  |
| Qh     | baseline     | 23.9119   |  6.96758   | 1.09945  | 0.938956 |  4.723      | 27.9332   | 35.6116   | 0.379632  |  6.96758   | 0.0994501  | 0.0610441  |   0.12341   |   0.33988   | 0.125539  |
| Qh     | detailed     | 22.6609   |  6.61806   | 1.08155  | 0.941982 |  2.68792    | 24.153    | 34.09     | 0.363523  |  6.61806   | 0.0815462  | 0.0580184  |   0.111991  |   0.338938  | 0.121425  |
| Qtau   | baseline     |  0.151346 |  0.114448  | 1.14417  | 0.873595 |  0.0146169  |  0.168619 |  0.215587 | 0.556816  |  0.114448  | 0.144174   | 0.126405   |   0.154043  |   0.190802  | 0.174692  |
| Qtau   | detailed     |  0.105537 |  0.0070833 | 0.841356 | 0.873385 |  0.00899506 |  0.134658 |  0.160304 | 0.488082  |  0.0070833 | 0.158644   | 0.126615   |   0.162371  |   0.216998  | 0.107212  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="datasheet"></a>Datasheet
[![CLMU5_AU-Preston_Datasheet.png](CLMU5_AU-Preston_Datasheet.png)](CLMU5_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![CLMU5_AU-Preston_Distributions.png](CLMU5_AU-Preston_Distributions.png)](CLMU5_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![CLMU5_AU-Preston_closure_baseline.png](CLMU5_AU-Preston_closure_baseline.png)](CLMU5_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![CLMU5_AU-Preston_closure_detailed.png](CLMU5_AU-Preston_closure_detailed.png)](CLMU5_AU-Preston_closure_detailed.png)

### <a name="subset_lwup"></a>subset_LWup
[![CLMU5_AU-Preston_subset_LWup.png](CLMU5_AU-Preston_subset_LWup.png)](CLMU5_AU-Preston_subset_LWup.png)

### <a name="subset_qh"></a>subset_Qh
[![CLMU5_AU-Preston_subset_Qh.png](CLMU5_AU-Preston_subset_Qh.png)](CLMU5_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![CLMU5_AU-Preston_subset_Qle.png](CLMU5_AU-Preston_subset_Qle.png)](CLMU5_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![CLMU5_AU-Preston_subset_SWup.png](CLMU5_AU-Preston_subset_SWup.png)](CLMU5_AU-Preston_subset_SWup.png)

### out of range: baseline

 - CLMU5 EvapF max value of 103.7278 is greater than expected 1.0 [1]
 - CLMU5 EvapF min value of -119.8021 is less than expected 0.0 [1]

### out of range: detailed

 - CLMU5 EvapF max value of 17.3577 is greater than expected 1.0 [1]
 - CLMU5 EvapF min value of -33.9371 is less than expected 0.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

