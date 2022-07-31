# AU-Preston: Manabe_1T

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |       MAE |        MBE |      nSD |        R |         5th |       95th |      RMSE |     cRMSE |       AMBE |      1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|----------:|-----------:|---------:|---------:|------------:|-----------:|----------:|----------:|-----------:|-----------:|-----------:|------------:|------------:|----------:|
| SWup   | baseline     |  6.96933  |  6.48988   | 1.13301  | 0.996707 |  0.381432   | 19.6766    |  9.83419  | 0.1586    |  6.48988   | 0.133013   | 0.00329283 |   0.011806  |  0.0199241  | 0.0894767 |
| SWup   | detailed     |  2.71585  | -0.254142  | 1.00802  | 0.996707 |  0.528      |  1.39796   |  3.82254  | 0.0818704 |  0.254142  | 0.00801814 | 0.00329283 |   0.0118059 |  0.019924   | 0.0586148 |
| LWup   | baseline     | 17.6431   | 17.2709    | 1.22722  | 0.966373 |  8.06943    | 41.2404    | 23.1318   | 0.366283  | 17.2709    | 0.227218   | 0.0336268  |   0.080895  |  0.0829516  | 0.14033   |
| LWup   | detailed     | 20.7841   | 20.4024    | 1.29338  | 0.956295 |  8.1396     | 51.1262    | 27.7076   | 0.446232  | 20.4024    | 0.293378   | 0.0437045  |   0.0733762 |  0.0309003  | 0.155885  |
| Qle    | baseline     | 27.8886   | -5.55426   | 0.675757 | 0.492437 | 12.1101     | 33.0265    | 46.6502   | 0.889445  |  5.55426   | 0.324243   | 0.507563   |   0.298583  |  0.0564534  | 0.180645  |
| Qle    | detailed     | 28.5094   | -5.64983   | 0.667259 | 0.472551 | 12.1101     | 33.8628    | 47.3395   | 0.902556  |  5.64983   | 0.332741   | 0.527449   |   0.275435  |  0.00736483 | 0.198377  |
| Qh     | baseline     | 33.8222   | -5.30531   | 0.895475 | 0.822938 |  5.33111    | 33.297     | 52.9547   | 0.572743  |  5.30531   | 0.104525   | 0.177062   |   0.0882923 |  0.472377   | 0.166592  |
| Qh     | detailed     | 35.6678   | -4.39938   | 0.850491 | 0.803951 |  0.106296   | 42.5411    | 55.051    | 0.596513  |  4.39938   | 0.149509   | 0.196049   |   0.0859415 |  0.481553   | 0.195475  |
| Qtau   | baseline     |  0.125696 |  0.0515693 | 0.95109  | 0.863202 |  0.0102949  |  0.0226573 |  0.175874 | 0.512451  |  0.0515693 | 0.0489101  | 0.136798   |   0.139892  |  0.144836   | 0.145945  |
| Qtau   | detailed     |  0.114606 | -0.0403959 | 0.68483  | 0.862558 |  0.00753722 |  0.286606  |  0.180535 | 0.536266  |  0.0403959 | 0.31517    | 0.137442   |   0.137934  |  0.140952   | 0.141344  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="datasheet"></a>Datasheet
[![Manabe_1T_AU-Preston_Datasheet.png](Manabe_1T_AU-Preston_Datasheet.png)](Manabe_1T_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![Manabe_1T_AU-Preston_Distributions.png](Manabe_1T_AU-Preston_Distributions.png)](Manabe_1T_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![Manabe_1T_AU-Preston_closure_baseline.png](Manabe_1T_AU-Preston_closure_baseline.png)](Manabe_1T_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![Manabe_1T_AU-Preston_closure_detailed.png](Manabe_1T_AU-Preston_closure_detailed.png)](Manabe_1T_AU-Preston_closure_detailed.png)

### <a name="subset_lwup"></a>subset_LWup
[![Manabe_1T_AU-Preston_subset_LWup.png](Manabe_1T_AU-Preston_subset_LWup.png)](Manabe_1T_AU-Preston_subset_LWup.png)

### <a name="subset_qh"></a>subset_Qh
[![Manabe_1T_AU-Preston_subset_Qh.png](Manabe_1T_AU-Preston_subset_Qh.png)](Manabe_1T_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![Manabe_1T_AU-Preston_subset_Qle.png](Manabe_1T_AU-Preston_subset_Qle.png)](Manabe_1T_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![Manabe_1T_AU-Preston_subset_SWup.png](Manabe_1T_AU-Preston_subset_SWup.png)](Manabe_1T_AU-Preston_subset_SWup.png)

### out of range: baseline

 - Manabe_1T EvapF max value of 392.1049 is greater than expected 1.0 [1]
 - Manabe_1T EvapF min value of -314.9456 is less than expected 0.0 [1]

### out of range: detailed

 - Manabe_1T EvapF max value of 26.0211 is greater than expected 1.0 [1]
 - Manabe_1T EvapF min value of -114.6580 is less than expected 0.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

