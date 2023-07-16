# US-WestPhoenix: TERRA_4.11

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](TERRA_4.11_US-WestPhoenix_baseline_attrs.md)
- [Detailed](TERRA_4.11_US-WestPhoenix_detailed_attrs.md)

### Error metrics

| flux     | experiment   |       MAE |       MBE |        nSD |          R |       5th |      95th |      RMSE |       cRMSE |      AMBE |       1-nSD |          1-R |    nSkewness |    nKurtosis |     Overlap |
|:---------|:-------------|----------:|----------:|-----------:|-----------:|----------:|----------:|----------:|------------:|----------:|------------:|-------------:|-------------:|-------------:|------------:|
| SWup     | baseline     |  12.74    | -12.7359  |   0.883723 |   0.995726 |   3.28465 |  21.4574  |  14.7605  |   0.145168  |  12.7359  |   0.116277  |   0.00427364 |   0.156184   |   0.00655098 |   0.107213  |
| SWup     | detailed     |   9.14216 |   7.64174 |   1.13928  |   0.995668 |   2.40135 |  20.3559  |  11.6498  |   0.171086  |   7.64174 |   0.139281  |   0.00433228 |   0.136426   |   0.0066661  |   0.103934  |
| LWup     | baseline     |  40.539   | -40.5141  |   0.881059 |   0.98247  |  29.9347  |  62.108   |  43.7481  |   0.212217  |  40.5141  |   0.118941  |   0.0175295  |   0.184761   |   0.194771   |   0.179767  |
| LWup     | detailed     |   4.63546 |  -1.36951 |   1.0131   |   0.99707  |   1.98015 |   3.91215 |   6.23246 |   0.0781632 |   1.36951 |   0.0131031 |   0.00293049 |   0.108939   |   0.104148   |   0.0475445 |
| Qle      | baseline     |  16.5031  | -12.8408  |   0.42804  |   0.439092 |   4.06044 |  53.3736  |  27.5948  |   0.89851   |  12.8408  |   0.57196   |   0.560908   |   2.27851    |   7.08319    |   0.404083  |
| Qle      | detailed     |  16.7249  | -13.1723  |   0.417571 |   0.41411  |   4.09039 |  54.0126  |  28.0315  |   0.910234  |  13.1723  |   0.582429  |   0.58589    |   2.09739    |   5.64015    |   0.52806   |
| Qh       | baseline     |  72.5217  |  71.4031  |   1.32686  |   0.935789 |  50.9806  | 151.356   |  86.0023  |   0.52653   |  71.4031  |   0.32686   |   0.0642112  |   0.0726618  |   0.284041   |   0.602327  |
| Qh       | detailed     |  49.8349  |  49.1959  |   1.38585  |   0.961445 |  32.1574  | 137.871   |  67.3804  |   0.505711  |  49.1959  |   0.385855  |   0.0385547  |   0.00758428 |   0.240707   |   0.56556   |
| Qtau     | baseline     | nan       | nan       | nan        | nan        | nan       | nan       | nan       | nan         | nan       | nan         | nan          | nan          | nan          | nan         |
| Qtau     | detailed     | nan       | nan       | nan        | nan        | nan       | nan       | nan       | nan         | nan       | nan         | nan          | nan          | nan          | nan         |
| SoilTemp | baseline     |   3.87847 |  -3.01105 |   0.958087 |   0.968632 |   1.72156 |   3.75891 |   4.45699 |   0.248723  |   3.01105 |   0.0419133 |   0.0313679  |   0.820182   |   0.0245783  |   0.122612  |
| SoilTemp | detailed     |   5.37775 |  -5.13986 |   0.853906 |   0.97284  |   2.39514 |   9.43762 |   6.18388 |   0.260246  |   5.13986 |   0.146094  |   0.0271602  |   2.30546    |   0.096717   |   0.149144  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![TERRA_4.11_US-WestPhoenix_subset_SWup_v0-9.png](TERRA_4.11_US-WestPhoenix_subset_SWup_v0-9.png)](TERRA_4.11_US-WestPhoenix_subset_SWup_v0-9.png)

### out of range: baseline

 - TERRA_4.11 Qh max value of 605.7334 is greater than expected 600.0 [W/m2]
 - TERRA_4.11 SoilTemp max value of 334.3254 is greater than expected 333.0 [K]

### out of range: detailed



[Link to variable definitions](../modelattrs/variable_definitions.md)

