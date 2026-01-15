# Deep Learning for Spatio-Temporal Weather Forecasting

This repository contains a **pedagogical deep learning demo** illustrating how neural networks can be used for **spatio-temporal weather forecasting**.

The demo is designed as part of the *Deep Learning* course taught at ISAE-Supaero, and accompanies an educational video explaining the concepts, models, and results.

The demo focuses on **ConvLSTM-based forecasting** and compares learned models to a classical **persistence baseline**, following ideas from recent data-driven weather prediction research.

## Objectives 

The goals of this project are to:

- Demonstrate how deep learning models can predict future weather fields
  from past observations
- Illustrate the strengths and limitations of **ConvLSTM** architectures
- Provide a clear comparison with a strong meteorological baseline (persistence)
- Offer an interpretable and reusable codebase for students discovering spatio-temporal deep learning

This demo emphasizes **understanding and interpretation**, not just performance.

## Reference Article

The project is inspired by the following paper:

[Pangu-Weather: A 3D High-Resolution System for Fast and Accurate Global Weather Forecast](https://arxiv.org/pdf/2211.02556)

While Pangu-Weather relies on large Transformer-based architectures, this demo focuses on **lighter spatio-temporal models** to highlight core concepts before introducing large-scale systems.


