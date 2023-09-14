---
title: "PyTorch Forecasting"
date: 2022-03-22T13:34:19+01:00
draft: true
---

[Docs](https://pytorch-forecasting.readthedocs.io/en/stable/)
<!--more-->

### Super forecasting package

Recently I have been working on temporal forecasting of air pollution.

Forecasting is a key part of migigating the worst effects of exposure to air pollution. By making accurate short-term forecasts we can provide warnings to those at risk. Carrying out this work with state-of-the-art models in native PyTorch is fairly involved, especially when trying to forecast a number of different time series with common behaviours. Enter *Pytorch Forecasting*. This is a really tight package which makes this type of forecasting relatively simple. Built by a now BCGer, adding to native PyTorch, with recent models already implemented, most things just work. What more can we ask for - thanks [Jan!](https://github.com/jdb78).
