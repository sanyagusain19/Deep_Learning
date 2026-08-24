# Deep Learning

An educational repository containing Jupyter notebooks and implementations that demonstrate core deep learning concepts using TensorFlow and Keras.

[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)](https://jupyter.org/) [![TensorFlow](https://img.shields.io/badge/TensorFlow-%5E2.0-blue)](https://www.tensorflow.org/)

## Table of contents

- Overview
- Notebooks (what's inside)
- Getting started
  - Prerequisites
  - Installation
  - Running the notebooks
- Recommended workflow
- Tips & notes
- Contributing
- License
- Author

## Overview

This repo is a hands-on guide to important deep learning topics for learners and practitioners. It includes explanatory notebooks, runnable code examples, and experiments focused on model design, training, optimization, and common issues (like vanishing gradients).

The notebooks are written with an educational intent: to explain concepts with simple examples, plots, and runnable Keras/TensorFlow code.

## Notebooks (what's inside)

- `keras1.ipynb` — Deep learning fundamentals: building and training basic neural networks with Keras.
- `keras2.ipynb` — Intermediate/advanced Keras concepts and model architectures.
- `keras3.ipynb` — Optimization techniques, learning rate schedules, and training best practices.
- `early_stopping.ipynb` — Demonstrates early stopping as a regularization technique to prevent overfitting.
- `Vanishing_gradient.ipynb` — Explains the vanishing gradient problem and ways to mitigate it (initialization, activations, architecture).
- `regularisation.ipynb`— used regularizers such as l1 and l2 to reduce overfitting.
- `keras_pooling_demo.ipynb` —  Used Maxpooling for mnist dataset


## Getting started

These instructions will get you a copy of the project up and running on your local machine for exploration and experimentation.

### Prerequisites

- Python 3.8+ (3.10 recommended)
- pip
- Jupyter Notebook or JupyterLab or can work in google colab.
- A recent GPU and CUDA drivers if you plan to run larger experiments (optional)

### Recommended packages

It's best to create a virtual environment and install required packages. Example using venv:

```bash
python -m venv .venv
source .venv/bin/activate    # macOS / Linux
.\.venv\Scripts\activate   # Windows (PowerShell)
```

Install dependencies:

```bash
pip install -r requirements.txt
```

(If a requirements.txt is not present in the repo yet, install these core packages manually:)

```bash
pip install jupyterlab jupyter tensorflow keras numpy pandas matplotlib scikit-learn seaborn
```

### Installation (clone the repo)

```bash
git clone https://github.com/sanyagusain19/Deep_Learning.git
cd Deep_Learning
```

### Running the notebooks

Start Jupyter Lab / Notebook:

```bash
jupyter lab    # or: jupyter notebook
```

Open any notebook from the list, for example:

- `keras1.ipynb`
- `keras2.ipynb`

You can also run a single notebook directly:

```bash
jupyter notebook keras1.ipynb
```

## Recommended workflow

- Read the notebook descriptions above to pick a topic.
- Run the notebook cells top-to-bottom to reproduce results and plots.
- Tweak hyperparameters (learning rate, batch size, number of layers) to observe effects.
- If you add experiments, consider exporting results (CSV or saved model) into a `results/` folder and committing code changes separately from data.

## Tips & notes

- Use smaller datasets or fewer epochs when running on CPU to speed up iteration.
- For reproducibility, set seeds where appropriate and record package versions (e.g., with `pip freeze > requirements.txt`).
- Consider adding a `requirements.txt` or an `environment.yml` (for conda) to make setup easier for others.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/my-notebook`.
3. Make changes and commit: `git commit -m "Add explanation for ..."`.
4. Push to your branch and open a Pull Request.



## License

This repository does not include a license file. If you want this code and notebooks to be reusable by others, consider adding a LICENSE (MIT, Apache-2.0, or similar).

## Author

[sanyagusain19](https://github.com/sanyagusain19)

---

If you'd like, I can also:
- Add a `requirements.txt` generated from your environment or suggested packages.
- Add badges (CI, license) and a small example GIF showing notebook output.
- Update the repository description and topics. 
