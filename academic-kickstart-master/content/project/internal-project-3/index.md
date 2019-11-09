---
title: Calibration of the Financial Model Based on Market Data (S&P 500)
summary: Implemented in Matlab. Analysis of implied volatility (smile). Manipulation of the Black-Scholes Model.
tags:
- Quantitative Finance
- Matlab
- Implied Volatility
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

The goal of this project was to calibrate financial models applying numerical methods. Using the set of market data (S&P 500; dataset contains 280 strike values for different maturities), the implied volatility (volatility smile) was calibrated in the Black-Scholes model for call and out Europian Options. The algorithm of Newton was used to calibrate implied volatility. The existence and unicity of the solution was investigated mathematically. Besides that Vega of un option was investigated.

As an additional practical problem an implied volatility for call options traded on the London Internetional Financial
Futures and Option Exchange (LIFFE, as reported in the Financial Times on Wednesday, 22 Audust
2001) was calibrated. The data is for the FTSE 100 index, which is an average of 100 shares quoted on the London
Stock Exchange.

The project was implemented in Matlab.

<a href="">

</a>
