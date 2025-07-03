# Estimations with PERT, Beta Distribution and Monte Carlo

This repository contains the Jupyter Notebook **estimations_pert_beta_MC.ipynb**, which demonstrates methods for project estimation and risk analysis using:

- **PERT (Program Evaluation Review Technique)**
- **Beta distributions**
- **Monte Carlo simulations**

The notebook can be adapted to estimate project durations, costs, or any other variables where uncertainty modeling is needed.

You can read about the use of these tools in IT and AI project estimation in my article:
[Between experiment and schedule - planning AI projects with PERT and Monte Carlo](https://edwardweinert.com/miedzy-eksperymentem-a-harmonogramem-planowanie-projektow-ai-z-pert-i-monte-carlo/)

---

## Contents

- `estimations_pert_beta_MC.ipynb` - main notebook with code examples, formulas, and visualization.

---

## Getting Started

### Prerequisites

To run this notebook, make sure you have:

- Python 3.8 or newer
- Jupyter Lab (or Jupyter Notebook)

Install dependencies in your python environment with:

`pip install numpy pandas matplotlib scipy networkx tqdm jupyterlab`

or if you prefer conda (like me):

'conda install numpy pandas matplotlib scipy networkx tqdm jupyterlab'

## Running the Notebook
1. Clone the repository:

`git clone https://github.com/ediw/project_estimations.git
cd project_estimations`

2. Launch Jupyter Lab:

'jupyterlab'

3. Open and run:

Select 'estimations_pert_beta_MC.ipynb' and execute the cells step by step. 

## Features
1. Calculation of PERT estimates combining optimistic, most likely, and pessimistic durations.
2. Sampling from Beta distributions to model uncertainty in estimates.
3. Monte Carlo simulations generating probability distributions of outcomes.
4. Visualization of simulated distributions and confidence intervals.

## Example Use Cases
1. Estimating project timelines with uncertainty.
2. Quantifying risk in project budgeting.
3. Supporting decisions in project planning.

## License
This repository is released under the MIT License.
See the [LICENSE](/LICENSE) file for details.
