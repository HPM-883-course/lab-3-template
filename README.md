# Lab 3: DML Implementation with DoubleML

HPM 883 — Advanced Quantitative Methods | Spring 2026

## Getting Started

1. Clone this repository locally
2. Open `hpm883-lab.Rproj` in RStudio or Positron
3. Run `renv::restore()` to install packages
4. Open `lab-3-dml.qmd` and follow along

## Required Packages

This lab uses `DoubleML`, `mlr3`, `mlr3learners`, `ranger`, `xgboost`, `glmnet`, and `data.table`. All are included in the `renv.lock` file.

## Troubleshooting

If `renv::restore()` fails, install packages manually:

```r
install.packages(c("DoubleML", "mlr3", "mlr3learners", "ranger", "xgboost", "glmnet", "data.table", "ggplot2"))
```
