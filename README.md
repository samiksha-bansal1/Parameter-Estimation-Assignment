# 📊 Parameter Estimation — Statistics Assignment

**Name:** Samiksha | **Roll No:** 102317096

---

## Overview

This assignment solves **Maximum Likelihood Estimation (MLE)** for parameters of two statistical distributions — Normal and Binomial.

---

## Problems

### Q1 — Normal Distribution: MLE of Mean (μ) and Variance (σ²)

**Given:** Random sample $(x_1, x_2, \ldots, x_n)$ from $N(\mu, \sigma^2)$

**PDF:**
$$f(x) = \frac{1}{\sqrt{2\pi\sigma^2}} \, e^{-\frac{(x_i - \mu)^2}{2\sigma^2}}$$

**Results (MLE Estimators):**

$$\hat{\mu} = \frac{\sum_{i=1}^{n} x_i}{n} \qquad \hat{\sigma}^2 = \frac{\sum_{i=1}^{n}(x_i - \mu)^2}{n}$$

---

### Q2 — Binomial Distribution: MLE of θ

**Given:** Random sample from $B(m, \theta)$, where $\theta \in (0,1)$ is unknown

**PMF:**
$$P(X_i = x_i) = \binom{m}{x_i} \theta^{x_i}(1-\theta)^{m - x_i}$$

**Result (MLE Estimator):**

$$\hat{\theta} = \frac{\sum_{i=1}^{n} x_i}{nm}$$

---

## Method

1. Write the **Likelihood Function** $L$
2. Take **log** → $\ln L$
3. **Differentiate** w.r.t. each parameter
4. **Equate to zero** and solve

---

## Topics Covered

- Maximum Likelihood Estimation (MLE)
- Normal Distribution
- Binomial Distribution
- Log-Likelihood Optimization
