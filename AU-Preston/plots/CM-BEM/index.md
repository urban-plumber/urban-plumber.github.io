# AU-Preston: CM-BEM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](CM-BEM_AU-Preston_baseline_attrs.md)
- [Detailed](CM-BEM_AU-Preston_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |       MBE |        nSD |          R |       5th |     95th |     RMSE |      cRMSE |      AMBE |       1-nSD |         1-R |   nSkewness |   nKurtosis |     Overlap |
|:-------|:-------------|----------:|----------:|-----------:|-----------:|----------:|---------:|---------:|-----------:|----------:|------------:|------------:|------------:|------------:|------------:|
| SWup   | baseline     |   9.5281  |   5.88691 |   1.00735  |   0.962844 |   0.0725  |   3.0005 |  14.0455 |   0.273703 |   5.88691 |   0.0073533 |   0.0371563 |   0.408884  |   0.713673  |   0.100944  |
| SWup   | detailed     |   5.98474 |   3.06342 |   0.974122 |   0.975978 |   0.0159  |   2.7038 |  10.6035 |   0.217879 |   3.06342 |   0.025878  |   0.0240223 |   0.230494  |   0.298935  |   0.0820797 |
| LWup   | baseline     |  13.5074  |   2.27634 |   1.33308  |   0.961307 |  11.6162  |  41.2864 |  19.5826 |   0.462718 |   2.27634 |   0.333084  |   0.0386933 |   0.104504  |   0.0488928 |   0.137763  |
| LWup   | detailed     |  12.4301  |   3.20071 |   1.28226  |   0.962816 |   7.50471 |  36.6399 |  17.8744 |   0.418364 |   3.20071 |   0.282256  |   0.0371845 |   0.0717615 |   0.122617  |   0.120964  |
| Qle    | baseline     |  24.948   | -12.5122  |   0.721662 |   0.652259 |   2.3928  |  21.8253 |  39.2348 |   0.761166 |  12.5122  |   0.278338  |   0.347741  |   0.232852  |   0.135577  |   0.227975  |
| Qle    | detailed     |  22.1255  |  -1.69118 |   0.915929 |   0.700497 |   5.7673  |  10.7411 |  36.4583 |   0.745463 |   1.69118 |   0.0840707 |   0.299503  |   0.105512  |   0.353226  |   0.143031  |
| Qh     | baseline     |  32.4616  |  17.3671  |   0.83917  |   0.903031 |  30.7177  |  21.4426 |  43.4178 |   0.434297 |  17.3671  |   0.16083   |   0.0969692 |   0.0438482 |   0.129976  |   0.364845  |
| Qh     | detailed     |  31.2219  |   6.71675 |   0.752895 |   0.890081 |  21.6522  |  49.4859 |  44.1283 |   0.475999 |   6.71675 |   0.247105  |   0.109919  |   0.0237779 |   0.0184425 |   0.353459  |
| Qtau   | baseline     | nan       | nan       | nan        | nan        | nan       | nan      | nan      | nan        | nan       | nan         | nan         | nan         | nan         | nan         |
| Qtau   | detailed     | nan       | nan       | nan        | nan        | nan       | nan      | nan      | nan        | nan       | nan         | nan         | nan         | nan         | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="albedo"></a>Albedo
[![CM-BEM_AU-Preston_Albedo.png](CM-BEM_AU-Preston_Albedo.png)](CM-BEM_AU-Preston_Albedo.png)

### <a name="datasheet"></a>Datasheet
[![CM-BEM_AU-Preston_Datasheet.png](CM-BEM_AU-Preston_Datasheet.png)](CM-BEM_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![CM-BEM_AU-Preston_Distributions.png](CM-BEM_AU-Preston_Distributions.png)](CM-BEM_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![CM-BEM_AU-Preston_closure_baseline.png](CM-BEM_AU-Preston_closure_baseline.png)](CM-BEM_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![CM-BEM_AU-Preston_closure_detailed.png](CM-BEM_AU-Preston_closure_detailed.png)](CM-BEM_AU-Preston_closure_detailed.png)

### <a name="subset_qh"></a>subset_Qh
[![CM-BEM_AU-Preston_subset_Qh.png](CM-BEM_AU-Preston_subset_Qh.png)](CM-BEM_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![CM-BEM_AU-Preston_subset_Qle.png](CM-BEM_AU-Preston_subset_Qle.png)](CM-BEM_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![CM-BEM_AU-Preston_subset_SWup.png](CM-BEM_AU-Preston_subset_SWup.png)](CM-BEM_AU-Preston_subset_SWup.png)

### out of range: baseline

 - CM-BEM SWnet min value of -0.3225 is less than expected 0.0 [W/m2]

### out of range: detailed

 - CM-BEM SWnet min value of -0.2861 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

