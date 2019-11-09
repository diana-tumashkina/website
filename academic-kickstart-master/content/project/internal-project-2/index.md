---
title: Markov Chains in Finance
summary: Implemented in Matlab. Monte-Carlo Markov Chain, Dynamic Programming methods to price options were implemented.
tags:
- Quantitative Finance
- Matlab
- Monte-Carlo Markov Chain
- Dynamic Programming
- Black-Scholes Model
date: "2019-06-30T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: #Photo by rawpixel on Unsplash
  focal_point: Smart

#links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
#url_code: ""
#url_pdf: ""
#url_slides: ""
#url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

In this project, the binomial and trinomial asset pricing models were investigated. The calibration of the model parameters was done by different methods, in particular Cox-Ross-Rubinstein, Jarrow-Rudd, Desmond John Higham. One application of these models is the evaluation of options and obligations.

Several methods exist to price options and one of them is Monte-Carlo Markov Chain method (MCMC), typically used for pricing path-dependent options. Monte-Carlo Markov chain algorithm is used to simulate from complex statistical distributions by way of a local exploration of these distributions. This local feature avoids heavy requests on understanding the nature of the target, but it also potentially induces a lengthy exploration of this target, with a requirement on the number of simulations that grows with the dimension of the problem and with the complexity of the data behind it.

That is why we also investigate another method to price the option that is implemented by Dynamic Programming, which is iterative and more rapid.

Beside that the greeks (Delta, Gamma, Vega) for some options were investigated.

The project was implemented in Matlab.

<a href="">

</a>
