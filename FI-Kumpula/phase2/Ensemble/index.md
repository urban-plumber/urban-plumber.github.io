# FI-Kumpula: Ensemble

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](Ensemble_FI-Kumpula_baseline_attrs.md)
- [Detailed](Ensemble_FI-Kumpula_detailed_attrs.md)

### Error metrics

| flux   | experiment   |      MAE |        MBE |      nSD |        R |        5th |     95th |     RMSE |    cRMSE |      AMBE |     1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|---------:|-----------:|---------:|---------:|-----------:|---------:|---------:|---------:|----------:|----------:|-----------:|------------:|------------:|----------:|
| SWup   | baseline     |  7.55654 | -3.97342   | 0.882441 | 0.960418 |  0.0401863 |  6.68816 | 13.9006  | 0.289272 | 3.97342   | 0.11757   | 0.0395824  |   0.309434  |  0.785327   | 0.100182  |
| SWup   | detailed     |  8.08266 | -5.83376   | 0.83158  | 0.956047 |  0.030709  | 11.8476  | 15.7858  | 0.318538 | 5.83376   | 0.16843   | 0.0439531  |   0.338045  |  0.838949   | 0.115728  |
| LWup   | baseline     |  5.67197 |  0.467145  | 1.08332  | 0.992893 |  1.566     | 15.2658  |  7.89378 | 0.149465 | 0.467145  | 0.0833169 | 0.00710666 |   1.8276    |  0.269228   | 0.0723035 |
| LWup   | detailed     |  6.96197 | -2.34879   | 1.08296  | 0.992295 |  2.29315   | 12.9989  |  8.42787 | 0.153524 | 2.34879   | 0.0829531 | 0.00770481 |   2.13731   |  0.246289   | 0.0994385 |
| Qle    | baseline     | 12.9678  | -6.40867   | 0.614309 | 0.804003 |  5.94295   | 33.2173  | 24.4725  | 0.624149 | 6.40867   | 0.38569   | 0.195997   |   0.0419609 |  0.186098   | 0.220512  |
| Qle    | detailed     | 12.6647  | -5.13891   | 0.649157 | 0.800998 |  6.35006   | 28.5001  | 23.9298  | 0.617622 | 5.13891   | 0.350842  | 0.199002   |   0.0428354 |  0.187057   | 0.234721  |
| Qh     | baseline     | 21.6673  | -0.0969825 | 0.684468 | 0.834996 | 15.0216    | 44.6156  | 33.7089  | 0.570474 | 0.0969825 | 0.315533  | 0.165004   |   0.0282817 |  0.00149908 | 0.243205  |
| Qh     | detailed     | 20.6874  | -5.7711    | 0.706085 | 0.842924 |  7.81879   | 45.8125  | 33.3078  | 0.555161 | 5.7711    | 0.293916  | 0.157076   |   0.0432996 |  0.0581997  | 0.157098  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### out of range: baseline


### out of range: detailed

 - Ensemble Qanth min value of -192.3668 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

