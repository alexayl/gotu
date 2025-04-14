# GOTU: Generalization on the Unseen, Logic Reasoning, and Degree Curriculum

This repository contains the implementation of the GOTU framework for the ECE 570 Course Project (Spring 2025). The project explores the generalization capabilities of Transformer architectures on unseen domains and reimplements Degree Curriculum Learning.

## Overview

[See the demo video here](https://drive.google.com/file/d/1iOuMvEazJn0NulrlIaCbfFgfh3_S5ym_/view?usp=sharing)

The GOTU framework is designed to:
1. **Prove the minimum-degree bias** of Transformer architectures.
2. **Reimplement Degree Curriculum Learning**, a method to improve generalization by gradually increasing the complexity of training data.

The implementation is based on the work of [Abbe et al., 2023]( https://proceedings.mlr.press/v202/abbe23a.html) and uses components adapted from the [lucidrains/vit-pytorch](https://github.com/lucidrains/vit-pytorch) library.

## Features

- Implementation of a Transformer-based architecture for logic reasoning tasks.
- Support for Degree Curriculum Learning to enhance model training.
- Visualization of Fourier coefficients and test losses for analysis.
- Predefined functions and unseen domain screeners for experiments.

## Requirements

This was run on Google Colab with an Nvidia A100 GPU.

Install the dependencies using:
```bash
pip install -r requirements.txt
```
