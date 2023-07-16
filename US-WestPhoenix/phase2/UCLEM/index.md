# US-WestPhoenix: UCLEM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](UCLEM_US-WestPhoenix_baseline_attrs.md)
- [Detailed](UCLEM_US-WestPhoenix_detailed_attrs.md)

### Error metrics

| flux     | experiment   |         MAE |         MBE |        nSD |          R |          5th |        95th |       RMSE |      cRMSE |        AMBE |       1-nSD |          1-R |   nSkewness |   nKurtosis |     Overlap |
|:---------|:-------------|------------:|------------:|-----------:|-----------:|-------------:|------------:|-----------:|-----------:|------------:|------------:|-------------:|------------:|------------:|------------:|
| SWup     | baseline     |   8.47578   |  -8.31727   |   0.902169 |   0.995387 |   3.2524     |  21.2468    |  10.7912   |   0.133773 |   8.31727   |   0.0978313 |   0.00461342 |    1.79384  |   0.0652585 |   0.115493  |
| SWup     | detailed     |   4.13193   |   1.14595   |   1.01269  |   0.994898 |   2.8952     |   4.1355    |   5.3884   |   0.102441 |   1.14595   |   0.0126948 |   0.00510172 |    2.01776  |   0.07301   |   0.110264  |
| LWup     | baseline     |  30.2296    |  30.2073    |   1.26181  |   0.9878   |   9.66339    |  78.5453    |  38.9043   |   0.315174 |  30.2073    |   0.261813  |   0.0122001  |    0.587195 |   0.792949  |   0.0878706 |
| LWup     | detailed     |  30.889     |  30.8547    |   1.17029  |   0.993285 |  16.2788     |  62.6288    |  34.9654   |   0.211458 |  30.8547    |   0.170289  |   0.00671467 |    0.303959 |   0.366523  |   0.116143  |
| Qle      | baseline     |  17.4128    | -13.4801    |   0.612632 |   0.347672 |   3.81077    |  40.8892    |  29.7193   |   0.974334 |  13.4801    |   0.387368  |   0.652328   |    5.52981  |  47.8832    |   0.528438  |
| Qle      | detailed     |  12.0128    |  -6.50872   |   0.805731 |   0.608756 |   3.95427    |  19.5048    |  23.1551   |   0.817445 |   6.50872   |   0.194268  |   0.391244   |    4.64086  |  49.2799    |   0.228326  |
| Qh       | baseline     |  23.0528    |   6.83437   |   0.989225 |   0.925584 |  15.6701     |  12.8176    |  35.6097   |   0.383855 |   6.83437   |   0.0107729 |   0.0744162  |    0.175896 |   1.0932    |   0.228455  |
| Qh       | detailed     |  35.284     |   5.75406   |   0.657109 |   0.901949 |  30.2535     |  58.5351    |  45.5609   |   0.496422 |   5.75406   |   0.342889  |   0.0980511  |    0.160148 |   1.25176   |   0.584249  |
| Qtau     | baseline     |   0.0565326 |   0.032586  |   1.57669  |   0.690555 |   0.00226532 |   0.0917224 |   0.129673 |   1.14384  |   0.032586  |   0.576686  |   0.309445   |    3.23701  |  27.0294    |   0.144152  |
| Qtau     | detailed     |   0.0514402 |   0.0191578 |   1.58241  |   0.543514 |   0.00026532 |   0.0289224 |   0.147803 |   1.33562  |   0.0191578 |   0.582404  |   0.456486   |    4.99896  |  40.7184    |   0.170173  |
| SoilTemp | baseline     | nan         | nan         | nan        | nan        | nan          | nan         | nan        | nan        | nan         | nan         | nan          |  nan        | nan         | nan         |
| SoilTemp | detailed     | nan         | nan         | nan        | nan        | nan          | nan         | nan        | nan        | nan         | nan         | nan          |  nan        | nan         | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![UCLEM_US-WestPhoenix_subset_SWup_v0-9.png](UCLEM_US-WestPhoenix_subset_SWup_v0-9.png)](UCLEM_US-WestPhoenix_subset_SWup_v0-9.png)

### out of range: baseline

 - UCLEM Qstor min value of -897.2451 is less than expected -800.0 [W/m2]
 - UCLEM Qle max value of 1074.7740 is greater than expected 700.0 [W/m2]

### out of range: detailed

 - UCLEM Qstor min value of -1064.5121 is less than expected -800.0 [W/m2]
 - UCLEM Qle max value of 1189.3718 is greater than expected 700.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

