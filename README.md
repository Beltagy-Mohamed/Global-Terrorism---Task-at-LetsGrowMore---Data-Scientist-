# Global-Terrorism---Task-at-LetsGrowMore---Data-Scientist-
# Global Terrorism Data Analysis

This repository contains a Jupyter Notebook that performs Exploratory Data Analysis (EDA) on the **Global Terrorism Database**. The dataset used contains records of terrorist incidents globally from 1970 onwards, with detailed information on each event.

## Dataset

The dataset used in this analysis is the **Global Terrorism Database** (`globalterrorismdb_0718dist.csv`), which includes:
- **Event Details**: Event ID, Date (year, month, day), Country, Region, etc.
- **Incident Information**: Target types, attack types, weapon types, and group names.
- **Casualties**: Number of kills and wounds caused by the incidents.

### Example of Dataset Columns:
- `eventid`: Unique identifier for each event.
- `iyear`, `imonth`, `iday`: Date details of the event.
- `country_txt`: Country where the event took place.
- `attacktype1_txt`: Type of attack.
- `nkill`: Number of people killed in the attack.
- `nwound`: Number of people wounded in the attack.
- ...and many more fields related to terrorist incidents.

## Notebook Overview

The notebook follows the following workflow:
1. **Import Libraries**: The required Python libraries for data analysis and visualization, including:
    - Pandas
    - NumPy
    - Scikit-learn
    - Matplotlib
    - Seaborn
    - Plotly
    - Warnings
    - Datetime
    
2. **Loading the Dataset**: 
    ```python
    df = pd.read_csv('globalterrorismdb_0718dist.csv', encoding='latin-1')
    ```

3. **Exploratory Data Analysis (EDA)**:
    - Initial data exploration using `.head()` to view the first few rows.
    - Statistical summaries and visualizations to uncover insights from the dataset.
    - Various plots such as bar charts, pie charts, and time series analysis to understand trends in terrorism activities globally.

4. **Data Visualization**:
    - Visualizations are created using libraries like Matplotlib, Seaborn, and Plotly for interactive plots.

5. **Key Insights**:
    - Analysis of trends in terrorist incidents over time.
    - Identification of countries most affected by terrorism.
    - Patterns of attack types, targets, and casualties.

## How to Run

To run this notebook, you will need to install the required Python packages:
```bash
pip install -r requirements.txt

