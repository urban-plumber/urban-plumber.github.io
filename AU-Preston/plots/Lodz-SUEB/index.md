# AU-Preston: Lodz-SUEB

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |       MAE |         MBE |      nSD |        R |         5th |      95th |      RMSE |     cRMSE |        AMBE |      1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|----------:|------------:|---------:|---------:|------------:|----------:|----------:|----------:|------------:|-----------:|-----------:|------------:|------------:|----------:|
| SWup   | baseline     |  2.71585  | -0.254132   | 1.00802  | 0.996707 |  0.528      |  1.398    |  3.82254  | 0.0818704 |  0.254132   | 0.00801835 | 0.00329283 |   0.0118061 |   0.0199243 | 0.0586148 |
| SWup   | detailed     |  2.71585  | -0.254132   | 1.00802  | 0.996707 |  0.528      |  1.398    |  3.82254  | 0.0818704 |  0.254132   | 0.00801835 | 0.00329283 |   0.0118061 |   0.0199243 | 0.0586148 |
| LWup   | baseline     | 15.0221   | 11.6384     | 1.36237  | 0.9712   |  4.4622     | 50.3467   | 22.4878   | 0.458023  | 11.6384     | 0.36237    | 0.0288004  |   0.0892634 |   0.0573558 | 0.10386   |
| LWup   | detailed     | 14.3957   | 10.7597     | 1.34259  | 0.971823 |  4.7411     | 46.8005   | 21.3645   | 0.439347  | 10.7597     | 0.342588   | 0.0281765  |   0.0846766 |   0.0689091 | 0.10331   |
| Qle    | baseline     | 24.5891   | -7.85056    | 0.789783 | 0.641108 | 12.1307     | 12.8782   | 41.4586   | 0.781719  |  7.85056    | 0.210217   | 0.358892   |   0.0950399 |   0.319148  | 0.392825  |
| Qle    | detailed     | 24.6072   | -7.99037    | 0.787289 | 0.639983 | 12.1299     | 14.2131   | 41.5191   | 0.782382  |  7.99037    | 0.212711   | 0.360017   |   0.107207  |   0.291607  | 0.393368  |
| Qh     | baseline     | 19.9421   |  5.1439     | 0.926005 | 0.941092 | 13.9533     |  7.2846   | 31.5604   | 0.338488  |  5.1439     | 0.0739955  | 0.0589082  |   0.0397639 |   0.189425  | 0.0975749 |
| Qh     | detailed     | 20.0195   |  6.13919    | 0.956348 | 0.939999 | 13.2205     |  0.0886   | 32.0161   | 0.34157   |  6.13919    | 0.043652   | 0.0600015  |   0.0204766 |   0.14381   | 0.0901858 |
| Qtau   | baseline     |  0.102855 |  0.00709458 | 0.852369 | 0.877569 |  0.00185029 |  0.125799 |  0.157691 | 0.480113  |  0.00709458 | 0.147631   | 0.122431   |   0.173824  |   0.251089  | 0.104748  |
| Qtau   | detailed     |  0.102062 | -0.0252503  | 0.762792 | 0.876419 |  7.386e-05  |  0.215491 |  0.164294 | 0.494774  |  0.0252503  | 0.237208   | 0.123581   |   0.176927  |   0.262434  | 0.0995226 |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="datasheet"></a>Datasheet
[![Lodz-SUEB_AU-Preston_Datasheet.png](Lodz-SUEB_AU-Preston_Datasheet.png)](Lodz-SUEB_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![Lodz-SUEB_AU-Preston_Distributions.png](Lodz-SUEB_AU-Preston_Distributions.png)](Lodz-SUEB_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![Lodz-SUEB_AU-Preston_closure_baseline.png](Lodz-SUEB_AU-Preston_closure_baseline.png)](Lodz-SUEB_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![Lodz-SUEB_AU-Preston_closure_detailed.png](Lodz-SUEB_AU-Preston_closure_detailed.png)](Lodz-SUEB_AU-Preston_closure_detailed.png)

### <a name="subset_lwup"></a>subset_LWup
[![Lodz-SUEB_AU-Preston_subset_LWup.png](Lodz-SUEB_AU-Preston_subset_LWup.png)](Lodz-SUEB_AU-Preston_subset_LWup.png)

### <a name="subset_qh"></a>subset_Qh
[![Lodz-SUEB_AU-Preston_subset_Qh.png](Lodz-SUEB_AU-Preston_subset_Qh.png)](Lodz-SUEB_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![Lodz-SUEB_AU-Preston_subset_Qle.png](Lodz-SUEB_AU-Preston_subset_Qle.png)](Lodz-SUEB_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![Lodz-SUEB_AU-Preston_subset_SWup.png](Lodz-SUEB_AU-Preston_subset_SWup.png)](Lodz-SUEB_AU-Preston_subset_SWup.png)

### out of range: baseline

 - Lodz-SUEB EvapF max value of 8.2131 is greater than expected 1.0 [1]
 - Lodz-SUEB EvapF min value of -203.4503 is less than expected 0.0 [1]

### out of range: detailed

 - Lodz-SUEB EvapF max value of 10.6208 is greater than expected 1.0 [1]
 - Lodz-SUEB EvapF min value of -29.1315 is less than expected 0.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

