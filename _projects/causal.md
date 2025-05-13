---
layout: page
title: Causal Inference Under Network Interference
description: March 2024 - August 2024
img: assets/img/projects_pic/causal.png
importance: 1
category: research
related_publications: false
---

Experiments in medical trials often suffer from **interference**, where the treatment status of an individual influences others' outcomes. To identify and evaluate causal effects, practitioners often study the **total treatment effect** (TTE), the average difference of the outcomes when everyone is treated versus not treated; however, few estimation methods account for interference without complete knowledge of the underlying social network. A recent line of work circumvents this by recasting the estimation task as a polynomial regression problem using the samples from a **staggered roll-out design**, in which treatment is incrementally given to a random subset of individuals. While this approach produces graph agnostic, unbiased estimators, it often exhibits unsuitably large variance. Addressing this, our work investigates unbiased estimation methods that take advantage of sampling at more stages to compensate for observation noise without requiring knowledge of the network. Under the special case of linear additive outcome models, we construct an estimator by fitting samples using ordinary least squares. For this method, we derive a tight bound on the amount of observation noise required for it to be beneficial to sample at more stages. Our bound is independent of the number of roll-out increments and can be verified with numerical simulations. We also propose estimators that can be used for more general outcome models and discuss preliminary numerical results on their performance.

See here for my [JMM 2025 Slides](https://drive.google.com/file/d/13pxdCyuKHRWXsGnRmJmJyzzClWmjzroq/view).

