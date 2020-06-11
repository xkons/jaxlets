## Differentiable and gpu enabled fast wavelet transforms in jax. 

## Features:
- 1d forward and backward fwt
- 2d forward and backard fwt (Todo)
- Wavelet packets (TODO)

## Installation:
- Head to https://github.com/google/jax#installation and follow the procedure described there.
- Install pytest `pip install -U pytest`
- Clone this repository `git clone https://github.com/v0lta/jax-wavelets`
- Move into the new directory `cd jax-wavelets`
- To verify your version of jax-wavelets type `pytest`.

## Goals:
- In the spirit of jax we aim to be 100% pywt compatible. Whenever possible, we want the same interfaces and the same results.
