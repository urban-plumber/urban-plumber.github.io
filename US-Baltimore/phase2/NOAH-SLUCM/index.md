# US-Baltimore: NOAH-SLUCM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](NOAH-SLUCM_US-Baltimore_baseline_attrs.md)
- [Detailed](NOAH-SLUCM_US-Baltimore_detailed_attrs.md)

### Error metrics

| flux     | experiment   |       MAE |       MBE |        nSD |          R |        5th |      95th |      RMSE |      cRMSE |      AMBE |       1-nSD |         1-R |   nSkewness |   nKurtosis |     Overlap |
|:---------|:-------------|----------:|----------:|-----------:|-----------:|-----------:|----------:|----------:|-----------:|----------:|------------:|------------:|------------:|------------:|------------:|
| SWup     | baseline     |  19.4612  |  18.4323  |   1.56738  |   0.964202 |   0.476    |  50.5103  |  28.7738  |   0.658887 |  18.4323  |   0.567376  |   0.0357978 |   0.836142  |    2.46319  |   0.183872  |
| SWup     | detailed     |  13.979   |  12.3681  |   1.43176  |   0.956294 |   0.244644 |  35.2667  |  22.435   |   0.558185 |  12.3681  |   0.43176   |   0.0437064 |   1.07299   |    3.50566  |   0.137073  |
| LWup     | baseline     |  12.5192  |   5.63356 |   1.19049  |   0.972632 |   3.56226  |  38.8663  |  18.482   |   0.318515 |   5.63356 |   0.190493  |   0.0273684 |   7.39207   |    0.521033 |   0.0772177 |
| LWup     | detailed     |  17.2311  |   9.24672 |   1.28414  |   0.952645 |   3.92459  |  58.6492  |  26.5239  |   0.449839 |   9.24672 |   0.284138  |   0.0473546 |  11.023     |    0.83232  |   0.0844268 |
| Qle      | baseline     |  25.2284  |  -4.03362 |   0.85135  |   0.815126 |  13.266    |  41.5752  |  42.1794  |   0.580415 |   4.03362 |   0.14865   |   0.184874  |   0.192418  |    0.577554 |   0.149044  |
| Qle      | detailed     |  25.2334  |  -4.025   |   0.851677 |   0.815005 |  13.2831   |  41.5678  |  42.1928  |   0.580613 |   4.025   |   0.148323  |   0.184995  |   0.193088  |    0.580244 |   0.149096  |
| Qh       | baseline     |  29.3615  |  -7.07252 |   0.796637 |   0.857903 |  15.496    |  43.7175  |  46.4282  |   0.517452 |   7.07252 |   0.203364  |   0.142097  |   0.0834045 |    0.247703 |   0.132618  |
| Qh       | detailed     |  28.6678  |  -7.58137 |   0.807778 |   0.864482 |  13.4155   |  43.2881  |  45.4938  |   0.505852 |   7.58137 |   0.192223  |   0.135518  |   0.0584055 |    0.177512 |   0.126191  |
| SoilTemp | baseline     |   2.24922 |  -1.73122 |   1.01263  |   0.973474 |   2.0191   |   2.56149 |   2.77668 |   0.232123 |   1.73122 |   0.0126287 |   0.0265257 |   2.81343   |    0.045182 |   0.13652   |
| SoilTemp | detailed     |   2.24922 |  -1.73122 |   1.01263  |   0.973474 |   2.0191   |   2.56149 |   2.77668 |   0.232123 |   1.73122 |   0.0126287 |   0.0265257 |   2.81343   |    0.045182 |   0.13652   |
| Qtau     | baseline     | nan       | nan       | nan        | nan        | nan        | nan       | nan       | nan        | nan       | nan         | nan         | nan         |  nan        | nan         |
| Qtau     | detailed     | nan       | nan       | nan        | nan        | nan        | nan       | nan       | nan        | nan       | nan         | nan         | nan         |  nan        | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![NOAH-SLUCM_US-Baltimore_subset_SWup_v0-9.png](NOAH-SLUCM_US-Baltimore_subset_SWup_v0-9.png)](NOAH-SLUCM_US-Baltimore_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed

 - NOAH-SLUCM Qle max value of 1155.9603 is greater than expected 700.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

