# AU-Preston: ASLUMv3.1

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |      MAE |        MBE |      nSD |        R |       5th |      95th |     cRMSE |      AMBE |      1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|---------:|-----------:|---------:|---------:|----------:|----------:|----------:|----------:|-----------:|-----------:|------------:|------------:|----------:|
| SWup   | baseline     |  3.18308 |  -0.579975 | 0.978932 | 0.99554  |  0.208895 |  1.97738  | 0.0957956 |  0.579975 | 0.0210681  | 0.00446044 |  0.00331041 |  0.00906472 | 0.0611111 |
| SWup   | detailed     |  5.53579 |  -3.80738  | 0.991081 | 0.988663 |  0.136322 |  0.415354 | 0.150173  |  3.80738  | 0.00891871 | 0.0113373  |  0.255889   |  0.511981   | 0.0772645 |
| LWup   | baseline     |  9.40801 |  -3.18348  | 1.11629  | 0.973292 | 11.1848   |  8.23883  | 0.270461  |  3.18348  | 0.116287   | 0.0267076  |  0.0744355  |  0.285011   | 0.1153    |
| LWup   | detailed     |  7.17658 |  -3.59277  | 0.977457 | 0.979169 |  4.98818  |  5.84159  | 0.203056  |  3.59277  | 0.0225432  | 0.0208314  |  0.0941954  |  0.222896   | 0.0658647 |
| Qle    | baseline     | 25.639   |  -3.87873  | 0.901521 | 0.630058 | 12.0868   |  8.64183  | 0.822629  |  3.87873  | 0.0984791  | 0.369942   |  0.161666   |  0.381978   | 0.277749  |
| Qle    | detailed     | 27.2641  |   8.66475  | 1.12202  | 0.660351 | 12.1507   | 43.0206   | 0.881521  |  8.66475  | 0.122025   | 0.339649   |  0.0678815  |  0.468075   | 0.16687   |
| Qh     | baseline     | 23.5319  | -13.5878   | 0.752505 | 0.935658 |  6.8024   | 60.0018   | 0.397605  | 13.5878   | 0.247495   | 0.0643422  |  0.104451   |  0.258248   | 0.150275  |
| Qh     | detailed     | 21.9695  | -12.1149   | 0.919181 | 0.934107 |  9.95226  | 28.1431   | 0.357305  | 12.1149   | 0.0808189  | 0.0658928  |  0.100613   |  0.332412   | 0.0902418 |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="datasheet"></a>Datasheet
[![ASLUMv3.1_AU-Preston_Datasheet.png](ASLUMv3.1_AU-Preston_Datasheet.png)](ASLUMv3.1_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![ASLUMv3.1_AU-Preston_Distributions.png](ASLUMv3.1_AU-Preston_Distributions.png)](ASLUMv3.1_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![ASLUMv3.1_AU-Preston_closure_baseline.png](ASLUMv3.1_AU-Preston_closure_baseline.png)](ASLUMv3.1_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![ASLUMv3.1_AU-Preston_closure_detailed.png](ASLUMv3.1_AU-Preston_closure_detailed.png)](ASLUMv3.1_AU-Preston_closure_detailed.png)

### <a name="subset_lwup"></a>subset_LWup
[![ASLUMv3.1_AU-Preston_subset_LWup.png](ASLUMv3.1_AU-Preston_subset_LWup.png)](ASLUMv3.1_AU-Preston_subset_LWup.png)

### <a name="subset_qh"></a>subset_Qh
[![ASLUMv3.1_AU-Preston_subset_Qh.png](ASLUMv3.1_AU-Preston_subset_Qh.png)](ASLUMv3.1_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![ASLUMv3.1_AU-Preston_subset_Qle.png](ASLUMv3.1_AU-Preston_subset_Qle.png)](ASLUMv3.1_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![ASLUMv3.1_AU-Preston_subset_SWup.png](ASLUMv3.1_AU-Preston_subset_SWup.png)](ASLUMv3.1_AU-Preston_subset_SWup.png)

### out of range: baseline

 - ASLUMv3.1 EvapF max value of 142.1361 is greater than expected 1.0 [1]
 - ASLUMv3.1 EvapF min value of -100.1998 is less than expected 0.0 [1]

### out of range: detailed

 - ASLUMv3.1 ESoil max value of 0.0003 is greater than expected 0.0003 [kg/m2/s]
 - ASLUMv3.1 EvapF max value of 451.3790 is greater than expected 1.0 [1]
 - ASLUMv3.1 EvapF min value of -28.6821 is less than expected 0.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

