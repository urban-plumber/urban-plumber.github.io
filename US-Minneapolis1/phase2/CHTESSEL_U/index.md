# US-Minneapolis1: CHTESSEL_U

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](CHTESSEL_U_US-Minneapolis1_baseline_attrs.md)
- [Detailed](CHTESSEL_U_US-Minneapolis1_detailed_attrs.md)

### Error metrics

| flux     | experiment   |       MAE |         MBE |      nSD |          R |       5th |       95th |      RMSE |      cRMSE |       AMBE |      1-nSD |         1-R |   nSkewness |   nKurtosis |   Overlap |
|:---------|:-------------|----------:|------------:|---------:|-----------:|----------:|-----------:|----------:|-----------:|-----------:|-----------:|------------:|------------:|------------:|----------:|
| SWup     | baseline     | 38.307    | -35.4519    | 0.627788 |   0.922557 | 1.5408    | 123.466    | 58.889    |   0.485569 | 35.4519    | 0.372213   |   0.0774431 |    0.159972 |    0.320863 | 0.181471  |
| SWup     | detailed     | 38.307    | -35.4519    | 0.627788 |   0.922557 | 1.5408    | 123.466    | 58.889    |   0.485569 | 35.4519    | 0.372213   |   0.0774431 |    0.159972 |    0.320863 | 0.181471  |
| LWup     | baseline     |  8.89955  |  -1.21507   | 0.978674 |   0.985684 | 0.111374  |   7.06183  | 12.2952   |   0.168752 |  1.21507   | 0.0213273  |   0.0143165 |    0.531587 |    0.37118  | 0.0553542 |
| LWup     | detailed     |  8.89955  |  -1.21507   | 0.978674 |   0.985684 | 0.111374  |   7.06183  | 12.2952   |   0.168752 |  1.21507   | 0.0213273  |   0.0143165 |    0.531587 |    0.37118  | 0.0553542 |
| Qle      | baseline     | 17.5818   |  -0.0799993 | 0.881843 |   0.809197 | 2.02542   |  10.287    | 32.8808   |   0.592012 |  0.0799993 | 0.118157   |   0.190803  |    0.178431 |    0.430602 | 0.0574502 |
| Qle      | detailed     | 17.5818   |  -0.0799993 | 0.881843 |   0.809197 | 2.02542   |  10.287    | 32.8808   |   0.592012 |  0.0799993 | 0.118157   |   0.190803  |    0.178431 |    0.430602 | 0.0574502 |
| Qh       | baseline     | 30.3131   |  10.976     | 1.28839  |   0.903783 | 8.88469   |  70.3935   | 49.5738   |   0.575415 | 10.976     | 0.288393   |   0.0962171 |    0.166789 |    0.41891  | 0.162371  |
| Qh       | detailed     | 30.3131   |  10.976     | 1.28839  |   0.903783 | 8.88469   |  70.3935   | 49.5738   |   0.575415 | 10.976     | 0.288393   |   0.0962171 |    0.166789 |    0.41891  | 0.162371  |
| Qg       | baseline     | 18.2556   |  -0.783866  | 0.996835 |   0.801643 | 9.807     |  12.1278   | 28.09     |   0.628862 |  0.783866  | 0.00317176 |   0.198357  |    0.430804 |    0.677511 | 0.127003  |
| Qg       | detailed     | 18.2556   |  -0.783866  | 0.996835 |   0.801643 | 9.807     |  12.1278   | 28.09     |   0.628862 |  0.783866  | 0.00317176 |   0.198357  |    0.430804 |    0.677511 | 0.127003  |
| Qtau     | baseline     |  0.245268 |  -0.245268  | 0        | nan        | 0.0077152 |   0.7076   |  0.337496 | nan        |  0.245268  | 1          | nan         |    1        |    1        | 0.931053  |
| Qtau     | detailed     |  0.245268 |  -0.245268  | 0        | nan        | 0.0077152 |   0.7076   |  0.337496 | nan        |  0.245268  | 1          | nan         |    1        |    1        | 0.931053  |
| SoilTemp | baseline     |  2.68089  |  -2.00082   | 1.02751  |   0.973546 | 0.874756  |   0.141296 |  3.1853   |   0.23478  |  2.00082   | 0.0275171  |   0.0264544 |    4.50469  |    0.115819 | 0.197464  |
| SoilTemp | detailed     |  2.68089  |  -2.00082   | 1.02751  |   0.973546 | 0.874756  |   0.141296 |  3.1853   |   0.23478  |  2.00082   | 0.0275171  |   0.0264544 |    4.50469  |    0.115819 | 0.197464  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![CHTESSEL_U_US-Minneapolis1_subset_SWup_v0-9.png](CHTESSEL_U_US-Minneapolis1_subset_SWup_v0-9.png)](CHTESSEL_U_US-Minneapolis1_subset_SWup_v0-9.png)

### out of range: baseline

 - CHTESSEL_U Qh min value of -939.9433 is less than expected -600.0 [W/m2]
 - CHTESSEL_U Qg max value of 540.7734 is greater than expected 500.0 [W/m2]
 - CHTESSEL_U Qle max value of 974.3456 is greater than expected 700.0 [W/m2]

### out of range: detailed

 - CHTESSEL_U Qh min value of -939.9433 is less than expected -600.0 [W/m2]
 - CHTESSEL_U Qg max value of 540.7734 is greater than expected 500.0 [W/m2]
 - CHTESSEL_U Qle max value of 974.3456 is greater than expected 700.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

