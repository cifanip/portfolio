---
title: Pairs Trading
layout: default
---

# Pairs Trading

In essence, pairs trading aims to construct a mean-reverting process by combining price signals that contain drift. If such an endeavour is successful, one obtains a statistical arbitrage opportunity. A long position initiated at a price well below the mean of the process will generate a positive return when the process will reveret to its mean. The opposite is be true for a short position. 

## 1. Theory
The mathematics behind pairs trading is known as **cointegration**. In the following, I will introduce the necessary tool to understand cointegrated processes.

### VAR(p) processes
The vector autoregressive model of order $p$, namely VAR(p), is defined as follows:

$$
y_t = \nu + A_1 y_{t-1}+ ... + A_p y_{t-p} + u_t, \qquad t > p \qquad\qquad  (1.0)
$$
