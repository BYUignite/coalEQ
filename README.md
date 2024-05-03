# Coal thermodynamic data and equilibrium

* Set NASA polynomial coefficients for coal.
* Coal heat capacity correlation: [D. Merrick, Fuel 62(5):540-546 (1983)](https://www.sciencedirect.com/science/article/pii/0016236183902235)
* Coal entropy correlation: [W. Eisermann et al., Fuel Processing Technology 3(1):39-53 (1980)](https://www.sciencedirect.com/science/article/pii/0378382080900223)
* The NASA polynomial coefficients are then used to create a coal.cti file for use in Cantera.
* Note, the NASA correlations are given separately in low and high temperature regions. Coefficients in the high temperature region are constrained to give continuity between the regions.

[Link to notebook file](https://nbviewer.org/github/BYUignite/coalEQ/blob/master/coal_nasa_coefficients.ipynb)

