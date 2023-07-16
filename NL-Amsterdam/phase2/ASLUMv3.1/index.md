# NL-Amsterdam: ASLUMv3.1

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](ASLUMv3.1_NL-Amsterdam_baseline_attrs.md)
- [Detailed](ASLUMv3.1_NL-Amsterdam_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |        MBE |        nSD |          R |       5th |      95th |      RMSE |      cRMSE |       AMBE |       1-nSD |         1-R |   nSkewness |   nKurtosis |     Overlap |
|:-------|:-------------|----------:|-----------:|-----------:|-----------:|----------:|----------:|----------:|-----------:|-----------:|------------:|------------:|------------:|------------:|------------:|
| SWup   | baseline     |  14.1837  |  14.1261   |   1.43154  |   0.985171 |   1.81536 |  35.3335  |  18.4697  |   0.478212 |  14.1261   |   0.431545  |   0.014829  |   0.0261938 |    0.136906 |   0.119088  |
| SWup   | detailed     |   4.24489 |   3.01599  |   1.05806  |   0.984241 |   1.15688 |   6.30231 |   5.64166 |   0.191618 |   3.01599  |   0.0580575 |   0.0157586 |   0.0378073 |    0.146906 |   0.0874011 |
| LWup   | baseline     |  10.3338  |   5.83445  |   1.18378  |   0.979786 |   8.91144 |  16.6112  |  12.5913  |   0.285717 |   5.83445  |   0.183782  |   0.0202139 |   0.370958  |    0.936386 |   0.143038  |
| LWup   | detailed     |   5.65118 |  -2.11068  |   0.986088 |   0.982323 |   6.55301 |   6.00891 |   7.61051 |   0.187234 |   2.11068  |   0.0139128 |   0.0176774 |   0.432124  |    0.78758  |   0.0651925 |
| Qle    | baseline     |  20.4879  |  -4.92075  |   0.89027  |   0.540147 |   3.75075 |   2.67835 |  32.3758  |   0.911497 |   4.92075  |   0.109731  |   0.459853  |   0.0384505 |    0.735834 |   0.162984  |
| Qle    | detailed     |  21.2071  |  -0.337375 |   1.01723  |   0.52938  |   2.82931 |  13.7082  |  34.3588  |   0.978649 |   0.337375 |   0.0172275 |   0.47062   |   0.0880208 |    0.641488 |   0.152349  |
| Qh     | baseline     |  32.162   |  -6.28942  |   0.868486 |   0.85542  |   4.99973 |  22.6093  |  48.6837  |   0.518099 |   6.28942  |   0.131514  |   0.14458   |   0.502267  |    0.80213  |   0.114946  |
| Qh     | detailed     |  41.6018  |  12.4503   |   1.28364  |   0.827363 |   5.52675 |  73.5295  |  68.568   |   0.723646 |  12.4503   |   0.283645  |   0.172637  |   1.13919   |    0.146375 |   0.158128  |
| Qtau   | baseline     | nan       | nan        | nan        | nan        | nan       | nan       | nan       | nan        | nan        | nan         | nan         | nan         |  nan        | nan         |
| Qtau   | detailed     | nan       | nan        | nan        | nan        | nan       | nan       | nan       | nan        | nan        | nan         | nan         | nan         |  nan        | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![ASLUMv3.1_NL-Amsterdam_subset_SWup_v0-9.png](ASLUMv3.1_NL-Amsterdam_subset_SWup_v0-9.png)](ASLUMv3.1_NL-Amsterdam_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed

 - ASLUMv3.1 Qstor min value of -827.1765 is less than expected -800.0 [W/m2]
 - ASLUMv3.1 Qh max value of 1084.1715 is greater than expected 600.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

