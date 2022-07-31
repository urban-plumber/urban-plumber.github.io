# AU-Preston: CHTESSEL

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](CHTESSEL_AU-Preston_baseline_attrs.md)
- [Detailed](CHTESSEL_AU-Preston_detailed_attrs.md)

### Error metrics

| flux   | experiment   |      MAE |      MBE |     nSD |        R |       5th |     95th |    RMSE |    cRMSE |     AMBE |     1-nSD |       1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|---------:|---------:|--------:|---------:|----------:|---------:|--------:|---------:|---------:|----------:|----------:|------------:|------------:|----------:|
| SWup   | baseline     |  4.19506 |  2.37588 | 1.08023 | 0.995652 |  0.508689 | 12.0247  |  6.3249 | 0.125823 |  2.37588 | 0.0802314 | 0.0043483 |   0.083625  |   0.145596  | 0.0718643 |
| LWup   | baseline     |  8.77247 | -2.10889 | 1.01314 | 0.965061 |  5.60885  |  0.33476 | 11.3886 | 0.266401 |  2.10889 | 0.013138  | 0.0349395 |   0.0537722 |   0.0857844 | 0.0576653 |
| Qle    | baseline     | 33.293   | 18.2242  | 1.42315 | 0.66611  | 10.1265   | 74.6359  | 58.2659 | 1.06273  | 18.2242  | 0.423149  | 0.33389   |   0.150006  |   0.261561  | 0.159918  |
| Qh     | baseline     | 28.9959  | -8.20893 | 1.13791 | 0.906494 | 23.8725   | 21.5282  | 45.0467 | 0.481478 |  8.20893 | 0.137906  | 0.0935062 |   0.102876  |   0.313304  | 0.174927  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="datasheet"></a>Datasheet
[![CHTESSEL_AU-Preston_Datasheet.png](CHTESSEL_AU-Preston_Datasheet.png)](CHTESSEL_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![CHTESSEL_AU-Preston_Distributions.png](CHTESSEL_AU-Preston_Distributions.png)](CHTESSEL_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![CHTESSEL_AU-Preston_closure_baseline.png](CHTESSEL_AU-Preston_closure_baseline.png)](CHTESSEL_AU-Preston_closure_baseline.png)

### <a name="subset_lwup"></a>subset_LWup
[![CHTESSEL_AU-Preston_subset_LWup.png](CHTESSEL_AU-Preston_subset_LWup.png)](CHTESSEL_AU-Preston_subset_LWup.png)

### <a name="subset_qh"></a>subset_Qh
[![CHTESSEL_AU-Preston_subset_Qh.png](CHTESSEL_AU-Preston_subset_Qh.png)](CHTESSEL_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![CHTESSEL_AU-Preston_subset_Qle.png](CHTESSEL_AU-Preston_subset_Qle.png)](CHTESSEL_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![CHTESSEL_AU-Preston_subset_SWup.png](CHTESSEL_AU-Preston_subset_SWup.png)](CHTESSEL_AU-Preston_subset_SWup.png)

### out of range: baseline

 - CHTESSEL EvapF max value of 29.0024 is greater than expected 1.0 [1]
 - CHTESSEL EvapF min value of -77.1617 is less than expected 0.0 [1]

### out of range: detailed



[Link to variable definitions](../modelattrs/variable_definitions.md)

