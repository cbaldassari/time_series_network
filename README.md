# Optimization of Mixture Models on time series networks encoded by Visibility Graphs: An analysis of the US electricity market

by
Carlo Mari,
Cristiano Baldassari.

This repository contains the code to reproduce all the results reported in the paper Optimization of Mixture Models on time series networks encoded by Visibility Graphs: An analysis of the US electricity market.

## Abstract
We present a fully unsupervised network-based methodology for estimating Mixture Models on financial time series by maximum likelihood. By employing time series networks, we can use graph-structured infor-
mation of the observed data to initialize the Expectation-Maximization algorithm. We observed that by using Visibility Graph encoding of time series, graph-structured information can capture time series behav-
ior and nonlinear interactions between observations. We applied the proposed methodology for estimating Gaussian Mixture Models on the US wholesale electricity market. Results show that our method-
ology performs well by outperforming more established approaches.

## Reproducing the results

The provided Python [notebook](https://github.com/cbaldassari/time_series_network/blob/main/time_series_network.ipynb) contains the code that implements the method of initialization we propose in the paper and covers all the paper's workflow.

## Getting the code
You can download a copy of all the files in this repository by cloning the
[git](https://github.com/cbaldassari/time_series_network) repository:
    git clone https://github.com/cbaldassari/time_series_network
or [download a zip archive](https://github.com/cbaldassari/time_series_network/archive/refs/heads/main.zip).
