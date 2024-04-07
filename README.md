# Cointegration 
Cointegration is the key trigger in statistical arbitrage for correlated pair,  measuring inconsistency
This algorithm implemented strong Monotonicity, guarantees convergence and stability properties, also implies cocoercivity

## Navigation
[Pairs Casuality Research with ARIMA Forecasting](https://github.com/ventositwaitang/A-Cointegration-Learning/blob/main/Pairs%20Trading%20Strategy%20Study%20with%20ARIMA%20Model%20Forecasting.pdf)

Explanation of Homoscedasticity with normal diffused (white noise)
```bash
ADF_Cointegration.ipynb
```


diffusion convergence with drift term
```bash
KPSS_Cointegration.ipynb
```

### Future direction
* to be refined by Grid Search for time-window & stop-profit hyper-param, and calibrating divergent adjusting factor (Cocoercivity, a basin hopping parameter for long-term drift, with Nadam iteration)

* adding momentum rules(MA cross/ RSI/ tailormade Alpha) in practice

* as Multi-asset Pricing Model by Second-Order Cone Programming (Solver for Linear/ Quadratic(non-linear) Gaussian simulation) with neural autograd
