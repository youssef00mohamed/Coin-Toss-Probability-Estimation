# Coin Toss Probability Estimation using Maximum Likelihood Estimation (MLE)

This Python project applies maximum likelihood estimation (MLE) to estimate the probability of a coin landing heads based on observed outcomes.

## Overview

- **Objective:** Estimate the parameter \( p \) of a binomial distribution that best fits observed coin toss outcomes (heads or tails).
- **Methodology:** 
  - Generates random coin toss outcomes based on a specified probability \( p \).
  - Computes the likelihood of different probabilities \( p \) using the binomial distribution.
  - Determines the maximum likelihood estimate by identifying the probability \( p \) that maximizes the likelihood function.
- **Visualization:** 
  - Plots the likelihood scores for various probabilities \( p \), aiding in understanding the estimation process.
 
## Requirements

- Programming Language: `Python 3.x`
- Libraries: `numpy`, `matplotlib`
  
## Usage

1.**Clone the repository:**

   ```bash
   git clone https://github.com/your_username/coin-toss-probability-mle.git
   cd coin-toss-probability-mle
   ```

2.**Run the script:**

   ```bash
   python coin toss probability estimation.ipynb
   ```

3.**View results:**
   
- The script will display the likelihood scores and the estimated probability 𝑝 that maximizes the likelihood.
- Visualizations will show how different probabilities affect the likelihood function.

## Contributions
Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.

## License
This project is licensed under the [MIT License](LICENSE).
