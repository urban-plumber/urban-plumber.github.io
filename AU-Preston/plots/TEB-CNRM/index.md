# AU-Preston: TEB-CNRM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |       MAE |       MBE |      nSD |        R |        5th |      95th |      RMSE |    cRMSE |      AMBE |     1-nSD |       1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|----------:|----------:|---------:|---------:|-----------:|----------:|----------:|---------:|----------:|----------:|----------:|------------:|------------:|----------:|
| SWup   | baseline     |  7.73153  | -7.6052   | 0.869552 | 0.995275 |  1.24467   | 19.1515   | 10.6115   | 0.15885  |  7.6052   | 0.130448  | 0.0047245 |  0.00669083 |  0.00435254 | 0.0845758 |
| SWup   | detailed     |  9.75244  | -9.69452  | 0.831376 | 0.995276 |  1.26573   | 24.732    | 13.1432   | 0.190497 |  9.69452  | 0.168624  | 0.0047243 |  0.00574783 |  0.00551792 | 0.086709  |
| LWup   | baseline     | 17.1252   | 10.0193   | 1.43003  | 0.966781 |  8.67637   | 54.5505   | 24.3812   | 0.52909  | 10.0193   | 0.430033  | 0.033219  |  0.113196   |  0.0999099  | 0.116515  |
| LWup   | detailed     | 11.6537   |  3.0451   | 1.25474  | 0.9752   |  9.27985   | 29.8963   | 15.2853   | 0.356551 |  3.0451   | 0.254743  | 0.0247999 |  0.0956607  |  0.179473   | 0.0991112 |
| Qle    | baseline     | 27.6805   | -5.34483  | 0.738279 | 0.47092  | 13.8574    | 29.7663   | 48.2999   | 0.9218   |  5.34483  | 0.261721  | 0.52908   |  0.600029   |  0.790098   | 0.288587  |
| Qle    | detailed     | 31.11     |  7.21466  | 1.05806  | 0.519003 | 13.0764    | 23.1158   | 53.1174   | 1.01055  |  7.21466  | 0.0580572 | 0.480997  |  0.251633   |  0.0959893  | 0.202178  |
| Qh     | baseline     | 34.1855   | 26.6663   | 1.25078  | 0.934765 | 15.2713    | 93.9982   | 51.2282   | 0.475479 | 26.6663   | 0.250781  | 0.0652351 |  0.0742858  |  0.1006     | 0.251713  |
| Qh     | detailed     | 29.3952   | 14.3264   | 1.26912  | 0.919134 |  3.93017   | 79.1322   | 50.5489   | 0.526958 | 14.3264   | 0.269124  | 0.0808658 |  0.184564   |  0.443559   | 0.0973994 |
| Qtau   | baseline     |  0.213515 |  0.188632 | 1.31986  | 0.873636 |  0.0342629 |  0.363829 |  0.287241 | 0.660208 |  0.188632 | 0.319857  | 0.126364  |  0.12741    |  0.139527   | 0.241719  |
| Qtau   | detailed     |  0.222207 |  0.199498 | 1.39246  | 0.871191 |  0.0231555 |  0.425815 |  0.308222 | 0.71606  |  0.199498 | 0.392456  | 0.128809  |  0.148677   |  0.193128   | 0.231587  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="datasheet"></a>Datasheet
[![TEB-CNRM_AU-Preston_Datasheet.png](TEB-CNRM_AU-Preston_Datasheet.png)](TEB-CNRM_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![TEB-CNRM_AU-Preston_Distributions.png](TEB-CNRM_AU-Preston_Distributions.png)](TEB-CNRM_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![TEB-CNRM_AU-Preston_closure_baseline.png](TEB-CNRM_AU-Preston_closure_baseline.png)](TEB-CNRM_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![TEB-CNRM_AU-Preston_closure_detailed.png](TEB-CNRM_AU-Preston_closure_detailed.png)](TEB-CNRM_AU-Preston_closure_detailed.png)

### <a name="subset_lwup"></a>subset_LWup
[![TEB-CNRM_AU-Preston_subset_LWup.png](TEB-CNRM_AU-Preston_subset_LWup.png)](TEB-CNRM_AU-Preston_subset_LWup.png)

### <a name="subset_qh"></a>subset_Qh
[![TEB-CNRM_AU-Preston_subset_Qh.png](TEB-CNRM_AU-Preston_subset_Qh.png)](TEB-CNRM_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![TEB-CNRM_AU-Preston_subset_Qle.png](TEB-CNRM_AU-Preston_subset_Qle.png)](TEB-CNRM_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![TEB-CNRM_AU-Preston_subset_SWup.png](TEB-CNRM_AU-Preston_subset_SWup.png)](TEB-CNRM_AU-Preston_subset_SWup.png)

### out of range: baseline

 - TEB-CNRM TVeg max value of 0.0004 is greater than expected 0.0003 [kg/m2/s]
 - TEB-CNRM EvapF max value of 18.0896 is greater than expected 1.0 [1]
 - TEB-CNRM EvapF min value of -8.2044 is less than expected 0.0 [1]

### out of range: detailed

 - TEB-CNRM Qh max value of 614.8715 is greater than expected 600.0 [W/m2]
 - TEB-CNRM TVeg max value of 0.0003 is greater than expected 0.0003 [kg/m2/s]
 - TEB-CNRM EvapF max value of 12.3854 is greater than expected 1.0 [1]
 - TEB-CNRM EvapF min value of -26.4026 is less than expected 0.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

