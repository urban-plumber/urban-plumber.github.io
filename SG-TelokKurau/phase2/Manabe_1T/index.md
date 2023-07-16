# SG-TelokKurau: Manabe_1T

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](Manabe_1T_SG-TelokKurau_baseline_attrs.md)
- [Detailed](Manabe_1T_SG-TelokKurau_detailed_attrs.md)

### Error metrics

| flux     | experiment   |        MAE |         MBE |      nSD |        R |        5th |      95th |       RMSE |    cRMSE |       AMBE |     1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:---------|:-------------|-----------:|------------:|---------:|---------:|-----------:|----------:|-----------:|---------:|-----------:|----------:|-----------:|------------:|------------:|----------:|
| SWup     | baseline     |  5.66898   |   2.7809    | 1.08914  | 0.992164 | 1.63336    | 11.5052   |  7.73674   | 0.15816  |  2.7809    | 0.0891385 | 0.00783601 |   0.169671  |   0.067229  | 0.116001  |
| SWup     | detailed     |  4.33215   |  -1.03713   | 1.02584  | 0.992164 | 1.7188     |  2.63817  |  5.99723   | 0.129401 |  1.03713   | 0.025838  | 0.00783601 |   0.169671  |   0.067229  | 0.0918284 |
| LWup     | baseline     | 30.3012    |  30.2221    | 1.97243  | 0.879664 | 5.04976    | 70.8421   | 40.0371    | 1.19177  | 30.2221    | 0.972429  | 0.120336   |   0.227361  |   1.86465   | 0.289989  |
| LWup     | detailed     | 30.5283    |  30.4157    | 2.00535  | 0.879502 | 4.47206    | 72.614    | 40.626     | 1.22229  | 30.4157    | 1.00535   | 0.120498   |   0.225658  |   1.84605   | 0.279657  |
| Qle      | baseline     | 23.8984    | -16.8184    | 0.451351 | 0.622419 | 4.65988    | 70.2141   | 40.8093    | 0.801161 | 16.8184    | 0.548649  | 0.377581   |   0.526186  |   1.83649   | 0.3073    |
| Qle      | detailed     | 23.7641    | -16.7279    | 0.461451 | 0.625336 | 4.48628    | 68.7702   | 40.612     | 0.797379 | 16.7279    | 0.538549  | 0.374664   |   0.498985  |   1.70114   | 0.296773  |
| Qh       | baseline     | 42.0914    |  -1.72212   | 0.7681   | 0.724919 | 5.41085    | 52.6349   | 60.1616    | 0.690186 |  1.72212   | 0.2319    | 0.275081   |   0.107691  |   0.259566  | 0.22814   |
| Qh       | detailed     | 42.2027    |  -0.0787389 | 0.787075 | 0.729078 | 5.24733    | 47.6833   | 59.8493    | 0.686884 |  0.0787389 | 0.212925  | 0.270922   |   0.109656  |   0.258498  | 0.228805  |
| Qtau     | baseline     |  0.0504161 |  -0.0347103 | 0.699072 | 0.856817 | 0.00554014 |  0.116116 |  0.0804466 | 0.539211 |  0.0347103 | 0.300928  | 0.143183   |   0.0753878 |   0.0798245 | 0.140061  |
| Qtau     | detailed     |  0.0482113 |  -0.0304439 | 0.719989 | 0.858949 | 0.00661567 |  0.108389 |  0.0776302 | 0.530582 |  0.0304439 | 0.280011  | 0.141051   |   0.0431108 |   0.0239184 | 0.131587  |
| TairSurf | baseline     |  0.414154  |  -0.0541359 | 0.941901 | 0.963885 | 0.04297    |  0.28133  |  0.524893  | 0.267226 |  0.0541359 | 0.0580988 | 0.0361154  |   0.26185   |   0.0918272 | 0.0700548 |
| TairSurf | detailed     |  0.418688  |  -0.166759  | 0.926794 | 0.964494 | 0.04016    |  0.4463   |  0.547253  | 0.266782 |  0.166759  | 0.0732059 | 0.035506   |   0.29212   |   0.10096   | 0.0755038 |
| SoilTemp | baseline     |  4.10342   |   3.05838   | 0.477154 | 0.17895  | 3.83859    |  1.6263   |  4.58317   | 1.02806  |  3.05838   | 0.522846  | 0.82105    |   1.37741   |   1.66939   | 0.653266  |
| SoilTemp | detailed     |  4.09947   |   3.04635   | 0.485146 | 0.178567 | 3.76929    |  1.58351  |  4.58141   | 1.03058  |  3.04635   | 0.514854  | 0.821433   |   1.37786   |   1.63431   | 0.64849   |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![Manabe_1T_SG-TelokKurau_subset_SWup_v0-9.png](Manabe_1T_SG-TelokKurau_subset_SWup_v0-9.png)](Manabe_1T_SG-TelokKurau_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed



[Link to variable definitions](../modelattrs/variable_definitions.md)

