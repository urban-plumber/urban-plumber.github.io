# US-Baltimore: CM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](CM_US-Baltimore_baseline_attrs.md)
- [Detailed](CM_US-Baltimore_detailed_attrs.md)

### Error metrics

| flux     | experiment   |      MAE |        MBE |        nSD |          R |     5th |    95th |     RMSE |      cRMSE |       AMBE |      1-nSD |         1-R |   nSkewness |   nKurtosis |    Overlap |
|:---------|:-------------|---------:|-----------:|-----------:|-----------:|--------:|--------:|---------:|-----------:|-----------:|-----------:|------------:|------------:|------------:|-----------:|
| SWup     | baseline     | nan      | nan        | nan        | nan        | nan     | nan     | nan      | nan        | nan        | nan        | nan         |  nan        | nan         | nan        |
| SWup     | detailed     | 286.659  | 286.658    |   8.04994  |   0.964133 |  10.107 | 735.525 | 372.44   |   7.09078  | 286.658    |   7.04994  |   0.0358668 |    0.179663 |   0.181769  |   0.275129 |
| LWup     | baseline     | nan      | nan        | nan        | nan        | nan     | nan     | nan      | nan        | nan        | nan        | nan         |  nan        | nan         | nan        |
| LWup     | detailed     |  58.7666 | -58.6044   |   1.18975  |   0.83946  |  86.779 |  49.263 |  68.6377 |   0.646538 |  58.6044   |   0.189752 |   0.16054   |    6.52081  |   0.0475726 |   0.29877  |
| Qle      | baseline     | nan      | nan        | nan        | nan        | nan     | nan     | nan      | nan        | nan        | nan        | nan         |  nan        | nan         | nan        |
| Qle      | detailed     |  36.9882 |  -7.77914  |   0.703396 |   0.541229 |  14.651 |  67.706 |  62.4346 |   0.85637  |   7.77914  |   0.296604 |   0.458771  |    0.176194 |   0.661942  |   0.193634 |
| Qh       | baseline     | nan      | nan        | nan        | nan        | nan     | nan     | nan      | nan        | nan        | nan        | nan         |  nan        | nan         | nan        |
| Qh       | detailed     |  37.1163 |  -0.779981 |   0.684338 |   0.790439 |  32.653 |  56.866 |  55.1329 |   0.621662 |   0.779981 |   0.315663 |   0.209561  |    0.206355 |   0.767832  |   0.328897 |
| SoilTemp | baseline     | nan      | nan        | nan        | nan        | nan     | nan     | nan      | nan        | nan        | nan        | nan         |  nan        | nan         | nan        |
| SoilTemp | detailed     | nan      | nan        | nan        | nan        | nan     | nan     | nan      | nan        | nan        | nan        | nan         |  nan        | nan         | nan        |
| Qtau     | baseline     | nan      | nan        | nan        | nan        | nan     | nan     | nan      | nan        | nan        | nan        | nan         |  nan        | nan         | nan        |
| Qtau     | detailed     | nan      | nan        | nan        | nan        | nan     | nan     | nan      | nan        | nan        | nan        | nan         |  nan        | nan         | nan        |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![CM_US-Baltimore_subset_SWup_v0-9.png](CM_US-Baltimore_subset_SWup_v0-9.png)](CM_US-Baltimore_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed

 - CM SWnet min value of -0.0050 is less than expected 0.0 [W/m2]
 - CM Albedo max value of 1.0001 is greater than expected 1.0 [1]
 - CM Qle min value of -841.6700 is less than expected -700.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

