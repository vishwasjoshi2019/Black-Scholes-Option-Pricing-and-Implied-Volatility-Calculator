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
- implied_volatility(S, K, T, r, observed_price, opt): Estimates the implied volatility of an option given its observed price. The opt parameter should be set to 1 for     
  calls and -1 for puts.

### 3. Example Usage
```python
  implied_volatility(15325, 15350, 3.08, 0, 143, 1)
```

## NOTE
This script provides a basic implementation of the Black-Scholes model for educational purposes. Option pricing and implied volatility estimation involve more factors in real-world scenarios.


## Creator

This project was created by [Vishwas Joshi](https://github.com/vishwasjoshi2019).


[![GitHub](https://img.shields.io/badge/GitHub-%40vishwasjoshi2019-blue)](https://github.com/vishwasjoshi2019)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%40vishwasjoshi2019-blue)](https://www.linkedin.com/in/vishwasjoshi2019/)
[![Gmail](https://img.shields.io/badge/Gmail-vishwasjoshi2019%40gmail.com-red)](mailto:vishwasjoshi2019@gmail.com)
[![Institute Email](https://img.shields.io/badge/Institute%20Email-vishwas.j%40iitgn.ac.in-red)](mailto:vishwas.j@iitgn.ac.in)
[![Instagram](https://img.shields.io/badge/Instagram-%40cursed__geek-orange)](https://www.instagram.com/cursed_geek/)
[![Twitter](https://img.shields.io/badge/Twitter-%40Vishwas79116150-blue)](https://twitter.com/Vishwas79116150)
