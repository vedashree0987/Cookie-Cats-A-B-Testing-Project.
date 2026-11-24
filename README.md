# Cookie Cats A/B Testing Project

## Project Overview

This project is an exploratory A/B testing analysis of the mobile game
**Cookie Cats**, with a focus on understanding player retention.

The notebook is titled `cookie_cats_ab_test.ipynb`. Its stated goal is
to analyse player retention using the Cookie Cats dataset. The current
notebook contains the initial Python imports and a dataset-loading step;
the statistical analysis and findings have not yet been added.

## Objective

The intended objective is to investigate whether the game experience
associated with the A/B test groups has an effect on player retention.

## Dataset

The notebook expects a CSV file named:

``` text
cookie_cats.csv
```

Place the dataset in the same directory as the notebook, or update the
file path in the data-loading cell.

The dataset is not included with the uploaded notebook. The notebook
currently attempts to load it with:

``` python
df = pd.read_csv("cookie_cats.csv")
```

## Tools and Libraries

The notebook imports the following Python libraries:

-   **Pandas** -- data loading and manipulation
-   **NumPy** -- numerical operations
-   **Matplotlib** -- data visualisation
-   **Seaborn** -- statistical visualisation

## Project Structure

``` text
cookie-cats-ab-testing/
├── cookie_cats_ab_test.ipynb
├── cookie_cats.csv          # Add the dataset here
└── README.md
```

## Getting Started

### 1. Clone or download the project

Download the project files to your computer.

### 2. Install the dependencies

``` bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Add the dataset

Place `cookie_cats.csv` in the project folder, alongside the notebook.

### 4. Launch Jupyter Notebook

``` bash
jupyter notebook
```

Open `cookie_cats_ab_test.ipynb` and run the cells.

## Current Status

The uploaded notebook currently includes:

-   Project title and introductory output
-   Imports for Pandas, NumPy, Matplotlib and Seaborn
-   A CSV-loading cell for `cookie_cats.csv`

The data-loading cell currently reports a `FileNotFoundError` because
the CSV file was not available at the expected path when the notebook
was run.

## Planned Analysis

The notebook's stated focus is player retention. The following are
possible next steps for completing the analysis; they are not results
already present in the notebook:

1.  Load and inspect the dataset.
2.  Check column names, data types, missing values and duplicate
    records.
3.  Explore the A/B test groups and their sample sizes.
4.  Calculate and visualise player retention for each group.
5.  Compare retention between groups using an appropriate statistical
    test.
6.  Interpret the results and explain their implications for the game.

## Results and Conclusion

No statistical results or final conclusion are included in the uploaded
notebook yet. This section should be completed after the dataset has
been loaded and the analysis has been performed.

## Author

Add your name here.
