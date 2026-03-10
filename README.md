# Product Feature A/B Testing Simulation

This project simulates an A/B test to evaluate whether a new product feature improves user engagement.

The analysis is implemented in Python using Jupyter Notebook and demonstrates common experimentation techniques used in product analytics.

---

## Experiment Design

Users are randomly assigned into two groups:

- **Control group** – users with the existing product experience
- **Treatment group** – users exposed to a new feature

The goal is to estimate whether the new feature leads to a statistically significant improvement in engagement.

---

## Metrics Analysed

The experiment evaluates three key metrics:

- **Session Time** – time spent in the product
- **Number of Clicks** – interaction intensity
- **Next-Day Retention** – whether the user returns the following day

---

## Methods

The analysis uses common product experimentation techniques:

- Difference-in-means estimation
- Hypothesis testing (t-test)
- Ordinary Least Squares regression
- Visualisation of engagement and retention metrics

---

## Key Results

The simulated experiment suggests that the new feature improves user behaviour:

- Session time increased by **1.16 minutes**
- Average clicks increased from **3.00 to 3.94**
- Next-day retention increased by **8.73 percentage points**
- All effects were statistically significant

---

## Recommendation

Based on the simulated evidence, the product team could consider rolling out the feature to a larger user base while continuing to monitor longer-term retention and engagement.

---

## Tools

- Python
- NumPy
- Pandas
- SciPy
- Statsmodels
- Matplotlib
- Jupyter Notebook
