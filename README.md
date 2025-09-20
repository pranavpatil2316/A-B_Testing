# A/B Testing for Website Headlines

This project performs an **A/B test** to compare two website headlines (A vs. B). It calculates conversion rates, runs statistical tests, and visualizes results to help decide which headline performs better.

## Features

* Simulates A/B test data (impressions & conversions for A and B)
* Computes conversion rates and 95% confidence intervals
* Performs a **two-proportion z-test** to check statistical significance
* Visualizes conversion rates with error bars (Plotly)
* Plots cumulative conversions over time
* Automatically recommends the better-performing headline based on p-value

## Technologies Used

* **Python**
* **NumPy**, **Pandas**, **SciPy**
* **Plotly** for visualization

## How to Run

1. Download the notebook: `AB_Testing_Experiment_With_Recommendation.ipynb`.
2. Open it in **Google Colab** or Jupyter Notebook.
3. Run all cells.
4. View the summary table, visualizations, and automatic recommendation.

## Output

* **Summary Table:** Impressions, conversions, conversion rates, z-stat, p-value, and confidence intervals.
* **Bar Chart:** Conversion rates with 95% CI.
* **Line Chart:** Cumulative conversions over time.
* **Recommendation:** Text output suggesting which headline performs better.

## Ethical Considerations

* Ensure user privacy during real tests.
* Avoid harming user experience.
* Run tests long enough to avoid false positives.
---

Would you like me to **generate this README as a downloadable `.md` file** right now?
