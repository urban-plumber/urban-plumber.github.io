# SG-TelokKurau: UCLEM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](UCLEM_SG-TelokKurau_baseline_attrs.md)
- [Detailed](UCLEM_SG-TelokKurau_detailed_attrs.md)

### Error metrics

| flux     | experiment   |         MAE |         MBE |        nSD |          R |           5th |       95th |        RMSE |      cRMSE |        AMBE |       1-nSD |         1-R |    nSkewness |     nKurtosis |    Overlap |
|:---------|:-------------|------------:|------------:|-----------:|-----------:|--------------:|-----------:|------------:|-----------:|------------:|------------:|------------:|-------------:|--------------:|-----------:|
| SWup     | baseline     |   7.18474   |  -6.2448    |   0.929681 |   0.988034 |   1.86781     |  11.4058   |   9.78062   |   0.164903 |   6.2448    |   0.0703191 |   0.0119656 |   0.0371205  |   0.0173609   |   0.118554 |
| SWup     | detailed     |  10.7051    | -10.5078    |   0.857963 |   0.987214 |   1.95561     |  21.7661   |  14.0772    |   0.205218 |  10.5078    |   0.142037  |   0.0127862 |   0.00228881 |   0.000367257 |   0.135936 |
| LWup     | baseline     |  34.3496    |  34.1       |   2.09914  |   0.924588 |   5.6709      |  84.0748   |  43.6239    |   1.23479  |  34.1       |   1.09914   |   0.0754117 |   0.106343   |   1.01625     |   0.358795 |
| LWup     | detailed     |  25.2847    |  24.6541    |   2.02868  |   0.94723  |   2.1969      |  71.2782   |  35.0074    |   1.12796  |  24.6541    |   1.02868   |   0.0527701 |   0.0666858  |   1.10088     |   0.212331 |
| Qle      | baseline     |  23.9295    | -12.1359    |   0.918235 |   0.538285 |   3.0866      |  54.4569   |  44.5869    |   0.924452 |  12.1359    |   0.0817646 |   0.461715  |   2.91128    |  21.5885      |   0.317094 |
| Qle      | detailed     |  25.085     | -13.3325    |   0.954179 |   0.493154 |   2.9837      |  62.0022   |  47.5982    |   0.984552 |  13.3325    |   0.0458213 |   0.506846  |   3.33725    |  23.0342      |   0.342015 |
| Qh       | baseline     |  31.6657    |   0.773144  |   0.751174 |   0.874806 |  14.128       |  46.7855   |  43.5715    |   0.499999 |   0.773144  |   0.248826  |   0.125194  |   0.00897791 |   0.0361304   |   0.415181 |
| Qh       | detailed     |  31.764     |  16.007     |   0.888915 |   0.913718 |  19.9517      |   3.3383   |  38.9154    |   0.407106 |  16.007     |   0.111085  |   0.0862824 |   0.0018891  |   0.0249657   |   0.462861 |
| Qtau     | baseline     |   0.0471078 |  -0.0282573 |   0.806626 |   0.766178 |   0.00781394  |   0.107581 |   0.0911537 |   0.6439   |   0.0282573 |   0.193374  |   0.233822  |   5.42554    | 104.37        |   0.133971 |
| Qtau     | detailed     |   0.0539323 |  -0.0423581 |   0.794491 |   0.737928 |   0.000413944 |   0.130981 |   0.100513  |   0.677245 |   0.0423581 |   0.205509  |   0.262072  |   5.77078    | 103.071       |   0.146145 |
| TairSurf | baseline     |   0.714733  |   0.512158  |   0.937318 |   0.923486 |   0.42017     |   0.28147  |   0.908184  |   0.383881 |   0.512158  |   0.0626822 |   0.076514  |   0.697554   |   0.75899     |   0.209662 |
| TairSurf | detailed     |   0.805884  |   0.581521  |   0.905404 |   0.893618 |   0.44667     |   0.10207  |   1.05243   |   0.448982 |   0.581521  |   0.0945962 |   0.106382  |   1.19173    |   1.04566     |   0.240045 |
| SoilTemp | baseline     | nan         | nan         | nan        | nan        | nan           | nan        | nan         | nan        | nan         | nan         | nan         | nan          | nan           | nan        |
| SoilTemp | detailed     | nan         | nan         | nan        | nan        | nan           | nan        | nan         | nan        | nan         | nan         | nan         | nan          | nan           | nan        |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![UCLEM_SG-TelokKurau_subset_SWup_v0-9.png](UCLEM_SG-TelokKurau_subset_SWup_v0-9.png)](UCLEM_SG-TelokKurau_subset_SWup_v0-9.png)

### out of range: baseline

 - UCLEM Qstor min value of -1281.1068 is less than expected -800.0 [W/m2]
 - UCLEM Qle max value of 1677.5171 is greater than expected 700.0 [W/m2]

### out of range: detailed

 - UCLEM Qstor min value of -1431.0411 is less than expected -800.0 [W/m2]
 - UCLEM Qle max value of 2314.1377 is greater than expected 700.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

