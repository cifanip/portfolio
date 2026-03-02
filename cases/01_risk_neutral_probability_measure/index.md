## 1. Theory
The central concept required for our analysis is the martingale. The precise definition is the following:

<div class="env definition">
  <div class="env-title">
    <span class="env-name">(Martingale)</span>
  </div>

  <div class="env-body">
    A stochastic process $\{M(t)\}_{t\ge 0}$ is called a <strong>martingale</strong>
    with respect to the filtration $\{\mathcal{F}_t\}_{t\ge 0}$ if it is adapted to
    $\{\mathcal{F}_t\}_{t\ge 0}$, $M(t)\in L^1(\Omega)$ for all $t\ge 0$, and
    $$
    \mathbb{E}\!\left[M(t)\mid \mathcal{F}_s\right] = M(s), \qquad 0 \le s \le t,
    $$
    for all $t\ge 0$.
  </div>
</div>
