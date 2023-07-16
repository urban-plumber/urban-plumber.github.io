# CA-Sunset: UCLEM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](UCLEM_CA-Sunset_baseline_attrs.md)
- [Detailed](UCLEM_CA-Sunset_detailed_attrs.md)

### Error metrics

| flux     | experiment   |         MAE |         MBE |        nSD |          R |          5th |        95th |       RMSE |      cRMSE |        AMBE |       1-nSD |         1-R |    nSkewness |    nKurtosis |     Overlap |
|:---------|:-------------|------------:|------------:|-----------:|-----------:|-------------:|------------:|-----------:|-----------:|------------:|------------:|------------:|-------------:|-------------:|------------:|
| SWup     | baseline     |  12.542     |  11.4347    |   1.43224  |   0.961386 |   0.670033   |  32.4752    |  19.1127   |   0.545378 |  11.4347    |   0.432238  |   0.0386145 |   0.0315089  |   0.49031    |   0.153526  |
| SWup     | detailed     |   5.70089   |  -0.968034  |   1.00872  |   0.911872 |   0.745933   |   6.464     |  11.8826   |   0.421746 |   0.968034  |   0.0087254 |   0.0881278 |   0.363176   |  15.3203     |   0.0969087 |
| LWup     | baseline     |  18.1255    |  15.6324    |   1.38662  |   0.959825 |   0.705844   |  51.3182    |  26.4975   |   0.510775 |  15.6324    |   0.386621  |   0.040175  |   0.0813075  |   0.270191   |   0.138273  |
| LWup     | detailed     |  18.3561    |  15.2078    |   1.45336  |   0.957225 |   2.98904    |  60.4646    |  28.4614   |   0.574346 |  15.2078    |   0.453362  |   0.0427753 |   0.258023   |   0.346019   |   0.117405  |
| Qle      | baseline     |  21.4863    | -12.7368    |   0.697548 |   0.629919 |   5.1402     |  37.63      |  37.7449   |   0.7796   |  12.7368    |   0.302454  |   0.370081  |   0.439103   |   1.81146    |   0.219365  |
| Qle      | detailed     |  20.6111    |  -8.10171   |   0.816688 |   0.645088 |   5.4676     |  22.0381    |  36.6003   |   0.78314  |   8.10171   |   0.183314  |   0.354912  |   0.285838   |   1.15133    |   0.194124  |
| Qh       | baseline     |  34.5417    |  -8.97246   |   0.597717 |   0.909297 |  19.3651     | 105.155     |  54.5236   |   0.519866 |   8.97246   |   0.402285  |   0.0907033 |   0.0142762  |   0.00909931 |   0.371704  |
| Qh       | detailed     |  27.3495    |  -1.87482   |   0.737557 |   0.932309 |  19.0785     |  61.0244    |  42.5351   |   0.410766 |   1.87482   |   0.262445  |   0.0676912 |   0.00510691 |   0.0615474  |   0.330092  |
| Qtau     | baseline     |   0.119415  |   0.0840717 |   1.72326  |   0.298408 |   0.0102836  |   0.18159   |   0.180745 |   1.71498  |   0.0840717 |   0.723258  |   0.701592  |   0.551903   |   3.69648    |   0.344468  |
| Qtau     | detailed     |   0.0601441 |  -0.0185913 |   1.0718   |   0.189661 |   0.00461641 |   0.0903096 |   0.124541 |   1.31993  |   0.0185913 |   0.0717983 |   0.810339  |   8.58541    |  84.1408     |   0.0877238 |
| SoilTemp | baseline     | nan         | nan         | nan        | nan        | nan          | nan         | nan        | nan        | nan         | nan         | nan         | nan          | nan          | nan         |
| SoilTemp | detailed     | nan         | nan         | nan        | nan        | nan          | nan         | nan        | nan        | nan         | nan         | nan         | nan          | nan          | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![UCLEM_CA-Sunset_subset_SWup_v0-9.png](UCLEM_CA-Sunset_subset_SWup_v0-9.png)](UCLEM_CA-Sunset_subset_SWup_v0-9.png)

### out of range: baseline

 - UCLEM Qle max value of 760.4786 is greater than expected 700.0 [W/m2]

### out of range: detailed

 - UCLEM Qle max value of 844.7067 is greater than expected 700.0 [W/m2]
 - UCLEM Qle min value of -721.1955 is less than expected -700.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

