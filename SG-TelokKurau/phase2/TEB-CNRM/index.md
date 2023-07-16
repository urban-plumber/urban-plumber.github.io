# SG-TelokKurau: TEB-CNRM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](TEB-CNRM_SG-TelokKurau_baseline_attrs.md)
- [Detailed](TEB-CNRM_SG-TelokKurau_detailed_attrs.md)

### Error metrics

| flux     | experiment   |        MAE |         MBE |      nSD |        R |         5th |        95th |       RMSE |    cRMSE |       AMBE |     1-nSD |       1-R |   nSkewness |   nKurtosis |   Overlap |
|:---------|:-------------|-----------:|------------:|---------:|---------:|------------:|------------:|-----------:|---------:|-----------:|----------:|----------:|------------:|------------:|----------:|
| SWup     | baseline     | 22.2824    | -22.2571    | 0.675045 | 0.987966 |  3.10341    |  47.2532    | 27.3727    | 0.349061 | 22.2571    | 0.324955  | 0.0120343 | 0.000937838 |   0.0323427 | 0.163706  |
| SWup     | detailed     | 13.5569    | -13.3764    | 0.819638 | 0.98652  |  3.10341    |  27.59      | 17.1102    | 0.233726 | 13.3764    | 0.180362  | 0.01348   | 0.0433468   |   0.0240998 | 0.163877  |
| LWup     | baseline     | 27.958     |  23.3298    | 2.67698  | 0.968999 |  7.65826    | 104.406     | 44.6115    | 1.72576  | 23.3298    | 1.67698   | 0.0310009 | 0.044863    |   0.793819  | 0.239417  |
| LWup     | detailed     | 18.9426    |  18.9292    | 1.58983  | 0.973647 |  6.61697    |  47.8635    | 23.8306    | 0.657034 | 18.9292    | 0.589832  | 0.0263527 | 0.00191548  |   0.717085  | 0.302574  |
| Qle      | baseline     | 26.0268    | -14.5885    | 0.84575  | 0.518863 |  2.62402    |  45.9552    | 44.9108    | 0.915225 | 14.5885    | 0.15425   | 0.481137  | 1.24537     |   4.28334   | 0.283377  |
| Qle      | detailed     | 21.9202    | -11.7245    | 0.813913 | 0.65681  |  1.84028    |  39.2626    | 37.6206    | 0.770248 | 11.7245    | 0.186087  | 0.34319   | 0.686144    |   2.4334    | 0.313544  |
| Qh       | baseline     | 43.1304    |  41.0879    | 1.28986  | 0.944953 | 22.148      | 103.698     | 58.3447    | 0.475423 | 41.0879    | 0.289863  | 0.0550473 | 0.044795    |   0.302544  | 0.498088  |
| Qh       | detailed     | 28.0182    |  18.5643    | 0.975862 | 0.9329   | 16.1543     |  15.8302    | 36.6504    | 0.36269  | 18.5643    | 0.0241382 | 0.0671003 | 0.0502208   |   0.234439  | 0.41713   |
| Qtau     | baseline     |  0.0546448 |  -0.0480391 | 0.632751 | 0.875878 |  0.00497215 |   0.149356  |  0.087157  | 0.540323 |  0.0480391 | 0.367249  | 0.124122  | 0.0956981   |   0.414101  | 0.197727  |
| Qtau     | detailed     |  0.0633622 |   0.0484951 | 1.14006  | 0.875769 |  0.0193158  |   0.0741842 |  0.0885344 | 0.550343 |  0.0484951 | 0.140058  | 0.124231  | 0.105291    |   0.10384   | 0.14637   |
| TairSurf | baseline     |  0.37381   |   0.224493  | 1.06354  | 0.978275 |  0.188081   |   0.645637  |  0.492137  | 0.224164 |  0.224493  | 0.063543  | 0.0217253 | 0.308313    |   0.340759  | 0.0905152 |
| TairSurf | detailed     |  0.312065  |   0.0102284 | 0.937416 | 0.977814 |  0.199023   |   0.116893  |  0.41692   | 0.213334 |  0.0102284 | 0.0625841 | 0.0221858 | 0.0350776   |   0.313704  | 0.0783657 |
| SoilTemp | baseline     |  1.29453   |  -1.14418   | 1.01652  | 0.945343 |  1.31909    |   0.955394  |  1.59284   | 0.333754 |  1.14418   | 0.0165168 | 0.0546567 | 0.0872202   |   0.294465  | 0.213149  |
| SoilTemp | detailed     |  1.76531   |  -1.73572   | 0.839025 | 0.931245 |  1.56558    |   3.00163   |  2.13782   | 0.375882 |  1.73572   | 0.160975  | 0.0687547 | 0.269128    |   0.715065  | 0.24655   |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![TEB-CNRM_SG-TelokKurau_subset_SWup_v0-9.png](TEB-CNRM_SG-TelokKurau_subset_SWup_v0-9.png)](TEB-CNRM_SG-TelokKurau_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed



[Link to variable definitions](../modelattrs/variable_definitions.md)

