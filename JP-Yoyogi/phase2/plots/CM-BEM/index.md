# JP-Yoyogi: CM-BEM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](CM-BEM_JP-Yoyogi_baseline_attrs.md)
- [Detailed](CM-BEM_JP-Yoyogi_detailed_attrs.md)

### Error metrics

| flux   | experiment   |      MAE |        MBE |        nSD |          R |       5th |     95th |     RMSE |      cRMSE |       AMBE |      1-nSD |         1-R |   nSkewness |   nKurtosis |    Overlap |
|:-------|:-------------|---------:|-----------:|-----------:|-----------:|----------:|---------:|---------:|-----------:|-----------:|-----------:|------------:|------------:|------------:|-----------:|
| SWup   | baseline     | nan      | nan        | nan        | nan        | nan       | nan      | nan      | nan        | nan        | nan        | nan         |  nan        |  nan        | nan        |
| SWup   | detailed     |  13.1263 |  -8.622    |   1.14053  |   0.845717 |  11.5678  |   2.7194 |  22.0653 |   0.609654 |   8.622    |   0.140528 |   0.154283  |    0.156767 |    0.282027 |   0.205619 |
| LWup   | baseline     | nan      | nan        | nan        | nan        | nan       | nan      | nan      | nan        | nan        | nan        | nan         |  nan        |  nan        | nan        |
| LWup   | detailed     |  16.5711 |   0.221375 |   1.32855  |   0.958796 |  14.281   |  48.3927 |  23.6203 |   0.46629  |   0.221375 |   0.328546 |   0.0412042 |    2.52929  |    1.88876  |   0.113484 |
| Qle    | baseline     | nan      | nan        | nan        | nan        | nan       | nan      | nan      | nan        | nan        | nan        | nan         |  nan        |  nan        | nan        |
| Qle    | detailed     |  24.0961 | -21.5779   |   0.231501 |   0.493049 |   1.69569 |  80.191  |  40.8237 |   0.908466 |  21.5779   |   0.768499 |   0.506951  |    0.250277 |    0.23381  |   0.389191 |
| Qh     | baseline     | nan      | nan        | nan        | nan        | nan       | nan      | nan      | nan        | nan        | nan        | nan         |  nan        |  nan        | nan        |
| Qh     | detailed     |  55.8393 |  53.3375   |   1.56648  |   0.879212 |  13.4943  | 132.338  |  76.7821 |   0.836258 |  53.3375   |   0.566482 |   0.120788  |    0.148282 |    0.54077  |   0.266706 |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![CM-BEM_JP-Yoyogi_subset_SWup_v0-9.png](CM-BEM_JP-Yoyogi_subset_SWup_v0-9.png)](CM-BEM_JP-Yoyogi_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed

 - CM-BEM SWnet min value of -23.7893 is less than expected 0.0 [W/m2]
 - CM-BEM SWup min value of -58.8805 is less than expected 0.0 [W/m2]
 - CM-BEM Albedo min value of -0.1406 is less than expected 0.0 [1]
 - CM-BEM alb min value of -0.1404 is less than expected 0.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

