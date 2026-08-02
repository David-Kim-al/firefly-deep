# Firefly Deep

![CI](https://github.com/David-Kim-al/firefly-deep/actions/workflows/ingest.yml/badge.svg) ![Python](https://img.shields.io/badge/python-3.10-blue) ![License](https://img.shields.io/github/license/David-Kim-al/firefly-deep) ![Platform](https://img.shields.io/badge/platform-linux%20%7C%20macOS-lightgrey)

萤火入深谷，训练日志化为星图。

A visualization toolkit for distributed deep learning training logs.
Parses TensorBoard / W&B exports and renders interactive dashboards
showing loss landscapes, gradient flows, and convergence trajectories.

## Stack
- Python backend (pandas, matplotlib, plotly)
- Static HTML dashboards auto-deployed via GitHub Pages
- Hourly scheduled refreshes from connected experiment trackers

## Philosophy
Training logs are rich signals. Firefly Deep turns them into stories.

Status: experimental. Runs on GitHub Actions.
