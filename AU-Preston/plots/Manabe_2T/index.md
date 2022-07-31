# AU-Preston: Manabe_2T

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |       MAE |        MBE |      nSD |        R |         5th |       95th |      RMSE |     cRMSE |       AMBE |      1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|----------:|-----------:|---------:|---------:|------------:|-----------:|----------:|----------:|-----------:|-----------:|-----------:|------------:|------------:|----------:|
| SWup   | baseline     |  6.96933  |  6.48988   | 1.13301  | 0.996707 |  0.381432   | 19.6766    |  9.83419  | 0.1586    |  6.48988   | 0.133013   | 0.00329283 |   0.011806  |   0.0199241 | 0.0894767 |
| SWup   | detailed     |  2.71585  | -0.254142  | 1.00802  | 0.996707 |  0.528      |  1.39796   |  3.82254  | 0.0818704 |  0.254142  | 0.00801814 | 0.00329283 |   0.0118059 |   0.019924  | 0.0586148 |
| LWup   | baseline     | 17.032    | 16.8464    | 1.27651  | 0.975999 |  6.4942     | 45.8351    | 22.9542   | 0.371119  | 16.8464    | 0.276507   | 0.0240005  |   0.117012  |   0.167348  | 0.128823  |
| LWup   | detailed     | 20.4304   | 19.2887    | 1.50198  | 0.963941 |  1.896      | 72.4523    | 31.749    | 0.600254  | 19.2887    | 0.501981   | 0.0360588  |   0.212179  |   0.376095  | 0.104185  |
| Qle    | baseline     | 27.736    | -5.5597    | 0.679626 | 0.496263 | 12.1101     | 32.7387    | 46.5412   | 0.887325  |  5.5597    | 0.320374   | 0.503737   |   0.294108  |   0.0455262 | 0.177911  |
| Qle    | detailed     | 28.0949   | -5.68719   | 0.684959 | 0.483704 | 12.11       | 31.8358    | 47.1122   | 0.898072  |  5.68719   | 0.315041   | 0.516296   |   0.264238  |   0.0223321 | 0.19105   |
| Qh     | baseline     | 27.8266   | -4.39444   | 0.931905 | 0.879029 |  7.36162    | 23.3661    | 44.3464   | 0.479692  |  4.39444   | 0.0680951  | 0.120971   |   0.0414001 |   0.281516  | 0.13937   |
| Qh     | detailed     | 22.4581   | -2.03776   | 0.998217 | 0.921836 |  8.72773    |  5.07963   | 36.3974   | 0.395035  |  2.03776   | 0.00178292 | 0.0781642  |   0.0151394 |   0.0353659 | 0.107349  |
| Qtau   | baseline     |  0.118506 |  0.046463  | 0.959505 | 0.871166 |  0.0100593  |  0.0185677 |  0.170155 | 0.498873  |  0.046463  | 0.0404949  | 0.128834   |   0.140151  |   0.159861  | 0.123219  |
| Qtau   | detailed     |  0.103968 | -0.0518104 | 0.705417 | 0.881641 |  0.00277292 |  0.281518  |  0.173219 | 0.50375   |  0.0518104 | 0.294583   | 0.118359   |   0.146322  |   0.194878  | 0.0861043 |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="datasheet"></a>Datasheet
[![Manabe_2T_AU-Preston_Datasheet.png](Manabe_2T_AU-Preston_Datasheet.png)](Manabe_2T_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![Manabe_2T_AU-Preston_Distributions.png](Manabe_2T_AU-Preston_Distributions.png)](Manabe_2T_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![Manabe_2T_AU-Preston_closure_baseline.png](Manabe_2T_AU-Preston_closure_baseline.png)](Manabe_2T_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![Manabe_2T_AU-Preston_closure_detailed.png](Manabe_2T_AU-Preston_closure_detailed.png)](Manabe_2T_AU-Preston_closure_detailed.png)

### <a name="subset_lwup"></a>subset_LWup
[![Manabe_2T_AU-Preston_subset_LWup.png](Manabe_2T_AU-Preston_subset_LWup.png)](Manabe_2T_AU-Preston_subset_LWup.png)

### <a name="subset_qh"></a>subset_Qh
[![Manabe_2T_AU-Preston_subset_Qh.png](Manabe_2T_AU-Preston_subset_Qh.png)](Manabe_2T_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![Manabe_2T_AU-Preston_subset_Qle.png](Manabe_2T_AU-Preston_subset_Qle.png)](Manabe_2T_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![Manabe_2T_AU-Preston_subset_SWup.png](Manabe_2T_AU-Preston_subset_SWup.png)](Manabe_2T_AU-Preston_subset_SWup.png)

### out of range: baseline

 - Manabe_2T EvapF max value of 173.6684 is greater than expected 1.0 [1]
 - Manabe_2T EvapF min value of -40.5611 is less than expected 0.0 [1]

### out of range: detailed

 - Manabe_2T EvapF max value of 10.1687 is greater than expected 1.0 [1]
 - Manabe_2T EvapF min value of -39.2173 is less than expected 0.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

