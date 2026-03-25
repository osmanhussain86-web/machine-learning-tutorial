# From Bagging to Boosting: Understanding Gradient Boosting with XGBoost

A machine learning tutorial demonstrating how Gradient Boosting works by building on Decision Trees and Random Forests. Uses the UCI Heart Failure Clinical Records Dataset to predict patient survival.

**Author:** Osman Hussain Mohammed
**Course:** Machine Learning, University of Hertfordshire (2025-2026)

## What You Will Learn

1. How Decision Trees, Random Forests (bagging), and Gradient Boosting (boosting) relate to each other
2. The step-by-step mechanics of the Gradient Boosting algorithm
3. How to use XGBoost for classification with hyperparameter tuning
4. How to compare models and interpret feature importance

## Repository Structure

```
gradient-boosting-tutorial/
├── notebook.ipynb          # Main tutorial notebook with code and explanations
├── data/
│   └── heart_failure_clinical_records.csv   # UCI Heart Failure dataset
├── figures/                # Generated plots (created by running the notebook)
├── requirements.txt        # Python dependencies
├── LICENSE                 # MIT License
└── README.md               # This file
```

## Getting Started

### Prerequisites

- Python 3.9 or higher
- pip package manager

### Installation

1. Clone this repository:
   ```bash
   git clone <your-github-url>
   cd gradient-boosting-tutorial
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook notebook.ipynb
   ```

4. Run all cells from top to bottom. All figures will be generated and saved to the `figures/` directory.

## Dataset

The [Heart Failure Clinical Records Dataset](https://archive.ics.uci.edu/dataset/519/heart+failure+clinical+records) contains 299 patient records with 12 clinical features and a binary target (DEATH_EVENT). It was published by Chicco and Jurman (2020).

## Accessibility

- All plots use a colour-blind friendly palette (seaborn "colorblind")
- Alt-text descriptions are provided for all figures
- Clear axis labels and large font sizes are used throughout

## References

1. Chen, T. and Guestrin, C. (2016) 'XGBoost: A Scalable Tree Boosting System', *KDD*, pp. 785-794.
2. Friedman, J.H. (2001) 'Greedy Function Approximation: A Gradient Boosting Machine', *The Annals of Statistics*, 29(5), pp. 1189-1232.
3. Chicco, D. and Jurman, G. (2020) 'Machine learning can predict survival of patients with heart failure', *BMC Medical Informatics and Decision Making*, 20(16).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
