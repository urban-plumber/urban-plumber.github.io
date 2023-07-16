# US-Baltimore: Ensemble

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](Ensemble_US-Baltimore_baseline_attrs.md)
- [Detailed](Ensemble_US-Baltimore_detailed_attrs.md)

### Error metrics

| flux     | experiment   |       MAE |        MBE |      nSD |        R |        5th |      95th |      RMSE |    cRMSE |       AMBE |       1-nSD |       1-R |   nSkewness |   nKurtosis |   Overlap |
|:---------|:-------------|----------:|-----------:|---------:|---------:|-----------:|----------:|----------:|---------:|-----------:|------------:|----------:|------------:|------------:|----------:|
| SWup     | baseline     |  9.41017  |  5.21552   | 1.28454  | 0.981572 |  1.98556   | 25.7644   | 13.0951   | 0.358198 |  5.21552   | 0.28454     | 0.0184279 |   0.254792  |   0.0363237 | 0.152369  |
| SWup     | detailed     | 16.5365   | 15.3932    | 1.44379  | 0.98319  |  0.570792  | 45.6138   | 22.6496   | 0.495472 | 15.3932    | 0.443793    | 0.01681   |   0.196081  |   0.0541131 | 0.1702    |
| LWup     | baseline     |  9.85835  |  2.18432   | 1.16133  | 0.982052 |  5.56402   | 30.3822   | 14.5458   | 0.260221 |  2.18432   | 0.161327    | 0.0179484 |   6.92233   |   0.454075  | 0.0772876 |
| LWup     | detailed     | 12.912    | -3.95964   | 1.17171  | 0.978643 | 12.0485    | 26.2085   | 16.0803   | 0.282014 |  3.95964   | 0.171708    | 0.0213567 |   7.48254   |   0.507131  | 0.107482  |
| Qle      | baseline     | 24.8863   |  0.694153  | 0.813866 | 0.829034 | 16.7418    | 32.7873   | 40.4721   | 0.559403 |  0.694153  | 0.186134    | 0.170966  |   0.0513509 |   0.233494  | 0.249698  |
| Qle      | detailed     | 25.9644   |  2.25842   | 0.820925 | 0.820228 | 16.6303    | 34.2339   | 41.4416   | 0.572037 |  2.25842   | 0.179075    | 0.179772  |   0.0983766 |   0.329956  | 0.223875  |
| Qh       | baseline     | 32.1871   |  4.96527   | 0.74697  | 0.860485 | 26.1905    | 47.5103   | 46.5524   | 0.521969 |  4.96527   | 0.253031    | 0.139515  |   0.0430928 |   0.0442717 | 0.271729  |
| Qh       | detailed     | 29.3408   | -0.771113  | 0.797522 | 0.86495  | 17.5772    | 41.1893   | 44.91     | 0.506367 |  0.771113  | 0.202479    | 0.13505   |   0.0535324 |   0.186646  | 0.149452  |
| SoilTemp | baseline     |  1.42887  | -1.00191   | 0.999414 | 0.986425 |  0.972822  |  1.33003  |  1.83773  | 0.164727 |  1.00191   | 0.000589509 | 0.0135753 |   1.17936   |   0.0333794 | 0.0866775 |
| SoilTemp | detailed     |  1.52853  | -1.12711   | 1.01341  | 0.986436 |  1.09029   |  1.12293  |  1.9211   | 0.166345 |  1.12711   | 0.0134017   | 0.0135636 |   0.92941   |   0.0370211 | 0.088978  |
| Qtau     | baseline     |  0.106557 | -0.0450427 | 0.648284 | 0.881188 |  0.0223837 |  0.265566 |  0.165969 | 0.527022 |  0.0450427 | 0.351717    | 0.118812  |   0.0696758 |   0.154682  | 0.236319  |
| Qtau     | detailed     |  0.101162 | -0.0317386 | 0.676065 | 0.885589 |  0.0218656 |  0.239778 |  0.157669 | 0.509541 |  0.0317386 | 0.323936    | 0.114411  |   0.0246176 |   0.0802755 | 0.219466  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### out of range: baseline

 - Ensemble SWup min value of -10.8688 is less than expected 0.0 [W/m2]
 - Ensemble alb min value of -0.1004 is less than expected 0.0 [1]
 - Ensemble Albedo min value of -448.6694 is less than expected 0.0 [1]

### out of range: detailed

 - Ensemble Qanth min value of -26.7495 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

