# AU-Preston: TERRA_4.11

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](TERRA_4.11_AU-Preston_baseline_attrs.md)
- [Detailed](TERRA_4.11_AU-Preston_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |        MBE |        nSD |          R |        5th |      95th |      RMSE |       cRMSE |       AMBE |       1-nSD |          1-R |   nSkewness |   nKurtosis |     Overlap |
|:-------|:-------------|----------:|-----------:|-----------:|-----------:|-----------:|----------:|----------:|------------:|-----------:|------------:|-------------:|------------:|------------:|------------:|
| SWup   | baseline     |  15.7154  | -15.7153   |   0.722678 |   0.996803 |   0.881326 |  40.3272  |  20.5901  |   0.28553   |  15.7153   |   0.277322  |   0.00319657 |   0.0144507 |   0.0268135 |   0.0844263 |
| SWup   | detailed     |   2.7205  |  -0.159868 |   1.01024  |   0.996802 |   0.5391   |   1.76488 |   3.77893 |   0.0810346 |   0.159868 |   0.0102429 |   0.00319809 |   0.014109  |   0.0262204 |   0.0586388 |
| LWup   | baseline     |  34.149   | -33.6146   |   0.822684 |   0.845311 |  38.5789   |  59.6487  |  40.4371  |   0.534754  |  33.6146   |   0.177316  |   0.154689   |   0.641144  |   0.708756  |   0.29818   |
| LWup   | detailed     |   9.92223 |   8.38542  |   1.15155  |   0.985492 |   1.96082  |  24.5514  |  13.0357  |   0.237451  |   8.38542  |   0.151555  |   0.0145083  |   0.076073  |   0.154075  |   0.0823556 |
| Qle    | baseline     |  25.2667  | -18.1958   |   0.412785 |   0.613951 |  10.5351   |  70.8254  |  43.758   |   0.814575  |  18.1958   |   0.587215  |   0.386049   |   0.0847432 |   0.367861  |   0.424808  |
| Qle    | detailed     |  25.2501  | -17.8694   |   0.409606 |   0.600937 |  10.5328   |  71.4822  |  43.949   |   0.821877  |  17.8694   |   0.590394  |   0.399063   |   0.0723124 |   0.363228  |   0.387793  |
| Qh     | baseline     |  86.6648  |  86.2778   |   1.44313  |   0.933439 |  61.5473   | 191.636   | 103.466   |   0.623279  |  86.2778   |   0.443131  |   0.0665607  |   0.0159231 |   0.0759749 |   0.608638  |
| Qh     | detailed     |  33.0638  |  29.5485   |   1.34289  |   0.953453 |  10.5979   | 114.561   |  53.942   |   0.492533  |  29.5485   |   0.34289   |   0.0465472  |   0.0257672 |   0.062116  |   0.240603  |
| Qtau   | baseline     | nan       | nan        | nan        | nan        | nan        | nan       | nan       | nan         | nan        | nan         | nan          | nan         | nan         | nan         |
| Qtau   | detailed     | nan       | nan        | nan        | nan        | nan        | nan       | nan       | nan         | nan        | nan         | nan          | nan         | nan         | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="albedo"></a>Albedo
[![TERRA_4.11_AU-Preston_Albedo.png](TERRA_4.11_AU-Preston_Albedo.png)](TERRA_4.11_AU-Preston_Albedo.png)

### <a name="datasheet"></a>Datasheet
[![TERRA_4.11_AU-Preston_Datasheet.png](TERRA_4.11_AU-Preston_Datasheet.png)](TERRA_4.11_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![TERRA_4.11_AU-Preston_Distributions.png](TERRA_4.11_AU-Preston_Distributions.png)](TERRA_4.11_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![TERRA_4.11_AU-Preston_closure_baseline.png](TERRA_4.11_AU-Preston_closure_baseline.png)](TERRA_4.11_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![TERRA_4.11_AU-Preston_closure_detailed.png](TERRA_4.11_AU-Preston_closure_detailed.png)](TERRA_4.11_AU-Preston_closure_detailed.png)

### <a name="subset_qh"></a>subset_Qh
[![TERRA_4.11_AU-Preston_subset_Qh.png](TERRA_4.11_AU-Preston_subset_Qh.png)](TERRA_4.11_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![TERRA_4.11_AU-Preston_subset_Qle.png](TERRA_4.11_AU-Preston_subset_Qle.png)](TERRA_4.11_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![TERRA_4.11_AU-Preston_subset_SWup.png](TERRA_4.11_AU-Preston_subset_SWup.png)](TERRA_4.11_AU-Preston_subset_SWup.png)

### out of range: baseline

 - TERRA_4.11 Qh max value of 731.2208 is greater than expected 600.0 [W/m2]

### out of range: detailed



[Link to variable definitions](../modelattrs/variable_definitions.md)

