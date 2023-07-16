# US-Minneapolis2: UCLEM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](UCLEM_US-Minneapolis2_baseline_attrs.md)
- [Detailed](UCLEM_US-Minneapolis2_detailed_attrs.md)

### Error metrics

| flux     | experiment   |        MAE |        MBE |        nSD |          R |          5th |       95th |       RMSE |      cRMSE |       AMBE |       1-nSD |         1-R |   nSkewness |   nKurtosis |     Overlap |
|:---------|:-------------|-----------:|-----------:|-----------:|-----------:|-------------:|-----------:|-----------:|-----------:|-----------:|------------:|------------:|------------:|------------:|------------:|
| SWup     | baseline     |  40.4572   | -39.8464   |   0.505321 |   0.829182 |   1.6468     | 161.165    |  74.1722   |   0.646021 |  39.8464   |   0.49468   |   0.170818  |   0.628362  |   1.05067   |   0.166684  |
| SWup     | detailed     |  25.6581   | -15.1434   |   0.730746 |   0.869761 |   1.2043     |  99.4036   |  51.9056   |   0.51268  |  15.1434   |   0.269255  |   0.130239  |   0.560201  |   0.956864  |   0.0978059 |
| LWup     | baseline     |  14.6996   |  13.1242   |   1.02802  |   0.984813 |   9.5524     |  17.0034   |  18.453    |   0.178915 |  13.1242   |   0.0280167 |   0.0151872 |   0.391072  |   0.363058  |   0.106121  |
| LWup     | detailed     |  17.0922   |   2.154    |   1.12244  |   0.963917 |  16.7055     |  19.0278   |  22.5666   |   0.309829 |   2.154    |   0.122437  |   0.0360835 |   0.426371  |   0.0235995 |   0.109816  |
| Qle      | baseline     |  21.7225   |   0.125008 |   1.14458  |   0.898302 |   2.7503     |  42.2988   |  38.8313   |   0.503693 |   0.125008 |   0.144579  |   0.101698  |   0.106522  |   0.365256  |   0.210492  |
| Qle      | detailed     |  25.612    |   4.5298   |   1.26081  |   0.897133 |   7.4981     |  64.5734   |  44.3445   |   0.572201 |   4.5298   |   0.26081   |   0.102867  |   0.163922  |   0.499741  |   0.243554  |
| Qh       | baseline     |  26.4016   |  19.998    |   1.10067  |   0.868095 |  21.774      |  40.3647   |  40.0968   |   0.548179 |  19.998    |   0.100667  |   0.131905  |   0.127424  |   0.542257  |   0.211526  |
| Qh       | detailed     |  21.2462   |  10.6127   |   1.01074  |   0.869668 |  18.1991     |  19.0796   |  34.2355   |   0.513401 |  10.6127   |   0.0107446 |   0.130332  |   0.0958927 |   0.613363  |   0.166129  |
| Qg       | baseline     | nan        | nan        | nan        | nan        | nan          | nan        | nan        | nan        | nan        | nan         | nan         | nan         | nan         | nan         |
| Qg       | detailed     | nan        | nan        | nan        | nan        | nan          | nan        | nan        | nan        | nan        | nan         | nan         | nan         | nan         | nan         |
| Qtau     | baseline     |   0.119159 |  -0.108489 |   0.522167 |   0.803179 |   0.00374557 |   0.397855 |   0.208261 |   0.658689 |   0.108489 |   0.477833  |   0.196821  |   2.21777   |  23.6209    |   0.18728   |
| Qtau     | detailed     |   0.13855  |  -0.132545 |   0.514402 |   0.777121 |   0.00474557 |   0.420155 |   0.226817 |   0.681986 |   0.132545 |   0.485599  |   0.222879  |   2.41647   |  25.644     |   0.259931  |
| SoilTemp | baseline     | nan        | nan        | nan        | nan        | nan          | nan        | nan        | nan        | nan        | nan         | nan         | nan         | nan         | nan         |
| SoilTemp | detailed     | nan        | nan        | nan        | nan        | nan          | nan        | nan        | nan        | nan        | nan         | nan         | nan         | nan         | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![UCLEM_US-Minneapolis2_subset_SWup_v0-9.png](UCLEM_US-Minneapolis2_subset_SWup_v0-9.png)](UCLEM_US-Minneapolis2_subset_SWup_v0-9.png)

### out of range: baseline

 - UCLEM Qh max value of 943.4786 is greater than expected 600.0 [W/m2]
 - UCLEM Qle min value of -1125.7659 is less than expected -700.0 [W/m2]

### out of range: detailed

 - UCLEM Qh max value of 862.6063 is greater than expected 600.0 [W/m2]
 - UCLEM Qle min value of -1028.0083 is less than expected -700.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

