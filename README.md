# Cointegration 
Cointegration is the key trigger in statistical arbitrage for correlated pair,  measuring inconsistency and stability properties

## Navigation

Explanation of Homoscedasticity with normal diffused (white noise)
```bash
ADF_Cointegration.ipynb
```


diffusion convergence with drift term
```bash
KPSS_Cointegration.ipynb
```

Thesis: [A Pairs Causality Research with ARIMA Forecasting](https://github.com/ventositwaitang/A-Cointegration-Learning/blob/main/Pairs%20Trading%20Strategy%20Study%20with%20ARIMA%20Model%20Forecasting.pdf)

### Future direction
* to be refined by Grid Search for time-window & stop-profit hyper-param, and calibrating divergent adjusting factor (Cocoercivity, a basin hopping parameter for long-term drift)

* adding momentum rules(MA cross/ RSI/ tailormade Alpha) in practice (Hurst exponent>0.5: Long Vol by trending α momentum; Hurst exponent<0.5: Short Vol by Mean Reversion) (e.g. 5 lag=0.86 means more reverse in short term and 20 lags=0.91 means more trendy in longer term)

* as Multi-asset Pricing Model by Second-Order Cone Programming (Solver for Linear/ Quadratic(non-linear) Gaussian simulation) with neural autograd


