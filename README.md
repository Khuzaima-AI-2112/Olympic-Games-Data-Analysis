# Olympic Games Data Analysis: A Case Study

### _Analyzing 120 Years of Olympic History with Python_

## Project Overview

This project serves as a case study in data analysis, using Python and its core data science libraries to explore a comprehensive dataset of the Olympic Games. Hired as a Junior Data Analyst, the mission was to clean, analyze, and visualize 120 years of Olympic data to uncover trends in athlete performance, country-wise medal statistics, gender participation, and the evolution of sports within the Games.

## Key Questions and Insights

The analysis sought to answer several key questions, yielding the following insights:

1.  **How has athlete participation changed over time?**
    *   There has been a consistent and significant growth in the number of unique athletes participating in both Summer and Winter Olympics, with a dramatic increase in the post-WWII era.

2.  **Which countries are the top performers?**
    *   The **United States** holds the highest all-time medal count, followed by the **Soviet Union**, **Germany**, and **Great Britain**.

3.  **What are the most dominant sports?**
    *   **Athletics** and **Swimming** are the largest sports, having the most events and awarding the most medals throughout Olympic history.

4.  **How has gender participation evolved?**
    *   The Olympics began as a male-exclusive event. The analysis visualizes a powerful trend of growing female participation over the decades, with a sharp acceleration in recent years towards achieving gender parity.

5.  **Who is the most decorated Olympian?**
    *   The analysis identified American swimmer **Michael Phelps** as the athlete with the most medals (28) in the dataset.

6.  **Which sports are emerging or declining?**
    *   **Emerging:** Sports like **Snowboarding**, **Triathlon**, and **Beach Volleyball** were identified as relatively new additions that have grown in the number of events.
    *   **Discontinued:** The analysis highlights historical sports like **Tug-Of-War**, **Polo**, and **Jeu De Paume** that are no longer part of the Olympic program.

## Analysis Workflow

The project followed a structured data analysis pipeline:

1.  **Data Loading & Inspection:** The `athlete_events.csv` dataset was loaded into a pandas DataFrame. Initial checks were performed to understand its structure, columns, and data types.
2.  **Data Cleaning:**
    *   Handled missing values in `Age`, `Height`, and `Weight` by filling them with the column median.
    *   Replaced `NaN` in the `Medal` column with 'No Medal' for clarity.
    *   Removed duplicate rows to ensure data integrity.
    *   Corrected data types, ensuring `Age` was an integer.
3.  **Exploratory Data Analysis (EDA):** Used pandas for data aggregation and Matplotlib for visualization to answer the key questions above.
4.  **Saving the Result:** The final, cleaned dataset was saved to `cleaned_athlete_events.csv` for future use.

## Technologies Used

*   **Python 3.x**
*   **Pandas:** For data manipulation and analysis.
*   **NumPy:** For numerical operations and statistical calculations.
*   **Matplotlib:** For data visualization.
*   **Jupyter Notebook:** As the environment for interactive analysis.


## How to Run This Project

1.  **Clone the repository:**
    ```bash
    git clone [Your-Repository-URL]
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd DATA_ANALYSIS_WITH_PYTHON
    ```
3.  **Install the required libraries:**
    ```bash
    pip install pandas numpy matplotlib jupyterlab
    ```
4.  **Run the analysis:**
    Open the `01_exploring_dataset.ipynb` file in Jupyter Notebook or JupyterLab to view and run the analysis.
    ```bash
    jupyter lab
    ```
