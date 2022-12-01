# AU-Preston: MUSE

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](MUSE_AU-Preston_baseline_attrs.md)
- [Detailed](MUSE_AU-Preston_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |       MBE |        nSD |          R |     5th |      95th |      RMSE |       cRMSE |      AMBE |       1-nSD |          1-R |   nSkewness |   nKurtosis |     Overlap |
|:-------|:-------------|----------:|----------:|-----------:|-----------:|--------:|----------:|----------:|------------:|----------:|------------:|-------------:|------------:|------------:|------------:|
| SWup   | baseline     |  16.5628  | -16.5626  |   0.692054 |   0.996063 |   1.043 |  44.553   |  22.1812  |   0.316669  |  16.5626  |   0.307946  |   0.00393656 |   0.0322017 |   0.0558936 |   0.106827  |
| SWup   | detailed     |   3.39367 |  -2.21592 |   0.979192 |   0.995826 |   0.825 |   2.321   |   4.85726 |   0.0927706 |   2.21592 |   0.0208084 |   0.00417355 |   0.0587267 |   0.100551  |   0.0797609 |
| LWup   | baseline     |  26.0909  | -24.6466  |   1.14086  |   0.972203 |  26.557 |   6.64799 |  27.4697  |   0.288561  |  24.6466  |   0.140864  |   0.0277968  |   0.282237  |   0.81193   |   0.350847  |
| LWup   | detailed     |  27.0428  | -26.2727  |   1.09512  |   0.975288 |  26.855 |  12.889   |  28.3175  |   0.251341  |  26.2727  |   0.0951218 |   0.0247115  |   0.246586  |   0.699244  |   0.357853  |
| Qle    | baseline     |  32.2848  | -26.9059  |   0.55011  |   0.640695 |   5.311 |  51.789   |  46.3737  |   0.773121  |  26.9059  |   0.44989   |   0.359305   |   0.183946  |   0.334829  |   0.55987   |
| Qle    | detailed     |  32.9729  | -28.0278  |   0.510772 |   0.636034 |   5.434 |  58.163   |  47.3731  |   0.781761  |  28.0278  |   0.489228  |   0.363966   |   0.181222  |   0.332819  |   0.570655  |
| Qh     | baseline     |  36.6906  |  27.5459  |   1.17837  |   0.904711 |  15.04  |  71.583   |  53.9561  |   0.506349  |  27.5459  |   0.178375  |   0.0952887  |   0.0654545 |   0.102888  |   0.316865  |
| Qh     | detailed     |  34.1776  |  23.6639  |   1.121    |   0.904564 |  14.179 |  55.346   |  49.7922  |   0.478133  |  23.6639  |   0.121005  |   0.0954364  |   0.0612643 |   0.103732  |   0.30651   |
| Qtau   | baseline     | nan       | nan       | nan        | nan        | nan     | nan       | nan       | nan         | nan       | nan         | nan          | nan         | nan         | nan         |
| Qtau   | detailed     | nan       | nan       | nan        | nan        | nan     | nan       | nan       | nan         | nan       | nan         | nan          | nan         | nan         | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="albedo"></a>Albedo
[![MUSE_AU-Preston_Albedo.png](MUSE_AU-Preston_Albedo.png)](MUSE_AU-Preston_Albedo.png)

### <a name="datasheet"></a>Datasheet
[![MUSE_AU-Preston_Datasheet.png](MUSE_AU-Preston_Datasheet.png)](MUSE_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![MUSE_AU-Preston_Distributions.png](MUSE_AU-Preston_Distributions.png)](MUSE_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![MUSE_AU-Preston_closure_baseline.png](MUSE_AU-Preston_closure_baseline.png)](MUSE_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![MUSE_AU-Preston_closure_detailed.png](MUSE_AU-Preston_closure_detailed.png)](MUSE_AU-Preston_closure_detailed.png)

### <a name="subset_qh"></a>subset_Qh
[![MUSE_AU-Preston_subset_Qh.png](MUSE_AU-Preston_subset_Qh.png)](MUSE_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![MUSE_AU-Preston_subset_Qle.png](MUSE_AU-Preston_subset_Qle.png)](MUSE_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![MUSE_AU-Preston_subset_SWup.png](MUSE_AU-Preston_subset_SWup.png)](MUSE_AU-Preston_subset_SWup.png)

### out of range: baseline

 - MUSE Qh max value of 655.5630 is greater than expected 600.0 [W/m2]

### out of range: detailed

 - MUSE Qh max value of 633.2700 is greater than expected 600.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

