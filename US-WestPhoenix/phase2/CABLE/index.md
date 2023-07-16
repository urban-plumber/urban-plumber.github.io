# US-WestPhoenix: CABLE

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](CABLE_US-WestPhoenix_baseline_attrs.md)
- [Detailed](CABLE_US-WestPhoenix_detailed_attrs.md)

### Error metrics

| flux     | experiment   |       MAE |       MBE |        nSD |          R |        5th |      95th |      RMSE |      cRMSE |      AMBE |       1-nSD |          1-R |   nSkewness |    nKurtosis |     Overlap |
|:---------|:-------------|----------:|----------:|-----------:|-----------:|-----------:|----------:|----------:|-----------:|----------:|------------:|-------------:|------------:|-------------:|------------:|
| SWup     | baseline     | nan       | nan       | nan        | nan        | nan        | nan       | nan       | nan        | nan       | nan         | nan          |  nan        | nan          | nan         |
| SWup     | detailed     |  23.1438  | -23.1433  |   0.752206 |   0.994247 |   3.7257   |  42.8988  |  26.8455  |   0.264683 |  23.1433  |   0.247795  |   0.00575299 |    0.135909 |   0.00631915 |   0.130503  |
| LWup     | baseline     | nan       | nan       | nan        | nan        | nan        | nan       | nan       | nan        | nan       | nan         | nan          |  nan        | nan          | nan         |
| LWup     | detailed     |  43.7367  |  42.7502  |   1.63637  |   0.960663 |   0.974953 | 163.361   |  71.1126  |   0.730554 |  42.7502  |   0.636371  |   0.039337   |    1.12676  |   1.2633     |   0.0539742 |
| Qle      | baseline     | nan       | nan       | nan        | nan        | nan        | nan       | nan       | nan        | nan       | nan         | nan          |  nan        | nan          | nan         |
| Qle      | detailed     |  17.6469  |  -9.41263 |   0.941904 |   0.352801 |   4.03152  |  36.5055  |  31.4968  |   1.1057   |   9.41263 |   0.0580958 |   0.647199   |    2.57047  |   7.94472    |   0.379337  |
| Qh       | baseline     | nan       | nan       | nan        | nan        | nan        | nan       | nan       | nan        | nan       | nan         | nan          |  nan        | nan          | nan         |
| Qh       | detailed     |  27.6513  |  -5.15401 |   0.934161 |   0.870042 |  10.9577   |   9.87036 |  45.5531  |   0.497129 |   5.15401 |   0.0658362 |   0.129958   |    0.284725 |   1.79695    |   0.236835  |
| Qtau     | baseline     | nan       | nan       | nan        | nan        | nan        | nan       | nan       | nan        | nan       | nan         | nan          |  nan        | nan          | nan         |
| Qtau     | detailed     | nan       | nan       | nan        | nan        | nan        | nan       | nan       | nan        | nan       | nan         | nan          |  nan        | nan          | nan         |
| SoilTemp | baseline     | nan       | nan       | nan        | nan        | nan        | nan       | nan       | nan        | nan       | nan         | nan          |  nan        | nan          | nan         |
| SoilTemp | detailed     |   5.84264 |   3.54757 |   1.37924  |   0.936345 |   0.612213 |  15.4794  |   8.26681 |   0.565169 |   3.54757 |   0.379242  |   0.0636545  |    7.52815  |   0.164547   |   0.102539  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![CABLE_US-WestPhoenix_subset_SWup_v0-9.png](CABLE_US-WestPhoenix_subset_SWup_v0-9.png)](CABLE_US-WestPhoenix_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed

 - CABLE Qstor min value of -972.8366 is less than expected -800.0 [W/m2]
 - CABLE LWnet min value of -532.2761 is less than expected -500.0 [W/m2]
 - CABLE SoilTemp max value of 357.2813 is greater than expected 333.0 [K]
 - CABLE Qle max value of 885.8264 is greater than expected 700.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

