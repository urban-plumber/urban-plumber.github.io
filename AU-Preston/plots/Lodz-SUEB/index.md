# AU-Preston: Lodz-SUEB

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](Lodz-SUEB_AU-Preston_baseline_attrs.md)
- [Detailed](Lodz-SUEB_AU-Preston_detailed_attrs.md)

### Error metrics

| flux   | experiment   |        MAE |          MBE |      nSD |        R |         5th |      95th |      RMSE |     cRMSE |        AMBE |      1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|-----------:|-------------:|---------:|---------:|------------:|----------:|----------:|----------:|------------:|-----------:|-----------:|------------:|------------:|----------:|
| SWup   | G11          |  2.71149   |  -0.256311   | 1.00811  | 0.996803 |  0.53       |  1.40001  |  3.76579  | 0.0806895 |  0.256311   | 0.00811484 | 0.00319653 |  0.0162291  |  0.0325834  | 0.0589239 |
| SWup   | baseline     |  2.71602   |  -0.245991   | 1.00846  | 0.996798 |  0.54       |  1.4706   |  3.77269  | 0.0808009 |  0.245991   | 0.00846081 | 0.00320151 |  0.0135132  |  0.025299   | 0.0588356 |
| SWup   | detailed     |  2.71602   |  -0.245991   | 1.00846  | 0.996798 |  0.54       |  1.4706   |  3.77269  | 0.0808009 |  0.245991   | 0.00846081 | 0.00320151 |  0.0135132  |  0.025299   | 0.0588356 |
| LWup   | G11          | 11.5638    |  -0.866014   | 1.19357  | 0.960781 |  7.07999    | 22.21     | 15.2355   | 0.362062  |  0.866014   | 0.193567   | 0.0392188  |  0.0936667  |  0.00901051 | 0.114285  |
| LWup   | baseline     | 15.0192    |  11.6295     | 1.36283  | 0.97128  |  4.47221    | 50.3583   | 22.4975   | 0.458182  | 11.6295     | 0.362833   | 0.0287204  |  0.0896214  |  0.0559531  | 0.104207  |
| LWup   | detailed     | 14.3915    |  10.749      | 1.34306  | 0.971912 |  4.75111    | 46.86     | 21.372    | 0.439472  | 10.749      | 0.343058   | 0.0280878  |  0.0850611  |  0.0676213  | 0.103488  |
| Qle    | G11          | 27.1601    |   7.71114    | 1.32406  | 0.723    | 10.25       | 72.13     | 45.408    | 0.915719  |  7.71114    | 0.324058   | 0.277      |  0.0232119  |  0.619175   | 0.398803  |
| Qle    | baseline     | 22.0704    |  -6.6369     | 0.851166 | 0.700058 | 10.5083     |  6.4662   | 36.2711   | 0.729899  |  6.6369     | 0.148834   | 0.299942   |  0.104172   |  0.271068   | 0.419996  |
| Qle    | detailed     | 22.0743    |  -6.77098    | 0.848244 | 0.699274 | 10.5067     |  7.3052   | 36.3108   | 0.730211  |  6.77098    | 0.151756   | 0.300726   |  0.115252   |  0.243144   | 0.420708  |
| Qh     | G11          | 20.0362    | -10.5714     | 0.850617 | 0.938568 |  2.64       | 48.01     | 34.3102   | 0.356125  | 10.5714     | 0.149383   | 0.0614319  |  0.009145   |  0.00632989 | 0.107403  |
| Qh     | baseline     | 18.297     |   4.22805    | 0.919938 | 0.949441 | 13.7301     | 10.6222   | 29.2002   | 0.31533   |  4.22805    | 0.0800619  | 0.0505593  |  0.0227353  |  0.139103   | 0.101443  |
| Qh     | detailed     | 18.2819    |   5.14766    | 0.950443 | 0.948478 | 13.0838     |  3.2461   | 29.4846   | 0.316849  |  5.14766    | 0.0495573  | 0.0515219  |  0.00420861 |  0.0965099  | 0.0916444 |
| Qtau   | baseline     |  0.0989292 |   0.00984099 | 0.848254 | 0.870982 |  0.0003322  |  0.107281 |  0.152656 | 0.491841  |  0.00984099 | 0.151746   | 0.129018   |  0.240857   |  0.432783   | 0.106651  |
| Qtau   | detailed     |  0.0974041 |  -0.0210079  | 0.75862  | 0.869508 |  0.00134371 |  0.192756 |  0.158191 | 0.506214  |  0.0210079  | 0.24138    | 0.130492   |  0.243295   |  0.442225   | 0.0970048 |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="albedo"></a>Albedo
[![Lodz-SUEB_AU-Preston_Albedo.png](Lodz-SUEB_AU-Preston_Albedo.png)](Lodz-SUEB_AU-Preston_Albedo.png)

### <a name="datasheet"></a>Datasheet
[![Lodz-SUEB_AU-Preston_Datasheet.png](Lodz-SUEB_AU-Preston_Datasheet.png)](Lodz-SUEB_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![Lodz-SUEB_AU-Preston_Distributions.png](Lodz-SUEB_AU-Preston_Distributions.png)](Lodz-SUEB_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![Lodz-SUEB_AU-Preston_closure_baseline.png](Lodz-SUEB_AU-Preston_closure_baseline.png)](Lodz-SUEB_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![Lodz-SUEB_AU-Preston_closure_detailed.png](Lodz-SUEB_AU-Preston_closure_detailed.png)](Lodz-SUEB_AU-Preston_closure_detailed.png)

### <a name="subset_qh"></a>subset_Qh
[![Lodz-SUEB_AU-Preston_subset_Qh.png](Lodz-SUEB_AU-Preston_subset_Qh.png)](Lodz-SUEB_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![Lodz-SUEB_AU-Preston_subset_Qle.png](Lodz-SUEB_AU-Preston_subset_Qle.png)](Lodz-SUEB_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![Lodz-SUEB_AU-Preston_subset_SWup.png](Lodz-SUEB_AU-Preston_subset_SWup.png)](Lodz-SUEB_AU-Preston_subset_SWup.png)

### out of range: baseline


### out of range: detailed



[Link to variable definitions](../modelattrs/variable_definitions.md)

