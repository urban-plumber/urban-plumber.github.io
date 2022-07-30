# AU-Preston: TEB-SPARTCS

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |       MAE |       MBE |      nSD |        R |         5th |      95th |    cRMSE |      AMBE |     1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|----------:|----------:|---------:|---------:|------------:|----------:|---------:|----------:|----------:|-----------:|------------:|------------:|----------:|
| SWup   | baseline     |  7.68716  | -7.56268  | 0.872627 | 0.995301 |  1.25741    | 18.5728   | 0.156286 |  7.56268  | 0.127373  | 0.00469936 |  0.00532616 |   0.0290317 | 0.0840195 |
| SWup   | detailed     |  9.70399  | -9.62802  | 0.821326 | 0.995064 |  1.26107    | 26.3642   | 0.200082 |  9.62802  | 0.178674  | 0.00493616 |  0.051441   |   0.0745019 | 0.0850449 |
| LWup   | baseline     | 17.3756   | 11.2064   | 1.44264  | 0.967812 |  7.49419    | 57.2659   | 0.5374   | 11.2064   | 0.442637  | 0.0321878  |  0.12411    |   0.113115  | 0.115151  |
| LWup   | detailed     | 12.7531   |  7.8255   | 1.30198  | 0.97587  |  4.5332     | 40.0949   | 0.392463 |  7.8255   | 0.301982  | 0.0241301  |  0.15353    |   0.287135  | 0.0894369 |
| Qle    | baseline     | 27.6845   | -5.33713  | 0.739879 | 0.470614 | 13.85       | 29.8393   | 0.922511 |  5.33713  | 0.260121  | 0.529386   |  0.597269   |   0.783722  | 0.269984  |
| Qle    | detailed     | 30.8871   |  7.10935  | 1.07264  | 0.527572 | 12.9227     | 25.4523   | 1.00934  |  7.10935  | 0.0726442 | 0.472428   |  0.212489   |   0.165849  | 0.171838  |
| Qh     | baseline     | 33.4711   | 25.5433   | 1.24836  | 0.93479  | 14.2156     | 90.8817   | 0.473806 | 25.5433   | 0.248357  | 0.0652102  |  0.069155   |   0.0874429 | 0.242117  |
| Qh     | detailed     | 27.439    |  9.72635  | 1.24239  | 0.920477 |  0.181143   | 68.4932   | 0.506309 |  9.72635  | 0.242387  | 0.0795233  |  0.187537   |   0.457569  | 0.0628576 |
| Qtau   | baseline     |  0.21249  |  0.187489 | 1.31975  | 0.873902 |  0.033933   |  0.363041 | 0.659604 |  0.187489 | 0.319751  | 0.126098   |  0.126224   |   0.137959  | 0.23962   |
| Qtau   | detailed     |  0.207402 |  0.180694 | 1.40922  | 0.872065 |  0.00307257 |  0.419852 | 0.726666 |  0.180694 | 0.409224  | 0.127935   |  0.160073   |   0.221434  | 0.201558  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="datasheet"></a>Datasheet
[![TEB-SPARTCS_AU-Preston_Datasheet.png](TEB-SPARTCS_AU-Preston_Datasheet.png)](TEB-SPARTCS_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![TEB-SPARTCS_AU-Preston_Distributions.png](TEB-SPARTCS_AU-Preston_Distributions.png)](TEB-SPARTCS_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![TEB-SPARTCS_AU-Preston_closure_baseline.png](TEB-SPARTCS_AU-Preston_closure_baseline.png)](TEB-SPARTCS_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![TEB-SPARTCS_AU-Preston_closure_detailed.png](TEB-SPARTCS_AU-Preston_closure_detailed.png)](TEB-SPARTCS_AU-Preston_closure_detailed.png)

### <a name="subset_lwup"></a>subset_LWup
[![TEB-SPARTCS_AU-Preston_subset_LWup.png](TEB-SPARTCS_AU-Preston_subset_LWup.png)](TEB-SPARTCS_AU-Preston_subset_LWup.png)

### <a name="subset_qh"></a>subset_Qh
[![TEB-SPARTCS_AU-Preston_subset_Qh.png](TEB-SPARTCS_AU-Preston_subset_Qh.png)](TEB-SPARTCS_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![TEB-SPARTCS_AU-Preston_subset_Qle.png](TEB-SPARTCS_AU-Preston_subset_Qle.png)](TEB-SPARTCS_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![TEB-SPARTCS_AU-Preston_subset_SWup.png](TEB-SPARTCS_AU-Preston_subset_SWup.png)](TEB-SPARTCS_AU-Preston_subset_SWup.png)

### out of range: baseline

 - TEB-SPARTCS TVeg max value of 0.0004 is greater than expected 0.0003 [kg/m2/s]
 - TEB-SPARTCS EvapF max value of 32.2770 is greater than expected 1.0 [1]
 - TEB-SPARTCS EvapF min value of -7.1219 is less than expected 0.0 [1]

### out of range: detailed

 - TEB-SPARTCS Qh max value of 602.5126 is greater than expected 600.0 [W/m2]
 - TEB-SPARTCS TVeg max value of 0.0004 is greater than expected 0.0003 [kg/m2/s]
 - TEB-SPARTCS EvapF max value of 13.3841 is greater than expected 1.0 [1]
 - TEB-SPARTCS EvapF min value of -8.7738 is less than expected 0.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

