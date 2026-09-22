# data-analytics-ml

This repository is used for completing exercises for the "Applied Analytics and AI" course, and all its contents are public.

## Top Kaggle Datasets for EDA & Visualizations

### [Palmer Archipelago Penguins](https://www.kaggle.com/datasets/parulpandey/palmer-archipelago-antarctica-penguin-data)

- **Why it's perfect:** Widely considered the modern, real-world replacement for the overused Iris dataset. It contains physical measurements of three penguin species across different islands.
- **Best visualization ideas:** Create a box plot of `flipper_length_mm` or `body_mass_g` grouped by species to instantly see distinct median differences and outliers. Use scatter plots with hue/sizing to explore the correlation between bill depth and length.

### [Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic)

- **Why it's perfect:** The ultimate baseline dataset for practice. It has demographic data mixed with survival metrics, allowing for excellent distribution analysis.
- **Best visualization ideas:** Map a box plot of passenger `Age` or `Fare` grouped by `Pclass` (passenger class) or `Survived`. It provides a fantastic lesson on data skewness and high-value outliers.

### [Avocado Prices](https://www.kaggle.com/datasets/neuromusic/avocado-prices)

- **Why it's perfect:** This clean dataset spans multiple years of retail data across various US markets. It features continuous variables and easy categorical segments.
- **Best visualization ideas:** Generate side-by-side box plots showing the distribution of `AveragePrice` across different `type` variables (organic vs. conventional) or broken down by year. Bar charts or line graphs work wonderfully here to view total volume over time.

### [80 Cereals Nutrition](https://www.kaggle.com/datasets/crawford/80-cereals)

- **Why it's perfect:** A highly intuitive, fun, and smaller dataset containing dietary facts (sugar, fiber, calories, vitamins) for 80 popular breakfast cereals.
- **Best visualization ideas:** Plot a box plot of `sugars` or `rating` grouped by manufacturer (`mfr`). It is great for noticing data spread, variance, and checking which manufacturer produces the healthiest options.

### [Red Wine Quality](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009)

- **Why it's perfect:** A strictly tabular dataset containing chemical properties of wines alongside an objective quality score ranging from 0 to 10.
- **Best visualization ideas:** Draw a box plot showing how alcohol percent or volatile acidity changes across the different wine quality tiers. This helps you immediately pinpoint which chemical traits correlate with premium scores.

## Code to Connect to Data

```python
import pandas as pd

df = pd.read_csv("/content/online food delivery dataset.csv", encoding='latin-1')
df
```

> Copy this code to Colab
