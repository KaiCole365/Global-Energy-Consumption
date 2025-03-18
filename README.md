# Global Energy Consumption Analysis

## Overview

This project analyzes global energy consumption trends using data from the World Bank and other sources. The primary goal is to explore energy usage patterns, 
identify key factors influencing consumption, and provide insights relevant to sustainable energy policy and resource management.

## Data Sources

*   **World Bank Data:** Provides comprehensive data on energy consumption, GDP, population, and other socioeconomic indicators.
*   **Other Relevant Datasets:**  (Specify any other datasets you used, e.g., BP Statistical Review of World Energy)

## Technologies Used

*   **Python:** Primary programming language for data analysis and visualization.
*   **Pandas:**  Data manipulation and analysis.
*   **NumPy:** Numerical computing.
*   **Matplotlib:** Data visualization.
*   **Seaborn:** Enhanced data visualization.
*   **Scikit-learn:** (If applicable) Machine learning for predictive modeling (e.g., forecasting energy consumption).

## Project Structure

The project is contained within the [Evaluating Global Energy Consumption.ipynb](Evaluating%20Global%20Energy%20Consumption.ipynb) Jupyter Notebook.  
The notebook is structured as follows:

1.  **Data Loading and Cleaning:**
    *   Loading data from CSV files.
    *   Handling missing values and outliers.
    *   Data type conversions.

2.  **Exploratory Data Analysis (EDA):**
    *   Visualizing energy consumption trends over time.
    *   Analyzing the relationship between energy consumption and GDP.
    *   Exploring energy consumption by region and country.
    *   Identifying key drivers of energy consumption.

3.  **Feature Engineering:**
    *   Creating new features from existing data (e.g., per capita energy consumption).

4.  **Data Visualization:**
    *   Creating visualizations to communicate insights effectively (e.g., line plots, scatter plots, bar charts, heatmaps).

5.  **Modeling:** (If applicable)
    *   Building predictive models for energy consumption (e.g., using linear regression, time series models).
    *   Evaluating model performance.

6.  **Conclusions and Recommendations:**
    *   Summarizing key findings.
    *   Providing recommendations for sustainable energy policy and resource management.

## Key Findings

*   Global energy consumption has been steadily increasing over the past decades in developing countries, with significant variations across regions.
*   There's a strong correlation between GDP and energy consumption, indicating that economic growth is a major driver.
*   Renewable energy sources are playing an increasingly important role in meeting global energy demand, but fossil fuels still dominate.
*   Certain regions, especially in some developing and third world countries, show a shift in reducing their carbon footprint by adopting greener initiatives.
*   More countries need to invest more in affordable renewable resources (i.e. hydroelectric, wind power) and less on fossil fuels.

## How to Run the Code

1.  **Clone the repository:**
    ```
    git clone https://github.com/KaiCole365/Sustainability-Projects.git
    cd Sustainability-Projects
    ```

2.  **Install the required libraries:**
    ```
    pip install pandas numpy matplotlib seaborn scikit-learn  # Add other libraries if needed
    ```

3.  **Run the Jupyter Notebook:**
    ```
    jupyter notebook Evaluating\ Global\ Energy\ Consumption.ipynb
    ```

## Potential Improvements

*   Incorporate more detailed data on specific energy sources (e.g., solar, wind, nuclear).
*   Develop more sophisticated predictive models (i.e. SARIMAX, Prophet + LSTM, ConvLSTM)
*   Conduct a deeper analysis of the social and environmental impacts of energy consumption.
*   Integrate economic data to measure growth.

## Author

*   Kai Cole
