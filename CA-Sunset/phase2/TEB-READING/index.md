# CA-Sunset: TEB-READING

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](TEB-READING_CA-Sunset_baseline_attrs.md)
- [Detailed](TEB-READING_CA-Sunset_detailed_attrs.md)

### Error metrics

| flux     | experiment   |       MAE |        MBE |        nSD |          R |        5th |      95th |      RMSE |      cRMSE |       AMBE |       1-nSD |         1-R |   nSkewness |   nKurtosis |     Overlap |
|:---------|:-------------|----------:|-----------:|-----------:|-----------:|-----------:|----------:|----------:|-----------:|-----------:|------------:|------------:|------------:|------------:|------------:|
| SWup     | baseline     |   4.35275 |   0.445499 |   1.04504  |   0.960139 |   0.623558 |   1.14462 |   8.21556 |   0.292135 |   0.445499 |   0.0450463 |   0.0398614 |   0.043101  |   1.91556   |   0.0660605 |
| SWup     | detailed     |   7.13506 |   4.68698  |   1.23335  |   0.951066 |   0.578684 |  17.36    |  12.6526  |   0.418518 |   4.68698  |   0.233351  |   0.0489345 |   0.184445  |   4.61812   |   0.0965348 |
| LWup     | baseline     |  13.5692  |   8.73764  |   1.37694  |   0.955648 |   4.5463   |  49.1884  |  23.2366  |   0.514028 |   8.73764  |   0.376942  |   0.0443518 |   0.372105  |   0.758286  |   0.0925616 |
| LWup     | detailed     |  16.2174  |   9.28505  |   1.47919  |   0.953636 |   8.40246  |  60.475   |  27.014   |   0.60563  |   9.28505  |   0.479193  |   0.0463637 |   0.425123  |   0.938266  |   0.114833  |
| Qle      | baseline     |  20.897   |  -9.72002  |   0.734704 |   0.660117 |   5.90996  |  24.9997  |  35.7501  |   0.754857 |   9.72002  |   0.265298  |   0.339883  |   0.134318  |   0.0328189 |   0.23275   |
| Qle      | detailed     |  22.6773  |   2.11925  |   1.03538  |   0.673773 |   6.61173  |  11.9798  |  37.554   |   0.822675 |   2.11925  |   0.0353821 |   0.326227  |   0.163799  |   0.594319  |   0.297545  |
| Qh       | baseline     |  31.1986  |  16.4061   |   0.822349 |   0.945074 |  29.4033   |  19.2398  |  39.6698  |   0.349137 |  16.4061   |   0.177654  |   0.0549263 |   0.0216541 |   0.116508  |   0.450463  |
| Qh       | detailed     |  22.3142  |  -5.63223  |   0.787719 |   0.949863 |  16.829    |  47.7653  |  36.8689  |   0.35221  |   5.63223  |   0.212284  |   0.0501374 |   0.0190485 |   0.184514  |   0.203605  |
| Qtau     | baseline     | nan       | nan        | nan        | nan        | nan        | nan       | nan       | nan        | nan        | nan         | nan         | nan         | nan         | nan         |
| Qtau     | detailed     | nan       | nan        | nan        | nan        | nan        | nan       | nan       | nan        | nan        | nan         | nan         | nan         | nan         | nan         |
| SoilTemp | baseline     | nan       | nan        | nan        | nan        | nan        | nan       | nan       | nan        | nan        | nan         | nan         | nan         | nan         | nan         |
| SoilTemp | detailed     | nan       | nan        | nan        | nan        | nan        | nan       | nan       | nan        | nan        | nan         | nan         | nan         | nan         | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![TEB-READING_CA-Sunset_subset_SWup_v0-9.png](TEB-READING_CA-Sunset_subset_SWup_v0-9.png)](TEB-READING_CA-Sunset_subset_SWup_v0-9.png)

### out of range: baseline

 - TEB-READING Qanth min value of -3.4537 is less than expected 0.0 [W/m2]

### out of range: detailed

 - TEB-READING Qanth min value of -4.0238 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

