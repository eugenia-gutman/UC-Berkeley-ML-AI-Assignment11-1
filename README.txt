Sequential feature selection was performed in a Linear Regression model to identify the factors that most strongly influence used car prices. The top 20 features account for 64% of the variation in used car prices (R-squared = 0.64). All selected features were found to be statistically significant.


Model Summary:
==============================================================================
Dep. Variable:                  price   R-squared:                       0.638
Model:                            OLS   Adj. R-squared:                  0.638
Method:                 Least Squares   F-statistic:                     7612.
Date:                Sun, 10 May 2026   Prob (F-statistic):               0.00
Time:                        23:09:06   Log-Likelihood:            -8.8692e+05
No. Observations:               86284   AIC:                         1.774e+06
Df Residuals:                   86263   BIC:                         1.774e+06
Df Model:                          20                                         
Covariance Type:            nonrobust                                         
==========================================================================================
                             coef    std err          t      P>|t|      [0.025      0.975]
------------------------------------------------------------------------------------------
const                   2.363e+04    197.757    119.475      0.000    2.32e+04     2.4e+04
cylinders               1322.8105     20.782     63.651      0.000    1282.077    1363.544
odometer                  -0.0519      0.001    -97.849      0.000      -0.053      -0.051
age                     -780.0072      5.490   -142.084      0.000    -790.767    -769.247
manufacturer_dodge     -2217.5123    130.673    -16.970      0.000   -2473.630   -1961.395
manufacturer_honda      1638.3572    106.233     15.422      0.000    1430.142    1846.573
manufacturer_lexus      3323.8813    174.335     19.066      0.000    2982.186    3665.577
manufacturer_nissan    -1698.6888    107.144    -15.854      0.000   -1908.690   -1488.688
manufacturer_toyota     2845.8747     87.083     32.680      0.000    2675.192    3016.557
condition_good           839.5887     54.331     15.453      0.000     733.100     946.078
fuel_diesel             8877.3031    120.582     73.620      0.000    8640.964    9113.643
title_status_clean      1610.6206    107.622     14.966      0.000    1399.683    1821.558
transmission_automatic -1764.8917    107.229    -16.459      0.000   -1975.059   -1554.725
transmission_other      4666.2638    141.671     32.937      0.000    4388.589    4943.938
drive_fwd              -3061.7989     67.566    -45.315      0.000   -3194.228   -2929.370
type_SUV               -2811.8567     70.631    -39.811      0.000   -2950.292   -2673.422
type_hatchback         -4491.7692    141.183    -31.815      0.000   -4768.488   -4215.051
type_mini-van          -3160.9443    169.952    -18.599      0.000   -3494.049   -2827.839
type_sedan             -4558.0230     77.172    -59.063      0.000   -4709.279   -4406.767
type_van               -2145.2949    147.364    -14.558      0.000   -2434.127   -1856.463
type_wagon             -4683.7227    157.988    -29.646      0.000   -4993.378   -4374.068
==============================================================================
Omnibus:                    14833.908   Durbin-Watson:                   2.003
Prob(Omnibus):                  0.000   Jarque-Bera (JB):            70092.126
Skew:                          -0.766   Prob(JB):                         0.00
Kurtosis:                       7.141   Cond. No.                     1.19e+06
==============================================================================