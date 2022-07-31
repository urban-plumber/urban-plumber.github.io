# AU-Preston: JULES_1T

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |       MAE |         MBE |      nSD |        R |         5th |      95th |      RMSE |    cRMSE |       AMBE |     1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|----------:|------------:|---------:|---------:|------------:|----------:|----------:|---------:|-----------:|----------:|-----------:|------------:|------------:|----------:|
| SWup   | baseline     | 12.7726   |  12.5085    | 1.24456  | 0.996707 |  0.250629   | 35.9891   | 17.4373   | 0.260782 | 12.5085    | 0.244562  | 0.00329283 |   0.011806  |   0.0199241 | 0.104541  |
| SWup   | detailed     |  6.14903  |   5.60673   | 1.11664  | 0.996707 |  0.400626   | 17.283    |  8.77069  | 0.144775 |  5.60673   | 0.116644  | 0.00329283 |   0.011806  |   0.0199241 | 0.0869166 |
| LWup   | baseline     | 11.7282   |  10.1532    | 1.09716  | 0.969616 |  5.93342    | 20.8603   | 15.4087   | 0.275886 | 10.1532    | 0.0971647 | 0.0303839  |   0.0276793 |   0.0125167 | 0.108267  |
| LWup   | detailed     | 13.4093   |  11.8067    | 1.12441  | 0.96012  |  6.07178    | 24.7925   | 18.0279   | 0.324283 | 11.8067    | 0.124407  | 0.0398799  |   0.0180074 |   0.079282  | 0.116276  |
| Qle    | baseline     | 23.8579   | -11.3288    | 0.527221 | 0.659109 | 12.2711     | 52.3804   | 41.3434   | 0.763524 | 11.3288    | 0.472779  | 0.340891   |   0.0143947 |   0.445542  | 0.219793  |
| Qle    | detailed     | 22.0946   |   2.27991   | 0.853786 | 0.694511 | 12.5011     |  2.394    | 38.4422   | 0.736901 |  2.27991   | 0.146214  | 0.305489   |   0.140965  |   0.724791  | 0.199953  |
| Qh     | baseline     | 26.82     |   1.01374   | 1.0346   | 0.896223 |  7.57938    |  5.37978  | 42.7596   | 0.464685 |  1.01374   | 0.0345953 | 0.103777   |   0.049866  |   0.204953  | 0.0964334 |
| Qh     | detailed     | 30.2301   | -10.2236    | 0.838067 | 0.855731 |  7.83724    | 53.2308   | 48.7117   | 0.517723 | 10.2236    | 0.161933  | 0.144269   |   0.0470694 |   0.382486  | 0.124814  |
| Qtau   | baseline     |  0.185807 |   0.154196  | 1.29268  | 0.866365 |  0.0120029  |  0.309245 |  0.264942 | 0.656622 |  0.154196  | 0.292676  | 0.133635   |   0.138334  |   0.163081  | 0.192322  |
| Qtau   | detailed     |  0.128508 |   0.0644557 | 1.0366   | 0.863232 |  0.00977071 |  0.051764 |  0.186616 | 0.533747 |  0.0644557 | 0.0365987 | 0.136768   |   0.119678  |   0.122095  | 0.122991  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="datasheet"></a>Datasheet
[![JULES_1T_AU-Preston_Datasheet.png](JULES_1T_AU-Preston_Datasheet.png)](JULES_1T_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![JULES_1T_AU-Preston_Distributions.png](JULES_1T_AU-Preston_Distributions.png)](JULES_1T_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![JULES_1T_AU-Preston_closure_baseline.png](JULES_1T_AU-Preston_closure_baseline.png)](JULES_1T_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![JULES_1T_AU-Preston_closure_detailed.png](JULES_1T_AU-Preston_closure_detailed.png)](JULES_1T_AU-Preston_closure_detailed.png)

### <a name="subset_lwup"></a>subset_LWup
[![JULES_1T_AU-Preston_subset_LWup.png](JULES_1T_AU-Preston_subset_LWup.png)](JULES_1T_AU-Preston_subset_LWup.png)

### <a name="subset_qh"></a>subset_Qh
[![JULES_1T_AU-Preston_subset_Qh.png](JULES_1T_AU-Preston_subset_Qh.png)](JULES_1T_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![JULES_1T_AU-Preston_subset_Qle.png](JULES_1T_AU-Preston_subset_Qle.png)](JULES_1T_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![JULES_1T_AU-Preston_subset_SWup.png](JULES_1T_AU-Preston_subset_SWup.png)](JULES_1T_AU-Preston_subset_SWup.png)

### out of range: baseline

 - JULES_1T Qh max value of 617.2024 is greater than expected 600.0 [W/m2]
 - JULES_1T EvapF max value of 64.5637 is greater than expected 1.0 [1]
 - JULES_1T EvapF min value of -24.3242 is less than expected 0.0 [1]

### out of range: detailed

 - JULES_1T SWE min value of -0.0000 is less than expected 0.0 [kg/m2]
 - JULES_1T EvapF max value of 81.1145 is greater than expected 1.0 [1]
 - JULES_1T EvapF min value of -256.6068 is less than expected 0.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

