# AU-Preston: UCLEM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](UCLEM_AU-Preston_baseline_attrs.md)
- [Detailed](UCLEM_AU-Preston_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |        MBE |      nSD |        R |     5th |    95th |      RMSE |    cRMSE |       AMBE |      1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|----------:|-----------:|---------:|---------:|--------:|--------:|----------:|---------:|-----------:|-----------:|-----------:|------------:|------------:|----------:|
| SWup   | baseline     |  3.96932  |  2.02687   | 1.03629  | 0.992971 |  0.5432 |  2.9017 |  6.21178  | 0.12604  |  2.02687   | 0.0362914  | 0.00702937 |   0.112526  |   0.292396  | 0.0654393 |
| SWup   | detailed     |  3.63623  |  0.0916978 | 1.00156  | 0.993798 |  0.571  |  1.6357 |  5.19399  | 0.111473 |  0.0916978 | 0.00156024 | 0.00620222 |   0.100621  |   0.259694  | 0.0697289 |
| LWup   | baseline     | 20.0328   | 19.9464    | 1.25236  | 0.979185 |  6.5396 | 44.4861 | 24.5412   | 0.340327 | 19.9464    | 0.252362   | 0.0208152  |   0.0667732 |   0.367433  | 0.162123  |
| LWup   | detailed     | 16.1092   | 15.9211    | 1.21102  | 0.983469 |  4.7407 | 36.6654 | 20.0683   | 0.290808 | 15.9211    | 0.211022   | 0.0165311  |   0.0536596 |   0.313962  | 0.136239  |
| Qle    | baseline     | 24.0636   | -8.43974   | 0.746087 | 0.656073 | 11.3822 | 19.5259 | 40.4697   | 0.760047 |  8.43974   | 0.253913   | 0.343927   |   0.223351  |   0.121807  | 0.268446  |
| Qle    | detailed     | 23.7249   | -6.37366   | 0.782409 | 0.662679 | 11.5046 | 12.7576 | 40.0059   | 0.758414 |  6.37366   | 0.217591   | 0.337321   |   0.106929  |   0.383817  | 0.257042  |
| Qh     | baseline     | 23.3093   |  5.0953    | 0.886571 | 0.921596 | 18.0855 | 19.372  | 36.2123   | 0.389727 |  5.0953    | 0.113429   | 0.0784037  |   0.0403961 |   0.0749721 | 0.170451  |
| Qh     | detailed     | 24.7948   |  9.68196   | 0.9451   | 0.921304 | 18.7824 |  1.0081 | 37.1225   | 0.389571 |  9.68196   | 0.0549002  | 0.0786961  |   0.0694068 |   0.135209  | 0.20366   |
| Qtau   | baseline     |  0.156543 |  0.120981  | 1.13677  | 0.868317 |  0.019  |  0.1746 |  0.221092 | 0.563996 |  0.120981  | 0.136769   | 0.131683   |   0.118994  |   0.0123116 | 0.194739  |
| Qtau   | detailed     |  0.1157   |  0.0471189 | 0.957159 | 0.869735 |  0.0065 |  0.019  |  0.171069 | 0.501203 |  0.0471189 | 0.0428411  | 0.130265   |   0.10657   |   0.0846321 | 0.13311   |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="datasheet"></a>Datasheet
[![UCLEM_AU-Preston_Datasheet.png](UCLEM_AU-Preston_Datasheet.png)](UCLEM_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![UCLEM_AU-Preston_Distributions.png](UCLEM_AU-Preston_Distributions.png)](UCLEM_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![UCLEM_AU-Preston_closure_baseline.png](UCLEM_AU-Preston_closure_baseline.png)](UCLEM_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![UCLEM_AU-Preston_closure_detailed.png](UCLEM_AU-Preston_closure_detailed.png)](UCLEM_AU-Preston_closure_detailed.png)

### <a name="subset_lwup"></a>subset_LWup
[![UCLEM_AU-Preston_subset_LWup.png](UCLEM_AU-Preston_subset_LWup.png)](UCLEM_AU-Preston_subset_LWup.png)

### <a name="subset_qh"></a>subset_Qh
[![UCLEM_AU-Preston_subset_Qh.png](UCLEM_AU-Preston_subset_Qh.png)](UCLEM_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![UCLEM_AU-Preston_subset_Qle.png](UCLEM_AU-Preston_subset_Qle.png)](UCLEM_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![UCLEM_AU-Preston_subset_SWup.png](UCLEM_AU-Preston_subset_SWup.png)](UCLEM_AU-Preston_subset_SWup.png)

### out of range: baseline

 - UCLEM EvapF max value of 53.5193 is greater than expected 1.0 [1]
 - UCLEM EvapF min value of -13.1833 is less than expected 0.0 [1]

### out of range: detailed

 - UCLEM EvapF max value of 16.1228 is greater than expected 1.0 [1]
 - UCLEM EvapF min value of -47.9918 is less than expected 0.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

