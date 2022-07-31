# AU-Preston: CHTESSEL_U

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |      MAE |        MBE |      nSD |        R |       5th |      95th |     RMSE |     cRMSE |      AMBE |      1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|---------:|-----------:|---------:|---------:|----------:|----------:|---------:|----------:|----------:|-----------:|-----------:|------------:|------------:|----------:|
| SWup   | baseline     |  2.90633 |  0.294026  | 1.01222  | 0.996374 |  0.389248 |   2.77522 |  4.04239 | 0.0865412 | 0.294026  | 0.0122165  | 0.00362577 |   0.0314551 |   0.0792735 | 0.0598721 |
| SWup   | detailed     |  2.86692 |  0.0784058 | 1.0122   | 0.996449 |  0.404486 |   2.62971 |  3.99149 | 0.0856619 | 0.0784058 | 0.0122022  | 0.0035512  |   0.0390519 |   0.0844602 | 0.0580438 |
| LWup   | baseline     | 10.102   |  0.920756  | 1.17621  | 0.970426 |  8.5103   |  18.2723  | 13.3578  | 0.317206  | 0.920756  | 0.176211   | 0.0295735  |   0.0289826 |   0.050621  | 0.0832373 |
| LWup   | detailed     |  8.80537 | -2.28732   | 1.08176  | 0.969617 |  9.35015  |   5.04826 | 11.5344  | 0.269106  | 2.28732   | 0.0817613  | 0.0303825  |   0.0393912 |   0.0469117 | 0.0759075 |
| Qle    | baseline     | 30.0436  |  2.54493   | 0.997103 | 0.521961 |  9.49197  |   7.32897 | 50.9092  | 0.976379  | 2.54493   | 0.00289726 | 0.478039   |   0.217216  |   0.0864206 | 0.142226  |
| Qle    | detailed     | 30.4101  |  3.84314   | 0.980954 | 0.519934 |  8.86399  |   4.28762 | 50.6943  | 0.970675  | 3.84314   | 0.0190455  | 0.480066   |   0.164354  |   0.122573  | 0.111758  |
| Qh     | baseline     | 30.2145  |  5.99427   | 1.3363   | 0.928643 | 16.023    |  89.2008  | 51.0582  | 0.551186  | 5.99427   | 0.3363     | 0.0713567  |   0.113249  |   0.206649  | 0.170233  |
| Qh     | detailed     | 37.0835  |  7.05139   | 1.47534  | 0.928183 | 29.8102   | 125.627   | 61.2797  | 0.661711  | 7.05139   | 0.475343   | 0.0718174  |   0.0766672 |   0.110751  | 0.22729   |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="datasheet"></a>Datasheet
[![CHTESSEL_U_AU-Preston_Datasheet.png](CHTESSEL_U_AU-Preston_Datasheet.png)](CHTESSEL_U_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![CHTESSEL_U_AU-Preston_Distributions.png](CHTESSEL_U_AU-Preston_Distributions.png)](CHTESSEL_U_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![CHTESSEL_U_AU-Preston_closure_baseline.png](CHTESSEL_U_AU-Preston_closure_baseline.png)](CHTESSEL_U_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![CHTESSEL_U_AU-Preston_closure_detailed.png](CHTESSEL_U_AU-Preston_closure_detailed.png)](CHTESSEL_U_AU-Preston_closure_detailed.png)

### <a name="subset_lwup"></a>subset_LWup
[![CHTESSEL_U_AU-Preston_subset_LWup.png](CHTESSEL_U_AU-Preston_subset_LWup.png)](CHTESSEL_U_AU-Preston_subset_LWup.png)

### <a name="subset_qh"></a>subset_Qh
[![CHTESSEL_U_AU-Preston_subset_Qh.png](CHTESSEL_U_AU-Preston_subset_Qh.png)](CHTESSEL_U_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![CHTESSEL_U_AU-Preston_subset_Qle.png](CHTESSEL_U_AU-Preston_subset_Qle.png)](CHTESSEL_U_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![CHTESSEL_U_AU-Preston_subset_SWup.png](CHTESSEL_U_AU-Preston_subset_SWup.png)](CHTESSEL_U_AU-Preston_subset_SWup.png)

### out of range: baseline

 - CHTESSEL_U Qh max value of 641.0618 is greater than expected 600.0 [W/m2]
 - CHTESSEL_U EvapF max value of 47.5853 is greater than expected 1.0 [1]
 - CHTESSEL_U EvapF min value of -44.8806 is less than expected 0.0 [1]

### out of range: detailed

 - CHTESSEL_U Qh max value of 690.3634 is greater than expected 600.0 [W/m2]
 - CHTESSEL_U EvapF max value of 32.3510 is greater than expected 1.0 [1]
 - CHTESSEL_U EvapF min value of -23.6449 is less than expected 0.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

