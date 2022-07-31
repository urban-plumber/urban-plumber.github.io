# AU-Preston: CABLE

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |      MAE |      MBE |        nSD |          R |        5th |     95th |     RMSE |      cRMSE |     AMBE |        1-nSD |          1-R |    nSkewness |   nKurtosis |     Overlap |
|:-------|:-------------|---------:|---------:|-----------:|-----------:|-----------:|---------:|---------:|-----------:|---------:|-------------:|-------------:|-------------:|------------:|------------:|
| SWup   | baseline     |  11.3152 | -11.3082 |   0.804421 |   0.994019 |   0.781812 |  29.2682 |  15.2243 |   0.218802 |  11.3082 |   0.195579   |   0.00598135 |   0.00628067 |   0.0638854 |   0.0809262 |
| LWup   | baseline     |  16.3636 |  13.8349 |   1.51044  |   0.958747 |   1.09088  |  71.608  |  29.5159 |   0.620619 |  13.8349 |   0.510437   |   0.0412533  |   0.395108   |   1.07139   |   0.0687868 |
| Qle    | baseline     |  38.3701 |  16.7921 |   1.52181  |   0.536006 |   8.43043  |  84.9323 |  69.6428 |   1.29788  |  16.7921 |   0.521807   |   0.463994   |   0.446612   |   0.261562  |   0.110008  |
| Qh     | baseline     |  27.8381 | -12.2579 |   0.996216 |   0.893699 |   2.89494  |  19.6525 |  44.0767 |   0.460231 |  12.2579 |   0.00378428 |   0.106301   |   0.268507   |   0.823843  |   0.215725  |
| Qtau   | baseline     | nan      | nan      | nan        | nan        | nan        | nan      | nan      | nan        | nan      | nan          | nan          | nan          | nan         | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="datasheet"></a>Datasheet
[![CABLE_AU-Preston_Datasheet.png](CABLE_AU-Preston_Datasheet.png)](CABLE_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![CABLE_AU-Preston_Distributions.png](CABLE_AU-Preston_Distributions.png)](CABLE_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![CABLE_AU-Preston_closure_baseline.png](CABLE_AU-Preston_closure_baseline.png)](CABLE_AU-Preston_closure_baseline.png)

### <a name="subset_lwup"></a>subset_LWup
[![CABLE_AU-Preston_subset_LWup.png](CABLE_AU-Preston_subset_LWup.png)](CABLE_AU-Preston_subset_LWup.png)

### <a name="subset_qh"></a>subset_Qh
[![CABLE_AU-Preston_subset_Qh.png](CABLE_AU-Preston_subset_Qh.png)](CABLE_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![CABLE_AU-Preston_subset_Qle.png](CABLE_AU-Preston_subset_Qle.png)](CABLE_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![CABLE_AU-Preston_subset_SWup.png](CABLE_AU-Preston_subset_SWup.png)](CABLE_AU-Preston_subset_SWup.png)

### out of range: baseline

 - CABLE Qle max value of 758.7974 is greater than expected 700.0 [W/m2]
 - CABLE Evap max value of 0.0003 is greater than expected 0.0003 [kg/m2/s]
 - CABLE EvapF max value of 55.4464 is greater than expected 1.0 [1]
 - CABLE EvapF min value of -15.6806 is less than expected 0.0 [1]

### out of range: detailed



[Link to variable definitions](../modelattrs/variable_definitions.md)

