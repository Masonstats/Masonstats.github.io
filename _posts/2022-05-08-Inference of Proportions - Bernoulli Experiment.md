---
layout: post
title: Inference of Proportions - A Bernoulli Experiment
featured-img: sleek
---

## Bernoulli experiment
Consider independent trials with only "success" and "failure", and if the probability of each success is $\theta$, then these experiments are called Bernoulli experiments with parameter $\theta$. And the distribution of whether the experimental result is "success" or "failure" is a Bernoulli $(\theta)$ distribution. If in n Bernoulli experiments, s experiments are successful (then there must be f = n-s failures). Therefore, the number of successes is said to follow a binomial distribution with parameters $(n,\theta)$. The Bernoulli distribution is a special case of the binomial distribution when n=1. We always hope to use the number or proportion of successful experiments to infer the parameter p. Formally, we can denote the observation x = (x1,,,) as the result of a Bernoulli experiment with parameter p. Each x takes the value 1 or 0, corresponding to "success" or "failure".

## Simple conjugate prior distribution
Taking the prior distribution p(p) of p as the conjugate prior distribution Beta(a,b), then s=x1+...+xn is a sufficient statistic. Then the posterior distribution is:
pppp

The posterior distribution is Beta(sss). If a quadratic loss function is used to estimate p, then:
Ppp

The commonly used "uninformative prior distribution" is a=b=1, then beta(1,1) is a uniform distribution U(0,1) in the [0,1] interval. At this time:
Ppp

The above model can be formally described by the following formula:
pppp


