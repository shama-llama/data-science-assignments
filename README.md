# Data Science Assignments

[![Python](https://img.shields.io/badge/Python-3.12+-3776AB?logo=python&logoColor=white)](https://docs.python.org/3.12/)
[![NumPy](https://img.shields.io/badge/NumPy-2.3.x-4DABCF?logo=numpy&logoColor=white)](https://numpy.org/doc/stable//release/2.3.0-notes.html)
[![SciPy](https://img.shields.io/badge/SciPy-1.16.x-003786?logo=scipy&logoColor=white)](https://docs.scipy.org/doc/scipy/release/1.16.0-notes.html)
[![Pandas](https://img.shields.io/badge/Pandas-2.3.x-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/pandas-docs/version/2.3/index.html)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.7+-F7931E?logo=scikit-learn&logoColor=white)](https://scikit-learn.org/stable/whats_new/v1.7.html)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository is a collection of assignments that were done as part of the Data Science (CoSc 6262) course. The notebooks cover fundamental topics and practical applications of core Python libraries for data analysis, scientific computing, and machine learning.

## Topics

- **NumPy:** Open source project for numerical computing with Python.
- **Pandas:** Open source data analysis and manipulation tool.
- **SciPy:** Tools for array computing and specialized data structures.
- **scikit-learn:** Tools for predictive data analysis.

## Datasets

> Kaggle, “Titanic - Machine Learning from Disaster,” Kaggle Competitions, 2012. [Online]. Accessed: Apr. 25, 2025. Available: [https://www.kaggle.com/c/titanic/data](https://www.kaggle.com/c/titanic/data).
>
> C. Zhang, “IMDB 5000 Movie Dataset,” Kaggle Datasets, [Online]. Accessed: Apr. 25, 2025. Available: [https://www.kaggle.com/datasets/carolzhangdc/imdb-5000-movie-dataset](https://www.kaggle.com/datasets/carolzhangdc/imdb-5000-movie-dataset).

## Project Setup

This project uses `uv` for package management. `uv` is an extremely fast Python package and project manager, written in Rust that can be used as a drop-in replacement for `pip`, `pip-tools`, `pipx`, `poetry`, `pyenv`, `twine`, `virtualenv`.

- **`uv` Installation**

    ```bash
    curl -LsSf https://astral.sh/uv/install.sh | sh
    ```

- **Clone the Repository:**

    ```bash
    git clone https://github.com/shama-llama/data-science-assignments.git
    cd data-science-assignments
    ```

- **Create a Virtual Environment and Install Dependencies with `uv`:**

    ```bash
    uv venv
    uv pip install -e .
    ```

- **Activate the Virtual Environment:**

    ```bash
    source .venv/bin/activate
    ```

- **Launch Jupyter Notebook:**

    ```bash
    jupyter notebook
    ```

    Navigate to the `notebooks/` directory to run the analysis.

## License

This project is licensed under the terms of the [MIT](LICENSE) open source license.
