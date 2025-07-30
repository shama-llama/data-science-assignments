# Data Science Assignments

![Python](https://img.shields.io/badge/Python-3.12+-3776AB?logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-2.3.x-4DABCF?logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-1.16.x-003786?logo=scipy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.3.x-150458?logo=pandas&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.7+-F7931E?logo=scikit-learn&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

This repository contains a collection of assignments completed as part of Data Science—CoSc 6262 curriculum. The notebooks cover concepts and practical applications of core Python libraries for scientific computing and machine learning.

## Topics

- **NumPy:** Foundational numerical computing and array manipulation.
- **Pandas:** Data loading, cleaning, and analysis with DataFrames.
- **SciPy:** Scientific and technical computing functions.
- **Scikit-learn:** Implementation of machine learning algorithms.

## Project Setup

This project uses `uv` for package management. `uv` is an extremely fast Python package and project manager, written in Rust that can be used as a drop-in replacement for `pip`, `pip-tools`, `pipx`, `poetry`, `pyenv`, `twine`, `virtualenv`.

- **`uv` Installation**

    ```bash
    curl -LsSf https://astral.sh/uv/install.sh | sh
    ```

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/shama-llama/data-science-assignments.git
    cd data-science-assignments
    ```

2. **Create a Virtual Environment and Install Dependencies with `uv`:**

    ```bash
    uv venv
    uv pip install -e .
    ```

3. **Activate the Virtual Environment:**

    ```bash
    source .venv/bin/activate
    ```

4. **Launch Jupyter Notebook:**

    ```bash
    jupyter notebook
    ```

    Navigate to the `notebooks/` directory to run the analysis.

## License

This project is licensed under the terms of the [MIT](LICENSE) open source license.
