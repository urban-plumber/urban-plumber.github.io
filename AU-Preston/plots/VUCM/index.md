# AU-Preston: VUCM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](VUCM_AU-Preston_baseline_attrs.md)
- [Detailed](VUCM_AU-Preston_detailed_attrs.md)

### Error metrics

| flux   | experiment   |        MAE |         MBE |        nSD |          R |       5th |      95th |       RMSE |       cRMSE |        AMBE |        1-nSD |          1-R |   nSkewness |   nKurtosis |     Overlap |
|:-------|:-------------|-----------:|------------:|-----------:|-----------:|----------:|----------:|-----------:|------------:|------------:|-------------:|-------------:|------------:|------------:|------------:|
| SWup   | G11          |   3.28295  |  -0.050805  |   0.988543 |   0.994918 |   0.44    |   2.45999 |   4.69791  |   0.10089   |   0.050805  |   0.0114572  |   0.00508199 |   0.0626712 |    0.119357 |   0.0697095 |
| SWup   | baseline     |   5.878    |  -5.57222   |   0.885328 |   0.996144 |   0.582   |  17.51    |   8.62647  |   0.141341  |   5.57222   |   0.114672   |   0.0038559  |   0.09622   |    0.201    |   0.0740256 |
| SWup   | detailed     |   3.41917  |  -1.79549   |   0.950624 |   0.996099 |   0.477   |   7.841   |   4.96164  |   0.0992746 |   1.79549   |   0.0493759  |   0.00390137 |   0.0967764 |    0.193395 |   0.0777629 |
| LWup   | G11          |  17.1367   |   2.73229   |   1.45874  |   0.961816 |  17.26    |  49.72    |  23.99     |   0.567315  |   2.73229   |   0.458742   |   0.0381844  |   0.132128  |    0.193084 |   0.166977  |
| LWup   | baseline     |   7.92572  |  -0.277623  |   0.873969 |   0.980203 |   8.41599 |   7.95899 |   9.44889  |   0.224695  |   0.277623  |   0.126031   |   0.0197969  |   0.189722  |    0.55766  |   0.122634  |
| LWup   | detailed     |  14.4796   | -12.995     |   0.850984 |   0.966079 |   2.56801 |  21.911   |  17.6099   |   0.282735  |  12.995     |   0.149016   |   0.0339215  |   0.257687  |    0.779391 |   0.169468  |
| Qle    | G11          |  26.2157   |  -1.08217   |   1.0123   |   0.577153 |  10.26    |  15.3     |  45.2315   |   0.925339  |   1.08217   |   0.0123048  |   0.422847   |   0.527365  |    0.511782 |   0.209282  |
| Qle    | baseline     |  28.0358   |   2.09634   |   0.894187 |   0.511609 |   9.362   |   3.269   |  45.9973   |   0.940543  |   2.09634   |   0.105813   |   0.488391   |   0.414392  |    0.513855 |   0.142918  |
| Qle    | detailed     |  28.2035   |   1.638     |   0.885845 |   0.49843  |   9.412   |   6.156   |  46.4188   |   0.949556  |   1.638     |   0.114155   |   0.50157    |   0.411512  |    0.483242 |   0.145829  |
| Qh     | G11          |  25.6035   |   9.10962   |   1.22832  |   0.924546 |   3.28    |  56.23    |  45.5867   |   0.487336  |   9.10962   |   0.228323   |   0.0754544  |   0.0971725 |    0.200232 |   0.0708248 |
| Qh     | baseline     |  25.8775   |   6.80927   |   1.00371  |   0.91456  |   0.784   |   1.95    |  38.554    |   0.41416   |   6.80927   |   0.00370793 |   0.0854404  |   0.0239363 |    0.207877 |   0.205931  |
| Qh     | detailed     |  24.5159   |   8.07544   |   0.98661  |   0.921983 |   8.317   |   2.662   |  36.8666   |   0.392586  |   8.07544   |   0.0133901  |   0.0780169  |   0.0736408 |    0.256911 |   0.217409  |
| Qtau   | G11          |   0.109989 |   0.0158036 |   0.897465 |   0.845465 |   0.003   |   0.064   |   0.167136 |   0.536556  |   0.0158036 |   0.102535   |   0.154535   |   0.210977  |    0.395504 |   0.092127  |
| Qtau   | baseline     | nan        | nan         | nan        | nan        | nan       | nan       | nan        | nan         | nan         | nan          | nan          | nan         |  nan        | nan         |
| Qtau   | detailed     | nan        | nan         | nan        | nan        | nan       | nan       | nan        | nan         | nan         | nan          | nan          | nan         |  nan        | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="albedo"></a>Albedo
[![VUCM_AU-Preston_Albedo.png](VUCM_AU-Preston_Albedo.png)](VUCM_AU-Preston_Albedo.png)

### <a name="datasheet"></a>Datasheet
[![VUCM_AU-Preston_Datasheet.png](VUCM_AU-Preston_Datasheet.png)](VUCM_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![VUCM_AU-Preston_Distributions.png](VUCM_AU-Preston_Distributions.png)](VUCM_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![VUCM_AU-Preston_closure_baseline.png](VUCM_AU-Preston_closure_baseline.png)](VUCM_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![VUCM_AU-Preston_closure_detailed.png](VUCM_AU-Preston_closure_detailed.png)](VUCM_AU-Preston_closure_detailed.png)

### <a name="subset_qh"></a>subset_Qh
[![VUCM_AU-Preston_subset_Qh.png](VUCM_AU-Preston_subset_Qh.png)](VUCM_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![VUCM_AU-Preston_subset_Qle.png](VUCM_AU-Preston_subset_Qle.png)](VUCM_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![VUCM_AU-Preston_subset_SWup.png](VUCM_AU-Preston_subset_SWup.png)](VUCM_AU-Preston_subset_SWup.png)

### out of range: baseline

 - VUCM SWup min value of -0.3180 is less than expected 0.0 [W/m2]
 - VUCM Qh max value of 606.7470 is greater than expected 600.0 [W/m2]

### out of range: detailed

 - VUCM SWup min value of -0.3140 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

