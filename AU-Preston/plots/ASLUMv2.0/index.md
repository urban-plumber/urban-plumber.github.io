# AU-Preston: ASLUMv2.0

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |      MAE |       MBE |      nSD |        R |       5th |     95th |     RMSE |     cRMSE |      AMBE |    1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|---------:|----------:|---------:|---------:|----------:|---------:|---------:|----------:|----------:|---------:|-----------:|------------:|------------:|----------:|
| SWup   | baseline     |  7.05582 |  6.4498   | 1.14594  | 0.996713 |  0.421111 | 22.3134  | 10.2064  | 0.169794  |  6.4498   | 0.145936 | 0.00328669 |   0.0560888 |   0.119031  | 0.0919685 |
| SWup   | detailed     |  2.90146 | -1.00607  | 1.01793  | 0.996479 |  0.630692 |  3.52479 |  4.15542 | 0.0865436 |  1.00607  | 0.017926 | 0.0035211  |   0.0842531 |   0.169768  | 0.0617042 |
| LWup   | baseline     | 10.3597  |  0.269825 | 1.16674  | 0.969018 |  9.45366  | 18.0985  | 13.2942  | 0.316383  |  0.269825 | 0.166744 | 0.0309815  |   0.0406869 |   0.227007  | 0.0991241 |
| LWup   | detailed     |  7.69127 | -1.71425  | 1.0592   | 0.975802 |  6.94748  |  3.70926 |  9.97973 | 0.234021  |  1.71425  | 0.059201 | 0.0241981  |   0.0783617 |   0.195681  | 0.0738271 |
| Qle    | baseline     | 24.5448  |  1.13798  | 0.950109 | 0.658375 | 12.1127   | 18.9311  | 42.0534  | 0.807249  |  1.13798  | 0.049891 | 0.341625   |   0.120173  |   0.405253  | 0.208841  |
| Qle    | detailed     | 27.6579  | 11.6081   | 1.16027  | 0.670964 | 12.1128   | 53.799   | 47.6973  | 0.888385  | 11.6081   | 0.160272 | 0.329036   |   0.106965  |   0.39624   | 0.108065  |
| Qh     | baseline     | 20.3974  | -6.70737  | 0.849681 | 0.937881 |  8.36336  | 36.742   | 33.6089  | 0.357993  |  6.70737  | 0.150319 | 0.0621194  |   0.0455324 |   0.0326986 | 0.140277  |
| Qh     | detailed     | 22.086   |  1.23604  | 1.10232  | 0.921621 |  7.12343  | 19.5239  | 39.401   | 0.428095  |  1.23604  | 0.102318 | 0.0783787  |   0.0392116 |   0.150945  | 0.127273  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="datasheet"></a>Datasheet
[![ASLUMv2.0_AU-Preston_Datasheet.png](ASLUMv2.0_AU-Preston_Datasheet.png)](ASLUMv2.0_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![ASLUMv2.0_AU-Preston_Distributions.png](ASLUMv2.0_AU-Preston_Distributions.png)](ASLUMv2.0_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![ASLUMv2.0_AU-Preston_closure_baseline.png](ASLUMv2.0_AU-Preston_closure_baseline.png)](ASLUMv2.0_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![ASLUMv2.0_AU-Preston_closure_detailed.png](ASLUMv2.0_AU-Preston_closure_detailed.png)](ASLUMv2.0_AU-Preston_closure_detailed.png)

### <a name="subset_lwup"></a>subset_LWup
[![ASLUMv2.0_AU-Preston_subset_LWup.png](ASLUMv2.0_AU-Preston_subset_LWup.png)](ASLUMv2.0_AU-Preston_subset_LWup.png)

### <a name="subset_qh"></a>subset_Qh
[![ASLUMv2.0_AU-Preston_subset_Qh.png](ASLUMv2.0_AU-Preston_subset_Qh.png)](ASLUMv2.0_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![ASLUMv2.0_AU-Preston_subset_Qle.png](ASLUMv2.0_AU-Preston_subset_Qle.png)](ASLUMv2.0_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![ASLUMv2.0_AU-Preston_subset_SWup.png](ASLUMv2.0_AU-Preston_subset_SWup.png)](ASLUMv2.0_AU-Preston_subset_SWup.png)

### out of range: baseline

 - ASLUMv2.0 EvapF max value of 608.3092 is greater than expected 1.0 [1]
 - ASLUMv2.0 EvapF min value of -43.4497 is less than expected 0.0 [1]

### out of range: detailed

 - ASLUMv2.0 Qh max value of 744.3455 is greater than expected 600.0 [W/m2]
 - ASLUMv2.0 ESoil max value of 0.0003 is greater than expected 0.0003 [kg/m2/s]
 - ASLUMv2.0 EvapF max value of 186.2600 is greater than expected 1.0 [1]
 - ASLUMv2.0 EvapF min value of -120.0947 is less than expected 0.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

