# Option_Pricing_with_Crank-Nicolson_Approximation
Pricing for both European and American Option using Crank-Nicolson finite difference approximation

1. Design and write a python class to price European/American options using the CrankNicolson approximation. It will also produce (1) delta, (2) gamma, and (3) theta Greeks for the same option.

2. Use the program to price following options, and plot the intermediate option values:
    i. European put option with the following parameters:
       Spot= 110, Strike=100, vol=30%, Maturity=1yr, r=0.05%, d=0%
          o Calculate the option premium
          o Calculate Delta, Gamma, and Theta
          o Check the above results against the analytical solution you implemented before
    ii. European call option with the following parameters:
        Spot= 90, Strike=100, vol=30%, Maturity=1yr, r=0.01%, d=0.15%
          o Calculate the option premium
          o Calculate Delta, Gamma, and Theta
          o Check the above results against the analytical solution you implemented before
    iii. American put option with the following parameters:
        Spot= 110, Strike=100, vol=30%, Maturity=1yr, r=0.05%, d=0%
          o Calculate the option premium
          o Calculate Delta, Gamma, and Theta
    iv. American call option with the following parameters:
        Spot= 90, Strike=100, vol=30%, Maturity=1yr, r=0.01%, d=0.15%
          o Calculate the option premium
          o Calculate Delta, Gamma, and Theta
