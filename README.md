# Bayesian Optimization

## Overview
Bayesian Optimization is a powerful technique for optimizing black-box functions that are expensive to evaluate. This repository is dedicated to comparing different acquisition functions used in Bayesian Optimization. Acquisition functions guide the optimization process by determining the next most informative data point to evaluate.

## Objectives
This project aims to:

- Explore and analyze various acquisition functions employed in Bayesian Optimization.
- Compare their performance across different benchmark problems.
- Provide insights into selecting appropriate acquisition functions for diverse applications.

## Features
- Implementation of commonly used acquisition functions such as:
  - **Expected Improvement (EI)**
  - **Upper Confidence Bound (UCB)**
  - **Probability of Improvement (PI)**
- Benchmark suite for testing optimization performance.
- Visualizations to contrast and evaluate the behavior of acquisition functions.

## Use Case
This repository is beneficial for practitioners, researchers, and students who want to:
- Understand how Bayesian Optimization works.
- Learn how acquisition functions impact optimization outcomes.
- Apply Bayesian Optimization to real-world black-box optimization tasks.

## Prerequisites
To use this codebase, ensure you have the following installed:
- Python 3.8 or higher
- Dependencies specified in `requirements.txt`.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/CarlSvejstrup/bayesian-optimization.git
    ```
2. Navigate to the project directory:
    ```bash
    cd bayesian-optimization
    ```
3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
Run the main script to start experimenting with different acquisition functions:
```bash
python main.py
```

Adjust parameters and settings in the configuration file (`config.yaml`) to customize your experiments.

## Contributing
Contributions are welcome! If you have ideas for improving this project or adding more acquisition functions, please follow these steps:
1. Fork this repository.
2. Create a new branch.
3. Make your changes and submit a pull request.
4. Ensure your code follows the existing style and includes necessary tests.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments
- Inspired by the foundational work in Bayesian Optimization research.
- Thank you to open-source contributors for making tools and libraries accessible to the community!

## References
- [A Tutorial on Bayesian Optimization](http://arxiv.org/abs/1807.02811)
- [Gaussian Processes for Machine Learning](http://www.gaussianprocess.org/)
