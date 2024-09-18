# Central-Limit-Theorem-Demonstration
This project demonstrates the Central Limit Theorem (CLT) using Python. The CLT states that the distribution of the sample means approaches a normal distribution, regardless of the shape of the original distribution, as the sample size becomes large. In this project, we illustrate this theorem using three different types of random variables: normal, binomial, and Poisson distributions.
## Project Overview
The project involves the following steps:

1. Generating random samples from three different distributions:
- Normal distribution
- Binomial distribution
- Poisson distribution

2. Drawing multiple samples from these distributions and calculating the sample means.
  
3. Visualizing the distributions of the original data and the sample means.
Fitting a normal distribution to the sample means to show how they approximate normality.

## Requirements
To run this project, you'll need the following Python libraries:

- ```scipy```
- ```numpy```
- ```matplotlib```
- ```seaborn```

The required packages can be installed using:

```
pip install scipy numpy matplotlib seaborn
```
## Code Explanation

### 1. Generating Random Samples
We generate random samples from the following distributions:

- Normal Distribution: Mean = 100, Standard Deviation = 10
- Binomial Distribution: Number of trials 𝑛 = 20, Probability of success 𝑝 = 0.10
- Poisson Distribution: Rate (𝜆) = 0.5

### 2. Sampling and Calculating Sample Means
- We take 1,000 samples, each containing 50 observations, from the generated distributions.
- We calculate the mean of each sample and store these means.

### 3. Visualizing the Results
- We plot histograms of the original distributions and the sample means using ```seaborn```.
- We fit a normal distribution to the sample means to show how they approximate a normal distribution as predicted by the CLT.
  
### 4. Central Limit Theorem Illustration
The CLT is illustrated by showing that the distribution of sample means from:

A normal distribution approaches normality.
A binomial distribution approximates normality as the number of samples increases.
A Poisson distribution also approximates normality, regardless of the original distribution's shape.
