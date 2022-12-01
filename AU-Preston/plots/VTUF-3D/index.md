# AU-Preston: VTUF-3D

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](VTUF-3D_AU-Preston_baseline_attrs.md)
- [Detailed](VTUF-3D_AU-Preston_detailed_attrs.md)

### Error metrics

| flux   | experiment   |        MAE |         MBE |        nSD |          R |       5th |     95th |       RMSE |      cRMSE |        AMBE |       1-nSD |          1-R |    nSkewness |   nKurtosis |     Overlap |
|:-------|:-------------|-----------:|------------:|-----------:|-----------:|----------:|---------:|-----------:|-----------:|------------:|------------:|-------------:|-------------:|------------:|------------:|
| SWup   | G11          |   4.6437   |  -3.11195   |   0.914094 |   0.99437  |   0.12    |  12.41   |   6.9282   |   0.132941 |   3.11195   |   0.0859065 |   0.00563034 |   0.101167   |   0.167694  |   0.0676303 |
| SWup   | baseline     |  20.0933   | -20.0931    |   0.623388 |   0.996174 |   0.80253 |  54.4936 |  26.8667   |   0.382892 |  20.0931    |   0.376612  |   0.00382583 |   0.0110302  |   0.0446402 |   0.0939652 |
| SWup   | detailed     |  16.9145   | -16.9106    |   0.681232 |   0.996379 |   0.73068 |  45.9885 |  22.7408   |   0.326415 |  16.9106    |   0.318768  |   0.00362138 |   0.00973887 |   0.0478787 |   0.0849599 |
| LWup   | G11          |  21.5243   |  12.3818    |   1.53783  |   0.939794 |   9.35999 |  66.16   |  31.4752   |   0.688795 |  12.3818    |   0.537835  |   0.0602057  |   0.189585   |   0.439515  |   0.122701  |
| LWup   | baseline     |  10.8534   |  -4.68162   |   0.730458 |   0.96234  |   6.88993 |  28.0941 |  15.706    |   0.357311 |   4.68162   |   0.269542  |   0.03766    |   0.014701   |   0.287026  |   0.144431  |
| LWup   | detailed     |  10.9741   |  -4.83765   |   0.727202 |   0.961239 |   6.87487 |  28.5835 |  15.9267   |   0.361653 |   4.83765   |   0.272798  |   0.038761   |   0.0137811  |   0.289982  |   0.143554  |
| Qle    | G11          |  35.4773   | -30.9755    |   0        | nan        |  10.33    | 126.79   |  57.8573   | nan        |  30.9755    |   1         | nan          |   1          |   1         |   0.660683  |
| Qle    | baseline     |  26.016    | -14.7728    |   0.39471  |   0.54704  |  10.49    |  75.1222 |  44.1037   |   0.850853 |  14.7728    |   0.60529   |   0.45296    |   0.0203773  |   0.149628  |   0.27661   |
| Qle    | detailed     |  26.0166   | -14.7725    |   0.394708 |   0.547043 |  10.49    |  75.1222 |  44.1035   |   0.850852 |  14.7725    |   0.605292  |   0.452957   |   0.0203918  |   0.149631  |   0.27661   |
| Qh     | G11          |  45.5841   |  29.3363    |   1.65482  |   0.947105 |  10.58    | 181.3    |  77.029    |   0.77708  |  29.3363    |   0.654821  |   0.0528949  |   0.0560461  |   0.276159  |   0.190241  |
| Qh     | baseline     |  23.5692   |  -7.27682   |   0.804591 |   0.930139 |   4.24796 |  48.7015 |  36.3088   |   0.388077 |   7.27682   |   0.195409  |   0.0698609  |   0.0728426  |   0.192943  |   0.127316  |
| Qh     | detailed     |  23.9421   |  -8.11683   |   0.791152 |   0.928901 |   3.9727  |  52.7235 |  37.1159   |   0.395118 |   8.11683   |   0.208848  |   0.0710993  |   0.0750788  |   0.192449  |   0.119787  |
| Qtau   | G11          |   0.114967 |   0.0430139 |   1.07893  |   0.859125 |   0.007   |   0.086  |   0.177993 |   0.556971 |   0.0430139 |   0.0789264 |   0.140875   |   0.329443   |   0.623437  |   0.688131  |
| Qtau   | baseline     | nan        | nan         | nan        | nan        | nan       | nan      | nan        | nan        | nan         | nan         | nan          | nan          | nan         | nan         |
| Qtau   | detailed     | nan        | nan         | nan        | nan        | nan       | nan      | nan        | nan        | nan         | nan         | nan          | nan          | nan         | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="albedo"></a>Albedo
[![VTUF-3D_AU-Preston_Albedo.png](VTUF-3D_AU-Preston_Albedo.png)](VTUF-3D_AU-Preston_Albedo.png)

### <a name="datasheet"></a>Datasheet
[![VTUF-3D_AU-Preston_Datasheet.png](VTUF-3D_AU-Preston_Datasheet.png)](VTUF-3D_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![VTUF-3D_AU-Preston_Distributions.png](VTUF-3D_AU-Preston_Distributions.png)](VTUF-3D_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![VTUF-3D_AU-Preston_closure_baseline.png](VTUF-3D_AU-Preston_closure_baseline.png)](VTUF-3D_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![VTUF-3D_AU-Preston_closure_detailed.png](VTUF-3D_AU-Preston_closure_detailed.png)](VTUF-3D_AU-Preston_closure_detailed.png)

### <a name="subset_qh"></a>subset_Qh
[![VTUF-3D_AU-Preston_subset_Qh.png](VTUF-3D_AU-Preston_subset_Qh.png)](VTUF-3D_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![VTUF-3D_AU-Preston_subset_Qle.png](VTUF-3D_AU-Preston_subset_Qle.png)](VTUF-3D_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![VTUF-3D_AU-Preston_subset_SWup.png](VTUF-3D_AU-Preston_subset_SWup.png)](VTUF-3D_AU-Preston_subset_SWup.png)

### out of range: baseline

 - VTUF-3D SWnet min value of -0.0002 is less than expected 0.0 [W/m2]

### out of range: detailed

 - VTUF-3D SWnet min value of -0.0003 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

