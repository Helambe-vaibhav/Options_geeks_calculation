### Options_geeks_calculation
# Option Pricing and Implied Volatility Calculation

This repository contains a Python script for option pricing using the Black-Scholes formula and calculating implied volatility. The script calculates call and put option prices, as well as option Greeks (Delta, Gamma, Vega, Theta, Rho) for given parameters.

## Overview

This script demonstrates option pricing and implied volatility calculation using the Black-Scholes model. The following functionalities are included:

- Calculation of call and put option prices using the Black-Scholes formula.
- Calculation of implied volatility using the Newton-Raphson method.
- Calculation of option Greeks: Delta, Gamma, Vega, Theta, and Rho.

## Usage

To use the script, follow these steps:

1. Install required dependencies using:
   pip install numpy scipy


2. Open the `option_pricing.py` script.

3. Set the parameters according to your use case:
- `s`: Current asset price
- `k`: Strike price
- `t`: Time to expiration in years
- `r`: Risk-free rate
- `market_priceCE`: Market price of the call option
- `market_pricePE`: Market price of the put option

4. Run the script using a Python interpreter.

5. The script will output the implied volatility, option prices, and option Greeks for both call and put options.

## Example

For instance, if you have the following parameters:

- Current asset price (`s`): 19778.30
- Strike price (`k`): 19800
- Time to expiration (`t`): 1/365
- Risk-free rate (`r`): 6.835/100
- Market price of call option (`market_priceCE`): 43.7
- Market price of put option (`market_pricePE`): 70.5

Running the script will calculate and display the implied volatility, option prices, and option Greeks for both the call and put options.

## Conclusion

This script provides a practical implementation of option pricing using the Black-Scholes model and the calculation of implied volatility. It can be a valuable tool for anyone interested in options trading or quantitative finance.

---

**Disclaimer:** This script is provided for educational and informational purposes only. Options trading involves risks, and this script is not intended as financial advice. Use it at your own risk and make informed decisions when trading options.

