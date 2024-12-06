# Assignments for Applied Statistics (Winter 2024)
**by Nur Bujang (G00426044@atu.ie)**

## Overview
This repository contains the Applied Statistics module's (Instructor: Dr Ian McLoughlin) tasks and project. Statistics provide the necessary framework and tools to make sense of data and make informed decisions based on it. This assessment contains examples of data visualisation tools such as histograms and boxplots to give quick insights into data distributions, relationships, and anomalies. It also contains statistical tests such as the Student t-test and ANOVA for reliable hypothesis testing, which will be used to guide decision-making processes.

## Features
### tasks.ipynb
This Jupyter notebook contains four tasks: Permutations and Combinations, NumPy's Normal Distribution, t-test Calculation, and ANOVA. Each task contains sections on the Plan, Methods and Implementation, Conclusion, and References.

### project.ipynb
This Jupyter notebook contains the body of work for the project "Analysis of Plantgrowth Dataset". This README.md contains the full list of references used in this project. The full list of contents are listed below: 

* PROJECT TITLE: Analysis of Plantgrowth Dataset

* Project Description

* Abstract

* 1.0 Plan

* 2.0 Methods and Implementation

    * 2.1 Download and save dataset

    * 2.2 Describe the dataset

    * 2.3 Describe what a t-test is, how it works, and what the assumptions are

        * 2.3.1 T-test

        * 2.3.2 How does a t-test work?

        * 2.3.3 Assumptions

            * 2.3.3.1 Continuous Data

                * 2.3.3.1.1 Histogram

                * 2.3.3.1.2 Box Plot

            * 2.3.3.2 Sample size

            * 2.3.3.3 Homogeneity of Variance with Levene's Test

            * 2.3.3.4 Test for Normality with Shapiro-Wilk Test

                * 2.3.3.4.1 Q-Q Plot

                * 2.3.3.4.2 Shapiro-Wilk Test

    * 2.4 Perform a t-test to determine whether there is a significant difference between the two treatment groups trt1 and trt2

        * 2.4.1 Independent Two-Sample T-test

    * 2.5 Perform ANOVA to determine whether there is a significant difference between the three treatment groups ctrl, trt1, and trt2

        * 2.5.1 One-way ANOVA

    * 2.6 Explain why it is more appropriate to apply ANOVA rather than several t-tests when analyzing more than two groups

        * 2.6.1 Tukey's HSD

* 3.0 Conclusion

* 4.0 References



## Technologies Used

Python 3.11.5

## Dependencies

* Python 3.8 or later

* Libraries:

    * `numpy` - for numerical computations
    * `pandas` - for data manipulation
    * `matplotlib` - for data visualization
    * `seaborn` - for data visualization
    * `scipy` - for statistical tests and distributions
    * `statsmodels` - for additional statistical models and tests

## Run The Jupyter Notebook in two ways:

### 1. Run Locally Using Visual Studio Code and Anaconda

#### Prerequisites:
- Install [Python](https://www.python.org/)
- Install [Anaconda](https://www.anaconda.com/products/distribution)
- Install [Visual Studio Code](https://code.visualstudio.com/)

#### Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/nurbujang/asappstatw24.git
   cd asappstatw24
   ```
2. Open the repository folder in Visual Studio Code:
  - install the Python extension if prompted.

  3. Create a new Anaconda environment (optional but recommended):
   ```bash
   conda create -n stats_env python=3.9
   conda activate stats_env
   ```
4. Install the required libraries:
   ```bash
    conda create --name <envname> --file requirements.txt
    pip install pandas numpy seaborn  matplotlib scipy statsmodels
   ```
5. Open the Jupyter Notebook:
   - Install the Jupyter extension in Visual Studio Code if not already installed.
   - Open `tasks.ipynb` or `project.ipynb` in Visual Studio Code and select the Python kernel associated with your environment.

### 2. Run Using GitHub Codespaces

#### Steps:
1. Click the **Code** button on this repository's main page.
2. Select **Open with Codespaces**.
3. If you don't have a Codespace created:
   - Follow the prompts to set up a new Codespace for this repository.
4. Once the Codespace is ready:
   - Open `tasks.ipynb` or `project.ipynb` directly in the integrated Jupyter Notebook environment.

## Support Information

G00426044@atu.ie

## License Information

GNU GENERAL PUBLIC LICENSE, Version 3, 29 June 2007