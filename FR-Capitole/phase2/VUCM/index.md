# FR-Capitole: VUCM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](VUCM_FR-Capitole_baseline_attrs.md)
- [Detailed](VUCM_FR-Capitole_detailed_attrs.md)

### Error metrics

| flux   | experiment   |      MAE |        MBE |        nSD |          R |      5th |     95th |     RMSE |      cRMSE |       AMBE |       1-nSD |        1-R |   nSkewness |   nKurtosis |    Overlap |
|:-------|:-------------|---------:|-----------:|-----------:|-----------:|---------:|---------:|---------:|-----------:|-----------:|------------:|-----------:|------------:|------------:|-----------:|
| SWup   | baseline     | nan      | nan        | nan        | nan        | nan      | nan      | nan      | nan        | nan        | nan         | nan        |  nan        |  nan        | nan        |
| SWup   | detailed     |  23.4632 | -14.8121   |   0.736349 |   0.617514 |   3.037  |  30.1883 |  30.4644 |   0.795486 |  14.8121   |   0.26365   |   0.382486 |    0.177139 |    0.331387 |   0.227295 |
| LWup   | baseline     | nan      | nan        | nan        | nan        | nan      | nan      | nan      | nan        | nan        | nan         | nan        |  nan        |  nan        | nan        |
| LWup   | detailed     |  41.6281 | -38.0045   |   0.975355 |   0.80925  |  44.2797 |  45.381  |  49.7611 |   0.610497 |  38.0045   |   0.0246455 |   0.19075  |    0.276303 |    0.838245 |   0.291749 |
| Qle    | baseline     | nan      | nan        | nan        | nan        | nan      | nan      | nan      | nan        | nan        | nan         | nan        |  nan        |  nan        | nan        |
| Qle    | detailed     |  22.7336 |  -0.827535 |   1.60457  |   0.228114 |   4.644  |  23.035  |  34.8264 |   1.686    |   0.827535 |   0.604568  |   0.771886 |    1.49483  |    2.30376  |   0.431387 |
| Qh     | baseline     | nan      | nan        | nan        | nan        | nan      | nan      | nan      | nan        | nan        | nan         | nan        |  nan        |  nan        | nan        |
| Qh     | detailed     |  64.4837 |  34.5953   |   0.962378 |   0.563485 |  13.232  |  13.518  |  82.9645 |   0.917388 |  34.5953   |   0.0376214 |   0.436515 |    0.375592 |    0.627443 |   0.285352 |
| Qtau   | baseline     | nan      | nan        | nan        | nan        | nan      | nan      | nan      | nan        | nan        | nan         | nan        |  nan        |  nan        | nan        |
| Qtau   | detailed     | nan      | nan        | nan        | nan        | nan      | nan      | nan      | nan        | nan        | nan         | nan        |  nan        |  nan        | nan        |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![VUCM_FR-Capitole_subset_SWup_v0-9.png](VUCM_FR-Capitole_subset_SWup_v0-9.png)](VUCM_FR-Capitole_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed

 - VUCM SWnet min value of -0.0010 is less than expected 0.0 [W/m2]
 - VUCM Albedo max value of 1.3574 is greater than expected 1.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

