# Computational Theory Assessment

This repository contains my assessment for the Computational Theory module.

## Contents
- `problems.ipynb`: the [Jupyter](https://jupyter.org/) notebook with all problems, explanations, code and tests
- `requirements.txt`: the approved Python packages

## Setup
Requires [Python 3](https://www.python.org/downloads/) and [Git](https://git-scm.com/).

```bash
git clone https://github.com/obnwachukwu/computational-theory.git
cd computational-theory
python -m venv .venv
.venv\Scripts\activate        # Windows (macOS/Linux: source .venv/bin/activate)
pip install -r requirements.txt
```

See the Python documentation for [`venv`](https://docs.python.org/3/library/venv.html) and the [pip user guide](https://pip.pypa.io/en/stable/user_guide/) for more on these steps.

## Usage
Open `problems.ipynb` in [VS Code](https://code.visualstudio.com/docs/datascience/jupyter-notebooks) or [JupyterLab](https://jupyterlab.readthedocs.io/), select the `.venv` kernel, and click **Run All**.

## Tools and references
- [NumPy](https://numpy.org/doc/stable/): used for fixed-width 32-bit unsigned integers (`numpy.uint32`)
- [FIPS 180-4 Secure Hash Standard](https://nvlpubs.nist.gov/nistpubs/fips/nist.fips.180-4.pdf): the specification for SHA-256 that the problems are based on
- [GitHub Issues](https://docs.github.com/en/issues): used to track progress on each problem
