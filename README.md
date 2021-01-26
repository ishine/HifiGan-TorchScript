# Hifigan TorchScript

This repository contains a slighly modified version of https://github.com/jik876/hifi-gan
Modifications are done to ensure code is TorchScriptable via torch.jit.Script, which both allows for
optimizations and ensures full code coverage.

## Usage

You can find a nice and simple example on export_to_torchscript.py with included benchmarks for comparing speeds.


## Warning

This is an early commit, due to time limitations I were not able to do detailed testing and modifications
may not have execution parity with original repo. I will update this repo on weekend.