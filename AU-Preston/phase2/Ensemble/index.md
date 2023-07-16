# AU-Preston: Ensemble

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](Ensemble_AU-Preston_baseline_attrs.md)
- [Detailed](Ensemble_AU-Preston_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |        MBE |      nSD |        R |        5th |       95th |      RMSE |     cRMSE |       AMBE |      1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|----------:|-----------:|---------:|---------:|-----------:|-----------:|----------:|----------:|-----------:|-----------:|-----------:|------------:|------------:|----------:|
| SWup   | baseline     |  2.77762  | -0.400295  | 0.996998 | 0.996573 |  0.488321  |  0.504672  |  3.87464  | 0.0827164 |  0.400295  | 0.00300129 | 0.00342678 |   0.0109635 | 0.0242418   | 0.060546  |
| SWup   | detailed     |  2.74009  | -0.855407  | 0.993764 | 0.996697 |  0.478002  |  0.277575  |  3.88148  | 0.0812601 |  0.855407  | 0.00623545 | 0.00330275 |   0.0182939 | 0.0415209   | 0.0583333 |
| LWup   | baseline     |  8.93721  |  6.93214   | 1.16684  | 0.986312 |  0.474055  | 24.536     | 12.3952   | 0.244498  |  6.93214   | 0.166836   | 0.0136884  |   0.0475817 | 0.000882789 | 0.0730927 |
| LWup   | detailed     |  8.35496  |  6.06607   | 1.17399  | 0.985808 |  0.57289   | 25.2624    | 12.2116   | 0.252183  |  6.06607   | 0.173993   | 0.0141918  |   0.0748668 | 0.0468771   | 0.0641188 |
| Qle    | baseline     | 19.1873   | -6.25769   | 0.662461 | 0.742931 | 10.4607    | 29.5052    | 33.5041   | 0.674188  |  6.25769   | 0.33754    | 0.257069   |   0.064619  | 0.550081    | 0.219926  |
| Qle    | detailed     | 18.5958   | -4.44526   | 0.687953 | 0.747936 | 10.543     | 27.6313    | 32.8403   | 0.666476  |  4.44526   | 0.312048   | 0.252064   |   0.063569  | 0.549171    | 0.218844  |
| Qh     | baseline     | 21.0726   | 13.1235    | 1.06293  | 0.952106 | 11.2462    | 29.8046    | 32.6054   | 0.325234  | 13.1235    | 0.0629336  | 0.0478942  |   0.030603  | 0.000992208 | 0.187162  |
| Qh     | detailed     | 17.1805   |  6.15315   | 1.03239  | 0.956099 |  7.61327   | 14.5923    | 28.4629   | 0.302811  |  6.15315   | 0.0323865  | 0.0439011  |   0.0346311 | 0.00752409  | 0.100077  |
| Qtau   | baseline     |  0.123689 |  0.072588  | 1.02822  | 0.867115 |  0.0156328 |  0.0662195 |  0.177554 | 0.523514  |  0.072588  | 0.0282252  | 0.132885   |   0.205843  | 0.36011     | 0.147813  |
| Qtau   | detailed     |  0.113688 |  0.0372023 | 0.842587 | 0.858331 |  0.0276522 |  0.0853892 |  0.163186 | 0.513337  |  0.0372023 | 0.157412   | 0.141669   |   0.275096  | 0.491408    | 0.175134  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### out of range: baseline


### out of range: detailed

 - Ensemble Qstor min value of -66138.0573 is less than expected -800.0 [W/m2]
 - Ensemble Qle max value of 66202.2494 is greater than expected 700.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

