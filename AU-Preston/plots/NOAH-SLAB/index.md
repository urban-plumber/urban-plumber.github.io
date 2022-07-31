# AU-Preston: NOAH-SLAB

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](NOAH-SLAB_AU-Preston_baseline_attrs.md)
- [Detailed](NOAH-SLAB_AU-Preston_detailed_attrs.md)

### Error metrics

| flux   | experiment   |      MAE |       MBE |      nSD |        R |       5th |     95th |     RMSE |     cRMSE |     AMBE |      1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|---------:|----------:|---------:|---------:|----------:|---------:|---------:|----------:|---------:|-----------:|-----------:|------------:|------------:|----------:|
| SWup   | baseline     |  2.71585 | -0.254131 | 1.00802  | 0.996707 |  0.528    |  1.398   |  3.82254 | 0.0818704 | 0.254131 | 0.00801834 | 0.00329283 |  0.0118059  |   0.0199241 | 0.0586148 |
| SWup   | detailed     |  2.71585 | -0.254131 | 1.00802  | 0.996707 |  0.528    |  1.398   |  3.82254 | 0.0818704 | 0.254131 | 0.00801834 | 0.00329283 |  0.0118059  |   0.0199241 | 0.0586148 |
| LWup   | baseline     |  4.75247 | -0.764897 | 0.935168 | 0.991381 |  0.756261 |  6.00292 |  6.03769 | 0.14256   | 0.764897 | 0.0648322  | 0.00861887 |  0.0207567  |   0.0344658 | 0.0599047 |
| LWup   | detailed     |  4.90161 | -1.06193  | 0.928778 | 0.991132 |  0.613042 |  7.12368 |  6.25717 | 0.146782  | 1.06193  | 0.0712222  | 0.00886772 |  0.0250684  |   0.0361773 | 0.0606184 |
| Qle    | baseline     | 22.6777  |  2.95683  | 0.694197 | 0.660784 | 14.1039   | 21.8795  | 39.237   | 0.75132   | 2.95683  | 0.305803   | 0.339216   |  0.10176    |   0.537576  | 0.223965  |
| Qle    | detailed     | 22.6237  |  2.98838  | 0.701912 | 0.661319 | 13.9259   | 21.0173  | 39.2333  | 0.751202  | 2.98838  | 0.298088   | 0.338681   |  0.103238   |   0.542622  | 0.223676  |
| Qh     | baseline     | 24.4791  |  3.21465  | 1.22186  | 0.948667 | 15.3064   | 58.898   | 38.5804  | 0.417927  | 3.21465  | 0.221857   | 0.0513327  |  0.00612952 |   0.0536178 | 0.156674  |
| Qh     | detailed     | 24.5641  |  3.455    | 1.22766  | 0.948546 | 15.0301   | 60.6264  | 38.9833  | 0.422097  | 3.455    | 0.227661   | 0.051454   |  0.0139674  |   0.0368804 | 0.157023  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="datasheet"></a>Datasheet
[![NOAH-SLAB_AU-Preston_Datasheet.png](NOAH-SLAB_AU-Preston_Datasheet.png)](NOAH-SLAB_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![NOAH-SLAB_AU-Preston_Distributions.png](NOAH-SLAB_AU-Preston_Distributions.png)](NOAH-SLAB_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![NOAH-SLAB_AU-Preston_closure_baseline.png](NOAH-SLAB_AU-Preston_closure_baseline.png)](NOAH-SLAB_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![NOAH-SLAB_AU-Preston_closure_detailed.png](NOAH-SLAB_AU-Preston_closure_detailed.png)](NOAH-SLAB_AU-Preston_closure_detailed.png)

### <a name="subset_lwup"></a>subset_LWup
[![NOAH-SLAB_AU-Preston_subset_LWup.png](NOAH-SLAB_AU-Preston_subset_LWup.png)](NOAH-SLAB_AU-Preston_subset_LWup.png)

### <a name="subset_qh"></a>subset_Qh
[![NOAH-SLAB_AU-Preston_subset_Qh.png](NOAH-SLAB_AU-Preston_subset_Qh.png)](NOAH-SLAB_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![NOAH-SLAB_AU-Preston_subset_Qle.png](NOAH-SLAB_AU-Preston_subset_Qle.png)](NOAH-SLAB_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![NOAH-SLAB_AU-Preston_subset_SWup.png](NOAH-SLAB_AU-Preston_subset_SWup.png)](NOAH-SLAB_AU-Preston_subset_SWup.png)

### out of range: baseline

 - NOAH-SLAB Qsm max value of 127.2791 is greater than expected 0.005 [kg/m2/s]
 - NOAH-SLAB Qsm min value of -10.5639 is less than expected 0.0 [kg/m2/s]
 - NOAH-SLAB EvapF max value of 62.3575 is greater than expected 1.0 [1]
 - NOAH-SLAB EvapF min value of -31.2638 is less than expected 0.0 [1]

### out of range: detailed

 - NOAH-SLAB EvapF max value of 325.7462 is greater than expected 1.0 [1]
 - NOAH-SLAB EvapF min value of -25.6641 is less than expected 0.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

