# PyTorch & Data Analysis Playground

This repo is my personal workspace for learning and experimenting with **PyTorch** and **simple data analysis**.

It contains small models, training loops, notebooks, and quick experiments.  
Some code is clean, some is exploratory, and some is just me trying things out.

## What’s inside

- PyTorch model experiments
- Simple regression and neural network examples
- Training / validation loops
- Loss function experiments
- Basic data analysis with Python
- Notebooks and small scripts

## Repo structure

```text
.
├── notebooks/        # Jupyter notebooks with experiments
├── src/              # Reusable Python code (when something becomes stable)
├── requirements.txt  # Python dependencies
├── .gitignore
└── README.md
```

## Notebooks

| Notebook                              | Description                                                                                                                                      |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| `01_data_understanding.ipynb`         | EDA on the Ames Housing dataset (2930 rows × 82 cols) — loading, summary stats, missing values, distributions, and feature exploration.          |
| `02_understanding_pytorch.ipynb`      | PyTorch basics: device setup (CPU/CUDA/XPU), tensor operations, and a CPU vs XPU matrix multiplication benchmark (~4.2x speedup on XPU).         |
| `03_learning_the_training_loop.ipynb` | Low-level training loop from scratch: manual forward/backward passes, MSE loss, SGD optimizer, and epoch-by-epoch loss tracking on housing data. |

## Links

[Amesh housing dataset ](https://www.kaggle.com/datasets/shashanknecrothapa/ames-housing-dataset?select=AmesHousing.csv)
