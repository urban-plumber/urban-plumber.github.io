# AU-Preston: TEB-CNRM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](TEB-CNRM_AU-Preston_baseline_attrs.md)
- [Detailed](TEB-CNRM_AU-Preston_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |        MBE |      nSD |        R |        5th |       95th |      RMSE |    cRMSE |      AMBE |      1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|----------:|-----------:|---------:|---------:|-----------:|-----------:|----------:|---------:|----------:|-----------:|-----------:|------------:|------------:|----------:|
| SWup   | G11          | 12.32     |  10.6299   | 1.20535  | 0.981226 |  0.28926   |  30.9519   | 17.3936   | 0.295681 | 10.6299   | 0.205349   | 0.0187741  |  0.0511411  |  0.11624    | 0.0811133 |
| SWup   | baseline     |  7.61786  |  -7.34187  | 0.866849 | 0.993575 |  0.434164  |  19.1076   | 10.7968   | 0.169908 |  7.34187  | 0.133151   | 0.00642529 |  0.00520456 |  0.0235549  | 0.0670989 |
| SWup   | detailed     |  9.78555  |  -9.65727  | 0.822659 | 0.993545 |  0.504691  |  25.5718   | 13.5863   | 0.20511  |  9.65727  | 0.177342   | 0.00645478 |  0.00288739 |  0.00937903 | 0.0714143 |
| LWup   | G11          | 13.0317   | -12.7156   | 0.985393 | 0.979585 | 12.2451    |  12.5121   | 15.2668   | 0.201116 | 12.7156   | 0.0146071  | 0.0204154  |  0.0566073  |  0.203805   | 0.155712  |
| LWup   | baseline     | 17.1102   |   9.57859  | 1.43652  | 0.966918 |  9.55957   |  54.7517   | 24.4199   | 0.534415 |  9.57859  | 0.436523   | 0.0330823  |  0.119639   |  0.119315   | 0.120053  |
| LWup   | detailed     | 11.3843   |   0.997343 | 1.2238   | 0.973059 | 11.2163    |  24.0866   | 14.352    | 0.340624 |  0.997343 | 0.223795   | 0.026941   |  0.0462771  |  0.0653452  | 0.103949  |
| Qle    | G11          | 30.5454   | -10.6548   | 0.897754 | 0.391461 |  7.93016   |  21.3647   | 52.4184   | 1.05028  | 10.6548   | 0.102246   | 0.608539   |  0.99067    |  1.55691    | 0.277092  |
| Qle    | baseline     | 25.036    |  -4.46301  | 0.785397 | 0.527937 | 12.1552    |  25.4077   | 43.5848   | 0.88745  |  4.46301  | 0.214603   | 0.472063   |  0.600237   |  0.903997   | 0.212549  |
| Qle    | detailed     | 21.6531   |   5.17833  | 0.999111 | 0.711122 | 11.3514    |  11.9018   | 37.4772   | 0.759765 |  5.17833  | 0.00088943 | 0.288878   |  0.0251381  |  0.41236    | 0.218576  |
| Qh     | G11          | 41.4137   |   1.16495  | 1.53411  | 0.902389 | 34.5894    | 137.294    | 70.0989   | 0.7647   |  1.16495  | 0.534109   | 0.0976115  |  0.154449   |  0.303505   | 0.265724  |
| Qh     | baseline     | 32.7894   |  26.0066   | 1.32669  | 0.944347 | 12.4762    | 110.19     | 53.0293   | 0.504378 | 26.0066   | 0.326691   | 0.0556535  |  0.0608704  |  0.0406089  | 0.213022  |
| Qh     | detailed     | 24.3025   |  17.0925   | 1.23624  | 0.950928 |  9.22379   |  76.3181   | 42.1819   | 0.42088  | 17.0925   | 0.236243   | 0.0490717  |  0.0810515  |  0.101705   | 0.124719  |
| Qtau   | G11          |  0.27203  |   0.254612 | 1.81962  | 0.869185 |  0.0138    |   0.76335  |  0.418578 | 1.07137  |  0.254612 | 0.819619   | 0.130815   |  0.166783   |  0.36255    | 0.211922  |
| Qtau   | baseline     |  0.300734 |   0.284642 | 1.65864  | 0.868147 |  0.0361937 |   0.676503 |  0.405707 | 0.933382 |  0.284642 | 0.658641   | 0.131853   |  0.181138   |  0.300207   | 0.297841  |
| Qtau   | detailed     |  0.530547 |   0.522259 | 2.38824  | 0.870133 |  0.0289369 |   1.35999  |  0.719128 | 1.59609  |  0.522259 | 1.38824    | 0.129867   |  0.209319   |  0.345214   | 0.403128  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="albedo"></a>Albedo
[![TEB-CNRM_AU-Preston_Albedo.png](TEB-CNRM_AU-Preston_Albedo.png)](TEB-CNRM_AU-Preston_Albedo.png)

### <a name="datasheet"></a>Datasheet
[![TEB-CNRM_AU-Preston_Datasheet.png](TEB-CNRM_AU-Preston_Datasheet.png)](TEB-CNRM_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![TEB-CNRM_AU-Preston_Distributions.png](TEB-CNRM_AU-Preston_Distributions.png)](TEB-CNRM_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![TEB-CNRM_AU-Preston_closure_baseline.png](TEB-CNRM_AU-Preston_closure_baseline.png)](TEB-CNRM_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![TEB-CNRM_AU-Preston_closure_detailed.png](TEB-CNRM_AU-Preston_closure_detailed.png)](TEB-CNRM_AU-Preston_closure_detailed.png)

### <a name="subset_qh"></a>subset_Qh
[![TEB-CNRM_AU-Preston_subset_Qh.png](TEB-CNRM_AU-Preston_subset_Qh.png)](TEB-CNRM_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![TEB-CNRM_AU-Preston_subset_Qle.png](TEB-CNRM_AU-Preston_subset_Qle.png)](TEB-CNRM_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![TEB-CNRM_AU-Preston_subset_SWup.png](TEB-CNRM_AU-Preston_subset_SWup.png)](TEB-CNRM_AU-Preston_subset_SWup.png)

### out of range: baseline


### out of range: detailed



[Link to variable definitions](../modelattrs/variable_definitions.md)

