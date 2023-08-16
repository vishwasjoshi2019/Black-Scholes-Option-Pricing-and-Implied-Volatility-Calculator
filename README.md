# Black-Scholes Option Pricing and Implied Volatility Calculator

This Python script calculates option prices and implied volatilities using the Black-Scholes option pricing model. The Black-Scholes model is a widely used formula for estimating the theoretical price of European-style options and determining the implied volatility based on observed option prices.

## Getting Started

### Prerequisites
Make sure you have the following libraries installed:
- `numpy`
- `scipy`

You can install them using the following command:

```bash
  pip install numpy scipy
```


## How to Use
### 1.Running the Script: 
  Run the script using a Python interpreter. It will calculate option prices and implied volatilities based on the provided functions.

### 2. Functions:

- black_scholes_call(S, K, T, r, sigma): Calculates the theoretical call option price using the Black-Scholes formula.
- black_scholes_put(S, K, T, r, sigma): Calculates the theoretical put option price using the Black-Scholes formula and the call option price.
- implied_volatility(S, K, T, r, observed_price, opt): Estimates the implied volatility of an option given its observed price. The opt parameter should be set to 1 for calls and -1 for puts.
