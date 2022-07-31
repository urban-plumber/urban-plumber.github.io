# AU-Preston: UT&C

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |       MAE |       MBE |        nSD |          R |        5th |      95th |      RMSE |      cRMSE |      AMBE |       1-nSD |          1-R |    nSkewness |   nKurtosis |     Overlap |
|:-------|:-------------|----------:|----------:|-----------:|-----------:|-----------:|----------:|----------:|-----------:|----------:|------------:|-------------:|-------------:|------------:|------------:|
| SWup   | baseline     |  13.0997  | -13.0975  |   0.761989 |   0.995459 |   0.806116 |  35.4604  |  17.5929  |   0.252129 |  13.0975  |   0.238011  |   0.00454062 |   0.036527   |   0.0830146 |   0.0861988 |
| SWup   | detailed     |   4.22418 |  -3.74266 |   0.935788 |   0.996017 |   0.599063 |   9.89551 |   6.25591 |   0.107603 |   3.74266 |   0.0642116 |   0.00398339 |   0.0216831  |   0.0470881 |   0.0746291 |
| LWup   | baseline     |  11.0382  |   9.20452 |   1.09731  |   0.97744  |   8.04929  |  21.9777  |  13.741   |   0.242858 |   9.20452 |   0.0973125 |   0.0225597  |   0.155179   |   0.282806  |   0.109991  |
| LWup   | detailed     |  11.9846  |   9.55508 |   1.12004  |   0.972359 |   7.91165  |  23.9159  |  15.0337  |   0.276276 |   9.55508 |   0.12004   |   0.0276414  |   0.170119   |   0.314697  |   0.106143  |
| Qle    | baseline     |  25.8755  |  10.7007  |   0.990576 |   0.675908 |  13.9033   |  21.8413  |  43.081   |   0.801352 |  10.7007  |   0.0094239 |   0.324092   |   0.169727   |   0.6834    |   0.25979   |
| Qle    | detailed     |  23.5661  |   3.99798 |   0.846808 |   0.659024 |  13.3104   |   1.79982 |  40.567   |   0.775209 |   3.99798 |   0.153192  |   0.340976   |   0.14982    |   0.602544  |   0.202322  |
| Qh     | baseline     |  27.1001  |  16.0698  |   1.15984  |   0.935835 |   7.02582  |  51.6646  |  41.642   |   0.417603 |  16.0698  |   0.159843  |   0.0641648  |   0.00284941 |   0.0785515 |   0.107967  |
| Qh     | detailed     |  26.2522  |  16.541   |   1.12249  |   0.936682 |  12.9319   |  46.5346  |  40.0442  |   0.396426 |  16.541   |   0.122493  |   0.0633183  |   0.018228   |   0.155102  |   0.111467  |
| Qtau   | baseline     | nan       | nan       | nan        | nan        | nan        | nan       | nan       | nan        | nan       | nan         | nan          | nan          | nan         | nan         |
| Qtau   | detailed     | nan       | nan       | nan        | nan        | nan        | nan       | nan       | nan        | nan       | nan         | nan          | nan          | nan         | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="datasheet"></a>Datasheet
[![UT&C_AU-Preston_Datasheet.png](UT&C_AU-Preston_Datasheet.png)](UT&C_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![UT&C_AU-Preston_Distributions.png](UT&C_AU-Preston_Distributions.png)](UT&C_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![UT&C_AU-Preston_closure_baseline.png](UT&C_AU-Preston_closure_baseline.png)](UT&C_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![UT&C_AU-Preston_closure_detailed.png](UT&C_AU-Preston_closure_detailed.png)](UT&C_AU-Preston_closure_detailed.png)

### <a name="subset_lwup"></a>subset_LWup
[![UT&C_AU-Preston_subset_LWup.png](UT&C_AU-Preston_subset_LWup.png)](UT&C_AU-Preston_subset_LWup.png)

### <a name="subset_qh"></a>subset_Qh
[![UT&C_AU-Preston_subset_Qh.png](UT&C_AU-Preston_subset_Qh.png)](UT&C_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![UT&C_AU-Preston_subset_Qle.png](UT&C_AU-Preston_subset_Qle.png)](UT&C_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![UT&C_AU-Preston_subset_SWup.png](UT&C_AU-Preston_subset_SWup.png)](UT&C_AU-Preston_subset_SWup.png)

### out of range: baseline

 - UT&C EvapF max value of 18.2642 is greater than expected 1.0 [1]
 - UT&C EvapF min value of -2996.5289 is less than expected 0.0 [1]

### out of range: detailed

 - UT&C EvapF max value of 11.3992 is greater than expected 1.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

