# GR-HECKOR: NOAH-SLUCM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](NOAH-SLUCM_GR-HECKOR_baseline_attrs.md)
- [Detailed](NOAH-SLUCM_GR-HECKOR_detailed_attrs.md)

### Error metrics

| flux   | experiment   |      MAE |       MBE |        nSD |           R |       5th |     95th |     RMSE |      cRMSE |      AMBE |       1-nSD |          1-R |    nSkewness |   nKurtosis |    Overlap |
|:-------|:-------------|---------:|----------:|-----------:|------------:|----------:|---------:|---------:|-----------:|----------:|------------:|-------------:|-------------:|------------:|-----------:|
| SWup   | baseline     |  16.3643 | -16.3518  |   0.885457 |   0.993331  |   2.97379 |  27.5699 |  19.0068 |   0.157896 |  16.3518  |   0.114544  |   0.00666942 |   0.18038    |   0.0678032 |   0.109416 |
| SWup   | detailed     |  13.5361 | -13.5064  |   0.920919 |   0.993327  |   2.91952 |  21.0765 |  15.8824 |   0.136179 |  13.5064  |   0.0790817 |   0.00667311 |   0.181511   |   0.0675903 |   0.107056 |
| LWup   | baseline     |  39.4583 |  39.389   |   1.69976  |   0.937335  |  13.1714  | 112.219  |  53.7597 |   0.838271 |  39.389   |   0.699757  |   0.0626652  |   1.07567    |   0.730046  |   0.142512 |
| LWup   | detailed     |  38.4139 |  37.8445  |   1.7469   |   0.927076  |  10.4044  | 115.764  |  54.5917 |   0.901466 |  37.8445  |   0.746896  |   0.0729239  |   1.14038    |   0.754293  |   0.124114 |
| Qle    | baseline     |  26.0339 | -22.2456  |   0.44289  |   0.139338  |   3.30427 |  74.7506 |  42.9031 |   1.03573  |  22.2456  |   0.55711   |   0.860662   |   7.92132    |  45.0629    |   0.592572 |
| Qle    | detailed     |  26.2152 | -22.0615  |   0.697147 |   0.0906112 |   3.30427 |  74.7268 |  46.8242 |   1.16605  |  22.0615  |   0.302853  |   0.909389   |  17.8618     | 214.241     |   0.592641 |
| Qh     | baseline     |  26.7936 |   1.50027 |   1.15793  |   0.94752   |   2.3424  |  50.6103 |  40.5436 |   0.382722 |   1.50027 |   0.157926  |   0.0524799  |   0.00814036 |   0.49003   |   0.229654 |
| Qh     | detailed     |  29.6837 |   1.96266 |   1.19954  |   0.944831  |   4.82756 |  59.6402 |  43.97   |   0.414936 |   1.96266 |   0.199543  |   0.055169   |   0.0144912  |   0.531988  |   0.283535 |
| Qtau   | baseline     | nan      | nan       | nan        | nan         | nan       | nan      | nan      | nan        | nan       | nan         | nan          | nan          | nan         | nan        |
| Qtau   | detailed     | nan      | nan       | nan        | nan         | nan       | nan      | nan      | nan        | nan       | nan         | nan          | nan          | nan         | nan        |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![NOAH-SLUCM_GR-HECKOR_subset_SWup_v0-9.png](NOAH-SLUCM_GR-HECKOR_subset_SWup_v0-9.png)](NOAH-SLUCM_GR-HECKOR_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed

 - NOAH-SLUCM Qle max value of 1846.2346 is greater than expected 700.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

