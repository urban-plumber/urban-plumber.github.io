# CA-Sunset: Ensemble

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](Ensemble_CA-Sunset_baseline_attrs.md)
- [Detailed](Ensemble_CA-Sunset_detailed_attrs.md)

### Error metrics

| flux     | experiment   |        MAE |        MBE |      nSD |        R |         5th |      95th |      RMSE |    cRMSE |      AMBE |     1-nSD |       1-R |   nSkewness |   nKurtosis |   Overlap |
|:---------|:-------------|-----------:|-----------:|---------:|---------:|------------:|----------:|----------:|---------:|----------:|----------:|----------:|------------:|------------:|----------:|
| SWup     | baseline     |  8.43681   |  6.77017   | 1.27205  | 0.977525 |  0.663577   | 21.9162   | 12.2183   | 0.362203 | 6.77017   | 0.272057  | 0.0224745 |   0.039495  |   0.85623   | 0.115784  |
| SWup     | detailed     |  4.24521   |  0.868434  | 1.06588  | 0.978191 |  0.695607   |  4.57488  |  6.3905   | 0.225461 | 0.868434  | 0.0658855 | 0.0218093 |   0.0232929 |   0.656613  | 0.0718408 |
| LWup     | baseline     | 10.3466    |  4.93141   | 1.25532  | 0.969693 |  5.57711    | 30.1249   | 16.4982   | 0.375866 | 4.93141   | 0.255317  | 0.0303065 |   0.167757  |   0.207518  | 0.0859103 |
| LWup     | detailed     | 12.5334    |  4.98538   | 1.32908  | 0.966916 |  7.59711    | 38.7648   | 19.2135   | 0.442985 | 4.98538   | 0.329078  | 0.0330841 |   0.27933   |   0.483142  | 0.109895  |
| Qle      | baseline     | 18.3684    | -8.58471   | 0.58977  | 0.722635 |  8.38714    | 41.0306   | 33.209    | 0.703884 | 8.58471   | 0.410231  | 0.277365  |   0.140627  |   0.555034  | 0.206916  |
| Qle      | detailed     | 18.0708    | -8.11461   | 0.644747 | 0.722798 |  7.59721    | 35.8257   | 32.7182   | 0.695453 | 8.11461   | 0.355255  | 0.277202  |   0.15105   |   0.612859  | 0.197734  |
| Qh       | baseline     | 27.3571    |  3.58127   | 0.757343 | 0.944429 | 21.2769     | 51.0518   | 39.2911   | 0.378225 | 3.58127   | 0.24266   | 0.0555705 |   0.0262909 |   0.114166  | 0.375268  |
| Qh       | detailed     | 24.9063    | -2.52647   | 0.746908 | 0.949116 | 17.7552     | 59.2819   | 38.7992   | 0.374256 | 2.52647   | 0.253095  | 0.0508843 |   0.0161944 |   0.106111  | 0.316328  |
| Qtau     | baseline     |  0.0972941 |  0.0539978 | 1.43786  | 0.309812 |  0.00854353 |  0.114305 |  0.147854 | 1.4753   | 0.0539978 | 0.43785   | 0.690188  |   0.0096358 |   0.061815  | 0.245459  |
| Qtau     | detailed     |  0.100182  |  0.061413  | 1.38329  | 0.312318 |  0.0161581  |  0.114045 |  0.147005 | 1.43159  | 0.061413  | 0.383289  | 0.687682  |   0.0620765 |   0.0699802 | 0.294784  |
| SoilTemp | baseline     |  1.22789   |  0.744473  | 1.01135  | 0.972961 |  0.997243   |  1.39408  |  1.72534  | 0.234136 | 0.744473  | 0.011352  | 0.0270386 |   0.280539  |   0.0421726 | 0.0894099 |
| SoilTemp | detailed     |  1.5025    |  1.19596   | 0.989456 | 0.970432 |  1.76887    |  1.92796  |  2.00523  | 0.242122 | 1.19596   | 0.0105372 | 0.0295676 |   0.764529  |   0.178622  | 0.117053  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### out of range: baseline


### out of range: detailed



[Link to variable definitions](../modelattrs/variable_definitions.md)

