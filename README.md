# Deep Learning for Spatio-Temporal Weather Forecasting

This repository contains a **pedagogical deep learning demo** illustrating how neural networks can be used for **spatio-temporal weather forecasting**.

The demo is designed as part of the *Deep Learning* course taught at ISAE-Supaero, and accompanies an educational video explaining the concepts, models, and results.

The demo focuses on **ConvLSTM-based forecasting** and compares learned models to a classical **persistence baseline**, following ideas from recent data-driven weather prediction research.

---

## Objectives

The goals of this project are to:

* Demonstrate how deep learning models can predict future weather fields from past observations
* Illustrate the strengths and limitations of **ConvLSTM** architectures
* Provide a clear comparison with a strong meteorological baseline (persistence)
* Offer an interpretable and reusable codebase for students discovering spatio-temporal deep learning

This demo emphasizes **understanding and interpretation**, not just raw performance.

---

## Ease of Use and Reproducibility

Ease of use is a key objective of this demo. The repository is intended to be run and modified by other students, possibly with limited prior experience in deep learning or scientific Python environments.

To ensure reproducibility and accessibility, the project follows these principles:

* **Clear installation instructions** with a minimal and explicit set of dependencies
* **Well-documented code and notebooks**, with explanations of each major step
* **Simple execution workflow**, allowing users to quickly reproduce the results
* **Usage examples**, so students can focus on understanding the models rather than debugging setup issues

All required steps to install dependencies, prepare the environment, and run the demo are documented below.

---

## Installation

### 1. Create a virtual environment (recommended)

```bash
conda env -n dl_weather_env
conda activate dl_weather_env
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

Main dependencies include:

* `numpy`
* `matplotlib`
* `torch`
* `xarray`
* `netCDF4`
* `scikit-learn`

---

## Usage

The main entry point of the demo is the Jupyter notebook:

```
DL_forecast_weather.ipynb
```

Then open the notebook and execute the cells sequentially.

The notebook is structured as follows:

1. Loading and preprocessing spatio-temporal weather data
2. Definition of the ConvLSTM model
3. Model training and prediction
4. Comparison with a persistence baseline
5. Visualization and interpretation of the forecasts

Each section contains explanatory comments to guide the reader through the methodology and results.

---

## Reference Article

The project is inspired by the following paper:

**Pangu-Weather: A 3D High-Resolution System for Fast and Accurate Global Weather Forecast**
[https://arxiv.org/pdf/2211.02556](https://arxiv.org/pdf/2211.02556)

While *Pangu-Weather* relies on large Transformer-based architectures and massive computational resources, this demo focuses on **lighter spatio-temporal models** to highlight the fundamental ideas behind data-driven weather forecasting before introducing large-scale systems.