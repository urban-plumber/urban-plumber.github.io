# KR-Ochang: UCLEM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](UCLEM_KR-Ochang_baseline_attrs.md)
- [Detailed](UCLEM_KR-Ochang_detailed_attrs.md)

### Error metrics

| flux   | experiment   |      MAE |        MBE |      nSD |        R |       5th |     95th |    RMSE |    cRMSE |       AMBE |      1-nSD |       1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|---------:|-----------:|---------:|---------:|----------:|---------:|--------:|---------:|-----------:|-----------:|----------:|------------:|------------:|----------:|
| SWup   | baseline     |  9.86768 |  0.0533388 | 0.94061  | 0.898432 |  1.66009  |  6.54899 | 21.2407 | 0.441134 |  0.0533388 | 0.0593914  | 0.101568  |   0.485388  | 1.04413     | 0.0881236 |
| SWup   | detailed     |  9.87851 |  1.24978   | 0.962921 | 0.89781  |  1.63329  |  2.78079 | 21.4714 | 0.445171 |  1.24978   | 0.037081   | 0.10219   |   0.471312  | 1.0338      | 0.0846366 |
| LWup   | baseline     | 27.2381  | 27.1003    | 1.21908  | 0.984997 |  8.1661   | 60.338   | 32.7843 | 0.290824 | 27.1003    | 0.219082   | 0.0150035 |   2.98797   | 0.287514    | 0.142944  |
| LWup   | detailed     | 31.4003  | 31.2926    | 1.26068  | 0.983023 |  9.189    | 69.596   | 37.7489 | 0.332803 | 31.2926    | 0.260678   | 0.0169765 |   3.33331   | 0.319798    | 0.159896  |
| Qle    | baseline     | 24.4943  |  0.605474  | 1.03492  | 0.715471 |  0.504137 | 16.6869  | 42.5106 | 0.76821  |  0.605474  | 0.0349171  | 0.284529  |   0.270819  | 0.689246    | 0.219562  |
| Qle    | detailed     | 24.0601  | -1.04061   | 0.997182 | 0.716491 |  0.529437 | 10.1842  | 41.6195 | 0.75195  |  1.04061   | 0.00281878 | 0.283509  |   0.274212  | 0.692113    | 0.221945  |
| Qh     | baseline     | 22.2197  |  3.57873   | 0.739161 | 0.873071 | 16.3115   | 39.0991  | 34.1196 | 0.505647 |  3.57873   | 0.260838   | 0.126929  |   0.0695816 | 0.117533    | 0.369603  |
| Qh     | detailed     | 23.1846  | -1.7581    | 0.625272 | 0.868763 | 16.9732   | 60.388   | 37.0735 | 0.55185  |  1.7581    | 0.374727   | 0.131237  |   0.0309193 | 0.000475514 | 0.431713  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![UCLEM_KR-Ochang_subset_SWup_v0-9.png](UCLEM_KR-Ochang_subset_SWup_v0-9.png)](UCLEM_KR-Ochang_subset_SWup_v0-9.png)

### out of range: baseline

 - UCLEM Qle min value of -843.5098 is less than expected -700.0 [W/m2]

### out of range: detailed

 - UCLEM Qle min value of -849.1327 is less than expected -700.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

