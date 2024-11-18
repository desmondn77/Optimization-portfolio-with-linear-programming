# Optimization portfolio with linear programming

![bitcoin-btc-ethereum-eth-binance-260nw-2186954251](https://github.com/user-attachments/assets/c351fbc2-fa4f-4c50-8715-c0a47eff547a)


## List of Contents
* Overview
* Construction steps
    1. Defining the Optimization Problem
    2. Objective Function
    3. Constraints
    4. Solving the Optimization Problem
    5. Optimization Results
    6. Calculating Portfolio Return and Risk
    7. Displaying Results
* Additional Explanation
* Conclusion

## Overview
Linear programming is one of the powerful ways with mathematical concept that can help to optimize mathematical methods and models. The concept of linear optimization, which is derived from this linear programming, has wide applications in various fields. The use of this concept in financial markets has been done to some extent, but it is not common in its deep form.
Over the past few days I have been working on a linear optimization based code to arrive at an optimal asset portfolio. This code works by using an objective function and a series of constraints.
There are different solvers that are used to solve linear programming. Pulp and Pyomo are among these. Here scipy library is used to solve linear programming.

## What are the result and outputs?
In this example, I chose 4 cryptocurrencies (including Bitcoin, Ethereum, Binance Coin, and Tron) for comparison. Finally, by calculating the variance and difference factors, the fluctuations of each currency during one year have been mentioned. According to this factor and other factors, the optimal portfolio for these 4 cryptocurrencies is suggested at the end, which can help the user in short-term and to some extent long-term investment.

## How can this project be optimized?
Optimizing this linear programming is possible by providing more intelligent models. Also, in my opinion, more complete answers can be provided for this built model. For example, by calculating the standard deviation, beta or similar methods, more accurate information can be obtained.
In the next versions, this code can be converted into an interactive project and receive items from the user.

## Refrences
1. [Mokhtar Bazaraa](https://www.amazon.com/Programming-Network-Mokhtar-Bazaraa-2010-01-15/dp/B01K0PQ6R0/ref=sr_1_5?dib=eyJ2IjoiMSJ9.BzsqdCiQoMq2_CIl5_fNaLocly2MNtgkq-Kz7AQ_2WFqhhemPdgf93RS-bmq_yLsMTKK_gM3Wo21qTMPvLPzlg.wJSyHRXavL5eYLjiWSHpiyabdW0CuRViXoS_uiOsbls&dib_tag=se&qid=1731919698&refinements=p_27%3AMokhtar+S.+Bazaraa&s=books&sr=1-5)
2. [Scipy Docs](https://docs.scipy.org/doc/scipy/)
3. [CoinGecko](https://www.coingecko.com/en/api)
