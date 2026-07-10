# Monte-Carlo-option-pricing-model
This project employs Monte Carlo simulation to price European & Asian options. Analytical methods like Black-Scholes fail for options such as Arithmetic Asian options. To tackle the problem of option pricing, Monte Carlo simulation is used to generate future stock paths. These paths are then used to generate European & Asian payoffs. Option price is obtained by averaging & discounting these payoffs.
Further, the convergence of monte carlo price is check with Black-Scholes price for European options. 
Finally, the model uses Antithetic Variates to reduce the variation of Monte Carlo estimator while keeping the same N (Number of simulations).
