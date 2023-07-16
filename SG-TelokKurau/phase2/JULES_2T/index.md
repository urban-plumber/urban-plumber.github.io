# SG-TelokKurau: JULES_2T

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](JULES_2T_SG-TelokKurau_baseline_attrs.md)
- [Detailed](JULES_2T_SG-TelokKurau_detailed_attrs.md)

### Error metrics

| flux     | experiment   |        MAE |         MBE |      nSD |        R |         5th |       95th |       RMSE |    cRMSE |       AMBE |      1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:---------|:-------------|-----------:|------------:|---------:|---------:|------------:|-----------:|-----------:|---------:|-----------:|-----------:|-----------:|------------:|------------:|----------:|
| SWup     | baseline     |  7.05019   |   4.90689   | 1.12439  | 0.992164 | 1.58578     | 16.4426    |  9.64547   | 0.181916 |  4.90689   | 0.124386   | 0.00783601 |   0.169671  |   0.067229  | 0.131631  |
| SWup     | detailed     |  4.84987   |   1.08886   | 1.06109  | 0.992164 | 1.67122     |  7.5756    |  6.60394   | 0.142691 |  1.08886   | 0.0610855  | 0.00783601 |   0.169671  |   0.067229  | 0.102889  |
| LWup     | baseline     | 25.407     |  25.1245    | 2.04515  | 0.944339 | 1.46992     | 69.9323    | 35.6669    | 1.14892  | 25.1245    | 1.04515    | 0.0556609  |   0.171185  |   1.82824   | 0.172948  |
| LWup     | detailed     | 26.2515    |  25.6113    | 2.22298  | 0.963801 | 0.24364     | 78.938     | 38.2132    | 1.2871   | 25.6113    | 1.22298    | 0.0361991  |   0.124013  |   1.64754   | 0.149205  |
| Qle      | baseline     | 19.2233    | -12.0976    | 0.570174 | 0.740679 | 3.35712     | 66.9716    | 34.3694    | 0.693157 | 12.0976    | 0.429826   | 0.259321   |   0.0468942 |   0.367428  | 0.361565  |
| Qle      | detailed     | 19.7981    | -13.3245    | 0.550406 | 0.732052 | 3.53985     | 70.9081    | 35.3308    | 0.70505  | 13.3245    | 0.449594   | 0.267948   |   0.0362711 |   0.665742  | 0.381109  |
| Qh       | baseline     | 29.6999    |  -1.19909   | 0.879153 | 0.857687 | 3.18728     | 25.9926    | 44.8556    | 0.51462  |  1.19909   | 0.120847   | 0.142313   |   0.0426879 |   0.0704325 | 0.120029  |
| Qh       | detailed     | 25.6881    |   1.85025   | 0.967446 | 0.893693 | 1.40408     |  4.49619   | 39.6619    | 0.4547   |  1.85025   | 0.0325539  | 0.106307   |   0.0376884 |   0.0952307 | 0.0898296 |
| Qtau     | baseline     |  0.0466657 |  -0.0268501 | 0.823115 | 0.867989 | 0.0013984   |  0.0747712 |  0.0722803 | 0.498608 |  0.0268501 | 0.176885   | 0.132011   |   0.0747643 |   0.138784  | 0.0906654 |
| Qtau     | detailed     |  0.0441884 |  -0.0198107 | 0.870432 | 0.871248 | 0.000169181 |  0.0576604 |  0.0689697 | 0.490844 |  0.0198107 | 0.129568   | 0.128752   |   0.0602563 |   0.0677221 | 0.0653411 |
| TairSurf | baseline     |  0.369683  |  -0.237906  | 0.993565 | 0.977798 | 0.21781     |  0.26781   |  0.474516  | 0.210143 |  0.237906  | 0.00643507 | 0.0222023  |   0.122902  |   0.0729576 | 0.0739202 |
| TairSurf | detailed     |  0.404217  |  -0.343045  | 0.992567 | 0.981585 | 0.33078     |  0.37486   |  0.507374  | 0.191339 |  0.343045  | 0.00743265 | 0.0184146  |   0.124598  |   0.0759015 | 0.0926011 |
| SoilTemp | baseline     |  3.60527   |   2.24184   | 0.301701 | 0.171113 | 4.16995     |  3.23918   |  3.98942   | 0.993868 |  2.24184   | 0.698299   | 0.828887   |   1.32894   |   1.20283   | 0.716573  |
| SoilTemp | detailed     |  3.61098   |   2.24905   | 0.311785 | 0.173435 | 4.11683     |  3.17482   |  3.99526   | 0.994515 |  2.24905   | 0.688215   | 0.826565   |   1.3363    |   1.14809   | 0.711586  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![JULES_2T_SG-TelokKurau_subset_SWup_v0-9.png](JULES_2T_SG-TelokKurau_subset_SWup_v0-9.png)](JULES_2T_SG-TelokKurau_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed



[Link to variable definitions](../modelattrs/variable_definitions.md)

