# q2-classo
[![BSD License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)
[![Python version](https://img.shields.io/badge/python-%3E3.6-blue)](https://www.python.org/)

*A [QIIME 2](https://qiime2.org) plugin for solving **constrained sparse regression and classification** problems with microbiome data including:*

- Lasso regression with taxonomic constraints
- Cross-validation for hyperparameter selection
- Stability selection for feature selection
- Classification and regression tasks
- Tree-aggregated predictive modeling
- Interactive visualizations with model diagnostics

📚 [Documentation](https://github.com/Vlasovets/q2-classo) |
📂 [Tutorial & Examples](https://github.com/Vlasovets/q2-hdstats-docs)

---

## Installation

First, make sure you have the required dependencies installed:

```bash
conda install -c conda-forge zarr plotly
```

OR

```bash
pip install zarr plotly c-lasso
```

Next to install the plugin:

```bash
pip install git+https://github.com/bio-datascience/q2-classo-latest.git
qiime dev refresh-cache
```

---

## Usage Tutorial

A complete tutorial on using `q2-classo` for microbiome data analysis — including preprocessing, CLR transformation, constrained regression, and visualization — is available in the repository examples.

👉 **[Quick Start Guide](https://github.com/Vlasovets/q2-hdstats-docs)**

This tutorial includes:

- Random data generation and basic workflow
- CLR transformation and taxonomic aggregation
- Constrained lasso regression with cross-validation
- Stability selection for robust feature selection
- HIV sCD14 prediction case study
- Interactive visualization of model results

---

## Citation

If you use `q2-classo`, please cite:

> Bien, J., Yan, X., Simpson, L. and Müller, C. L. (2020). **Tree-Aggregated Predictive Modeling of Microbiome Data**. *arXiv preprint arXiv:2002.08698*.

## Related Projects

- [`c-lasso`](https://github.com/Leo-Simpson/c-lasso): Python solvers for constrained lasso problems
- [`q2-gglasso`](https://github.com/Vlasovets/q2-gglasso): QIIME 2 plugin for graphical lasso problems
- [QIIME 2](https://qiime2.org): Extensible microbiome analysis platform

---

## License

BSD 3-Clause License. See [LICENSE](./LICENSE) for details.
