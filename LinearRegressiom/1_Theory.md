We will cover the theory behind the Linear Regression (LR) model first. The Wikipedia page for the LR model provides a suitable introduction to the mathematical formulation of this model.
Given a dataset of the form: $\lbrace y_{i}, x_{i1}, x_{i2}, \dots, x_{ip} \rbrace_{i = 1}^{n}$, LR models the relation between the $y_{i}$'s and the $x_{ip}$'s as:
```math
y_{i} = \theta_{0} + \theta_{1}x_{i1} + \dots + \theta_{p}x_{ip} + \epsilon_{i}.
```
Or, in the language of linear algebra:
```math
\mathbf{y} = \mathbf{X}\boldsymbol{\theta} + \boldsymbol{\epsilon}
```
