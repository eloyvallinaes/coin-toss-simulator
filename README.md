# Coin Toss Simulator

A single-file browser app for simulating two coin-toss experiments and comparing their observed heads rates with a two-proportion Z-test.
Visit at: **https://eloyvallinaes.github.io/coin-toss-simulator/**

## What It Does

- Lets you set the heads probability for both Coin A and Coin B with independent sliders
- Runs both experiments with configurable toss counts
- Shows heads/tails counts, percentages, and a heads-ratio bar for each coin
- Computes a two-sided two-proportion Z-test on the observed difference in heads rates
- Visualizes the null distribution and marks the observed effect and $\alpha = 0.05$ critical cutoffs

## How It Works

For each run:

1. Coin A is simulated using its slider-selected heads probability.
2. Coin B is simulated using its slider-selected heads probability.
3. The app calculates the observed gap in sample proportions:

$$
\hat{p}_{A} - \hat{p}_{B}
$$

4. It then applies a pooled two-proportion Z-test under the null hypothesis that both coins have the same true heads rate.

## Run Locally

No build step or dependencies are required.

1. Download or clone the repository.
2. Open `index.html` in a modern browser.

## Use Cases

- Teaching basic probability and sampling variability
- Demonstrating how different coin biases and sample sizes change observed outcomes
- Explaining hypothesis testing with a simple visual example
- Quick classroom or interview-style statistics demos

## License

Add your preferred license here if you plan to publish the project.
