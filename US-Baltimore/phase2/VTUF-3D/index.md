# US-Baltimore: VTUF-3D

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](VTUF-3D_US-Baltimore_baseline_attrs.md)
- [Detailed](VTUF-3D_US-Baltimore_detailed_attrs.md)

### Error metrics

| flux     | experiment   |       MAE |       MBE |        nSD |          R |       5th |     95th |     RMSE |      cRMSE |      AMBE |       1-nSD |         1-R |   nSkewness |   nKurtosis |    Overlap |
|:---------|:-------------|----------:|----------:|-----------:|-----------:|----------:|---------:|---------:|-----------:|----------:|------------:|------------:|------------:|------------:|-----------:|
| SWup     | baseline     | nan       | nan       | nan        | nan        | nan       | nan      | nan      | nan        | nan       | nan         | nan         |  nan        |  nan        | nan        |
| SWup     | detailed     |  22.3579  | -22.3361  |   0.572202 |   0.925564 |   1.0887  |  39.9024 |  27.6182 |   0.517876 |  22.3361  |   0.427797  |   0.0744356 |    0.810684 |    0.752886 |   0.29764  |
| LWup     | baseline     | nan       | nan       | nan        | nan        | nan       | nan      | nan      | nan        | nan       | nan         | nan         |  nan        |  nan        | nan        |
| LWup     | detailed     |   8.55455 |  -7.70763 |   0.907673 |   0.96688  |   4.11621 |  16.7741 |  12.5617 |   0.26201  |   7.70763 |   0.0923269 |   0.0331203 |   16.7069   |    2.13019  |   0.128027 |
| Qle      | baseline     | nan       | nan       | nan        | nan        | nan       | nan      | nan      | nan        | nan       | nan         | nan         |  nan        |  nan        | nan        |
| Qle      | detailed     |  17.2653  |  -2.96684 |   0.594436 |   0.460895 |  11.982   |  19.4626 |  32.8995 |   0.897446 |   2.96684 |   0.405564  |   0.539105  |    0.543702 |    3.26035  |   0.27738  |
| Qh       | baseline     | nan       | nan       | nan        | nan        | nan       | nan      | nan      | nan        | nan       | nan         | nan         |  nan        |  nan        | nan        |
| Qh       | detailed     |  66.6211  | -38.078   |   0.211857 |   0.623619 |  40.7409  | 227.695  | 102.133  |   0.883543 |  38.078   |   0.788143  |   0.376381  |    0.221879 |    0.332435 |   0.402969 |
| SoilTemp | baseline     | nan       | nan       | nan        | nan        | nan       | nan      | nan      | nan        | nan       | nan         | nan         |  nan        |  nan        | nan        |
| SoilTemp | detailed     | nan       | nan       | nan        | nan        | nan       | nan      | nan      | nan        | nan       | nan         | nan         |  nan        |  nan        | nan        |
| Qtau     | baseline     | nan       | nan       | nan        | nan        | nan       | nan      | nan      | nan        | nan       | nan         | nan         |  nan        |  nan        | nan        |
| Qtau     | detailed     | nan       | nan       | nan        | nan        | nan       | nan      | nan      | nan        | nan       | nan         | nan         |  nan        |  nan        | nan        |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### out of range: baseline


### out of range: detailed

 - VTUF-3D SWnet min value of -0.0001 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

