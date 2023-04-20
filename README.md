# Optimization of Mixture Models on time series networks encoded by Visibility Graphs: An analysis of the US electricity market

by
Carlo Mari,
Cristiano Baldassari.

This repository contains the code to reproduce all the results reported in the paper Optimization of Mixture Models on time series networks encoded by Visibility Graphs: An analysis of the US electricity market.

## Abstract
We propose a fully unsupervised network-based methodology for estimating Gaussian Mixture Models on financial time series by maximum
likelihood using the Expectation-Maximization algorithm. Visibility Graph-structured information of observed data is used to initialize the
algorithm. The proposed methodology is applied to the US wholesale electricity market. We will show that encoding time series through Visibility Graphs allows us to capture well the behavior of the time series and the nonlinear interactions between observations. The results reveal that the proposed methodology outperforms more established approaches.

## Reproducing the results

The provided Python [notebook](https://github.com/cbaldassari/time_series_network/blob/main/time_series_network.ipynb) contains the code that implements the method of initialization we propose in the paper and covers all the paper's workflow.

## Getting the code
You can download a copy of all the files in this repository by cloning the
[git](https://github.com/cbaldassari/time_series_network) repository:
    git clone https://github.com/cbaldassari/time_series_network
or [download a zip archive](https://github.com/cbaldassari/time_series_network/archive/refs/heads/main.zip).
