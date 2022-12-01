# AU-Preston: NOAH-SLUCM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](NOAH-SLUCM_AU-Preston_baseline_attrs.md)
- [Detailed](NOAH-SLUCM_AU-Preston_detailed_attrs.md)

### Error metrics

| flux   | experiment   |        MAE |         MBE |        nSD |          R |         5th |       95th |       RMSE |       cRMSE |        AMBE |        1-nSD |          1-R |   nSkewness |     nKurtosis |     Overlap |
|:-------|:-------------|-----------:|------------:|-----------:|-----------:|------------:|-----------:|-----------:|------------:|------------:|-------------:|-------------:|------------:|--------------:|------------:|
| SWup   | G11          |   3.29388  |  -2.12904   |   0.962856 |   0.996031 |   0.56647   |   5.31445  |   4.90843  |   0.0949844 |   2.12904   |   0.0371436  |   0.0039686  |   0.0295287 |   0.0636547   |   0.0720179 |
| SWup   | baseline     |  10.0663   |   9.71904   |   1.203    |   0.996569 |   0.344674  |  30.0731   |  14.2067   |   0.222399  |   9.71904   |   0.202997   |   0.00343053 |   0.0442265 |   0.0788223   |   0.0836262 |
| SWup   | detailed     |   3.52561  |   1.97305   |   1.05984  |   0.996489 |   0.518706  |   9.1272   |   5.27463  |   0.104991  |   1.97305   |   0.0598445  |   0.00351074 |   0.048404  |   0.0859741   |   0.0724846 |
| LWup   | G11          |  11.2795   |  11.0937    |   0.986332 |   0.990132 |   8.70987   |   8.93866  |  12.5602   |   0.14019   |  11.0937    |   0.0136681  |   0.00986814 |   0.1213    |   0.30761     |   0.148422  |
| LWup   | baseline     |  20.7121   |  20.328     |   1.36124  |   0.982771 |   2.31772   |  55.0172   |  26.9564   |   0.421188  |  20.328     |   0.361241   |   0.0172287  |   0.0182068 |   0.0710259   |   0.153249  |
| LWup   | detailed     |  22.9023   |  22.4394    |   1.44104  |   0.97848  |   2.19922   |  66.76     |  30.9317   |   0.506499  |  22.4394    |   0.441042   |   0.0215203  |   0.0634005 |   6.28085e-05 |   0.151664  |
| Qle    | G11          |  23.9056   | -15.1999    |   0.490494 |   0.637354 |   8.12578   |  62.5605   |  41.2368   |   0.784441  |  15.1999    |   0.509506   |   0.362646   |   0.105021  |   0.26887     |   0.26945   |
| Qle    | baseline     |  23.729    | -15.0102    |   0.467829 |   0.621029 |   8.92495   |  62.5817   |  41.8037   |   0.798619  |  15.0102    |   0.532171   |   0.378971   |   0.0828305 |   0.305269    |   0.253324  |
| Qle    | detailed     |  23.7371   | -14.9899    |   0.468925 |   0.620068 |   8.92213   |  62.5817   |  41.8126   |   0.798974  |  14.9899    |   0.531075   |   0.379932   |   0.0895095 |   0.287079    |   0.257058  |
| Qh     | G11          |  35.0245   |  20.8391    |   0.993046 |   0.895221 |  14.1854    |   9.31552  |  46.7213   |   0.456233  |  20.8391    |   0.00695422 |   0.104779   |   0.016765  |   0.0492651   |   0.296767  |
| Qh     | baseline     |  19.0339   |   6.61051   |   1.12257  |   0.95468  |   3.91318   |  40.7001   |  32.0009   |   0.341722  |   6.61051   |   0.122568   |   0.0453205  |   0.0353684 |   0.0242682   |   0.104302  |
| Qh     | detailed     |  19.5054   |   5.24904   |   1.15319  |   0.955984 |   0.158249  |  46.9987   |  32.8153   |   0.353531  |   5.24904   |   0.15319    |   0.0440158  |   0.0257939 |   0.0528507   |   0.146409  |
| Qtau   | G11          |   0.122575 |  -0.0995477 |   0.535597 |   0.875952 |   0.0054204 |   0.409426 |   0.208393 |   0.590381  |   0.0995477 |   0.464403   |   0.124048   |   0.11066   |   0.20481     |   0.176056  |
| Qtau   | baseline     | nan        | nan         | nan        | nan        | nan         | nan        | nan        | nan         | nan         | nan          | nan          | nan         | nan           | nan         |
| Qtau   | detailed     | nan        | nan         | nan        | nan        | nan         | nan        | nan        | nan         | nan         | nan          | nan          | nan         | nan           | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="albedo"></a>Albedo
[![NOAH-SLUCM_AU-Preston_Albedo.png](NOAH-SLUCM_AU-Preston_Albedo.png)](NOAH-SLUCM_AU-Preston_Albedo.png)

### <a name="datasheet"></a>Datasheet
[![NOAH-SLUCM_AU-Preston_Datasheet.png](NOAH-SLUCM_AU-Preston_Datasheet.png)](NOAH-SLUCM_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![NOAH-SLUCM_AU-Preston_Distributions.png](NOAH-SLUCM_AU-Preston_Distributions.png)](NOAH-SLUCM_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![NOAH-SLUCM_AU-Preston_closure_baseline.png](NOAH-SLUCM_AU-Preston_closure_baseline.png)](NOAH-SLUCM_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![NOAH-SLUCM_AU-Preston_closure_detailed.png](NOAH-SLUCM_AU-Preston_closure_detailed.png)](NOAH-SLUCM_AU-Preston_closure_detailed.png)

### <a name="subset_qh"></a>subset_Qh
[![NOAH-SLUCM_AU-Preston_subset_Qh.png](NOAH-SLUCM_AU-Preston_subset_Qh.png)](NOAH-SLUCM_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![NOAH-SLUCM_AU-Preston_subset_Qle.png](NOAH-SLUCM_AU-Preston_subset_Qle.png)](NOAH-SLUCM_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![NOAH-SLUCM_AU-Preston_subset_SWup.png](NOAH-SLUCM_AU-Preston_subset_SWup.png)](NOAH-SLUCM_AU-Preston_subset_SWup.png)

### out of range: baseline


### out of range: detailed



[Link to variable definitions](../modelattrs/variable_definitions.md)

