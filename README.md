# MOL Stock Autocorrelation Analysis

This repository contains a small empirical project analyzing the daily closing prices of MOL shares listed on the Budapest Stock Exchange (BSE). The goal is to explore the time-series properties of the price data, with a focus on autocorrelation and the white-noise hypothesis.

## Description

The analysis covers:

- Collection of daily closing prices for MOL from the official BSE source.
- Visualization of the price time series to inspect basic dynamics and trends.
- Computation of first-order autocorrelation for the price series.
- Statistical hypothesis testing of the autocorrelation coefficient.
- Plotting and interpretation of the autocorrelation function (ACF).
- Discussion of whether the underlying price process can be treated as white noise.

## Data

- **Asset:** MOL (MOL Hungarian Oil and Gas Plc.)
- **Frequency:** Daily closing prices
- **Source:** Budapest Stock Exchange (BSE) official website

Raw or preprocessed datasets should be placed in a `data/` directory (e.g. `data/mol_prices.csv`).

## Methods

The project applies standard tools from time-series analysis, including:

- Log-return or level-based transformations (depending on specification)
- Sample autocorrelation calculation
- Parametric test of autocorrelation significance
- ACF plotting for multiple lags
