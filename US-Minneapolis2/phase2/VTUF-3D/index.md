# US-Minneapolis2: VTUF-3D

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](VTUF-3D_US-Minneapolis2_baseline_attrs.md)
- [Detailed](VTUF-3D_US-Minneapolis2_detailed_attrs.md)

### Error metrics

| flux     | experiment   |      MAE |        MBE |         nSD |          R |      5th |     95th |     RMSE |      cRMSE |       AMBE |      1-nSD |         1-R |   nSkewness |   nKurtosis |     Overlap |
|:---------|:-------------|---------:|-----------:|------------:|-----------:|---------:|---------:|---------:|-----------:|-----------:|-----------:|------------:|------------:|------------:|------------:|
| SWup     | baseline     | nan      | nan        | nan         | nan        | nan      | nan      | nan      | nan        | nan        | nan        | nan         |  nan        |  nan        | nan         |
| SWup     | detailed     |  96.4278 | -96.4276   |   0.0166954 |   0.200102 |   2.6098 | 297.974  | 136.445  |   0.996793 |  96.4276   |   0.983305 |   0.799898  |    0.46532  |    0.809169 |   0.672363  |
| LWup     | baseline     | nan      | nan        | nan         | nan        | nan      | nan      | nan      | nan        | nan        | nan        | nan         |  nan        |  nan        | nan         |
| LWup     | detailed     |  17.8946 |  -0.676871 |   0.885844  |   0.940226 |   7.4023 |  29.0635 |  25.0161 |   0.344866 |   0.676871 |   0.114156 |   0.0597742 |    1.2569   |    0.856663 |   0.0986054 |
| Qle      | baseline     | nan      | nan        | nan         | nan        | nan      | nan      | nan      | nan        | nan        | nan        | nan         |  nan        |  nan        | nan         |
| Qle      | detailed     |  37.9106 | -33.1662   |   0.191997  |   0.740564 |   5.742  | 182.44   |  74.6476 |   0.867462 |  33.1662   |   0.808003 |   0.259436  |    0.28788  |    0.399393 |   0.308396  |
| Qh       | baseline     | nan      | nan        | nan         | nan        | nan      | nan      | nan      | nan        | nan        | nan        | nan         |  nan        |  nan        | nan         |
| Qh       | detailed     |  42.4563 | -14.9731   |   0.280048  |   0.21084  |  31.4446 | 111.843  |  63.9076 |   0.979968 |  14.9731   |   0.719952 |   0.78916   |    0.840564 |    4.06194  |   0.548078  |
| Qg       | baseline     | nan      | nan        | nan         | nan        | nan      | nan      | nan      | nan        | nan        | nan        | nan         |  nan        |  nan        | nan         |
| Qg       | detailed     | nan      | nan        | nan         | nan        | nan      | nan      | nan      | nan        | nan        | nan        | nan         |  nan        |  nan        | nan         |
| Qtau     | baseline     | nan      | nan        | nan         | nan        | nan      | nan      | nan      | nan        | nan        | nan        | nan         |  nan        |  nan        | nan         |
| Qtau     | detailed     | nan      | nan        | nan         | nan        | nan      | nan      | nan      | nan        | nan        | nan        | nan         |  nan        |  nan        | nan         |
| SoilTemp | baseline     | nan      | nan        | nan         | nan        | nan      | nan      | nan      | nan        | nan        | nan        | nan         |  nan        |  nan        | nan         |
| SoilTemp | detailed     | nan      | nan        | nan         | nan        | nan      | nan      | nan      | nan        | nan        | nan        | nan         |  nan        |  nan        | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![VTUF-3D_US-Minneapolis2_subset_SWup_v0-9.png](VTUF-3D_US-Minneapolis2_subset_SWup_v0-9.png)](VTUF-3D_US-Minneapolis2_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed

 - VTUF-3D SWup min value of -1.2324 is less than expected 0.0 [W/m2]
 - VTUF-3D alb min value of -0.0040 is less than expected 0.0 [1]
 - VTUF-3D SWnet min value of -0.0001 is less than expected 0.0 [W/m2]
 - VTUF-3D Albedo min value of -0.0040 is less than expected 0.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

