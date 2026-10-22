# From Energy to Air: A Predictive Model of State Air Quality

This repository contains the SIADS 696: Milestone II project from Fall 2026 for the following team members:
* Michael Leone
* Hayley Tice
* Sravan Gannavarapu

## Repository Structure
* **Datasets/**: Contains the raw and cleaned AQS datasets, SEDS datasets, and a downloaded US States JSON file for the choropleths.
* **Notebooks/**: Jupyter Notebooks containing cleaning, EDA, and supervised/unsupervised learning.

## Getting Started
To replicate this environment and run the notebooks locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/micleone/SIADS_696_F26_Team10.git
   cd SIADS_696_F26_Team10
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv env
   # On macOS/Linux: source env/bin/activate
   # On Windows: env\Scripts\activate
   ```

3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Register the environment with Jupyter and launch:
   ```bash
   python -m ipykernel install --user --name=env --display-name="Python (env)"
   jupyter notebook
   ```
