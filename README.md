# Comprehensive Analysis of Tumor Treatment in Mice

## Project Overview

This project delves into the statistical analysis and visualization of tumor treatment efficacy across different drug regimens in laboratory mice. Using a rich dataset, we conduct a selective cleaning process, execute statistical analysis, and visualize the results to identify trends and outliers in tumor volume changes, comparing them across various conditions.

## Technologies Used

- Python: For overall programming.
- Pandas: For data manipulation and cleaning.
- Matplotlib: For creating visualizations.
- SciPy: For statistical analysis, specifically linear regression.

## Objectives
- To evaluate the effectiveness of different drug regimens on tumor volume in mice.
- To understand the relationship between the mice's weight and tumor volume under different treatment plans.
- To assess the distribution of tumor volume data to identify outliers and overall trends.

## Methods and Results
### Data Cleaning
- Duplicates were removed, ensuring clean and reliable data for analysis.
- A new column was calculated to represent the maximum time point for each mouse, aiding in focused subsequent analyses.

### Statistical Analysis
- Computed summary statistics of tumor volumes, grouped by drug regimen to highlight potential differences in treatment effectiveness.
- Used the Pearson correlation coefficient to highlight a strong correlation between one of the drug regimens and the weight of the mice.

## Visualizations

**Bar Chart: Number of Observed Mouse Timepoints per Drug Regimen**
![Bar Chart](https://imgur.com/sMLtApO.png)

**Pie Chart: Distribution of Mouse Sex**

![Pie Chart](https://imgur.com/UadFzk9.png)

**Line Graph: Tumor Volume Over Time for a Single Mouse**
![Line Graph](https://imgur.com/Qaubzya.png)

**Scatter Plot: Mouse Weight Versus Average Tumor Volume**
![Scatter Plot](https://imgur.com/w7H4DwU.png)

**Linear Regression on Scatter Plot**

![Linear Regression](https://imgur.com/ZBDy5GM.png)

**Box Plot: Tumor Volume by Drug Regimen**
![Box Plot](https://imgur.com/LIRjJbO.png)

**Summary Table: Tumor Volume Statistics**
![Summary Table](https://imgur.com/iQPR8aM.png)

## Findings
- The analysis highlighted significant variations in tumor response to different drug regimens.
- One drug regimen `Capomulin`, in particular, showed a strong correlation between mouse weight and average tumor volume, with a Pearson correlation coefficient of 0.84. This indicates a strong positive relationship, suggesting that dosage adjustments might be necessary based on the mouse’s weight to optimize treatment efficacy.
- The presence of an outlier in one of the drug treatments suggests potential anomalies in response or errors in data collection.

## Conclusions

This project not only sheds light on the potential efficacy of different drug treatments but also underscores the importance of considering physiological traits such as weight in treatment plans. The visualizations provide clear, actionable insights that can guide further research and treatment adjustments.

## Installation
Before running the analysis, ensure you have Python installed on your system. You can then install the required libraries using `pip`. It's recommended to use a virtual environment.

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/SaadNasir92/CancerDrugEfficacy-in-Mice
    ```
2. Navigate to the root directory of the project:
    ```bash
    cd CancerDrugEfficacy-in-Mice
    ```
    then 
    ```bash
    cd notebooks
    ```
3. Install the required packages:
    ```bash
    pip install pandas matplotlib scipy
    ```
4. Once the dependencies are installed, open the Jupyter Notebook to view the project:
    ```bash
    jupyter notebook main.ipynb
    ```

**Note:** If you don't have Jupyter installed, you can install it via pip with `pip install notebook`

## Lessons Learned
- Reinforced the importance of thorough data cleaning for accurate analysis. Handling duplicates and deriving new columns can significantly impact the study's outcome.
- Gained a deeper understanding of statistical methods, especially in interpreting Pearson's correlation coefficient in practical scenarios.
- Improved skills in creating effective visualizations that communicate complex data in a clear and understandable manner.
- Learned to apply linear regression in a real-world context, interpreting the slope and intercept in the framework of the study's goals.

## Future Work
- Expand the dataset to include more variables for a multifaceted analysis.
- Implement more advanced statistical models to predict trends.
