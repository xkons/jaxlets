## Differentiable and gpu enabled fast wavelet transforms in jax. 

## Features:
- 1d forward and backward fwt implemented in `conv_fwt.py`.
- 2d forward and backard fwt methods are part of the `conv_fwt_2d.py` module.

## Installation:
- Head to https://github.com/google/jax#installation and follow the procedure described there.
- Install pytest `pip install -U pytest`
- Clone this repository `git clone https://github.com/v0lta/jaxlets`
- Move into the new directory `cd jaxlets`
- To verify your version of jax-wavelets type `pytest`.

## Goals:
- In the spirit of jax the aim is to be 100% pywt compatible. Whenever possible, interfaces should be the same
  results identical.

## Coming up:
- Wavelet packets (TODO)
- Interface improvements
- Extended jit support.

## Feedback:
This is an early release, if you have questions or run into issues, please let me know.
